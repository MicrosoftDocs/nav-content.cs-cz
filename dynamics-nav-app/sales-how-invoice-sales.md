---
title: "Vytvoření prodejní faktury nebo prodejní objednávky"
description: "Popisuje, jak vytvořit prodejní doklad nebo prodejní fakturu nebo objednávku prodeje, abyste zaznamenali vaši dohodu se zákazníkem o prodeji produktů za určitých podmínek."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bill, sale, invoice, order
ms.date: 10/11/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7da07d1491fde4e555ea259f61babc02664094a8
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-invoice-sales"></a>Návod: Prodejní faktury
Můžete vytvořit prodejní faktury nebo prodejní objednávky, abyste zaznamenali vaši smlouvu se zákazníkem o prodeji určitých produktů za určitých dodacích a platebních podmínek.  

Existuje několik scénářů, kde musíte místo prodejní faktury použít prodejní příkaz:  

* Pokud potřebujete odeslat pouze část objednávkového množství, protože celé množství není po ruce.  
* Pokud prodáváte zboží, které dodává váš prodejce přímo zákazníkovi, známý jako zásilka pro zásilku. Další informace naleznete v [Návod: Vytvoření přímé dodávky](sales-how-drop-shipment.md).  

Ve všech ostatních ohledech fungují obchodní příkazy a prodejní faktury stejným způsobem. Další informace naleznete v [Návod: Prodávání produktů](sales-how-sell-products.md).

Můžete vyjednávat se zákazníkem tím, že nejprve vytvoříte prodejní nabídku, kterou můžete při prodeji převést na prodejní fakturu, pokud s obchodem souhlasíte. Další informace naleznete v [Návod: Vytváření nabídek](sales-how-make-offers.md).

Pokud se zákazník rozhodne koupit, zaúčtujete prodejní fakturu a vytvoříte související položky o množství a hodnotě. Při vystavení faktury za prodej můžete také dokument poslat jako přílohu ve formátu PDF. Tělo e-mailu můžete vyplnit předběžně souhrnem faktury a platebních informací, jako je odkaz na PayPal. Další informace naleznete v [Návod: Posílání dokumentů pomocí Emailu](ui-how-send-documents-email.md).

V obchodních prostředích, kde musí zákazník platit před dodáním produktů, například v maloobchodě, musíte počkat na příjem platby před dodáním produktů. Ve většině případů zpracováváte příchozí platby několik týdnů po doručení, a to tak, že platby jsou uplatněny na související účtované prodejní nezaplacené faktury. Další informace naleznete v [Návod: Odsouhlasení plateb pomocí automatické aplikace](receivables-how-reconcile-payments-auto-application.md).

Skutečnou prodejní fakturu lze jednoduše opravit nebo zrušit před zaplacením. Toto je například užitečné, pokud chcete opravit chybu při psaní nebo pokud zákazník požaduje změnu včas v procesu objednávky. Další informace naleznete v [Návod: Opravit  nebo zrušit nezaplacené prodejní faktury](sales-how-correct-cancel-sales-invoice.md). Pokud je účtovaná prodejní faktura, musíte si vytvořit dobropis ke zpětnému prodeji. Další informace naleznete v [Návod: Proces prodejní vratky nebo zrušení.](sales-how-process-sales-returns-cancellations.md)

Položky zákazníků můžete vyplnit na prodejní faktuře dvěma způsoby v závislosti na tom, zda je zákazník již zaregistrován. Viz kroky 2 a 3 v následujícím postupu.

## <a name="to-create-a-sales-invoice"></a>Vytvoření prodejní faktury
1. Na domovské stránce vyberte tlačítko **Prodejní faktury**.  
2. V políčku **Zákazník** napište jméno existujícího zákazníka.

   Ostatní pole v okně **Prodejní faktury** obsahují informace vybraného zákazníka. Pokud není zákazník registrován, následujte tyto kroky:
3. V políčku **Zákazník** napište jméno nového zákazníka.
4. V dialogovém okně o registraci nového zákazníka zvolte tlačítko **Ano**.
5. V okně **Vybrat šablonu pro nového zákazníka** vyberte šablonu, na které bude založena nová zákaznická karta, a potom klepněte na tlačítko **OK**.
6. Displej nová zákaznická karta předvyplněná informacemi ze zvolené šablony zákazníků. Vyplňte zbývající pole. Další informace naleznete v [Návod: Registrace nového zákazníka](sales-how-register-new-customers.md).  
7. Po dokončení karty zákazníka zmáčkněte tlačítko **OK**, abyste se vrátili do okna **Prodejní faktury**.

   Několik polí na prodejní faktuře je nyní vyplněno informacemi uvedenými na nové kartě zákazníka.  
8. V případě potřeby vyplňte zbývající pole v okně **Prodejní faktury**. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

Nyní jste připraveni vyplnit řádky prodejních faktur pro produkty, které prodáváte zákazníkovi, nebo pro jakoukoli transakci se zákazníkem, kterou chcete zaznamenat na účet hlavní knihy.   

Pokud jste pro zákazníka nastavili opakované prodejní řádky, například objednávku měsíčního doplňování, můžete tyto řádky vložit na objednávku vybráním akce **Získat periodické prodejní řádky**.  
9. Na záložka s náhledem **Řádky** v poli **Typ** vyberte, jaký typ produktu, účtování nebo transakci, kterou zaúčtujete zákazníkovi s prodejním řádkem.
10. Do pole **Číslo** vyberte záznam, který chcete odesílat podle hodnoty v poli **Typ**.

 Necháte pole **Číslo** Prázdné v následujících případech: -Pokud je řádek pro komentář. Napište komentář do pole **Popis**.
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
15. Po dokončení řádků prodejních faktur vyberte akci **Účtovat a odeslat**.  

Dialogové okno **Potvrzení zaúčtování a odeslání** zobrazuje preferovaný způsob přijímání dokumentů od zákazníka. Způsob odesílání můžete změnit výběrem vyhledávacího tlačítka pro pole **Odeslat dokument do**. Další informace naleznete v [Návod: Nastavení profilů odesílaného dokladu](sales-how-setup-document-send-profiles.md).

Položky souvisejících položek a účtů zákazníků jsou nyní vytvořeny ve vašem systému a prodejní faktura je vyexportována jako dokument PDF. Prodejní faktura je odstraněna ze seznamu prodejních faktur a nahrazena novým dokumentem v seznamu prodejních faktur.

## <a name="see-also"></a>Viz také
[Prodej](sales-manage-sales.md)  
[Nastavení prodeje](sales-setup-sales.md)  
[Sklady](inventory-manage-inventory.md)  
[Návody Odesílání dokladů e-mailem](ui-how-send-documents-email.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

