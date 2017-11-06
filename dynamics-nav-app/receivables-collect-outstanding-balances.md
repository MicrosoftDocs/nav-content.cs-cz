---
title: "Připomenutí nebo pokutování zákazníků z prodlení"
description: "Popisuje jjak poslat připomínku zákazníkovi o platbě, která je po splatnosti a poplatku za zpoždění."
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment due, debt, overdue, fee, charge, reminder
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: e7543ab169a1a6ab16c9fdf0afdec88b7749d717
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-collect-outstanding-balances"></a>Návod: Shromáždění zbývajících zůstatků
Správa pohledávek zahrnuje kontrolu, zda jsou splatné částky uhrazeny včas. Pokud mají zákazníci platby po lhůtě splatnosti, můžete poslat zákazníkovi výkaz jako připomenutí. Alternativně můžete vydat upozornění.

Můžete používat upomínky k upozornění zákazníků o prodlení. Také můžete použít připomenutí k kalkulaci finančních poplatků, jako jsou úroky, poplatky a zahrnout je do připomenutí. Používejte penále, pokud chcete inkasovat zákazníky za úroky nebo poplatky, aniž byste jim připomínali splatné částky.  

## <a name="reminders"></a>Upomínky
Předtím, než vytvoříte upomínku, musíte nastavit pravidla a ty nastavit k vašim zákazníkům Každé pravidlo má předdefinované úrovně. Každá úroveň upomínky obsahuje pravidla, podle kterých budou vystaveny. Například, kolik dnů po splatnosti faktury nebo kolik dnů uplyne od poslední upomínky.  Obsah okna **Podmínky penále** určuje, zda se na připomenutí vypočítá úročení.  

Pravidelně můžete spustit dávkovou úlohu **Vytvořit upomínky**, abyste vytvořili připomenutí pro všechny zákazníky se se zůstatky po splatnosti, nebo můžete ručně vytvořit připomenutí pro konkrétního zákazníka a automaticky vypočítat a vyplnit řádky.  

Po vytvoření upomínek je můžete také upravit. Text, který se zobrazí na začátku a na konci připomenutí, je určen podmínkami úrovně upomínky a může být viděn ve sloupci **Popis**. Pokud byla vypočtená částka automaticky vložena do začátku nebo konce textu, nebude text upraven, pokud odstraníte řádky. Potom musíte použít funkci **Aktualizovat text upomínky**.  

Věcné položky zákazníka s vyplněným polem **Vyčkat** nevyvolá vytvoření připomenutí. Je-li však připomenutí vytvořeno na základě jiného záznamu, do připomenutí bude také zahrnut pozdržený záznam označený jako podržený. Úroky se nezapočítávají na řádky s těmito údaji.

Po vytvoření připomenutí a provádění potřebných úprav můžete buď vytisknout jako zkušební sestavy, nebo vytisknout připomenutí, obvykle jako e-mail.

## <a name="finance-charges"></a>Finanční poplatky
Pokud zákazník zaplatí do splatnosti, můžete automaticky vypočítat finanční náklady a přidat je na částky po splatnosti na účtu zákazníka. Zákazníky můžete informovat o přidání poplatku posláním zprávy o penále.  

> [!NOTE]  
> Můžete použít penále k vypočítání úrokových a finančních nákladů a informovali své zákazníky o úrocích a finančních poplatcích, aniž byste jim připomínali platby po lhůtě splatnosti. Případně můžete vypočítat úroky z prodlení při vytváření upomínek.  

Manuálně můžete vytvořit penále pro individuálního zákazníka a vyplní se řádky automaticky. Případně můžete použít úlohu funkce **Vytvořit penále**, abyste vytvořili poznámky o finančních poplatcích pro všechny nebo vybrané zákazníky se zhoršenými zůstatky.  

Po vytvoření penále je můžete také upravit. Text, který se zobrazí na začátku a na konci penále, je určen podmínkami úrovněmi pravidel a může být viděn ve sloupci **Popis**. Pokud byla vypočtená částka automaticky vložena do začátku nebo konce textu, nebude text upraven, pokud odstraníte řádky. Potom musíte použít funkci **Aktualizovat text penále**.  

