---
title: "Nastavení cyklů prodejních příležitostí a fází prodejních cyklů"
description: "Popisuje jak definovat prodejní fáze, od založení kontaktu až po uzavření, vytvoření prodejního cyklu a přiřazení příležitostem v Dynamics NAV."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 547e24b87fcd643406f1aa9cbde9bf85c44cae71
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-opportunity-sales-cycles-and-cycle-stages"></a>Návody: Nastavení cyklů prodejních příležitostí a fází prodejních cyklů
Než začnete využívat prodejní příležitosti, musíte nastavit prodejní cykly a fáze prodejního cyklu. Prodejní cyklus se skládá ze série fází, které jdou od počátečního kontaktu až k uzavření prodeje. Každá fáze může mít určité požadavky, které musí být splněny, jako je požadavek na prodejní nabídku, než může jít příležitost do další fáze. Můžete také určit, zda je možné přeskočit fázi. Můžete nastavit tolik prodejních cyklů, kolik potřebujete, a můžete nastavit tolik fází prodejních cyklů, kolik bude potřeba v rámci prodejního cyklu.

Implementace příležitostných prodejních cyklů zahrnuje nastavení prodejního cyklu, definování jednotlivých fází cyklu a následné zařazení cyklu do příležitostí. Součástí nastavení prodejního cyklu také může být přiřazení příslušné aktivity nebo úkoly k příležitosti.

Toto téma také popisuje jak nastavit úkoly a aktivity a jak přiřadit úkoly k aktivitám. Další informace naleznete v tématu "Nastavení aktivit s úkoly".

## <a name="to-set-up-opportunity-sales-cycle-codes"></a>Nastavení kódu příležitostného prodejního cyklu
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní cykly** a vyberte související odkaz. Otevře se okno **Prodejní cykly** a zobrazí seznam všech stávajících prodejních cyklů.
2. Vyberte akci **Nový** a poté vyplňte potřebná pole. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

Opakujte tyto kroky k nastavení prodejních cyklů tolikrát, kolik jich budete potřebovat. Po nastavení příležitostných prodejních cyklů můžete nastavit různé fáze v rámci každého cyklu.

## <a name="to-define-opportunity-sales-cycle-stages"></a>Definování fáze příležitostných prodejních cyklů
1. V okně **Prodejní cykly** vyberte příležitostný prodejní cyklus, pro který chcete nastavit fáze, a poté zvolte akci **Fáze**. Zobrazí se okno **Fáze prodejních cyklů**.
2. Zvolte akci **Nový**, chcete-li zadat novou fázi v prodejním cyklu.

Opakujte tyto kroky, abyste nastavili tolik fází, kolik v rámci prodejního cyklu chcete.

## <a name="to-assign-stage-cycles-to-opportunities"></a>Přiřazení fáze cyklů k příležitostem
Po přidání  příležitostného prodejního cyklu můžete začít přidávat prodejní příležitosti a přiřadit cyklus fáze k příležitostem nastavením pole **Kód prodejního cyklu**. Další informace naleznete v tématu [Návod: Vytvoření prodejních příležitostí.](marketing-how-create-opportunities.md)

## <a name="to-set-up-activities-with-tasks"></a>Nastavení aktivit s úkoly
Můžete kombinovat několik úkolů, například úkoly představující krok aktivity. Úkoly aktivit jsou navzájem propojeny vzorem data. Můžete přiřazovat aktivity příležitostem, prodejcům nebo kontaktům.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Aktivity** a vyberte související odkaz.
2. Vyberte akci **Nový** a poté vyplňte potřebná pole.
3. Na záložce **Řádky** vyplňte pole podle potřeby k definování jednoho nebo více úkolů aktivity.

## <a name="to-assign-tasks-or-activities-of-tasks-to-opportunities"></a>Přiřazení úkolů nebo úkolů aktivity k příležitosti
Když založíte úkol, můžete ho připsat k prodejní příležitosti a tím přiřadit aktivity do daného úkolu.

> [!NOTE]  
>   Tato procedura popisuje jak přiřadit úkol aktivity k příležitosti. Kroky jsou stejní jako při přiřazování úkolů prodejci nebo kontaktu.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Příležitosti** a vyberte související odkaz.
2. Vyberte příležitost a poté zvolte akci **Úkoly**.
3. V okně **Seznam úkolů** zvolte akci **Vytvořit úkol**.
4.  V okně **Vytvořit úkol** vyplňte pole podle potřeby.

    V poli **Příležitosti** si všimněte, že je automaticky přiděleno příslušné příležitosti.
5. Zvolte tlačítko **OK**.
6. V okně **Seznam úkolů** vyberte nový úkol a pak vyberte akci **Přiřadit aktivitu**.
7. V okně **Přiřadit aktivitu** vyplňte pole podle potřeby a poté klepněte na tlačítko **OK**.

## <a name="see-also"></a>Viz také
[Zpracování prodejních příležitostí](marketing-processing-sales-opportunities.md)  
[Prodej](sales-manage-sales.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

