---
title: "Vytvoření prodejní objednávku a prodávání produktu"
description: "Popisuje, jak vytvořit objednávku prodeje, abyste zaznamenali vaši dohodu se zákazníkem o prodeji produktů za určitých podmínek."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: trade
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 1371f7a1d1e5b5c9bd0add845d37e194db86218d
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-sell-products"></a>Návod: Prodávání produktu
Můžete vytvořit prodejní objednávku nebo prodejní fakturu k zaznamenání vaší dohody se zákazníkem o prodeji určitých produktů za určitých dodacích a platebních podmínek.

> [!NOTE]  
>   Musíte použít prodejní objednávky, pokud to váš prodejní proces vyžaduje, a můžete dodat pouze části objednávky, například pokud celé množství není k dispozici najednou. Pokud prodáváte zboží dodáním přímo od svého dodavatele zákazníkovi jako zásilku, musíte také použít prodejní objednávky. Další informace naleznete v [Návod: Vytvoření přímé dodávky](sales-how-drop-shipment.md). Ve všech ostatních ohledech fungují prodejní objednávky stejným způsobem jako prodejní faktury. Další informace naleznete v [Návod: Prodejní faktury](sales-how-invoice-sales.md).

Můžete vyjednávat se zákazníkem tím, že nejprve vytvoříte prodejní nabídku, kterou můžete při prodeji převést na prodejní objednávku, pokud souhlasíte s obchodem. Další informace naleznete v [Návod: Vytváření nabídek](sales-how-make-offers.md).

Poté, co zákazník potvrdí dohodu, například po nabídce cen, můžete odeslat potvrzení objednávky, abyste si zaznamenali povinnost dodat produkty podle dohody.

Když doručujete produkty, ať již plně nebo částečně, účtujete objednávku jako dodanou nebo jako dodanou a fakturovanou k vytvoření souvisejících položek a záznamů pro zákazníky v systému. Při účtování prodejní faktury můžete také dokument poslat jako přílohu ve formátu PDF. Tělo e-mailu můžete předvyplnit informacemi o objednávce a platbě, stejně jako odkaz na platbu PayPal. Další informace naleznete v [Návod: Posílání dokumentů pomocí Emailu](ui-how-send-documents-email.md).

V obchodních prostředích, kde musí zákazník platit před dodáním produktů, například v maloobchodě, musíte počkat na příjem platby před dodáním produktů. Ve většině případů zpracováváte příchozí platby několik týdnů po doručení, a to tak, že platby jsou uplatněny na související účtované prodejní nezaplacené faktury. Další informace naleznete v [Návod: Odsouhlasení plateb pomocí automatické aplikace](receivables-how-reconcile-payments-auto-application.md).

Skutečnou prodejní fakturu lze jednoduše opravit nebo zrušit před zaplacením. Toto je užitečné, pokud chcete opravit chybu při psaní nebo pokud zákazník požaduje změnu včas v procesu objednávky. Další informace naleznete v [Návod: Opravit  nebo zrušit nezaplacené prodejní faktury](sales-how-correct-cancel-sales-invoice.md). Pokud je účtovaná prodejní faktura, musíte si vytvořit dobropis ke zpětnému prodeji. Další informace naleznete v [Návod: Proces prodejní vratky nebo zrušení.](sales-how-process-sales-returns-cancellations.md)

Položky zákazníků můžete vyplnit na prodejní objednávce dvěma způsoby v závislosti na tom, zda je zákazník již zaregistrován. Viz kroky 2 a 3 v následujícím postupu.

## <a name="to-create-a-sales-order"></a>Vytvoření prodejní objednávky
1. Na domovské stránce vyberte tlačítko **Prodejní objednávka**.  
2. V políčku **Zákazník** napište jméno existujícího zákazníka.

    Ostatní pole v okně **Prodejní objednávka** jsou nyní vyplněny informacemi vybraného zákazníka. Pokud není zákazník registrován, následujte tyto kroky:
