---
title: "Návod: Registrovat nové produkty"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: df84a4d3e15035cd956c7612a12069844f5601d2
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-register-new-products"></a><span data-ttu-id="f6e97-102">Návod: Registrovat nové produkty</span><span class="sxs-lookup"><span data-stu-id="f6e97-102">How to: Register New Products</span></span>

<span data-ttu-id="f6e97-103">Výrobky jsou základem vašeho podnikání, zboží nebo služeb, se kterými obchodujete.</span><span class="sxs-lookup"><span data-stu-id="f6e97-103">Products are the basis of your business, the goods or services that you trade in.</span></span> <span data-ttu-id="f6e97-104">Každý produkt musí být registrován jako karta zboží.</span><span class="sxs-lookup"><span data-stu-id="f6e97-104">Each product must be registered as an item card.</span></span>

<span data-ttu-id="f6e97-105">**Poznámka**: V Dynamics NAV se produkt označuje výrazem "zboží".</span><span class="sxs-lookup"><span data-stu-id="f6e97-105">**Note**: In Dynamics NAV, a product is referred to using the term “item”.</span></span>

<span data-ttu-id="f6e97-106">Karty zboží obsahují informace, které jsou nutné k nákupu, skladování, prodeji, doručení a pro účet produktů.</span><span class="sxs-lookup"><span data-stu-id="f6e97-106">Item cards hold the information that is required to buy, store, sell, deliver, and account for products.</span></span>

<span data-ttu-id="f6e97-107">Karta zboží může být typu Zásoba nebo Služba, která určuje, zda je produkt fyzickou jednotkou nebo jednotkou času.</span><span class="sxs-lookup"><span data-stu-id="f6e97-107">The item card can be of type Inventory or Service to specify if the product is a physical unit or labor time unit.</span></span> <span data-ttu-id="f6e97-108">Kromě některých polí, které se vztahují k fyzickým aspektům položky, všechny políčka na kartě zboží fungují stejně pro skladové položky a služby.</span><span class="sxs-lookup"><span data-stu-id="f6e97-108">Apart from some fields that relate to the physical aspects of an item, all fields on an item card function in the same way for inventory items and services.</span></span> <span data-ttu-id="f6e97-109">Další informace o prodeji zboží naleznete v [Návod: Prodej produktů](sales-how-sell-products.md) nebo [Návod: Prodejní faktury](sales-how-invoice-sales.md).</span><span class="sxs-lookup"><span data-stu-id="f6e97-109">For more information about selling an item, see [How to: Sell Products](sales-how-sell-products.md) or [How to: Invoice Sales](sales-how-invoice-sales.md).</span></span>

<span data-ttu-id="f6e97-110">**Poznámka**: Pokud existují šablony zboží pro různé typy zboží, objeví se okno při vytváření nové karty zboží, odkud můžete vybrat vhodnou šablonu.</span><span class="sxs-lookup"><span data-stu-id="f6e97-110">**Note**: If item templates exist for different item types, then a window appears when you create a new item card from where you can select an appropriate template.</span></span> <span data-ttu-id="f6e97-111">Pokud existuje pouze jedna šablona zboží, pak nové karty zboží používají vždy tuto šablonu.</span><span class="sxs-lookup"><span data-stu-id="f6e97-111">If only one item template exists, then new item cards always use that template.</span></span>

## <a name="to-create-a-new-item-card"></a><span data-ttu-id="f6e97-112">K vytvoření nové karty zboží</span><span class="sxs-lookup"><span data-stu-id="f6e97-112">To create a new item card</span></span>
1. <span data-ttu-id="f6e97-113">Na domovské stránce vyberte akci **Zboží** pro otevření seznamu existujícího zboží.</span><span class="sxs-lookup"><span data-stu-id="f6e97-113">On the Home page, choose the **Items** action to open the list of existing items.</span></span>  
2. <span data-ttu-id="f6e97-114">V okně **Zboží** vyberte akci **Nový**.</span><span class="sxs-lookup"><span data-stu-id="f6e97-114">In the **Items** window, choose the **New** action.</span></span>

    <span data-ttu-id="f6e97-115">Pokud existuje pouze jedna šablona zboží, otevře se nová karta zboží s několika poli vyplněnými informacemi ze šablony.</span><span class="sxs-lookup"><span data-stu-id="f6e97-115">If only one item template exists, then a new item card opens with some fields filled with information from the template.</span></span>
3. <span data-ttu-id="f6e97-116">V okně **Vybrat šablonu pro nové zboží** vyberte šablonu, kterou chcete použít pro novou kartu zboží.</span><span class="sxs-lookup"><span data-stu-id="f6e97-116">In the **Select a template for a new item** window, choose the template that you want to use for the new item card.</span></span>
4. <span data-ttu-id="f6e97-117">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="f6e97-117">Choose the **OK** button.</span></span> <span data-ttu-id="f6e97-118">Otevře se nová karta zboží s některými poli vyplněnými informacemi ze šablony.</span><span class="sxs-lookup"><span data-stu-id="f6e97-118">A new item card opens with some fields filled with information from the template.</span></span>
5. <span data-ttu-id="f6e97-119">Postupujte podle potřeby tak, že vyplníte nebo změníte pole na kartě zboží.</span><span class="sxs-lookup"><span data-stu-id="f6e97-119">Proceed to fill or change fields on the item card as necessary.</span></span> <span data-ttu-id="f6e97-120">Vybrat pole k zobrazení krátkého popisu nebo odkazu pro více informací.</span><span class="sxs-lookup"><span data-stu-id="f6e97-120">Choose a field to read a short description of the field or link to more information.</span></span>

