---
title: "Návod: Odsouhlasení plateb zákazníků ručně"
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
ms.openlocfilehash: de0c94386ad5a0bbfba5cc0516fa7faa5cdcc0b4
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-customer-payments-manually"></a>Návod: Odsouhlasení plateb zákazníků ručně
Když obdržíte od zákazníka doklad o hotovosti nebo provedete vrácení peněz zákazníkovi, musíte se rozhodnout, zda chcete platbu vyrovnat nebo vrátit zpět na jednu nebo více otevřených položek MD nebo Dal. Můžete určit přesnou částku, kterou chcete vyrovnat. Můžete například vyrovnat pouze část platby a tím jen částečně zaúčtovat položky v knize zákazníků. V určitém okamžiku je důležité zavřít (vyrovnat) všechny záznamy zákazníků, abyste získali správné statistiky zákazníků a vytištěné výpisy z účtu a poplatky za nastavení financí.

Položky v knize zákazníků můžete vyrovnat třemi způsoby:

- Zadáním informací do vyhrazených oken, jako je například okno **Deník přijaté hotovosti** a okno **Deník odsouhlasení plateb**.
- Z dokladů prodejních dobropisů.
- Položky z knihy zákazníků po prodejních dokladech se zaúčtují, ale nejsou vyrovnány.

**Poznámka**: Pokud pole **Metoda vyrovnání** na kartě zákazníka obsahuje **Vyrovnat nejstarší**, pak budou platby automaticky vyrovnány na nejstarší otevřenou položku Dal, pokud ručně neurčíte, ke které položce se mají vyrovnat. Pokud je metoda vyrovnání pro zákazníka **Ruční**, musíte položky vyrovnat ručně.

Můžete vyrovnat platby zákazníků ručně v okně **Deník přijaté hotovosti**. Deník přijaté hotovosti je typ hlavní knihy, takže jej můžete použít k zaúčtování transakcí do hlavní knihy, bank, zákazníků, prodejců a účtů dlouhodobého majetku. Platbu můžete vyrovnat na jednu nebo více položek MD, když zaúčtujete platbu nebo je můžete vyrovnat ze zaúčtovaných položek později.

Můžete také vyrovnat platby zákazníků a platby dodavatelů v okně **Deník odsouhlasení plateb** pomocí funkcí pro import bankovních výpisů, automatické vyrovnání a odsouhlasení bankovních účtů. Další informace naleznete v tématu [Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md). Případně můžete odsouhlasit platby zákazníků na základě seznamu nezaplacených prodejních dokladů v okně **Registrace plateb**. Další informace naleznete v tématu [Návod: Odsouhlasení plateb zákazníků ze seznamu nezaplacených prodejních dokladů](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md).

## <a name="to-fill-and-post-a-cash-receipt-journal"></a>Vyplnění a zaúčtování deníku přijaté hotovosti
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deník přijaté hotovosti** a pak vyberte související odkaz.
2. Zvolte příslušnou dávku v poli **Název dávky**.
3. Vyplňte pole **Zúčtovací datum**.  
4. Do pole **Typ dokladu** vyberte **Platba**.

    Pole **Číslo dokladu** je vyplněno číselnými řadami přiřazenými dávce.
5. Použijte pole **Číslo externího dokladu** pro uložení identifikátoru, jako je číslo zákazníka.
6. V poli **Typ účtu** vyberte **Zákazník**.
7. V poli **Číslo účtu** vyberte relevantní finanční účet.
8. Chcete-li zaúčtovat vyrovnání současně se zaúčtováním deníku, proveďte jeden z následujících úkonů.
9. V poli **Typ protiúčtu** vyberte **Finanční účet** pro platbu v hotovosti a **Bankovní účet** pro ostatní platby.
10. V poli **Číslo bankovního účtu** zadejte hotovostní účet pro hotovostní platby nebo příslušný bankovní účet pro jiné platby.
11. Zaúčtujte deník.

## <a name="to-apply-a-payment-to-a-single-customer-ledger-entry"></a>Vyrovnání platby na jednu položku knihy zákazníka
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deník přijaté hotovosti** a vyberte související odkaz.
2. Na prvním řádku deníku zadejte příslušné informace o položce, která má být vyrovnána.
3. Do pole **Typ dokumentu** zadejte **Platba**.
4. V poli **Typ účtu** vyberte **Zákazník**.
5. V poli **Typ protiúčtu **vyberte **Bankovní účet**.
6. V poli **Číslo vyrovnání dokladu vyberte pole** k otevření okna **Položky vyrovnání zákazníka**.
7. V okně **Vyrovnat položky zákazníka** vyberte položku, na kterou chcete platbu vyrovnat.
8. Do pole **Částka k vyrovnání** zadejte částku, kterou chcete vyrovnat pro položku. Pokud nezadáte částku, vyrovná se maximum částky.

    V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka** a také zda se vyrovná zůstatek.
