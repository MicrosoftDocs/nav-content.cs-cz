---
title: "Plánování dodávky"
description: "Připravte si podrobný spustitelný plán a výrobní plán konečné montáže pro prodej a poptávku produkce."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/14/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b904d539509c005f3d00b41a3724d1e70523059e
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="planning"></a>Plánování
Výrobní operace potřebné k přeměně vstupů na hotové výrobky musí být plánovány denně nebo týdně v závislosti na objemu a povaze výrobků. [!INCLUDE[d365fin](includes/d365fin_md.md)] nabízí funkce k dodávce pro očekávanou a aktuální poptávku z prodeje, montáže a výroby, jakož i funkce pro plánování distribuce s využitím skladových jednotek a převodů umístění.

> [!NOTE]
> Toto téma popisuje především plánování pro společnosti zabývající se výrobou nebo montážním řízením, kde výsledné prodejní objednávky mohou být buď výroba, montáž, převod nebo nákupní objednávky. Hlavním rozhraním pro toto plánování práce je okno **Plánovací sešit**.

> [!INCLUDE[d365fin](includes/d365fin_md.md)] také podporuje plánování dodávek pro velkoobchodní společnosti, jejichž výsledkem dodací objednávky mohou být pouze převody a nákupní objednávky. Hlavním rozhraním pro toto plánování práce je okno **Sešit požadavků**, který je v tomto tématu nepřímo popsán, jelikož většina funkcí plánování se týká obou sešitů.

Než budete moci naplánovat a provádět výrobní zakázky, musíte nakonfigurovat výrobní kapacity, například vytvořit obchodní kalendář, směrování, výrobní kusovníky a strojní centra. Další informace naleznete v tématu: [Nastavení výroby](production-configure-production-processes.md).

Plánování lze považovat za požadovanou přípravu dodacích objednávek v montážních nebo výrobních odděleních, které splňují poptávku. Další informace naleznete v tématu: [Správa montáže](assembly-assemble-items.md) a [Výroba](production-manage-manufacturing.md).

Následující tabulka popisuje sekvenci úloh s odkazy na témata, která je popisují.   

|**Pro**|**Odkaz**|  
|------------|-------------|  
|Získejte stručný přehled o tom, jak lze plánovací systém použít k odhalení a stanovení priority poptávky a navrhnout vyrovnaný plán dodání.|[O plánovacích funkcionalitách](production-about-planning-functionality.md)|
|Porozumění, jak fungují všechny aspekty plánovacího systému a jak nastavit algoritmy tak, aby splňovaly požadavky na plánování v různých prostředích.|[Podrobnosti návrhu: Plánování dodávky](design-details-supply-planning.md)|
|Zjistěte, jak logika plánování rozlišuje mezi poptávkou v umístění podle nastavení SKU a poptávkou bez kódů umístění.|[Plánování s nebo bez umístění](production-planning-with-without-locations.md)|
|Prognóza poptávka po výrobě předvedená očekávanou prodejní a výrobní zakázkou.|[Návod: Vytvoření prognózy po výrobě](production-how-to-create-a-forecast.md)|  
|Vytvoření individuální výrobní zakázky automaticky z prodejní objednávky k pokrytí přesné poptávky z tohoto řádku prodejní objednávky.|[Návod: Vytvoření výrobní zakázky z prodejní objednávky](production-how-to-create-production-orders-from-sales-orders.md)|
|Vytvořte výrobní zakázku projektu přímo z víceřádkové prodejní objednávky představující výrobní projekt.|[Návod: Plánování projektových objednávek](production-how-to-plan-project-orders.md)|
|Použijte okno **Plánování objednávek** k manuálnímu plánování prodeje nebo poptávky po výrobě v jedné úrovni kusovníku.|[Návod: Plánování pro novou poptávku objednávky k objednávce](production-how-to-plan-for-new-demand.md)|
|Použijte okno **Plánovací sešit** pro spuštění obou možností MPS a MRP, které automaticky vytvoří buď vysokoúrovňový nebo podrobný plán poptávky na všech úrovních zboží.|[Návod: Spuštění plánování, MPS nebo MRP](production-how-to-run-mps-and-mrp.md)|
|Spusťte sešit požadavků k automatickému vytvoření podrobného plánu dodávky k pokrytí poptávky pro zboží, které jsou doplněny pouze nákupem nebo převodem.|Stránka **Sešit požadavků**|  
|Vyvolání nebo aktualizace výrobní zakázky jako hrubé plánované operace v hlavním výrobním plánu.|[Návod: Přeplánování nebo obnovení výrobní zakázky přímo](production-how-to-replan-refresh-production-orders.md)|
|Přepočítání pracovního kalendáře nebo kalendáře strojů v důsledku plánovaných změn.|„K výpočtu kalendáře pracovního střediska“ téma v [Návod: Nastavení obchodního kalendáře](production-how-to-create-work-center-calendars.md)|
|Sledujte poptávku po objednávce (sledované množství), prognózu, prodejní objednávku nebo plánovací parametr (nevyčerpané množství), které bylo dáno k dotyčnému plánovacímu řádku.|[Návod: Sledování vztahů mezi poptávkou a nabídkou](production-how-track-demand-supply.md)|
|Zobrazte zboží dostupné v zásobách podle různých pohledů a zjistěte, které požadavky, plánované objednávky příjmu a další ovlivňující události v průběhu času.|[Návod: Zobrazit dostupnost zboží](inventory-how-availability-overview.md)|  
|Provádějte vybrané plánovací činnosti, například změnu nebo přidání plánovacích řádků sešitu v pohledu plánu dodání.|[Návod: Upravit návrhy plánování v pohledu](production-how-to-modify-planning-suggestions-in-a-graphical-view.md)|

## <a name="see-also"></a>Viz také
[Nastavení výroby](production-configure-production-processes.md)  
[Výroba](production-manage-manufacturing.md)    
[Sklady](inventory-manage-inventory.md)  
[Nákup](purchasing-manage-purchasing.md)  
[Podrobnosti návrhu: Plánování dodávky](design-details-supply-planning.md)   
[Nastavení nejlepšího postupu Plánování dodávky](setup-best-practices-supply-planning.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

