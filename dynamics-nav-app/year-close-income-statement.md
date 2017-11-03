---
title: "Uzavřít účty výsledovky"
description: "Při ukončení roku musíte spustit dávkovou úlohu výkazu zisku a ztráty a uzavřít účetní období, které tvoří fiskální rok."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, bank account detailed trial balance
ms.date: 06/02/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5f004a835ce5b7b55326bdb08a78cb36d430fd45
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-close-income-statement-accounts"></a>Návod: Uzavřít účty výsledovky
Po ukončení fiskálního roku musíte ukončit období, kterého se fiskální rok týká. Chcete-li to provést, spusťte dávkovou úlohu **Uzavření výsledovky** . Tato úloha přenáší roční výsledek na účet v rozvaze a zavírá nákladové a výnosové účty. To provedete vytvořením řádků v deníku, které můžete následně zaúčtovat.

## <a name="to-run-the-close-income-statement-batch-job"></a>Chcete-li spustit dávkovou úlohu Uzavření výsledovky
1. Uzavřete fiskální rok. Fiskální rok musí být uzavřen před spuštěním dávkové úlohy. Další informace naleznete v [Návod: Uzavřít fiskální období](year-close-account-periods.md).
2. Zvolte ikonu ![Hledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Hledat stránku nebo sestavu"), zadejte **Uzavření výsledovky** a pak vyberte související odkaz.
3. Zvolte tlačítko **OK** pro spuštění dávkové úlohy.

## <a name="about-the-close-income-statement-batch-job"></a>O dávkové úloze Uzavření výsledovky
Dávková úloha zpracovává všechny položky hlavní knihy typu Výsledovka a vytváří položky, které stornují příslušné zůstatky. To znamená, že každá položka je součtem všech položek hlavní knihy k účtu ve fiskálním roce. Tyto nové položky jsou umístěny v deníku, ve kterém musíte zadat protiúčet a účet nerozděleného zisku před zaúčtováním. Když zaúčtujete deník, položka je zaúčtována ke každému nákladovému a výnosovému účtu, tak že saldo je nula, a zároveň je zisk převeden k rozvahovému účtu.

Deník musíte zaúčtovat sám. Dávková úloha nezaúčtuje položky automaticky, s výjimkou případů, kdy je používána přídavná měna prohlášení. Při použití přídavné měny prohlášení dávková úloha přidává položky přímo do hlavní knihy.

Datum na řádcích, které dávková úloha vkládá do deníku, je vždy posledním datem fiskálního roku. Poslední datum fiskálního roku je fiktivní datum mezi posledním dnem starého fiskálního roku a prvním dnem nového roku. Výhodou zaúčtování k poslednímu datu fiskálního roku je udržení správných zůstatků běžných dat fiskálního roku.

Dávkovou úlohu **Uzavření výsledovky** lze použít několikrát. Můžete zaúčtovat v předchozím fiskálním roce, dokonce i po uzavření účtů nákladů a výnosů, pokud znovu spustíte dávkovou úlohu.

## <a name="see-also"></a>Viz také
[Uzavřít knihy](year-close-books.md)  
[Návod: Zaúčtování položky ukončující rok](year-how-post-year-end-close-entry.md)  
[Návod: Otevření nového fiskálního roku](finance-how-open-new-fiscal-year.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

