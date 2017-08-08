---
title: "Návod: Vyhledání zaúčtovaných dokumentů bez záznamů příchozího dokumentu"
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
ms.openlocfilehash: eb65922decc86ca6834cae4cf46c6f2ff492e29c
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-find-posted-documents-without-incoming-document-records"></a>Návod: Vyhledání zaúčtovaných dokumentů bez záznamů příchozího dokumentu
Z okna **Účtová osnova** a **Položek hlavní knihy** můžete pomocí vyhledávací funkce vyhledat položky hlavní knihy pro zaúčtované nákupní a prodejní dokumenty, které nemají záznamy příchozího dokumentu a poté centrálně odkazovat na existující záznamy nebo vytvářet nové dokumenty s přiloženými soubory.

## <a name="to-find-posted-documents-without-incoming-document-records"></a>Vyhledání zaúčtovaných dokumentů bez záznamů příchozího dokumentu
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účtová osnova** a pak vyberte související odkaz.
2. Vyberte řádek pro finanční účet, kde jsou položky hlavní knihy, které chcete zaúčtovat jako nákupní a prodejní dokumenty bez záznamů příchozího dokumentu a pak zvolte akci **Zaúčtovat dokumenty bez příchozího dokumentu**.
3. Alternativně zvolte akci **Položky knihy**.
4. V okně **Položky hlavní knihy** zvolte akci **Zaúčtovat dokumenty bez příchozího dokumentu**.

Okno **Zaúčtované dokumenty bez příchozího dokumentu** otevře zaúčtované nákupní a prodejní dokumenty bez záznamů příchozího dokumentu reprezentovány položkami hlavní knihy ve finančním účtu, který pro toto okno otevřete. Okno může ukázat maximum 1000 řádků. Ve výchozím nastavení pole **Filtr data** omezuje řádky na položky s daty zveřejnění od začátku účetního období do data práce.

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a>Připojení nalezených dokumentů k existujícím záznamům příchozího dokumentu
1. V okně **Zaúčtované dokumenty bez příchozího dokumentu** vyberte řádek pro zaúčtovaný dokument, který chcete připojit k existujícímu záznamu příchozího dokumentu a pak zvolte akci **Vybrat příchozí dokument**.
2. V okně **Příchozí dokumenty** vyberte záznam příchozího dokumentu, který chcete připojit k zaúčtovanému dokumentu a pak zvolte tlačítko **OK**.
3. V okně **Zaúčtované dokumenty bez příchozího dokumentu** vyberte záznam příchozího dokument, který je nyní připojen k zaúčtovanému dokumentu, jak můžete vidět v okně s fakty **Soubory příchozího dokumentu**.

Pokud v okně **Příchozí dokumenty** neexistuje příslušný záznam příchozího dokumentu, můžete jej vytvořit. Další informace naleznete v [Návod: Vytvořit záznamy příchozího dokumentu](across-how-create-income-document-records.md).

## <a name="see-also"></a>Viz také  
[Proces Příchozího dokumentu](across-process-income-documents.md)  
[Příchozí dokumenty](across-income-documents.md)  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Práce s Dynamics NAV](ui-work-product.md)

