---
title: "Práce s pracovními výkazy pro projekty"
description: "Popisuje jak vytvořit pracovní výkaz pro projekt, jak do nich kopírovat řádky plánování, definovat typ práce, vyplňovat rozvrh a odesílat odsouhlasení."
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
ms.openlocfilehash: c4a2bc57833af88038d022e2a13cb8a50a4a61f3
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-use-time-sheets-for-jobs"></a>Návod: Použití pracovních výkazů pro projekty
Používáte dávkovou úlohu **Vytvořit pracovní výkazy** pro nastavení pracovních výkazů pro určitý počet časových období nebo týdnů. Abyste mohli vytvářet pracovní výkazy, musíte mít oprávnění.

Můžete kopírovat a používat své řádky plánování projektu v pracovním výkazu. Tímto způsobem musíte zadat informace pouze na jednom místě a informace o řádcích jsou vždy správné.

Poté, co jste pro danou úlohu schválili záznamy pracovních výkazů, můžete je zaúčtovat do příslušného deníku projektu nebo deníku zdrojů.

Než budete moci používat pracovní výkazy, musíte nastavit obecné informace, určit správce a jednoho nebo více schvalovatelů pracovních výkazů. Další informace naleznete v tématu [Návod: Nastavení pracovních výkazů.](projects-how-setup-time-sheets.md)

## <a name="to-create-a-time-sheet"></a>Vytvoření nového pracovního výkazu
Můžete použít dávkovou úlohu **Vytvořit pracovní výkazy** k nastavení pracovních výkazů  pro určitý počet časových období nebo týdnů. Poté může vlastník rozvrhu otevřít a zaznamenat čas, který byl na činnost vynaložen.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Přehled pracovních výkazů** a vyberte související odkaz.
2. V okně **Seznam pracovních výkazů** vyberte akci **Vytvořit pracovní výkazy**.
3. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   Pole **Použít pracovní výkaz** a **ID vlastníka pracovního výkazu** musí být vyplněna na kartě pro zdroj časového listu.

1. Zvolte tlačítko **OK**.  

Můžete zobrazit pracovní výkazy, které jste vytvořili v okně **Seznam pracovních výkazů**.

## <a name="to-copy-job-planning-lines-to-a-time-sheet"></a>Kopírování řádků plánování projektu do časového rozvrhu
Následující postup popisuje, jak rychle přidat řádky plánování projektu do časového rozvrhu.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Přehled pracovních výkazů** a vyberte související odkaz.  
2. V okně **Seznam pracovních výkazů** vyberte časový list příslušného časového období a potom vyberte akci **Upravit pracovní výkaz**.  
3. Zvolte akci **Vytvořit řádek z plánování projektu**. Všechny řádky plánování projektu v časovém období pracovního výkazu jsou zkopírovány do časového rozvrhu pro osobu nebo stroj v poli **Číslo zdroje**

## <a name="to-define-work-types-and-add-one-to-a-time-sheet"></a>Definování typu práce a přidání do pracovního výkazu
Můžete definovat typ práce pro všechny řádky pracovního výkazu pro projekty. Tímto způsobem můžete přidat informace, které je třeba účtovat zákazníkovi za různé druhy práce.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Přehled pracovních výkazů** a vyberte související odkaz.   
2. Otevřít příslušný pracovní výkaz.
3. Zvolte pole **Popis**.  
4. V okně **Podrobnosti o řádku pracovního výkazu projektu** vyberte pole **Kód typu práce** a vyberte typ práce ze seznamu.  
5. Pokud neexistují žádné typy práce, vyberte akci **Nový**.
6. V okně **Typy práce** vyplňte pole podle potřeby.
7. Opakujte krok 4, abyste přiřadili nový typ práce do pracovního výkazu.

## <a name="to-reuse-time-sheet-lines-in-other-time-sheets"></a>Opakované použití řádků pracovního výkazu v jiných pracovních výkazech
Pokud informace o pracovním výkazu zůstanou stejné z časového hlediska na časové období, můžete ušetřit čas kopírováním řádků z předchozího časového období. Poté zadáte vaši spotřebu času pro nové období.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Pracovní výkazy** a vyberte související odkaz.  
2. Otevřít časový list pro dobu delší než je doba pro existující časový list s řádky.  
3. Zvolte akci **Kopírovat řádky z předchozího pracovního výkazu**.

