---
title: "Návod: Vyřazení nebo odebrání DM"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 795bb23e7c0b46be095b2bbdfe7705b3d7b1e4ee
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-dispose-of-or-retire-fixed-assets"></a>Návod: Vyřazení nebo odebrání DM
Při prodeji nebo jiném vyřazování DM musí být hodnota vyřazení zaúčtována k výpočtu a zaznamenání zisku nebo ztrát. Vyřazená položka musí být poslední položkou zaúčtovanou pro dlouhodobý majetek. Pro částečné vyřazení DM můžete zaúčtovat více než jednu vyřazenou položku. Všechny zaúčtované částky musí činit částku Dal.

 **POZNÁMKA**: Pokud obchodujete s dlouhodobým majetkem, musíte zaznamenat jak prodej starého majetku (vyřazení), tak i nákup nového (pořízení). Další informace naleznete v [Návod: Pořízení DM](fa-how-acquire.md).

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a>Zaúčtování vyřazeného DM z finančního deníku  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Finanční deník DM** a pak vyberte související odkaz.  
2. Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
3. V poli **Typ zaúčtování DM** vyberte **Likvidace**.
4. Zvolte **Vložení zůstatku DM Akce Účet**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování vyřazeného.

    **Poznámka**: Krok 4 funguje pouze v případě, že jste nastavili následující: V okně **Karta zúčtovací skupiny DM** pro zaúčtování skupin DM, pole **Likvidační účet** obsahuje účet MD hlavní knihy a **Vyřazení Bal.. Pole Účet** obsahuje účet hlavní knihy, na který chcete zaúčtovat zůstatkové položky za účelem zhodnocení. Další informace naleznete v části "Nastavení skupin zaúčtování DM“[Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).
5. Zvolte akci **Zaúčtovat**. 

Pokud chcete prodat nebo vyřadit část DM, musíte rozdělit majetek před tím, než zaznamenáte transakci vyřazení. Další informace naleznete v [Návod: Převod, rozdělení nebo kombinace DM](fa-how-trans-split-combine.md).

## <a name="to-view-disposal-ledger-entries"></a>Zobrazení vyřazených položek z knihy  
Při prodeji nebo vyřazení DM je hodnota vyřazení zaúčtována do hlavní knihy, kde můžete zobrazit výsledek.   

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.  
2. Vyberte dlouhodobý majetek, u kterého chcete zobrazit položky a pak vyberte akci **Odpisové knihy**.
3. Vyberte odpisovou knihu, kde chcete zobrazit položky a poté vyberte akci **Knihovní položky**.
4. Vyberte řádek s **Vyřazení** v poli **Kategorie účtování DM** a pak zvolte akci **Navigovat**.  
5. V okně **Navigace** vyberte řádky položky hlavní knihy a pak zvolte akci **Ukázat**.
Okno **Položky hlavní knihy** se otevře tam, kde můžete vidět položky, které vedly k vyřazení.

## <a name="see-also"></a>Viz také
[Správa DM](fa-manage.md)  
[Nastavení DM](fa-setup.md)  
[Finance](finance-setup.md)  
[Vítejte v Dynamics NAV](across-get-started.md)

