---
title: "Vyrovnání položek zákazníka manuálním odsouhlasením plateb"
description: "Popisuje jak vyrovnat účtenky zákazníka, vrátit jednu nebo více otevřených položek a odsouhlasit platbu."
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment process, cash receipt
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: bf6be6c1e4130396210555a394f39f0ce4b54f5a
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-reconcile-customer-payments-manually"></a>Návody: Ruční odsouhlasení plateb zákazníkům
Když obdržíte od zákazníka doklad o hotovosti nebo provedete vrácení peněz zákazníkovi, musíte se rozhodnout, zda chcete platbu vyrovnat nebo vrátit zpět na jednu nebo více otevřených položek MD nebo Dal. Můžete určit částku, kterou chcete vyrovnat. Například, když chcete vyrovnat částečnými platbami položky zákazníka Uzavírání položek zákazníka zajišťuje, že informace jako jsou statistika zákazníka, výpisy z účtů a finanční poplatky jsou správné.

> [!NOTE]  
>   V okně **Položky zákazníka** červený font písma znamená, že příslušná platba je po splatnosti

Položky v knize zákazníků můžete vyrovnat několika způsoby:

* Zadáním informací do vyhrazených oken, jako jsou například okna **Deník přijaté hotovosti** a **Deník odsouhlasení plateb**.
* Z dokladů prodejních dobropisů.
* Položky z knihy zákazníků po prodejních dokladech se zaúčtují, ale nejsou vyrovnány.

> [!NOTE]  
>   Pokud pole **Metoda vyrovnání** na kartě zákazníka obsahuje **Vyrovnat nejstarší**, pak budou platby vyrovnány na nejstarší otevřenou položku Dal, pokud ručně neurčíte položku. Pokud je metoda vyrovnání **Ruční**, vždy se položky vyrovnávají ručně.

Můžete vyrovnat platby zákazníků ručně v okně **Deník přijaté hotovosti**. Deník přijaté hotovosti je typ hlavní knihy, takže jej můžete použít k zaúčtování transakcí do hlavní knihy, bank, zákazníků, prodejců a účtů dlouhodobého majetku. Platbu můžete vyrovnat na jednu nebo více položek MD, když zaúčtujete platbu nebo je můžete vyrovnat ze zaúčtovaných položek později.

Můžete také vyrovnat platby zákazníků a dodavatelů v okně **Deník odsouhlasení plateb** pomocí funkcí pro import bankovních výpisů, automatické vyrovnání a odsouhlasení bankovních účtů. Další informace naleznete v tématu [Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md). Případně můžete odsouhlasit platby zákazníků na základě seznamu nezaplacených prodejních dokladů v okně **Registrace plateb**. Další informace naleznete v tématu [Návod: Odsouhlasení plateb zákazníků ze seznamu nezaplacených prodejních dokladů.](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md)

## <a name="to-fill-and-post-a-cash-receipt-journal"></a>Vyplnění a zaúčtování deníku přijaté hotovosti
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky přijaté hotovosti** a vyberte související odkaz.
2. Vyberte akci **Upravit deník**.
3. Zvolte příslušnou dávku v poli **Název dávky**.
4. Vyplňte pole **Zúčtovací datum**.  
5. Do pole **Typ dokladu** vyberte **Platba**.

    Pole **Číslo dokladu** je vyplněno číselnými řadami přiřazenými dávce.  
6. Použijte pole **Číslo externího dokladu** pro uložení identifikátoru, jako je číslo šeku zákazníka.
7. V poli **Typ účtu** vyberte **Zákazník**.
8. V poli **Číslo účtu** vyberte relevantní finanční účet.
9. Chcete-li zaúčtovat vyrovnání současně se zaúčtováním deníku, proveďte jeden z následujících úkonů.
10. V poli **Typ protiúčtu** vyberte **Finanční účet** pro platbu v hotovosti a **Bankovní účet** pro ostatní platby.
11. V poli **Číslo protiúčtu** zadejte hotovostní účet pro hotovostní platby nebo příslušný bankovní účet pro jiné platby.
12. Zaúčtujte deník.

## <a name="to-apply-a-payment-to-a-single-customer-ledger-entry"></a>Vyrovnání platby na jednu položku knihy zákazníka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky přijaté hotovosti** a vyberte související odkaz.
2. Vyberte akci **Upravit deník**.
3. Na prvním řádku deníku zadejte příslušné informace o položce, která má být vyrovnána.
4. Do pole **Typ dokumentu** zadejte **Platba**.
5. V poli **Typ účtu** vyberte **Zákazník**.
6. V poli **Číslo zdroje protiúčtu **vyberte **Bankovní účet**.
7. V poli **Číslo vyrovnání **dokladu, které otevře okno **Vyrovnat položky zákazníka**.
8. V okně **Vyrovnat položky zákazníka** vyberte položku, na kterou chcete platbu vyrovnat.
9. Do pole **Částka k vyrovnání** zadejte částku, kterou chcete vyrovnat pro položku. Pokud nezadáte částku, vyrovná se maximum částky.

    V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka** a také zda se vyrovná zůstatek.  
