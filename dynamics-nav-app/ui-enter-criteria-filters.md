---
title: "Vkládání kriterií do filtrů"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: df386e1195db385ee053b69fec0f5082d8df4116
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="entering-criteria-in-filters"></a><span data-ttu-id="10639-102">Vkládání kriterií do filtrů</span><span class="sxs-lookup"><span data-stu-id="10639-102">Entering Criteria in Filters</span></span>
<span data-ttu-id="10639-103">Chcete-li hledat data, například názvy zákazníků, adresy nebo skupiny produktů, vložte vaše kritéria.</span><span class="sxs-lookup"><span data-stu-id="10639-103">When you want to search for data, such as customer names, addresses, or product groups, you enter criteria.</span></span> <span data-ttu-id="10639-104">Ve vyhledávacích kritériích můžete použít všechna čísla a písmena, která běžně používáte v konkrétním poli.</span><span class="sxs-lookup"><span data-stu-id="10639-104">In search criteria you can use all the numbers and letters that you normally use in the specific field.</span></span> <span data-ttu-id="10639-105">K dalšímu filtrování výsledků můžete použít speciální symboly.</span><span class="sxs-lookup"><span data-stu-id="10639-105">In addition, you can use special symbols to further filter the results.</span></span>

## <a name="searching-using-the-quick-filter"></a><span data-ttu-id="10639-106">Vyhledávání pomocí rychlého filtru</span><span class="sxs-lookup"><span data-stu-id="10639-106">Searching using the Quick Filter</span></span>
<span data-ttu-id="10639-107">Pomocí rychlého filtru můžete filtrovat všechny stránky.</span><span class="sxs-lookup"><span data-stu-id="10639-107">You can add filters to all pages by using the Quick Filter.</span></span> <span data-ttu-id="10639-108">Rychlý filtr je aktivován výběrem ikony lupy v pravém horním rohu stránky.</span><span class="sxs-lookup"><span data-stu-id="10639-108">The Quick Filter is enabled by choosing the magnifier icon in the top right corner of a page.</span></span> <span data-ttu-id="10639-109">Tento typ filtrování slouží k rychlému zadání kritérií.</span><span class="sxs-lookup"><span data-stu-id="10639-109">This filtering type is used for a fast entry of criteria.</span></span>

<span data-ttu-id="10639-110">**Důležité**: Rychlý filtr poskytuje snadný přístup k vyfiltrovaným datům zadáním prostého textu, ale poskytuje také mnoho kritérií pro vyhledávání.</span><span class="sxs-lookup"><span data-stu-id="10639-110">**Important**: The Quick Filter provides an easy access to filter data by entering plain text, but does also provide a lot of search criteria options.</span></span> <span data-ttu-id="10639-111">V závislosti na tom, zda zadáváte prostý text nebo text včetně symbolů se rychlý filtr chová jinak.</span><span class="sxs-lookup"><span data-stu-id="10639-111">Depending on whether you enter plain text or text including symbols, the Quick Filter behaves differently.</span></span>  
- <span data-ttu-id="10639-112">Pokud do vyhledávacích kritérií zadáte obyčejný text, kritéria vyhledávání budou vyhledávány bez rozlišení malých a velkých písmen.</span><span class="sxs-lookup"><span data-stu-id="10639-112">If you enter plain text in the search criteria, the search criteria is interpreted as a case insensitive search that contains certain text.</span></span>  
- <span data-ttu-id="10639-113">Pokud v kritériích vyhledávání zadáte text obsahující symboly, kritéria vyhledávání budou interpretována přesně tak, jak jste je zadali a vyhledávání bude citlivé na malá a velká písmena.</span><span class="sxs-lookup"><span data-stu-id="10639-113">If you enter text including symbols in the search criteria, the search criteria is interpreted exactly as you entered it, and the search is case sensitive.</span></span>

