---
title: "Návod: Tvorba projektů"
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
ms.openlocfilehash: df34c435d07e9526cb4d93e2bfc30162258ba957
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-jobs"></a>Návod: Tvorba projektů
Když spustíte nový projekt, musíte vytvořit kartu projektu s integrovanými úlohami a řádky plánování projektu, které jsou strukturované ve dvou vrstvách.  

První vrstva se skládá z úloh projektu. Musíte vytvořit alespoň jednu úlohu na projektu, protože veškeré účtování se týká úloh projektu. Pokud máte alespoň jednu úlohu projektu, můžete nastavit řádky plánování projektu a účtovat spotřebu do projektu.

Druhá vrstva se skládá z řádků plánování projektu, které specifikují podrobné využití zdrojů, zboží a různých výdajů hlavní knihy.

Struktura vrstev umožňuje rozdělit projekt na menší úlohy a proto použijte podrobnější informace v rozpočtování, nabídkách a registraci. Kromě toho vám poskytuje přehled o tom, jak projekt postupuje. Můžete například sledovat, zda jste v souladu s určenými milníky nebo zda jste v rozmezí tak, abyste splnili očekávání rozpočtu.

**Poznámka**: Akce **Nový projekt** na nástroji **Project manager** v Centru rolí spustí asistované nastavení, které vás provede kroky při vytváření projektu s integrovanými úlohami a řádky plánování. Následující postup popisuje, jak provést kroky ručně.

## <a name="to-create-a-job-card"></a>Vytvoření karty projektu
Vytvořte kartu projektu a potom pro ni vytvořte řádky úloh projektu a řádky plánování projektu.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.  
2. Vyberte akci **Nový** a poté vyplňte pole. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
3. Chcete-li zadat projekt s informacemi z jiných projektů, zvolte akci **Kopírovat Projekt**, vyplňte pole podle potřeby a potom klepněte na tlačítko **OK** .

**POZNÁMKA**: Pokud používáte časové rozvrhy s vaší prací, musíte také určit odpovědnou osobu. Tato osoba může schvalovat časové rozvrhy pro úkoly zaměstnanců spojené s daným projektem. Další informace naleznete v tématu [Návod: Nastavení časových rozvrhů](projects-how-setup-time-sheets.md).

## <a name="to-create-tasks-for-a-job"></a>Vytvoření činností pro projekt  
Klíčovou součástí tvorby projektu je specifikovat různé úlohy spojené s projektem. To lze provést přidáním nových řádků na záložce **Úlohy** v okně **Karta projektu**, jedna úloha na řádek. Každý projekt musí mít alespoň jeden řádek úlohy projektu.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.
2. Otevřete kartu projektu pro příslušný projekt.
3. Na záložce **Úlohy** vyplňte pole podle potřeby na novém řádku.
4. Chcete-li odsadit řádky úloh projektu a vytvořit hierarchii, zvolte akci **Úlohy** a pak zvolte akci **Odsadit úlohy projektu**.
5. Opakujte kroky 3 a 4 pro všechny úlohy, které potřebujete pro daný projekt.
6. Chcete-li zadat úlohy projektu s informacemi o úlohách z jiných projektů, zvolte akci **Kopírovat úlohy projektu**, vyplňte pole podle potřeby a potom klepněte na tlačítko **OK**.

## <a name="to-create-planning-lines-for-a-job"></a>Vytvoření řádků plánování pro projekt  
Nové úlohy projektu můžete upřesnit na řádcích plánování projektu. Řádek plánování můžete použít k zachycení všech informací, které chcete sledovat pro daný projekt. Pomocí řádků plánování můžete přidat informace například o tom, jaké jsou potřeba zdroje nebo zachytit, jaké zboží je potřeba k dokončení projektu. Například pokud máte úlohu získat schválení zákazníka na projektu, můžete tuto úlohu spojit s řádky plánování jako je například setkání se zákazníkem a přiřadit zdroje.  

Řádek plánování projektu může mít jeden z následujících typů.  

|Typ|Popis|
|----|-----------|
|**Plán**|Poskytuje odhadovanou spotřebu a náklady na projekt, obvykle v časovém a materiálním typu projektu. Řádky plánování tohoto typu nelze fakturovat.|
|**Fakturovatelné**|Poskytuje odhadovanou fakturaci zákazníkovi obvykle v projektu s pevnou cenou.|
|**Oba typy Plán i Fakturovatelné**|Poskytuje rozpočtovou spotřebu stejně jako to, co chcete fakturovat.|  

**Poznámka**. Při zadávání informací na řádcích plánování projektu se automaticky vyplňují informace o nákladech. Například náklady, cena a sleva pro zdroje a zboží jsou zpočátku založeny na informacích, které jsou uvedeny na kartě zboží a zdrojů.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.
2. Otevřete příslušnou kartu projektu.
3. Vyberte úlohu projektu, která v poli **Typ úlohy projektu** obsahuje hodnotu **Účet** a poté vyberte akci **Řádky plánování projektu**.  
4. V okně **Řádky plánování projektu** na novém řádku vyplňte pole podle potřeby.
5. Opakujte kroky 3 a 4 pro všechny řádky plánování, které potřebujete pro úlohu projektu.

## <a name="see-also"></a>Viz také
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Správa prodeje](sales-manage-sales.md)      
[Práce s Dynamics NAV](ui-work-product.md)  

