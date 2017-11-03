---
title: "Práce s Dimenzemi"
description: "Používejte dimenze pro kategorizaci položek, například podle oddělení nebo projektu, takže můžete snadno sledovat a analyzovat data."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: analysis, history, track
ms.date: 06/14/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f312a30686566cc5bf123b473c0d2b93d0fadd89
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="working-with-dimensions"></a>Práce s Dimenzemi
Chcete-li zjednodušeně provést analýzu dokumentů, například objednávek, můžete použít dimenze. Dimenze jsou atributy a hodnoty, které kategorizují položky, takže je můžete sledovat a analyzovat. Například dimenze můžou indikovat projekt či oddělení odkud položka pochází.  

Například místo nastavení oddělených účtů hlavní knihy pro každé oddělení či projekt, můžete použít dimenze. To dává lepší příležitost k analýze, aniž by vznikla komplikovaná účetní osnova. Další informace naleznete v tématu [Business Intelligence](bi.md).

Další příklad k nastavení dimenzí je zvaná *Oddělení* a použijete tuto dimenzi, když účtujete prodejní doklady. To vám umožní používat nástroje Business Intelligence, abyste zjistili, které oddělení prodávaly tyto položky.
Čím více dimenzí používáte, tím detailnější sestavy můžete založit pro vaše obchodní rozhodnutí. Například jedna položka prodeje může obsahovat informace o více dimenzích, například:  

* Účet, na který bylo zaúčtováno prodejní zboží  
* Kde bylo zboží prodáno
* Kdo jej prodal
* Druh zákazníka, který ho koupil  

## <a name="analyzing-by-dimensions"></a>Analýza podle dimenzí
Funkce dimenzí hraje důležitou roli v business intelligence, například při definování zobrazení analýzy. Další informace naleznete v tématu [Návod: Analýza dat podle dimenzí](bi-how-analyze-data-dimension.md).

> [!TIP]
> Jako rychlý způsob, jak analyzovat transakční data podle dimenzí, můžete filtrovat součty v účetní osnově a položkách ve všech oknech **Položek** podle dimenzí. Podívejte se na akci **Sady filtrů dimenzí**.

## <a name="dimension-sets"></a>Sady dimenzí
Sada dimenzí je jedinečná kombinace hodnot dimenzí. Ukládá se jako sada hodnot dimenzí v databázi. Každá hodnota sady dimenzí představuje jednotlivou hodnotu dimenze. Sada dimenzí je identifikována běžným ID sady dimenzí, které je připojeno ke každé hodnotě sady dimenzí, která patří do sady dimenzí.  

Když vytvoříte řádek deníku, hlavičku dokumentu nebo řádek dokumentu, můžete specifikovat kombinaci hodnot dimenzí. Namísto explicitně ukládané každé hodnoty dimenze v databázi, ID sady dimenze je přiřazeno k řádku deníku, hlavičce dokumentu, nebo řádku dokumentu ke specifikaci sady dimenze.  

## <a name="setting-up-dimensions"></a>Nastavení dimenzí
Můžete definovat dimenze a hodnoty dimenzí pro kategorizaci deníků a dokladů, jako jsou prodejní a nákupní objednávky. Nastavte dimenze v okně **Dimenze**, kde vytvoříte jeden řádek pro každou dimenzi, jako je *Projekt*, *Oddělení*, *Oblast* a *Prodejce*.

Také nastavte hodnoty pro dimenze. Například hodnoty, které mohou být v oddělení vaší společnosti. Hodnoty dimenzí můžou být nastaveny v hierarchické struktuře podobně jako v účetní osnově, takže data se mohou rozložit na různě stupně členitosti a podmnožiny hodnot dimenzí mohou být sečteny. Můžete definovat tolik dimenzí a hodnot dimenzí, kolik potřebujete a každý ve vaší společnosti je může použít.

Můžete také nastavit některé globální a zkratkové dimenze:  

* **Globální dimenze** jsou použity jako filtry, například na sestavy a dávkové úlohy. Můžete použít pouze dvě globální dimenze, proto zvolte dimenze, které budete často používat.
* **Zkratky dimenzí** jsou dostupné v polích na deníku a řádku dokladů. Můžete vytvořit až šest z nich.  

