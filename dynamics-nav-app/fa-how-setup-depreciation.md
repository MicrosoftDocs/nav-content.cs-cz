---
title: "Návod: Nastavení odpisů DM"
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
ms.openlocfilehash: 7efc50c673514498de0caa5b3a2dc4b32d4f7f5d
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-fixed-asset-depreciation"></a>Návod: Nastavení odpisů DM
 Můžete použít různé metody odpisování pro sestavení finančního výkazu a daně z příjmu. Mnoho velkých společností používá přímé odpisy v jejich finančních výkazech, protože toto obecně umožňuje vykazovat vyšší výdělky. Pro účely daně z příjmů však mnoho podniků používá metodu urychleného odpisování. Další informace naleznete v [Metody odpisování](fa-depreciation-methods.md).

 Když jste vytvořili příslušné odpisové knihy, musíte každému dlouhodobému majetku přiřadit jeden nebo více odpisových knih. Odpisová kniha, která je přidělena k dlouhodobému majetku, se označuje jako odpisová kniha DM. Okno pro přidělené odpisové knihy se jmenuje **Odpisové knihy DM**.

## <a name="to-create-a-depreciation-book"></a>Vytvoření odpisové knihy  
V odpisové knize DM specifikujete, jak je odpisován dlouhodobý majetek. Chcete-li přizpůsobit různé metody odpisování, můžete nastavit více odpisových knih.  
1.  V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Odpisové knihy** a pak vyberte související odkaz.
2. V okně **Seznam odpisových knih** zvolte akci **Nový**.
3. V okně **Karta odpisové knihy** vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.

    **Poznámka**: Můžete zaznamenat transakce DM v okně **Finanční deník DM** nebo v okně **Deník DM** v závislosti na tom, zda jsou transakce určeny pro finanční sestavy nebo pro interní správu. Postupujte podle následujícího kroku a definujte, který typ deníku se používá pro různé činnosti DM ve výchozím nastavení.
4. Na kartě záložky s náhledem **Integrace** vyberte zaškrtávací políčko pro každou aktivitu DM, jejíž transakce chcete zaúčtovat pomocí okna **Finanční deník DM**.
5. Opakujte kroky 2 až 4 pro každou metodu odpisování nebo metodu zaúčtování, kterou chcete přiřadit k dlouhodobému majetku jako odpisovou knihu.

## <a name="to-assign-a-depreciation-book-to-a-fixed-asset"></a>Přiřazení odpisové knihy k dlouhodobému majetku  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, pro který chcete nastavit odpisovou knihu DM.
3. V záložce s náhledem **Kniha odpisů** vyplňte pole podle potřeby.
4. Pokud potřebujete přiřadit k dlouhodobému majetku více než jednu knihu odpisů, zvolte akci **Přidat více knih odpisů**.
5. Případně vyberte akci **Odpisové knihy** k určení jedné nebo více odpisových knih DM.

**Poznámka**: Pokud používáte ruční metodu odpisů, je nutné ručně zadat odpis DM ve finančním deníku. Funkce **Výpočet odpisů** vynechává dlouhodobý majetek, který používá metodu ručního odpisování. Tuto metodu můžete použít pro majetek, který nepodléhá odpisům například pozemky.

## <a name="to-assign-a-depreciation-book-to-multiple-fixed-assets-with-a-batch-job"></a>Přidělení odpisové knihy do více dlouhodobých aktiv s dávkovou úlohou
Chcete-li přiřadit odpisovou knihu k několika dlouhodobému majetku, můžete použít dávkovou úlohu **Vytvořit odpisové knihy DM**, abyste v Dynamics NAV automaticky vytvořili potřebné odpisové knihy DM.  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, u kterého chcete přiřadit odpisovou knihu a pak vyberte akci **Upravit**.
3. Na kartě **Karta odpisové knihy** vyberte akci **Vytvořit odpisové knihy DM**.
4. V okně **Vytvořit odpisovou knihu DM** vyplňte pole **Odpisová kniha**.
5. Zvolte pole **Kopírovat z čísla DM**  a poté vyberte číslo DM, které chcete použít jako základ pro vytváření nových odpisových knih DM.

    Pokud vyplníte toto pole, odpisové pole v nových odpisových knihách DM bude obsahovat stejné informace jako odpovídající pole v odpisové knize DM, z které jste kopírovali. Ponechejte pole prázdné, chcete-li vytvořit nové odpisové knihy DM s prázdnými poli odpisů.  
6. Na záložce s náhledem **Dlouhodobý majetek** můžete nastavit filtr pro výběr majetku, který chcete vytvořit pro odpisové knihy DM.
7. Zvolte tlačítko **OK**.

## <a name="to-set-up-depreciation-posting-types"></a>Nastavení typů odpisů zaúčtování  
Pro každou odpisovou knihu musíte nastavit, jak chcete v Dynamics NAV zpracovávat různé typy zaúčtování. Například, zda by zaúčtování mělo být MD nebo Dal a zda by měl být typ zaúčtování zahrnut do odpisovatelného základu.  
1.  V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Odpisové knihy** a pak vyberte související odkaz.  
2. Vyberte odpisovou knihu, kterou chcete nastavit a poté vyberte akci **Nastavení typu zaúčtování DM**.
3. V okně **Nastavení typu zaúčtování DM** vyplňte pole podle potřeby.

**POZNÁMKA**: Nemůžete vložit nebo odstranit řádky v okně **Nastavení typu zaúčtování DM**. Můžete upravit pouze existující řádky.

Doporučujeme, abyste nezměnili nastavení odpisových knih pro položky, které již byly zaúčtovány. Změny nebudou mít vliv na položky, které již byly zaúčtovány, což by způsobilo statistiky odpisových knih zavádějící.

## <a name="to-set-up-default-templates-and-batches-for-fixed-asset-depreciation"></a>Nastavení výchozích šablon a dávek pro odpisy DM  
Pro každou odpisovou knihu definujete výchozí nastavení šablon a dávek. Tyto výchozí hodnoty používejte k:
- Duplikaci řádků z jednoho deníku do druhého.
- Vytvoření řádků deníku pomocí dávkových úloh **Výpočet odpisů** nebo **Indexovat DM**.
- Duplikaci pořizovací ceny v deníku pojištění.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Odpisové knihy** a pak vyberte související odkaz.
2. Vyberte odpisovou knihu, pro kterou chcete definovat výchozí deník a poté vyberte akci **Nastavení deníku DM**.
3. Chcete-li mít výchozí nastavení pro každého uživatele, vyberte pole **ID uživatele** z okna **Uživatelé**.
4. V ostatních polích vyberte šablonu deníku nebo dávku deníku, která musí být použita ve výchozím nastavení.

## <a name="see-also"></a>Viz také
[Nastavení DM](fa-setup.md)  
[Správa DM](fa-manage.md)  
[Finance](finance-setup.md)  
[Vítejte v Dynamics NAV](across-get-started.md)

