---
title: "Vytvoření nákupní faktury z prodejní faktury k nákupuju zboží pro prodej"
description: "Z prodejní faktury pro nákup produktů můžete vytvořit nákupní fakturu pro dodavatele."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supply planning, sales demand, replenish
ms.date: 05/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a6380570c9fb2bc5880bf531b4311fbf6e9cf4ec
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-purchase-items-for-a-sale"></a><span data-ttu-id="20a94-103">Návod: Nákup zboží pro prodej</span><span class="sxs-lookup"><span data-stu-id="20a94-103">How to: Purchase Items for a Sale</span></span>
<span data-ttu-id="20a94-104">Z prodejních objednávek a prodejních faktur můžete použít funkci k rychlému vytvoření nákupních dokumentů pro chybějící množství zboží, které je potřebné pro prodej.</span><span class="sxs-lookup"><span data-stu-id="20a94-104">From sales orders and sales invoices, you can use functions to quickly create purchase documents for missing item quantities that are required by the sale.</span></span> <span data-ttu-id="20a94-105">Můžete použít dvě různé funkce odvíjející se od typu dokumentu.</span><span class="sxs-lookup"><span data-stu-id="20a94-105">You can use two different functions depending on the document type.</span></span>
|<span data-ttu-id="20a94-106">Funkce</span><span class="sxs-lookup"><span data-stu-id="20a94-106">Function</span></span>|<span data-ttu-id="20a94-107">Popis</span><span class="sxs-lookup"><span data-stu-id="20a94-107">Description</span></span>|
|--------|-----------|
|<span data-ttu-id="20a94-108">**Vytvořte nákupní objednávku**</span><span class="sxs-lookup"><span data-stu-id="20a94-108">**Create Purchase Orders**</span></span>|<span data-ttu-id="20a94-109">Z prodejní objednávky, funkce vytvoří nákupní objednávku pro každého dodavatele daného zboží na prodejní objednávce</span><span class="sxs-lookup"><span data-stu-id="20a94-109">From a sales order, this function creates a purchase order for each vendor of items on the sales order.</span></span> <span data-ttu-id="20a94-110">Můžete upravit nakupované množství předtím, než vytvoříte nákupní fakturu.</span><span class="sxs-lookup"><span data-stu-id="20a94-110">You can edit the purchase quantity before you create the purchase orders.</span></span> <span data-ttu-id="20a94-111">Je navrhováno pouze množství k prodeji.</span><span class="sxs-lookup"><span data-stu-id="20a94-111">Only unavailable sales quantities are suggested.</span></span>
|<span data-ttu-id="20a94-112">**Vytvořte nákupní fakturu**</span><span class="sxs-lookup"><span data-stu-id="20a94-112">**Create Purchase Invoice**</span></span>|<span data-ttu-id="20a94-113">Z prodejní objednávky a z prodejní faktury funkce vytvoří nákupní fakturu pro vybraného dodavatele a všechny řádky nebo zvolené řádky na prodejním dokumentu.</span><span class="sxs-lookup"><span data-stu-id="20a94-113">From a sales order and from a sales invoice, this function creates a purchase invoice for a selected vendor for all lines or selected lines on the sales document.</span></span> <span data-ttu-id="20a94-114">Zde je navrhováno celé množství</span><span class="sxs-lookup"><span data-stu-id="20a94-114">The full sales quantity is suggested.</span></span>|

## <a name="to-create-one-or-more-purchase-orders-from-a-sales-order"></a><span data-ttu-id="20a94-115">Vytvoření jedné nebo více nákupních objednávek z prodejní objednávky</span><span class="sxs-lookup"><span data-stu-id="20a94-115">To create one or more purchase orders from a sales order</span></span>
<span data-ttu-id="20a94-116">Pro vytvoření nákupní objednávky pro každe nedostupné množství zboží na prodejní objednávce použijte funkci **Vytvořit nákupní objednávky**.</span><span class="sxs-lookup"><span data-stu-id="20a94-116">To create a purchase order for each unavailable item quantity on the sales order, you use the **Create Purchase Orders** function.</span></span>

