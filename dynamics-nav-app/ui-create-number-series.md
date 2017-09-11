---
title: "Vytváření číselných řad"
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
ms.openlocfilehash: e42e5ed139b2487fea13ef0fd57757035764addd
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="create-number-series"></a><span data-ttu-id="5ec83-102">Vytváření číselných řad</span><span class="sxs-lookup"><span data-stu-id="5ec83-102">Create Number Series</span></span>

<span data-ttu-id="5ec83-103">Pro každou společnost, kterou jste založili, musíte přiřadit jedinečné identifikační kódy věcem, jako jsou účty hlavní knihy, účty zákazníků a dodavatelů, faktury a dokumenty.</span><span class="sxs-lookup"><span data-stu-id="5ec83-103">For each company that you set up, you need to assign unique identification codes to things such as general ledger accounts, customer and vendor accounts, invoices, and documents.</span></span> <span data-ttu-id="5ec83-104">Číslování je důležité nejen pro identifikaci,</span><span class="sxs-lookup"><span data-stu-id="5ec83-104">Numbering is important not only for identification.</span></span> <span data-ttu-id="5ec83-105">dobře navržený systém číslování také usnadňuje správu a snadnou analýzu společnosti a může snížit počet chyb, ke kterým dochází při zadávání dat.</span><span class="sxs-lookup"><span data-stu-id="5ec83-105">A well-designed numbering system also makes the company more manageable and easy to analyze, and can reduce the number of errors that occur in data entry.</span></span>

<span data-ttu-id="5ec83-106">Můžete nastavit kompletní číslovací systém s neomezeným počtem číselných řad.</span><span class="sxs-lookup"><span data-stu-id="5ec83-106">You can set up a complete numbering system with an unlimited number of number series.</span></span> <span data-ttu-id="5ec83-107">Číselné řady můžete používat pro všechny typy dokumentů a deníků, stejně jako pro hlavní údaje, jako jsou zákazníci, položky a projekty.</span><span class="sxs-lookup"><span data-stu-id="5ec83-107">You can use number series for all types of documents and journals, as well as for master data such as customers, items, and jobs.</span></span>

<span data-ttu-id="5ec83-108">Můžete kombinovat použití číselných řad s manuálním číslováním.</span><span class="sxs-lookup"><span data-stu-id="5ec83-108">You can combine the use of number series with manual numbering.</span></span>

<span data-ttu-id="5ec83-109">Systém číslování vytvoříte nastavením jednoho nebo více kódů pro každý typ hlavních dat nebo dokumentu.</span><span class="sxs-lookup"><span data-stu-id="5ec83-109">You create a numbering system by setting up one or more codes for each type of master data or document.</span></span> <span data-ttu-id="5ec83-110">Například můžete nastavit jeden kód pro číslování zákazníků, jiný kód pro číslování prodejních faktur a další kód pro číslování dokumentů ve všeobecných denících.</span><span class="sxs-lookup"><span data-stu-id="5ec83-110">For example, you can set up one code for numbering customers, another code for numbering sales invoices, and another code for numbering documents in general journals.</span></span>

<span data-ttu-id="5ec83-111">Pokud nastavíte kód, musíte nastavit alespoň jednu číselnou řadu.</span><span class="sxs-lookup"><span data-stu-id="5ec83-111">After you have set up a code, you set must set up at least one number series line.</span></span> <span data-ttu-id="5ec83-112">Řádek číselné řady obsahuje informace jako první a poslední číslo v sérii a počáteční datum.</span><span class="sxs-lookup"><span data-stu-id="5ec83-112">The number series line contains information such as the first and last number in the series and the starting date.</span></span> <span data-ttu-id="5ec83-113">Můžete nastavit více než jednu číselnou řadu pro každý kód číselné řady s jiným počátečním datem pro každý řádek.</span><span class="sxs-lookup"><span data-stu-id="5ec83-113">You can set up more than one number series line per number series code, with a different starting date for each line.</span></span> <span data-ttu-id="5ec83-114">Řady budou použity postupně počínaje každou sérií v příslušném počátečním datu.</span><span class="sxs-lookup"><span data-stu-id="5ec83-114">The series will be used consecutively, starting each series on the respective starting date.</span></span>

