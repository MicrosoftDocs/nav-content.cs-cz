---
title: "Návod: Nastavení zdrojů"
author: SorenGP
ms.custom: na
ms.date: 12/14/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 72f5304e6a69a736c9df2cbb9ca64c5f3c5261a2
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-resources"></a>Návod: Nastavení zdrojů
Chcete-li správně spravovat aktivity zdrojů, musíte nastavit zdroje a související náklady a ceny. Ceny související s projektem, slevy a nákladová pravidla jsou nastaveny na kartě projektu. Můžete specifikovat náklady a ceny jednotlivých zdrojů, skupin zdrojů nebo všech dostupných zdrojů společnosti.

Když jsou zdroje využívány nebo prodávány v projektu, ceny a náklady spojené s nimi jsou získány z informací, které jste nastavili.

Určujete výchozí částku za hodinu, kdy je zdroj vytvořen. Například pokud používáte konkrétní stroj na projektu po dobu pěti hodin, bude projekt vypočítán na základě částky za hodinu.

## <a name="to-set-up-a-resource"></a>Nastavení zdroje
Vytvořte kartu pro každý zdroj, který chcete použít v projektech.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zdroje** a zvolte související odkaz.
2. Zvolte akci **Nový**.
3. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.  

## <a name="to-set-up-a-resource-group"></a>Nastavení skupiny zdrojů
Můžete kombinovat několik zdrojů v jedné skupině zdrojů. Všechny kapacity a rozpočty skupin zdrojů jsou shromažďovány z jednotlivých zdrojů. Je také možné zadávat kapacity pro skupiny zdrojů buď nezávisle na nahromaděných hodnotách nebo vedle nich.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu** , zadejte **Skupiny zdrojů** a zvolte související odkaz.
2. Zvolte akci **Nový**.
3. Vyplňte pole podle potřeby.

## <a name="to-set-capacity-for-a-resource"></a>Nastavení kapacity pro prostředek 
Chcete-li vypočítat, kolik času může zdroj vynaložit na projekty, musí být jejich kapacita nejprve nastavena jako dostupný čas za období v pracovním kalendáři. Toto nastavení se používá při vyplňování řádků plánování projektu, které obsahují zdroj. Další informace naleznete v tématu [Návod: Vytvořit projekty](projects-how-create-jobs.md).

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zdroje** a zvolte související odkaz.
2. Otevřete příslušnou kartu zdroje a potom vyberte akci **Kapacita zdroje**.
3. V okně **Kapacita zdroje** v poli **Zobrazit po** určete délku období, například **Den** , který je zobrazen ve sloupcích na záložce s náhledem **Matice kapacity zdrojů**.
4. Pro každý prostředek na řádku určete pro každé období ve sloupcích počet hodin, kdy je prostředek k dispozici.
5. Chcete-li podrobně popsat týdenní kapacitu zdroje v počátečním a konečném datu, zvolte akci **Nastavit kapacitu** .
6. V okně **Nastavení kapacit zdrojů** vyplňte pole podle potřeby.
7. Zvolte akci **Aktualizovat kapacitu** . Okno **Kapacita zdroje** se aktualizuje o zadanou kapacitu.
8. Zavřete okno.

## <a name="to-set-up-alternate-resource-costs"></a>Nastavení alternativních nákladů na zdroje
Kromě nákladů uvedených na kartě zdroje můžete nastavit alternativní náklady pro každý zdroj. Například pokud zaplatíte zaměstnanci vyšší hodinovou sazbu za přesčasy, můžete nastavit náklady na zdroje za přesčasovou sazbu. Náhradní cena, kterou nastavíte pro zdroj, přepíše náklady na kartě zdroje při použití zdroje v deníku zdrojů.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zdroje** a zvolte související odkaz.  
2. Vyberte zdroj, pro který chcete nastavit jeden nebo více alternativních nákladů a pak vyberte akci **Náklady**.  
3. V okně **Náklady zdrojů** vyplňte pole podle potřeby.  
4. Opakujte krok 3 pro každou alternativní cenu zdroje, kterou chcete nastavit.

**Poznámka**. Chcete-li nastavit náklady na zdroje, které se budou vztahovat na všechny zdroje a skupiny zdrojů, otevřete okno **Náklady zdroje** a vyplňte pole.

## <a name="to-set-up-alternate-resource-prices"></a>Nastavení alternativních cen zdrojů  
Kromě ceny uvedené na kartě zdrojů můžete nastavit alternativní ceny pro každý zdroj. Tyto alternativní ceny mohou být podmíněné. Mohou záviset na tom, zda je zdroj používán s určitým projektem nebo typem práce.

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Zdroje** a zvolte související odkaz.
2. Vyberte zdroj, pro který chcete nastavit jednu nebo více alternativních cena a pak vyberte akci **Ceny**.
3. V okně **Ceny zdrojů** vyplňte pole podle potřeby.
4. Opakujte krok 3 pro každou alternativní cenu zdroje, kterou chcete nastavit.

## <a name="see-also"></a>Viz také
[Nastavit řízení projektu](projects-setup-projects.md)  
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Spravovat prodej](sales-manage-sales.md)      
[Pracujte s Dynamics NAV](ui-work-product.md)  

