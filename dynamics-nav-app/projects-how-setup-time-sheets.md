---
title: "Návod: Nastavení časových rozvrhů."
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
ms.openlocfilehash: 6cbacce79ce185d6ed00ea8383259d1b28f9e11b
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-time-sheets"></a>Návod: Nastavení časových rozvrhů.
Časové rozvrhy v Dynamics NAV zaznamenávejte v týdenních přírůstcích po sedmi dnech. Používáte je ke sledování času použitého na projektech a můžete je použít k záznamu jednoduché registrace času. Než budete moci používat časové rozvrhy, musíte určit, jak chcete, aby byly nastaveny a nakonfigurovány.

Jakmile nastavíte, jak bude vaše organizace používat časové rozvrhy, můžete určit, zda a jak jsou schvalovány. V závislosti na potřebách vaší organizace můžete určit:

- Jeden nebo více uživatelů jako správce časového rozvrhu a schvalovatel pro všechny časové rozvrhy.
- Schvalovatel časového rozvrhu pro každý zdroj.

Když jste nastavili časové rozvrhy, můžete vytvořit časové rozvrhy pro zdroje, přiřadit je k řádkům plánování projektu a zaúčtovat řádky časových rozvrhů. Pro další informace, viz [Návod: Použití časových rozvrhů](projects-how-use-time-sheets.md).

## <a name="to-set-up-general-information-for-time-sheets"></a>Nastavení obecných informací pro časové rozvrhy  

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu** , zadejte **Nastavení zdrojů** a zvolte související odkaz.  
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
3. Pro pole **Časový rozvrh podle schválení projektu** vyberte jednu z následujících možností.

|Možnost |Popis|
|---|---|
|**Nikdy**|Uživatel v poli **ID schvalovatele časového rozvrhu** na kartě zdrojů schvaluje časový rozvrh.|
|**Vždy**|Uživatel v poli **Zodpovědná osoba** na pracovní kartě schvaluje časový rozvrh.|
|**Pouze stroj** ´|Je-li časový rozvrh stroje spojen s projektem, uživatel v poli **Odpovědná osoba** na kartě projektu schvaluje časový rozvrh. Je-li časový rozvrh stroje spojen se zdrojem, pak uživatel v poli **ID schvalovatele časového rozvrhu** na kartě zdrojů schvaluje časový rozvrh.

## <a name="to-assign-a-time-sheet-administrator"></a>Přiřadit správce časového rozvrhu  

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu** , zadejte **Nastavení uživatele** a zvolte související odkaz.  
2.  Přidejte nového uživatele, pokud seznam uživatelů neobsahuje osobu, kterou chcete mít správcem časových rozvrhů. Pro další informace prosím kontaktujte svého správce.  
3. Vyberte uživatele, kterého chcete mít správcem časových rozvrhů, a poté vyberte **Admin. časového rozvrhu**. zaškrtávací políčko.  

**Tip**: Doporučuje se, abyste pro společnost určili pouze jednoho uživatele, který bude správcem časových rozvrhů. V následujícím postupu nastavíte vlastníka a schvalovatele časového rozvrhu, kde je pro každý zdroj přidělen schvalovatel časového rozvrhu.  

## <a name="to-assign-a-time-sheets-owner-and-approver"></a>Přiřazení vlastníku časového rozvrhu a schvalovatele  

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Zdroje** a zvolte související odkaz.
2. Vyberte zdroj, pro který chcete nastavit možnost používat časové rozvrhy, a poté zaškrtněte políčko **Použít časový rozvrh** .  
3. V poli **ID vlastníka časového rozvrhu** zadejte ID vlastníka časového rozvrhu. Vlastník může zadat časový údaj na časovém rozvrhu a předložit jej ke schválení. Obecně platí, že pokud je zdroj osoba, je tato osoba také vlastníkem.  
4. Do pole **ID schvalovatele časového rozvrhu** zadejte ID schvalovatele časového rozvrhu. Schvalovatel může schvalovat, odmítnout nebo znovu otevřít časový rozvrh.  

**Poznámka**: Nemůžete změnit ID schvalovatele časového rozvrhu, pokud existují časové rozvrhy, které dosud nebyly zpracovány a mají status **Odeslané** nebo **Otevřené** .

## <a name="see-also"></a>Viz také
[Nastavit řízení projektu](projects-setup-projects.md)  
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Spravovat prodej](sales-manage-sales.md)      
[Pracujte s Dynamics NAV](ui-work-product.md)  