Po vytvoření penále a provádění potřebných úprav můžete buď vytisknout jako zkušební sestavy, nebo vytisknout penále, obvykle jako e-mail.  

## <a name="to-send-the-customer-statement-report"></a>Odesílání Výkazu zákazníka
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Výkaz zákazníka** a vyberte související odkaz.
2. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Pod **Výstupní možnosti** vyberte, jak odeslat sestavu zákazníkovi.

> [!NOTE]  
>   Pokud používáte více měn, sestava výkaz zákazníka je vždy vytištěna v měně zákazníka. Poslední datum ve výkazovém období se také používá jako datum výpisu a datum pásma splatnosti, pokud jsou pásma splatnosti zahrnuta.

## <a name="to-set-up-reminder-terms"></a>Nastavení podmínek upomínky
Pokud mají zákazníci platbu po splatnosti, musíte se rozhodnout, kdy a jak jim poslat připomenutí. Kromě toho můžete chtít své účty debetovat za úroky nebo poplatky. Můžete nastavit jakýkoli počet podmínek upomínky U každého kódu připomínek můžete definovat neomezený počet úrovní upomínky.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Podmínky upomínky** a vyberte související odkaz.  
2. Vyplňte pole dle potřeby.  
3. Chcete-li použít více než jednu kombinaci podmínek upomínky, nastavte kód pro každou z nich.

## <a name="to-set-up-reminder-levels"></a>Nastavení úrovní podmínek upomínky
Při prvním vytvoření upomínky pro zákazníka se použije nastavení z úrovně 1. Po vydání upozornění je číslo úrovně registrováno v položkách připomenutí, které jsou vytvořeny a propojeny s jednotlivými položkami zákazníků. Pokud je třeba zákazníkovi znovu připomenout, všechny položky připomenutí spojené s otevřenými položkami zákazníků se kontrolují, aby se zjistilo číslo nejvyšší úrovně Podmínky z další úrovně budou použity jako nové upozornění.

Pokud vytvoříte více upomínek, které máte pro různé úrovně, budou použity ty s tou nejvyšší. Můžete vytvořit tolik připomínek, kolik to umožňuje pole **Max.počet upomínek** v podmínkách upomínek.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Podmínky upomínky** a vyberte související odkaz.  
2. V okně **Podmínky upomínky** vyberte řádek s podmínkou kterou chcete nastavit pro úroveň a zvolte akci **Úrovně**.  
3. Vyplňte pole dle potřeby.  

    Pro každou úroveň připomenutí můžete zadat jednotlivé podmínky, které mohou zahrnovat další poplatky v lokální i v cizí měně Můžete definovat mnoho příplatků v cizích měnách pro každý kód v okně **Úrovně upomínky**.
4. Zvolte akci **Měny**.
5. V okně **Měny pro úroveň upomínky** definujte pro každý kód úrovně upomínky a odpovídající číslo úrovně upomínky kód měny a další poplatek.

    > [!NOTE]  
    > Když vytvoříte připomenutí v cizí měně, podmínky cizí měny, které zde nastavíte, budou použity k vytvoření upomínky. Pokud nejsou nastaveny žádné podmínky pro upomínky v cizí měně, použijí se podmínky připomínání lokální měny, které jsou nastaveny v okně **Úrovně upomínky**, a pak se převedou na příslušnou měnu.

    Pro každou úroveň, můžete specifikovat text, který bude vytištěn před (**Text na začátku**) a po (**Text na konci**) na každé položce upomínky

6. Zvolte akce **Text na začátku** nebo **Text na konci** a vyplňte okno **Text upomínky**.
7. K automatickému vyplnění souvisejících řádků v textu upomínky vlože následující zástupné symboly do pole **Text**.  

