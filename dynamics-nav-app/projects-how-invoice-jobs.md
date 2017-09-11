---
title: "Návod: Fakturace projektů"
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
ms.openlocfilehash: c0dcce83dfba30af38f33a6bf814b15862d5fc19
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-invoice-jobs"></a>Návod: Fakturace projektů
Během projektu se mohou hromadit projektové náklady ze spotřeby zdrojů, materiálů a nákupů souvisejících s projektem. Jak probíhá projekt, tyto transakce se zaúčtují do deníku projektu. Je důležité, aby se všechny náklady zaznamenaly do deníku projektů dříve než fakturace zákazníkovi.

Můžete fakturovat celý projekt z okna **Řádky úlohy projektu** nebo pouze vyfakturovat vybrané fakturovatelné řádky z okna **Řádky plánování**. Fakturování lze provést po dokončení projektu nebo v určitých intervalech během průběhu projektu na základě fakturačního plánu.

**Poznámka**: Pokud vyberete volbu **Fakturovatelné** v poli **Typ řádku projektu** na nákupních dokladech pro nákupy související s projektem, vytvoří se řádky plánování projektu, které jsou připraveny k fakturování zákazníkovi. Další informace naleznete v tématu [Návod: Správa projektových zásob](projects-how-manage-project-supplies.md).

## <a name="to-create-and-post-a-job-sales-invoice"></a>Vytvoření a zaúčtování prodejní faktury projektu  
Můžete vytvořit fakturu pro projekt nebo pro jednu nebo více úloh projektu pro zákazníka při dokončení práce nebo když bylo dosaženo data fakturace na základě fakturačního plánu.

V okně **Projekty** můžete fakturovat zákazníkovi výběrem zakázky a poté zvolit akci **Vytvořit prodejní fakturu projektu**. Následující postup ukazuje, jak použít dávkovou úlohu k fakturování více projektů.  

1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Vytvořit prodejní fakturu projektu** a pak vyberte související odkaz.  
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
3. Nastavte filtry, pokud chcete omezit projekty, které bude zpracovávat dávková úloha.
3. Zvolte tlačítko **OK** pro vytvoření faktur.  

## <a name="to-create-multiple-job-sales-invoices-from-job-planning-lines"></a>Vytvoření více prodejních faktur projektu z řádků plánování projektu  
Fakturu můžete vytvořit z řádků plánování projektu a v té době označit množství zboží, zdrojů nebo finanční účet, který chcete fakturovat.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.
2. Otevřít příslušný projekt.
3. Vyberte úlohu projektu, pro kterou pole **Typ úlohy projektu** obsahuje **Účet** a poté vyberte akci **Řádky plánování úlohy projektu**.  
4. Na řádku plánování projektu v poli **Množství k transferu k fakturaci** zadejte množství zboží, zdrojů nebo finančního účtu, které chcete fakturovat.  
5. Zvolte akci **Vytvořit prodejní fakturu**.
6. V okně **Vytvořit prodejní fakturu projektu** zadejte zúčtovací datum a zda chcete vytvořit novou fakturu nebo připojit tuto fakturu k již existující faktuře.
7. Zvolte tlačítko **OK**.

    Na řádku plánování projektu v poli **Transferované množství k fakturaci** můžete vidět množství.

8. V okně **Řádky plánování projektu** zvolte akci **Prodejní faktury/dobropisy**.

    Otevřete se okno **Prodejní faktura** zobrazující množství, které jste převedli na fakturu.  
9. Proveďte další změny a poté vyberte akci **Zaúčtovat**.

**Poznámka**: Výše uvedený postup je podobný při vytváření, kontrole a účtování s projektem souvisejících prodejních dobropisů.

## <a name="to-calculate-and-post-job-completion-entries"></a>Vypočítání a zaúčtování položek k dokončení projektu  
Po dokončení všech úloh pro daný projekt včetně zaúčtování spotřeby a fakturace, je nutné aktualizovat projekt tak, aby měl **Stav** **Dokončeno**. Poté musíte vrátit všechny záznamy NV, které byly zaúčtovány v hlavní knize.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.  
2. Vyberte otevřený projekt a poté zvolte akci **Úpravy**.
3. V poli **Stav** vyberte **Dokončeno**.
4. Postupujte podle pokynů pro výpočet a účtování NV. Alternativně postupujte podle kroků 5 a 6 tak, abyste to provedli ručně.  
5. Vyberte akci **Kalkulovat NV**.
6. V okně **Vypočítat NV projektu** vyplňte pole podle potřeby.  

     Položky NV projektu vytvořené spuštěním dávkové úlohy budou mít zaškrtnuto políčko **Dokončený projekt**, aby bylo jasné, že jsou dokončeny.  

7. Vyberte akci **Účto NV projektu do fin. den.**.
8. V okně **Účto NV projektu do fin. den.** vyplňte pole podle potřeby.  

     Položky hlav. knihy NV projektu vytvořené spuštěním dávkové úlohy budou mít zaškrtnuto políčko **Dokončený projekt**, aby bylo jasné, že jsou dokončeny.

## <a name="see-also"></a>Viz také
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Správa prodeje](sales-manage-sales.md)      
[Práce s Dynamics NAV](ui-work-product.md)  

