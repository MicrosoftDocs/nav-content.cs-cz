---
title: "Návod: Nastavení barevného indikátoru hromádek"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 38cd904d0cf22374eac430d035e6ea6d205bcab8
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---
    
# <a name="how-to-set-up-a-colored-indicator-on-cues"></a><span data-ttu-id="bb5f8-102">Návod: Nastavení barevného indikátoru hromádek</span><span class="sxs-lookup"><span data-stu-id="bb5f8-102">How to: Set Up a Colored Indicator on Cues</span></span>
<span data-ttu-id="bb5f8-103">Hromádky, které se zobrazí na **Domovské stránce**, můžete nastavit tak, aby obsahovaly indikátor, který změní barvu na základě hodnot dat v hromádkách.</span><span class="sxs-lookup"><span data-stu-id="bb5f8-103">You can set up Cues that appear on the **Home** page to include an indicator that changes color based on the data values in the Cues.</span></span> 

<span data-ttu-id="bb5f8-104">Indikátor se objevuje jako barevný sloupec podél horního okraje dlaždice hromádky.</span><span class="sxs-lookup"><span data-stu-id="bb5f8-104">The indicator appears as a colored bar along the top border of the Cue tile.</span></span> <span data-ttu-id="bb5f8-105">Poskytuje vizuální signál o stavu činnosti hromádky, který může naznačovat příznivé nebo nepříznivé podmínky pro vyvolání akce.</span><span class="sxs-lookup"><span data-stu-id="bb5f8-105">It provides a visual signal of the status of the Cue's activity, which can indicate favorable or unfavorable conditions to prompt the user to take action.</span></span> <span data-ttu-id="bb5f8-106">Pokud například hromádka zobrazuje otevřené prodejní faktury, můžete nastavit indikátor tak, aby vypadal zeleně (příznivý), když je celkový počet otevřených prodejních faktur nižší než 10, a aby vypadal červeně (nepříznivý), když je celkový počet vyšší než 20.</span><span class="sxs-lookup"><span data-stu-id="bb5f8-106">For example, if a Cue displays ongoing sales invoices, you can set up the indicator to appear green (favorable) when total number of ongoing sales invoices is below 10, and appears red (unfavorable) when the total is greater than 20.</span></span>

<span data-ttu-id="bb5f8-107">V okně **Nastavení hromádky** můžete nastavit indikátory pro všechny hromádky, které jsou dostupné ve firemní databázi. </span><span class="sxs-lookup"><span data-stu-id="bb5f8-107">From the **Cue Setup** window, you set up indicators for all the Cues that are available in the company database.</span></span>

<span data-ttu-id="bb5f8-108">Chcete-li nastavit indikátor, zadejte dvě mezní hodnoty, které definují tři rozsahy hodnot dat (nízké, střední a vysoké), ke kterým můžete použít jinou barvu (nebo styl).</span><span class="sxs-lookup"><span data-stu-id="bb5f8-108">To set up the indicator, you specify up to two threshold values that define three ranges of data values (low, middle, and high) to which you can apply a different color (or style).</span></span>

## <a name="to-set-up-colored-indicators-on-cues"></a><span data-ttu-id="bb5f8-109">Nastavení barevných indikátorů hromádek</span><span class="sxs-lookup"><span data-stu-id="bb5f8-109">To set up colored indicators on Cues</span></span>
1. <span data-ttu-id="bb5f8-110">V sekci **Aktivity** na vaší **Domovské stránce** vyberte možnost **Nastavit hromádky**.</span><span class="sxs-lookup"><span data-stu-id="bb5f8-110">Under **Activities** on your **Home** page, choose **Set Up Cues**.</span></span>  
<span data-ttu-id="bb5f8-111">Zobrazí se okno **Nastavení hromádek**.</span><span class="sxs-lookup"><span data-stu-id="bb5f8-111">The **Cue Setup** window appears.</span></span> <span data-ttu-id="bb5f8-112">Okno obsahuje seznam indikátorů, které jsou aktuálně v hromádkách nastaveny.</span><span class="sxs-lookup"><span data-stu-id="bb5f8-112">The window lists the indicators that are currently setup up on Cues.</span></span>
2. <span data-ttu-id="bb5f8-113">Chcete-li změnit indikátor, upravte pole a modifikujte například, hodnoty pro různé mezní hodnoty.</span><span class="sxs-lookup"><span data-stu-id="bb5f8-113">To modify an indicator, edit the fields and modify, for example, the values for the different thresholds.</span></span>  

<span data-ttu-id="bb5f8-114">V následující tabulce jsou uvedeny barvy, které odpovídají možnostem polí  **Styl pro nízké hodnoty**, **Styl spro střední hodnoty** a **Styl pro vysoké hodnoty**.</span><span class="sxs-lookup"><span data-stu-id="bb5f8-114">The following table lists the colors that correspond to the options of the **Low Range Style**, **Middle Range Style**, and **High Range Style** fields.</span></span>

|<span data-ttu-id="bb5f8-115">Možnost</span><span class="sxs-lookup"><span data-stu-id="bb5f8-115">Option</span></span>|<span data-ttu-id="bb5f8-116">Barva</span><span class="sxs-lookup"><span data-stu-id="bb5f8-116">Color</span></span>|
|------|-----|
|<span data-ttu-id="bb5f8-117">**Žádný**</span><span class="sxs-lookup"><span data-stu-id="bb5f8-117">**None**</span></span>|<span data-ttu-id="bb5f8-118">Žádná barva (stejná barva jako dlaždice Hromádka)</span><span class="sxs-lookup"><span data-stu-id="bb5f8-118">No color (same color as the Cue tile</span></span>|
|<span data-ttu-id="bb5f8-119">**Příznivý**</span><span class="sxs-lookup"><span data-stu-id="bb5f8-119">**Favorable**</span></span>|<span data-ttu-id="bb5f8-120">Zelená</span><span class="sxs-lookup"><span data-stu-id="bb5f8-120">Green</span></span>|
|<span data-ttu-id="bb5f8-121">**Nepříznivý**</span><span class="sxs-lookup"><span data-stu-id="bb5f8-121">**Unfavorable**</span></span>|<span data-ttu-id="bb5f8-122">Červená</span><span class="sxs-lookup"><span data-stu-id="bb5f8-122">Red</span></span>|
|<span data-ttu-id="bb5f8-123">**Nejednoznačný**</span><span class="sxs-lookup"><span data-stu-id="bb5f8-123">**Ambiguous**</span></span>|<span data-ttu-id="bb5f8-124">Žlutá</span><span class="sxs-lookup"><span data-stu-id="bb5f8-124">Yellow</span></span>|
|<span data-ttu-id="bb5f8-125">**Podřízený**</span><span class="sxs-lookup"><span data-stu-id="bb5f8-125">**Subordinate**</span></span>|<span data-ttu-id="bb5f8-126">Šedá</span><span class="sxs-lookup"><span data-stu-id="bb5f8-126">Gray</span></span>|

## <a name="see-also"></a><span data-ttu-id="bb5f8-127">Viz také</span><span class="sxs-lookup"><span data-stu-id="bb5f8-127">See Also</span></span>
[<span data-ttu-id="bb5f8-128">Práce s Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="bb5f8-128">Work with Dynamics NAV</span></span>](ui-work-product.md)


