---
title: "Určení barevných indikátorů pro přizpůsobení vizuálních signálů o aktivitě Hromádka"
description: "Nastavte barevný indikátor na dlaždici Hromádka, abyste získali personalizovaný vizuální signál o aktivitě Hromádka."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: personalize, customize
ms.date: 03/29/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: af570c73a82edf8c94805ebe07428bb6eea9f0bf
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-a-colored-indicator-on-cues"></a><span data-ttu-id="e0ffa-103">Návod: Nastavení barevného indikátoru v Hromádkách</span><span class="sxs-lookup"><span data-stu-id="e0ffa-103">How to: Set Up a Colored Indicator on Cues</span></span>
<span data-ttu-id="e0ffa-104">Hromádky, které se zobrazí na **Domovské stránce**, můžete nastavit tak, aby obsahovaly indikátor, který změní barvu na základě hodnot dat v hromádkách.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-104">You can set up Cues that appear on the **Home** page to include an indicator that changes color based on the data values in the Cues.</span></span>

<span data-ttu-id="e0ffa-105">Indikátor se objevuje jako barevný sloupec podél horního okraje dlaždice hromádky.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-105">The indicator appears as a colored bar along the top border of the Cue tile.</span></span> <span data-ttu-id="e0ffa-106">Poskytuje vizuální signál o stavu činnosti hromádky, který může naznačovat příznivé nebo nepříznivé podmínky pro vyvolání akce.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-106">It provides a visual signal of the status of the Cue's activity, which can indicate favorable or unfavorable conditions to prompt the user to take action.</span></span> <span data-ttu-id="e0ffa-107">Pokud například hromádka zobrazuje otevřené prodejní faktury, můžete nastavit indikátor tak, aby vypadal zeleně (příznivý), když je celkový počet otevřených prodejních faktur nižší než 10, a aby vypadal červeně (nepříznivý), když je celkový počet vyšší než 20.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-107">For example, if a Cue displays ongoing sales invoices, you can set up the indicator to appear green (favorable) when total number of ongoing sales invoices is below 10, and appears red (unfavorable) when the total is greater than 20.</span></span>

<span data-ttu-id="e0ffa-108">V okně **Nastavení hromádky** můžete nastavit indikátory pro všechny hromádky, které jsou dostupné ve firemní databázi.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-108">From the **Cue Setup** window, you set up indicators for all the Cues that are available in the company database.</span></span>

<span data-ttu-id="e0ffa-109">Chcete-li nastavit indikátor, zadejte dvě mezní hodnoty, které definují tři rozsahy hodnot dat (nízké, střední a vysoké), ke kterým můžete použít jinou barvu (nebo styl).</span><span class="sxs-lookup"><span data-stu-id="e0ffa-109">To set up the indicator, you specify up to two threshold values that define three ranges of data values (low, middle, and high) to which you can apply a different color (or style).</span></span>

## <a name="to-set-up-colored-indicators-on-cues"></a><span data-ttu-id="e0ffa-110">Nastavení barevných indikátorů hromádek</span><span class="sxs-lookup"><span data-stu-id="e0ffa-110">To set up colored indicators on Cues</span></span>
1. <span data-ttu-id="e0ffa-111">V sekci **Aktivity** na vaší **Domovské stránce** vyberte možnost **Nastavit hromádky**.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-111">Under **Activities** on your **Home** page, choose **Set Up Cues**.</span></span>  
   <span data-ttu-id="e0ffa-112">Zobrazí se okno **Nastavení hromádek**.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-112">The **Cue Setup** window appears.</span></span> <span data-ttu-id="e0ffa-113">Okno obsahuje seznam indikátorů, které jsou aktuálně v hromádkách nastaveny.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-113">The window lists the indicators that are currently setup up on Cues.</span></span>
2. <span data-ttu-id="e0ffa-114">Chcete-li změnit indikátor, upravte pole a modifikujte například, hodnoty pro různé mezní hodnoty.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-114">To modify an indicator, edit the fields and modify, for example, the values for the different thresholds.</span></span>  

<span data-ttu-id="e0ffa-115">V následující tabulce jsou uvedeny barvy, které odpovídají možnostem polí  **Styl pro nízké hodnoty**, **Styl spro střední hodnoty** a **Styl pro vysoké hodnoty**.</span><span class="sxs-lookup"><span data-stu-id="e0ffa-115">The following table lists the colors that correspond to the options of the **Low Range Style**, **Middle Range Style**, and **High Range Style** fields.</span></span>

| <span data-ttu-id="e0ffa-116">Možnost</span><span class="sxs-lookup"><span data-stu-id="e0ffa-116">Option</span></span> | <span data-ttu-id="e0ffa-117">Barva</span><span class="sxs-lookup"><span data-stu-id="e0ffa-117">Color</span></span> |
| --- | --- |
| <span data-ttu-id="e0ffa-118">**Žádný**</span><span class="sxs-lookup"><span data-stu-id="e0ffa-118">**None**</span></span> |<span data-ttu-id="e0ffa-119">Žádná barva (stejná barva jako dlaždice Hromádka)</span><span class="sxs-lookup"><span data-stu-id="e0ffa-119">No color (same color as the Cue )</span></span>|
| <span data-ttu-id="e0ffa-120">**Příznivý**</span><span class="sxs-lookup"><span data-stu-id="e0ffa-120">**Favorable**</span></span> |<span data-ttu-id="e0ffa-121">Zelená</span><span class="sxs-lookup"><span data-stu-id="e0ffa-121">Green</span></span> |
| <span data-ttu-id="e0ffa-122">**Nepříznivý**</span><span class="sxs-lookup"><span data-stu-id="e0ffa-122">**Unfavorable**</span></span> |<span data-ttu-id="e0ffa-123">Červená</span><span class="sxs-lookup"><span data-stu-id="e0ffa-123">Red</span></span> |
| <span data-ttu-id="e0ffa-124">**Nejednoznačný**</span><span class="sxs-lookup"><span data-stu-id="e0ffa-124">**Ambiguous**</span></span> |<span data-ttu-id="e0ffa-125">Žlutá</span><span class="sxs-lookup"><span data-stu-id="e0ffa-125">Yellow</span></span> |
| <span data-ttu-id="e0ffa-126">**Podřízený**</span><span class="sxs-lookup"><span data-stu-id="e0ffa-126">**Subordinate**</span></span> |<span data-ttu-id="e0ffa-127">Šedá</span><span class="sxs-lookup"><span data-stu-id="e0ffa-127">Gray</span></span> |

## <a name="see-also"></a><span data-ttu-id="e0ffa-128">Viz také</span><span class="sxs-lookup"><span data-stu-id="e0ffa-128">See Also</span></span>
<span data-ttu-id="e0ffa-129">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="e0ffa-129">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

