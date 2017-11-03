---
title: "Použití funkce dávkové úlohy Návrh platby dodavateli"
description: "Můžete zadat nastavení plateb dodavatelů získat podněty a návrhy na platby, které jsou splatné dříve nebo pokud je k dispozici sleva"
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: vendor payment, creditor, debt, balance due, AP
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 99bec4a5cc06209d4e7cfc0e7d2736bfc6fe9e1e
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-suggest-vendor-payments"></a><span data-ttu-id="77294-103">Návody: Navrhnutí plateb dodavatele</span><span class="sxs-lookup"><span data-stu-id="77294-103">How to: Suggest Vendor Payments</span></span>
<span data-ttu-id="77294-104">V okně **Deník plateb**, můžete použít dávkové úlohy **Navrhnout platby dodavateli**k návrhu řádků deníku.</span><span class="sxs-lookup"><span data-stu-id="77294-104">In the **Payment Journal** window, you can use the **Suggest Vendor Payments** batch job to suggest payment lines.</span></span> <span data-ttu-id="77294-105">Na základě vašich nastavení jsou navrženy řádky pro platby, které jsou brzy splatné, nebo platby, u kterých je k dispozici sleva.</span><span class="sxs-lookup"><span data-stu-id="77294-105">Lines for things like payments that are due soon, or payments where a payment discount is available, are suggested based on your settings.</span></span>

<span data-ttu-id="77294-106">Chcete-li plně využít funkce na navrhnutí řádku, musíte nejdříve upřednostnit dodavatele.</span><span class="sxs-lookup"><span data-stu-id="77294-106">To benefit fully from suggested lines, you must first prioritize your vendors.</span></span> <span data-ttu-id="77294-107">Další informace naleznete v tématu [Návod: Určení priority dodavatelů.](purchasing-how-prioritize-vendors.md)</span><span class="sxs-lookup"><span data-stu-id="77294-107">For more information, see [How to: Prioritize Vendors](purchasing-how-prioritize-vendors.md).</span></span>  

<span data-ttu-id="77294-108">Položky dodavatele, které nejsou označeny jako **Vyčkat** nejsou zahrnuty.</span><span class="sxs-lookup"><span data-stu-id="77294-108">Vendor entries that are not **On Hold** are not included.</span></span>  

> [!IMPORTANT]  
>   <span data-ttu-id="77294-109">Chcete-li využít platební slevy a zadali dostupné množství, bude částka použita pro:</span><span class="sxs-lookup"><span data-stu-id="77294-109">If you want to take advantage of payment discounts, and have entered an available amount, the amount will be used for:</span></span>  

* <span data-ttu-id="77294-110">Na základě priority objednávky, budou prioritní položky dodavatele po splatnosti.</span><span class="sxs-lookup"><span data-stu-id="77294-110">Prioritized overdue vendor entries first in order of priority.</span></span>  
* <span data-ttu-id="77294-111">Položky dodavatelů, které nemají nastavenou prioritu.</span><span class="sxs-lookup"><span data-stu-id="77294-111">Overdue vendor entries that are not prioritized.</span></span>  
* <span data-ttu-id="77294-112">Otevřené položky dodavatele, které splňují podmínky pro platební slevy, uspořádané podle počtu dodavatelů.</span><span class="sxs-lookup"><span data-stu-id="77294-112">Open vendor entries that qualify for payment discounts, arranged by vendor number.</span></span>  

## <a name="to-use-the-suggest-vendor-payments-function"></a><span data-ttu-id="77294-113">Použití funkce Návrh platby dodavateli</span><span class="sxs-lookup"><span data-stu-id="77294-113">To use the Suggest Vendor Payments function</span></span>
1. <span data-ttu-id="77294-114">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky plateb** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="77294-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="77294-115">Otevřete příslušný deník a poté vyberte akci **Navrhnout platby dodavateli**.</span><span class="sxs-lookup"><span data-stu-id="77294-115">Open the relevant journal, and then choose the **Suggest Vendor Payments** action.</span></span>  
3. <span data-ttu-id="77294-116">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="77294-116">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
4. <span data-ttu-id="77294-117">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="77294-117">Choose the **OK** button.</span></span>  

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a><span data-ttu-id="77294-118">Vložení data splatnosti jako data zaúčtování do řádků deníku plateb</span><span class="sxs-lookup"><span data-stu-id="77294-118">To insert the due date as posting date on payment journal lines</span></span>
<span data-ttu-id="77294-119">Když použijete dávkovou úlohu **Navrhnout platby dodavateli** pro vytvoření platebních řádků pro dodavatele, můžete vyplnit dvě zvláštní pole, abyste se ujistili, že generované řádky používají datum splatnosti pro výpočet data zaúčtování.</span><span class="sxs-lookup"><span data-stu-id="77294-119">When you use the **Suggest Vendor Payments** batch job to create payment lines for your vendors, you can fill two special fields to make sure that the generated lines use the due date to calculate the posting date.</span></span> <span data-ttu-id="77294-120">Tato pole jsou **Vypočítat zúčtovací datum z datumu splatnosti vyrovnání dokladu** a **Posun datumu splatnosti vyrovnání dokladu.**.</span><span class="sxs-lookup"><span data-stu-id="77294-120">These fields are **Calculate Posting Date from Applies-to-Doc Due Date** and **Applies-to-Doc Due Date Offset**.</span></span>  

