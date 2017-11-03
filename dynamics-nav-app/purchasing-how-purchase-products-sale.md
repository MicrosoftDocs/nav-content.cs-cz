---
title: "Vytvoření nákupní faktury z prodejní faktury k nákupuju zboží pro prodej"
description: "Z prodejní faktury pro nákup produktů můžete vytvořit nákupní fakturu pro dodavatele."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supply planning, sales demand, replenish
ms.date: 05/16/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a6380570c9fb2bc5880bf531b4311fbf6e9cf4ec
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-purchase-items-for-a-sale"></a>Návody: Nákup zboží pro prodej
Z prodejních objednávek a prodejních faktur můžete použít funkci k rychlému vytvoření nákupních dokumentů pro chybějící množství zboží, které je potřebné pro prodej. Můžete použít dvě různé funkce odvíjející se od typu dokumentu.
|Funkce|Popis|
|--------|-----------|
|**Vytvořte nákupní objednávku**|Z prodejní objednávky, funkce vytvoří nákupní objednávku pro každého dodavatele daného zboží na prodejní objednávce Můžete upravit nakupované množství předtím, než vytvoříte nákupní fakturu. Je navrhováno pouze množství k prodeji.
|**Vytvořte nákupní fakturu**|Z prodejní objednávky a z prodejní faktury funkce vytvoří nákupní fakturu pro vybraného dodavatele a všechny řádky nebo zvolené řádky na prodejním dokumentu. Zde je navrhováno celé množství|

## <a name="to-create-one-or-more-purchase-orders-from-a-sales-order"></a>Vytvoření jedné nebo více nákupních objednávek z prodejní objednávky
Pro vytvoření nákupní objednávky pro každe nedostupné množství zboží na prodejní objednávce použijte funkci **Vytvořit nákupní objednávky**.

1. Na domovské stránce vyberte dlaždici **Průběžné prodejní objednávky**.
2. otebřete prodejní objednávku, kterou chcete nakupovat zboží.
3. Zvolte akci **Vytvořit nákupní objednávku**.

    Otevře se okno **Vytvořit nákupní objednávku** zobrazující řádek pro každé rozdílné zboží na prodejní objednávce. Do výchozího nastavení jsou zobrazeny řádky pro plně dostupné prodejní množství a nedostupné prodejní množství (šedě). Můžete zvolit **Zobrazit nedostupné** k zobrazení řádků s pouze nedostupným prodejním množstvím.

    Pole **Množství k nákupu** obsahuje ve výchozím nastavení nedostupné prodejní množství. 
4. K nákupu jiného množství než nedostupného, upravte hodnotu v poli **Množství k nákupu**.

    > [!NOTE]  
>   Políčko **Množství k nákupu** můžete také změnit na šedých řádcích, přestože představují plně dostupné prodejní množství.
5. Zvolte tlačítko **OK**.

    Pro každého dodavatele zboží je vytvovřena nákupní objednávka včetně změn množství, které jste provedli na prodejní objednávce.
7. Pokračujte ve zpracování nákupní objednávky / objednávek, například úpravou nebo přidáním nákupních objednávkových řádků. Další informace naleznete v tématu [Návod: Zaznamenávání nákupů.](purchasing-how-record-purchases.md).


## <a name="to-create-a-purchase-invoice-from-a-sales-order-or-sales-invoice"></a>Vytvoření nákupní faktury z prodejní objednávky nebo prodejní faktury
Chcete-li vytvořit jednu nákupní fakturu pro jeden nebo více řádků v prodejním dokladu, vyberte nejprve dodavatele, od kterého chcete nakupovat a použijte funkci **Vytvořit nákupní fakturu fakturu**.

> [!NOTE]  
>   Tato funkce vytvořte nákupní fakturu pro stejné množství zboží jako na vybraném prodejním dokumentu. Chcete-li změnit nakupované množství, musíte nejdříve vytvořit nákupní fakturu.  

1. Na domovské stránce vyberte dlaždici **Pokračující prodejní faktury**.
2. Otevřete prodejní fakturu, kterou chcete nakupovat zboží.
3. Vyberte jeden nebo více řádků prodejních faktur, které chcete použít na nákupní faktuře. Chcete-li použít všechny řádky prodejních faktur, vyberte buď všechny z nich nebo nevybírejte žádné řádky.
4. Zvolte akci **Vytvořit nákupní fakturu**.
5. Vyberte možnost **Všechny řádky** nebo **Vybrané řádky** a potom klepněte na tlačítko **OK**.  
6. V seznamu dodavatelů, který se zobrazí, vyberte dodavatele, od kterého chcete nakupovat zboží a klepněte na tlačítko **OK**.

    Vytvoří se nákupní faktura, která obsahuje jeden nebo více řádků na prodejní faktuře.
7. Pokračujte ve zpracování nákupní faktury například úpravou nebo přidáním nákupních fakturačních řádků. Další informace naleznete v tématu [Návod: Zaznamenávání nákupů.](purchasing-how-record-purchases.md).

## <a name="see-also"></a>Viz také
[Nákup](purchasing-manage-purchasing.md)  
[Návody: Zaznamenávání nákupu](purchasing-how-record-purchases.md)  
[Návody: Prodejní faktury.](sales-how-invoice-sales.md)  
[Návody: Registrace nového dodavatele](purchasing-how-register-new-vendors.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

