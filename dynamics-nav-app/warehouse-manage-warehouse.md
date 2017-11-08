---
title: "Skladové aktivity"
description: "Potom, co je zboží obdrženo, ale nedodáno, uskuteční se série vnitřních skladových aktivit k zajištění efektivního toku skrz sklad a organizaci a údržby zásob společnosti."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 608dc6f0d4fcf84d5df5a7d7c0c0dc304fdcad5f
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="warehouse-management"></a><span data-ttu-id="93d11-103">Správa skladu</span><span class="sxs-lookup"><span data-stu-id="93d11-103">Warehouse Management</span></span>
<span data-ttu-id="93d11-104">Potom, co je zboží obdrženo, ale nedodáno, uskuteční se série vnitřních skladových aktivit k zajištění efektivního toku skrz sklad a organizaci a údržby zásob společnosti.</span><span class="sxs-lookup"><span data-stu-id="93d11-104">After goods are received and before goods are shipped, a series of internal warehouse activities take place to ensure an effective flow through the warehouse and to organize and maintain company inventories.</span></span>

<span data-ttu-id="93d11-105">Typické skladové aktivity zahrnují zaskladnění zboží, přesun zboží do skladu nebo mezi sklady a vyskladnění zboží pro montáž, výrobu nebo dodávku.</span><span class="sxs-lookup"><span data-stu-id="93d11-105">Typical warehouse activities include putting items away, moving items inside or between warehouses, and picking items for assembly, production, or shipment.</span></span> <span data-ttu-id="93d11-106">Montáž zboží pro prodej nebo zásoby může také být považováno za skladovou aktivitu, ale tyhle jsou zahrnuty jinde.</span><span class="sxs-lookup"><span data-stu-id="93d11-106">Assembling items for sale or inventory may also be considered warehouse activities, but these are covered elsewhere.</span></span> <span data-ttu-id="93d11-107">Další informace naleznete v tématu [Správa montáže](assembly-assemble-items.md).</span><span class="sxs-lookup"><span data-stu-id="93d11-107">For more information, see [Assembly Management](assembly-assemble-items.md).</span></span>  

<span data-ttu-id="93d11-108">Ve velkých skladech mohou být tyhle různě vykonávané úlohy rozděleny odděleními a integrace spravována řízeným workflow.</span><span class="sxs-lookup"><span data-stu-id="93d11-108">In large warehouses, these different handling tasks can be separated by departments and the integration managed by a directed workflow.</span></span> <span data-ttu-id="93d11-109">V jednodušších instalacích je tok méně formalizován a skladové aktivity jsou vykonávány s takzvaným zaskladněním a vyskladněním zásob.</span><span class="sxs-lookup"><span data-stu-id="93d11-109">In simpler installations, the flow is less formalized and the warehouse activities are performed with so-called inventory put-aways and inventory picks.</span></span> <span data-ttu-id="93d11-110">Více informací o základních versus pokročilých konfigurací skladu jděte na [Detaily návrhu: Přehled skladu](design-details-warehouse-overview.md).</span><span class="sxs-lookup"><span data-stu-id="93d11-110">For more information about basic versus advanced warehouse configurations, see [Design Details: Warehouse Overview](design-details-warehouse-overview.md).</span></span>

<span data-ttu-id="93d11-111">Než budete moci vykonávat skladové aktivity, musíte nastavit systém pro odpovídající složitost zpracování skladu.</span><span class="sxs-lookup"><span data-stu-id="93d11-111">Before you can perform warehouse activities, you must set the system up for the relevant complexity of warehouse processing.</span></span> <span data-ttu-id="93d11-112">Další informace naleznete v části [Nastavení správy skladu](warehouse-setup-warehouse.md).</span><span class="sxs-lookup"><span data-stu-id="93d11-112">For more information, see [Setting Up Warehouse Management](warehouse-setup-warehouse.md).</span></span>

 <span data-ttu-id="93d11-113">Následující tabulka popisuje sekvenci úloh s odkazy na témata, která je popisují.</span><span class="sxs-lookup"><span data-stu-id="93d11-113">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>   

