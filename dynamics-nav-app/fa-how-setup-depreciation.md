---
title: "Nastavení odpisu DM"
description: "Uvádíte v odpisové knize, jak chcete, aby byl dlouhodobý majetek odpisován nebo odepsán."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: write down
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 6fcc5d86da55923a671c001ab423b6da01d7d3da
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-fixed-asset-depreciation"></a>Návod: Nastavení odpisu dlouhodobého majetku
 Můžete použít různé metody odpisování pro sestavení finančního výkazu a daně z příjmu. Mnoho velkých společností používá přímé odpisy v jejich finančních výkazech, protože toto obecně umožňuje vykazovat vyšší výdělky. Pro účely daně z příjmů však mnoho podniků používá metodu zrychleného odpisování. Další informace naleznete v tématu [Metody odpisování](fa-depreciation-methods.md).

 Když jste vytvořili příslušné odpisové knihy, musíte každému dlouhodobému majetku přiřadit jeden nebo více odpisových knih. Odpisová kniha, která je přidělena k dlouhodobému majetku, se označuje jako odpisová kniha DM. Okno pro přidělené odpisové knihy se jmenuje **Knihy odpisů DM**.

## <a name="to-create-a-depreciation-book"></a>Vytvoření odpisové knihy
V odpisové knize DM specifikujete, jak je odpisován dlouhodobý majetek. Chcete-li přizpůsobit různé metody odpisování, můžete nastavit více odpisových knih.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Knihy odpisů** a pak vyberte související odkaz.
2. V okně **Seznam knih odpisů** zvolte akci **Nový**.
3. V okně **Karta knihy odpisů** vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    > [!NOTE]  
>   Můžete zaznamenat transakce dlouhodobého majetku v okně **Finanční deník DM** nebo v okně **Deník dlouhodobého majetku** podle toho, zda jsou transakce pro finanční generování sestav nebo interní správu. Postupujte podle následujícího kroku a definujte, který typ deníku se používá pro různé činnosti DM ve výchozím nastavení.
4. Na kartě záložky s náhledem **Integrace** vyberte zaškrtávací políčko pro každou aktivitu DM, jejíž transakce chcete zaúčtovat pomocí okna **Finanční deník DM**.
5. Opakujte kroky 2 až 4 pro každou metodu odpisování nebo metodu zaúčtování, kterou chcete přiřadit k dlouhodobému majetku jako odpisovou knihu.

## <a name="to-assign-a-depreciation-book-to-a-fixed-asset"></a>Přiřazení odpisové knihy k dlouhodobému majetku
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, pro který chcete nastavit odpisovou knihu DM.
3. V záložce s náhledem **Knihy odpisů** vyplňte pole podle potřeby.
4. Pokud potřebujete přiřadit k dlouhodobému majetku více než jednu knihu odpisů, zvolte akci **Přidat více knih odpisů**.
5. Případně vyberte akci **Knihy odpisů** k určení jedné nebo více odpisových knih DM.

    > [!NOTE]  
>   Pokud používáte ruční metodu odpisů, je nutné ručně zadat odpis DM ve finančním deníku. Funkce **Výpočet odpisů** vynechává dlouhodobý majetek, který používá metodu ručního odpisování. Tuto metodu můžete použít pro majetek, který nepodléhá odpisům například pozemky.

## <a name="to-assign-a-depreciation-book-to-multiple-fixed-assets-with-a-batch-job"></a>Přidělení odpisové knihy do více dlouhodobých aktiv s dávkovou úlohou
Chcete-li přiřadit odpisovou knihu k více dlouhodobému majetku, můžete použít dávkovou úlohu **Vytvořit knihy odpisů DM** k vytvoření odpisových knih dlouhodobého majetku.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, u kterého chcete přiřadit odpisovou knihu a pak vyberte akci **Upravit**.
3. Na kartě **Karta knihy odpisů** vyberte akci **Vytvořit knihy odpisů DM**.
4. V okně **Vytvořit knihy odpisů DM** vyplňte pole **Kniha odpisů**.
5. Zvolte pole **Kopie čísla z DM** a poté vyberte číslo DM, které chcete použít jako základ pro vytváření nových odpisových knih DM.

    Pokud vyplníte toto pole, odpisové pole v nových odpisových knihách DM bude obsahovat stejné informace jako odpovídající pole v odpisové knize DM, z které jste kopírovali. Ponechejte pole prázdné, chcete-li vytvořit nové odpisové knihy DM s prázdnými poli odpisů.  
6. Na záložce s náhledem **Dlouhodobý majetek** můžete nastavit filtr pro výběr majetku, který chcete vytvořit pro odpisové knihy DM.
7. Zvolte tlačítko **OK**.

## <a name="to-set-up-depreciation-posting-types"></a>Nastavení typů odpisů zaúčtování
Pro každou odpisovou knihu musíte nastavit, jak chcete v [!INCLUDE[d365fin](includes/d365fin_md.md)] zpracovávat různé typy zaúčtování. Například, zda by zaúčtování mělo být MD nebo Dal a zda by měl být typ zaúčtování zahrnut do odpisovatelného základu.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Knihy odpisů** a pak vyberte související odkaz.  
2. Vyberte odpisovou knihu, kterou chcete nastavit a poté vyberte akci **Nastavení typu účtování DM**.
3. V okně **Nastavení typu účtování DM** vyplňte pole podle potřeby.

    > [!NOTE]  
>   Nemůžete vložit nebo odstranit řádky v okně **Nastavení typu účtování DM**. Můžete upravit pouze existující řádky.

    Doporučujeme, abyste nezměnili nastavení odpisových knih pro položky, které již byly zaúčtovány. Změny nebudou mít vliv na položky, které již byly zaúčtovány, což by způsobilo statistiky odpisových knih zavádějící.

## <a name="to-set-up-default-templates-and-batches-for-fixed-asset-depreciation"></a>Nastavení výchozích šablon a dávek pro odpisy DM
Pro každou odpisovou knihu definujete výchozí nastavení šablon a dávek. Použijte tyto výchozí hodnoty pro duplikování řádků z jednoho deníku do jiného, vytvořte řádky deníku pomocí dávkových úloh **Výpočet odpisů** nebo **Indexovat DM**, duplikujte pořizovací náklady v deníku pojištění.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Knihy odpisů** a pak vyberte související odkaz.  
2. Vyberte odpisovou knihu, pro kterou chcete definovat výchozí deník a poté vyberte akci **Nastavení deníku DM**.  
3. Chcete-li mít výchozí nastavení pro každého uživatele, vyberte pole **ID uživatele** z okna **Uživatelé**.  
4. V ostatních polích vyberte šablonu deníku nebo dávku deníku, která musí být použita ve výchozím nastavení.  

## <a name="see-also"></a>Viz také
[Nastavení DM](fa-setup.md)  
[Dlouhodobý majetek](fa-manage.md)  
[Finance](finance.md)  
[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

