---
title: "Pozdržení výnosů a výdajů"
description: "Chcete-li rozpoznat výnos nebo výdaj v jiném období, než je období, ve kterém byla transakce zaúčtována, můžete použít funkci automatického pozdržení výnosů a výdajů přes stanovené specifikované schéma."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: postpone
ms.date: 06/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f06d241d07bc613bb54cc0a278de419fafffbb58
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-defer-revenues-and-expenses"></a>Návod: Pozdržení výnosů a výdajů
Chcete-li rozpoznat výnos nebo výdaj v jiném období, než je období, ve kterém byla transakce zaúčtována, můžete použít funkci automatického odložení výnosů a výdajů přes stanovené specifikované schéma.

K distribuci výdajů a výnosů na zahrnuté účtovací období nastavíte šablony odložení pro zdroj, zboží nebo finanční účet, na který bude výnos nebo výdaj zaúčtován. Když zaúčtujete související nákupní nebo prodejní doklad, výdaje nebo výnosy jsou odloženy k zahrnutí do účtovacích období podle šablony odložení, které se řídí nastavením v šabloně odložení a datem zaúčtování.

## <a name="to-set-up-a-gl-account-for-deferral"></a>Nastavení finančního účtu pro odložení
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účetní osnova** a pak vyberte související odkaz.
2. Vyberte akci **Nový**.
3. Vyplňte pole podle potřeby k vytvoření finančního účtu pro odložené výnosy. Další informace naleznete v tématu [Hlavní kniha a účetní osnova](finance-general-ledger.md).
4. Opakujte kroky 2 a 3 k vytvoření nového finančního účtu pro odložené výdaje.

Pro oba typy odložených vyberte **Rozvaha** v poli **Typ** a pojmenujte účty vhodně jako "Nezaplacený příjem“ pro odložené výnosy a "Nezaplacený výdaj“ pro odložené výdaje.

## <a name="to-set-up-a-deferral-template"></a>Nastavení šablony odložení
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Šablony odložení** a pak vyberte související odkaz.
2. Vyberte akci **Nový**.
3. Vyplňte pole dle potřeby.
4. V poli **Metoda výpočtu** specifikujte jak bude pole **Částka** pro každé období v okně **Šablona časového rozlišení** počítáno. Můžete si vybrat mezi následujícími možnostmi:

   * **Lineární**: Pravidelné odklady jsou počítány podle počtu období, distribuovány podle délky období.
   * **Stejně za období**: Pravidelné odklady jsou počítány podle počtu období, distribuovány rovnoměrně na období.
   * **Dny za období**: Pravidelné odklady jsou počítány podle počtu dní v období.
   * **Uživatelsky definovaná**: Pravidelné odklady nejsou počítány. Musíte manuálně vyplnit pole **Částka** pro každé období v okně Plán časového rozlišení. Další informace naleznete v tématu „Změna schématu odložení z prodejní faktury”.
5. V poli **Popis období** specifikujte popis, který se ukáže na položkách pro odložené zaúčtování. Můžete zadat následující zástupné symboly kódů pro typické hodnoty, které budou vyplněny automaticky, když je popis období zobrazen.

   * %1 = Počet dní období data zaúčtování
   * %2 = Počet týdnů období data zaúčtování
   * %3 = Počet měsíců období data zaúčtování
   * %4 = Název měsíce období data zaúčtování
   * %5 = Název měsíce období data zaúčtování
   * %6 = Fiskální rok období data zaúčtování

Příklad: Datum zaúčtování je 02/06/2016. Pokud zadáte “Výdaje odloženy na %4 %6”, pak zobrazený popis bude “Výdaje odloženy na Únor 2016”.

## <a name="to-assign-a-deferral-template-to-an-item"></a>Přiřazení šablony odložení k položce
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Šablony odložení** a pak vyberte související odkaz.
2. Otevřete kartu pro položku, pro kterou výnosy a výdaje musí být odloženy na období zaúčtování, kdy položka byla prodána nebo koupena.
3. V poli **Výchozí šablony časového rozlišení** vyberte relevantní šablonu odložení.

## <a name="to-change-a-deferral-schedule-from-a-sales-invoice"></a>Změna šablony odložení z prodejní smlouvy
> [!NOTE]  
>   Kroky v téhle proceduře jsou stejné jako, když měníte schéma odložení, pro výdaje z nákupní faktury.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní faktury** a pak vyberte související odkaz.
2. Vytvořte prodejní fakturu pro zboží, které má přiřazenou šablonu rozlišení. Další informace naleznete v tématu [Návod: Prodejní faktury](sales-how-invoice-sales.md).

    Všimněte si, že jakmile zadáte zboží (zdroje nebo finanční účet) na řádek faktury, pole **Kód časového rozlišení** je vyplněno kódem přiřazené šablony odložení.
3. Vyberte akci **Plán časového rozlišení**.
4. V okně **Schéma časového rozlišení** změňte nastavení v hlavičce nebo hodnotách na řádcích, např. k pozdržení částky na přídavné období účtování.
5. Vyberte akci **Plán časového rozlišení**.
6. Zvolte tlačítko **OK**. Plán odložení je aktualizován pro prodejní fakturu. Související šablona odložení je nezměněna.

## <a name="to-preview-how-deferred-revenues-or-expenses-will-be-posted-to-the-general-ledger"></a>Náhled, jak budou odložené výnosy nebo výdaje účtovány do hlavní knihy
> [!NOTE]  
>   Kroky v této proceduře jsou stejné jako náhled zaúčtování odložení výdajů.

1. V okně **Prodejní faktura** vyberte akci **Náhled zaúčtování**.
2. V okně **Náhled zaúčtování** vyberte akci **Položka financí** a zvolte akci **Zobrazit související položky**.

Položky financí k zaúčtování do specifikovaného účtu časového rozlišení, například  Nerozdělený příjem, jsou označeny popisem, který jste zadali v poli **Popis období** v šabloně odložení, například "Výdaje odložené na Únor 2016".

## <a name="to-review-posted-deferrals-in-the-sales-deferral-summary-report"></a>Revize zaúčtovaných odložení v sestavě prodeje souhrnu odložení
> [!NOTE]  
>   Kroky v této proceduře jsou stejné jako revize sestavy nákupu souhrnu odložení.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Přehled odloženého prodeje** a pak vyberte související odkaz.
2. V okně **Shrnutí časového rozlišení prodeje** v poli **Zůstatek k datu** zadejte datum, ke kterému chcete vidět odložené výnosy.
3. Zvolte tlačítko **OK**.

## <a name="see-also"></a>Viz také
[Finance](finance.md)  
[Nastavení financí](finance-setup-finance.md)  
[Práce s finančními deníky](ui-work-general-journals.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

