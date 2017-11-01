---
title: "Vyrovnání plateb k nezaplaceným prodejním dokumentům"
description: "Můžete vyrovnat sumy placené zákazníkem k souvisejícím prodejním dokumentům a účtovat platby k aktualizaci zákazníka, hlavní knihy a položek banky."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment process, cash receipts, customer payment
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c39a45d513ef6d5f6d4da7a052888a051d9f06d6
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-reconcile-customer-payments-manually-from-a-list-of-unpaid-sales-documents"></a>Návody Manuální odsouhlasení plateb zákazníka z seznamu nezaplacených prodejních dokumentů
Když vaši zákazníci provedli platby na váš bankovní účet, musíte vyrovnat každou zaplacenou částku do souvisejícího prodejního dokladu a následně zaúčtovat platbu za účelem aktualizace zákazníka, hlavní knihy a položek knihy bank.

> [!NOTE]  
>   Stejné úkoly včetně plateb dodavatelů, můžete provést v okně **Deníky odsouhlasení plateb** pomocí funkcí pro import bankovního výpisu, automatické vyrovnání a odsouhlasení bankovního účtu. Další informace naleznete v tématu [Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).

Okno **Registrace plateb** je navrženo tak, aby vám pomohlo při úkonech při vyrovnávacích vnitřních účtech pomocí skutečných peněžních údajů, abyste se ujistili, že platby jsou vybírány od zákazníků efektivně. Tento nástroj pro zpracování plateb vám umožňuje rychle ověřit a zaúčtovat jednotlivé nebo jednorázové platby, zpracovat slevové platby a najít konkrétní nezaplacené doklady, pro které byla úhrada vytvořena.

Platby pro různé zákazníky, které mají různé datum platby, musí být zaúčtovány jako jednotlivé platby. Platby pro stejného zákazníka, které mají stejné datum platby, můžete zaúčtovat jako jednorázovou platbu. To je užitečné například když zákazník provedl jednu platbu, která pokrývá více prodejních faktur.

## <a name="to-set-up-the-payment-registration-journal"></a>Nastavení deníku pro registraci plateb
Protože můžete zaúčtovat různé typy plateb do různých vyrovnávacích účtů, musíte vybrat vyrovnávací účet v okně **Nastavení registrace plateb** předtím, než začnete zpracovávat platby zákazníků. Pokud vždy zaúčtujete na stejný vyrovnávací účet, můžete tento účet nastavit jako výchozí a vyhýbat se tomuto kroku pokaždé, když otevřete okno **Registrace plateb**.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **nastavení registrace plateb** a vyberte související odkaz.

    Alternativně v okně **Registrace plateb** vyberte akci **Nastavení**.    
2. Vyplňte pole v okně **Nastavení registrace plateb**. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro související informace.  

## <a name="to-reconcile-payments-individually"></a>Odsouhlasení plateb jednotlivě
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Registrace plateb** a vyberte související odkaz.  
2. Zaškrtněte políčko **Platba provedena** v řádku, který představuje zaúčtovaný doklad, pro který byla platba provedena.

    Pokud je zaškrtnuto políčko **Automatické vyplnění data přijetí** v okně **Nastavení registrace plateb**, pak je datum práce zadáno do pole **Datum přijetí**.  
3. Do pole **Datum přijetí** zadejte datum, kdy byla platba provedena. Toto datum se může lišit od data práce.  
4. V poli **Přijatá částka** zadejte částku, která byla zaplacena.

    Pro plné platby je tato hodnota stejná jako částka v poli **Zbývající částka** na řádku. Pro částečné platby je tato hodnota nižší než částka v poli **Zbývající částka** na řádku.    
5. Opakujte kroky 2 až 4 pro další řádky, které představují zaúčtované dokumenty, pro které jsou platby prováděny.  
6. Zvolte akci **Účtovat platby**.  

Platební informace jsou zaúčtovány pro doklady představovanými řádky, kde je zaškrtnuto políčko **Platba provedena**.  

Položky plateb jsou zaúčtovány do hlavní knihy, bank a účtů zákazníka. Každá platba je vyrovnána na příslušný zaúčtovaný prodejní doklad.  