|Zástupný znak|Hodnota|  
|-----------------|-----------|  
|%1|Obsah pole **Datum dokladu** na hlavičce upomínky|  
|%2|Obsah pole **Datum splatnosti** na hlavičce upomínky|  
|%3|Obsah pole **Úroková sazba** v souvisejících podmínkách penále|  
|%4|Obsah pole **Zbývající částka** na hlavičce upomínky|  
|%5|Obsah pole **Částka úroku** na hlavičce upomínky|  
|%6|Obsah pole **Poplatek** na hlavičce upomínky|  
|%7|Celková částka upomínky|  
|%8|Obsah pole **Úroveň upomínky** na hlavičce upomínky|  
|%9|Obsah pole **Kód měny** na hlavičce upomínky|  
|%10|Obsah pole **Zúčtovací datum** na hlavičce upomínky|  
|%11|Název Společnosti|  
|%12|Obsah pole** Poplatek na řádku** na hlavičce upomínky|  

Například, pokud napíšete **Dlužíte %9 %7 splatné %2.**, pak výsledná upomínka bude obsahovat následující text: **Dlužíte USD 1200,50 splatné 02-02-2014**

Po nastavení podmínek upomínek s dodatečnými úrovni textu, zadejte jeden z kódů na každou kartu zákazníka. Další informace naleznete v tématu [Návod: Registrace nového zákazníka.](sales-how-register-new-customers.md)

## <a name="to-create-a-reminder-automatically"></a>Vytvoření upomínky automaticky
Upomínka je podobná faktuře. Když vytváříte upomínky, hlavička upomínky tak jako více upomínek musí být vyplněna. Můžete použít funkci vytvořit upomínky automaticky pro všechny zákazníky

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Upomínky** a vyberte související odkaz.
2. V okně **Upomínka** zvolte akci **Vytvořit upomínku**.
3. V okně** Upomínka** vyplňte pole k definování jak a komu bude upomínka vytvořena.
4. Zvolte tlačítko **OK**.

## <a name="to-create-a-reminder-manually"></a>Vytvoření upomínky ručně
V okně **upomínky**, můžete vyplnit záložku **Obecné** ručně a potom  budou řádky vyplněny automaticky

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Upomínky** a vyberte související odkaz.
2. Vyberte akci **Nový**.
3. Na záložce s náhledem **Obecné** vyplňte pole podle potřeby.
4. Vyberte tlačítko **Navrhnout řádky upomínky...**.
5. V dávkové úloze **Navrhnout řádky upomínky...** vyplňte pole k definování jak a komu bude upomínka vytvořena.
6. Vyberte check box **Zahrnout podržené položky** pokud chcete, aby upomínky obsahovali zpožděné položky.

    > [!Important]
    > Otevřené položky, které jsou podrženy, budou vloženy bez ohledu na nastavení v políčku Pouze položky se splatnými částkami.

7. Zvolte tlačítko **OK**.

## <a name="to-replace-reminder-texts"></a>Nahrazení textu upomínky  
Existuje několik způsobů, jak určit text, který se zobrazí na zobrazené upomínce. V některých případech možná budete chtít nahradit počáteční a koncové texty, které byly pro aktuální úroveň nahrazeny texty z jiné úrovně.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Upomínky** a vyberte související odkaz.
2. Otevřete příslušné upozornění a poté vyberte akci **Aktualizovat text upomínky**.
3. V okně **Aktualizovat text upomínky** vložte požadované úrovně v poli **Úroveň upomínky**.
3. Zvolte tlačítko **OK** k aktualizaci Textu na začátku a konci.

## <a name="to-issue-a-reminder"></a>Vystavení upomínky
Po vytvoření připomenutí a provádění potřebných úprav můžete buď vytisknout jako zkušební sestavy, nebo vytisknout připomenutí.

Při vystavení upomínky jsou data přenesena do samostatného okna pro vygenerované upomínky. Ve stejná čas jsou položky upomínky zaúčtovány. Pokud byly vypočteny úroky nebo dodatečný poplatek, jsou záznamy zaúčtovány do účetní knihy zákazníků a hlavní knihy.

