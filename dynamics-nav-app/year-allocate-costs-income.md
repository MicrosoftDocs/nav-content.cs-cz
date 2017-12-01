---
title: "Přehled úloh k rozdělení nákladů a výnosů"
description: "Popisuje úlohy při přidělování položky do finančního deníku několika účtům při účtování deníku."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: e7d6aed9a57bb2ddd20cb45fd4d68ec0a30eb61a
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-allocate-costs-and-income"></a><span data-ttu-id="f2674-103">Návod: Rozdělte náklady a výnosy</span><span class="sxs-lookup"><span data-stu-id="f2674-103">How to: Allocate Costs and Income</span></span>
<span data-ttu-id="f2674-104">Můžete rozdělit záznam při účtování ve finančním deníku na několik různých účtů.</span><span class="sxs-lookup"><span data-stu-id="f2674-104">You can allocate an entry in a general journal to several different accounts when you post the journal.</span></span> <span data-ttu-id="f2674-105">Rozdělení může být provedeno třemi různými způsoby:</span><span class="sxs-lookup"><span data-stu-id="f2674-105">The allocation can be made by three different methods:</span></span>

* <span data-ttu-id="f2674-106">Množství</span><span class="sxs-lookup"><span data-stu-id="f2674-106">Quantity</span></span>
* <span data-ttu-id="f2674-107">Procento (%)</span><span class="sxs-lookup"><span data-stu-id="f2674-107">Percentage (%)</span></span>
* <span data-ttu-id="f2674-108">Částka</span><span class="sxs-lookup"><span data-stu-id="f2674-108">Amount</span></span>

<span data-ttu-id="f2674-109">Funkci rozdělení lze použít v periodických finančních denících a denících dlouhodobého majetku.</span><span class="sxs-lookup"><span data-stu-id="f2674-109">The allocation features can be used with recurring general journals and in fixed assets journals.</span></span>
<!--You can also distribute the cost or revenue of a line to an intercompany partner when you post a sales or purchase document. When you post the document, a line will be posted in your general journal, and a corresponding line will be created in the intercompany outbox.-->

