---
title: "Vyhledání dokladů bez příloh"
Description: "Můžete vyhledávat položky hlavní knihy pro zaúčtované nákupní a prodejní doklady, které nemají došlé elektronické doklady, jako jsou importované faktury."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, e-invoice, incoming document, OCR, ecommerce, document exchange, import invoice
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 515026b4da842afeda1759f50313dc26bcfd3350
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="9982b-103">Návody: Vyhledání zaúčtovaných dokladů bez záznamů došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="9982b-103">How to: Find Posted Documents without Incoming Document Records</span></span>
<span data-ttu-id="9982b-104">Z okna **Účetní osnova** a **Položky hlavní knihy** můžete pomocí vyhledávací funkce vyhledat položky hlavní knihy pro zaúčtované nákupní a prodejní doklady, které nemají záznamy došlého dokladu a poté centrálně odkazovat na existující záznamy nebo vytvářet nové doklady s přiloženými soubory.</span><span class="sxs-lookup"><span data-stu-id="9982b-104">From the **Chart of Accounts** and **General Ledger Entries** windows, you can use a search function to find general ledger entries for posted purchase and sales documents that do not have incoming document records and then centrally link to existing records or create new ones with attached document files.</span></span>

## <a name="to-find-posted-documents-without-incoming-document-records"></a><span data-ttu-id="9982b-105">Vyhledání zaúčtovaných dokladů bez záznamů došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="9982b-105">To find posted documents without incoming document records</span></span>
1. <span data-ttu-id="9982b-106">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účetní osnova** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="9982b-106">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="9982b-107">Vyberte řádek pro finanční účet, kde jsou položky hlavní knihy, které chcete zaúčtovat jako nákupní a prodejní doklady bez záznamů došlého dokladu a pak zvolte akci **Zaúčtovat doklad bez došlého dokladu**.</span><span class="sxs-lookup"><span data-stu-id="9982b-107">Select a line for a G/L account for whose general ledger entries you want to see posted purchase and sales documents without incoming document records, and then choose the **Posted Documents without Incoming Document** action.</span></span>
3. <span data-ttu-id="9982b-108">Alternativně zvolte akci **Položky knihy**.</span><span class="sxs-lookup"><span data-stu-id="9982b-108">Alternatively, choose the **Ledger Entries** action.</span></span>
4. <span data-ttu-id="9982b-109">V okně **Položky hlavní knihy** zvolte akci **Zaúčtovat doklady bez došlých dokladů**.</span><span class="sxs-lookup"><span data-stu-id="9982b-109">In the **General Ledger Entries** window, choose the **Posted Documents without Incoming Documents** action.</span></span>

<span data-ttu-id="9982b-110">Okno **Zaúčtované doklady bez došlých dokladů** otevře zaúčtované nákupní a prodejní doklady bez záznamů došlého dokladu reprezentovány položkami hlavní knihy ve finančním účtu, který pro toto okno otevřete.</span><span class="sxs-lookup"><span data-stu-id="9982b-110">The **Posted Documents without Incoming Document** window opens showing posted purchase and sales documents without incoming document records represented by general ledger entries on the G/L account that you opened the window for.</span></span> <span data-ttu-id="9982b-111">Okno může ukázat maximum 1000 řádků.</span><span class="sxs-lookup"><span data-stu-id="9982b-111">The window can show a maximum of 1000 lines.</span></span> <span data-ttu-id="9982b-112">Ve výchozím nastavení pole **Filtr data** omezuje řádky na položky s daty zveřejnění od začátku účetního období do pracovního data.</span><span class="sxs-lookup"><span data-stu-id="9982b-112">By default, the **Date Filter** field therefore contains a filter that limits the lines to entries with posting dates from the beginning of the accounting period to the work date.</span></span>

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a><span data-ttu-id="9982b-113">Připojení nalezených dokladů k existujícím záznamům došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="9982b-113">To connect found documents to existing incoming document records</span></span>
1. <span data-ttu-id="9982b-114">V okně **Zaúčtované doklady bez došlého dokladu** vyberte řádek pro zaúčtovaný doklad, který chcete připojit k existujícímu záznamu došlého dokladu a pak zvolte akci **Vybrat došlý doklad**.</span><span class="sxs-lookup"><span data-stu-id="9982b-114">In the **Posted Documents without Incoming Document** window, select the line for a posted document that you want to connect to an existing incoming document record, and then choose the **Select Incoming Document** action.</span></span>
2. <span data-ttu-id="9982b-115">V okně **Došlé doklady** vyberte záznam došlého dokladu, který chcete připojit k zaúčtovanému dokladu a pak zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="9982b-115">In the **Incoming Documents** window, select the incoming document record that you want to connect to posted document found, and then choose the **OK** button.</span></span>
3. <span data-ttu-id="9982b-116">V okně **Zaúčtované doklady bez došlého dokladu** vyberte záznam došlého dokladu, který je nyní připojen k zaúčtovanému dokladu, jak můžete vidět v okně s fakty **Soubory došlého dokladu**.</span><span class="sxs-lookup"><span data-stu-id="9982b-116">In the **Posted Documents without Incoming Document** window, the selected incoming document record is now connected to the posted document, as you can see in the **Incoming Document Files** FactBox.</span></span>

<span data-ttu-id="9982b-117">Pokud v okně **Došlé doklady** neexistuje příslušný záznam došlého dokladu, můžete jej vytvořit.</span><span class="sxs-lookup"><span data-stu-id="9982b-117">If a relevant incoming document record does not exist in the **Incoming Documents** window, then you can create it.</span></span> <span data-ttu-id="9982b-118">Další informace naleznete v tématu [Návod: Vytvořit záznamy došlého dokladu](across-how-create-income-document-records.md).</span><span class="sxs-lookup"><span data-stu-id="9982b-118">For more information, see [How to: Create Incoming Document Records](across-how-create-income-document-records.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="9982b-119">Viz také</span><span class="sxs-lookup"><span data-stu-id="9982b-119">See Also</span></span>
[<span data-ttu-id="9982b-120">Proces Došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="9982b-120">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="9982b-121">Došlé doklady</span><span class="sxs-lookup"><span data-stu-id="9982b-121">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="9982b-122">Nákup</span><span class="sxs-lookup"><span data-stu-id="9982b-122">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="9982b-123">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="9982b-123">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