3. V políčku **Zákazník** napište jméno nového zákazníka.
4. V dialogovém okně o registraci nového zákazníka zvolte tlačítko **Ano**.
5. V okně **Vybrat šablonu pro nového zákazníka** vyberte šablonu, na které bude založena nová zákaznická karta, a potom klepněte na tlačítko **OK**.

    Otevře se nová zákaznická karta předvyplněná informacemi ze zvolené šablony zákazníků. Políčko **Název** je předvyplněno novým jménem zákazníka, kterého jste zadali v prodejní objednávce.
6. Pokračujte vyplněním zbývajících polí na kartě zákazníka. Další informace naleznete v [Návod: Registrace nového zákazníka](sales-how-register-new-customers.md).  
7. Po dokončení karty zákazníka zmáčkněte tlačítko **OK**, abyste se vrátili do okna **Prodejní objednávka**.

    Několik polí na prodejní objednávce je nyní vyplněno informacemi uvedenými na nové kartě zákazníka.
8. V případě potřeby vyplňte zbývající pole v okně **Prodejní objednávka**. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

    Nyní jste připraveni vyplnit řádky prodejní objednávky zbožím nebo službami, které chcete prodávat zákazníkovi.

    Pokud jste pro zákazníka nastavili opakované prodejní řádky, například objednávku měsíčního doplňování, můžete tyto řádky vložit na objednávku vybráním akce **Získat periodické prodejní řádky**.
9. Na záložce **Řádky** v políčku **Zboží**, vložte číslo skladové položky nebo služby.  
10. V políčku **Množství** vložte množství zboží k prodeji.

    Pole **Částka na řádku** je aktualizováno tak, aby zobrazovalo hodnotu v poli **Jednotková cena** vynásobenou hodnotou v poli **Množství**.

    Částka ceny a řádku se zobrazuje s nebo bez DPH v závislosti na tom, co jste vybrali v poli **Ceny včetně DPH** na kartě zákazníka.
11. Do pole **Částka řádkové slevy** zadejte procentuální slevu, pokud chcete zákazníkovi poskytnout slevu na produkt. Hodnota v poli **Částka na řádku** je odpovídajícím způsobem aktualizována.

    Pokud nastavíte speciální ceny na záložce **Prodejní ceny a řádkové slevy** na kartě zákazníka nebo kartě položky, potom se cena na řádku automaticky aktualizuje pokud jsou splněna daná kritéria. Další informace naleznete v tématu: [Zaznamenání prodejní ceny, slevy, a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).
12. Chcete-li přidat komentář na řádek nabídky, který se zákazníkovi zobrazí na vytištěné prodejní nabídce, napište text do pole **Popis** na prázdném řádku.  
13. Opakujte kroky 10 až 13 pro každou položku, kterou chcete nabídnout zákazníkovi.

    Součty pod řádky se automaticky vypočítají při vytváření nebo úpravách řádků.
6. Displej nová zákaznická karta předvyplněná informacemi ze zvolené šablony zákazníků. Vyplňte příslušná pole. Další informace naleznete v [Návod: Registrace nového zákazníka](sales-how-register-new-customers.md).  
7. Po dokončení karty zákazníka zmáčkněte tlačítko **OK**, abyste se vrátili do okna **Prodejní objednávka**.

   Několik polí na prodejní objednávce je nyní vyplněno informacemi uvedenými na nové kartě zákazníka.  
8. V případě potřeby vyplňte zbývající pole v okně **Prodejní objednávka**. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

   Nyní jste připraveni vyplnit řádky prodejní objednávky pro produkty, které prodáváte zákazníkovi, nebo pro jakoukoli transakci se zákazníkem, kterou chcete zaznamenat do hlavní knihy.   

   Pokud jste pro zákazníka nastavili opakované prodejní řádky, například objednávku měsíčního doplňování, můžete tyto řádky vložit na objednávku vybráním akce **Získat periodické prodejní řádky**.  
