---
title: "Nastavení speciálních a alternativních cen a slev pro dodavatele"
description: "Můžete definovat jinou nebo alternativní cenu a dohody o slevách a použít je na nákupních dokumentech."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: special price, alternate price, pricing
ms.date: 07/03/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: cc4240ea4201bd68b3c2c9c27ab91dc49583e6a6
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-record-special-purchase-prices-and-discounts"></a>Návod: Zaznamenávání speciálních nákupních cen a slev
Různé cenové a slevové dohody, které použijete při nákupu od různých dodavatelů musí být definovány tak, aby se dohodnuté pravidla a hodnoty použily na nákupní doklad, které vytvoříte pro dodavatele.

Když zaznamenáte speciální ceny a slevy na řádcích pro nákup a prodej, [!INCLUDE[d365fin](includes/d365fin_md.md)] zajistí, že váš zisk z obchodu se zbožím je vždy optimální tím, že automaticky vypočítá nejlepší cenu na nákupních a prodejních dokumentech, projektech a řádcích deníku zboží. Pro více informací sledujte následující sekci „Výpočet nejlepší ceny“.

Pokud jde o ceny, můžete mít speciální nákupní ceny zadané na nákupním řádku, pokud existuje určitá kombinace dodavatele, zboží, minimálního množství, měrné jednotky nebo počátečního/koncového data.

Pokud jde o slevy, můžete nastavit a použít dva typy nákupních slev:

| Typ slevy | Popis |
| --- | --- |
| **Sleva na nákupním řádku** |Zvýhodněná částka, která je vložena na nákupním řádku, pokud existuje určitá kombinace dodavatele, zboží, minimálního množství, měrné jednotky nebo počátečního/koncového data. Toto funguje stejným způsobem jako u nákupních cen. |
| **Fakturační slevy** |Procentní sleva, která se odečte od celkové hodnoty dokladu, pokud hodnota všech řádků na nákupním dokladu převyšuje určité minimum. |

Vzhledem k tomu, že slevy na nákupním řádku a nákupní ceny jsou založeny na kombinaci zboží a dodavatele, můžete také tuto konfiguraci zadat z karty zboží, kde jsou definována pravidla a hodnoty. Další informace naleznete v tématu [Návod: Registrovat nového zboží](inventory-how-register-new-items.md).

## <a name="to-set-up-a-special-purchase-price-for-a-vendor"></a>Nastavení zvláštní nákupní ceny pro dodavatele
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dodavatelé** a vyberte související odkaz.
2. Otevřete příslušnou kartu dodavatele a pak zvolte akci **Cena**.

    Pole **Typ nákupu** je předem vyplněno **Dodavatelem** a pole **Kód nákupu** je předvyplněno číslem dodavatele.
3. Vyplňte pole na řádku podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Vyplňte řádek pro každou kombinaci, pro kterou vám prodejce uděluje slevu na nákupním řádku.

## <a name="to-set-up-a-line-discount-for-a-vendor"></a>Nastavení slevy na řádku pro dodavatele
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dodavatelé** a vyberte související odkaz.
2. Otevřete příslušnou kartu dodavatele a pak zvolte akci **Řádkové slevy**.

    Pole **Typ nákupu** je předem vyplněno **Dodavatelem** a pole **Kód nákupu** je předvyplněno číslem dodavatele.
3. Vyplňte pole na řádku podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
4. Vyplňte řádek pro každou kombinaci, pro kterou vám prodejce uděluje slevu na nákupním řádku.

## <a name="to-set-up-an-invoice-discount-for-a-vendor"></a>Nastavení fakturační slevy pro dodavatele
Pokud vás váš dodavatel informuje o fakturačních slevách, které poskytne, zadejte na kartě dodavatele kód fakturační slevy a nastavte podmínky pro každý kód.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dodavatelé** a vyberte související odkaz.
2. Otevřete kartu dodavatele, který bude mít nárok na fakturační slevu.
3. V poli **Kód fakturační slevy **vyberte kód pro příslušné podmínky fakturační slevy pro výpočet slev na fakturu pro dodavatele.

    > [!NOTE]  
>   Kódy fakturační slevy představují stávající karty dodavatele. To vám umožní rychle přiřadit podmínky fakturační slevy výběrem jména dalších dodavatelů, kteří budou mít stejné podmínky.

    Pokračujte v nastavení nových podmínek slevy na nákupní fakturu.
4. V okně **Karta dodavatele** vyberte akci **Fakturační slevy**. Otevře se okno** Dod.fakturační slevy**.
5. Do pole **Kód měny** zadejte kód pro měnu, na kterou se využijí podmínky fakturační slevy na řádku. Nechte pole prázdné pro nastavení podmínek fakturační slevy v USD.
6. V poli **Minimální částka** zadejte minimální částku, kterou musí mít faktura pro slevu.
7. V poli **Sleva %** zadejte fakturační slevu jako procento částky faktury.
8. Opakujte kroky 5 až 7 pro každou měnu, na kterou dodavatel obdrží jinou fakturační slevu.

Fakturační sleva je nyní nastavena a přidělena danému dodavateli. Když vyberete kód dodavatele v poli **Kód fakturační slevy **na ostatních kartách dodavatelů, stejná fakturační sleva je přidělena těmto dodavatelům.

