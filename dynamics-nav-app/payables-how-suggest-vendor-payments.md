---
title: "Návod: Návrh platby dodavatele"
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
ms.openlocfilehash: 3ede5942798e34fd0e4b3ab8cc48ca94eed3d1a4
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-suggest-vendor-payments"></a><span data-ttu-id="8eeb8-102">Návod: Návrh platby dodavatele</span><span class="sxs-lookup"><span data-stu-id="8eeb8-102">How to: Suggest Vendor Payments</span></span>
<span data-ttu-id="8eeb8-103">V okně **Deníky plateb** můžete pomocí funkce navrhnout platební řádky podle vašich nastavení, jako jsou platby, které jsou brzy splatné, nebo platby, u kterých je k dispozici skonto sleva.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-103">In the **Payment Journal** window, you can use a function to suggest payment lines according to your settings, such as payments that are due soon or payments where a payment discount is available.</span></span>

<span data-ttu-id="8eeb8-104">Chcete-li plně využít funkce Navrhnout platby dodavateli, musíte nejdříve upřednostnit dodavatele.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-104">To benefit fully from the Suggest Vendor Payments function, you must first prioritize your vendors.</span></span> <span data-ttu-id="8eeb8-105">Pro další informace viz [Návod: Určení priority dodavatelů](purchasing-how-prioritize-vendors.md).</span><span class="sxs-lookup"><span data-stu-id="8eeb8-105">For more information, see [How to: Prioritize Vendors](purchasing-how-prioritize-vendors.md).</span></span>

<span data-ttu-id="8eeb8-106">Položky dodavatele, které nejsou označeny jako **Vyčkat** nejsou zahrnuty do dávkové úlohy.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-106">Vendor entries that are not marked **On Hold** are not included in the batch job.</span></span>  

<span data-ttu-id="8eeb8-107">**Důležité**: Chcete-li využívat skonto slev a zadáte dostupnou částku, bude částka použita nejprve pro položky po splatnosti prioritních dodavatelů v pořadí priority, pak pro položky po splatnosti dodavatelů, kteří nemají prioritu, a nakonec pro otevřeného položky dodavatelů, kde je nárok na skonto slevy v pořadí podle čísla dodavatele.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-107">**Important**: If you want to take advantage of payment discounts and have entered an available amount, the amount will be used for prioritized overdue vendor entries first in order of priority, and then for overdue vendor entries that are not prioritized, and finally for open vendor entries that qualify for payment discounts in order of vendor number.</span></span>

## <a name="to-use-the-suggest-vendor-payments-function"></a><span data-ttu-id="8eeb8-108">Použití funkce Návrh platby dodavateli</span><span class="sxs-lookup"><span data-stu-id="8eeb8-108">To use the Suggest Vendor Payments function</span></span>
1. <span data-ttu-id="8eeb8-109">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky plateb** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-109">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="8eeb8-110">Otevřete příslušný deník a poté vyberte akci **Navrhnout platby dodavateli**.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-110">Open the relevant journal, and then choose the **Suggest Vendor Payments** action.</span></span>
3. <span data-ttu-id="8eeb8-111">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="8eeb8-112">Vyberte pole a přečtěte si krátký popis pole nebo zvolte odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-112">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="8eeb8-113">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-113">Choose the **OK** button.</span></span>

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a><span data-ttu-id="8eeb8-114">Vložení data splatnosti jako data zaúčtování do řádků deníku plateb</span><span class="sxs-lookup"><span data-stu-id="8eeb8-114">To insert the due date as posting date on payment journal lines</span></span>
<span data-ttu-id="8eeb8-115">Když použijete dávkovou úlohu **Navrhnout platby dodavateli** pro vytvoření platebních řádků pro dodavatele, můžete vyplnit dvě zvláštní pole, abyste se ujistili, že generované řádky používají datum splatnosti pro výpočet data zaúčtování.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-115">When you use the **Suggest Vendor Payments** batch job to create payment lines for your vendors, you can fill two special fields to make sure that the generated lines use the due date to calculate the posting date.</span></span> <span data-ttu-id="8eeb8-116">Tato pole jsou **Vypočítat zúčtovací datum z datumu splatnosti vyrovnání dokladu** a **Posun datumu splatnosti vyrovnání dokladu.**.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-116">These fields are **Calculate Posting Date from Applies-to-Doc Due Date** and **Applies-to-Doc Due Date Offset**.</span></span>

