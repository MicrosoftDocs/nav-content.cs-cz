---
title: "Nastavení a správa rozpočtů projektu"
description: "Popisuje jak plánovat zdroje, dále předpovídat a řídit náklady projektu pomocí nastavení rozpočtu pro každý projekt. "
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project budget, forecast
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 67874a8d10a975818d1c0d94d5e178259a5c5782
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-manage-job-budgets"></a><span data-ttu-id="7ac49-103">Návod: Správa rozpočtů projektu</span><span class="sxs-lookup"><span data-stu-id="7ac49-103">How to: Manage Job Budgets</span></span>
<span data-ttu-id="7ac49-104">Můžete nastavit rozpočet pro každý projekt.</span><span class="sxs-lookup"><span data-stu-id="7ac49-104">You can set up a budget for each job.</span></span> <span data-ttu-id="7ac49-105">Rozpočet se používá k plánování zdrojů, které přidělíte projektu.</span><span class="sxs-lookup"><span data-stu-id="7ac49-105">The budget is used to plan the resources that you allocate to a job.</span></span> <span data-ttu-id="7ac49-106">Rozpočet může být buď obecný s několika položkami nebo může obsahovat více položek rozdělených do úrovní aktivit.</span><span class="sxs-lookup"><span data-stu-id="7ac49-106">The budget can be either general with few entries or it can contain more entries that are divided into activity levels.</span></span> <span data-ttu-id="7ac49-107">Poté můžete porovnat rozpočtové částky se skutečnou spotřebou, jak je zaznamenáno v deníku projektů.</span><span class="sxs-lookup"><span data-stu-id="7ac49-107">You can then compare the budgeted amounts with the actual usage as recorded in the job journal.</span></span> <span data-ttu-id="7ac49-108">Monitorováním rozdílů mezi skutečnou spotřebou a rozpočtovou spotřebou můžete řídit probíhající projekt a zlepšit kvalitu budoucích pracovních míst tím, že snížíte riziko podhodnocení nákladů.</span><span class="sxs-lookup"><span data-stu-id="7ac49-108">By monitoring differences between actual usage and budgeted usage, you can control an ongoing project and improve the quality of future jobs by reducing the risk of underestimating costs.</span></span>

<span data-ttu-id="7ac49-109">Následující postup popisuje, jak odhadnout rozpočtované náklady během plánování.</span><span class="sxs-lookup"><span data-stu-id="7ac49-109">The following procedure describes how to estimate budgeted costs during planning.</span></span> <span data-ttu-id="7ac49-110">Informace o zaznamenaném rozpočtu versus skutečné ceně a nákladům naleznete v části [Návod: Záznam spotřeby pro projekty](projects-how-record-job-usage.md).</span><span class="sxs-lookup"><span data-stu-id="7ac49-110">For information about recording budgeted versus actual job prices and costs, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).</span></span>  

## <span data-ttu-id="7ac49-111"><a name="JobBudgetCosts"></a> Odhadnutí rozpočtových nákladů na projekt</span><span class="sxs-lookup"><span data-stu-id="7ac49-111"><a name="JobBudgetCosts"></a> To estimate the budgeted costs for a job</span></span>
<span data-ttu-id="7ac49-112">Pokud chce zákazník znát cenu projektu, která bude fakturována na základě jejího použití, musíte určit výši rozpočtových nákladů na projekt.</span><span class="sxs-lookup"><span data-stu-id="7ac49-112">When a customer wants to know the price of a job that will be invoiced based on usage, you must have to determine the budgeted costs for the job.</span></span> <span data-ttu-id="7ac49-113">K tomu použijte okno **Řádky úlohy projektu**.</span><span class="sxs-lookup"><span data-stu-id="7ac49-113">You use the **Job Task Lines** window to do this.</span></span>

1. <span data-ttu-id="7ac49-114">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="7ac49-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Jobs**, and then choose the related link.</span></span>  
2. <span data-ttu-id="7ac49-115">Otevřete příslušný projekt.</span><span class="sxs-lookup"><span data-stu-id="7ac49-115">Open a relevant job.</span></span>
3. <span data-ttu-id="7ac49-116">Vyberte řádek úlohy typu Účet a poté vyberte akci **Řádky plánování projektu**.</span><span class="sxs-lookup"><span data-stu-id="7ac49-116">Select a task line of type Posting, and then choose the **Job Planning Lines** action.</span></span>
4. <span data-ttu-id="7ac49-117">Na novém řádku, vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="7ac49-117">On a new line, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]   

<span data-ttu-id="7ac49-118">U pole **Typ řádku** naleznete následující informace.</span><span class="sxs-lookup"><span data-stu-id="7ac49-118">For the **Line Type** field, refer to the following information.</span></span>  

