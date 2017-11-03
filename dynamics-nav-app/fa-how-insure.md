---
title: "Pojištění dlouhodobého majetku"
Description: "Můžete přiřadit dlouhodobý majetek k pojistné smlouvě, kterou představuje pojišťovací karta."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: policy, coverage
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b4e6733454a56396daa4bbbc817e1bbcde9dec46
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-insure-fixed-assets"></a>Návod: Pojištění dlouhodobého majetku
Pojistnou smlouvu na dlouhodobý majetek představuje pojišťovací karta. Můžete přiřadit jeden dlouhodobý majetek k jedné pojistné smlouvě nebo více DM k jedné pojistné smlouvě.

Do pojistné smlouvy přidělíte dlouhodobý majetek zaúčtováním do knihy pojištění v okně **Deník pojištění**.

Kromě toho můžete přiřadit dlouhodobý majetek k pojistné smlouvě a vytvářet položky záznamu pokrytí, když zaúčtujete pořizovací cenu. To provedete tím, že zaúčtujete pořizovací cenu z deníku DM s vyplněným polem **Číslo pojištění**. Zaškrtávací políčko **Automatické účtování pojištění** v okně **Nastavení DM** musí být vybráno. Další informace naleznete v tématu "Zaúčtování pořízení DM ručně s dlouhodobým majetkem finančního deníku“ v [Návod: Získání DM](fa-how-acquire.md).

Pokud není zaškrtnuto políčko **Automatické účtování pojištění** v okně **Nastavení DM**, pak zaúčtování pořízení z deníku DM vytvoří řádky v okně **Deník pojištění**, které musíte následně ručně zaúčtovat.

> [!WARNING]  
>   Pokud zaškrtávací políčko **Automatické účtování pojištění** nezvolíte v okně **Nastavení DM**, pak by měl váš deník pojištění vycházet z šablony deníku bez číselné řady. Je tomu tak proto, že vložené čísla dokumentů z řádků deníku DM budou jinak v rozporu s číselnou řadou deníku pojištění. Další informace o šablonách deníku a dávkách naleznete v tématu [Návod: Nastavení obecných informací dlouhodobého majetku](fa-how-setup-general.md).

Po přidělení DM do pojistné smlouvy je zaškrtnuto políčko **Pojištěno** na kartě DM. Při prodeji DM se zaškrtávací políčko automaticky zruší.

## <a name="to-create-or-modify-an-insurance-card"></a>Vytvoření nebo změna pojistné karty
Pojistná smlouva na dlouhodobý majetek musí představovat pojistná karta.

Pokud obdržíte informace o změnách výše pokrytí, musíte v okně **Pojistné karty** zadat nové informace, abyste zajistili, že budete správně analyzovat pokrytí pojištění.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Pojištění** a pak vyberte související odkaz.
2. Zvolte akci **Nový** pro vytvoření nové karty pojistné smlouvy. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Případně vyberte pojistnou smlouvu, kterou chcete změnit a pak vyberte akci **Upravit**.

## <a name="to-assign-a-fixed-asset-to-an-insurance-policy-by-posting-from-the-insurance-journal"></a>Přidělení DM k pojistné smlouvě zaúčtováním z deníku pojištění
Přidělíte dlouhodobý majetek k pojistné smlouvě zaúčtováním do knihy pojištění.  

Následující postup vysvětluje, jak ručně vytvořit řádek pojistného deníku. Pokud je zaškrtnuto políčko **Automatické účtování pojištění**, které je v okně **Nastavení DM**, pak se řádky deníku pojištění automaticky vytvoří, když zaúčtujete pořizovací cenu. V takovém případě stačí uvést deník.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deník pojištění** a pak vyberte související odkaz.  
2. Otevřete příslušný deník a v případě potřeby vyplňte řádky deníku.  
3. Chcete-li přiřadit více DM k jedné pojistné smlouvě, vytvořte řádky deníků se stejnou hodnotou v poli **Číslo pojištění** a různé hodnoty v poli **Číslo DM**.  
4. Zvolte akci **Zaúčtovat**.  

    > [!NOTE]  
>   Položky z deníku pojištění jsou zaúčtovány pouze do knihy pojištění.  

## <a name="to-update-the-insurance-value-of-a-fixed-asset"></a>Aktualizace ceny pojištění DM
Můžete použít dávkovou úlohu **Indexovat pojištění** k aktualizaci hodnoty DM, který je pokryt.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Požadavky ke schválení** a pak vyberte související odkaz.
2. Vyplňte pole dle potřeby.

    > [!NOTE]  
