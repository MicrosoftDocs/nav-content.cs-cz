---
title: "Import mzdových transakcí"
description: "Ke správě platů importujte a zaúčtujte finanční transakce od svého poskytovatele mzdových plateb do hlavní knihy pomocí rozšíření o mzdy, jako jsou například Ceridian nebo Quickbooks."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: Ceridian, Quickbooks, salary
ms.date: 06/16/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 675a63c7862854ef3f8e2ca3d37dd3f2e290cf29
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-import-payroll-transactions"></a><span data-ttu-id="ec7e8-103">Návod: Import mzdových transakcí</span><span class="sxs-lookup"><span data-stu-id="ec7e8-103">How to: Import Payroll Transactions</span></span>
<span data-ttu-id="ec7e8-104">Na účet pro platby výplat a související transakce musíte importovat a zaúčtovat finanční transakce vytvořené vašim mzdovým poskytovatelem do hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-104">To account for salary payments and related transactions, you must import and post financial transactions made by your payroll provider to the general ledger.</span></span> <span data-ttu-id="ec7e8-105">Pokud chcete tohle udělat, nejdříve naimportujte soubor, který jste obdrželi od poskytovatele mezd do okna **Finanční deníky**.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-105">To do this, you first import a file that you receive from the payroll provider into the **General Journal** window.</span></span> <span data-ttu-id="ec7e8-106">Pak namapujete externí účty v mzdovém souboru k souvisejícím finančním účtů.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-106">Then you map the external accounts in the payroll file to the relevant G/L accounts.</span></span> <span data-ttu-id="ec7e8-107">Nakonec zaúčtujete mzdové transakce podle mapování účtu.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-107">Lastly, you post the payroll transactions according to the account mapping.</span></span>

> [!NOTE]  
>   <span data-ttu-id="ec7e8-108">K použití této funkcionality musí být nainstalováno a povoleno rozšíření pro import mzdy.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-108">To use this functionality, an extension for payroll import must be installed and enabled.</span></span> <span data-ttu-id="ec7e8-109">Ceridian Payroll a Quickbooks Payroll import souborů jsou předinstalovány v [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="ec7e8-109">The Ceridian Payroll and the Quickbooks Payroll File Import extensions are pre-installed in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="ec7e8-110">Další informace naleznete v tématu: [Přizpůsobení [!INCLUDE[d365fin](includes/d365fin_md.md)]  Pomocí rozšíření](ui-extensions.md).</span><span class="sxs-lookup"><span data-stu-id="ec7e8-110">For more information, see [Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions](ui-extensions.md).</span></span>

## <a name="to-import-a-payroll-file"></a><span data-ttu-id="ec7e8-111">Import mzdového souboru</span><span class="sxs-lookup"><span data-stu-id="ec7e8-111">To import a payroll file</span></span>
1. <span data-ttu-id="ec7e8-112">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **General Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="ec7e8-113">V relevantní dávce finančního deníku vyberte akci **Importovat mzdové transakce**.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-113">In the relevant general journal batch, choose the **Import Payroll Transactions** action.</span></span> <span data-ttu-id="ec7e8-114">Otevře se průvodce asistovaného nastavení.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-114">An assisted setup guide opens.</span></span>
3. <span data-ttu-id="ec7e8-115">Následujte kroky v okně **Import mzdových transakcí**.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-115">Follow the steps in the **Import Payroll Transactions** window.</span></span>

    > [!TIP]  
>   <span data-ttu-id="ec7e8-116">V kroku mapování externích záznamů o mzdách na vaše finanční účty, mapování, která vytvoříte, budou zapamatovány při příštím importu stejných záznamů.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-116">In the step about mapping the external payroll records to your G/L accounts, the mappings that you make will be remembered next time the same records are imported.</span></span> <span data-ttu-id="ec7e8-117">Tím ušetříte čas, protože nemusíte ručně vyplnit pole **Číslo účtu** ve finančním deníku pokaždé, když importujete opakované mzdové transakce.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-117">This will save you time as you do not have to manually fill in the **Account No.** field in the general journal every time you have imported recurring payroll transactions.</span></span>   

    <span data-ttu-id="ec7e8-118">Po výběru tlačítka **OK** v průvodci asistovaného nastavení, okno **Finanční deník** je vyplněno řádky představující transakce, které obsahují soubory mzdových plateb a příslušné účty předvyplněné v poli **Finanční účet** podle mapování provedených v průvodci.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-118">When you choose the **OK** button in the assisted setup guide, the **General Journal** window is filled with lines representing the transactions that the payroll file contains and with the relevant accounts prefilled in the **G/L Account** fields according to mappings you made in the guide.</span></span>
4. <span data-ttu-id="ec7e8-119">Upravte nebo zaúčtujte řádky deníku pro kteroukoli jinou transakci financí.</span><span class="sxs-lookup"><span data-stu-id="ec7e8-119">Edit or post the journal lines as for any other general ledger transactions.</span></span> <span data-ttu-id="ec7e8-120">Další informace naleznete v tématu [Návod: Zaúčtování transakcí přímo do hlavní knihy](finance-how-post-transactions-directly.md).</span><span class="sxs-lookup"><span data-stu-id="ec7e8-120">For more information, see [How to: Post Transactions Directly to the General Ledger](finance-how-post-transactions-directly.md).</span></span>   

## <a name="see-also"></a><span data-ttu-id="ec7e8-121">Viz také</span><span class="sxs-lookup"><span data-stu-id="ec7e8-121">See Also</span></span>
[<span data-ttu-id="ec7e8-122">Finance</span><span class="sxs-lookup"><span data-stu-id="ec7e8-122">Finance</span></span>](finance.md)  
<span data-ttu-id="ec7e8-123">[Přizpůsobení [!INCLUDE[d365fin](includes/d365fin_md.md)] Pomocí rozšíření](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="ec7e8-123">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions](ui-extensions.md)</span></span>  
[<span data-ttu-id="ec7e8-124">Práce s finančními deníky</span><span class="sxs-lookup"><span data-stu-id="ec7e8-124">Working with General Journals</span></span>](ui-work-general-journals.md)  

