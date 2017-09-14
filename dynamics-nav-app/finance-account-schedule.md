---
title: "Účetní schémata"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ba67e7e09f4375cbdbf53f401fd0f3d83450c9ec
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="account-schedules"></a><span data-ttu-id="f0e93-102">Účetní schémata</span><span class="sxs-lookup"><span data-stu-id="f0e93-102">Account Schedules</span></span>
<span data-ttu-id="f0e93-103">S účetními schématy můžete získat detailní pohled do vašich finančních dat.</span><span class="sxs-lookup"><span data-stu-id="f0e93-103">With account schedules, you can get detailed insights into your financial data.</span></span> <span data-ttu-id="f0e93-104">Můžete nastavit různá rozložení k definování informací, které chcete extrahovat z účtové osnovy. Účtová osnova uchovává vaše finanční data, ale občas můžete chtít získat pohled na data, který účtová osnova nemůže ukázat.</span><span class="sxs-lookup"><span data-stu-id="f0e93-104">You can set up various layouts to define the information that you want to extract from the chart of accounts The chart of accounts stores your financial data, but sometimes you want to get a view on your data that the chart of accounts cannot really show.</span></span> <span data-ttu-id="f0e93-105">Tak použijete účetní schémata pro analýzu čísel na účtech hlavní knihy a pro porovnání položek hlavní knihy s položkami rozpočtu.</span><span class="sxs-lookup"><span data-stu-id="f0e93-105">So you use account schedules to analyze figures in general ledger accounts and to compare general ledger entries with general ledger budget entries.</span></span>
<span data-ttu-id="f0e93-106">Například chcete spočítat mezisoučty pro skupiny účtů a chcete zahrnout tyto mezisoučty do nových součtů atd.</span><span class="sxs-lookup"><span data-stu-id="f0e93-106">For example, you want to calculate subtotals for groups of accounts, and you want to include these subtotals in new totals, and so on.</span></span>
<span data-ttu-id="f0e93-107">[!INCLUDE[navnow](includes/navnow_md.md)] obsahuje ukázkové účetní schémata, která slouží ke generování grafů na domovské stránce.</span><span class="sxs-lookup"><span data-stu-id="f0e93-107">Dynamics NAV includes sample account schedules that are used to generate the charts on your Home page.</span></span> <span data-ttu-id="f0e93-108">Můžete také vytvořit účetní schémata k výpočtu marží na dimenzích jako oddělení nebo skupina odběratelů.</span><span class="sxs-lookup"><span data-stu-id="f0e93-108">You can also create account schedules to calculate profit margins on such dimensions as departments or customer groups.</span></span>  

<span data-ttu-id="f0e93-109">Nastavení účetních schémat vyžaduje porozumění finančním datům v účtové osnově.</span><span class="sxs-lookup"><span data-stu-id="f0e93-109">Setting up account schedules requires an understanding of the financial data in the chart of accounts.</span></span>
<span data-ttu-id="f0e93-110">Například můžete zobrazit hodnoty hlavní knihy jako procenta položek rozpočtu.</span><span class="sxs-lookup"><span data-stu-id="f0e93-110">For example, you can view general ledger entries as percentages of budget entries.</span></span>
<span data-ttu-id="f0e93-111">Můžete použít jedno z výchozích rozložení pro účetní schéma, nebo můžete nastavit své vlastní řádky a sloupce tak, že se můžete rozhodnout přesně které hodnoty si přejete porovnat a jak.</span><span class="sxs-lookup"><span data-stu-id="f0e93-111">You can use one of the default layouts for your account schedule, or you can set up your own rows and columns so that you can decide exactly which figures you wish to compare and how.</span></span>
<span data-ttu-id="f0e93-112">To znamená, že můžete vytvořit tolik upravených finančních výkazů, kolik chcete.</span><span class="sxs-lookup"><span data-stu-id="f0e93-112">This means that you can create as many customized financial statements as you want.</span></span> <span data-ttu-id="f0e93-113">Používejte okno **Účetní schémata** k nastavení účetních schémat.</span><span class="sxs-lookup"><span data-stu-id="f0e93-113">You use the **Account Schedule** window to set up account schedules.</span></span>  

## <a name="account-categories-and-account-schedules"></a><span data-ttu-id="f0e93-114">Kategorie účtů a účetní schémata</span><span class="sxs-lookup"><span data-stu-id="f0e93-114">Account Categories and Account Schedules</span></span>
<span data-ttu-id="f0e93-115">Můžete použít kategorie účtů ke změně rozložení vašich finančních výkazů.</span><span class="sxs-lookup"><span data-stu-id="f0e93-115">You can use account categories to change the layout of your financial statements.</span></span> <span data-ttu-id="f0e93-116">Když jste nastavili vaše kategorie účtů v okně **Kategorie finančního účtů** a zvolili akci **Generovat účetní schémata**, podřízené účetní schémata pro hlavní finanční sestavy budou aktualizovány </span><span class="sxs-lookup"><span data-stu-id="f0e93-116">When you have set up your account categories in the **G/L Account Categories** window, and you choose the **Generate Account Schedules** action, the underlying account schedules for the core financial reports are updated.</span></span> <span data-ttu-id="f0e93-117">při příštím spuštění jedné z těchto sestav, např. výpis zůstatku, nové součty a dílčí položky.</span><span class="sxs-lookup"><span data-stu-id="f0e93-117">the next time you run one of these reports, such as the balance statement, new totals and subentries are added, based on your changes.</span></span> <span data-ttu-id="f0e93-118">Další informace naleznete v tématu [Hlavní kniha a Účtová osnova](finance-setup-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="f0e93-118">For more information, see [The General Ledger and the Chart of Accounts](finance-setup-general-ledger.md).</span></span>    
## <a name="see-also"></a><span data-ttu-id="f0e93-119">Viz také</span><span class="sxs-lookup"><span data-stu-id="f0e93-119">See Also</span></span>
[<span data-ttu-id="f0e93-120">Finance</span><span class="sxs-lookup"><span data-stu-id="f0e93-120">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="f0e93-121">Nastavení financí</span><span class="sxs-lookup"><span data-stu-id="f0e93-121">Set Up Finance</span></span>](finance-setup-setup-finance-setup.md)  
[<span data-ttu-id="f0e93-122">Hlavní kniha a Účtová osnova</span><span class="sxs-lookup"><span data-stu-id="f0e93-122">The General Ledger and the Chart of Accounts</span></span>](finance-setup-general-ledger.md)  

