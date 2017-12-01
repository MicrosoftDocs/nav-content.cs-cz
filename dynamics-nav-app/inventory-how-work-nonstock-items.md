---
title: "Vytvoření a správa neskladovaného zboží"
description: "Popisuje, jak obchodovat se zbožím, které není v zásobách nebo se zbožím, které není ve vašich zásobách udržováno."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: non-inventoriable
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: dee8b9ec3b47760f0ececc0a13f68c0039ad4c1a
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-work-with-nonstock-items"></a><span data-ttu-id="a331a-103">Návod: Práce s neskladovaným zbožím</span><span class="sxs-lookup"><span data-stu-id="a331a-103">How to: Work with Nonstock Items</span></span>
<span data-ttu-id="a331a-104">Můžete nabídnout svým zákazníkům určité zboží pro jejich pohodlí, které nechcete udržovat v zásobách, dokud je nezačnete prodávat.</span><span class="sxs-lookup"><span data-stu-id="a331a-104">You can offer certain items to your customers for their convenience, which you do not want to maintain in inventory until you start selling them.</span></span> <span data-ttu-id="a331a-105">Chcete-li toto zboží ukládat do zásob, můžete ho převést na běžné karty zboží dvěma způsoby.</span><span class="sxs-lookup"><span data-stu-id="a331a-105">When you want to start maintaining such items in inventory, you can convert them to normal item cards in two ways.</span></span>

* <span data-ttu-id="a331a-106">Z karty neskladovaného zboží vytvořte novou kartu zboží založenou na šabloně.</span><span class="sxs-lookup"><span data-stu-id="a331a-106">From a nonstock item card, create a new item card based on a template.</span></span>
* <span data-ttu-id="a331a-107">Z řádku prodejní objednávky typu **Zboží** s prázdným polem **Číslo** vyberte neskladované zboží.</span><span class="sxs-lookup"><span data-stu-id="a331a-107">From a sales order line of type **Item** with an empty **No* field, select a nonstock item.</span></span> <span data-ttu-id="a331a-108">Karta zboží je automaticky vytvořena pro neskladované zboží.</span><span class="sxs-lookup"><span data-stu-id="a331a-108">An item card is automatically created for the nonstock item.</span></span>

> [!NOTE]  
>   <span data-ttu-id="a331a-109">Nemůžete vybrat neskladované zboží z okna **Prodejní faktura**.</span><span class="sxs-lookup"><span data-stu-id="a331a-109">You cannot select a nonstock item from the **Sales Invoice** window.</span></span> <span data-ttu-id="a331a-110">Můžete vybrat neskladované zboží z okna **Prodejní nabídka**, ale neskladované zboží nebude převedeno na normální, pokud použijete funkci **Vytvořit objednávku**.</span><span class="sxs-lookup"><span data-stu-id="a331a-110">You can select a nonstock item from the **Sales Quote** window, but the nonstock item will not be converted to a normal item when you use the **Make Order** function.</span></span>

<span data-ttu-id="a331a-111">Neskladové zboží má typicky číslo zboží dodavatele, který jej nabízí.</span><span class="sxs-lookup"><span data-stu-id="a331a-111">A nonstock item typically has the item number of the vendor who supplies it.</span></span> <span data-ttu-id="a331a-112">Chcete-li povolit konverzi karty neskladovaného zboží na normální kartu zboží, musíte nejprve nastavit, jak bude převedeno číslování položek dodavatele na vaše číslování položek.</span><span class="sxs-lookup"><span data-stu-id="a331a-112">To enable conversion of a nonstock item card to a normal item card, you must first set up how vendor item numbering is converted to your own item numbering.</span></span>   

