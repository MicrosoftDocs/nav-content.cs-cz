---
title: "Zadání výběru tiskáren pro sestavy"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 56a5c1428651162293e56d71e2369fe55d291594
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---
    
# <a name="specify-printer-selection-for-reports"></a><span data-ttu-id="8b009-102">Zadání výběru tiskáren pro sestavy</span><span class="sxs-lookup"><span data-stu-id="8b009-102">Specify Printer Selection for Reports</span></span>
<span data-ttu-id="8b009-103">Můžete nastavit sestavy tak, aby byly vytištěny na konkrétní tiskárně.</span><span class="sxs-lookup"><span data-stu-id="8b009-103">You can set up reports so that they must be printed on a specific printer.</span></span> <span data-ttu-id="8b009-104">Níže jsou uvedeny některé způsoby použití výběru tiskárny:</span><span class="sxs-lookup"><span data-stu-id="8b009-104">The following are some uses of printer selection:</span></span> 

- <span data-ttu-id="8b009-105">Můžete tisknout sestavy se speciálními hlavičkami společnosti. </span><span class="sxs-lookup"><span data-stu-id="8b009-105">You can print reports on special company letterhead.</span></span>
- <span data-ttu-id="8b009-106">Můžete tisknout sestavy na různě velké papíry.</span><span class="sxs-lookup"><span data-stu-id="8b009-106">You can print reports on different paper sizes.</span></span>
- <span data-ttu-id="8b009-107">Můžete vytisknout sestavy na výchozí tiskárně konkrétního zaměstnance.</span><span class="sxs-lookup"><span data-stu-id="8b009-107">You can print reports on the default printer of a specified employee.</span></span>

<span data-ttu-id="8b009-108">V okně **Výběr tiskárny** můžete nastavit různé hodnoty pro získání odlišného výstupu.</span><span class="sxs-lookup"><span data-stu-id="8b009-108">You use the **Printer Selections** window to set different values to obtain different output.</span></span> <span data-ttu-id="8b009-109">Pokud nastavíte konkrétní výběr tiskárny, bude mít přednost před obecnějším výběrem tiskárny.</span><span class="sxs-lookup"><span data-stu-id="8b009-109">If you set a specific printer selection, then it takes precedence over a more general printer selection.</span></span> <span data-ttu-id="8b009-110">Můžete například nastavit výběr tiskárny, který obsahuje hodnoty v poli **ID uživatele**, **ID sestavy** a **Název tiskárny**.</span><span class="sxs-lookup"><span data-stu-id="8b009-110">For example, you can set a printer selection that has values in the **User ID**, **Report ID**, and **Printer Name** fields.</span></span> <span data-ttu-id="8b009-111">Tato volba tiskárny má přednost před volbou tiskárny s prázdnými položkami v polích **ID uživatele**, nebo **ID sestavy**.</span><span class="sxs-lookup"><span data-stu-id="8b009-111">This printer selection takes precedence over a printer selection that has blank entries in the **User ID** or **Report ID** fields.</span></span> 

<span data-ttu-id="8b009-112">Následující tabulka popisuje kombinaci hodnot určených pro nastavení výběru tiskárny pro sestavu.</span><span class="sxs-lookup"><span data-stu-id="8b009-112">The following table describes the combination of values to specify when you set up printer selections for a report.</span></span>

|<span data-ttu-id="8b009-113">K</span><span class="sxs-lookup"><span data-stu-id="8b009-113">To</span></span>                                                 |<span data-ttu-id="8b009-114">Nastavení následujících hodnot</span><span class="sxs-lookup"><span data-stu-id="8b009-114">Set the following values</span></span>                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|<span data-ttu-id="8b009-115">Vytiskněte sestavu na konkrétní tiskárně pro všechny uživatele</span><span class="sxs-lookup"><span data-stu-id="8b009-115">Print a report to a specific printer for all users</span></span> |<span data-ttu-id="8b009-116">Určete hodnoty v polích **ID sestavy** a **Název tiskárny** a pole **ID uživatele** nechejte prázdné.</span><span class="sxs-lookup"><span data-stu-id="8b009-116">Specify values in the **Report ID** and **Printer Name** fields and leave the **User ID** field blank.</span></span>|
|<span data-ttu-id="8b009-117">Vytiskněte všechny sestavy na konkrétní tiskárně pro konkrétního uživatele</span><span class="sxs-lookup"><span data-stu-id="8b009-117">Print all reports to a specific printer for a specific user</span></span>|<span data-ttu-id="8b009-118">Zadejte hodnoty v polích **ID uživatele** a **Název tiskárny** a pole **ID sestavy** nechejte prázdné.</span><span class="sxs-lookup"><span data-stu-id="8b009-118">Specify values in the **User ID** and **Printer Name** fields and leave the **Report ID** field blank.</span></span>|
|<span data-ttu-id="8b009-119">Nastavte výchozí tiskárnu pro všechny sestavy</span><span class="sxs-lookup"><span data-stu-id="8b009-119">Set the default printer for all reports</span></span>|<span data-ttu-id="8b009-120">Zadejte hodnotu v poli **Název tiskárny** a pole **ID uživatele** a **ID sestavy** nechte prázdné.</span><span class="sxs-lookup"><span data-stu-id="8b009-120">Specify a value in the **Printer Name** field and leave the **User ID** and **Report ID** fields blank.</span></span>|
|<span data-ttu-id="8b009-121">Vytiskněte konkrétní sestavu na výchozí tiskárně uživatele</span><span class="sxs-lookup"><span data-stu-id="8b009-121">Print a specific report to the user’s default printer</span></span>|<span data-ttu-id="8b009-122">Zadejte hodnotu v poli **ID sestavy** a pole **Název tiskárny** a **ID uživatele** nechejte prázdné.</span><span class="sxs-lookup"><span data-stu-id="8b009-122">Specify a value in the **Report ID** field and leave the **Printer Name** and **User ID** fields blank.</span></span>|
|<span data-ttu-id="8b009-123">Vytiskněte konkrétní sestavu na konkrétní tiskárně pro konkrétního uživatele</span><span class="sxs-lookup"><span data-stu-id="8b009-123">Print a specific report to a specific printer for a specific user</span></span>|<span data-ttu-id="8b009-124">Určete hodnoty ve všech třech polích.</span><span class="sxs-lookup"><span data-stu-id="8b009-124">Specify values in all three fields.</span></span>|

## <a name="see-also"></a><span data-ttu-id="8b009-125">Viz také</span><span class="sxs-lookup"><span data-stu-id="8b009-125">See Also</span></span>
[<span data-ttu-id="8b009-126">Práce s Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="8b009-126">Work with Dynamics NAV</span></span>](ui-work-product.md)

