---
title: "Změna způsobu, jak vypadá sestava, výběrem jiného rozvržení"
description: "Pro sestavu můžete použít různé rozvržení a přepínat mezi rozvrženími, abyste změnili, jak vypadá sestava."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customized report, document layout, logo, personalize
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7fc680503a3fb2d685758b69e123dc98b2d98e75
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-change-which-layout-is-currently-used-on-a-report"></a><span data-ttu-id="37c78-103">Návod: Změna využívaného rozvržení pro danou sestavu</span><span class="sxs-lookup"><span data-stu-id="37c78-103">How to: Change Which Layout is Currently Used on a Report</span></span>
<span data-ttu-id="37c78-104">Sestava může být nastavena s více než jedním rozvržením, které můžete podle potřeby přepínat.</span><span class="sxs-lookup"><span data-stu-id="37c78-104">A report can be set up with more than one report layout, which you can then switch among as needed.</span></span>

<span data-ttu-id="37c78-105">V závislosti na rozvržení, které jsou k dispozici pro sestavu, můžete zvolit použití vestavěného rozvržení sestavy RDLC, vestavěného rozvržení sestavy aplikace Word nebo vlastního rozvržení.</span><span class="sxs-lookup"><span data-stu-id="37c78-105">Depending on the layouts that are available for a report, you can choose to use a built-in RDLC report layout, a built-in Word report layout, or a custom layout.</span></span> <span data-ttu-id="37c78-106">Další informace o rozvržení RDLC a Wordových sestav, vestavěných, vlastních rozvržení a dalších naleznete v tématu [Správa rozvržení sestav](ui-manage-report-layouts.md).</span><span class="sxs-lookup"><span data-stu-id="37c78-106">For more information about RDLC and Word report layouts, built-in and custom layouts, and more, see [Manage Report Layouts](ui-manage-report-layouts.md).</span></span>

## <a name="to-change-the-layout-that-is-used-on-a-report"></a><span data-ttu-id="37c78-107">Změna využívaného rozvržení pro sestavu</span><span class="sxs-lookup"><span data-stu-id="37c78-107">To change the layout that is used on a report</span></span>
1. <span data-ttu-id="37c78-108">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Výběr rozvržení sestavy** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="37c78-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Report Layout Selection**, and then choose the related link.</span></span>  
   <span data-ttu-id="37c78-109">Okno **Výběr rozvržení sestav** obsahuje seznam všech sestav, které jsou k dispozici ve společnosti, která je uvedena v poli Společnost v horní části okna.</span><span class="sxs-lookup"><span data-stu-id="37c78-109">The **Report Layout Selection** window lists all the reports that are available for the company that is specified in the Company field at the top of the window.</span></span> <span data-ttu-id="37c78-110">Pole Vybrané rozložení určuje rozvržení, které se aktuálně používá v sestavě.</span><span class="sxs-lookup"><span data-stu-id="37c78-110">The Selected Layout field specifies the layout that is currently used on the report.</span></span>
