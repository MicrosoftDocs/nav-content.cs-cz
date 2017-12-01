---
title: Odpis nebo amortizace DM
description: "Musíte definovat jak budete odpisovat, znehodnocovat nebo amortizovat každý s dlouhodobého majetku."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: write down
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 582be0b55df7f3f353b5320080e56e4922cb789a
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-depreciate-or-amortize-fixed-assets"></a>Návod: Odepsání nebo amortizace dlouhodobého majetku
Odpisy se používají k rozdělení nákladů na dlouhodobý majetek, jako jsou stroje a zařízení na dobu jejich odpisovatelného života. Pro každý dlouhodobý majetek musíte definovat, jak bude odpisován.  

 Existují dva způsoby, jak zaúčtovat odpis:  

* Automaticky spuštěním dávkové úlohy **Výpočet odpisu**.  
* Ručně pomocí DM ve finančním deníku.  

[!INCLUDE[d365fin](includes/d365fin_md.md)] Můžete vypočítat denní odpis, který vám umožní vypočítat odpisy za jakékoliv období. Můžete tedy analyzovat aktuální provozní výsledky, například měsíční, čtvrtletní nebo roční. Výpočet používá standardní rok 360 dnů a standardní měsíc 30 dní. Další informace naleznete v tématu [Metody odpisování](fa-depreciation-methods.md).  

Pokud je dlouhodobý majetek využíván několika odděleními, mohou být tyto oddělení automaticky přiděleny pravidelně podle odměnové tabulky definované uživatelem.  

Záznamy o nesprávném odpisu můžete zrušit pomocí dávkové úlohy **Storno položek DM**. Poté můžete zaúčtovat správné množství odpisů spuštěním dávkové úlohy **Výpočet odpisů** znovu. Když opravujete chyby, jsou zaúčtovány jako chyby v položkách knih DM.  

Odsazení slouží k úpravě hodnot pro obecné změny cenové hladiny. Dávková úloha **Indexovat DM** může být použita k vypočítání odpisové částky.  

## <a name="to-calculate-depreciation-automatically"></a>Automatický výpočet odpisu
Jednou za měsíc nebo vždy, když si zvolíte, můžete spustit dávkovou úlohu **Výpočet odpisů**. Dávková úloha ignoruje dlouhodobý majetek, který byl prodán, blokován nebo neaktivní, nebo odepsán ruční metodou.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Výpočet odpisů** a pak vyberte související odkaz.  
2. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
3. Zvolte tlačítko **OK**.  

    Dávková úloha vypočítá odpis a vytvoří řádky ve finančním deníku DM.  
4. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.  

    V okně **Dlouhodobý majetek finančního deníku** v poli **Počet dní odpisu** můžete vidět, za kolik dní byly odpisy vypočteny.  
5. Zvolte akci **Zaúčtovat**.  

## <a name="to-post-depreciation-manually-from-the-fixed-asset-gl-journal"></a>Zaúčtování odpisů ručně z finančního deníku DM
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.  
2. Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby.  
3. Do pole **Typ účtování DM** vyberte **Odpis**.  
4. Zvolte možnost **Vložit protiúčet DM**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování odpisů. Další informace naleznete v tématu "Nastavení skupin zaúčtování DM“ v [Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).  
5. Na kartě **Domů** vyberte možnost **Účtovat** k zaúčtování deníku.  

Pokud jste nastavili přidělovací klíče DM pro přidělování částek různým oddělením nebo projektům, pak budou částky přiděleny během zaúčtování. Další informace naleznete v tématu [Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).  

## <a name="to-calculate-allocations-in-the-fixed-asset-gl-journal"></a>Výpočet přidělení ve finančním deníku DM
Pokud je dlouhodobý majetek využíván několika odděleními, mohou být tyto oddělení automaticky přiděleny pravidelně podle odměnové tabulky definované uživatelem.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.  
2. Vytvořte počáteční řádek a vyplňte pole podle potřeby.
3. Do pole **Typ účtování DM** vyberte **Přidělení**.  
4. Zvolte možnost **Vložit protiúčet** **DM**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování přidělení.  
5. Na kartě **Domů** vyberte možnost **Účtovat** k zaúčtování deníku.  

## <a name="use-duplication-lists-to-prepare-to-post-to-multiple-depreciation-books"></a>Použijte duplicitní seznamy, abyste se mohli připravit k zaúčtování více odpisových knih
Když vyplníte řádky deníků, které mají být zaúčtovány do odpisové knihy, můžete duplikovat řádky v samostatném deníku, po kterém mohou být zaúčtovány do jiné odpisové knihy. Další informace naleznete v tématu "Zaúčtování položek do různých odpisových knih".

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Odpisové knihy** a pak vyberte související odkaz.  
2. Otevřete příslušnou odpisovou knihu a zaškrtněte políčko **Část seznamu duplikací**.  

> [!IMPORTANT]  
>   Pokud jste vybrali políčko **Použít seznam duplikací**, nepoužívejte v deníku číselné řady. Důvodem je, že číselné řady pro dlouhodobý majetek finančního deníku nepředstavují číselné řady pro dlouhodobý majetek deníku.  

## <a name="to-post-entries-to-different-depreciation-books"></a>Zaúčtování položek do různých odpisových knih
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.  
2. V deníku, který chcete zaúčtovat, zaškrtněte políčko **Použít seznam duplikací**.  
3. Vyplňte pole podle potřeby.  
4. Zvolte akci **Zaúčtovat**.  
5. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deník DM** a pak vyberte související odkaz.  

    > [!NOTE]  
>   Okno **Deník DM** obsahuje nové řádky pro různé odpisové knihy podle seznamu duplikací.  
6. Ověřte nebo upravte řádky a vyberte akci **Odeslat**.  

    > [!NOTE]  
>   Dalším způsobem jak duplikovat položku v samostatné knize je zadat v kódu odpisové knihy pole **Duplikovat do odpisové knihy**, když vyplníte řádek deníku.  

Můžete kopírovat položky z jedné odpisové knihy do jiné pomocí dávkové úlohy **Kopie odpisových knih**. Dávková úloha vytvoří řádky deníku v dávkovém deníku, který jste zadali v okně **Nastavení deníku DM** pro odpisovou knihu, kterou chcete kopírovat. Další informace naleznete v následujícím postupu.  

## <a name="to-copy-fixed-asset-ledger-entries-between-depreciation-books"></a>Zkopírování položek knihy DM mezi odpisovými knihami
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Odpisové knihy** a pak vyberte související odkaz.  
2. Otevřete příslušnou kartu odpisové knihy a potom vyberte akci **Kopírovat odpisovou knihu**.  
3. V okně **Kopírovat odpisovou knihu** vyplňte pole podle potřeby.  
4. Zvolte tlačítko **OK**.  

Zkopírované řádky jsou vytvářeny buď ve finančním deníku DM nebo deníku DM v závislosti na tom, zda je odpisová kniha, kterou kopírujete integrována do hlavní knihy.  

## <a name="see-also"></a>Viz také
[Dlouhodobý majetek](fa-manage.md)  
[Nastavení DM](fa-setup.md)  
[Finance](finance.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

