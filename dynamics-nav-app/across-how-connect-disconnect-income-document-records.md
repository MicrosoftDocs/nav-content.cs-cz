---
title: "Návod: Připojení a odpojení záznamů došlého dokladu z dokladů a položek"
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

# <a name="how-to-connect-and-disconnect-incoming-document-records-from-documents-and-entries"></a>Návod: Připojení a odpojení záznamů došlého dokladu z dokladů a položek
V aplikaci Dynamics NAV můžete ukládat externí obchodní doklady připojením souborů k souvisejícím záznamům došlého dokladu. Pokud se doklad jako třeba nákupní faktura nespustí jako záznam došlého dokladu, můžete stále vytvořit a připojit záznam došlého dokladu později. Soubory došlých dokladů můžete také připojit k zaúčtovaným nákupním a prodejním dokladům a k záznamům prodejců, zákazníků a položek hlavní knihy pomocí okna s fakty **Soubory došlého dokladu**, pro příklad okna **Účtované nákupní faktury** a **Položky dodavatelů**.

Z oken **Účtová osnova** a **Hlavní kniha položek** můžete použít vyhledávací funkci k nalezení položek hlavní knihy pro zaúčtování nákupních a prodejních dokladů, které nemají záznamy došlého dokladu a pak centrálně odkazovat na existující záznamy nebo vytvářet nové s připojenými soubory. Další informace naleznete v [Návod: Nalezení zaúčtovaných dokladů bez záznamů došlého dokladu](across-how-find-posted-documents-without-income-document-records.md).

Následující procedura ukazuje návod, jak připojit soubor k existující nákupní faktuře, která nebyla vytvořena ze záznamu došlého dokladu a návod jak připojit soubor k položkám dodavatele. Připojení souboru k zaúčtovaným nákupním nebo prodejním dokladům funguje podobným způsobem.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-purchase-invoice"></a>Vytvoření a připojení záznamu došlého dokladu k nákupní faktuře
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nákupní faktury** a pak vyberte související odkaz.
2. Vyberte řádek pro nákupní fakturu, kterou chcete připojit k souboru a pak zvolte akci **Vytvořit došlý doklad ze souboru**.
3. Alternativně, vyberte řádek pro nákupní fakturu, kterou chcete připojit k souboru a pak zvolte akci **Připojit soubor**.
4. V okně **Vložit soubor** vyberte soubor, který představuje daný došlý doklad a pak zvolte tlačítko **Otevřít**.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-vendor-ledger-entry"></a>Vytvoření a připojení záznamu došlého dokladu z položky dodavatele
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Položky dodavatele** a pak vyberte související odkaz.
2. Vyberte řádek pro položku dodavatele, kterou chcete připojit k souboru a pak zvolte akci **Vytvořit došlý doklad ze souboru**.
3. Alternativně, vyberte řádek pro položku dodavatele, kterou chcete připojit k souboru a pak zvolte akci **Připojit soubor**.
4. V okně **Vložit soubor** vyberte soubor, který představuje daný příchozí dokument a pak zvolte tlačítko **Otevřít**.

## <a name="to-remove-a-connection-from-an-incoming-document-record-to-a-posted-document"></a>Odebrání připojení ze záznamu došlého dokladu k zaúčtovanému dokladu
Můžete odebrat soubor připojený k nezaúčtovaným dokladům smazáním souvisejícího záznamu došlého dokladu. Pokud je doklad zaúčtovaný, pak musíte nejdřív odebrat připojení ze záznamu došlého dokladu.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Došlé doklady** a pak vyberte související odkaz.
2. Vyberte řádek pro záznam došlého dokladu připojeného k zaúčtovanému dokladu, který chcete odebrat a pak zvolte akci **Odebrat odkaz k záznamu**.

Připojení zaúčtovaného dokladu je odebráno. Nyní můžete pokračovat v připojení dalšího záznamu došlého dokladu k zaúčtovanému dokladu, tak jak je popsáno v tomto tématu.

## <a name="see-also"></a>Viz také  
[Proces došlých dokladů](across-process-income-documents.md)  
[Došlé doklady](across-income-documents.md)  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Práce s Dynamics NAV](ui-work-product.md)

