---
title: "Ruční odsouhlasení plateb dodavatelů"
description: "Chcete-li zpracovat, spojit, vyrovnat nebo vrátit platby dodavatelů manuálně, můžete vyrovnat součet jedné nebo více otevřených souvisejících položek. "
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment application, payment processing, match payments
ms.date: 06/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b65b39c120dc1c6837e0b1f53a22bc2ef9b1de38
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-reconcile-vendor-payments-manually"></a>Návod: Ruční odsouhlasení plateb dodavatelů
Když odešlete platbu nebo obdržíte od dodavatele refundaci, musíte se rozhodnout, zda bude platit nebo refundovat na jednu nebo více otevřených položek. Můžete zadat přesnou částku, kterou chcete použít na doklad o platbě nebo refundaci, a pak jen částečně použít položky dodavatele. Musíte použít všechny záznamy v registru dodavatelů, abyste získali správné statistiky dodavatelů a přehledy výpisů z účtu a poplatků za nastavení finančních prostředků.

> [!NOTE]  
>   Dodavatelé mohou někdy vrátit refundaci platby namísto dobropisu k zaplacení budoucích faktur, zvláště když vrátíte položky, které jste již zaplatili, nebo když jste zaplatili fakturu.

Položky dodavatele můžete vyrovnat třemi různými způsoby:

* Zadáním informací do specializovaných oken, například okna **Deníky plateb** a **Deníky odsouhlasení plateb**.
* Z dokladů nákupních dobropisů.
* Z položek dodavatele po zakoupení jsou zaúčtovány nákupní doklady, ale nejsou vyrovnány.

> [!NOTE]  
>   Pokud pole **Metoda vyrovnání** na kartě dodavatele obsahuje **Vyrovnat nejstarší**, pak budou platby automaticky uplatněny na nejstarší položku otevřeného kreditu, pokud ručně neurčíte, ke které položce se vztahuje. Pokud je metoda použití pro zákazníka **Ručně**, musíte je vyrovnat ručně.

Platby dodavatelů můžete vyrovnat ručně na související doklady o nákupu, když zaúčtujete platby v okně **Deníky plateb**. Informace o vyplňování deníku plateb naleznete v části [Provedení plateb](payables-make-payments.md).

Můžete také vyrovnat platby dodavatele a platby zákazníka poté, co se platby objeví ve vaší bance jako záporné bankovní transakce. V okně **Deníky odsouhlasení plateb** můžete použít funkce pro import bankovních výpisů, automatické vyrovnání a odsouhlasení bankovních účtů. Další informace naleznete v tématu [Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).

## <a name="to-apply-a-payment-to-a-single-or-multiple-vendor-ledger-entries"></a>Platba na jednu nebo více položek dodavatele
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky plateb** a vyberte související odkaz.
2. V okně **Deníky plateb** vložte do prvního řádku deníku příslušné informace o položce platby.
3. Chcete-li použít jedinou položku dodavatele:
   1. V poli **Číslo vyrovnání **dokladu, které otevře okno **Vyrovnat položky dodavatele**.
   2. V okně **Vyrovnat položky dodavatele** vyberte položku, na kterou chcete platbu vyrovnat.
   3. Na řádku v poli **Částka k vyrovnání** zadejte částku k použití na položku.
4. Nebo použijte více položek dodavatele:

   1. Vyberte tlačítko **Vyrovnat položky**.
   2. V okně **Vyrovnání položek dodavatele** vyberte řádek s položkami, ve kterých chcete platbu použít.
   3. Zvolte akci **Nastavit ID vyrovnání**.  
   4. Na každém řádku v poli **Částka k vyrovnání** zadejte částku k vyrovnání jednotlivé položky.

      Pokud nezadáte částku, automaticky se použije maximální částka. V dolní části okna **Vyrovnání položek dodavatele** můžete vidět částku v poli Vyrovnaná částka a zjistíte, zda se aplikace vyrovnává.
5. Zvolte tlačítko **OK**.
6. Zvolte akci **Účtovat** pro zaúčtování deníku plateb.

## <a name="to-apply-a-credit-memo-to-a-single-or-multiple-vendor-ledger-entries"></a>Vyrovnání dobropisu k jedné nebo více položkám dodavatele
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nákupní dobropisy** a vyberte související odkaz.
2. Otevřete dobropis, který chcete vyrovnat.
3. Zadejte příslušné informace do hlavičky.
4. K vyrovnání jedné položky hlavní knihy dodavatele, běžte na záložku **Vyrovnání**,  políčko **Číslo vyrovnání dokladu. **vyberte položku, kterou chcete vyrovnat v políčku **Částka k vyrovnání** a vložte sumu k vyrovávní položky.
5. Nebo použijte více položek dodavatele:

   1. Vyberte tlačítko **Vyrovnat položky**.
   2. Zvolte řádky s položkami, které chcete vyrovnat dobropisem.
   3. Zvolte akci **Nastavit ID vyrovnání**.  
   4. Na každém řádku v poli **Částka k vyrovnání** zadejte částku k vyrovnání jednotlivé položky.

       Pokud nezadáte částku, automaticky se použije maximální částka. V dolní části okna **Vyrovnání položky dodavatele** můžete vidět částku v poli **Vyrovnaná částka** a zjistíte, zda se aplikace vyrovnává.
