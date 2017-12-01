---
title: "Nastavení účetní osnovy"
description: "Změňte výchozí účty v účetní osnově (COA) a můžete přidat nové účty."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: COA, cha of acc
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 41e0af4aa5ca7e8309d9c61457998933ef4433d8
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="setting-up-or-changing-the-chart-of-accounts"></a><span data-ttu-id="0ce54-103">Nastavení nebo změna účetní osnovy</span><span class="sxs-lookup"><span data-stu-id="0ce54-103">Setting Up or Changing the Chart of Accounts</span></span>
<span data-ttu-id="0ce54-104">Účetní osnova ukazuje účet hlavní knihy, který ukládá vaše finanční data.</span><span class="sxs-lookup"><span data-stu-id="0ce54-104">The chart of accounts shows the ledger accounts that store your financial data.</span></span> [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]<span data-ttu-id="0ce54-105"> zahrnuje standardní účetní osnovu, která je připravena podpořit váš obchod.</span><span class="sxs-lookup"><span data-stu-id="0ce54-105"> includes a standard chart of accounts that is ready to support your business.</span></span>
<span data-ttu-id="0ce54-106">Avšak můžete měnit výchozí účty a přidávat nové.</span><span class="sxs-lookup"><span data-stu-id="0ce54-106">However, you can change the default accounts, and you can add new accounts.</span></span>  

## <a name="adding-or-changing-accounts"></a><span data-ttu-id="0ce54-107">Přidání nebo změna účtů</span><span class="sxs-lookup"><span data-stu-id="0ce54-107">Adding or Changing Accounts</span></span>
<span data-ttu-id="0ce54-108">Z účtové osnovy můžete otevřít každý finanční účet a přidat nebo změnit nastavení.</span><span class="sxs-lookup"><span data-stu-id="0ce54-108">From the chart of accounts, you can open each G/L account and add or change settings.</span></span>

> [!NOTE]  
>   <span data-ttu-id="0ce54-109">Můžete smazat účet hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="0ce54-109">You can delete a general ledger account.</span></span> <span data-ttu-id="0ce54-110">Avšak než jej smažete, musí platit následující:</span><span class="sxs-lookup"><span data-stu-id="0ce54-110">However, before you delete it, the following must be true:</span></span>  

* <span data-ttu-id="0ce54-111">Zůstatek na účtu musí být nula.</span><span class="sxs-lookup"><span data-stu-id="0ce54-111">The balance on the account must be zero.</span></span>  
* <span data-ttu-id="0ce54-112">Pole **Povolit odstranění finančního účtu před** musí být nastaveno v okně **Nastavení financí** a účet nesmí mít položky toho data či po něm.</span><span class="sxs-lookup"><span data-stu-id="0ce54-112">The **Allow G/L Acc. Deletion Before** field must be set in the **General Ledger Setup** window, and the account must not have ledger entries on or after that date.</span></span>  
* <span data-ttu-id="0ce54-113">Pokud pole **Kontrolovat použití fin.účtu** v okně **Nastavení financí** je vybráno, pak účet nesmí být využíván v žádné z účtovacích skupin nebo účtovacího nastavení.</span><span class="sxs-lookup"><span data-stu-id="0ce54-113">If the **Check G/L Account Usage** field in the **General Ledger Setup** window is selected, then the account must not be used in any posting groups or posting setup.</span></span>  

[!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="0ce54-114"> bude předcházet tomu, abyste si vymazali finanční účty, které ukládají potřebné data v účetní osnově.</span><span class="sxs-lookup"><span data-stu-id="0ce54-114"> will prevent you from deleting a general ledger account that stores data that is needed in the chart of accounts.</span></span>  

## <a name="see-also"></a><span data-ttu-id="0ce54-115">Viz také</span><span class="sxs-lookup"><span data-stu-id="0ce54-115">See Also</span></span>
[<span data-ttu-id="0ce54-116">Hlavní kniha a Účetní osnova</span><span class="sxs-lookup"><span data-stu-id="0ce54-116">The General Ledger and the Chart of Accounts</span></span>](finance-general-ledger.md)  
[<span data-ttu-id="0ce54-117">Správa bankovních účtů</span><span class="sxs-lookup"><span data-stu-id="0ce54-117">Managing Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="0ce54-118">Práce s Dimenzemi</span><span class="sxs-lookup"><span data-stu-id="0ce54-118">Working with Dimensions</span></span>](finance-dimensions.md)  
[<span data-ttu-id="0ce54-119">Import z jiných finančních systémů</span><span class="sxs-lookup"><span data-stu-id="0ce54-119">Importing from Other Finance Systems</span></span>](upload-data.md)  
<span data-ttu-id="0ce54-120">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="0ce54-120">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  

## 

