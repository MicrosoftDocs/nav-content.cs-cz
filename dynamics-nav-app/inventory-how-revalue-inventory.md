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
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: f945b13f87dfbab07d4df59a43dd4daf26ff9cb0
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-revalue-inventory"></a><span data-ttu-id="673a8-103">Návod: Přecenění zásob</span><span class="sxs-lookup"><span data-stu-id="673a8-103">How to: Revalue Inventory</span></span>
<span data-ttu-id="673a8-104">Chcete-li ocenit nebo odepsat zboží nebo položku, musíte použít deník přecenění.</span><span class="sxs-lookup"><span data-stu-id="673a8-104">If you want to appreciate or depreciate an item or a specific item ledger entry, you must use the revaluation journal.</span></span>

## <a name="to-revalue-inventory"></a><span data-ttu-id="673a8-105">Přecenění zásob</span><span class="sxs-lookup"><span data-stu-id="673a8-105">To revalue inventory</span></span>
1. <span data-ttu-id="673a8-106">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deník přecenění** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="673a8-106">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Revaluation Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="673a8-107">Vyberte akci **Vypočítat hodnotu zásob**.</span><span class="sxs-lookup"><span data-stu-id="673a8-107">Choose the **Calculate Inventory Value** action.</span></span>
3. <span data-ttu-id="673a8-108">V okně **Vypočítat hodnotu zásob** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="673a8-108">In the **Calculate Inventory Value** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. <span data-ttu-id="673a8-109">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="673a8-109">Choose the **OK** button.</span></span>
5. <span data-ttu-id="673a8-110">Na každém řádku v okně **Deník přecenění** v poli **Pořizovací cena (přeceněná)** zadejte novou pořizovací cenu.</span><span class="sxs-lookup"><span data-stu-id="673a8-110">On each line in the **Revaluation Journal** window, in the **Unit Cost (Revalued)** field, enter the new unit cost.</span></span> <span data-ttu-id="673a8-111">Případně zadejte novou celkovou částku do pole **Hodnota zásob (přeceněná)**.</span><span class="sxs-lookup"><span data-stu-id="673a8-111">Alternatively, enter the new total amount in the **Inventory Value (Revalued)** field.</span></span>

    <span data-ttu-id="673a8-112">Příslušná pole jsou automaticky aktualizována.</span><span class="sxs-lookup"><span data-stu-id="673a8-112">The relevant fields are automatically updated.</span></span> <span data-ttu-id="673a8-113">Všimněte si, že pole **Částka** zobrazuje skutečnou změnu hodnoty zásob pro vybranou položku zboží.</span><span class="sxs-lookup"><span data-stu-id="673a8-113">Note that the **Amount** field shows the actual change in inventory value for the selected item ledger entry.</span></span> <span data-ttu-id="673a8-114">Vypočítá rozdíl mezi polem **Hodnota zásob (vypočtená)** a **Hodnota zásob (přeceněná)**.</span><span class="sxs-lookup"><span data-stu-id="673a8-114">It calculates the difference between the **Inventory Value (Calculated)** field and the **Inventory Value (Revalued)** field.</span></span>
6. <span data-ttu-id="673a8-115">Jakmile dokončíte všechny řádky v deníku přecenění, vyberte akci **Účtovat**.</span><span class="sxs-lookup"><span data-stu-id="673a8-115">When you have completed all lines in the revaluation journal, choose the **Post** action.</span></span>

<span data-ttu-id="673a8-116">Nové položky přecenění jsou nyní vytvořeny tak, aby odrážely přecenění, která jste zaúčtovali.</span><span class="sxs-lookup"><span data-stu-id="673a8-116">New value entries are now created to reflect the revaluations that you have posted.</span></span> <span data-ttu-id="673a8-117">Nové hodnoty můžete vidět na příslušných kartách zboží.</span><span class="sxs-lookup"><span data-stu-id="673a8-117">You can see the new values on the respective item cards.</span></span>

## <a name="see-also"></a><span data-ttu-id="673a8-118">Viz také</span><span class="sxs-lookup"><span data-stu-id="673a8-118">See Also</span></span>
[<span data-ttu-id="673a8-119">Detaily návrhu: Přecenění</span><span class="sxs-lookup"><span data-stu-id="673a8-119">Design Details: Revaluation</span></span>](design-details-revaluation.md)  
[<span data-ttu-id="673a8-120">Sklady</span><span class="sxs-lookup"><span data-stu-id="673a8-120">Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="673a8-121">Prodej</span><span class="sxs-lookup"><span data-stu-id="673a8-121">Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="673a8-122">Nákup</span><span class="sxs-lookup"><span data-stu-id="673a8-122">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="673a8-123">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="673a8-123">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

