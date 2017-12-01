---
title: "Přiřazení úrovně priority dodavateli"
description: "Můžete přidělit čísla vašim dodavatelům, abyste je upřednostnili a usnadnili návrhy na platby v Dynamics NAV."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supplier, payment priority
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: f7e02a756c58067876ce8d02b3a0ae3661b2e496
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-prioritize-vendors"></a><span data-ttu-id="98eea-103">Návod: Prioritizace dodavatelů</span><span class="sxs-lookup"><span data-stu-id="98eea-103">How to: Prioritize Vendors</span></span>
[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="98eea-104"> může navrhnout různé platby dodavatelům například platby, které budou brzy splatné nebo platby, u kterých je skonto k dispozici.</span><span class="sxs-lookup"><span data-stu-id="98eea-104"> can suggest various payments to vendors, for example, payments that will be due soon or payments where a discount is available.</span></span> <span data-ttu-id="98eea-105">Další informace naleznete v tématu [Návod: Navrhnutí plateb dodavatelů ](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="98eea-105">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>

<span data-ttu-id="98eea-106">Nejprve musíte upřednostnit dodavatele přiřazením čísel.</span><span class="sxs-lookup"><span data-stu-id="98eea-106">First, you must prioritize your vendors by assigning numbers to them.</span></span>

## <a name="to-prioritize-vendors"></a><span data-ttu-id="98eea-107">Prioritizace dodavatelů</span><span class="sxs-lookup"><span data-stu-id="98eea-107">To prioritize vendors</span></span>
1. <span data-ttu-id="98eea-108">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dodavatelé** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="98eea-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="98eea-109">Vyberte příslušného dodavatele a poté zvolte **Úpravy**.</span><span class="sxs-lookup"><span data-stu-id="98eea-109">Select the relevant vendor, and then choose **Edit**.</span></span>
3. <span data-ttu-id="98eea-110">Do pole **Priorita** zadejte číslo.</span><span class="sxs-lookup"><span data-stu-id="98eea-110">In the **Priority** field, enter a number.</span></span>

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="98eea-111"> považuje nejnižší hodnotu, s výjimkou 0, za nejvyšší prioritu.</span><span class="sxs-lookup"><span data-stu-id="98eea-111"> considers the lowest number, except 0, to have the highest priority.</span></span> <span data-ttu-id="98eea-112">Takže například pokud používáte 1, 2 a 3, pak bude mít 1 nejvyšší prioritu.</span><span class="sxs-lookup"><span data-stu-id="98eea-112">So, for example, if you use 1, 2, and 3, then 1 will have the highest priority.</span></span>

<span data-ttu-id="98eea-113">Pokud nechcete upřednostnit dodavatele, ponechte pole **Priorita** prázdné.</span><span class="sxs-lookup"><span data-stu-id="98eea-113">If you do not want to prioritize a vendor, leave the **Priority** field blank.</span></span> <span data-ttu-id="98eea-114">Poté, pokud použijete funkci návrhu platby, dodavatel bude uveden po všech dodavatelích, kteří mají číslo priority.</span><span class="sxs-lookup"><span data-stu-id="98eea-114">Then, if you use the payment suggestion feature, the vendor will be listed after all the vendors that have a priority number.</span></span> <span data-ttu-id="98eea-115">Můžete zadat tolik prioritních úrovní, kolik potřebujete.</span><span class="sxs-lookup"><span data-stu-id="98eea-115">You can enter as many priority levels as necessary.</span></span>

## <a name="see-also"></a><span data-ttu-id="98eea-116">Viz také</span><span class="sxs-lookup"><span data-stu-id="98eea-116">See Also</span></span>
[<span data-ttu-id="98eea-117">Nastavení nákupu</span><span class="sxs-lookup"><span data-stu-id="98eea-117">Setting Up Purchasing</span></span>](purchasing-setup-purchasing.md)  
[<span data-ttu-id="98eea-118">Správa závazků</span><span class="sxs-lookup"><span data-stu-id="98eea-118">Managing Payables</span></span>](payables-manage-payables.md)  
<span data-ttu-id="98eea-119">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="98eea-119">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

