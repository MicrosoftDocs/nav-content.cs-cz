---
title: "Správa bankovních účtů"
description: "Musíte pravidelně odsouhlasit bankovní položky v Dynamics NAV se souvisejícími bankovními transakcemi na bankovních účtech."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reconcile
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 7306b71cc42142d3b1452da610ff69085a66917f
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="managing-bank-accounts"></a><span data-ttu-id="7f8a1-103">Správa bankovních účtů</span><span class="sxs-lookup"><span data-stu-id="7f8a1-103">Managing Bank Accounts</span></span>
<span data-ttu-id="7f8a1-104">V pravidelných intervalech musíte odsouhlasit bankovní položky v [!INCLUDE[d365fin](includes/d365fin_md.md)] se souvisejícími bankovními transakcemi na bankovních účtech u vaší banky a pak musíte zaúčtovat zůstatek na vašem bankovním účtu.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-104">At regular intervals, you must reconcile your bank ledger entries in [!INCLUDE[d365fin](includes/d365fin_md.md)] with the related bank transactions in bank accounts at your bank, and then post the balance to your bank account.</span></span> <span data-ttu-id="7f8a1-105">Tuto úlohu můžete provést jako součást zpracování plateb uvedených v bankovním výpisu v **Deník odsouhlasení plateb**.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-105">You can perform this task either as part of processing the payments represented on a bank statement in the **Payment Reconciliation Journal**.</span></span> <span data-ttu-id="7f8a1-106">Případně můžete úlohu provádět odděleně od zpracování plateb v **Odsouhlasení bank. účtů**, které podporuje kontrolu položek knihy.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-106">Alternatively, you can perform the task separately from payment processing, in the **Bank Acc. Reconciliation** window, which supports check ledger entries.</span></span> <span data-ttu-id="7f8a1-107">V obou případech vyplníte okna importováním bankovního výpisu do [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="7f8a1-107">In both cases, you fill in the windows by importing the bank statement into [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>

<span data-ttu-id="7f8a1-108">Někdy je třeba převést částky mezi bankovním účtem v [!INCLUDE[d365fin](includes/d365fin_md.md)] tak, aby odrážely převody ve vaší bance.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-108">Sometimes, you need to transfer amounts between bank account in [!INCLUDE[d365fin](includes/d365fin_md.md)] to reflect transfers at your bank.</span></span> <span data-ttu-id="7f8a1-109">Tento úkol provedete v okně **Finanční deník** různými způsoby v závislosti na měně finančních prostředků.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-109">You perform this task in the **General Journal** window, in different ways depending on the currency of the funds.</span></span>

<span data-ttu-id="7f8a1-110">Než budete moci spravovat bankovní účty, musíte nastavit každý bankovní účet jako kartu bankovního účtu.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-110">Before you can manage bank accounts, you must set each bank account up as a bank account card.</span></span> <span data-ttu-id="7f8a1-111">Navíc musíte nastavit elektronické služby, které můžete použít pro import bankovních výpisů a export platebních souborů.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-111">In addition, you must set up electronic services that you may use for bank statement import and payment file export.</span></span> <span data-ttu-id="7f8a1-112">Další informace naleznete v tématu [Nastavení bankovních účtů](bank-setup-banking.md).</span><span class="sxs-lookup"><span data-stu-id="7f8a1-112">For more information, see [Set Up Bank Accounts](bank-setup-banking.md).</span></span>

<span data-ttu-id="7f8a1-113">Následující tabulka popisuje postup úkolů s odkazy na téma, která je popisují.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-113">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

| <span data-ttu-id="7f8a1-114">Viz</span><span class="sxs-lookup"><span data-stu-id="7f8a1-114">To</span></span> | <span data-ttu-id="7f8a1-115">také</span><span class="sxs-lookup"><span data-stu-id="7f8a1-115">See</span></span> |
| --- | --- |
| <span data-ttu-id="7f8a1-116">Odsouhlasení bankovních účtů v souvislosti se zpracováním plateb v okně **Deník odsouhlasení plateb**.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-116">Reconcile bank accounts in connection with payment processing in the **Payment Reconciliation Journal** window.</span></span> |[<span data-ttu-id="7f8a1-117">Automatické vyrovnání plateb a odsouhlasení bankovních účtů</span><span class="sxs-lookup"><span data-stu-id="7f8a1-117">Applying Payments Automatically and Reconciling Bank Accounts</span></span>](receivables-apply-payments-auto-reconcile-bank-accounts.md) |
| <span data-ttu-id="7f8a1-118">Odsouhlasení bankovních účtů, včetně položek v knize jako samostatný úkol v okně **Odsouhlasení bank. účtů**.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-118">Reconcile bank accounts, including check ledger entries, as a separate task in the **Bank Acc. Reconciliation** window.</span></span> |[<span data-ttu-id="7f8a1-119">Návod: Odsouhlasení bankovních účtů zvlášť</span><span class="sxs-lookup"><span data-stu-id="7f8a1-119">How to: Reconcile Bank Accounts Separately</span></span>](bank-how-reconcile-bank-accounts-separately.md) |
| <span data-ttu-id="7f8a1-120">Zaúčtování převodu mezi bankovními účty ve stejné měně nebo v různých měnách.</span><span class="sxs-lookup"><span data-stu-id="7f8a1-120">Post transfers between bank accounts in the same currency or in different currencies.</span></span> |[<span data-ttu-id="7f8a1-121">Návod: Převod bankovních prostředků</span><span class="sxs-lookup"><span data-stu-id="7f8a1-121">How to: Transfer Bank Funds</span></span>](bank-how-transfer-bank-funds.md) |

## <a name="see-also"></a><span data-ttu-id="7f8a1-122">Viz také</span><span class="sxs-lookup"><span data-stu-id="7f8a1-122">See Also</span></span>
[<span data-ttu-id="7f8a1-123">Nastavení bankovnictví</span><span class="sxs-lookup"><span data-stu-id="7f8a1-123">Setting Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="7f8a1-124">Správa pohledávek</span><span class="sxs-lookup"><span data-stu-id="7f8a1-124">Managing Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="7f8a1-125">[Správa závazků](payables-manage-payables.md)  </span><span class="sxs-lookup"><span data-stu-id="7f8a1-125">[Managing Payables](payables-manage-payables.md)  </span></span>  
<span data-ttu-id="7f8a1-126">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="7f8a1-126">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
[<span data-ttu-id="7f8a1-127">Obecné obchodní funkce</span><span class="sxs-lookup"><span data-stu-id="7f8a1-127">General Business Functionality</span></span>](ui-across-business-areas.md)  

