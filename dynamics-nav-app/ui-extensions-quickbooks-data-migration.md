---
title: "POužiPoužití rozšíření QuickBooks Migration"
description: "Popisuje jak použít rozšíření k importu zákazníků, dodavatelů, zboží, a finančních účtů z QuickBooks Desktop do Dynamics NAV."
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, import, implement
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7b8cf77369a2073f746aebdca5d4cbeba80283ec
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="the-quickbooks-data-migration-extension-for-dynamics-nav"></a>Rozšíření migrace dat QuickBooks pro Dynamics NAV
Toto rozšíření usnadňuje migraci zákazníků, dodavatelů, zboží a fin. účtů z QuickBooks do [!INCLUDE[d365fin](includes/d365fin_md.md)]. Pokud vaše firma používá služby QuickBooks, můžete exportovat příslušné informace a poté otevřít pomocnou instalační příručku pro nahrání dat do [!INCLUDE[d365fin](includes/d365fin_md.md)].  
Pro více informací bežte na: [Import obchodních dat z jiných finančních systémů](upload-data.md).

## <a name="exporting-data-from-quickbooks-desktop"></a>Export dat z QuickBooks Desktop
Musíte exportovat některé nebo všechny své stávající zákazníky, dodavatele, zásoby zboží a účty položky do souboru Intuit Interchange Format (IIF). Rozšíření migrace dat QuickBooks obsahuje standardní mapování dat služby QuickBooks, takže můžete použít stávající data k otestování nové společnosti v [!INCLUDE[d365fin](includes/d365fin_md.md)]. Výchozí mapování bude v převážné většině případů postačující, ale můžete změnit mapování v příručce pro asistenci.  
QuickBooks obsahuje nástroj na export seznamů v menu. Pro účely [!INCLUDE[d365fin](includes/d365fin_md.md)] můžete exportovat následující seznamy:

* Seznam zákazníků  
* Seznam dodavatelů  
* Seznam zboží  
* Seznam účtů  

Exportovaná data jsou uložena jako soubor typu IIF, který můžete poté nahrát do aplikace [!INCLUDE[d365fin](includes/d365fin_md.md)].

## <a name="finding-the-quickbooks-data-migration-extension"></a>Nalezení rozšíření QuickBooks Data Migration
Rozšíření QuickjBooks Data Migration je instalováno a připraveno k použití jako integrovaná část asistovaného nastavení migrace dat. Pokud jste připraveni začít a máte exportovaná vaše data z QuickBooks, zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Asistovaná nastavení** a vyberte související odkaz. Vyberte **Migrovat obchodní data** a sledujte následující kroky v průvodci.  

## <a name="see-also"></a>Viz také
[Importování obchodních dat z jiných finančních systémů](upload-data.md)  
[Přizpůsobení [!INCLUDE[d365fin](includes/d365fin_md.md)] Pomocí rozšíření ](ui-extensions.md)  