## <a name="to-create-a-nonstock-item"></a><span data-ttu-id="a331a-113">Vytvoření neskladovaného zboží</span><span class="sxs-lookup"><span data-stu-id="a331a-113">To create a nonstock item</span></span>
<span data-ttu-id="a331a-114">Karty neskladovaného zboží mají mnohem méně informací než karty normálního zboží, protože je používáte pouze na nabídkách a jinými způsoby.</span><span class="sxs-lookup"><span data-stu-id="a331a-114">Nonstock item cards have much less information than normal item cards because you only use them to offer on quotes and in other ways.</span></span> <span data-ttu-id="a331a-115">Z tohoto důvodu je třeba je převést na normální kartu, než budete moci za ně zaúčtovat prodejní transakce.</span><span class="sxs-lookup"><span data-stu-id="a331a-115">For that reason, they must be converted to normal item cards before you can post sales transactions for them.</span></span>

1. <span data-ttu-id="a331a-116">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Neskladované zboží** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="a331a-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Nonstock Items**, and then choose the related link.</span></span>
2. <span data-ttu-id="a331a-117">Vyberte akci **Nový**.</span><span class="sxs-lookup"><span data-stu-id="a331a-117">Choose the **New** action.</span></span>
3. <span data-ttu-id="a331a-118">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="a331a-118">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-how-nonstock-item-numbers-are-converted-to-your-own-numbering"></a><span data-ttu-id="a331a-119">Nastavení převodu čísel neskladovaných položek na vlastní číslování</span><span class="sxs-lookup"><span data-stu-id="a331a-119">To set up how nonstock item numbers are converted to your own numbering</span></span>
<span data-ttu-id="a331a-120">Chcete-li povolit konverzi karty neskladovaného zboží na kartu normálního zboží, musíte nejprve nastavit, jak bude číslování zboží prodejce převedeno na váš vlastní formát čísla zboží.</span><span class="sxs-lookup"><span data-stu-id="a331a-120">To enable conversion of a nonstock item card to a normal item card, you must first set up how the vendor's item numbering is converted to your own item number format.</span></span>

1. <span data-ttu-id="a331a-121">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení neskladovaného zboží** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="a331a-121">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Nonstock Item Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="a331a-122">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="a331a-122">Fill in the fields as necessary.</span></span>

## <a name="to-convert-a-nonstock-item-to-a-normal-item"></a><span data-ttu-id="a331a-123">Převod neskladovaného zboží na normální</span><span class="sxs-lookup"><span data-stu-id="a331a-123">To convert a nonstock item to a normal item</span></span>
1. <span data-ttu-id="a331a-124">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Neskladované zboží** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="a331a-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Nonstock Items**, and then choose the related link.</span></span>
2. <span data-ttu-id="a331a-125">Otevřete kartu pro neskladované zboží, které chcete převést na normální.</span><span class="sxs-lookup"><span data-stu-id="a331a-125">Open the card for a nonstock item that you want to convert to a normal item.</span></span>
3. <span data-ttu-id="a331a-126">V okně **Karta neskladovaného zboží** vyberte akci **Vytvořit zboží**.</span><span class="sxs-lookup"><span data-stu-id="a331a-126">In the **Nonstock Item Card** window, choose the **Create Item** action.</span></span>

