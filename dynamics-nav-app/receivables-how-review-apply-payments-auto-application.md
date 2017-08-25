---
title: "Návod: Kontrola nebo manuální vyrovnání plateb po automatickém vyrovnání."
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
ms.openlocfilehash: 556a0f74a7407d247008e2d74420803123056eff
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-review-or-apply-payments-manually-after-automatic-application"></a>Návod: Kontrola nebo manuální vyrovnání plateb po automatickém vyrovnání.
Pro každý řádek deníku představující platbu v okně **Deníku odsouhlasení plateb**, můžete otevřít okno **Vyrovnání plateb**, aby jste viděli všechny kandidátní otevřené položky pro platbu a také můžete zobrazit podrobné informace pro každou položku shodného data, z něhož je založeno platební vyrovnání. Můžete zde ručně vyrovnat platby nebo znovu vyrovnat platby, které byly automaticky vyrovnány se špatným záznamem. Pro více informací o automatickém vyrovnání jděte na [Návod: Vyrovnání plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).

**Důležité**: Pokud je bankovní účet, na kterém vyrovnáváte platby nastaven na lokální měnu, potom okno **Vyrovnání plateb** zobrazí všechny otevřené položky v lokální měně včetně otevřených položek pro dokumenty, které byly původně fakturovány v cizí měně. Vyrovnání plateb položek s konvertovanými měnami mohou být zaúčtovány s různými částkami, než na původním dokladu, protože mohou být rozdílné směnné kurzy používané bankou a Dynamics NAV.

Proto doporučujeme sledovat kódy cizích měn v poli **Kód měny** v okně **Vyrovnání plateb**, abyste zjistili, zda je vyrovnání založené na měně. Chcete-li zkontrolovat počáteční částku v cizí měně a zobrazit použitý směnný kurz, vyberte pole **Vyrovnat položku číslo**  a poté, v místní nabídce vyberte tlačítko na rozbalení nabídky **Položky zákazníka** nebo **Položky dodavatele**

Každá úprava zisku a ztrát, která je zapotřebí v důsledku měnových konverzí, není automaticky prováděna Dynamics NAV.

**Poznámka**: Nemůžete vyrovnávat položky s jiným znaménkem než znaménkem platby. Chcete-li například uzavřít dobropis s záporným znaménkem a jeho související faktura je s kladným znaménkem, musíte nejprve vyrovnat fakturu k dobropisu a poté platbu vyrovnat na faktuře se sníženou zbývající částkou.

**Upozornění**: Pokud používáte platební slevy a pokud je datum splatnosti před datem splatnosti platby, poté políčko **Zbývající částka včetně slevy** v okně **Vyrovnání plateb** bude použita pro párování. V opačném případě se použije hodnota v poli  **Zbývající částka**. Pokud byla platba provedena s diskontovanou částkou po splatnosti platby nebo byla zaplacena celá částka, ale byla poskytnuta sleva, částka nebude odpovídat.

**Poznámka**: Můžete pouze vyrovnat položku pro jeden účet. Chcete-li rozdělit vyrovnání na několik otevřených položek, například k uplatnění jednorázové platby, musí být otevřené položky pro stejný účet. Další informace naleznete v krocích 7 a 8 v postupu v tomto tématu.

## <a name="to-review-or-apply-payments-after-automatic-application"></a>Kontrola nebo vyrovnaní platby po automatickém vyrovnání
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky odsouhlasení plateb** a poté vyberte příslušný odkaz.
2. Otevřete deník odsouhlasení plateb pro bankovní účet, u kterého chcete odsouhlasit platby. Další informace naleznete v tématu [Návod: Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).
3. V okně **Deníku odsouhlasení plateb** vyberte platbu, kterou chcete zkontrolovat nebo ručně vyrovnat na jednu nebo více otevřených položek a potom vyberte akci **Vyrovnat ručně**
4. Vyberte zaškrtávací políčko **Vyrovnáno** na řádku pro otevřenou položku, na kterou chcete platbu použít.
5. Částka platby, která je zobrazena také v poli **Částka transakce** v okně **Vyrovnání plateb**, je vložena do pole **Vyrovnaná částka**, ale pole můžete upravit, například pokud chcete částku použít na několik otevřených položek.
6. Chcete-li část částky platit na jinou otevřenou položku účtu, například použít jednorázovou platbu, zaškrtněte políčko **Vyrovnáno** za řádku. Použitá částka se automaticky odečte z objemu transakcí tak, aby odrážely rozdělení na dvou otevřených položkách.
7. Chcete-li část částky vyrovnat do jedné nebo více otevřených položek, které v databázi neexistují, vytvořte nový řádek pod řádkem pro stejný účet. Do pole **Vyrovnaná částka** zadejte částku, která se má použít na nový řádek, a upravte pole **Vyrovnaná částka** na existujícím řádku.
8. Opakujte kroky 5, 6 nebo 7 pro další otevřené položky, u kterých chcete vyrovnat úplnou nebo částečnou sumu platby.
9. Po kontrole vyrovnání platby nebo při ručním vyrovnání na jednu nebo více otevřených položek zvolte akci **Přijmout vyrovnání**.

Okno **Vyrovnání plateb** se zavře a v **Deníku vyrovnání plateb** se hodnota v poli **Spolehlivost spárovaní** změní na hodnotu **Přijato** a zobrazí se Vám, že jste platbu prověřili nebo ručně provedli.

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Správa prodeje](sales-manage-sales.md)