Když je připomenutí vydáno, položky jsou zaúčtovány vzhledem k specifikaci v okně **Podmínky upomínek**. Tato specifikace určuje, zda jsou úroky a / nebo dodatečné poplatky účtovány na účet zákazníka a hlavní účetní knihu. Nastavení v okně **Účto skupiny zákazníků** určije, na které účty se bude zaúčtovávat.

Pro každé věcné položky zákazníka na dobropisu, jsou položky vytvořeny v okně** Položka upomínky/penále**

Pokud jsou check boxy **Účtovat úrok** nebo **Účtovat další poplatek** vybrány v okně **Podmínky upomínky** budou následující položky taktéž vytvořeny.

- Jedna položka v okně** Položky zákazníka**
- Jedna položka pohledávky v příslušném účtu hlavní knihy
- Úrok a / nebo jeden dodatečný poplatek na příslušném účtu hlavní knihy

Vydání upozornění může navíc pozměnit položky DPH.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Upomínky** a vyberte související odkaz.
2. Vyberte příslušnou upomínku a poté vyberte akci **Upravit**.
3. V okně **Vydání upomínky** vyplňte pole podle potřeby.
4. Zvolte tlačítko **OK**

Upomínka je připravena buď pro tisk nebo odeslání e-mailem.

## <a name="to-set-up-finance-charge-terms"></a>Nastavení Podmínek penále
Musíte nastavit kód reprezentující každý výpočet penále Kód můžete vložit do pole** Kód podmínky penále** na kartě zákazníka nebo dodavatele.

Penále lze vypočítat buď metodou průměrného denního zůstatku nebo metodou splatnosti zůstatku.

Při způsobu zůstatku je finanční poplatek pouze procentem z prodloužené částky:  

    Balance Due method - Finance Charge = Overdue Amount x (Interest Rate / 100)

Při průměrné metodě denního zůstatku je zohledněn počet dnů, kdy je platba opožděna:  

    Average Daily Balance method - Finance Charge = Overdue Amount x (Days Overdue / Interest Period) x (Interest Rate/100)

Navíc každý kód v tabulce podmínek účtů penále je propojen s tabulkou textů financování fakturace. Pro každou sadu podmínek finančního poplatku můžete definovat počáteční a / nebo koncový text, který má být zahrnut do poznámky o finančním poplatku.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Podmínky penále** a vyberte související odkaz.  
2. Vyplňte pole dle potřeby.  
3. Chcete-li použít více než jednu kombinaci podmínek penále, nastavte kód pro každou z nich.

    Pro každou podmínku penále můžete zadat jednotlivé podmínky, které mohou zahrnovat další poplatky v lokální i v cizí měně Můžete definovat mnoho příplatků v cizích měnách pro každý kód v okně **Podmínky penále**.
4. Zvolte akci **Měny**.
5. V** poli Měny pro podmínky penále** definujte podmínky pro danou měnu a poplatek.

    > [!NOTE]  
    > Když vytvoříte ponále v cizí měně, podmínky cizí měny, které zde nastavíte, budou použity k vytvoření penále. Pokud nejsou nastaveny žádné podmínky pro penále v cizí měně, použijí se podmínky připomínání lokální měny, které jsou nastaveny v okně **podmínky penále**, a pak se převedou na příslušnou měnu.

    Pro každou podmínku penále, můžete specifikovat text, který bude vytištěn před (**Text na začátku**) a po (**Text na konci**) na každém penále.  
6. Zvolte akce **Text na začátku** nebo **Text na konci** a vyplňte okno **Text penále**.
7. K automatickému vyplnění souvisejících řádků v textu penále vložte následující zástupné symboly do pole **Text**.

