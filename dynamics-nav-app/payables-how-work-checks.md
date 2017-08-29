---
title: "Návod: Práce se šeky"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a>Návod: Práce se šeky
Dynamics NAV podporuje elektronické a manuální vydávání šeků. Obě metody používají deník plateb k vystavení šeků dodavatelům. Můžete také anulovat šeky a zobrazit položky šeku.

Proces vydávání šeků navrhuje platby, vytváří položky a tiskne počítačové šeky.

Tiskárna musí být správně nastavena pomocí šekových formulářů a musíte určit, které rozvržení šeku použijete. Další informace naleznete v tématu: [Návod: Definování rozvržení šeku](finance-setup-how-define-check-layouts.md)

## <a name="to-issue-checks"></a>Vydání šeků
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky plateb** a pak vyberte související odkaz.
2. Vyplňte deník příslušnými platbami, například pomocí funkce Navrhnout platby dodavateli. Další informace naleznete v tématu: [Návod: Návrh platby dodavatele](payables-how-suggest-vendor-payments.md).
3. V poli **Typ bankovní platby** na řádcích deníku pro platbu, kterou chcete provést pomocí šeků, vyberte jednu z následujících možností:

 - **Počítačový šek**: Tuto volbu vyberte, pokud chcete vytisknout šek částky na řádku deníku plateb. Musíte vytisknout kontroly před tím, než budete moci zaúčtovat řádky žurnálu. Můžete zvolit pouze možnost **Počítačový šek**, pokud je nastavena hodnota **Protiúčet Typ účtu** nebo **Typ účtu** je **Bankovní účet**.

 - **Ruční kontrola**: Tuto volbu vyberte, pokud jste ručně vytvořili šek a chcete vytvořit odpovídající záznam pro tuto částku. Pomocí této možnosti nelze vytisknout šeky z Dynamics NAV. Můžete zvolit pouze možnost **Počítačový šek**, pokud je nastavena hodnota **Protiúčet Typ účtu** nebo **Typ účtu** je **Bankovní účet**.

    **Poznámka**: Musíte vytisknout počítačové šeky před tím, než budete moci zaúčtovat řádky žurnálu.
4. V případě kontroly počítače zvolte možnost **Tisk šeku**.
5. V okně **Šek** vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
6. Zvolte tlačítko **Tisk**.

**Poznámka**: Chcete-li vytisknout šeky z více bankovních účtů ve více než jedné měně, musíte pro každou měnu spustit dávkovou úlohu **Tisk šeku** samostatně a určit příslušný bankovní účet.

## <a name="to-cancel-printed-checks-that-are-not-posted"></a>Zrušení vytištěných šeků, které nejsou zaúčtovány
Po vytištění můžete zrušit nezaúčtované šeky pomocí akce **Zrušit šek** v okně **Deník plateb**.
1. V okně **Deníky plateb** vyberte možnost **Zrušit šek** a poté vyberte, které šeky chcete zrušit.

## <a name="to-void-checks"></a>Anulování šeků
Když byla zaúčtována šeková platba, můžete zrušit (anulovat) šeky pouze z výsledných položek bank.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Banky** a pak vyberte související odkaz.
2. Zvolte příslušný bankovní účet, vyberte akci **Úpravy** a poté vyberte akci **Položky šeků**.
3. V okně **Položky šeků** vyberte akci **Zrušit šek**.
4. Vyberte zaškrtávací políčko **Pouze zrušit šeky**.
5. Zvolte tlačítko **OK**.

## <a name="see-also"></a>Viz také
[Správa závazků](payables-manage-payables.md)  
[Nastavit bankovnictví](bank-setup-banking.md)  

