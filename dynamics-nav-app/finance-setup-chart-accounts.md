---
title: "Nastavení nebo změna účtové osnovy"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 2a2f1f2ec3ac5bdd935ec19c11d74e16bdee7686
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="set-up-or-change-the-chart-of-accounts"></a><span data-ttu-id="15840-102">Nastavení nebo změna účtové osnovy</span><span class="sxs-lookup"><span data-stu-id="15840-102">Set Up or Change the Chart of Accounts</span></span>
<span data-ttu-id="15840-103">Účtová osnova ukazuje účet hlavní knihy, který ukládá vaše finanční data.</span><span class="sxs-lookup"><span data-stu-id="15840-103">The chart of accounts shows the ledger accounts that store your financial data.</span></span> <span data-ttu-id="15840-104">Dynamics NAV zahrnuje standardní účtovou osnovu, která je připravena podpořit váš obchod.</span><span class="sxs-lookup"><span data-stu-id="15840-104">Dynamics NAV includes a standard chart of accounts that is ready to support your business.</span></span>
<span data-ttu-id="15840-105">Avšak můžete měnit výchozí účty a přidávat nové.</span><span class="sxs-lookup"><span data-stu-id="15840-105">However, you can change the default accounts, and you can add new accounts.</span></span>  

## <a name="adding-or-changing-accounts"></a><span data-ttu-id="15840-106">Přidání nebo změna účtů</span><span class="sxs-lookup"><span data-stu-id="15840-106">Adding or Changing Accounts</span></span>
<span data-ttu-id="15840-107">Z účtové osnovy můžete otevřít každý finanční účet a přidat nebo změnit nastavení.</span><span class="sxs-lookup"><span data-stu-id="15840-107">From the chart of accounts, you can open each G/L account and add or change settings.</span></span>

<span data-ttu-id="15840-108">**Poznámka**: Můžete smazat účet hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="15840-108">**Note**: You can delete a general ledger account.</span></span> <span data-ttu-id="15840-109">Avšak než jej smažete, musí platit následující:</span><span class="sxs-lookup"><span data-stu-id="15840-109">However, before you delete it, the following must be true:</span></span>  
- <span data-ttu-id="15840-110">Zůstatek na účtu musí být nula.</span><span class="sxs-lookup"><span data-stu-id="15840-110">The balance on the account must be zero.</span></span>  
- <span data-ttu-id="15840-111">Pole **Povolit odstranění finančního účtu před** musí být nastaveno v okně **Nastavení financí** a účet nesmí mít položky toho data či po něm.</span><span class="sxs-lookup"><span data-stu-id="15840-111">The **Allow G/L Acc. Deletion Before** field must be set in the **General Ledger Setup** window, and the account must not have ledger entries on or after that date.</span></span>  
- <span data-ttu-id="15840-112">Pokud pole **Kontrolovat použití fin. účtu** v okně **Nastavení financí** je vybráno, pak účet nesmí být využíván v žádné z účtovacích skupin nebo účtovacího nastavení.</span><span class="sxs-lookup"><span data-stu-id="15840-112">If the **Check G/L Account Usage** field in the **General Ledger Setup** window is selected, then the account must not be used in any posting groups or posting setup.</span></span>  

<span data-ttu-id="15840-113">Dynamics NAV bude předcházet tomu, abyste si vymazali účet hlavní knihy, který ukládá potřebné data v účtové osnově.</span><span class="sxs-lookup"><span data-stu-id="15840-113">Dynamics NAV will prevent you from deleting a general ledger account that stores data that is needed in the chart of accounts.</span></span>  

##<a name="see-also"></a><span data-ttu-id="15840-114">Viz také</span><span class="sxs-lookup"><span data-stu-id="15840-114">See Also</span></span>  
[<span data-ttu-id="15840-115">Hlavní kniha a Účetní osnova</span><span class="sxs-lookup"><span data-stu-id="15840-115">The General Ledger and the Chart of Accounts</span></span>](finance-setup-general-ledger.md)  
[<span data-ttu-id="15840-116">Spravovat bankovní účty.</span><span class="sxs-lookup"><span data-stu-id="15840-116">Manage Bank Accounts</span></span>](bank-manage-bank-accounts.md)  
[<span data-ttu-id="15840-117">Dimenze</span><span class="sxs-lookup"><span data-stu-id="15840-117">Dimensions</span></span>](finance-setup-dimensions.md)  
[<span data-ttu-id="15840-118">Návod: Práce s GIFI kódy v Kanadě</span><span class="sxs-lookup"><span data-stu-id="15840-118">How to: Work With GIFI Codes in Canada</span></span>](ca-finance-setup-work-GiFI-codes.md)

