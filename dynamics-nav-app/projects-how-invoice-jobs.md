---
title: "Vytvářte prodejní fakturu projektu k fakturaci projektu"
description: "Popisuje jak fakturovat zákazníky za výdaje a vývoj projektu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: project invoice
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 74b9209216f6e62dfc9519b288adca785cdb8100
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-invoice-jobs"></a>Návody Fakturace projektu
Během projektu se mohou hromadit projektové náklady ze spotřeby zdrojů, materiálů a nákupů souvisejících s projektem. Jak probíhá projekt, tyto transakce se zaúčtují do deníku projektu. Je důležité, aby se všechny náklady zaznamenaly do deníku projektů dříve než fakturace zákazníkovi.

Můžete fakturovat celý projekt z okna **Řádky úlohy projektu** nebo pouze vyfakturovat vybrané fakturovatelné řádky z okna **Řádky plánování**. Fakturování lze provést po dokončení projektu nebo v určitých intervalech během průběhu projektu na základě fakturačního plánu.

> [!NOTE]  
>   Pokud vyberete volbu **Fakturovatelné** v poli **Typ řádku projektu** na nákupních dokladech pro nákupy související s projektem, vytvoří se řádky plánování projektu, které jsou připraveny k fakturování zákazníkovi. Další informace naleznete v tématu [Návod: Správa zásob projektu.](projects-how-manage-project-supplies.md)

## <a name="to-create-and-post-a-job-sales-invoice"></a>Vytvoření a zaúčtování prodejní faktury projektu
Můžete vytvořit fakturu pro projekt nebo pro jednu nebo více úloh projektu pro zákazníka při dokončení práce nebo když bylo dosaženo data fakturace na základě fakturačního plánu.

V okně **Projekty** můžete fakturovat zákazníkovi výběrem zakázky a poté zvolit akci **Vytvořit prodejní fakturu projektu**. Následující postup ukazuje, jak použít dávkovou úlohu k fakturování více projektů.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Vytvořit prodejní fakturu projektu** a vyberte související odkaz.  
2. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Nastavte filtry, pokud chcete omezit projekty, které bude zpracovávat dávková úloha.
4. Zvolte tlačítko **OK** pro vytvoření faktur.  

## <a name="to-create-multiple-job-sales-invoices-from-job-planning-lines"></a>Vytvoření více prodejních faktur projektu z řádků plánování projektu
Fakturu můžete vytvořit z řádků plánování projektu a v té době označit množství zboží, zdrojů nebo finanční účet, který chcete fakturovat.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.
2. Otevřete příslušný projekt.
3. Vyberte úlohu projektu, pro kterou pole **Typ úlohy projektu** obsahuje **Účet** a poté vyberte akci **Řádky plánování úlohy projektu**.  
4. Na řádku plánování projektu v poli **Množství k transferu k fakturaci** zadejte množství zboží, zdrojů nebo finančního účtu, které chcete fakturovat.  
5. Zvolte akci **Vytvořit prodejní fakturu**.
6. V okně **Vytvořit prodejní fakturu projektu** zadejte zúčtovací datum a zda chcete vytvořit novou fakturu nebo připojit tuto fakturu k již existující faktuře.
7. Zvolte tlačítko **OK**.  

    Na řádku plánování projektu v poli **Transferované množství k fakturaci** můžete vidět množství.
8. V okně **Řádky plánování projektu** zvolte akci **Prodejní faktury/dobropisy**.

    Otevřete se okno **Prodejní faktura** zobrazující množství, které jste převedli na fakturu.  
9. Proveďte další změny a poté vyberte akci **Zaúčtovat**.

> [!NOTE]  
>   Výše uvedený postup je podobný při vytváření, kontrole a účtování s projektem souvisejících prodejních dobropisů.

## <a name="to-calculate-and-post-job-completion-entries"></a>Vypočítání a zaúčtování položek k dokončení projektu
Po dokončení všech úloh pro daný projekt včetně zaúčtování spotřeby a fakturace, je nutné aktualizovat projekt tak, aby měl **Stav** **Dokončeno**. Poté musíte vrátit všechny záznamy NV, které byly zaúčtovány v hlavní knize.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Projekty** a vyberte související odkaz.  
2. Vyberte otevřený projekt a poté zvolte akci **Úpravy**.
3. V poli **Stav** vyberte **Dokončeno**.
4. Postupujte podle pokynů pro výpočet a účtování NV. Alternativně postupujte podle kroků 5 a 6 tak, abyste to provedli ručně.  
5. Vyberte akci **Kalkulovat NV**.
6. V okně **Vypočítat NV projektu** vyplňte pole podle potřeby.  

     Položky NV projektu vytvořené spuštěním dávkové úlohy budou mít zaškrtnuto políčko **Dokončený projekt**, aby bylo jasné, že jsou dokončeny.  
7. Vyberte akci **Účto NV projektu do fin. den**.
8. V okně **Účto NV projektu do fin. den.** vyplňte pole podle potřeby.  

     Položky hlav. knihy NV projektu vytvořené spuštěním dávkové úlohy budou mít zaškrtnuto políčko **Dokončený projekt**, aby bylo jasné, že jsou dokončeny.

## <a name="see-also"></a>Viz také
[Správa projektů](projects-manage-projects.md)  
[Finance](finance.md)  
[Nákup](purchasing-manage-purchasing.md)         
[Prodej](sales-manage-sales.md)      
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

