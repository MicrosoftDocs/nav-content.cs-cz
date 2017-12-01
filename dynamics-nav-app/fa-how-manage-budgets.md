---
title: "Správa rozpočtů DM"
description: "Nastavte informace o budoucích investicích, prodejích a odpisování dlouhodobého majetku, abyste mohli připravit rozpočty a prognózy."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: forecast
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 18c4d5fff83f1d71c261a5d3a3e065554fbea228
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-manage-budgets-for-fixed-assets"></a><span data-ttu-id="c3ddc-103">Návod: Správa rozpočtů pro dlouhodobý majetek</span><span class="sxs-lookup"><span data-stu-id="c3ddc-103">How to: Manage Budgets for Fixed Assets</span></span>
<span data-ttu-id="c3ddc-104">Můžete nastavit rozpočty pro dlouhodobý majetek.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-104">You can set up budgeted fixed assets.</span></span> <span data-ttu-id="c3ddc-105">Můžete například zahrnout očekávané akvizice a prodeje do přehledů.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-105">For example, this lets you include anticipated acquisitions and sales in reports.</span></span>  

<span data-ttu-id="c3ddc-106">Chcete-li připravit plánovaný výkaz zisku a ztráty, rozpočtovou rozvahu a hotovostní rozpočet, potřebujete informace o budoucích investicích, prodeji a odpisování DM.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-106">To prepare your budgeted income statement, budgeted balance sheet, and cash budget, you need information about future investments, disposals and depreciation of fixed assets.</span></span> <span data-ttu-id="c3ddc-107">Tyto informace můžete získat ze zprávy **Dlouhodobý majetek - očekávaná hodnota**.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-107">You can get this information from the **Fixed Asset - Projected Value** report.</span></span> <span data-ttu-id="c3ddc-108">Než vytisknete tuto sestavu, musíte připravit rozpočet.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-108">Before you print this report, you must prepare the budget.</span></span>  

## <a name="to-budget-the-acquisition-cost-of-a-fixed-asset"></a><span data-ttu-id="c3ddc-109">Rozpočet na pořizovací cenu DM</span><span class="sxs-lookup"><span data-stu-id="c3ddc-109">To budget the acquisition cost of a fixed asset</span></span>
<span data-ttu-id="c3ddc-110">Chcete-li připravit rozpočet, musíte v budoucnu nastavit karty DM, který chcete koupit.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-110">To prepare a budget, you have to set up fixed asset cards for fixed assets that you intend to buy in the future.</span></span> <span data-ttu-id="c3ddc-111">Rozpočet DM je stanoven jako běžný dlouhodobý majetek, ale musí být nastaven tak, aby se nezaúčtoval do hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-111">The budget fixed assets are set up as ordinary fixed assets, but it must be set up to not post to the general ledger.</span></span>

<span data-ttu-id="c3ddc-112">Když uveřejníte pořizovací cenu, zadejte číslo rozpočtu DM v poli **Číslo rozpočtu DM**.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-112">When you post the acquisition cost, you enter the number of the budgeted fixed asset in the **Budgeted FA No.** field.</span></span> <span data-ttu-id="c3ddc-113">Zaúčtuje se pořizovací cena s opačným znaménkem pro rozpočet majetku.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-113">This will post an acquisition cost with an opposite sign for the budgeted asset.</span></span> <span data-ttu-id="c3ddc-114">To znamená, že celková pořizovací cena rozpočtu majetku je rozdílem mezi rozpočtovanými a skutečnými pořizovacími náklady.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-114">This means that the total acquisition cost on the budgeted asset is the difference between the budgeted and the actual acquisition cost.</span></span>

1. <span data-ttu-id="c3ddc-115">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-115">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Fixed Assets**, and then choose the related link.</span></span>
2. <span data-ttu-id="c3ddc-116">Zvolte akci **Nový** pro vytvoření nové karty DM pro rozpočet DM.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-116">Choose the **New** action to create a new fixed asset card for the budgeted fixed asset.</span></span>
3. <span data-ttu-id="c3ddc-117">Zaškrtněte políčko **Rozpočtový majetek**, abyste zabránili zaúčtování do hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-117">Select the **Budgeted Asset** check box to prevent posting to the general ledger.</span></span>
4. <span data-ttu-id="c3ddc-118">Vyplňte zbývající pole, přiřaďte odpisovou knihu a poté zaúčtujte první pořizovací cenu s rozpočtem DM zadaným v poli **Číslo rozpočtu DM** na řádku deníku.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-118">Fill in the remaining fields, assign a depreciation book, and then post the first acquisition cost with the budgeted fixed asset entered in the **Budgeted FA No.** field on the journal line.</span></span> <span data-ttu-id="c3ddc-119">Další informace naleznete v tématu [Návod: Pořízení DM](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="c3ddc-119">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>

