---
title: "Návod: Nastavení Projektů"
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
ms.openlocfilehash: ce9c980caf73a36b3e2c7d07141b096fcff06590
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-jobs"></a>Návod: Nastavení Projektů
V okně **Nastavení projektů** musíte určit, jak chcete používat určité funkce projektu.

Na jednotlivých kartách projektu musíte nastavit ceny pro položky projektu, zdroje a finanční účty projektu, zároveň musíte nastavit účto skupiny projektu.

## <a name="to-set-general-information-for-jobs"></a>Nastavení obecných informací pro projekty
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu** , zadejte **Nastavení projektů** a zvolte související odkaz.
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.

**Poznámka**: Zaškrtávací políčko **Apply Usage Link** je poměrně složité, a proto je vysvětleno v následující části.

## <a name="to-set-up-job-usage-tracking"></a>Nastavení sledování spotřeby projektu
Když pracujete na projektu, možná budete chtít vědět, jak spotřeba odpovídá vašemu plánu. Abyste to mohli snadno udělat, můžete vytvořit spojení mezi vašimi řádky plánování a skutečnou spotřebou. To vám umožní sledovat vaše náklady a snadno zjistit, kolik práce je třeba udělat. Ve výchozím nastavení je typ řádku plánování **Rozpočet** , ale použití typu řádku **Rozpočet a Fakturace** má podobný efekt.

Pokud zaškrtnete políčko **Apply Usage Link** , můžete zobrazit informace o řádku plánování projektu. Můžete nastavit množství zdrojů, zboží nebo finančních účtů a pak uvést, jaké množství chcete převést do deníku projektu. Pole **Zbývající množství** na řádku plánování projektu vám poví, co má být zbývá přenést a zaúčtovat do deníku projektu.

Pokud je zaškrtnuto políčko **Apply Usage Link** a typ řádku plánování projektu je **Fakturovatelný** , Finance vytvoří řádek plánování projektu typu **Rozpočet** poté, co zaúčtujete řádek deníku.

**Poznámka**: Pokud je zaškrtnuto políčko **Apply Usage Link** na kartě projektu a pole **Typ řádku** na řádku deníku projektu je prázdné, tak se nové řádky plánování projektu typu **Rozpočet** vytvoří když zaúčtujete řádky deníku projektu. Pokud není zaškrtnuto políčko **Apply Usage Link** na kartě projektu a pole **Typ řádku** na řádku deníku projektu je prázdné, potom se řádky plánování projektu nevytvoří když zaúčtujete řádky deníku projektu. Pro další informace, viz [Návod: Záznam spotřeby pro Projekty](projects-how-record-job-usage.md) .

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu** , zadejte **Nastavení projektů** a zvolte související odkaz.
2. Zaškrtněte nebo zrušte zaškrtnutí políčka **Apply Usage Link** .

**Poznámka**: Můžete provést jiné nastavení zaškrtávacího pole **Apply Usage Link** jednotlivých kartách projektu. V takovém případě nastavení pro tento projekt přepíše obecné výchozí hodnoty popsané výše.

## <a name="to-set-up-prices-for-job-resources"></a>Nastavení cen zdrojů projektu  
Můžete nastavit konkrétní ceny zdrojů pro projekt. K tomu použijte okno **Ceny zdrojů projektu** .

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.  
2. Vyberte příslušný projekt a poté vyberte akci **Zdroj** .
3. V okně **Ceny zdrojů projektu** vyplňte pole podle potřeby.

Volitelná informace v polích **Č. činnosti projektu** , **Typ práce** , **Kód měny** , **Řádková sleva %** a **Faktor pořízovací ceny** budou použita na řádcích plánování projektu a v deníku spotřeby, když je tento zdroj zadán a přidán do projektu.  

Hodnota v poli **Jednotková cena** pro zdroj bude použita na řádcích plánování projektu a deníků projektu, když je tento zdroj přiřazen ke skupině zdrojů nebo jakémukoli zdroji zadán.  

**Poznámka**: Tato cena vždy přepisuje všechny ceny stanovené ve stávajícím okně **Ceny zdrojů / skupin zdrojů** .

## <a name="to-set-up-prices-for-job-items"></a>Nastavení cen pro položky projektu  
Můžete nastavit konkrétní ceny zboží pro projekt. Chcete-li to provést, použijte okno **Ceny položek projektu** .

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.  
2. Vyberte příslušný projekt a poté vyberte akci **Položka** .
3. V okně **Ceny položek projektu** vyplňte pole podle potřeby.

Volitelné informace v polích **Č. činnosti projektu** , **Kód měny** a **Řádková sleva %** budou použity v řádcích plánování projektu a deníku projektu při zadání nebo přidání této položky do projektu.  

Hodnota v poli **Jednotková cena** pro danou položku bude použita na řádcích plánování projektu a denících projektu při zadání této položky.  

**Poznámka**: Tato cena bude vždy převyšovat běžnou cenu zákazníka (mechanismus "nejlepší ceny") pro zboží. Chcete-li použít obvyklé mechanismy zákaznických cen, neměli byste pro daný projekt vytvářet žádné cenové položky.