### <a name="setting-up-default-dimensions-for-customers-vendors-and-other-accounts"></a>Nastavení výchozích dimenzí pro zákazníky, dodavatele a ostatní účty
Můžete přiřadit výchozí dimenzi pro zvláštní účty. Dimenze budou zkopírovány do deníku nebo dokladu při zadání čísla účtu na řádku, ale pokud je to vhodné, můžete smazat nebo změnit kód na řádku. Můžete také vytvořit požadovanou dimenzi pro zaúčtování položky s konkrétním typem účtu.  

### <a name="translating-the-names-of-dimensions"></a>Překládání názvů dimenzí
Když vytvoříte dimenzi a zejména zkratku dimenzí, tak to, co skutečně vytváříte je vlastní pole nebo záhlaví sloupce. Pokud je vaše firma mezinárodní, můžete zadat překlad názvů dimenze. Doklady, které obsahují dimenze, budou mít přeložené názvy.   

### <a name="example-of-dimension-setup"></a>Příklad nastavení dimenzí
Řekněme, že vaše společnost chce sledovat transakce na základě organizační struktury a geografických umístění. Chcete-li to provést, můžete v okně **Dimenze** nastavit dvě dimenze:

* **OBLAST**  
* **STŘEDISKO**  

| Kód | Název | Titulek kódu | Titulek filtru |
| --- | --- | --- | --- |
| OBLAST |Oblast |Kód oblasti |Filtr oblasti |
| STŘEDISKO |Středisko |Kód střediska |Filtr střediska |

Pro **OBLAST** můžete přidat následující hodnoty dimenze:

| Kód | Název | Typ hodnoty dimenze |
| --- | --- | --- |
| 10 |Amerika |Od-součet |
| 20 |Severní Amerika |Standard |
| 30 |Pacifik |Standard |
| 40 |Jížní Amerika |Standard |
| 50 |Amerika, Součet |Do-součet |
| 60 |Evropa |Od-součet |
| 70 |EU |Standard |
| 80 |Mimo EU |Standard |
| 90 |Evropa, Součet |Do-součet |

Pro dvě hlavní geografické oblasti, Ameriku a Evropu, můžete přidat podkategorie pro regiony odsazením hodnot dimenzí. Umožní vám to sestava o prodejích nebo výdajích v regionech a dostanete součty pro větší geografické oblasti. Můžete také zvolit, které země nebo oblasti použijete jako hodnoty svých dimenzí nebo kraje nebo města v závislosti na vaší firmě.  
> [!NOTE]  
>   Chcete-li nastavit hierarchii, musí být kódy v abecedním pořadí. To zahrnuje kódy hodnot dimenzí, které jsou uvedeny v [!INCLUDE[d365fin](includes/d365fin_md.md)].  

Pro **STŘEDISKO** můžete přidat následující hodnoty dimenze:

| Kód | Název | Typ hodnoty dimenze |
| --- | --- | --- |
| ADMIN |Správce |Standard |
| PROD |Produkce |Standard |
| SALES |Prodej |Standard |

S tímto nastavením pak přidáte dvě dimenze jako dvě globální dimenze v okně **Nastavení hlavní knihy**. To znamená, že můžete použít OBLAST a STŘEDISKO jako filtry pro položky hlavní knihy, stejně jako pro všechny sestavy a plány účtů. Obě globální dimenze jsou také automaticky dostupné pro použití na vstupních řádcích a hlavičkách dokladů jako zkratky dimenzí.  

## <a name="using-dimensions"></a>Použití dimenzí
V dokladu, jakým je prodejní objednávka, můžete přidat informace o dimenzi pro oba řádky jednotlivého dokladu a dokladu jako takového. Například v okně **Prodejní objednávka** můžete zadat hodnoty dimenze pro první dvě zkratky dimenzí přímo na dokumentu a můžete přidat další informace, pokud zvolíte tlačítko **Dimenze**.  

Pokud místo toho pracujete v deníku, můžete také přidat informace o dimenzi do hodnoty stejným způsobem, pokud jste nastavili zkratku dimenzí jako pole přímo na řádcích deníku.  

Můžete nastavit výchozí dimenze pro účty nebo typy účtů tak, aby dimenze a hodnoty dimenzí byly vyplněny automaticky.

## <a name="see-also"></a>Viz také
[Business Intelligence](bi.md)  
[Finance](finance.md)  
[Návod: Analýza dat podle dimenzí](bi-how-analyze-data-dimension.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

