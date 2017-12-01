---
title: "Volitelné aktivity pro uzavírání období"
description: "Toto téma popisuje volitelné procesy a činnosti pro uzavírání účetních období v Dynamics NAV."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, aging, creditor payments, vendor payments
ms.date: 06/19/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 2d6754559e35ab1765bd34704a975dce0575c108
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="overview-of-tasks-to-close-accounting-periods"></a><span data-ttu-id="b0c5a-103">Přehled úkolů pro uzavření účetních období</span><span class="sxs-lookup"><span data-stu-id="b0c5a-103">Overview of Tasks to Close Accounting Periods</span></span>
[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="b0c5a-104"> vás nenutí uzavřít období, avšak existuje mnoho aktivit týkajících se ukončení období, které mohou být v pokud chcete.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-104"> does not force you to close periods, however, there are many period-end (month-end) activities that you can do.</span></span> <span data-ttu-id="b0c5a-105">Toto téma poskytuje přehled o volitelných procesech a aktivitách pro uzavírací období.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-105">This topic provides an overview of optional processes and activities for closing periods.</span></span>  

## <a name="general-ledger"></a><span data-ttu-id="b0c5a-106">Hlavní kniha</span><span class="sxs-lookup"><span data-stu-id="b0c5a-106">General Ledger</span></span>
* <span data-ttu-id="b0c5a-107">Určete systémové a uživatelské období zaúčtování.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-107">Specify system-wide and user-specific posting periods.</span></span>  

    <span data-ttu-id="b0c5a-108">Toto určuje data, mezi kterými je povoleno zaúčtovat.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-108">This specifies the dates between which you allow posting.</span></span> <span data-ttu-id="b0c5a-109">V závislosti na vaší firmě budete chtít povolit přidávání příspěvků na začátku nebo do konce.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-109">Depending on your business, you may want to allow posting at the start of the period, or toward the end.</span></span> <span data-ttu-id="b0c5a-110">Další informace naleznete v [Návod: Specifikovat účetní období](finance-how-specify-posting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="b0c5a-110">For more information, see [How to: Specify Posting Periods](finance-how-specify-posting-periods.md).</span></span>  
* <span data-ttu-id="b0c5a-111">Proveďte všechny potřebné úpravy v hlavní knize.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-111">Make all necessary G/L adjustments.</span></span>  
* <span data-ttu-id="b0c5a-112">Aktualizujte a zaúčtujte periodické deníky.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-112">Update and post Recurring Journals.</span></span>  
  <!--* Process Consolidations-->
* <span data-ttu-id="b0c5a-113">Spusťte účetní schémata následovně:</span><span class="sxs-lookup"><span data-stu-id="b0c5a-113">Run account schedules as follows:</span></span>  
  * <span data-ttu-id="b0c5a-114">Otevřete okno **Účetní schéma** a zvolte akci **Tisk**.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-114">Open the **Account Schedule** window, and then choose the **Print** action.</span></span>  

## <a name="sales-and-receivables"></a><span data-ttu-id="b0c5a-115">Prodej a pohledávky</span><span class="sxs-lookup"><span data-stu-id="b0c5a-115">Sales and Receivables</span></span>
* <span data-ttu-id="b0c5a-116">Zaúčtujte všechny objednávky, faktury, dobropisy a objednávky prodejní vratky.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-116">Post all sales orders, invoices, credit memos, and return orders.</span></span>  
* <span data-ttu-id="b0c5a-117">Zaúčtujte všechny deníky přijaté hotovosti.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-117">Post all cash receipt journals.</span></span>  
* <span data-ttu-id="b0c5a-118">Aktualizujte a zaúčtujte periodické deníky, které se vztahují k prodeji a pohledávkám.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-118">Update and post recurring journals that are related to sales and receivables.</span></span>  
* <span data-ttu-id="b0c5a-119">Odsouhlaste pohledávky s hlavní účetní knihou.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-119">Reconcile accounts receivable to the general ledger.</span></span>  
* <span data-ttu-id="b0c5a-120">Spusťte dávkovou úlohu **Odstranit fakt. prod. objednávky**.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-120">Run the **Delete Invoiced Sales Orders** batch job.</span></span>  

## <a name="purchases-and-payables"></a><span data-ttu-id="b0c5a-121">Nákupy a závazky</span><span class="sxs-lookup"><span data-stu-id="b0c5a-121">Purchases and Payables</span></span>
* <span data-ttu-id="b0c5a-122">Zaúčtujte všechny objednávky, faktury, dobropisy a pobjednávky prodejní vratky.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-122">Post all purchase orders, invoices, credit memos, and return orders.</span></span>  
* <span data-ttu-id="b0c5a-123">Zaúčtujte všechny deníky plateb.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-123">Post all payment journals.</span></span>  
* <span data-ttu-id="b0c5a-124">Aktualizujte a zaúčtujte periodické deníky, které se vztahují k nákupům a závazkům.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-124">Update and post recurring journals that are related to purchases & payables.</span></span>  
* <span data-ttu-id="b0c5a-125">Spusťte sestavu **Splatné závazky** a odsouhlaste účty závazků s hlavní knihou.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span></span>  
* <span data-ttu-id="b0c5a-126">Spusťte dávkovou úlohu **Odstranit fakt. nák. objednávky** .</span><span class="sxs-lookup"><span data-stu-id="b0c5a-126">Run the **Delete Invoiced Purchase Orders** batch job.</span></span>  

<span data-ttu-id="b0c5a-127">Dlouhodobý majetek</span><span class="sxs-lookup"><span data-stu-id="b0c5a-127">Fixed Assets</span></span>
* <span data-ttu-id="b0c5a-128">Všechny náklady na údržbu byly zveřejněny prostřednictvím časopisů nebo faktur s pevnými částkami.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-128">Post all maintenance costs have been posted through the fixed asset journals or invoices.</span></span>
* <span data-ttu-id="b0c5a-129">Zaúčtovat adjustace.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-129">Post adjustments.</span></span>
* <span data-ttu-id="b0c5a-130">Zaúčtovat ocenění.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-130">Post appreciation.</span></span>
* <span data-ttu-id="b0c5a-131">Zaúčtovat odpisy.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-131">Post depreciation.</span></span>
* <span data-ttu-id="b0c5a-132">Aktualizujte a publikujte opakující se deník dlouhodobého majetku.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-132">Update and post the recurring fixed asset journal.</span></span>

<span data-ttu-id="b0c5a-133">Mezipodnikový</span><span class="sxs-lookup"><span data-stu-id="b0c5a-133">Intercompany</span></span>
* <span data-ttu-id="b0c5a-134">Proces mezipodnikových transakcí</span><span class="sxs-lookup"><span data-stu-id="b0c5a-134">Process Intercompany Transactions</span></span>

## <a name="calculate-and-process-sales-tax"></a><span data-ttu-id="b0c5a-135">Vypočítat a zpracovat prodejní daň</span><span class="sxs-lookup"><span data-stu-id="b0c5a-135">Calculate and Process Sales Tax</span></span>
* <span data-ttu-id="b0c5a-136">Dokončete daňové výkazy.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-136">Complete Tax Statements.</span></span>  

## <a name="see-also"></a><span data-ttu-id="b0c5a-137">Viz také</span><span class="sxs-lookup"><span data-stu-id="b0c5a-137">See Also</span></span>
[<span data-ttu-id="b0c5a-138">Uzavřít roky a období.</span><span class="sxs-lookup"><span data-stu-id="b0c5a-138">Closing Years and Periods</span></span>](year-close-years-periods.md)  
[<span data-ttu-id="b0c5a-139">Uzavřít knihy</span><span class="sxs-lookup"><span data-stu-id="b0c5a-139">Closing Books</span></span>](year-close-books.md)  
<span data-ttu-id="b0c5a-140">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="b0c5a-140">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

