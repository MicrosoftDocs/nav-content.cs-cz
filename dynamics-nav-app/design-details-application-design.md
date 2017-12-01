---
title: Podrobnosti designu
description: "Tento obsah obsahuje technické informace o komplexních funkcích v aplikaci [!INCLUDE[d365fin](includes/d365fin_md.md)]."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 9ae445d41c2f5b33d6d7f45910db0256f8782ca4
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="design-details"></a><span data-ttu-id="bd8d1-103">Podrobnosti designu</span><span class="sxs-lookup"><span data-stu-id="bd8d1-103">Design Details</span></span>
<span data-ttu-id="bd8d1-104">Tento obsah obsahuje technické informace o komplexních funkcích v aplikaci [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="bd8d1-104">This content contains detailed technical information about complex application features in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

 <span data-ttu-id="bd8d1-105">Obsah podrobnostií designu je zaměřen na implemntátory, vývojáře a super-uživatele, kteří potřebubí hlubší pohled do implementací, customizací nebo nastavení funkcí.</span><span class="sxs-lookup"><span data-stu-id="bd8d1-105">Design details content is aimed at implementers, developers, and super users who need deeper insight to implement, customize, or set up the features in question.</span></span>  

|<span data-ttu-id="bd8d1-106">**Viz**</span><span class="sxs-lookup"><span data-stu-id="bd8d1-106">**To**</span></span>|<span data-ttu-id="bd8d1-107">**také**</span><span class="sxs-lookup"><span data-stu-id="bd8d1-107">**See**</span></span>|  
|------------|-------------|  
|<span data-ttu-id="bd8d1-108">Naučte se o designu pro ukládání a účtování dimezí, včetně příkladů kódu jak migrovat a aktualizovat kódy dimenzí.</span><span class="sxs-lookup"><span data-stu-id="bd8d1-108">Learn about the design for storing and posting dimensions, including code examples on how to migrate and upgrade dimension code.</span></span>|[<span data-ttu-id="bd8d1-109">Podrobnosti designu: Položky sady dimenzí</span><span class="sxs-lookup"><span data-stu-id="bd8d1-109">Design Details: Dimension Set Entries</span></span>](design-details-dimension-set-entries.md)|  
|<span data-ttu-id="bd8d1-110">naučte se plánovat systémovou práci a jak upravit algoritmy pro plánování požadavků v rozdílném prostředí.</span><span class="sxs-lookup"><span data-stu-id="bd8d1-110">Learn how the planning system works and how to adjust the algorithms to meet planning requirements in different environments.</span></span>|[<span data-ttu-id="bd8d1-111">Podrobnosti designu: Plánování zásob</span><span class="sxs-lookup"><span data-stu-id="bd8d1-111">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)|  
|<span data-ttu-id="bd8d1-112">Pochopte mechanismus cenového enginu, jako například je metody ocenění a úprava nákladů a které účty jsou pro ně navrženy.</span><span class="sxs-lookup"><span data-stu-id="bd8d1-112">Understand mechanisms in the costing engine, such as costing method and cost adjustment, and which accounting principles they are designed for.</span></span>|[<span data-ttu-id="bd8d1-113">Podrobnosti designu: Zásoby a ocenění</span><span class="sxs-lookup"><span data-stu-id="bd8d1-113">Design Details: Inventory Costing</span></span>](design-details-inventory-costing.md)|  
|<span data-ttu-id="bd8d1-114">Další informace o základních principech pokročilých a základních funkcí skladu a o tom, jak se integrují s dalšími funkcemi dodavatelského řetězce.</span><span class="sxs-lookup"><span data-stu-id="bd8d1-114">Learn about central principles behind advanced and basic warehouse features and how they integrate with other supply chain features.</span></span>|[<span data-ttu-id="bd8d1-115">Podrobnosti designu: Správa Skladu</span><span class="sxs-lookup"><span data-stu-id="bd8d1-115">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)|  
|<span data-ttu-id="bd8d1-116">Naučte se o historickém a současném sledování položek a o tom, jak se integruje s rezervačním systémem, aby zahrnoval sériová čísla / čísla šarží ve výpočtech dostupnosti.</span><span class="sxs-lookup"><span data-stu-id="bd8d1-116">Learn about historic and the current design of item tracking functionality and how it integrates with the reservation system to include serial/lot numbers in availability calculations.</span></span>|[<span data-ttu-id="bd8d1-117">Podrobnosti designu: Sledování zboží</span><span class="sxs-lookup"><span data-stu-id="bd8d1-117">Design Details: Item Tracking</span></span>](design-details-item-tracking.md)|  
|<span data-ttu-id="bd8d1-118">Naučte se o funkcionalitě Účtování řádku finančního deníku včetně nedávného zjednodušení designu codenutiny 12.</span><span class="sxs-lookup"><span data-stu-id="bd8d1-118">Learn about the General Journal Posting Line feature, including recent simplifications to the design of codeunit 12.</span></span>|[<span data-ttu-id="bd8d1-119">Podrobnosti designu: Účtování řádku finančního deníku</span><span class="sxs-lookup"><span data-stu-id="bd8d1-119">Design Details: General Journal Post Line</span></span>](design-details-general-journal-post-line.md)|  

## <a name="see-also"></a><span data-ttu-id="bd8d1-120">Viz také</span><span class="sxs-lookup"><span data-stu-id="bd8d1-120">See Also</span></span>  
 <span data-ttu-id="bd8d1-121">[Plánování](production-planning.md) </span><span class="sxs-lookup"><span data-stu-id="bd8d1-121">[Planning](production-planning.md) </span></span>  
 <span data-ttu-id="bd8d1-122">[Správa nákladů zásob](finance-manage-inventory-costs.md) </span><span class="sxs-lookup"><span data-stu-id="bd8d1-122">[Managing Inventory Costs](finance-manage-inventory-costs.md) </span></span>  
 <span data-ttu-id="bd8d1-123">[Správa Skladu](warehouse-manage-warehouse.md) </span><span class="sxs-lookup"><span data-stu-id="bd8d1-123">[Warehouse Management](warehouse-manage-warehouse.md) </span></span>  
 [<span data-ttu-id="bd8d1-124">Nastavení komplexních aplikačních oblastí pomocí osvědčených postupů</span><span class="sxs-lookup"><span data-stu-id="bd8d1-124">Setting Up Complex Application Areas Using Best Practices</span></span>](set-up-complex-application-areas-using-best-practices.md)  
 <span data-ttu-id="bd8d1-125">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="bd8d1-125">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