<span data-ttu-id="f6e97-121">Na záložce s náhledem **Prodejní ceny** můžete zobrazit zvláštní ceny nebo slevy, které udělujete za dané zboží, pokud jsou splněna určitá kritéria, jako je zákazník, minimální objednávkové množství nebo datum ukončení.</span><span class="sxs-lookup"><span data-stu-id="f6e97-121">On the **Sales Prices** FastTab, you can view special prices or discounts that you grant for the item if certain criteria are met, such as customer, minimum order quantity, or ending date.</span></span> <span data-ttu-id="f6e97-122">Každý řádek představuje speciální slevu nebo řádkovou slevu.</span><span class="sxs-lookup"><span data-stu-id="f6e97-122">Each row represents a special price or line discount.</span></span> <span data-ttu-id="f6e97-123">Každý sloupec představuje kritérium, které musí platit, aby se zaručila speciální cena, kterou zadáte do pole **Jednotková cena**, nebo řádkovou slevu, kterou zadáte do pole **Řádková sleva**</span><span class="sxs-lookup"><span data-stu-id="f6e97-123">Each column represents a criterion that must apply to warrant the special price that you enter in the **Unit Price** field, or the line discount that you enter in the **Line Discount %** field.</span></span> <span data-ttu-id="f6e97-124">Další informace naleznete v tématu: [Zaznamenání Prodejní ceny, slevy a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).</span><span class="sxs-lookup"><span data-stu-id="f6e97-124">For more information, see [Record Sales Price, Discount, and Payment Agreements](sales-how-record-sales-price-discount-payment-agreements.md).</span></span>

<span data-ttu-id="f6e97-125">Položka je nyní zaregistrována a karta zboží je připravena k použití v nákupních a prodejních dokladech.</span><span class="sxs-lookup"><span data-stu-id="f6e97-125">The item is now registered, and the item card is ready to be used on purchase and sales documents.</span></span>

<span data-ttu-id="f6e97-126">Chcete-li tuto kartu zboží použít jako šablonu při vytváření nových karet zboží, můžete ji uložit jako šablonu.</span><span class="sxs-lookup"><span data-stu-id="f6e97-126">If you want to use this item card as a template when you create new item cards, you can save it as a template.</span></span> <span data-ttu-id="f6e97-127">Pro více informací, sledujte následující sekci.</span><span class="sxs-lookup"><span data-stu-id="f6e97-127">For more information, see the following section.</span></span>

## <a name="to-save-the-item-card-as-a-template"></a><span data-ttu-id="f6e97-128">K uložení karty zboží jako šablony</span><span class="sxs-lookup"><span data-stu-id="f6e97-128">To save the item card as a template</span></span>
1. <span data-ttu-id="f6e97-129">V okně **Karta zboží**, vyberte akci **Uložit jako šablonu**.</span><span class="sxs-lookup"><span data-stu-id="f6e97-129">In the **Item Card** window, choose the **Save as Template** action.</span></span> <span data-ttu-id="f6e97-130">Okno **Šablona zboží** otevírá kartu zboží jako šablonu.</span><span class="sxs-lookup"><span data-stu-id="f6e97-130">The **Item Template** window opens showing the item card as a template.</span></span>
2. <span data-ttu-id="f6e97-131">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="f6e97-131">Fill in the fields as necessary.</span></span> <span data-ttu-id="f6e97-132">Vybrat pole k zobrazení krátkého popisu nebo odkazu pro více informací.</span><span class="sxs-lookup"><span data-stu-id="f6e97-132">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="f6e97-133">K opětovnému použití dimenzí v šablonách, zvolte tlačítko **Dimenze**.</span><span class="sxs-lookup"><span data-stu-id="f6e97-133">To reuse dimensions in templates, choose the **Dimensions** action.</span></span> <span data-ttu-id="f6e97-134">Okno **Šablony dimenzí** otevírá jakékoli kódy dimenzí, které jsou pro dané zboží nastaveny.</span><span class="sxs-lookup"><span data-stu-id="f6e97-134">The **Dimension Templates** window opens showing any dimension codes that are set up for the item.</span></span>
4. <span data-ttu-id="f6e97-135">Upravte nebo zadejte kódy dimenzí, které se budou vztahovat na nové karty zboží vytvořené pomocí šablony.</span><span class="sxs-lookup"><span data-stu-id="f6e97-135">Edit or enter dimension codes that will apply to new item cards created by using the template.</span></span>
5. <span data-ttu-id="f6e97-136">Po dokončení nové šablony zboží vyberte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="f6e97-136">When you have completed the new item template, choose the **OK** button.</span></span>

<span data-ttu-id="f6e97-137">Šablona zboží je přidána do seznamu šablon zboží, takže ji můžete použít k vytvoření nových karet zboží.</span><span class="sxs-lookup"><span data-stu-id="f6e97-137">The item template is added to the list of item templates, so that you can use it to create new item cards.</span></span>

## <a name="see-also"></a><span data-ttu-id="f6e97-138">Viz také</span><span class="sxs-lookup"><span data-stu-id="f6e97-138">See Also</span></span>
  [<span data-ttu-id="f6e97-139">Správa skladů</span><span class="sxs-lookup"><span data-stu-id="f6e97-139">Manage Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="f6e97-140">  [Správa nákupu](purchasing-manage-purchasing.md)</span><span class="sxs-lookup"><span data-stu-id="f6e97-140">  [Manage Purchasing](purchasing-manage-purchasing.md)</span></span>  
<span data-ttu-id="f6e97-141">  [Správa prodeje](sales-manage-sales.md)</span><span class="sxs-lookup"><span data-stu-id="f6e97-141">  [Manage Sales](sales-manage-sales.md)</span></span>