9. Zvolte tlačítko **OK**. Okno **Deník přijaté hotovosti** nyní zobrazuje položku, kterou jste vybrali,** zadanou v** Polích Typ vyrovnání dokladu**** a **Číslo vyrovnání dokladu**.
10. Zaúčtujte deník přijaté hotovosti.

## <a name="to-apply-a-payment-to-multiple-customer-ledger-entries"></a>Vyrovnání platby pro více položek knihy zákazníka
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deník přijaté hotovosti** a vyberte související odkaz.
2. Na prvním řádku deníku zadejte příslušné informace o položce, která má být vyrovnána.
3. Do pole **Typ dokumentu** zadejte **Platba**.
4. V poli **Typ účtu** vyberte **Zákazník**.
5. V poli **Typ protiúčtu **vyberte **Bankovní účet**.
6. Do pole **Částka** zadejte úplnou platbu jako zápornou částku.
7. Chcete-li platbu zaúčtovat na více položek knihy zákazníka, zvolte akci **Vyrovnat položky**.
8. Vyberte řádek s položkami, které chcete vyrovnat a potom vyberte akci **Nastavit ID vyrovnání**.
9. Na každém řádku v poli **Částka k vyrovnání** zadejte částku, pro kterou chcete vyrovnat jednotlivé položky. Pokud nezadáte částku, vyrovná se maximum částky.

    V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka** a také zda se vyrovná zůstatek.
10. Zvolte tlačítko **OK**.
11. Zaúčtujte deník přijaté hotovosti.

## <a name="to-apply-a-credit-memo-to-a-single-customer-ledger-entry"></a>Použití dobropisů k položce knihy jednoho zákazníka
1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Prodejní dobropisy** a pak vyberte související odkaz.
2. Otevřete relevantní prodejní dobropis.
3. Chcete-li vyrovnat dobropis pro položku knihy jednoho zákazníka při zaúčtování, v poli **Číslo vyrovnání dokladu ** vyberte položku, na kterou chcete vyrovnat platbu.
4. Na řádku v poli **Částka k vyrovnání** zadejte částku, kterou chcete vyrovnat pro položku.

    Pokud nezadáte částku, program automaticky použije maximum částky. V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka** a také zda se vyrovná zůstatek.
5. Zvolte tlačítko **OK**. Okno **Prodejní dobropisy** nyní zobrazuje položku, kterou jste vybrali,** zadanou** v polích Typ vyrovnání dokladu**** a **Číslo vyrovnání dokladu**. a částka dobropisu k zaúčtování je upravená o případné slevy na platbu.
6. Zaúčtujte dobropis.

## <a name="to-apply-a-credit-memo-to-multiple-customer-ledger-entries"></a>Vyrovnání dobropisu na více položek knihy zákazníka
1. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Prodejní dobropisy** a pak vyberte související odkaz.
2. Otevřete relevantní prodejní dobropis.
3. Chcete-li vyrovnat dobropis pro více položek knihy zákazníka při zaúčtování, zvolte akci **Vyrovnání položek**.
4. Vyberte řádek s položkami, které chcete vyrovnat a potom vyberte akci **Nastavit ID vyrovnání**.
5. Na každém řádku v poli **Částka k vyrovnání** zadejte částku, pro kterou chcete vyrovnat jednotlivé položky. Pokud nezadáte částku, vyrovná se maximum částky.

  V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka** a také zda se vyrovná zůstatek.
6. Zvolte tlačítko **OK**. Okno **Prodejní dobropisy** nyní zobrazuje částku dobropisu k zaúčtování upravenou o případné slevy.
7. Zaúčtujte dobropis.

## <a name="to-apply-posted-customer-ledger-entries"></a>Vyrovnání zaúčtovaných položek knihy zákazníka
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zákazníci** a zvolte související odkaz.
2. Otevřete kartu zákazníka pro zákazníka s položkami, které chcete vyrovnat.
3. Zvolte akci **Položky knihy** a potom vyberte řádek s položkou, která bude vyrovnána.
4. Zvolte akci **Vyrovnat položky**. Otevře se okno **Vyrovnání položek zákazníka**, které zobrazuje otevřené položky pro zákazníka.
5. Zvolte řádky s položkami, které chcete použít pro vyrovnání a pak vyberte akci **Nastavení vyrovnání k ID**. action.
6. U každého řádku v poli **Částka k vyrovnání** zadejte částku, kterou chcete vyrovnat pro jednotlivé položky. Pokud nezadáte částku, vyrovná se maximum částky.

    V dolní části okna **Vyrovnat položky zákazníka** můžete vidět konkrétní částku v poli **Vyrovnaná částka**.
