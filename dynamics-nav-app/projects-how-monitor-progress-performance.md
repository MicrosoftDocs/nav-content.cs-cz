---
title: "Návod: Monitorování pokroku a výkonu projektu"
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
ms.openlocfilehash: 05b990dd93ddff12581efdc2918ada69681482a1
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-monitor-job-progress-and-performance"></a>Návod: Monitorování pokroku a výkonu projektu
Jak postupuje projekt, materiály, zdroje a další výdaje jsou spotřebovány a musí být zaúčtovány k projektu. Nedokončená výroba (NV) je funkce, která umožňuje odhadnout finanční hodnotu projektů v hlavní knize, zatímco projekty probíhají. V mnoha případech můžete zaúčtovat výdaje za práci před fakturací projektu. Pokud byly zaúčtovány pouze výdaje, vaše finanční výkazy budou nepřesné. Další informace naleznete v tématu [Porozumnění Metod NV](projects-understanding-wip.md).

Chcete-li sledovat hodnotu v hlavní knize, můžete vypočítat NV a zaúčtovat hodnotu do hlavní knihy.

NV můžete vypočítat na základě následujících údajů:

- Hodnota nákladů
- Prodejní hodnota
- Rozpoznatelné náklady
- Procento dokončení
- Dokončená smlouva

Chcete-li výsledek zobrazit jiným způsobem, můžete změnit metodu a vypočítat znovu NV. Neexistuje žádný limit počtu výpočtů NV. NV se pouze vypočítává, neúčtuje se do hlavní knihy. Poté, co jste vypočítali NV, můžete ji zaúčtovat do hlavní knihy.

## <a name="to-create-a-job-wip-method"></a>Vytvořit metodu NV projektu  
Můžete vytvořit metodu NV projektu, která odráží potřeby vaší organizace. Poté, co jste je vytvořili, můžete ji nastavit jako výchozí metodu výpočtu NV, která bude použita ve vaší organizaci.  

**Poznámka**. Po použití nové metody k vytvoření položek NV nelze metodu odstranit nebo upravit.  

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu** , zadejte **Metody projektu NV** a zvolte související odkaz.  
2. Vyberte akci **Nový** a poté vyplňte pole. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.  
3. Zavřete okno.   
4. Pro nastavení této metody jako výchozí, v pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu** , zadejte **Nastavení projektů** a zvolte související odkaz.  
5. V poli **Výchozí metoda NV** vyberte metodu ze seznamu.

## <a name="to-define-a-wip-method-for-a-job"></a>Pro definování metody NV pro projekt  
Při vytváření nového projektu musíte zadat, kterou metodu NV použijete. V některých případech je metoda NV projektu, kterou můžete použít, nastavena jako výchozí.

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.
2. Zvolte akci **Nový**. Pro další informace, viz [Návod: Vytvořit projekty](projects-how-create-jobs.md).  
3. V okně **Karta projektu** v poli **Metoda NV** vyberte metodu NV ze seznamu. Pokud byla definována výchozí metoda, můžete v případě potřeby vybrat jinou možnost.  

## <a name="to-calculate-wip"></a>Vypočítat NV  
Můžete stanovit částku NV, která má být zaúčtována na rozvahové účty pro vykazování konce období. Použijete dávkovou úlohu **Vypočítat NV projektu** .  

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu** , zadejte **Výpočet NV projektu** a zvolte související odkaz.  
2. Vyberte akci **Vypočítat NV**.
3. V okně **Vypočítat NV projektu** vyplňte pole podle potřeby.
4. Zvolte tlačítko **OK**.  

**Poznámka**: Dávková úloha vypočítá pouze NV. Neúčtuje se do hlavní knihy. Chcete-li tak učinit, musíte po výpočtu NV spustit dávkovou úlohu **Zaúčtovat NV do hl. knihy**. Další informace naleznete v následujícím postupu.

## <a name="to-post-wip"></a>Zaúčtovat NV  
Když jste vypočítali NV, můžete ji zaúčtovat do rozvahových účtů pro vykazování konce období. Použijete dávkovou úlohu **Zaúčtovat NV projektu do hl. knihy** .

1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu** , zadejte **Zaúčtovat NV projektu do hl. knihy** a zvolte související odkaz.  
2. V okně **Zaúčtovat NV projektu do fin. den.** vyplňte pole podle potřeby.  
3. Zvolte tlačítko **OK**.

## <a name="to-view-job-usage-estimates-and-post-updates"></a>Chcete-li zobrazit odhady spotřeby projektu a zaúčtovat aktualizace  
Můžete sledovat spotřebu projektu až do jeho dokončení v jednom kroku. K tomu použijte **Výp. projektu Dávková úloha Zbývající spotřeba** pro všechny činnosti až do konce projektu včetně.  

To vám umožní sledovat a porovnávat původní odhady s aktuálními výsledky a podle potřeby provádět úpravy nebo nové položky. Například můžete odhadnout, že práce vyžadovala 10 hodin a dosud to trvalo 15 hodin. Můžete přidat další pět hodin do existujícího řádku deníku nebo vytvořit nový řádek deníku, který vykáže těchto pět hodin jako přesčas, což je další typ práce. Vypočítá se příslušná cena a náklady a poté je můžete zaúčtovat do deníku.  

**Poznámka**: Položky zboží vytvářejí položky zboží a snižují množství zásob. Dávková úloha **Zaúčtovat náklady na zás. do hl. knihy** převádí náklady ze zásob do hlavní knihy. Položky zdrojů vytvářejí položky zdrojů.  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deník projektu** a pak vyberte související odkaz.  
2. Vyberte příslušný deník projektu a potom vyberte položku **Výp. Akce Zbývající spotřeba** .  
3. V **Výp. projektu Okně Zbývající spotřeba** , zadejte číslo dokladu a datum zaúčtování, které chcete vložit do deníku, a potom klepněte na tlačítko **OK** .  
4. Aktualizujte deník se všemi možnými úpravami.  
5. Zvolte **Zaúčtovat**.

## <a name="to-view-job-ledger-entries"></a>Zobrazení položek projektu
Všechny záznamy týkající se projektu jsou zaznamenány v žurnálu projektů a číslovány postupně, počínaje 1. Z žurnálu projektu získáte přehled o všech položkách projektu.    

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Žurnál projektu** a pak vyberte související odkaz.
2. Vyberte příslušný žurnál a poté zvolte akci **Položky projektu** .

V okně **Položky projektu** můžete zkontrolovat položky, které jsou přiřazeny k libovolnému projektu.  

## <a name="see-also"></a>Viz také
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Spravovat prodej](sales-manage-sales.md)      
[Pracujte s Dynamics NAV](ui-work-product.md)  