> [!IMPORTANT]  
>   <span data-ttu-id="77294-121">Nemůžete použít pole **Vypočítat zúčtovací datum z data splatnosti vyrovnání dokladu** spolu s polem **Vyhledat skonto** nebo s polem **Dodavatel na jeden řádek**.</span><span class="sxs-lookup"><span data-stu-id="77294-121">You cannot use the **Calculate Posting Date from Applies-to-Doc Due Date** field together with the **Find Payment Discounts** field or the **Summarize per Vendor** field.</span></span> <span data-ttu-id="77294-122">Důvodem je to, že pokud je datum zaúčtování založeno na datu splatnosti, určitá sleva se nemusí vypočítat správně, protože datum zaúčtování by mohlo nastat po datu slevy.</span><span class="sxs-lookup"><span data-stu-id="77294-122">If the posting date is based on the due date, some payment discounts may not calculate correctly because the posting date is after the payment discount date.</span></span>  

<span data-ttu-id="77294-123">Také, pokud se vypočítané datum zaúčtování vyskytne v minulosti, datum zaúčtování je změněno na pracovní datum a zobrazí se varování.</span><span class="sxs-lookup"><span data-stu-id="77294-123">Also, if the calculated posting date is in the past, then the posting date is moved up to the work date, and a warning is displayed.</span></span>  

<span data-ttu-id="77294-124">Případně můžete ručně vytvořit platební řádky za použití data splatnosti pro výpočet data zaúčtování.</span><span class="sxs-lookup"><span data-stu-id="77294-124">Alternatively, you can manually create payment lines using the due date to calculate the posting date.</span></span> <span data-ttu-id="77294-125">Poté co vyrovnáte položky dodavateli, můžete použít tlačítko **Výpočet zúčtovaího data** k aktualizaci zúčtovacího data na řádku deníku s datem splatnosti na příslušné nákupní faktuře.</span><span class="sxs-lookup"><span data-stu-id="77294-125">After you apply vendor ledger entries, you can use the **Calculate Posting Date** action to update the posting date on the journal line with the due date of the related purchase invoice.</span></span> <span data-ttu-id="77294-126">Další informace naleznete v tématu [Návod: Vyrovnání nákupní transakce ručně.](payables-how-apply-purchase-transactions-manually.md)</span><span class="sxs-lookup"><span data-stu-id="77294-126">For more information, see [How to: Apply Purchase Transactions Manually](payables-how-apply-purchase-transactions-manually.md).</span></span>  

> [!NOTE]  
>   <span data-ttu-id="77294-127">Pokud je nákupní faktura po splatnosti, zúčtovací datum bude nastaveno na pracovní datum a font písma na řádku se změní na červenou .</span><span class="sxs-lookup"><span data-stu-id="77294-127">If the purchase invoice is overdue, the posting date is set to the work date, and the font on the line becomes red.</span></span>  

## <a name="see-also"></a><span data-ttu-id="77294-128">Viz také</span><span class="sxs-lookup"><span data-stu-id="77294-128">See Also</span></span>
[<span data-ttu-id="77294-129">Správa závazků</span><span class="sxs-lookup"><span data-stu-id="77294-129">Managing Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="77294-130">Provedení plateb</span><span class="sxs-lookup"><span data-stu-id="77294-130">Making Payments</span></span>](payables-make-payments.md)  
[<span data-ttu-id="77294-131">Práce s finančními deníky</span><span class="sxs-lookup"><span data-stu-id="77294-131">Working with General Journals</span></span>](ui-work-general-journals.md)  
<span data-ttu-id="77294-132">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="77294-132">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

