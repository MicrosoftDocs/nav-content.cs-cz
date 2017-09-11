---
title: "Správa bankovních účtů"
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
ms.openlocfilehash: d97c3afba0e899768bda1b637c4f288db210d38c
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="manage-bank-accounts"></a><span data-ttu-id="a767b-102">Správa bankovních účtů</span><span class="sxs-lookup"><span data-stu-id="a767b-102">Manage Bank Accounts</span></span>
<span data-ttu-id="a767b-103">V pravidelných intervalech musíte odsouhlasit bankovní položky v Dynamics NAV se souvisejícími bankovními transakcemi na bankovních účtech u vaší banky a pak musíte zaúčtovat zůstatek na vašem bankovním účtu.</span><span class="sxs-lookup"><span data-stu-id="a767b-103">At regular intervals, you must reconcile your bank ledger entries in Dynamics NAV with the related bank transactions in bank accounts at your bank, and then post the balance to your bank account.</span></span> <span data-ttu-id="a767b-104">Tuto úlohu můžete provést jako součást zpracování plateb uvedených v bankovním výpisu v **Deník odsouhlasení plateb**.</span><span class="sxs-lookup"><span data-stu-id="a767b-104">You can perform this task either as part of processing the payments represented on a bank statement in the **Payment Reconciliation Journal**.</span></span> <span data-ttu-id="a767b-105">Případně můžete úlohu provádět odděleně od zpracování plateb v **Odsouhlasení bank. účtů**, které podporuje kontrolu položek knihy.</span><span class="sxs-lookup"><span data-stu-id="a767b-105">Alternatively, you can perform the task separately from payment processing, in the **Bank Acc. Reconciliation** window, which supports check ledger entries.</span></span> <span data-ttu-id="a767b-106">V obou případech vyplníte okna importováním bankovního výpisu do Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="a767b-106">In both cases, you fill the windows by importing the bank statement into Dynamics NAV.</span></span>

<span data-ttu-id="a767b-107">Někdy je třeba převést částky mezi bankovním účtem v Dynamics NAV tak, aby odrážely převody ve vaší bance.</span><span class="sxs-lookup"><span data-stu-id="a767b-107">Sometimes, you need to transfer amounts between bank account in Dynamics NAV to reflect transfers at your bank.</span></span> <span data-ttu-id="a767b-108">Tento úkol provedete v okně **Finanční deník** různými způsoby v závislosti na měně finančních prostředků.</span><span class="sxs-lookup"><span data-stu-id="a767b-108">You perform this task in the **General Journal** window, in different ways depending on the currency of the funds.</span></span>

<span data-ttu-id="a767b-109">Než budete moci spravovat bankovní účty, musíte nastavit každý bankovní účet jako kartu bankovního účtu.</span><span class="sxs-lookup"><span data-stu-id="a767b-109">Before you can manage bank accounts, you must set each bank account up as a bank account card.</span></span> <span data-ttu-id="a767b-110">Navíc musíte nastavit elektronické služby, které můžete použít pro import bankovních výpisů a export platebních souborů.</span><span class="sxs-lookup"><span data-stu-id="a767b-110">In addition, you must set up electronic services that you may use for bank statement import and payment file export.</span></span> <span data-ttu-id="a767b-111">Další informace naleznete v tématu [Nastavení bankovních účtů](bank-setup-banking.md).</span><span class="sxs-lookup"><span data-stu-id="a767b-111">For more information, see [Set Up Bank Accounts](bank-setup-banking.md).</span></span>

<span data-ttu-id="a767b-112">Následující tabulka popisuje postup úkolů s odkazy na téma, která je popisují.</span><span class="sxs-lookup"><span data-stu-id="a767b-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

|<span data-ttu-id="a767b-113">Popis</span><span class="sxs-lookup"><span data-stu-id="a767b-113">To</span></span> |<span data-ttu-id="a767b-114">Odkaz</span><span class="sxs-lookup"><span data-stu-id="a767b-114">See</span></span> |
|---|----|
|<span data-ttu-id="a767b-115">Odsouhlasení bankovních účtů v souvislosti se zpracováním plateb v okně **Deník odsouhlasení plateb**.</span><span class="sxs-lookup"><span data-stu-id="a767b-115">Reconcile bank accounts in connection with payment processing in the **Payment Reconciliation Journal** window.</span></span>|[<span data-ttu-id="a767b-116">Automatické vyrovnání plateb a odsouhlasení bankovních účtů</span><span class="sxs-lookup"><span data-stu-id="a767b-116">Apply Payments Automatically and Reconcile Bank Accounts</span></span>](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|<span data-ttu-id="a767b-117">Odsouhlasení bankovních účtů, včetně položek v knize jako samostatný úkol v okně **Odsouhlasení bank. účtů**.</span><span class="sxs-lookup"><span data-stu-id="a767b-117">Reconcile bank accounts, including check ledger entries, as a separate task in the **Bank Acc. Reconciliation** window.</span></span>|[<span data-ttu-id="a767b-118">Návod: Odsouhlasení bankovních účtů zvlášť</span><span class="sxs-lookup"><span data-stu-id="a767b-118">How to: Reconcile Bank Accounts Separately</span></span>](bank-how-reconcile-bank-accounts-separately.md)|
|<span data-ttu-id="a767b-119">Zaúčtování převodu mezi bankovními účty ve stejné měně nebo v různých měnách.</span><span class="sxs-lookup"><span data-stu-id="a767b-119">Post transfers between bank accounts in the same currency or in different currencies.</span></span>|[<span data-ttu-id="a767b-120">Návod: Převod bankovních prostředků</span><span class="sxs-lookup"><span data-stu-id="a767b-120">How to: Transfer Bank Funds</span></span>](bank-how-transfer-bank-funds.md)
## <a name="see-also"></a><span data-ttu-id="a767b-121">Viz také</span><span class="sxs-lookup"><span data-stu-id="a767b-121">See Also</span></span>  
[<span data-ttu-id="a767b-122">Nastavení bankovnictví</span><span class="sxs-lookup"><span data-stu-id="a767b-122">Set Up Banking</span></span>](bank-setup-banking.md)  
[<span data-ttu-id="a767b-123">Správa pohledávek</span><span class="sxs-lookup"><span data-stu-id="a767b-123">Manage Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="a767b-124">[Správa závazků](payables-manage-payables.md)  </span><span class="sxs-lookup"><span data-stu-id="a767b-124">[Manage Payables](payables-manage-payables.md)  </span></span>  
[<span data-ttu-id="a767b-125">Práce s Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="a767b-125">Work With Dynamics NAV</span></span>](ui-work-product.md)  
[<span data-ttu-id="a767b-126">Skrz obchodní oblasti</span><span class="sxs-lookup"><span data-stu-id="a767b-126">Across Business Areas</span></span>](ui-across-business-areas.md)

