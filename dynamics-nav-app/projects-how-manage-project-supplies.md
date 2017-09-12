---
title: "Návod: Správa projektových zásob"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 00b9ed8480f6b5ab9265beb0fe2dc0060b1c3192
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-job-supplies"></a><span data-ttu-id="7e302-102">Návod: Správa projektových zásob</span><span class="sxs-lookup"><span data-stu-id="7e302-102">How to: Manage Job Supplies</span></span>
<span data-ttu-id="7e302-103">Řízení projektových dodávek zboží, služeb a nákladů je nedílnou a kritickou stránkou výkonu všech projektů.</span><span class="sxs-lookup"><span data-stu-id="7e302-103">Managing project supplies of items, services, and expenses is an integral and critical aspect of the execution of all jobs.</span></span> <span data-ttu-id="7e302-104">Můžete použít inventární množství nebo udělat specifický projektový nákup pro danou zakázku pomocí nákupních objednávek nebo nákupních faktur.</span><span class="sxs-lookup"><span data-stu-id="7e302-104">You can use inventory quantities or make job-specific purchases using purchase orders or purchase invoices.</span></span> <span data-ttu-id="7e302-105">Například projektová služba ohledně počítače vyžaduje nový disk.</span><span class="sxs-lookup"><span data-stu-id="7e302-105">For example, a service job on a computer requires a new disk.</span></span> <span data-ttu-id="7e302-106">Vytvořte nákupní fakturu pro zakoupení nového disku a zaznamenejte projekt, na který bude použita.</span><span class="sxs-lookup"><span data-stu-id="7e302-106">You create a purchase invoice to buy a new disk and record the job that it will be used on.</span></span>

<span data-ttu-id="7e302-107">Pokud proces nákupu nevyžaduje, aby byla fyzická transakce zaznamenána samostatně, může být nákup zpracován v okně **Finanční deník projektu**.</span><span class="sxs-lookup"><span data-stu-id="7e302-107">If the purchase process does not require that the physical transaction be recorded separately, then a purchase may be processed in the **Job G/L Journal** window.</span></span> <span data-ttu-id="7e302-108">Další informace naleznete v tématu [Návod: Využití záznamu pro projekty](projects-how-record-job-usage.md).</span><span class="sxs-lookup"><span data-stu-id="7e302-108">For more information, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).</span></span>

## <a name="to-purchase-items-or-services-for-a-job"></a><span data-ttu-id="7e302-109">Zakoupení zboží nebo služeb pro projekt</span><span class="sxs-lookup"><span data-stu-id="7e302-109">To purchase items or services for a job</span></span>
<span data-ttu-id="7e302-110">Následující postup ukazuje, jak použít nákupní fakturu k nákupu produktů pro daný projekt.</span><span class="sxs-lookup"><span data-stu-id="7e302-110">The following procedure shows how to use a purchase invoice to purchase products for a job.</span></span> <span data-ttu-id="7e302-111">Při použití nákupní objednávky platí stejné kroky.</span><span class="sxs-lookup"><span data-stu-id="7e302-111">The same steps apply when using a purchase order.</span></span>  

