---
title: "Uzavření výsledovky"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 2e100cb0ca992b2f4f8cc731deccf9ddae49b3ef
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---
# <a name="close-income-statement"></a>Uzavření výsledovky
Po ukončení fiskálního roku musíte ukončit období, kterého se fiskální rok týká. Chcete-li to provést, spusťte dávkovou úlohu **Uzavření výsledovky** . Tato úloha přenáší roční výsledek na účet v rozvaze a zavírá nákladové a výnosové účty. To provedete vytvořením řádků v deníku, které můžete následně zaúčtovat.

## <a name="to-run-the-close-income-statement-batch-job"></a>Chcete-li spustit dávkovou úlohu Uzavření výsledovky
1. Uzavřete fiskální rok. Fiskální rok musí být uzavřen před spuštěním dávkové úlohy. Pro další informace, viz [Návody: ](year-close-account-periods.md)Uzavřít rok.
2. V pravém horním rohu zvolte ikonu **Hledat**, zadejte **Uzavření výsledovky** a pak vyberte související odkaz.
3. Zvolte tlačítko **OK** pro spuštění dávkové úlohy.

## <a name="about-the-close-income-statement-batch-job"></a>O dávkové úloze Uzavření výsledovky
Dávková úloha zpracovává všechny položky hlavní knihy typu Výsledovka a vytváří položky, které stornují příslušné zůstatky. To znamená, že každá položka je součtem všech položek hlavní knihy k účtu ve fiskálním roce. Tyto nové položky jsou umístěny v deníku, ve kterém musíte zadat protiúčet a účet nerozděleného zisku před zaúčtováním. Když zaúčtujete deník, položka je zaúčtována ke každému nákladovému a výnosovému účtu, tak že saldo je nula, a zároveň je zisk převeden k rozvahovému účtu.

Deník musíte zaúčtovat sám. Dávková úloha nezaúčtuje položky automaticky, s výjimkou případů, kdy je používána přídavná měna prohlášení. Při použití přídavné měny prohlášení dávková úloha přidává položky přímo do hlavní knihy.

Datum na řádcích, které dávková úloha vkládá do deníku, je vždy posledním datem fiskálního roku. Poslední datum fiskálního roku je fiktivní datum mezi posledním dnem starého fiskálního roku a prvním dnem nového roku. Výhodou zaúčtování k poslednímu datu fiskálního roku je udržení správných zůstatků běžných dat fiskálního roku.

Dávkovou úlohu **Uzavření výsledovky** lze použít několikrát. Můžete zaúčtovat v předchozím fiskálním roce, dokonce i po uzavření účtů nákladů a výnosů, pokud znovu spustíte dávkovou úlohu.

## <a name="see-also"></a>Viz také
[Uzavřít knihy](year-close-books.md)  
[Návody: Zaúčtovat položku ukončující rok](year-how-post-year-end-close-entry.md)  
[Návody: Otevřít nový fiskální rok](finance-how-open-new-fiscal-year.md)

