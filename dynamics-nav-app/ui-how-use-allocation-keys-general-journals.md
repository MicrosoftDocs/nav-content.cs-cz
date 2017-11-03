---
title: "Návod: Použití klíče rozdělení ve finančních denících "
description: "Přečtěte si, jak můžete v denících používat klíče rozdělení."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cost accounting
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3d3944d5f7e9bfe5390fd63b2ae1d05f62efab49
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-use-allocation-keys-in-general-journals"></a><span data-ttu-id="da2f1-103">Návod: Použití klíče rozdělení ve finančních denících</span><span class="sxs-lookup"><span data-stu-id="da2f1-103">How to: Use Allocation Keys in General Journals</span></span>
<span data-ttu-id="da2f1-104">Když zaúčtováváte finanční deník, můžete přidělit  položku několika různým účtům.</span><span class="sxs-lookup"><span data-stu-id="da2f1-104">You can allocate an entry in a general journal to several different accounts when you post the journal.</span></span> <span data-ttu-id="da2f1-105">Rozdělení může být provedeno podle množství, procent nebo částky.</span><span class="sxs-lookup"><span data-stu-id="da2f1-105">The allocation can be made by quantity, percentage, or amount.</span></span>

## <a name="to-set-up-allocation-keys"></a><span data-ttu-id="da2f1-106">Nastavení rozdělovacích klíčů</span><span class="sxs-lookup"><span data-stu-id="da2f1-106">To set up allocation keys</span></span>
1. <span data-ttu-id="da2f1-107">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Opakovaný finanční deník** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="da2f1-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="da2f1-108">Zvolte pole **Název listu** a otevřete okno **Listy finančního deníku**.</span><span class="sxs-lookup"><span data-stu-id="da2f1-108">Choose the **Batch Name** field to open the **General Journal Batches** window.</span></span>
3. <span data-ttu-id="da2f1-109">Můžete buď upravit rozdělení v existující dávce v seznamu nebo vytvořit novou dávku s přiděleními.</span><span class="sxs-lookup"><span data-stu-id="da2f1-109">You can either modify allocations on an existing batch in the list or create a new batch with allocations.</span></span>
   * <span data-ttu-id="da2f1-110">Chcete-li vytvořit novou dávku, zvolte akci **Nový** a přejděte k dalšímu kroku.</span><span class="sxs-lookup"><span data-stu-id="da2f1-110">To create a new batch, choose the **New** action, and go to the next step.</span></span>
   * <span data-ttu-id="da2f1-111">Chcete-li změnit rozdělení existujícího deníku, vyberte deník a přejděte ke kroku 7.</span><span class="sxs-lookup"><span data-stu-id="da2f1-111">To change the allocations of an existing journal, select the journal and go to step 7.</span></span>    
