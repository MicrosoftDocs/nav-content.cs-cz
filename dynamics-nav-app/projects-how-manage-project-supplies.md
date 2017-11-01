---
title: "Nákup zboží nebo servisu pro projekty a správa zásob"
description: "Popisuje jak spravovat zásoby a nákup materiálu a servisu pro projekty."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project management, material, purchase
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3405af0c06df0fb04c528cf114d4ef6326f7c0a9
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-manage-job-supplies"></a><span data-ttu-id="9efc1-103">Návody Správa projektových zásob</span><span class="sxs-lookup"><span data-stu-id="9efc1-103">How to: Manage Job Supplies</span></span>
<span data-ttu-id="9efc1-104">Řízení projektových dodávek zboží, služeb a nákladů je nedílnou a kritickou stránkou výkonu všech projektů.</span><span class="sxs-lookup"><span data-stu-id="9efc1-104">Managing project supplies of items, services, and expenses is an integral and critical aspect of the execution of all jobs.</span></span> <span data-ttu-id="9efc1-105">Můžete použít inventární množství nebo udělat specifický projektový nákup pro danou zakázku pomocí nákupních objednávek nebo nákupních faktur.</span><span class="sxs-lookup"><span data-stu-id="9efc1-105">You can use inventory quantities or make job-specific purchases using purchase orders or purchase invoices.</span></span> <span data-ttu-id="9efc1-106">Například projektová služba ohledně počítače vyžaduje nový disk.</span><span class="sxs-lookup"><span data-stu-id="9efc1-106">For example, a service job on a computer requires a new disk.</span></span> <span data-ttu-id="9efc1-107">Vytvořte nákupní fakturu pro zakoupení nového disku a zaznamenejte projekt, na který bude použita.</span><span class="sxs-lookup"><span data-stu-id="9efc1-107">You create a purchase invoice to buy a new disk and record the job that it will be used on.</span></span>

<span data-ttu-id="9efc1-108">Pokud proces nákupu nevyžaduje, aby byla fyzická transakce zaznamenána samostatně, může být nákup zpracován v okně **Finanční deník projektu**.</span><span class="sxs-lookup"><span data-stu-id="9efc1-108">If the purchase process does not require that the physical transaction be recorded separately, then a purchase may be processed in the **Job G/L Journal** window.</span></span> <span data-ttu-id="9efc1-109">Další informace naleznete v tématu [Návod: Záznam spotřeby pro projekty](projects-how-record-job-usage.md).</span><span class="sxs-lookup"><span data-stu-id="9efc1-109">For more information, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).</span></span>

## <a name="to-purchase-items-or-services-for-a-job"></a><span data-ttu-id="9efc1-110">Zakoupení zboží nebo služeb pro projekt</span><span class="sxs-lookup"><span data-stu-id="9efc1-110">To purchase items or services for a job</span></span>
<span data-ttu-id="9efc1-111">Následující postup ukazuje, jak použít nákupní fakturu k nákupu produktů pro daný projekt.</span><span class="sxs-lookup"><span data-stu-id="9efc1-111">The following procedure shows how to use a purchase invoice to purchase products for a job.</span></span> <span data-ttu-id="9efc1-112">Při použití nákupní objednávky platí stejné kroky.</span><span class="sxs-lookup"><span data-stu-id="9efc1-112">The same steps apply when using a purchase order.</span></span>  

1. <span data-ttu-id="9efc1-113">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nákupní faktury** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="9efc1-113">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9efc1-114">Vyberte akci **Nový** a poté vyplňte potřebná pole.</span><span class="sxs-lookup"><span data-stu-id="9efc1-114">Choose the **New** action and fill in the fields as necessary.</span></span> <span data-ttu-id="9efc1-115">Další informace naleznete v tématu [Návod: Zaznamenávání nákupů.](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="9efc1-115">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
3. <span data-ttu-id="9efc1-116">V polích **Číslo projektu** a **Číslo úlohy projektu** vyberte informace o projektu, pro který chcete zakoupit zboží nebo služby.</span><span class="sxs-lookup"><span data-stu-id="9efc1-116">In the **Job No.** and **Job Task No.** fields, select the information of the job that you want to purchase items or services for.</span></span> <span data-ttu-id="9efc1-117">Použijte funkci **Zvolit sloupce** pokud nebudou viditelné.</span><span class="sxs-lookup"><span data-stu-id="9efc1-117">Use the **Choose Columns** function if the field is not visible.</span></span> <span data-ttu-id="9efc1-118">Další informace naleznete v tématu [Uživatelská personalizace](ui-user-personalization.md).</span><span class="sxs-lookup"><span data-stu-id="9efc1-118">For more information, see [User Personalization](ui-user-personalization.md).</span></span>

    <span data-ttu-id="9efc1-119">Hodnota, kterou vyberete v poli **Typ řádku projektu** určuje, zda je po zaúčtování spotřeby zboží vytvořen řádek plánování.</span><span class="sxs-lookup"><span data-stu-id="9efc1-119">The value that you select in the **Job Line Type** field defines whether a planning line is created when you post the usage of the item.</span></span> <span data-ttu-id="9efc1-120">Pokud pole obsahuje možnost **Fakturovatelné**, jsou vytvořeny řádky plánování projektu, které jsou připraveny k fakturaci zákazníkovi.</span><span class="sxs-lookup"><span data-stu-id="9efc1-120">If the field contains **Billable**, then job planning lines that are ready to be invoiced to the customer are created.</span></span> <span data-ttu-id="9efc1-121">Další informace naleznete v tématu [Návod: Fakturace projektů](projects-how-invoice-jobs.md).</span><span class="sxs-lookup"><span data-stu-id="9efc1-121">For more information, see [How to: Invoice Jobs](projects-how-invoice-jobs.md).</span></span>
