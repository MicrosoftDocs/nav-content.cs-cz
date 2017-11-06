---
title: "Vydání, Tisk, Zrušení šeku "
description: "Popisuje jak vydávat šeky pomocí deníku plateb, tisk šeků a zrušení nebo zobrazení položek šeků v Dynamics NAV."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment journal, print check, vendor payment, creditor, debt, balance due, AP
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 716cb17bf65b225036576dc73f3fe43b102ccb81
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-checks"></a><span data-ttu-id="92682-103">Návod: Práce s šeky</span><span class="sxs-lookup"><span data-stu-id="92682-103">How to: Work With Checks</span></span>
<span data-ttu-id="92682-104">Můžete vydávat elektronické mebo ruční šeky v .</span><span class="sxs-lookup"><span data-stu-id="92682-104">You can issue electronic and manual checks in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="92682-105">Obě metody používají deník plateb k vystavení šeků dodavatelům.</span><span class="sxs-lookup"><span data-stu-id="92682-105">Both methods use the payment journal to issue checks to vendors.</span></span> <span data-ttu-id="92682-106">Můžete také anulovat šeky a zobrazit položky šeku.</span><span class="sxs-lookup"><span data-stu-id="92682-106">You can also void checks and view check ledger entries.</span></span>

<span data-ttu-id="92682-107">Proces vydávání šeků navrhuje platby, vytváří položky a tiskne počítačové šeky.</span><span class="sxs-lookup"><span data-stu-id="92682-107">The process of issuing checks suggests payments, creates ledger entries, and prints the computer checks.</span></span>

> [!NOTE]  
>   <span data-ttu-id="92682-108">Chcete-li se ujistit, že banka vymaže pouze ověřené šeky a částky, můžete je poslat soubor, který obsahuje informace o dodavateli, kontrole a platbě.</span><span class="sxs-lookup"><span data-stu-id="92682-108">To make sure that your bank only clears validated checks and amounts, you can send them a file that contains vendor, check, and payment information.</span></span> <span data-ttu-id="92682-109">Další informace naleznete v tématu [Návod: Export souboru pozitivních plateb](finance-how-positive-pay.md).</span><span class="sxs-lookup"><span data-stu-id="92682-109">For more information, see [How to: Export a Positive Pay file](finance-how-positive-pay.md).</span></span>

<span data-ttu-id="92682-110">Tiskárna musí být správně nastavena pomocí šekových formulářů a musíte určit, které rozvržení šeku použijete.</span><span class="sxs-lookup"><span data-stu-id="92682-110">Your printer must be correctly set up with the check forms, and you must define which check layout to use.</span></span> <span data-ttu-id="92682-111">Další informace naleznete v tématu [Návod: Definování rozvržení šeku](finance-how-define-check-layouts.md)</span><span class="sxs-lookup"><span data-stu-id="92682-111">For more information, see [How to: Define Check Layouts](finance-how-define-check-layouts.md)</span></span>

