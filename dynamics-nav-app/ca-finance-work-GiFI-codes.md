---
title: "Návod: Práce s kódy GIFI v Kanadě"
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 695bca0a6836c47610210b759ae48af27484761f
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-work-with-gifi-codes-in-canada"></a><span data-ttu-id="cf633-102">Návod: Práce s kódy GIFI v Kanadě</span><span class="sxs-lookup"><span data-stu-id="cf633-102">How to: Work With GIFI Codes in Canada</span></span>
<span data-ttu-id="cf633-103">Fiskální informace mohou zahrnovat účty hlavní knihy, výkazy, výkazy zisku a ztrát, rozvahy a výkazy nerozděleného zisku.</span><span class="sxs-lookup"><span data-stu-id="cf633-103">Fiscal information can include general ledger accounts, reports, income statements, balance sheets, and statements of retained earnings.</span></span> <span data-ttu-id="cf633-104">Fiskální informace jsou klasifikovány pomocí kódů.</span><span class="sxs-lookup"><span data-stu-id="cf633-104">Fiscal information is classified using codes.</span></span> <span data-ttu-id="cf633-105">Používání kódů pomáhá vládě zpracovávat informace, připravovat se na elektronické podání a ověřovat daňové informace elektronicky.</span><span class="sxs-lookup"><span data-stu-id="cf633-105">The use of codes helps the government to process information, prepare for electronic filing, and validate tax information electronically.</span></span> <span data-ttu-id="cf633-106">Používání kódů také pomáhá statistickým organizacím pracovat efektivněji, protože finanční informace jsou snadněji dostupné.</span><span class="sxs-lookup"><span data-stu-id="cf633-106">The use of codes also helps statistical organizations to work more efficiently, as financial information is more readily available.</span></span> <span data-ttu-id="cf633-107">Další informace naleznete v tématu [Kanadská agentura pro daňovou agendu](http://www.cra-arc.gc.ca/).</span><span class="sxs-lookup"><span data-stu-id="cf633-107">For more information, see the [Canada Revenue Agency website](http://www.cra-arc.gc.ca/).</span></span>

<span data-ttu-id="cf633-108">Kanadská daňová agentura využívá kódy obecného indexu finančních informací (GIFI) pro shromažďování, ověřování a zpracování finančních a daňových informací elektronicky.</span><span class="sxs-lookup"><span data-stu-id="cf633-108">The Canada Revenue Agency uses General Index of Financial Information (GIFI) codes to collect, validate, and process financial and tax information electronically.</span></span> <span data-ttu-id="cf633-109">Nejlepším postupem je přiřadit kódy GIFI pouze zaúčtovaným účtům, takže celkový součet je prováděn pomocí softwaru pro daňovou přípravu.</span><span class="sxs-lookup"><span data-stu-id="cf633-109">It is a best practice to assign GIFI codes only to posting accounts, so that all totaling is done by your tax preparation software.</span></span>

<span data-ttu-id="cf633-110">Pokud je účet spojen s kódem GIFI, je nahlášen agentuře pro příjem pod tímto kódem.</span><span class="sxs-lookup"><span data-stu-id="cf633-110">When an account is associated with a GIFI code, it is reported to the revenue agency under that code.</span></span> <span data-ttu-id="cf633-111">Více účtů může mít stejný kód GIFI, ale každý účet může mít pouze jeden kód GIFI.</span><span class="sxs-lookup"><span data-stu-id="cf633-111">Multiple accounts can all have the same GIFI code, but each account can have only one GIFI code.</span></span>

<span data-ttu-id="cf633-112">Můžete exportovat informace o zůstatku pomocí kódu GIFI a uložit exportovaný soubor v aplikaci Excel, což je užitečné pro přenos informací do softwaru pro daňové zpracování.</span><span class="sxs-lookup"><span data-stu-id="cf633-112">You can export balance information by GIFI code and save the exported file in Excel, which is useful for transferring information to your tax preparation software.</span></span>

## <a name="to-set-up-gifi-codes"></a><span data-ttu-id="cf633-113">Nastavení kódů GIFI</span><span class="sxs-lookup"><span data-stu-id="cf633-113">To set up GIFI codes</span></span>
<span data-ttu-id="cf633-114">V Dynamics NAV musíte nastavit kódy GIFI pro účty hlavní knihy, přehledy, rozvahy, výkazy příjmů a výkazy nerozděleného zisku.</span><span class="sxs-lookup"><span data-stu-id="cf633-114">In Dynamics NAV, you must set up GIFI codes for general ledger accounts, reports, balance sheets, income sheets, and statements of retained earnings.</span></span>

1. <span data-ttu-id="cf633-115">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Kódy GIFI** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="cf633-115">In the top right corner, choose the **Search for Page or Report** icon, enter **GIFI Codes**, and then choose the related link.</span></span>
2. <span data-ttu-id="cf633-116">V okně **Kódy GIFI** vyberte akci **Nový**.</span><span class="sxs-lookup"><span data-stu-id="cf633-116">In the **GIFI Codes** window, choose the **New** action.</span></span>
3. <span data-ttu-id="cf633-117">Nastavení kódů GIFI vyplněním polí.</span><span class="sxs-lookup"><span data-stu-id="cf633-117">Set up GIFI codes by filling the fields.</span></span> <span data-ttu-id="cf633-118">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="cf633-118">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-associate-gifi-codes-with-gl-accounts"></a><span data-ttu-id="cf633-119">Přidělení kódů GIFI k finančním účtům</span><span class="sxs-lookup"><span data-stu-id="cf633-119">To associate GIFI codes with G/L accounts</span></span>
<span data-ttu-id="cf633-120">Chcete-li ohlásit finanční informace pomocí kódu GIFI, musí být každý kód GIFI přidružen k příslušným účtům v účtové osnově.</span><span class="sxs-lookup"><span data-stu-id="cf633-120">To report financial information by GIFI code, each GIFI code must be associated with the appropriate accounts in the chart of accounts.</span></span>

1. <span data-ttu-id="cf633-121">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účetní osnova** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="cf633-121">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="cf633-122">Vyberte příslušný účet hlavní knihy a pak zvolte akci **Upravit**. </span><span class="sxs-lookup"><span data-stu-id="cf633-122">Select a relevant general ledger account, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="cf633-123">Na záložce s náhledem **Účtování nákladů** vyberte v poli **Kód GIFI** příslušný kód GIFI.</span><span class="sxs-lookup"><span data-stu-id="cf633-123">On the **Cost Accounting** FastTab, in the **GIFI Code** field, select an appropriate GIFI code.</span></span>

## <a name="to-view-account-balances-using-the-gifi-code-report"></a><span data-ttu-id="cf633-124">Zobrazení zůstatků na účtů pomocí kódu GIFI</span><span class="sxs-lookup"><span data-stu-id="cf633-124">To view account balances using the GIFI code report</span></span>
<span data-ttu-id="cf633-125">Zůstatek účtu můžete zkontrolovat podle kódu GIFI pomocí přehledu **Zůstatky na účtu podle kódu GIFI**.</span><span class="sxs-lookup"><span data-stu-id="cf633-125">You can review your account balances by GIFI code by using the **Account Balances by GIFI Code** report.</span></span>

1. <span data-ttu-id="cf633-126">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zůstatky na účtu podle kódu GIFI** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="cf633-126">In the top right corner, choose the **Search for Page or Report** icon, enter **Account Balances by GIFI Code**, and then choose the related link.</span></span>
2. <span data-ttu-id="cf633-127">Uveďte, co se má ve zprávě zapsat vyplněním polí.</span><span class="sxs-lookup"><span data-stu-id="cf633-127">Specify what to include in the report by filling the fields.</span></span> <span data-ttu-id="cf633-128">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="cf633-128">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="cf633-129">Zvolte tlačítko **Tisk** nebo **Náhled**. </span><span class="sxs-lookup"><span data-stu-id="cf633-129">Choose the **Print** or the **Preview** button.</span></span>

## <a name="to-export-balance-information-using-gifi-codes"></a><span data-ttu-id="cf633-130">Export informací o zůstatcích pomocí kódu GIFI</span><span class="sxs-lookup"><span data-stu-id="cf633-130">To export balance information using GIFI codes</span></span>
<span data-ttu-id="cf633-131">Informace o exportu zůstatků pomocí kódů GIFI a uložení exportovaného souboru v aplikaci Excel.</span><span class="sxs-lookup"><span data-stu-id="cf633-131">You can export balance information using GIFI codes and save the exported file in Excel.</span></span> <span data-ttu-id="cf633-132">Můžete upravit, uložit nebo smazat soubor.</span><span class="sxs-lookup"><span data-stu-id="cf633-132">You can modify, save, or delete the file.</span></span> <span data-ttu-id="cf633-133">Soubor můžete použít k přenosu informací do softwaru pro daňové zpracování.</span><span class="sxs-lookup"><span data-stu-id="cf633-133">You can use the file to transfer information to your tax preparation software.</span></span>

1. <span data-ttu-id="cf633-134">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Export GIFI info. do Excelu** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="cf633-134">In the top right corner, choose the **Search for Page or Report** icon, enter **Export GIFI Info. to Excel**, and then choose the related link.</span></span>
2. <span data-ttu-id="cf633-135">Určete, co exportovat do aplikace Excel vyplněním polí.</span><span class="sxs-lookup"><span data-stu-id="cf633-135">Specify what to export to Excel by filling the fields.</span></span> <span data-ttu-id="cf633-136">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="cf633-136">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="cf633-137">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="cf633-137">Choose the **OK** button.</span></span>

<span data-ttu-id="cf633-138">**Poznámka:** Soubor aplikace Excel má následující vlastnosti:</span><span class="sxs-lookup"><span data-stu-id="cf633-138">**Note:** The Excel file has the following characteristics:</span></span>

* <span data-ttu-id="cf633-139">Zůstatek je zaokrouhlen na nejbližší procentní podíl, ale hodnota buňky zůstává stejná jako v hlavní knize.</span><span class="sxs-lookup"><span data-stu-id="cf633-139">The balance is rounded to the nearest percentage, but the cell value maintains the same percentage as it does in the general ledger.</span></span>

* <span data-ttu-id="cf633-140">Negativní čísla jsou v závorkách reprezentována jako kladné číslo.</span><span class="sxs-lookup"><span data-stu-id="cf633-140">Negative numbers are represented as positive number in brackets.</span></span> <span data-ttu-id="cf633-141">Proto je -123 reprezentováno jako (123).</span><span class="sxs-lookup"><span data-stu-id="cf633-141">Accordingly, -123 is represented as (123).</span></span>

## <a name="see-also"></a><span data-ttu-id="cf633-142">Viz také</span><span class="sxs-lookup"><span data-stu-id="cf633-142">See Also</span></span>
<span data-ttu-id="cf633-143">[Finance](finance-setup.md) </span><span class="sxs-lookup"><span data-stu-id="cf633-143">[Finance](finance-setup.md) </span></span>  
[<span data-ttu-id="cf633-144">Nastavení klíčových finančních procesů</span><span class="sxs-lookup"><span data-stu-id="cf633-144">Set Up Core Financial Processes</span></span>](finance-setup-setup-finance-setup.md)

