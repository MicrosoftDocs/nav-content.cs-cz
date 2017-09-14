---
title: "Návod: Nastavení Došlých dokladů"
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

# <a name="how-to-set-up-incoming-documents"></a>Návod: Nastavení Došlých dokladů
Pokud vytvoříte řádky finančního deníku ze záznamů došlého dokladu, musíte zadat v okně **Nastavení došlých dokladů** šablonu deníku a dávku, které chcete použít. 

Pokud nechcete, aby uživatelé vytvářeli faktury nebo řádky finančního deníku ze záznamů došlého dokladu, pokud nejsou doklady prvně schváleny, je nutné nastavit schvalovatele v okně **Schvalovatelé došlého dokladu**.

Chcete-li soubory PDF a obrázkové soubory převést do elektronických dokumentů, které lze převést například na nákupní faktury v [!INCLUDE[navnow](includes/navnow_md.md)], musíte nejprve nastavit funkci OCR a povolit službu.

Když je nastavena funkce Došlých dokladů, můžete použít různé funkce pro kontrolu výdajů, správu úloh OCR a převod souborů došlého dokladu ručně nebo automaticky na příslušné doklady nebo řádky deníku. Externí soubory lze připojit v libovolné fázi procesu včetně zaúčtovaných dokladů a výsledných záznamů prodejce, zákazníka a položek hlavní knihy. Další informace naleznete v tématu [Návod: Proces došlých dokladů](across-process-income-documents.md).

## <a name="to-set-up-the-incoming-documents-feature"></a>Nastavení funkcí Došlých dokladů
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení došlých dokladů** a pak vyberte související odkaz.
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.

## <a name="to-set-up-approvers-of-incoming-document-records"></a>Nastavení schvalovatelů záznamů došlého dokladu
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení došlých dokladů** a pak vyberte související odkaz.  
2. V okně **Nastavení došlých dokladů** zvolte akci **Schvalovatelé**. 

    Okno **Schvalovatelé došlých dokladů** ukáže všechny uživatele, kteří jsou nastaveni v [!INCLUDE[navnow](includes/navnow_md.md)].  
3. Vyberte jednoho nebo více uživatelů, kteří mohou schválit došlý doklad předtím, než lze vytvořit související doklad nebo řádek deníku.

Pokud byli schvalovatelé nastaveni v okně **Schvalovatelé došlých dokladů**, pouze tito uživatelé mohou schválit došlý doklad, pokud je zaškrtnuto políčko **K vytvoření vyžaduje schválení** v okně **Nastavení došlých dokladů**.

**Poznámka**: Toto nastavení schválení nesouvisí se schvalovacími postupy. Další informace naleznete v tématu [Návod: Použití schvalovacího workflow](across-how-use-approval-workflows.md).

## <a name="to-set-up-an-ocr-service"></a>Nastavení služby OCR
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení služby OCR** a pak vyberte související odkaz.
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.


## <a name="to-encrypt-your-login-information"></a>Šifrování přihlašovacích údajů
Doporučuje se chránit přihlašovací informace, které zadáte do okna **Nastavení služby OCR**. Můžete šifrovat data na serveru generováním nového nebo importováním existujícího šifrovacího klíče, který povolíte na instanci serveru, který je připojen k databázi.

1. V okně **Nastavení služby OCR** zvolte akci **Správce šifrování**.
2. Okno **Správa šifrování dat** umožňuje šifrování vašich dat.

## <a name="see-also"></a>Viz také  
[Proces došlých dokladů](across-process-income-documents.md)  
[Došlé doklady](across-income-documents.md)  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md)

