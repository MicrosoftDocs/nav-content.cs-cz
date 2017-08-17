---
title: "Návod: Převod bankovních prostředků"
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f34bef80c64cbad0a0b20d4d021cefbdc5a1cb64
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-transfer-bank-funds"></a>Návod: Převod bankovních prostředků
Někdy budete možná muset převést částku z jednoho bankovního účtu na jiný. Chcete-li to provést, musíte odeslat transakci do finančního deníku. Úloha se liší v závislosti na tom, zda bankovní účty používají stejnou měnu nebo různé měny.

## <a name="to-post-a-transfer-between-bank-accounts-with-the-same-currency-code"></a>Zaúčtování převodu mezi bankovními účty se stejným kódem měny
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Finanční deník** a pak vyberte související odkaz.
2. Na řádku deníku vyplňte pole **Zúčtovací datum** a **Číslo dokladu** .
3. V poli **Typ účtu** vyberte **Bankovní účet**.
4. V poli **Číslo účtu** vyberte banku, ze které chcete peníze převést.
5. Do pole **Částka** zadejte částku, kterou chcete převést.
6. V **Bal. V poli Typ účtu** vyberte **Bankovní účet**.
7. V **Bal. číslo účtu** pole vyberte bankovní účet, ke kterému chcete peníze převést.
8. Zaúčtovat deník.

## <a name="to-post-a-transfer-between-bank-accounts-with-different-currency-codes"></a>Zaúčtování převodu mezi bankovními účty s různými kódy měn
Chcete-li převádět finanční prostředky mezi bankovními účty, které používají různé měny, musíte zaúčtovat dva řádky finančního deníku.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Finanční deník** a pak vyberte související odkaz.
2. Vytvořte dva řádky deníku a vyplňte pole **Zúčtovací datum** a **Číslo dokumentu** .
3. Na prvním řádku deníku v poli **Typ** vyberte **Bankovní účet**.
4. V poli **Číslo účtu** vyberte bankovní účet, ze kterého chcete peníze převést.
5. V poli **Částka** zadejte částku v měně bankovního účtu. Zadejte částku Dal se znaménkem mínus. Zadejte částku MD se znaménkem mínus.
6. V **Bal. V poli Typ účtu** vyberte **Bankovní účet**.
7. V **Bal. Číslo účtu** Pole vyberte bankovní účet, na který chcete peníze převést.
8. Na druhém řádku deníku v poli **Typ** vyberte **Bankovní účet**.
9. V poli **Číslo účtu** vyberte bankovní účet, na který chcete peníze převést.
10. V poli **Částka** zadejte částku v měně bankovního účtu. Zadejte částku Dal se znaménkem mínus. Zadejte částku MD se znaménkem mínus.
11. V **Bal. V poli Typ účtu** vyberte **Bankovní účet**.  
12. V **Bal. Číslo účtu** vyberte bankovní účet, ze kterého chcete peníze převést.

    **Poznámka**: Pokud se kurzy používané v deníku liší od směnných kurzů v okně **Směnné kurzy**, zadejte třetí řádek pro kurzový zisk nebo ztrátu. Zadejte **Finanční účet** v poli **Typ účtu**. Zadejte číslo finančního účtu pro kurzový zisk nebo ztrátu v poli **Číslo účtu** . Zadejte kurzový zisk nebo ztrátu v poli **Částka** s nebo bez znaménka mínus pro částku Dal a MD.
13. Zaúčtovat deník.

## <a name="see-also"></a>Viz také  
[Správa bankovních účtů.](bank-manage-bank-accounts.md)  
[Nastavení bankovnictví](bank-setup-banking.md)  
[Práce s finančním deníkem](ui-work-general-journals.md)

