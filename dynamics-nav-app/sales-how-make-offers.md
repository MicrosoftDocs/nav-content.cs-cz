---
title: "Návod: Vytváření nabídek"
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
ms.openlocfilehash: e126c755a9121c3a91f3af72f3f1ae14702a4701
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-offers"></a>Návod: Vytváření nabídek
Můžete vytvořit prodejní nabídky, abyste zaznamenali vaši nabídku zákazníkovi o prodeji určitých produktů za určitých dodacích a platebních podmínek. Můžete posílat prodejní nabídku zákazníkovi pro budoucí komunikaci o nabídce. Nabídku můžete odeslat jako přílohu ve formátu PDF emailem. Tělo emailu může být předvyplněno souhrnem nabídky. Další informace naleznete v tématu [Návod: Posílání dokumentů pomocí Emailu](ui-how-send-documents-email.md).

Při vyjednávání se zákazníkem můžete změnit a odeslat prodejní nabídku, tak jak budete potřebovat. Když zákazník přijme nabídku, můžete ji převést na prodejní fakturu nebo prodejní objednávku, kterou zpracujete pro prodej. Další informace naleznete v tématu [Návod: Fakturování prodeje](sales-how-invoice-sales.md) nebo [Návod: Prodávání produktu](sales-how-sell-products.md).

Produkt mohou být inventární položky nebo služby. Další informace naleznete v tématu [Návod: Zaznamenávání nových produktů](inventory-how-register-new-products.md). Proces prodejních nabídek je stejný pro oba typy produktů.

**Poznámka**: V produktu [!INCLUDE[navnow](includes/navnow_md.md)] se produkt označuje výrazem „zboží".

Políčka zákazníků můžete vyplnit na prodejní nabídce dvěma způsoby v závislosti na tom, zda je zákazník již zaregistrován.

## <a name="to-create-a-sales-quote"></a>Vytvoření prodejní nabídky
1. Na domovské stránce vyberte tlačítko **Prodejní nabídky**.  
2. V políčku **Zákazník** napište jméno existujícího zákazníka.

    Ostatní pole v okně **Prodejní nabídka** jsou nyní vyplněny informacemi vybraného zákazníka. Pokud není zákazník registrován, následujte tyto kroky:

3. V políčku **Zákazník** napište jméno nového zákazníka.
4. V dialogovém okně o registraci nového zákazníka zvolte tlačítko **Ano**.
5. V okně **Vybrat šablonu pro nového zákazníka** vyberte šablonu, na které bude založena nová zákaznická karta, a potom klepněte na tlačítko **OK**.
6. Otevře se nová zákaznická karta s předplněná informacemi ze zvolené šablony zákazníků. Políčko **Název** je předvyplněno novým jménem zákazníka, kterého jste zadali v prodejní faktuře.
7. Pokračujte vyplněním zbývajících polí na kartě zákazníka. Další informace naleznete v tématu [Návod: Registrace nového zákazníka.](sales-how-register-new-customers.md)  
8. Po dokončení karty zákazníka zmáčkněte tlačítko **OK**, abyste se vrátili do okna **Prodejní nabídka**.

    Několik polí na prodejní nabídce je nyní vyplněno informacemi uvedenými na nové kartě zákazníka.
9. V případě potřeby vyplňte zbývající pole v okně **Prodejní nabídka**. Vyberte pole a přečtěte si krátký popis pole nebo zvolte odkaz pro další informace.

    Nyní jste připraveni vyplnit řádky prodejní nabídky zbožím nebo službami, které chcete prodávat zákazníkovi.

    **Poznámka**: Pokud jste pro zákazníka nastavili opakované prodejní řádky, například objednávku měsíčního doplňování, můžete tyto řádky vložit na nabídku vybráním akce **Získat periodické prodejní řádky**.
10. Na záložce **Řádky** v políčku **Číslo zboží** vložte množství položky nebo služby.
11. V políčku **Množství** zadejte množství zboží k prodeji.

    **Poznámka**: U položek typu Servis je množství v jednotce času, např. hodiny, jak je uvedeno v poli **Kód měrné jednotky**

    Pole **Částka na řádku** je aktualizována tak, aby zobrazovala hodnotu v poli **Jednotková cena** vynásobená hodnotou v poli **Množství**.

    Částka ceny a řádku se zobrazuje s nebo bez DPH v závislosti na tom, co jste vybrali v poli **Ceny včetně DPH** na kartě zákazníka.
12. Do pole **Částka řádkové slevy** zadejte procento, pokud chcete zákazníkovi poskytnout slevu na produkt. Hodnota v poli **Částka na řádku** je odpovídajícím způsobem aktualizována.

    **Poznámka**: Pokud nastavíte speciální ceny na záložce **Prodejní ceny a řádkové slevy** na kartě zákazníka nebo kartě položky, potom se cena na řádku automaticky aktualizuje, pokud jsou splněna daná kritéria. Další informace naleznete v tématu: [Zaznamenání prodejní ceny, slevy a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).
13. Chcete-li přidat komentář na řádek nabídky, který se zákazníkovi zobrazí na vytištěné prodejní nabídce, napište text do pole **Popis** na prázdném řádku.  
14. Opakujte kroky 10 až 13 pro každou položku, kterou chcete nabídnout zákazníkovi.

    Součty pod řádky se automaticky vypočítají při vytváření nebo úpravách řádků.
15. Do pole **Částka fakturační slevy** zadejte částku, která by měla být odečtena od hodnoty zobrazené v položce **Celkem včetně DPH**.

    **Poznámka**: Pokud jste zákazníkovi nastavili fakturační slevu, zadaná procentní hodnota se automaticky vloží do pole **Fakturační sleva %**, pokud jsou splněna kritéria a příslušná částka je vložena do **Faktury do pole Fakturační sleva včetně DPH**. Další informace naleznete v tématu: [Zaznamenání prodejní ceny, slevy a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).
16. Po dokončení řádků prodejní nabídky vyberte tlačítko **E-mail** nebo **Tisk**.

    Pokud jste zvolili tlačítko **E-mail**, potom PDF soubor bude automaticky připojen jako příloha e-mailu zákazníkovi. Tělo emailu může být předvyplněno souhrnem nabídky. Další informace naleznete v tématu: [Návod: Posílání dokumentů pomocí Emailu](ui-how-send-documents-email.md).
17. Pokud zákazník akceptuje nabídku, zvolte **Vytvořit fakturu** nebo **Vytvořit objednávku**.

Prodejní nabídka je smazána z databáze. Prodejní faktura nebo prodejní objednávka je vytvořena na základě informací z prodejní nabídky, ze které uskutečňujete prodej. V políčku **Nabídka číslo** na prodejní faktuře nebo prodejní objednávce můžete vidět číslo prodejní nabídky, ze které byly vytvořeny. Další informace naleznete v tématu: [Návod: Fakturování prodeje](sales-how-invoice-sales.md) nebo [Návod: Prodávání produktu](sales-how-sell-products.md).

## <a name="see-also"></a>Viz také  
[Správa prodeje](sales-manage-sales.md)  
[Nastavení prodeje](sales-setup-sales.md)  
[Návod: Posílání dokumentů pomocí Emailu](ui-how-send-documents-email.md)  
[Práce s [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md)