10. Zvolte tlačítko **OK**. Okno **Deník přijaté hotovosti** nyní zobrazuje položku, kterou jste vybrali, zadanou v polích **Typ vyrovnání **a** Číslo vyrovnání dokladu**
11. Zaúčtujte deník přijaté hotovosti.

## <a name="to-apply-a-payment-to-multiple-customer-ledger-entries"></a>Vyrovnání platby pro více položek knihy zákazníka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky přijaté hotovosti** a vyberte související odkaz.
2. Vyberte akci **Upravit deník**.
3. Na prvním řádku deníku zadejte příslušné informace o položce, která má být vyrovnána.
4. Do pole **Typ dokumentu** zadejte **Platba**.
5. V poli **Typ účtu** vyberte **Zákazník**.
6. V poli **Číslo zdroje protiúčtu **vyberte **Bankovní účet**.
7. Do pole **Částka** zadejte úplnou platbu jako zápornou částku.
8. Chcete-li platbu zaúčtovat na více položek knihy zákazníka, zvolte akci **Vyrovnat položky**.  
9. Vyberte řádek s položkami, které chcete vyrovnat a potom vyberte akci **Nastavit ID vyrovnání**.  
10. Na každém řádku v poli **Částka k vyrovnání** zadejte částku, pro kterou chcete vyrovnat jednotlivé položky. Pokud nezadáte částku, vyrovná se maximum částky.

    V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka** a také zda se vyrovná zůstatek.  
11. Zvolte tlačítko **OK**.
12. Zaúčtujte deník přijaté hotovosti.

## <a name="to-apply-a-credit-memo-to-a-single-customer-ledger-entry"></a>Použití dobropisů k položce knihy jednoho zákazníka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní dobropisy** a vyberte související odkaz.
2. Otevřete relevantní prodejní dobropis.
3. Chcete-li vyrovnat dobropis pro položku knihy jednoho zákazníka při zaúčtování, v poli **Číslo vyrovnání **dokladu vyberte položku, na kterou chcete vyrovnat platbu.
4. Na řádku v poli **Částka k vyrovnání** zadejte částku, kterou chcete vyrovnat pro položku.  

    Pokud nezadáte částku, program automaticky použije maximum částky. V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka** a také zda se vyrovná zůstatek.    
5. Zvolte tlačítko **OK**. Okno **Prodejní dobropisy** nyní zobrazuje položku, kterou jste vybrali, zadanou v polích **Typ vyrovnání **a** Číslo vyrovnání dokladu** a částka dobropisu k zaúčtování je upravená o případné slevy na platbu.
6. Zaúčtujte dobropis.

## <a name="to-apply-a-credit-memo-to-multiple-customer-ledger-entries"></a>Vyrovnání dobropisu na více položek knihy zákazníka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní dobropisy** a vyberte související odkaz.
2. Otevřete relevantní prodejní dobropis.
3. Chcete-li vyrovnat dobropis pro více položek knihy zákazníka při zaúčtování, zvolte akci **Vyrovnání položek**.
4. Vyberte řádek s položkami, které chcete vyrovnat a potom vyberte akci **Nastavit ID vyrovnání**.
5. Na každém řádku v poli **Částka k vyrovnání** zadejte částku, pro kterou chcete vyrovnat jednotlivé položky. Pokud nezadáte částku, vyrovná se maximum částky.  

    V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka** a také zda se vyrovná zůstatek.  
6. Zvolte tlačítko **OK**. Okno **Prodejní dobropisy** nyní zobrazuje částku dobropisu k zaúčtování upravenou o případné slevy.
7. Zaúčtujte dobropis.

## <a name="to-apply-posted-customer-ledger-entries"></a>Vyrovnání zaúčtovaných položek knihy zákazníka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zákazníci** a vyberte související odkaz.
2. Otevřete kartu zákazníka pro zákazníka s položkami, které chcete vyrovnat.
3. Zvolte akci **Položky knihy** a potom vyberte řádek s položkou, která bude vyrovnána.
4. Zvolte akci **Vyrovnat položky**. Otevře se okno **Vyrovnání položek zákazníka**, které zobrazuje otevřené položky pro zákazníka.
5. Zvolte řádky s položkami, které chcete použít pro vyrovnání a pak vyberte akci **Nastavení vyrovnání k ID**.
6. U každého řádku v poli **Částka k vyrovnání** zadejte částku, kterou chcete vyrovnat pro jednotlivé položky. Pokud nezadáte částku, vyrovná se maximum částky.  

    V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka**.  
