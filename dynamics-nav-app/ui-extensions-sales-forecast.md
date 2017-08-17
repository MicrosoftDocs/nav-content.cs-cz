---
title: "Prognóza prodeje a zásob"
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 765527ed4f4800acec20f0abbd4374e95c9c36dc
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="sales-and-inventory-forecast-for-dynamics-nav"></a>Prognóza prodeje a zásob pro Dynamics NAV
Řízení zásob je kompromis mezi zákaznickým servisem a řízením nákladů. Na jedné straně nízké zásoby vyžadují menší provozní kapitál, na druhé straně však zásoby potenciálně vedou ke ztrátě prodeje. Prodloužení predikce prodeje a skladů předpovídá potenciální prodej za použití historických údajů a poskytuje jasný přehled očekávaných zásob. Na základě prognózy rozšíření pomáhá vytvářet požadavky na doplňování od Vašich dodavatelů a Vám šetří čas.  

## <a name="setting-up-forecasting"></a>Nastavení předpovědi
V aplikaci Dynamics NAV musíte nastavit připojení k Azure ML (Azure ML). Další informace naleznete v tématu [Jak na: Registrujte Dynamics NAV na portálu Azure Management](ui-how-register-dynamics-nav-azure.md) Po vytvoření připojení můžete nakonfigurovat prognózu tak, aby bylo možné použít jiný typ období, např. Změna z prognózy podle měsíce na prognózu podle čtvrtletí. Můžete také vybrat počet období pro výpočet prognózy podle toho, jak granulární chcete, aby prognóza byla. Doporučujeme, abyste prognózu odhadli měsíčně a v horizontu 12 měsíců.  

## <a name="using-the-forecasts"></a>Používání prognóz
Rozšíření využívá možnosti Azure ML, které předpovídají budoucí tržby na základě vaší prodejní historie, což vám pomůže vyhnout se nedostatku zásob. Když například vyberete položku v okně **Zboží**, graf v  **Předpověď zboží** zobrazí položky odhadovaný prodej této položky v příštím období. Tímto způsobem zjistíte, jestli je pravděpodobné, že brzy vyčerpáte zásoby zboží.  

Rozšíření můžete také použít k tomu, abyste navrhli, kdy chcete inventarizovat zásoby. Pokud například vytváříte nákupní objednávku od společnosti Fabrikam, protože chcete koupit novou židli, prognóza prodeje a zásob navrhne, že by jste měli přeskladnit židle LONDON, kterou obvykle nakupujete od tohoto výrobce. Je to proto, že prodloužení předpovídá, že v nadcházejících dvou měsících dojde k výdeji otočné židle LONDON, takže si možná budete chtít objednat více židlí již nyní.  

## <a name="see-also"></a>Viz také
[Správa prodeje](sales-manage-sales.md)  
[Správa skladů](inventory-manage-inventory.md)  
[Přizpůsobení Dynamics NAV pomocí Extensions](ui-extensions.md)  
[Návody Registrujte Dynamics NAV na portálu Azure Management](ui-how-register-dynamics-nav-azure.md)  

