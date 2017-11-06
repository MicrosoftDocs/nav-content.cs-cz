---
title: "Nákup zboží nebo servisu pro projekty a správa zásob"
description: "Popisuje jak spravovat zásoby a nákup materiálu a servisu pro projekty."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project management, material, purchase
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3405af0c06df0fb04c528cf114d4ef6326f7c0a9
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-manage-job-supplies"></a>Návod: Správa projektových zásob
Řízení projektových dodávek zboží, služeb a nákladů je nedílnou a kritickou stránkou výkonu všech projektů. Můžete použít inventární množství nebo udělat specifický projektový nákup pro danou zakázku pomocí nákupních objednávek nebo nákupních faktur. Například projektová služba ohledně počítače vyžaduje nový disk. Vytvořte nákupní fakturu pro zakoupení nového disku a zaznamenejte projekt, na který bude použita.

Pokud proces nákupu nevyžaduje, aby byla fyzická transakce zaznamenána samostatně, může být nákup zpracován v okně **Finanční deník projektu**. Další informace naleznete v tématu [Návod: Záznam spotřeby pro projekty](projects-how-record-job-usage.md).

## <a name="to-purchase-items-or-services-for-a-job"></a>Zakoupení zboží nebo služeb pro projekt
Následující postup ukazuje, jak použít nákupní fakturu k nákupu produktů pro daný projekt. Při použití nákupní objednávky platí stejné kroky.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nákupní faktury** a vyberte související odkaz.  
2. Vyberte akci **Nový** a poté vyplňte potřebná pole. Další informace naleznete v tématu [Návod: Zaznamenávání nákupů.](purchasing-how-record-purchases.md).
3. V polích **Číslo projektu** a **Číslo úlohy projektu** vyberte informace o projektu, pro který chcete zakoupit zboží nebo služby. Použijte funkci **Zvolit sloupce** pokud nebudou viditelné. Další informace naleznete v tématu [Uživatelská personalizace](ui-user-personalization.md).

    Hodnota, kterou vyberete v poli **Typ řádku projektu** určuje, zda je po zaúčtování spotřeby zboží vytvořen řádek plánování. Pokud pole obsahuje možnost **Fakturovatelné**, jsou vytvořeny řádky plánování projektu, které jsou připraveny k fakturaci zákazníkovi. Další informace naleznete v tématu [Návod: Fakturace projektů](projects-how-invoice-jobs.md).
4. Zvolte akci **Zaúčtovat**.

## <a name="to-view-the-value-of-purchases-for-a-job"></a>Zobrazení hodnoty nákupů pro projekt
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.
2. Otevřete příslušnou kartu projektu.

    Na kartě **Úlohy** v poli **Otevřené objednávky** zobrazuje celkovou nevyřízenou částku v lokální měně zboží a služeb na nákupních dokladech pro řádek úlohy projektu.  

    Pole** Celková nefakturovaná částka **zobrazuje hodnotu zboží přijatých na nákupních dokladech, které dosud nebyly fakturovány.  
3. Zvolte jedno z polí, chcete-li otevřít okno **Nákupní řádky**, kde můžete zkontrolovat informace o souvisejících řádcích nákupních dokladů včetně zboží nebo služeb, které byly přijaty.

## <a name="to-post-a-job-related-expense"></a>Účtování nákladů souvisejících s projektem
Máte-li mimořádné nebo jednorázové výdaje na projekt, můžete použít okno **Finanční deník projektu**, abyste je mohli zaúčtovat přímo na příslušný účet projektu.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník projektu** a vyberte související odkaz.  
2. Vytvořte nový řádek a zadejte informace o výdajích včetně informací v poli **Č. projektu** a** Č. úlohy projektu**.  
3. Po dokončení deníku zvolte akci **Zaúčtovat**.

## <a name="see-also"></a>Viz také
[Řízení projektů](projects-manage-projects.md)  
[Finance](finance.md)  
[Nákup](purchasing-manage-purchasing.md)         
[Prodej](sales-manage-sales.md)      
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