1. <span data-ttu-id="20a94-117">Na domovské stránce vyberte dlaždici **Průběžné prodejní objednávky**.</span><span class="sxs-lookup"><span data-stu-id="20a94-117">On the Home page, choose the **Ongoing Sales Orders** tile.</span></span>
2. <span data-ttu-id="20a94-118">otebřete prodejní objednávku, kterou chcete nakupovat zboží.</span><span class="sxs-lookup"><span data-stu-id="20a94-118">Open a sales order that you want to purchase items for.</span></span>
3. <span data-ttu-id="20a94-119">Zvolte akci **Vytvořit nákupní objednávku**.</span><span class="sxs-lookup"><span data-stu-id="20a94-119">Choose the **Create Purchase Orders** action.</span></span>

    <span data-ttu-id="20a94-120">Otevře se okno **Vytvořit nákupní objednávku** zobrazující řádek pro každé rozdílné zboží na prodejní objednávce.</span><span class="sxs-lookup"><span data-stu-id="20a94-120">The **Create Purchase Orders** window opens showing a line for each different item on the sales order.</span></span> <span data-ttu-id="20a94-121">Do výchozího nastavení jsou zobrazeny řádky pro plně dostupné prodejní množství a nedostupné prodejní množství (šedě).</span><span class="sxs-lookup"><span data-stu-id="20a94-121">Lines for both fully available sales quantities and unavailable sales quantities (grayed) are shown by default.</span></span> <span data-ttu-id="20a94-122">Můžete zvolit **Zobrazit nedostupné** k zobrazení řádků s pouze nedostupným prodejním množstvím.</span><span class="sxs-lookup"><span data-stu-id="20a94-122">You can choose the **Show Unavailable** action to only see lines for unavailable sales quantities.</span></span>

    <span data-ttu-id="20a94-123">Pole **Množství k nákupu** obsahuje ve výchozím nastavení nedostupné prodejní množství. </span><span class="sxs-lookup"><span data-stu-id="20a94-123">The **Quantity to Purchase** field contains the unavailable sales quantity by default.</span></span>
4. <span data-ttu-id="20a94-124">K nákupu jiného množství než nedostupného, upravte hodnotu v poli **Množství k nákupu**.</span><span class="sxs-lookup"><span data-stu-id="20a94-124">To purchase another quantity than the unavailable sales quantity, edit the value in the **Quantity to Purchase** field.</span></span>

    > [!NOTE]  
>   <span data-ttu-id="20a94-125">Políčko **Množství k nákupu** můžete také změnit na šedých řádcích, přestože představují plně dostupné prodejní množství.</span><span class="sxs-lookup"><span data-stu-id="20a94-125">You can also change the **Quantity to Purchase** field on grayed lines even though they represent fully available sales quantities.</span></span>
5. <span data-ttu-id="20a94-126">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="20a94-126">Choose the **OK** button.</span></span>

    <span data-ttu-id="20a94-127">Pro každého dodavatele zboží je vytvovřena nákupní objednávka včetně změn množství, které jste provedli na prodejní objednávce.</span><span class="sxs-lookup"><span data-stu-id="20a94-127">A purchase order is created for each vendor of items on the sales order, including any quantity changes that you made in the **Create Purchase Orders** window.</span></span>
