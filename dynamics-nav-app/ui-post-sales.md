---
title: "Porozumění, jak účtovat prodejní doklady"
description: "Informace o různých funkcích účtování prodejních dokumentů."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7261e8faca0c14330e66093f8db3d44935c4d141
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="posting-sales"></a>Účtování prodeje
Ve skupině **Účtování** na prodejním dokladu si můžete vybrat mezi následujícími účtovacími funkcemi:

* **Účtovat**
* **Testovací sestava**
* **Účtovat a odeslat**
* **Účtovat a vytisknout**
* **Účtovat a poslat e-mailem**
* **Dávkové účtování**
* **Náhled účtování**

Po dokončení všech řádků a zadání všech informací na objednávce ji můžete zaúčtovat. Tím vytvoříte dodávku a fakturu.

Po zaúčtování prodejní objednávky se aktualizují účty zákazníka, hlavní knihy a položky zboží.

Pro každou prodejní objednávku je v tabulce **Věcných položek** vytvořena položka prodeje. Položka je také vytvořena na účtu zákazníka v **Položkách zákazníka Na příslušném účtu pohledávek je vytvořena tabulka Položek** hlavní knihy a položka hlavní knihy. Kromě toho, může zaúčtování objednávky vést k položce DPH a položce hlavní knihy pro částku slevy. Zda je položka pro slevu zaúčtována, závisí na obsahu pole **Účtování slevy** v okně **Nastavení Prodeje a Pohledávek**.

Pro každý řádek prodejní objednávky bude vytvořena položka zboží v tabulce **Položky zboží** (pokud budou řádky prodeje obsahovat čísla zboží) nebo bude vytvořena položka hlavní knihy v tabulce **Věcných položek** (pokud budou řádky prodeje obsahovat finanční účet). Kromě toho jsou prodejní objednávky vždy zaznamenávány v tabulkách **Hlavička prodejní dodávky** a **Hlavička prodejních faktur**.

> [!IMPORTANT]  
>   Když zaúčtujete objednávku, můžete vytvořit jak dodávku, tak fakturu. To může být provedeno současně nebo nezávisle. Můžete také vytvořit částečnou dodávku a částečnou fakturu tím, že předtím než účtujete, vyplníte pole **Množ. k dodání** a **Množ. k fakturaci** na jednotlivých řádcích prodejní objednávky. Všimněte si, že nemůžete vytvořit fakturu za něco, co není dodáno. To znamená, že předtím, než budete moci fakturovat, musíte mít zaznamenanou dodávku, nebo musíte vybrat dodat a fakturovat současně.

Když je účtování kompletní, zaúčtované prodejná řádky jsou z objednávky odebrány. Zpráva vám sděluje, kdy je účtování dokončeno. Poté budete moci zobrazit zaúčtované položky v různých oknech, které obsahují zaúčtované položky, jako například okna **Položky zákazníka**, **Věcné položky**, **Položky zboží**, **Zaúčtování prodejních dodávek** a **Zaúčtování prodejních faktur**.

## <a name="see-also"></a>Viz také
[Prodej](sales-manage-sales.md)  
[Návod: Odesílání dokladů e-mailem](ui-how-send-documents-email.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


