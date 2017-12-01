---
title: "Vytvoření a správa neskladovaného zboží"
description: "Popisuje, jak obchodovat se zbožím, které není v zásobách nebo se zbožím, které není ve vašich zásobách udržováno."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: non-inventoriable
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: dd1497d0727935d4954f826eceb303761850dada
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-nonstock-items"></a>Návod: Práce s neskladovaným zbožím
Můžete nabídnout svým zákazníkům určité zboží pro jejich pohodlí, které nechcete udržovat v zásobách, dokud je nezačnete prodávat. Chcete-li toto zboží ukládat do zásob, můžete ho převést na běžné karty zboží dvěma způsoby.

* Z karty neskladovaného zboží vytvořte novou kartu zboží založenou na šabloně.
* Z řádku prodejní objednávky typu **Zboží** s prázdným polem **Číslo** vyberte neskladované zboží. Karta zboží je automaticky vytvořena pro neskladované zboží.

> [!NOTE]  
>   Nemůžete vybrat neskladované zboží z okna **Prodejní faktura**. Můžete vybrat neskladované zboží z okna **Prodejní nabídka**, ale neskladované zboží nebude převedeno na normální, pokud použijete funkci **Vytvořit objednávku**.

Neskladové zboží má typicky číslo zboží dodavatele, který jej nabízí. Chcete-li povolit konverzi karty neskladovaného zboží na normální kartu zboží, musíte nejprve nastavit, jak bude převedeno číslování položek dodavatele na vaše číslování položek.   

## <a name="to-create-a-nonstock-item"></a>Vytvoření neskladovaného zboží
Karty neskladovaného zboží mají mnohem méně informací než karty normálního zboží, protože je používáte pouze na nabídkách a jinými způsoby. Z tohoto důvodu je třeba je převést na normální kartu, než budete moci za ně zaúčtovat prodejní transakce.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Neskladované zboží** a pak vyberte související odkaz.
2. Vyberte akci **Nový**.
3. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-how-nonstock-item-numbers-are-converted-to-your-own-numbering"></a>Nastavení převodu čísel neskladovaných položek na vlastní číslování
Chcete-li povolit konverzi karty neskladovaného zboží na kartu normálního zboží, musíte nejprve nastavit, jak bude číslování zboží prodejce převedeno na váš vlastní formát čísla zboží.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení neskladovaného zboží** a pak vyberte související odkaz.
2. Vyplňte pole dle potřeby.

## <a name="to-convert-a-nonstock-item-to-a-normal-item"></a>Převod neskladovaného zboží na normální
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Neskladované zboží** a pak vyberte související odkaz.
2. Otevřete kartu pro neskladované zboží, které chcete převést na normální.
3. V okně **Karta neskladovaného zboží** vyberte akci **Vytvořit zboží**.

Nová karta zboží předvyplněná informacemi ze šablon neskladovaného zboží a odpovídající šablona zboží je vytvořena. Můžete vyplnit nebo upravit pole na nové kartě zboží podle potřeby. Další informace naleznete v tématu [Návod: Registrace nového zboží](inventory-how-register-new-items.md).

## <a name="to-sell-a-nonstock-item-and-convert-it-to-a-normal-item"></a>Prodej neskladovaného zboží a převod na normální zboží
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní objednávky** a pak vyberte související odkaz.
2. Vyberte akci **Nový**. Vyplňte pole na záložce s náhledem **Obecné** jako u každé prodejní objednávky. Další informace naleznete v tématu [Návod: Prodávání produktů](sales-how-sell-products.md).
3. Na novém prodejním řádku v poli **Typ**, vyberte **Zboží** ale nechte pole **Číslo** prázdné .
4. Vyberte akci **Řádek** a pak zvolte akci **Vybrat neskladované zboží**.

    Neskladované zboží je převedeno na normální zboží. Nová karta zboží předvyplněná informacemi ze šablon neskladovaného zboží a odpovídající šablona zboží je vytvořena.
5. V okně **Neskladované zboží** vyberte neskladované zboží, které chcete prodat a potom vyberte tlačítko **OK**.
6. Po dokončení prodejní objednávky zvolte akci **Účtovat**.

Můžete vyplnit nebo upravit pole na nové kartě zboží podle potřeby. Další informace naleznete v tématu [Návod: Registrace nového zboží](inventory-how-register-new-items.md).

> [!NOTE]  
>   Záznam křížového odkazu zboží je automaticky vytvořen pro dodavatele zboží mezi číslem zboží dodavatele a novým číslem zboží.

## <a name="see-also"></a>Viz také
[Návod: Registrace nového zboží](inventory-how-register-new-items.md)  
[Návod: Vytvořit speciální objednávku](sales-how-to-create-special-orders.md)|  
[Sklady](inventory-manage-inventory.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

