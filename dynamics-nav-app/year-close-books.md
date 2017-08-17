---
title: "Uzavřít knihy"
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
ms.openlocfilehash: fbad97555caad5d8088ca644a47a3f6c470def55
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---
# <a name="close-books"></a>Uzavřít knihy
Poté, co se ujistíte, že všechny vaše účty jsou aktuální a rozdělíte náklady a výnosy, můžete knihy uzavřít za fiskální rok nebo období.

Nemusíte zavírat rok, ale pokud to uděláte, budete pracovat v systému jednodušeji, protože budete moci využít výhodných možností filtrování. Také se nemusíte obávat, že ztratíte detaily transakcí, když uzavřete, protože všechny detaily zůstanou zachovány i po ukončení roku.

## <a name="closing-book-process"></a>Proces uzavření knih
Proces uzavření knih zahrnuje tyto hlavní úkoly:

1. Uzavření fiskálního období.

    Fiskální rok je definován jako jedno nebo více otevřených období definovaných na stránce **Účetní období** . Typický fiskální rok obsahuje 12 období (12 měsíců), ale můžete zvolit jinou metodu definování roku.

    Pro další informace, viz [Návody: ](year-close-account-periods.md)Uzavřít fiskální období.

2. Registrace položek předchozího roku.

    Při uzavření fiskálního roku musíte zadat řadu administrativních transakcí (například předplacené a časově rozlišené položky). Tyto transakce se nazývají upravující. Neexistují žádná zvláštní pravidla pro zaúčtování těchto položek a tyto položky (stejně jako ostatní položky) obsahují zaškrtnutí v poli **Položka předchozího roku**, pokud jsou zaúčtovány k datu uzavřeného fiskálního roku. Přestože jste uzavřeli fiskální rok, můžete do něho stále zaúčtovat položky hlavní knihy.

3. Převedení salda z účtu výkazu zisků a ztrát do rozvahy.

    Po uzavření fiskálního roku a zaúčtování všech položek za předchozí rok musí být náklady a výnosy uzavřeny a čistý zisk za rok musí být převeden na rozvahový účet. Pro tento účel použijte dávkovou úlohu Uzavření výsledovky. Dávková úloha zpracovává všechny účty hlavní knihy typu Výsledovka a vytváří položky, které obsahují zůstatky s opačným znamínkem. Tyto položky jsou umístěny v deníku, ze kterého mohou být zaůčtovány. Dávkové úlohy je nezaúčtují automaticky, s výjimkou případů, kdy je použita přídavná měna pro hlášení. Pokud je použita přídavná měna prohlášení, dávková úloha zaúčtuje přímo do hlavní knihy.

    Další informace naleznete v části [Uzavření výsledovky](year-close-income-statement.md).
4. Zaúčtování položky zisku.

    Po dokončení dávkového úlohy Uzavření výsledovky, zaúčtujete položky vygenerované dávkou. Pokud jste v dávkovém úloze neuvedli Účet dosažených zisků, zadejte jeden řádek s protiúčtem, který zaúčtuje čistý zisk na účet nerozděleného zisku v rozvaze. Nakonec zaúčtujte deník.

    Pro další informace, viz [Návody: ](year-how-post-year-end-close-entry.md)Zaúčtovat položku uzavření roku.

## <a name="what-happens-when-you-close"></a>Co se stane při uzavření
Když uzavřete rok, systém přenese vypočtený zisk na účet Nerozdělený zisk. Systém také označí fiskální rok za "uzavřený" a označí všechny následující položky za uzavřený rok jako "položky předchozího roku".

Systém pak vygeneruje uzavírací položku, ale neukládá ji automaticky. Dostáváte příležitost vytvořit položku nebo položky, které vám umožní rozhodnout, jak zaúčtovat závěrečnou položku. Například pokud má vaše společnost několik divizí, můžete nechat systém vygenerovat jednu uzavírací položku pro všechny divize a pak můžete provést zaúčtování dle divizí.

Můžete zaúčtovat v předchozím fiskálním roce, a to i po uzavření účtů výkazu zisku a ztráty, pokud spustíte dávkovou úlohu uzavření výsledovky později.

## <a name="see-also"></a>Viz také
[Návody: Otevřít nový fiskální rok](finance-how-open-new-fiscal-year.md)

