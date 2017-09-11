---
title: "Návod: Vyhledání zaúčtovaných dokladů bez záznamů došlého dokladu"
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
ms.openlocfilehash: eca38d238361a9ac50aac117199fa97fbba4374f
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="0cce5-102">Návod: Vyhledání zaúčtovaných dokladů bez záznamů došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="0cce5-102">How to: Find Posted Documents without Incoming Document Records</span></span>
<span data-ttu-id="0cce5-103">Z okna **Účetní osnova** a **Položky hlavní knihy** můžete pomocí vyhledávací funkce vyhledat položky hlavní knihy pro zaúčtované nákupní a prodejní doklady, které nemají záznamy došlého dokladu a poté centrálně odkazovat na existující záznamy nebo vytvářet nové doklady s přiloženými soubory.</span><span class="sxs-lookup"><span data-stu-id="0cce5-103">From the **Chart of Accounts** and **General Ledger Entries** windows, you can use a search function to find general ledger entries for posted purchase and sales documents that do not have incoming document records and then centrally link to existing records or create new ones with attached document files.</span></span>

## <a name="to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="0cce5-104">Vyhledání zaúčtovaných dokladů bez záznamů došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="0cce5-104">To find posted documents without incoming document records</span></span>
1. <span data-ttu-id="0cce5-105">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účetní osnova** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="0cce5-105">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="0cce5-106">Vyberte řádek pro finanční účet, kde jsou položky hlavní knihy, které chcete zaúčtovat jako nákupní a prodejní doklady bez záznamů došlého dokladu a pak zvolte akci **Zaúčtovat doklad bez došlého dokladu**.</span><span class="sxs-lookup"><span data-stu-id="0cce5-106">Select a line for a G/L account for whose general ledger entries you want to see posted purchase and sales documents without incoming document records, and then choose the **Posted Documents without Incoming Document** action.</span></span>
3. <span data-ttu-id="0cce5-107">Alternativně zvolte akci **Položky knihy**.</span><span class="sxs-lookup"><span data-stu-id="0cce5-107">Alternatively, choose the **Ledger Entries** action.</span></span>
4. <span data-ttu-id="0cce5-108">V okně **Položky hlavní knihy** zvolte akci **Zaúčtovat doklady bez došlých dokladů**.</span><span class="sxs-lookup"><span data-stu-id="0cce5-108">In the **General Ledger Entries** window, choose the **Posted Documents without Incoming Documents** action.</span></span>

<span data-ttu-id="0cce5-109">Okno **Zaúčtované doklady bez došlých dokladů** otevře zaúčtované nákupní a prodejní doklady bez záznamů došlého dokladu reprezentovány položkami hlavní knihy ve finančním účtu, který pro toto okno otevřete.</span><span class="sxs-lookup"><span data-stu-id="0cce5-109">The **Posted Documents without Incoming Document** window opens showing posted purchase and sales documents without incoming document records represented by general ledger entries on the G/L account that you opened the window for.</span></span> <span data-ttu-id="0cce5-110">Okno může ukázat maximum 1000 řádků.</span><span class="sxs-lookup"><span data-stu-id="0cce5-110">The window can show a maximum of 1000 lines.</span></span> <span data-ttu-id="0cce5-111">Ve výchozím nastavení pole **Filtr data** omezuje řádky na položky s daty zveřejnění od začátku účetního období do pracovního data.</span><span class="sxs-lookup"><span data-stu-id="0cce5-111">By default, the **Date Filter** field therefore contains a filter that limits the lines to entries with posting dates from the beginning of the accounting period to the work date.</span></span>

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a><span data-ttu-id="0cce5-112">Připojení nalezených dokladů k existujícím záznamům došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="0cce5-112">To connect found documents to existing incoming document records</span></span>
1. <span data-ttu-id="0cce5-113">V okně **Zaúčtované doklady bez došlého dokladu** vyberte řádek pro zaúčtovaný doklad, který chcete připojit k existujícímu záznamu došlého dokladu a pak zvolte akci **Vybrat došlý doklad**.</span><span class="sxs-lookup"><span data-stu-id="0cce5-113">In the **Posted Documents without Incoming Document** window, select the line for a posted document that you want to connect to an existing incoming document record, and then choose the **Select Incoming Document** action.</span></span>
2. <span data-ttu-id="0cce5-114">V okně **Došlé doklady** vyberte záznam došlého dokladu, který chcete připojit k zaúčtovanému dokladu a pak zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="0cce5-114">In the **Incoming Documents** window, select the incoming document record that you want to connect to posted document found, and then choose the **OK** button.</span></span>
3. <span data-ttu-id="0cce5-115">V okně **Zaúčtované doklady bez došlého dokladu** vyberte záznam došlého dokladu, který je nyní připojen k zaúčtovanému dokladu, jak můžete vidět v okně s fakty **Soubory došlého dokladu**.</span><span class="sxs-lookup"><span data-stu-id="0cce5-115">In the **Posted Documents without Incoming Document** window, the selected incoming document record is now connected to the posted document, as you can see in the **Incoming Document Files** FactBox.</span></span>

<span data-ttu-id="0cce5-116">Pokud v okně **Došlé doklady** neexistuje příslušný záznam došlého dokladu, můžete jej vytvořit.</span><span class="sxs-lookup"><span data-stu-id="0cce5-116">If a relevant incoming document record does not exist in the **Incoming Documents** window, then you can create it.</span></span> <span data-ttu-id="0cce5-117">Další informace naleznete v tématu [Návod: Vytvoření záznamů došlého dokladu](across-how-create-income-document-records.md).</span><span class="sxs-lookup"><span data-stu-id="0cce5-117">For more information, see [How to: Create Incoming Document Records](across-how-create-income-document-records.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="0cce5-118">Viz také</span><span class="sxs-lookup"><span data-stu-id="0cce5-118">See Also</span></span>  
[<span data-ttu-id="0cce5-119">Proces Došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="0cce5-119">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="0cce5-120">Došlé doklady</span><span class="sxs-lookup"><span data-stu-id="0cce5-120">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="0cce5-121">Správa nákupu</span><span class="sxs-lookup"><span data-stu-id="0cce5-121">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="0cce5-122">Práce s Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="0cce5-122">Work With Dynamics NAV</span></span>](ui-work-product.md)

