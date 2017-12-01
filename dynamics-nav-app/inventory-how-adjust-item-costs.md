---
title: "Ruční upravení nákladů zboží"
description: "Můžete upravit hodnotu zboží pomocí metod FIFO nebo průměrných nákladů, například když se náklady zboží mění z jiných důvodů než transakce."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cost adjustment, cost forwarding, costing method, inventory valuation, costing
ms.date: 08/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 40647e0263b7c21c1f085cd6dde449f8210ede10
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-adjust-item-costs"></a>Návod: Upravení nákladů zboží
Náklady na zboží (hodnotu zásob), kterou si koupíte a později prodáváte, se mohou během své životnosti měnit, například proto, že náklady na dopravu jsou po prodeji zboží přidány k nákupním nákladům. To je zvláště důležité v situacích, kdy prodáváte zboží před fakturováním nákupu tohoto zboží. Aby byla vždy známá správná hodnota zásob, je třeba pravidelně upravovat náklady zboží. To zajišťuje, že statistiky prodeje a zisku jsou aktuální a že finanční ukazatele KPI jsou správné. Další informace naleznete v tématu [Detaily návrhu: Úprava nákladů](design-details-cost-adjustment.md).

Hodnota v poli **Pořizovací cena** na kartě zboží je zpravidla založena na standardních nákladech na zboží se standardní metodou výpočtu nákladů. Zboží se všemi ostatními způsoby výpočtu je založeno na výpočtu dostupných zásob (fakturované náklady a očekávané náklady) vydělené daným množstvím. Další informace naleznete v sekci „Porozumění výpočtu pořizovací ceny“.

V [!INCLUDE[d365fin](includes/d365fin_md.md)] náklady zboží se automaticky upravují pokaždé, když dojde k uskutečnění inventarizace, například při zaúčtování nákupní faktury za zboží.

Můžete také použít funkci pro manuální úpravu nákladů na jedno nebo více zboží. To je užitečné, například když víte, že náklady zboží se změnily z jiných důvodů než je transakce zboží.

Náklady zboží jsou upraveny metodou FIFO nebo metodou průměrných nákladů v závislosti na vašem výběru v asistovaném nastavení **Nastavení mojí společnosti** nebo v poli **Metoda nákladů** na kartě zboží. Další informace naleznete v tématu [Návod: Registrace nového zboží](inventory-how-register-new-items.md).  

Pokud použijete metodu FIFO, pak pořizovací cena zboží je skutečná hodnota jakéhokoliv přijetí zboží. Zásoby se oceňují za předpokladu, že první zboží zařazené do zásob je prodáno jako první.

Používáte-li metodu Průměrné náklady, potom se pořizovací cena zboží vypočte jako průměrná pořizovací cena v každém okamžiku po zakoupení. Zásoby jsou oceněny za předpokladu, že všechny zásoby se prodávají současně. U zboží, které používá tuto metodu nákladů, můžete zvolit pole **Pořizovací cena** na kartě zboží, aby se zobrazila historie transakcí, od kterých se vypočítávají průměrné náklady

Funkce úpravy nákladů zpracovává pouze hodnoty, které ještě nebyly upraveny. Pokud se funkce setká se situací, kdy je třeba přenést změněné příchozí náklady do přidružených odchozích položek, vytvoří se nové upravené položky, které jsou založeny na informacích v položkách původní hodnoty, ale obsahují upravenou částku. Funkce úpravy nákladů používá datum zaúčtování položky původní hodnoty do upravené položky, pokud se toto datum nenachází v uzavřeném období zásob. V takovém případě program používá datum zahájení dalšího otevřeného období zásob. Pokud se nepoužije doba zásob, pak bude definováno v poli **Povolit účto od** v okně **Nastavení Financí**, kdy bude zaúčtována upravená položka.

## <a name="to-adjust-item-costs-manually"></a>Ruční úprava nákladů zboží
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Adjustace nákladů - položky zboží** a pak vyberte související odkaz.
2. V okně **Adjustace nákladů - položky zboží** specifikujte, které zboží chcete upravit.
3. Zvolte tlačítko **OK**.

## <a name="to-make-general-changes-in-the-direct-unit-cost"></a>Provedení obecných změn v přímé pořizovací ceně
Pokud potřebujete změnit přímé pořizovací ceny několika zboží, můžete použít dávkovou úlohu **Upravit náklady/ceny zboží**.  

 Dávková úloha změní obsah do pole **Pořizovací cena** na kartě zboží. Dávkové úlohy mění obsah pole stejným způsobem pro všechno zboží nebo vybrané zboží. Dávková úloha vynásobí hodnotu v poli pomocí specifikovaného faktoru úprav.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Upravit náklady/ceny zboží** a pak vyberte související odkaz.  
