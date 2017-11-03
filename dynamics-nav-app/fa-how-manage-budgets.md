---
title: "Správa rozpočtů DM"
description: "Nastavte informace o budoucích investicích, prodejích a odpisování dlouhodobého majetku, abyste mohli připravit rozpočty a prognózy."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: forecast
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 52b5e72d4d0a3e2c914894c58c10f44cb42d9c9d
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-manage-budgets-for-fixed-assets"></a>Návod: Správa rozpočtů pro dlouhodobý majetek
Můžete nastavit rozpočty pro dlouhodobý majetek. Můžete například zahrnout očekávané akvizice a prodeje do přehledů.  

Chcete-li připravit plánovaný výkaz zisku a ztráty, rozpočtovou rozvahu a hotovostní rozpočet, potřebujete informace o budoucích investicích, prodeji a odpisování DM. Tyto informace můžete získat ze zprávy **Dlouhodobý majetek - očekávaná hodnota**. Než vytisknete tuto sestavu, musíte připravit rozpočet.  

## <a name="to-budget-the-acquisition-cost-of-a-fixed-asset"></a>Rozpočet na pořizovací cenu DM
Chcete-li připravit rozpočet, musíte v budoucnu nastavit karty DM, který chcete koupit. Rozpočet DM je stanoven jako běžný dlouhodobý majetek, ale musí být nastaven tak, aby se nezaúčtoval do hlavní knihy.

Když uveřejníte pořizovací cenu, zadejte číslo rozpočtu DM v poli **Číslo rozpočtu DM**. Zaúčtuje se pořizovací cena s opačným znaménkem pro rozpočet majetku. To znamená, že celková pořizovací cena rozpočtu majetku je rozdílem mezi rozpočtovanými a skutečnými pořizovacími náklady.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Zvolte akci **Nový** pro vytvoření nové karty DM pro rozpočet DM.
3. Zaškrtněte políčko **Rozpočtový majetek**, abyste zabránili zaúčtování do hlavní knihy.
4. Vyplňte zbývající pole, přiřaďte odpisovou knihu a poté zaúčtujte první pořizovací cenu s rozpočtem DM zadaným v poli **Číslo rozpočtu DM** na řádku deníku. Další informace naleznete v tématu [Návod: Pořízení DM](fa-how-acquire.md).

## <a name="to-budget-the-disposal-of-a-fixed-asset"></a>Rozpočet na vyřazení DM
Pokud máte v úmyslu prodat majetek během rozpočtového období, můžete zadat informace o prodejní ceně a dni prodeje.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, který chcete vyřadit a pak vyberte akci **Knihy odpisů**.
3. V okně **Knihy odpisů DM** vyplňte pole **Plánované datum vyřazení** a **Plánovaný výsledek vyřazení**. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-view-projected-disposal-values"></a>Zobrazení očekávané hodnoty vyřazení
Chcete-li zobrazit hodnoty předpokládaných vyřazení a vypočítat zisk a ztráty, můžete použít sestavu **Očekávaná hodnota DM**.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Očekávaná hodnota DM** a pak vyberte související odkaz.
2. Vyplňte pole dle potřeby.
3. Vyberte tlačítko **Tisk** nebo **Náhled**.

## <a name="to-budget-depreciation"></a>Odpis rozpočtu
Pro výpočet budoucího odpisu můžete použít sestavu **Dlouhodobý majetek - očekávaná hodnota**. Zpráva uvádí účetní hodnotu a akumulované odpisy na začátku vybraného období, změny v daném období a účetní hodnotu a akumulované odpisy na konci vybraného období.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Očekávaná hodnota DM** a pak vyberte související odkaz.
2. Vyplňte pole dle potřeby.
3. Chcete-li zobrazit souhrnné hodnoty pro všechen majetek, zrušte zaškrtnutí políčka **Tisk dle DM**.
4. Ponechte záložku s náhledem **Dlouhodobý majetek** prázdnou, aby byl zahrnut všechen majetek. Do pole **Rozpočtový majetek** zadejte **Ne**, chcete-li vyloučit rozpočtovaný majetek nebo **Ano**, abyste viděli pouze rozpočtovaný majetek.
5. Vyberte tlačítko **Tisk** nebo **Náhled**.

## <a name="see-also"></a>Viz také
[Dlouhodobý majetek](fa-manage.md)  
[Nastavení DM](fa-setup.md)  
[Finance](finance.md)  
[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

