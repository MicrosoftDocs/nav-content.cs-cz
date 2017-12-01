---
title: "Přeřazení dlouhodobého majetku"
description: "Přeřazení dlouhodobého majetku k převedení na jiné oddělení, rozdělení nebo spojení s jiným dlouhodobým majetkem."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 43b24201037de228faf4f58cc46bd92f796d72e3
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-transfer-split-or-combine-fixed-assets"></a>Návod: Převedení, rozdělení nebo kombinování dlouhodobého majetku
Používejte deník přeřazení dlouhodobého majetku k převedení, rozdělení nebo kombinaci dlouhodobého majetku. Zobrazte nebo vytiskněte výsledky přeřazení dlouhodobého majetku sestavou **Dlouhodobý majetek-úč.hodn.02**.

## <a name="to-transfer-a-fixed-asset-to-a-different-department"></a>Převedení dlouhodobého majetku na jiné středisko
Možná budete potřebovat přenést dlouhodobý majetek na jiné oddělení, např.: umístíte majetek do oddělení výroby, zatímco probíhá výroba a jakmile bude dokončena, můžete ho převést do oddělení správy.  

1. Založení nového dlouhodobého majetku. Zvolit nové středisko v poli **Středisko Kód**.
2. Přiřadit knihu odpisů dlouhodobého majetku k novému dlouhodobému majetku. Další informace naleznete v tématu [Návod: Pořízení DM](fa-how-acquire.md).
3. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Šablony deníku DM** a vyberte související odkaz.
4. Vytvořte přeřazovací deník, kde pole **Číslo DM** obsahuje původní dlouhodobý majetek a pole **Nové číslo DM** obsahuje nový dlouhodobý majetek k přesunu.  
5. Zvolte akci **Přeřadit**.

    Nyní jsou vytvořeny dva řádky ve finančním deníku dlouhodobého majetku, který používá šablonu a listy, které jste specifikovali v okně **Nastavení DM deníku** pro specifikovanou knihu odpisů. Další informace naleznete v tématu [Návod: Nastavení odpisů dlouhodobého majetku](fa-how-setup-depreciation.md).
6. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.    
7. V okně **Finanční deníky dlouhodobého majetku** vyberte akci **Zaúčtovat** k zaúčtování přeřazení, které jste provedli v kroku 4 a 5.

Pokud jste zaúčtovali částku pořízeni za jeden prostředek, můžete použít deník přeřazení dlouhodobého majetku k rozdělení částky pořízení mezi několik prostředků.  

## <a name="to-split-a-fixed-asset-into-three-fixed-assets"></a>Rozdělení dlouhodobého majetku do tří dlouhodobých majetků
Můžete rozdělit jeden dlouhodobý majetek do více dlouhodobých majetků, např. když potřebujete distribuovat dlouhodobý majetek do tří různých oddělení. V případě, že můžete přesunout např.: 25 procent částky pořízení a odpis pro původní dlouhodobý majetek na druhý dlouhodobý majetek a 45 procent na třetí majetek. Zbývajících 30 procent zůstane na původním dlouhodobém majetku.

1. Založení dvou dlouhodobých majetků. Zvolit nové středisko v poli **Středisko Kód**.
2. Přiřadit knihy odpisu dlouhodobého majetku k novému dlouhodobému majetku. Další informace naleznete v tématu [Návod: Pořízení DM](fa-how-acquire.md).
3. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Šablony deníku DM** a vyberte související odkaz.
4. Vytvořte dva řádky deníku přeřazení, jeden pro každý nový dlouhodobý majetek.
5. Na prvním řádku zvolte druhý dlouhodobý majetek v poli **Nové číslo DM** a 25 v poli **Přeřadit % pořízení**.
6. Na druhém řádku, zadejte třetí dlouhodobý majetek v poli **Nové číslo DM** a 40 v poli **Přeřadit % pořízení**.
7. Na obou řádcích vyberte zaškrtávací políčka **Přeřadit pořízení** a **Přeřadit odpis**.   
8. Zvolte akci **Přeřadit**.

    Nyní jsou vytvořeny dva řádky ve finančním deníku dlouhodobého majetku, který používá šablonu a listy, které jste specifikovali v okně **Nastavení DM deníku** pro specifikovanou knihu odpisů. Další informace naleznete v tématu [Návod: Nastavení odpisů dlouhodobého majetku](fa-how-setup-depreciation.md).    
9. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.
10. V okně **Finanční deník DM**, vyberte akci **Zaúčtovat** k zaúčtování přeřazení, které jste provedli v krocích 4 až 8.

## <a name="to-combine-two-fixed-assets-into-one"></a>Kombinace dvou dlouhodobých majetků do jednoho
Můžete kombinovat více dlouhodobých majetků do jednoho dlouhodobého majetku, např. když přesouváte distribuovaný dlouhodobý majetek do jednoho oddělení. Pokud jste zaúčtovali náklady na pořízení a odpisy pro dlouhodobý majetek k přesunu, hodnoty budou kombinovány do jednoho dlouhodobého majetku.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Šablony deníku DM** a vyberte související odkaz.
2. Vytvořte přeřazovací deník, kde pole **Číslo DM** obsahuje dlouhodobý majetek k přesunu/kombinaci a pole **Nové číslo DM** obsahuje dlouhodobý majetek, kterým bude kombinován.
3. Nechejte pole **Přeřadit % pořízení** prázdné k přesunutí/kombinaci všech nákladů na pořízení.    
4. Vyberte zaškrtávací políčka **Přeřadit pořízení** a **Přeřadit odpis**.
5. Na záložce **Akce** zvolte **Přeřadit**.

    Nyní jsou vytvořeny dva řádky ve finančním deníku dlouhodobého majetku, který používá šablonu a listy, které jste specifikovali v okně **Nastavení DM deníku** pro specifikovanou knihu odpisů. Další informace naleznete v tématu [Návod: Nastavení odpisů dlouhodobého majetku](fa-how-setup-depreciation.md).   
6. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.
7. V okně **Finanční deník DM** vyberte akci **Zaúčtovat** k zaúčtování přeřazení, které jste provedli v krocích 2 až 5.

## <a name="to-view-changed-depreciation-book-values-due-to-fixed-asset-reclassification"></a>Zobrazení změněných hodnot knihy odpisů kvůli přeřazení dlouhodobého majetku
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účetní hodnota DM 02** a pak vyberte související odkaz.
2. Vyplňte pole dle potřeby.
3. Vyberte tlačítko **Tisk** nebo **Náhled**.  

## <a name="see-also"></a>Viz také
[Dlouhodobý majetek](fa-manage.md)  
[Nastavení DM](fa-setup.md)  
[Finance](finance.md)  
[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

