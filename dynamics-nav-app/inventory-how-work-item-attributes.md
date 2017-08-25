---
title: "Návod: Práce s atributy zboží"
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
ms.openlocfilehash: eaf539f1d4d00c2cd5679f39f29a3428e33ee1fd
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-item-attributes"></a>Návod: Práce s atributy zboží
Když se zákazníci dotazují na položku, ať už v korespondenci nebo v integrovaném internetovém obchodu, mohou se zeptat nebo vyhledat podle charakteristik, jako je výška a modelový rok. Chcete-li poskytnout tuto službu zákazníkům, můžete přiřadit hodnoty atributů zboží různého typu k vašemu zboží, které pak lze použít při hledání zboží.

Atributy zboží můžete také přiřadit kategoriím zboží, které se pak použijí na zboží, které používají kategorie zboží. Další informace naleznete v tématu [Návod: Kategorizace zboží](inventory-how-categorize-items.md).

## <a name="to-create-item-attributes"></a>Vytvoření atributů zboží
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Atributy zboží** a zvolte související odkaz.
2. V okně **Atributy zboží** vyberte akci **Nové**.
3. V okně **Atributy zboží** vyplňte pole podle potřeby. Vybrat pole k zobrazení krátkého popisu nebo odkazu pro více informací.

**Poznámka**: Pokud zvolíte **Možnosti** v poli **Typ**, pak můžete zvolit akci **Hodnoty atributů zboží** k vytvoření hodnot pro atributy zboží. Další informace naleznete v tématu "K vytvoření hodnot pro atributy zboží typu Volba".  

## <a name="to-create-values-for-item-attributes-of-type-option"></a>Vytvoření hodnoty pro atributy zboží typu Volba
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Atributy zboží** a zvolte související odkaz.
2. V okně **Atributy zboží**, vyberte atribut zboží typu Volba, pro který chcete vytvořit hodnoty a pak zvolte akci **Hodnoty atributů zboží**.
3. V okně **hodnoty atributů zboží** vyplňte pole podle potřeby. Vybrat pole k zobrazení krátkého popisu nebo odkazu pro více informací.

## <a name="to-assign-item-attributes-to-items"></a>Přiřazení atributů zboží ke zboží
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zboží** a zvolte související odkaz.
2. V okně **Zboží** vyberte zboží, ke kterému chcete přiřadit atributy zboží a potom vyberte akci **Atributy**.
3. V okně **Hodnoty atributů zboží** vyberte akci **Nové**.
4. Zvolte tlačítko AssistEdit v poli **Atribut** a vyberte existující atribut zboží. Nebo zvolte akci **Nové**, chcete-li nejprve vytvořit nový atribut zboží, jak je vysvětleno v sekci "Vytvořit atributy zboží".
5. Do pole **Hodnota** zadejte hodnotu atributu zboží, například "2010" pro atribut modelového roku.
6. U atributů zboží typu Volba vyberte tlačítko AssistEdit v poli **Hodnota** a vyberte hodnotu atributu zboží. Nebo zvolte akci **Nové**, chcete-li nejprve vytvořit novou hodnotu atributu zboží, jak je vysvětleno v sekci "Vytvořit hodnoty atributů zboží typu Volba".
7. Opakujte kroky 4 až 6 pro všechny atributy zboží, které chcete přiřadit ke zboží.

## <a name="to-assign-item-attributes-to-item-categories"></a>Přiřadit atributy zboží ke kategoriím zboží.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Kategorie zboží** a zvolte související odkaz.
2. V okně **Kategorie zboží** vyberte kategorii zboží, ke kterým chcete přiřadit atributy zboží, a potom vyberte akci **Upravit** 
3. V okně **Karta kategorií zboží** na záložce s náhledem **Atributy** zvolte akci **Nové**.
4. Zvolte tlačítko AssistEdit v poli **Atribut** a vyberte existující atribut zboží. Nebo zvolte akci **Nové**, chcete-li nejprve vytvořit nový atribut zboží, jak je vysvětleno v sekci "Vytvořit atributy zboží".
5. V poli **Výchozí hodnota** vyberte tlačítko AssistEdit a vyberte hodnotu atributu zboží.
6. Opakujte kroky 4 a 5 pro všechny atributy zboží, které chcete přiřadit ke kategorii zboží.

**Poznámka**: Atributy zboží pro nadřazené kategorie zboží budou zděděny do podřízených kategorií zboží. To je označeno políčkem **Zděděno z** na záložce s náhledem **Atributy**. Další informace naleznete v tématu [Návod: Kategorizace zboží](inventory-how-categorize-items.md).

## <a name="to-filter-by-item-attributes"></a>Filtrování podle atributů zboží
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zboží** a zvolte související odkaz.
2. V okně **Zboží** vyberte akci **Filtrovat podle atributů**.
3. V okně **Filtrovat zboží podle atributů** vyberte tlačítko AssistEdit v poli **Atribut** a vyberte atribut zboží.
4. V poli **Hodnota** vyberte tlačítko AssistEdit a vyberte hodnotu atributu pro filtrování zboží.

    **Poznámka**: Hodnoty můžete vybrat pouze přímo pro atributy zboží, které mají fixní hodnoty, například Barva. Pro atributy položek, které mají proměnné hodnoty, jako je šířka, musíte zadat hodnotu atributu zboží výběrem podmínky nejprve. Viz krok 5.
5. V poli **Hodnota** pro atribut proměnné zboží zvolte tlačítko AssistEdit.
6. V okně **Určit hodnotu filtru** v poli **Podmínka** vyberte rozbalovací šipku a vyberte podmínku.
7. Do pole **Hodnota** zadejte hodnotu atributu pro filtrování položek.

    **Příklad**: Chcete-li filtrovat zboží, u kterého popis materiálu začíná "modrá", vyplňte následující pole: Pole **Atribut**: Popis materiálu, pole **Podmínka**: Začíná s, pole **Hodnota**: modrá.
8. Vyberte tlačítko **OK**.   

Zboží v okně **Zboží** je filtrováno podle specifikované hodnoty atributu zboží.

## <a name="see-also"></a>Viz také
[Návod: Kategorizace zboží](inventory-how-categorize-items.md)    
[Návod: Registrace nových produktů](inventory-how-register-new-products.md)  
[Správa zásob](inventory-manage-inventory.md)  
[Práce s Dynamics NAV](ui-work-product.md)

