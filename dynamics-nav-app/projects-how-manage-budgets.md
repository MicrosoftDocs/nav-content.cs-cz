---
title: "Nastavení a správa rozpočtů projektu"
description: "Popisuje jak plánovat zdroje, dále předpovídat a řídit náklady projektu pomocí nastavení rozpočtu pro každý projekt. "
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project budget, forecast
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 69ac2811e90985f49739ef3e5df020f136112654
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-manage-job-budgets"></a>Návod: Správa rozpočtů projektu
Můžete nastavit rozpočet pro každý projekt. Rozpočet se používá k plánování zdrojů, které přidělíte projektu. Rozpočet může být buď obecný s několika položkami nebo může obsahovat více položek rozdělených do úrovní aktivit. Poté můžete porovnat rozpočtové částky se skutečnou spotřebou, jak je zaznamenáno v deníku projektů. Monitorováním rozdílů mezi skutečnou spotřebou a rozpočtovou spotřebou můžete řídit probíhající projekt a zlepšit kvalitu budoucích pracovních míst tím, že snížíte riziko podhodnocení nákladů.

Následující postup popisuje, jak odhadnout rozpočtované náklady během plánování. Informace o zaznamenaném rozpočtu versus skutečné ceně a nákladům naleznete v části [Návod: Záznam spotřeby pro projekty](projects-how-record-job-usage.md).  

## <a name="JobBudgetCosts"></a> Odhadnutí rozpočtových nákladů na projekt
Pokud chce zákazník znát cenu projektu, která bude fakturována na základě jejího použití, musíte určit výši rozpočtových nákladů na projekt. K tomu použijte okno **Řádky úlohy projektu**.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.  
2. Otevřete příslušný projekt.
3. Vyberte řádek úlohy typu Účet a poté vyberte akci **Řádky plánování projektu**.
4. Na novém řádku, vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]   

U pole **Typ řádku** naleznete následující informace.  

| Typ řádku | Popis |
| --- | --- |
| **Oba typy Plán a Fakturovatelné** |Částky nákladů a cen zapsané na řádku plánování jsou rozpočtové náklady na konkrétním řádku plánování. Cena bude fakturována. |
| **Plán** |Zákazník za spotřebu neúčtuje. Spotřeba není převedena na fakturu, ale bude se i nadále používat při výpočtu NV. |
| **Fakturovatelné** |Zákazníkovi je účtována spotřeba. Spotřeba je převedena na fakturu na základě množství specifikovaného v poli Množství k fakturaci. |

> [!NOTE]  
>   Pole **Datum plánování** pro řádek plánování obsahuje datum, kdy se očekává, že bude spotřeba související s řádkem plánování dokončena. Je také datem, kdy lze řádek plánování převést na prodejní fakturu a zaúčtovat ji.  

> [!NOTE]  
>   Po vyplnění pole **Množství** se pro tento řádek plánování vypočítají a vyplní veškeré informace o celkové ceně a celkových nákladech. Můžete je kdykoli upravit.

V okně **Karta projektu** můžete nyní zobrazit souhrn všech rozpočtových nákladů, rozpočtovou cenu, fakturační náklady a fakturační cenu pro každou činnost.

Informace o zaznamenaném rozpočtu versus skutečné ceně a nákladům naleznete v části [Návod: Záznam spotřeby pro projekty](projects-how-record-job-usage.md).

## <a name="see-also"></a>Viz také
[Řízení projektů](projects-manage-projects.md)  
[Finance](finance.md)  
[Nákup](purchasing-manage-purchasing.md)         
[Prodej](sales-manage-sales.md)      
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

