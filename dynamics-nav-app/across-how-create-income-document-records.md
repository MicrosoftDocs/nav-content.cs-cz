---
title: "Návod: Vytvoření záznamu došlého dokladu"
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
ms.openlocfilehash: e91c4570ff60d991974ac6afd16ba3bc3e73e44f
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-create-incoming-document-records"></a><span data-ttu-id="9c1c1-102">Návod: Vytvoření záznamu došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="9c1c1-102">How to: Create Incoming Document Records</span></span>
<span data-ttu-id="9c1c1-103">V okně **Došlé doklady** můžete použít různé funkce pro kontrolu výdajů, správu OCR úkolů a převod došlých dokladů ručně nebo automaticky na příslušné doklady nebo řádky deníku.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-103">In the **Incoming Documents** window, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="9c1c1-104">Externí doklady lze připojit v libovolné fázi procesu, včetně zaúčtovaných dokladů a výsledků dodavatelů, zákazníků a položek hlavní knihy.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-104">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span>

<span data-ttu-id="9c1c1-105">Pro záznam externího dokladu v [!INCLUDE[navnow](includes/navnow_md.md)] musíte nejdřív vytvořit nebo dokončit záznam došlého dokladu.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-105">To record an external document in Dynamics NAV, you must first create or complete an incoming document record.</span></span> <span data-ttu-id="9c1c1-106">Toto můžete udělat manuálně nebo můžete pořídit fotografii externích dokladů a pak vytvořit záznam došlého dokladu s připojeným obrazovým souborem.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-106">You can do this manually, or you can take a photo of the external document and then create the incoming document record with the image file attached.</span></span>

<span data-ttu-id="9c1c1-107">Předtím než můžete použít funkce Došlého dokladu, musíte provést požadované nastavení.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-107">Before you can use the Incoming Documents feature, you must perform the required setup.</span></span> <span data-ttu-id="9c1c1-108">Další informace naleznete v tématu [Návod: Nastavení došlých dokladů](across-how-setup-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="9c1c1-108">For more information, see [How to: Set Up Incoming Documents](across-how-setup-income-documents.md).</span></span>

## <a name="to-approve-or-reject-an-incoming-document"></a><span data-ttu-id="9c1c1-109">Schválení nebo odmítnutí došlého dokladu</span><span class="sxs-lookup"><span data-stu-id="9c1c1-109">To approve or reject an incoming document</span></span>
<span data-ttu-id="9c1c1-110">Pokud chcete povolit uživatelům vytvářet faktury nebo řádky finančního deníku ze záznamů došlého dokladu, dokud nejsou schváleny, můžete nastavit toho, kdo musí schválit záznamy předtím, než budou zpracovány.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-110">If you do want to allow users to create invoices or general journal lines from incoming document records unless they are approved, you can set up approvers who must approve the records before they can be processed.</span></span>

1. <span data-ttu-id="9c1c1-111">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Došlé doklady** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-111">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="9c1c1-112">Vyberte řádek dokladu, který chcete vydat nebo odmítnout a pak zvolte akci **Vydat** nebo **Odmítnout**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-112">Select the line with the document that you want to approve or reject, and then choose the **Approve** or **Reject** actions.</span></span>

<span data-ttu-id="9c1c1-113">Pokud vydáte záznam došlého dokladu, je vybráno zaškrtávací políčko **Uvolnit** v řádku došlého dokladu.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-113">If you approve the incoming document record, the **Released** check box on the incoming document line is selected.</span></span> <span data-ttu-id="9c1c1-114">Uživatel, který je pověřen tvorbou například nákupních faktur, může zpracovat záznam.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-114">The user in charge of creating, for example, purchase invoices can proceed to process the record.</span></span>

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="9c1c1-115">Vytvoření záznamu došlého dokladu pořízením fotografie</span><span class="sxs-lookup"><span data-stu-id="9c1c1-115">To create an incoming document record by taking a photo</span></span>
<span data-ttu-id="9c1c1-116">**Poznámka**: Následující postup platí pouze pro klienty tabletu a telefonu [!INCLUDE[navnow](includes/navnow_md.md)].</span><span class="sxs-lookup"><span data-stu-id="9c1c1-116">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="9c1c1-117">Na panelu aplikace zvolte dlaždici **Vytvořit došlý doklad z fotoaparátu** a pak pokračujte na krok 4.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-117">On the app bar, choose the **Create Incoming Document from Camera** tile, and then go to step 4.</span></span>
2. <span data-ttu-id="9c1c1-118">Alternativně na panelu aplikace zvolte tlačítko možnosti, vyberte **Došlé doklady** a pak zvolte **Vše**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-118">Alternatively, on the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
3. <span data-ttu-id="9c1c1-119">V okně **Došlé doklady** zvolte tlačítko tři tečky a pak zvolte **Vytvořit z fotoaparátu**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-119">In the **Incoming Documents** window, choose the ellipsis button, and then choose **Create from Camera**.</span></span> <span data-ttu-id="9c1c1-120">Kamera v tabletu nebo telefonu se aktivuje.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-120">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="9c1c1-121">Udělejte fotku dokladu například nákupního dokladu, který chcete zpracovat jako došlý doklad a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-121">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="9c1c1-122">Nový záznam došlého dokladu je vytvořen s připojením obrázku.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-122">A new incoming document record is created, with the image attached.</span></span>

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a><span data-ttu-id="9c1c1-123">Připojení obrázku k záznamu došlého dokladu pomocí fotografie</span><span class="sxs-lookup"><span data-stu-id="9c1c1-123">To attach an image to an incoming document record by taking a photo</span></span>
<span data-ttu-id="9c1c1-124">**Poznámka**: Následující postup platí pouze pro klienty tabletu a telefonu [!INCLUDE[navnow](includes/navnow_md.md)].</span><span class="sxs-lookup"><span data-stu-id="9c1c1-124">**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.</span></span>

