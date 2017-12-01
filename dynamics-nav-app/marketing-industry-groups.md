---
title: "Nastavení průmyslové skupiny pro kontaktní společnosti"
description: "Popisuje jak definovat průmyslové skupiny a přiřadit je ke společnosti, například maloobchodní průmysl nebo automobilový průmysl."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 303b619c4188a1b74a9c325c3458e244b364cd37
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-set-up-industry-groups-for-contact-companies"></a><span data-ttu-id="f5ad6-103">Návod: Nastavení průmyslové skupiny pro kontaktní společnosti</span><span class="sxs-lookup"><span data-stu-id="f5ad6-103">How to: Set Up Industry Groups for Contact Companies</span></span>
<span data-ttu-id="f5ad6-104">Používáte průmyslové skupiny k označení typu průmyslu, ke kterému patří vaše kontakty, například maloobchod nebo automobilový průmysl.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-104">You use industry groups to indicate the type of industry to which your contacts belong, for example, the retail industry or the automobile industry.</span></span>

<span data-ttu-id="f5ad6-105">Použití průmyslových skupin v kontaktech je proces o dvou krocích.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-105">Using industry groups on contacts is a two-step process.</span></span> <span data-ttu-id="f5ad6-106">Nejprve definujete kód průmyslové skupiny.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-106">First, you define the industry group code.</span></span> <span data-ttu-id="f5ad6-107">Pro každou průmyslovou skupinu stačí tento krok provést pouze jednou.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-107">You only have to perform this step one time for each industry group.</span></span> <span data-ttu-id="f5ad6-108">Jakmile máte průmyslovou skupinu, můžete začít přiřazovat kódy ke kontaktním společnostem.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-108">Once you have an industry group code, you can start to assign the code to contact companies.</span></span>

> [!NOTE]  
>   <span data-ttu-id="f5ad6-109">Pokud máte v úmyslu synchronizovat své kontakty s dodavateli, zákazníky nebo bankovními účty v jiných částech aplikace, můžete si pro ně nastavit obchodní vztah.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-109">If you plan to synchronize your contacts with vendors, customers, or bank accounts in other parts of the application, you may want to set up a business relation for them.</span></span>

## <a name="to-define-an-industry-group-code"></a><span data-ttu-id="f5ad6-110">Definování kódu průmyslové skupiny</span><span class="sxs-lookup"><span data-stu-id="f5ad6-110">To define an industry group code</span></span>
<span data-ttu-id="f5ad6-111">Kód průmyslové skupiny definuje typ nebo kategorii skupiny, např. REKLAMA pro reklamu nebo TISK pro televizní a rozhlasové vysílání.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-111">The industry group code defines the type or category of the group, such as ADVERT for advertising, or PRESS, for TV and radio.</span></span> <span data-ttu-id="f5ad6-112">Můžete mít několik kódů průmyslových skupin.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-112">You can have several industry group codes.</span></span> <span data-ttu-id="f5ad6-113">Chcete-li definovat průmyslové skupiny, použijete okno **Průmyslové skupiny**.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-113">To define the industry groups, you use the **Industry Groups** window.</span></span>

1. <span data-ttu-id="f5ad6-114">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Průmyslové skupiny** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Industry Groups**, and then choose the related link.</span></span>
2. <span data-ttu-id="f5ad6-115">Vyberte tlačítko **Nový** a vyplňte kód a popis.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-115">Choose the **New** action, and fill in a code and description.</span></span> <span data-ttu-id="f5ad6-116">Kód může mít maximálně 11 znaků a může obsahovat jakékoli kombinace čísel a písmen.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-116">The code can be a maximum of 11 characters, and can be any combination of numbers and letters.</span></span>

## <span data-ttu-id="f5ad6-117"><a name="AssignIndustryGroupContact"></a> Přiřazení průmyslových skupin ke kontaktu</span><span class="sxs-lookup"><span data-stu-id="f5ad6-117"><a name="AssignIndustryGroupContact"></a> To assign industry groups to a contact</span></span>
<span data-ttu-id="f5ad6-118">Nemůžete přiřadit průmyslové skupiny ke kontaktním osobám - pouze společnosti.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-118">You cannot assign industry groups to a contact person - only companies.</span></span>

1. <span data-ttu-id="f5ad6-119">Otevřete kontakt.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-119">Open the contact.</span></span>
2. <span data-ttu-id="f5ad6-120">Zvolte akci **Společnost** a poté akci **Průmyslové skupiny**.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-120">Choose the **Company** action, and then the **Industry Groups** action.</span></span> <span data-ttu-id="f5ad6-121">Otevře se okno **Průmyslové skupiny kontaktu**.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-121">The **Contact Industry Groups** window opens.</span></span>
3. <span data-ttu-id="f5ad6-122">V poli **Kód průmyslových skupiny** vyberte průmyslové skupiny, které chcete přiřadit.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-122">In the **Industry Groups Code** field, select the industry groups you want to assign.</span></span>

<span data-ttu-id="f5ad6-123">Opakujte tyto kroky, abyste přiřadili tolik průmyslových skupin, kolik chcete.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-123">Repeat these steps to assign as many industry groups as you want.</span></span> <span data-ttu-id="f5ad6-124">Průmyslové skupiny můžete také přiřadit stejným postupem ze seznamu kontaktů.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-124">You can also assign industry groups from the contact list by following the same procedure.</span></span>

<span data-ttu-id="f5ad6-125">Počet průmyslových skupin, které jste přidali ke kontaktu, se zobrazuje v poli **Počet průmyslových skupin** v sekci **Segmentace** v okně **Kontaktu**.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-125">The number of industry groups that you have assigned to the contact is displayed in the **No. of Industry Groups** field in the **Segmentation** section in the **Contact** window.</span></span>

<span data-ttu-id="f5ad6-126">Po přidělení průmyslových skupin k vašim kontaktům můžete pomocí těchto informací vybrat kontakty pro vaše segmenty.</span><span class="sxs-lookup"><span data-stu-id="f5ad6-126">After you have assigned industry groups to your contacts, you can use this information to select contacts for your segments.</span></span> <span data-ttu-id="f5ad6-127">Další informace naleznete v tématu [Návod: Přidání kontaktů do segmentů.](marketing-add-contact-segment.md).</span><span class="sxs-lookup"><span data-stu-id="f5ad6-127">For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="f5ad6-128">Viz také</span><span class="sxs-lookup"><span data-stu-id="f5ad6-128">See Also</span></span>
[<span data-ttu-id="f5ad6-129">Vytvoření kontaktních společností</span><span class="sxs-lookup"><span data-stu-id="f5ad6-129">Creating Contact Companies</span></span>](marketing-create-contact-companies.md)  
<span data-ttu-id="f5ad6-130">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f5ad6-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

