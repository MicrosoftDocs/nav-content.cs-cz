---
title: "Návod: Odsouhlasení plateb zákazníků ručně ze seznamu nezaplacených prodejních dokladů"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: c03503324ba74ee265a8a432b7df416198b255b0
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-customer-payments-manually-from-a-list-of-unpaid-sales-documents"></a>Návod: Odsouhlasení plateb zákazníků ručně ze seznamu nezaplacených prodejních dokladů
Když vaši zákazníci provedli platby na váš bankovní účet, musíte vyrovnat každou zaplacenou částku do souvisejícího prodejního dokladu a následně zaúčtovat platbu za účelem aktualizace zákazníka, hlavní knihy a položek knihy bank.

**Poznámka**: Stejné úkoly včetně plateb dodavatelů, můžete provést v okně **Deníky odsouhlasení plateb** pomocí funkcí pro import bankovního výpisu, automatické vyrovnání a odsouhlasení bankovního účtu. Další informace naleznete v tématu [Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).

Okno **Registrace plateb** je navrženo tak, aby vám pomohlo při úkonech při vyrovnávacích vnitřních účtech pomocí skutečných peněžních údajů, abyste se ujistili, že platby jsou vybírány od zákazníků efektivně. Tento nástroj pro zpracování plateb vám umožňuje rychle ověřit a zaúčtovat jednotlivé nebo jednorázové platby, zpracovat slevové platby a najít konkrétní nezaplacené doklady, pro které byla úhrada vytvořena.

Platby pro různé zákazníky, které mají různé datum platby, musí být zaúčtovány jako jednotlivé platby. Platby pro stejného zákazníka, které mají stejné datum platby, můžete zaúčtovat jako jednorázovou platbu. To je užitečné například když zákazník provedl jednu platbu, která pokrývá více prodejních faktur.

## <a name="to-set-up-the-payment-registration-journal"></a>Nastavení deníku pro registraci plateb
Protože můžete zaúčtovat různé typy plateb do různých vyrovnávacích účtů, musíte vybrat vyrovnávací účet v okně **Nastavení registrace plateb** předtím, než začnete zpracovávat platby zákazníků. Pokud vždy zaúčtujete na stejný vyrovnávací účet, můžete tento účet nastavit jako výchozí a vyhýbat se tomuto kroku pokaždé, když otevřete okno **Registrace plateb**.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení registrace plateb** a pak vyberte související odkaz. Alternativně v okně **Registrace plateb** vyberte akci **Nastavení**.
2. Vyplňte pole v okně **Nastavení registrace plateb**. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro související informace.  

## <a name="to-reconcile-payments-individually"></a>Odsouhlasení plateb jednotlivě
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Registrace plateb** a pak vyberte související odkaz.  
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
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Registrace plateb** a pak vyberte související odkaz.
2. Zaškrtněte políčko **Platba provedena** na řádcích, které představují zaúčtované doklady pro stejného zákazníka, pro kterého byla provedena jednorázová platba.

    **Poznámka**: Zákazník v poli **Jméno** musí mít to samé na všech řádcích, které budou zaúčtovány jako jednorázová platba.

    Pokud je zaškrtnuto políčko **Automatické vyplnění data přijetí** v okně **Nastavení registrací plateb**, pak datum práce je vyplněno v poli **Datum přijetí**.
3. Do pole **Datum přijetí** zadejte datum, kdy byla platba provedena. Toto datum se může lišit od data práce.

    **Poznámka**: Toto datum musí být stejné na všech řádcích, které budou zaúčtovány jako jednorázová platba.
4. Do pole **Přijatá částka** zadejte částky na více řádcích, které se shodují s částkou jednorázové platby.

    **Tip**: Pokuste se zaúčtovat co nejvíce plných plateb s jednorázovou částkou. Zadejte částky, které jsou stejné jako částka v poli **Zbývající částka**, na co nejvíce řádků je to možné.