## <a name="to-choose-a-principle-for-posting-purchase-discounts"></a>Výběr principu pro účtování nákupních slev  
Když účtujete nákupní fakturu obsahující jednu nebo více slev, můžete si vybrat mezi dvěma principy pro účtování slev. Můžete účtovat slevy separátně nebo je můžete odečíst z fakturačních slev.  

Předtím, než to uděláte, musíte mít již nastavené potřebně účty pro účtování slev v hlavní knize. Také musíte zkontrolovat, že máte vložené správné účty v nastavení účtování** v poli Účet nákupní řádkové slevy**** a Účet nákupní fakturační slevy **.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení nákupů a závazků** a vyberte související odkaz.
2. V poli **Účtování slevy** vyberte následující principy pro účtování slev.

|**Princip účtování slev**|**Fakturační slevy**|**Řádková sleva**|  
|------------------------------------|--------------------------|-----------------------|  
|**Všechny slevy**|Účtováno samostatně|Účtováno samostatně|  
|**Fakturační slevy**|Účtováno samostatně|Odečtené|  
|**Řádková sleva**|Odečtené|Účtováno samostatně|  
|**Bez slev**|Odečtené|Odečtené|  

# <a name="purchase-invoice-discounts-and-service-charges"></a>Platba fakturačních slev a servisních poplatků
Pokud máte fixní termín pro fakturační slevu s jakýmkoli dodavatelem, slevy můžete vložit. Poté bude sleva kalkulována, když ji vyplníte do faktury.  

 Předtím, než začnete používat fakturační slevy, musíte specifikovat dodavatele, kteří vám nabídli slevy.  

 Procentuální hodnotu slevy specifikujete pro specifickou sumu v okně** Dod.fakturační slevy**. Můžete vložit jakékoli procento slevy do každého okna. Každý dodavatel může mít vlastní okno, nebo můžete propojit několik dodavatelů do jednoho okna.  

 Kromě procenta slevy můžete propojit částku za službu k určité částce faktury.  

 Nebo můžete definovat podmínky pro fakturační slevy v domácí měně pro domácí dodavatele a cizí měnu pro zahraniční.  

 Můžete si zvolitt zda [!INCLUDE[d365fin](includes/d365fin_md.md)] automaticky vypočítá fakturaní slevy pro nabídky, hromadné objednávky, objednávky, faktury a dobropisy.  

> [!TIP]  
>  Předtím, než vložíte tyto informace je dobré připravit si v návrh struktury slev, které chcete používat. Toto vám zjednoduší přehled, kteří dodavatelé jsou spojení na stejnou fakturační slevu. Čím méně oken musíte nastavit, tím rychleji můžete zadat základní informace.

## <a name="best-price-calculation"></a>Výpočet nejlepší ceny
Když zaznamenáte speciální ceny a slevy na řádcích pro nákup a prodej, [!INCLUDE[d365fin](includes/d365fin_md.md)] zajistí, že váš zisk z obchodu se zbožím je vždy optimální tím, že automaticky vypočítá nejlepší cenu na nákupních a prodejních dokumentech, projektech a řádcích deníku zboží.

Nejvýhodnější cenou je nejnižší dovolená cena s nejvyšší přípustnou slevou v dané lhůtě. [!INCLUDE[d365fin](includes/d365fin_md.md)] Dynamics NAV automaticky vypočítá při vložení jednotkové ceny a procentuální slevy pro položky na nových řádcích dokumentů a deníků.

> [!NOTE]  
>   Následující část popisuje jak jsou vypočítány nejlepší ceny pro prodej. Kalkulace stejně počítá pro nákup.

1. [!INCLUDE[d365fin](includes/d365fin_md.md)] Kontroluje kombinaci zákazníka s fakturou a zboží, poté vypočítá příslušnou jednotkovou cenu a procentní sazbu lineárních plateb podle následujících kritérií:

    - Má zákazník cenovou/slevovou smlouvu nebo zákazník patří do skupiny, která je má?
    - Je zboží zahrnuté do skupiny slev nebo je na cenová/slevová smlouva?
    - Je datum objednání (nebo datum zúčtování pro fakturu nebo dobropis) v rozpětí počátečního/koncového data slevové smlouvy?
    - Je specifikovaný kód měrné jednoty? V [!INCLUDE[d365fin](includes/d365fin_md.md)] kontroluje pro slevy/ceny se stejnou měrnou jednotkou nebo slevy/ceny bez měrné jednotky.

2. [!INCLUDE[d365fin](includes/d365fin_md.md)] Ověření, zda se na informace o dokumentu nebo deníku vztahují na dohody o ceně / slevách a poté se vloží příslušná jednotková cena a procentní sazba slevy podle následujících kritérií:

    - Je podmínka minimálního množství ve smlouvě o ceně/slevě splněna?
    - Je podmínka požadované měny ve smlouvě o ceně/slevě splněna? Pokud ano, dojde k vložení nejnižší ceny a nejvyšší řádkové slevy pro danou měnu a to i v případě, že je v lokální měně lepší cena. Pokud neexistuje daná kód měny ve smlouvě o ceně/slevě, [!INCLUDE[d365fin](includes/d365fin_md.md)] vloží do lokální měny nejnižší cenu a největší řádkovou slevu.

Dále, pokud není zadaná speciální cena, může být vypočítána pro položku na řádku, nebo se vloží  poslední přímá cena nebo cena z karty zboží.

## <a name="see-also"></a>Viz také
[Nastavení nákupu](purchasing-setup-purchasing.md)  
[Nákup](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

