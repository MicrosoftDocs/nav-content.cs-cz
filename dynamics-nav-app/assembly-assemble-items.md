---
title: "Správa montáže"
description: "Podporované společnosti, které dodávají produkty svým zákazníkům tím, že kombinují komponenty v jednoduchých procesech bez nutnosti výrobních funkcí, ale s funkcemi pro montáž zboží, které se integrují s existujícími funkcemi, jako je prodej, plánování, rezervace a skladování."
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
ms.openlocfilehash: 4e0490e63268edd68a22e61b25311aa133c507c1
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="assembly-management"></a>Správa montáže
Podporované společnosti, které dodávají produkty svým zákazníkům tím, že kombinují komponenty v jednoduchých procesech bez nutnosti výrobních funkcí, [!INCLUDE[d365fin](includes/d365fin_md.md)] zahrnuje funkce k montáži zboží, které je integrováno s existujícími funkcemi, jako je prodej, plánování, rezervace a skladování.  

 Montáž zboží je definováno jako prodej zboží, které obsahuje montážní kusovník. Další informace naleznete v tématu [Návod: Práce s kusovníky](inventory-how-work-BOMs.md).

 Montážní objednávka je vnitřní objednávka, stejně jako výrobní objednávka, která se používá ke správě procesu montáže a propojení prodejních požadavků s aktivitami skladu. Montážní objednávka se liší od ostatních typů objednávek, protože zahrnuje výstup a spotřebu při zaúčtování. Hlavička montážní objednávky se chová podobně jako řádek prodejní objednávky a řádek montážní objednávky se chová obdobně jako řádky spotřebního deníku.  

 K podpoře strategie zásobování včas a možnosti přizpůsobení produktů požadavkům zákazníků mohou montážní objednávky být vytvořeny automaticky a propojeny, jakmile je vytvořen řádek prodejní objednávky. Spojení mezi prodejní poptávkou a montážní dodávkou umožňuje prodejní objednávku upravit o  montážní zboží, slíbit datum dodání podle dostupnosti komponenty a zaúčtovat výstup a dodávku smontovaného zboží přímo z rozhraní prodejní objednávky. Další informace naleznete v tématu [Návod: Prodej zboží smontovaného na objednávku](assembly-how-to-sell-items-assembled-to-order.md).  

 Na jednom řádku prodejní objednávky můžete prodat množství, které je k dispozici a musí být vybráno ze skladu společně s množstvím, které musí být smontováno k objednávce. Existují určitá pravidla, kterými se řídí rozdělení takových množství, aby bylo zajištěno, že množství k montáži na objednávku má přednost před množstvím zásob při částečném dodání. Další informace naleznete v části „Kombinace scénářů“ v tématu: [Porozumění montáži na objednávku a montáži na sklad](assembly-assemble-to-order-or-assemble-to-stock.md).  

 Existuje zvláštní funkčnost, aby se řídilo množství dodávky k montáži na objednávku. Když je množství k montáži na objednávku připraveno k dodání, odpovědný skladový pracovník zaúčtuje vybrané zásoby pro řádek nebo řádky prodejní objednávky. To zase vytváří pohyb zásob pro komponenty, zaúčtuje výstup montáže a dodání prodejní objednávky. Další informace naleznete v tématu „Manipulace se zbožím montáže na objednávku ve vyskladněných zásobách“ v [Návod: ](warehouse-how-to-pick-items-with-inventory-picks.md)Výběr zboží s vyskladněním zásob

Následující tabulka popisuje sekvenci úloh s odkazy na témata, která je popisují.   

|**Pro**|**Odkaz**|  
|------------|-------------|  
|Přečtěte si o rozdílech mezi montáži zboží těsně před odesláním prodejní objednávky a montáži zboží, které jsou určeny pro sklad.|[Porozumění montáži na objednávku a montáži na sklad](assembly-assemble-to-order-or-assemble-to-stock.md)|
|Vyplňte pole na kartách umístění a nastavení zásob, abyste určili, jak jde zboží skrz montážní oddělení.|[Návod: Nastavení základního skladu s provozními oblastmi](warehouse-how-to-set-up-basic-warehouses-with-operations-areas.md)|
|Upravte montáž zboží podle požadavků zákazníka během prodejního procesu a přejděte na prodej, když je přijat.|[Návod: Nabídka k prodeji montáže na objednávku](assembly-how-to-quote-an-assemble-to-order-sale.md)|
|Kombinujte komponenty tak, abyste vytvořili zboží v jednoduchém procesu, na objednávku nebo na sklad.|[Návod: Montáž zboží](assembly-how-to-assemble-items.md)|  
|Prodej zboží k montáži, které není v současné době k dispozici a to vytvořením připojené montážní objednávky k dodání úplného nebo částečného množství prodejní objednávky.|[Návod: Prodej zboží k montáži na objednávku](assembly-how-to-sell-items-assembled-to-order.md)|
|Když je nějaké zboží k montáži na objednávku připraveno ve skladu, odečtěte toto množství z montážní objednávky a rezervujte ho ze skladu.|[Návod: Prodej skladového zboží s množstvím na objednávku](assembly-how-to-sell-inventory-items-in-assemble-to-order-flows.md)|  
|Když prodáváte zboží k montáži ze skladu a všechno zboží není dostupné, vyvolejte montážní objednávku k automatickému dodání části nebo celého množství prodejní objednávky.|[Návod: Prodej zboží k montáži na objednávku a skladového zboží současně](assembly-how-to-sell-assemble-to-order-items-and-inventory-items-together.md)|
|Zrušit zaúčtovanou montážní objednávku například proto, že objednávka byla zaúčtována s chybami, které musí být opraveny.|[Návod: Zrušit zaúčtování montáže](assembly-how-to-undo-assembly-posting.md)|
|Přečtěte si o rozdílech mezi montážními kusovníky a výrobními kusovníky a zahrnutými rozdíly v zpracování.|[Návod: Práce s kusovníky](inventory-how-work-BOMs.md)|
|Přečtěte si, jak je řešena montážní spotřeba a výstup, když zaúčtujete montážní objednávku a jak doručit zboží a jak jsou zpracovány a distribuovány náklady na zdroje do hlavní knihy.|[Podrobnosti návrhu: Zaúčtování montážní objednávky](design-details-assembly-order-posting.md)|  

## <a name="see-also"></a>Viz také  
[Návod: Práce s kusovníky](inventory-how-work-BOMs.md)  
[Sklady](inventory-manage-inventory.md)  
[Podrobnosti návrhu: Správa skladu](design-details-warehouse-management.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