## <a name="to-set-up-prices-for-job-general-ledger-accounts"></a>Nastavení cen pro finanční účty projektu  
Můžete nastavit konkrétní ceny pro finanční výdaje projektu K tomu použijete okno **Ceny Finančního účtu projektu** .

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.  
2. Vyberte příslušný projekt a poté vyberte akci **Finanční účet** .  
3. V okně **Ceny Finančního účtu projektu** vyplňte pole podle potřeby.

Nepovinné informace v poli **Č. činnosti projektu** , **Kód měny** , **Řádková sleva %** , **Faktor pořizovací ceny** a **Jednotkové náklady** budou použity na řádcích plánování projektu a v denících projektu, když je tento finanční účet vložen a přidán do projektu.  

Hodnota v poli **Jednotková cena** pro finanční výdaje projektu bude použita na řádcích plánování projektu a denících projektu při zadání tohoto finančního účtu.

## <a name="to-set-up-job-posting-groups"></a>Nastavení účto skupin projektu  
Jedním z aspektů plánování projektů je rozhodování o účtování účtů, které se mají použít při kalkulaci projektu. Chcete-li zaúčtovat projekty, nastavte účty pro účtování pro každou účto skupinu projektu. Účto skupina představuje vazbu mezi tímto projektem a tím, jak by měla být zpracována v hlavní knize. Při vytváření projektu určíte účto skupinu a ve výchozím nastavení je každá činnost vytvořená pro projekt přidružena k této účto skupině. Avšak jakmile vytváříte činnost, můžete výchozí hodnotu přepsat a zvolit vhodnější účto skupinu.  

**Poznámka**: Potřebné účty v účetní osnově musí být nastaveny před nastavením účto skupin. Další informace naleznete v části [Nastavení nebo změna Účetní osnovy](finance-setup-setup-chart-accounts.md).  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účto skupiny projektu** a pak vyberte související odkaz.  
2. Vyberte akci **Nový** a poté vyplňte pole účtu tak, jak popisuje následující tabulka.  

|Pole účtu|Popis|
|-------------|-----------|
|**Kód**|Určuje kód účto skupiny. Můžete zadat až 10 znaků, včetně mezer.|  
|**Účet NV**|Účet NV pro vypočítané náklady na NV projektu, což je rozvahový účet kapitálového majetku.|
|**Účet s časovým rozlišením nákladů NV**|Účet pro Hodnotu nákladů nebo Nákladovou prodejní metodu výpočtu NV, což je rozvahový účet s časovým rozlišením výdajů. Toto bude zaúčtováno, až bude úprava NV vyžadovat, aby náklady na využití účtované do výkazu zisku a ztráty byly zvýšeny.|  
|**Účet použitých nákladů projektu**|Vyrovnávací účet k účtu nákladů NV, což je protihodnota pro účet záporných výdajů.|
|**Účet použitých nákladů položky**|Vyrovnávací účet k účtu nákladů NV, což je protihodnota pro účet záporných výdajů.|
|**Účet použitých nákladů na zdroje**|Vyrovnávací účet k účtu nákladů NV, což je protihodnota pro účet záporných výdajů.|
|**Účet použitých nákladů projektu**|Vyrovnávací účet k účtu nákladů NV, což je protihodnota pro účet záporných výdajů.|
|**Účet úpravy nákladů na projekt**|Vyrovnávací účet k účtu NV s časovým rozlišením nákladů, což je výdajový účet.|
|**Finanční účet Výdaje (Rozpočet)**|Prodejní účet, který bude použit pro výdaje hlavní knihy v činnostech projektu s touto účto skupinou. Pokud je ponecháno prázdné, použije se účet hlavní knihy zadaný v řádku plánování projektu.|
|**Účet NV s časovým rozlišením prodeje**|Účet NV pro vypočítanou hodnotu prodeje NV, což je rozvahový účet s časovým rozlišením příjmů. Toto je zaúčtováno, když úprava NV vyžaduje, aby se zvýšil uznaný příjem.|
|**Účet fakturovaných výnosů NV**|Účet fakturované hodnoty prodeje NV, který nelze rozpoznat. Jedná se o rozvahový účet nerozdělených výnosů.|
|**Účet použitých výnosů projektu**|Určuje zůstatkový účet pro účet fakturovaných výnosů NV, je obvykle protiúčet příjmů.|
|**Účet adjustace výnosů projektu**|Vyrovnávací účet k prodejnímu účtu NV projektu, což je příjmový účet.|
|**Účet uznaných nákladů**|Výdajový účet, který obsahuje uznané náklady na projekt. Je to běžný debetní účet.|
|**Rozpoznaný prodejní účet**|Účet příjmů, který obsahuje uznaný příjem za projekt. Jedná se obvykle o účet úvěrových výnosů.|

## <a name="see-also"></a>Viz také
[Nastavit řízení projektu](projects-setup-projects.md)  
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Spravovat prodej](sales-manage-sales.md)      
[Pracujte s Dynamics NAV](ui-work-product.md)  