4. <span data-ttu-id="9efc1-122">Zvolte akci **Zaúčtovat**.</span><span class="sxs-lookup"><span data-stu-id="9efc1-122">Choose the **Post** action.</span></span>

## <a name="to-view-the-value-of-purchases-for-a-job"></a><span data-ttu-id="9efc1-123">Zobrazení hodnoty nákupů pro projekt</span><span class="sxs-lookup"><span data-stu-id="9efc1-123">To view the value of purchases for a job</span></span>
1. <span data-ttu-id="9efc1-124">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="9efc1-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Jobs**, and then choose the related link.</span></span>
2. <span data-ttu-id="9efc1-125">Otevřete příslušnou kartu projektu.</span><span class="sxs-lookup"><span data-stu-id="9efc1-125">Open a relevant job card.</span></span>

    <span data-ttu-id="9efc1-126">Na kartě **Úlohy** v poli **Otevřené objednávky** zobrazuje celkovou nevyřízenou částku v lokální měně zboží a služeb na nákupních dokladech pro řádek úlohy projektu.</span><span class="sxs-lookup"><span data-stu-id="9efc1-126">On the **Tasks** FastTab, the **Outstanding Orders** field shows the total outstanding amount, in local currency, of inventory items and services on purchase documents for the job task line.</span></span>  

    <span data-ttu-id="9efc1-127">Pole** Celková nefakturovaná částka **zobrazuje hodnotu zboží přijatých na nákupních dokladech, které dosud nebyly fakturovány.</span><span class="sxs-lookup"><span data-stu-id="9efc1-127">The **Amt. Rec. Not Invoiced** field shows the value of items delivered on purchase documents, but not yet invoiced.</span></span>  
3. <span data-ttu-id="9efc1-128">Zvolte jedno z polí, chcete-li otevřít okno **Nákupní řádky**, kde můžete zkontrolovat informace o souvisejících řádcích nákupních dokladů včetně zboží nebo služeb, které byly přijaty.</span><span class="sxs-lookup"><span data-stu-id="9efc1-128">Choose either of the fields to open the **Purchase Lines** window where you can review information about the related purchase document lines, including which items or services have been received.</span></span>

## <a name="to-post-a-job-related-expense"></a><span data-ttu-id="9efc1-129">Účtování nákladů souvisejících s projektem</span><span class="sxs-lookup"><span data-stu-id="9efc1-129">To post a job-related expense</span></span>
<span data-ttu-id="9efc1-130">Máte-li mimořádné nebo jednorázové výdaje na projekt, můžete použít okno **Finanční deník projektu**, abyste je mohli zaúčtovat přímo na příslušný účet projektu.</span><span class="sxs-lookup"><span data-stu-id="9efc1-130">If you incur extraordinary or one-time job expenses, you can use the **Job G/L Journal** window to post them directly to the relevant job account.</span></span>

1. <span data-ttu-id="9efc1-131">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník projektu** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="9efc1-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Job G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9efc1-132">Vytvořte nový řádek a zadejte informace o výdajích včetně informací v poli **Č. projektu** a** Č. úlohy projektu**.</span><span class="sxs-lookup"><span data-stu-id="9efc1-132">Create a new line and enter information about the expense, including information in the **Job No.** and **Job Task No** fields.</span></span>  
3. <span data-ttu-id="9efc1-133">Po dokončení deníku zvolte akci **Zaúčtovat**.</span><span class="sxs-lookup"><span data-stu-id="9efc1-133">When the journal is complete, choose the **Post** action.</span></span>

## <a name="see-also"></a><span data-ttu-id="9efc1-134">Viz také</span><span class="sxs-lookup"><span data-stu-id="9efc1-134">See Also</span></span>
[<span data-ttu-id="9efc1-135">Řízení projektů</span><span class="sxs-lookup"><span data-stu-id="9efc1-135">Project Management</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="9efc1-136">Finance</span><span class="sxs-lookup"><span data-stu-id="9efc1-136">Finance</span></span>](finance.md)  
<span data-ttu-id="9efc1-137">[Nákup](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="9efc1-137">[Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="9efc1-138">[Prodej](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="9efc1-138">[Sales](sales-manage-sales.md)    </span></span>  
<span data-ttu-id="9efc1-139">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="9efc1-139">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

