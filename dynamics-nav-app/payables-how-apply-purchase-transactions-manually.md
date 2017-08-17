---
title: "Návody: Použít platby dodavatele ručně"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: d3aaafc9ac3dcfd1fba3802b1158bde890e09110
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-apply-vendor-payments-manually"></a>Návody: Použít platby dodavatele ručně

Když odešlete platbu nebo obdržíte od dodavatele refundaci, musíte se rozhodnout, zda bude platit nebo refundovat na jednu nebo více otevřených položek. Můžete zadat přesnou částku, kterou chcete použít na doklad o platbě nebo refundaci, a pak jen částečně použít položky dodavatele. Musíte použít všechny záznamy v registru dodavatelů, abyste získali správné statistiky dodavatelů a přehledy výpisů z účtu a poplatků za nastavení finančních prostředků.

**Poznámka**: Dodavatelé mohou někdy vrátit refundaci platby namísto dobropisu k zaplacení budoucích faktur, zvláště když vrátíte položky, které jste již zaplatili, nebo když jste zaplatili fakturu.

Položky dodavatele můžete použít třemi různými způsoby:

- Zadáním informací do specializovaných oken, například okna **Deník plateb** a okna **Deník vyrovnání plateb**.
- Z dokladů o koupi dobropisu.
- Z položek dodavatele po zakoupení jsou zaúčtovány nákupní doklady, ale nejsou použity.

**Poznámka**: Pokud pole **Metoda vyrovnání** na kartě dodavatele obsahuje **Vyrovnat nejstarší**, pak budou platby automaticky uplatněny na nejstarší položku otevřeného kreditu, pokud ručně neurčíte, ke které položce se vztahuje. Pokud je metoda použití pro zákazníka **Ručně**, musíte je použít ručně.

Platby dodavatelů můžete uplatnit ručně na související doklady o nákupu, když zaúčtujete platby v okně **Deník plateb**. Informace o vyplňování deníku plateb naleznete v části [Postupy: Provést platby](payables-make-payments.md).

Můžete také použít platby dodavatele a platby zákazníka poté, co se platby objeví ve vaší bance jako záporné bankovní transakce. V okně **Deník vyrovnání plateb** můžete použít funkce pro import bankovních výpisů, automatické přihlašování a odsouhlasení bankovních účtů. Další informace naleznete v [Porovnání plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).

## <a name="to-apply-a-payment-to-a-single-or-multiple-vendor-ledger-entries"></a>Chcete-li platbu použít na jednu nebo více položek dodavatele
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deník plateb** a pak vyberte související odkaz.
2. V okně **Deník plateb** vložte do prvního řádku deníku příslušné informace o položce platby.
3. Chcete-li použít jedinou položku dodavatele:
4. V **Číslo vyrovnání dokladu číslo** pole vyberte pole, které otevře okno **Vyrovnat položky dodavatele**.
5. V okně **Vyrovnat položky dodavatele** vyberte položku, na kterou chcete platbu použít.
6. Na řádku v poli **Částka k vyrovnání** zadejte částku k použití na položku.
7. Nebo použijte více položek dodavatele:
8. Zvolte akci **Použít položky**.
9. V okně **Vyrovnat položky dodavatele** vyberte řádek s položkami, ve kterých chcete platbu použít.
10. Zvolte akci **Nastavit ID vyrovnání**.  
11. Na každém řádku v poli **Částka k vyrovnání** zadejte částku k vyrovnání jednotlivé položky.

    Pokud nezadáte částku, automaticky se použije maximální částka. V dolní části okna **Vyrovnat položky dodavatele** můžete vidět částku v poli Použitá částka a zjistíte, zda se aplikace vyrovnává.
12. Zvolte tlačítko **OK**.
13. Zvolte akci **Zúčtovat** uveďte deník plateb.

## <a name="to-apply-a-credit-memo-to-a-single-or-multiple-vendor-ledger-entries"></a>K vyrovnání dobropisu k jedné nebo více položkám prodejce
1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Nákupní dobropis** a zvolte související odkaz.
2. Otevřete dobropis, který chcete použít.
3. Zadejte příslušné informace do hlavičky.
4. Chcete-li použít jedinou položku dodavatele:
5. Na záložce s náhledem**Vyrovnání** v dokladu **Číslo vyrovnání dokladu číslo** pole, vyberte položku, na kterou chcete použít kredit.
6. Na řádku v poli **Částka k vyrovnání** zadejte částku k použití na položku.
7. Nebo použijte více položek dodavatele:
8. Zvolte akci **Použít položky**.
9. Zvolte řádky s položkami, na které chcete použít dobropis.
10. Zvolte akci **Nastavit ID vyrovnání**.  
11. Na každém řádku v poli **Částka k vyrovnání** zadejte částku k vyrovnání jednotlivé položky.

    Pokud nezadáte částku, automaticky se použije maximální částka. V dolní části okna **Použít položky dodavatele** můžete vidět částku v poli **Použitá částka** a zjistíte, zda se aplikace vyrovnává.
