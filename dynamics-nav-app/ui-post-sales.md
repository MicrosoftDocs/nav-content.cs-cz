---
title: "Porozumění, jak účtovat prodejní doklady"
description: "Informace o různých funkcích účtování prodejních dokumentů."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: a43c9639592b8249481832cb2b3a89e93638f229
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="posting-sales"></a><span data-ttu-id="b9153-103">Účtování prodeje</span><span class="sxs-lookup"><span data-stu-id="b9153-103">Posting Sales</span></span>
<span data-ttu-id="b9153-104">Ve skupině **Účtování** na prodejním dokladu si můžete vybrat mezi následujícími účtovacími funkcemi:</span><span class="sxs-lookup"><span data-stu-id="b9153-104">In the **Posting group** on a sales document, you can choose between the following posting functions:</span></span>

* <span data-ttu-id="b9153-105">**Účtovat**</span><span class="sxs-lookup"><span data-stu-id="b9153-105">**Post**</span></span>
* <span data-ttu-id="b9153-106">**Testovací sestava**</span><span class="sxs-lookup"><span data-stu-id="b9153-106">**Test Report**</span></span>
* <span data-ttu-id="b9153-107">**Účtovat a odeslat**</span><span class="sxs-lookup"><span data-stu-id="b9153-107">**Post and Send**</span></span>
* <span data-ttu-id="b9153-108">**Účtovat a vytisknout**</span><span class="sxs-lookup"><span data-stu-id="b9153-108">**Post and Print**</span></span>
* <span data-ttu-id="b9153-109">**Účtovat a poslat e-mailem**</span><span class="sxs-lookup"><span data-stu-id="b9153-109">**Post and Email**</span></span>
* <span data-ttu-id="b9153-110">**Dávkové účtování**</span><span class="sxs-lookup"><span data-stu-id="b9153-110">**Post Batch**</span></span>
* <span data-ttu-id="b9153-111">**Náhled účtování**</span><span class="sxs-lookup"><span data-stu-id="b9153-111">**Preview Posting**</span></span>

<span data-ttu-id="b9153-112">Po dokončení všech řádků a zadání všech informací na objednávce ji můžete zaúčtovat.</span><span class="sxs-lookup"><span data-stu-id="b9153-112">When you have completed all the lines and entered all the information on the sales order, you can post it.</span></span> <span data-ttu-id="b9153-113">Tím vytvoříte dodávku a fakturu.</span><span class="sxs-lookup"><span data-stu-id="b9153-113">This creates a shipment and an invoice.</span></span>

<span data-ttu-id="b9153-114">Po zaúčtování prodejní objednávky se aktualizují účty zákazníka, hlavní knihy a položky zboží.</span><span class="sxs-lookup"><span data-stu-id="b9153-114">When a sales order is posted, the customer's account, the general ledger, and the item ledger entries are updated.</span></span>

<span data-ttu-id="b9153-115">Pro každou prodejní objednávku je v tabulce **Věcných položek** vytvořena položka prodeje.</span><span class="sxs-lookup"><span data-stu-id="b9153-115">For each sales order, a sales entry is created in the **G/L Entry** table.</span></span> <span data-ttu-id="b9153-116">Položka je také vytvořena na účtu zákazníka v **Položkách zákazníka Na příslušném účtu pohledávek je vytvořena tabulka Položek** hlavní knihy a položka hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="b9153-116">An entry is also created in the customer's account in the **Cust. Ledger Entry** table and a general ledger entry is created in the relevant receivables account.</span></span> <span data-ttu-id="b9153-117">Kromě toho, může zaúčtování objednávky vést k položce DPH a položce hlavní knihy pro částku slevy.</span><span class="sxs-lookup"><span data-stu-id="b9153-117">In addition, posting the order may result in a VAT entry and a general ledger entry for the discount amount.</span></span> <span data-ttu-id="b9153-118">Zda je položka pro slevu zaúčtována, závisí na obsahu pole **Účtování slevy** v okně **Nastavení Prodeje a Pohledávek**.</span><span class="sxs-lookup"><span data-stu-id="b9153-118">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Sales & Receivables Setup** window.</span></span>

