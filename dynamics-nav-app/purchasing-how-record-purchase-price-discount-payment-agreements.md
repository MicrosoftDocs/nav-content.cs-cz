---
title: "Návod: Záznam nákupních cen a slev"
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
ms.openlocfilehash: af5ba3a17412ba4c123c4d3cb337b8d5df36cace
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

#<a name="how-to-record-purchase-prices-and-discounts"></a><span data-ttu-id="7238e-102">Návod: Záznam nákupních cen a slev</span><span class="sxs-lookup"><span data-stu-id="7238e-102">How to: Record Purchase Prices and Discounts</span></span>
<span data-ttu-id="7238e-103">Různé cenové a slevové dohody, které použijete při nákupu od různých dodavatelů musí být definovány tak, aby se dohodnuté pravidla a hodnoty použily na nákupní doklad, které vytvoříte pro dodavatele.</span><span class="sxs-lookup"><span data-stu-id="7238e-103">The different price and discount agreements that apply when you buy from different vendors must be defined so that the agreed rules and values are applied to purchase documents that you create for the vendors.</span></span>

<span data-ttu-id="7238e-104">Pokud jde o ceny, můžete mít speciální nákupní ceny zadané na nákupním řádku, pokud existuje určitá kombinace dodavatele, zboží, minimálního množství, měrné jednotky nebo počátečního/koncového data.</span><span class="sxs-lookup"><span data-stu-id="7238e-104">Concerning prices, you can have a special purchase price inserted on purchase lines if a certain combination of vendor, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span>

<span data-ttu-id="7238e-105">Pokud jde o slevy, můžete nastavit a použít dva typy nákupních slev:</span><span class="sxs-lookup"><span data-stu-id="7238e-105">Concerning discounts, you can set up and use two types of purchase discounts:</span></span>

|<span data-ttu-id="7238e-106">Typ slevy</span><span class="sxs-lookup"><span data-stu-id="7238e-106">Discount Type</span></span> |<span data-ttu-id="7238e-107">Popis</span><span class="sxs-lookup"><span data-stu-id="7238e-107">Description</span></span> |
|--------------|------------|
|<span data-ttu-id="7238e-108">**Sleva na nákupním řádku**</span><span class="sxs-lookup"><span data-stu-id="7238e-108">**Purchase Line Discount**</span></span>|<span data-ttu-id="7238e-109">Zvýhodněná částka, která je vložena na nákupním řádku, pokud existuje určitá kombinace dodavatele, zboží, minimálního množství, měrné jednotky nebo počátečního/koncového data.</span><span class="sxs-lookup"><span data-stu-id="7238e-109">An amount discount that is inserted on purchase lines if a certain combination of vendor, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span> <span data-ttu-id="7238e-110">Toto funguje stejným způsobem jako u nákupních cen.</span><span class="sxs-lookup"><span data-stu-id="7238e-110">This works in the same way as for purchase prices.</span></span>|
|<span data-ttu-id="7238e-111">**Fakturační slevy**</span><span class="sxs-lookup"><span data-stu-id="7238e-111">**Invoice Discount**</span></span>|<span data-ttu-id="7238e-112">Procentní sleva, která se odečte od celkové hodnoty dokladu, pokud hodnota všech řádků na nákupním dokladu převyšuje určité minimum.</span><span class="sxs-lookup"><span data-stu-id="7238e-112">A percentage discount that is subtracted from the document total if the value amount of all lines on a purchase document exceeds a certain minimum.</span></span>|

<span data-ttu-id="7238e-113">Vzhledem k tomu, že slevy na nákupním řádku a nákupní ceny jsou založeny na kombinaci zboží a dodavatele, můžete také tuto konfiguraci zadat z karty zboží, kde jsou definována pravidla a hodnoty.</span><span class="sxs-lookup"><span data-stu-id="7238e-113">Because purchase line discounts and purchase prices are based on a combination of item and vendor, you can also enter this configuration from the item card, where the rules and values are defined.</span></span> <span data-ttu-id="7238e-114">Další informace naleznete v tématu [Návod: Registrace nového produktu](inventory-how-register-new-products.md).</span><span class="sxs-lookup"><span data-stu-id="7238e-114">For more information, see [How to: Register New Products](inventory-how-register-new-products.md).</span></span>

