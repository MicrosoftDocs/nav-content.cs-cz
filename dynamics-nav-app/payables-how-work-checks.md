---
title: "Vydání, Tisk, Zrušení šeku "
description: "Popisuje jak vydávat šeky pomocí deníku plateb, tisk šeků a zrušení nebo zobrazení položek šeků v Dynamics NAV."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment journal, print check, vendor payment, creditor, debt, balance due, AP
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 716cb17bf65b225036576dc73f3fe43b102ccb81
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-checks"></a>Návod: Práce s šeky
Můžete vydávat elektronické mebo ruční šeky v . Obě metody používají deník plateb k vystavení šeků dodavatelům. Můžete také anulovat šeky a zobrazit položky šeku.

Proces vydávání šeků navrhuje platby, vytváří položky a tiskne počítačové šeky.

> [!NOTE]  
>   Chcete-li se ujistit, že banka vymaže pouze ověřené šeky a částky, můžete je poslat soubor, který obsahuje informace o dodavateli, kontrole a platbě. Další informace naleznete v tématu [Návod: Export souboru pozitivních plateb](finance-how-positive-pay.md).

Tiskárna musí být správně nastavena pomocí šekových formulářů a musíte určit, které rozvržení šeku použijete. Další informace naleznete v tématu [Návod: Definování rozvržení šeku](finance-how-define-check-layouts.md)

## <a name="to-issue-checks"></a>Vydání šeků
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky plateb** a vyberte související odkaz.
2. Vyplňte deník příslušnými platbami, například pomocí funkce Navrhnout platby dodavateli. Další informace naleznete v tématu [Návod: Navrhnutí plateb dodavatelů ](payables-how-suggest-vendor-payments.md).
3. V poli **Typ bankovní platby** na řádcích deníku pro platbu, kterou chcete provést pomocí šeků, vyberte jednu z následujících možností:

   * **Počítačový šek**: Tuto volbu vyberte, pokud chcete vytisknout šek částky na řádku deníku plateb. Musíte vytisknout kontroly před tím, než budete moci zaúčtovat řádky žurnálu. Můžete zvolit pouze možnost **Počítačový šek**, pokud je nastavena hodnota Protiúčet** **Typ účtu nebo **Typ účtu** je **Bankovní účet**.
   * **Ruční kontrola**: Tuto volbu vyberte, pokud jste ručně vytvořili šek a chcete vytvořit odpovídající záznam pro tuto částku. Pomocí této možnosti nelze vytisknout šeky z [!INCLUDE[d365fin](includes/d365fin_md.md)]. Můžete zvolit pouze možnost **Počítačový šek**, pokud je nastavena hodnota Protiúčet** **Typ účtu nebo **Typ účtu** je **Bankovní účet**.

     > [!NOTE]  
>   Musíte vytisknout počítačové šeky před tím, než budete moci zaúčtovat řádky žurnálu.
4. V případě kontroly počítače zvolte možnost **Tisk šeku**.
5. V okně **Šek** vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
6. Zvolte tlačítko **Tisk**.

> [!NOTE]  
>   Chcete-li vytisknout šeky z více bankovních účtů ve více než jedné měně, musíte pro každou měnu spustit dávkovou úlohu **Tisk šeku** samostatně a určit příslušný bankovní účet.

## <a name="to-cancel-printed-checks-that-are-not-posted"></a>Zrušení vytištěných šeků, které nejsou zaúčtovány
Po vytištění můžete zrušit nezaúčtované šeky pomocí akce **Zrušit šek** v okně **Deník plateb**.

1. V okně **Deníky plateb** vyberte možnost **Zrušit šek** a poté vyberte, které šeky chcete zrušit.

## <a name="to-void-checks"></a>Anulování šeků
Když byla zaúčtována šeková platba, můžete zrušit (anulovat) šeky pouze z výsledných položek bank.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Bankovní účty** a vyberte související odkaz.
2. Zvolte příslušný bankovní účet, vyberte akci **Úpravy** a poté vyberte akci **Položky šeků**.
3. V okně **Položky šeků** vyberte akci **Zrušit šek**.
4. Vyberte zaškrtávací políčko **Pouze zrušit šeky**.
5. Zvolte tlačítko **OK**.

## <a name="see-also"></a>Viz také
[Správa závazků](payables-manage-payables.md)  
[Nastavení bankovnictví](bank-setup-banking.md)  
[Návod: Export souboru pozitivních plateb](finance-how-positive-pay.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

