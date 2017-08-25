---
title: "Návod: Vyhledání zaúčtovaných dokladů bez záznamů došlého dokladu"
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

# <a name="how-to-find-posted-documents-without-incoming-document-records"></a>Návod: Vyhledání zaúčtovaných dokladů bez záznamů došlého dokladu
Z okna **Účetní osnova** a **Položky hlavní knihy** můžete pomocí vyhledávací funkce vyhledat položky hlavní knihy pro zaúčtované nákupní a prodejní doklady, které nemají záznamy došlého dokladu a poté centrálně odkazovat na existující záznamy nebo vytvářet nové doklady s přiloženými soubory.

## <a name="to-find-posted-documents-without-incoming-document-records"></a>Vyhledání zaúčtovaných dokladů bez záznamů došlého dokladu
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účetní osnova** a pak vyberte související odkaz.
2. Vyberte řádek pro finanční účet, kde jsou položky hlavní knihy, které chcete zaúčtovat jako nákupní a prodejní doklady bez záznamů došlého dokladu a pak zvolte akci **Zaúčtovat doklad bez došlého dokladu**.
3. Alternativně zvolte akci **Položky knihy**.
4. V okně **Položky hlavní knihy** zvolte akci **Zaúčtovat doklady bez došlých dokladů**.

Okno **Zaúčtované doklady bez došlých dokladů** otevře zaúčtované nákupní a prodejní doklady bez záznamů došlého dokladu reprezentovány položkami hlavní knihy ve finančním účtu, který pro toto okno otevřete. Okno může ukázat maximum 1000 řádků. Ve výchozím nastavení pole **Filtr data** omezuje řádky na položky s daty zveřejnění od začátku účetního období do pracovního data.

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a>Připojení nalezených dokladů k existujícím záznamům došlého dokladu
1. V okně **Zaúčtované doklady bez došlého dokladu** vyberte řádek pro zaúčtovaný doklad, který chcete připojit k existujícímu záznamu došlého dokladu a pak zvolte akci **Vybrat došlý doklad**.
2. V okně **Došlé doklady** vyberte záznam došlého dokladu, který chcete připojit k zaúčtovanému dokladu a pak zvolte tlačítko **OK**.
3. V okně **Zaúčtované doklady bez došlého dokladu** vyberte záznam došlého dokladu, který je nyní připojen k zaúčtovanému dokladu, jak můžete vidět v okně s fakty **Soubory došlého dokladu**.

Pokud v okně **Došlé doklady** neexistuje příslušný záznam došlého dokladu, můžete jej vytvořit. Další informace naleznete v tématu [Návod: Vytvoření záznamů došlého dokladu](across-how-create-income-document-records.md).

## <a name="see-also"></a>Viz také  
[Proces Došlých dokladů](across-process-income-documents.md)  
[Došlé doklady](across-income-documents.md)  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Práce s Dynamics NAV](ui-work-product.md)

