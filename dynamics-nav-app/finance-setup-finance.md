---
title: "Nastavení finančních procesů"
description: "Další informace o úkolech, jak nastavit finance ve vaší firmě tak, aby vyhovovaly všem vašim účetním, auditorským nebo účetním potřebám."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: accounting, auditing, bookkeeping
ms.date: 08/10/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: f3d7c01b079b6af60505fc232faf0d9c5ac393cd
ms.contentlocale: cs-cz
ms.lasthandoff: 10/23/2017

---
# <a name="setting-up-finance"></a><span data-ttu-id="609e3-103">Nastavení financí</span><span class="sxs-lookup"><span data-stu-id="609e3-103">Setting Up Finance</span></span>
<span data-ttu-id="609e3-104">K rychlému pokračování [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] obsahuje standardní konfigurace pro většinu finančních procesů.</span><span class="sxs-lookup"><span data-stu-id="609e3-104">To help you get going quickly, [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] includes standard configurations for most financial processes.</span></span> <span data-ttu-id="609e3-105">Pokud potřebujete změnit konfigurace tak, aby odpovídaly vaší firmě, jděte vpřed.</span><span class="sxs-lookup"><span data-stu-id="609e3-105">If you need to change the configurations to suit your business, go right ahead.</span></span> <span data-ttu-id="609e3-106">Například z domovské stránky můžete použít průvodce nastavením daní z prodeje pro vaši polohu.</span><span class="sxs-lookup"><span data-stu-id="609e3-106">For example, from the Home page you can use an assisted setup guide to set up sales tax rate for your location.</span></span>  

<span data-ttu-id="609e3-107">Nicméně, jsou tu některé věci, které potřebujete nastavit vlastnoručně.</span><span class="sxs-lookup"><span data-stu-id="609e3-107">However, there are some things you need to set up yourself.</span></span> <span data-ttu-id="609e3-108">Například pokud chcete použít dimenze jako základ pro business Intelligence.</span><span class="sxs-lookup"><span data-stu-id="609e3-108">For example, if you want to use dimensions as a basis for business intelligence.</span></span>  

<span data-ttu-id="609e3-109">Následující tabulka popisuje sekvenci úloh s odkazy na témata, která je popisují.</span><span class="sxs-lookup"><span data-stu-id="609e3-109">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>