7. Zvolte akci **Účtovat vyrovnání**. Zobrazí se okno **Účtovat vyrovnání** s číslem dokumentu vyrovnávací položky a účtovacím datem položky s posledním datem účtování.  
8. Zvolte tlačítko **OK** pro účtování vyrovnání.

    Pokud účtování vyrovnání vedlo k uzavření položek knihy zákazníka, pole **Otevřít** je čisté pro tyto položky knihy.    
9. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zákazníci** a vyberte související odkaz. Prohlédněte si kartu pro příslušného zákazníka, abyste mohli vidět položky knihy.  

V seznamu položky knihy na řádku, který obsahuje položka knihy, která byla plně vyrovnána, můžeme vidět, že není zaškrtnuto políčko **Otevřít**.  

> [!NOTE]  
>   Poté, co jste vybrali položku z okna **Vyrovnat položky zákazníka** nebo více položek nastavením **ID vyrovnání** bude pole **Vyrovnaná částka** na řádku deníku obsahovat součet zbývajících částek pro účtované položky, které jste vybrali, neobsahuje-li již pole něco. Pokud zvolíte **Vyrovnat nejstarší** v poli **Metody vyrovnání** na kartě zákazníka, vyrovnání se automaticky spustí.

## <a name="to-apply-customer-ledger-entries-in-different-currencies-to-one-another"></a>Vyrovnání položek knihy zákazníka v různých měnách
Když prodáte zákazníkovi v jedné měně a obdržíte platbu v druhé měně, můžete stále vyrovnat platbu na faktuře.  

Pokud vyrovnáte položku (položka 1) v jedné měně na položku (položka 2) v jiné měně, datum účtování v položce 1 se použije k nalezení příslušného směnného kurzu pro převod částek na položku 2. Příslušný směnný kurz naleznete v okně **Směnné kurzy**.  

Vyrovnání položek knihy zákazníka v různých měnách musí být povolena. Další informace naleznete v tématu [Návod: Povolení vyrovnání položek knihy v různých měnách.](finance-how-enable-application-ledger-entries-different-currencies.md)  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky přijaté hotovosti** a vyberte související odkaz.
2. Otevřete deník, který chcete, a vyplňte první prázdný řádek deníku s použitím kódu měny.
3. Zvolte akci **Vyrovnat položky**.
4. Vyberte řádek s položkou, kterou chcete použít pro položku v deníku přijaté hotovosti, zvolte akci **Nastavit ID vyrovnání** a vyberte položku, kterou chcete vyrovnat.
5. Klepnutím na tlačítko **OK** se vrátíte do deníku přijaté hotovosti.
6. Zaúčtujte deník prodeje.  

> [!IMPORTANT]  
>   Při použití položek v různých měnách se položky přepočítají na USD. I když jsou směnné kurzy pro dvě příslušné měny pevně stanoveny, například mezi USD a EUR, mohou být tyto částky v cizí měně přepočteny na USD. Tyto malé zbytkové částky jsou účtovány jako zisky a ztráty na účtu uvedeném v poli **Účet realizovaných zisků** nebo **Účet realizovaných ztrát** v okně **Měny**. Pole **Částka (USD)** je také nastavena na příslušných položkách knihy dodavatelů.  

## <a name="to-correct-an-application-of-customer-entries"></a>Oprava vyrovnání položek zákazníka
Pokud opravíte vyrovnání, položky které jsou totožné s původní položkou, ale s opačným znaménkem v poli částka a jsou vytvořeny a účtovány pro všechny položky včetně veškerého účtování hlavní knihy odvozené z vyrovnání, jako jsou slevy a zisky/ztráty měn. Položky, které byly uzavřeny vyrovnáním, jsou znovu otevřeny.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zákazníci** a vyberte související odkaz.
2. Otevřete příslušnou zákaznickou kartu.
3. Zvolte akci **Položky knihy**.
4. Vyberte příslušné položky knihy a poté zvolte akci **Zrušit vyrovnání položek**.
5. Alternativně zvolte akci **Detailní položky knihy**.
6. Vyberte položky vyrovnání a potom vyberte akci **Zrušit vyrovnání položek**.
7. Vyplňte pole v hlavičce a poté klepněte na tlačítko **Zrušit vyrovnání**.  

> [!IMPORTANT]  
>   Pokud byla položka vyrovnána více než jednou, musíte nejprve zrušit vyrovnání nejnovější položky.  

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Prodej](sales-manage-sales.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

