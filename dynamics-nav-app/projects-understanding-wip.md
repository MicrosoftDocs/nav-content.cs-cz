---
title: "Porozumění metodám WIP"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f21357897dd730d96db7abab469d5958c6fe117c
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="understanding-wip-methods"></a>Porozumění metodám WIP

[!INCLUDE[navnow](includes/navnow_md.md)] podporuje následující metody výpočtu a zaznamenávání hodnoty práce v procesu.

|Metoda WIP |Vzorec výpočtu |Popis výpočtu|
|-----------|--------------------|-----------------------|
|Hodnota ceny|Uznané příjmy = fakturační zaúčtovaná cena<br /><br /> Odhadované celkové náklady = Celková cena fakturace x Rozpočtové poměrné náklady<br /><br /> Náklady WIP = \( Procento dokončení - Fakturované % \) x Odhadované celkové náklady<br /><br /> Procento dokončení = Celkové náklady na využití / Celkové náklady na rozpočet<br /> Fakturované % = fakturační zaúčtovaná cena<br /><br /> Fakturační celková cena uznaných nákladů = Celkové náklady na využití - WIP|Výpočet hodnoty nákladů začínají výpočtem hodnoty toho, co bylo poskytnuto, přičemž část odhadovaných celkových nákladů vychází z procentního podílu dokončení. Fakturované náklady jsou odečteny tím, že se část odhadovaných celkových nákladů na základě fakturovaného procenta odečte.<br /><br /> Tento výpočet vyžaduje, aby celková cena fakturace, celková cena rozpočtu a celkové náklady na rozpočet byly správně zadány pro celou práci.|
|Náklady na prodej|Uznané příjmy = fakturační zaúčtovaná cena<br /><br /> Uznané náklady = Celkové náklady rozpočtu x Fakturované procento<br /><br /> Fakturované % = fakturační zaúčtovaná cena / fakturační celková cena<br /><br /> \(Fakturované % existuje jako sloupec na řádcích úloh\)<br /><br /> Náklady WIP = Celkové náklady na využití - uznané náklady|Výpočet nákladů na prodej začíná výpočtem uznaných nákladů. Náklady jsou účtovány proporcionálně na základě celkových nákladů na rozpočet.<br /><br /> Tento výpočet vyžaduje, aby celková cena fakturace a celkové náklady byly správně zadány pro celou práci.|
|Prodejní hodnota|Uznané náklady = Celkové náklady na využití<br /><br /> Uznané příjmy = Celková cena za použití x Poměr očekávané fakturace<br /><br /> Obnova nákladů % = Celková cena fakturace / celková cena rozpočtu<br /><br /> Prodejní WIP = Uznané prodeje - fakturační zaúčtovaná cena|Výpočty prodejní hodnoty vykazují příjmy úměrně na základě celkových nákladů na využití a očekávaného poměru návratnosti nákladů.<br /><br /> Tento výpočet vyžaduje, aby celková cena fakturace a celková cena rozpočtu byly správně zadány pro celou práci.|
|Procento dokončení|Uznané náklady = Celkové náklady na využití<br /><br /> Uznané příjmy = Celková cena fakturace x Procento dokončení<br /><br /> Procento dokončení = Celkové náklady na využití / celkové náklady na rozpočet<br /><br /> \(Uváděno jako "Dokončení nákladů %" na řádcích úloh\)<br /> Prodejní WIP = Uznané prodeje - fakturační zaúčtovaná cena|Procentuální výpočty vykazují výnosy poměrně podle procentuálního podílu dokončení, tj. celkových nákladů na užívání versus rozpočtových nákladů.<br /><br /> Tento výpočet vyžaduje, aby celková cena fakturace a celkové náklady byly správně zadány pro celou práci.|
|Dokončená smlouva|WIP částka = WIP cena = Využití \( celkových nákladů\)<br /><br /> Prodejní částka WIP = Fakturační \( zaúčtovaná cena\)|Dokončená smlouva neuznává příjmy a náklady, dokud není dokončena práce. Možná toto budete chtít, když máte vysokou nejistotu ohledně odhadů nákladů a příjmů na práci.<br /><br /> Veškeré využití je zaúčtováno do účtu nákladů WIP \( aktivum \) a všechny fakturované tržby jsou účtovány do účtu fakturovaného prodeje WIP \( odpovědnost \), dokud není práce dokončena.|

## <a name="see-also"></a>Viz také
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Správa prodeje](sales-manage-sales.md)      
[Práce s [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md)  