|<span data-ttu-id="93d11-114">**Popis**</span><span class="sxs-lookup"><span data-stu-id="93d11-114">**To**</span></span>|<span data-ttu-id="93d11-115">**Odkaz**</span><span class="sxs-lookup"><span data-stu-id="93d11-115">**See**</span></span>|  
|------------|-------------|  
|<span data-ttu-id="93d11-116">Zaznamenávejte příjemky zboží ve skladových lokacích buď jen s nákupní objednávkou v jednoduchých nastaveních lokací, nebo se skladovou příjemkou v případě polo nebo plno automatizovaného zpracování skladu v dané lokaci.</span><span class="sxs-lookup"><span data-stu-id="93d11-116">Record the receipt of items at warehouse locations, either with a purchase order only, in simple location setups, or with a warehouse receipt, in case of semi or fully automated warehouse processing at the location.</span></span>|[<span data-ttu-id="93d11-117">Návod: Přijmout zboží</span><span class="sxs-lookup"><span data-stu-id="93d11-117">How to: Receive Items</span></span>](warehouse-how-receive-items.md)|
|<span data-ttu-id="93d11-118">Obejděte procesy zaskladnění a vyskladnění pro expedici zboží přímo od příjmu nebo výroby k dodávce.</span><span class="sxs-lookup"><span data-stu-id="93d11-118">Bypass the put-away and pick processes to expedite an item straight from receiving or production to shipping.</span></span>|[<span data-ttu-id="93d11-119">Návod: Přeložení zboží</span><span class="sxs-lookup"><span data-stu-id="93d11-119">How to: Cross-Dock Items</span></span>](warehouse-how-to-cross-dock-items.md)|    
|<span data-ttu-id="93d11-120">Zboží zaskladnění přijato z nákupů, vratek, transferů nebo výrobního výstupu podle nakonfigurovaného zpracování skladu.</span><span class="sxs-lookup"><span data-stu-id="93d11-120">Put away items received from purchases, sales returns, transfers, or production output according to the configured warehouse process.</span></span>|[<span data-ttu-id="93d11-121">Zaskladnění zboží</span><span class="sxs-lookup"><span data-stu-id="93d11-121">Putting Items Away</span></span>](warehouse-put-away-items.md)|
|<span data-ttu-id="93d11-122">Přesuňte zboží mezi přihrádkami ve skladu.</span><span class="sxs-lookup"><span data-stu-id="93d11-122">Move items between bins in the warehouse.</span></span>|[<span data-ttu-id="93d11-123">Přesun zboží</span><span class="sxs-lookup"><span data-stu-id="93d11-123">Moving Items</span></span>](warehouse-move-items.md)|
|<span data-ttu-id="93d11-124">Vyskladněte zboží pro dodávku, transfer, potřebu na montáži nebo ve výrobě.</span><span class="sxs-lookup"><span data-stu-id="93d11-124">Pick items to be shipped, transferred, or consumed in assembly or production, according to the configured warehouse process.</span></span>|[<span data-ttu-id="93d11-125">Vyskladnění zboží</span><span class="sxs-lookup"><span data-stu-id="93d11-125">Picking Items</span></span>](warehouse-pick-items.md)|
|<span data-ttu-id="93d11-126">Zaznamenávejte dodávky zboží ve skladových lokacích buď jen s prodejní objednávkou v jednoduchých nastaveních lokací, nebo se skladovou dodávkou v případě polo nebo plno automatizovaného zpracování skladu v dané lokaci.</span><span class="sxs-lookup"><span data-stu-id="93d11-126">Record the shipment of items from warehouse locations, either with a sales order only, in simple location setups, or with a warehouse shipment, in case of semi or fully automated warehouse processes at the location.</span></span>|[<span data-ttu-id="93d11-127">Návod: Dodání zboží</span><span class="sxs-lookup"><span data-stu-id="93d11-127">How to: Ship Items</span></span>](warehouse-how-ship-items.md)|  

## <a name="see-also"></a><span data-ttu-id="93d11-128">Viz také</span><span class="sxs-lookup"><span data-stu-id="93d11-128">See Also</span></span>  
 [<span data-ttu-id="93d11-129">Sklady</span><span class="sxs-lookup"><span data-stu-id="93d11-129">Inventory</span></span>](inventory-manage-inventory.md)  
 <span data-ttu-id="93d11-130">[Nastavení správy skladu](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="93d11-130">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
 <span data-ttu-id="93d11-131">[Správa montáže](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="93d11-131">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="93d11-132">Detaily návrhu: Správa skladu</span><span class="sxs-lookup"><span data-stu-id="93d11-132">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
 <span data-ttu-id="93d11-133">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="93d11-133">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

