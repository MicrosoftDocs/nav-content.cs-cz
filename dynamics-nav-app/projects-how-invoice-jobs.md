---
title: "Vytvářte prodejní fakturu projektu k fakturaci projektu"
description: "Popisuje jak fakturovat zákazníky za výdaje a vývoj projektu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project invoice
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 74b9209216f6e62dfc9519b288adca785cdb8100
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-invoice-jobs"></a><span data-ttu-id="6b2a7-103">Návody Fakturace projektu</span><span class="sxs-lookup"><span data-stu-id="6b2a7-103">How to: Invoice Jobs</span></span>
<span data-ttu-id="6b2a7-104">Během projektu se mohou hromadit projektové náklady ze spotřeby zdrojů, materiálů a nákupů souvisejících s projektem.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-104">During the project, job costs from resource usage, materials, and job-related purchases can accumulate.</span></span> <span data-ttu-id="6b2a7-105">Jak probíhá projekt, tyto transakce se zaúčtují do deníku projektu.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-105">As the job progresses, these transactions get posted to the job journal.</span></span> <span data-ttu-id="6b2a7-106">Je důležité, aby se všechny náklady zaznamenaly do deníku projektů dříve než fakturace zákazníkovi.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-106">It is important that all costs get recorded in the job journal before you invoice the customer.</span></span>

<span data-ttu-id="6b2a7-107">Můžete fakturovat celý projekt z okna **Řádky úlohy projektu** nebo pouze vyfakturovat vybrané fakturovatelné řádky z okna **Řádky plánování**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-107">You can invoice the whole job from the **Job Task Lines** window or only invoice selected billable lines from the **Planning Lines** window.</span></span> <span data-ttu-id="6b2a7-108">Fakturování lze provést po dokončení projektu nebo v určitých intervalech během průběhu projektu na základě fakturačního plánu.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-108">Invoicing can be done after the job is finished or at certain intervals during the job's progress based on an invoicing schedule.</span></span>

> [!NOTE]  
>   <span data-ttu-id="6b2a7-109">Pokud vyberete volbu **Fakturovatelné** v poli **Typ řádku projektu** na nákupních dokladech pro nákupy související s projektem, vytvoří se řádky plánování projektu, které jsou připraveny k fakturování zákazníkovi.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-109">If you select **Billable** in the **Job Line Type** field on the purchase documents for job-related purchases, then job planning lines that are ready to be invoiced to the customer are created.</span></span> <span data-ttu-id="6b2a7-110">Další informace naleznete v tématu [Návod: Správa zásob projektu.](projects-how-manage-project-supplies.md)</span><span class="sxs-lookup"><span data-stu-id="6b2a7-110">For more information, see [How to: Manage Project Supplies](projects-how-manage-project-supplies.md).</span></span>

## <a name="to-create-and-post-a-job-sales-invoice"></a><span data-ttu-id="6b2a7-111">Vytvoření a zaúčtování prodejní faktury projektu</span><span class="sxs-lookup"><span data-stu-id="6b2a7-111">To create and post a job sales invoice</span></span>
<span data-ttu-id="6b2a7-112">Můžete vytvořit fakturu pro projekt nebo pro jednu nebo více úloh projektu pro zákazníka při dokončení práce nebo když bylo dosaženo data fakturace na základě fakturačního plánu.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-112">You can create an invoice for a job or for one or more job tasks for a customer when either the work to be invoiced is complete or the date for invoicing based on an invoicing schedule has been reached.</span></span>

<span data-ttu-id="6b2a7-113">V okně **Projekty** můžete fakturovat zákazníkovi výběrem zakázky a poté zvolit akci **Vytvořit prodejní fakturu projektu**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-113">From the **Jobs** window, you can invoice a customer by selecting the job, and then choosing the **Create Job Sales Invoice** action.</span></span> <span data-ttu-id="6b2a7-114">Následující postup ukazuje, jak použít dávkovou úlohu k fakturování více projektů.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-114">The following procedure shows how to use a batch job to invoice multiple jobs.</span></span>  

