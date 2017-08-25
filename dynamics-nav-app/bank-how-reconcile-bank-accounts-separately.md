---
title: "Návod: Odsouhlasení bankovních účtů zvlášť"
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
ms.openlocfilehash: 8b05bc9d09fa1e1a7a01eb4816ffba727611b776
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-bank-accounts-separately"></a>Návod: Odsouhlasení bankovních účtů zvlášť
Chcete-li odsouhlasit bankovní účty v systému Dynamics NAV s výpisy přijatými z banky, musíte vyplnit řádky v okně **Odsouhlasení bank. účtu**. 

**Poznámka**: Bankovní účty můžete také odsouhlasit v okně **Deník odsouhlasení plateb**. Veškeré položky bankovních účtů, které se vztahují k položkám účtů zákazníků nebo prodejců budou uzavřeny, když zvolíte akci **Zaúčtování plateb a odsouhlasení bankovních účtů**. To znamená, že bankovní účet je automaticky odsouhlasen pro platby, které zaúčtujete do deníku. Další informace naleznete v tématu [Návod: Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).

Chcete-li povolit import bankovních výpisů jako bankovních zdrojů, musíte nejprve nastavit a aktivovat službu Envestnet Yodlee Bank Feed a pak propojit své bankovní účty se souvisejícími online bankovními účty. Další informace naleznete v tématu [Návod: Nastavení služby Envestnet Yodlee Bank Feeds](bank-how-setup-bank-statement-service.md).

**Poznámka**: Služba Envestnet Yodlee Bank Feeds nebo jiná služba bankovního doručovatele nemusí být ve vašem systému k dispozici. Obraťte se na svého partnera Microsoft, chcete-li pro import bankovních výpisů použít bankovní službu.

Řádky v okně **Odsouhlasení bank. účtu** jsou rozděleny do dvou tabulek. V podokně **Řádky bankovního výpisu** se zobrazují buď importované bankovní transakce nebo položky knihy s nevyrovnanými platbami. V podokně **Položky bankovního účtu** se zobrazují záznamy položek na bankovním účtu.

Činnost zjišťování a používání položek, které mají být odsouhlaseny, se označuje jako *Shodný*. Můžete provést automatické přiřazování pomocí funkce **Shoda automaticky**. Případně můžete ručně vybrat řádky v obou panelech, abyste propojili každý řádek bankovního výpisu s jednou nebo více souvisejícími položkami knihy bankovních účtů a poté použijte funkci **Shoda ručně**. Zaškrtávací políčko **Použito** je vybráno na řádcích, kde se položky shodují. 

Můžete vyplnit podokno **Řádky bankovního výpisu** v okně **Odsouhlasení bank. účtu** následujícím způsobem:

* Automaticky funkce **Importovat výpis bankovního účtu** vyplní řádky podle skutečných bankovních výpisů na základě souboru poskytnutého bankou.
* Ručně pomocí funkce **Návrh řádků** zaplňte řádky s položkami knihy pro faktury, které mají nevyřízené platby.

Pokud se hodnota v poli **Celkový rozdíl** v podokně **Řádky bankovního výpisu** rovná hodnotě v poli **Saldo k odsouhlasení** v podokně **Položky bankovního účtu**, můžete zvolit akci **Účtovat** za účelem odsouhlasení položek bankovního účtu. Veškeré nepoužité položky knihy bankovních účtů zůstanou v okně, což znamená, že platby zpracované pro bankovní účet se nezobrazují v posledním bankovním výpisu nebo že některé platby byly obdrženy při kontrolách.

**Poznámka**: Pokud řádky bankovního výpisu odkazují na položky knihy, nemůžete použít odpovídající funkce. Namísto toho musíte vybrat akci **Použít položky** a poté vyberte příslušnou položku knihy, která odpovídá řádku bankovního výpisu.

## <a name="to-fill-bank-reconciliation-lines-by-importing-a-bank-statement"></a>Vyplnění řádků odsouhlasených bankou importováním bankovního výpisu  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Odsouhlasení bankovního účtu** a pak vyberte související odkaz.
2. Zvolte akci **Nový**.
3. V poli **Číslo bankovního účtu** vyberte relevantní bankovní účet. Položky bankovního účtu, které se na bankovním účtu vyskytují, se zobrazí v podokně **Položky bankovního účtu**.
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
Někdy bankovní výpis obsahuje částky za úroky nebo poplatky. Takové bankovní transakce nemohou být shodné, protože v Dynamics NAV neexistují žádné související položky knihy. Musíte zaúčtovat řádek deníku pro každou transakci a vytvořit příslušnou položku knihy, kterou lze porovnat.

1. V okně **Odsouhlasení bank. účtu** zvolte akci **Přenos do fin. deníku**.  
2. V okně **Přev.odsouhl.bank.účtu do fin.den.   ** zadejte, který finanční deník použijete a potom klepněte na tlačítko **OK**.

    V okně **Finanční deník** se otevřou nové řádky deníku pro všechny řádky bankovních výpisů s chybějícími položkami hlavní knihy.
3. Dokončete řádek deníku příslušnými informacemi, jako je vyrovnávací účet. Další informace naleznete v tématu [Práce s Finančním deníkem](ui-work-general-journals.md).  
4. Zvolte akci **Účtovat**.  
Po zaúčtování položky postupujte tak, aby bankovní transakce odpovídala.
5. Obnovte nebo znovu otevřete okno **Odsouhlasení bank. účtu**. Nová položka hlavní knihy se objeví v podokně **Položky bankovního účtu**.
6. Řádek bankovního výpisu porovnejte s položkou knihy bankovního účtu, a to ručně nebo automaticky.

## <a name="see-also"></a>Viz také  
[Správa bankovních účtů](bank-manage-bank-accounts.md)  
[Nastavení bankovnictví](bank-setup-banking.md)

