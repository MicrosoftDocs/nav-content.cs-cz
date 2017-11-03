---
title: "Vyhledávání dat a vkládání kriterií filtru"
description: "Popisuje jak vkládat a pracovat s filtry, například s rychlým filtrem, abyste upřesnili výsledky dat, které hledáte."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: delimit, FlowFilter
ms.date: 03/29/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f981d303f75bba627e224e49b9e2f2818246fe39
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="searching-filtering-and-sorting-data"></a>Vyhledávání, filtrování a řazení dat
Je zde několik věcí, které vám pomohou najít, přesně ukázat a skenovat data v seznamu. Do těchto věcí patří řazení, hledání a filtrování.

Chcete-li hledat data, například názvy zákazníků, adresy nebo skupiny produktů, vložte vaše kritéria. Ve vyhledávacích kritériích můžete použít všechna čísla a písmena, která běžně používáte v konkrétním poli. K dalšímu filtrování výsledků můžete použít speciální symboly. Jsou zde dva způsoby ke hledání: Rychlý filtr nebo sloupcové filtry

## <a name="sorting"></a>Řazení
Řazení usnadňuje zobrazení rychlého přehledu o vašich datech. Máte-li například mnoho zákazníků, můžete si vybrat jejích třídění tak jak budete potřebovat podle **Zákaznického čísla**, **Účto skupiny zákazníků**, **Kódu měny**, **Kódu země/ oblasti** nebo **IČ**.

Chcete-li třídit seznam, můžete buď zvolit text záhlaví sloupce pro přepínání mezi vzestupným a sestupným pořadím nebo zvolit malou šipku v záhlaví sloupce a poté zvolit **Vzestupně** nebo **Sestupně**.  

> [!NOTE]  
>   Třídění není podporováno pro obrázky, pole binárního rozsáhlého objektu, tok filtrů a pole, která nepatří do tabulky.  

## <a name="searching-by-using-the-quick-filter"></a>Vyhledávání pomocí rychlého filtru
Pomocí rychlého filtru můžete filtrovat všechny stránky. Rychlý filtr je aktivován výběrem ikony lupy v pravém horním rohu stránky. Tento typ filtrování slouží k rychlému zadání kritérií.

> [!IMPORTANT]  
>   Rychlý filtr poskytuje snadný přístup k vyfiltrovaným datům zadáním prostého textu, ale poskytuje také mnoho kritérií pro vyhledávání. V závislosti na tom, zda zadáváte prostý text nebo text včetně symbolů se rychlý filtr chová jinak.  

* Pokud do vyhledávacích kritérií zadáte obyčejný text, kritéria vyhledávání budou vyhledávány bez rozlišení malých a velkých písmen.  
* Pokud v kritériích vyhledávání zadáte text obsahující symboly, kritéria vyhledávání budou interpretována přesně tak, jak jste je zadali a vyhledávání bude citlivé na malá a velká písmena.

### <a name="quick-filter-criteria"></a>Kritéria rychlého filtru
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH>Vyhledávací kritérium</TH>
    <TH>Interpretování jako..</TH>
    <TH>Výsledek..</TH>
  </TR>
  <TR>
    <TD>man</TD>
    <TD>@&#42;man&#42;</TD>
    <TD>Všechny záznamy obsahující text <b>„man“</b> bez ohledu na malá a velká písmena.</TD>
  </TR>
  <TR>
    <TD>se</TD>
    <TD>@&#42;se&#42;</TD>
    <TD>Všechny záznamy obsahující text <b>„se“</b> bez ohledu na malá a velká písmena.</TD>
  </TR>
  <TR>
    <TD>Man&#42;</TD>
    <TD>Začíná <b>Man</b> a bere ohled na velká a malá písmena.</TD>
    <TD>Všechny záznamy začínající na text <b>„Man“</b></TD>
  </TR>
  <TR>
    <TD>'man‘</TD>
    <TD>Přímo obsahuje řetězec man s ohledem na velká a malá písmena.</TD>
    <TD>Všechny záznamy, které přesně odpovídají textu <b>„man“</b></TD>
  </TR>
  <TR>
    <TD>@man* </TD>
    <TD>Začíná a nebere ohled na velká a malá písmena.</TD>
    <TD>Všechny záznamy začínající na <b>man</b>.</TD>
  </TR>
    <TR>
    <TD>@&#42;man</TD>
    <TD>Končí na man bez ohledu na velká a malá písmena.</TD>
    <TD>Všechny záznamy končící na <b>„man“</b>.</TD>
  </TR>
</TABLE>

> [!NOTE]  
>   Při filtrování polí výčtu nelze použít zástupný znak. Například pole **Stav** v Prodejních objednávkách. Chcete-li zadat filtr pro tento typ pole, můžete zadat číselnou hodnotu jako parametr filtrování. Například v poli **Stav** na prodejní objednávce, která má hodnoty **Otevřeno**, **Vydáno**, **Čeká na schválení** a **Čeká na zálohu**, použijte hodnoty **0**, **1**, **2** a **3** pro filtrování těchto voleb. 