7. Zvolte akci **Účtovat vyrovnání**. Zobrazí se okno **Účtovat vyrovnání** s číslem dokumentu vyrovnávací položky a účtovacím datem položky s posledním datem účtování.  
8. Zvolte tlačítko **OK** pro účtování vyrovnání.

    Pokud účtování vyrovnání vedlo k uzavření položek knihy zákazníka, pole **Otevřít** je čisté pro tyto položky knihy.
9. Chcete-li zobrazit položky knihy, v pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zákazníci** a pak vyberte související odkaz. Prohlédněte si kartu pro příslušného zákazníka, abyste mohli vidět položky knihy.

V seznamu položky knihy na řádku, který obsahuje položka knihy, která byla plně vyrovnána, můžeme vidět, že není zaškrtnuto políčko **Otevřít**.  

**Poznámka**: Poté, co jste vybrali položku z okna **Vyrovnat položky zákazníka** nebo více položek nastavením **ID vyrovnání** bude pole **Vyrovnaná částka** na řádku deníku obsahovat součet zbývajících částek pro účtované položky, které jste vybrali, neobsahuje-li již pole něco. Pokud zvolíte **Vyrovnat nejstarší** v poli **Metody vyrovnání** na kartě zákazníka, vyrovnání se automaticky spustí.

## <a name="to-apply-customer-ledger-entries-in-different-currencies-to-one-another"></a>Vyrovnání položek knihy zákazníka v různých měnách
Když prodáte zákazníkovi v jedné měně a obdržíte platbu v druhé měně, můžete stále vyrovnat platbu na faktuře.

Pokud vyrovnáte položku (položka 1) v jedné měně na položku (položka 2) v jiné měně, datum účtování v položce 1 se použije k nalezení příslušného směnného kurzu pro převod částek na položku 2. Příslušný směnný kurz naleznete v okně **Směnné kurzy**.

Vyrovnání položek knihy zákazníka v různých měnách musí být povolena. Další informace naleznete v tématu [Návod: Povolení vyrovnání položek knihy v různých měnách](finance-setup-how-enable-application-ledger-entries-different-currencies.md).

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deník přijaté hotovosti** a vyberte související odkaz.
2. Otevřete deník, který chcete a vyplňte první prázdný řádek deníku pomocí kódu měny.
3. Zvolte akci **Vyrovnat položky**.
4. Vyberte řádek s položkou, kterou chcete použít pro položku v deníku přijaté hotovosti, zvolte akci **Nastavit ID vyrovnání** a vyberte položku, kterou chcete vyrovnat.
5. Klepnutím na tlačítko **OK** se vrátíte do deníku přijaté hotovosti.
6. Zaúčtujte deník prodeje.

**Důležité**: Při použití položek v různých měnách se položky přepočítají na USD. I když jsou směnné kurzy pro dvě příslušné měny pevně stanoveny, například mezi USD a EUR, mohou být tyto částky v cizí měně přepočteny na USD. Tyto malé zbytkové částky jsou účtovány jako zisky a ztráty na účtu uvedeném v poli **Účet realizovaných zisků** nebo **Účet realizovaných ztrát** v okně **Měny**. Pole **Částka (USD)** je také nastavena na příslušných položkách knihy dodavatelů.

## <a name="to-unapply-an-application-of-customer-entries"></a>Nevyrovnání položek zákazníka
Pokud nevyrovnáte chybné vyrovnání, opravené položky které jsou totožné s původní položkou, ale s opačným znaménkem v poli částka a jsou vytvořeny a účtovány pro všechny položky včetně veškerého účtování hlavní knihy odvozené z vyrovnání, jako jsou slevy a zisky/ztráty měn. Položky, které byly uzavřeny vyrovnáním, jsou znovu otevřeny.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zákazníci** a zvolte související odkaz.
2. Otevřete příslušnou zákaznickou kartu.
3. Zvolte akci **Položky knihy**.
4. Vyberte příslušné položky knihy a poté zvolte akci **Zrušit vyrovnání položek**.
5. Alternativně zvolte akci **Detailní položky knihy**.
6. Vyberte položky vyrovnání a potom vyberte akci **Zrušit vyrovnání položek**.
7. Vyplňte pole v hlavičce a poté klepněte na tlačítko **Zrušit vyrovnání**.

**Důležité** : Pokud byla položka vyrovnána více než jednou, musíte nejprve zrušit vyrovnání nejnovější položky.

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Správa prodeje](sales-manage-sales.md)

