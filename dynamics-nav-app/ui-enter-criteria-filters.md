---
title: "Vkládání kriterií do filtrů"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 8eab393a0a77f9f1595ca1247c7549e68b491cb2
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="entering-criteria-in-filters"></a>Vkládání kriterií do filtrů
Chcete-li hledat data, například názvy zákazníků, adresy nebo skupiny produktů, vložte vaše kritéria. Ve vyhledávacích kritériích můžete použít všechna čísla a písmena, která běžně používáte v konkrétním poli. K dalšímu filtrování výsledků můžete použít speciální symboly.

## <a name="searching-using-the-quick-filter"></a>Vyhledávání pomocí rychlého filtru
Pomocí rychlého filtru můžete filtrovat všechny stránky. Rychlý filtr je aktivován výběrem ikony lupy v pravém horním rohu stránky. Tento typ filtrování slouží k rychlému zadání kritérií.

**Důležité**: Rychlý filtr poskytuje snadný přístup k vyfiltrovaným datům zadáním prostého textu, ale poskytuje také mnoho kritérií pro vyhledávání. V závislosti na tom, zda zadáváte prostý text nebo text včetně symbolů se rychlý filtr chová jinak.  
- Pokud do vyhledávacích kritérií zadáte obyčejný text, kritéria vyhledávání budou vyhledávány bez rozlišení malých a velkých písmen.  
- Pokud v kritériích vyhledávání zadáte text obsahující symboly, kritéria vyhledávání budou interpretována přesně tak, jak jste je zadali a vyhledávání bude citlivé na malá a velká písmena.

### <a name="quick-filter-criteria"></a>Kritéria rychlého filtru
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH>Vyhledávací kritérium</TH>
    <TH>Interpretování jako..</TH>
    <TH>Výsledek..</TH>
  </TR>
  <TR>
    <TD>>man</TD>
    <TD>@*man*</TD>
    <TD>Všechny záznamy obsahující text „man“ bez ohledu na malá a velká písmena.</TD>
  </TR>
  <TR>
    <TD>>se</TD>
    <TD>@*se*</TD>
    <TD>Všechny záznamy obsahující text „se“ bez ohledu na malá a velká písmena.</TD>
  </TR>
  <TR>
    <TD>>Man*</TD>
    <TD>Začíná Man a bere ohled na velká a malá písmena.</TD>
    <TD>Všechny záznamy začínající na text „Man“</TD>
  </TR>
  <TR>
    <TD>'man‘</TD>
    <TD>Přímo obsahuje řetězec man s ohledem na velká a malá písmena.</TD>
    <TD>Všechny záznamy, které přesně odpovídají textu „man“</TD>
  </TR>
  <TR>
    <TD>@*man</TD>
    <TD>Končí na man bez ohledu na velká a malá písmena.</TD>
    <TD>Všechny záznamy končící na „man“.</TD>
  </TR>
  <TR>
    <TD>@man*</TD>
    <TD>Začíná a nebere ohled na velká a malá písmena.</TD>
    <TD>Všechny záznamy začínající na man.</TD>
  </TR>
</TABLE>

**Poznámka**: Při filtrování polí výčtu nelze použít zástupný znak. Například pole **Stav** v Prodejních objednávkách. Chcete-li zadat filtr pro tento typ pole, můžete zadat číselnou hodnotu jako parametr filtrování. Například v poli **Stav** na prodejní objednávce, která má hodnoty **Otevřeno**, **Vydáno**, **Čeká na schválení** a **Čeká na zálohu**, použijte hodnoty **0**, **1**, **2** a **3** pro filtrování těchto voleb.  

## <a name="see-also"></a>Viz také
[Práce s [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md)

