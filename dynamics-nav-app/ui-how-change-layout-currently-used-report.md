---
title: "Návody Změna rozvržení, které se v současnosti používá na sestavu."
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f1411704a7b2a0565d4b23d91e04e271af07659e
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-change-which-layout-is-currently-used-on-a-report"></a>Návody Změna rozvržení, které se v současnosti používá na sestavu.
Sestava může být nastavena s více než jedním rozložením, které můžete podle potřeby přepínat.

V závislosti na rozvržení, které jsou k dispozici pro sestavu, můžete zvolit použití vestavěného rozvržení sestavy RDLC, vestavěného rozvržení sestavy aplikace Word nebo vlastního rozvržení. Další informace o rozvržení RDLC a Wordových sestav, vestavěných, vlastních rozvržení a dalších naleznete v tématu [Správa rozvržení sestav](ui-manage-report-layouts.md).

## <a name="to-change-the-layout-that-is-used-on-a-report"></a>Změna rozvržení, které se používa na sestavě.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Výběr rozvržení sestav** a poté vyberte příslušný odkaz.  
Okno **Výběr rozvržení sestav** obsahuje seznam všech sestav, které jsou k dispozici ve společnosti, která je uvedena v poli Společnost v horní části okna. Pole Vybrané rozložení určuje rozvržení, které se aktuálně používá v sestavě.
2. Položku **Společnost** v horní části okna nastavte na společnost, ve které je sestava.
3. Chcete-li změnit rozvržení, které používá sestava, v řádku seznamu sestav nastavte pole **Vybrané rozložení** na jednu z následujících možností:
    -  RDLC (vestavěný) používá vestavěné RDLC rozvržení sestavy.
    - Word (vestavěný) používá vestavěné Word rozvržení sestavy.
    - Vlastní používá vlastní rozvržení sestavy  
    Můžete vídět, které vlastní rozvržení jsou k dispozici pro sestavu v část FactBoxu Rozvržení sestav. Pokud pro sestavu neexistují žádné vlastní rozvržení, budete muset vytvořit první. kud zvolíte tuto možnost, přejděte k dalšímu postupu, abyste navrhli vlastní rozvržení, které chcete použít.
**Poznámka**: Pokud zvolíte **RDLC (vestavěný)** nebo **Word (vestavěný)** a zobrazí se chybová zpráva, že sestava nemá rozložení zadaného typu, musíte vybrat jinou možnost rozložení nebo vytvořit vlastní rozvržení sestavy daného typu.

Pokud jste vybrali vestavěné rozložení sestav RDLC nebo Word, není třeba provádět žádné další akce a rozložení bude použito při příštím spuštění sestavy.

## <a name="to-specify-a-custom-layout-on-a-report"></a>Navrhnutí vlastního rozvržení sestavy
1. Můžete navrhnou vlastní rozvržení sestavy na sestavu z okna **Vlastní rozvržení sestav**. Není-li okno **Vlastní rozvržení sestav** otevřené, vyberte v poli **Popis Rozvržení sestavy** tlačítko pro rozbalení.
2. V okně **Vlastní rozvržení sestav** vyberte řádek pro vlastní rozložení, který chcete použít, a potom klepněte na tlačítko **OK**.

Vrátíte se do okna **Výběr rozvržení sestav** Název vybraného vlastního rozvržení se zobrazí v poli **Popis vlastního rozvržení**. Vlastní rozložení se použije při příštím spuštění sestavy.

## <a name="see-also"></a>Viz také
[Správa rozvržení sestav](ui-manage-report-layouts.md)

