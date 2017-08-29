---
title: "Návod: Záznam nákupních cen a slev"
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
ms.openlocfilehash: f99bb0aeef2c25048b0da3e0476ae2d612bff562
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-record-purchase-prices-and-discounts"></a>Návod: Záznam nákupních cen a slev
Různé cenové a slevové dohody, které použijete při nákupu od různých dodavatelů musí být definovány tak, aby se dohodnuté pravidla a hodnoty použily na nákupní doklad, které vytvoříte pro dodavatele.

Pokud jde o ceny, můžete mít speciální nákupní ceny zadané na nákupním řádku, pokud existuje určitá kombinace dodavatele, zboží, minimálního množství, měrné jednotky nebo počátečního/koncového data.

Pokud jde o slevy, můžete nastavit a použít dva typy nákupních slev:

|Typ slevy |Popis |
|--------------|------------|
|**Sleva na nákupním řádku**|Zvýhodněná částka, která je vložena na nákupním řádku, pokud existuje určitá kombinace dodavatele, zboží, minimálního množství, měrné jednotky nebo počátečního/koncového data. Toto funguje stejným způsobem jako u nákupních cen.|
|**Fakturační slevy**|Procentní sleva, která se odečte od celkové hodnoty dokladu, pokud hodnota všech řádků na nákupním dokladu převyšuje určité minimum.|

Vzhledem k tomu, že slevy na nákupním řádku a nákupní ceny jsou založeny na kombinaci zboží a dodavatele, můžete také tuto konfiguraci zadat z karty zboží, kde jsou definována pravidla a hodnoty. Další informace naleznete v tématu [Návod: Registrace nového produktu](inventory-how-register-new-products.md).

## <a name="to-set-up-a-special-purchase-price-for-a-vendor"></a>Nastavení zvláštní nákupní ceny pro dodavatele
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.
2. Otevřete příslušnou kartu dodavatele a pak zvolte akci **Cena**.

    Pole **Typ nákupu** je předem vyplněno **Dodavatelem** a pole **Kód nákupu** je předvyplněno číslem dodavatele.
3. Vyplňte pole na řádku podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
4. Vyplňte řádek pro každou kombinaci, pro kterou vám prodejce uděluje slevu na nákupním řádku.

## <a name="to-set-up-a-line-discount-for-a-vendor"></a>Nastavení slevy na řádku pro dodavatele
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.
2. Otevřete příslušnou kartu dodavatele a pak zvolte akci **Řádkové slevy**.

    Pole **Typ nákupu** je předem vyplněno **Dodavatelem** a pole **Kód nákupu** je předvyplněno číslem dodavatele.
3. Vyplňte pole na řádku podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
4. Vyplňte řádek pro každou kombinaci, pro kterou vám prodejce uděluje slevu na nákupním řádku.

## <a name="to-set-up-an-invoice-discount-for-a-vendor"></a>Nastavení fakturační slevy pro dodavatele
Pokud vás váš dodavatel informuje o fakturačních slevách, které poskytne, zadejte na kartě dodavatele kód fakturační slevy a nastavte podmínky pro každý kód.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.
2. Otevřete kartu dodavatele, který bude mít nárok na fakturační slevu.
3. V poli **Kód fakturační slevy vyberte **kód pro příslušné podmínky fakturační slevy pro výpočet slev na fakturu pro dodavatele.

    **Poznámka**: Kódy fakturační slevy představují stávající karty dodavatele. To vám umožní rychle přiřadit podmínky fakturační slevy výběrem jména dalších dodavatelů, kteří budou mít stejné podmínky.

    Pokračujte v nastavení nových podmínek slevy na nákupní fakturu.
4. V okně **Karta dodavatele** vyberte akci **Fakturační slevy**. Otevře se** okno Dod.fakturační slevy**.
5. Do pole **Kód měny** zadejte kód pro měnu, na kterou se využijí podmínky fakturační slevy na řádku. Nechte pole prázdné pro nastavení podmínek fakturační slevy v USD.
6. V poli **Minimální částka** zadejte minimální částku, kterou musí mít faktura pro slevu.
7. V poli **Sleva %** zadejte fakturační slevu jako procento částky faktury.
8. Opakujte kroky 5 až 7 pro každou měnu, na kterou dodavatel obdrží jinou fakturační slevu.

Fakturační sleva je nyní nastavena a přidělena danému dodavateli. Když vyberete kód dodavatele v poli **Kód fakturační slevy na **ostatních kartách dodavatelů, stejná fakturační sleva je přidělena těmto dodavatelům.

## <a name="see-also"></a>Viz také  
[Nastavení nákupu](purchasing-setup-purchasing.md)  
[Správa nákupu](purchasing-manage-purchasing.md)

