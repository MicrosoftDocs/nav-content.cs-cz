---
title: "Návod: Použití schvalovacího workflow"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: e4135aa801b0b507b5f179d02a240a7554ed45cd
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-use-approval-workflows"></a>Návod: Použití schvalovacího workflow
Pokud musí být záznam, například nákupní doklad nebo zákaznická karta schválen někým ve vaší organizaci, odešlete požadavek na schválení jako součást workflow. Na základě nastavení workflow je příslušná schvalující osoba informována o tom, že záznam vyžaduje schválení.

Základní schvalovací workflow pro nákupní doklady, prodejní doklady, platební deníky, zákaznické karty a karty položek jsou připraveny k zahájení jako asistenční nastavení. Další informace naleznete v tématu [Vítejte v Dynamics NAV](across-get-started.md).

## <a name="to-request-approval-of-a-record"></a>Požadavek na schválení záznamu
Následující úloha je prováděna schvalovacím uživatelem.

1. V okně, které představuje záznam, zvolte akci **Odeslat žádost o schválení**.
2. Chcete-li zobrazit všechny vaše žádosti o schválení, zvolte v pravém horním rohu ikonu **Vyhledat stránku nebo sestavu**, zadejte **Požadavky na schválení** a pak vyberte související odkaz.

Stav položky ke schválení je aktualizován z **Vytvořeno** do **Otevřeno**. Stav záznamu například nákupní faktury je aktualizována z **Otevřeno** do **Čeká na schválení** a zůstává uzamčen pro zpracování až do doby, než všichni schvalovatelé schválí záznam.

Když schvalovatel schválil záznam, stav se změní na **Vydáno**. Potom můžete pokračovat ve svých úkolech se záznamem.

## <a name="to-cancel-requests-for-approval"></a>Zrušení žádosti o schválení
Následující úloha je prováděna schvalovacím uživatelem s právy schvalující osoby.

Zákazník může chtít po odeslání ke schválení změnit objednávku. V takovém případě můžete zrušit proces schvalování a provést potřebné změny objednávky, než požádáte o opětovné schválení.

1. V okně, které zobrazuje záznam, zvolte akci **Zrušit žádost o schválení**.

Pokud byla žádost o schválení zrušena, změní se status příslušné položky schválení na **Zrušeno**. Stav záznamu je aktualizován z **Čeká na schválení** do **Otevřeno**. Schvalovací proces pak může začít znovu.

## <a name="to-make-minor-changes-to-approved-records"></a>Provedení drobné změny schválených záznamů
Chcete-li provést menší změnu záznamu po jeho schválení, můžete znovu otevřít záznam, provést změnu a poté ji vydat. U drobných změn to provedete pomocí tlačítek **Znovu otevřít** a **Vydat**.

1. Otevřete okno, které zobrazuje záznam například nákupní fakturu a poté zvolte akci **Znovu otevřít**.

    Políčko **Stav dokumentu** se změní na Otevřeno.
3. Proveďte potřebné změny v záznamu, například adresu dodavatele.
4. Zvolte akci **Vydat**.

Když znovu otevřete zdrojový záznam, stav příslušné položky schválení zůstane schválen v okně **Položky ke schválení**.

## <a name="to-approve-or-reject-requests-for-approval"></a>Schválení nebo odmítnutí žádosti o schválení
Následující úloha je prováděna schvalovacím uživatelem s právy schvalující osoby.

Žádosti o schválení můžete zpracovat v okně **Požadavky na schválení** například za účelem schválení více žádostí najednou. Alternativně můžete zpracovat každý požadavek na souvisejícím záznamu například okno **Nákupní faktura**, výběrem odkazu v obdržené notifikaci.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Požadavky na schválení** a pak vyberte související odkaz. 
2. Vyberte jeden nebo více řádků pro záznam nebo záznamy, které chcete schválit nebo odmítnout.
3. Zvolte akci **Schválit**, **Odmítnout** nebo **Delegovat**.

Pokud byl záznam schválen nebo odmítnut, změní se stav schválení v poli **Stav** na **Schváleno** nebo **Odmítnuto**.

Je-li nastavena schvalovací hierarchie, stav záznamu bude **Čeká na schválení**, dokud všichni schvalovatelé neschválí záznam. Pak se stav záznamu změní na **Vydáno**.

Současně se stav schválení změní z **Vytvořeno** na **Otevřeno**, jakmile bude vytvořena žádost o schválení pro záznam. Pokud je žádost zamítnuta, změní se status schválení na **Odmítnuto**. Stav zůstává **Otevřeno** nebo **Odmítnuto**, dokud všichni schvalující žádost neschválí.

## <a name="to-delegate-requests-for-approval"></a>Delegování žádosti o schválení
Následující úloha je prováděna schvalovacím uživatelem s právy schvalující osoby.

Chcete-li zabránit tomu, aby se dokumenty shromažďovaly nebo jinak zablokovaly workflow, schvalovatel a správce schvalování mohou přenést žádost o schválení na náhradního schvalujícího. Náhradník může být buď určeným náhradníkem, přímým schvalovatelem nebo schvalovacím správcem v uvedeném pořadí priority. Tuto funkci obvykle používáte, pokud je schvalovatel mimo kancelář a není schopen schválit žádosti před datem splatnosti.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Požadavky na schválení** a pak vyberte související odkaz.
2. Vyberte jeden nebo více řádků pro žádosti o schválení, které chcete přenést na náhradního schvalujícího a potom vyberte akci **Delegovat**.

Oznámení o schválení žádosti je odesláno schvalujícímu náhradníkovi.

## <a name="to-manage-overdue-approval-requests"></a>Správa žádostí o schválení po splatnosti
Následující úloha je prováděna schvalovacím uživatelem s právy schvalující osoby.

V pravidelných intervalech musíte připomenout uživatelům schvalovacího workflow žádosti o schválení po splatnosti, na které musí reagovat. Použijete funkci Odeslání upozornění o schválení.

Funkce Odeslání upozornění o schválení kontroluje všechny otevřené žádosti o schválení, které jsou v současné době opožděné. Každý schvalovatel, který má alespoň jeden záznam o schválení po uplynutí doby platnosti, obdrží oznámení se seznamem všech žádostí o schválení po splatnosti. Oznámení se také zašle jejich schvalovatelům a všem žadatelům o schválení po splatnosti. Toto pomáhá, pokud musí být položka schválení po splatnosti delegována na náhradníka.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Požadavky na schválení po splatnosti** a pak vyberte související odkaz.
2. V okně **Požadavky na schválení po splatnosti** zvolte akci **Odeslat upozornění o schválení po splatnosti**.

## <a name="see-also"></a>Viz také  
[Správa prodeje](sales-manage-sales.md)    
[Došlé doklady](across-income-documents.md)  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Práce s Dynamics NAV](ui-work-product.md)