### <a name="quick-filter-criteria"></a><span data-ttu-id="10639-114">Kritéria rychlého filtru</span><span class="sxs-lookup"><span data-stu-id="10639-114">Quick filter criteria</span></span>
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH><span data-ttu-id="10639-115">Vyhledávací kritérium</span><span class="sxs-lookup"><span data-stu-id="10639-115">Search Criteria</span></span></TH>
    <TH><span data-ttu-id="10639-116">Interpretování jako..</span><span class="sxs-lookup"><span data-stu-id="10639-116">Interpreted as...</span></span></TH>
    <TH><span data-ttu-id="10639-117">Výsledek..</span><span class="sxs-lookup"><span data-stu-id="10639-117">Returns...</span></span></TH>
  </TR>
  <TR>
    <TD><span data-ttu-id="10639-118">>man</span><span class="sxs-lookup"><span data-stu-id="10639-118">>man</span></span></TD>
    <TD><span data-ttu-id="10639-119">@*man*</span><span class="sxs-lookup"><span data-stu-id="10639-119">@*man*</span></span></TD>
    <TD><span data-ttu-id="10639-120">Všechny záznamy obsahující text „man“ bez ohledu na malá a velká písmena.</span><span class="sxs-lookup"><span data-stu-id="10639-120">All records that contain the text man and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="10639-121">>se</span><span class="sxs-lookup"><span data-stu-id="10639-121">>se</span></span></TD>
    <TD><span data-ttu-id="10639-122">@*se*</span><span class="sxs-lookup"><span data-stu-id="10639-122">@*se*</span></span></TD>
    <TD><span data-ttu-id="10639-123">Všechny záznamy obsahující text „se“ bez ohledu na malá a velká písmena.</span><span class="sxs-lookup"><span data-stu-id="10639-123">All records that contain the text se and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="10639-124">>Man*</span><span class="sxs-lookup"><span data-stu-id="10639-124">>Man*</span></span></TD>
    <TD><span data-ttu-id="10639-125">Začíná Man a bere ohled na velká a malá písmena.</span><span class="sxs-lookup"><span data-stu-id="10639-125">Starts with Man and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="10639-126">Všechny záznamy začínající na text „Man“</span><span class="sxs-lookup"><span data-stu-id="10639-126">All records that start with the text Man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="10639-127">'man‘</span><span class="sxs-lookup"><span data-stu-id="10639-127">'man'</span></span></TD>
    <TD><span data-ttu-id="10639-128">Přímo obsahuje řetězec man s ohledem na velká a malá písmena.</span><span class="sxs-lookup"><span data-stu-id="10639-128">An exact text and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="10639-129">Všechny záznamy, které přesně odpovídají textu „man“</span><span class="sxs-lookup"><span data-stu-id="10639-129">All records that match man exactly.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="10639-130">@*man</span><span class="sxs-lookup"><span data-stu-id="10639-130">@*man</span></span></TD>
    <TD><span data-ttu-id="10639-131">Končí na man bez ohledu na velká a malá písmena.</span><span class="sxs-lookup"><span data-stu-id="10639-131">Ends with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="10639-132">Všechny záznamy končící na „man“.</span><span class="sxs-lookup"><span data-stu-id="10639-132">All records that end with man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="10639-133">@man*</span><span class="sxs-lookup"><span data-stu-id="10639-133">@man*</span></span></TD>
    <TD><span data-ttu-id="10639-134">Začíná a nebere ohled na velká a malá písmena.</span><span class="sxs-lookup"><span data-stu-id="10639-134">Starts with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="10639-135">Všechny záznamy začínající na man.</span><span class="sxs-lookup"><span data-stu-id="10639-135">All records that start with man.</span></span></TD>
  </TR>
</TABLE>

<span data-ttu-id="10639-136">**Poznámka**: Při filtrování polí výčtu nelze použít zástupný znak. Například pole **Stav** v Prodejních objednávkách.</span><span class="sxs-lookup"><span data-stu-id="10639-136">**Note**: You cannot use a wildcard when filtering on enumeration fields, such as the **Status** field on sales orders.</span></span> <span data-ttu-id="10639-137">Chcete-li zadat filtr pro tento typ pole, můžete zadat číselnou hodnotu jako parametr filtrování.</span><span class="sxs-lookup"><span data-stu-id="10639-137">To enter a filter for this type of field, you can enter the numeric value as a filtering parameter.</span></span> <span data-ttu-id="10639-138">Například v poli **Stav** na prodejní objednávce, která má hodnoty **Otevřeno**, **Vydáno**, **Čeká na schválení** a **Čeká na zálohu**, použijte hodnoty **0**, **1**, **2** a **3** pro filtrování těchto voleb.</span><span class="sxs-lookup"><span data-stu-id="10639-138">For example, in the **Status** field on a sales order that has the values **Open**, **Released**, **Pending Approval**, and **Pending Prepayment**, use the values **0**, **1**, **2**, and **3** to filter for these options.</span></span>  

## <a name="see-also"></a><span data-ttu-id="10639-139">Viz také</span><span class="sxs-lookup"><span data-stu-id="10639-139">See Also</span></span>
<span data-ttu-id="10639-140">[Práce s [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="10639-140">[Work with Dynamics NAV](ui-work-product.md)</span></span>

