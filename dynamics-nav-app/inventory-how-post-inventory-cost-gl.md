---
title: "Návody: Zaúčtovat náklady na zásoby do hlavní knihy"
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
ms.openlocfilehash: 59815db9c7b435ff585e1174b570029a360dea6e
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-post-inventory-costs-to-the-general-ledger"></a>Návody: Zaúčtovat náklady na zásoby do hlavní knihy   
Při zadávání transakcí zásob, jako jsou prodejní dodávky, nákupní faktury nebo úpravy zásob, změněné množství a náklady zaznamenány jsou zaznamenány v položkách zboží a položkách. Chcete-li odrážet tuto změnu hodnoty zásob ve vašich finančních knihách, musíte zaúčtovat náklady k souvisejícím účtům zásob v hlavní knize.

Náklady na zásoby můžete vyúčtovat do hlavní knihy dvěma způsoby:

- Automaticky tak, aby náklady na zásoby byly zaúčtovány do hlavní knihy pokaždé, když zaúčtujete transakci zásob.
- Manuálně tak, že náklady na zásoby jsou zaúčtovány pouze do hlavní knihy při spuštění dávkové úlohy.


## <a name="to-post-inventory-costs-automatically"></a>K zaúčtování nákladů na zásoby automaticky
1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Nastavení zásob** a zvolte související odkaz.
2. V okně **Nastavení zásob** zaškrtněte políčko **Automatické účtování nákladů** 

Pro každou transakci nákladů, kterou zaúčtujete, jsou příslušné hodnoty zaúčtovány do účtu nákladů, účtu úprav a účtu NNPZ v hlavní knize.

Dokonce i když používáte automatické účtování nákladů, je třeba pravidelně provádět dávkovou úlohu Úpravit náklady - Položky zboží, abyste zajistili, že náklady na zboží budou předány příslušným odchozím transakcím, jako jsou prodeje nebo přenosy. To je zvláště důležité v situacích, kdy prodáváte zboží před fakturováním nákupu tohoto zboží.

Pokud dojde k chybě v nastavení dimenze při odesílání nákladů na zásoby do hlavní knihy, účtování se ukončí s chybou.

## <a name="to-post-inventory-costs-manually"></a>Chcete-li náklady na zásoby zaúčtovat ručně
1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Zaúčtovat náklady na zásoby do financí** a zvolte související odkaz.
2. Zaúčtovat náklady na zásoby do hlavní knihy ručně spuštěním dávkové úlohy. Při spuštění této dávkové úlohy se položky hlavní knihy vytvářejí na základě položek ocenění. Položky můžete zaúčtovat tak, aby byly shrnuty podle účtovací skupiny.

**Poznámka**: Při spuštění této dávkové úlohy může dojít k chybám souvisejícím s chybějícím nastavením nebo nekompatibilním nastavením dimenzí. Pokud dávková úloha narazí na chyby v nastavení dimenze, přepíše tyto chyby a použije dimenzi položky ocenění. Pro jiné chyby dávkové úlohy přeskočí účtování položek ocenění a seskupí je na konec sestavy v části s názvem "Přeskočené položky". Chcete-li tyto položky zaúčtovat, musíte opravit chyby.

Chcete-li zobrazit seznam chyb před spuštěním účtovací dávkové úlohy, můžete spustit **Zaúčtovat zásoby Náklady do financí - Test** sestava. Ve testovací sestavě jsou uvedeny všechny chyby, které se při testování vyskytly. Poté můžete chyby opravit a spustit dávkovou úlohu účtování nákladů na zásoby, aniž byste přeskočili jakékoli položky.

Pokud byste chtěli jednoduše získat přehled o tom, jaké hodnoty by mohly být účtovány do hlavní knihy, aniž by se skutečně provádělo účtování, můžete spustit dávkovou úlohu Zaúčtovat náklady zásob do financí bez toho, abyste skutečně účtovali hodnoty do hlavní knihy. To provedete zrušením zaškrtnutí políčka Zaúčtovat pole na stránce požadavku. Tímto způsobem při spuštění dávkové úlohy sestava zobrazí hodnoty, které jsou připraveny k zaúčtování do hlavní knihy, ale nejsou zaúčtovány.

## <a name="see-also"></a>Viz také
[Spravovat zásoby](inventory-manage-inventory.md)    
[Návody: Upravit cenu položky](inventory-how-adjust-item-costs.md)  
[Spravovat prodej](sales-manage-sales.md)  
[Správa nákupu](purchasing-manage-purchasing.md)