## <a name="to-budget-the-disposal-of-a-fixed-asset"></a><span data-ttu-id="c3ddc-120">Rozpočet na vyřazení DM</span><span class="sxs-lookup"><span data-stu-id="c3ddc-120">To budget the disposal of a fixed asset</span></span>
<span data-ttu-id="c3ddc-121">Pokud máte v úmyslu prodat majetek během rozpočtového období, můžete zadat informace o prodejní ceně a dni prodeje.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-121">If you plan to sell assets within the budget period, you can enter information about sales price and sales date.</span></span>

1. <span data-ttu-id="c3ddc-122">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-122">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Fixed Assets**, and then choose the related link.</span></span>
2. <span data-ttu-id="c3ddc-123">Vyberte dlouhodobý majetek, který chcete vyřadit a pak vyberte akci **Knihy odpisů**.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-123">Select the fixed asset to be disposed of, and then choose the **Depreciation Books** action.</span></span>
3. <span data-ttu-id="c3ddc-124">V okně **Knihy odpisů DM** vyplňte pole **Plánované datum vyřazení** a **Plánovaný výsledek vyřazení**.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-124">In the **FA Depreciation Books** window, fill in the **Projected Disposal Date** and **Projected Proceeds on Disposal** fields.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-view-projected-disposal-values"></a><span data-ttu-id="c3ddc-125">Zobrazení očekávané hodnoty vyřazení</span><span class="sxs-lookup"><span data-stu-id="c3ddc-125">To view projected disposal values</span></span>
<span data-ttu-id="c3ddc-126">Chcete-li zobrazit hodnoty předpokládaných vyřazení a vypočítat zisk a ztráty, můžete použít sestavu **Očekávaná hodnota DM**.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-126">To see the projected disposal values and have the gain and loss calculated, you can use the **FA Projected Value** report.</span></span>

1. <span data-ttu-id="c3ddc-127">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Očekávaná hodnota DM** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-127">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Projected Value**, and then choose the related link.</span></span>
2. <span data-ttu-id="c3ddc-128">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-128">Fill in the fields as necessary.</span></span>
3. <span data-ttu-id="c3ddc-129">Vyberte tlačítko **Tisk** nebo **Náhled**.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-129">Choose the **Print** or **Preview** button.</span></span>

## <a name="to-budget-depreciation"></a><span data-ttu-id="c3ddc-130">Odpis rozpočtu</span><span class="sxs-lookup"><span data-stu-id="c3ddc-130">To budget depreciation</span></span>
<span data-ttu-id="c3ddc-131">Pro výpočet budoucího odpisu můžete použít sestavu **Dlouhodobý majetek - očekávaná hodnota**.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-131">You can use the **Fixed Asset - Projected Value** report to calculate future depreciation.</span></span> <span data-ttu-id="c3ddc-132">Zpráva uvádí účetní hodnotu a akumulované odpisy na začátku vybraného období, změny v daném období a účetní hodnotu a akumulované odpisy na konci vybraného období.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-132">The report shows the book value and accumulated depreciation at the start of the selected period, changes during the period, and the book value and accumulated depreciation at the end of the selected period.</span></span>

1. <span data-ttu-id="c3ddc-133">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Očekávaná hodnota DM** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-133">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA Projected Value**, and then choose the related link.</span></span>
2. <span data-ttu-id="c3ddc-134">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-134">Fill in the fields as necessary.</span></span>
3. <span data-ttu-id="c3ddc-135">Chcete-li zobrazit souhrnné hodnoty pro všechen majetek, zrušte zaškrtnutí políčka **Tisk dle DM**.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-135">To see total values for all assets, clear the **Print per Fixed Asset** check box.</span></span>
4. <span data-ttu-id="c3ddc-136">Ponechte záložku s náhledem **Dlouhodobý majetek** prázdnou, aby byl zahrnut všechen majetek.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-136">Leave the **Fixed Asset** FastTab blank to have all assets included.</span></span> <span data-ttu-id="c3ddc-137">Do pole **Rozpočtový majetek** zadejte **Ne**, chcete-li vyloučit rozpočtovaný majetek nebo **Ano**, abyste viděli pouze rozpočtovaný majetek.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-137">In the **Budgeted Asset** field, enter **No** to exclude budgeted assets or **Yes** to see budgeted assets only.</span></span>
5. <span data-ttu-id="c3ddc-138">Vyberte tlačítko **Tisk** nebo **Náhled**.</span><span class="sxs-lookup"><span data-stu-id="c3ddc-138">Choose the **Print** or **Preview** button.</span></span>

## <a name="see-also"></a><span data-ttu-id="c3ddc-139">Viz také</span><span class="sxs-lookup"><span data-stu-id="c3ddc-139">See Also</span></span>
[<span data-ttu-id="c3ddc-140">Dlouhodobý majetek</span><span class="sxs-lookup"><span data-stu-id="c3ddc-140">Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="c3ddc-141">Nastavení DM</span><span class="sxs-lookup"><span data-stu-id="c3ddc-141">Setting Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="c3ddc-142">Finance</span><span class="sxs-lookup"><span data-stu-id="c3ddc-142">Finance</span></span>](finance.md)  
<span data-ttu-id="c3ddc-143">[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="c3ddc-143">[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span></span>  
<span data-ttu-id="c3ddc-144">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="c3ddc-144">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