<span data-ttu-id="b9153-119">Pro každý řádek prodejní objednávky bude vytvořena položka zboží v tabulce **Položky zboží** (pokud budou řádky prodeje obsahovat čísla zboží) nebo bude vytvořena položka hlavní knihy v tabulce **Věcných položek** (pokud budou řádky prodeje obsahovat finanční účet).</span><span class="sxs-lookup"><span data-stu-id="b9153-119">For each sales order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the sales lines contain item numbers) or a general ledger entry will be created in the **G/L Entry** table (if the sales lines contain a general ledger account).</span></span> <span data-ttu-id="b9153-120">Kromě toho jsou prodejní objednávky vždy zaznamenávány v tabulkách **Hlavička prodejní dodávky** a **Hlavička prodejních faktur**.</span><span class="sxs-lookup"><span data-stu-id="b9153-120">In addition to this, sales orders are always recorded in the **Sales Shipment Header** and **Sales Invoice Header** tables.</span></span>

> [!IMPORTANT]  
>   <span data-ttu-id="b9153-121">Když zaúčtujete objednávku, můžete vytvořit jak dodávku, tak fakturu.</span><span class="sxs-lookup"><span data-stu-id="b9153-121">When you post an order, you can create both a shipment and an invoice.</span></span> <span data-ttu-id="b9153-122">To může být provedeno současně nebo nezávisle.</span><span class="sxs-lookup"><span data-stu-id="b9153-122">These can be done at the same time or independently.</span></span> <span data-ttu-id="b9153-123">Můžete také vytvořit částečnou dodávku a částečnou fakturu tím, že předtím než účtujete, vyplníte pole **Množ. k dodání** a **Množ. k fakturaci** na jednotlivých řádcích prodejní objednávky.</span><span class="sxs-lookup"><span data-stu-id="b9153-123">You can also create a partial shipment and a partial invoice by completing the **Qty. to Ship** and **Qty. to Invoice** fields on the individual sales order lines before you post.</span></span> <span data-ttu-id="b9153-124">Všimněte si, že nemůžete vytvořit fakturu za něco, co není dodáno.</span><span class="sxs-lookup"><span data-stu-id="b9153-124">Note that you cannot create an invoice for something that is not shipped.</span></span> <span data-ttu-id="b9153-125">To znamená, že předtím, než budete moci fakturovat, musíte mít zaznamenanou dodávku, nebo musíte vybrat dodat a fakturovat současně.</span><span class="sxs-lookup"><span data-stu-id="b9153-125">That is, before you can invoice, you must have recorded a shipment, or you must choose to ship and invoice at the same time.</span></span>

<span data-ttu-id="b9153-126">Když je účtování kompletní, zaúčtované prodejná řádky jsou z objednávky odebrány.</span><span class="sxs-lookup"><span data-stu-id="b9153-126">When the posting is completed, the posted sales lines are removed from the order.</span></span> <span data-ttu-id="b9153-127">Zpráva vám sděluje, kdy je účtování dokončeno.</span><span class="sxs-lookup"><span data-stu-id="b9153-127">A message tells you when the posting is completed.</span></span> <span data-ttu-id="b9153-128">Poté budete moci zobrazit zaúčtované položky v různých oknech, které obsahují zaúčtované položky, jako například okna **Položky zákazníka**, **Věcné položky**, **Položky zboží**, **Zaúčtování prodejních dodávek** a **Zaúčtování prodejních faktur**.</span><span class="sxs-lookup"><span data-stu-id="b9153-128">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Cust. Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Posted Sales Shipments**, and **Posted Sales Invoices** windows.</span></span>

## <a name="see-also"></a><span data-ttu-id="b9153-129">Viz také</span><span class="sxs-lookup"><span data-stu-id="b9153-129">See Also</span></span>
[<span data-ttu-id="b9153-130">Prodej</span><span class="sxs-lookup"><span data-stu-id="b9153-130">Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="b9153-131">Návod: Odesílání dokladů e-mailem</span><span class="sxs-lookup"><span data-stu-id="b9153-131">How to: Send Documents by Email</span></span>](ui-how-send-documents-email.md)  
<span data-ttu-id="b9153-132">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="b9153-132">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>