5. Opakujte kroky 2 až 4 pro další řádky, které představují zaúčtované doklady pro stejného zákazníka, pro kterého byla provedena jednorázová platba.  
6. Zvolte akci **Účtovat jako jednorázovou platbu**. Zadané informace o platbě jsou zaúčtovány pro dokumenty představované řádky, kde je zaškrtnuto políčko **Platba provedena**.

Položky platby jsou účtovány v hlavní knize, bankách a účtů zákazníků. Každá platba je vyrovnána na příslušný zaúčtovaný prodejní doklad.

Pokud platba v bance není zobrazena v řádku **Registrace plateb**, může to být proto, že související dokument nebyl dosud zaúčtován. V takovém případě můžete pomocí funkce vyhledávání, rychle vyhledat doklad a zaúčtovat jej, aby zpracoval platbu. Další informace naleznete v tématu Návod: Nalezení nezaplacených dokladů během ručního odsouhlasení plateb zákazníků.

Pokud není platba v bance reprezentována žádným dokumentem v [!INCLUDE[navnow](includes/navnow_md.md)], můžete otevřít předem vyplněný finanční deník z okna **Registrace plateb** a zaúčtovat platbu přímo na vyrovnávací účet bez použití platby k dokladu. Případně možná budete chtít zaznamenat platbu v deníku, dokud nebude původní platba vyřešena. Další informace naleznete v tématu „Zaznamenání nebo zaúčtování platby bez souvisejícího dokumentu.“

## <a name="to-customer-payments-with-discounts-manually"></a>Platby zákazníků se slevami ručně
Pokud máte odsouhlasenu platební slevu s vaším zákazníkem, může být částka platby nižší než částky faktury, pokud k platbě dojde před dohodnutým datem slevy.

Tento postup vysvětluje čtyři různé postupy pro zaúčtování slev plateb v okně **Registrace plateb**.

- Částka platby se rovná zbývající slevové částce a datum platby je před datem slevy. Platbu zaúčtujete tak, jak je.
- Částka platby se rovná zbývající slevové částce, ale datum platby je po datu slevy. Platbu zaúčtujete jako částečnou. Dokument zůstává otevřený pro vybírání/zaplacení zbývající částky. Případně můžete nastavit datum slevy později, abyste mohli povolit platbu v plné výši.
- Výše platby je nižší než zbývající slevová částka. Platbu zaúčtujete jako částečnou. Dokument zůstává otevřený pro vybírání/zaplacení zbývající částky.
- Výše platby je vyšší než zbývající slevová částka. Platby zaúčtujete tak, jak jsou. Pouze zbývající částka je zaúčtována. Dodatečná částka je připsána zákazníkovi.

## <a name="to-process-a-payment-amount-that-is-equal-to-the-discounted-amount-and-where-the-payment-date-is-before-the-discount-date"></a>Zpracování části platby, která se rovná slevové částce a kde je datum platby před datem slevy
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Registrace plateb** a pak vyberte související odkaz.  
2. Zadejte částku platby do pole **Přijatá částka**. Částka se rovná částce v** poli Rem. Amt. after Discount**.

    Zaškrtávací políčko **Platba provedena** se automaticky vybere a pole **Datum přijetí** je vyplněno datem práce.
3. Do pole **Datum přijetí** zadejte datum platby. Datum je před datem v** poli Pmt. Discount Date**.
4. Ověřte, zda pole **Zbývající částka** obsahuje nula (0).  
5. Zvolte akci **Účtovat platby**, chcete-li zaúčtovat celou platbu do hlavní knihy, banky a účtů zákazníka.

Související dokument je uzavřen.

## <a name="to-process-a-payment-amount-that-is-equal-to-the-discounted-amount-but-where-the-payment-date-is-after-the-discount-date"></a>Zpracování části platby, která se rovná slevové částce, ale datum platby je po datu slevy
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Registrace plateb** a pak vyberte související odkaz.  
2. Zadejte částku platby do pole **Přijatá částka**. Částka se rovná částce v** poli Rem. Amt. after Discount**.

    Zaškrtávací políčko **Platba provedena** se automaticky vybere a pole **Datum přijetí** je vyplněno datem práce.