2. <span data-ttu-id="37c78-111">Pole **Název společnosti** v horní části okna nastavte na společnost, ve které se používá daná sestava.</span><span class="sxs-lookup"><span data-stu-id="37c78-111">Set the **Company** field at the top of the window to the company that includes the report.</span></span>
3. <span data-ttu-id="37c78-112">Chcete-li změnit rozvržení, které používá sestava, v řádku seznamu sestav nastavte pole **Vybrané rozložení** na jednu z následujících možností:</span><span class="sxs-lookup"><span data-stu-id="37c78-112">To change the layout that is used by a report, in the row for the report in the list, set the **Selected Layout** field to one of the following options:</span></span>
   * <span data-ttu-id="37c78-113">RDLC (vestavěný) používá vestavěné RDLC rozvržení sestavy</span><span class="sxs-lookup"><span data-stu-id="37c78-113">RDLC (built-in), uses the built-in RDLC report layout on the report.</span></span>
   * <span data-ttu-id="37c78-114">Word (vestavěný) používá vestavěné Word rozvržení sestavy</span><span class="sxs-lookup"><span data-stu-id="37c78-114">Word (built-in), uses the built-in Word report layout on the report.</span></span>
   * <span data-ttu-id="37c78-115">Vlastní používá vlastní rozvržení sestavy</span><span class="sxs-lookup"><span data-stu-id="37c78-115">Custom, uses a custom layout on the report.</span></span>  
     <span data-ttu-id="37c78-116">Můžete vidět, které vlastní rozvržení jsou k dispozici pro sestavu v část FactBoxu Rozvržení sestav.</span><span class="sxs-lookup"><span data-stu-id="37c78-116">You can see which custom layouts are available for the report in the Report Layouts Part FactBox.</span></span> <span data-ttu-id="37c78-117">Pokud pro sestavu neexistují žádné vlastní rozvržení, budete muset vytvořit nejprve nové.</span><span class="sxs-lookup"><span data-stu-id="37c78-117">If there are no custom layouts for the report, then you will have to create one first.</span></span> <span data-ttu-id="37c78-118">Pokud zvolíte tuto možnost, přejděte k dalšímu postupu, abyste navrhli vlastní rozvržení, které chcete použít.</span><span class="sxs-lookup"><span data-stu-id="37c78-118">If you choose this option, go to the next procedure to specify the custom layout that you want to use.</span></span>

    > [!NOTE]  
    >   <span data-ttu-id="37c78-119">Pokud zvolíte **RDLC (vestavěný)** nebo **Word (vestavěný)** a zobrazí se chybová zpráva, že sestava nemá rozložení zadaného typu, musíte vybrat jinou možnost rozložení nebo vytvořit vlastní rozvržení sestavy daného typu.</span><span class="sxs-lookup"><span data-stu-id="37c78-119">If you choose **RDLC (built-in)** or **Word (built-in)** and you get an error message that the report does not have a layout of the specified type, then you must choose another layout option or create a custom report layout of the type that you want to use.</span></span>

<span data-ttu-id="37c78-120">Pokud jste vybrali vestavěné rozložení sestav RDLC nebo Word, není třeba provádět žádné další akce a rozložení bude použito při příštím spuštění sestavy.</span><span class="sxs-lookup"><span data-stu-id="37c78-120">If you selected a built-in RDLC or Word report layout, then no further action is required and the layout will be used the next time the report is run.</span></span>

## <a name="to-specify-a-custom-layout-on-a-report"></a><span data-ttu-id="37c78-121">Navrhnutí vlastního rozvržení sestavy</span><span class="sxs-lookup"><span data-stu-id="37c78-121">To specify a custom layout on a report</span></span>
1. <span data-ttu-id="37c78-122">Můžete navrhnou vlastní rozvržení sestavy na sestavu z okna **Vlastní rozvržení sestav**.</span><span class="sxs-lookup"><span data-stu-id="37c78-122">You specify which custom layout to use on the report from the **Custom Report Layouts** window.</span></span> <span data-ttu-id="37c78-123">Není-li okno **Vlastní rozvržení sestav** otevřené, vyberte v poli **Popis rozvržení sestavy** tlačítko pro rozbalení.</span><span class="sxs-lookup"><span data-stu-id="37c78-123">If the **Custom Report Layouts** window is not open, then in the **Report Layout Description** field, choose the lookup button.</span></span>
2. <span data-ttu-id="37c78-124">V okně **Vlastní rozvržení sestav** vyberte řádek pro vlastní rozložení, které chcete použít, a potom zavřete okno.</span><span class="sxs-lookup"><span data-stu-id="37c78-124">In the **Custom Report Layouts** window, select the row for custom layout that you want to use, and then close the window.</span></span>

<span data-ttu-id="37c78-125">Vrátíte se do okna **Výběr rozvržení sestav**.</span><span class="sxs-lookup"><span data-stu-id="37c78-125">You return to the **Report Layout Selection** window.</span></span> <span data-ttu-id="37c78-126">Název vybraného vlastního rozvržení se zobrazí v poli **Popis vlastního rozvržení**.</span><span class="sxs-lookup"><span data-stu-id="37c78-126">The name of the selected custom layout displays in the **Custom Layout Description** field.</span></span> <span data-ttu-id="37c78-127">Vlastní rozložení se použije při příštím spuštění sestavy.</span><span class="sxs-lookup"><span data-stu-id="37c78-127">The custom layout will be used the next time that you run the report.</span></span>

## <a name="see-also"></a><span data-ttu-id="37c78-128">Viz také</span><span class="sxs-lookup"><span data-stu-id="37c78-128">See Also</span></span>
[<span data-ttu-id="37c78-129">Správa rozvržení sestav</span><span class="sxs-lookup"><span data-stu-id="37c78-129">Managing Report Layouts</span></span>](ui-manage-report-layouts.md)  
<span data-ttu-id="37c78-130">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="37c78-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

