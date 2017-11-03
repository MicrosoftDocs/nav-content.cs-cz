---
title: "Nastavení údržby DM"
description: "Ke správě oprav a servisu dlouhodobého majetku, specifikujte všeobecné informace o údržbě, kódy pro typ práce a zaúčtovací účty pro náklady."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: repair, service
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: cb437985793e7fa4330d5bd8301d2808b5deafcc
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-fixed-asset-maintenance"></a><span data-ttu-id="b6120-103">Návod: Nastavení údržby dlouhodobého majetku</span><span class="sxs-lookup"><span data-stu-id="b6120-103">How to: Set Up Fixed Asset Maintenance</span></span>
<span data-ttu-id="b6120-104">Ke správě údržby dlouhodobého majetku musíte nejprve nastavit obecné informace o údržbě, účet pro zaúčtování a kódy údržby pro typ práce, např. služba rutiny nebo oprava.</span><span class="sxs-lookup"><span data-stu-id="b6120-104">To manage fixed asset maintenance, you must first set up some general maintenance information, a posting account for maintenance costs, and maintenance codes for types of work, such as Routine Service or Repair.</span></span>

## <a name="to-set-up-general-maintenance-information"></a><span data-ttu-id="b6120-105">Nastavení obecných informací o údržbě</span><span class="sxs-lookup"><span data-stu-id="b6120-105">To set up general maintenance information</span></span>
<span data-ttu-id="b6120-106">Pokud nastavíte pole pro údržbu, můžete účtovat výdaje za údržbu z deníku dlouhodobého majetku.</span><span class="sxs-lookup"><span data-stu-id="b6120-106">If you set up the fields for maintenance, you can post maintenance expenses from the fixed asset journal.</span></span>

1. <span data-ttu-id="b6120-107">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="b6120-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Fixed Assets**, and then choose the related link.</span></span>
2. <span data-ttu-id="b6120-108">Vybrat dlouhodobý majetek, pro který chcete definovat pokrytí pojištění a pak vyberte akci **Úpravy**.</span><span class="sxs-lookup"><span data-stu-id="b6120-108">Select the fixed asset that you to define insurance coverage for, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="b6120-109">Na záložce s náhledem **Údržba** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="b6120-109">On the **Maintenance** FastTab, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-maintenance-codes"></a><span data-ttu-id="b6120-110">Nastavení kódů údržby</span><span class="sxs-lookup"><span data-stu-id="b6120-110">To set up maintenance codes</span></span>
<span data-ttu-id="b6120-111">Když účtujete náklady na údržbu z finančního deníku, vyplníte pole **Kód údržby** k zaznamenání toho, k jaké údržbě došlo, např. rutinního servisu nebo opravě.</span><span class="sxs-lookup"><span data-stu-id="b6120-111">When you post maintenance costs from a general journal, you fill in the **Maintenance Code** field to record what kind of maintenance has been performed, such as routine service or repair.</span></span>

1. <span data-ttu-id="b6120-112">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Údržba** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="b6120-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Maintenance**, and then choose the related link.</span></span>
2. <span data-ttu-id="b6120-113">V okně **Údržba** nastavte kódy pro různé typy práce údržby.</span><span class="sxs-lookup"><span data-stu-id="b6120-113">In the **Maintenance** window, set up codes for different types of maintenance work.</span></span>

## <a name="to-set-up-maintenance-expense-accounts"></a><span data-ttu-id="b6120-114">Nastavení účtů výdajů za údržbu</span><span class="sxs-lookup"><span data-stu-id="b6120-114">To set up maintenance expense accounts</span></span>
<span data-ttu-id="b6120-115">K účtování výdajů za údržbu musíte nejprve zvolit číslo účtu v okně **Účto skupiny DM**.</span><span class="sxs-lookup"><span data-stu-id="b6120-115">To post maintenance costs, you must first enter an account number in the **FA Posting Groups** window.</span></span>

1. <span data-ttu-id="b6120-116">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účto skupiny DM** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="b6120-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Posting Groups**, and then choose the related link.</span></span>
2. <span data-ttu-id="b6120-117">Vyplňte pole **Účet nákladů údržby** pro každou účto skupinu.</span><span class="sxs-lookup"><span data-stu-id="b6120-117">Fill in the **Maintenance Expense Account** field for each posting group.</span></span>

> [!NOTE]  
>   <span data-ttu-id="b6120-118">K definování, že výdaje za údržbu jsou přiděleny k oddělení nebo projektům, nastavte alokační klíče.</span><span class="sxs-lookup"><span data-stu-id="b6120-118">To define that maintenance costs are allocated to departments or projects, set up an allocation keys.</span></span> <span data-ttu-id="b6120-119">Další informace naleznete v tématu [Návod: Nastavení funkcí obecného dlouhodobého majetku](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="b6120-119">For more information, see [How to: Set Up General Fixed Assets Features](fa-how-setup-general.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="b6120-120">Viz také</span><span class="sxs-lookup"><span data-stu-id="b6120-120">See Also</span></span>
[<span data-ttu-id="b6120-121">Nastavení DM</span><span class="sxs-lookup"><span data-stu-id="b6120-121">Setting Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="b6120-122">Dlouhodobý majetek</span><span class="sxs-lookup"><span data-stu-id="b6120-122">Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="b6120-123">Finance</span><span class="sxs-lookup"><span data-stu-id="b6120-123">Finance</span></span>](finance.md)  
<span data-ttu-id="b6120-124">[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="b6120-124">[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span></span>  
<span data-ttu-id="b6120-125">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="b6120-125">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

