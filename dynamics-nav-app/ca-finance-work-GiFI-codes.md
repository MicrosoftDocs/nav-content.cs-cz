---
title: "Návod: Práce s kódy GIFI v Kanadě"
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 695bca0a6836c47610210b759ae48af27484761f
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-work-with-gifi-codes-in-canada"></a>Návod: Práce s kódy GIFI v Kanadě
Fiskální informace mohou zahrnovat účty hlavní knihy, výkazy, výkazy zisku a ztrát, rozvahy a výkazy nerozděleného zisku. Fiskální informace jsou klasifikovány pomocí kódů. Používání kódů pomáhá vládě zpracovávat informace, připravovat se na elektronické podání a ověřovat daňové informace elektronicky. Používání kódů také pomáhá statistickým organizacím pracovat efektivněji, protože finanční informace jsou snadněji dostupné. Další informace naleznete v části [Kanadská agentura pro daňovou agendu](http://www.cra-arc.gc.ca/).

Kanadská daňová agentura využívá kódy obecného indexu finančních informací (GIFI) pro shromažďování, ověřování a zpracování finančních a daňových informací elektronicky. Nejlepším postupem je přiřadit kódy GIFI pouze zaúčtovaným účtům, takže celkový součet je prováděn pomocí softwaru pro daňovou přípravu.

Pokud je účet spojen s kódem GIFI, je nahlášen agentuře pro příjem pod tímto kódem. Více účtů může mít stejný kód GIFI, ale každý účet může mít pouze jeden kód GIFI.

Můžete exportovat informace o zůstatku pomocí kódu GIFI a uložit exportovaný soubor v aplikaci Excel, což je užitečné pro přenos informací do softwaru pro daňové zpracování.

## <a name="to-set-up-gifi-codes"></a>Nastavení kódů GIFI
V Dynamics NAV musíte nastavit kódy GIFI pro účty hlavní knihy, přehledy, rozvahy, výkazy příjmů a výkazy nerozděleného zisku.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Kódy GIFI** a pak vyberte související odkaz.
2. V okně **Kódy GIFI** vyberte akci **Nový**.
3. Nastavení kódů GIFI vyplněním polí. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.

## <a name="to-associate-gifi-codes-with-gl-accounts"></a>Přidělení kódů GIFI k finančním účtům
Chcete-li ohlásit finanční informace pomocí kódu GIFI, musí být každý kód GIFI přidružen k příslušným účtům v účtové osnově.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účetní osnova** a pak vyberte související odkaz.
2. Vyberte příslušný účet hlavní knihy a pak zvolte akci **Upravit**. 
3. Na záložce s náhledem **Účtování nákladů** vyberte v poli **Kód GIFI** příslušný kód GIFI.

## <a name="to-view-account-balances-using-the-gifi-code-report"></a>Zobrazení zůstatků na účtů pomocí kódu GIFI
Zůstatek účtu můžete zkontrolovat podle kódu GIFI pomocí přehledu **Zůstatky na účtu podle kódu GIFI**.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zůstatky na účtu podle kódu GIFI** a pak vyberte související odkaz.
2. Uveďte, co se má ve zprávě zapsat vyplněním polí. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
3. Zvolte tlačítko **Tisk** nebo **Náhled**. 

## <a name="to-export-balance-information-using-gifi-codes"></a>Export informací o zůstatcích pomocí kódu GIFI
Informace o exportu zůstatků pomocí kódů GIFI a uložení exportovaného souboru v aplikaci Excel. Můžete upravit, uložit nebo smazat soubor. Soubor můžete použít k přenosu informací do softwaru pro daňové zpracování.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Export GIFI Info. to Excel** a pak vyberte související odkaz.
2. Určete, co exportovat do aplikace Excel vyplněním polí. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
3. Zvolte tlačítko **OK**.

**Poznámka:** Soubor aplikace Excel má následující vlastnosti:

* Zůstatek je zaokrouhlen na nejbližší procentní podíl, ale hodnota buňky zůstává stejná jako v hlavní knize.

* Negativní čísla jsou v závorkách reprezentována jako kladné číslo. Proto je -123 reprezentováno jako (123).

## <a name="see-also"></a>Viz také
[Finance](finance-setup.md)   
[Nastavení klíčových finančních procesů](finance-setup-setup-finance-setup.md)

