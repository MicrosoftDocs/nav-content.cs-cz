---
title: "Návody: Zaznamenejte nákupy"
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 070023ce05a5e5eefe6fc1151d81f0b88484bb99
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-record-purchases"></a>Návody: Zaznamenejte nákupy
Vytvoříte nákupní fakturu nebo nákupní objednávku k zaznamenání nákladů za nákupy a ke sledování závazků.  Pokud potřebujete kontrolovat zásoby, nákupní faktury a pokud jsou nákupní objednávky také používány k dynamickému aktualizování úrovní zásob, takže můžete minimalizovat náklady zásob a poskytovat lepší služby zákazníkům.  Náklady na nákup, včetně nákladů na služby a hodnoty zásob, které jsou výsledkem účtování nákupních faktur nebo objednávek, přispívají k hodnotám zisku a k dalším finančním ukazatelům KPI na vaší domovské stránce.

**Poznámka**: Musíte použít nákupní objednávky, pokud váš nákupní proces vyžaduje, abyste zaznamenali částečné příjemky objednaného množství, například proto, že v dodavateli nebylo k dispozici celé množství. Pokud prodáváte zboží dodáním přímo od vašeho  dodavatele zákazníkovi jako přímou dodávku zboží, pak musíte také použít nákupní objednávky. Pro další informace, viz [Návody: Provádění přímých dodávek zboží](sales-how-drop-shipment.md). Ve všech ostatních ohledech fungují nákupní objednávky stejným způsobem jako nákupní faktury. Následující postup je založen na nákupní faktuře. Kroky jsou podobné jako u nákupní objednávky.

Když obdržíte skladové položky, nebo když je dokončena nákupní služba, zaúčtujete nákupní fakturu nebo objednávku k aktualizaci zásob a finančních záznamů a aktivujete platbu dodavateli podle platebních podmínek. Pro další informace viz [Provést platby](payables-make-payments.md).

**Pozor**: Neúčtujte nákupní fakturu, dokud neobdržíte produkty a nebudete vědět finální náklady nákupu, včetně případných dodatečných poplatků.  V opačném případě může být hodnota vašich zásob zkreslená.

Pokud jste již zaplatili za produkty na vyúčtované nákupní faktuře, pak si musíte pro stornování nákupu vytvořit nákupní dobropis. Pro další informace, viz [Návody: Zpracování vratek nebo zrušení nákupů](purchasing-how-process-purchase-returns-cancellations.md).

Produkty mohou být jak skladové položky, tak služby. Pro další informace, viz [Návody: Registrace nových produktů](inventory-how-register-new-products.md). Proces nákupní faktury je stejný pro oba typy produktů.



Položky dodavatele na nákupní faktuře můžete vyplnit dvěma způsoby v závislosti na tom, zda je dodavatel již zaregistrován.

## <a name="to-create-a-purchase-invoice"></a>Vytvoření nákupní faktury
1. Na domovské stránce vyberte akci **Nákupní faktury**.  
2. Do pole **Dodavatel** zadejte název stávajícího zákazníka.

    Další pole v okně **Nákupní faktury** jsou nyní vyplněna standardními informacemi vybraného dodavatele. Pokud dodavatel není registrován, postupujte takto:
3. Do pole **Dodavatel** zadejte název nového dodavatele.
4. V dialogovém okně o registraci nového dodavatele zvolte tlačítko **Ano**.
5. V okně **Vybrat šablonu pro nového dodavatele**  vyberte šablonu, na které bude založena nová karta dodavatele, a potom klepněte na tlačítko **OK**.
6. Otevře se nová karta dodavatele, která je předvyplněná informacemi o vybrané šabloně dodavatele. Pole **Název** je vyplněno novým jménem dodavatele, které jste zadali na nákupní faktuře.
7. Pokračujte k vyplnění zbývajících polí na kartě dodavatele. Pro další informace, viz [Návody: Registrace nového dodavatele](purchasing-how-register-new-vendors.md).  
8. Po dokončení karty dodavatele zvolte tlačítko **OK** k návratu do okna **Nákupní faktura**.

    Několik polí v okně **Nákupní faktury** je vyplněno informacemi uvedenými na nové kartě dodavatele.
9. V případě potřeby vyplňte zbývající pole v okně **Nákupní faktury**. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.

    Nyní jste připraveni vyplnit řádky nákupní faktury skladovými položkami inventáře nebo službami, které jste zakoupili od dodavatele.

    **Poznámka**: Pokud jste pro dodavatele nastavili opakované řádky nákupu, jako například měsíční doplňující objednávku, pak můžete tyto řádky na fakturu vložit výběrem akce **Získat opakované nákupní řádky**.
10. Na záložce s náhledem **Řádky**, v poli **Číslo zboží** zadejte číslo skladové položky nebo služby.
11. Do pole **Množství** zadejte číslo položek k nákupu. 

    **Poznámka**: U položek typu **Služba** je množství časovou jednotkou, např. hodiny, jak je uvedeno na řádku v poli **Kód měrné jednotky**.

    Pole **Částka řádku** je aktualizována tak, aby zobrazovala hodnotu v poli **Nákupní cena** vynásobená hodnotou v poli **Množství**.

    Cena a částka řádku jsou zobrazeny s nebo bez prodejní daně podle toho, co jste vybrali v poli **Ceny včetně daně** na kartě dodavatele.
12. Do pole **Částka fakturační slevy** zadejte částku, která by měla být odečtena od hodnoty zobrazené v poli **Celkem včetně daně** v dolní části faktury.

    **Poznámka**: Pokud jste pro dodavatele nastavili slevy z faktury, pak se zadaná procentní hodnota automaticky vloží do pole **Sleva z faktury dodavatele (%)**, pokud jsou splněna kritéria, a příslušná částka je se vloží do pole **Částka slevy z faktury**.
13. Když obdržíte zakoupené položky nebo služby, zvolte možnost **zaúčtovat**.

Nákup se nyní odráží v zásobách a finančních záznamech a aktivuje se platba dodavateli. Nákupní faktura je odstraněna ze seznamu nákupních faktur a nahrazena novým dokumentem v seznamu vyúčtovaných nákupních faktur.

## <a name="see-also"></a>Viz také  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Nastavení nákupu](purchasing-setup-purchasing.md)  
[Návody: Nákup produktů pro prodej](purchasing-how-purchase-products-sale.md)  
[Návody: Registrace nového dodavatele](purchasing-how-register-new-vendors.md)  
[Návody: Příprava přímé dodávky zboží](sales-how-drop-shipment.md)  
[Práce s Dynamics NAV](ui-work-product.md)

