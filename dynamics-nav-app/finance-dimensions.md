---
title: Dimenze
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: a1b38e74717e87bea6efb46f8f4e5236b6ec4e64
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

#<a name="dimensions"></a><span data-ttu-id="fbe59-102">Dimenze</span><span class="sxs-lookup"><span data-stu-id="fbe59-102">Dimensions</span></span>
<span data-ttu-id="fbe59-103">Dimenze jsou data, která přidáváte do hodnot ke kategorizaci pro analýzu.</span><span class="sxs-lookup"><span data-stu-id="fbe59-103">Dimensions are data that you add to entries to categorize them for analysis.</span></span> <span data-ttu-id="fbe59-104">Například můžete mít dimenze, které indikují, ze kterého projektu či oddělení položka pochází.</span><span class="sxs-lookup"><span data-stu-id="fbe59-104">For example, you can have dimensions that indicate which project or department an entry originates from.</span></span>
<span data-ttu-id="fbe59-105">Pak můžete použít dimenze namísto nastavení oddělených účtů hlavní knihy pro každé oddělení či projekt.</span><span class="sxs-lookup"><span data-stu-id="fbe59-105">Then you can use dimensions instead of setting up separate general ledger accounts for each department and project.</span></span> <span data-ttu-id="fbe59-106">To vám umožňuje mít bohaté informace pro analýzu v datech bez nutnosti použití komplikované účtové osnovy.</span><span class="sxs-lookup"><span data-stu-id="fbe59-106">This allows you to have rich analysis information in your data without having to use a complicated chart of accounts.</span></span>
<span data-ttu-id="fbe59-107">Můžete specifikovat neomezený počet dimenzí s neomezeným počtem hodnot dimenzí.</span><span class="sxs-lookup"><span data-stu-id="fbe59-107">You can define an unlimited number of dimensions with an unlimited number of dimension values.</span></span>  

<span data-ttu-id="fbe59-108">Například nastavíte dimenzi zvanou *Oddělení* a použijete tuto dimenzi a hodnotu dimenze, když účtujete prodejní doklady.</span><span class="sxs-lookup"><span data-stu-id="fbe59-108">For example, you set up a dimension called *Department*, and you use this dimension and a dimension value when you post sales documents.</span></span> <span data-ttu-id="fbe59-109">Pak můžete získat data business intelligence, například které položky byly prodány kterým oddělením.</span><span class="sxs-lookup"><span data-stu-id="fbe59-109">Then, you can later get business intelligence data on which items have been sold by which departments, for example.</span></span>
<span data-ttu-id="fbe59-110">Čím více dimenzí nastavíte a používáte, tím na detailnějších sestavách můžete založit Vaše obchodní rozhodnutí.</span><span class="sxs-lookup"><span data-stu-id="fbe59-110">The more dimensions you set up and use, the more detailed reports you can base your business decisions on.</span></span> <span data-ttu-id="fbe59-111">Například jednotlivá položka prodeje může zahrnout více informací o dimenzích, na jaký účet byla položka prodeje zaúčtována, kde byla položka prodána, kdo ji prodal, jaká typ zákazníka provedl nákup.</span><span class="sxs-lookup"><span data-stu-id="fbe59-111">For example, a single sales entry can include multiple dimension information about which account the item sale has been posted to, where the item was sold, who sold it, and what kind of customer made the purchase.</span></span>  