## <a name="searching-by-using-column-filters"></a>Vyhledávání použitím sloupcového filtru
Můžete přidat filtr na jeden nebo více sloupců na přehledu. Sloupcový filtr je více flexibilní a rozšířený než rychlý filtr 

### <a name="to-add-a-filter-on-a-column"></a>Přidání filtru do sloupce
1.  Předtím než přidáte filtr, vyberte ![Zobrazit jako seznam](media/ui_show_as_list_icon.png "Zobrazit jako seznam") ikonu ke změně náhledu přehledu.
2. Zvolte šipku dolů v záhlaví sloupců a vyberte **Filtr**.
3. Proveďte následující: 
  -  Zvolte *...* vedle pole a vyberte hodnotu ze seznamu
  -  Vložte kritéria do pole. Prohlédněte si další sekci pro detaily
4. Zvolte tlačítko **OK**.

## <a name="filter-criteria-and-symbols"></a>Filtrování kriterií a symbolů
Při vkládání kriterií můžete použít všechna čísla a písmena, která běžně používáte v konkrétním poli. K dalšímu filtrování výsledků můžete použít speciální symboly. Následující tabulka ukazuje symboly, které mohou být použity ve filtrech.  
  
> [!IMPORTANT]  
>  Může být instance kde políčka obsahují tyto symboly, které chce vyfiltrovat. Pro to aby jste to udělali, musíte zahrnout do filtru výraz, který obsahuje znaky v uvozovkách (''). Například, pokud chcete filtrovat na záznamech která začínají textem *S&R*, zadáte do filtru **'S&R*'**.  
  
### <a name="-interval"></a>(..) Interval  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|1100..2100|Čísla od 1100 do 2100|  
|..2500|Do a včetně 2500|  
|..311200|Datum Do a včetně 31.12. 00|  
|P8..|Informace pro účetní období 8 a poté|  
|..23|Datum od počátku do 23-aktuální měsíc-aktuální rok 23:59:59|  
|23..|Od 23-aktuální měsíc-aktuální rok 0:00:00 do konce času|  
|22..23|Od 22-aktuální měsíc-aktuální rok 0:00:00 do do 23-aktuální měsíc-aktuální rok 23:59:59|  
  
### <a name="124-eitheror"></a>(&#124;) Buď/Nebo  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|1200&#124;1300|Čísla s 1200 nebo 1300|  
  
### <a name="-not-equal-to"></a>(<>) Nerovná se  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|<>0|Všechna čísla kromě 0<br /><br /> Možnost SQL serveru vám dovolí kombinovat symbol s výrazem expresní karty Například, <>A* Znamená nerovná se jakémukoli textui začínající na A|  
  
### <a name="-greater-than"></a>(>) Větší než  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|>1200|Čísla větší než 1200|  
  
### <a name="-greater-than-or-equal-to"></a>(>=) Vetší nebo rovno  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|>=1200|Čísla větší nebo rovno 1200|  
  
### <a name="-less-than"></a>(<) Méně než  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|<1200|Čísla menší než 1200|  
  
### <a name="-less-than-or-equal-to"></a>(<=) Menší nebo rovno  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|<=1200|Čísla menší nebo rovno 1200|  
  
### <a name="-and"></a>(&) And  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|> 200&<1200|Čísla větší než 200 a menší než 1200|  
  
### <a name="-an-exact-character-match"></a>('') Přesná shoda znaků  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|'man‘|Text přesně odpovídá a je citlivý na malá a velká písmena|  
  
### <a name="-case-insensitive"></a>(@)  Nerozlišení velkým a malých písmen  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|@man*|Text začíná man a nerozlišuje na velká a malá písmena|  
  
### <a name="-an-indefinite-number-of-unknown-characters"></a>(*) Identifikuje počet neznámých znaků  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|*Co*|Text obsahuje „Co“ a rozlišuje velká a malá písmena.|  
|*Co|Text končí na „Co“ a rozlišuje velká a malá písmena.|  
|Co*|Text začíná na „Co“ a rozlišuje velká a malá písmena.|  
  
### <a name="-one-unknown-character"></a>(?) Jeden neznámý znak  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|Hans?n|Text jako je Hansen nebo Hanson|  
  
### <a name="combined-format-expressions"></a>Kombinovaný formát výrazů  
  
|Vzorové vyjádření|Zobrazené položky|  
|-----------------------|-----------------------|  
|5999&#124;8100..8490|Obsahuje jakékoli záznamy s čísly 5999 nebo čísla v intervalu 8100 do 8490|  
|..1299&#124;1400..|Obsahuje záznamy s čísly menšími nebo rovny 1299 nebo čísla rovny 1400 nebo většími (Všechna čísla kromě od 1300 do 1399).|  
|> 50&<100|Obsahuje záznamy s čísly, které jsou větší než 50 a menší než 100 (od 51 do 99)|  
 
## <a name="see-also"></a>Viz také
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

