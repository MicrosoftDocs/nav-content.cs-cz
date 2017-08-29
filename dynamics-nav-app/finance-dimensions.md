---
title: Dimenze
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: a1b38e74717e87bea6efb46f8f4e5236b6ec4e64
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

#<a name="dimensions"></a>Dimenze
Dimenze jsou data, která přidáváte do hodnot ke kategorizaci pro analýzu. Například můžete mít dimenze, které indikují, ze kterého projektu či oddělení položka pochází.
Pak můžete použít dimenze namísto nastavení oddělených účtů hlavní knihy pro každé oddělení či projekt. To vám umožňuje mít bohaté informace pro analýzu v datech bez nutnosti použití komplikované účtové osnovy.
Můžete specifikovat neomezený počet dimenzí s neomezeným počtem hodnot dimenzí.  

Například nastavíte dimenzi zvanou *Oddělení* a použijete tuto dimenzi a hodnotu dimenze, když účtujete prodejní doklady. Pak můžete získat data business intelligence, například které položky byly prodány kterým oddělením.
Čím více dimenzí nastavíte a používáte, tím na detailnějších sestavách můžete založit Vaše obchodní rozhodnutí. Například jednotlivá položka prodeje může zahrnout více informací o dimenzích, na jaký účet byla položka prodeje zaúčtována, kde byla položka prodána, kdo ji prodal, jaká typ zákazníka provedl nákup.  

## <a name="using-dimensions"></a>Použití dimenzí
V dokladu, jakým je prodejní objednávka, můžete přidat informace o dimenzi pro oba řádky jednotlivého dokladu a dokladu jako takového. Například v okně **Prodejní objednávka** můžete zadat hodnoty dimenze pro první dvě zkratky dimenzí přímo na dokumentu a můžete přidat další informace, pokud zvolíte tlačítko **Dimenze**.  
Pokud místo toho pracujete v deníku, můžete také přidat informace o dimenzi do hodnoty stejným způsobem, pokud jste nastavili zkratku dimenzí jako pole přímo na řádcích deníku.  
Můžete nastavit výchozí dimenze pro účty nebo typy účtů tak, aby dimenze a hodnoty dimenzí byly vyplněny automaticky.  

## <a name="dimension-sets"></a>Sady dimenzí
Sada dimenzí je jedinečná kombinace hodnot dimenzí. Ukládá se jako sada hodnot dimenzí v databázi. Každá hodnota sady dimenzí představuje jednotlivou hodnotu dimenze. Sada dimenzí je identifikována běžným ID sady dimenzí, které je připojeno ke každé hodnotě sady dimenzí, která patří do sady dimenzí.  

Když vytvoříte nový řádek deníku, hlavičku dokumentu nebo řádek dokumentu, můžete specifikovat kombinaci hodnot dimenzí. Namísto explicitně ukládané každé hodnoty dimenze v databázi, ID sady dimenze je přiřazeno k řádku deníku, hlavičce dokumentu, nebo řádku dokumentu ke specifikaci sady dimenze.  

## <a name="see-also"></a>Viz také
[Finance](finance-setup.md)  
[Nastavení dimenzí](finance-setup-setup-dimensions.md)  

