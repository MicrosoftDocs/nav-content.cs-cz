---
title: "Návod: Nastavení údržby dlouhodobého majetku"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ace0fb13d2be71c7204f16f34f6b65b54ff98230
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-fixed-asset-maintenance"></a><span data-ttu-id="c4745-102">Návod: Nastavení údržby dlouhodobého majetku</span><span class="sxs-lookup"><span data-stu-id="c4745-102">How to: Set Up Fixed Asset Maintenance</span></span>
<span data-ttu-id="c4745-103">Ke správě údržby dlouhodobého majetku musíte nejprve nastavit obecné informace o údržbě, účet pro zaúčtování a kódy údržby pro typ práce, např. služba rutiny nebo oprava.</span><span class="sxs-lookup"><span data-stu-id="c4745-103">To manage fixed asset maintenance, you must first set up some general maintenance information, a posting account for maintenance costs, and maintenance codes for types of work, such as Routine Service or Repair.</span></span>

## <a name="to-set-up-general-maintenance-information"></a><span data-ttu-id="c4745-104">Nastavení obecných informací o údržbě</span><span class="sxs-lookup"><span data-stu-id="c4745-104">To set up general maintenance information</span></span>
<span data-ttu-id="c4745-105">Pokud nastavíte pole pro údržbu, můžete účtovat výdaje za údržbu z deníku dlouhodobého majetku.</span><span class="sxs-lookup"><span data-stu-id="c4745-105">If you set up the fields for maintenance, you can post maintenance expenses from the fixed asset journal.</span></span>
1. <span data-ttu-id="c4745-106">V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zvolte **Dlouhodobý majetek** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="c4745-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.</span></span>
2. <span data-ttu-id="c4745-107">Vybrat dlouhodobý majetek, pro který chcete definovat pokrytí pojištění a pak vyberte akci **Úpravy**.</span><span class="sxs-lookup"><span data-stu-id="c4745-107">Select the fixed asset that you to define insurance coverage for, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="c4745-108">Na záložce s náhledem **Údržba** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="c4745-108">On the **Maintenance** FastTab, fill in the fields as necessary.</span></span> <span data-ttu-id="c4745-109">Vyberte pole a přečtěte si krátký popis pole nebo odkaz pro více informací.</span><span class="sxs-lookup"><span data-stu-id="c4745-109">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-maintenance-codes"></a><span data-ttu-id="c4745-110">Nastavení kódů údržby</span><span class="sxs-lookup"><span data-stu-id="c4745-110">To set up maintenance codes</span></span>  
<span data-ttu-id="c4745-111">Když účtujete náklady na údržbu z finančního deníku, vyplníte pole **Kód údržby** k zaznamenání k jaké údržbě došlo, např. službě rutiny nebo opravě.</span><span class="sxs-lookup"><span data-stu-id="c4745-111">When you post maintenance costs from a general journal, you fill in the **Maintenance Code** field to record what kind of maintenance has been performed, such as routine service or repair.</span></span>
1. <span data-ttu-id="c4745-112">V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zvolte **Údržba** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="c4745-112">In the top right corner, choose the **Search for Page or Report** icon, enter **Maintenance**, and then choose the related link.</span></span>
2. <span data-ttu-id="c4745-113">V okně **Údržba** nastavte kódy pro různé typy práce údržby.</span><span class="sxs-lookup"><span data-stu-id="c4745-113">In the **Maintenance** window, set up codes for different types of maintenance work.</span></span>

## <a name="to-set-up-maintenance-expense-accounts"></a><span data-ttu-id="c4745-114">Nastavení účtů výdajů za údržbu</span><span class="sxs-lookup"><span data-stu-id="c4745-114">To set up maintenance expense accounts</span></span>  
<span data-ttu-id="c4745-115">K účtování výdajů za údržbu musíte nejprve zvolit číslo účtu v okně **Účto skupiny DM**.</span><span class="sxs-lookup"><span data-stu-id="c4745-115">To post maintenance costs, you must first enter an account number in the **FA Posting Groups** window.</span></span>
1. <span data-ttu-id="c4745-116">V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zvolte **Účto skupiny DM** a pak vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="c4745-116">In the top right corner, choose the **Search for Page or Report** icon, enter **FA Posting Groups**, and then choose the related link.</span></span>
2. <span data-ttu-id="c4745-117">Vyplňte pole **Účet nákladů údržby** pro každou účto skupinu.</span><span class="sxs-lookup"><span data-stu-id="c4745-117">Fill in the **Maintenance Expense Account** field for each posting group.</span></span>

<span data-ttu-id="c4745-118">**POZNÁMKA**: K definování, že výdaje za údržbu jsou přiděleny k oddělení nebo projektům, nastavte alokační klíče.</span><span class="sxs-lookup"><span data-stu-id="c4745-118">**Note**: To define that maintenance costs are allocated to departments or projects, set up an allocation keys.</span></span> <span data-ttu-id="c4745-119">Pro další informace viz [Návod: Nastavení funkcí obecného dlouhodobého majetku](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="c4745-119">For more information, see [How to: Set Up General Fixed Assets Features](fa-how-setup-general.md).</span></span>

## <a name="see-also"></a><span data-ttu-id="c4745-120">Viz také</span><span class="sxs-lookup"><span data-stu-id="c4745-120">See Also</span></span>
[<span data-ttu-id="c4745-121">Nastavení dlouhodobého majetku</span><span class="sxs-lookup"><span data-stu-id="c4745-121">Set Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="c4745-122">Správa dlouhodobého majetku</span><span class="sxs-lookup"><span data-stu-id="c4745-122">Manage Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="c4745-123">Finance</span><span class="sxs-lookup"><span data-stu-id="c4745-123">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="c4745-124">[Vítejte v [!INCLUDE[navnow](includes/navnow_md.md)]](across-get-started.md)</span><span class="sxs-lookup"><span data-stu-id="c4745-124">[Welcome to Dynamics NAV](across-get-started.md)</span></span>