## <a name="to-reconcile-lump-payments"></a>Odsouhlasení jednorázových plateb
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Registrace plateb** a vyberte související odkaz.
2. Zaškrtněte políčko **Platba provedena** na řádcích, které představují zaúčtované doklady pro stejného zákazníka, pro kterého byla provedena jednorázová platba.  

    > [!NOTE]  
>   Zákazník v poli **Jméno** musí mít to samé na všech řádcích, které budou zaúčtovány jako jednorázová platba.  

    Pokud je zaškrtnuto políčko **Automatické vyplnění data přijetí** v okně **Nastavení registrací plateb**, pak datum práce je vyplněno v poli **Datum přijetí**.  
3. Do pole **Datum přijetí** zadejte datum, kdy byla platba provedena. Toto datum se může lišit od data práce.  

    > [!NOTE]  
>   Toto datum musí být stejné na všech řádcích, které budou zaúčtovány jako jednorázová platba.  
4. Do pole **Přijatá částka** zadejte částky na více řádcích, které se shodují s částkou jednorázové platby.  

    > [!TIP]  
>   Pokuste se zaúčtovat co nejvíce plných plateb s jednorázovou částkou. Zadejte částky, které jsou stejné jako částka v poli **Zbývající částka**, na co nejvíce řádků je to možné.  
5. Opakujte kroky 2 až 4 pro další řádky, které představují zaúčtované doklady pro stejného zákazníka, pro kterého byla provedena jednorázová platba.  
6. Zvolte akci **Účtovat jako jednorázovou platbu**. Zadané informace o platbě jsou zaúčtovány pro dokumenty představované řádky, kde je zaškrtnuto políčko **Platba provedena**.  

Položky platby jsou účtovány v hlavní knize, bankách a účtů zákazníků. Každá platba je vyrovnána na příslušný zaúčtovaný prodejní doklad.  

Pokud platba v bance není zobrazena v řádku **Registrace plateb**, může to být proto, že související dokument nebyl dosud zaúčtován. V takovém případě můžete pomocí funkce vyhledávání, rychle vyhledat doklad a zaúčtovat jej, aby zpracoval platbu. Pro více informací jděte na: „Vyhledání konkrétního prodejního dokladu, který není plně fakturován“  

Pokud není platba v bance reprezentována žádným dokladem v [!INCLUDE[d365fin](includes/d365fin_md.md)], potom můžete otevřít předem vyplněný finanční deník z okna **Registrace plateb** a zaúčtovat platbu přímo na vyrovnávací účet bez použití platby k dokladu. Případně možná budete chtít zaznamenat platbu v deníku, dokud nebude původní platba vyřešena. Další informace naleznete v tématu „Zaznamenání nebo zaúčtování platby bez souvisejícího dokumentu.“  

## <a name="to-process-customer-payments-with-discounts-manually"></a>Ruční zpracování plateb zákazníků se slevami
Pokud máte odsouhlasenu platební slevu s vaším zákazníkem, může být částka platby nižší než částky faktury, pokud k platbě dojde před dohodnutým datem slevy.  

Tento postup vysvětluje čtyři různé postupy pro zaúčtování slev plateb v okně **Registrace plateb**.  

* Částka platby se rovná zbývající slevové částce a datum platby je před datem slevy. Platbu zaúčtujete tak, jak je.  
* Částka platby se rovná zbývající slevové částce, ale datum platby je po datu slevy. Platbu zaúčtujete jako částečnou. Dokument zůstává otevřený pro vybírání/zaplacení zbývající částky. Případně můžete nastavit datum slevy později, abyste mohli povolit platbu v plné výši.  
* Výše platby je nižší než zbývající slevová částka. Platbu zaúčtujete jako částečnou. Dokument zůstává otevřený pro vybírání/zaplacení zbývající částky.  
* Výše platby je vyšší než zbývající slevová částka. Platby zaúčtujete tak, jak jsou. Pouze zbývající částka je zaúčtována. Dodatečná částka je připsána zákazníkovi.  

### <a name="to-process-a-payment-amount-that-is-equal-to-the-discounted-amount-and-where-the-payment-date-is-before-the-discount-date"></a>Zpracování části platby, která se rovná slevové částce a kde je datum platby před datem slevy
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Registrace plateb** a vyberte související odkaz.  
2. Zadejte částku platby do pole **Přijatá částka**. Částka se rovná částce v** poli zbývající částka po slevě**

    Zaškrtávací políčko **Platba provedena** se automaticky vybere a pole **Datum přijetí** je vyplněno datem práce.    