## <a name="to-set-up-a-special-purchase-price-for-a-vendor"></a><span data-ttu-id="7238e-115">Nastavení zvláštní nákupní ceny pro dodavatele</span><span class="sxs-lookup"><span data-stu-id="7238e-115">To set up a special purchase price for a vendor</span></span>
1. <span data-ttu-id="7238e-116">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="7238e-116">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="7238e-117">Otevřete příslušnou kartu dodavatele a pak zvolte akci **Cena**.</span><span class="sxs-lookup"><span data-stu-id="7238e-117">Open the relevant vendor card, and then choose the **Prices** action.</span></span>

    <span data-ttu-id="7238e-118">Pole **Typ nákupu** je předem vyplněno **Dodavatelem** a pole **Kód nákupu** je předvyplněno číslem dodavatele.</span><span class="sxs-lookup"><span data-stu-id="7238e-118">The **Purchase Type** field is prefilled with **Vendor**, and the **Purchase Code** field is prefilled with the vendor number.</span></span>
3. <span data-ttu-id="7238e-119">Vyplňte pole na řádku podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="7238e-119">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="7238e-120">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="7238e-120">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="7238e-121">Vyplňte řádek pro každou kombinaci, pro kterou vám prodejce uděluje slevu na nákupním řádku.</span><span class="sxs-lookup"><span data-stu-id="7238e-121">Fill a line for each combination for which the vendor grants you a purchase line discount.</span></span>

## <a name="to-set-up-a-line-discount-for-a-vendor"></a><span data-ttu-id="7238e-122">Nastavení slevy na řádku pro dodavatele</span><span class="sxs-lookup"><span data-stu-id="7238e-122">To set up a line discount for a vendor</span></span>
1. <span data-ttu-id="7238e-123">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="7238e-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="7238e-124">Otevřete příslušnou kartu dodavatele a pak zvolte akci **Řádkové slevy**.</span><span class="sxs-lookup"><span data-stu-id="7238e-124">Open the relevant vendor card, and then choose the **Line Discounts** action.</span></span>

    <span data-ttu-id="7238e-125">Pole **Typ nákupu** je předem vyplněno **Dodavatelem** a pole **Kód nákupu** je předvyplněno číslem dodavatele.</span><span class="sxs-lookup"><span data-stu-id="7238e-125">The **Purchase Type** field is prefilled with **Vendor**, and the **Purchase Code** field is prefilled with the vendor number.</span></span>
3. <span data-ttu-id="7238e-126">Vyplňte pole na řádku podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="7238e-126">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="7238e-127">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="7238e-127">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="7238e-128">Vyplňte řádek pro každou kombinaci, pro kterou vám prodejce uděluje slevu na nákupním řádku.</span><span class="sxs-lookup"><span data-stu-id="7238e-128">Fill a line for each combination for which the vendor grants you a purchase line discount.</span></span>

## <a name="to-set-up-an-invoice-discount-for-a-vendor"></a><span data-ttu-id="7238e-129">Nastavení fakturační slevy pro dodavatele</span><span class="sxs-lookup"><span data-stu-id="7238e-129">To set up an invoice discount for a vendor</span></span>
<span data-ttu-id="7238e-130">Pokud vás váš dodavatel informuje o fakturačních slevách, které poskytne, zadejte na kartě dodavatele kód fakturační slevy a nastavte podmínky pro každý kód.</span><span class="sxs-lookup"><span data-stu-id="7238e-130">When your vendors have informed you which invoice discounts they grant, enter the invoice discount code on the vendor cards and set up the terms for each code.</span></span>

