---
title: "Vyřazení nebo odebrání dlouhodobého majetku"
description: "Musíte zaúčtovat vyřazovací hodnotu při vyřazování, prodeji nebo odebrání dlouhodobého majetku."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: scrap
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f6e90150a2fd14be13746dcbc91a6fca82d39738
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-dispose-of-or-retire-fixed-assets"></a>Návod: Vyřazení (z provozu) nebo odebrání dlouhodobého majetku
Při prodeji nebo jiném vyřazování DM musí být hodnota vyřazení zaúčtována k výpočtu a zaznamenání zisku nebo ztrát. Vyřazená položka musí být poslední položkou zaúčtovanou pro dlouhodobý majetek. Pro částečné vyřazení DM můžete zaúčtovat více než jednu vyřazenou položku. Všechny zaúčtované částky musí činit částku Dal.  

> [!NOTE]  
>   Pokud obchodujete s dlouhodobým majetkem musíte zaznamenat, jak prodej starého majetku (vyřazení) tak i nákup nového (pořízení). Další informace naleznete v tématu [Návod: Pořízení DM](fa-how-acquire.md).  

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a>Zaúčtování vyřazeného DM z finančního deníku
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.  
2. Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
3. V poli **Typ účtování DM** vyberte **Vyřazení**.  
4. Zvolte možnost **Vložit protiúčet DM**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování vyřazeného.  

    > [!NOTE]  
>   Krok 4 funguje pouze v případě, že jste nastavili následující: V okně **Karta účto skupiny DM** pro zaúčtování skupin DM, pole **Účet vyřazení** obsahuje účet MD hlavní knihy a pole **Odpisový protiúčet** při vyřazení obsahuje účet hlavní knihy, na který chcete zaúčtovat zůstatkové položky za účelem zhodnocení. Další informace naleznete v tématu "Nastavení skupin zaúčtování DM“ [Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).  
5. Zvolte akci **Zaúčtovat**.  

    Pokud chcete prodat nebo vyřadit část DM, musíte rozdělit majetek před tím, než zaznamenáte transakci vyřazení. Další informace naleznete v tématu [Návod: Převod, rozdělení nebo kombinace DM](fa-how-trans-split-combine.md).  

## <a name="to-view-disposal-ledger-entries"></a>Zobrazení vyřazených položek z knihy
Při prodeji nebo vyřazení DM je hodnota vyřazení zaúčtována do hlavní knihy, kde můžete zobrazit výsledek.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.  
2. Vyberte dlouhodobý majetek, u kterého chcete zobrazit položky a pak vyberte akci **Kniha odpisů**.  
3. Vyberte odpisovou knihu, kde chcete zobrazit položky a poté vyberte akci **Položky**.  
4. Vyberte řádek s **Vyřazení** v poli **Kategorie účtování DM** a pak zvolte akci **Navigovat**.  
5. V okně **Navigace** vyberte řádky položky hlavní knihy a pak zvolte akci **Ukázat**.  

Okno **Věcné položky** se otevře tam, kde můžete vidět položky, které vedly k vyřazení.  

## <a name="see-also"></a>Viz také
[Dlouhodobý majetek](fa-manage.md)  
[Nastavení dlouhodobého majetku](fa-setup.md)  
[Finance](finance.md)  
[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