1. <span data-ttu-id="9c1c1-125">Na panelu aplikace zvolte tlačítko možnosti, zvolte **Došlé doklady** a pak zvolte **Vše**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-125">On the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.</span></span>
2. <span data-ttu-id="9c1c1-126">Otevře se karta pro existující záznam došlého dokladu.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-126">Open the card for an existing incoming document record.</span></span>
3. <span data-ttu-id="9c1c1-127">V okně **Došlé doklady** zvolte tlačítko tři tečky a pak zvolte **Připojit obrázek z fotoaparátu**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-127">In the **Incoming Document** window, choose the ellipsis button, and then choose **Attach Image from Camera**.</span></span> <span data-ttu-id="9c1c1-128">Kamera v tabletu nebo telefonu se aktivuje.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-128">The camera on the tablet or phone is activated.</span></span>
4. <span data-ttu-id="9c1c1-129">Udělejte fotku dokladu například nákupního dokladu, který chcete zpracovat jako došlý doklad a potom klepněte na tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-129">Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.</span></span>

<span data-ttu-id="9c1c1-130">Obrázek je připojen k záznamu došlého dokladu.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-130">The image is attached to the incoming document record.</span></span>

## <a name="to-create-an-incoming-document-record-manually"></a><span data-ttu-id="9c1c1-131">Vytvoření záznamu došlého dokladu manuálně</span><span class="sxs-lookup"><span data-stu-id="9c1c1-131">To create an incoming document record manually</span></span>
1. <span data-ttu-id="9c1c1-132">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Došlé doklady** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-132">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.</span></span>
2. <span data-ttu-id="9c1c1-133">Zvolte akci **Vytvořit ze souboru**</span><span class="sxs-lookup"><span data-stu-id="9c1c1-133">Choose the **Create from File** action.</span></span>  
3. <span data-ttu-id="9c1c1-134">V okně **Vložit soubor** vyberte soubor a pak zvolte **Otevřít**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-134">In the **Insert File** window, select a file, and then choose **Open**.</span></span>

    <span data-ttu-id="9c1c1-135">Soubor je automaticky připojen.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-135">The file is automatically attached.</span></span>
4. <span data-ttu-id="9c1c1-136">Alternativně zvolte akci **Nový**. </span><span class="sxs-lookup"><span data-stu-id="9c1c1-136">Alternatively, choose the **New** action.</span></span>
5. <span data-ttu-id="9c1c1-137">Pro připojení souboru zvolte akci **Připojit soubor**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-137">To attach a file, choose the **Attach File** action.</span></span>
6. <span data-ttu-id="9c1c1-138">V okně **Vložit soubor** vyberte soubor, který reprezentuje došlý doklad a pak zvolte tlačítko **Otevřít**.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-138">In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.</span></span>
7. <span data-ttu-id="9c1c1-139">V okně **Došlý doklad** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-139">In the **Incoming Document** window, fill in the fields as necessary.</span></span> <span data-ttu-id="9c1c1-140">Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="9c1c1-140">Choose a field to read a short description of the field or link to more information.</span></span>

##<a name="see-also"></a><span data-ttu-id="9c1c1-141">Viz také</span><span class="sxs-lookup"><span data-stu-id="9c1c1-141">See Also</span></span>  
[<span data-ttu-id="9c1c1-142">Proces došlých dokladů</span><span class="sxs-lookup"><span data-stu-id="9c1c1-142">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="9c1c1-143">Došlé doklady</span><span class="sxs-lookup"><span data-stu-id="9c1c1-143">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="9c1c1-144">Správa nákupu</span><span class="sxs-lookup"><span data-stu-id="9c1c1-144">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
<span data-ttu-id="9c1c1-145">[Práce s [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="9c1c1-145">[Work With Dynamics NAV](ui-work-product.md)</span></span>

