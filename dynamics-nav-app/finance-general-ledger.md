---
title: "Hlavní kniha a Účtová osnova"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 9965ddcad214e97c5e4858824395d6f651b3c003
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="the-general-ledger-and-the-chart-of-accounts"></a>Hlavní kniha a Účtová osnova
Hlavní kniha ukládá vaše finanční data a účtová osnova ukazuje účty, ke kterým jsou položky hlavní knihy zaúčtovány. Dynamics NAV zahrnuje standardní účtovou osnovu, která je připravena podpořit váš obchod.

## <a name="general-ledger-setup-and-general-posting-setup"></a>Nastavení hlavní knihy a obecného účtování
V jádře vašich obchodních procesů je hlavní kniha a konfigurace, jak jsou data účtována do hlavní knihy.
V okně **Nastavení hlavní knihy** specifikujete, jak se vypořádat s určitými účetními problémy ve vaší firmě. To zahrnuje zaokrouhlování fakturačních detailů, formát adres a například, jestli chcete použít přídavnou měnu pro hlášení.
Podobně v okně **Nastavení obecného účtování** specifikujete, jak chcete nastavit kombinace obecných obchodních a obecných produkčních účtovacích skupin. Vyplňte řádek pro každou kombinaci obchodní účtovací skupiny a produkční účtovací skupiny.  

## <a name="the-chart-of-accounts"></a>Účtová osnova
Účtová osnova ukazuje všechny účty. Odtud můžete otevřít různé sestavy, které ukazují položky hlavní knihy a zůstatky, a můžete uzavřít výsledovku. Pro každý účet můžete otevřít kartu finančních účtů a přidat nebo změnit nastavení. Můžete také vidět seznam účtovacích skupin, které tomu účtu účtují.  

Dynamics NAV bude předcházet tomu, abyste si vymazali účet hlavní knihy, který ukládá potřebné v účtové osnově.  

## <a name="account-categories"></a>Kategorie účtů
S kategoriemi účtů, můžete mapovat účty hlavní knihy ke kategoriím jako je personalizace struktury vašich finančních výkazů.  

Okno **Kategorie finančního účtu** ukazuje existující hlavní kategorie a podkategorie a finanční účty, které jste přiřadili ke každé kategorii. Můžete vytvořit nové podkategorie a přiřadit je k existujícím účtům.  

Můžete seskupit kategorie účtů odsazením individuálních kategorií. Tohle vám usnadňuje získání přehledu, protože každé seskupení ukazuje celkový zůstatek. Například můžete vytvořit podkategorie pro rozdílné typy majetku a pak například vytvořit skupiny kategorií pro dlouhodobý majetek versus běžná aktiva. Vytvoříte skupinu kategorií odsazením dalších podkategorií pod řádkem v okně **Kategorie finančních účtů**.  

Pro každou podkategorii můžete specifikovat, zda účty této kategorie musí být zahrnuty do specifických typů finančních sestav. Kategorie účtů pomáhají definovat rozložení vašich finančních výkazů. Například, výchozí stav zůstatku má jednu položku pro hotovost pod majetkem. Pokud chcete, aby byl stav zůstatku pro malé výdaje a váš kontrolní účet, pak můžete přidat dvě nové podkategorie, specifikovat přídavné definice sestav Hotovostní účty pro každý z nich a odsadit je pod Hotovostní podkategorie. Pak když jste vygenerovali účetní schémata založené na vašich změnách, váš další stav zůstatku bude ukazovat celkový zůstatek hotovosti a dva řádky se zůstatky pro malé výdaje a kontrolní účet.     

##<a name="see-also"></a>Viz také
[Finance](finance-setup.md)  
[Nastavení nebo změna účtové osnovy](finance-setup-setup-chart-accounts.md)  
[Účetní schémata](finance-setup-account-schedule.md)  