9. Na záložce s náhledem **Řádky** v poli **Typ** vyberte, jaký typ produktu, účtování nebo transakci, kterou zaúčtujete zákazníkovi s prodejní linkou.
10. Do pole **Číslo** vyberte záznam, který chcete odesílat podle hodnoty v poli **Typ**.

    Pole **Číslo** necháte prázdné v následujících případech: -Pokud je řádek pro komentář: Napište komentář do pole **Popis**.
    -Pokud je řádek pro neskladové zboží. Zvolte akci **Vybrat neskladové zboží**. Další informace naleznete v [Návod: Práce s neskladovaným zbožím](inventory-how-work-nonstock-items.md).

11. Do pole **Množství** zadejte počet jednotek produktu, účtování nebo transakci, který řádek se zaznamená pro zákazníka.  

    > [!NOTE]  
>   U položek typu **položka - Služba** je množství časovou jednotkou, např. hodiny, jak je uvedeno na řádku v poli **Kód měrné jednotky**.  

    Hodnota v poli **Částka řádku** se vypočítá jako *Jednotková cena* x *Množství*.  

    Částka ceny a řádku jsou s nebo bez DPH v závislosti na tom, co jste vybrali v poli **Ceny včetně DPH** na kartě zákazníka.  
12. Pokud chcete poskytnout slevu, zadejte procento do pole **Sleva na řádek %**. Hodnota v poli **Částka na řádku** se odpovídajícím způsobem aktualizována.  

    Pokud nastavíte speciální ceny na záložce **Prodejní ceny a řádkové slevy** na kartě zákazníka nebo kartě položky, potom se cena na řádku automaticky aktualizuje pokud jsou splněna daná kritéria. Další informace naleznete v tématu: [Zaznamenání prodejní ceny, slevy, a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).  
13. Opakujte kroky 9 až 12 pro každou položku, kterou chcete nabídnout zákazníkovi.  

    Součty pod řádky se automaticky vypočítají při vytváření nebo úpravách řádků.  
14. Do pole **Částka fakturační slevy** zadejte částku, která by měla být odečtena od hodnoty zobrazené v položce **Celkem včetně DPH**.

    Pokud jste zákazníkovi nastavili fakturační slevu, zadaná procentní hodnota se automaticky vloží do pole **Fakturační sleva %**, pokud jsou splněna kritéria a příslušná částka je vložena do pole **Fakturační sleva bez DPH**. Pro více informací jděte na: [Zaznamenání prodejní ceny, slevy, a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).
15. Chcete-li odeslat pouze část objednávky, zadejte množství do pole **Množství k odeslání**. Hodnota se zkopíruje do pole **K fakturaci**.
16. Chcete-li fakturovat pouze část objednávky, zadejte množství do pole **K fakturaci**. Množství musí být nižší než hodnota v poli **K fakturaci**.   
17. Po dokončení řádků prodejních objednávek vyberte akci **Účtovat a odeslat**.

Dialogové okno **Potvrzení zaúčtování a odeslání** zobrazuje preferovaný způsob přijímání dokumentů od zákazníka. Způsob odesílání můžete změnit výběrem vyhledávacího tlačítka pro pole **Odeslat dokument do**. Další informace naleznete v [Návod: Nastavení profilů odesílaného dokladu](sales-how-setup-document-send-profiles.md).

Položky souvisejících položek a účtů zákazníků jsou nyní vytvořeny ve vašem systému a prodejní objednávka je vyexportována jako dokument PDF. Když je prodejní objednávka plně vyúčtována, je odstraněna ze seznamu prodejních objednávek a nahrazena novým dokumentem v seznamu zaúčtovaných prodejních faktur a seznamu odeslaných zásilek.

## <a name="see-also"></a>Viz také
[Prodej](sales-manage-sales.md)  
[Nastavení prodeje](sales-setup-sales.md)  
[Sklady](inventory-manage-inventory.md)  
[Návody Odesílání dokladů e-mailem](ui-how-send-documents-email.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

