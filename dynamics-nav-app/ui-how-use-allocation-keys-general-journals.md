---
title: "Návody: Použití rozdělovacích klíčů ve finančních denících."
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: ca21d9d129dbc98d75371d1b2b7a0ffad4aa2848
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

#  <a name="how-to-use-allocation-keys-in-general-journals"></a>Návody: Použití rozdělovacích klíčů ve finančních denících.
Když zaúčtováváte finanční deník, můžete přidělit  položku několika různým účtům.  Rozdělení může být provedeno podle množství, procent nebo částky.

## <a name="to-set-up-allocation-keys"></a>Nastavení rozdělovacích klíčů 
1. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Periodický finanční deník**, a pak zvolte související odkaz.
2. Zvolte pole **Název dávky** a otevřete okno **Dávky finančního deníku**.
3. Můžete buď upravit rozdělení v existující dávce v seznamu nebo vytvořit novou dávku s přiděleními.
  * Chcete-li vytvořit novou dávku, zvolte akci **Nové** a přejděte k dalšímu kroku.
  * Chcete-li změnit rozdělení existujícího deníku, vyberte deník a přejděte ke kroku 7.    
4. Do pole **Název** zadejte název dávky, například ČIŠTĚNÍ. Do pole **Popis** zadejte popis, například Deník výdajů za úklid.
5. Až budete hotoví, zavřete okno. Otevře se nový prázdný periodický deník. 
6. Vyplňte pole na řádku.
7. Zvolte akci **Rozdělení**. 
8. Přidejte řádek pro každé rozdělení. Buď musíte vyplnit pole **Rozdělení %**, **Rozdělené množství** nebo **Částka**. Musíte také vyplnit pole **Číslo účtu** a pokud rozdělujete transakci mezi více globálních dimenzí i pole globální dimenze.
9. Pokud na řádek zadáte procento, částka v poli **Částka** se vypočítá automaticky. Tyto částky mají opačné znaménko oproti celkové částce v poli **Částka** v periodickém deníku.
10. Po zadání řádků rozdělení vyberte **OK** k vrácení se do okna **Periodický finanční deník**. Pole **Částka rozdělení (CZK)** je vyplněno a odpovídá poli **Částka**.
11. Zaúčtovat deník.

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a>Změna rozdělovacího klíče, který již byl nastaven.
1. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Periodický finanční deník**, a pak zvolte související odkaz.
2. V okně **Periodický finanční deník** vyberte deník s rozdělením.
3. Vyberte řádek s rozdělením a poté zvolte akci **Rozdělení**.
4. Změňte příslušná pole a zavřete okno.

## <a name="see-also"></a>Viz také
[Práce s finančními deníky](ui-work-general-journals.md)  
[Zaúčtovat doklady a deníky](ui-post-documents-journals.md)