1. <span data-ttu-id="7e302-112">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nákupní faktury** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="7e302-112">In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Invoices**, and then choose the related link.</span></span>  
2. <span data-ttu-id="7e302-113">Vyberte akci **Nový** a poté vyplňte potřebná pole.</span><span class="sxs-lookup"><span data-stu-id="7e302-113">Choose the **New** action and fill in the fields as necessary.</span></span> <span data-ttu-id="7e302-114">Další informace naleznete v tématu [Návod: Záznam nákupů](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="7e302-114">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
3. <span data-ttu-id="7e302-115">V poli **Číslo projektu**</span><span class="sxs-lookup"><span data-stu-id="7e302-115">In the **Job No.**</span></span> <span data-ttu-id="7e302-116">a **Č. úlohy projektu**</span><span class="sxs-lookup"><span data-stu-id="7e302-116">and **Job Task No.**</span></span> <span data-ttu-id="7e302-117">vyberte informace o projektu, pro který chcete zakoupit zboží nebo služby.</span><span class="sxs-lookup"><span data-stu-id="7e302-117">fields, select the information of the job that you want to purchase items or services for.</span></span>  

    <span data-ttu-id="7e302-118">Hodnota, kterou vyberete v poli **Typ řádku projektu** určuje, zda je po zaúčtování spotřeby zboží vytvořen řádek plánování.</span><span class="sxs-lookup"><span data-stu-id="7e302-118">The value that you select in the **Job Line Type** field defines whether a planning line is created when you post the usage of the item.</span></span> <span data-ttu-id="7e302-119">Pokud pole obsahuje možnost **Fakturovatelné**, jsou vytvořeny řádky plánování projektu, které jsou připraveny k fakturaci zákazníkovi.</span><span class="sxs-lookup"><span data-stu-id="7e302-119">If the field contains **Billable**, then job planning lines that are ready to be invoiced to the customer are created.</span></span> <span data-ttu-id="7e302-120">Další informace naleznete v tématu [Návod: Faktury projektu](projects-how-invoice-jobs.md).</span><span class="sxs-lookup"><span data-stu-id="7e302-120">For more information, see [How to: Invoice Jobs](projects-how-invoice-jobs.md).</span></span>

4. <span data-ttu-id="7e302-121">Zvolte akci **Zaúčtovat**.</span><span class="sxs-lookup"><span data-stu-id="7e302-121">Choose the **Post** action.</span></span>

## <a name="to-view-the-value-of-purchases-for-a-job"></a><span data-ttu-id="7e302-122">Zobrazení hodnoty nákupů pro projekt</span><span class="sxs-lookup"><span data-stu-id="7e302-122">To view the value of purchases for a job</span></span>  

1. <span data-ttu-id="7e302-123">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="7e302-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span></span>
2. <span data-ttu-id="7e302-124">Otevřete příslušnou kartu projektu.</span><span class="sxs-lookup"><span data-stu-id="7e302-124">Open a relevant job card.</span></span>

    <span data-ttu-id="7e302-125">Na kartě **Úlohy** v poli **Otevřené objednávky** zobrazuje celkovou nevyřízenou částku v lokální měně zboží a služeb na nákupních dokladech pro řádek úlohy projektu.</span><span class="sxs-lookup"><span data-stu-id="7e302-125">On the **Tasks** FastTab, the **Outstanding Orders** field shows the total outstanding amount, in local currency, of inventory items and services on purchase documents for the job task line.</span></span>  

    <span data-ttu-id="7e302-126">Pole **Přijato, nefakturováno (částka)** zobrazuje hodnotu zboží přijatých na nákupních dokladech, které dosud nebyly fakturovány.</span><span class="sxs-lookup"><span data-stu-id="7e302-126">The **Amt. Rec. Not Invoiced** field shows the value of items delivered on purchase documents, but not yet invoiced.</span></span>  

3. <span data-ttu-id="7e302-127">Zvolte jedno z polí, chcete-li otevřít okno **Nákupní řádky**, kde můžete zkontrolovat informace o souvisejících řádcích nákupních dokladů včetně zboží nebo služeb, které byly přijaty.</span><span class="sxs-lookup"><span data-stu-id="7e302-127">Choose either of the fields to open the **Purchase Lines** window where you can review information about the related purchase document lines, including which items or services have been received.</span></span>

## <a name="to-post-a-job-related-expense"></a><span data-ttu-id="7e302-128">Účtování nákladů souvisejících s projektem</span><span class="sxs-lookup"><span data-stu-id="7e302-128">To post a job-related expense</span></span>  
<span data-ttu-id="7e302-129">Máte-li mimořádné nebo jednorázové výdaje na projekt, můžete použít okno **Finanční deník projektu**, abyste je mohli zaúčtovat přímo na příslušný účet projektu.</span><span class="sxs-lookup"><span data-stu-id="7e302-129">If you incur extraordinary or one-time job expenses, you can use the **Job G/L Journal** window to post them directly to the relevant job account.</span></span>

1. <span data-ttu-id="7e302-130">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Finanční deník projektu** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="7e302-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Job G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="7e302-131">Vytvořte nový řádek a zadejte informace o výdajích včetně informací v poli **Č. projektu**</span><span class="sxs-lookup"><span data-stu-id="7e302-131">Create a new line and enter information about the expense, including information in the **Job No.**</span></span> <span data-ttu-id="7e302-132">a **Č. činnosti projektu**.</span><span class="sxs-lookup"><span data-stu-id="7e302-132">and **Job Task No** fields.</span></span>  
3. <span data-ttu-id="7e302-133">Po dokončení deníku zvolte akci **Zaúčtovat**.</span><span class="sxs-lookup"><span data-stu-id="7e302-133">When the journal is complete, choose the **Post** action.</span></span>


## <a name="see-also"></a><span data-ttu-id="7e302-134">Viz také</span><span class="sxs-lookup"><span data-stu-id="7e302-134">See Also</span></span>
[<span data-ttu-id="7e302-135">Správa projektů</span><span class="sxs-lookup"><span data-stu-id="7e302-135">Manage Projects</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="7e302-136">Finance</span><span class="sxs-lookup"><span data-stu-id="7e302-136">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="7e302-137">[Správa nákupu](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="7e302-137">[Manage Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="7e302-138">[Správa prodeje](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="7e302-138">[Manage Sales](sales-manage-sales.md)    </span></span>  
[<span data-ttu-id="7e302-139">Práce s Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="7e302-139">Work With Dynamics NAV</span></span>](ui-work-product.md)  