>   V poli **Hodnota indexu** zadejte snížení o 5%, například 95, zatímco zadáte zvýšení o 2% jako 102.  
3. Zvolte tlačítko **OK**.  

   Dávková úloha vypočítává novou částku jako procento z celkové pojistné hodnoty, jak je uvedeno v okně **Statistika pojištění** a poté vytvoří řádky v pojistném deníku.  
4. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Požadavky ke schválení** a pak vyberte související odkaz.  
5. Otevřete příslušný deník pojištění, zkontrolujte vytvořené hodnoty a poté je zaúčtujte do knihy pojištění.  

## <a name="to-monitor-insurance-coverage"></a>Monitorování pojistného krytí
[!INCLUDE[d365fin](includes/d365fin_md.md)] poskytuje specializované přehledy a statistiky, které se používají při analýze pojistných smluv a zda vaše dlouhodobá aktiva jsou nadměrně nebo nedostatečně pojištěná.  

### <a name="overview-of-insurance-policies"></a>Přehled pojistných smluv
Chcete-li získat přehled o vašich pojistných smlouvách, přečtěte si náhled nebo vytiskněte **Přehled pojištění**. Přehled obsahuje všechny smlouvy a nejdůležitější pole z pojistných karet.  

### <a name="insurance-coverage"></a>Pojistné krytí
Chcete-li zjistit, které pojistné smlouvy pokrývají jednotlivý majetek a jakou částkou, můžete si zobrazit nebo vytisknout sestavu **Pojištění-celk.hodnota poj.**.  

### <a name="overunder-coverage"></a>Předimenzované nebo poddimenzované krytí
Můžete zkontrolovat, zda je dlouhodobý majetek nadměrně nebo nedostatečně pojištěn následujícími způsoby:  

* Okno **Statistika pojištění**. Pozitivní částka v poli **Předimenzované nebo poddimenzované pojištění** znamená, že dlouhodobý majetek je nadbytečně pojištěn. Záporná částka znamená, že je nedostatečně pojištěn.  
* V okně **Statistika DM** zvolte pole **Celková pojištěná částka** pro zobrazení okna **Položky pojistného krytí**.  
* Sestava **Předimenzované nebo poddimenzované krytí**.  
* Sestava **Analýza pojištění**.  

### <a name="uninsured-fixed-assets"></a>Nepojištěný dlouhodobý majetek
Chcete-li zkontrolovat, zda jste nezapomněli přiřadit dlouhodobý majetek k pojistné smlouvě, můžete vytisknout nebo zobrazit náhled sestavy **Pojištěný - Nepojištěný DM**. V této zprávě je zobrazen dlouhodobý majetek, jejichž částky nebyly zaúčtovány do knihy pojištění.  

## <a name="to-view-insurance-coverage-ledger-entries"></a>Zobrazení položek knihy o pojištění
Můžete si prohlédnout položky, které jste provedli v knize pojištění.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Pojištění** a pak vyberte související odkaz.  
2. Vyberte příslušnou pojistnou smlouvu a poté zvolte akci **Položky krytí**.  

## <a name="to-view-the-total-insurance-value-of-fixed-assets"></a>Zobrazení celkové pojistné hodnoty DM
Zvláštní maticové okno zobrazuje pojistné hodnoty, které jsou registrovány pro každou pojistku pro každé dlouhodobé aktivum v důsledku částek souvisejících s pojištěním, které jste zveřejnili.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Pojištění** a pak vyberte související odkaz.  
2. Vyberte příslušnou pojistnou smlouvu a poté zvolte akci **Celková hodnota pojištění na DM**.  
3. Vyplňte pole dle potřeby.  
4. Zvolte akci **Zobrazit matici**.  
5. Chcete-li zobrazit základní položky účtů pojištění, vyberte hodnotu v matici.  

## <a name="to-correct-insurance-coverage-entries"></a>Opravení položek pojištění
Je-li k nesprávné pojistné smlouvě připojen dlouhodobý majetek, můžete ho opravit vytvořením dvou položek z deníku pojištění.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deník pojištění** a pak vyberte související odkaz.  
2. Vytvořte jeden řádek deníku pro dlouhodobý majetek a správnou pojistku, kde je hodnota v poli **Částka** kladná.  
3. Vytvořte jiný řádek deníku pro dlouhodobý majetek a nesprávnou pojistku, kde je hodnota v poli **Částka** záporná.  
4. Zvolte akci **Zaúčtovat**.  

Dlouhodobý majetek bude odpojen od nesprávné pojistky na druhém řádku a připojen ke správné pojistné smlouvě na prvním řádku.  

## <a name="see-also"></a>Viz také
[Dlouhodobý majetek](fa-manage.md)  
[Nastavení dlouhodobého majetku](fa-setup.md)  
[Finance](finance.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