3. Do pole **Datum přijetí** zadejte datum platby. Datum je před datem v** Poli datum slevy**
4. Ověřte, zda pole **Zbývající částka** obsahuje nulu (0).  
5. Zvolte akci **Účtovat platby**, chcete-li zaúčtovat celou platbu do hlavní knihy, banky a účtů zákazníka.

### <a name="to-process-a-payment-amount-that-is-equal-to-the-discounted-amount-but-where-the-payment-date-is-after-the-discount-date"></a>Zpracování části platby, která se rovná slevové částce, ale datum platby je po datu slevy
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Registrace plateb** a vyberte související odkaz.  
2. Zadejte částku platby do pole **Přijatá částka**. Částka se rovná částce v** poli zbývající částka po slevě**

    Zaškrtávací políčko **Platba provedena** se automaticky vybere a pole **Datum přijetí** je vyplněno datem práce.
3. Do pole **Datum přijetí** zadejte datum platby, které je po datu v** Poli datum slevy** Políčka data se změní na červené písmo a v dolní části okna se zobrazí chybová zpráva.

    > [!TIP]  
>   Chcete-li udělat výjimku a udělit slevu, i když je úhrada vytvořena, pak postupujte následovně:
4. Zvolte akci **Detaily**.  
5. V okně **Detaily registrace plateb** v poli **datum skonta na **záložce s náhledem **Platební sleva**, zadejte datum, které je po datu v poli **Datum přijetí** v okně **Registrace platby**.  

    Chybová zpráva a červené písmo zmizí a můžete pokračovat v zpracování slevové platby.    
6. Ověřte, zda pole **Zbývající částka** obsahuje částku, která zbývá zaplatit do celé částky faktury.  
7. Zvolte akci **Zaúčtování plateb**, chcete-li zaúčtovat částečnou platbu do hlavní knihy, banky a účtů zákazníka.  

Související doklad zůstává otevřený.

### <a name="to-process-a-payment-that-is-lower-than-the-remaining-discounted-amount"></a>Zpracování platby, která je nižší než zbývající slevová částka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Registrace plateb** a vyberte související odkaz.  
2. Zadejte částku platby do pole **Přijatá částka**. Částka je nižší než částka v** poli zbývající částka po slevě**

    Zaškrtávací políčko **Platba provedena** se automaticky vybere a pole **Datum přijetí** je vyplněno datem práce.  
3. Do pole **Datum přijetí** zadejte datum platby. Datum je před datem v** Poli datum slevy**
4. Ověřte, zda pole **Zbývající částka** obsahuje částku, která zůstává k zaplacení slevové částky.  
5. Zvolte akci **Zaúčtování plateb**, chcete-li zaúčtovat částečnou platbu do hlavní knihy, banky a účtů zákazníka.  

Související doklad zůstává otevřený.

### <a name="to-process-a-payment-that-is-more-than-the-remaining-discounted-amount"></a>Zpracování platby, která je vyšší než zbývající slevová částka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Registrace plateb** a vyberte související odkaz.  
2. Zadejte částku platby do pole **Přijatá částka**. Částka je vyšší než částka v** poli zbývající částka po slevě**  

    Zaškrtávací políčko **Platba provedena** se automaticky vybere a pole **Datum přijetí** je vyplněno datem práce.    
3. Do pole **Datum přijetí** zadejte datum platby. Datum je před datem v** Poli datum slevy**
4. Ověřte, zda pole **Zbývající částka** obsahuje nulu (0).  
5. Zvolte akci **Účtovat platby**, chcete-li zaúčtovat celou platbu do hlavní knihy, banky a účtů zákazníka.  

Související dokument je uzavřen a zákazníkovi je připsána částka nadměrné platby.  

## <a name="to-find-a-specific-sales-document-that-is-not-fully-invoiced"></a>Vyhledání konkrétního prodejního dokladu, který není plně fakturován
Okno **Registrace plateb** vám pomáhá v úkolech potřebných k vyrovnání vyrovnávacích interních účtů s aktuálními peněžními částkami, abyste zajistili efektivní sběr od zákazníků. Zobrazuje příchozí platby jako řádky, které představují prodejní doklady, kde je splatná částka.  

