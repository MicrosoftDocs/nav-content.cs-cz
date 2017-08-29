---
title: "Návod: Vytvoření vlastního rozvržení Sestavy"
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
ms.openlocfilehash: 90136439e09deb00a9aed9344fc5f89812caef3a
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-a-custom-report-layout"></a>Návod: Vytvoření vlastního rozvržení Sestavy
Ve výchozím nastavení bude mít sestava vestavěný rozvrh sestav, který může být RDLC, rozvržení sestavy aplikace Word nebo obojí. Nemůžete editovat vestavěné sestavy. Můžete však vytvořit vlastní rozvržení, které vám umožní změnit vzhled sestavy při jejím náhledu, tisku nebo uložení. Pro sestavu můžete vytvořit více rozvržení sestav a podle potřeby přepnout rozvržení, které sestava používá.

Chcete-li vytvořit vlastní rozvržení, můžete buď vytvořit kopii stávajícího vlastního rozvržení, nebo přidat nové vlastní rozvržení, které je ve většině případů založeno na vestavěném rozvržení. Když přidáte nové vlastní rozvržení, můžete přidat typ rozvržení sestavy RDLC, typ rozvržení sestavy aplikace Word nebo obojí. Nové vlastní rozvržení bude automaticky založeno na vestavěném, pokud je k dispozici. Není-li pro daný typ vestavěné rozvržení, vytvoří se nové prázdné rozvržení, které budete muset modifikovat a navrhnout od začátku. Další informace o rozvržení RDLC a Wordových sestav, vestavěných, vlastních rozvržení a dalších naleznete v tématu [Správa rozvržení sestav](ui-manage-report-layouts.md).  

## <a name="to-create-a-custom-layout"></a>Vytvoření vlastního rozvržení
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Výběr rozvržení sestav** a poté vyberte příslušný odkaz.  
Okno ** Výběr rozvržení sestav ** obsahuje seznam všech sestav, které jsou k dispozici ve společnosti, která je uvedena v poli Společnost v horní části okna.
2. Nastavte pole **Název společnosti**, ve které chcete vytvořit rozvržení sestavy.
3. Vyberte řádek se sestavou, pro kterou chcete vytvořit rozvržení, a poté zvolte **Vlastní rozvržení**.  
Zobrazí se okno **Vlastní rozvržení sestav** a zobrazí seznam všech vlastních rozvržení, které jsou k dispozici pro vybraný přehled.
4. Chcete-li vytvořit kopii existujícího vlastního rozvržení, vyberte existující vlastní rozložení v seznamu a zvolte možnost **Kopírovat**.  
Kopie vlastního rozvržení se zobrazí v okně **Vlastní rozvržení sestav** a v poli Popis obsahuje zkopírovaná slova.
5. Pokud chcete přidat nové vlastní rozvržení založené na vestavěném rozvržení, postupujte takto:  
    1. Zvolte **Nový**. Objeví se okno **Vložit rozvržení sestav**,  **ID** a **Název** se vyplní automaticky.
    2. Chcete-li přidat vlastní formát rozvržení sestavy z aplikace Word, vyberte zaškrtávací políčko **Vložit rozvržení Wordu**.
    3. Chcete-li přidat vlastní formát rozvržení sestavy z aplikace RDLC, vyberte zaškrtávací políčko **Vložit RDLC rozvržení**.
    4. Zvolte tlačítko **OK**.  
    Nové vlastní rozvržení se zobrazí v okně **Vlastní rozvržení sestav**. Pokud je nové rozvržení založeno na vestavěném rozvržení, má v poli **Popis** slova **Kopie vestavěného rozvržení**. Pokud pro sestavu neexistuje žádné vestavěné rozvržení, nové rozložení má v poli **Popis** výraz **Nové rozvržení**, což znamená, že vlastní rozvržení je prázdné.
6. Ve výchozím nastavení je pole **Název společnosti** prázdné, což znamená, že vlastní sestava bude k dispozici ve všech společnostech. Chcete-li vytvořit vlastní uspořádání pouze v konkrétní společnosti, zvolte možnost **Upravit** a poté pole **Název společnosti** k nastavení na požadované společnosti.

## <a name="see-also"></a>Viz také
[Správa rozvržení sestav](ui-manage-report-layouts.md)  
[Návod: Změna využívaného rozvržení pro danou sestavu](ui-how-change-layout-currently-used-report.md)

