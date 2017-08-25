---
title: "Návod: Zaznamenávání prodejních cen a slev"
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
ms.openlocfilehash: 2d6438108fb2c36bb6f0d44efddc053bd628d068
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a>Návod: Zaznamenávání prodejních cen a slev
Různé cenové a slevové dohody, které při prodeji platí pro různé zákazníky musí být definovány tak, aby dohodnutá pravidla a hodnoty byly použity na prodejních dokumentech, které vytvoříte pro zákazníky.

Pokud jde o ceny, můžete mít speciální ceny na řádcích, jestliže existuje určitá kombinace zákazníka, zboží, minimálního množství, měrné jednotky a počátečního či koncového data.

Pokud jde o slevy, můžete nastavit a použít tyto dva druhy slev:

|Typ slevy |Popis |
|--------------|------------|
|**Prodejní řádková sleva**|Částka slevy, která je vložena na prodejních řádcích v závislosti na kombinaci zákazníka, zboží, minimálního množství, měrné jednotky a počátečního či koncového data. Stejně to funguje pro prodejní ceny.|
|**Sleva z faktury**|Procentuální sleva je odečtena od celkové hodnoty dokumentu, pokud hodnota všech řádků na prodejním dokumentu přesahuje určité minimum.|

Vzhledem k tomu, že prodejní ceny a řádkové slevy jsou založeny na kombinaci položky a zákazníka, můžete tuto konfiguraci provést také z karty zboží (položky), kde můžete nastavit pravidla a hodnoty.

## <a name="to-set-up-a-sales-price-for-a-customer"></a>Nastavení prodejních cen zákazníka.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zákazníci** a poté vyberte příslušný odkaz.
2. Otevřete příslušnou kartu zákazníka a zvolte tlačítko **Ceny**.

    Políčko **Typ prodeje** je předvyplněno **Zákazníkem** a pole **Kód prodeje** je předvyplněno číslem zákazníka.
3. Vyplňte políčka na řádku jak je potřeba. Vyberte pole a přečtěte si krátký popis pole nebo zvolte odkaz pro další informace.
4. Vyplňte řádek pro každou kombinaci, která poskytne speciální cenu pro zákazníka.

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a>Nastavení Prodejních řádkových sleva zákazníka.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zákazníci** a poté vyberte příslušný odkaz.
2. Otevřete příslušnou kartu zákazníka a zvolte tlačítko **Řádkové slevy**.

    Políčko **Typ prodeje** je předvyplněno **Zákazníkem** a pole **Kód prodeje** je předvyplněno číslem zákazníka.
3.  Vyplňte políčka na řádku jak je potřeba. Vyberte pole a přečtěte si krátký popis pole nebo zvolte odkaz pro další informace.
4. Vyplňtě řádek pro každou kombinaci, která poskytne prodejní řádkovou slevu pro zákazníka.

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a>Nastavení slevy z faktury pro zákazníka.
Když se rozhodnete, kteří zákazníci mají nárok na fakturační slevu, tak vložte kód fakturační slevy na kartu zákazníka a nastavte podmínky pro daný kód. 

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zákazníci** a poté vyberte příslušný odkaz.
2. Otevřete kartu zákazníka, pro zákazníka, který bude mít nárok na fakturační slevy.
3. V okně **Fakturační slevy Políčko Kód** vyberte kód příslušné podmínky fakturační slevy k vypočítání fakturačních slev pro daného zákazníka.

    **Poznámka**: Kódy fakturačních slev jsou zastoupeny na existujících kartách zákazníků. To vám umožní rychle přiřadit podmínky fakturačních slev zákazníkovi výběrem jména jiného zákazníka, který má stejné podmínky.

     Pokračujte v nastavení nových podmínnek fakturačních slev.
4. V okně **Karta zákazníka** zvolte **Fakturační slevy**. **Zákazník Otevře se okno Fakturační slevy**
5. V poli **Kód měny** vložte kód pro měnu, kterou chcete použít do podmínek fakturačních slev. Zanechte prázdné pole k nastavení podmínek fakturačních slev v CZK.
6. V poli **Minimální částka** vložte minimální částku, která musí být na faktuře, aby byla sleva uplatněna.
7. V poli **Sleva %** vložte procentuální fakturační slevu celkové částky.
8. Opakujte kroky 5 až 7 pro každou měnu, pokud zákazník obdrží různé faktury.

Fakturační sleva je nyní nastavena a přiřazena dotyčnému zákazníkovi.  Když si vyberete kód zákazníka v okně **Fakturační slevy pole Kód** na ostatních kartách zákazníků, stejná fakturační sleva je přiřazena těmto zákazníkům.

## <a name="see-also"></a>Viz také  
[Nastavení prodeje](sales-setup-sales.md)  
[Správa prodeje](sales-manage-sales.md)

