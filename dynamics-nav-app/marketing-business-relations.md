---
title: "Definujte kódy obchodních vztahů v kontaktech"
description: "Použijte obchodní vztahy v Dynamics NAV, abyste pomohli s marketingem a označili obchodní vztah, který máte s vašimi klienty a zákazníky, například s bankou nebo poskytovatelem služeb."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: marketing, prospect, contact, client, customer
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 6d0f157502eb9d82875c8585ab43d48cfd9e8ffb
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="setting-up-business-relations-on-contact-companies"></a><span data-ttu-id="d14b0-103">Nastavení obchodních vztahů ke kontaktním společnostem</span><span class="sxs-lookup"><span data-stu-id="d14b0-103">Setting Up Business Relations on Contact Companies</span></span>
<span data-ttu-id="d14b0-104">Pomocí obchodních vztahů můžete označit obchodní vztah, který máte s vašimi kontakty, například potencionálním zákazníkem, bankou, konzultantem, dodavatelem služeb atd.</span><span class="sxs-lookup"><span data-stu-id="d14b0-104">You can use business relations to indicate the business relationship you have with your contacts, for example, a prospect, bank, consultant, service supplier, and so on.</span></span>

<span data-ttu-id="d14b0-105">Použití obchodních vztahů na kontaktech je proces o dvou krocích.</span><span class="sxs-lookup"><span data-stu-id="d14b0-105">Using business relations on contacts is a two-step process.</span></span> <span data-ttu-id="d14b0-106">Nejprve definujete kód obchodních vztahů.</span><span class="sxs-lookup"><span data-stu-id="d14b0-106">First, you define the business relation code.</span></span> <span data-ttu-id="d14b0-107">Pro každý obchodní vztah stačí tento krok provést pouze jednou.</span><span class="sxs-lookup"><span data-stu-id="d14b0-107">You only have to perform this step one time for each business relation.</span></span> <span data-ttu-id="d14b0-108">Jakmile máte kód pro obchodní vztahy, můžete jej přiřadit ke kontaktním společnostem.</span><span class="sxs-lookup"><span data-stu-id="d14b0-108">Once you have a business relation code, you can start to assign the code to contact companies.</span></span>

> [!NOTE]  
>   <span data-ttu-id="d14b0-109">Pokud máte v úmyslu synchronizovat své kontakty s dodavateli, zákazníky nebo bankovními účty v jiných částech aplikace, můžete si pro ně nastavit obchodní vztah.</span><span class="sxs-lookup"><span data-stu-id="d14b0-109">If you plan to synchronize your contacts with vendors, customers, or bank accounts in other parts of the application, you may want to set up a business relation for them.</span></span>

## <a name="to-define-a-business-relation-code"></a><span data-ttu-id="d14b0-110">Definování kódu obchodních vztahů</span><span class="sxs-lookup"><span data-stu-id="d14b0-110">To define a business relation code</span></span>
<span data-ttu-id="d14b0-111">Kód obchodních vztahů definuje kategorii nebo typ obchodního vztahu, jako je například BANKA nebo PRÁVO.</span><span class="sxs-lookup"><span data-stu-id="d14b0-111">The business relation code defines a category or type of the business relationship, such as BANK or Law.</span></span> <span data-ttu-id="d14b0-112">Můžete mít několik kódů obchodních vztahů.</span><span class="sxs-lookup"><span data-stu-id="d14b0-112">You can have several business relation codes.</span></span> <span data-ttu-id="d14b0-113">Chcete-li definovat obchodní vztah, použijete okno **Obchodní vztahy**.</span><span class="sxs-lookup"><span data-stu-id="d14b0-113">To define the business relation, you use the **Business Relations** window.</span></span>

