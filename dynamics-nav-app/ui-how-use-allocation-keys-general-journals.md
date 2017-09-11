---
title: "Návod: Použití rozdělovacích klíčů ve finančních denících."
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: ca21d9d129dbc98d75371d1b2b7a0ffad4aa2848
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

#  <a name="how-to-use-allocation-keys-in-general-journals"></a><span data-ttu-id="76a5d-102">Návod: Použití rozdělovacích klíčů ve finančních denících.</span><span class="sxs-lookup"><span data-stu-id="76a5d-102">How to: Use Allocation Keys in General Journals</span></span>
<span data-ttu-id="76a5d-103">Když zaúčtováváte finanční deník, můžete přidělit  položku několika různým účtům. </span><span class="sxs-lookup"><span data-stu-id="76a5d-103">You can allocate an entry in a general journal to several different accounts when you post the journal.</span></span> <span data-ttu-id="76a5d-104">Rozdělení může být provedeno podle množství, procent nebo částky.</span><span class="sxs-lookup"><span data-stu-id="76a5d-104">The allocation can be made by quantity, percentage, or amount.</span></span>

## <a name="to-set-up-allocation-keys"></a><span data-ttu-id="76a5d-105">Nastavení rozdělovacích klíčů</span><span class="sxs-lookup"><span data-stu-id="76a5d-105">To set up allocation keys</span></span> 
1. <span data-ttu-id="76a5d-106">V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Periodický finanční deník**, a pak zvolte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="76a5d-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="76a5d-107">Zvolte pole **Název listu** a otevřete okno **Listy finančního deníku**.</span><span class="sxs-lookup"><span data-stu-id="76a5d-107">Choose the **Batch Name** field to open the **General Journal Batches** window.</span></span>
3. <span data-ttu-id="76a5d-108">Můžete buď upravit rozdělení v existující dávce v seznamu nebo vytvořit novou dávku s přiděleními.</span><span class="sxs-lookup"><span data-stu-id="76a5d-108">You can either modify allocations on an existing batch in the list or create a new batch with allocations.</span></span>
  * <span data-ttu-id="76a5d-109">Chcete-li vytvořit novou dávku, zvolte akci **Nový** a přejděte k dalšímu kroku.</span><span class="sxs-lookup"><span data-stu-id="76a5d-109">To create a new batch, choose the **New** action, and go to the next step.</span></span>
  * <span data-ttu-id="76a5d-110">Chcete-li změnit rozdělení existujícího deníku, vyberte deník a přejděte ke kroku 7.</span><span class="sxs-lookup"><span data-stu-id="76a5d-110">To change the allocations of an existing journal, select the journal and go to step 7.</span></span>    
