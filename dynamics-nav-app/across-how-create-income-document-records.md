---
title: "Vytvoření záznamů došlých dokladů"
description: "Můžete vytvořit záznam došlého dokladu jako například elektronické faktury a řízení úkolů OCR, eCommerce a výměny dokumentů."
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
ms.openlocfilehash: f7b90a92fe0f0efac4c79881501732267cec2497
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-incoming-document-records"></a><span data-ttu-id="29c9c-103">Návody: Vytvoření záznamu došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="29c9c-103">How to: Create Incoming Document Records</span></span>
<span data-ttu-id="29c9c-104">V okně **Došlé doklady** můžete použít různé funkce pro kontrolu výdajů, správu OCR úkolů a převod došlých dokladů ručně nebo automaticky na příslušné doklady nebo řádky deníku.</span><span class="sxs-lookup"><span data-stu-id="29c9c-104">In the **Incoming Documents** window, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="29c9c-105">Externí doklady lze připojit v libovolné fázi procesu, včetně zaúčtovaných dokladů a výsledků dodavatelů, zákazníků a položek hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="29c9c-105">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span>

<span data-ttu-id="29c9c-106">K záznamu externího dokladu v [!INCLUDE[d365fin](includes/d365fin_md.md)], musíte nejprve vytvořit nebo dokončit záznam došlého dokladu.</span><span class="sxs-lookup"><span data-stu-id="29c9c-106">To record an external document in [!INCLUDE[d365fin](includes/d365fin_md.md)], you must first create or complete an incoming document record.</span></span> <span data-ttu-id="29c9c-107">Můžete to provést ručně nebo můžete pořídit fotografii externího dokladu a pak vytvořit záznam došlého dokladu s připojeným obrazovým souborem.</span><span class="sxs-lookup"><span data-stu-id="29c9c-107">You can do this manually, or you can take a photo of the external document and then create the incoming document record with the image file attached.</span></span>