## <a name="to-issue-checks"></a><span data-ttu-id="92682-112">Vydání šeků</span><span class="sxs-lookup"><span data-stu-id="92682-112">To issue checks</span></span>
1. <span data-ttu-id="92682-113">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky plateb** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="92682-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="92682-114">Vyplňte deník příslušnými platbami, například pomocí funkce Navrhnout platby dodavateli.</span><span class="sxs-lookup"><span data-stu-id="92682-114">Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function.</span></span> <span data-ttu-id="92682-115">Další informace naleznete v tématu [Návod: Navrhnutí plateb dodavatelů ](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="92682-115">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>
3. <span data-ttu-id="92682-116">V poli **Typ bankovní platby** na řádcích deníku pro platbu, kterou chcete provést pomocí šeků, vyberte jednu z následujících možností:</span><span class="sxs-lookup"><span data-stu-id="92682-116">In the **Bank Payment Type** field on journal lines for payment that you want to make with checks, select one of the following options:</span></span>

   * <span data-ttu-id="92682-117">**Počítačový šek**: Tuto volbu vyberte, pokud chcete vytisknout šek částky na řádku deníku plateb.</span><span class="sxs-lookup"><span data-stu-id="92682-117">**Computer Check**: Select this option if you want to print a check for the amount on the payment journal line.</span></span> <span data-ttu-id="92682-118">Musíte vytisknout kontroly před tím, než budete moci zaúčtovat řádky žurnálu.</span><span class="sxs-lookup"><span data-stu-id="92682-118">You must print the checks before you can post the journal lines.</span></span> <span data-ttu-id="92682-119">Můžete zvolit pouze možnost **Počítačový šek**, pokud je nastavena hodnota Protiúčet** **Typ účtu nebo **Typ účtu** je **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="92682-119">You can only select **Computer Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>
   * <span data-ttu-id="92682-120">**Ruční kontrola**: Tuto volbu vyberte, pokud jste ručně vytvořili šek a chcete vytvořit odpovídající záznam pro tuto částku.</span><span class="sxs-lookup"><span data-stu-id="92682-120">**Manual Check**: Select this option if you have created a check manually and want to create a corresponding check ledger entry for this amount.</span></span> <span data-ttu-id="92682-121">Pomocí této možnosti nelze vytisknout šeky z [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="92682-121">By using this option, you cannot print checks from [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="92682-122">Můžete zvolit pouze možnost **Počítačový šek**, pokud je nastavena hodnota Protiúčet** **Typ účtu nebo **Typ účtu** je **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="92682-122">You can only select **Manual Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

     > [!NOTE]  
>   <span data-ttu-id="92682-123">Musíte vytisknout počítačové šeky před tím, než budete moci zaúčtovat řádky žurnálu.</span><span class="sxs-lookup"><span data-stu-id="92682-123">You must print computer checks before you post the related journal lines.</span></span>
4. <span data-ttu-id="92682-124">V případě kontroly počítače zvolte možnost **Tisk šeku**.</span><span class="sxs-lookup"><span data-stu-id="92682-124">In case of computer checks, choose **Print Check**.</span></span>
5. <span data-ttu-id="92682-125">V okně **Šek** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="92682-125">In the **Check** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
6. <span data-ttu-id="92682-126">Zvolte tlačítko **Tisk**.</span><span class="sxs-lookup"><span data-stu-id="92682-126">Choose the **Print** button.</span></span>

> [!NOTE]  
>   <span data-ttu-id="92682-127">Chcete-li vytisknout šeky z více bankovních účtů ve více než jedné měně, musíte pro každou měnu spustit dávkovou úlohu **Tisk šeku** samostatně a určit příslušný bankovní účet.</span><span class="sxs-lookup"><span data-stu-id="92682-127">If you want to print checks in more than one currency from different bank accounts, you must run the **Print Check** batch job separately for each currency and specify the appropriate bank account.</span></span>

## <a name="to-cancel-printed-checks-that-are-not-posted"></a><span data-ttu-id="92682-128">Zrušení vytištěných šeků, které nejsou zaúčtovány</span><span class="sxs-lookup"><span data-stu-id="92682-128">To cancel printed checks that are not posted</span></span>
<span data-ttu-id="92682-129">Po vytištění můžete zrušit nezaúčtované šeky pomocí akce **Zrušit šek** v okně **Deník plateb**.</span><span class="sxs-lookup"><span data-stu-id="92682-129">You can cancel non-posted checks after they have been printed by using the **Void Check** action in the **Payment Journal** window.</span></span>

1. <span data-ttu-id="92682-130">V okně **Deníky plateb** vyberte možnost **Zrušit šek** a poté vyberte, které šeky chcete zrušit.</span><span class="sxs-lookup"><span data-stu-id="92682-130">In the **Payment Journal** window, choose the **Void Check**, and then choose which checks to cancel.</span></span>

## <a name="to-void-checks"></a><span data-ttu-id="92682-131">Anulování šeků</span><span class="sxs-lookup"><span data-stu-id="92682-131">To void checks</span></span>
<span data-ttu-id="92682-132">Když byla zaúčtována šeková platba, můžete zrušit (anulovat) šeky pouze z výsledných položek bank.</span><span class="sxs-lookup"><span data-stu-id="92682-132">When check payment have been posted, you can only cancel (void) checks from the resulting bank ledger entries.</span></span>

1. <span data-ttu-id="92682-133">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Bankovní účty** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="92682-133">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="92682-134">Zvolte příslušný bankovní účet, vyberte akci **Úpravy** a poté vyberte akci **Položky šeků**.</span><span class="sxs-lookup"><span data-stu-id="92682-134">Select the relevant bank account, choose the **Edit** action, and then choose the **Check Ledger Entries** action.</span></span>
3. <span data-ttu-id="92682-135">V okně **Položky šeků** vyberte akci **Zrušit šek**.</span><span class="sxs-lookup"><span data-stu-id="92682-135">In the **Check Ledger Entries** window, choose the **Void Check** action.</span></span>
4. <span data-ttu-id="92682-136">Vyberte zaškrtávací políčko **Pouze zrušit šeky**.</span><span class="sxs-lookup"><span data-stu-id="92682-136">Select the **Void Check Only** check box.</span></span>
5. <span data-ttu-id="92682-137">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="92682-137">Choose the **OK** button.</span></span>

## <a name="see-also"></a><span data-ttu-id="92682-138">Viz také</span><span class="sxs-lookup"><span data-stu-id="92682-138">See Also</span></span>
[<span data-ttu-id="92682-139">Správa závazků</span><span class="sxs-lookup"><span data-stu-id="92682-139">Managing Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="92682-140">Nastavení bankovnictví</span><span class="sxs-lookup"><span data-stu-id="92682-140">Setting Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="92682-141">Návod: Export souboru pozitivních plateb</span><span class="sxs-lookup"><span data-stu-id="92682-141">How to: Export a Positive Pay file</span></span>](finance-how-positive-pay.md)  
<span data-ttu-id="92682-142">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="92682-142">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

