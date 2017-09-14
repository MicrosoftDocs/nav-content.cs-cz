---
title: "Návod: Priorita dodavatelů"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: df14bab26aa0d52e7ad5215862fcef608ba5a7d7
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-prioritize-vendors"></a><span data-ttu-id="fa4bc-102">Návod: Priorita dodavatelů</span><span class="sxs-lookup"><span data-stu-id="fa4bc-102">How to: Prioritize Vendors</span></span>
<span data-ttu-id="fa4bc-103">[!INCLUDE[navnow](includes/navnow_md.md)] může navrhnout různé platby dodavatelům například platby, které budou brzy splatné nebo platby, u kterých je skonto k dispozici.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-103">Dynamics NAV can suggest various payments to vendors, for example, payments that will be due soon or payments where a discount is available.</span></span> <span data-ttu-id="fa4bc-104">Další informace naleznete v tématu [Návod: Navrhnutí plateb dodavatelů](payables-how-suggest-vendor-payments.md) .</span><span class="sxs-lookup"><span data-stu-id="fa4bc-104">for more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>

<span data-ttu-id="fa4bc-105">Nejprve musíte upřednostnit dodavatele přiřazením čísel.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-105">First, you must prioritize your vendors by assigning numbers to them.</span></span>

## <a name="to-prioritize-vendors"></a><span data-ttu-id="fa4bc-106">Prioritizace dodavatelů</span><span class="sxs-lookup"><span data-stu-id="fa4bc-106">To prioritize vendors</span></span>
1. <span data-ttu-id="fa4bc-107">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-107">In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.</span></span>
2. <span data-ttu-id="fa4bc-108">Vyberte příslušného dodavatele a poté zvolte **Úpravy**.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-108">Select the relevant vendor, and then choose **Edit**.</span></span>
3. <span data-ttu-id="fa4bc-109">Do pole **Priorita** zadejte číslo.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-109">In the **Priority** field, enter a number.</span></span>

<span data-ttu-id="fa4bc-110">[!INCLUDE[navnow](includes/navnow_md.md)] považuje nejnižší hodnotu, s výjimkou 0, za nejvyšší prioritu.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-110">Dynamics NAV considers the lowest number, except 0, to have the highest priority.</span></span> <span data-ttu-id="fa4bc-111">Takže například pokud používáte 1, 2 a 3, pak bude mít 1 nejvyšší prioritu.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-111">So, for example, if you use 1, 2, and 3, then 1 will have the highest priority.</span></span>

<span data-ttu-id="fa4bc-112">Pokud nechcete upřednostnit dodavatele, ponechte pole **Priorita** prázdné.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-112">If you do not want to prioritize a vendor, leave the **Priority** field blank.</span></span> <span data-ttu-id="fa4bc-113">Poté, pokud použijete funkci návrhu platby, dodavatel bude uveden po všech dodavatelích, kteří mají číslo priority.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-113">Then, if you use the payment suggestion feature, the vendor will be listed after all the vendors that have a priority number.</span></span> <span data-ttu-id="fa4bc-114">Můžete zadat tolik prioritních úrovní, kolik potřebujete.</span><span class="sxs-lookup"><span data-stu-id="fa4bc-114">You can enter as many priority levels as necessary.</span></span>

## <a name="see-also"></a><span data-ttu-id="fa4bc-115">Viz také</span><span class="sxs-lookup"><span data-stu-id="fa4bc-115">See Also</span></span>
[<span data-ttu-id="fa4bc-116">Nastavení nákupu</span><span class="sxs-lookup"><span data-stu-id="fa4bc-116">Set Up Purchasing</span></span>](purchasing-setup-purchasing.md)  
[<span data-ttu-id="fa4bc-117">Správa závazků</span><span class="sxs-lookup"><span data-stu-id="fa4bc-117">Manage Payables</span></span>](payables-manage-payables.md)

