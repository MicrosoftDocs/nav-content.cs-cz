---
title: "Návod: Pozdržení výnosů a výdajů"
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
ms.openlocfilehash: 865bc307e8635b5a5aba11b5bc2e2e448c05e769
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-defer-revenues-and-expenses"></a>Návod: Pozdržení výnosů a výdajů
Chcete-li rozpoznat výnos nebo výdaj v jiném období, než je období, ve kterém byla transakce zaúčtována, můžete použít funkci automatického odložení výnosů a výdajů přes stanovené specifikované schéma.

K distribuci výdajů a výnosů na zahrnuté účtovací období nastavíte šablony odložení pro zdroj, zboží nebo finanční účet, na který bude výnos nebo výdaj zaúčtován. Když zaúčtujete související nákupní nebo prodejní doklad, výdaje nebo výnosy jsou odloženy k zahrnutí do účtovacích období podle šablony odložení, které se řídí nastavením v šabloně odložení a datem zaúčtování.

## <a name="to-set-up-a-gl-account-for-deferral"></a>Nastavení finančního účtu pro odložení
1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účetní osnova** a pak vyberte související odkaz.
2. Vyberte akci **Nové**.
3. Vyplňte pole podle potřeby k vytvoření finančního účtu pro odložené výnosy. Další informace naleznete v tématu [Hlavní kniha a účtová osnova](finance-setup-general-ledger.md).
3. Opakujte kroky 2 a 3 k vytvoření nového finančního účtu pro odložené výdaje.

Pro oba typy odložených vyberte **Rozvaha** v poli **Typ** a pojmenujte účty vhodně jako "Nezaplacený příjem“ pro odložené výnosy a "Nezaplacený výdaj“ pro odložené výdaje.

## <a name="to-set-up-a-deferral-template"></a>Nastavení šablony odložení
1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Šablony odložení** a pak vyberte související odkaz.
2. Vyberte akci **Nové**.
3. Vyplňte pole podle potřeby.
4. V poli **Způsob výpočtu** specifikujte jak bude pole **Částka** pro každé období v okně **Šablona odložení** počítáno. Můžete si vybrat mezi následujícími možnostmi:
    - **Lineární**: Pravidelné odklady jsou počítány podle počtu období, distribuovány podle délky období.
    - **Rovno za období**: Pravidelné odklady jsou počítány podle počtu období, distribuovány rovnoměrně na období.
    - **Dny za období**: Pravidelné odklady jsou počítány podle počtu dní v období.
    - **Definované uživatelem**: Pravidelné odklady nejsou počítány. Musíte manuálně vyplnit pole hodnoty pro každé období v okně Schéma odložení. Další informace naleznete v tématu „Změna schématu odložení z prodejní faktury”.

5. V poli **Období sestupně** specifikuj popis, který se ukáže na položkách pro odložené zaúčtování. Můžete zadat následující zástupné symboly kódů pro typické hodnoty, které budou vyplněny automaticky, když je popis období zobrazen.
    - %1 = Počet dní období data zaúčtování
    - %2 = Počet týdnů období data zaúčtování
    - %3 = Počet měsíců období data zaúčtování
    - %4 = Název měsíce období data zaúčtování
    - %5 = Název měsíce období data zaúčtování
    - %6 = Fiskální rok období data zaúčtování

Příklad: Datum zaúčtování je 02/06/2016. Pokud zadáte “Výdaje odloženy na %4 %6”, pak zobrazený popis bude “Výdaje odloženy na Únor 2016”

## <a name="to-assign-a-deferral-template-to-an-item"></a>Přiřadit šablonu odložení k položce
1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Šablony odložení**, a pak vyberte související odkaz.
2. Otevřete kartu pro položku, pro kterou výnosy a výdaje musí být odloženy na období zaúčtování, kdy položka byla prodána nebo koupena.
3. V poli **Výchozí šablony odložení** vyberte relevantní šablonu odložení.

## <a name="to-change-a-deferral-schedule-from-a-sales-invoice"></a>Změna šablony odložení z prodejní smlouvy
**Poznámka**: Kroky v téhle proceduře jsou stejné jako, když měníte schéma odložení, pro výdaje, z nákupní faktury.

1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Prodejní faktura**, a pak vyberte související odkaz.
2. Vytvořte prodejní fakturu pro zboží, které má přiřazenou šablonu odložení. Další informace naleznete v tématu [Návod: Prodejní faktury](sales-how-invoice-sales.md).

    Všimněte si, že jakmile zadáte zboží (zdroje nebo finanční účet) na řádek faktury, pole **Odkladový kód** je vyplněno kódem přiřazené šablony odložení.
3. Vyberte akci **Schéma odložení**.
4. V okně **Schéma odložení**, změňte nastavení v hlavičce nebo hodnotách na řádcích, např. k pozdržení částky na přídavné období účtování.
5. Vyberte akci **Vypočítat schéma**.
6. Vyberte tlačítko **OK**. Plán odložení je aktualizován pro prodejní fakturu. Související šablona odložení je nezměněna.

## <a name="to-preview-how-deferred-revenues-or-expenses-will-be-posted-to-the-general-ledger"></a>Náhled, jak budou odložené výnosy nebo výdaje účtovány do hlavní knihy
**Poznámka**: Kroky v této proceduře jsou stejné jako náhled zaúčtování odložení výdajů.

1. V okně **Prodejní faktura** vyberte akci **Náhled zaúčtování**.
2. V okně **Náhled zaúčtování** vyberte akci **Položka financí** a zvolte akci **Zobrazit související položky**.

Položky financí k zaúčtování do specifikovaného účtu odložení, například  Nerozdělený příjem, jsou označeny popisem, který jste zadali v poli ** Období sestupně** v šabloně odložení, například "Výdaje odložené na Únor 2016".

## <a name="to-review-posted-deferrals-in-the-sales-deferral-summary-report"></a>K revizi zaúčtovaných odložení v sestavě prodeje souhrnu odložení
**Poznámka**: Kroky v této proceduře jsou stejné jako revize sestavy nákupu souhrnu odložení.

1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Shrnutí odložených prodejů** a pak vyberte související odkaz.
2. V okně **Shrnutí odložených prodejů**, v poli **Zůstatek k datu** zadejte datum, ke kterému chcete vidět odložené výnosy.
3. Vyberte tlačítko **Náhled**.

## <a name="see-also"></a>Viz také
[Finance](finance-setup.md)  
[Nastavení jaderných finanční procesy](finance-setup-setup-finance-setup.md)  
[Návod: Práce s hlavními deníky](ui-work-general-journals.md)

