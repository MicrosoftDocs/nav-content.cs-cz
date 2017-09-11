---
title: "Návod: Zaznamenávání prodejních cen a slev"
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
ms.openlocfilehash: 80a0ac1edc994f44795f7f907a647b269578bc47
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a><span data-ttu-id="6fffa-102">Návod: Zaznamenávání prodejních cen a slev</span><span class="sxs-lookup"><span data-stu-id="6fffa-102">How to: Record Sales Prices and Discounts</span></span>
<span data-ttu-id="6fffa-103">Různé cenové a slevové dohody, které při prodeji platí pro různé zákazníky musí být definovány tak, aby dohodnutá pravidla a hodnoty byly použity na prodejních dokumentech, které vytvoříte pro zákazníky.</span><span class="sxs-lookup"><span data-stu-id="6fffa-103">The different price and discount agreements that apply when selling to different customers must be defined so that the agreed rules and values are applied to sales documents that you create for the customers.</span></span>

<span data-ttu-id="6fffa-104">Pokud jde o ceny, můžete mít speciální ceny na řádcích, jestliže existuje určitá kombinace zákazníka, zboží, minimálního množství, měrné jednotky a počátečního či koncového data.</span><span class="sxs-lookup"><span data-stu-id="6fffa-104">Concerning prices, you can have a special sales price inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span>

<span data-ttu-id="6fffa-105">Pokud jde o slevy, můžete nastavit a použít tyto dva druhy slev:</span><span class="sxs-lookup"><span data-stu-id="6fffa-105">Concerning discounts, you can set up and use two types of sales discounts:</span></span>

|<span data-ttu-id="6fffa-106">Typ slevy</span><span class="sxs-lookup"><span data-stu-id="6fffa-106">Discount Type</span></span> |<span data-ttu-id="6fffa-107">Popis</span><span class="sxs-lookup"><span data-stu-id="6fffa-107">Description</span></span> |
|--------------|------------|
|<span data-ttu-id="6fffa-108">**Prodejní řádková sleva**</span><span class="sxs-lookup"><span data-stu-id="6fffa-108">**Sales Line Discount**</span></span>|<span data-ttu-id="6fffa-109">Částka slevy, která je vložena na prodejních řádcích v závislosti na kombinaci zákazníka, zboží, minimálního množství, měrné jednotky a počátečního či koncového data.</span><span class="sxs-lookup"><span data-stu-id="6fffa-109">An amount discount that is inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span> <span data-ttu-id="6fffa-110">Stejně to funguje pro prodejní ceny.</span><span class="sxs-lookup"><span data-stu-id="6fffa-110">This works in the same way as for sales prices.</span></span>|
|<span data-ttu-id="6fffa-111">**Sleva z faktury**</span><span class="sxs-lookup"><span data-stu-id="6fffa-111">**Invoice Discount**</span></span>|<span data-ttu-id="6fffa-112">Procentuální sleva je odečtena od celkové hodnoty dokumentu, pokud hodnota všech řádků na prodejním dokumentu přesahuje určité minimum.</span><span class="sxs-lookup"><span data-stu-id="6fffa-112">A percentage discount that is subtracted from the document total if the value amount of all lines on a sales document exceeds a certain minimum.</span></span>|

<span data-ttu-id="6fffa-113">Vzhledem k tomu, že prodejní ceny a řádkové slevy jsou založeny na kombinaci položky a zákazníka, můžete tuto konfiguraci provést také z karty zboží (položky), kde můžete nastavit pravidla a hodnoty.</span><span class="sxs-lookup"><span data-stu-id="6fffa-113">Because sales prices and sales line discounts are based on a combination of item and customer, you can also perform this configuration from the item card of the item where the rules and values apply.</span></span>

