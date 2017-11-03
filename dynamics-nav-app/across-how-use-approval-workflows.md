---
title: "Schválení nebo odmítnutí dokladů ve workflow."
description: "Žádost, zamítnutí nebo delegování schválení například nákupního nebo prodejního dokladu jako část workflow."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: reject, delegate, request
ms.date: 08/24/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: b0cd3c6c2465c29d5e4710ae2ef13e3f42522245
ms.contentlocale: cs-cz
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-use-approval-workflows"></a>Návod: Použití schvalovacího workflow
Pokud musí být záznam, například nákupní doklad nebo zákaznická karta schválen někým ve vaší organizaci, odešlete požadavek na schválení jako součást workflow. Na základě nastavení workflow je příslušná schvalující osoba informována o tom, že záznam vyžaduje schválení.

Nastavení schvalovacího workflow v okně **Workflow**. Další informace naleznete v tématu: [Nastavení workflow](across-set-up-workflows.md).

Kromě schvalovacích pracovních postupů popsaných v tomto tématu můžete provádět různé další úkoly pracovního postupu. Další informace naleznete v tématu: [Použití WorkFlow](across-use-workflows.md).

Základní schvalovací workflow pro nákupní doklady, prodejní doklady, platební deníky, zákaznické karty a karty položek jsou připraveny k zahájení jako asistenční nastavení. Další informace naleznete v tématu[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md).

## <a name="to-request-approval-of-a-record"></a>Požadavek na schválení záznamu
Následující úloha je prováděna schvalovacím uživatelem.

1. V okně, které představuje záznam, zvolte akci **Odeslat žádost o schválení**.
2. Chcete-li zobrazit všechny vaše žádosti o schválení, zvolte ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Položky na schválení** a pak vyberte související odkaz.  

Stav položky ke schválení je aktualizován z **Vytvořeno** do **Otevřeno**. Stav záznamu například nákupní faktury je aktualizována z **Otevřeno** do **Čeká na schválení** a zůstává uzamčen pro zpracování až do doby, než všichni schvalovatelé schválí záznam.

Když schvalovatel schválil záznam, stav se změní na **Vydáno**. Potom můžete pokračovat ve svých úkolech se záznamem.

## <a name="to-cancel-requests-for-approval"></a>Zrušení žádosti o schválení
Následující úloha je prováděna schvalovacím uživatelem s právy schvalující osoby.

Zákazník může chtít po odeslání ke schválení změnit objednávku. V takovém případě můžete zrušit proces schvalování a provést potřebné změny objednávky, než požádáte o opětovné schválení.

- V okně, které zobrazuje záznam, zvolte akci **Zrušit žádost o schválení**.

Pokud byla žádost o schválení zrušena, změní se status příslušné položky schválení na **Zrušeno**. Stav záznamu je aktualizován z **Čeká na schválení** do **Otevřeno**. Schvalovací proces pak může začít znovu.

## <a name="to-approve-or-reject-requests-for-approval"></a>Schválení nebo odmítnutí žádosti o schválení
Následující úloha je prováděna schvalovacím uživatelem s právy schvalující osoby.

Žádosti o schválení můžete zpracovat v okně **Požadavky na schválení** například za účelem schválení více žádostí najednou. Alternativně můžete zpracovat každý požadavek na souvisejícím záznamu například okno **Nákupní faktura**, výběrem odkazu v obdržené notifikaci.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Požadavky ke schválení** a pak vyberte související odkaz.
2. Vyberte jeden nebo více řádků pro záznam nebo záznamy, které chcete schválit nebo odmítnout.
3. Zvolte akci **Schválit**, **Odmítnout** nebo **Delegovat**.

Pokud byl záznam schválen nebo odmítnut, změní se stav schválení v poli **Stav** na **Schváleno** nebo **Odmítnuto**.

Je-li nastavena schvalovací hierarchie, stav záznamu bude **Čeká na schválení**, dokud všichni schvalovatelé neschválí záznam. Pak se stav záznamu změní na **Vydáno**.

Současně se stav schválení změní z **Vytvořeno** na **Otevřeno**, jakmile bude vytvořena žádost o schválení pro záznam. Pokud je žádost zamítnuta, změní se status schválení na **Odmítnuto**. Stav zůstává **Otevřeno** nebo **Odmítnuto**, dokud všichni schvalující žádost neschválí.

## <a name="to-delegate-requests-for-approval"></a>Delegování žádosti o schválení
Následující úloha je prováděna schvalovacím uživatelem s právy schvalující osoby.

Chcete-li zabránit tomu, aby se dokumenty shromažďovaly nebo jinak zablokovaly workflow, schvalovatel a správce schvalování mohou přenést žádost o schválení na náhradního schvalujícího. Náhradník může být buď určeným náhradníkem, přímým schvalovatelem nebo schvalovacím správcem v uvedeném pořadí priority. Tuto funkci obvykle používáte, pokud je schvalovatel mimo kancelář a není schopen schválit žádosti před datem splatnosti.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Požadavky ke schválení** a pak vyberte související odkaz.
2. Vyberte jeden nebo více řádků pro žádosti o schválení, které chcete přenést na náhradního schvalujícího a potom vyberte akci **Delegovat**.

Oznámení o schválení žádosti je odesláno schvalujícímu náhradníkovi.

## <a name="to-manage-overdue-approval-requests"></a>Správa žádostí o schválení po splatnosti
Následující úloha je prováděna schvalovacím uživatelem s právy schvalující osoby.

V pravidelných intervalech musíte připomenout uživatelům schvalovacího workflow žádosti o schválení po splatnosti, na které musí reagovat. Použijete funkci **Odeslání upozornění o schválení**.

Funkce **Odeslání upozornění o schválení** kontroluje všechny otevřené žádosti o schválení, které jsou v současné době opožděné. Každý schvalovatel, který má alespoň jeden záznam o schválení po uplynutí doby platnosti, obdrží oznámení se seznamem všech žádostí o schválení po splatnosti. Oznámení se také zašle jejich schvalovatelům a všem žadatelům o schválení po splatnosti. Toto pomáhá, pokud musí být položka schválení po splatnosti delegována na náhradníka.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Upozornění o schválení** a pak vyberte související odkaz.
2. V okně **Požadavky na schválení po splatnosti** zvolte akci **Odeslat upozornění o schválení po splatnosti**.

## <a name="see-also"></a>Viz také
[Prodej](sales-manage-sales.md)    
[Došlé doklady](across-income-documents.md)  
[Nákup](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