4. <span data-ttu-id="da2f1-112">Do pole **Název** zadejte název dávky, například ČIŠTĚNÍ.</span><span class="sxs-lookup"><span data-stu-id="da2f1-112">In the **Name** field, enter a name for the batch, such as CLEANING.</span></span> <span data-ttu-id="da2f1-113">Do pole **Popis** zadejte popis, například Deník výdajů za úklid.</span><span class="sxs-lookup"><span data-stu-id="da2f1-113">In the **Description** field, enter a description, such as Cleaning Expenses Journal.</span></span>
5. <span data-ttu-id="da2f1-114">Až budete hotoví, zavřete okno.</span><span class="sxs-lookup"><span data-stu-id="da2f1-114">When you are done, close the window.</span></span> <span data-ttu-id="da2f1-115">Otevře se nový prázdný periodický deník.</span><span class="sxs-lookup"><span data-stu-id="da2f1-115">A new, empty recurring journal opens.</span></span>
6. <span data-ttu-id="da2f1-116">Vyplňte pole na řádku.</span><span class="sxs-lookup"><span data-stu-id="da2f1-116">Fill in the fields on the line.</span></span>
7. <span data-ttu-id="da2f1-117">Zvolte akci **Rozdělení**.</span><span class="sxs-lookup"><span data-stu-id="da2f1-117">Choose the **Allocations** action.</span></span>
8. <span data-ttu-id="da2f1-118">Přidejte řádek pro každé rozdělení.</span><span class="sxs-lookup"><span data-stu-id="da2f1-118">Add a line for each allocation.</span></span> <span data-ttu-id="da2f1-119">Buď musíte vyplnit pole **Rozdělení %**, **Rozdělené množství** nebo **Částka**.</span><span class="sxs-lookup"><span data-stu-id="da2f1-119">You must fill in either the **Allocation %**, **Allocation Quantity**, or **Amount** field.</span></span> <span data-ttu-id="da2f1-120">Musíte také vyplnit pole **Číslo účtu**, a pokud rozdělujete transakci mezi více globálních dimenzí i pole globální dimenze.</span><span class="sxs-lookup"><span data-stu-id="da2f1-120">You must also fill in the **Account No.** field and, if you are allocating the transaction among global dimensions, the global dimension fields.</span></span>
9. <span data-ttu-id="da2f1-121">Pokud na řádek zadáte procento, částka v poli **Částka** se vypočítá automaticky.</span><span class="sxs-lookup"><span data-stu-id="da2f1-121">If you enter a percentage on a line, the amount in the **Amount** field is calculated automatically.</span></span> <span data-ttu-id="da2f1-122">Tyto částky mají opačné znaménko oproti celkové částce v poli **Částka** v periodickém deníku.</span><span class="sxs-lookup"><span data-stu-id="da2f1-122">These amounts have the opposite sign from the total amount in the **Amount** field in the recurring journal.</span></span>
10. <span data-ttu-id="da2f1-123">Po zadání řádků rozdělení vyberte **OK** k vrácení se do okna **Periodický finanční deník**.</span><span class="sxs-lookup"><span data-stu-id="da2f1-123">After entering the allocations lines, choose **OK** to return to the **Recurring General Journal** window.</span></span> <span data-ttu-id="da2f1-124">Pole **Částka rozdělení (CZK)** je vyplněno a odpovídá poli **Částka**.</span><span class="sxs-lookup"><span data-stu-id="da2f1-124">The **Allocated Amt. (USD)** field is filled in and matches the **Amount** field.</span></span>
11. <span data-ttu-id="da2f1-125">Zaúčtovat deník.</span><span class="sxs-lookup"><span data-stu-id="da2f1-125">Post the journal.</span></span>

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a><span data-ttu-id="da2f1-126">Změna rozdělovacího klíče, který již byl nastaven.</span><span class="sxs-lookup"><span data-stu-id="da2f1-126">To change an allocation key that has already been set up</span></span>
1. <span data-ttu-id="da2f1-127">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Opakovaný finanční deník** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="da2f1-127">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="da2f1-128">V okně **Periodický finanční deník** vyberte deník s rozdělením.</span><span class="sxs-lookup"><span data-stu-id="da2f1-128">In the **Recurring General Journal** window, select the journal with the allocation.</span></span>
3. <span data-ttu-id="da2f1-129">Vyberte řádek s rozdělením a poté zvolte akci **Rozdělení**.</span><span class="sxs-lookup"><span data-stu-id="da2f1-129">Choose the line with the allocation, and then choose **Allocations** action.</span></span>
4. <span data-ttu-id="da2f1-130">Změňte pole a poté klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="da2f1-130">Change the relevant fields, and then choose the **OK** button.</span></span>

## <a name="see-also"></a><span data-ttu-id="da2f1-131">Viz také</span><span class="sxs-lookup"><span data-stu-id="da2f1-131">See Also</span></span>
[<span data-ttu-id="da2f1-132">Práce s finančními deníky</span><span class="sxs-lookup"><span data-stu-id="da2f1-132">Working with General Journals</span></span>](ui-work-general-journals.md)  
[<span data-ttu-id="da2f1-133">Účtování dokladů a deníků</span><span class="sxs-lookup"><span data-stu-id="da2f1-133">Posting Documents and Journals</span></span>](ui-post-documents-journals.md)  
<span data-ttu-id="da2f1-134">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="da2f1-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

