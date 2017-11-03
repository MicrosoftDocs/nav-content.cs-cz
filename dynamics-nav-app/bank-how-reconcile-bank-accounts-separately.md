---
title: "Odsouhlasení bankovních účtů zvlášť"
description: "Popisuje jak je vaše inventární hodnota v souladu s hlavní knihou."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bank account balance, bank statement
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 9742569e97f8b2ad5546b364d76edb702f1a0c1c
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-reconcile-bank-accounts-separately"></a>Návod: Odsouhlasení bankovních účtů zvlášť
Chcete-li odsouhlasit bankovní účty v [!INCLUDE[d365fin](includes/d365fin_md.md)] s výpisy přijatými z banky, musíte vyplnit řádky v okně **Odsouhlasení bank. účtu**.

> [!NOTE]  
>   Bankovní účty můžete také odsouhlasit v okně **Deník odsouhlasení plateb**. Veškeré položky bankovních účtů, které se vztahují k položkám účtů zákazníků nebo dodavatelů budou uzavřeny, když zvolíte akci **Zaúčtování plateb a odsouhlasení bankovních účtů**. To znamená, že bankovní účet je automaticky odsouhlasen pro platby, které zaúčtujete do deníku. Další informace naleznete v tématu [Návod: Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).

Chcete-li povolit import bankovních výpisů jako bankovních zdrojů, musíte nejprve nastavit a aktivovat službu převodu bankovních dat. Další informace naleznete v tématu [Návod: Nastavení služby převodu bankovních dat](bank-how-setup-bank-data-conversion-service.md).

Řádky v okně **Odsouhlasení bank. účtu** jsou rozděleny do dvou tabulek. V podokně **Řádky bankovního výpisu** se zobrazují buď importované bankovní transakce nebo položky knihy s nevyrovnanými platbami. V podokně **Položky bankovního účtu** se zobrazují záznamy položek na bankovním účtu.

Činnost zjišťování a používání položek, které mají být odsouhlaseny, se označuje jako *Shodný*. Můžete provést automatické přiřazování pomocí funkce **Shoda automaticky**. Případně můžete ručně vybrat řádky v obou panelech, abyste propojili každý řádek bankovního výpisu s jednou nebo více souvisejícími položkami knihy bankovních účtů a poté použijte funkci **Shoda ručně**. Zaškrtávací políčko **Použito** je vybráno na řádcích, kde se položky shodují.

Můžete vyplnit podokno **Řádky bankovního výpisu** v okně **Odsouhlasení bank. účtu** následujícím způsobem:

* Automaticky pomocí funkce **Importovat výpis bankovního účtu** vyplní řádky podle skutečných bankovních výpisů na základě souboru poskytnutého bankou.
* Ručně pomocí funkce **Návrh řádků** vyplňte řádky s položkami knihy pro faktury, které mají nevyřízené platby.

Pokud se hodnota v poli **Celkový rozdíl** v podokně **Řádky bankovního výpisu** rovná hodnotě v poli **Saldo k odsouhlasení** v podokně **Položky bankovního účtu**, můžete zvolit akci **Účtovat** za účelem odsouhlasení položek bankovního účtu. Veškeré nepoužité položky knihy bankovních účtů zůstanou v okně, což znamená, že platby zpracované pro bankovní účet se nezobrazují v posledním bankovním výpisu nebo, že některé platby byly obdrženy při kontrolách.

> [!NOTE]  
>   Pokud řádky bankovního výpisu odkazují na položky knihy, nemůžete použít odpovídající funkce. Namísto toho musíte vybrat akci **Použít položky** a poté vyberte příslušnou položku knihy, která odpovídá řádku bankovního výpisu.

## <a name="to-fill-bank-reconciliation-lines-by-importing-a-bank-statement"></a>Vyplnění řádků odsouhlasených bankou importováním bankovního výpisu
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Požadavky ke schválení** a pak vyberte související odkaz.
2. Vyberte akci **Nový**.
3. V poli **Číslo bankovního účtu** vyberte relevantní bankovní účet.  Položky bankovního účtu, které se na bankovním účtu vyskytují, se zobrazí v podokně **Položky bankovního účtu**.
4. Do pole **Datum výpisu** zadejte datum výpisu z banky.
5. Do pole **Saldo posledního výpisu** zadejte zůstatek výpisu z banky.
6. Pokud máte soubor s bankovním výpisem, zvolte akci **Import výpisu bankovního účtu**.
7. Vyhledejte soubor a poté zvolte tlačítko **Otevřít**, chcete-li importovat bankovní transakce do řádků v okně **Odsouhlasení bank. účtu**.

