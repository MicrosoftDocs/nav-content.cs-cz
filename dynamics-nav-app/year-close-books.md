---
title: "Přehled úloh pro uzavření knih"
description: "Informace o procesu uzavření knih za fiskální rok nebo období a co se stane po ukončení konce roku."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, bank account detailed trial balance
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d709f8bfb5da3a0ebf5b44f3246fa3ccaa69c77f
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="closing-the-books"></a>Uzavření knih
Poté, co se ujistíte, že všechny vaše účty jsou aktuální a rozdělíte náklady a výnosy, můžete knihy uzavřít za fiskální rok nebo období.

Nemusíte zavírat rok, ale pokud to uděláte, budete pracovat v systému jednodušeji, protože budete moci využít výhodných možností filtrování. Také se nemusíte obávat, že ztratíte detaily transakcí, když uzavřete, protože všechny detaily zůstanou zachovány i po ukončení roku.

## <a name="closing-book-process"></a>Proces uzavření knih
Proces uzavření knih zahrnuje tyto hlavní úkoly:

1. Uzavření fiskálního období.

    Fiskální rok je definován jako jedno nebo více otevřených období definovaných na okno **Účetní období** . Typický fiskální rok obsahuje 12 období (12 měsíců), ale můžete zvolit jinou metodu definování roku.

    Další informace naleznete v [Návod: Uzavřít fiskální období](year-close-account-periods.md).
2. Registrace položek předchozího roku.

    Při uzavření fiskálního roku musíte zadat řadu administrativních transakcí (například předplacené a časově rozlišené položky). Tyto transakce se nazývají upravující. Neexistují žádná zvláštní pravidla pro zaúčtování těchto položek a tyto položky (stejně jako ostatní položky) obsahují zaškrtnutí v poli **Položka předchozího roku**, pokud jsou zaúčtovány k datu uzavřeného fiskálního roku. Přestože jste uzavřeli fiskální rok, můžete do něho stále zaúčtovat položky hlavní knihy.
3. Převedení salda z účtu výkazu zisků a ztrát do rozvahy.

    Po uzavření fiskálního roku a zaúčtování všech položek za předchozí rok musí být náklady a výnosy uzavřeny a čistý zisk za rok musí být převeden na rozvahový účet. Pro tento účel použijte dávkovou úlohu Uzavření výsledovky. Dávková úloha zpracovává všechny účty hlavní knihy typu Výsledovka a vytváří položky, které obsahují zůstatky s opačným znamínkem. Tyto položky jsou umístěny v deníku, ze kterého mohou být zaůčtovány. Dávkové úlohy je nezaúčtují automaticky, s výjimkou případů, kdy je použita přídavná měna pro hlášení. Pokud je použita přídavná měna prohlášení, dávková úloha zaúčtuje přímo do hlavní knihy.

    Další informace naleznete v části [Uzavření výsledovky](year-close-income-statement.md).
4. Zaúčtování položky zisku.

    Po dokončení dávkového úlohy Uzavření výsledovky, zaúčtujete položky vygenerované dávkou. Pokud jste v dávkovém úloze neuvedli Účet dosažených zisků, zadejte jeden řádek s protiúčtem, který zaúčtuje čistý zisk na účet nerozděleného zisku v rozvaze. Nakonec zaúčtujte deník.

    Další informace naleznete v [Návod: Zaúčtovat položku uzavření roku](year-how-post-year-end-close-entry.md).

## <a name="what-happens-when-you-close"></a>Co se stane při uzavření
Když uzavřete rok, systém přenese vypočtený zisk na účet Nerozdělený zisk. Systém také označí fiskální rok za "uzavřený" a označí všechny následující položky za uzavřený rok jako "položky předchozího roku".

Systém pak vygeneruje uzavírací položku, ale neukládá ji automaticky. Dostáváte příležitost vytvořit položku nebo položky, které vám umožní rozhodnout, jak zaúčtovat závěrečnou položku. Například pokud má vaše společnost několik divizí, můžete nechat systém vygenerovat jednu uzavírací položku pro všechny divize a pak můžete provést zaúčtování dle divizí.

Můžete zaúčtovat v předchozím fiskálním roce, a to i po uzavření účtů výkazu zisku a ztráty, pokud spustíte dávkovou úlohu uzavření výsledovky později.

## <a name="see-also"></a>Viz také
[Návody: Otevření nového fiskálního roku](finance-how-open-new-fiscal-year.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

