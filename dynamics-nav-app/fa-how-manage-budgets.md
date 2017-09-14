---
title: "Návod: Správa rozpočtů pro dlouhodobý majetek"
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
ms.openlocfilehash: 47b5e0abcae4fab92da5dd9c1bda350a37ec0358
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-budgets-for-fixed-assets"></a><span data-ttu-id="f85fe-102">Návod: Správa rozpočtů pro dlouhodobý majetek</span><span class="sxs-lookup"><span data-stu-id="f85fe-102">How to: Manage Budgets for Fixed Assets</span></span>
<span data-ttu-id="f85fe-103">Můžete nastavit rozpočty pro dlouhodobý majetek.</span><span class="sxs-lookup"><span data-stu-id="f85fe-103">You can set up budgeted fixed assets.</span></span> <span data-ttu-id="f85fe-104">To umožňuje zahrnout veškeré očekávané pořízení a prodeje v sestavách.</span><span class="sxs-lookup"><span data-stu-id="f85fe-104">This makes it possible to include any anticipated acquisitions and sales in reports.</span></span>  

 <span data-ttu-id="f85fe-105">Chcete-li připravit plánovaný výkaz zisku a ztráty, rozpočtovou rozvahu a hotovostní rozpočet, potřebujete informace o budoucích investicích, prodeji a odpisování DM.</span><span class="sxs-lookup"><span data-stu-id="f85fe-105">To prepare your budgeted income statement, budgeted balance sheet and cash budget, you need information about future investments, disposals and depreciation of fixed assets.</span></span> <span data-ttu-id="f85fe-106">Tyto informace můžete získat ze zprávy **Dlouhodobý majetek - očekávaná hodnota**.</span><span class="sxs-lookup"><span data-stu-id="f85fe-106">You can get this information from the **Fixed Asset - Projected Value** report.</span></span> <span data-ttu-id="f85fe-107">Než vytisknete tuto sestavu, musíte připravit rozpočet.</span><span class="sxs-lookup"><span data-stu-id="f85fe-107">Before you print this report, you must prepare the budget.</span></span>  

## <a name="to-budget-the-acquisition-cost-of-a-fixed-asset"></a><span data-ttu-id="f85fe-108">Rozpočet na pořizovací cenu DM</span><span class="sxs-lookup"><span data-stu-id="f85fe-108">To budget the acquisition cost of a fixed asset</span></span>
<span data-ttu-id="f85fe-109">Chcete-li připravit rozpočet, musíte v budoucnu nastavit karty DM, který chcete koupit.</span><span class="sxs-lookup"><span data-stu-id="f85fe-109">To prepare a budget, you have to set up fixed asset cards for fixed assets that you intend to buy in the future.</span></span> <span data-ttu-id="f85fe-110">Rozpočet DM je stanoven jako běžný dlouhodobý majetek, ale musí být nastaven tak, aby se nezaúčtoval do hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="f85fe-110">The budget fixed assets are set up as ordinary fixed assets, but it must be set up to not post to the general ledger.</span></span>

<span data-ttu-id="f85fe-111">Když uveřejníte pořizovací cenu, zadejte číslo rozpočtu DM v poli **Číslo rozpočtu DM**</span><span class="sxs-lookup"><span data-stu-id="f85fe-111">When you post the acquisition cost, you enter the number of the budgeted fixed asset in the **Budgeted FA No.**</span></span> <span data-ttu-id="f85fe-112">.</span><span class="sxs-lookup"><span data-stu-id="f85fe-112">field.</span></span> <span data-ttu-id="f85fe-113">Zaúčtuje se pořizovací cena s opačným znaménkem pro rozpočet majetku.</span><span class="sxs-lookup"><span data-stu-id="f85fe-113">This will post an acquisition cost with an opposite sign for the budgeted asset.</span></span> <span data-ttu-id="f85fe-114">To znamená, že celková pořizovací cena rozpočtu majetku je rozdílem mezi rozpočtovanými a skutečnými pořizovacími náklady.</span><span class="sxs-lookup"><span data-stu-id="f85fe-114">This means that the total acquisition cost on the budgeted asset is the difference between the budgeted and the actual acquisition cost.</span></span>

