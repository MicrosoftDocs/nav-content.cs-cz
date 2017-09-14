---
title: "Návod: Nastavení cyklů prodejních příležitostí a fází prodejních cyklů"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 756e9b2f33fe66cd4c2b4e26ca4390683bd087af
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---
# <a name="how-to-set-up-opportunity-sales-cycles-and-cycle-stages"></a><span data-ttu-id="73eca-102">Návod: Nastavení cyklů prodejních příležitostí a fází prodejních cyklů</span><span class="sxs-lookup"><span data-stu-id="73eca-102">How to: Set Up Opportunity Sales Cycles and Cycle Stages</span></span>
<span data-ttu-id="73eca-103">Než začnete využívat prodejní příležitosti, musíte nastavit prodejní cykly a fáze prodejního cyklu.</span><span class="sxs-lookup"><span data-stu-id="73eca-103">Before you can start using sales opportunities, you must set up sales cycles and sales cycle stages.</span></span> <span data-ttu-id="73eca-104">Prodejní cyklus se skládá ze série fází, které jdou od počátečního kontaktu až k uzavření prodeje.</span><span class="sxs-lookup"><span data-stu-id="73eca-104">A sales cycle is made up of a series of stages that go from the initial contact to the closing of a sale.</span></span> <span data-ttu-id="73eca-105">Každá fáze může mít určité požadavky, které musí být splněny, jako je požadavek na prodejní nabídku, než může jít příležitost do další fáze.</span><span class="sxs-lookup"><span data-stu-id="73eca-105">Each stage can have certain requirements that must be met, such as requiring a sales quote, before an opportunity can go to the next stage.</span></span> <span data-ttu-id="73eca-106">Můžete také určit, zda je možné přeskočit fázi.</span><span class="sxs-lookup"><span data-stu-id="73eca-106">You can also specify whether a stage can be skipped.</span></span> <span data-ttu-id="73eca-107">Můžete nastavit tolik prodejních cyklů, kolik potřebujete, a můžete nastavit tolik fází prodejních cyklů, kolik bude potřeba v rámci prodejního cyklu.</span><span class="sxs-lookup"><span data-stu-id="73eca-107">You can setup as many sales cycles as you need, and you can set up as many sales cycle stages as necessary within a sales cycle.</span></span>

<span data-ttu-id="73eca-108">Implementace příležitostných prodejních cyklů zahrnuje nastavení kódu prodejního cyklu, definování jednotlivých fází cyklu a následné zařazení cyklu do příležitostí.</span><span class="sxs-lookup"><span data-stu-id="73eca-108">Implementing opportunity sales cycles involves setting up the sales cycle code, defining the different stages of the cycle, and then assigning the cycle to opportunities.</span></span>

## <a name="to-set-up-an-opportunity-sales-cycle-code"></a><span data-ttu-id="73eca-109">Nastavení kódu příležitostného prodejního cyklu</span><span class="sxs-lookup"><span data-stu-id="73eca-109">To set up an opportunity sales cycle code</span></span>
1. <span data-ttu-id="73eca-110">V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Prodejní cykly** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="73eca-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales Cycles**, and then choose the related link.</span></span> <span data-ttu-id="73eca-111">Otevře se okno **Prodejní cykly** a zobrazí seznam všech stávajících prodejních cyklů.</span><span class="sxs-lookup"><span data-stu-id="73eca-111">The **Sales Cycles** window opens, and lists all the existing sales cycles.</span></span>
2. <span data-ttu-id="73eca-112">Vyberte akci **Nový** a vyplňte pole.</span><span class="sxs-lookup"><span data-stu-id="73eca-112">Choose the **New** action, and fill in the fields.</span></span>

<span data-ttu-id="73eca-113">Opakujte tyto kroky k nastavení prodejních cyklů tolikrát, kolik jich budete potřebovat.</span><span class="sxs-lookup"><span data-stu-id="73eca-113">Repeat these steps to set up as many sales cycles as you want.</span></span> <span data-ttu-id="73eca-114">Po nastavení příležitostných prodejních cyklů můžete nastavit různé fáze v rámci každého cyklu.</span><span class="sxs-lookup"><span data-stu-id="73eca-114">After you have set up opportunity sales cycles, you may want to set up the different stages within each cycle.</span></span>

## <a name="to-define-opportunity-sales-cycle-stages"></a><span data-ttu-id="73eca-115">Definování fáze příležitostných prodejních cyklů</span><span class="sxs-lookup"><span data-stu-id="73eca-115">To define opportunity sales cycle stages</span></span>
1. <span data-ttu-id="73eca-116">V okně **Prodejní cykly** vyberte příležitostný prodejní cyklus, pro který chcete nastavit fáze, a poté zvolte akci **Fáze**.</span><span class="sxs-lookup"><span data-stu-id="73eca-116">In the **Sales Cycles** window, select the opportunity sales cycle for which you want to set up stages, and then choose the **Stages** action.</span></span> <span data-ttu-id="73eca-117">Zobrazí se okno **Fáze prodejních cyklů**.</span><span class="sxs-lookup"><span data-stu-id="73eca-117">The **Sales Cycle Stages** window opens.</span></span>
2. <span data-ttu-id="73eca-118">Zvolte akci **Nový**, chcete-li zadat novou fázi v prodejním cyklu.</span><span class="sxs-lookup"><span data-stu-id="73eca-118">Choose the **New** action to enter a new stage in the sales cycle.</span></span>

<span data-ttu-id="73eca-119">Opakujte tyto kroky, abyste nastavili tolik fází, kolik v rámci prodejního cyklu chcete.</span><span class="sxs-lookup"><span data-stu-id="73eca-119">Repeat these steps to set up as many stages as you want within the sales cycle.</span></span>

## <a name="to-assign-stage-cycle-to-an-opportunity"></a><span data-ttu-id="73eca-120">Přiřazení fáze cyklu k příležitosti</span><span class="sxs-lookup"><span data-stu-id="73eca-120">To assign stage cycle to an opportunity</span></span>
<span data-ttu-id="73eca-121">Po přidání  příležitostného prodejního cyklu můžete začít přidávat prodejní příležitosti a přiřadit cyklus fáze k příležitostem nastavením pole **Kód prodejního cyklu**.</span><span class="sxs-lookup"><span data-stu-id="73eca-121">After you add the opportunities stage cycle, you can start to add sales opportunities, and then assign the stage cycle to opportunities by setting the **Sales Cycle Code** field.</span></span> <span data-ttu-id="73eca-122">Pro další informace viz [Návod: Vytvoření prodejních příležitostí](marketing-how-create-opportunities.md).</span><span class="sxs-lookup"><span data-stu-id="73eca-122">For more information, see [How to: Create Sales Opportunities](marketing-how-create-opportunities.md).</span></span>

##<a name="see-also"></a><span data-ttu-id="73eca-123">Viz také</span><span class="sxs-lookup"><span data-stu-id="73eca-123">See Also</span></span>  
[<span data-ttu-id="73eca-124">Zpracování prodejních příležitostí</span><span class="sxs-lookup"><span data-stu-id="73eca-124">Processing Sales Opportunities</span></span>](marketing-processing-sales-opportunities.md)  
[<span data-ttu-id="73eca-125">Správa prodeje</span><span class="sxs-lookup"><span data-stu-id="73eca-125">Manage Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="73eca-126">[Práce s [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="73eca-126">[Working with Dynamics NAV](ui-work-product.md)</span></span>

