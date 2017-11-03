---
title: "Použití rozšíření předpovědi prodeje a zásob pro správu zásob"
description: "Toto rozšíření vám pomůže předpovídat tržby, získat přehled o očekávaných zásobách a dokonce vám pomůže vytvářet požadavky dodavatelů na doplňování."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, budget
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 355d1104a210a249db7deff254947bbbaa2a783b
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="sales-and-inventory-forecast-for-dynamics-nav"></a>Prognóza prodeje a zásob pro Dynamics NAV
Řízení zásob je kompromis mezi zákaznickým servisem a řízením nákladů. Na jedné straně nízké zásoby vyžadují menší provozní kapitál, na druhé straně však zásoby potenciálně vedou ke ztrátě prodeje. Prodloužení predikce prodeje a skladů předpovídá potenciální prodej za použití historických údajů a poskytuje jasný přehled očekávaných zásob. Na základě prognózy rozšíření pomáhá vytvářet požadavky na doplňování od vašich dodavatelů a šetří vám čas.  

## <a name="setting-up-forecasting"></a>Nastavení předpovědi
V [!INCLUDE[d365fin](includes/d365fin_md.md)] spojení s [Cortana Intelligence](https://www.microsoft.com/en-us/cloud-platform/what-is-cortana-intelligence-suite) je již připraveno pro vás. Ale můžete nakonfigurovat prognózu tak, aby bylo možné použít jiný typ období, například změnu z prognózy podle měsíce na prognózu podle čtvrtletí. Můžete také vybrat počet období pro výpočet prognózy podle toho, jak granulární chcete, aby prognóza byla. Doporučujeme, abyste prognózu odhadli měsíčně a v horizontu 12 měsíců.  

## <a name="using-the-forecasts"></a>Používání prognóz
Rozšíření využívá možnosti Cortana Intelligence, které předpovídá budoucí tržby na základě vaší prodejní historie, což vám pomůže vyhnout se nedostatku zásob. Když například vyberete položku v okně **Zboží** graf v  **Předpověď zboží**, zobrazí se položky jako odhadovaný prodej této položky v příštím období. Tímto způsobem zjistíte, jestli je pravděpodobné, že brzy vyčerpáte zásoby zboží.  

Rozšíření můžete také použít k tomu, abyste navrhli, kdy chcete inventarizovat zásoby. Pokud například vytváříte nákupní objednávku od společnosti Fabrikam, protože chcete koupit novou židli, prognóza prodeje a zásob navrhne, že by jste měli přeskladnit židle LONDON, kterou obvykle nakupujete od tohoto výrobce. Je to proto, že rozšíření předpovídá, že v nadcházejících dvou měsících dojde k výdeji otočné židle LONDON, takže si možná budete chtít objednat více židlí již nyní.  

## <a name="see-also"></a>Viz také
[Prodej](sales-manage-sales.md)  
[Sklady](inventory-manage-inventory.md)  
[Přizpůsobení [!INCLUDE[d365fin](includes/d365fin_md.md)] pomocí rozšíření](ui-extensions.md)  

