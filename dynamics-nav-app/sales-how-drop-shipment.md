---
title: "Návod: Vytvoření Přímé dodávky"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: a726c8c24d8f843b33b4df4d85ad2b5eab3790e7
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-make-drop-shipments"></a><span data-ttu-id="fc6a2-102">Návod: Vytvoření Přímé dodávky</span><span class="sxs-lookup"><span data-stu-id="fc6a2-102">How to: Make Drop Shipments</span></span>
<span data-ttu-id="fc6a2-103">Přímá dodávka je zásilka položek od jednoho z vašich dodavatelů přímo k vašemu zákazníkovi.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-103">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span></span>

<span data-ttu-id="fc6a2-104">Je-li prodejní objednávka označena jako přímá dodávka a vy vytvoříte nákupní objednávku určující zákazníka v políčku **Prodat zákazníkovi číslo**,</span><span class="sxs-lookup"><span data-stu-id="fc6a2-104">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span></span> <span data-ttu-id="fc6a2-105">poté můžete propojit dva dokumenty a instruovat dodavatele, aby odeslal objednávku přímo zákazníkovi.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-105">field, then you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span></span>

## <a name="to-create-a-sales-order-for-drop-shipment"></a><span data-ttu-id="fc6a2-106">Vytvoření nové prodejní objednávky pro přímou dodávku.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-106">To create a sales order for drop shipment</span></span>
<span data-ttu-id="fc6a2-107">Chcete-li připravit přímou dodávku, vytvořte prodejní objednávku zboží jako obvykle, kromě toho, že na řádku prodejní objednávky musíte uvést, že se jedná o přímou dodávku.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-107">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span></span>

1. <span data-ttu-id="fc6a2-108">Vytvoření prodejní objednávky pro položku.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-108">Create a sales order for an item.</span></span> <span data-ttu-id="fc6a2-109">Další informace naleznete v tématu [Návod: Prodávání produktů](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="fc6a2-109">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
2. <span data-ttu-id="fc6a2-110">Na řádku prodejní objednávky pro přímou dodávku zaškrtněte políčko **Přímá dodávka**.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-110">On the sales order line for the drop-shipment item, select the **Drop Shipment** check box.</span></span>

## <a name="to-create-the-purchase-order-for-drop-shipment"></a><span data-ttu-id="fc6a2-111">Vytvoření nákupní objednávky pro přímou dodávku</span><span class="sxs-lookup"><span data-stu-id="fc6a2-111">To create the purchase order for drop shipment</span></span>
<span data-ttu-id="fc6a2-112">Chcete-li vytvořit přímou dodávku pro zboží, které má být prodáváno, vytvořte prodejní objednávku jako obvykle. Jen v objednávce musíte uvést, že zásilka musí být odeslána zákazníkovi, nikoli vám.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-112">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span></span>

