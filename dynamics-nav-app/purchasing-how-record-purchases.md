---
title: "Vytvoření nákupní faktury nebo zaznamenávání nákupů"
description: "Popisuje jak platit zásoby a servis vytvořením a účtováním nákupních faktur a objednávek."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: procurement
ms.date: 08/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d5583290925252acee6a05be29f589d057794c28
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-record-purchases"></a>Návod: Zaznamenávání nákupu
Vytvořte nákupní fakturu nebo nákupní objednávku k zaznamenání nákladů za nákupy a ke sledování závazků. Pokud potřebujete kontrolovat zásoby, nákupní faktury a pokud jsou nákupní objednávky také používány k dynamickému aktualizování úrovní zásob, můžete minimalizovat náklady zásob a poskytovat lepší služby zákazníkům. Náklady na nákup, včetně nákladů na služby a hodnoty zásob, které jsou výsledkem účtování nákupních faktur nebo objednávek, přispívají k hodnotám zisku a k dalším finančním ukazatelům KPI na vaší domovské stránce.

> [!NOTE]  
>   Musíte použít nákupní objednávky, pokud váš nákupní proces vyžaduje, abyste zaznamenali částečné příjmy objednaného množství, například proto, že dodavatelé nemají k dispozici celé množství. Pokud prodáváte zboží zákazníkovi dodáním přímo od vašeho  dodavatele jako přímou dodávku zboží, pak musíte také použít nákupní objednávky. Další informace naleznete v tématu [Návod: Vytvoření přímé dodávky.](sales-how-drop-shipment.md) Ve všech ostatních ohledech fungují nákupní objednávky stejným způsobem jako nákupní faktury. Následující postup je založen na nákupní faktuře. Kroky jsou podobné jako u nákupní objednávky.

Když obdržíte skladové položky, nebo když je dokončena nákupní služba, zaúčtujete nákupní fakturu nebo objednávku k aktualizaci zásob a finančních záznamů a aktivujete platbu dodavateli podle platebních podmínek. Další informace naleznete v tématu: [Provést platby](payables-make-payments.md).

> [!CAUTION]  
>   Neúčtujte nákupní fakturu, dokud neobdržíte produkty a nebudete vědět finální náklady nákupu, včetně případných dodatečných poplatků. V opačném případě může být hodnota vašich zásob zkreslená.

Jednoduše můžete opravit nebo zrušit účtovanou nákupní fakturu předtím, než ji zaplatíte dodavateli. Je to velice užitečné pokud chcete opravit chybu při zadávaní nebo když chcete změnit platbu dříve než je zpracovaná. Další informace naleznete v tématu [Návod: Opravit nebo zrušit nezaplacené nákupní faktury](purchasing-how-correct-cancel-unpaid-purchase-invoices.md) Pokud jste již zaplatili za zboží na vyúčtované nákupní faktuře, pak si musíte pro stornování nákupu vytvořit nákupní dobropis. Další informace naleznete v tématu [Návod: Zpracování vratek nebo zrušení nákupů.](purchasing-how-process-purchase-returns-cancellations.md)

Zboží může být typ: **Zásoby** nebo **Servis**. Další informace naleznete v tématu [Návod: Registrovat nového zboží](inventory-how-register-new-items.md). Proces nákupní faktury je stejný pro oba typy produktů.

Položky dodavatele na nákupní faktuře můžete vyplnit dvěma způsoby v závislosti na tom, zda je dodavatel již zaregistrován.

## <a name="to-create-a-purchase-invoice"></a>Vytvoření nákupní faktury
1. Na domovské stránce vyberte akci **Nákupní faktury**.  
2. Do pole **Dodavatel** zadejte název existujícího dodavatele.

    Další pole v okně **Nákupní faktury** jsou nyní vyplněna standardními informacemi vybraného dodavatele. Pokud dodavatel není registrován, postupujte takto:
3. Do pole **Dodavatel** zadejte název nového dodavatele.
4. V dialogovém okně o registraci nového dodavatele zvolte tlačítko **Ano**.
5. V okně **Vybrat šablonu pro nového dodavatele**  vyberte šablonu, podle které bude založena nová karta dodavatele, a potom klepněte na tlačítko **OK**.
6. Otevře se nová karta dodavatele, která je předvyplněná informacemi z vybrané šablony dodavatele. Pole **Název** je vyplněno novým jménem dodavatele, které jste zadali na nákupní faktuře.
7. Pokračujte k vyplnění zbývajících polí na kartě dodavatele. Další informace naleznete v tématu [Návod: Registrace nového dodavatele.](purchasing-how-register-new-vendors.md)  
8. Po dokončení karty dodavatele zvolte tlačítko **OK** k návratu do okna **Nákupní faktura**.

    Několik polí v okně **Nákupní faktury** je vyplněno informacemi uvedenými na nové kartě dodavatele.
9. V případě potřeby vyplňte zbývající pole v okně **Nákupní faktury**. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    Nyní jste připraveni vyplnit řádky nákupní faktury skladovými položkami zboží nebo službami, které jste zakoupili od dodavatele.

    > [!NOTE]  
>   Pokud jste pro dodavatele nastavili periodické řádky nákupu, jako například měsíční doplňující objednávku, pak můžete tyto řádky na fakturu vložit výběrem akce **Získat periodické nákupní řádky**.
10. Na záložce **Řádky** v políčku **Zboží**, vložte číslo skladové položky nebo služby.
11. Do pole **Množství** zadejte číslo položek k nákupu.

    > [!NOTE]  
>   U položek typu **Služba** je množství časovou jednotkou, např. hodiny, jak je uvedeno na řádku v poli **Kód měrné jednotky**.

    Pole **Částka řádku** je aktualizována tak, aby zobrazovala hodnotu v poli **Nákupní cena** vynásobená hodnotou v poli **Množství**.

    Cena a částka řádku jsou zobrazeny s nebo bez prodejní daně podle toho, co jste vybrali v poli **Ceny včetně daně** na kartě dodavatele.
12. Do pole **Částka fakturační slevy** zadejte částku, která by měla být odečtena od hodnoty zobrazené v poli **Celkem včetně daně** v dolní části faktury.

    > [!NOTE]  
>   Pokud jste pro dodavatele nastavili fakturační slevy, pak se zadaná procentní hodnota automaticky vloží do pole **Fakturační sleva (%)**, pokud jsou splněna kritéria, a příslušná částka je se vloží do pole **Částka fakturační slevy**.
13. Když obdržíte zakoupené položky nebo služby, zvolte možnost **Účtovat**.

Nákup se nyní odráží v zásobách a finančních záznamech a aktivuje se platba dodavateli. Nákupní faktura je odstraněna ze seznamu nákupních faktur a nahrazena novým dokumentem v seznamu Účtovaných nákupních faktur.

## <a name="see-also"></a>Viz také
[Nákup](purchasing-manage-purchasing.md)  
[Nastavení nákupu](purchasing-setup-purchasing.md)  
[Návod: Požadované nabídky](purchasing-how-request-quotes.md)  
[Návod: Nákup zboží pro prodej](purchasing-how-purchase-products-sale.md)  
[Návod: Registrace nového dodavatele](purchasing-how-register-new-vendors.md)  
[Návod: Příprava přímé dodávky zboží](sales-how-drop-shipment.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

