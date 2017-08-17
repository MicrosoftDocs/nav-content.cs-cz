---
title: "Návody Prodejní produkty"
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: e45d67005364f7d45817d917ccaeab219b6f8446
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-sell-products"></a>Návody Prodejní produkty
Můžete vytvořit prodejní objednávku nebo prodejní fakturu, k zaznamenání vaší smlouvy se zákazníkem o prodeji určitých produktů za určitých dodacích a platebních podmínek.

**Poznámka**: Musíte použít prodejní objednávky pokud to váš prodejní proces vyžaduje a můžete dodat pouze části objednávky např.: Pokud celé množství není k dispozici najednou. Pokud prodáváte zboží dodáním přímo od svého dodavatele zákazníkovi jako zásilku, musíte také použít prodejní objednávky Další informace naleznete v tématu [Jak na: Vytvořit přímou dodávku](sales-how-drop-shipment.md). Ve všech ostatních ohledech fungují prodejní objednávky stejným způsobem jako prodejní faktury. Další informace naleznete v tématu [Jak na: Prodejní faktury](sales-how-invoice-sales.md).

Můžete vyjednávat se zákazníkem tím, že nejprve vytvoříte prodejní nabídku, kterou můžete při prodeji převést na prodejní objednávku, pokud souhlasíte s obchodem. Další informace naleznete v tématu [Jak na: Vytvoření nabídek](sales-how-make-offers.md).

Poté, co zákazník potvrdí smlouvu, například po nabídce cen, můžete odeslat potvrzení objednávky, abyste si zaznamenali povinnost dodat produkty podle dohody.

Když doručujete produkty, ať již plně nebo částečně, účtujete objednávku jako dodanou nebo jako dodanou a fakturovanou k vytvoření souvisejících položek a záznamů pro zákazníky v systému. Při účtování prodejní faktury můžete také dokument poslat jako přílohu ve formátu PDF. Tělo e-mailu můžete předvyplnit informacemi o objednávce a platbě, stejně jako odkaz na platbu PayPal. Další informace naleznete v tématu [Jak na: Posílání dokumentů pomocí Emailu](ui-how-send-documents-email.md).

V obchodních prostředích, kde musí zákazník platit před dodáním produktů, například v maloobchodě, musíte počkat na příjem platby před dodáním produktů. Ve většině případů zpracováváte příchozí platby několik týdnů po doručení, a to tak, že platby jsou uplatněny na související účtované, prodejní nezaplacené faktury. Další informace naleznete v tématu [Jak na: Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).

Pokud je účtovaná prodejní faktura, musíte si vytvořit dobropis ke zpětnému prodeji. Další informace naleznete v tématu [Jak na: Proces Prodejní vratky nebo Zrušení](sales-how-process-sales-returns-cancellations.md).

Produkt mohou být inventární položky nebo služby Další informace naleznete v tématu [Jak na: Registrovat nové zboží](inventory-how-register-new-products.md). Proces prodejních objednávek je stejný pro oba typy produktů.

**Poznámka**: V produktu Dynamics NAV se produkt označuje výrazem "zboží".

Položky zákazníků můžete vyplnit na prodejní objednávce dvěma způsoby, v závislosti na tom, zda je zákazník již zaregistrován.

## <a name="to-create-a-sales-order"></a>Vytvoření prodejní objednávky.
1. Na domovské stránce vyberte tlačítko **Prodejní objednávka**.  
2. V políčku **Zákazník** napište jméno existujícího zákazníka.

    Ostatní pole v okně **Prodejní objednávka** jsou nyní vyplněny informacemi vybraného zákazníka. Pokud není zákazník registrován, následujte tyto kroky:

3. V políčku **Zákazník** napište jméno nového zákazníka.
4. V dialogovém okně o registraci nového zákazníka zvolte tlačítko **Ano**  
5. V okně **Vybrat šablonu pro nového zákazníka** vyberte šablonu, na které bude založena nová zákaznická karta, a potom klepněte na tlačítko **OK**.

    Otevře se nová zákaznická karta s předplněná informacemi ze zvolené šablony zákazníků. Políčko **Jméno** je předvyplněno novým jménem zákazníka, kterého jste zadali v prodejní objednávce.
6. Pokračujte vyplněním zbývajících polí na kartě zákazníka. Další informace naleznete v tématu [Jak na: Zaregistrovat nového zákazníka.](sales-how-register-new-customers.md)  
7. Po dokončení karty zákazníka zmáčkněte tlačítko **OK**, abyste se vrátili do okna **Prodejní objednávka**.

    Několik polí na prodejní objednávce je nyní vyplněno informacemi uvedenými na nové kartě zákazníka.
