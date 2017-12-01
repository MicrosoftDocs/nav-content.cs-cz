---
title: "Nastavení speciálních a prodejních cen a slev pro zákazníky"
description: "Popisuje jak definovat alternativní cenové a slevové smlouvy, které chcete použít na prodejních dokumentech když prodáváte různým dodavatelům."
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: special price, alternate price, pricing
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 980e6e117887e0a0dab68aedfa99f99c27b876c9
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-record-special-sales-prices-and-discounts"></a>Návod: Zaznamenávání speciálních prodejních cen a slev
Různé cenové a slevové dohody, které při prodeji platí pro různé zákazníky musí být definovány tak, aby dohodnutá pravidla a hodnoty byly použity na prodejních dokumentech, které vytvoříte pro zákazníky.

Když zaznamenáte speciální ceny a slevy na řádcích pro nákup a prodej, [!INCLUDE[d365fin](includes/d365fin_md.md)] zajistí, že váš zisk z obchodu se zbožím je vždy optimální tím, že automaticky vypočítá nejlepší cenu na nákupních a prodejních dokumentech, projektech a řádcích deníku zboží. Pro více informací sledujte následující sekci „Výpočet nejlepší ceny“.

Pokud jde o ceny, můžete mít speciální ceny na řádcích, jestliže existuje určitá kombinace zákazníka, zboží, minimálního množství, měrné jednotky a počátečního či koncového data.

Pokud jde o slevy, můžete nastavit a použít tyto dva druhy slev:

| Typ slevy | Popis |
| --- | --- |
| **Prodejní řádková sleva** |Částka slevy, která je vložena na prodejních řádcích v závislosti na kombinaci zákazníka, zboží, minimálního množství, měrné jednotky a počátečního či koncového data. Stejně to funguje pro prodejní ceny. |
| **Fakturační slevy** |Procentuální sleva je odečtena od celkové hodnoty dokumentu, pokud hodnota všech řádků na prodejním dokumentu přesahuje určité minimum. |

Vzhledem k tomu, že prodejní ceny a řádkové slevy jsou založeny na kombinaci položky a zákazníka, můžete tuto konfiguraci provést také z karty zboží (položky), kde můžete nastavit pravidla a hodnoty.

## <a name="to-set-up-a-sales-price-for-a-customer"></a>Nastavení prodejních cen zákazníka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zákazníci** a vyberte související odkaz.
2. Otevřete příslušnou kartu zákazníka a zvolte tlačítko **Ceny**.

    Políčko **Typ prodeje** je předvyplněno **Zákazníkem** a pole **Kód prodeje** je předvyplněno číslem zákazníka.
3. Vyplňte políčka na řádku, jak je potřeba. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)] Vyplňte řádek pro každou kombinaci, která poskytne speciální cenu pro zákazníka.

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a>Nastavení Prodejních řádkových sleva zákazníka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zákazníci** a vyberte související odkaz.
2. Otevřete příslušnou kartu zákazníka a zvolte tlačítko **Řádkové slevy**.

    Políčko **Typ prodeje** je předvyplněno **Zákazníkem** a pole **Kód prodeje** je předvyplněno číslem zákazníka.
3. Vyplňte políčka na řádku, jak je potřeba. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)] Vyplňtě řádek pro každou kombinaci, která poskytne prodejní řádkovou slevu pro zákazníka.

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a>Nastavení slevy z faktury pro zákazníka
Když se rozhodnete, kteří zákazníci mají nárok na fakturační slevu, tak vložte kód fakturační slevy na kartu zákazníka a nastavte podmínky pro daný kód.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zákazníci** a vyberte související odkaz.
2. Otevřete kartu zákazníka, pro zákazníka, který bude mít nárok na fakturační slevy.
3. V poli **Kód fakturační slevy **vyberte kód příslušné podmínky fakturační slevy k vypočítání fakturačních slev pro daného zákazníka.

    > [!NOTE]  
>   Kódy fakturačních slev jsou zastoupeny na existujících kartách zákazníků. To vám umožní rychle přiřadit podmínky fakturačních slev zákazníkovi výběrem jména jiného zákazníka, který má stejné podmínky.

    Pokračujte v nastavení nových podmínek fakturačních slev.