## <a name="using-dimensions"></a><span data-ttu-id="fbe59-112">Použití dimenzí</span><span class="sxs-lookup"><span data-stu-id="fbe59-112">Using dimensions</span></span>
<span data-ttu-id="fbe59-113">V dokladu, jakým je prodejní objednávka, můžete přidat informace o dimenzi pro oba řádky jednotlivého dokladu a dokladu jako takového.</span><span class="sxs-lookup"><span data-stu-id="fbe59-113">In a document such as a sales order, you can add dimension information for both an individual document line and the document itself.</span></span> <span data-ttu-id="fbe59-114">Například v okně **Prodejní objednávka** můžete zadat hodnoty dimenze pro první dvě zkratky dimenzí přímo na dokumentu a můžete přidat další informace, pokud zvolíte tlačítko **Dimenze**.</span><span class="sxs-lookup"><span data-stu-id="fbe59-114">For example, in the **Sales Order** window, you can enter dimension values for the first two shortcut dimensions directly on the document, and you can add further dimension information if you choose the **Dimensions** button.</span></span>  
<span data-ttu-id="fbe59-115">Pokud místo toho pracujete v deníku, můžete také přidat informace o dimenzi do hodnoty stejným způsobem, pokud jste nastavili zkratku dimenzí jako pole přímo na řádcích deníku.</span><span class="sxs-lookup"><span data-stu-id="fbe59-115">In you work in a journal instead, you can also add dimension information to an entry in the same way, if you have set up shortcut dimensions as fields directly on journal lines.</span></span>  
<span data-ttu-id="fbe59-116">Můžete nastavit výchozí dimenze pro účty nebo typy účtů tak, aby dimenze a hodnoty dimenzí byly vyplněny automaticky.</span><span class="sxs-lookup"><span data-stu-id="fbe59-116">You can set up default dimensions for accounts or account types, so that dimensions and dimension values are filled in automatically.</span></span>  

## <a name="dimension-sets"></a><span data-ttu-id="fbe59-117">Sady dimenzí</span><span class="sxs-lookup"><span data-stu-id="fbe59-117">Dimension sets</span></span>
<span data-ttu-id="fbe59-118">Sada dimenzí je jedinečná kombinace hodnot dimenzí.</span><span class="sxs-lookup"><span data-stu-id="fbe59-118">A dimension set is a unique combination of dimension values.</span></span> <span data-ttu-id="fbe59-119">Ukládá se jako sada hodnot dimenzí v databázi.</span><span class="sxs-lookup"><span data-stu-id="fbe59-119">It is stored as dimension set entries in the database.</span></span> <span data-ttu-id="fbe59-120">Každá hodnota sady dimenzí představuje jednotlivou hodnotu dimenze.</span><span class="sxs-lookup"><span data-stu-id="fbe59-120">Each dimension set entry represents a single dimension value.</span></span> <span data-ttu-id="fbe59-121">Sada dimenzí je identifikována běžným ID sady dimenzí, které je připojeno ke každé hodnotě sady dimenzí, která patří do sady dimenzí.</span><span class="sxs-lookup"><span data-stu-id="fbe59-121">The dimension set is identified by a common dimension set ID that is assigned to each dimension set entry that belongs to the dimension set.</span></span>  

<span data-ttu-id="fbe59-122">Když vytvoříte nový řádek deníku, hlavičku dokumentu nebo řádek dokumentu, můžete specifikovat kombinaci hodnot dimenzí.</span><span class="sxs-lookup"><span data-stu-id="fbe59-122">When you create a new journal line, document header, or document line, you can specify a combination of dimension values.</span></span> <span data-ttu-id="fbe59-123">Namísto explicitně ukládané každé hodnoty dimenze v databázi, ID sady dimenze je přiřazeno k řádku deníku, hlavičce dokumentu, nebo řádku dokumentu ke specifikaci sady dimenze.</span><span class="sxs-lookup"><span data-stu-id="fbe59-123">Instead of explicitly storing each dimension value in the database, a dimension set ID is assigned to the journal line, document header, or document line to specify the dimension set.</span></span>  

## <a name="see-also"></a><span data-ttu-id="fbe59-124">Viz také</span><span class="sxs-lookup"><span data-stu-id="fbe59-124">See Also</span></span>
[<span data-ttu-id="fbe59-125">Finance</span><span class="sxs-lookup"><span data-stu-id="fbe59-125">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="fbe59-126">Nastavení dimenzí</span><span class="sxs-lookup"><span data-stu-id="fbe59-126">Set Up Dimensions</span></span>](finance-setup-setup-dimensions.md)  

