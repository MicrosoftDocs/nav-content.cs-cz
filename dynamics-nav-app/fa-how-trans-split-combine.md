---
title: "Návody: Přenést, rozdělit nebo kombinovat dlouhodobý majetek"
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
ms.openlocfilehash: 96bea0054d2ea3cdabfa179d8f4c78cf90d7777c
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-transfer-split-or-combine-fixed-assets"></a>Návody: Přenést, rozdělit nebo kombinovat dlouhodobý majetek
Používáte deník přeřazení dlouhodobého majetku k přenosu, rozdělení nebo kombinaci dlouhodobého majetku. Zobrazíte nebo vytisknete výsledky přeřazení dlouhodobého majetku se sestavou **Dlouhodobý majetek-úč.hodn.02**.

## <a name="to-transfer-a-fixed-asset-to-a-different-department"></a>K přenosu dlouhodobého majetku na jiné oddělení  
Možná potřebujete přenést dlouhodobý majetekna jiné oddělení, když např. umístíte majetek do střediska dílen, zatímco probíhá vytváření a pak se přesouvá do střediska správy, jakmile je dokončeno.  

1. Nastavit nový dlouhodobý majetek. Zvolit nové oddělení v poli **Kód oddělení**.
2. Přiřadit knihu odpisů dlouhodobého majetku k novému dlouhodobému majetku. Pro další informace, viz [Návody: Načíst dlouhodobý majetek](fa-how-acquire.md).
3. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zvolte **Přeřazení DM. Deníky** a vyberte související odkaz.
4. Vytvořit deník přeřazení, kde **Číslo DM** pole obsahuje původní dlouhodobý majetek a **Nové číslo DM** pole obsahuje nový dlouhodobý majetek k přesunu.  
5. Zvolte akci **Přeřaď**.

    Dva řádky jsou nyní vytvořeny ve finančním deníku dlouhodobého majetku, který používá šablonu a dávku, kterou jste specifikovali v okně **Nastavení DM deníku** pro specifikovanou knihu odpisů. Pro další informace, viz [Návody: Nastavit odpisy dlouhodobého majetku](fa-how-setup-depreciation.md).
6. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zvolte **Finanční deníky DM **, a pak zvolte související link.    
7. V okně **Finanční deníky dlouhodobého majetku** vybrte akci **Zaúčtovat ** k zaúčtování přeřazení, které jste provedli v kroku 4 a 5.

Pokud jste zaúčtovali částku pořízeni za jeden prostředek, můžete použít deník přeřazení dlouhodobého majetku k rozdělení částky pořízení mezi několik přostředků.  

## <a name="to-split-a-fixed-asset-into-three-fixed-assets"></a>Rozdělit dlouhodobý majetek do tří dlouhodobých majetků.
Můžete rozdělit jeden dlouhodobý majetekdo více dlouhodobých majetků, např. když potřebujete distribuovat dlouhodobý majetek do tří různých oddělení. V případě, že můžete přesunout např. 25 procent částky pořízení a odpis pro původní dlouhodobý majetek na druhý dlouhodobý majetek a 45 procent na třetí majetek. Zbývajících 30 procent zůstane na původním dlouhodobém majetku.

1. Nastavit dva nové dlouhodobé majetky. Zvolit nové oddělení v poli **Kód oddělení**.
2. Přiřadit knihy odpisu dlouhodobého majetku k novému dlouhodobému majetku. Pro další informace, viz [Návody: Načíst dlouhodobý majetek](fa-how-acquire.md).
3. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zvolte **Přeřazení DM. Deníky** a vyberte související odkaz.
4. Vytvořit dva řádky deníku přeřazení, jeden pro každý nový dlouhodobý majetek.
5. Na prvním řádku, zvolte druhý dlouhodobý majetek v poli **Nové číslo DM** Pole a 25 v **Přeřadit pole % nákladů**.
6. Na druhém řádku, zadejte třetí dlouhodobý majetek v poli **Nové číslo DM** Pole a 40 v **Přeřadit pole % nákladů**.
7. Na obou řádcích vyberte zaškrtávací políčka **Přeřadit náklady pořízení** a **Přeřadit odpis**.   
8. Zvolte akci **Přeřaď**.

    Dva řádky jsou nyní vytvořeny ve finančním deníku dlouhodobého majetku, který používá šablonu a dávku, kterou jste specifikovali v okně **Nastavení DM deníku** pro specifikovanou knihu odpisů. Pro další informace, viz [Návody: Nastavit odpisy dlouhodobého majetku](fa-how-setup-depreciation.md).    
9. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zvolte **Finanční deníky DM **, a pak zvolte související link.
10. V okně **Finanční deník DM**, vyberte akci **Zaúčtovat** k zaúčtování přeřazení, které jste provedli v krocích 4 až 8.

## <a name="to-combine-two-fixed-assets-into-one"></a>Kombinovat dva dlouhodobé majetky do jednoho.
Můžete kombinovat více dlouhodobých majetků do jednoho dlouhodobého majetku, např. když přesouváte distribuovaný dlouhodobý majetek do jednoho oddělení. Pokud jste zaúčtovali náklady na pořízení a odpisy pro dlouhodobý majetek k přesunu, hodnoty budou kombinovány do jednoho dlouhodobého majetku.

1. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zvolte **Přeřazení DM. Deníky** a vyberte související odkaz.
2. Vytvořit deník přeřazení, kde **Číslo DM** pole obsahuje dlouhodobý majetek k přesunu/kombinaci a **Nové číslo DM** pole obsahuje dlouhodobý majetek, se kterým bude kombinován.
3. Nechat **Přeřadit Pole % nákladů** prázdné k přesunutí/kombinaci všech Nákladů na pořízení    
4. Vybrat zaškrtávací políčka **Přeřadit náklady pořízení** a **Přeřadit odpis**.
5. Na záložce **Actions** zvolte **Přeřadit**.

    Dva řádky jsou nyní vytvořeny ve finančním deníku dlouhodobého majetku, který používá šablonu a dávku, kterou jste specifikovali v okně **Nastavení DM deníku** pro specifikovanou knihu odpisů. Pro další informace, viz [Návody: Nastavit odpisy dlouhodobého majetku](fa-how-setup-depreciation.md).   
6. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Finanční deníky DM**, a pak vyberte související odkaz.
7. V okně **Finanční deník DM**, vyberte akci **Zaúčtovat** k zaúčtování přeřazení, které jste provedli v krocích 2 až 5.

## <a name="to-view-changed-depreciation-book-values-due-to-fixed-asset-reclassification"></a>K zobrazení změněných hodnot knihy odpisů kvůli přeřazení dlouhodobého majetku  
1. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Finanční deníky DM**, a pak vyberte související odkaz.
2. Vyplňte pole podle potřeby.
3. Vyberte tlačítko **Tisk** nebo **Náhled**.  

## <a name="see-also"></a>Viz také
[Spravovat dlouhodobý majetek](fa-manage.md)  
[Nastavit dlouhodobého majetku](fa-setup.md)  
[Finance](finance-setup.md)  
[Vítejte v Dynamics NAV](across-get-started.md)