## <a name="to-set-up-a-sales-price-for-a-customer"></a><span data-ttu-id="6fffa-114">Nastavení prodejních cen zákazníka</span><span class="sxs-lookup"><span data-stu-id="6fffa-114">To set up a sales price for a customer</span></span>
1. <span data-ttu-id="6fffa-115">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zákazníci** a poté vyberte příslušný odkaz.</span><span class="sxs-lookup"><span data-stu-id="6fffa-115">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="6fffa-116">Otevřete příslušnou kartu zákazníka a zvolte tlačítko **Ceny**.</span><span class="sxs-lookup"><span data-stu-id="6fffa-116">Open the relevant customer card, and then choose the **Prices** action.</span></span>

    <span data-ttu-id="6fffa-117">Políčko **Typ prodeje** je předvyplněno **Zákazníkem** a pole **Kód prodeje** je předvyplněno číslem zákazníka.</span><span class="sxs-lookup"><span data-stu-id="6fffa-117">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3. <span data-ttu-id="6fffa-118">Vyplňte políčka na řádku, jak je potřeba.</span><span class="sxs-lookup"><span data-stu-id="6fffa-118">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="6fffa-119">Vyberte pole a přečtěte si krátký popis pole nebo zvolte odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="6fffa-119">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="6fffa-120">Vyplňte řádek pro každou kombinaci, která poskytne speciální cenu pro zákazníka.</span><span class="sxs-lookup"><span data-stu-id="6fffa-120">Fill a line for each combination that will grant a special sales price to the customer.</span></span>

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a><span data-ttu-id="6fffa-121">Nastavení Prodejních řádkových sleva zákazníka</span><span class="sxs-lookup"><span data-stu-id="6fffa-121">To set up a sales line discount for a customer</span></span>
1. <span data-ttu-id="6fffa-122">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zákazníci** a poté vyberte příslušný odkaz.</span><span class="sxs-lookup"><span data-stu-id="6fffa-122">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="6fffa-123">Otevřete příslušnou kartu zákazníka a zvolte tlačítko **Řádkové slevy**.</span><span class="sxs-lookup"><span data-stu-id="6fffa-123">Open the relevant customer card, and then choose the **Line Discounts** action.</span></span>

    <span data-ttu-id="6fffa-124">Políčko **Typ prodeje** je předvyplněno **Zákazníkem** a pole **Kód prodeje** je předvyplněno číslem zákazníka.</span><span class="sxs-lookup"><span data-stu-id="6fffa-124">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3.  <span data-ttu-id="6fffa-125">Vyplňte políčka na řádku, jak je potřeba.</span><span class="sxs-lookup"><span data-stu-id="6fffa-125">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="6fffa-126">Vyberte pole a přečtěte si krátký popis pole nebo zvolte odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="6fffa-126">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="6fffa-127">Vyplňtě řádek pro každou kombinaci, která poskytne prodejní řádkovou slevu pro zákazníka.</span><span class="sxs-lookup"><span data-stu-id="6fffa-127">Fill a line for each combination that will grant a sales line discount to the customer.</span></span>

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a><span data-ttu-id="6fffa-128">Nastavení slevy z faktury pro zákazníka</span><span class="sxs-lookup"><span data-stu-id="6fffa-128">To set up an invoice discount for a customer</span></span>
<span data-ttu-id="6fffa-129">Když se rozhodnete, kteří zákazníci mají nárok na fakturační slevu, tak vložte kód fakturační slevy na kartu zákazníka a nastavte podmínky pro daný kód. </span><span class="sxs-lookup"><span data-stu-id="6fffa-129">When you have decided which customers are eligible for invoice discounts, enter the invoice discount code on the customer cards and set up the terms for each code.</span></span>