|Zástupný znak|Hodnota|  
|-----------------|-----------|  
|%1|Obsah pole **Datum dokladu** na hlavičce Penále|  
|%2|Obsah pole **Datum splatnosti** na hlavičce Penále|  
|%3|Obsah pole **Úroková sazba** v souvisejících podmínkách penále|  
|%4|Obsah pole **Zbývající Částka** na hlavičce Penále|  
|%5|Obsah pole **Částka úroku** na hlavičce Penále|  
|%6|Obsah pole **Poplatek** na hlavičce Penále|  
|%7|Celková částka upomínky|  
|%8|Obsah pole **Kód měny** na hlavičce Penále|  
|%9|Obsah pole **Zúčtovací datum** na hlavičce Penále|  

## <a name="to-create-a-finance-charge-memo-manually"></a>Vytvoření penále manuálně  
Penále jsou podobné faktuře. Hlavičku můžete vyplnit ručně a vyplnit řádky pro vás, nebo si můžete automaticky vytvořit poznámky o finančních poplatcích pro všechny zákazníky.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Penále** a vyberte související odkaz.  
2. Vyberte akci **Nový** a poté vyplňte pole.  
3. Vyberte akci** Vytvořit řádky penále**
4. V okně **Vytvořit řádky penále** nastavte filtr na **položky zákazníka **pokud chcete vytvořit peníle za určité položky.  
5.  Zvolte tlačítko **OK** pro spuštění dávkové úlohy.  

## <a name="to-update-finance-charge-memo-texts"></a>Aktualizace Penále - textů  
V některých případech možná budete chtít upravit počáteční a koncový text, který jste nastavili pro podmínky penále. Pokud to provedete v době, kdy jste vytvořili, ale dosud nebyli vystaveni penále, můžete aktualizovat poznámky s upraveným textem.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Penále** a vyberte související odkaz.  
2. Otevřete penále, u kterých chcete změnit text a klikněte na tlačítko **Aktualizovat text penále**
3. V okně **Aktualizovat text penále** můžete nasrtavit filtr, pokud chcete aktualizovat jen některé penále.
4. Zvolte tlačítko **OK** k aktualizaci Textu na začátku a konci.  

## <a name="to-issue-finance-charge-memos"></a>Vydání penále
Po vytvoření penále a provádění potřebných úprav můžete buď vytisknout jako zkušební sestavy, nebo vytisknout penále.

Když je penále vydáno, položky jsou zaúčtovány vzhledem k specifikaci v okně **podmínky penále**. Tato specifikace určuje, zda jsou úroky a / nebo dodatečné poplatky účtovány na účet zákazníka a hlavní účetní knihu. Nastavení v okně **Účto skupiny zákazníků** určije, na které účty se bude zaúčtovávat.

Pro každé věcné položky zákazníka na dobropisu, jsou položky vytvořeny v okně** Položka upomínky/penále**

Pokud jsou check boxy **Účtovat úrok** nebo **Účtovat další poplatek** vybrány v okně **Podmínky penále** budou následující položky taktéž vytvořeny.

- Jedna položka v okně** Položky zákazníka**
- Jedna položka pohledávky v příslušném účtu hlavní knihy
- Úrok a / nebo jeden dodatečný poplatek na příslušném účtu hlavní knihy

Vydání penále může navíc pozměnit položky DPH.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Penále** a vyberte související odkaz.
2. Vyberte příslušné penále a poté vyberte akci **Upravit**.
3. V okně **Vydání penále** vyplňte pole podle potřeby.
4. Zvolte tlačítko **OK**

Penále jsou připravena buď pro tisk nebo odeslání e-mailem.

## <a name="to-view-reminder-and-finance-charge-entries"></a>Zobrazení upomínek a penále  
Pokud vydýte upomínku, jedna z položek je vytvořena z okna **Položka upomínky/penále **Pro každou upomínku, která obsahuje položky zákazníka Potom můžete získat přehled o vytvořených upomínkách pro konkrétního zákazníka.    
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zákazníci** a vyberte související odkaz.  
2. Otevřete příslušnou kartu zákazníka a zvolte tlačítko **Věcné položky**.
3. V okně **Věcné položky zákazníka** vyberte řádek s věcnými položkami, které vidět v upomínce a potom zvolte akci ** Položka upomínky/penále**

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Prodej](sales-manage-sales.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