Řádky jsou kopírovány včetně podrobností, jako je typ a popis. Například pokud řádek souvisí s projektem, **Č. projektuje** zkopírováno. Všechny kopírované řádky mají stav **Otevřít**. Nyní můžete upravovat řádky podle potřeby.

## <a name="to-fill-in-a-time-sheet-lines-and-submit-for-approval"></a>Vyplnění řádků časového listu a odeslání je ke schválení
Registrace pracovního výkazu je sledována v hodinách, což je standardní základní měrná jednotka pro zdroje. Ve výchozím nastavení se v pracovním výkazu zobrazují běžné pracovní dny od pondělí do pátku.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Pracovní výkazy** a vyberte související odkaz.  
2. Vyberte časový rozvrh pro příslušné časové období a potom zvolte akci **Upravit pracovní výkaz**.  
3. Vyplňte pole na řádku podle potřeby. Zadejte počet hodin používaných zdrojem pro každý den v týdnu.

    > [!TIP]  
>   Můžete si prohlédnout součet hodin pracovního výkazu, které jste zadali do okna s fakty **Aktuální/Rozpočtový souhrn**.  
4. Opakujte krok 3 pro ostatní typy práce, které zdroj provádí.
5. Zvolte akci **Odeslat** a potom vyberte akci **Všechny otevřené řádky**, chcete-li odeslat všechny řádky nebo akci **Pouze vybrané řádky**, abyste odeslali pouze řádky, které jsou vybrány v okně **Pracovní výkaz**.  

    > [!NOTE]  
>   Můžete odesílat pouze řádky pracovních výkazů, pro které jste zadali čas.  
6. Chcete-li upravit informace na řádku, který byl nastaven na **Odesláno**, vyberte řádek a poté zvolte akci **Znovu otevřít**.

    > [!NOTE]  
>   Správce může odmítnout řádek pracovního výkazu, který je předložen ke schválení. Pokud má řádek stav **Odmítnuto**, můžete provést změny řádku a poté znovu vybrat možnost **Odeslat**.  
7. Zvolte tlačítko **OK**.

## <a name="to-approve-or-reject-a-time-sheet"></a>Schválení nebo odmítnutí pracovního výkazu
Pracovní výkaz musí být před použitím předložen ke schválení. Jednotlivé řádky můžete schválit a odmítnout na pracovním výkazu nebo je poslat zpět zadavateli pro další akce. Pracovní výkaz lze schválit dvěma způsoby:

* Správce pracovního výkazu může schvalovat libovolný pracovní výkaz.
* Osoba, která je uvedena v poli **ID schavalovatele pracovního výkazu** na kartě zdroje, může schválit Pracovní výkazy tohoto zdroje. Další informace naleznete v tématu [Návod: Nastavení pracovních výkazů.](projects-how-setup-time-sheets.md)

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Správce pracovních výkazů** a vyberte související odkaz.
2. Vyberte pracovní výkaz ze seznamu.  
3. V okně **Pracovní výkaz** vyberte akci **Schválení** a poté vyberte akci **Všechny odeslané řádky** pro schválení všech řádků nebo akci **Pouze vybrané řádky** pro schválení pouze řádků, které jste vybrali v okně **Pracovní výkaz**.
4. Zvolte tlačítko **OK**.  
5. Nebo zvolte akci **Odmítnout** a postupujte podle kroků 4 až 5.  

> [!TIP]  
>   Použijte Factboxy **Stav pracovního výkazu** a **Aktuální/Rozpočtový Souhrn** pro získání přehledu o pracovních výkazech.

Poté, co schválíte nebo odmítnete pracovní výkaz, nelze jej změnit, dokud nebude znovu otevřen. Následující postup vysvětluje, jak znovu otevřít schválený nebo zamítnutý pracovní výkaz.

