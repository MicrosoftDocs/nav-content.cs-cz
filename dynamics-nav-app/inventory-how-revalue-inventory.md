---
title: "Vytvoření nové hodnoty položek pro zboží v zásobách"
description: "Popisuje, jak ocenit nebo odepsat hodnoty položek jednoho nebo více zboží v zásobách zaúčtováním jejich aktuální vypočtené hodnoty."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: costing, inventory cost, value entries
ms.date: 08/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5bc7e72a44f002e42ad9b3d37c9eab6cd512eff3
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-revalue-inventory"></a>Návod: Přecenění zásob
Chcete-li ocenit nebo odepsat zboží nebo položku, musíte použít deník přecenění.

## <a name="to-revalue-inventory"></a>Přecenění zásob
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deník přecenění** a pak vyberte související odkaz.
2. Vyberte akci **Vypočítat hodnotu zásob**.
3. V okně **Vypočítat hodnotu zásob** vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Zvolte tlačítko **OK**.
5. Na každém řádku v okně **Deník přecenění** v poli **Pořizovací cena (přeceněná)** zadejte novou pořizovací cenu. Případně zadejte novou celkovou částku do pole **Hodnota zásob (přeceněná)**.

    Příslušná pole jsou automaticky aktualizována. Všimněte si, že pole **Částka** zobrazuje skutečnou změnu hodnoty zásob pro vybranou položku zboží. Vypočítá rozdíl mezi polem **Hodnota zásob (vypočtená)** a **Hodnota zásob (přeceněná)**.
6. Jakmile dokončíte všechny řádky v deníku přecenění, vyberte akci **Účtovat**.

Nové položky přecenění jsou nyní vytvořeny tak, aby odrážely přecenění, která jste zaúčtovali. Nové hodnoty můžete vidět na příslušných kartách zboží.

## <a name="see-also"></a>Viz také
[Detaily návrhu: Přecenění](design-details-revaluation.md)  
[Sklady](inventory-manage-inventory.md)  
[Prodej](sales-manage-sales.md)  
[Nákup](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