<span data-ttu-id="f2674-110">Následující procedury popisují, jak připravit přidělování nákladů do opakovaných finančních deníků definováním klíčů přidělení.</span><span class="sxs-lookup"><span data-stu-id="f2674-110">The following procedures describe how to prepare to allocate costs in a recurring general journal by defining allocation keys.</span></span> <span data-ttu-id="f2674-111">Když jsou definovány klíče přidělení, dokončíte a publikujete deník jako každý jiný opakovaný finanční deník.</span><span class="sxs-lookup"><span data-stu-id="f2674-111">When allocation keys are defined, you complete and post the journal like any other recurring general journal.</span></span> <span data-ttu-id="f2674-112">Pro další informace se podívejte na [Práce s finančními deníky](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="f2674-112">For more information, see [Working with General Journals](ui-work-general-journals.md).</span></span>

## <a name="to-set-up-allocation-keys"></a><span data-ttu-id="f2674-113">Nastavení rozdělovacích klíčů</span><span class="sxs-lookup"><span data-stu-id="f2674-113">To set up allocation keys</span></span>
<span data-ttu-id="f2674-114">Můžete rozdělit záznam při účtování v opakovaném finančním deníku na několik různých účtů.</span><span class="sxs-lookup"><span data-stu-id="f2674-114">You can allocate an entry in a recurring general journal to several different accounts when you post the journal.</span></span> <span data-ttu-id="f2674-115">Rozdělení může být provedeno podle množství, procent nebo částky.</span><span class="sxs-lookup"><span data-stu-id="f2674-115">The allocation can be made by quantity, percentage, or amount.</span></span>
1. <span data-ttu-id="f2674-116">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Opakovaný finanční deník** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="f2674-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="f2674-117">Zvolte pole **Název listu** a otevřete okno **Listy finančního deníku**.</span><span class="sxs-lookup"><span data-stu-id="f2674-117">Choose the **Batch Name** field to open the **General Journal Batches** window.</span></span>
3. <span data-ttu-id="f2674-118">Můžete buď upravit rozdělení v existující dávce v seznamu nebo vytvořit novou dávku s přiděleními.</span><span class="sxs-lookup"><span data-stu-id="f2674-118">You can either modify allocations on an existing batch in the list or create a new batch with allocations.</span></span>
   * <span data-ttu-id="f2674-119">Chcete-li vytvořit novou dávku, zvolte akci **Nový** a přejděte k dalšímu kroku.</span><span class="sxs-lookup"><span data-stu-id="f2674-119">To create a new batch, choose the **New** action, and go to the next step.</span></span>
   * <span data-ttu-id="f2674-120">Chcete-li změnit rozdělení existujícího deníku, vyberte deník a přejděte ke kroku 7.</span><span class="sxs-lookup"><span data-stu-id="f2674-120">To change the allocations of an existing journal, select the journal and go to step 7.</span></span>    
4. <span data-ttu-id="f2674-121">Do pole **Název** zadejte název dávky, například ČIŠTĚNÍ.</span><span class="sxs-lookup"><span data-stu-id="f2674-121">In the **Name** field, enter a name for the batch, such as CLEANING.</span></span> <span data-ttu-id="f2674-122">Do pole **Popis** zadejte popis, například Deník výdajů za úklid.</span><span class="sxs-lookup"><span data-stu-id="f2674-122">In the **Description** field, enter a description, such as Cleaning Expenses Journal.</span></span>
5. <span data-ttu-id="f2674-123">Až budete hotoví, zavřete okno.</span><span class="sxs-lookup"><span data-stu-id="f2674-123">When you are done, close the window.</span></span> <span data-ttu-id="f2674-124">Otevře se nový prázdný periodický deník.</span><span class="sxs-lookup"><span data-stu-id="f2674-124">A new, empty recurring journal opens.</span></span>
6. <span data-ttu-id="f2674-125">Vyplňte pole na řádku.</span><span class="sxs-lookup"><span data-stu-id="f2674-125">Fill in the fields on the line.</span></span>
7. <span data-ttu-id="f2674-126">Zvolte akci **Rozdělení**.</span><span class="sxs-lookup"><span data-stu-id="f2674-126">Choose the **Allocations** action.</span></span>
8. <span data-ttu-id="f2674-127">Přidejte řádek pro každé rozdělení.</span><span class="sxs-lookup"><span data-stu-id="f2674-127">Add a line for each allocation.</span></span> <span data-ttu-id="f2674-128">Buď musíte vyplnit pole **Rozdělení %**, **Rozdělené množství** nebo **Částka**.</span><span class="sxs-lookup"><span data-stu-id="f2674-128">You must fill in either the **Allocation %**, **Allocation Quantity**, or **Amount** field.</span></span> <span data-ttu-id="f2674-129">Musíte také vyplnit pole **Číslo účtu**, a pokud rozdělujete transakci mezi více globálních dimenzí i pole globální dimenze.</span><span class="sxs-lookup"><span data-stu-id="f2674-129">You must also fill in the **Account No.** field and, if you are allocating the transaction among global dimensions, the global dimension fields.</span></span>
9. <span data-ttu-id="f2674-130">Pokud na řádek zadáte procento, částka v poli **Částka** se vypočítá automaticky.</span><span class="sxs-lookup"><span data-stu-id="f2674-130">If you enter a percentage on a line, the amount in the **Amount** field is calculated automatically.</span></span> <span data-ttu-id="f2674-131">Tyto částky mají opačné znaménko oproti celkové částce v poli **Částka** v periodickém deníku.</span><span class="sxs-lookup"><span data-stu-id="f2674-131">These amounts have the opposite sign from the total amount in the **Amount** field in the recurring journal.</span></span>
10. <span data-ttu-id="f2674-132">Po zadání řádků rozdělení vyberte **OK** k vrácení se do okna **Periodický finanční deník**.</span><span class="sxs-lookup"><span data-stu-id="f2674-132">After entering the allocations lines, choose **OK** to return to the **Recurring General Journal** window.</span></span> <span data-ttu-id="f2674-133">Pole **Částka rozdělení (CZK)** je vyplněno a odpovídá poli **Částka**.</span><span class="sxs-lookup"><span data-stu-id="f2674-133">The **Allocated Amt. (USD)** field is filled in and matches the **Amount** field.</span></span>
11. <span data-ttu-id="f2674-134">Zaúčtovat deník.</span><span class="sxs-lookup"><span data-stu-id="f2674-134">Post the journal.</span></span>

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a><span data-ttu-id="f2674-135">Změna rozdělovacího klíče, který již byl nastaven.</span><span class="sxs-lookup"><span data-stu-id="f2674-135">To change an allocation key that has already been set up</span></span>
1. <span data-ttu-id="f2674-136">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Opakovaný finanční deník** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="f2674-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="f2674-137">V okně **Periodický finanční deník** vyberte deník s rozdělením.</span><span class="sxs-lookup"><span data-stu-id="f2674-137">In the **Recurring General Journal** window, select the journal with the allocation.</span></span>
3. <span data-ttu-id="f2674-138">Vyberte řádek s rozdělením a poté zvolte akci **Rozdělení**.</span><span class="sxs-lookup"><span data-stu-id="f2674-138">Choose the line with the allocation, and then choose **Allocations** action.</span></span>
4. <span data-ttu-id="f2674-139">Změňte pole a poté klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="f2674-139">Change the relevant fields, and then choose the **OK** button.</span></span>

## <a name="see-also"></a><span data-ttu-id="f2674-140">Viz také</span><span class="sxs-lookup"><span data-stu-id="f2674-140">See Also</span></span>
[<span data-ttu-id="f2674-141">Uzavřít roky a období.</span><span class="sxs-lookup"><span data-stu-id="f2674-141">Closing Years and Periods</span></span>](year-close-years-periods.md)  
<span data-ttu-id="f2674-142">[Práce s finančními deníky](ui-work-general-journals.md)  </span><span class="sxs-lookup"><span data-stu-id="f2674-142">[Working with General Journals](ui-work-general-journals.md)  </span></span>  
<span data-ttu-id="f2674-143">[Účtování dokladů a deníků](ui-post-documents-journals.md)  </span><span class="sxs-lookup"><span data-stu-id="f2674-143">[Posting Documents and Journals](ui-post-documents-journals.md)  </span></span>  
<span data-ttu-id="f2674-144">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f2674-144">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

