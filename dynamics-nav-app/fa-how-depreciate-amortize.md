---
title: "Návod: Odpis a amortizace DM"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: af71f30681d436ed5da1cd6cb3c2e13f86558631
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-depreciate-or-amortize-fixed-assets"></a>Návod: Odpis a amortizace DM
Odpisy se používají k rozdělení nákladů na dlouhodobý majetek, jako jsou stroje a zařízení na dobu jejich odpisovatelného života. Pro každý dlouhodobý majetek musíte definovat, jak bude odpisován.  

 Existují dva způsoby, jak zaúčtovat odpis:
- Automaticky spuštěním dávkové úlohy **Výpočet odpisu**.
- Ručně pomocí DM ve finančním deníku.  

Dynamics NAV může vypočítat denní odpis, který vám umožní vypočítat odpisy za jakékoliv období. Můžete tedy analyzovat aktuální provozní výsledky, například měsíční, čtvrtletní nebo roční. Výpočet používá standardní rok 360 dnů a standardní měsíc 30 dní. Další informace naleznete v tématu [Metody odpisování](fa-depreciation-methods.md).

Pokud je dlouhodobý majetek využíván několika odděleními, mohou být tyto oddělení automaticky přiděleny pravidelně podle odměnové tabulky definované uživatelem.  

Záznamy o nesprávném odpisu můžete zrušit pomocí dávkové úlohy **Zrušit položky knihy DM**. Poté můžete zaúčtovat správné množství odpisů spuštěním dávkové úlohy **Výpočet odpisů** znovu. Když opravujete chyby, jsou zaúčtovány jako chyby v položkách knih DM.  

Odsazení slouží k úpravě hodnot pro obecné změny cenové hladiny. Dávková úloha **Indexovat DM** může být použita k vypočítání pořizovací ceny v reprodukčních nákladech.  

## <a name="to-calculate-a-depreciation-automatically"></a>Automatický výpočet odpisu
Jednou za měsíc nebo vždy, když si zvolíte, můžete spustit dávkovou úlohu **Výpočet odpisů**. Prodaný dlouhodobý majetek, který je blokován nebo neaktivní a dlouhodobý majetek, který používá metodu ručního odpisování, je ignorován.    

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Výpočet Odpisu** a pak vyberte související odkaz.  
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
3. Zvolte tlačítko **OK**.  

    Dávková úloha vypočítá odpis a vytvoří řádky ve finančním deníku DM.  
4. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Finanční deník** a pak vyberte související odkaz.

    V okně **Dlouhodobý majetek finančního deníku** v poli **Počet dní odpisu** můžete vidět, za kolik dní byly odpisy vypočteny.  
5. Zvolte akci **Účtovat**.

## <a name="to-post-a-depreciation-manually-from-the-fixed-asset-gl-journal"></a>Zaúčtování odpisů ručně z finančního deníku DM
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek finančního deníku** a pak vyberte související odkaz.  
2. Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby.
3. Do pole **Typ zaúčtování DM** vyberte **Odpis**.
4. Zvolte** možnost Vložit protiúčet DM**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování odpisů. Další informace naleznete v tématu "Nastavení skupin zaúčtování DM“[Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).
5. Na kartě **Domů** vyberte možnost **Účtovat** k zaúčtování deníku.

Pokud jste nastavili přidělovací klíče DM pro přidělování částek různým oddělením nebo projektům, pak budou částky přiděleny během zaúčtování. Další informace naleznete v tématu [Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).

## <a name="to-calculate-allocations-in-the-fixed-asset-gl-journal"></a>Výpočet přidělení ve finančním deníku DM
Pokud je dlouhodobý majetek využíván několika odděleními, mohou být tyto oddělení automaticky přiděleny pravidelně podle odměnové tabulky definované uživatelem.  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek finančního deníku** a pak vyberte související odkaz.   
Vytvořte počáteční řádek a vyplňte pole podle potřeby.
3. Do pole **Typ zaúčtování DM** vyberte **Přidělení**.
4. Zvolte** **možnost **Vložit protiúčet DM**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování přidělení.
5. Na kartě **Domů** vyberte možnost **Účtovat** k zaúčtování deníku.

## <a name="use-duplication-lists-to-prepare-to-post-to-multiple-depreciation-books"></a>Použijte duplicitní seznamy, abyste se mohli připravit k zaúčtování více odpisových knih  
Když vyplníte řádky deníků, které mají být zaúčtovány do odpisové knihy, můžete duplikovat řádky v samostatném deníku, po kterém mohou být zaúčtovány do jiné odpisové knihy. Další informace naleznete v tématu "Zaúčtování položek do různých odpisových knih".

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Odpisové knihy** a pak vyberte související odkaz.  
2. Otevřete příslušnou odpisovou knihu a zaškrtněte políčko **Část seznamu duplikací**.  

**Důležité**: Pokud jste vybrali políčko **Použít seznam duplikací**, nepoužívejte v deníku číselné řady. Důvodem je, že číselné řady pro dlouhodobý majetek finančního deníku nepředstavují číselné řady pro dlouhodobý majetek deníku.

## <a name="to-post-entries-to-different-depreciation-books"></a>Zaúčtování položek do různých odpisových knih  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek finančního deníku** a pak vyberte související odkaz.
2. V deníku, který chcete zaúčtovat, zaškrtněte políčko **Použít seznam duplikací**.
3. Vyplňte pole podle potřeby.
4. Zvolte akci **Zaúčtovat**.
5. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deník DM** a pak vyberte související odkaz.

    Okno **Deník DM** obsahuje nové řádky pro různé odpisové knihy podle seznamu duplikací.   

6. Ověřte nebo upravte řádky a vyberte akci **Odeslat**.

**Poznámka**: Dalším způsobem jak duplikovat položku v samostatné knize je zadat v kódu odpisové knihy pole **Duplikovat do odpisové knihy**, když vyplníte řádek deníku.

Můžete kopírovat položky z jedné odpisové knihy do jiné s dávkovou úlohou **Kopie odpisových knih**. Dávková úloha vytvoří řádky deníku v dávkovém deníku, který jste zadali v okně **Nastavení deníku DM** pro odpisovou knihu, kterou chcete kopírovat. Další informace naleznete v následujícím postupu.

## <a name="to-copy-fixed-asset-ledger-entries-between-depreciation-books"></a>Zkopírování položek knihy DM mezi odpisovými knihami  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Odpisové knihy** a pak vyberte související odkaz.
2. Otevřete příslušnou kartu odpisové knihy a potom vyberte akci **Kopírovat odpisovou knihu**.  
3. V okně **Kopírovat odpisovou knihu** vyplňte pole podle potřeby.  
4. Zvolte tlačítko **OK**.  

Zkopírované řádky jsou vytvářeny buď ve finančním deníku DM nebo deníku DM v závislosti na tom, zda je odpisová kniha, kterou kopírujete integrována do hlavní knihy.

## <a name="see-also"></a>Viz také
[Správa DM](fa-manage.md)  
[Nastavení DM](fa-setup.md)  
[Finance](finance-setup.md)  
[Vítejte v Dynamics NAV](across-get-started.md)

