---
title: "Import vašich starších obchodních dat do Dynamics NAV"
description: "Můžete migrovat data o zákaznících, dodavatelích a zásobách. Například, z Excelu, QuickBooks nebo Dynamics GP do vašeho Dynamics NAV"
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: migrate, initialize, implement
ms.date: 09/25/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b19a05fba8a940dad4dcb6c8aebbefdcae67c324
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="importing-business-data-from-other-finance-systems"></a>Importování obchodních dat z jiných finančních systémů
Když se přihlásíte do [!INCLUDE[d365fin](includes/d365fin_md.md)], můžete si vybrat zda chcete vytvořit prázdnou společnost, takže později můžete nahrát vaše vlastní data a testovat v [!INCLUDE[d365fin](includes/d365fin_md.md)]. V závislosti finančního řešení, které vaše firma používá dnes, můžete přenést informace o zákaznících, dodavatelích, zásobách a bankovních účtech.  

Z domovské stránky získáte přístup k asistovanému nastavení, které vám pomůže přenést obchodní data ze souboru aplikace Excel nebo jiných formátů. Typy souborů, které lze nahrát, závisí na dostupných rozšířeních. Můžete například nahrát data z QuickBooks, protože obsahuje [!INCLUDE[d365fin](includes/d365fin_md.md)] rozšíření, které zpracovává konverzi z QuickBooks. Chcete-li migrovat data z jiných finančních řešení, musíte buď zkontrolovat, zda je rozšíření pro toto řešení k dispozici nebo importovat z aplikace Excel.  

[!INCLUDE[d365fin](includes/d365fin_md.md)] Program obsahuje šablony pro zákazníky, dodavatele a zboží, které můžete použít při nahrávání dat.  

## <a name="importing-data-from-quickbooks-or-dynamics-gp"></a>Import Dat z QuickBooks nebo Dynamics GP
Pokud vaše firma dnes používá QuickBooks, můžete odpovídající informace exportovat do souboru.. Potom můžete otevřít asistované nastavení pro přenos dat.
Pokud například váš soubor zahrnuje zákazníky a dodavatele, můžete se rozhodnout přenést pouze data zákazníků. Ostatní informace pak můžete přenést později.  

Asistované nastavení obsahuje možnost změnit výchozí konfiguraci přenosu, ale pokročilé nastavení doporučujeme pouze, pokud jste obeznámeni s databázovými tabulkami. V převážné většině společností výchozí mapování z QuickBooks nebo Dynamics GP převede do [!INCLUDE[d365fin](includes/d365fin_md.md)] požadované informace.  

Další informace naleznete v tématu [QuickBooks Desktop Data Migration](ui-extensions-quickbooks-data-migration.md), [QuickBooks Online Data Migration](ui-extensions-quickbooks-online-data-migration.md), or [Dynamics GP Data Migration](ui-extensions-dynamicsgp-data-migration.md).  

## <a name="importing-data-from-configuration-packages"></a>Importování dat z konfiguračních balíčků
[!INCLUDE[d365fin](includes/d365fin_md.md)] Tato funkce zahrnuje konfigurační balíčky, které můžete exportovat do Excelu a nastavili zde vaše data. Potom můžete data z Excelu naimportovat zpět. Balíček obsahuje 27 tabulek obsahující hlavní data, například o zákaznících, dodavatelích, zboží, fin. účtech. Další tabulky obsahují základní nastavení jako metody dodávky, tabulky transakcí obsahující prodejní hlavničky a řádky.   

> [!NOTE]  
>   Práce s konfiguračními balíčky jsou pokročilé funkcionality, proto doporučujeme kontaktovat administrátora. Další informace naleznete v tématu [Importování dat ze starého účetnického programu použitím konfiguračního balíčku](across-import-data-configuration-packages.md).  

## <a name="see-also"></a>Viz také
[Finance](finance.md)  
[Další informace naleznete v tématu Importování dat ze starého účetnického programu použitím konfiguračního balíčku.](across-import-data-configuration-packages.md)  
[Migrace dat QuickBooks](ui-extensions-quickbooks-data-migration.md)  
[Migrace dat QuickBooks](ui-extensions-quickbooks-online-data-migration.md)  
[Migrace dat pomocí Dynamics GP](ui-extensions-dynamicsgp-data-migration.md)  
[Přizpůsobení [!INCLUDE[d365fin](includes/d365fin_md.md)] Pomocí rozšíření](ui-extensions.md)   
[Nastavení [!INCLUDE[d365fin](includes/d365fin_md.md)]](setup.md)

## 

