---
title: "Návod: Připojení a odpojení záznamů příchozího dokumentu z dokumentů a položek"
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
ms.openlocfilehash: fece4e6e38075db6d394c71418fda82a7aa082e1
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-connect-and-disconnect-incoming-document-records-from-documents-and-entries"></a>Návod: Připojení a odpojení záznamů příchozího dokumentu z dokumentů a položek
V aplikaci Dynamics NAV můžete ukládat externí obchodní dokumenty připojením souborů k souvisejícím záznamům příchozího dokumentu. Pokud se dokument jako třeba nákupní faktura nespustí jako záznam příchozího dokumentu, můžete stále vytvořit a připojit záznam příchozího dokumentu později. Soubory příchozích dokumentů můžete také připojit k zaúčtovaným nákupním a prodejním dokladům a k záznamům prodejců, zákazníků a položek hlavní knihy pomocí okna s fakty **Soubory příchozích dokumentů**, pro příklad okna **Účtované nákupní faktury** a **Položky dodavatelů**.

Z oken **Účtové osnovy** a **Hlavní knihy položek** můžete použít vyhledávací funkci k nalezení položek hlavní knihy pro zaúčtování nákupních a prodejních dokladů, které nemají záznamy příchozího dokumentu a pak centrálně odkazovat na existující záznamy nebo vytvářet nové s připojenými soubory. Další informace naleznete v [Návod: Nalezení zaúčtovaných dokumentů bez záznamů příchozího dokumentu](across-how-find-posted-documents-without-income-document-records.md).

Následující procedura ukazuje návod jak připojit soubor k existující nákupní faktuře, která nebyla vytvořena ze záznamu příchozího dokumentu a návod jak připojit soubor k položkám dodavatele. Připojení souboru k zaúčtovaným nákupním nebo prodejním dokumentům funguje podobným způsobem.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-purchase-invoice"></a>Vytvoření a připojení záznamu příchozího dokumentu k nákupní faktuře
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nákupní faktury** a pak vyberte související odkaz.
2. Vyberte řádek pro nákupní fakturu, kterou chcete připojit k souboru a pak zvolte akci **Vytvořit příchozí dokument ze souboru**.
3. Alternativně, vyberte řádek pro nákupní fakturu, kterou chcete připojit k souboru a pak zvolte akci **Připojit soubor**.
4. V okně **Vložit soubor** vyberte soubor, který představuje daný příchozí dokument a pak zvolte tlačítko **Otevřít**.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-vendor-ledger-entry"></a>Vytvoření a připojení záznamu příchozího dokumentu z položky dodavatele
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Položky dodavatele** a pak vyberte související odkaz.
2. Vyberte řádek pro položku dodavatele, kterou chcete připojit k souboru a pak zvolte akci **Vytvořit příchozí dokument ze souboru**.
3. Alternativně, vyberte řádek pro položku dodavatele, kterou chcete připojit k souboru a pak zvolte akci **Připojit soubor**.
4. V okně **Vložit soubor** vyberte soubor, který představuje daný příchozí dokument a pak zvolte tlačítko **Otevřít**.

## <a name="to-remove-a-connection-from-an-incoming-document-record-to-a-posted-document"></a>Odebrání připojení ze záznamu příchozího dokumentu k zaúčtovanému dokumentu
Můžete odebrat soubor připojený k nezaúčtovaným dokumentům smazáním souvisejícího záznamu příchozího dokumentu. Pokud je dokument zaúčtovaný, pak musíte nejdřív odebrat připojení ze záznamu příchozího dokumentu.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Příchozí dokumenty** a pak vyberte související odkaz.
2. Vyberte řádek pro záznam příchozího dokumentu připojeného k zaúčtovanému dokumentu, který chcete odebrat a pak zvolte akci **Odebrat odkaz k záznamu**.

Připojení zaúčtovaného dokumentu je odebráno. Nyní můžete pokračovat v připojení dalšího záznamu příchozího dokumentu k zaúčtovanému dokumentu jako je popsán v tomto tématu.

## <a name="see-also"></a>Viz také  
[Proces příchozích dokumentů](across-process-income-documents.md)  
[Příchozí dokumenty](across-income-documents.md)  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Práce s Dynamics NAV](ui-work-product.md)