1. <span data-ttu-id="6fffa-130">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zákazníci** a poté vyberte příslušný odkaz.</span><span class="sxs-lookup"><span data-stu-id="6fffa-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="6fffa-131">Otevřete kartu zákazníka, pro zákazníka, který bude mít nárok na fakturační slevy.</span><span class="sxs-lookup"><span data-stu-id="6fffa-131">Open the customer card for a customer that will be eligible for invoice discounts.</span></span>
3. <span data-ttu-id="6fffa-132">V políčku **Kód fakturační slevy ** vyberte kód příslušné podmínky fakturační slevy k vypočítání fakturačních slev pro daného zákazníka.</span><span class="sxs-lookup"><span data-stu-id="6fffa-132">In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the customer.</span></span>

    <span data-ttu-id="6fffa-133">**Poznámka**: Kódy fakturačních slev jsou zastoupeny na existujících kartách zákazníků.</span><span class="sxs-lookup"><span data-stu-id="6fffa-133">**Note**: Invoice discount codes are represented by existing customer cards.</span></span> <span data-ttu-id="6fffa-134">To vám umožní rychle přiřadit podmínky fakturačních slev zákazníkovi výběrem jména jiného zákazníka, který má stejné podmínky.</span><span class="sxs-lookup"><span data-stu-id="6fffa-134">This enables you to quickly assign invoice discount terms to customers by picking the name of another customer who will have the same terms.</span></span>

    <span data-ttu-id="6fffa-135">Pokračujte v nastavení nových podmínek fakturačních slev.</span><span class="sxs-lookup"><span data-stu-id="6fffa-135">Proceed to set up new the sales invoice discount terms.</span></span>
4. <span data-ttu-id="6fffa-136">V okně **Karta zákazníka** zvolte **Fakturační slevy**.</span><span class="sxs-lookup"><span data-stu-id="6fffa-136">In the **Customer Card** window, choose the **Invoice Discounts** action.</span></span> <span data-ttu-id="6fffa-137">Otevře se okno ** Fakturační slevy zákazníka**.</span><span class="sxs-lookup"><span data-stu-id="6fffa-137">The **Cust. Invoice Discounts** window opens.</span></span>
5. <span data-ttu-id="6fffa-138">V poli **Kód měny** vložte kód pro měnu, kterou chcete použít do podmínek fakturačních slev.</span><span class="sxs-lookup"><span data-stu-id="6fffa-138">In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to.</span></span> <span data-ttu-id="6fffa-139">Zanechte prázdné pole k nastavení podmínek fakturačních slev v CZK.</span><span class="sxs-lookup"><span data-stu-id="6fffa-139">Leave the field blank to set up invoice discount terms in USD.</span></span>
6. <span data-ttu-id="6fffa-140">V poli **Minimální částka** vložte minimální částku, která musí být na faktuře, aby byla sleva uplatněna.</span><span class="sxs-lookup"><span data-stu-id="6fffa-140">In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.</span></span>
7. <span data-ttu-id="6fffa-141">V poli **Sleva %** vložte procentuální fakturační slevu celkové částky.</span><span class="sxs-lookup"><span data-stu-id="6fffa-141">In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.</span></span>
8. <span data-ttu-id="6fffa-142">Opakujte kroky 5 až 7 pro každou měnu, pokud zákazník obdrží různé faktury.</span><span class="sxs-lookup"><span data-stu-id="6fffa-142">Repeat steps 5 through 7 for each currency that the customer will receive a different invoice discount for.</span></span>

<span data-ttu-id="6fffa-143">Fakturační sleva je nyní nastavena a přiřazena dotyčnému zákazníkovi. </span><span class="sxs-lookup"><span data-stu-id="6fffa-143">The invoice discount is now set up and assigned to the customer in question.</span></span> <span data-ttu-id="6fffa-144">Když si vyberete kód zákazníka v políčku **Kód fakturační slevy ** na ostatních kartách zákazníků, bude přiřazena těmto zákazníkům stejná fakturační sleva.</span><span class="sxs-lookup"><span data-stu-id="6fffa-144">When you select the customer code in the **Invoice Disc. Code** field on other customer cards, the same invoice discount is assigned to those customers.</span></span>

## <a name="see-also"></a><span data-ttu-id="6fffa-145">Viz také</span><span class="sxs-lookup"><span data-stu-id="6fffa-145">See Also</span></span>  
[<span data-ttu-id="6fffa-146">Nastavení prodeje</span><span class="sxs-lookup"><span data-stu-id="6fffa-146">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="6fffa-147">Správa prodeje</span><span class="sxs-lookup"><span data-stu-id="6fffa-147">Manage Sales</span></span>](sales-manage-sales.md)