<span data-ttu-id="29c9c-108">Předtím než můžete použít funkce Došlého dokladu, musíte provést požadované nastavení.</span><span class="sxs-lookup"><span data-stu-id="29c9c-108">Before you can use the Incoming Documents feature, you must perform the required setup.</span></span> <span data-ttu-id="29c9c-109">Další informace naleznete v tématu [Návod: Nastavení došlých dokladů](across-how-setup-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="29c9c-109">For more information, see [How to: Set Up Incoming Documents](across-how-setup-income-documents.md).</span></span>

## <a name="to-approve-or-reject-an-incoming-document"></a><span data-ttu-id="29c9c-110">Schválení nebo odmítnutí došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="29c9c-110">To approve or reject an incoming document</span></span>
<span data-ttu-id="29c9c-111">Pokud chcete povolit uživatelům vytvářet faktury nebo řádky finančního deníku ze záznamů došlého dokladu, dokud nejsou schváleny, můžete nastavit toho, kdo musí schválit záznamy předtím, než budou zpracovány.</span><span class="sxs-lookup"><span data-stu-id="29c9c-111">If you do want to allow users to create invoices or general journal lines from incoming document records unless they are approved, you can set up approvers who must approve the records before they can be processed.</span></span>

1. <span data-ttu-id="29c9c-112">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Došlé doklady** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="29c9c-112">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="29c9c-113">Vyberte řádek dokladu, který chcete vydat nebo odmítnout a pak zvolte akci **Vydat** nebo **Odmítnout**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-113">Select the line with the document that you want to approve or reject, and then choose the **Approve** or **Reject** actions.</span></span>

<span data-ttu-id="29c9c-114">Pokud vydáte záznam došlého dokladu, je vybráno zaškrtávací políčko **Uvolnit** v řádku došlého dokladu.</span><span class="sxs-lookup"><span data-stu-id="29c9c-114">If you approve the incoming document record, the **Released** check box on the incoming document line is selected.</span></span> <span data-ttu-id="29c9c-115">Uživatel, který je pověřen tvorbou například nákupních faktur, může zpracovat záznam.</span><span class="sxs-lookup"><span data-stu-id="29c9c-115">The user in charge of creating, for example, purchase invoices can proceed to process the record.</span></span>

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="29c9c-116">Vytvoření záznamu došlého dokladu pořízením fotografie</span><span class="sxs-lookup"><span data-stu-id="29c9c-116">To create an incoming document record by taking a photo</span></span>
> [!NOTE]  
>   <span data-ttu-id="29c9c-117">Následující postup platí pouze [!INCLUDE[d365fin](includes/d365fin_md.md)] pro klienty tabletu a telefonu.</span><span class="sxs-lookup"><span data-stu-id="29c9c-117">The following procedure only applies to the [!INCLUDE[d365fin](includes/d365fin_md.md)] Tablet and Phone clients.</span></span>

1. <span data-ttu-id="29c9c-118">Na panelu aplikace zvolte dlaždici **Vytvořit došlý doklad z fotoaparátu** a pak pokračujte na krok 4.</span><span class="sxs-lookup"><span data-stu-id="29c9c-118">On the app bar, choose the **Create Incoming Document from Camera** tile, and then go to step 4.</span></span>
2. <span data-ttu-id="29c9c-119">Alternativně na panelu aplikace zvolte tlačítko možnosti, vyberte **Došlé doklady** a pak zvolte **Vše**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-119">Alternatively, on the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
3. <span data-ttu-id="29c9c-120">V okně **Došlé doklady** zvolte tlačítko tři tečky a pak zvolte **Vytvořit z fotoaparátu**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-120">In the **Incoming Documents** window, choose the ellipsis button, and then choose **Create from Camera**.</span></span> <span data-ttu-id="29c9c-121">Kamera v tabletu nebo telefonu se aktivuje.</span><span class="sxs-lookup"><span data-stu-id="29c9c-121">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="29c9c-122">Udělejte fotku dokladu například nákupního dokladu, který chcete zpracovat jako došlý doklad a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-122">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

    <span data-ttu-id="29c9c-123">Nový záznam došlého dokladu je vytvořen s připojením obrázku.</span><span class="sxs-lookup"><span data-stu-id="29c9c-123">A new incoming document record is created, with the image attached.</span></span>

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="29c9c-124">Připojení obrázku k záznamu došlého dokladu pomocí fotografie</span><span class="sxs-lookup"><span data-stu-id="29c9c-124">To attach an image to an incoming document record by taking a photo</span></span>
> [!NOTE]  
>   <span data-ttu-id="29c9c-125">Následující postup platí pouze [!INCLUDE[d365fin](includes/d365fin_md.md)] pro klienty tabletu a telefonu.</span><span class="sxs-lookup"><span data-stu-id="29c9c-125">The following procedure only applies to the [!INCLUDE[d365fin](includes/d365fin_md.md)] Tablet and Phone clients.</span></span>

1. <span data-ttu-id="29c9c-126">Na panelu aplikace zvolte tlačítko možnosti, zvolte **Došlé doklady** a pak zvolte **Vše**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-126">On the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
2. <span data-ttu-id="29c9c-127">Otevře se karta pro existující záznam došlého dokladu.</span><span class="sxs-lookup"><span data-stu-id="29c9c-127">Open the card for an existing incoming document record.</span></span>
3. <span data-ttu-id="29c9c-128">V okně **Došlé doklady** zvolte tlačítko tři tečky a pak zvolte **Připojit obrázek z fotoaparátu**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-128">In the **Incoming Document** window, choose the ellipsis button, and then choose **Attach Image from Camera**.</span></span> <span data-ttu-id="29c9c-129">Kamera v tabletu nebo telefonu se aktivuje.</span><span class="sxs-lookup"><span data-stu-id="29c9c-129">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="29c9c-130">Udělejte fotku dokladu například nákupního dokladu, který chcete zpracovat jako došlý doklad a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-130">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

    <span data-ttu-id="29c9c-131">Obrázek je připojen k záznamu došlého dokladu.</span><span class="sxs-lookup"><span data-stu-id="29c9c-131">The image is attached to the incoming document record.</span></span>

## <a name="to-create-an-incoming-document-record-manually"></a><span data-ttu-id="29c9c-132">Vytvoření záznamu došlého dokladu manuálně</span><span class="sxs-lookup"><span data-stu-id="29c9c-132">To create an incoming document record manually</span></span>
1. <span data-ttu-id="29c9c-133">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Došlé doklady** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="29c9c-133">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="29c9c-134">Zvolte akci **Vytvořit ze souboru**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-134">Choose the **Create from File** action.</span></span>  
3. <span data-ttu-id="29c9c-135">V okně **Vložit soubor** vyberte soubor a pak zvolte **Otevřít**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-135">In the **Insert File** window, select a file, and then choose **Open**.</span></span> <span data-ttu-id="29c9c-136">Soubor je automaticky připojen.</span><span class="sxs-lookup"><span data-stu-id="29c9c-136">The file is automatically attached.</span></span>
4. <span data-ttu-id="29c9c-137">Alternativně zvolte akci **Nový**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-137">Alternatively, choose the **New** action.</span></span>
5. <span data-ttu-id="29c9c-138">Pro připojení souboru zvolte akci **Připojit soubor**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-138">To attach a file, choose the **Attach File** action.</span></span>
6. <span data-ttu-id="29c9c-139">V okně **Vložit soubor** vyberte soubor, který reprezentuje došlý doklad a pak zvolte tlačítko **Otevřít**.</span><span class="sxs-lookup"><span data-stu-id="29c9c-139">In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.</span></span>
7. <span data-ttu-id="29c9c-140">V okně **Došlý doklad** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="29c9c-140">In the **Incoming Document** window, fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="see-also"></a><span data-ttu-id="29c9c-141">Viz také</span><span class="sxs-lookup"><span data-stu-id="29c9c-141">See Also</span></span>
[<span data-ttu-id="29c9c-142">Proces Došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="29c9c-142">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="29c9c-143">Došlé doklady</span><span class="sxs-lookup"><span data-stu-id="29c9c-143">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="29c9c-144">Nákup</span><span class="sxs-lookup"><span data-stu-id="29c9c-144">Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="29c9c-145">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="29c9c-145">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