| <span data-ttu-id="609e3-110">Viz</span><span class="sxs-lookup"><span data-stu-id="609e3-110">To</span></span> | <span data-ttu-id="609e3-111">také</span><span class="sxs-lookup"><span data-stu-id="609e3-111">See</span></span> |
| --- | --- |
| <span data-ttu-id="609e3-112">Zvolte jak platíte vašim dodavatelům.</span><span class="sxs-lookup"><span data-stu-id="609e3-112">Choose how you pay your vendors.</span></span> |[<span data-ttu-id="609e3-113">Definujte platební metody</span><span class="sxs-lookup"><span data-stu-id="609e3-113">Defining Payment Methods</span></span>](finance-payment-methods.md) |
| <span data-ttu-id="609e3-114">Určuje účtovací skupiny pro mapování entit jako jsou zákazníci, dodavatelé, zboží, zdroje a prodejní a nákupní doklady do finančních účtů.</span><span class="sxs-lookup"><span data-stu-id="609e3-114">Specify the posting groups that map entities like customers, vendors, items, resources, and sales and purchase documents to general ledger accounts.</span></span> |[<span data-ttu-id="609e3-115">Nastavení účetních skupin</span><span class="sxs-lookup"><span data-stu-id="609e3-115">Setting Up Posting Groups</span></span>](finance-posting-groups.md)|
|<span data-ttu-id="609e3-116">Nastavte toleranci, po kterou systém uzavírá faktury po zaplacení včetně slev, které plně nekryjí částku na faktuře.</span><span class="sxs-lookup"><span data-stu-id="609e3-116">Set up a tolerance by which the system closes an invoice even though the payment, including any discount, does not fully cover the amount on the invoice.</span></span>|[<span data-ttu-id="609e3-117">Návod: Práce s platebními tolerancemi a tolerance platebních slev</span><span class="sxs-lookup"><span data-stu-id="609e3-117">How to: Work with Payment Tolerances and Payment Discount Tolerances</span></span>](finance-payment-tolerance-and-payment-discount-tolerance.md)|
| <span data-ttu-id="609e3-118">Nastavení fiskálního období.</span><span class="sxs-lookup"><span data-stu-id="609e3-118">Set up fiscal periods.</span></span> |[<span data-ttu-id="609e3-119">Návod: Otevření nového fiskálního roku</span><span class="sxs-lookup"><span data-stu-id="609e3-119">How to: Open a New Fiscal Year</span></span>](finance-how-open-new-fiscal-year.md) |
| <span data-ttu-id="609e3-120">Určete způsob vykazování částek daně z přidané hodnoty, které jste shromáždili za prodej, daňovým úřadům.</span><span class="sxs-lookup"><span data-stu-id="609e3-120">Define how you report value-added tax amounts that you have collected for sales to the tax authorities.</span></span> |[<span data-ttu-id="609e3-121">Návod: Sestavy DPH daňovým úřadům</span><span class="sxs-lookup"><span data-stu-id="609e3-121">How To: Report VAT to Tax Authorities</span></span>](finance-how-report-vat.md)|
| <span data-ttu-id="609e3-122">Nastavení funkcí prodeje a nákupů tak, abyste mohli zpracovávat platby v cizích měnách.</span><span class="sxs-lookup"><span data-stu-id="609e3-122">Set your Sales and Purchases features up to handle payments in foreign currencies.</span></span>|[<span data-ttu-id="609e3-123">Návod: Umožnění vyrovnání položek v různých měnách</span><span class="sxs-lookup"><span data-stu-id="609e3-123">How to: Enable Application of Ledger Entries in Different Currencies</span></span>](finance-how-enable-application-ledger-entries-different-currencies.md)
| <span data-ttu-id="609e3-124">Přidání nových účtů k existující účetní osnově.</span><span class="sxs-lookup"><span data-stu-id="609e3-124">Add new accounts to the existing chart of accounts.</span></span> |[<span data-ttu-id="609e3-125">Nastavení účetní osnovy</span><span class="sxs-lookup"><span data-stu-id="609e3-125">Setting Up the Chart of Accounts</span></span>](finance-setup-chart-accounts.md) |
| <span data-ttu-id="609e3-126">Nastavení grafů business Intelligence (BI) k analýze cashflow.</span><span class="sxs-lookup"><span data-stu-id="609e3-126">Set up business intelligence (BI) charts to analyze cash flow.</span></span> |[<span data-ttu-id="609e3-127">Nastavení analýzy CashFlow</span><span class="sxs-lookup"><span data-stu-id="609e3-127">Setting Up Cash Flow Analysis</span></span>](finance-setup-cash-flow-analyses.md) |
|<span data-ttu-id="609e3-128">Povolit fakturaci zákazníka, který není v systému nastaven.</span><span class="sxs-lookup"><span data-stu-id="609e3-128">Enable invoicing of a customer who is not set up in the system.</span></span>|[<span data-ttu-id="609e3-129">Návod: Nastavení hotovosti zákazníka</span><span class="sxs-lookup"><span data-stu-id="609e3-129">How to: Set Up Cash Customers</span></span>](finance-how-to-set-up-cash-customers.md)|
| <span data-ttu-id="609e3-130">Nastavení sestav Intrastat a odeslání sestav úřadům</span><span class="sxs-lookup"><span data-stu-id="609e3-130">Set up Intrastat reporting, and submit the report to an authority</span></span> | [<span data-ttu-id="609e3-131">Návod: Nastavení a sestavy Intrastat</span><span class="sxs-lookup"><span data-stu-id="609e3-131">How to: Set Up and Report Intrastat</span></span>](finance-how-setup-report-intrastat.md)|

## <a name="see-also"></a><span data-ttu-id="609e3-132">Viz také</span><span class="sxs-lookup"><span data-stu-id="609e3-132">See Also</span></span>
[<span data-ttu-id="609e3-133">Finance</span><span class="sxs-lookup"><span data-stu-id="609e3-133">Finance</span></span>](finance.md)  
[<span data-ttu-id="609e3-134">Správa bankovních účtů</span><span class="sxs-lookup"><span data-stu-id="609e3-134">Managing Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="609e3-135">Práce s Dimenzemi</span><span class="sxs-lookup"><span data-stu-id="609e3-135">Working with Dimensions</span></span>](finance-dimensions.md)  
[<span data-ttu-id="609e3-136">Import obchodních dat z jiných finančních systémů</span><span class="sxs-lookup"><span data-stu-id="609e3-136">Importing Business Data from Other Finance Systems</span></span>](upload-data.md)  
[<span data-ttu-id="609e3-137">Analýza CashFlow ve vaší společnosti</span><span class="sxs-lookup"><span data-stu-id="609e3-137">Analyzing Cash Flow in Your Company</span></span>](finance-analyze-cash-flow.md)  
<span data-ttu-id="609e3-138">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="609e3-138">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

##

