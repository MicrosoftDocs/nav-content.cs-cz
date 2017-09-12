---
title: "Návod: Nastavení pracovních výkazů"
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

# <a name="how-to-set-up-time-sheets"></a>Návod: Nastavení pracovních výkazů
Pracovní výkazy v Dynamics NAV zaznamenávejte v týdenních přírůstcích po sedmi dnech.  Používáte je ke sledování času použitého na projektech a můžete je použít k záznamu jednoduché registrace času. Než budete moci používat pracovní výkazy, musíte určit, jak chcete, aby byly nastaveny a nakonfigurovány.

Jakmile nastavíte, jak bude vaše organizace používat pracovní výkazy, můžete určit, zda a jak jsou schvalovány.  V závislosti na potřebách vaší organizace můžete určit:

- Jeden nebo více uživatelů jako správce pracovního výkazu a schvalovatel pro všechny pracovní výkazy.
- Schvalovatel pracovního výkazu pro každý zdroj.

Když jste nastavili pracovní výkazy, můžete vytvořit pracovní výkazy pro zdroje, přiřadit je k řádkům plánování projektu a zaúčtovat řádky pracovních výkazů. Další informace naleznete v tématu [Návod: Použití pracovních výkazů](projects-how-use-time-sheets.md).

## <a name="to-set-up-general-information-for-time-sheets"></a>Nastavení obecných informací pro pracovní výkazy  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení zdrojů** a zvolte související odkaz.  
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
3. Pro pole **Pracovní výkaz Schválení pracovního výkazu za projekt** vyberte jednu z následujících možností.

|Možnost |Popis|
|---|---|
|**Nikdy**|Uživatel v poli **ID schvalovatele pracovního výkazu** na kartě zdrojů schvaluje pracovní výkaz.|
|**Vždy**|uživatel v poli **Zodpovědná osoba** na pracovní kartě schvaluje pracovní výkaz.|
|**Pouze stroj** ´|Je-li pracovní výkaz stroje spojen s projektem, uživatel v poli **Odpovědná osoba** na kartě projektu schvaluje pracovní výkaz. Je-li pracovní výkaz stroje spojen se zdrojem, pak uživatel v poli **ID schvalovatele pracovního výkazu** na kartě zdrojů schvaluje pracovní výkaz.

## <a name="to-assign-a-time-sheet-administrator"></a>Přiřazení správce pracovního výkazu  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení uživatele** a zvolte související odkaz.  
2.  Přidejte nového uživatele, pokud seznam uživatelů neobsahuje osobu, kterou chcete mít správcem pracovních výkazů. Pro další informace prosím kontaktujte svého správce.  
3. Vyberte uživatele, kterého chcete mít správcem pracovních výkazů a poté vyberte **Správce pracovního výkazu** zaškrtávací políčko.  

**Tip**: Doporučuje se, abyste pro společnost určili pouze jednoho uživatele, který bude správcem pracovních výkazů. V následujícím postupu nastavíte vlastníka a schvalovatele pracovního výkazu, kde je pro každý zdroj přidělen schvalovatel pracovního výkazu.  

## <a name="to-assign-a-time-sheets-owner-and-approver"></a>Přiřazení vlastníku pracovního výkazu a schvalovatele  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Zdroje** a zvolte související odkaz.
2. Vyberte zdroj, pro který chcete nastavit možnost používat pracovní výkazy a poté zaškrtněte políčko **Použít pracovní výkaz**.  
3. V poli **ID vlastníka pracovního výkazu** zadejte ID vlastníka pracovního výkazu. Vlastník může zadat časový údaj na časovém rozvrhu a předložit jej ke schválení. Obecně platí, že pokud je zdroj osoba, je tato osoba také vlastníkem.  
4. Do pole **ID schvalovatele pracovního výkazu** zadejte ID schvalovatele pracovního výkazu. Schvalovatel může schvalovat, odmítnout nebo znovu otevřít pracovní výkaz.  

**Poznámka**: Nemůžete změnit ID schvalovatele pracovního výkazu, pokud existují pracovní výkazy, které dosud nebyly zpracovány a mají status **Odeslané** nebo **Otevřené**.

## <a name="see-also"></a>Viz také
[Nastavení řízení projektu](projects-setup-projects.md)  
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Správa prodeje](sales-manage-sales.md)      
[Práce s Dynamics NAV](ui-work-product.md)  

