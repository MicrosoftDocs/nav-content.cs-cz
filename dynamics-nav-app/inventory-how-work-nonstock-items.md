---
title: "Návod: Práce s neskladovaným zbožím"
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 2b49d95904732dcf091fd060a96006fdcb477ec1
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# Návod: Práce s neskladovaným zbožím
Můžete nabídnout svým zákazníkům určité zboží pro jejich pohodlí, které nechcete udržovat v zásobách, dokud je nezačnete prodávat. Chcete-li toto zboží ukládat do zásob, můžete ho převést na běžné karty zboží dvěma způsoby.

- Z karty neskladovaného zboží vytvořte novou kartu zboží založenou na šabloně.
- Z řádku prodejní objednávky s prázdným polem **Zboží** vyberte neskladované. Při zaúčtování prodeje se automaticky vytvoří karta zboží pro neskladované zboží.

**Poznámka**: Nemůžete vybrat neskladované zboží z okna **Prodejní faktura**. Můžete vybrat neskladované zboží z okna **Prodejní nabídka**, ale neskladované zboží nebude převedeno na normální, pokud použijete funkci **Objednat**.

Neskladové zboží má typicky číslo zboží dodavatele, který jej nabízí. Chcete-li povolit konverzi karty neskladovaného zboží na normální kartu zboží, musíte nejprve nastavit, jak bude převedeno číslování položek dodavatele na vaše číslování položek.   

## Vytvoření neskladované zboží
Karty neskladovaného zboží mají mnohem méně informací než karty normálního zboží, protože je používáte pouze na nabídkách a jinými způsoby. Z tohoto důvodu je třeba je převést na normální kartu, než budete moci za ně zaúčtovat prodejní transakce.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Neskladované zboží** a zvolte související odkaz.
2. Vyberte akci **Nové**.
2. Vyplňte pole podle potřeby. Vybrat pole k zobrazení krátkého popisu nebo odkazu pro více informací.

## Nastavení převodu čísel neskladovaných položek na vlastní číslování  
Chcete-li povolit konverzi karty neskladovaného zboží na kartu normálního zboží, musíte nejprve nastavit, jak bude číslování zboží prodejce převedeno na váš vlastní formát čísla zboží.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu** instalace, zadejte **Nastavení neskladovaného zboží** a zvolte související odkaz.
2. Vyplňte pole podle potřeby.

## Převod neskladovaného zboží na normální
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Neskladované zboží** a zvolte související odkaz.
2. Otevřete kartu pro neskladované zboží, které chcete převést na normální.
3. V okně **Karta neskladovaného zboží** vyberte akci **Vytvořit zboží**.

Nová karta zboží předvyplněná informacemi ze šablon neskladované zboží a odpovídající šablona zboží je vytvořena. Můžete vyplnit nebo upravit pole na nové kartě zboží podle potřeby. Další informace naleznete v tématu [Návod: Zaregistrovat nové produkty](inventory-how-register-new-products.md).

## Prodej neskladovaného zboží a převod na normální zboží
1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Prodejní objednávky** a pak vyberte související odkaz.
2. Vyberte akci **Nové**. Vyplňte pole na záložce s náhledem **Obecné** jako u každé prodejní objednávky.
3. Na novém prodejním řádku ponechte políčko **Zboží** prázdné, zvolte **Řádek**, **Funkce** a poté **Neskladované zboží**.

    Neskladované zboží je převedeno na normální zboží. Nová karta zboží předvyplněná informacemi ze šablony neskladované zboží a odpovídající šablona zboží je vytvořena.
4. V okně **Neskladované zboží** vyberte neskladované zboží, které chcete prodat a potom vyberte tlačítko **OK**.
5. Po dokončení prodejní objednávky zvolte akci **Zaúčtovat**.

Můžete vyplnit nebo upravit pole na nové kartě zboží podle potřeby. Další informace naleznete v tématu s[Návod: Zaregistrovat nové produkty](inventory-how-register-new-products.md).

**Poznámka**: Záznam křížového odkazu zboží je automaticky vytvořen pro dodavatele zboží mezi číslem zboží dodavatele a novým číslem zboží.

## Viz také
[Návod: Registrace nových produktů](inventory-how-register-new-products.md)  
[Správa zásob](inventory-manage-inventory.md)  
[Práce s Dynamics NAV](ui-work-product.md)

