---
title: "Účtování prodeje"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: e87dd5faf7713aecfbe7209d00bb8076fcae9d25
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="posting-sales"></a>Účtování prodeje
V **Účto skupině** na prodejním dokladu si můžete vybrat mezi následujícími účtovacími funkcemi:

- **Účtovat**
- **Testovací sestava**
- **Účtovat a odeslat**
- **Účtovat a vytisknout**
- **Účtovat a poslat e-mailem**
- **Dávkové účtování**
- **Náhled účtování**

Po dokončení všech řádků a zadání všech informací na objednávce ji můžete zaúčtovat. Tím vytvoříte dodávku a fakturu.

Po zaúčtování prodejní objednávky se aktualizují účty zákazníka, hlavní knihy a položky zboží.

Pro každou prodejní objednávku je v tabulce **Věcných položek** vytvořena položka prodeje. Položka je také vytvořena na účtu zákazníka v **ZÁK. Na příslušném účtu pohledávek je vytvořena tabulka Položek hlavní knihy** a položka hlavní knihy. Kromě toho, může zaúčtování objednávky vést k položce DPH a položce hlavní knihy pro částku slevy. Zda je položka pro slevu zaúčtována, závisí na obsahu pole **Účtování slevy** v okně **Nastavení Prodeje a Pohledávek**.

Pro každý řádek prodejní objednávky bude vytvořena položka zboží v tabulce **Položky zboží** (pokud budou řádky prodeje obsahovat čísla zboží) nebo bude vytvořena položka hlavní knihy v tabulce **Věcných položek** (pokud budou řádky prodeje obsahovat finanční účet). Kromě toho jsou prodejní objednávky vždy zaznamenávány v tabulkách **Hlavička prodejní dodávky** a **Hlavička prodejních faktur**.

**Důležité**: Když zaúčtujete objednávku, můžete vytvořit jak dodávku, tak fakturu. To může být provedeno současně nebo nezávisle. Můžete také vytvořit částečnou dodávku a částečnou fakturu tím, že předtím než účtujete, vyplníte pole **Množ. k dodání** a **Množ. k fakturaci** na jednotlivých řádcích prodejní objednávky. Všimněte si, že nemůžete vytvořit fakturu za něco, co není dodáno.  To znamená, že předtím, než budete moci fakturovat, musíte mít zaznamenanou dodávku, nebo musíte vybrat dodat a fakturovat současně. 

Když je účtování kompletní, zaúčtované prodejná řádky jsou z objednávky odebrány. Zpráva vám sděluje, kdy je účtování dokončeno. Poté budete moci zobrazit zaúčtované položky v různých oknech, které obsahují zaúčtované položky, jako například okna **ZÁK., Položky hlavní knihy**, **Věcné položky**, **Položky zboží**, **Zaúčtování prodejních dodávek** a **Zaúčtování prodejních faktur**.

## <a name="see-also"></a>Viz také
[Návody: Odesílání dokladů e-mailem](ui-how-send-documents-email.md)