1. <span data-ttu-id="f85fe-115">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="f85fe-115">In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.</span></span>
2. <span data-ttu-id="f85fe-116">Zvolte akci **Nový** pro vytvoření nové karty DM pro rozpočet DM.</span><span class="sxs-lookup"><span data-stu-id="f85fe-116">Choose the **New** action to create a new fixed asset card for the budgeted fixed asset.</span></span>
3. <span data-ttu-id="f85fe-117">Zaškrtněte políčko **Rozpočtový majetek**, abyste zabránili zaúčtování do hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="f85fe-117">Select the **Budgeted Asset** check box to prevent posting to the general ledger.</span></span>
4. <span data-ttu-id="f85fe-118">Vyplňte zbývající pole, přiřaďte odpisovou knihu a poté zaúčtujte první pořizovací cenu s rozpočtem DM zadaným v poli **Číslo rozpočtu DM**</span><span class="sxs-lookup"><span data-stu-id="f85fe-118">Fill in the remaining fields, assign a depreciation book, and then post the first acquisition cost with the budgeted fixed asset entered in the **Budgeted FA No.**</span></span> <span data-ttu-id="f85fe-119">na řádku deníku.</span><span class="sxs-lookup"><span data-stu-id="f85fe-119">field on the journal line.</span></span> <span data-ttu-id="f85fe-120">Další informace naleznete v tématu [Návod: Získání DM](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="f85fe-120">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>

## <a name="to-budget-the-disposal-of-a-fixed-asset"></a><span data-ttu-id="f85fe-121">Rozpočet na vyřazení DM</span><span class="sxs-lookup"><span data-stu-id="f85fe-121">To budget the disposal of a fixed asset</span></span>
<span data-ttu-id="f85fe-122">Pokud máte v úmyslu prodat majetek během rozpočtového období, můžete zadat informace o prodejní ceně a dni prodeje.</span><span class="sxs-lookup"><span data-stu-id="f85fe-122">If you plan to sell assets within the budget period, you can enter information about sales price and sales date.</span></span>

1. <span data-ttu-id="f85fe-123">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="f85fe-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.</span></span>
2. <span data-ttu-id="f85fe-124">Vyberte dlouhodobý majetek, který chcete vyřadit a pak vyberte akci **Knihy odpisů**.</span><span class="sxs-lookup"><span data-stu-id="f85fe-124">Select the fixed asset to be disposed of, and then choose the **Depreciation Books** action.</span></span>
3. <span data-ttu-id="f85fe-125">V okně **Knihy odpisů DM** vyplňte pole **Plánované datum vyřazení** a **Plánovaný výsledek vyřazení**.</span><span class="sxs-lookup"><span data-stu-id="f85fe-125">In the **FA Depreciation Books** window, fill in the **Projected Disposal Date** and **Projected Proceeds on Disposal** fields.</span></span> <span data-ttu-id="f85fe-126">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="f85fe-126">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-view-projected-disposal-values"></a><span data-ttu-id="f85fe-127">Zobrazení očekávané hodnoty vyřazení</span><span class="sxs-lookup"><span data-stu-id="f85fe-127">To view projected disposal values</span></span>
<span data-ttu-id="f85fe-128">Chcete-li zobrazit hodnoty předpokládaných vyřazení a vypočítat zisk a ztráty, můžete použít sestavu **Očekávaná hodnota DM**.</span><span class="sxs-lookup"><span data-stu-id="f85fe-128">To see the projected disposal values and have the gain and loss calculated, you can use the **FA Projected Value** report.</span></span>

1. <span data-ttu-id="f85fe-129">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Očekávaná hodnota DM** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="f85fe-129">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Projected Value**, and then choose the related link.</span></span>
2. <span data-ttu-id="f85fe-130">Vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="f85fe-130">Fill in the fields as necessary.</span></span>
3. <span data-ttu-id="f85fe-131">Zvolte tlačítko **Tisk** nebo **Náhled**.</span><span class="sxs-lookup"><span data-stu-id="f85fe-131">Choose the **Print** or **Preview** button.</span></span>

## <a name="to-budget-depreciation"></a><span data-ttu-id="f85fe-132">Odpis rozpočtu</span><span class="sxs-lookup"><span data-stu-id="f85fe-132">To budget depreciation</span></span>
<span data-ttu-id="f85fe-133">Pro výpočet budoucího odpisu můžete použít sestavu **Dlouhodobý majetek - očekávaná hodnota**.</span><span class="sxs-lookup"><span data-stu-id="f85fe-133">You can use the **Fixed Asset - Projected Value** report to calculate future depreciation.</span></span> <span data-ttu-id="f85fe-134">Zpráva uvádí účetní hodnotu a akumulované odpisy na začátku vybraného období, změny v daném období a účetní hodnotu a akumulované odpisy na konci vybraného období.</span><span class="sxs-lookup"><span data-stu-id="f85fe-134">The report shows the book value and accumulated depreciation at the start of the selected period, changes during the period, and the book value and accumulated depreciation at the end of the selected period.</span></span>

1. <span data-ttu-id="f85fe-135">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Očekávaná hodnota DM** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="f85fe-135">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Projected Value**, and then choose the related link.</span></span>
2. <span data-ttu-id="f85fe-136">Vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="f85fe-136">Fill in the fields as necessary.</span></span>
3. <span data-ttu-id="f85fe-137">Chcete-li zobrazit souhrnné hodnoty pro všechen majetek, zrušte zaškrtnutí políčka **Tisk dle DM**.</span><span class="sxs-lookup"><span data-stu-id="f85fe-137">To see total values for all assets, clear the **Print per Fixed Asset** check box.</span></span>
4. <span data-ttu-id="f85fe-138">Ponechte záložku s náhledem **Dlouhodobý majetek** prázdnou, aby byl zahrnut všechen majetek.</span><span class="sxs-lookup"><span data-stu-id="f85fe-138">Leave the **Fixed Asset** FastTab blank to have all assets included.</span></span> <span data-ttu-id="f85fe-139">Do pole **Rozpočtový majetek** zadejte **Ne**, chcete-li vyloučit rozpočtovaný majetek nebo **Ano**, abyste viděli pouze rozpočtovaný majetek.</span><span class="sxs-lookup"><span data-stu-id="f85fe-139">In the **Budgeted Asset** field, enter **No** to exclude budgeted assets or **Yes** to see budgeted assets only.</span></span>
5. <span data-ttu-id="f85fe-140">Zvolte tlačítko **Tisk** nebo **Náhled**.</span><span class="sxs-lookup"><span data-stu-id="f85fe-140">Choose the **Print** or **Preview** button.</span></span>

## <a name="see-also"></a><span data-ttu-id="f85fe-141">Viz také</span><span class="sxs-lookup"><span data-stu-id="f85fe-141">See Also</span></span>
[<span data-ttu-id="f85fe-142">Správa DM</span><span class="sxs-lookup"><span data-stu-id="f85fe-142">Manage Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="f85fe-143">Nastavení DM</span><span class="sxs-lookup"><span data-stu-id="f85fe-143">Set Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="f85fe-144">Finance</span><span class="sxs-lookup"><span data-stu-id="f85fe-144">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="f85fe-145">[Vítejte v [!INCLUDE[navnow](includes/navnow_md.md)]](across-get-started.md)</span><span class="sxs-lookup"><span data-stu-id="f85fe-145">[Welcome to Dynamics NAV](across-get-started.md)</span></span>