4. V okně **Karta zákazníka** zvolte **Fakturační slevy**. Otevře se okno ** Zák.fakturační slevy**.
5. Do pole **Kód měny** zadejte kód pro měnu, na kterou se využijí podmínky fakturační slevy na řádku. Nechte pole prázdné pro nastavení podmínek fakturační slevy v USD.
6. V poli **Minimální částka** zadejte minimální částku, kterou musí mít faktura pro slevu.
7. V poli **Sleva %** zadejte fakturační slevu jako procento částky faktury.
8. Opakujte kroky 5 až 7 pro každou měnu, pokud zákazník obdrží různé faktury.

Fakturační sleva je nyní nastavena a přiřazena dotyčnému zákazníkovi. Když si vyberete kód zákazníka v políčku **Kód fakturační slevy **na ostatních kartách zákazníků, bude přiřazena těmto zákazníkům stejná fakturační sleva.

## <a name="to-work-with-sales-invoice-discounts-and-service-charges"></a>Práce s fakturačními prodejními slevami a servisními poplatky
Když účtujete fakturační slevu, velikost fakturační částky určuje velikost slevy, která je udělená.  

Otevře se okno** ****Zák.fakturační slevy**, kde můžete přidat servisní poplatek k fakturaci k celkové částce.  

Předtím, než použijete fakturační slevy s prodejem, musíte nastavit určující informace v programu. Musíte se rozhodnout:  

- Kterým zákazníkům bude přidělena sleva.  
- Která slevová procenta použijete.  

Pokud budete fakturační slevu počítat automaticky, musíte to specifikovat v okně **Nastavení Prodeje a pohledávek**.  

Pro každého zákazníka můžete určit, zda bude mít fakturační slevu, pokud bude splněn požadavek. (Tj. Pokud bude částka faktury dostatečně vysoká) Nebo můžete definovat podmínky pro fakturační slevy v domácí měně pro domácí zákazníky a cizí měnu pro zahraniční.  

Procentuální hodnotu slevy specifikujete pro specifickou sumu v okně** Zák.fakturační slevy**. Můžete vložit jakékoli procento slevy do každého okna. Každý zákazník může mít vlastní okno, nebo můžete propojit několik zákazníků do jednoho okna.  

Kromě (nebo místo) procenta slevy můžete propojit částku za službu k určité částce faktury.  

> [!TIP]  
>  Předtím, než začnete vkládat tyto informace do programu, je dobré připravit si v návrh struktury slev, které chcete používat. Toto vám zjednoduší přehled, kteří zákazníci jsou spojení na stejnou fakturační slevu. Čím méně oken musíte nastavit, tím rychleji můžete zadat základní informace.  

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

## <a name="to-copy-sales-prices"></a>Kopírování prodejních cen  
Pokud chcete kopírovat prodejní ceny, jako je individuální zákaznická cena, která může být použita pro cenovou skupinu zákazníků, musíte spustit dávkovou úlohu. **Navrhnout cenu z  ceny** Tuto dávkovou úlohu naleznete v okně **Sešit prodejní ceny**.    

1.  Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Sešit prodejní ceny** a vyberte související odkaz.  
2.  Zvolte akci **Navrhnout cenu z ceny**  
3.  Na záložce **Prodejní ceny** vyplňte **Typ prodeje** a **Kód prodeje** s původní prodejní cenou, kterou chcete zkopírovat  
4.  V horní části v oknu požadavku vyplňte **Typ prodeje** a **Kód prodeje** typem a názvem, kam chcete kopírovat slevy.  
5.  Pokud chcete dávkovou úlohou vytvořit nové ceny, vyberte pole **Vytvořit nové ceny**.  
6.  Vybráním tlačítka **OK** k vyplnění řádku v **Sešitu prodejní ceny** s navrhnutými novými cenami, indikující, že byly validovány a jsou v **Typu prodeje**.  

> [!NOTE]  
>  Tato dávková úloha vytváří pouze návrhy a nevykonává navrhované změny. Pokud jste spokojeni s návrhem a chcete ho implementovat, to znamená vložení dat do tabulky **Prodejní cena**, můžete použít dávkovou úlohu **Provést změnu ceny**, kterou naleznete v záložce **Akce** ve skupině **Funkce** v okně **Sešitu prodejní ceny**.

## <a name="see-also"></a>Viz také
[Nastavení prodeje](sales-setup-sales.md)  
[Prodej](sales-manage-sales.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

