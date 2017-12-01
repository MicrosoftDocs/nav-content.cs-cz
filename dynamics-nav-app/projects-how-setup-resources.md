---
title: "Nastavení nákladů zdrojů, cen a kapacity"
description: "Chcete-li použít zdroje a usnadnit správu projektů, specifikujete náklady a ceny jednotlivých zdrojů nebo skupin zdrojů a nastavte kapacitu zdrojů."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project management, capacity, staff
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: e1c2f8f41bb493c4ce2efa2156631c6d9d273439
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-resources"></a>Návod: Nastavení zdrojů
Chcete-li správně spravovat aktivity zdrojů, musíte nastavit zdroje a související náklady a ceny. Ceny související s projektem, slevy a nákladová pravidla jsou nastaveny na kartě projektu. Můžete specifikovat náklady a ceny jednotlivých zdrojů, skupin zdrojů nebo všech dostupných zdrojů společnosti.

Když jsou zdroje využívány nebo prodávány v projektu, ceny a náklady spojené s nimi jsou získány z informací, které jste nastavili.

Určujete výchozí částku za hodinu, kdy je zdroj vytvořen. Například pokud používáte konkrétní stroj na projektu po dobu pěti hodin, bude projekt vypočítán na základě částky za hodinu.

## <a name="to-set-up-a-resource"></a>Nastavení zdroje
Vytvořte kartu pro každý zdroj, který chcete použít v projektech.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zdroje** a vyberte související odkaz.
2. Vyberte akci **Nový**.
3. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

## <a name="to-set-up-a-resource-group"></a>Nastavení skupiny zdrojů
Můžete kombinovat několik zdrojů v jedné skupině zdrojů. Všechny kapacity a rozpočty skupin zdrojů jsou shromažďovány z jednotlivých zdrojů. Je také možné zadávat kapacity pro skupiny zdrojů buď nezávisle na nahromaděných hodnotách nebo vedle nich.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Skupiny zdrojů** a vyberte související odkaz.
2. Vyberte akci **Nový**.
3. Vyplňte pole dle potřeby.

## <a name="to-set-capacity-for-a-resource"></a>Nastavení kapacity pro prostředek
Chcete-li vypočítat, kolik času může zdroj vynaložit na projekty, musí být jejich kapacita nejprve nastavena jako dostupný čas za období v pracovním kalendáři. Toto nastavení se používá při vyplňování řádků plánování projektu, které obsahují zdroj. Další informace naleznete v tématu [Návod: Tvorba projektů.](projects-how-create-jobs.md).

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zdroje** a vyberte související odkaz.
2. Otevřete příslušnou kartu zdroje a potom vyberte akci **Kapacita zdroje**.
3. V okně **Kapacita zdroje** v poli **Zobrazit po** určete délku období například **Den**, který je zobrazen ve sloupcích na záložce s náhledem **Matice kapacity zdrojů**.
4. Pro každý prostředek na řádku určete pro každé období ve sloupcích počet hodin, kdy je prostředek k dispozici.
5. Chcete-li podrobně popsat týdenní kapacitu zdroje v počátečním a konečném datu, zvolte akci **Nastavit kapacitu**.
6. V okně **Nastavení kapacit zdrojů** vyplňte pole podle potřeby.
7. Zvolte akci **Aktualizovat kapacitu**. Okno **Kapacita zdroje** se aktualizuje o zadanou kapacitu.
8. Zavřete okno.

## <a name="to-set-up-alternate-resource-costs"></a>Nastavení alternativních nákladů na zdroje
Kromě nákladů uvedených na kartě zdroje můžete nastavit alternativní náklady pro každý zdroj. Například pokud zaplatíte zaměstnanci vyšší hodinovou sazbu za přesčasy, můžete nastavit náklady na zdroje za přesčasovou sazbu. Náhradní cena, kterou nastavíte pro zdroj, přepíše náklady na kartě zdroje při použití zdroje v deníku zdrojů.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zdroje** a vyberte související odkaz.  
2. Vyberte zdroj, pro který chcete nastavit jeden nebo více alternativních nákladů a pak vyberte akci **Náklady**.  
3. V okně **Náklady zdrojů** vyplňte pole podle potřeby.  
4. Opakujte krok 3 pro každou alternativní cenu zdroje, kterou chcete nastavit.

**Poznámka**. Chcete-li nastavit náklady na zdroje, které se budou vztahovat na všechny zdroje a skupiny zdrojů, otevřete okno **Náklady zdroje** a vyplňte pole.

## <a name="to-set-up-alternate-resource-prices"></a>Nastavení alternativních cen zdrojů
Kromě ceny uvedené na kartě zdrojů můžete nastavit alternativní ceny pro každý zdroj. Tyto alternativní ceny mohou být podmíněné. Mohou záviset na tom, zda je zdroj používán s určitým projektem nebo typem práce.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zdroje** a vyberte související odkaz.
2. Vyberte zdroj, pro který chcete nastavit jednu nebo více alternativních cena a pak vyberte akci **Ceny**.
3. V okně **Ceny zdrojů** vyplňte pole podle potřeby.
4. Opakujte krok 3 pro každou alternativní cenu zdroje, kterou chcete nastavit.

## <a name="see-also"></a>Viz také
[Nastavení Správy vztahů](projects-setup-projects.md)  
[Řízení projektů](projects-manage-projects.md)  
[Finance](finance.md)  
[Nákup](purchasing-manage-purchasing.md)         
[Prodej](sales-manage-sales.md)      
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

