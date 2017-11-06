---
title: "Nastavení pracovních výkazů a jejich schválení"
description: "Můžete nastavit pracovní výkazy ke sledování využitého času na projektech a využití zdrojů. Toto vám pomůže s projektovým řízením, personální obsazení a kapacitami."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project management, capacity, staff, resource
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 636bf45213ab4adf33244cb97dd1328733bf27ad
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-time-sheets"></a>Návod: Nastavení pracovních výkazů
Pracovní výkazy v [!INCLUDE[d365fin](includes/d365fin_md.md)] zaznamenávejte v týdenních přírůstcích po sedmi dnech. Používáte je ke sledování času použitého na projektech a můžete je použít k záznamu jednoduché registrace času. Než budete moci používat pracovní výkazy, musíte určit, jak chcete, aby byly nastaveny a nakonfigurovány.

Jakmile nastavíte, jak bude vaše organizace používat pracovní výkazy, můžete určit, zda a jak jsou schvalovány. V závislosti na potřebách vaší organizace můžete určit:

* Jeden nebo více uživatelů jako správce pracovního výkazu a schvalovatel pro všechny pracovní výkazy.
* Schvalovatel pracovního výkazu pro každý zdroj.

Když jste nastavili pracovní výkazy, můžete vytvořit pracovní výkazy pro zdroje, přiřadit je k řádkům plánování projektu a zaúčtovat řádky pracovních výkazů. Další informace naleznete v tématu [Návod: Použití pracovních výkazů.](projects-how-use-time-sheets.md)

## <a name="to-set-up-general-information-for-time-sheets"></a>Nastavení obecných informací pro pracovní výkazy
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení zdrojů** a vyberte související odkaz.  
2. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Pro pole **Pracovní výkaz Schválení pracovního výkazu za projekt** vyberte jednu z následujících možností.

| Možnost | Popis |
| --- | --- |
| **Nikdy** |Uživatel v poli **ID schvalovatele pracovního výkazu** na kartě zdrojů schvaluje pracovní výkaz. |
| **Vždy** |uživatel v poli **Zodpovědná osoba** na pracovní kartě schvaluje pracovní výkaz. |
| **Pouze stroj ´** |Je-li pracovní výkaz stroje spojen s projektem, uživatel v poli **Odpovědná osoba** na kartě projektu schvaluje pracovní výkaz. Je-li pracovní výkaz stroje spojen se zdrojem, pak uživatel v poli **ID schvalovatele pracovního výkazu** na kartě zdrojů schvaluje pracovní výkaz. |

## <a name="to-assign-a-time-sheet-administrator"></a>Přiřazení správce pracovního výkazu
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení uživatelů** a vyberte související odkaz.  
2. Přidejte nového uživatele, pokud seznam uživatelů neobsahuje osobu, kterou chcete mít správcem pracovních výkazů. Další informace naleznete v tématu [Návod: Správa uživatelů a oprávnění](ui-how-users-permissions.md).
3. Vyberte uživatele, kterého chcete mít správcem pracovních výkazů a poté vyberte **Správce pracovního výkazu**.  

> [!TIP]  
>   Doporučuje se, abyste pro společnost určili pouze jednoho uživatele, který bude správcem pracovních výkazů. V následujícím postupu nastavíte vlastníka a schvalovatele pracovního výkazu, kde je pro každý zdroj přidělen schvalovatel pracovního výkazu.  

## <a name="to-assign-a-time-sheets-owner-and-approver"></a>Přiřazení vlastníku pracovního výkazu a schvalovatele
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zdroje** a vyberte související odkaz.
2. Vyberte zdroj, pro který chcete nastavit možnost používat pracovní výkazy a poté zaškrtněte políčko **Použít pracovní výkaz**.  
3. V poli **ID vlastníka pracovního výkazu** zadejte ID vlastníka pracovního výkazu. Vlastník může zadat časový údaj na časovém rozvrhu a předložit jej ke schválení. Obecně platí, že pokud je zdroj osoba, je tato osoba také vlastníkem.  
4. Do pole **ID schvalovatele pracovního výkazu** zadejte ID schvalovatele pracovního výkazu. Schvalovatel může schvalovat, odmítnout nebo znovu otevřít pracovní výkaz.  

> [!NOTE]  
>   Nemůžete změnit ID schvalovatele pracovního výkazu, pokud existují pracovní výkazy, které dosud nebyly zpracovány a mají status **Odeslané** nebo **Otevřené**.

## <a name="see-also"></a>Viz také
[Nastavení Správy vztahů](projects-setup-projects.md)  
[Řízení projektů](projects-manage-projects.md)  
[Finance](finance.md)  
[Nákup](purchasing-manage-purchasing.md)         
[Prodej](sales-manage-sales.md)      
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

