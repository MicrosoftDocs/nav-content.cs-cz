---
title: "Vytvoření došlých dokladů z dokumentů"
description: "Můžete vytvořit záznam došlého dokladu jako například elektronické faktury a řízení úkolů OCR, eCommerce a výměny dokumentů."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, e-invoice, incoming document, OCR, ecommerce, document exchange, import invoice
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: fd8eba03f98d4d667a25639c1c958edf6936b0cb
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-incoming-document-records-directly-from-documents-and-entries"></a>Návody: Vytvoření záznamu došlého dokladu přímo z dokumentu nebo položek
Můžete ukládat externí obchodní doklady v [!INCLUDE[d365fin](includes/d365fin_md.md)] připojením souborů k souvisejícím záznamům došlého dokladu. Pokud se doklad jako třeba nákupní faktura nespustí jako záznam došlého dokladu, můžete stále vytvořit a připojit záznam došlého dokladu později. Soubory došlých dokladů můžete také připojit k zaúčtovaným nákupním a prodejním dokladům a k záznamům prodejců, zákazníků a položek hlavní knihy pomocí okna s fakty **Soubory došlého dokladu**, pro příklad okna **Účtované nákupní faktury** a **Položky dodavatelů**.

Z oken **Účtová osnova** a **Hlavní kniha položek** můžete použít vyhledávací funkci k nalezení položek hlavní knihy pro zaúčtování nákupních a prodejních dokladů, které nemají záznamy došlého dokladu a pak centrálně odkazovat na existující záznamy nebo vytvářet nové s připojenými soubory. Další informace naleznete v tématu [Návod: Nalezení zaúčtovaných dokladů bez záznamů došlého dokladu](across-how-find-posted-documents-without-income-document-records.md).

Následující procedura ukazuje návod, jak připojit soubor k existující nákupní faktuře, která nebyla vytvořena ze záznamu došlého dokladu a návod jak připojit soubor k položkám dodavatele. Připojení souboru k zaúčtovaným nákupním nebo prodejním dokladům funguje podobným způsobem.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-purchase-invoice"></a>Vytvoření a připojení záznamu došlého dokladu k nákupní faktuře
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nákupní faktury** a poté vyberte příslušný odkaz.
2. Vyberte řádek pro nákupní fakturu, kterou chcete připojit k souboru a pak zvolte akci **Vytvořit došlý doklad ze souboru**.
3. Alternativně, vyberte řádek pro nákupní fakturu, kterou chcete připojit k souboru a pak zvolte akci **Připojit soubor**.
4. V okně **Vložit soubor** vyberte soubor, který představuje daný došlý doklad a pak zvolte tlačítko **Otevřít**.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-vendor-ledger-entry"></a>Vytvoření a připojení záznamu došlého dokladu z položky dodavatele
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Položky dodavatele** a poté vyberte příslušný odkaz.
2. Vyberte řádek pro položku dodavatele, kterou chcete připojit k souboru a pak zvolte akci **Vytvořit došlý doklad ze souboru**.
3. Alternativně, vyberte řádek pro položku dodavatele, kterou chcete připojit k souboru a pak zvolte akci **Připojit soubor**.
4. V okně **Vložit soubor** vyberte soubor, který představuje daný došlý doklad a pak zvolte tlačítko **Otevřít**.

## <a name="to-remove-a-connection-from-an-incoming-document-record-to-a-posted-document"></a>Odebrání připojení ze záznamu došlého dokladu k zaúčtovanému dokladu
Můžete odebrat soubor připojený k nezaúčtovaným dokladům smazáním souvisejícího záznamu došlého dokladu. Pokud je doklad zaúčtovaný, pak musíte nejdřív odebrat připojení ze záznamu došlého dokladu.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Došlé doklady** a poté vyberte příslušný odkaz.
2. Vyberte řádek pro záznam došlého dokladu připojeného k zaúčtovanému dokladu, který chcete odebrat a pak zvolte akci **Odebrat odkaz k záznamu**.

Připojení zaúčtovaného dokladu je odebráno. Nyní můžete pokračovat v připojení dalšího záznamu došlého dokladu k zaúčtovanému dokladu, tak jak je popsáno v tomto tématu.

## <a name="see-also"></a>Viz také
[Proces Došlých dokladů](across-process-income-documents.md)  
[Došlé doklady](across-income-documents.md)  
[Nákup](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

