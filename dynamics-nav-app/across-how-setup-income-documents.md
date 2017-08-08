---
title: "Návod: Nastavení Příchozích dokumentů"
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
ms.openlocfilehash: 2bce97c76876c86a576ec6a281a306a46881027c
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-incoming-documents"></a>Návod: Nastavení Příchozích dokumentů
Pokud vytvoříte řádky finančního deníku ze záznamů příchozího dokumentu, musíte zadat v okně **Nastavení příchozích dokumentů** šablonu deníku a dávku, které chcete použít. 

Pokud nechcete, aby uživatelé vytvářeli faktury nebo řádky finančního deníku ze záznamů příchozího dokumentu, pokud nejsou dokumenty prvně schváleny, je nutné nastavit schvalovatele v okně **Schvalovatelé příchozího dokumentu**.

Chcete-li soubory PDF a obrázkové soubory převést do elektronických dokumentů, které lze převést například na nákupní faktury v Dynamics NAV, musíte nejprve nastavit funkci OCR a povolit službu.

Když je nastavena funkce Příchozí dokumenty, můžete použít různé funkce pro kontrolu výdajů, správu úloh OCR a převod souborů příchozího dokumentu ručně nebo automaticky na příslušné dokumenty nebo řádky deníku. Externí soubory lze připojit v libovolné fázi procesu, včetně zaúčtovaných dokumentů a výsledných záznamů prodejce, zákazníka a položek hlavní knihy. Další informace naleznete v [Návod: Proces příchozích dokumentů](across-process-income-documents.md).

## <a name="to-set-up-the-incoming-documents-feature"></a>Nastavení funkcí Příchozích dokumentů
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení příchozích dokumentů** a pak vyberte související odkaz.
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.

## <a name="to-set-up-approvers-of-incoming-document-records"></a>Nastavení schvalovatelů záznamů o příchozím dokumentu
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení příchozích dokumentů** a pak vyberte související odkaz.  
2. V okně **Nastavení příchozích dokumentů** zvolte akci **Schvalovatelé**. 

    Okno **Schvalovatelé příchozího dokumentu** ukáže všechny uživatele, kteří jsou nastaveni v Dynamics NAV.  
3. Vyberte jednoho nebo více uživatelů, kteří mohou schválit příchozí dokument předtím, než lze vytvořit související dokument nebo řádek deníku.

Pokud byli schvalovatelé nastaveni v okně **Schvalovatelé příchozích dokumentů**, pouze tito uživatelé mohou schválit příchozí dokument, pokud je zaškrtnuto políčko **K vytvoření požadovat schválení** v okně **Nastavení příchozích dokumentů**.

**Poznámka**: Toto nastavení schválení nesouvisí se schvalovacími postupy. Další informace naleznete v [Návod: Použijte schvalovací postupy](across-how-use-approval-workflows.md).

## <a name="to-set-up-an-ocr-service"></a>Nastavení služby OCR
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení služby OCR** a pak vyberte související odkaz.
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.


## <a name="to-encrypt-your-login-information"></a>Šifrování přihlašovacích údajů
Doporučuje se chránit přihlašovací informace, které zadáte do okna **Nastavení služby OCR**. Můžete šifrovat data na serveru generováním nového nebo importováním existujícího šifrovacího klíče, který povolíte na instanci serveru, který je připojen k databázi.

1. V okně **Nastavení služby OCR** zvolte akci **Správa šifrování**.
2. Okno **Správa šifrování dat** umožňuje šifrování vašich dat.

## <a name="see-also"></a>Viz také  
[Proces příchozích dokumentů](across-process-income-documents.md)  
[Příchozí dokumenty](across-income-documents.md)  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Práce s Dynamics NAV](ui-work-product.md)

