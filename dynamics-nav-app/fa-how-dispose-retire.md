---
title: "Návod: Vyřazení nebo odebrání DM"
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
ms.openlocfilehash: 795bb23e7c0b46be095b2bbdfe7705b3d7b1e4ee
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-dispose-of-or-retire-fixed-assets"></a><span data-ttu-id="24898-102">Návod: Vyřazení nebo odebrání DM</span><span class="sxs-lookup"><span data-stu-id="24898-102">How to: Dispose of or Retire Fixed Assets</span></span>
<span data-ttu-id="24898-103">Při prodeji nebo jiném vyřazování DM musí být hodnota vyřazení zaúčtována k výpočtu a zaznamenání zisku nebo ztrát.</span><span class="sxs-lookup"><span data-stu-id="24898-103">When you sell or otherwise dispose of a fixed asset, the disposal value must be posted to calculate and record the gain or loss.</span></span> <span data-ttu-id="24898-104">Vyřazená položka musí být poslední položkou zaúčtovanou pro dlouhodobý majetek.</span><span class="sxs-lookup"><span data-stu-id="24898-104">A disposal entry must be the last entry posted for a fixed asset.</span></span> <span data-ttu-id="24898-105">Pro částečné vyřazení DM můžete zaúčtovat více než jednu vyřazenou položku.</span><span class="sxs-lookup"><span data-stu-id="24898-105">For partially disposed fixed assets, you can post more than one disposal entry.</span></span> <span data-ttu-id="24898-106">Všechny zaúčtované částky musí činit částku Dal.</span><span class="sxs-lookup"><span data-stu-id="24898-106">The total of all posted disposal amounts must be a credit amount.</span></span>

 <span data-ttu-id="24898-107">**POZNÁMKA**: Pokud obchodujete s dlouhodobým majetkem musíte zaznamenat, jak prodej starého majetku (vyřazení) tak i nákup nového (pořízení).</span><span class="sxs-lookup"><span data-stu-id="24898-107">**NOTE**: If you trade in a fixed asset for another one, you must record both the sale of the old asset (disposal) and the purchase of the new one (acquisition).</span></span> <span data-ttu-id="24898-108">Další informace naleznete v tématu [Návod: Pořízení DM](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="24898-108">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a><span data-ttu-id="24898-109">Zaúčtování vyřazeného DM z finančního deníku</span><span class="sxs-lookup"><span data-stu-id="24898-109">To post a disposal from the fixed asset G/L journal</span></span>  
1. <span data-ttu-id="24898-110">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Finanční deníky DM** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="24898-110">In the top right corner, choose the **Search for Page or Report** icon, enter **FA G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="24898-111">Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="24898-111">Create an initial journal line and fill in the fields as necessary.</span></span> <span data-ttu-id="24898-112">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="24898-112">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="24898-113">V poli **Typ účtování DM** vyberte **Vyřazení**.</span><span class="sxs-lookup"><span data-stu-id="24898-113">In the **FA Posting Type** field, select **Disposal**.</span></span>
4. <span data-ttu-id="24898-114">Zvolte možnost **Vložit protiúčet DM**.</span><span class="sxs-lookup"><span data-stu-id="24898-114">Choose the **Insert FA Bal. Account** action.</span></span> <span data-ttu-id="24898-115">Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování vyřazeného.</span><span class="sxs-lookup"><span data-stu-id="24898-115">A second journal line is created for the balancing account that is set up for disposal posting.</span></span>

    <span data-ttu-id="24898-116">**Poznámka**: Krok 4 funguje pouze v případě, že jste nastavili následující: V okně **Karta účto skupiny DM** pro zaúčtování skupin DM, pole **Účet vyřazení** obsahuje účet MD hlavní knihy a pole **Protiúčet  při vyřazení** obsahuje účet hlavní knihy, na který chcete zaúčtovat zůstatkové položky za účelem zhodnocení.</span><span class="sxs-lookup"><span data-stu-id="24898-116">**Note**: Step 4 only works if you have set up the following: In the **FA Posting Group Card** window for the posting group of the fixed asset, the **Disposal Account** field contains the general ledger debit account and the **Disposal Bal. Account** field contains the general ledger account to which you want to post balancing entries for appreciation.</span></span> <span data-ttu-id="24898-117">Další informace naleznete v tématu "Nastavení skupin zaúčtování DM“ [Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="24898-117">For more information, see the "To set up fixed asset posting groups" section in [How to: Set Up General Fixed Asset Information](fa-how-setup-general.md).</span></span>
5. <span data-ttu-id="24898-118">Zvolte akci **Účtovat**. </span><span class="sxs-lookup"><span data-stu-id="24898-118">Choose the **Post** action.</span></span>

<span data-ttu-id="24898-119">Pokud chcete prodat nebo vyřadit část DM, musíte rozdělit majetek před tím, než zaznamenáte transakci vyřazení.</span><span class="sxs-lookup"><span data-stu-id="24898-119">If you sell or dispose of part of a fixed asset, you must split up the asset before you can record the disposal transaction.</span></span> <span data-ttu-id="24898-120">Další informace naleznete v tématu [Návod: Převod, rozdělení nebo kombinace DM](fa-how-trans-split-combine.md).</span><span class="sxs-lookup"><span data-stu-id="24898-120">For more information, see [How to: Transfer, Split, or Combine Fixed Assets](fa-how-trans-split-combine.md).</span></span>

## <a name="to-view-disposal-ledger-entries"></a><span data-ttu-id="24898-121">Zobrazení vyřazených položek z knihy</span><span class="sxs-lookup"><span data-stu-id="24898-121">To view disposal ledger entries</span></span>  
<span data-ttu-id="24898-122">Při prodeji nebo vyřazení DM je hodnota vyřazení zaúčtována do hlavní knihy, kde můžete zobrazit výsledek.</span><span class="sxs-lookup"><span data-stu-id="24898-122">When you sell or dispose of a fixed asset, the disposal value is posted to the general ledger where you can view the result.</span></span>   

1. <span data-ttu-id="24898-123">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="24898-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.</span></span>  
2. <span data-ttu-id="24898-124">Vyberte dlouhodobý majetek, u kterého chcete zobrazit položky a pak vyberte akci **Kniha odpisů**.</span><span class="sxs-lookup"><span data-stu-id="24898-124">Select the fixed asset that you want to view entries for, and then choose the **Depreciation Books** action.</span></span>
3. <span data-ttu-id="24898-125">Vyberte odpisovou knihu, kde chcete zobrazit položky a poté vyberte akci **Položky**.</span><span class="sxs-lookup"><span data-stu-id="24898-125">Select the depreciation book that you want to view entries for, and then choose the **Ledger Entries** action.</span></span>
4. <span data-ttu-id="24898-126">Vyberte řádek s **Vyřazení** v poli **Kategorie účtování DM** a pak zvolte akci **Navigovat**.</span><span class="sxs-lookup"><span data-stu-id="24898-126">Select a line with **Disposal** in the **FA Posting Category** field, and then choose the **Navigate** action.</span></span>  
5. <span data-ttu-id="24898-127">V okně **Navigace** vyberte řádky položky hlavní knihy a pak zvolte akci **Ukázat**.</span><span class="sxs-lookup"><span data-stu-id="24898-127">In the **Navigate** window, select the general ledger entry line, and then choose the **Show** action.</span></span>
<span data-ttu-id="24898-128">Okno **Věcné položky** se otevře tam, kde můžete vidět položky, které vedly k vyřazení.</span><span class="sxs-lookup"><span data-stu-id="24898-128">The **General Ledger Entries** window opens where you can see the entries that the disposal posting resulted in.</span></span>

## <a name="see-also"></a><span data-ttu-id="24898-129">Viz také</span><span class="sxs-lookup"><span data-stu-id="24898-129">See Also</span></span>
[<span data-ttu-id="24898-130">Správa DM</span><span class="sxs-lookup"><span data-stu-id="24898-130">Manage Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="24898-131">Nastavení DM</span><span class="sxs-lookup"><span data-stu-id="24898-131">Set Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="24898-132">Finance</span><span class="sxs-lookup"><span data-stu-id="24898-132">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="24898-133">[Vítejte v [!INCLUDE[navnow](includes/navnow_md.md)]](across-get-started.md)</span><span class="sxs-lookup"><span data-stu-id="24898-133">[Welcome to Dynamics NAV](across-get-started.md)</span></span>

