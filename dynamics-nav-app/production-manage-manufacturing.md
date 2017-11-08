---
title: "Spuštění výroby"
description: "Když je naplánována poptávka a materiál byl vydán podle výrobních kusovníků, mohou se skutečné výrobní operace spustit a provádět v pořadí definovaném podle směrování výrobní zakázky."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/26/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1d3e6b49626aaf60f398b9f9cf8a656bd3dc4946
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="manufacturing"></a>Výroba
Když je naplánována poptávka a materiál byl vydán podle výrobních kusovníků, mohou se skutečné výrobní operace spustit a provádět v pořadí definovaném podle směrování výrobní zakázky.  

Důležitou součástí provádění výroby z hlediska systému je zaúčtování výstupu do databáze k sestavení průběhu a aktualizace skladu s dokončeným zbožím. Zaúčtování výstupu lze provést ručně, vyplněním a zaúčtováním řádku deníku po výrobních operacích. Nebo to může být provedeno automaticky s použitím zpětného vyprazdňování. V takovém případě se automaticky zaúčtuje spotřeba materiálu spolu s výstupem, když je výrobní zakázka změněna na dokončenou.  

Jako alternativu dávky deníku pro zaúčtování výstupu pro více výrobních objednávek, můžete použít okno **Deník výroby** pro zaúčtování spotřeby a/nebo výstupu pro jeden řádek výrobní zakázky.

Než začnete vyrábět zboží, musíte provést různá nastavení, jako jsou pracovní centra, trasy a výrobní kusovníky. Další informace naleznete v tématu: [Nastavení výroby](production-configure-production-processes.md).

Následující tabulka popisuje sekvenci úloh s odkazy na témata, která je popisují.   

|**Pro**|**Odkaz**|  
|------------|-------------|  
|Porozumění jak pracovat s výrobními zakázkami.|[O výrobních zakázkách](production-about-production-orders.md)|
|Vytvoření výrobní zakázky ručně.|[Návod: Vytvoření výrobní zakázky](production-how-to-create-production-orders.md)|
|Zadávejte všechny nebo vybrané operace ve výrobní zakázce subdodavateli.|[Návod: Subdodavatelská výroba](production-how-to-subcontract-manufacturing.md)|
|Zaznamenávejte a zaúčtujte produkci výstupu spolu s materiálem a časovou spotřebu pro jeden uvolněný řádek výrobní zakázky.|[Návod: Zaúčtování spotřeby a výstup pro jeden uvolněný řádek výrobní zakázky.](production-how-to-register-consumption-and-output.md)|  
|Dávka zaúčtování používá množství komponentů za operaci v deníku, který může zpracovávat vícero plánovaných výrobních zakázek.|[Návod: Dávka zaúčtování spotřeby](production-how-to-post-consumption.md)|
|Zaúčtujte množství hotového zboží a čas strávený na jednu operaci v deníku, který může zpracovávat vícero uvolněných výrobních zakázek.|[Návod: Dávka zaúčtování výstupu a uběhlý čas](production-how-to-post-output-quantity.md)|  
|Zaúčtujte počet zboží, které bylo vyrobeno v každé dokončené operaci a které se nedá považovat za hotový výstup, ale za zlikvidovaný materiál.|[Návod: Zaúčtování odpadu](production-how-to-post-scrap.md)|
|Zobrazte si dílenské řízení jako důsledek plánovaných a uvolněných výrobních zakázek.|[Návod: Zobrazte si zatížení v pracovních a strojních centrech](production-how-to-view-the-load-on-work-centers.md)|      
|Použijte okno **Deník kapacity**, abyste zaúčtovali spotřebované kapacity, které nejsou přiřazeny výrobní zakázce, například údržbářské práce.|[Návod: Zaúčtování kapacit](production-how-to-post-capacities.md)|  
|Výpočet a upravení nákladů na hotové výrobní zboží a spotřebované komponenty pro finanční odsouhlasení.|[O nákladech dokončených výrobních zakázek](finance-about-finished-production-order-costs.md)|  

## <a name="see-also"></a>Viz také  
[Nastavení výroby](production-configure-production-processes.md)  
[Plánování](production-planning.md)      
[Sklady](inventory-manage-inventory.md)  
[Nákup](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

