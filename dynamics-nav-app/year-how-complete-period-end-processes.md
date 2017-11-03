---
title: "Volitelné aktivity pro uzavírání období"
description: "Toto téma popisuje volitelné procesy a činnosti pro uzavírání účetních období v Dynamics NAV."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, aging, creditor payments, vendor payments
ms.date: 06/19/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ca22e72552c69d3bcb0b85101b586796ff026896
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="overview-of-tasks-to-close-accounting-periods"></a>Přehled úkolů pro uzavření účetních období
[!INCLUDE[d365fin](includes/d365fin_md.md)] vás nenutí uzavřít období, avšak existuje mnoho aktivit týkajících se ukončení období, které mohou být v pokud chcete. Toto téma poskytuje přehled o volitelných procesech a aktivitách pro uzavírací období.  

## <a name="general-ledger"></a>Hlavní kniha
* Určete systémové a uživatelské období zaúčtování.  

    Toto určuje data, mezi kterými je povoleno zaúčtovat. V závislosti na vaší firmě budete chtít povolit přidávání příspěvků na začátku nebo do konce. Další informace naleznete v [Návod: Specifikovat účetní období](finance-how-specify-posting-periods.md).  
* Proveďte všechny potřebné úpravy v hlavní knize.  
* Aktualizujte a zaúčtujte periodické deníky.  
  <!--* Process Consolidations-->
* Spusťte účetní schémata následovně:  
  * Otevřete okno **Účetní schéma** a zvolte akci **Tisk**.  

## <a name="sales-and-receivables"></a>Prodej a pohledávky
* Zaúčtujte všechny objednávky, faktury, dobropisy a objednávky prodejní vratky.  
* Zaúčtujte všechny deníky přijaté hotovosti.  
* Aktualizujte a zaúčtujte periodické deníky, které se vztahují k prodeji a pohledávkám.  
* Odsouhlaste pohledávky s hlavní účetní knihou.  
* Spusťte dávkovou úlohu **Odstranit fakt. prod. objednávky**.  

## <a name="purchases-and-payables"></a>Nákupy a závazky
* Zaúčtujte všechny objednávky, faktury, dobropisy a pobjednávky prodejní vratky.  
* Zaúčtujte všechny deníky plateb.  
* Aktualizujte a zaúčtujte periodické deníky, které se vztahují k nákupům a závazkům.  
* Spusťte sestavu **Splatné závazky** a odsouhlaste účty závazků s hlavní knihou.  
* Spusťte dávkovou úlohu **Odstranit fakt. nák. objednávky** .  

Dlouhodobý majetek
* Všechny náklady na údržbu byly zveřejněny prostřednictvím časopisů nebo faktur s pevnými částkami.
* Zaúčtovat adjustace.
* Zaúčtovat ocenění.
* Zaúčtovat odpisy.
* Aktualizujte a publikujte opakující se deník dlouhodobého majetku.

Mezipodnikový
* Proces mezipodnikových transakcí

## <a name="calculate-and-process-sales-tax"></a>Vypočítat a zpracovat prodejní daň
* Dokončete daňové výkazy.  

## <a name="see-also"></a>Viz také
[Uzavřít roky a období.](year-close-years-periods.md)  
[Uzavřít knihy](year-close-books.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