<span data-ttu-id="8eeb8-117">**Důležité**: Nemůžete použít pole **Vypočítat zúčtovací datum z data splatnosti vyrovnání dokladu** spolu s polem **Vyhledat skonto** nebo s polem **Dodavatel na jeden řádek**.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-117">**Important**: You cannot use the **Calculate Posting Date from Applies-to-Doc Due Date** field together with the **Find Payment Discounts** field or the **Summarize per Vendor** field.</span></span> <span data-ttu-id="8eeb8-118">Důvodem je to, že pokud je datum zaúčtování založeno na datu splatnosti, určitá skonto sleva se nemusí vypočítat správně, protože datum zaúčtování by mohlo nastat po datu skonto slevy.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-118">The reason is that if the posting date is based on the due date, then some payment discount may not be calculated correctly, because the posting date could occur after the payment discount date.</span></span>
<span data-ttu-id="8eeb8-119">Také, pokud se vypočítané datum zaúčtování vyskytne v minulosti, datum zaúčtování bude změněno na pracovní datum a zobrazí se varování.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-119">Also, if the calculated posting date occurs in the past, then the posting date will be moved up to the work date, and a warning is displayed.</span></span>

<span data-ttu-id="8eeb8-120">Případně můžete také ručně vytvořit platební řádky za použití data splatnosti pro výpočet data zaúčtování.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-120">Alternatively, you can also manually create payment lines using the due date to calculate the posting date.</span></span> <span data-ttu-id="8eeb8-121">Poté, co jste vyrovnali položky dodavatelů, můžete použít akci **Vypočítat zúčtovací datum**.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-121">After you have applied vendor ledger entries, you can use the **Calculate Posting Date** action.</span></span> <span data-ttu-id="8eeb8-122">Tím se aktualizuje datum zaúčtování na řádku deníku s datem splatnosti příslušné nákupní faktury.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-122">This will update the posting date on the journal line with the due date of the related purchase invoice.</span></span> <span data-ttu-id="8eeb8-123">Další informace naleznete v tématu: [Návod: Vyrovnání nákupní transakce ručně](payables-how-apply-purchase-transactions-manually.md).</span><span class="sxs-lookup"><span data-stu-id="8eeb8-123">For more information, see [How to: Apply Purchase Transactions Manually](payables-how-apply-purchase-transactions-manually.md).</span></span>  

<span data-ttu-id="8eeb8-124">**Poznámka**: Pokud je nákupní faktura po splatnosti, zúčtovací datum bude nastaveno na pracovní datum a font písma na řádku se změní na červenou barvu.</span><span class="sxs-lookup"><span data-stu-id="8eeb8-124">**Note**: If the purchase invoice is overdue, then the posting date will be set to the work date, and the font on the line will change to red color.</span></span>

## <a name="see-also"></a><span data-ttu-id="8eeb8-125">Viz také</span><span class="sxs-lookup"><span data-stu-id="8eeb8-125">See Also</span></span>
[<span data-ttu-id="8eeb8-126">Správa závazků</span><span class="sxs-lookup"><span data-stu-id="8eeb8-126">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="8eeb8-127">Provedení plateb</span><span class="sxs-lookup"><span data-stu-id="8eeb8-127">Make Payments</span></span>](payables-make-payments.md)  
[<span data-ttu-id="8eeb8-128">Práce s finančními deníky</span><span class="sxs-lookup"><span data-stu-id="8eeb8-128">Work with General Journals</span></span>](ui-work-general-journals.md)

