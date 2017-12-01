---
title: "Vyrovnání položek v různých měnách"
description: "Můžete vyrovnat položky v různých měnách, například pokud prodáváte v jedné měně a obdržíte platbu v jiné."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: multiple currencies, payment, reconcile
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 2146d80becea5e0c52b04b85aab7890566443be9
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-enable-application-of-ledger-entries-in-different-currencies"></a><span data-ttu-id="0544f-103">Návod: Umožnění vyrovnání položek v různých měnách</span><span class="sxs-lookup"><span data-stu-id="0544f-103">How to: Enable Application of Ledger Entries in Different Currencies</span></span>
<span data-ttu-id="0544f-104">Pokud nakoupíte od dodavatele v jedné měně a odešlete v druhé měně, můžete použít platbu k nákupu.</span><span class="sxs-lookup"><span data-stu-id="0544f-104">If you purchase from a vendor in one currency and submit payment in another currency, you can apply the payment to the purchase.</span></span>

<span data-ttu-id="0544f-105">Když prodáte zákazníkovi v jedné měně a obdržíte platbu v druhé měně, můžete použít platbu k prodejní faktuře.</span><span class="sxs-lookup"><span data-stu-id="0544f-105">Likewise, if you sell to a customer in one currency and receive payment in another currency, you can apply the payment to the sales invoice.</span></span>

<span data-ttu-id="0544f-106">Následující procedura popisuje, jak nastavit položky dodavatele v okně **Nastavení nákupu a závazků**.</span><span class="sxs-lookup"><span data-stu-id="0544f-106">The following procedure describes how to set this up for vendor ledger entries in the **Purchases & Payables Setup** window.</span></span> <span data-ttu-id="0544f-107">Nastavení je podobné pro položky zákazníka v okně **Nastavení prodeje a pohledávek**.</span><span class="sxs-lookup"><span data-stu-id="0544f-107">The setup is similar for customer ledger entries in the **Sales & Receivables Setup** window.</span></span>

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies"></a><span data-ttu-id="0544f-108">Umožnění vyrovnání položek v různých měnách</span><span class="sxs-lookup"><span data-stu-id="0544f-108">To enable application of vendor ledger entries in different currencies</span></span>
1. <span data-ttu-id="0544f-109">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení nákupu a závazků** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="0544f-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="0544f-110">V poli **Vyrovnání mezi měnami** vyberte jednu z následujících možností.</span><span class="sxs-lookup"><span data-stu-id="0544f-110">In the **Appln. between Currencies** field, select one of the following options.</span></span>

| <span data-ttu-id="0544f-111">Volba</span><span class="sxs-lookup"><span data-stu-id="0544f-111">Option</span></span> | <span data-ttu-id="0544f-112">Popis</span><span class="sxs-lookup"><span data-stu-id="0544f-112">Description</span></span> |
| --- | --- |
| <span data-ttu-id="0544f-113">Žádný</span><span class="sxs-lookup"><span data-stu-id="0544f-113">None</span></span> |<span data-ttu-id="0544f-114">Vyrovnání mezi měnami není povoleno.</span><span class="sxs-lookup"><span data-stu-id="0544f-114">Application between currencies is not allowed.</span></span> |
| <span data-ttu-id="0544f-115">EMU</span><span class="sxs-lookup"><span data-stu-id="0544f-115">EMU</span></span> |<span data-ttu-id="0544f-116">Vyrovnání mezi EMU měny je povoleno.</span><span class="sxs-lookup"><span data-stu-id="0544f-116">Application between EMU currencies is allowed.</span></span> |
| <span data-ttu-id="0544f-117">Všechno</span><span class="sxs-lookup"><span data-stu-id="0544f-117">All</span></span> |<span data-ttu-id="0544f-118">Vyrovnání mezi všemi měnami je povoleno.</span><span class="sxs-lookup"><span data-stu-id="0544f-118">Application between all currencies is allowed.</span></span> |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences"></a><span data-ttu-id="0544f-119">Nastavení finančních účtů pro rozdílné zaokrouhlení měny</span><span class="sxs-lookup"><span data-stu-id="0544f-119">To set up G/L accounts for currency application rounding differences</span></span>  
<span data-ttu-id="0544f-120">Pokud vyrovnáte položky v různých měnách, musíte nastavit finanční účty, na které chcete zaúčtovat zaokrouhlené rozdíly.</span><span class="sxs-lookup"><span data-stu-id="0544f-120">If you apply entries in different currencies, you must set up the general ledger accounts to which you want to post rounding differences.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="0544f-121">Musíte nastavit finanční účty předtím, než dokončíte úkol.</span><span class="sxs-lookup"><span data-stu-id="0544f-121">You must set up the general ledger accounts before you complete the task.</span></span> <span data-ttu-id="0544f-122">Další informace naleznete v tématu [Porozumění Hlavní knize a účetní osnově](finance-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="0544f-122">For more information, see [Understanding the General Ledger and the Chart of Accounts](finance-general-ledger.md).</span></span>

1. <span data-ttu-id="0544f-123">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účto skupiny zákazníka** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="0544f-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customer Posting Groups**, and then choose the related link.</span></span>  
2. <span data-ttu-id="0544f-124">V polích **MD účet  zaok. vyrovnání měny** a **Dal účet zaok. vyrovnání měny** zadejte příslušné finanční účty k zaúčtování zaokrouhlených rozdílů.</span><span class="sxs-lookup"><span data-stu-id="0544f-124">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span></span>  
3. <span data-ttu-id="0544f-125">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účto skupiny dodavatele** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="0544f-125">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendor Posting Groups**, and then choose the related link.</span></span>  
4. <span data-ttu-id="0544f-126">V polích **MD účet zaok. vyrovnání měny** a **Dal účet zaok. vyrovnání měny** zadejte příslušné finanční účty k zaúčtování zaokrouhlených rozdílů.</span><span class="sxs-lookup"><span data-stu-id="0544f-126">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span></span>  

## <a name="see-also"></a><span data-ttu-id="0544f-127">Viz také</span><span class="sxs-lookup"><span data-stu-id="0544f-127">See Also</span></span>
[<span data-ttu-id="0544f-128">Správa závazků</span><span class="sxs-lookup"><span data-stu-id="0544f-128">Managing Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="0544f-129">Správa pohledávek</span><span class="sxs-lookup"><span data-stu-id="0544f-129">Managing Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="0544f-130">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="0544f-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

