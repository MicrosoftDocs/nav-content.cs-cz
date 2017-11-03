---
title: "Údržba dlouhodobého majetku"
description: "Uchovávejte záznamy o jakékoliv opravě a servisu dlouhodobého majetku."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: repair, service
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c43ed582294a5f77408e076a13d3cd07eb9f4d0f
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-maintain-fixed-assets"></a>Návod: Údržba dlouhodobého majetku
Náklady na údržbu jsou rutinní pravidelné náklady na zachování hodnoty DM. Na rozdíl od kapitálu nezvyšují hodnotu.

Můžete si zaznamenat a udržovat aktualizovaný soubor o údržbě a servisu svého DM, abyste měli k dispozici kompletní záznamy o údržbě DM, které jsou snadno dostupné. Pokaždé, když je dlouhodobý majetek poslán do servisu, zaznamenáváte všechny relevantní informace, jako je datum servisu, číslo dodavatele a telefonní číslo servisního agenta. Registrace údržby se zaznamenává pro každý dlouhodobý majetek z příslušné karty DM.

Odsazení slouží k úpravě hodnot pro obecné změny cenové hladiny. Dávková úloha **Indexovat DM** může být použita k vypočítání nákladů na údržbu.

## <a name="to-record-maintenance-work-on-a-fixed-asset"></a>Záznam prací k údržbě DM
Pokaždé, když byla provedena údržba, například návštěva servisu, můžete ji zaznamenat pro příslušný dlouhodobý majetek v okně **Evidence údržby**.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.  
2. Vyberte dlouhodobý majetek, u kterého chcete zobrazit údržbu a pak vyberte akci **Evidence údržby**.
3. V okně **Evidence údržby** vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

## <a name="to-post-maintenance-costs-from-a-fixed-asset-gl-journal"></a>Zaúčtování nákladů na údržbu z finančního deníku DM
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Přehled knihy odpisů** a pak vyberte související odkaz.  
2. Vyberte odpisovou knihu, kde chcete zobrazit dlouhodobý majetek a poté vyberte akci **Upravit**.
3. V okně **Karta odpisové knihy** zkontrolujte, zda není zaškrtnuto políčko **Údržba**. Tím je zajištěno, že náklady na údržbu nejsou zaúčtovány do hlavní knihy.
4. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční kniha DM** a pak vyberte související odkaz.  
5. Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby.
6. Do pole **Typ účtování DM** vyberte **Údržba**.
7. Zvolte možnost **Vložit protiúčet DM**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování údržby.

    > [!NOTE]  
>   Krok 7 funguje pouze v případě, že jste nastavili následující: V okně **Karta účto skupiny DM** pro účtovací skupinu DM pole **Účet nákladů údržby** obsahuje účet MD v hlavní knize a pole **Protiúčet údržby **obsahuje účet hlavní knihy, na který chcete zaúčtovat zůstatkové položky za účelem zhodnocení. Další informace naleznete v tématu "Nastavení skupin zaúčtování DM“ [Návod: Nastavení informací o obecném dlouhodobém majetku.](fa-how-setup-general.md).
8. Zvolte akci **Zaúčtovat**.

## <a name="to-follow-up-on-fixed-assets-service-visits"></a>Pokračování servisu na dlouhodobém majetku
Můžete vytisknout sestavu **Údržba - příští servis**, abyste zjistili, který majetek jste pro službu použili. Tuto sestavu můžete také použít při aktualizaci pole **Datum další údržby** na kartách DM.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Údržba – příští servis** a pak vyberte související odkaz.  
2. Vyplňte pole **Počáteční datum** a **Koncové datum**.  
3. Zvolte tlačítko **Tisk** nebo **Náhled**.

## <a name="to-monitor-maintenance-costs"></a>Monitorování nákladů na údržbu
Náklady na údržbu můžete zobrazit, když se podíváte na statistiky DM.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, u kterého chcete zobrazit náklady na údržbu a pak vyberte akci **Knihy odpisů**.
3. V okně **Knihy odpisů DM** vyberte příslušnou odpisovou knihu DM a poté zvolte akci **Statistiky**.
4. V okně **Statistiky DM** vyberte pole **Údržba**.

Okno **Položky údržby** zobrazuje položky, které tvoří částku v poli **Údržba**.

## <a name="to-view-or-print-maintenance-costs-for-multiple-fixed-assets"></a>Zobrazení nebo tisk nákladů na údržbu více DM
Ve zprávě **Údržba - analýza** můžete zvolit, zda chcete zobrazit údržbu na základě jednoho, dvou nebo tří kódů údržby pro zadané datum nebo období. Můžete vidět součet všech vybraných majetků nebo celkový součet každého majetku.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Údržba - analýza** a pak vyberte související odkaz.
2. Vyplňte pole dle potřeby.
3. Vyberte tlačítko **Tisk** nebo **Náhled**.

## <a name="to-view-maintenance-ledger-entries"></a>Zobrazení položek údržby
Náklady na údržbu si můžete prohlédnout také prostřednictvím prohlížení položek údržby.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, u kterého chcete zobrazit položky a pak vyberte akci **Knihy odpisů**.
3. V okně **Knihy odpisů DM** vyberte příslušnou odpisovou knihu DM a poté zvolte akci **Položky údržby**.

## <a name="to-view-or-print-maintenance-ledger-entries-for-multiple-fixed-assets"></a>Zobrazení nebo tisk položek údržby pro více DM
V přehledu **Údržba - detaily** můžete zobrazit nebo vytisknout položky o údržbě jednoho nebo více DM.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Údržba - detaily** a pak vyberte související odkaz.
2. Vyplňte pole dle potřeby.
3. Vyberte tlačítko **Tisk** nebo **Náhled**.

## <a name="see-also"></a>Viz také
[Dlouhodobý majetek](fa-manage.md)  
[Nastavení DM](fa-setup.md)  
[Finance](finance.md)  
[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

