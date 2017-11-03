---
title: "Import mzdových transakcí"
description: "Ke správě platů importujte a zaúčtujte finanční transakce od svého poskytovatele mzdových plateb do hlavní knihy pomocí rozšíření o mzdy, jako jsou například Ceridian nebo Quickbooks."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: Ceridian, Quickbooks, salary
ms.date: 06/16/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 675a63c7862854ef3f8e2ca3d37dd3f2e290cf29
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-import-payroll-transactions"></a>Návod: Import mzdových transakcí
Na účet pro platby výplat a související transakce musíte importovat a zaúčtovat finanční transakce vytvořené vašim mzdovým poskytovatelem do hlavní knihy. Pokud chcete tohle udělat, nejdříve naimportujte soubor, který jste obdrželi od poskytovatele mezd do okna **Finanční deníky**. Pak namapujete externí účty v mzdovém souboru k souvisejícím finančním účtů. Nakonec zaúčtujete mzdové transakce podle mapování účtu.

> [!NOTE]  
>   K použití této funkcionality musí být nainstalováno a povoleno rozšíření pro import mzdy. Ceridian Payroll a Quickbooks Payroll import souborů jsou předinstalovány v [!INCLUDE[d365fin](includes/d365fin_md.md)]. Další informace naleznete v tématu: [Přizpůsobení [!INCLUDE[d365fin](includes/d365fin_md.md)]  Pomocí rozšíření](ui-extensions.md).

## <a name="to-import-a-payroll-file"></a>Import mzdového souboru
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník** a pak vyberte související odkaz.
2. V relevantní dávce finančního deníku vyberte akci **Importovat mzdové transakce**. Otevře se průvodce asistovaného nastavení.
3. Následujte kroky v okně **Import mzdových transakcí**.

    > [!TIP]  
>   V kroku mapování externích záznamů o mzdách na vaše finanční účty, mapování, která vytvoříte, budou zapamatovány při příštím importu stejných záznamů. Tím ušetříte čas, protože nemusíte ručně vyplnit pole **Číslo účtu** ve finančním deníku pokaždé, když importujete opakované mzdové transakce.   

    Po výběru tlačítka **OK** v průvodci asistovaného nastavení, okno **Finanční deník** je vyplněno řádky představující transakce, které obsahují soubory mzdových plateb a příslušné účty předvyplněné v poli **Finanční účet** podle mapování provedených v průvodci.
4. Upravte nebo zaúčtujte řádky deníku pro kteroukoli jinou transakci financí. Další informace naleznete v tématu [Návod: Zaúčtování transakcí přímo do hlavní knihy](finance-how-post-transactions-directly.md).   

## <a name="see-also"></a>Viz také
[Finance](finance.md)  
[Přizpůsobení [!INCLUDE[d365fin](includes/d365fin_md.md)] Pomocí rozšíření](ui-extensions.md)  
[Práce s finančními deníky](ui-work-general-journals.md)  

