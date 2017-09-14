---
title: "Návod: Práce se šeky"
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
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a><span data-ttu-id="f4643-102">Návod: Práce se šeky</span><span class="sxs-lookup"><span data-stu-id="f4643-102">How to: Work With Checks</span></span>
<span data-ttu-id="f4643-103">[!INCLUDE[navnow](includes/navnow_md.md)] podporuje elektronické a manuální vydávání šeků.</span><span class="sxs-lookup"><span data-stu-id="f4643-103">Dynamics NAV supports electronic and manual check issuance.</span></span> <span data-ttu-id="f4643-104">Obě metody používají deník plateb k vystavení šeků dodavatelům.</span><span class="sxs-lookup"><span data-stu-id="f4643-104">Both methods use the payment journal to issue checks to vendors.</span></span> <span data-ttu-id="f4643-105">Můžete také anulovat šeky a zobrazit položky šeku.</span><span class="sxs-lookup"><span data-stu-id="f4643-105">You can also void checks and view check ledger entries.</span></span>

<span data-ttu-id="f4643-106">Proces vydávání šeků navrhuje platby, vytváří položky a tiskne počítačové šeky.</span><span class="sxs-lookup"><span data-stu-id="f4643-106">The process of issuing checks suggests payments, creates ledger entries, and prints the computer checks.</span></span>

<span data-ttu-id="f4643-107">Tiskárna musí být správně nastavena pomocí šekových formulářů a musíte určit, které rozvržení šeku použijete.</span><span class="sxs-lookup"><span data-stu-id="f4643-107">Your printer must be correctly set up with the check forms, and you must define which check layout to use.</span></span> <span data-ttu-id="f4643-108">Další informace naleznete v tématu: [Návod: Definování rozvržení šeku](finance-setup-how-define-check-layouts.md)</span><span class="sxs-lookup"><span data-stu-id="f4643-108">For more information, see [How to: Define Check Layouts](finance-setup-how-define-check-layouts.md)</span></span>

## <a name="to-issue-checks"></a><span data-ttu-id="f4643-109">Vydání šeků</span><span class="sxs-lookup"><span data-stu-id="f4643-109">To issue checks</span></span>
1. <span data-ttu-id="f4643-110">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky plateb** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="f4643-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="f4643-111">Vyplňte deník příslušnými platbami, například pomocí funkce Navrhnout platby dodavateli.</span><span class="sxs-lookup"><span data-stu-id="f4643-111">Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function.</span></span> <span data-ttu-id="f4643-112">Další informace naleznete v tématu: [Návod: Návrh platby dodavatele](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="f4643-112">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>
3. <span data-ttu-id="f4643-113">V poli **Typ bankovní platby** na řádcích deníku pro platbu, kterou chcete provést pomocí šeků, vyberte jednu z následujících možností:</span><span class="sxs-lookup"><span data-stu-id="f4643-113">In the **Bank Payment Type** field on journal lines for payment that you want to make with checks, select one of the following options:</span></span>

 - <span data-ttu-id="f4643-114">**Počítačový šek**: Tuto volbu vyberte, pokud chcete vytisknout šek částky na řádku deníku plateb.</span><span class="sxs-lookup"><span data-stu-id="f4643-114">**Computer Check**: Select this option if you want to print a check for the amount on the payment journal line.</span></span> <span data-ttu-id="f4643-115">Musíte vytisknout kontroly před tím, než budete moci zaúčtovat řádky žurnálu.</span><span class="sxs-lookup"><span data-stu-id="f4643-115">You must print the checks before you can post the journal lines.</span></span> <span data-ttu-id="f4643-116">Můžete zvolit pouze možnost **Počítačový šek**, pokud je nastavena hodnota **Protiúčet Typ účtu** nebo **Typ účtu** je **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="f4643-116">You can only select **Computer Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

 - <span data-ttu-id="f4643-117">**Ruční kontrola**: Tuto volbu vyberte, pokud jste ručně vytvořili šek a chcete vytvořit odpovídající záznam pro tuto částku.</span><span class="sxs-lookup"><span data-stu-id="f4643-117">**Manual Check**: Select this option if you have created a check manually and want to create a corresponding check ledger entry for this amount.</span></span> <span data-ttu-id="f4643-118">Pomocí této možnosti nelze vytisknout šeky z [!INCLUDE[navnow](includes/navnow_md.md)].</span><span class="sxs-lookup"><span data-stu-id="f4643-118">By using this option, you cannot print checks from Dynamics NAV.</span></span> <span data-ttu-id="f4643-119">Můžete zvolit pouze možnost **Počítačový šek**, pokud je nastavena hodnota **Protiúčet Typ účtu** nebo **Typ účtu** je **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="f4643-119">You can only select **Manual Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

    <span data-ttu-id="f4643-120">**Poznámka**: Musíte vytisknout počítačové šeky před tím, než budete moci zaúčtovat řádky žurnálu.</span><span class="sxs-lookup"><span data-stu-id="f4643-120">**Note**: You must print computer checks before you post the related journal lines.</span></span>
