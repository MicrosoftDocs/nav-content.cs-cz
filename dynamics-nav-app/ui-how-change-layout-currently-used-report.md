---
title: "Změna způsobu, jak vypadá sestava, výběrem jiného rozvržení"
description: "Pro sestavu můžete použít různé rozvržení a přepínat mezi rozvrženími, abyste změnili, jak vypadá sestava."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customized report, document layout, logo, personalize
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7fc680503a3fb2d685758b69e123dc98b2d98e75
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-change-which-layout-is-currently-used-on-a-report"></a>Návod: Změna využívaného rozvržení pro danou sestavu
Sestava může být nastavena s více než jedním rozvržením, které můžete podle potřeby přepínat.

V závislosti na rozvržení, které jsou k dispozici pro sestavu, můžete zvolit použití vestavěného rozvržení sestavy RDLC, vestavěného rozvržení sestavy aplikace Word nebo vlastního rozvržení. Další informace o rozvržení RDLC a Wordových sestav, vestavěných, vlastních rozvržení a dalších naleznete v tématu [Správa rozvržení sestav](ui-manage-report-layouts.md).

## <a name="to-change-the-layout-that-is-used-on-a-report"></a>Změna využívaného rozvržení pro sestavu
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Výběr rozvržení sestavy** a pak vyberte související odkaz.  
   Okno **Výběr rozvržení sestav** obsahuje seznam všech sestav, které jsou k dispozici ve společnosti, která je uvedena v poli Společnost v horní části okna. Pole Vybrané rozložení určuje rozvržení, které se aktuálně používá v sestavě.
2. Pole **Název společnosti** v horní části okna nastavte na společnost, ve které se používá daná sestava.
3. Chcete-li změnit rozvržení, které používá sestava, v řádku seznamu sestav nastavte pole **Vybrané rozložení** na jednu z následujících možností:
   * RDLC (vestavěný) používá vestavěné RDLC rozvržení sestavy
   * Word (vestavěný) používá vestavěné Word rozvržení sestavy
   * Vlastní používá vlastní rozvržení sestavy  
     Můžete vidět, které vlastní rozvržení jsou k dispozici pro sestavu v část FactBoxu Rozvržení sestav. Pokud pro sestavu neexistují žádné vlastní rozvržení, budete muset vytvořit nejprve nové. Pokud zvolíte tuto možnost, přejděte k dalšímu postupu, abyste navrhli vlastní rozvržení, které chcete použít.

    > [!NOTE]  
    >   Pokud zvolíte **RDLC (vestavěný)** nebo **Word (vestavěný)** a zobrazí se chybová zpráva, že sestava nemá rozložení zadaného typu, musíte vybrat jinou možnost rozložení nebo vytvořit vlastní rozvržení sestavy daného typu.

Pokud jste vybrali vestavěné rozložení sestav RDLC nebo Word, není třeba provádět žádné další akce a rozložení bude použito při příštím spuštění sestavy.

## <a name="to-specify-a-custom-layout-on-a-report"></a>Navrhnutí vlastního rozvržení sestavy
1. Můžete navrhnou vlastní rozvržení sestavy na sestavu z okna **Vlastní rozvržení sestav**. Není-li okno **Vlastní rozvržení sestav** otevřené, vyberte v poli **Popis rozvržení sestavy** tlačítko pro rozbalení.
2. V okně **Vlastní rozvržení sestav** vyberte řádek pro vlastní rozložení, které chcete použít, a potom zavřete okno.

Vrátíte se do okna **Výběr rozvržení sestav**. Název vybraného vlastního rozvržení se zobrazí v poli **Popis vlastního rozvržení**. Vlastní rozložení se použije při příštím spuštění sestavy.

## <a name="see-also"></a>Viz také
[Správa rozvržení sestav](ui-manage-report-layouts.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