1. <span data-ttu-id="d14b0-114">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Obchodní vztahy** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="d14b0-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Business Relations**, and then choose the related link.</span></span>
2. <span data-ttu-id="d14b0-115">Vyberte tlačítko **Nový** a vyplňte kód a popis.</span><span class="sxs-lookup"><span data-stu-id="d14b0-115">Choose the **New** action, and fill in a code and description.</span></span> <span data-ttu-id="d14b0-116">Kód může mít maximálně 11 znaků a může obsahovat jakékoli kombinace čísel a písmen.</span><span class="sxs-lookup"><span data-stu-id="d14b0-116">The code can be a maximum of 11 characters, and can be any combination of numbers and letters.</span></span>

## <span data-ttu-id="d14b0-117"><a name="AssignBusRelContact"></a> Přiřazení obchodních vztahů ke kontaktu</span><span class="sxs-lookup"><span data-stu-id="d14b0-117"><a name="AssignBusRelContact"></a> To assign business relations to a contact</span></span>
<span data-ttu-id="d14b0-118">Nemůžete přiřadit obchodní vztahy ke kontaktním osobám - pouze společnosti.</span><span class="sxs-lookup"><span data-stu-id="d14b0-118">You cannot assign business relations to a contact person - only companies.</span></span>

1. <span data-ttu-id="d14b0-119">Otevřete kontakt.</span><span class="sxs-lookup"><span data-stu-id="d14b0-119">Open the contact.</span></span>
2. <span data-ttu-id="d14b0-120">Zvolte akci **Společnost** a poté akci **Obchodní vztahy**.</span><span class="sxs-lookup"><span data-stu-id="d14b0-120">Choose the **Company** action, and then the **Business Relations** action.</span></span>

    <span data-ttu-id="d14b0-121">Otevře se okno **Obchodní vztahy kontaktu**.</span><span class="sxs-lookup"><span data-stu-id="d14b0-121">The **Contact Business Relations** window opens.</span></span>
3. <span data-ttu-id="d14b0-122">V poli **Kód obchodních vztahů** vyberte obchodní vztah, který chcete přiřadit.</span><span class="sxs-lookup"><span data-stu-id="d14b0-122">In the **Business Relation Code** field, select the business relation you want to assign.</span></span>

<span data-ttu-id="d14b0-123">Opakujte tyto kroky, abyste přiřadili tolik obchodních vztahů, kolik chcete.</span><span class="sxs-lookup"><span data-stu-id="d14b0-123">Repeat these steps to assign as many business relations as you want.</span></span> <span data-ttu-id="d14b0-124">Obchodní vztahy můžete také přidělit stejným postupem ze seznamu kontaktů.</span><span class="sxs-lookup"><span data-stu-id="d14b0-124">You can also assign business relations from the contact list by following the same procedure.</span></span>

<span data-ttu-id="d14b0-125">Počet obchodních vztahů, které jste přidali ke kontaktu, se zobrazuje v poli **Počet obchodních vztahů** v sekci **Segmentace** v okně **Kontakt**.</span><span class="sxs-lookup"><span data-stu-id="d14b0-125">The number of business relations you have assigned to the contact is displayed in the **No. of Business Relations** field in the **Segmentation** section in the **Contact** window.</span></span>

<span data-ttu-id="d14b0-126">Po přidělení obchodních vztahů k vašim kontaktům můžete pomocí těchto informací vybrat kontakty pro vaše segmenty.</span><span class="sxs-lookup"><span data-stu-id="d14b0-126">After you have assigned business relations to your contacts, you can use this information to select contacts for your segments.</span></span> <span data-ttu-id="d14b0-127">Další informace naleznete v tématu [Návod: Přidání kontaktů do segmentů](marketing-add-contact-segment.md).</span><span class="sxs-lookup"><span data-stu-id="d14b0-127">For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="d14b0-128">Viz také</span><span class="sxs-lookup"><span data-stu-id="d14b0-128">See Also</span></span>
[<span data-ttu-id="d14b0-129">Vytvoření kontaktních společností</span><span class="sxs-lookup"><span data-stu-id="d14b0-129">Creating Contact Companies</span></span>](marketing-create-contact-companies.md)  
<span data-ttu-id="d14b0-130">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="d14b0-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