Obvykle, když je platba provedena, zaznamenána v bance nebo jinak, související prodejní nebo nákupní doklad je zobrazen jako řádek v okně **Registrace plateb**, protože dotyčný doklad čeká, aby byla platba zaúčtována proti nezaplacené částce. Někdy však platba, která byla provedena, není zobrazena v řádku **Registrace plateb** a to zpravidla proto, že dotyčný doklad nebyl plně zaúčtován.

V okně **Hledat doklad** můžete vyhledat doklad, který není plně fakturován. Můžete vyhledat podle jednoho nebo více následujících kritérií:  

* Číslo dokladu  
* Množství nebo rozsah množství  

Následující postup vysvětluje, jak najít konkrétní doklad pomocí obou kritérií hledání.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Registrace plateb** a vyberte související odkaz.
2. Pomocí ukazatele na libovolném řádku vyberte akci **Najít doklad**.
3. V okně **Najít doklad** zadejte vyhledávací hodnotu v dokladu  

    > [!NOTE]  
>   Hodnota zadaná v tomto poli je uzavřena ve skrytých zástupných znacích. To znamená, že funkce vyhledá všechna čísla dokladů, které obsahují zadanou hodnotu.    
4. Do pole **Částka** zadejte konkrétní částku, která existuje v dokladu, který chcete najít.  
5. Do pole **Množství tolerance %** zadejte procentuální hodnotu pro definování rozsahu částek, které chcete vyhledat, abyste nalezli otevřený doklad.  

    Pokud zadáte hodnotu 10, funkce bude vyhledávat částky v rozsahu mezi deseti procenty nižší a deset procent vyšší než hodnota v poli **Částka**.    
6. Zvolte akci **Najít**.  

Funkce vyhledávání vyhledává doklady, které nejsou na základě zadaných kritérií plně fakturovány.  

Pokud jeden nebo více dokladů odpovídá kritériím, otevře se okno **Výsledek hledání dokladu**, čímž se zobrazí řádky, které tyto doklady představují. Každý řádek obsahuje číslo dokladu, popis a částku, takže můžete snadno najít konkrétní doklad, například na základě informací ve vašem bankovním výpisu.  

Pokud není platba v bance reprezentována žádným dokladem v [!INCLUDE[d365fin](includes/d365fin_md.md)], potom můžete otevřít předem vyplněný finanční deník z okna **Registrace plateb** a zaúčtovat platbu přímo na vyrovnávací účet bez použití platby k dokladu. Případně možná budete chtít zaznamenat platbu v deníku, dokud nebude původní platba vyřešena.  

## <a name="to-record-or-post-a-payment-without-a-related-document"></a>Zaznamenání nebo zaúčtování platby bez souvisejícího dokladu
Pokud není platba v bance reprezentována žádným dokladem v [!INCLUDE[d365fin](includes/d365fin_md.md)], potom můžete otevřít předem vyplněný finanční deník z okna **Registrace plateb** a zaúčtovat platbu přímo na vyrovnávací účet bez použití platby k dokladu. Případně můžete zaznamenat platbu v deníku, dokud není objasněna původní platba.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Registrace plateb** a vyberte související odkaz.  

Proces zaznamenávání nedokumentované platby.  

1. Vyberte akci **Finanční deník**.  

    Okno **Finanční deník** se otevře s jedním řádkem předvyplněným vyrovnávacím účtem z dávky deníku, která je nastavena v okně **Nastavení registrace plateb**.  
2. Vyplňte zbývající pole na řádku finančního deníku například částku a číslem zákazníka nebo dalšími informacemi z bankovního výpisu. Další informace naleznete v tématu [Návod: Přímé účtování do hlavní knihy.](finance-how-post-transactions-directly.md)  

Můžete zaúčtovat řádek deníku k aktualizaci celkové částky na vyrovnávacím účtu. Případně můžete ponechat řádek deníku nezaúčtovaný a třeba ho připojit k poznámce, že platba vyžaduje další analýzu.  

Pokud ponecháte řádek deníku nezaúčtovaný, přidá se k hodnotě v poli **Nezaúčtovaný zůstatek** v dolní části okna **Registrace plateb**.  

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Prodej](sales-manage-sales.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

