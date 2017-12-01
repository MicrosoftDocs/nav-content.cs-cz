---
title: "Skladové aktivity"
description: "Potom, co je zboží obdrženo, ale nedodáno, uskuteční se série vnitřních skladových aktivit k zajištění efektivního toku skrz sklad a organizaci a údržby zásob společnosti."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 608dc6f0d4fcf84d5df5a7d7c0c0dc304fdcad5f
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="warehouse-management"></a>Správa skladu
Potom, co je zboží obdrženo, ale nedodáno, uskuteční se série vnitřních skladových aktivit k zajištění efektivního toku skrz sklad a organizaci a údržby zásob společnosti.

Typické skladové aktivity zahrnují zaskladnění zboží, přesun zboží do skladu nebo mezi sklady a vyskladnění zboží pro montáž, výrobu nebo dodávku. Montáž zboží pro prodej nebo zásoby může také být považováno za skladovou aktivitu, ale tyhle jsou zahrnuty jinde. Další informace naleznete v tématu [Správa montáže](assembly-assemble-items.md).  

Ve velkých skladech mohou být tyhle různě vykonávané úlohy rozděleny odděleními a integrace spravována řízeným workflow. V jednodušších instalacích je tok méně formalizován a skladové aktivity jsou vykonávány s takzvaným zaskladněním a vyskladněním zásob. Více informací o základních versus pokročilých konfigurací skladu jděte na [Detaily návrhu: Přehled skladu](design-details-warehouse-overview.md).

Než budete moci vykonávat skladové aktivity, musíte nastavit systém pro odpovídající složitost zpracování skladu. Další informace naleznete v části [Nastavení správy skladu](warehouse-setup-warehouse.md).

 Následující tabulka popisuje sekvenci úloh s odkazy na témata, která je popisují.   

|**Popis**|**Odkaz**|  
|------------|-------------|  
|Zaznamenávejte příjemky zboží ve skladových lokacích buď jen s nákupní objednávkou v jednoduchých nastaveních lokací, nebo se skladovou příjemkou v případě polo nebo plno automatizovaného zpracování skladu v dané lokaci.|[Návod: Přijmout zboží](warehouse-how-receive-items.md)|
|Obejděte procesy zaskladnění a vyskladnění pro expedici zboží přímo od příjmu nebo výroby k dodávce.|[Návod: Přeložení zboží](warehouse-how-to-cross-dock-items.md)|    
|Zboží zaskladnění přijato z nákupů, vratek, transferů nebo výrobního výstupu podle nakonfigurovaného zpracování skladu.|[Zaskladnění zboží](warehouse-put-away-items.md)|
|Přesuňte zboží mezi přihrádkami ve skladu.|[Přesun zboží](warehouse-move-items.md)|
|Vyskladněte zboží pro dodávku, transfer, potřebu na montáži nebo ve výrobě.|[Vyskladnění zboží](warehouse-pick-items.md)|
|Zaznamenávejte dodávky zboží ve skladových lokacích buď jen s prodejní objednávkou v jednoduchých nastaveních lokací, nebo se skladovou dodávkou v případě polo nebo plno automatizovaného zpracování skladu v dané lokaci.|[Návod: Dodání zboží](warehouse-how-ship-items.md)|  

## <a name="see-also"></a>Viz také  
 [Sklady](inventory-manage-inventory.md)  
 [Nastavení správy skladu](warehouse-setup-warehouse.md)     
 [Správa montáže](assembly-assemble-items.md)    
[Detaily návrhu: Správa skladu](design-details-warehouse-management.md)  
 [Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

