---
title: "Ověření automaticky vyrovnaných plateb a ručně znovu vyrovnat platby"
description: "Po automatickém vyrovnání plateb můžete zkontrolovat všechny položky pro platbu a ručně znovu vyrovnat ty, které byly vyrovnány nesprávně."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment process, reconcile payment, expenses, cash receipts
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 336dd02d1f29e5f80209961eae164a6faeaf65bc
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-review-or-apply-payments-manually-after-automatic-application"></a>Návod: Kontrola nebo manuální vyrovnání plateb po automatickém vyrovnání.
Pro každý řádek deníku představující platbu v okně **Deníku odsouhlasení plateb**, můžete otevřít okno **Vyrovnání plateb**, aby jste viděli všechny kandidátní otevřené položky pro platbu a také můžete zobrazit podrobné informace pro každou položku shodného data, z něhož je založeno platební vyrovnání. Můžete zde ručně vyrovnat platby nebo znovu vyrovnat platby, které byly automaticky vyrovnány se špatným záznamem. Pro více informací o automatickém vyrovnání jděte na [Návod: Odsouhlasení plateb pomocí automatické aplikace](receivables-how-reconcile-payments-auto-application.md).

> [!IMPORTANT]  
>   Pokud je bankovní účet, na kterém vyrovnáváte platby nastaven na lokální měnu, potom okno **Vyrovnání plateb** zobrazí všechny otevřené položky v lokální měně včetně otevřených položek pro dokumenty, které byly původně fakturovány v cizí měně. Vyrovnání plateb položek s konvertovanými měnami mohou být zaúčtovány s jinými částkami, než byly na původním dokladu, protože mohou být rozdílné směnné kurzy používané bankou a [!INCLUDE[d365fin](includes/d365fin_md.md)].

Proto doporučujeme sledovat kódy cizích měn v poli **Kód měny** v okně **Vyrovnání plateb**, abyste zjistili, zda je vyrovnání založené na měně. Ke kontrole původní částky dokladu v cizí měně použitého směnného kurzu, zvolte pole **Vyrovnává položku číslo** a poté v místní nabídce vyberte tlačítko na rozbalení nabídky **Položky zákazníka** nebo **Položky dodavatele**.

Každá úprava zisku a ztrát, která je zapotřebí v důsledku měnových konverzí, není automaticky prováděna [!INCLUDE[d365fin](includes/d365fin_md.md)].

> [!NOTE]  
>   Nemůžete vyrovnávat položky s jiným znaménkem než znaménkem platby. Chcete-li například uzavřít dobropis se záporným znaménkem a jeho související faktura je s kladným znaménkem, musíte nejprve vyrovnat fakturu k dobropisu a poté platbu vyrovnat na faktuře se sníženou zbývající částkou.

> [!WARNING]  
>   Pokud používáte skonto slevy a pokud je datum splatnosti před datem splatnosti platby, poté políčko **Zůstatková částka Včetně skonta** v okně **Vyrovnání plateb** bude použito pro párování. V opačném případě se použije hodnota v poli  **Zůstatek**. Pokud byla platba provedena s diskontovanou částkou po splatnosti platby nebo byla zaplacena celá částka, ale byla poskytnuta sleva, částka nebude odpovídat.

> [!NOTE]  
>   Můžete pouze vyrovnat položku pro jeden účet. Chcete-li rozdělit vyrovnání na několik otevřených položek, například k uplatnění jednorázové platby, musí být otevřené položky pro stejný účet. Další informace naleznete v krocích 7 a 8 v postupu v tomto tématu.

## <a name="to-review-or-apply-payments-after-automatic-application"></a>Kontrola nebo vyrovnaní platby po automatickém vyrovnání
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky odsouhlasení plateb** a poté vyberte příslušný odkaz.
2. Otevřete deník odsouhlasení plateb pro bankovní účet, u kterého chcete odsouhlasit platby. Další informace naleznete v [Návod: Odsouhlasení plateb pomocí automatické aplikace](receivables-how-reconcile-payments-auto-application.md).
3. V okně **Deníku odsouhlasení plateb** vyberte platbu, kterou chcete zkontrolovat nebo ručně vyrovnat na jednu nebo více otevřených položek a potom vyberte akci **Vyrovnat ručně**.
4. Vyberte zaškrtávací políčko **Vyrovnáno** na řádku pro otevřenou položku, na kterou chcete platbu použít.
5. Částka platby, která je zobrazena také v poli **Částka transakce** v okně **Vyrovnání plateb**, je vložena do pole **Vyrovnaná částka**, ale pole můžete upravit, například pokud chcete částku použít na několik otevřených položek.
6. Chcete-li část částky platit na jinou otevřenou položku účtu, například použít jednorázovou platbu, zaškrtněte políčko **Vyrovnáno** za řádku. Použitá částka se automaticky odečte z objemu transakcí tak, aby odrážely rozdělení na dvou otevřených položkách.
7. Chcete-li část částky vyrovnat do jedné nebo více otevřených položek, které v databázi neexistují, vytvořte nový řádek pod řádkem pro stejný účet. Do pole **Vyrovnaná částka** zadejte částku, která se má použít na nový řádek, a upravte pole **Vyrovnaná částka** na existujícím řádku.
8. Opakujte kroky 5, 6 nebo 7 pro další otevřené položky, u kterých chcete vyrovnat úplnou nebo částečnou sumu platby.
9. Po kontrole vyrovnání platby nebo při ručním vyrovnání na jednu nebo více otevřených položek zvolte akci **Akceptovat vyrovnání**.

Okno **Vyrovnání plateb** se zavře a v **Deníku vyrovnání plateb** se hodnota v poli **Spolehlivost spárovaní** změní na hodnotu **Přijato** a zobrazí se Vám, že jste platbu prověřili nebo ručně provedli.

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Prodej](sales-manage-sales.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

