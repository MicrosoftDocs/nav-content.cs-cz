---
title: "Návod: Import mzdových transakcí"
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: d5e70a0a1659c7facdeec3f0971eda43ff8a03cc
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-import-payroll-transactions"></a><span data-ttu-id="5b8db-102">Návod: Import mzdových transakcí</span><span class="sxs-lookup"><span data-stu-id="5b8db-102">How to: Import Payroll Transactions</span></span>
<span data-ttu-id="5b8db-103">Na účet pro platby výplat a související transakce musíte importovat a zaúčtovat finanční transakce vytvořené vašim mzdovým poskytovatelem do hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="5b8db-103">To account for salary payments and related transactions, you must import and post financial transactions made by your payroll provider to the general ledger.</span></span> <span data-ttu-id="5b8db-104">Chcete-li to provést, nejprve importujte csv</span><span class="sxs-lookup"><span data-stu-id="5b8db-104">To do this, you first import a csv.</span></span> <span data-ttu-id="5b8db-105">soubor, který jste obdrželi od poskytovatele mezd do okna **Finanční deníky**.</span><span class="sxs-lookup"><span data-stu-id="5b8db-105">file that you receive from the payroll provider into the **General Journal** window.</span></span> <span data-ttu-id="5b8db-106">Pak namapujete externí účty v mzdovém souboru k souvisejícím finančním účtů.</span><span class="sxs-lookup"><span data-stu-id="5b8db-106">Then you map the external accounts in the payroll file to the relevant G/L accounts.</span></span> <span data-ttu-id="5b8db-107">Nakonec zaúčtujete mzdové transakce podle mapování účtu.</span><span class="sxs-lookup"><span data-stu-id="5b8db-107">Lastly, you post the payroll transactions according to the account mapping.</span></span>

## <a name="to-import-a-payroll-file"></a><span data-ttu-id="5b8db-108">Import mzdového souboru</span><span class="sxs-lookup"><span data-stu-id="5b8db-108">To import a payroll file</span></span>
1. <span data-ttu-id="5b8db-109">V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Finanční deníky** a pak zvolte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="5b8db-109">In the top right corner, choose the **Search for Page or Report** icon, enter **General Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="5b8db-110">V relevantní dávce finančního deníku vyberte akci **Importovat mzdové transakce**</span><span class="sxs-lookup"><span data-stu-id="5b8db-110">In the relevant general journal batch, choose the **Import Payroll Transactions** action.</span></span>
3. <span data-ttu-id="5b8db-111">V okně **Importovat** vyberte relevantní mzdový soubor a pak zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="5b8db-111">In the **Import** window, select the relevant payroll file, and then choose the **OK** button.</span></span> <span data-ttu-id="5b8db-112">Soubor musí být typu CSV.</span><span class="sxs-lookup"><span data-stu-id="5b8db-112">The file must be in CSV format.</span></span> 
4. <span data-ttu-id="5b8db-113">Sledujte kroky v okně **Importovat mzdové transakce** k importování účtů transakcí a map, pak zvolte tlačítko **Dokončit**.</span><span class="sxs-lookup"><span data-stu-id="5b8db-113">Follow the steps in the **Import Payroll Transactions** window to import transactions and map accounts, and then choose the **Finish** button.</span></span>

    <span data-ttu-id="5b8db-114">Finanční deník je vyplněn řádky reprezentujícími transakce, které obsahuje mzdový soubor a s odpovídajícími účty ve sloupci **Finanční účet**.</span><span class="sxs-lookup"><span data-stu-id="5b8db-114">The general journal is filled with lines representing the transactions that the payroll file contains and with the relevant accounts in the **G/L Account** column.</span></span>
4. <span data-ttu-id="5b8db-115">Upravte nebo zaúčtujte řádky deníku pro kteroukoli jinou transakci financí.</span><span class="sxs-lookup"><span data-stu-id="5b8db-115">Edit or post the journal lines as for any other general ledger transactions.</span></span> <span data-ttu-id="5b8db-116">Další informace naleznete v tématu [Návod: Práce s finančními deníky](ui-work-general-journals.md).</span><span class="sxs-lookup"><span data-stu-id="5b8db-116">For more information, see [How to: Work With General Journals](ui-work-general-journals.md).</span></span>   

## <a name="see-also"></a><span data-ttu-id="5b8db-117">Viz také</span><span class="sxs-lookup"><span data-stu-id="5b8db-117">See Also</span></span>
[<span data-ttu-id="5b8db-118">Finance</span><span class="sxs-lookup"><span data-stu-id="5b8db-118">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="5b8db-119">Návod: Práce s finančními deníky.</span><span class="sxs-lookup"><span data-stu-id="5b8db-119">How to: Work With General Journals</span></span>](ui-work-general-journals.md)  

