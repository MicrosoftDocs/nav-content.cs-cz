---
title: "Zadání výběru tiskáren pro sestavy"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 56a5c1428651162293e56d71e2369fe55d291594
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---
    
# <a name="specify-printer-selection-for-reports"></a>Zadání výběru tiskáren pro sestavy
Můžete nastavit sestavy tak, aby byly vytištěny na konkrétní tiskárně. Níže jsou uvedeny některé způsoby použití výběru tiskárny: 

- Můžete tisknout sestavy se speciálními hlavičkami společnosti. 
- Můžete tisknout sestavy na různě velké papíry.
- Můžete vytisknout sestavy na výchozí tiskárně konkrétního zaměstnance.

V okně **Výběr tiskárny** můžete nastavit různé hodnoty pro získání odlišného výstupu. Pokud nastavíte konkrétní výběr tiskárny, bude mít přednost před obecnějším výběrem tiskárny. Můžete například nastavit výběr tiskárny, který obsahuje hodnoty v poli **ID uživatele**, **ID sestavy** a **Název tiskárny**. Tato volba tiskárny má přednost před volbou tiskárny s prázdnými položkami v polích **ID uživatele**, nebo **ID sestavy**. 

Následující tabulka popisuje kombinaci hodnot určených pro nastavení výběru tiskárny pro sestavu.

|K                                                 |Nastavení následujících hodnot                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|Vytiskněte sestavu na konkrétní tiskárně pro všechny uživatele |Určete hodnoty v polích **ID sestavy** a **Název tiskárny** a pole **ID uživatele** nechejte prázdné.|
|Vytiskněte všechny sestavy na konkrétní tiskárně pro konkrétního uživatele|Zadejte hodnoty v polích **ID uživatele** a **Název tiskárny** a pole **ID sestavy** nechejte prázdné.|
|Nastavte výchozí tiskárnu pro všechny sestavy|Zadejte hodnotu v poli **Název tiskárny** a pole **ID uživatele** a **ID sestavy** nechte prázdné.|
|Vytiskněte konkrétní sestavu na výchozí tiskárně uživatele|Zadejte hodnotu v poli **ID sestavy** a pole **Název tiskárny** a **ID uživatele** nechejte prázdné.|
|Vytiskněte konkrétní sestavu na konkrétní tiskárně pro konkrétního uživatele|Určete hodnoty ve všech třech polích.|

## <a name="see-also"></a>Viz také
[Práce s Dynamics NAV](ui-work-product.md)

