---
title: "Práce s finančními deníky"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 4eb580971d86db59380e29beee62b5257a1d2846
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="work-with-general-journals"></a>Práce s finančními deníky
Používáte finanční deníky k účtování finančních transakcí do účtů hlavní knihy a do ostatních účtů, jako jsou bankovní, zákaznické a dodavatelské účty. Účtování pomocí finančního deníku vždy vytvoří položky na účtech hlavní knihy.  To platí i v případě, že například zaúčtujete řádek deníku na účet zákazníka, protože je položka zaúčtována na účtu pohledávek hlavní knihy prostřednictvím účto skupiny.

Informace, které zadáte do deníku jsou dočasné, a mohou být změněny, když jsou v deníku.  Při zaúčtovávání deníku se informace přenášejí na položky v jednotlivých účtech, kde je nelze změnit. Můžete však neaplikovat účtované položky a můžete zadat opačné nebo opravné položky.

## <a name="journal-templates-and-batches"></a>Šablony a listy deníku
Existuje několik šablon finančního deníku.  Každá šablona deníku je reprezentována vyhrazeným oknem s konkrétními funkcemi a poli, která jsou potřebná k podpoře těchto funkcí, jako je například okno **Deník odsouhlasení plateb** pro zpracování bankovních plateb a okno **Deníky plateb** pro platby vašim dodavatelům. 

Pro každou šablonu deníku můžete nastavit svůj vlastní osobní deník jako list deníku. Například můžete definovat váš vlastní list deníku pro platební deník, který má vaše osobní rozložení a nastavení. 

**Poznámka**: Příkladem osobního nastavení, které můžete definovat ve vašem listu finančního deníku je systém, který vám pomůže vyplnit pole částky. Pokud pro váš list zaškrtnete na řádku pole **Navrhovat vyrovnávací částku** v okně **Listy finančního deníku**, a pak pole **Částka**, pak jsou například řádky finančního deníku pro stejné číslo dokladu automaticky předvyplněné hodnotou, která je vyžadována k vyrovnání dokladu. Další informace naleznete v [Povolení navrhování hodnot aplikací Dynamics NAV](ui-let-system-suggest-values.md).

## <a name="main-accounts-and-balancing-accounts"></a>Hlavní účty a vyrovnávací účty
Pokud jste nastavili výchozí vyrovnávací účty pro listy deníku, vyrovnávací účet bude vyplněn automaticky, když vyplníte pole **Číslo účtu** . V opačném případě vyplňte ručně jak pole **Číslo účtu**, tak pole **Číslo  ** protiúčtu. Kladná částka v poli **Částka** je odečtena od hlavního účtu a připsána na vyrovnávací účet. Záporná částka je připsána na hlavní účet a odečtena z vyrovnávacího účtu.

**Poznámka**: DPH se vypočítává samostatně pro hlavní účet a vyrovnávací účet, takže mohou být použity různé procentní sazby DPH.

## <a name="recurring-journals"></a>Periodické deníky
Periodický deník je obecný deník se specifickými poli pro správu transakcí, které často odesíláte beze změn nebo s malými změnami.  Pomocí těchto polí pro periodické transakce můžete odesílat jak pevné, tak variabilní částky. Můžete také zadat položky storna pro den po datu zúčtování a použít rozdělovací klíče s periodickými položkami.

## <a name="see-also"></a>Viz také
[Návod: Použití rozdělovacích klíčů ve finančních denících.](ui-how-use-allocation-keys-general-journals.md)  
[Finance](Finance.md)  
[Práce s Dynamics NAV](ui-work-product.md)

