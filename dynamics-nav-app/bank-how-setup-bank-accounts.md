---
title: "Nastavení bankovních účtů"
description: "Můžete odsouhlasit bankovní účty v Dynamics NAV s výpisy z bank."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: feed, stream
ms.date: 09/26/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3581615fe94006aa9245f5e66fe6cf475b22acfb
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-bank-accounts"></a>Návod: Nastavení bankovních účtů
Použijte bankovní účty v [!INCLUDE[d365fin](includes/d365fin_md.md)], které slouží ke sledování vašich bankovních transakcí. Účty mohou být denominovány v místní měně nebo v cizí měně. Po nastavení bankovních účtů můžete použít také možnost kontroly tisku.

## <a name="to-set-up-bank-accounts"></a>Nastavení bankovních účtů
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Bankovní účty** a pak vyberte související odkaz.
2. V okně **Bankovní účty** zvolte akci **Nový**.
3. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]
> K vyplnění pole **Zůstatek** s počátečním zůstatkem, musíte zaúčtovat položku bankovního účtu s příslušnou částkou. Můžete to provést pomocí odsouhlasení bankovního účtu. Další informace naleznete v tématu [Návod: Odsouhlasení bankovních účtů zvlášť](bank-how-reconcile-bank-accounts-separately.md). Případně můžete provést počáteční zůstatek jako část tvorby obecných dat v nových společnostech pomocí nastavení **Migrovat obchodní data**. Další informace naleznete v [Vítejte v [!INCLUDE[d365fin](includes/d365fin_md.md)](index.md).

## <a name="to-set-up-your-bank-account-for-import-or-export-of-bank-files"></a>Nastavení bankovního účtu pro import nebo export bankovních souborů
Pole v záložce s náhledem **Převod** v okně **Karta bankovního účtu** se týkají importu a exportu bankovních prostředků a souborů. Další informace naleznete v tématu [Návod: Nastavení služby převodu bankovních dat](bank-how-setup-bank-data-conversion-service.md).

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Bankovní účty** a pak vyberte související odkaz.
2. Otevřete kartu pro bankovní účet, který budete exportovat nebo importovat pro bankovní soubory.
3. Na záložce s náhledem **Převod** vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   Různé služby exportu souborů a jejich formáty vyžadují různé hodnoty nastavení v okně **Karta bankovního účtu**. Během exportu souboru budete informováni o nesprávných nebo chybějících hodnotách nastavení. Takže si pečlivě přečtěte krátké popisy polí nebo se podívejte na příslušná témata. Například při exportu platebního souboru pro přenos elektronických peněz v Severní Americe (EFT) je třeba vyplňovat pole **Číslo poslední úhrady** a pole **Číslo převodu**. Další informace naleznete v tématu [Návod: Export plateb do bankovního souboru](payables-how-export-payments-bank-file.md).

## <a name="to-set-up-vendor-bank-accounts-for-export-of-bank-files"></a>Nastavení bankovních účtů dodavatele pro export bankovních souborů
Pole na záložce s náhledem **Převod** v okně **Karta bankovního účtu dodavatele** je připojena k exportu bankovních prostředků a souborů. Další informace naleznete v tématu [Návod: Nastavení služby převodu bankovních dat](bank-how-setup-bank-data-conversion-service.md) a [Návod: Export plateb do bankovního souboru](payables-how-export-payments-bank-file.md).

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dodavatelé** a pak vyberte související odkaz.
2. Otevřete kartu pro dodavatele, jehož bankovní účet budete exportovat do platebních souborů banky.
3. Zvolte akci **Bankovní účty**.
3. V okně **Karta bankovního účtu dodavatele** na záložce s náhledem **Převod** vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-the-opening-balance-on-new-bank-accounts"></a>Nastavení počátečních zůstatků na novém bankovním účtu


## <a name="see-also"></a>Viz také
[Nastavení bankovnictví](bank-setup-banking.md)  
[Správa bankovních účtů](bank-manage-bank-accounts.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

