---
title: "Prodejní daň a daňové skupiny v USA a Kanadě"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: be431bd5feade85f3fd7a5f9bc330814d7c8b1d6
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="sales-tax-and-tax-groups-in-the-us-and-canada"></a>Prodejní daň a daňové skupiny v USA a Kanadě
Když poprvé začnete používat aplikaci [!INCLUDE[navnow](includes/navnow_md.md)], můžete spustit asistované nastavení pro rychlé a snadné nastavení informací o prodejní dani pro vaši společnost a volitelně pro vaše zákazníky a dodavatele. Během několika minut jste připraveni vytvářet prodejní doklady a nákupní doklady s prodejní daní, které jsou správně vypočteny.
Pokud se přesunete do nastavení prázdné společnosti Moje Společnost, doporučujeme použít všechna asistovaná nastavení, včetně nastavení pro prodejní daň. Pokud si přejete sami nastavit prodejní daň, tento článek vysvětluje, co musíte vzít v úvahu.  

## <a name="tax-groups-tax-areas-and-tax-jurisdictions"></a>Daňové skupiny, daňové oblasti a daňové předpisy
V [!INCLUDE[navnow](includes/navnow_md.md)] představuje daňová skupina skupinu zboží nebo zdrojů, které podléhají stejným daňovým podmínkám. Například můžete nastavit jednu daňovou skupinu pro zdanitelné zboží a druhou daňovou skupinu pro zboží, které není předmětem daně. Ke zboží a k účtům hlavní knihy musíte přiřadit kódy daňových skupin. Podobně musíte přiřadit kódy daňové oblasti k zákazníkům, lokacím a k vlastnímu nastavení společnosti. Asistovaná nastavení vám s tím pomohou.  

Každá daňová oblast je seskupením předpisů prodejní daně založených na konkrétní geografické poloze. Například daňová oblast Miami, Florida, zahrnuje tři předpisy prodejní daně: město (Miami), kraj (Dade) a stát (Florida). [!INCLUDE[navnow](includes/navnow_md.md)] obsahuje omezenou sadu daňových oblastí ve výchozí konfiguraci, ale můžete ji změnit a přidat nové daňové oblasti.  

Pokud nastavíte nové daňové oblasti a daňové předpisy, musíte se ujistit, že pole vyplníte správně. Ve Spojených státech mohou státy, kraje, města a lokality účtovat prodejní daň. V Kanadě může federální vláda a provincie účtovat prodejní daň. Společnosti shromažďují a odvádějí prodejní daň těmto orgánům státní správy za produkty prodávané koncovým uživatelům. Prodejní daň může být také účtována na stávající prodejní daň. Například daň lze vypočítat z částky prodejní faktury, která již zahrnuje prodejní daň dle jiných předpisů.  

V Kanadě musí být částky daní uvedeny v dokladech pro každý daňový předpis. V dokladu lze zobrazit až čtyři předpisy a při vytištění jsou kombinovány předpisy, které mají stejné pořadí tisku.

## <a name="tax-details"></a>Daňové detaily
Okno **Daňové detaily** zobrazuje různé kombinace předpisů prodejní daně a skupin prodejní daně pro stanovení sazeb prodejní daně. Pro každý daňový předpis doporučujeme nastavit jednu daňovou skupinu pro běžnou prodejní daň, jinou daňovou skupinu pro zboží nebo služby, které nejsou zdaněny, a další daňovou skupinu pro každý typ zboží nebo služby, který je zdaněn jinou sazbou prodejní daně v daném předpisu.  

Ve Spojených státech, když prodáváte zákazníkovi v místě, kde nemají *sídlo* - nebo legální provozovnu v tom státě - nevybíráte daň z prodeje. U míst, kde nemáte sídlo, ujistěte se, že obě políčka **Daň pod minimem** a **Daň nad maximem** jsou 0,00.  

## <a name="see-also"></a>Viz také
[Finance](Finance.md)  
[Nastavit finance](finance-setup-finance.md)  
[Prodejní daň a daň ze zboží a služeb v Kanadě](ca-finance-setup-tax.md)  
[Nastavení prodejní daně usnadněno](https://madeira.microsoft.com/en-us/blog/sales-tax-setup-made-easy)  

