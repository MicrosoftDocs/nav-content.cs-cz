---
title: "Správa skladů"
description: "Popisuje, jak spravovat fyzické produkty, se kterými obchodujete, například manipulace s zásobami ve vašem skladu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: warehouse, stock
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 8b79bfd187b04e378180d699aa880e21cf8410c9
ms.contentlocale: cs-cz
ms.lasthandoff: 10/23/2017

---

# <a name="inventory"></a>Sklady
Pro každý fyzický produkt, s nímž obchodujete, musíte vytvořit kartu zboží typu **Zásoba**. Zboží, které zákazníkům nabízíte, ale nezachováváte v zásobách, můžete registrovat jako neskladované zboží, které není v zásobách, ale v případě potřeby převést na skladované zboží. Můžete zvýšit nebo snížit množství zboží v zásobách účtováním přímo do Položek zboží, např. po fyzickém počítání nebo pokud nechcete zaznamenat nákupy.

Zvýšení a snížení zásob se přirozeně také zaznamenává, když účtujete nákupní a prodejní doklady. Další informace naleznete v tématu [Návod: Záznam nákupů](purchasing-how-record-purchases.md), [Návod: Prodávání produktu](sales-how-sell-products.md) a [Návod: Fakturování prodeje](sales-how-invoice-sales.md). Přesuny mezi umístěními mění množství zásob ve skladech společnosti.   

Chcete-li zvýšit přehled o zboží a zlepšit vyhledávání, můžete kategorizovat zboží a dát jim atributy pro vyhledávání a řazení.

> [!NOTE]
> Fyzická manipulace se zbožím se označuje jako skladové činnosti. Další informace naleznete v tématu [Správa skladů](warehouse-manage-warehouse.md).

## <a name="inventory-reconciliation"></a>Sladění zásob
Při zaúčtování transakcí zásob, jako jsou prodejní dodávky, nákupní faktury nebo úpravy zásob, změněné náklady zboží jsou zaznamenány v položkách hodnot zboží. Chcete-li odrážet tuto změnu hodnot zásob ve vašich finančních knihách, náklady zásob jsou automaticky zaúčtovány k souvisejícím účtům zásob v hlavní knize. Pro každou transakci nákladů, kterou zaúčtujete, jsou příslušné hodnoty zaúčtovány do účtu nákladů, účtu úprav a účtu NNPZ v hlavní knize. Další informace naleznete v tématu [Návod: Odsouhlasení nákladů na zásoby do hlavní knihy](finance-how-to-post-inventory-costs-to-the-general-ledger.md).

I když jsou náklady na zásoby automaticky zaúčtovány do hlavní knihy, je stále nutné zajistit, aby náklady na zboží byly předány do související transakce odchozího prodeje, zejména v situacích, kdy prodáváte zboží před nákupní fakturou tohoto zboží. Toto se označuje jako úprava nákladů. Náklady zboží jsou automaticky upraveny, když zaúčtujete transakce zboží, ale můžete také upravovat náklady zboží ručně. Další informace naleznete v tématu [Návod: Upravení nákladů zboží](inventory-how-adjust-item-costs.md).

|Viz |také |
|---|----|
|Vytvoření karty zboží pro zásoby, ve kterých obchodujete.|[Návod: Registrace nového zboží](inventory-how-register-new-items.md)|
|Strukturujte nadřazené zboží, které prodáváte jako sady, které se skládají z komponentů nebo které sestavujete na objednávku nebo na sklad.|[Návod: Práce s kusovníky](inventory-how-work-BOMs.md)|
|Chcete-li zvýšit přehled o zboží a zlepšit vyhledávání pomocí kategorií.|[Návod: Kategorizace zboží](inventory-how-categorize-items.md)|
|Přiřaďte atributy zboží různých typů hodnot ke zboží a to vám pomůže uspořádat a najít zboží.|[Návod: Práce s atributy zboží](inventory-how-work-item-attributes.md)|
|Vytvořte karty neskladovaného zboží.|[Návod: Práce s neskladovaným zbožím](inventory-how-work-nonstock-items.md)|
|Proveďte fyzické počítání, proveďte záporné nebo pozitivní úpravy a změňte informace, například o umístění nebo číslo šarže na položky zboží.|[Návod: Počítat, upravovat a reklasifikovat zásoby](inventory-how-count-adjust-reclassify.md)|
|Prohlédněte si dostupnost zboží podle umístění, období, prodeje nebo nákupu nebo jejich použití na montážních nebo výrobních kusovnících.|[Návod: Návod: Zobrazení dostupnosti zboží](inventory-how-availability-overview.md)|
|Přenos zásob zboží mezi umístěním s objednávkovými transakcemi ke správě skladových aktivit nebo s deníkem přeřazení zboží.|[Návod: Přenos zásob mezi umístěním](inventory-how-transfer-between-locations.md)|
|Rezervní zásoby nebo příchozí zboží pro prodejní objednávky, nákupní objednávky, servisní objednávky, montážní objednávky nebo výrobní objednávky.|[Návod: Rezervní zboží](inventory-how-to-reserve-items.md)|
|Přiřaďte sériová čísla nebo čísla šarží do všech odchozích nebo příchozích řádků dokladu nebo řádků deníku, například pro sledování zboží v případě stažení.|[Návod: Práce se sériovými čísly a čísly šarží](inventory-how-work-item-tracking.md)|
|Zjistěte, kde bylo použito nějaké sériové nebo číslo šarže v dodavatelském řetězci například v situaci stažení.|[Návod: Sledování zboží](inventory-how-to-trace-item-tracked-items.md)|
|Správa obchodních operací v prodejních kancelářích, nákupních odděleních nebo kancelářích pro plánování provozu na více místech.|[Návod: Práce s centrem odpovědnosti](inventory-responsibility-centers.md)|

## <a name="see-also"></a>Viz také  
[Nákup](purchasing-manage-purchasing.md)  
[Prodej](sales-manage-sales.md)    
[Práce s [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](ui-work-product.md)  
[Obecné obchodní funkce](ui-across-business-areas.md)

##