1. <span data-ttu-id="6b2a7-115">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Vytvořit prodejní fakturu projektu** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Job Create Sales Invoice**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6b2a7-116">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-116">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. <span data-ttu-id="6b2a7-117">Nastavte filtry, pokud chcete omezit projekty, které bude zpracovávat dávková úloha.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-117">Set filters if you want to limit the jobs that the batch job will process.</span></span>
4. <span data-ttu-id="6b2a7-118">Zvolte tlačítko **OK** pro vytvoření faktur.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-118">Choose the **OK** button to create the invoices.</span></span>  

## <a name="to-create-multiple-job-sales-invoices-from-job-planning-lines"></a><span data-ttu-id="6b2a7-119">Vytvoření více prodejních faktur projektu z řádků plánování projektu</span><span class="sxs-lookup"><span data-stu-id="6b2a7-119">To create multiple job sales invoices from job planning lines</span></span>
<span data-ttu-id="6b2a7-120">Fakturu můžete vytvořit z řádků plánování projektu a v té době označit množství zboží, zdrojů nebo finanční účet, který chcete fakturovat.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-120">You can create an invoice from a job planning lines, and indicate at that time the quantity of the item, resource, or general ledger account that you want to invoice.</span></span>

1. <span data-ttu-id="6b2a7-121">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-121">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Jobs**, and then choose the related link.</span></span>
2. <span data-ttu-id="6b2a7-122">Otevřete příslušný projekt.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-122">Open a relevant job.</span></span>
3. <span data-ttu-id="6b2a7-123">Vyberte úlohu projektu, pro kterou pole **Typ úlohy projektu** obsahuje **Účet** a poté vyberte akci **Řádky plánování úlohy projektu**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-123">Select a job task for which the **Job Task Type** field contains **Posting**, and then choose the **Job Planning Lines** action.</span></span>  
4. <span data-ttu-id="6b2a7-124">Na řádku plánování projektu v poli **Množství k transferu k fakturaci** zadejte množství zboží, zdrojů nebo finančního účtu, které chcete fakturovat.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-124">On a job planning line, in the **Qty. To Transfer to Invoice** field, enter the quantity of the item, resource, general ledger account type that you want to invoice.</span></span>  
5. <span data-ttu-id="6b2a7-125">Zvolte akci **Vytvořit prodejní fakturu**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-125">Choose the **Create Sales Invoice** action.</span></span>
6. <span data-ttu-id="6b2a7-126">V okně **Vytvořit prodejní fakturu projektu** zadejte zúčtovací datum a zda chcete vytvořit novou fakturu nebo připojit tuto fakturu k již existující faktuře.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-126">In the **Job Create Sales Invoice** window, enter the posting date and whether you want to create a new invoice or append this invoice to an existing one.</span></span>
7. <span data-ttu-id="6b2a7-127">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-127">Choose the **OK** button.</span></span>  

    <span data-ttu-id="6b2a7-128">Na řádku plánování projektu v poli **Transferované množství k fakturaci** můžete vidět množství.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-128">On the job planning line, in the **Qty. Transferred to Invoice** field, you can see the quantity.</span></span>
8. <span data-ttu-id="6b2a7-129">V okně **Řádky plánování projektu** zvolte akci **Prodejní faktury/dobropisy**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-129">In the **Job Planning Lines** window, choose the **Sales Invoices/Credit Memos** action.</span></span>

    <span data-ttu-id="6b2a7-130">Otevřete se okno **Prodejní faktura** zobrazující množství, které jste převedli na fakturu.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-130">The **Sales Invoice** window opens, showing the quantity that you have transferred to the invoice.</span></span>  
9. <span data-ttu-id="6b2a7-131">Proveďte další změny a poté vyberte akci **Zaúčtovat**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-131">Make any additional changes, and then choose the **Post** action.</span></span>

> [!NOTE]  
>   <span data-ttu-id="6b2a7-132">Výše uvedený postup je podobný při vytváření, kontrole a účtování s projektem souvisejících prodejních dobropisů.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-132">The above procedure is similar for creating, reviewing, and posting a job-related sales credit memo.</span></span>

