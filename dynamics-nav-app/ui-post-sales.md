---
title: "Účtování prodeje"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: e87dd5faf7713aecfbe7209d00bb8076fcae9d25
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="posting-sales"></a><span data-ttu-id="ebabf-102">Účtování prodeje</span><span class="sxs-lookup"><span data-stu-id="ebabf-102">Posting Sales</span></span>
<span data-ttu-id="ebabf-103">Ve skupině **Účtování** na prodejním dokladu si můžete vybrat mezi následujícími účtovacími funkcemi:</span><span class="sxs-lookup"><span data-stu-id="ebabf-103">In the **Posting group** on a sales document, you can choose between the following posting functions:</span></span>

- <span data-ttu-id="ebabf-104">**Účtovat**</span><span class="sxs-lookup"><span data-stu-id="ebabf-104">**Post**</span></span>
- <span data-ttu-id="ebabf-105">**Testovací sestava**</span><span class="sxs-lookup"><span data-stu-id="ebabf-105">**Test Report**</span></span>
- <span data-ttu-id="ebabf-106">**Účtovat a odeslat**</span><span class="sxs-lookup"><span data-stu-id="ebabf-106">**Post and Send**</span></span>
- <span data-ttu-id="ebabf-107">**Účtovat a vytisknout**</span><span class="sxs-lookup"><span data-stu-id="ebabf-107">**Post and Print**</span></span>
- <span data-ttu-id="ebabf-108">**Účtovat a poslat e-mailem**</span><span class="sxs-lookup"><span data-stu-id="ebabf-108">**Post and Email**</span></span>
- <span data-ttu-id="ebabf-109">**Dávkové účtování**</span><span class="sxs-lookup"><span data-stu-id="ebabf-109">**Post Batch**</span></span>
- <span data-ttu-id="ebabf-110">**Náhled účtování**</span><span class="sxs-lookup"><span data-stu-id="ebabf-110">**Preview Posting**</span></span>

<span data-ttu-id="ebabf-111">Po dokončení všech řádků a zadání všech informací na objednávce ji můžete zaúčtovat.</span><span class="sxs-lookup"><span data-stu-id="ebabf-111">When you have completed all the lines and entered all the information on the sales order, you can post it.</span></span> <span data-ttu-id="ebabf-112">Tím vytvoříte dodávku a fakturu.</span><span class="sxs-lookup"><span data-stu-id="ebabf-112">This creates a shipment and an invoice.</span></span>

<span data-ttu-id="ebabf-113">Po zaúčtování prodejní objednávky se aktualizují účty zákazníka, hlavní knihy a položky zboží.</span><span class="sxs-lookup"><span data-stu-id="ebabf-113">When a sales order is posted, the customer's account, the general ledger, and the item ledger entries are updated.</span></span>

<span data-ttu-id="ebabf-114">Pro každou prodejní objednávku je v tabulce **Věcných položek** vytvořena položka prodeje.</span><span class="sxs-lookup"><span data-stu-id="ebabf-114">For each sales order, a sales entry is created in the **G/L Entry** table.</span></span> <span data-ttu-id="ebabf-115">Položka je také vytvořena na účtu zákazníka v **Položkách zákazníka** Na příslušném účtu pohledávek je vytvořena tabulka Položek hlavní knihy a položka hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="ebabf-115">An entry is also created in the customer's account in the **Cust. Ledger Entry** table and a general ledger entry is created in the relevant receivables account.</span></span> <span data-ttu-id="ebabf-116">Kromě toho, může zaúčtování objednávky vést k položce DPH a položce hlavní knihy pro částku slevy.</span><span class="sxs-lookup"><span data-stu-id="ebabf-116">In addition, posting the order may result in a VAT entry and a general ledger entry for the discount amount.</span></span> <span data-ttu-id="ebabf-117">Zda je položka pro slevu zaúčtována, závisí na obsahu pole **Účtování slevy** v okně **Nastavení Prodeje a Pohledávek**.</span><span class="sxs-lookup"><span data-stu-id="ebabf-117">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Sales & Receivables Setup** window.</span></span>

