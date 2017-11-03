---
title: "Pořízení dlouhodobého majetku"
description: "Můžete nastavit dlouhodobý majetek, přiřadit odpisovou knihu a zaznamenat pořizovací náklady dlouhodobého majetku."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: purchase fixed asset
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 17a61be2cd0977a55b098c8ec0b1d1cc164d7898
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-acquire-fixed-assets"></a>Návod: Pořízení dlouhodobého majetku
Pro každý dlouhodobý majetek musíte nastavit kartu obsahující informace o majetku. Můžete nastavit budovy nebo výrobní vybavení jako hlavní majetek se seznamem komponent a můžete je seskupovat různými způsoby, např. podle třídy nebo umístění. Odpisová kniha musí být nastavena a přiřazena každému dlouhodobému majetku předtím, než si jej můžete pořídit.

Pokud je dlouhodobý majetek nastaven a je přiřazena odpisová kniha, musíte si pořídit dlouhodobý majetek. Chcete-li si pořídit dlouhodobý majetek, zaznamenáte jeho pořizovací cenu na příslušný finanční účet, bankovní účet nebo dodavatele zaúčtováním pořizovací transakce v okně **Finanční deník DM**. Můžete použít okno **Pořízení DM** k vytvoření a zaúčtování požadovaných řádků finančního deníku automaticky.

Hodnota při vyřazení je zbytková hodnota DM, pokud již nemůže být dál použit. Můžete zaúčtovat hodnotu při vyřazení současně s zaúčtováním pořizovací ceny. Další informace naleznete v tématu [Návod: Odpis a amortizace DM](fa-how-depreciate-amortize.md).

Odsazení slouží k úpravě hodnot pro obecné změny cenové hladiny. Dávková úloha **Indexovat DM** může být použita k vypočítání pořizovací ceny v reprodukčních nákladech.

## <a name="to-create-a-fixed-asset-and-acquire-it-automatically"></a>Vytvoření a pořízení DM automaticky
Následující postup popisuje, jak vytvořit dlouhodobý majetek a pořídit jej pomocí okna **Pořízení DM**, čímž vytvoříte a zaúčtujete požadované řádky DM ve finančním deníku. Stejně tak můžete vytvořit a zaúčtovat řádky deníku ručně. Další informace naleznete v tématu "Zaúčtování pořízení DM ručně s dlouhodobým majetkem finančního deníku."

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.  
2. Zvolte akci **Nový** a pak vyplňte pole záložky s náhledem **Obecné** podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. V záložce s náhledem **Knihy odpisů** vyplňte pole podle potřeby. Tento krok přiřadí knihu odpisů k dlouhodobému majetku.  
4. Pokud potřebujete přiřadit k dlouhodobému majetku více než jednu knihu odpisů, zvolte akci **Přidat více knih odpisů**. Další informace naleznete v tématu "Přiřazení knihy odpisů k dlouhodobému majetku“ v [Návod: Nastavení odpisů DM](fa-how-setup-depreciation.md).

    Když jsou vyplněna všechna požadovaná pole k pořízení DM **Jste připraveni k pořízení DM. Pořízení** upozornění se zobrazí v horní části stránky.
5. Zvolte akci **Pořízení** v upozornění.
6. Postupujte podle kroků v okně **Pořízení DM** k dokončení automatického pořízení DM.

> [!NOTE]  
>   Můžete také zaúčtovat pořizovací cenu jako kredity. V takovém případě nezapomeňte, že hodnota v poli  **Pořizovací cena včetně DPH** musí obsahovat znaménko mínus, která označuje Dal.

Pokud zvolíte možnost **Dokončit**, vyplní se pole **Hodnota knihy** v okně **Karta DM**, což znamená, že dlouhodobý majetek byl pořízený při stanovených pořizovacích nákladech.  

## <a name="to-set-up-a-component-list-for-a-main-asset"></a>Nastavení seznamu komponent pro hlavní majetek
Můžete seskupit váš dlouhodobý majetek a jejich komponenty do hlavního majetku. Například můžete mít výrobní stroj, který se skládá z mnoha částí, které chcete tímto způsobem seskupit.  

