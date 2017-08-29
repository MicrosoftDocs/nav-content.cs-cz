---
title: "Návod: Správa projektových zásob"
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 00b9ed8480f6b5ab9265beb0fe2dc0060b1c3192
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-job-supplies"></a>Návod: Správa projektových zásob
Řízení projektových dodávek zboží, služeb a nákladů je nedílnou a kritickou stránkou výkonu všech projektů. Můžete použít inventární množství nebo udělat specifický projektový nákup pro danou zakázku pomocí nákupních objednávek nebo nákupních faktur. Například projektová služba ohledně počítače vyžaduje nový disk. Vytvořte nákupní fakturu pro zakoupení nového disku a zaznamenejte projekt, na který bude použita.

Pokud proces nákupu nevyžaduje, aby byla fyzická transakce zaznamenána samostatně, může být nákup zpracován v okně **Finanční deník projektu** . Pro další informace , viz [Návod: Využití záznamu pro projekty](projects-how-record-job-usage.md) .

## <a name="to-purchase-items-or-services-for-a-job"></a>Zakoupení zboží nebo služeb pro projekt
Následující postup ukazuje, jak použít nákupní fakturu k nákupu produktů pro daný projekt. Při použití nákupní objednávky platí stejné kroky.  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nákupní faktury** a pak vyberte související odkaz.  
2. Vyberte akci **Nový** a poté vyplňte potřebná pole. Pro další informace , viz [Návod: Záznam nákupů](purchasing-how-record-purchases.md) .
3. V poli **Číslo projektu** a **Č. činnosti projektu** pole, vyberte informace o projektu, pro který chcete zakoupit zboží nebo služby.  

    Hodnota, kterou vyberete v poli **Typ řádku projektu,** určuje, zda je po zaúčtování spotřeby zboží vytvořen řádek plánování. Pokud pole obsahuje možnost **Fakturace** , jsou vytvořeny řádky plánování projektu, které jsou připraveny k fakturaci zákazníkovi. Pro další informace , viz [Návod: Faktury projektu](projects-how-invoice-jobs.md) .

4. Zvolte akci **Zaúčtovat**.

## <a name="to-view-the-value-of-purchases-for-a-job"></a>Zobrazit hodnotu nákupů pro projekt  

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.
2. Otevřít příslušnou kartu projektu.

    Na kartě **Činnosti** v poli **Nevyřízené objednávky** zobrazuje celkovou nevyřízenou částku, v místní měně, inventáře zboží a služeb na nákupních dokladech pro řádek činnosti projektu.  

    **Část. Rec. Pole Nefakturováno** zobrazuje hodnotu zboží dodaných na nákupních dokladech, které  dosud nebyly fakturovány.  

3. Zvolte jedno z polí, chcete-li otevřít okno **Nákupní řádky** kde můžete zkontrolovat informace o souvisejících řádcích nákupních dokladů, včetně zboží nebo služeb, které byly přijaty.

## <a name="to-post-a-job-related-expense"></a>Účtování nákladů souvisejících s prací  
Máte-li mimořádné nebo jednorázové výdaje na práci, můžete použít okno **Finanční deník projektu** ,abyste je mohli zaúčtovat přímo na příslušný účet projektu.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Finanční deník projektu** a pak vyberte související odkaz.  
2. Vytvořte nový řádek a zadejte informace o výdajích, včetně informací v poli **Č. projektu** a pole **Č. činnosti projektu** .  
3. Po dokončení deníku zvolte akci **Zaúčtovat**.


## <a name="see-also"></a>Viz také
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Spravovat prodej](sales-manage-sales.md)      
[Pracujte s Dynamics NAV](ui-work-product.md)  