6. Zvolte tlačítko **OK**.  
   Okno **Nákupní dobropis** zobrazuje položku, kterou jste vybrali v poli dokumentu **Typ vyrovnání dokladu a **v poli** Číslo vyrovnání dokladu** Okno také zobrazuje částku dobropisu, která má být zaúčtována, upravenou o případné skonto slevy.
7. Zvolte tlačítko **Účtovat**, chcete-li dobropis zaúčtovat.

## <a name="to-apply-posted-vendor-ledger-entries"></a>Vyrovnání položek dodavatele
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dodavatelé** a vyberte související odkaz.
2. Otevřete příslušného dodavatele s položkami, které již byly zaúčtovány.
3. Zvolte akci **Položky** a poté akci **Vyrovnat položky**.
4. V okně **Vyrovnat položky dodavatele** můžete vidět otevřené položky dodavatele.
5. Vyberte řádek s položkou, která bude vyrovnána.
6. Zvolte akci **Nastavit ID vyrovnání**.

    Pole **ID Vvyrování** zobrazuje tři hvězdičky, pokud pracujete v systému pro jednoho uživatele nebo vaše uživatelském ID, pokud pracujete v systému více uživatelů.  
7. Pro každý řádek v poli **Částka k vyrovnání** zadejte částku k vyrovnání jednotlivé položky.

    Pokud nezadáte částku, automaticky se použije maximální částka. Částku můžete vidět v poli **Vyrovnaná částka** v dolní části okna **Vyrovnat položky dodavatele**.
8. Zvolte akci **Účtovat vyrovnání**.  

    Zobrazí se okno **Účtovat vyrovnání** s číslem dokladu vyrovnávající položky a datem zaúčtování položky s datem posledního zadávání.
9. Zvolte tlačítko **OK** pro zaúčtování vyrovnání.

## <a name="to-apply-vendor-ledger-entries-in-different-currencies-to-one-another"></a>Vyrovnání položek dodavatele v různých měnách
Pokud nakoupíte od dodavatele v jedné měně a vytvoříte platbu v druhé měně, můžete pořád vyrovnat fakturu s touto platbou.

Pokud vyrovnáte položku (položka 1) v jedné měně k položce (položka 2) v jiné měně, datum zaúčtování položky 1 se použije k nalezení příslušného směnného kurzu pro převod částek na položku 2. Příslušný směnný kurz naleznete v okně **Směnné kurzy**. V tomto případě musíte zapnout vyrovnání položek dodavatele v různých měnách. Další informace naleznete v tématu [Návod: Umožnění vyrovnání položek v různých měnách](finance-how-enable-application-ledger-entries-different-currencies.md)

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky plateb** a vyberte související odkaz.
2. Otevřete deník, který chcete, a vyplňte první prázdný řádek deníku s použitím kódu měny.
3. Zvolte akci **Vyrovnat položky**.
4. Vyberte řádek s položkou, pro kterou chcete použít položku v deníku plateb, vyberte akci **Nastavit ID vyrovnání** a pak vyberte položku, kterou chcete použít.
5. Zvolte tlačítko **OK** pro návrat do deníku plateb.
6. Zaúčtujte deník plateb.

> [!IMPORTANT]  
>   Při použití položek v různých měnách se položky přepočítají na USD. I když jsou směnné kurzy pro dvě příslušné měny pevně stanoveny, například mezi USD a EUR, mohou být tyto částky v cizí měně přepočteny na USD. Tyto malé zbytkové částky jsou účtovány jako zisky a ztráty na účtu uvedeném v poli **Účet realizovaných zisků** nebo **Účet realizovaných ztrát** v okně **Měny**. Pole **Částka (USD)** je také nastavena na příslušných položkách knihy dodavatelů.

## <a name="to-unapply-an-application-of-vendor-entries"></a>Zrušení vyrovnání položek dodavatele
Pokud zrušíte chybné vyrovnání, oprava položek, které jsou totožné s původní položkou, ale s opačným znaménkem v poli částky, jsou vytvořeny a zaúčtovány pro všechny položky včetně veškerého účtování hlavní knihy odvozené z vyrovnání jako jsou skonto slevy a kurzové zisky/ztráty. Položky, které byly uzavřeny vyrovnáním, jsou znovu otevřeny.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dodavatelé** a vyberte související odkaz.
2. Otevřete příslušnou kartu dodavatele.
3. Zvolte akci **Položky**.
4. Vyberte odpovídající položku a potom vyberte akci **Zrušit vyrovnání položek**.
5. Alternativně zvolte akci **Detailní položky**.
6. Vyberte položku vyrovnání a potom vyberte akci **Zrušit vyrovnání položek**.
7. Vyplňte pole v hlavičce a poté klepněte na tlačítko **Zrušit vyrovnání**.

> [!IMPORTANT]  
>   Pokud byla položka vyrovnána více než jednou, musíte nejprve zrušit vyrovnání nejnovější položky.

## <a name="see-also"></a>Viz také
[Závazky](payables-manage-payables.md)  
[Nákup](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

