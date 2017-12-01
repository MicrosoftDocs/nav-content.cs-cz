---
title: "Naučte se o hlavní knize a účetní osnově"
description: "Popisuje hlavní knihu, účetní osnovu a kategorie účtů."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: analysis, history, track
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 348a1bcbe6908c7bfd84e99245363e733414aeae
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="understanding-the-general-ledger-and-the-coa"></a>Porozumněte Hlavní knize a účetní osnově
Hlavní kniha ukládá Vaše finanční data a účetní osnova ukazuje účty, ke kterým jsou položky hlavní knihy zaúčtovány. [!INCLUDE[d365fin](includes/d365fin_md.md)] zahrnuje standardní účtovou osnovu, která je připravena podpořit váš obchod.

## <a name="general-ledger-setup-and-general-posting-setup"></a>Nastavení hlavní knihy a obecného účtování
Nastavení hlavní knihy je jádrem finančních procesů, protože definuje, jak zaúčtujete data.  

V okně **Nastavení financí** specifikujete, jak se vypořádat s určitými účetními problémy ve vaší společnosti, jako jsou:  

* Podrobnosti o zaokrouhlení faktury  
* Formáty adres  
* Finanční sestavy  

Podobně v okně **Nastavení obecného účtování** specifikujete, jak chcete nastavit kombinace obecných obchodních a obecných produkčních účtovacích skupin. Účtovací skupiny mapují entity jako zákazníci, prodejci, zboží, zdroje a prodejní a nákupní doklady do účtů hlavní knihy. Vyplňte řádek pro každou kombinaci obchodní účtovací skupiny a produkční účtovací skupiny. Další informace naleznete v tématu [Nastavení účto skupin](finance-posting-groups.md)  

## <a name="the-chart-of-accounts"></a>Účetní osnova
Účetní osnova ukazuje všechny finanční účty. Z účetní osnovy můžete dělat věci jako:  

* Zobrazit sestavy, které ukazují položky financí a zůstatků.  
* Uzavřít výsledovku.  
* Otevřít kartu finančního účtu k přidání nebo změny nastavení.  
* Vidět seznam účtovacích skupin, podle kterých se účtuje na účet.
* Zobrazit oddělené MD a Dal zůstatky pro jednotlivý účet.  

Můžete přidat, změnit nebo smazat finanční účet. Nicméně, chcete-li zabránit nesrovnalostem, nelze smazat finanční účet, pokud jsou data použita v účetní osnově.  

## <a name="account-categories"></a>Kategorie účtů
Můžete přizpůsobit strukturu vašich financí mapováním finančních účtů na kategorie účtů.  

Okno **Kategorie finančního účtu** ukazuje kategorie a podkategorie a finanční účty, které k nim patří. Můžete vytvořit nové podkategorie a přiřadit je k existujícím účtům.  

Vytvoříte skupinu kategorií odsazením dalších podkategorií pod řádkem v okně **Kategorie finančních účtů**. Toto Vám usnadňuje získání přehledu, protože každé seskupení ukazuje celkový zůstatek. Například můžete vytvořit podkategorie pro rozdílné typy majetku a pak například vytvořit skupiny kategorií pro dlouhodobý majetek versus oběžná aktiva.  

Můžete určit, zda mají být účty v každé podkategorii zahrnuty do konkrétních typů sestav. Kategorie účtů pomáhají definovat rozložení Vašich finančních výkazů.  

Například výchozí stav zůstatku má podkategorii pro hotovost pod oběžnými aktivy. Pokud chcete výkaz zůstatku pokládat za malé výdaje a kontrolu, můžete:  

1. Přidat dvě nové podkategorie. Jednu pro malé výdaje a druhou pro kontrolující účet.  
2. Upřesněte definici přidaných sestav **Pokladní účty** pro tyto podkategorie.  
3. Vložte je do podkategorie **Pokladna**.  

Dále vygenerování účetních schémat vašich zůstatkových výkazů ukáže celkový zůstatek pro hotovost a dva řádky se zůstatky pro malé výdaje a kontrolní účet.  

## <a name="see-also"></a>Viz také
[Finance](finance.md)  
[Nastavení nebo změna účetní osnovy](finance-setup-chart-accounts.md)  
[Business Intelligence](bi.md)  