## <a name="to-calculate-and-post-job-completion-entries"></a><span data-ttu-id="6b2a7-133">Vypočítání a zaúčtování položek k dokončení projektu</span><span class="sxs-lookup"><span data-stu-id="6b2a7-133">To calculate and post job completion entries</span></span>
<span data-ttu-id="6b2a7-134">Po dokončení všech úloh pro daný projekt včetně zaúčtování spotřeby a fakturace, je nutné aktualizovat projekt tak, aby měl **Stav** **Dokončeno**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-134">When you have completed all activities for a job, including usage posting and invoicing, you must update the job to have a **Status** of **Completed**.</span></span> <span data-ttu-id="6b2a7-135">Poté musíte vrátit všechny záznamy NV, které byly zaúčtovány v hlavní knize.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-135">Then, you must reverse any WIP that has been posted to the general ledger.</span></span>

1. <span data-ttu-id="6b2a7-136">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-136">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Jobs**, and then choose the related link.</span></span>  
2. <span data-ttu-id="6b2a7-137">Vyberte otevřený projekt a poté zvolte akci **Úpravy**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-137">Select an open job, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="6b2a7-138">V poli **Stav** vyberte **Dokončeno**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-138">In the **Status** field, select **Completed**.</span></span>
4. <span data-ttu-id="6b2a7-139">Postupujte podle pokynů pro výpočet a účtování NV.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-139">Follow the assistance steps to calculate and post WIP.</span></span> <span data-ttu-id="6b2a7-140">Alternativně postupujte podle kroků 5 a 6 tak, abyste to provedli ručně.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-140">Alternatively, follows steps 5 and 6 to do so manually.</span></span>  
5. <span data-ttu-id="6b2a7-141">Vyberte akci **Kalkulovat NV**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-141">Choose the **Calculate WIP** action.</span></span>
6. <span data-ttu-id="6b2a7-142">V okně **Vypočítat NV projektu** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-142">In the **Job Calculate WIP** window, fill in the fields as necessary.</span></span>  

     <span data-ttu-id="6b2a7-143">Položky NV projektu vytvořené spuštěním dávkové úlohy budou mít zaškrtnuto políčko **Dokončený projekt**, aby bylo jasné, že jsou dokončeny.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-143">The job WIP entries created by running the batch job will have the **Job Complete** check box selected to show that they are completion entries.</span></span>  
7. <span data-ttu-id="6b2a7-144">Vyberte akci **Účto NV projektu do fin. den**.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-144">Choose the **Job Post WIP to G/L** action.</span></span>
8. <span data-ttu-id="6b2a7-145">V okně **Účto NV projektu do fin. den.** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-145">In the **Job Post WIP to G/L** window, fill in the fields as necessary.</span></span>  

     <span data-ttu-id="6b2a7-146">Položky hlav. knihy NV projektu vytvořené spuštěním dávkové úlohy budou mít zaškrtnuto políčko **Dokončený projekt**, aby bylo jasné, že jsou dokončeny.</span><span class="sxs-lookup"><span data-stu-id="6b2a7-146">The job WIP general ledger entries created by running the batch job will have the **Job Complete** check box selected to show they are completion entries.</span></span>

## <a name="see-also"></a><span data-ttu-id="6b2a7-147">Viz také</span><span class="sxs-lookup"><span data-stu-id="6b2a7-147">See Also</span></span>
[<span data-ttu-id="6b2a7-148">Správa projektů</span><span class="sxs-lookup"><span data-stu-id="6b2a7-148">Managing Projects</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="6b2a7-149">Finance</span><span class="sxs-lookup"><span data-stu-id="6b2a7-149">Finance</span></span>](finance.md)  
<span data-ttu-id="6b2a7-150">[Nákup](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="6b2a7-150">[Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="6b2a7-151">[Prodej](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="6b2a7-151">[Sales](sales-manage-sales.md)    </span></span>  
<span data-ttu-id="6b2a7-152">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="6b2a7-152">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