<span data-ttu-id="a331a-127">Nová karta zboží předvyplněná informacemi ze šablon neskladovaného zboží a odpovídající šablona zboží je vytvořena.</span><span class="sxs-lookup"><span data-stu-id="a331a-127">A new item card prefilled with information from the nonstock item and a relevant item template is created.</span></span> <span data-ttu-id="a331a-128">Můžete vyplnit nebo upravit pole na nové kartě zboží podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="a331a-128">You can then fill or edit fields on the new item card as necessary.</span></span> <span data-ttu-id="a331a-129">Další informace naleznete v tématu [Návod: Registrace nového zboží](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="a331a-129">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>

## <a name="to-sell-a-nonstock-item-and-convert-it-to-a-normal-item"></a><span data-ttu-id="a331a-130">Prodej neskladovaného zboží a převod na normální zboží</span><span class="sxs-lookup"><span data-stu-id="a331a-130">To sell a nonstock item, and convert it to a normal item</span></span>
1. <span data-ttu-id="a331a-131">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní objednávky** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="a331a-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="a331a-132">Vyberte akci **Nový**.</span><span class="sxs-lookup"><span data-stu-id="a331a-132">Choose the **New** action.</span></span> <span data-ttu-id="a331a-133">Vyplňte pole na záložce s náhledem **Obecné** jako u každé prodejní objednávky.</span><span class="sxs-lookup"><span data-stu-id="a331a-133">Fill in the fields on the **General** FastTab as for any sales order.</span></span> <span data-ttu-id="a331a-134">Další informace naleznete v tématu [Návod: Prodávání produktů](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="a331a-134">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
3. <span data-ttu-id="a331a-135">Na novém prodejním řádku v poli **Typ**, vyberte **Zboží** ale nechte pole **Číslo** prázdné</span><span class="sxs-lookup"><span data-stu-id="a331a-135">On a new sales line, in the **Type** field, select **Item**, but leave the **No.**</span></span> <span data-ttu-id="a331a-136">.</span><span class="sxs-lookup"><span data-stu-id="a331a-136">field empty.</span></span>
4. <span data-ttu-id="a331a-137">Vyberte akci **Řádek** a pak zvolte akci **Vybrat neskladované zboží**.</span><span class="sxs-lookup"><span data-stu-id="a331a-137">Choose the **Line** action, and then choose the **Select Nonstock Items** action.</span></span>

    <span data-ttu-id="a331a-138">Neskladované zboží je převedeno na normální zboží.</span><span class="sxs-lookup"><span data-stu-id="a331a-138">The nonstock item is converted to a normal item.</span></span> <span data-ttu-id="a331a-139">Nová karta zboží předvyplněná informacemi ze šablon neskladovaného zboží a odpovídající šablona zboží je vytvořena.</span><span class="sxs-lookup"><span data-stu-id="a331a-139">A new item card prefilled with information from the nonstock item and a relevant item template is created.</span></span>
5. <span data-ttu-id="a331a-140">V okně **Neskladované zboží** vyberte neskladované zboží, které chcete prodat a potom vyberte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="a331a-140">In the **Nonstock Items** window, select the nonstock item that you want to sell, and then choose the **OK** button.</span></span>
6. <span data-ttu-id="a331a-141">Po dokončení prodejní objednávky zvolte akci **Účtovat**.</span><span class="sxs-lookup"><span data-stu-id="a331a-141">When the sales order is complete, choose the **Post** action.</span></span>

<span data-ttu-id="a331a-142">Můžete vyplnit nebo upravit pole na nové kartě zboží podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="a331a-142">You can then fill or edit fields on the new item card as necessary.</span></span> <span data-ttu-id="a331a-143">Další informace naleznete v tématu [Návod: Registrace nového zboží](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="a331a-143">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>

> [!NOTE]  
>   <span data-ttu-id="a331a-144">Záznam křížového odkazu zboží je automaticky vytvořen pro dodavatele zboží mezi číslem zboží dodavatele a novým číslem zboží.</span><span class="sxs-lookup"><span data-stu-id="a331a-144">An Item cross reference record is automatically created for the vendor of the item between the vendor's item number and your new item number.</span></span>

## <a name="see-also"></a><span data-ttu-id="a331a-145">Viz také</span><span class="sxs-lookup"><span data-stu-id="a331a-145">See Also</span></span>
[<span data-ttu-id="a331a-146">Návod: Registrace nového zboží</span><span class="sxs-lookup"><span data-stu-id="a331a-146">How to: Register New Items</span></span>](inventory-how-register-new-items.md)  
<span data-ttu-id="a331a-147">[Návod: Vytvořit speciální objednávku](sales-how-to-create-special-orders.md)|</span><span class="sxs-lookup"><span data-stu-id="a331a-147">[How to: Create Special Orders](sales-how-to-create-special-orders.md)|</span></span>  
[<span data-ttu-id="a331a-148">Sklady</span><span class="sxs-lookup"><span data-stu-id="a331a-148">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="a331a-149">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a331a-149">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

