---
title: "Vytvořit prodejní objednávku propojenou k nákupní objednávce pro přímou dodávku"
description: "Popisuje, jak vytvořit prodejní objednávku propojenou k nákupní objednávce k povolení dodávky přímo od dodavatele k zákazníkovi."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: direct shipment
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 6a8210808532ff8945660c23f0bf91719e2f2963
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-make-drop-shipments"></a><span data-ttu-id="a0b5f-103">Návod: Vytvoření přímé dodávky</span><span class="sxs-lookup"><span data-stu-id="a0b5f-103">How to: Make Drop Shipments</span></span>
<span data-ttu-id="a0b5f-104">Přímá dodávka je zásilka položek od jednoho z vašich dodavatelů přímo k vašemu zákazníkovi.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-104">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span></span>

<span data-ttu-id="a0b5f-105">Je-li prodejní objednávka označena jako přímá dodávka a vy vytvoříte nákupní objednávku určující zákazníka v políčku **Prodat zákazníkovi číslo**,</span><span class="sxs-lookup"><span data-stu-id="a0b5f-105">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span></span> <span data-ttu-id="a0b5f-106">poté můžete propojit dva dokumenty a instruovat dodavatele, aby odeslal objednávku přímo zákazníkovi.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-106">field, you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span></span>

## <a name="to-create-a-sales-order-for-drop-shipment"></a><span data-ttu-id="a0b5f-107">Vytvoření nové prodejní objednávky pro přímou dodávku.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-107">To create a sales order for drop shipment</span></span>
<span data-ttu-id="a0b5f-108">Chcete-li připravit přímou dodávku, vytvořte prodejní objednávku zboží jako obvykle, kromě toho, že na řádku prodejní objednávky musíte uvést, že se jedná o přímou dodávku.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-108">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span></span>

1. <span data-ttu-id="a0b5f-109">Vytvoření prodejní objednávky pro položku.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-109">Create a sales order for an item.</span></span> <span data-ttu-id="a0b5f-110">Další informace naleznete v [Návod: Prodávání produktů](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="a0b5f-110">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
2. <span data-ttu-id="a0b5f-111">Na řádku prodejní objednávky pro přímou dodávku zaškrtněte políčko **Přímá dodávka**.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-111">On the sales order line for the drop shipment, select the **Drop Shipment** check box.</span></span> <span data-ttu-id="a0b5f-112">Použijte funkci **Vybrat sloupce**, pokud .není pole viditelné</span><span class="sxs-lookup"><span data-stu-id="a0b5f-112">Use the **Choose Columns** function if the field is not visible.</span></span> <span data-ttu-id="a0b5f-113">Další informace naleznete v tématu [Přizpůsobení uživatele](ui-user-personalization.md).</span><span class="sxs-lookup"><span data-stu-id="a0b5f-113">For more information, see [User Personalization](ui-user-personalization.md).</span></span>

## <a name="to-create-the-purchase-order-for-drop-shipment"></a><span data-ttu-id="a0b5f-114">Vytvoření nákupní objednávky pro přímou dodávku</span><span class="sxs-lookup"><span data-stu-id="a0b5f-114">To create the purchase order for drop shipment</span></span>
<span data-ttu-id="a0b5f-115">Chcete-li vytvořit přímou dodávku pro zboží, které má být prodáváno, vytvořte prodejní objednávku jako obvykle. Jen v objednávce musíte uvést, že zásilka musí být odeslána zákazníkovi, nikoli vám.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-115">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span></span>

