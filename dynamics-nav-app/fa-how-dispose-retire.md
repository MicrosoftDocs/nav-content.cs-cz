---
title: "Vyřazení nebo odebrání dlouhodobého majetku"
description: "Musíte zaúčtovat vyřazovací hodnotu při vyřazování, prodeji nebo odebrání dlouhodobého majetku."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: scrap
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 38753282687aafa1d06542ba265225eb30720c20
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-dispose-of-or-retire-fixed-assets"></a><span data-ttu-id="df13a-103">Návod: Vyřazení (z provozu) nebo odebrání dlouhodobého majetku</span><span class="sxs-lookup"><span data-stu-id="df13a-103">How to: Dispose of or Retire Fixed Assets</span></span>
<span data-ttu-id="df13a-104">Při prodeji nebo jiném vyřazování DM musí být hodnota vyřazení zaúčtována k výpočtu a zaznamenání zisku nebo ztrát.</span><span class="sxs-lookup"><span data-stu-id="df13a-104">When you sell or otherwise dispose of a fixed asset, the disposal value must be posted to calculate and record the gain or loss.</span></span> <span data-ttu-id="df13a-105">Vyřazená položka musí být poslední položkou zaúčtovanou pro dlouhodobý majetek.</span><span class="sxs-lookup"><span data-stu-id="df13a-105">A disposal entry must be the last entry posted for a fixed asset.</span></span> <span data-ttu-id="df13a-106">Pro částečné vyřazení DM můžete zaúčtovat více než jednu vyřazenou položku.</span><span class="sxs-lookup"><span data-stu-id="df13a-106">For partially disposed fixed assets, you can post more than one disposal entry.</span></span> <span data-ttu-id="df13a-107">Všechny zaúčtované částky musí činit částku Dal.</span><span class="sxs-lookup"><span data-stu-id="df13a-107">The total of all posted disposal amounts must be a credit amount.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="df13a-108">Pokud obchodujete s dlouhodobým majetkem musíte zaznamenat, jak prodej starého majetku (vyřazení) tak i nákup nového (pořízení).</span><span class="sxs-lookup"><span data-stu-id="df13a-108">If you trade-in a fixed asset for another one, you must record both the sale of the old asset (disposal) and the purchase of the new one (acquisition).</span></span> <span data-ttu-id="df13a-109">Další informace naleznete v tématu [Návod: Pořízení DM](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="df13a-109">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>  

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a><span data-ttu-id="df13a-110">Zaúčtování vyřazeného DM z finančního deníku</span><span class="sxs-lookup"><span data-stu-id="df13a-110">To post a disposal from the fixed asset G/L journal</span></span>
1. <span data-ttu-id="df13a-111">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="df13a-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="df13a-112">Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="df13a-112">Create an initial journal line and fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
3. <span data-ttu-id="df13a-113">V poli **Typ účtování DM** vyberte **Vyřazení**.</span><span class="sxs-lookup"><span data-stu-id="df13a-113">In the **FA Posting Type** field, select **Disposal**.</span></span>  
4. <span data-ttu-id="df13a-114">Zvolte možnost **Vložit protiúčet DM**.</span><span class="sxs-lookup"><span data-stu-id="df13a-114">Choose the **Insert FA Bal. Account** action.</span></span> <span data-ttu-id="df13a-115">Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování vyřazeného.</span><span class="sxs-lookup"><span data-stu-id="df13a-115">A second journal line is created for the balancing account that is set up for disposal posting.</span></span>  

    > [!NOTE]  
>   <span data-ttu-id="df13a-116">Krok 4 funguje pouze v případě, že jste nastavili následující: V okně **Karta účto skupiny DM** pro zaúčtování skupin DM, pole **Účet vyřazení** obsahuje účet MD hlavní knihy a pole **Odpisový protiúčet** při vyřazení obsahuje účet hlavní knihy, na který chcete zaúčtovat zůstatkové položky za účelem zhodnocení.</span><span class="sxs-lookup"><span data-stu-id="df13a-116">Step 4 only works if you have set up the following: In the **FA Posting Group Card** window for the posting group of the fixed asset, the **Disposal Account** field contains the general ledger debit account and the **Disposal Bal. Account** field contains the general ledger account to which you want to post balancing entries for appreciation.</span></span> <span data-ttu-id="df13a-117">Další informace naleznete v tématu "Nastavení skupin zaúčtování DM“ [Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="df13a-117">For more information, see the "To set up fixed asset posting groups" section in [How to: Set Up General Fixed Asset Information](fa-how-setup-general.md).</span></span>  
5. <span data-ttu-id="df13a-118">Zvolte akci **Zaúčtovat**.</span><span class="sxs-lookup"><span data-stu-id="df13a-118">Choose the **Post** action.</span></span>  

    <span data-ttu-id="df13a-119">Pokud chcete prodat nebo vyřadit část DM, musíte rozdělit majetek před tím, než zaznamenáte transakci vyřazení.</span><span class="sxs-lookup"><span data-stu-id="df13a-119">If you sell or dispose of part of a fixed asset, you must split up the asset before you can record the disposal transaction.</span></span> <span data-ttu-id="df13a-120">Další informace naleznete v tématu [Návod: Převod, rozdělení nebo kombinace DM](fa-how-trans-split-combine.md).</span><span class="sxs-lookup"><span data-stu-id="df13a-120">For more information, see [How to: Transfer, Split, or Combine Fixed Assets](fa-how-trans-split-combine.md).</span></span>  

## <a name="to-view-disposal-ledger-entries"></a><span data-ttu-id="df13a-121">Zobrazení vyřazených položek z knihy</span><span class="sxs-lookup"><span data-stu-id="df13a-121">To view disposal ledger entries</span></span>
<span data-ttu-id="df13a-122">Při prodeji nebo vyřazení DM je hodnota vyřazení zaúčtována do hlavní knihy, kde můžete zobrazit výsledek.</span><span class="sxs-lookup"><span data-stu-id="df13a-122">When you sell or dispose of a fixed asset, the disposal value is posted to the general ledger where you can view the result.</span></span>  

1. <span data-ttu-id="df13a-123">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="df13a-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Fixed Assets**, and then choose the related link.</span></span>  
2. <span data-ttu-id="df13a-124">Vyberte dlouhodobý majetek, u kterého chcete zobrazit položky a pak vyberte akci **Kniha odpisů**.</span><span class="sxs-lookup"><span data-stu-id="df13a-124">Select the fixed asset that you want to view entries for, and then choose the **Depreciation Books** action.</span></span>  
3. <span data-ttu-id="df13a-125">Vyberte odpisovou knihu, kde chcete zobrazit položky a poté vyberte akci **Položky**.</span><span class="sxs-lookup"><span data-stu-id="df13a-125">Select the depreciation book that you want to view entries for, and then choose the **Ledger Entries** action.</span></span>  
4. <span data-ttu-id="df13a-126">Vyberte řádek s **Vyřazení** v poli **Kategorie účtování DM** a pak zvolte akci **Navigovat**.</span><span class="sxs-lookup"><span data-stu-id="df13a-126">Select a line with **Disposal** in the **FA Posting Category** field, and then choose the **Navigate** action.</span></span>  
5. <span data-ttu-id="df13a-127">V okně **Navigace** vyberte řádky položky hlavní knihy a pak zvolte akci **Ukázat**.</span><span class="sxs-lookup"><span data-stu-id="df13a-127">In the **Navigate** window, select the general ledger entry line, and then choose the **Show** action.</span></span>  

<span data-ttu-id="df13a-128">Okno **Věcné položky** se otevře tam, kde můžete vidět položky, které vedly k vyřazení.</span><span class="sxs-lookup"><span data-stu-id="df13a-128">The **General Ledger Entries** window opens where you can see the entries that the disposal posting resulted in.</span></span>  

## <a name="see-also"></a><span data-ttu-id="df13a-129">Viz také</span><span class="sxs-lookup"><span data-stu-id="df13a-129">See Also</span></span>
[<span data-ttu-id="df13a-130">Dlouhodobý majetek</span><span class="sxs-lookup"><span data-stu-id="df13a-130">Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="df13a-131">Nastavení dlouhodobého majetku</span><span class="sxs-lookup"><span data-stu-id="df13a-131">Setting Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="df13a-132">Finance</span><span class="sxs-lookup"><span data-stu-id="df13a-132">Finance</span></span>](finance.md)  
<span data-ttu-id="df13a-133">[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="df13a-133">[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span></span>  
<span data-ttu-id="df13a-134">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="df13a-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

