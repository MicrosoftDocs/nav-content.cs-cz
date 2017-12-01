---
title: "Vytvořte prodejní nabídku zákazníkovi"
description: "Popisuje, jak vytvořit doklad o prodeji nebo žádosti o návrh (RFG), který zaznamená vaši nabídku zákazníkovi za účelem prodeje produktů za určitých podmínek."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: rfq
ms.date: 08/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 21611abbb658ddcd4e422269db9677bca3ea4f35
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-make-offers"></a>Návod: Vytváření nabídek
Můžete vytvořit prodejní nabídky, abyste zaznamenali vaši nabídku zákazníkovi o prodeji určitých produktů za určitých dodacích a platebních podmínek. Můžete posílat prodejní nabídku zákazníkovi pro budoucí komunikaci o nabídce. Nabídku můžete odeslat jako přílohu ve formátu PDF emailem. Tělo emailu může být předvyplněno souhrnem nabídky. Další informace naleznete v [Návod: Posílání dokumentů pomocí Emailu](ui-how-send-documents-email.md).

Při vyjednávání se zákazníkem můžete změnit a odeslat prodejní nabídku, tak jak budete potřebovat. Když zákazník přijme nabídku, můžete ji převést na prodejní fakturu nebo prodejní objednávku, kterou zpracujete pro prodej. Další informace naleznete v [Návod: Fakturování prodeje](sales-how-invoice-sales.md) nebo[ Návod: Prodávání produktu](sales-how-sell-products.md).

Políčka zákazníků můžete vyplnit na prodejní nabídce dvěma způsoby v závislosti na tom, zda je zákazník již zaregistrován. Viz kroky 2 a 3 v následujícím postupu.

## <a name="to-create-a-sales-quote"></a>Vytvoření prodejní nabídky
Na domovské stránce vyberte tlačítko **Prodejní nabídky**.  
2. V políčku **Zákazník** napište jméno existujícího zákazníka.

   Ostatní pole v okně **Prodejní nabídka** jsou nyní vyplněny informacemi vybraného zákazníka. Pokud není zákazník registrován, následujte tyto kroky:
3. V políčku **Zákazník** napište jméno nového zákazníka.
4. V dialogovém okně o registraci nového zákazníka zvolte tlačítko **Ano**.
5. V okně **Vybrat šablonu pro nového zákazníka** vyberte šablonu, na které bude založena nová zákaznická karta, a potom klepněte na tlačítko **OK**.
6. Displej nová zákaznická karta předvyplněná informacemi ze zvolené šablony zákazníků. Vyplňte příslušná pole. Další informace naleznete v [Návod: Registrace nového zákazníka](sales-how-register-new-customers.md).  
7. Po dokončení karty zákazníka zmáčkněte tlačítko **OK**, abyste se vrátili do okna **Prodejní nabídka**.

   Několik polí na prodejní nabídce je nyní vyplněno informacemi uvedenými na nové kartě zákazníka.  
8. V případě potřeby vyplňte zbývající pole v okně **Prodejní nabídka**. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

Nyní jste připraveni vyplnit řádky prodejní objednávky pro produkty, které prodáváte zákazníkovi, nebo pro jakoukoli transakci se zákazníkem, kterou chcete zaznamenat do hlavní knihy.   

Pokud jste pro zákazníka nastavili opakované prodejní řádky, například objednávku měsíčního doplňování, můžete tyto řádky vložit na objednávku vybráním akce **Získat periodické prodejní řádky**.  
9. Na záložce s náhledem **Řádky** v poli **Typ** vyberte, jaký typ produktu, účtování nebo transakci, kterou zaúčtujete zákazníkovi s prodejní linkou.
10. Do pole **Číslo** vyberte záznam, který chcete odesílat podle hodnoty v poli **Typ**.

 Pole **Číslo** necháte prázdné v následujících případech: -Pokud je řádek pro komentář: Napište komentář do pole **Popis**.
 -Pokud je řádek pro neskladové zboží. Zvolte akci **Vybrat neskladové zboží**. Další informace naleznete v [Návod: Práce s neskladovaným zbožím](inventory-how-work-nonstock-items.md).

11. Do pole **Množství** zadejte počet jednotek produktu, účtování nebo transakci, který řádek se zaznamená pro zákazníka.

    Hodnota v poli **Částka řádku** se vypočítá jako *Jednotková cena* x *Množství*.  

    Částka ceny a řádku jsou s nebo bez DPH v závislosti na tom, co jste vybrali v poli **Ceny včetně DPH** na kartě zákazníka.  
12. Pokud chcete poskytnout slevu, zadejte procento do pole **Sleva na řádek %**. Hodnota v poli **Částka na řádku** se odpovídajícím způsobem aktualizována.  

    Pokud nastavíte speciální ceny na záložce **Prodejní ceny a řádkové slevy** na kartě zákazníka nebo kartě položky, potom se cena na řádku automaticky aktualizuje pokud jsou splněna daná kritéria. Další informace naleznete v tématu: [Zaznamenání prodejní ceny, slevy, a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).  
13. Opakujte kroky 9 až 12 pro každou položku, kterou chcete nabídnout zákazníkovi.  

    Součty pod řádky se automaticky vypočítají při vytváření nebo úpravách řádků.  
14. Do pole **Částka fakturační slevy** zadejte částku, která by měla být odečtena od hodnoty zobrazené v položce **Celkem včetně DPH**.

    Pokud jste zákazníkovi nastavili fakturační slevu, zadaná procentní hodnota se automaticky vloží do pole **Fakturační sleva %**, pokud jsou splněna kritéria a příslušná částka je vložena do pole **Fakturační sleva bez DPH**. Pro více informací jděte na: [Zaznamenání prodejní ceny, slevy, a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).
15. Po dokončení řádků prodejní nabídky vyberte tlačítko **Poslat E-mailem** nebo Tisk.
16. V okně **Poslat e-mailem** vyplňte všechna zbývající pole a zkontrolujte vestavěnou prodejní nabídku. Další informace naleznete v [Návod: Posílání dokumentů pomocí Emailu](ui-how-send-documents-email.md).
17. Pokud zákazník akceptuje nabídku, zvolte **Vytvořit fakturu** nebo **Vytvořit objednávku**.

Prodejní nabídka je smazána z databáze. Prodejní faktura nebo prodejní objednávka je vytvořena na základě informací z prodejní nabídky, ze které uskutečňujete prodej. V poli **Nabídka číslo** na prodejní faktuře nebo prodejní objednávce můžete vidět číslo prodejní nabídky, ze které byly vytvořeny. Další informace naleznete v [Návod: Fakturování prodeje](sales-how-invoice-sales.md) nebo[ Návod: Prodávání produktu](sales-how-sell-products.md).

## <a name="see-also"></a>Viz také
[Prodej](sales-manage-sales.md)  
[Nastavení prodeje](sales-setup-sales.md)  
[Návody Odesílání dokladů e-mailem](ui-how-send-documents-email.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

