---
title: "Návod: Odsouhlasení plateb, které nelze vyrovnat automaticky"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f9fd7c2958aaa359d2f6af5dde2e8be81349e900
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-payments-that-cannot-be-applied-automatically"></a>Návod: Odsouhlasení plateb, které nelze vyrovnat automaticky
Někdy budete muset zpracovávat platby na váš bankovní účet, které nelze vyrovnat na souvisejícího otevřeného zákazníka, dodavatele nebo položku knihy bankovního učtu. Důvodem může být skutečnost, že v programu Dynamics NAV neexistuje žádný doklad, který by umožňoval vyrovnat platbu nebo žádný související dokument v Dynamics NAV nemá jinou částku než částku transakce například kvůli směnně měny. V okně **Deník odsouhlasení plateb** se všechny transakce částek za platby, které nejsou vyrovnány, objeví v poli **Rozdíl** včetně částek, které nelze vyrovnat z důvodů, které jsou uvedené výše.

Platby, které nelze vyrovnat se mohou objevit na řádcích deníku odsouhlasení plateb následujícími různými způsoby:

- Hodnota v poli **Rozdíl** se rovná hodnotě v poli **Částka transakce**, což znamená, že žádnou část platby nelze vyrovnat na souvisejícího otevřeného zákazníka, dodavatele nebo položku knihy bankovního účtu.

- Hodnota v poli **Rozdíl** je nižší než hodnota v poli **Částka transakce**, což znamená, že část platby může být vyrovnána na souvisejícího otevřeného zákazníka, dodavatele nebo položku knihy bankovního účtu. Zbývající část platby nemůže být vyrovnána a musí být odsouhlasena ručně nebo zaúčtována přímo na účet.

Chcete-li odsouhlasit takové platby, můžete zvolit tlačítko Přenos rozdílu k účtu a poté určit, na který účet bude částka v poli Rozdíl zaúčtována, když zaúčtujete deník odsouhlasení plateb.

**Poznámka**: Podobné funkce existují pro nastavení automatického odsouhlasení opakujících se plateb, které nelze vyrovnat na souvisejícího otevřeného zákazníka, dodavatele nebo položku knihy bankovního účtu. [Další informace naleznete v tématu Návod: Mapovat text periodických plateb na účtech pro automatické odsouhlasení](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md).

## <a name="to-reconcile-payments-that-cannot-be-applied"></a>Odsouhlasení plateb, které nelze vyrovnat
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky odsouhlasení plateb** a pak vyberte související odkaz.
2. Otevřete deník odsouhlasení plateb. Další informace naleznete v tématu [Návod: Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).
3. Zvolte **Převod rozdílu k účtu**. Otevře se okno **Převod rozdílu k účtu** 3.
4. Pole **Typ účtu** určuje typ účtu, kde částka platby bude vyrovnána.
5. Pole **Číslo účtu** určuje účet, kde částka platby bude vyrovnána.
6. Pole **Popis** určuje text, který popisuje toto přímé zaúčtování platby. Ve výchozím nastavení je vložen text v poli **Text transakce** na řádku deníku odsouhlasení plateb.
7. Zvolte tlačítko **OK**.

Pokud byla hodnota v poli **Rozdíl** rovna hodnotě v poli **Částka transakce** při zaúčtování deníku odsouhlasení plateb, bude celá platba na řádku deníku zaúčtována přímo pro specifický vyrovnávací účet.

Pokud by hodnota v poli **Rozdíl** byla nižší než hodnota v poli **Částka transakce**, vytvoří se další řádek deníku se stejným textem a datem a s rozdílem vloženým do pole **Částka transakce**. Na původním řádku deníku bude rozdíl odečten od hodnoty v poli **Částka transakce** a platba zůstane vyrovnána na příslušného zákazníka, dodavatele nebo položku knihy bankovního účtu. Při zaúčtování deníku odsouhlasení plateb bude jedna část platby zaúčtována jako vyrovnaná platba. Druhá část platby bude zaúčtována přímo na uvedený účet.

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Správa prodeje](sales-manage-sales.md)

