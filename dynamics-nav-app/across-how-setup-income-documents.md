---
title: "Nastavení Došlých dokladů"
description: "Pomocí funkce Došlých dokladů můžete vytvářet elektronické doklady, spravovat úlohy OCR, importovat faktury a převádět obrazové soubory."
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
ms.openlocfilehash: 80c57f6a332ace58941929811e3f3a9b1f156028
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-incoming-documents"></a><span data-ttu-id="1637d-103">Návody: Nastavení Došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="1637d-103">How to: Set Up Incoming Documents</span></span>
<span data-ttu-id="1637d-104">Pokud vytvoříte řádky finančního deníku ze záznamů došlého dokladu, musíte zadat v okně **Nastavení došlých dokladů** šablonu deníku a dávku, které chcete použít.</span><span class="sxs-lookup"><span data-stu-id="1637d-104">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span></span>

<span data-ttu-id="1637d-105">Pokud nechcete, aby uživatelé vytvářeli faktury nebo řádky finančního deníku ze záznamů došlého dokladu, pokud nejsou doklady prvně schváleny, je nutné nastavit schvalovatele v okně **Schvalovatelé došlého dokladu**.</span><span class="sxs-lookup"><span data-stu-id="1637d-105">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span></span>

<span data-ttu-id="1637d-106">Chcete-li soubory PDF a obrázkové soubory převést do elektronických dokumentů, které lze převést například na nákupní faktury v [!INCLUDE[d365fin](includes/d365fin_md.md)], musíte nejprve nastavit funkci OCR a povolit službu.</span><span class="sxs-lookup"><span data-stu-id="1637d-106">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside [!INCLUDE[d365fin](includes/d365fin_md.md)], you must first set up the OCR feature and enable the service.</span></span>

<span data-ttu-id="1637d-107">Když je nastavena funkce Došlých dokladů, můžete použít různé funkce pro kontrolu výdajů, správu úloh OCR a převod souborů došlého dokladu ručně nebo automaticky na příslušné doklady nebo řádky deníku.</span><span class="sxs-lookup"><span data-stu-id="1637d-107">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="1637d-108">Externí soubory lze připojit v libovolné fázi procesu včetně zaúčtovaných dokladů a výsledných záznamů prodejce, zákazníka a položek hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="1637d-108">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span> <span data-ttu-id="1637d-109">Další informace naleznete v tématu [Proces došlých dokladů](across-process-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="1637d-109">For more information, see [Processing Incoming Documents](across-process-income-documents.md).</span></span>

## <a name="to-set-up-the-incoming-documents-feature"></a><span data-ttu-id="1637d-110">Nastavení funkcí Došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="1637d-110">To set up the Incoming Documents feature</span></span>
1. <span data-ttu-id="1637d-111">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení došlých dokladů** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="1637d-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="1637d-112">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="1637d-112">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-approvers-of-incoming-document-records"></a><span data-ttu-id="1637d-113">Nastavení schvalovatelů záznamů došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="1637d-113">To set up approvers of incoming document records</span></span>
1. <span data-ttu-id="1637d-114">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení došlých dokladů** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="1637d-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="1637d-115">V okně **Nastavení došlých dokladů** zvolte akci **Schvalovatelé**.</span><span class="sxs-lookup"><span data-stu-id="1637d-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span></span>

    <span data-ttu-id="1637d-116">Okno **Schvalovatelé došlých dokladů** ukáže všechny uživatele, kteří jsou nastaveni v [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="1637d-116">The **Incoming Document Approvers** window shows all users that are set up in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  
3. <span data-ttu-id="1637d-117">Vyberte jednoho nebo více uživatelů, kteří mohou schválit došlý doklad předtím, než lze vytvořit související doklad nebo řádek deníku.</span><span class="sxs-lookup"><span data-stu-id="1637d-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span></span>

<span data-ttu-id="1637d-118">Pokud byli schvalovatelé nastaveni v okně **Schvalovatelé došlých dokladů**, pouze tito uživatelé mohou schválit došlý doklad, pokud je zaškrtnuto políčko **K vytvoření vyžaduje schválení** v okně **Nastavení došlých dokladů**.</span><span class="sxs-lookup"><span data-stu-id="1637d-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span></span>

> [!NOTE]  
>   <span data-ttu-id="1637d-119">Toto nastavení schválení nesouvisí se schvalovacími postupy.</span><span class="sxs-lookup"><span data-stu-id="1637d-119">This approval setup is not related to approval workflows.</span></span> <span data-ttu-id="1637d-120">Další informace naleznete v tématu [Návod: Použití schvalovacího workflow](across-how-use-approval-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="1637d-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span></span>

## <a name="to-set-up-an-ocr-service"></a><span data-ttu-id="1637d-121">Nastavení služby OCR</span><span class="sxs-lookup"><span data-stu-id="1637d-121">To set up an OCR service</span></span>
1. <span data-ttu-id="1637d-122">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení služby OCR** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="1637d-122">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **OCR Service Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="1637d-123">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="1637d-123">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-encrypt-your-login-information"></a><span data-ttu-id="1637d-124">Šifrování přihlašovacích údajů</span><span class="sxs-lookup"><span data-stu-id="1637d-124">To encrypt your login information</span></span>
<span data-ttu-id="1637d-125">Doporučuje se chránit přihlašovací informace, které zadáte do okna **Nastavení služby OCR**.</span><span class="sxs-lookup"><span data-stu-id="1637d-125">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span></span> <span data-ttu-id="1637d-126">Můžete šifrovat data na serveru generováním nového nebo importováním existujícího šifrovacího klíče, který povolíte na instanci serveru, který je připojen k databázi.</span><span class="sxs-lookup"><span data-stu-id="1637d-126">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span></span>

1. <span data-ttu-id="1637d-127">V okně **Nastavení služby OCR** zvolte akci **Správce šifrování**.</span><span class="sxs-lookup"><span data-stu-id="1637d-127">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span></span>
2. <span data-ttu-id="1637d-128">Okno **Správa šifrování dat** umožňuje šifrování vašich dat.</span><span class="sxs-lookup"><span data-stu-id="1637d-128">In the **Data Encryption Management** window, enable encryption of your data.</span></span>

## <a name="see-also"></a><span data-ttu-id="1637d-129">Viz také</span><span class="sxs-lookup"><span data-stu-id="1637d-129">See Also</span></span>
[<span data-ttu-id="1637d-130">Proces Došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="1637d-130">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="1637d-131">Došlé doklady</span><span class="sxs-lookup"><span data-stu-id="1637d-131">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="1637d-132">Nákup</span><span class="sxs-lookup"><span data-stu-id="1637d-132">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="1637d-133">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="1637d-133">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