4. <span data-ttu-id="76a5d-111">Do pole **Název** zadejte název dávky, například ČIŠTĚNÍ.</span><span class="sxs-lookup"><span data-stu-id="76a5d-111">In the **Name** field, enter a name for the batch, such as CLEANING.</span></span> <span data-ttu-id="76a5d-112">Do pole **Popis** zadejte popis, například Deník výdajů za úklid.</span><span class="sxs-lookup"><span data-stu-id="76a5d-112">In the **Description** field, enter a description, such as Cleaning Expenses Journal.</span></span>
5. <span data-ttu-id="76a5d-113">Až budete hotoví, zavřete okno.</span><span class="sxs-lookup"><span data-stu-id="76a5d-113">When you are done, close the window.</span></span> <span data-ttu-id="76a5d-114">Otevře se nový prázdný periodický deník.</span><span class="sxs-lookup"><span data-stu-id="76a5d-114">A new, empty recurring journal opens.</span></span> 
6. <span data-ttu-id="76a5d-115">Vyplňte pole na řádku.</span><span class="sxs-lookup"><span data-stu-id="76a5d-115">Fill in the fields in the line.</span></span>
7. <span data-ttu-id="76a5d-116">Zvolte akci **Rozdělení**.</span><span class="sxs-lookup"><span data-stu-id="76a5d-116">Choose the **Allocations** action.</span></span> 
8. <span data-ttu-id="76a5d-117">Přidejte řádek pro každé rozdělení.</span><span class="sxs-lookup"><span data-stu-id="76a5d-117">Add a line for each allocation.</span></span> <span data-ttu-id="76a5d-118">Buď musíte vyplnit pole **Rozdělení %**, **Rozdělené množství** nebo **Částka**.</span><span class="sxs-lookup"><span data-stu-id="76a5d-118">You must fill in either the **Allocation %**, **Allocation Quantity**, or **Amount** field.</span></span> <span data-ttu-id="76a5d-119">Musíte také vyplnit pole **Číslo účtu**</span><span class="sxs-lookup"><span data-stu-id="76a5d-119">You must also fill in the **Account No.**</span></span> <span data-ttu-id="76a5d-120">a pokud rozdělujete transakci mezi více globálních dimenzí i pole globální dimenze.</span><span class="sxs-lookup"><span data-stu-id="76a5d-120">field and, if you are allocating the transaction among global dimensions, the global dimension fields.</span></span>
9. <span data-ttu-id="76a5d-121">Pokud na řádek zadáte procento, částka v poli **Částka** se vypočítá automaticky.</span><span class="sxs-lookup"><span data-stu-id="76a5d-121">If you enter a percentage on a line, the amount in the **Amount** field is calculated automatically.</span></span> <span data-ttu-id="76a5d-122">Tyto částky mají opačné znaménko oproti celkové částce v poli **Částka** v periodickém deníku.</span><span class="sxs-lookup"><span data-stu-id="76a5d-122">These amounts have the opposite sign from the total amount in the **Amount** field in the recurring journal.</span></span>
10. <span data-ttu-id="76a5d-123">Po zadání řádků rozdělení vyberte **OK** k vrácení se do okna **Periodický finanční deník**.</span><span class="sxs-lookup"><span data-stu-id="76a5d-123">After entering the allocations lines, choose **OK** to return to the **Recurring General Journal** window.</span></span> <span data-ttu-id="76a5d-124">Pole **Částka rozdělení (CZK)** je vyplněno a odpovídá poli **Částka**.</span><span class="sxs-lookup"><span data-stu-id="76a5d-124">The **Allocated Amt. (USD)** field is filled in and matches the **Amount** field.</span></span>
11. <span data-ttu-id="76a5d-125">Zaúčtovat deník.</span><span class="sxs-lookup"><span data-stu-id="76a5d-125">Post the journal.</span></span>

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a><span data-ttu-id="76a5d-126">Změna rozdělovacího klíče, který již byl nastaven.</span><span class="sxs-lookup"><span data-stu-id="76a5d-126">To change an allocation key that has already been set up</span></span>
1. <span data-ttu-id="76a5d-127">V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Periodický finanční deník**, a pak zvolte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="76a5d-127">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="76a5d-128">V okně **Periodický finanční deník** vyberte deník s rozdělením.</span><span class="sxs-lookup"><span data-stu-id="76a5d-128">In the **Recurring General Journal** window, select the journal with the allocation.</span></span>
3. <span data-ttu-id="76a5d-129">Vyberte řádek s rozdělením a poté zvolte akci **Rozdělení**.</span><span class="sxs-lookup"><span data-stu-id="76a5d-129">Choose the line with the allocation, and then choose **Allocations** action.</span></span>
4. <span data-ttu-id="76a5d-130">Změňte příslušná pole a zavřete okno.</span><span class="sxs-lookup"><span data-stu-id="76a5d-130">Change the relevant fields, and close the window.</span></span>

## <a name="see-also"></a><span data-ttu-id="76a5d-131">Viz také</span><span class="sxs-lookup"><span data-stu-id="76a5d-131">See Also</span></span>
[<span data-ttu-id="76a5d-132">Práce s finančními deníky</span><span class="sxs-lookup"><span data-stu-id="76a5d-132">Work With General Journals</span></span>](ui-work-general-journals.md)  
[<span data-ttu-id="76a5d-133">Zaúčtovat doklady a deníky</span><span class="sxs-lookup"><span data-stu-id="76a5d-133">Post Documents and Journals</span></span>](ui-post-documents-journals.md)