12. Zvolte tlačítko **OK**.  
Okno **Nákupní dobropis** zobrazuje položku, kterou jste vybrali v dokumentech **Vyrovnání dokladu Typ** pole a **Vyrovnání dokladu číslo** pole Okno také zobrazuje částku dobropisu, který má být zaúčtován, upraveno o případné slevy na platbě.
13. Zvolte tlačítko **Zaúčtovat** , chcete-li zaúčtovat dobropis.

## <a name="to-apply-posted-vendor-ledger-entries"></a>Chcete-li použít položky dodavatele

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.
2. Otevřete příslušného dodavatele s položkami, které již byly zaúčtovány.
3. Zvolte akci **Položky** a poté akci **Vyrovnat položky**.
4. V okně **Vyrovnat položky dodavatele** můžete vidět otevřené položky dodavatele.
5. Vyberte řádek s položkou, která bude vyrovnána.
6. Zvolte akci **Nastavit ID vyrovnání**.
7. Pole " **Platí pro ID** zobrazuje tři hvězdičky, pokud pracujete v systému pro jednoho uživatele nebo v uživatelském ID, pokud pracujete v systému více uživatelů.  
8. Pro každý řádek v poli **Částka k vyrovnání** zadejte částku k vyrovnání jednotlivé položky.

    Pokud nezadáte částku, automaticky se použije maximální částka. Částku můžete vidět v poli **Vyrovnaná částka** v dolní části okna **Vyrovnat položky dodavatele**.
9. Zvolte akci **Zaúčtovat vyrovnání**.  
Zobrazí se okno **Zaúčtovat vyrovnání** s číslem dokladu přihlášené položky a datem zaúčtování položky s datem posledního zadávání.
10. Zvolte tlačítko **OK** pro zaúčtování vyrovnání.

## <a name="to-apply-vendor-ledger-entries-in-different-currencies-to-one-another"></a>Vyrovnat položky dodavatele v různých měnách navzájem
Pokud nakoupíte od dodavatele v jedné měně a odešlete v druhé měně, můžete pořád použít fakturaci nákupu.

Pokud vyrovnáte položku (položka 1) v jedné měně k položce (položka 2) v jiné měně, datum zaúčtování položky 1 se použije k nalezení příslušného směnného kurzu pro převod částek na položku 2. Příslušný směnný kurz naleznete v okně **Směnné kurzy**.

Vyrovnání položek dodavatele v různých měnách musí být povoleno. Pro další informace viz [Návody: Umožnit aplikaci položek v různých měnách](finance-setup-how-enable-application-ledger-entries-different-currencies.md)

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deník pojištění** a vyberte související odkaz.
2. Otevřete deník, který chcete, a vyplňte první prázdný řádek deníku pomocí kódu měny.
3. Zvolte akci **Použít položky**.
4. Vyberte řádek s položkou, pro kterou chcete použít položku v deníku plateb, vyberte akci **Nastavit ID vyrovnání** a pak vyberte položku, kterou chcete použít.
5. Zvolte tlačítko **OK** pro návrat do deníku plateb.
6. Zaúčtovat deník plateb.

**Důležité** : Při vyrovnání položek v různých měnách se položky přepočítají na USD. I když jsou směnné kurzy pro dvě příslušné měny pevně stanoveny, například mezi USD a EUR, mohou být tyto částky v cizí měně přepočteny na USD. Tyto malé zbytkové částky jsou účtovány jako zisky a ztráty na účtu uvedeném v poli **Účet realizovaných zisků zisků** nebo **Účet realizovaných ztrát** v okně **Měny**. Pole **Částka (USD)** je také nastavena podle příslušných položek dodavatele.

## <a name="to-unapply-an-application-of-vendor-entries"></a>Chcete-li zrušit vyrovnání položek dodavatele
Pokud zrušíte chybné vyrovnání, oprava položek, které jsou totožné s původní položkou, ale s opačným znaménkem v poli částky, jsou vytvořeny a zaúčtovány pro všechny položky včetně veškerého účtování hlavní knihy odvozené z vyrovnání jako jsou slevy na platbě a měnové zisky/ztráty. Položky, které byly uzavřeny vyrovnáním, jsou znovu otevřeny.

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.
2. Otevřete příslušnou kartu dodavatele.
3. Zvolte akci **Položky**.
4. Vyberte odpovídající položku a potom vyberte akci **Zrušit vyrovnání položek**.
5. Alternativně zvolte akci **Detailní položka**.
6. Vyberte položku vyrovnání a potom vyberte akci **Zrušit vyrovnání položek**.
7. Vyplňte pole v hlavičce a poté klepněte na tlačítko **Zrušit vyrovnání**.

**Důležité**: Pokud byla položka použita více než jednou položkou vyrovnání, musíte nejprve použít nejnovější položku vyrovnání.

## <a name="see-also"></a>Viz také
[Závazky](payables-manage-payables.md)  
[Správa nákupu](purchasing-manage-purchasing.md)