## <a name="to-fill-bank-reconciliation-lines-with-the-suggest-lines-function"></a>Vyplnění řádků odsouhlasených bankou pomocí funkce Návrh řádků
1. V okně **Odsouhlasení bank. účtu** zvolte akci **Návrh řádků**.
2. Do pole **Počáteční datum** zadejte nejdřívější datum zaúčtování položek knihy, které chcete odsouhlasit.
3. Do pole **Konečné datum** zadejte nejpozdější datum zaúčtování položek knihy, které chcete odsouhlasit.
4. Zaškrtněte políčko **Včetně šeků** na všechny doporučené položky knihy namísto odpovídajících položek knih bankovních účtů.
5. Zvolte tlačítko **OK**.

## <a name="to-match-bank-statement-lines-with-bank-account-ledger-entries-automatically"></a>Automatická shoda řádků bankovních výpisů s položkami bankovních účtů
1. V okně **Odsouhlasení bank. účtu** zvolte **Shoda automaticky**. Otevře se okno **Shoda bankovních položek**.
2. Do pole **Transakce datumu tolerance (dny)** zadejte rozmezí dnů před a po datumu účtování záznamu bankovního účtu, v rámci kterého funkce vyhledá odpovídající data transakce v bankovním výpisu.

    Pokud zadáte hodnotu 0 nebo ponecháte pole prázdné, funkce **Shoda automaticky** vyhledá pouze odpovídající data transakce v datu zaúčtování položek knihy bankovního účtu.
3. Zvolte tlačítko **OK**.

    Všechny řádky bankovního výpisu a položky bankovních účtů, které lze porovnat, se změní na zelené písmo a zaškrtne se políčko **Použito**.
4. Chcete-li odstranit shodu, vyberte řádek výpisu banky a potom zvolte akci **Odebrat shodu**.

## <a name="to-match-bank-statement-lines-with-bank-account-ledger-entries-manually"></a>Ruční shoda řádků bankovních účtů s položkami knihy bankovního účtu
1. V okně **Odsouhlasení bank. účtu** vyberte nepoužité řádky v podokně **Řádky bankovního výpisu**.
2. V podokně **Položky bankovního účtu** vyberte jednu nebo více položek v knize bankovních účtů, které lze porovnat s vybraným řádkem výpisu banky. Chcete-li vybrat více řádků, stiskněte a podržte klávesu Ctrl.
3. Zvolte akci **Shoda ručně**.

    Vybraný řádek bankovního výpisu a vybrané položky knihy bankovního účtu se změní na zelené písmo a zaškrtne se políčko **Použito** v pravém podokně.
4. Opakujte kroky 1 až 3 pro všechny řádky bankovního výpisu, které nejsou shodné.
5. Chcete-li odstranit shodu, vyberte řádek výpisu banky a potom zvolte akci **Odebrat shodu**.

## <a name="to-create-missing-ledger-entries-to-match-bank-transactions-with"></a>Vytvoření chybějící položky knihy tak, aby odpovídaly bankovním transakcím
Někdy bankovní výpis obsahuje částky za úroky nebo poplatky. Takové bankovní transakce nemohou být shodné, protože neexistují žádné související položky knihy v [!INCLUDE[d365fin](includes/d365fin_md.md)]. Musíte zaúčtovat řádek deníku pro každou transakci a vytvořit příslušnou položku knihy, kterou lze porovnat.

1. V okně **Odsouhlasení bank. účtu** zvolte akci **Přenos do fin. deníku**.  
2. V okně **Přev. odsouhl.bank.účtu do fin.den** specifikujte finanční deník k použití a zvolte tlačítko **OK**.  

    V okně **Finanční deník** se otevřou nové řádky deníku pro všechny řádky bankovních výpisů s chybějícími položkami hlavní knihy.
3. Dokončete řádek deníku příslušnými informacemi, jako je vyrovnávací účet. Pro další informace se podívejte na [Práce s finančními deníky](ui-work-general-journals.md).  
4. Zvolte akci **Účtovat**.

    Po zaúčtování položky postupujte tak, aby bankovní transakce odpovídala.
5. Obnovte nebo znovu otevřete okno **Odsouhlasení bank. účtu**. Nová položka hlavní knihy se objeví v podokně **Položky bankovního účtu**.
6. Řádek bankovního výpisu porovnejte s položkou knihy bankovního účtu, a to ručně nebo automaticky.

## <a name="see-also"></a>Viz také
[Správa bankovních účtů](bank-manage-bank-accounts.md)  
[Nastavení bankovnictví](bank-setup-banking.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