4. <span data-ttu-id="f4643-121">V případě kontroly počítače zvolte možnost **Tisk šeku**.</span><span class="sxs-lookup"><span data-stu-id="f4643-121">In case of computer checks, choose **Print Check**.</span></span>
5. <span data-ttu-id="f4643-122">V okně **Šek** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="f4643-122">In the **Check** window, fill in the fields as necessary.</span></span> <span data-ttu-id="f4643-123">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="f4643-123">Choose a field to read a short description of the field or link to more information.</span></span>
6. <span data-ttu-id="f4643-124">Zvolte tlačítko **Tisk**.</span><span class="sxs-lookup"><span data-stu-id="f4643-124">Choose the **Print** button.</span></span>

<span data-ttu-id="f4643-125">**Poznámka**: Chcete-li vytisknout šeky z více bankovních účtů ve více než jedné měně, musíte pro každou měnu spustit dávkovou úlohu **Tisk šeku** samostatně a určit příslušný bankovní účet.</span><span class="sxs-lookup"><span data-stu-id="f4643-125">**Note**: If you want to print checks in more than one currency from different bank accounts, you must run the **Print Check** batch job separately for each currency and specify the appropriate bank account.</span></span>

## <a name="to-cancel-printed-checks-that-are-not-posted"></a><span data-ttu-id="f4643-126">Zrušení vytištěných šeků, které nejsou zaúčtovány</span><span class="sxs-lookup"><span data-stu-id="f4643-126">To cancel printed checks that are not posted</span></span>
<span data-ttu-id="f4643-127">Po vytištění můžete zrušit nezaúčtované šeky pomocí akce **Zrušit šek** v okně **Deník plateb**.</span><span class="sxs-lookup"><span data-stu-id="f4643-127">You can cancel non-posted checks after they have been printed by using the **Void Check** action in the **Payment Journal** window.</span></span>
1. <span data-ttu-id="f4643-128">V okně **Deníky plateb** vyberte možnost **Zrušit šek** a poté vyberte, které šeky chcete zrušit.</span><span class="sxs-lookup"><span data-stu-id="f4643-128">In the **Payment Journal** window, choose the **Void Check**, and then choose which checks to cancel.</span></span>

## <a name="to-void-checks"></a><span data-ttu-id="f4643-129">Anulování šeků</span><span class="sxs-lookup"><span data-stu-id="f4643-129">To void checks</span></span>
<span data-ttu-id="f4643-130">Když byla zaúčtována šeková platba, můžete zrušit (anulovat) šeky pouze z výsledných položek bank.</span><span class="sxs-lookup"><span data-stu-id="f4643-130">When check payment have been posted, you can only cancel (void) checks from the resulting bank ledger entries.</span></span>

1. <span data-ttu-id="f4643-131">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Banky** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="f4643-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="f4643-132">Zvolte příslušný bankovní účet, vyberte akci **Úpravy** a poté vyberte akci **Položky šeků**.</span><span class="sxs-lookup"><span data-stu-id="f4643-132">Select the relevant bank account, choose the **Edit** action, and then choose the **Check Ledger Entries** action.</span></span>
3. <span data-ttu-id="f4643-133">V okně **Položky šeků** vyberte akci **Zrušit šek**.</span><span class="sxs-lookup"><span data-stu-id="f4643-133">In the **Check Ledger Entries** window, choose the **Void Check** action.</span></span>
4. <span data-ttu-id="f4643-134">Vyberte zaškrtávací políčko **Pouze zrušit šeky**.</span><span class="sxs-lookup"><span data-stu-id="f4643-134">Select the **Void Check Only** check box.</span></span>
5. <span data-ttu-id="f4643-135">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="f4643-135">Choose the **OK**button.</span></span>

## <a name="see-also"></a><span data-ttu-id="f4643-136">Viz také</span><span class="sxs-lookup"><span data-stu-id="f4643-136">See Also</span></span>
[<span data-ttu-id="f4643-137">Správa závazků</span><span class="sxs-lookup"><span data-stu-id="f4643-137">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="f4643-138">Nastavit bankovnictví</span><span class="sxs-lookup"><span data-stu-id="f4643-138">Set Up Banking</span></span>](bank-setup-banking.md)  