Jak základní aktivum, tak i všechny její komponenty musí být nastaveny jako individuální karty DM. Po nastavení seznamu komponent [!INCLUDE[d365fin](includes/d365fin_md.md)] se automaticky vyplní pole **Hlavní majetek/Komponenty** a **Komponenty hlavního majetku** na kartách s dlouhodobým majetkem.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, který je hlavním aktivem a poté vyberte akci **Hlavní aktiva komponent**.
3. V okně **Komponenty hlavního majetku** zvolte pole **Číslo DM** a pak vyberte dlouhodobý majetek, který chcete přidat jako komponentu k hlavnímu majetku.
4. Zavřete okno.
5. Opakujte krok 3 a 4 pro každou komponentu majetku, kterou chcete přidat.
6. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení dlouhodobého majetku** a pak vyberte související odkaz.
7. Vyberte zaškrtávací políčko **Umožnit zaúčtování do hlavního majetku**.

## <a name="to-post-a-fixed-asset-acquisition-manually-with-the-fixed-asset-gl-journal"></a>Zaúčtování pořízení DM ručně s dlouhodobým majetkem finančního deníku
Následující postup popisuje, jak pořídit dlouhodobý majetek ručně vytvořením a zaúčtováním řádků v okně **Finanční deník DM**. Můžete také pořídit dlouhodobý majetek automaticky pomocí okna **Asistované pořízení DM**. Další informace naleznete v kroku 5 v části "Vytvoření DM a pořízení DM automaticky."

> [!NOTE]  
>   Můžete také zaúčtovat pořizovací cenu jako kredity. V tomto případě, pamatujte že hodnota v poli **Částka** musí mít znaménko mínus, která označuje kredit.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.
2. V okně **Dlouhodobý majetek finančního deníku** v poli **Typ zaúčtování DM** vyberte **Pořízení**.
3. Vyplňte pole podle potřeby.
4. Zvolte akci **Zaúčtovat**.  

> [!TIP]  
>   Pokud vyplníte pole **Číslo pojištění** ve finančním deníku DM při zaúčtování pořizovací ceny, pak [!INCLUDE[d365fin](includes/d365fin_md.md)] bude také zaúčtována pořizovací cena DM do knihy pojištění. Další informace naleznete v tématu [Návod: Pojištění DM](fa-how-insure.md).

## <a name="to-cancel-an-acquisition-cost-posting-for-one-fixed-asset"></a>Zrušení zaúčtování pořizovací ceny pro jeden dlouhodobý majetek
Pokud se při přidání pořizovací ceny vyskytne chyba, můžete záznam odebrat pomocí dávkové úlohy **Storno položek DM** a poté odeslat správnou položku pořízení. Chybné položky jsou přeneseny do okna **Chybné položky DM**.

Pokud například zaúčtujete pořízení se špatným datem, musíte ji co nejdříve opravit, protože je použito datum zaúčtování DM pro spoustu kritických výpočtů.

> [!IMPORTANT]  
>   Funkci **Storno transakce** nelze použít pro položky DM.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Storno položek DM** a pak vyberte související odkaz.
2. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. Zvolte tlačítko **OK** pro spuštění dávkové úlohy.
4. Pokud je nesprávná položka nebo položky zrušeny, postupujte k zaúčtování se správnými pořizovacími náklady.

Pro zrušení položek knihy pro několik dlouhodobých majetků najednou použijte dávkovou úlohu **Storno položek DM**.

## <a name="to-post-the-salvage-value-together-with-the-acquisition-cost"></a>Zaúčtování hodnoty při vyřazení s pořizovacími náklady
Můžete zaúčtovat hodnotu při vyřazení společně s pořizovací cenou z finančního deníku DM.    

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Storno položek DM** a pak vyberte související odkaz.
2. Vytvořte řádek knihy pořízení. Další informace naleznete v tématu "Zaúčtování pořízení DM ručně s dlouhodobým majetkem finančního deníku."
3. V poli **Hodnota při vyřazení** v řádku deníku zadejte hodnotu při vyřazení jako kredit (se znaménkem mínus).
4. Zvolte akci **Zaúčtovat**.

> [!NOTE]  
>   Typ zaúčtování **Hodnota při vyřazení** je možnost pouze v okně **Deník DM**. Není k dispozici v okně **Dlouhodobý majetek finančního deníku**, protože hodnota při vyřazení není nikdy zaúčtována v hlavní knize.

## <a name="see-also"></a>Viz také
[Dlouhodobý majetek](fa-manage.md)  
[Nastavení dlouhodobého majetku](fa-setup.md)  
[Finance](finance.md)  
[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

