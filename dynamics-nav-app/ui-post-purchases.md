---
title: "Účtování nákupů"
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
ms.openlocfilehash: 646ea47adfe2f949e0fdf950607e7d246dcb9f59
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="posting-purchases"></a>Účtování nákupů
Ve skupině **Účtování** na nákupním dokladu si můžete vybrat mezi následujícími funkcemi:

- **Účtovat**
- **Náhled účtování**
- **Účtovat a vytisknout**
- **Testovací sestava**
- **Dávkové účtování**

Po dokončení všech řádků a zadání všech informací na objednávce ji můžete zaúčtovat, to znamená vytvoření příjemky a faktury.

Po zaúčtování nákupní objednávky se aktualizují účty dodavatele, hlavní knihy a položky zboží.

Pro každou nákupní objednávku je vytvořena nákupní položka v tabulce **Věcných položek**. Položka je také vytvořena pro účet dodavatele v tabulce **Položka dodavatele** a věcná položka je vytvořena na příslušném účtu závazků. Kromě toho může zaúčtování objednávky vést k vytvoření položky DPH a věcné položky pro částku slevy.  Zda je položka pro slevu zaúčtována, závisí na obsahu pole **Účtování slevy** v okně **Nastavení nákupu a závazků**.

Pro každý řádek nákupní objednávky bude vytvořena položka zboží v tabulce **Položky zboží** (pokud budou řádky nákupu obsahovat čísla zboží) nebo bude vytvořena věcná položka v tabulce **Věcných položek** (pokud budou řádky nákupu obsahovat finanční účet). Kromě toho jsou nákupní objednávky vždy zaznamenávány v tabulkách **Hlavička nákupní příjemky a   Hlavička nákupní faktury**. 

Než začnete účtovat, můžete vytisknout testovací sestavu, která obsahuje všechny informace z nákupní objednávky a označuje případné chyby. Chcete-li sestavu vytisknout, zvolte možnost **Účtovat** a poté zvolte **Testovací sestava**.

**Důležité**: Když zaúčtujete objednávku, můžete vytvořit jak příjemku, tak fakturu.  To může být provedeno současně nebo nezávisle. Můžete také vytvořit částečnou příjemku a částečnou fakturu tím, že předtím než zaúčtujete, vyplníte pole **Množ. k příjmu** a **Množ. k fakturaci** na jednotlivých řádcích nákupní objednávky.  Všimněte si, že nemůžete vytvořit fakturu za něco, co nebylo přijato. To znamená, že předtím, než budete moci fakturovat, musíte mít zaznamenanou příjemku, nebo musíte vybrat přijmout a fakturovat současně. 

Můžete buď účtovat, nebo účtovat a tisknout. Pokud zvolíte účtovat a tisknout, pak se sestava vytiskne v okamžiku, kdy je objednávka účtována.  Můžete také zvolit funkci **Dávkové účtování**, která umožňuje účtovat více objednávek najednou.

Když je účtování kompletní, zaúčtované nákupní řádky jsou z objednávky odebrány. Jakmile je účtování dokončeno je zobrazena zpráva. Poté budete moci v různých oknech zobrazit zaúčtované položky jako jsou **Položky dodavatele**, **Věcné položky**, **Položky zboží**, **Nákupní příjemky** a **Zaúčtované nákupní faktury**.

## <a name="see-also"></a>Viz také
[Účtovat doklady a deníky](ui-post-documents-journals.md)
