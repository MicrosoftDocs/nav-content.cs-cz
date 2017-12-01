---
title: "Přehled úloh k rozdělení nákladů a výnosů"
description: "Popisuje úlohy při přidělování položky do finančního deníku několika účtům při účtování deníku."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fdb03090dc9ba024d84a175e313f7d530bd0feae
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-allocate-costs-and-income"></a>Návod: Rozdělte náklady a výnosy
Můžete rozdělit záznam při účtování ve finančním deníku na několik různých účtů. Rozdělení může být provedeno třemi různými způsoby:

* Množství
* Procento (%)
* Částka

Funkci rozdělení lze použít v periodických finančních denících a denících dlouhodobého majetku.
<!--You can also distribute the cost or revenue of a line to an intercompany partner when you post a sales or purchase document. When you post the document, a line will be posted in your general journal, and a corresponding line will be created in the intercompany outbox.-->

Následující procedury popisují, jak připravit přidělování nákladů do opakovaných finančních deníků definováním klíčů přidělení. Když jsou definovány klíče přidělení, dokončíte a publikujete deník jako každý jiný opakovaný finanční deník. Pro další informace se podívejte na [Práce s finančními deníky](ui-work-general-journals.md).

## <a name="to-set-up-allocation-keys"></a>Nastavení rozdělovacích klíčů
Můžete rozdělit záznam při účtování v opakovaném finančním deníku na několik různých účtů. Rozdělení může být provedeno podle množství, procent nebo částky.
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Opakovaný finanční deník** a pak vyberte související odkaz.
2. Zvolte pole **Název listu** a otevřete okno **Listy finančního deníku**.
3. Můžete buď upravit rozdělení v existující dávce v seznamu nebo vytvořit novou dávku s přiděleními.
   * Chcete-li vytvořit novou dávku, zvolte akci **Nový** a přejděte k dalšímu kroku.
   * Chcete-li změnit rozdělení existujícího deníku, vyberte deník a přejděte ke kroku 7.    
4. Do pole **Název** zadejte název dávky, například ČIŠTĚNÍ. Do pole **Popis** zadejte popis, například Deník výdajů za úklid.
5. Až budete hotoví, zavřete okno. Otevře se nový prázdný periodický deník.
6. Vyplňte pole na řádku.
7. Zvolte akci **Rozdělení**.
8. Přidejte řádek pro každé rozdělení. Buď musíte vyplnit pole **Rozdělení %**, **Rozdělené množství** nebo **Částka**. Musíte také vyplnit pole **Číslo účtu**, a pokud rozdělujete transakci mezi více globálních dimenzí i pole globální dimenze.
9. Pokud na řádek zadáte procento, částka v poli **Částka** se vypočítá automaticky. Tyto částky mají opačné znaménko oproti celkové částce v poli **Částka** v periodickém deníku.
10. Po zadání řádků rozdělení vyberte **OK** k vrácení se do okna **Periodický finanční deník**. Pole **Částka rozdělení (CZK)** je vyplněno a odpovídá poli **Částka**.
11. Zaúčtovat deník.

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a>Změna rozdělovacího klíče, který již byl nastaven.
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Opakovaný finanční deník** a pak vyberte související odkaz.
2. V okně **Periodický finanční deník** vyberte deník s rozdělením.
3. Vyberte řádek s rozdělením a poté zvolte akci **Rozdělení**.
4. Změňte pole a poté klepněte na tlačítko **OK**.

## <a name="see-also"></a>Viz také
[Uzavřít roky a období.](year-close-years-periods.md)  
[Práce s finančními deníky](ui-work-general-journals.md)    
[Účtování dokladů a deníků](ui-post-documents-journals.md)    
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