## <a name="to-reopen-a-time-sheet"></a>Opětovné otevření pracovního výkazu
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Správce pracovních výkazů** a vyberte související odkaz.
2. Otevřete časový rozvrh ze seznamu.  

    > [!NOTE]  
>   Můžete pouze znovu otevřít řádky, které mají stav **Schváleno**. Nemůžete znovu otevřít řádky, které mají stav **Odmítnuto**. Pokud jste již zaúčtovali pracovní výkaz, nelze jej znovu otevřít.  
3. V okně **Pracovní výkaz** vyberte akci **Opětovné otevření** a poté vyberte akci **Všechny odeslané řádky**, chcete-li znovu otevřít všechny řádky nebo akci **Pouze vybrané řádky**, abyste znovu otevřeli pouze řádky, které jsou vybrány v okně **Pracovná výkaz**.
4. Zvolte tlačítko **OK**. Stav řádku nebo řádků pracovních výkazů je změněn na **Odesláno**.  

## <a name="to-post-time-sheet-lines-in-a-resource-journal"></a>Zaúčtování řádků pracovního výkazu v deníku zdrojů
Po schválení položek pracovního výkazu pro zdroj je můžete zaúčtovat do příslušného deníku zdrojů.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky zdrojů** a vyberte související odkaz.  
2. Zvolte akci **Navrhnout řádky z pracovních výkazů**.  
3. Vyplňte pole dle potřeby.  
4. Zvolte tlačítko **OK**. Položky pro spotřebu jsou vytvořeny v deníku zdrojů, kde je možné upravit informace podle potřeby.  
5. Zvolte akci **Zaúčtovat**.  
6. Chcete-li ověřit účtování, zvolte akci **Věcné položky**. Okno **Položky zdrojů** zobrazuje výsledek účtování deníku zdrojů.

## <a name="to-post-time-sheet-lines-in-a-job-journal"></a>Zaúčtování řádků pracovního výkazu v deníku projektu
Poté, co schválíte položky pracovních výkazů pro projekt, můžete je zaúčtovat do příslušného deníku projektu.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky projektů** a vyberte související odkaz.  
2. Zvolte akci **Navrhnout řádky z pracovních výkazů**.  
3. Vyplňte pole dle potřeby.  
4. Zvolte tlačítko **OK**. Položky spotřeby jsou vytvořeny v deníku projektu, kde je možné podle potřeby upravit informace.  

    > [!NOTE]  
>   Informace o typu práce a o tom, zda je práce fakturovatelná, je zkopírována z řádku pracovního výkazu. V případě potřeby můžete počet hodin snížit a částečně zaúčtovat. Pokud snížíte množství, potom při vybrání akce **Navrhnout řádky z pracovního výkazu**, bude vytvořený řádek obsahovat zbývající množství hodin.  
5. Zvolte akci **Zaúčtovat**.  
6. Chcete-li ověřit účtování, zvolte akci **Věcné položky**. Otevře se okno **Položky projektu**, které zobrazuje výsledek účtování deníku zdrojů.

## <a name="to-archive-time-sheets"></a>Archiv pracovních výkazů
Po zaúčtování pracovních výkazů je můžete archivovat pro budoucí použití. Všechny řádky pracovních výkazů musí být zaúčtovány před archivací pracovního výkazu.

> [!NOTE]  
>   Při archivaci pracovního výkazu je ze seznamů odstraněn v těchto dvou oknech **Pracovní výkaz** a **Správce pracovních výkazů**.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Přesunou pracovní výkazy do archivu** a vyberte související odkaz.  
2. Vyplňte pole a poté klepněte na tlačítko **OK**.  
3. Chcete-li si prohlédnout archivované pracovní výkazy, v pravém horním rohu zvolte ikonu ![Vyhledat stránku nebo sestavu], zadejte **Archiv pracovních výkazů** nebo **Archivy časového listu správce** a vyberte příslušný odkaz.

## <a name="see-also"></a>Viz také
[Řízení projektů](projects-manage-projects.md)  
[Nastavení Správy vztahů](projects-setup-projects.md)    
[Finance](finance.md)  
[Nákup](purchasing-manage-purchasing.md)         
[Prodej](sales-manage-sales.md)     
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

