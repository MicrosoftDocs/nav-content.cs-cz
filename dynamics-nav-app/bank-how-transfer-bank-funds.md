---
title: "Převod bankovních prostředků"
description: "Můžete převést částky z jednoho bankovního účtu na jiný včetně různých měn tím, že zaúčtujete transakci do finančního deníku."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bank account transfer, multiple currencies
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5cb652df51fc5b24088bb5cc6a41d8d3f067cfd4
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-transfer-bank-funds"></a><span data-ttu-id="33cf7-103">Návod: Převod bankovních prostředků</span><span class="sxs-lookup"><span data-stu-id="33cf7-103">How to: Transfer Bank Funds</span></span>
<span data-ttu-id="33cf7-104">Někdy budete možná muset převést částku z jednoho bankovního účtu na jiný.</span><span class="sxs-lookup"><span data-stu-id="33cf7-104">You may sometimes need to transfer an amount from one bank account to another.</span></span> <span data-ttu-id="33cf7-105">Chcete-li to provést, musíte odeslat transakci do finančního deníku.</span><span class="sxs-lookup"><span data-stu-id="33cf7-105">To do this, you must post the a transaction in the general journal.</span></span> <span data-ttu-id="33cf7-106">Úloha se liší v závislosti na tom, zda bankovní účty používají stejnou měnu nebo různé měny.</span><span class="sxs-lookup"><span data-stu-id="33cf7-106">The task varies depending on whether the bank accounts use the same currency or different currencies.</span></span>

## <a name="to-post-a-transfer-between-bank-accounts-with-the-same-currency-code"></a><span data-ttu-id="33cf7-107">Zaúčtování převodu mezi bankovními účty se stejným kódem měny</span><span class="sxs-lookup"><span data-stu-id="33cf7-107">To post a transfer between bank accounts with the same currency code</span></span>
1. <span data-ttu-id="33cf7-108">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="33cf7-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="33cf7-109">Na řádku deníku vyplňte pole **Zúčtovací datum** a **Číslo dokladu**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-109">On a journal line, fill in the **Posting Date** and **Document No.** fields.</span></span>
3. <span data-ttu-id="33cf7-110">V poli **Typ účtu** vyberte **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-110">In the **Account Type** field, select **Bank Account**.</span></span>
4. <span data-ttu-id="33cf7-111">V poli **Číslo účtu**, vyberte banku, ze které chcete peníze převést.</span><span class="sxs-lookup"><span data-stu-id="33cf7-111">In the **Account No.** field, select the bank from which you want to transfer the funds.</span></span>
5. <span data-ttu-id="33cf7-112">Do pole **Částka** zadejte částku, kterou chcete převést.</span><span class="sxs-lookup"><span data-stu-id="33cf7-112">In the **Amount** field, enter the amount to be transferred.</span></span>
6. <span data-ttu-id="33cf7-113">V poli **Typ protiúčtu** vyberte **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-113">In the **Bal. Account Type** field, select **Bank Account**.</span></span>
7. <span data-ttu-id="33cf7-114">V poli **Typ protiúčtu** vyberte bankovní účet, na který chcete peníze převést.</span><span class="sxs-lookup"><span data-stu-id="33cf7-114">In the **Bal. Account No.** field, select the bank account to which you want to transfer the funds.</span></span>
8. <span data-ttu-id="33cf7-115">Zaúčtujte deník.</span><span class="sxs-lookup"><span data-stu-id="33cf7-115">Post the journal.</span></span>

## <a name="to-post-a-transfer-between-bank-accounts-with-different-currency-codes"></a><span data-ttu-id="33cf7-116">Zaúčtování převodu mezi bankovními účty s různými kódy měn</span><span class="sxs-lookup"><span data-stu-id="33cf7-116">To post a transfer between bank accounts with different currency codes</span></span>
<span data-ttu-id="33cf7-117">Chcete-li převádět finanční prostředky mezi bankovními účty, které používají různé měny, musíte zaúčtovat dva řádky finančního deníku.</span><span class="sxs-lookup"><span data-stu-id="33cf7-117">To transfer funds between bank accounts that use different currencies, you must post two general journal lines.</span></span>

