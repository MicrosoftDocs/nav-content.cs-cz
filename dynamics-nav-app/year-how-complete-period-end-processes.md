---
title: "Uzavřít období"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 6d390ae2c7bf7e70cf5fc2ac4df7da07be93e3f2
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---
# <a name="close-periods"></a><span data-ttu-id="89fa2-102">Uzavřít období</span><span class="sxs-lookup"><span data-stu-id="89fa2-102">Close Periods</span></span>
<span data-ttu-id="89fa2-103">Aplikace vás nedonutí uzavřít období, avšak existuje mnoho aktivit týkajících se ukončení období, které mohou být v aplikaci vykonány, pokud chcete.</span><span class="sxs-lookup"><span data-stu-id="89fa2-103">The application does not force you to close periods, however, there are many period-end (month-end) activities that can be performed in the application if you want.</span></span> <span data-ttu-id="89fa2-104">Toto téma poskytuje přehled o těchto procesech a aktivitách, které mohou nebo nemusí být pro vaši společnost nezbytné.</span><span class="sxs-lookup"><span data-stu-id="89fa2-104">This topic provides an overview of these processes and activities, which may or may not be necessary for your company.</span></span>

## <a name="general-ledger"></a><span data-ttu-id="89fa2-105">Hlavní kniha</span><span class="sxs-lookup"><span data-stu-id="89fa2-105">General Ledger</span></span>
* <span data-ttu-id="89fa2-106">Určete systémové a uživatelské období zaúčtování.</span><span class="sxs-lookup"><span data-stu-id="89fa2-106">Specify system-wide and user-specific posting period.</span></span>

    <span data-ttu-id="89fa2-107">Toto určuje data, mezi kterými je povoleno zaúčtovat.</span><span class="sxs-lookup"><span data-stu-id="89fa2-107">This specifies the dates between which postings are allowed.</span></span> <span data-ttu-id="89fa2-108">V závislosti na vašich obchodních potřebách možná budete chtít uživatelům omezit povolené období účtování.</span><span class="sxs-lookup"><span data-stu-id="89fa2-108">Depending on your business needs, you may want to restrict user posting date ranges at the start of the period-end process or at later time towards the end of the period.</span></span> <span data-ttu-id="89fa2-109">Pro další informace , viz [Návody: ](finance-how-specify-posting-periods.md)Specifikovat účetní období.</span><span class="sxs-lookup"><span data-stu-id="89fa2-109">For more information, see [How to: Specify Posting Periods](finance-how-specify-posting-periods.md).</span></span>
* <span data-ttu-id="89fa2-110">Proveďte všechny potřebné úpravy v hlavní knize.</span><span class="sxs-lookup"><span data-stu-id="89fa2-110">Make all necessary G/L adjustments.</span></span>
* <span data-ttu-id="89fa2-111">Aktualizujte a zaúčtujte periodické deníky.</span><span class="sxs-lookup"><span data-stu-id="89fa2-111">Update and post Recurring Journals.</span></span>
<!--* Process Consolidations-->
* <span data-ttu-id="89fa2-112">Spusťte účetní schémata následovně:</span><span class="sxs-lookup"><span data-stu-id="89fa2-112">Run account schedules as follows:</span></span>
  1. <span data-ttu-id="89fa2-113">Otevřete okno **Účetní schéma** a zvolte akci **Tisk**.</span><span class="sxs-lookup"><span data-stu-id="89fa2-113">Open the **Account Schedule** window, and choose the **Print** action.</span></span>
  2. <span data-ttu-id="89fa2-114">Vyplňte okno **Možnosti** a zvolte akci **Tisk**.</span><span class="sxs-lookup"><span data-stu-id="89fa2-114">Fill the **Account Schedule** request window and choose the **Print** action.</span></span>

## <a name="sales--receivables"></a><span data-ttu-id="89fa2-115">Prodej a pohledávky</span><span class="sxs-lookup"><span data-stu-id="89fa2-115">Sales & Receivables</span></span>
* <span data-ttu-id="89fa2-116">Zaúčtujte všechny objednávky, faktury, dobropisy a objednávky prodejní vratky.</span><span class="sxs-lookup"><span data-stu-id="89fa2-116">Post all sales orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="89fa2-117">Zaúčtujte všechny deníky přijaté hotovosti.</span><span class="sxs-lookup"><span data-stu-id="89fa2-117">Post all cash receipt journals.</span></span>
* <span data-ttu-id="89fa2-118">Aktualizujte a zaúčtujte periodické deníky, které se vztahují k prodeji a pohledávkám.</span><span class="sxs-lookup"><span data-stu-id="89fa2-118">Update and post recurring journals that are related to Sales & Receivables.</span></span>
* <span data-ttu-id="89fa2-119">Odsouhlaste pohledávky s hlavní účetní knihou.</span><span class="sxs-lookup"><span data-stu-id="89fa2-119">Reconcile accounts receivable to the general ledger.</span></span>
* <span data-ttu-id="89fa2-120">Spusťte dávkovou úlohu **Odstranit fakt. prod. objednávky**.</span><span class="sxs-lookup"><span data-stu-id="89fa2-120">Run the **Delete Invoiced Sales Orders** batch job.</span></span>

## <a name="purchases--payables"></a><span data-ttu-id="89fa2-121">Nákupy a závazky</span><span class="sxs-lookup"><span data-stu-id="89fa2-121">Purchases & Payables</span></span>
* <span data-ttu-id="89fa2-122">Zaúčtujte všechny objednávky, faktury, dobropisy a pobjednávky prodejní vratky.</span><span class="sxs-lookup"><span data-stu-id="89fa2-122">Post all purchase orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="89fa2-123">Zaúčtujte všechny deníky plateb.</span><span class="sxs-lookup"><span data-stu-id="89fa2-123">Post all payment journals.</span></span>
* <span data-ttu-id="89fa2-124">Aktualizujte a zaúčtujte periodické deníky, které se vztahují k nákupům a závazkům.</span><span class="sxs-lookup"><span data-stu-id="89fa2-124">Update and post recurring journals that are related to purchases & payables.</span></span>
* <span data-ttu-id="89fa2-125">Spusťte sestavu **Splatné závazky** a odsouhlaste účty závazků s hlavní knihou.</span><span class="sxs-lookup"><span data-stu-id="89fa2-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span></span>
* <span data-ttu-id="89fa2-126">Spusťte dávkovou úlohu **Odstranit fakt. nák. objednávky** .</span><span class="sxs-lookup"><span data-stu-id="89fa2-126">Run the **Delete Invoiced Purchase Orders** batch job.</span></span>

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a><span data-ttu-id="89fa2-127">Vypočítat a zpracovat prodejní daň</span><span class="sxs-lookup"><span data-stu-id="89fa2-127">Calculate and Process Sales Tax</span></span>
*  <span data-ttu-id="89fa2-128">Dokončete daňové výkazy.</span><span class="sxs-lookup"><span data-stu-id="89fa2-128">Complete Tax Statements.</span></span>

## <a name="see-also"></a><span data-ttu-id="89fa2-129">Viz také</span><span class="sxs-lookup"><span data-stu-id="89fa2-129">See Also</span></span>
[<span data-ttu-id="89fa2-130">Uzavřít roky a období.</span><span class="sxs-lookup"><span data-stu-id="89fa2-130">Closing Years and Periods</span></span>](year-close-years-periods.md)  
[<span data-ttu-id="89fa2-131">Uzavřít knihy</span><span class="sxs-lookup"><span data-stu-id="89fa2-131">Close Books</span></span>](year-close-books.md)