1. <span data-ttu-id="a0b5f-116">Vytvořte nákupní objednávku.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-116">Create a purchase order.</span></span> <span data-ttu-id="a0b5f-117">Nevyplňujte žádná políčka na řádcích.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-117">Do not fill any fields on the lines.</span></span> <span data-ttu-id="a0b5f-118">Další informace naleznete v [Návod: Zaznamenávání nákupů](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="a0b5f-118">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
2. <span data-ttu-id="a0b5f-119">V políčku **Zákazník**</span><span class="sxs-lookup"><span data-stu-id="a0b5f-119">In the **Sell-to Customer No.**</span></span> <span data-ttu-id="a0b5f-120">vyberte zákazníka, kterému chcete prodávat.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-120">field, select the customer that you are selling to.</span></span>
3. <span data-ttu-id="a0b5f-121">Vyberte tlačítko **Přímá dodávka** a tlačítko **Kopírovat prodejní objednávku**.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-121">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span></span>
4. <span data-ttu-id="a0b5f-122">V okně **Přehled prodeje** vyberte prodejní objednávku, kterou jste nachystali v sekci „Vytvoření prodejní objednávky pro přímou dodávku“.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-122">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span></span>
5. <span data-ttu-id="a0b5f-123">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-123">Choose the **OK** button.</span></span>

<span data-ttu-id="a0b5f-124">Informace o řádku z prodejní objednávky jsou vloženy na řádku (řádcích) nákupní objednávky.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-124">The line information from the sales order is inserted on the purchase order line(s).</span></span>

<span data-ttu-id="a0b5f-125">Nyní můžete instruovat dodavatele, aby zboží odeslal zákazníkovi, například zasláním objednávky ve formátu PDF.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-125">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span></span>     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a><span data-ttu-id="a0b5f-126">Zobrazení propojení nákupní objednávky s prodejní objednávkou.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-126">To view the linked purchase order from the sales order</span></span>
* <span data-ttu-id="a0b5f-127">Vyberte řádek přímé objednávky a zvolte tlačítko **Objednávka**, vyberte **Přímá objednávka** a vyberte tlačítko **Nákupní objednávka**.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-127">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span></span>

## <a name="to-post-a-drop-shipment"></a><span data-ttu-id="a0b5f-128">Účtování přímé dodávky</span><span class="sxs-lookup"><span data-stu-id="a0b5f-128">To post a drop shipment</span></span>
<span data-ttu-id="a0b5f-129">Potom, co dodavatel odeslal zboží, můžete zaúčtovat prodejní objednávku jako dodanou.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-129">After the vendor ships the items, you can post the sales order as shipped.</span></span> <span data-ttu-id="a0b5f-130">Také můžete účtovat nákupní objednávku, ale jen s možností **Přijatá** dokud prodejní objednávka nebude vyfakturována.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-130">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span></span>

1. <span data-ttu-id="a0b5f-131">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní objednávky** a poté vyberte příslušný odkaz.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="a0b5f-132">Otevřete prodejní objednávku, kterou jste vytvořili v sekci „Vytvoření prodejní objednávky pro přímou dodávku“.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-132">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span></span>
3. <span data-ttu-id="a0b5f-133">V políčku **Množství k odeslání** specifikujte počet jednotek z objednaného zboží k odeslání, buď celé nebo částečné množství.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-133">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span></span>
4. <span data-ttu-id="a0b5f-134">Vyberte tlačítko **Účtovat** nebo **Účtovat a odeslat**.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-134">Choose the **Post** or **Post and Send** action.</span></span>
5. <span data-ttu-id="a0b5f-135">Zvolte buď volbu **Odeslat** pro pozdější fakturaci, nebo volbu **Odeslat a fakturovat** okamžitě fakturovat.</span><span class="sxs-lookup"><span data-stu-id="a0b5f-135">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span></span>

## <a name="see-also"></a><span data-ttu-id="a0b5f-136">Viz také</span><span class="sxs-lookup"><span data-stu-id="a0b5f-136">See Also</span></span>
<span data-ttu-id="a0b5f-137">[Návody: Vytvořit zvláštní objednávky](sales-how-to-create-special-orders.md)|</span><span class="sxs-lookup"><span data-stu-id="a0b5f-137">[How to: Create Special Orders](sales-how-to-create-special-orders.md)|</span></span>  
[<span data-ttu-id="a0b5f-138">Návod: Prodávání produktu</span><span class="sxs-lookup"><span data-stu-id="a0b5f-138">How to: Sell Products</span></span>](sales-how-sell-products.md)  
[<span data-ttu-id="a0b5f-139">Návod: Zaznamenávání nákupu</span><span class="sxs-lookup"><span data-stu-id="a0b5f-139">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="a0b5f-140">Prodej</span><span class="sxs-lookup"><span data-stu-id="a0b5f-140">Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="a0b5f-141">Sklady</span><span class="sxs-lookup"><span data-stu-id="a0b5f-141">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="a0b5f-142">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a0b5f-142">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