1. <span data-ttu-id="fc6a2-113">Vytvořte nákupní objednávku.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-113">Create a purchase order.</span></span> <span data-ttu-id="fc6a2-114">Nevyplňujte žádná políčka na řádcích.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-114">Do not fill any fields on the lines.</span></span> <span data-ttu-id="fc6a2-115">Další informace naleznete v tématu [Návod: Zaznamenávání nákupů](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="fc6a2-115">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
2. <span data-ttu-id="fc6a2-116">V políčku **Zákazník**</span><span class="sxs-lookup"><span data-stu-id="fc6a2-116">In the **Sell-to Customer No.**</span></span> <span data-ttu-id="fc6a2-117">vyberte zákazníka, kterému chcete prodávat.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-117">field, select the customer that you are selling to.</span></span>
3. <span data-ttu-id="fc6a2-118">Vyberte tlačítko **Přímá dodávka** a tlačítko **Kopírovat prodejní objednávku**.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-118">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span></span>
4. <span data-ttu-id="fc6a2-119">V okně **Přehled prodeje** vyberte prodejní objednávku, kterou jste nachystali v sekci „Vytvoření prodejní objednávky pro přímou dodávku“.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-119">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span></span>
5. <span data-ttu-id="fc6a2-120">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-120">Choose the **OK** button.</span></span>

<span data-ttu-id="fc6a2-121">Informace o řádku z prodejní objednávky jsou vloženy na řádku (řádcích) nákupní objednávky.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-121">The line information from the sales order is inserted on the purchase order line(s).</span></span>

<span data-ttu-id="fc6a2-122">Nyní můžete instruovat dodavatele, aby zboží odeslal zákazníkovi, například zasláním objednávky ve formátu PDF.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-122">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span></span>     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a><span data-ttu-id="fc6a2-123">Zobrazení propojení nákupní objednávky s prodejní objednávkou.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-123">To view the linked purchase order from the sales order</span></span>
1. <span data-ttu-id="fc6a2-124">Vyberte řádek přímé objednávky a zvolte tlačítko **Objednávka**, vyberte **Přímá objednávka** a vyberte tlačítko **Nákupní objednávka**.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-124">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span></span>

<span data-ttu-id="fc6a2-125">Propojená nákupní objednávka se otevře.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-125">The linked purchase order opens.</span></span>

## <a name="to-post-a-drop-shipment"></a><span data-ttu-id="fc6a2-126">Účtování přímé dodávky</span><span class="sxs-lookup"><span data-stu-id="fc6a2-126">To post a drop shipment</span></span>
<span data-ttu-id="fc6a2-127">Když dodavatel odeslal zboží, můžete zaúčtovat prodejní objednávku jako dodanou.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-127">When the vendor has shipped the items, you can post the sales order as shipped.</span></span> <span data-ttu-id="fc6a2-128">Také můžete účtovat nákupní objednávku, ale jen s možností **Přijatá** dokud prodejní objednávka nebude vyfakturována.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-128">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span></span>
1. <span data-ttu-id="fc6a2-129">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Prodejní objednávky** a poté vyberte příslušný odkaz.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-129">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="fc6a2-130">Otevřete prodejní objednávku, kterou jste vytvořili v sekci „Vytvoření prodejní objednávky pro přímou dodávku“.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-130">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span></span>
3. <span data-ttu-id="fc6a2-131">V políčku **Množství k odeslání** specifikujte počet jednotek z objednaného zboží k odeslání, buď celé nebo částečné množství.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-131">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span></span>
3. <span data-ttu-id="fc6a2-132">Vyberte tlačítko **Účtovat** nebo **Účtovat a odeslat**.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-132">Choose the **Post** or **Post and Send** action.</span></span>
4. <span data-ttu-id="fc6a2-133">Zvolte buď volbu **Odeslat** pro pozdější fakturaci, nebo volbu **Odeslat a fakturovat** okamžitě fakturovat.</span><span class="sxs-lookup"><span data-stu-id="fc6a2-133">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span></span>

## <a name="see-also"></a><span data-ttu-id="fc6a2-134">Viz také</span><span class="sxs-lookup"><span data-stu-id="fc6a2-134">See Also</span></span>
<span data-ttu-id="fc6a2-135">[Návod: Prodejní produkty](sales-how-sell-products.md)  </span><span class="sxs-lookup"><span data-stu-id="fc6a2-135">[How to: Sell Products](sales-how-sell-products.md)  </span></span>  
[<span data-ttu-id="fc6a2-136">Návod: Zaznamenávání nákupů</span><span class="sxs-lookup"><span data-stu-id="fc6a2-136">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="fc6a2-137">Správa prodeje</span><span class="sxs-lookup"><span data-stu-id="fc6a2-137">Manage Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="fc6a2-138">[Správa skladů](inventory-manage-inventory.md)    </span><span class="sxs-lookup"><span data-stu-id="fc6a2-138">[Manage Inventory](inventory-manage-inventory.md)    </span></span>  
<span data-ttu-id="fc6a2-139">[Práce s [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="fc6a2-139">[Work with Dynamics NAV](ui-work-product.md)</span></span>