<span data-ttu-id="ebabf-118">Pro každý řádek prodejní objednávky bude vytvořena položka zboží v tabulce **Položky zboží** (pokud budou řádky prodeje obsahovat čísla zboží) nebo bude vytvořena položka hlavní knihy v tabulce **Věcných položek** (pokud budou řádky prodeje obsahovat finanční účet).</span><span class="sxs-lookup"><span data-stu-id="ebabf-118">For each sales order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the sales lines contain item numbers) or a general ledger entry will be created in the **G/L Entry** table (if the sales lines contain a general ledger account).</span></span> <span data-ttu-id="ebabf-119">Kromě toho jsou prodejní objednávky vždy zaznamenávány v tabulkách **Hlavička prodejní dodávky** a **Hlavička prodejních faktur**.</span><span class="sxs-lookup"><span data-stu-id="ebabf-119">In addition to this, sales orders are always recorded in the **Sales Shipment Header** and **Sales Invoice Header** tables.</span></span>

<span data-ttu-id="ebabf-120">**Důležité**: Když zaúčtujete objednávku, můžete vytvořit jak dodávku, tak fakturu.</span><span class="sxs-lookup"><span data-stu-id="ebabf-120">**Important**: When you post an order, you can create both a shipment and an invoice.</span></span> <span data-ttu-id="ebabf-121">To může být provedeno současně nebo nezávisle.</span><span class="sxs-lookup"><span data-stu-id="ebabf-121">These can be done at the same time or independently.</span></span> <span data-ttu-id="ebabf-122">Můžete také vytvořit částečnou dodávku a částečnou fakturu tím, že předtím než účtujete, vyplníte pole **Množ. k dodání** a **Množ. k fakturaci** na jednotlivých řádcích prodejní objednávky.</span><span class="sxs-lookup"><span data-stu-id="ebabf-122">You can also create a partial shipment and a partial invoice by completing the **Qty. to Ship** and **Qty. to Invoice** fields on the individual sales order lines before you post.</span></span> <span data-ttu-id="ebabf-123">Všimněte si, že nemůžete vytvořit fakturu za něco, co není dodáno. </span><span class="sxs-lookup"><span data-stu-id="ebabf-123">Note that you cannot create an invoice for something that is not shipped.</span></span> <span data-ttu-id="ebabf-124">To znamená, že předtím, než budete moci fakturovat, musíte mít zaznamenanou dodávku, nebo musíte vybrat dodat a fakturovat současně.</span><span class="sxs-lookup"><span data-stu-id="ebabf-124">That is, before you can invoice, you must have recorded a shipment, or you must choose to ship and invoice at the same time.</span></span> 

<span data-ttu-id="ebabf-125">Když je účtování kompletní, zaúčtované prodejná řádky jsou z objednávky odebrány.</span><span class="sxs-lookup"><span data-stu-id="ebabf-125">When the posting is completed, the posted sales lines are removed from the order.</span></span> <span data-ttu-id="ebabf-126">Zpráva vám sděluje, kdy je účtování dokončeno.</span><span class="sxs-lookup"><span data-stu-id="ebabf-126">A message tells you when the posting is completed.</span></span> <span data-ttu-id="ebabf-127">Poté budete moci zobrazit zaúčtované položky v různých oknech, které obsahují zaúčtované položky, jako například okna **Položky zákazníka**, **Věcné položky**, **Položky zboží**, **Zaúčtování prodejních dodávek** a **Zaúčtování prodejních faktur**.</span><span class="sxs-lookup"><span data-stu-id="ebabf-127">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Cust. Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Posted Sales Shipments**, and **Posted Sales Invoices** windows.</span></span>

## <a name="see-also"></a><span data-ttu-id="ebabf-128">Viz také</span><span class="sxs-lookup"><span data-stu-id="ebabf-128">See Also</span></span>
[<span data-ttu-id="ebabf-129">Návod: Odesílání dokladů e-mailem</span><span class="sxs-lookup"><span data-stu-id="ebabf-129">How to: Send Documents by Email</span></span>](ui-how-send-documents-email.md)

