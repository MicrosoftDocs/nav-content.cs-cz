---
title: "Definování metod NV a monitorování průběhu projektu"
descrition: Describes how you can create a work in process (WIP) method and calculate WIP to estimate the financial value of jobs while they are ongoing.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project management, KPI, work in process, work in progress
ms.date: 07/04/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a39f15313a24c726cd7ce7b55db85c5feced9911
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-monitor-job-progress-and-performance"></a>Návod: Monitorování pokroku a výkonu projektu
Jak postupuje projekt, materiály, zdroje a další výdaje jsou spotřebovány a musí být zaúčtovány k projektu. Nedokončená výroba (NV) je funkce, která umožňuje odhadnout finanční hodnotu projektů v hlavní knize, zatímco projekty probíhají. V mnoha případech můžete zaúčtovat výdaje za práci před fakturací projektu. Pokud byly zaúčtovány pouze výdaje, vaše finanční výkazy budou nepřesné. Další informace naleznete v tématu [Porozumnění Metod NV](projects-understanding-wip.md).

Chcete-li sledovat hodnotu v hlavní knize, můžete vypočítat NV a zaúčtovat hodnotu do hlavní knihy.

NV můžete vypočítat na základě následujících údajů:

* Hodnota nákladů
* Prodejní hodnota
* Rozpoznatelné náklady
* Procento dokončení
* Dokončená smlouva

Chcete-li výsledek zobrazit jiným způsobem, můžete změnit metodu a vypočítat znovu NV. Neexistuje žádný limit počtu výpočtů NV. NV se pouze vypočítává, neúčtuje se do hlavní knihy. Poté, co jste vypočítali NV, můžete ji zaúčtovat do hlavní knihy.

## <a name="to-create-a-job-wip-method"></a>Vytvoření metody NV projektu
Můžete vytvořit metodu NV projektu, která odráží potřeby vaší organizace. Poté, co jste je vytvořili, můžete ji nastavit jako výchozí metodu výpočtu NV, která bude použita ve vaší organizaci.  

> [!NOTE]
> Po použití nové metody k vytvoření položek NV nelze metodu odstranit nebo upravit.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Metody NV projektu** a vyberte související odkaz.  
2. Vyberte akci **Nový** a poté vyplňte pole. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
3. Zavřete okno.   
4. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení projektů** a vyberte související odkaz.  
5. V poli **Výchozí metoda NV** vyberte metodu ze seznamu.

## <a name="to-define-a-wip-method-for-a-job"></a>Definice metody NV pro projekt
Při vytváření nového projektu musíte zadat, kterou metodu NV použijete. V některých případech je metoda NV projektu, kterou můžete použít nastavena jako výchozí.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.
2. Vyberte akci **Nový**. Další informace naleznete v tématu [Návod: Tvorba projektů.](projects-how-create-jobs.md).  
3. V okně **Karta projektu** v poli **Metoda NV** vyberte metodu NV ze seznamu. Pokud byla definována výchozí metoda, můžete v případě potřeby vybrat jinou možnost.  

## <a name="to-calculate-wip"></a>Vypočítání NV
Můžete stanovit částku NV, která má být zaúčtována na rozvahové účty pro vykazování konce období. Použijete dávkovou úlohu **Vypočítat NV projektu**.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Vypočítat NV projektu** a vyberte související odkaz.  
2. Vyberte akci **Vypočítat NV**.
3. V okně **Vypočítat NV projektu** vyplňte pole podle potřeby.
4. Zvolte tlačítko **OK**.  

> [!NOTE]  
>   Dávková úloha vypočítá pouze NV. Neúčtuje se do hlavní knihy. Chcete-li tak učinit, musíte po výpočtu NV spustit dávkovou úlohu **Zaúčtovat NV do hl. knihy**. Další informace naleznete v následujícím postupu.

## <a name="to-post-wip"></a>Zaúčtování NV
Když jste vypočítali NV, můžete ji zaúčtovat do rozvahových účtů pro vykazování konce období. Použijete dávkovou úlohu **Zaúčtovat NV projektu do hl. knihy**.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Věcné položky NV projektu** a vyberte související odkaz.  
2. V okně **Zaúčtovat NV projektu** vyplňte pole podle potřeby.  
3. Zvolte tlačítko **OK**.

## <a name="to-view-job-usage-estimates-and-post-updates"></a>Zobrazení odhadu spotřeby projektu a zaúčtování aktualizace
Můžete sledovat spotřebu projektu až do jeho dokončení v jednom kroku. K tomu použijte dávkovou úlohu **Výp. projektu. Dávková úloha zbývající spotřeba** pro všechny činnosti až do konce projektu.  

To vám umožní sledovat a porovnávat původní odhady s aktuálními výsledky a podle potřeby provádět úpravy nebo nové položky. Například můžete odhadnout, že práce vyžadovala 10 hodin a dosud to trvalo 15 hodin. Můžete přidat další pět hodin do existujícího řádku deníku nebo vytvořit nový řádek deníku, který vykáže těchto pět hodin jako přesčas, což je další typ práce. Vypočítá se příslušná cena a náklady a poté je můžete zaúčtovat do deníku.  

> [!NOTE]  
>   Položky zboží vytvářejí položky zboží a snižují množství zásob. Dávková úloha **Účtování nákladů na zboží** převádí náklady ze zásob do hlavní knihy. Položky zdrojů vytvářejí věcné položky zdrojů.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky projektů** a vyberte související odkaz.  
2. Vyberte příslušný deník projektu a potom vyberte akci **Výpočet zbývajícího použití**.  
3. V okně **Výpočet zbývajícího použití **zadejte číslo dokladu a zúčtovací datum, které chcete vložit do deníku a potom klepněte na tlačítko **OK**.  
4. Aktualizujte deník se všemi možnými úpravami.  
5. Zvolte **Zaúčtovat**.

## <a name="to-view-job-ledger-entries"></a>Zobrazení položek projektu
Všechny záznamy týkající se projektu jsou zaznamenány v žurnálu projektů a číslovány postupně, počínaje 1. Z žurnálu projektu získáte přehled o všech položkách projektu.    

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Žurnály projektů** a vyberte související odkaz.
2. Vyberte příslušný žurnál a poté zvolte akci **Položky projektu**.

V okně **Položky projektu** můžete zkontrolovat položky, které jsou přiřazeny k libovolnému projektu.  

## <a name="see-also"></a>Viz také
[Správa projektů](projects-manage-projects.md)
[Správa nákladů zásob](finance-manage-inventory-costs.md)   
[Finance](finance.md)  
[Nákup](purchasing-manage-purchasing.md)         
[Prodej](sales-manage-sales.md)      
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