7. <span data-ttu-id="20a94-128">Pokračujte ve zpracování nákupní objednávky / objednávek, například úpravou nebo přidáním nákupních objednávkových řádků.</span><span class="sxs-lookup"><span data-stu-id="20a94-128">Proceed to process the purchase order or orders, for example, by editing or adding purchase order lines.</span></span> <span data-ttu-id="20a94-129">Další informace naleznete v tématu [Návod: Zaznamenávání nákupů.](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="20a94-129">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>


## <a name="to-create-a-purchase-invoice-from-a-sales-order-or-sales-invoice"></a><span data-ttu-id="20a94-130">Vytvoření nákupní faktury z prodejní objednávky nebo prodejní faktury</span><span class="sxs-lookup"><span data-stu-id="20a94-130">To create a purchase invoice from a sales order or sales invoice</span></span>
<span data-ttu-id="20a94-131">Chcete-li vytvořit jednu nákupní fakturu pro jeden nebo více řádků v prodejním dokladu, vyberte nejprve dodavatele, od kterého chcete nakupovat a použijte funkci **Vytvořit nákupní fakturu fakturu**.</span><span class="sxs-lookup"><span data-stu-id="20a94-131">To create a single purchase invoice for one or more lines on a sales document by first selecting which vendor to buy from, you use the **Create Purchase Invoice** function.</span></span>

> [!NOTE]  
>   <span data-ttu-id="20a94-132">Tato funkce vytvořte nákupní fakturu pro stejné množství zboží jako na vybraném prodejním dokumentu.</span><span class="sxs-lookup"><span data-stu-id="20a94-132">This function creates a purchase invoice for the exact item quantity on the selected sales document.</span></span> <span data-ttu-id="20a94-133">Chcete-li změnit nakupované množství, musíte nejdříve vytvořit nákupní fakturu.</span><span class="sxs-lookup"><span data-stu-id="20a94-133">To change the purchase quantity, you must edit the purchase invoice after it is created.</span></span>  

1. <span data-ttu-id="20a94-134">Na domovské stránce vyberte dlaždici **Pokračující prodejní faktury**.</span><span class="sxs-lookup"><span data-stu-id="20a94-134">On the Home page, choose the **Ongoing Sales Invoices** tile.</span></span>
2. <span data-ttu-id="20a94-135">Otevřete prodejní fakturu, kterou chcete nakupovat zboží.</span><span class="sxs-lookup"><span data-stu-id="20a94-135">Open a sales invoice that you want to purchase items for.</span></span>
3. <span data-ttu-id="20a94-136">Vyberte jeden nebo více řádků prodejních faktur, které chcete použít na nákupní faktuře.</span><span class="sxs-lookup"><span data-stu-id="20a94-136">Select one or more sales invoice lines that you want to use on the purchase invoice.</span></span> <span data-ttu-id="20a94-137">Chcete-li použít všechny řádky prodejních faktur, vyberte buď všechny z nich nebo nevybírejte žádné řádky.</span><span class="sxs-lookup"><span data-stu-id="20a94-137">To use all the sales invoice lines, select either all of them or do not select any lines.</span></span>
4. <span data-ttu-id="20a94-138">Zvolte akci **Vytvořit nákupní fakturu**.</span><span class="sxs-lookup"><span data-stu-id="20a94-138">Choose the **Create Purchase Invoice** action.</span></span>
5. <span data-ttu-id="20a94-139">Vyberte možnost **Všechny řádky** nebo **Vybrané řádky** a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="20a94-139">Select either **All Lines** or **Selected Lines**, and then choose the **OK** button.</span></span>  
6. <span data-ttu-id="20a94-140">V seznamu dodavatelů, který se zobrazí, vyberte dodavatele, od kterého chcete nakupovat zboží a klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="20a94-140">In the list of vendors that appears, select the vendor that you want to buy all the items from, and then choose the **OK** button.</span></span>

    <span data-ttu-id="20a94-141">Vytvoří se nákupní faktura, která obsahuje jeden nebo více řádků na prodejní faktuře.</span><span class="sxs-lookup"><span data-stu-id="20a94-141">A purchase invoice is created that contains one, more, or all the lines on the sales invoice.</span></span>
7. <span data-ttu-id="20a94-142">Pokračujte ve zpracování nákupní faktury například úpravou nebo přidáním nákupních fakturačních řádků.</span><span class="sxs-lookup"><span data-stu-id="20a94-142">Proceed to process the purchase invoice, for example, by editing or adding purchase invoice lines.</span></span> <span data-ttu-id="20a94-143">Další informace naleznete v tématu [Návod: Zaznamenávání nákupů.](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="20a94-143">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="20a94-144">Viz také</span><span class="sxs-lookup"><span data-stu-id="20a94-144">See Also</span></span>
[<span data-ttu-id="20a94-145">Nákup</span><span class="sxs-lookup"><span data-stu-id="20a94-145">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="20a94-146">Návod: Zaznamenávání nákupu</span><span class="sxs-lookup"><span data-stu-id="20a94-146">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="20a94-147">Návod: Prodejní faktury.</span><span class="sxs-lookup"><span data-stu-id="20a94-147">How to: Invoice Sales</span></span>](sales-how-invoice-sales.md)  
[<span data-ttu-id="20a94-148">Návod: Registrace nového dodavatele</span><span class="sxs-lookup"><span data-stu-id="20a94-148">How to: Register New Vendors</span></span>](purchasing-how-register-new-vendors.md)  
<span data-ttu-id="20a94-149">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="20a94-149">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

