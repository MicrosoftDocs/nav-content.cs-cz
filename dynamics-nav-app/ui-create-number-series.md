---
title: "Návod: Vytváření číselných řad "
description: "Přečtěte si, jak nastavit číselné řady, které přiřazují jedinečné identifikační kódy účtům a dokladům v Dynamics NAV."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: numbers, numbering
ms.date: 06/02/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 643e3e6a3374a2364f850c9d77ca3f59f01dab61
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-number-series"></a>Návod: Vytváření číselných řad
Pro každou společnost, kterou jste založili, musíte přiřadit jedinečné identifikační kódy věcem, jako jsou účty hlavní knihy, účty zákazníků a dodavatelů, faktury a ostatní doklady. Číslování je důležité nejen pro identifikaci, dobře navržený systém číslování také usnadňuje správu a snadnou analýzu společnosti a může snížit počet chyb, ke kterým dochází při zadávání dat.

> [!NOTE]  
>   Doporučujeme vám, abyste v demonstrační společnosti CRONUS používali stejné kódy číselných řad, jak je uvedeno v **Seznamu číselných řad**. Kódy, jako je například *N-FAK+*, vám ihned nemusí dávat smysl, ale [!INCLUDE[d365fin](includes/d365fin_md.md)] má řadu výchozích nastavení, která závisí na těchto číselných řadách.

Systém číslování vytvoříte nastavením jednoho nebo více kódů pro každý typ hlavních dat nebo dokumentu. Například můžete nastavit jeden kód pro číslování zákazníků, jiný kód pro číslování prodejních faktur a další kód pro číslování dokumentů ve všeobecných denících. Pokud nastavíte kód, musíte nastavit alespoň jednu číselnou řadu. Řádek číselné řady obsahuje informace jako první a poslední číslo v sérii a počáteční datum. Můžete nastavit více než jednu číselnou řadu pro každý kód číselné řady s jiným počátečním datem pro každý řádek. Řady budou použity postupně počínaje každou sérií v příslušném počátečním datu.

Obvykle nastavíte svou číselnou řadu tak, aby automaticky vložila další po sobě jdoucí číslo na nové karty nebo dokumenty, které vytvoříte. Můžete také nastavit číselné řady, abyste mohli ručně zadat nové číslo. Zadáte toto zaškrtávací políčko **Ruční čísla**.

Chcete-li pro jeden typ hlavních dat použít více než jeden kód číselné řady - například chcete-li použít různé číselné řady pro různé kategorie zboží - můžete použít vztahy číselných řad.

## <a name="to-create-a-new-number-series"></a>Vytváření nových číselných řad
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Číselné řady** a pak vyberte související odkaz.
2. Vyberte akci **Nový**.
3. Na novém řádku vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

**TIP**: Chcete-li povolit ruční zadání čísla na nové karty nebo doklady, zrušte zaškrtnutí políčka **Výchozí čísla** a zaškrtněte políčko **Ruční čísla**.

Nyní, když vytvoříte novou kartu nebo doklad, který je nastaven pro použití příslušné číselné řady, můžete ručně vyplnit pole **Číslo** jakoukoli hodnotou.  

## <a name="to-set-up-where-a-number-series-is-used"></a>Nastavení, kde jsou číselné řady použity
Následující procedura ukazuje, jak nastavit číselné řady pro prodejní oblast. Kroky jsou podobné pro ostatní oblasti.
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodej a pohledávky** a poté vyberte příslušný odkaz.
2. V okně **Prodej a pohledávky** na záložce s náhledem  vyberte požadovanou **Číselnou řadu** pro každou prodejní kartu nebo doklad.

Vybrané číslo bude nyní použito k vyplnění pole **Číslo** Na kartě nebo dokladu v dotazu podle toho, jak jste nastavili Číselné řady.

## <a name="to-create-relationships-between-number-series"></a>Vytváření vztahů mezi číselnými řadami
Pokud jste nastavili více než jednu číselnou řadu pro stejný druh informací nebo transakcí, můžete vytvářet vztahy mezi kódy. Tato funkce vám pomůže  při rozhodování mezi kódy pokud používáte čísla.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Číselné řady** a pak vyberte související odkaz.
2. Vyberte řádek s číselnou řadou, pro kterou chcete vytvořit vztahy, a poté zvolte **Vztah**.
3. V poli **Kód řady** vložte kód číselné řady, kterou chcete spojit s řadou, kterou jste vybrali v kroku 2.
4. Přidejte řádek pro každý kód, který chcete spojit s vybranou číselnou řadou.
5. Zavřete okno.

Nyní, když nastavíte něco, co vyžaduje číslo, můžete použít vztahy, které jste vytvořili k výběru mezi souvisejícími číselnými řadami.

## <a name="see-also"></a>Viz také
[Nastavení [!INCLUDE[d365fin](includes/d365fin_md.md)]](setup.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