3. Do pole **Datum přijetí** zadejte datum platby, které je po datu v** poli Pmt. Dicsount Date**. Políčka data se změní na červené písmo a v dolní části okna se zobrazí chybová zpráva.

    **Tip**: Chcete-li udělat výjimku a udělit slevu, i když je úhrada vytvořena, pak postupujte následovně:  
4. Zvolte akci **Detaily**.  
5. V okně **Detaily registrace plateb** v poli **Pmt. Discount Date na **záložce s náhledem **Platební sleva**, zadejte datum, které je po datu v poli **Datum přijetí** v okně **Registrace platby**.

    Chybová zpráva a červené písmo zmizí a můžete pokračovat v zpracování slevové platby.
6. Ověřte, zda pole **Zbývající částka** obsahuje částku, která zbývá zaplatit do celé částky faktury.  
7. Zvolte akci **Zaúčtování plateb**, chcete-li zaúčtovat částečnou platbu do hlavní knihy, banky a účtů zákazníka.  
Související doklad zůstává otevřený.

## <a name="to-process-a-payment-that-is-lower-than-the-remaining-discounted-amount"></a>Zpracování platby, která je nižší než zbývající slevová částka
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Registrace plateb** a pak vyberte související odkaz.  
2. Zadejte částku platby do pole **Přijatá částka**. Částka je nižší než částka v** poli Rem. Amt. After Discount**.

    Zaškrtávací políčko **Platba provedena** se automaticky vybere a pole **Datum přijetí** je vyplněno datem práce.
3. Do pole **Datum přijetí** zadejte datum platby. Datum je před datem v** poli Pmt. Discount Date**.
4. Ověřte, zda pole **Zbývající částka** obsahuje částku, která zůstává k zaplacení slevové částky.  
5. Zvolte akci **Zaúčtování plateb**, chcete-li zaúčtovat částečnou platbu do hlavní knihy, banky a účtů zákazníka.  
Související doklad zůstává otevřený.

## <a name="to-process-a-payment-that-is-more-than-the-remaining-discounted-amount"></a>Zpracování platby, která je vyšší než zbývající slevová částka
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Registrace plateb** a pak vyberte související odkaz.  
2. Zadejte částku platby do pole **Přijatá částka**. Částka je vyšší než částka v** poli Rem. Amt after Discount**.

    Zaškrtávací políčko **Platba provedena** se automaticky vybere a pole **Datum přijetí** je vyplněno datem práce.
3. Do pole **Datum přijetí** zadejte datum platby. Datum je před datem v** poli Pmt. Discount Date**.
4. Ověřte, zda pole **Zbývající částka** obsahuje nulu (0).  
5. Zvolte akci **Účtovat platby**, chcete-li zaúčtovat celou platbu do hlavní knihy, banky a účtů zákazníka.

Související dokument je uzavřen a zákazníkovi je připsána částka nadměrné platby.

## <a name="to-find-a-specific-sales-document-that-is-not-fully-invoiced"></a>Vyhledání konkrétního prodejního dokladu, který není plně fakturován
Okno **Registrace plateb** vám pomáhá v úkolech potřebných k vyrovnání vyrovnávacích interních účtů s aktuálními peněžními částkami, abyste zajistili efektivní sběr od zákazníků a plateb dodavatelům. Zobrazuje příchozí platby jako řádky, které představují prodejní doklady, kde je splatná částka.

Obvykle, když je platba provedena, zaznamenána v bance nebo jinak, související prodejní nebo nákupní doklad je zobrazen jako řádek v okně **Registrace plateb**, protože dotyčný doklad čeká, aby byla platba zaúčtována proti nezaplacené částce. Někdy však platba, která byla provedena, není zobrazena v řádku **Registrace plateb** a to zpravidla proto, že dotyčný doklad nebyl plně zaúčtován.