2. V poli **Upravit pole** specifikujete, které zboží nebo kartu SKU chcete upravit.  
3. V poli **Faktor úpravy** zadejte faktor, podle kterého bude hodnota upravena. Například zadejte hodnotu **1,5** pro zvýšení hodnoty o 50%.  
4. V záložce s náhledem **Zboží** nastavte filtry, které specifikují například zboží, které se má zpracovat s dávkovou úlohou.  
5. Zvolte tlačítko **OK**.  

## <a name="understanding-unit-cost-calculation"></a>Porozumění výpočtu pořizovací ceny
Hodnota v poli **Pořizovací cena** na kartě zboží je zpravidla založena na standardních nákladech pro zboží s metodou ocenění standardní. Zboží se všemi ostatními metodami ocenění je založeno na výpočtu dostupných zásob (fakturované náklady a očekávané náklady) vydělené daným množstvím.  

 Jak ovlivňuje obsah pole **Metoda ocenění** náklady na výpočet pořizovací ceny při nákupu a prodeji, je podrobněji popsáno v následujících částech.  

## <a name="unit-cost-calculation-for-purchases"></a>Výpočet pořizovací ceny pro nákup  
 Při zakoupení zboží se hodnota v poli **Poslední přímé náklady** na kartě zboží zkopíruje do pole **Přímá pořizovací cena** na nákupním řádku nebo na řádku částka jednotky na řádku deníku zboží.  

 To, co jste vybrali v poli **Metoda ocenění** ovlivňuje způsob jak [!INCLUDE[d365fin](includes/d365fin_md.md)] výpočte obsah pole **Pořizovací cena** na řádcích.  

### <a name="costing-method-fifo-lifo-specific-or-average"></a>Metoda ocenění FIFO, LIFO, specifická nebo průměrná  
 [!INCLUDE[d365fin](includes/d365fin_md.md)] vypočítá obsah pole **Pořizovací cena (CZK)** na nákupním řádku nebo obsah pole **Pořizovací cena** na řádku deníku zboží podle následujícího vzorce:  

 Pořizovací cena (CZK) = (Nákupní cena - (Částka slevy / Množství)) x (1 + Nepřímé náklady % / 100) + Režijní náklady  

### <a name="costing-method-standard"></a>Standardní metoda ocenění  
 Pole **Pořizovací cena (CZK)** na nákupním řádku nebo pole **Pořizovací cena** je vyplněno na řádku deníku zboží kopírováním hodnoty v poli **Pořizovací cena** na kartě zboží. Použitím metody ocenění standardní, je toto vždy založeno na standardním oceněním.  

 Po zaúčtování nákupu se pořizovací cena z nákupního řádku nebo řádku deníku zboží zkopíruje do položky faktury nákupního zboží a může být vidět na seznamu položek pro zboží.  

### <a name="all-costing-methods"></a>Všechny metody ocenění  
 Pořizovací cena z řádku zdrojového dokladu se použije k výpočtu obsahu pole **Částka nákladů (skutečná)** nebo popřípadě pole **Částka nákladů (očekávaná)**, která se vztahuje k této položce zboží bez ohledu na metodu ocenění pro zboží.  

## <a name="unit-cost-calculation-for-sales"></a>Výpočet pořizovací ceny pro prodej  
 Při prodeji zboží se pořizovací cena zkopíruje z pole Pořizovací cena na kartu zboží do prodejního řádku nebo do řádku deníku zboží.  

 Po zaúčtování se pořizovací cena zkopíruje do položky prodejní faktury zboží a je vidět na seznamu položek pro zboží. [!INCLUDE[d365fin](includes/d365fin_md.md)] Použije se pořizovací cena z řádku zdrojového dokladu k výpočtu obsahu pole **Částka nákladů (skutečná)** nebo popřípadě pole **Částka nákladů (očekávaná)** souvisí hodnota položky s touto položkou zboží.  

## <a name="see-also"></a>Viz také
[Správa nákladů zásob](finance-manage-inventory-costs.md)  
[Sklady](inventory-manage-inventory.md)  
[Prodej](sales-manage-sales.md)  
[Nákup](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

