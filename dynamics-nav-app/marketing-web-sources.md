---
title: "Nastavení webových zdrojů pro kontaktní společnosti"
description: "Můžete definovat internetové nebo webové zdroje přiřazené ke kontaktní společnosti jako pomoc pro identifikaci, informací o kontaktech, které chcete."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: internet
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c744a4fb90c65b27fce8da3c37379cd93b40a8f6
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-web-sources-for-contact-companies"></a><span data-ttu-id="b9a0c-103">Návod: Nastavení webových zdrojů pro kontaktní společnosti</span><span class="sxs-lookup"><span data-stu-id="b9a0c-103">How to: Set Up Web Sources for Contact Companies</span></span>
<span data-ttu-id="b9a0c-104">Můžete použít webové zdroje se svými kontaktními společnostmi například k identifikaci vyhledávačů a webových stránek na internetu, které chcete použít k vyhledání informací o kontaktech.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-104">You can use web sources with your contact companies to identify, for example, search engines and web sites, on the Internet that you want to use to search for information about the contacts.</span></span> <span data-ttu-id="b9a0c-105">Při přiřazování webových zdrojů určíte vyhledávač a vyhledávací slovo, které aplikace použije k vyhledání požadovaných informací.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-105">When assigning web sources, you specify which search engine and search word the application will use to find the requested information.</span></span>

<span data-ttu-id="b9a0c-106">Použití webových zdrojů v kontaktech je proces o dvou krocích.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-106">Using web sources on contacts is a two-step process.</span></span> <span data-ttu-id="b9a0c-107">Nejprve definujete kód webových zdrojů.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-107">First, you define the web source code.</span></span> <span data-ttu-id="b9a0c-108">Pro každý webový zdroj stačí tento krok provést pouze jednou.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-108">You only have to perform this step one time for each web source.</span></span> <span data-ttu-id="b9a0c-109">Jakmile máte kód pro webové zdroje, můžete začít přiřazovat kód ke kontaktním osobám.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-109">Once you have a web source code, you can start to assign the code to contact persons.</span></span>

## <a name="to-define-a-web-source-code"></a><span data-ttu-id="b9a0c-110">Definování kódu webového zdroje</span><span class="sxs-lookup"><span data-stu-id="b9a0c-110">To define a web source code</span></span>
1. <span data-ttu-id="b9a0c-111">Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **webové zdroje** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Web Sources**, and then choose the related link.</span></span>
2. <span data-ttu-id="b9a0c-112">Zvolte akci **Nový**.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-112">Choose the **New** actions.</span></span>
3. <span data-ttu-id="b9a0c-113">Vyplňte pole **Kód** , **Popis** a **URL** .</span><span class="sxs-lookup"><span data-stu-id="b9a0c-113">Fill in the **Code**, **Description**, and **URL** fields.</span></span>

    <span data-ttu-id="b9a0c-114">Zadejte %1 v poli **URL** a vložte zástupný symbol pro hledané slovo do URL.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-114">Type %1 in the **URL** field to insert a placeholder for a search word in the URL.</span></span> <span data-ttu-id="b9a0c-115">Při spuštění webového zdroje z kontaktu je znak %1 nahrazen hledaným slovem, například názvem společnosti, kterou jste zadali do okna **Webové zdroje kontaktů**.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-115">When you launch the web source from a contact, the %1 is replaced with the search word, for example, the name of the company that you have entered in the **Contact Web Sources** window.</span></span>

<span data-ttu-id="b9a0c-116">Opakujte tyto kroky k nastavení tolika webových zdrojů, kolik chcete.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-116">Repeat these steps to set up as many web sources as you want.</span></span>

## <a name="to-assign-web-sources-to-a-contact-company"></a><span data-ttu-id="b9a0c-117">Přiřazení webových zdrojů ke kontaktní společnosti</span><span class="sxs-lookup"><span data-stu-id="b9a0c-117">To assign web sources to a contact company</span></span>
<span data-ttu-id="b9a0c-118">Při přiřazování webových zdrojů určíte vyhledávač a hledané slovo, které aplikace použije k vyhledání požadovaných informací.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-118">When assigning web sources, you specify which search engine and search word that the application will use to find the requested information.</span></span>

1. <span data-ttu-id="b9a0c-119">Otevřete kontakt.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-119">Open the contact.</span></span>
2. <span data-ttu-id="b9a0c-120">Zvolte akci **Společnost** a poté akci **Webové zdroje**.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-120">Choose the **Company** action, and then choose the **Web Sources** action.</span></span> <span data-ttu-id="b9a0c-121">Otevře se okno **Webové zdroje kontaktů**.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-121">The **Contact Web Sources** window opens.</span></span>
3. <span data-ttu-id="b9a0c-122">V poli **Kód webových zdrojů** vyberte webový zdroj, který chcete přiřadit.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-122">In the **Web Source Code** field, choose the web source you want to assign.</span></span>
4. <span data-ttu-id="b9a0c-123">Do pole **Hledané slovo** zadejte hledané slovo, které chcete použít k nalezení informací.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-123">In the **Search Word** field, enter the search word that you want to use to find the information.</span></span>

<span data-ttu-id="b9a0c-124">Opakujte tyto kroky, abyste přiřadili tolik webových zdrojů, kolik chcete.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-124">Repeat these steps to assign as many web sources as you want.</span></span>

<span data-ttu-id="b9a0c-125">Můžete také stejným postupem přiřadit webové zdroje z okna **Seznam kontaktů**.</span><span class="sxs-lookup"><span data-stu-id="b9a0c-125">You can also assign web sources from the **Contact List** window by following the same procedure.</span></span>

## <a name="see-also"></a><span data-ttu-id="b9a0c-126">Viz také</span><span class="sxs-lookup"><span data-stu-id="b9a0c-126">See Also</span></span>
[<span data-ttu-id="b9a0c-127">Vytvoření kontaktních společností</span><span class="sxs-lookup"><span data-stu-id="b9a0c-127">Creating Contact Companies</span></span>](marketing-create-contact-companies.md)  
<span data-ttu-id="b9a0c-128">[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="b9a0c-128">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

