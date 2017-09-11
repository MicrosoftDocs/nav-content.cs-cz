---
title: "Návod: Nastavení Došlých dokladů"
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
ms.openlocfilehash: d55329b571e4c59d4821a86a39362ea58480b86a
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-set-up-incoming-documents"></a><span data-ttu-id="69ac6-102">Návod: Nastavení Došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="69ac6-102">How to: Set Up Incoming Documents</span></span>
<span data-ttu-id="69ac6-103">Pokud vytvoříte řádky finančního deníku ze záznamů došlého dokladu, musíte zadat v okně **Nastavení došlých dokladů** šablonu deníku a dávku, které chcete použít. </span><span class="sxs-lookup"><span data-stu-id="69ac6-103">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span></span>

<span data-ttu-id="69ac6-104">Pokud nechcete, aby uživatelé vytvářeli faktury nebo řádky finančního deníku ze záznamů došlého dokladu, pokud nejsou doklady prvně schváleny, je nutné nastavit schvalovatele v okně **Schvalovatelé došlého dokladu**.</span><span class="sxs-lookup"><span data-stu-id="69ac6-104">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span></span>

<span data-ttu-id="69ac6-105">Chcete-li soubory PDF a obrázkové soubory převést do elektronických dokumentů, které lze převést například na nákupní faktury v Dynamics NAV, musíte nejprve nastavit funkci OCR a povolit službu.</span><span class="sxs-lookup"><span data-stu-id="69ac6-105">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside Dynamics NAV, you must first set up the OCR feature and enable the service.</span></span>

<span data-ttu-id="69ac6-106">Když je nastavena funkce Došlých dokladů, můžete použít různé funkce pro kontrolu výdajů, správu úloh OCR a převod souborů došlého dokladu ručně nebo automaticky na příslušné doklady nebo řádky deníku.</span><span class="sxs-lookup"><span data-stu-id="69ac6-106">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="69ac6-107">Externí soubory lze připojit v libovolné fázi procesu včetně zaúčtovaných dokladů a výsledných záznamů prodejce, zákazníka a položek hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="69ac6-107">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span> <span data-ttu-id="69ac6-108">Další informace naleznete v tématu [Návod: Proces došlých dokladů](across-process-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="69ac6-108">For more information, see [How to: Process Incoming Documents](across-process-income-documents.md).</span></span>

## <a name="to-set-up-the-incoming-documents-feature"></a><span data-ttu-id="69ac6-109">Nastavení funkcí Došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="69ac6-109">To set up the Incoming Documents feature</span></span>
1. <span data-ttu-id="69ac6-110">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení došlých dokladů** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="69ac6-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="69ac6-111">Vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="69ac6-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="69ac6-112">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="69ac6-112">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-approvers-of-incoming-document-records"></a><span data-ttu-id="69ac6-113">Nastavení schvalovatelů záznamů došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="69ac6-113">To set up approvers of incoming document records</span></span>
1. <span data-ttu-id="69ac6-114">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení došlých dokladů** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="69ac6-114">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="69ac6-115">V okně **Nastavení došlých dokladů** zvolte akci **Schvalovatelé**. </span><span class="sxs-lookup"><span data-stu-id="69ac6-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span></span>

    <span data-ttu-id="69ac6-116">Okno **Schvalovatelé došlých dokladů** ukáže všechny uživatele, kteří jsou nastaveni v Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="69ac6-116">The **Incoming Document Approvers** window shows all users that are set up in your Dynamics NAV .</span></span>  
3. <span data-ttu-id="69ac6-117">Vyberte jednoho nebo více uživatelů, kteří mohou schválit došlý doklad předtím, než lze vytvořit související doklad nebo řádek deníku.</span><span class="sxs-lookup"><span data-stu-id="69ac6-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span></span>

<span data-ttu-id="69ac6-118">Pokud byli schvalovatelé nastaveni v okně **Schvalovatelé došlých dokladů**, pouze tito uživatelé mohou schválit došlý doklad, pokud je zaškrtnuto políčko **K vytvoření vyžaduje schválení** v okně **Nastavení došlých dokladů**.</span><span class="sxs-lookup"><span data-stu-id="69ac6-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span></span>

<span data-ttu-id="69ac6-119">**Poznámka**: Toto nastavení schválení nesouvisí se schvalovacími postupy.</span><span class="sxs-lookup"><span data-stu-id="69ac6-119">**Note**: This approval setup is not related to approval workflows.</span></span> <span data-ttu-id="69ac6-120">Další informace naleznete v tématu [Návod: Použití schvalovacího workflow](across-how-use-approval-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="69ac6-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span></span>

## <a name="to-set-up-an-ocr-service"></a><span data-ttu-id="69ac6-121">Nastavení služby OCR</span><span class="sxs-lookup"><span data-stu-id="69ac6-121">To set up an OCR service</span></span>
1. <span data-ttu-id="69ac6-122">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení služby OCR** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="69ac6-122">In the top right corner, choose the **Search for Page or Report** icon, enter **OCR Service Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="69ac6-123">Vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="69ac6-123">Fill in the fields as necessary.</span></span> <span data-ttu-id="69ac6-124">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="69ac6-124">Choose a field to read a short description of the field or link to more information.</span></span>


## <a name="to-encrypt-your-login-information"></a><span data-ttu-id="69ac6-125">Šifrování přihlašovacích údajů</span><span class="sxs-lookup"><span data-stu-id="69ac6-125">To encrypt your login information</span></span>
<span data-ttu-id="69ac6-126">Doporučuje se chránit přihlašovací informace, které zadáte do okna **Nastavení služby OCR**.</span><span class="sxs-lookup"><span data-stu-id="69ac6-126">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span></span> <span data-ttu-id="69ac6-127">Můžete šifrovat data na serveru generováním nového nebo importováním existujícího šifrovacího klíče, který povolíte na instanci serveru, který je připojen k databázi.</span><span class="sxs-lookup"><span data-stu-id="69ac6-127">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span></span>

1. <span data-ttu-id="69ac6-128">V okně **Nastavení služby OCR** zvolte akci **Správce šifrování**.</span><span class="sxs-lookup"><span data-stu-id="69ac6-128">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span></span>
2. <span data-ttu-id="69ac6-129">Okno **Správa šifrování dat** umožňuje šifrování vašich dat.</span><span class="sxs-lookup"><span data-stu-id="69ac6-129">In the **Data Encryption Management** window, enable encryption of your data.</span></span>

## <a name="see-also"></a><span data-ttu-id="69ac6-130">Viz také</span><span class="sxs-lookup"><span data-stu-id="69ac6-130">See Also</span></span>  
[<span data-ttu-id="69ac6-131">Proces došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="69ac6-131">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="69ac6-132">Došlé doklady</span><span class="sxs-lookup"><span data-stu-id="69ac6-132">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="69ac6-133">Správa nákupu</span><span class="sxs-lookup"><span data-stu-id="69ac6-133">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="69ac6-134">Práce s Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="69ac6-134">Work With Dynamics NAV</span></span>](ui-work-product.md)