8. V případě potřeby vyplňte zbývající pole v okně **Prodejní objednávka**. Vyberte pole a přečtěte si krátký popis pole nebo zvolte odkaz pro další informace.

    Nyní jste připraveni vyplnit řádky prodejní objednávky zbožím nebo službami, které chcete prodávat zákazníkovi.

    Pokud jste pro zákazníka nastavili opakované prodejní řádky, například objednávku měsíčního doplňování, můžete tyto řádky vložit na objednávku vybráním akce **Získat periodické prodejní řádky**.
9. Na záložce **Řádky** v políčku **Zboží**, vložte číslo skladové položky nebo služby.  
10. V políčku **Množství** vložte množství zboží k prodeji.

    **Poznámka**: U položek typu Servis je množství v jednotce času, např. hodiny, jak je uvedeno v poli **Kód měrné jednotky**

    Pole **Částka na řádku** je aktualizována tak, aby zobrazovala hodnotu v poli **Jednotková cena** vynásobená hodnotou v poli **Množství**.

    Částka ceny a řádku se zobrazuje s nebo bez DPH v závislosti na tom, co jste vybrali v poli **Ceny včetně DPH** na kartě zákazníka.
11. Do pole **Částka řádkové slevy** zadejte procento, pokud chcete zákazníkovi poskytnout slevu na produkt. Hodnota v poli **Částka na řádku** je odpovídajícím způsobem aktualizována.

    Pokud nastavíte speciální ceny na záložce **Prodejní ceny a řádkové slevy** na kartě zákazníka nebo kartě položky, potom se cena na řádku automaticky aktualizuje pokud jsou splněna daná kritéria. Pro více informací bežte na: [Zaznamenání prodejní ceny, Sleva, a Platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).
12. Chcete-li přidat komentář na řádek nabídky, který se zákazníkovi zobrazí na vytištěné prodejní nabídce, napište text do pole **Popis** na prázdném řádku.  
13. Opakujte kroky 10 až 13 pro každou položku, který chcete nabídnout zákazníkovi.

    Součty pod řádky se automaticky vypočítají při vytváření nebo úpravách řádků.
14. Do pole **Částka fakturační slevy** zadejte částku, která by měla být odečtena od hodnoty zobrazené v položce **Celkem včetně DPH**

    Pokud jste zákazníkovi nastavili fakturační slevu, zadaná procentní hodnota se automaticky vloží do pole **Fakturační sleva%**, pokud jsou splněna kritéria a příslušná částka je vložena do **Faktura Fakturační sleva včetně DPH** pole. Pro více informací jděte na: [Zaznamenání prodejní ceny, Sleva, a Platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).
15. Chcete-li odeslat pouze část objednávky, zadejte množství do pole **Množství k odeslání** Hodnota se zkopíruje do pole **K fakturaci**
16. Chcete-li fakturova pouze část objednávky, zadejte množství do pole **K fakturaci** Množství musí být nižší než hodnota v poli **K fakturaci**   
17. Po dokončení řádků prodejních objednávke,  vyberte akci **Účtovat a odeslat**.
Zobrazí se dialogové okno **Potvrzení účtování a odeslání** s uvedením preferovaného způsobu odeslání pro zákazníka.

Způsob odesílání můžete změnit výběrem vyhledávacího tlačítka pro pole **Odeslat dokument do**. Další informace naleznete v tématu [Jak na: Nastavení Profilů odesílání dokumentů](sales-how-setup-document-send-profiles.md).

Položky souvisejících položek a účtů zákazníků jsou nyní vytvořeny ve vašem systému a prodejní objednávka je vyexportována jako dokument PDF. Když je prodejní objednávka plně vyúčtována, je odstraněna ze seznamu prodejních objednávek a nahrazena novým dokumentem v seznamu zaúčtovaných prodejních faktur a seznamu odeslaných zásilek.

## <a name="see-also"></a>Viz také  
[Správa prodeje](sales-manage-sales.md)  
[Nastavení prodeje](sales-setup-sales.md)  
[Sklady](inventory-manage-inventory.md)  
[Návody Posílání dokumentů pomocí Emailu.](ui-how-send-documents-email.md)  
[Práce s Dynamics NAV](ui-work-product.md)

