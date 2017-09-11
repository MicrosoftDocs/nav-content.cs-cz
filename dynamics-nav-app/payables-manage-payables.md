---
title: "Správa závazků"
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
ms.openlocfilehash: 08f72aded5c8090dee9a790487fee1db4393220c
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="manage-payables"></a><span data-ttu-id="3168c-102">Správa závazků</span><span class="sxs-lookup"><span data-stu-id="3168c-102">Manage Payables</span></span>
<span data-ttu-id="3168c-103">Ústředním úkolem v oblasti správy plateb je zaplatit vašim dodavatelům.</span><span class="sxs-lookup"><span data-stu-id="3168c-103">A central task in managing accounts payable is to pay your vendors.</span></span> <span data-ttu-id="3168c-104">Funkce můžete použít k automatickému vyplnění okna **Deník plateb** s platebními řádky pro splatnost nákupních faktur.</span><span class="sxs-lookup"><span data-stu-id="3168c-104">You can use functions to automatically fill in the **Payment Journal** window with payments lines for due purchase invoices.</span></span> <span data-ttu-id="3168c-105">Chcete-li rychle provádět příslušné transakce s bankami, můžete exportovat několik řádků platebního deníku do souboru, který pak nahrajete do banky ke zpracování.</span><span class="sxs-lookup"><span data-stu-id="3168c-105">To quickly perform the involved bank transactions, you can export multiple payment journal lines to a file, which you then upload to your bank for processing.</span></span> <span data-ttu-id="3168c-106">Můžete také provádět platby šekem, včetně přenosu šeků jako elektronických plateb.</span><span class="sxs-lookup"><span data-stu-id="3168c-106">You can also make payments by check, including to transmit checks as electronic payments.</span></span>

<span data-ttu-id="3168c-107">Dalším typickým úkolem je uplatňovat odchozí platby na jejich související položky dodavatelů, a tím uzavřít související nákupní faktury nebo nákupní dobropisy jako zaplacené.</span><span class="sxs-lookup"><span data-stu-id="3168c-107">Another typical task is to apply outgoing payments to their related vendor ledger entries and thereby close the related purchase invoices or purchase credit memos as paid.</span></span> <span data-ttu-id="3168c-108">Tuto práci můžete provést v okně **Deník odsouhlasení plateb** importováním souboru výpisu z účtu, abyste mohli rychle zapsat platby v systému Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="3168c-108">You can perform this work in the **Payment Reconciliation Journal** window by importing a bank statement file to quickly register the payments in Dynamics NAV.</span></span> <span data-ttu-id="3168c-109">Funkce automatické aplikace uplatňuje platby na příslušné otevřené položky prodejce nebo zákazníka založené na datových shodách mezi textem platby a zadaných informacích.</span><span class="sxs-lookup"><span data-stu-id="3168c-109">An automatic application function applies the payments to their related open vendor or customer ledger entries based on a data matches between payment text and entry information.</span></span> <span data-ttu-id="3168c-110">Můžete použít různé funkce pro kontrolu a změnu automatických aplikací před tím, než zaúčtujete deník.</span><span class="sxs-lookup"><span data-stu-id="3168c-110">You can use various functionality to review and change automatic applications before you post the journal.</span></span> <span data-ttu-id="3168c-111">Při účtování deníku můžete uzavřít všechny otevřené položky bankovního účtu, které se vztahují k zaplaceným položkám.</span><span class="sxs-lookup"><span data-stu-id="3168c-111">You can choose to close any open bank account ledger entries related to the applied ledger entries when you post the journal.</span></span> <span data-ttu-id="3168c-112">To znamená, že bankovní účet je automaticky odsouhlasen po zaplacení všech plateb.</span><span class="sxs-lookup"><span data-stu-id="3168c-112">This means that the bank account is automatically reconciled when all payments are applied.</span></span>

<span data-ttu-id="3168c-113">Případně můžete odesílat platby ručně v okně **Deník plateb** nebo v související položkách dodavatele.</span><span class="sxs-lookup"><span data-stu-id="3168c-113">Alternatively, you can apply outgoing payments manually in the **Payment Journal** window or from the related vendor ledger entries.</span></span>

<span data-ttu-id="3168c-114">Následující tabulka popisuje sekvenci úloh v rámci závazků s odkazy na témata, které je popisují.</span><span class="sxs-lookup"><span data-stu-id="3168c-114">The following table describes a sequence of tasks within accounts payable, with links to the topics that describe them.</span></span>

|<span data-ttu-id="3168c-115">Popis</span><span class="sxs-lookup"><span data-stu-id="3168c-115">To</span></span> |<span data-ttu-id="3168c-116">Odkaz</span><span class="sxs-lookup"><span data-stu-id="3168c-116">See</span></span> |
|---|----|
|<span data-ttu-id="3168c-117">Vytvořte platby s předepsaným dodavatelem podle prioritních platebních slev a penále po splatnosti.</span><span class="sxs-lookup"><span data-stu-id="3168c-117">Generate due vendor payments prioritized according to payment discounts and overdue penalties.</span></span> <span data-ttu-id="3168c-118">Volitelně exportujte platby do bankovního souboru při účtování.</span><span class="sxs-lookup"><span data-stu-id="3168c-118">Optionally, export the payments to a bank file when posting.</span></span>|[<span data-ttu-id="3168c-119">Proveďte platby</span><span class="sxs-lookup"><span data-stu-id="3168c-119">Make Payments</span></span>](payables-make-payments.md)|
|<span data-ttu-id="3168c-120">Použít automaticky platby dodavatele na nezaplacené nákupní faktury importem souboru bankovního výpisu.</span><span class="sxs-lookup"><span data-stu-id="3168c-120">Apply vendor payments automatically to unpaid purchase invoices by importing a bank statement file.</span></span>|[<span data-ttu-id="3168c-121">Použití automatických plateb a odsouhlasení bankovních účtů</span><span class="sxs-lookup"><span data-stu-id="3168c-121">Apply Payments Automatically and Reconcile Bank Accounts</span></span>](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|<span data-ttu-id="3168c-122">Ručně přiřadit dodavatelské platby k nezaplaceným nákupním fakturám.</span><span class="sxs-lookup"><span data-stu-id="3168c-122">Apply vendor payments to unpaid purchase invoices manually.</span></span>|[<span data-ttu-id="3168c-123">Návod: Ručně uhradit dodavatelské platby</span><span class="sxs-lookup"><span data-stu-id="3168c-123">How to: Apply Vendor Payments Manually</span></span>](payables-how-apply-purchase-transactions-manually.md)|

## <a name="see-also"></a><span data-ttu-id="3168c-124">Viz také</span><span class="sxs-lookup"><span data-stu-id="3168c-124">See Also</span></span>
[<span data-ttu-id="3168c-125">Správa nákupu</span><span class="sxs-lookup"><span data-stu-id="3168c-125">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="3168c-126">Spravovat pohledávky</span><span class="sxs-lookup"><span data-stu-id="3168c-126">Manage Receivables</span></span>](receivables-manage-receivables.md)  
[<span data-ttu-id="3168c-127">Práce s Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="3168c-127">Work With Dynamics NAV</span></span>](ui-work-product.md)  
[<span data-ttu-id="3168c-128">V obchodních oblastech</span><span class="sxs-lookup"><span data-stu-id="3168c-128">Across Business Areas</span></span>](ui-across-business-areas.md)