1. <span data-ttu-id="33cf7-118">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="33cf7-118">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="33cf7-119">Vytvořte dva řádky deníku a vyplňte pole **Zúčtovací datum** a **Číslo dokladu**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-119">Create two journal lines, and fill in the **Posting Date** and **Document No.** fields.</span></span>
3. <span data-ttu-id="33cf7-120">Na prvním řádku deníku v poli **Typ** vyberte **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-120">On the first journal line, in the **Type** field, select **Bank Account**.</span></span>
4. <span data-ttu-id="33cf7-121">V poli **Číslo účtu**, vyberte bankovní účet, ze kterého chcete peníze převést.</span><span class="sxs-lookup"><span data-stu-id="33cf7-121">In the **Account No.** field, select the bank account from which you want to transfer the funds.</span></span>
5. <span data-ttu-id="33cf7-122">V poli **Částka** zadejte částku v měně bankovního účtu.</span><span class="sxs-lookup"><span data-stu-id="33cf7-122">In the **Amount** field, enter the amount in the currency of the bank account.</span></span> <span data-ttu-id="33cf7-123">Zadejte částku Dal se znaménkem mínus.</span><span class="sxs-lookup"><span data-stu-id="33cf7-123">Enter credit amounts with a minus sign.</span></span> <span data-ttu-id="33cf7-124">Zadejte částku MD se znaménkem mínus.</span><span class="sxs-lookup"><span data-stu-id="33cf7-124">Enter debit amounts without a minus sign.</span></span>
6. <span data-ttu-id="33cf7-125">V poli **Typ protiúčtu** vyberte **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-125">In the **Bal. Account Type** field, select **Bank Account**.</span></span>
7. <span data-ttu-id="33cf7-126">V poli **Typ protiúčtu** vyberte bankovní účet, na který chcete peníze převést.</span><span class="sxs-lookup"><span data-stu-id="33cf7-126">In the **Bal. Account No.** field, select the bank account to which you want to transfer the funds.</span></span>
8. <span data-ttu-id="33cf7-127">Na druhém řádku deníku v poli **Typ** vyberte **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-127">On the second journal line, in the **Type** field, select **Bank Account**.</span></span>
9. <span data-ttu-id="33cf7-128">V poli **Číslo účtu** vyberte bankovní účet, na který chcete peníze převést.</span><span class="sxs-lookup"><span data-stu-id="33cf7-128">In the **Account No.** field, select the bank account to which you want to transfer the funds.</span></span>
10. <span data-ttu-id="33cf7-129">V poli **Částka** zadejte částku v měně bankovního účtu.</span><span class="sxs-lookup"><span data-stu-id="33cf7-129">In the **Amount** field, enter the amount in the currency of the bank account.</span></span> <span data-ttu-id="33cf7-130">Zadejte částku Dal se znaménkem mínus.</span><span class="sxs-lookup"><span data-stu-id="33cf7-130">Enter credit amounts with a minus sign.</span></span> <span data-ttu-id="33cf7-131">Zadejte částku MD se znaménkem mínus.</span><span class="sxs-lookup"><span data-stu-id="33cf7-131">Enter debit amounts without a minus sign.</span></span>
11. <span data-ttu-id="33cf7-132">V poli **Typ protiúčtu** vyberte **Bankovní účet**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-132">In the **Bal. Account Type** field, select **Bank Account**.</span></span>  
12. <span data-ttu-id="33cf7-133">V poli **Typ protiúčtu** vyberte bankovní účet, na který chcete peníze převést.</span><span class="sxs-lookup"><span data-stu-id="33cf7-133">In the **Bal. Account No.** field, select the bank account from which you want to transfer the funds.</span></span>

    > [!NOTE]  
>   <span data-ttu-id="33cf7-134">Pokud se kurzy používané v deníku liší od směnných kurzů v okně **Směnné kurzy**, zadejte třetí řádek pro kurzový zisk nebo ztrátu.</span><span class="sxs-lookup"><span data-stu-id="33cf7-134">If the exchange rates used in the journal are different than the exchange rates in the **Currency Exchange Rates** window, enter a third line for the exchange rate gain or loss.</span></span> <span data-ttu-id="33cf7-135">Zadejte **Finanční účet** v poli **Typ účtu**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-135">Enter **G/L Account** in the **Account Type** field.</span></span> <span data-ttu-id="33cf7-136">Zadejte číslo finančního účtu pro kurzový zisk nebo ztrátu v poli **Číslo účtu**.</span><span class="sxs-lookup"><span data-stu-id="33cf7-136">Enter the G/L account number for exchange rate gain or loss in the **Account No.** field.</span></span> <span data-ttu-id="33cf7-137">Zadejte kurzový zisk nebo ztrátu v poli **Částka** s nebo bez znaménka mínus pro částku Dal a MD.</span><span class="sxs-lookup"><span data-stu-id="33cf7-137">Enter the exchange rate gain or loss in the **Amount** field with or without a minus sign for credits and debits respectively.</span></span>
13. <span data-ttu-id="33cf7-138">Zaúčtujte deník.</span><span class="sxs-lookup"><span data-stu-id="33cf7-138">Post the journal.</span></span>

## <a name="see-also"></a><span data-ttu-id="33cf7-139">Viz také</span><span class="sxs-lookup"><span data-stu-id="33cf7-139">See Also</span></span>
[<span data-ttu-id="33cf7-140">Správa bankovních účtů</span><span class="sxs-lookup"><span data-stu-id="33cf7-140">Managing Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="33cf7-141">Nastavení bankovnictví</span><span class="sxs-lookup"><span data-stu-id="33cf7-141">Setting Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="33cf7-142">Práce s finančními deníky</span><span class="sxs-lookup"><span data-stu-id="33cf7-142">Working with General Journals</span></span>](ui-work-general-journals.md)  
<span data-ttu-id="33cf7-143">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="33cf7-143">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