1. <span data-ttu-id="7238e-131">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="7238e-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="7238e-132">Otevřete kartu dodavatele, který bude mít nárok na fakturační slevu.</span><span class="sxs-lookup"><span data-stu-id="7238e-132">Open the vendor card for a vendor that will be eligible for invoice discounts.</span></span>
3. <span data-ttu-id="7238e-133">V poli **Kód fakturační Slevy** vyberte kód pro příslušné podmínky fakturační slevy pro výpočet slev na fakturu pro dodavatele.</span><span class="sxs-lookup"><span data-stu-id="7238e-133">In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the vendor.</span></span>

    <span data-ttu-id="7238e-134">**Poznámka**: Kódy fakturační slevy představují stávající karty dodavatele.</span><span class="sxs-lookup"><span data-stu-id="7238e-134">**Note**: Invoice discount codes are represented by existing vendor cards.</span></span> <span data-ttu-id="7238e-135">To vám umožní rychle přiřadit podmínky fakturační slevy výběrem jména dalších dodavatelů, kteří budou mít stejné podmínky.</span><span class="sxs-lookup"><span data-stu-id="7238e-135">This enables you to quickly assign invoice discount terms to vendors by picking the name of another vendors who will have the same terms.</span></span>

    <span data-ttu-id="7238e-136">Pokračujte v nastavení nových podmínek slevy na nákupní fakturu.</span><span class="sxs-lookup"><span data-stu-id="7238e-136">Proceed to set up new the purchase invoice discount terms.</span></span>
4. <span data-ttu-id="7238e-137">V okně **Karta dodavatele** vyberte akci **Fakturační slevy**.</span><span class="sxs-lookup"><span data-stu-id="7238e-137">In the **Vendor Card** window, choose the **Invoice Discounts** action.</span></span> <span data-ttu-id="7238e-138">Otevře se okno **Dod.fakturační slevy**.</span><span class="sxs-lookup"><span data-stu-id="7238e-138">The **Vend. Invoice Discounts** window opens.</span></span>
5. <span data-ttu-id="7238e-139">Do pole **Kód měny** zadejte kód pro měnu, na kterou se využijí podmínky fakturační slevy na řádku.</span><span class="sxs-lookup"><span data-stu-id="7238e-139">In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to.</span></span> <span data-ttu-id="7238e-140">Nechte pole prázdné pro nastavení podmínek fakturační slevy v USD.</span><span class="sxs-lookup"><span data-stu-id="7238e-140">Leave the field blank to set up invoice discount terms in USD.</span></span>
6. <span data-ttu-id="7238e-141">V poli **Minimální částka** zadejte minimální částku, kterou musí mít faktura pro slevu.</span><span class="sxs-lookup"><span data-stu-id="7238e-141">In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.</span></span>
7. <span data-ttu-id="7238e-142">V poli **Sleva %** zadejte fakturační slevu jako procento částky faktury.</span><span class="sxs-lookup"><span data-stu-id="7238e-142">In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.</span></span>
8. <span data-ttu-id="7238e-143">Opakujte kroky 5 až 7 pro každou měnu, na kterou dodavatel obdrží jinou fakturační slevu.</span><span class="sxs-lookup"><span data-stu-id="7238e-143">Repeat steps 5 through 7 for each currency that the vendor will receive a different invoice discount for.</span></span>

<span data-ttu-id="7238e-144">Fakturační sleva je nyní nastavena a přidělena danému dodavateli.</span><span class="sxs-lookup"><span data-stu-id="7238e-144">The invoice discount is now set up and assigned to the vendor in question.</span></span> <span data-ttu-id="7238e-145">Když vyberete kód dodavatele v poli **Kód fakturační Slevy** na ostatních kartách dodavatelů, stejná fakturační sleva je přidělena těmto dodavatelům.</span><span class="sxs-lookup"><span data-stu-id="7238e-145">When you select the vendor code in the **Invoice Disc. Code** field on other vendor cards, the same invoice discount is assigned to those vendor.</span></span>

## <a name="see-also"></a><span data-ttu-id="7238e-146">Viz také</span><span class="sxs-lookup"><span data-stu-id="7238e-146">See Also</span></span>  
[<span data-ttu-id="7238e-147">Nastavení nákupu</span><span class="sxs-lookup"><span data-stu-id="7238e-147">Set Up Purchasing</span></span>](purchasing-setup-purchasing.md)  
[<span data-ttu-id="7238e-148">Správa nákupu</span><span class="sxs-lookup"><span data-stu-id="7238e-148">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)

