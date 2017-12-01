---
title: "Vytvořte kartu projektu pro projekt a specifikujte úkoly."
description: "Pro nový projekt vytvořte kartu projektu obsahující úkoly a řádky plánování, které vám pomůžou řídit proces a rozpočty."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project management, task
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2ba145cd15e7d7e87796b159c5d4617b39ab76c7
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-jobs"></a>Návod: Tvorba projektů
Když spustíte nový projekt, musíte vytvořit kartu projektu s integrovanými úlohami a řádky plánování projektu, které jsou strukturované ve dvou vrstvách.  

První vrstva se skládá z úloh projektu. Musíte vytvořit alespoň jednu úlohu na projektu, protože veškeré účtování se týká úloh projektu. Pokud máte alespoň jednu úlohu projektu, můžete nastavit řádky plánování projektu a účtovat spotřebu do projektu.

Druhá vrstva se skládá z řádků plánování projektu, které specifikují podrobné využití zdrojů, zboží a různých výdajů hlavní knihy.

Struktura vrstev umožňuje rozdělit projekt na menší úlohy a proto použijte podrobnější informace v rozpočtování, nabídkách a registraci. Kromě toho vám poskytuje přehled o tom, jak projekt postupuje. Můžete například sledovat, zda jste v souladu s určenými milníky nebo zda jste v rozmezí tak, abyste splnili očekávání rozpočtu.

> [!NOTE]  
>   Akce **Nový projekt** na nástroji **Project manager** v Centru rolí spustí asistované nastavení, které vás provede kroky při vytváření projektu s integrovanými úlohami a řádky plánování. Následující postup popisuje, jak provést kroky ručně.

## <a name="to-create-a-job-card"></a>Vytvoření karty projektu
Vytvořte kartu projektu a potom pro ni vytvořte řádky úloh projektu a řádky plánování projektu.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.  
2. Vyberte akci **Nový** a poté vyplňte pole. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Chcete-li zadat projekt s informacemi z jiných projektů, zvolte akci **Kopírovat Projekt**, vyplňte pole podle potřeby a potom klepněte na tlačítko **OK** .

> [!NOTE]  
>   Pokud používáte časové rozvrhy s vaší prací, musíte také určit odpovědnou osobu. Tato osoba může schvalovat časové rozvrhy pro úkoly zaměstnanců spojené s daným projektem. Další informace naleznete v tématu [Návod: Nastavení časových rozvrhů](projects-how-setup-time-sheets.md)

## <a name="to-create-tasks-for-a-job"></a>Vytvoření činností pro projekt
Klíčovou součástí tvorby projektu je specifikovat různé úlohy spojené s projektem. To lze provést přidáním nových řádků na záložce **Úlohy** v okně **Karta projektu**, jedna úloha na řádek. Každý projekt musí mít alespoň jeden řádek úlohy projektu.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.
2. Otevřete kartu projektu pro příslušný projekt.
3. Na záložce **Úlohy** vyplňte pole podle potřeby na novém řádku.
4. Chcete-li odsadit řádky úloh projektu a vytvořit hierarchii, zvolte akci **Úlohy** a pak zvolte akci **Odsadit úlohy projektu**.
5. Opakujte kroky 3 a 4 pro všechny úlohy, které potřebujete pro daný projekt.
6. Chcete-li zadat úlohy projektu s informacemi o úlohách z jiných projektů, zvolte akci **Kopírovat úlohy projektu**, vyplňte pole podle potřeby a potom klepněte na tlačítko **OK**.

## <a name="to-create-planning-lines-for-a-job"></a>Vytvoření řádků plánování pro projekt
Nové úlohy projektu můžete upřesnit na řádcích plánování projektu. Řádek plánování můžete použít k zachycení všech informací, které chcete sledovat pro daný projekt. Pomocí řádků plánování můžete přidat informace například o tom, jaké jsou potřeba zdroje nebo zachytit, jaké zboží je potřeba k dokončení projektu. Například pokud máte úlohu získat schválení zákazníka na projektu, můžete tuto úlohu spojit s řádky plánování jako je například setkání se zákazníkem a přiřadit zdroje.  

Řádek plánování projektu může mít jeden z následujících typů.  

| Typ | Popis |
| --- | --- |
| **Plán** |Poskytuje odhadovanou spotřebu a náklady na projekt, obvykle v časovém a materiálním typu projektu. Řádky plánování tohoto typu nelze fakturovat. |
| **Fakturovatelné** |Poskytuje odhadovanou fakturaci zákazníkovi obvykle v projektu s pevnou cenou. |
| **Oba typy Plán i Fakturovatelné** |Poskytuje rozpočtovou spotřebu stejně jako to, co chcete fakturovat. |

**Poznámka**. Při zadávání informací na řádcích plánování projektu se automaticky vyplňují informace o nákladech. Například náklady, cena a sleva pro zdroje a zboží jsou zpočátku založeny na informacích, které jsou uvedeny na kartě zboží a zdrojů.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.
2. Otevřete příslušnou kartu projektu.
3. Vyberte úlohu projektu, která v poli **Typ úlohy projektu** obsahuje hodnotu **Účet** a poté vyberte akci **Řádky plánování projektu**.  
4. V okně **Řádky plánování projektu** na novém řádku vyplňte pole podle potřeby.
5. Opakujte kroky 3 a 4 pro všechny řádky plánování, které potřebujete pro úlohu projektu.

## <a name="see-also"></a>Viz také
[Řízení projektů](projects-manage-projects.md)  
[Finance](finance.md)  
[Nákup](purchasing-manage-purchasing.md)         
[Prodej](sales-manage-sales.md)      
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