<span data-ttu-id="5ec83-115">Chcete-li pro jeden typ hlavních dat použít více než jeden kód číselné řady - například chcete-li použít různé číselné řady pro různé kategorie zboží - můžete použít vztahy číselných řad.</span><span class="sxs-lookup"><span data-stu-id="5ec83-115">If you want to use more than one number series code for one type of master data - for example, if you want to use different number series for different categories of items - you can use number series relationships.</span></span>

<span data-ttu-id="5ec83-116">Vedle čísel, které přiřadíte ručně nebo pomocí systému číslování, jsou všechny transakce (záznamy v knihách) automaticky přiděleny po sobě jdoucím číslům.</span><span class="sxs-lookup"><span data-stu-id="5ec83-116">In addition to the numbers that you assign manually or by use of the numbering system, all transactions (ledger entries) are automatically assigned consecutive numbers.</span></span> <span data-ttu-id="5ec83-117">Tyto čísla můžete vidět v políčku **Číslo položky**</span><span class="sxs-lookup"><span data-stu-id="5ec83-117">These numbers can be seen in the **Entry No.**</span></span> <span data-ttu-id="5ec83-118">v okně souvisejících položek.</span><span class="sxs-lookup"><span data-stu-id="5ec83-118">field in all the ledger entry windows.</span></span> <span data-ttu-id="5ec83-119">Nemůžete editovat nebo mazat tyto čísla.</span><span class="sxs-lookup"><span data-stu-id="5ec83-119">You cannot modify or delete these numbers.</span></span>

## <a name="to-create-relationships-between-number-series"></a><span data-ttu-id="5ec83-120">Vytváření vztahů mezi číselnými řadami</span><span class="sxs-lookup"><span data-stu-id="5ec83-120">To create relationships between number series</span></span>
<span data-ttu-id="5ec83-121">Pokud jste nastavili více než jednu číselnou řadu pro stejný druh informací nebo transakcí, můžete vytvářet vztahy mezi kódy.</span><span class="sxs-lookup"><span data-stu-id="5ec83-121">If you have set up more than one number series code for the same kind of basic information or transactions, you can create relationships between the codes.</span></span> <span data-ttu-id="5ec83-122">Tato funkce vám pomůže  při rozhodování mezi kódy pokud používáte čísla.</span><span class="sxs-lookup"><span data-stu-id="5ec83-122">This feature can assist you in deciding among the codes when you use a number.</span></span>

1. <span data-ttu-id="5ec83-123">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Číselná řada** a poté vyberte příslušný odkaz.</span><span class="sxs-lookup"><span data-stu-id="5ec83-123">In the top right corner, choose the **Search for Page or Report** icon, enter **No. Series**, and then choose the related link.</span></span>
2. <span data-ttu-id="5ec83-124">Vyberte řádek s číselnou řadou, pro kterou chcete vytvořit vztahy, a poté zvolte **Vztah**.</span><span class="sxs-lookup"><span data-stu-id="5ec83-124">Select the line with the number series you want to create relationships for and then choose **Relationships**.</span></span>
3. <span data-ttu-id="5ec83-125">V poli **Kód řady** vložte kód číselné řady, kterou chcete spojit s řadou, kterou jste vybrali v kroku 2.</span><span class="sxs-lookup"><span data-stu-id="5ec83-125">In the **Series Code** field, enter the code for the number series that you want to relate to the series you selected in step 2.</span></span>
4. <span data-ttu-id="5ec83-126">Přidejte řádek pro každý kód, který chcete spojit s vybranou číselnou řadou.</span><span class="sxs-lookup"><span data-stu-id="5ec83-126">Add a line for each code that you want to relate to the selected number series.</span></span>
5. <span data-ttu-id="5ec83-127">Zavřete okno.</span><span class="sxs-lookup"><span data-stu-id="5ec83-127">Close the window.</span></span>

<span data-ttu-id="5ec83-128">Nyní, když nastavíte něco, co vyžaduje číslo, můžete použít vztahy, které jste vytvořili k výběru mezi souvisejícími číselnými řadami.</span><span class="sxs-lookup"><span data-stu-id="5ec83-128">Now when you set up something that requires a number, you can use the relationships you created to select among the related number series.</span></span>

## <a name="see-also"></a><span data-ttu-id="5ec83-129">Viz také</span><span class="sxs-lookup"><span data-stu-id="5ec83-129">See Also</span></span>
[<span data-ttu-id="5ec83-130">Práce s Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="5ec83-130">Work with Dynamics NAV</span></span>](ui-work-product.md)