| <span data-ttu-id="7ac49-119">Typ řádku</span><span class="sxs-lookup"><span data-stu-id="7ac49-119">Line Type</span></span> | <span data-ttu-id="7ac49-120">Popis</span><span class="sxs-lookup"><span data-stu-id="7ac49-120">Description</span></span> |
| --- | --- |
| <span data-ttu-id="7ac49-121">**Oba typy Plán a Fakturovatelné**</span><span class="sxs-lookup"><span data-stu-id="7ac49-121">**Both Budget and Billable**</span></span> |<span data-ttu-id="7ac49-122">Částky nákladů a cen zapsané na řádku plánování jsou rozpočtové náklady na konkrétním řádku plánování.</span><span class="sxs-lookup"><span data-stu-id="7ac49-122">The cost and price amounts entered on the planning line are the budgeted costs for the particular planning line.</span></span> <span data-ttu-id="7ac49-123">Cena bude fakturována.</span><span class="sxs-lookup"><span data-stu-id="7ac49-123">The price amount will be invoiced.</span></span> |
| <span data-ttu-id="7ac49-124">**Plán**</span><span class="sxs-lookup"><span data-stu-id="7ac49-124">**Budget**</span></span> |<span data-ttu-id="7ac49-125">Zákazník za spotřebu neúčtuje.</span><span class="sxs-lookup"><span data-stu-id="7ac49-125">The customer is not charged for usage.</span></span> <span data-ttu-id="7ac49-126">Spotřeba není převedena na fakturu, ale bude se i nadále používat při výpočtu NV.</span><span class="sxs-lookup"><span data-stu-id="7ac49-126">Usage is not transferred to an invoice, but will still be used in the calculation of WIP.</span></span> |
| <span data-ttu-id="7ac49-127">**Fakturovatelné**</span><span class="sxs-lookup"><span data-stu-id="7ac49-127">**Billable**</span></span> |<span data-ttu-id="7ac49-128">Zákazníkovi je účtována spotřeba.</span><span class="sxs-lookup"><span data-stu-id="7ac49-128">The customer is charged for usage.</span></span> <span data-ttu-id="7ac49-129">Spotřeba je převedena na fakturu na základě množství specifikovaného v poli Množství k fakturaci.</span><span class="sxs-lookup"><span data-stu-id="7ac49-129">Usage is transferred to the invoice, based on the quantity specified in the Qty. to Transfer to Invoice field.</span></span> |

> [!NOTE]  
>   <span data-ttu-id="7ac49-130">Pole **Datum plánování** pro řádek plánování obsahuje datum, kdy se očekává, že bude spotřeba související s řádkem plánování dokončena.</span><span class="sxs-lookup"><span data-stu-id="7ac49-130">The **Planning Date** field for the planning line contains the date when usage related to the planning line is expected to be completed.</span></span> <span data-ttu-id="7ac49-131">Je také datem, kdy lze řádek plánování převést na prodejní fakturu a zaúčtovat ji.</span><span class="sxs-lookup"><span data-stu-id="7ac49-131">It is also the date when the planning line may be transferred to a sales invoice and posted.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="7ac49-132">Po vyplnění pole **Množství** se pro tento řádek plánování vypočítají a vyplní veškeré informace o celkové ceně a celkových nákladech.</span><span class="sxs-lookup"><span data-stu-id="7ac49-132">When you fill in the **Quantity** field, all total price and total cost information will be calculated and filled in for that planning line.</span></span> <span data-ttu-id="7ac49-133">Můžete je kdykoli upravit.</span><span class="sxs-lookup"><span data-stu-id="7ac49-133">You can edit them at any time.</span></span>

<span data-ttu-id="7ac49-134">V okně **Karta projektu** můžete nyní zobrazit souhrn všech rozpočtových nákladů, rozpočtovou cenu, fakturační náklady a fakturační cenu pro každou činnost.</span><span class="sxs-lookup"><span data-stu-id="7ac49-134">In the **Job Card** window, you can now see a summary of the total budgeted costs, budgeted price, billable cost and billable price for each task.</span></span>

<span data-ttu-id="7ac49-135">Informace o zaznamenaném rozpočtu versus skutečné ceně a nákladům naleznete v části [Návod: Záznam spotřeby pro projekty](projects-how-record-job-usage.md).</span><span class="sxs-lookup"><span data-stu-id="7ac49-135">For information about recording budgeted versus actual job prices and costs, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="7ac49-136">Viz také</span><span class="sxs-lookup"><span data-stu-id="7ac49-136">See Also</span></span>
[<span data-ttu-id="7ac49-137">Řízení projektů</span><span class="sxs-lookup"><span data-stu-id="7ac49-137">Project Management</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="7ac49-138">Finance</span><span class="sxs-lookup"><span data-stu-id="7ac49-138">Finance</span></span>](finance.md)  
<span data-ttu-id="7ac49-139">[Nákup](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="7ac49-139">[Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="7ac49-140">[Prodej](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="7ac49-140">[Sales](sales-manage-sales.md)    </span></span>  
<span data-ttu-id="7ac49-141">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="7ac49-141">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