V okně **Hledat doklad** můžete vyhledat doklad, který není plně fakturován. Můžete vyhledat podle jednoho nebo více následujících kritérií:

- Číslo dokladu
- Množství nebo rozsah množství

Následující postup vysvětluje, jak najít konkrétní doklad pomocí obou kritérií hledání.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Registrace plateb** a pak vyberte související odkaz.
2. Pomocí ukazatele na libovolném řádku vyberte akci **Najít doklad**.
3. V okně **Najít doklad** zadejte vyhledávací hodnotu v poli **Číslo dokladu**.

    **Poznámka**: Hodnota zadaná v tomto poli je uzavřena ve skrytých zástupných znacích. To znamená, že funkce vyhledá všechna čísla dokladů, které obsahují zadanou hodnotu.
4. Do pole **Částka** zadejte konkrétní částku, která existuje v dokladu, který chcete najít.  
5. Do pole **Množství tolerance %** zadejte procentuální hodnotu pro definování rozsahu částek, které chcete vyhledat, abyste nalezli otevřený doklad.

    Pokud zadáte hodnotu 10, funkce bude vyhledávat částky v rozsahu mezi deseti procenty nižší a deset procent vyšší než hodnota v poli **Částka**.
6. Zvolte akci **Najít**.

Funkce vyhledávání vyhledává doklady, které nejsou na základě zadaných kritérií plně fakturovány.

Pokud jeden nebo více dokladů odpovídá kritériím, otevře se okno **Výsledek hledání dokladu**, čímž se zobrazí řádky, které tyto doklady představují. Každý řádek obsahuje číslo dokladu, popis a částku, takže můžete snadno najít konkrétní doklad, například na základě informací ve vašem bankovním výpisu.

Pokud není platba v bance reprezentována žádným dokladem v [!INCLUDE[navnow](includes/navnow_md.md)], můžete otevřít předem vyplněný finanční deník z okna **Registrace plateb** a zaúčtovat platbu přímo na vyrovnávací účet bez použití platby k dokladu. Případně možná budete chtít zaznamenat platbu v deníku, dokud nebude původní platba vyřešena.

##<a name="to-record-or-post-a-payment-without-a-related-document"></a>Zaznamenání nebo zaúčtování platby bez souvisejícího dokladu
Pokud není platba v bance reprezentována žádným dokladem [!INCLUDE[navnow](includes/navnow_md.md)], můžete otevřít předem vyplněný řádek finančního deníku z okna **Registrace plateb** a zaúčtovat platbu přímo na vyrovnávací účet bez použití platby do dokladu. Případně můžete zaznamenat platbu v deníku, dokud není objasněna původní platba.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Registrace plateb** a pak vyberte související odkaz.  
Proces zaznamenávání nedokumentované platby.  
2. Vyberte akci **Finanční deník**.

    Okno **Finanční deník** se otevře s jedním řádkem předvyplněným vyrovnávacím účtem z dávky deníku, která je nastavena v okně **Nastavení registrace plateb**.
3. Vyplňte zbývající pole na řádku finančního deníku například částku a číslem zákazníka nebo dalšími informacemi z bankovního výpisu. Další informace naleznete v tématu [Návod: Práce s finančními deníky](ui-work-general-journals.md).

Můžete zaúčtovat řádek deníku k aktualizaci celkové částky na vyrovnávacím účtu. Případně můžete ponechat řádek deníku nezaúčtovaný a třeba ho připojit k poznámce, že platba vyžaduje další analýzu.

Pokud ponecháte řádek deníku nezaúčtovaný, přidá se k hodnotě v poli **Nezaúčtovaný zůstatek** v dolní části okna **Registrace plateb**.

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Správa prodeje](sales-manage-sales.md)

