---
title: "Návod: Odesílání dokumentů e-mailem"
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
ms.openlocfilehash: 443519de31bf315dd30e6961f4c1a03c13525250
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-send-documents-by-email"></a>Návod: Odesílání dokumentů e-mailem
Chcete-li rychle informovat své obchodní partnery o obsahu obchodních dokumentů, například pokud chcete svým zákazníkům sdělit platební informace na prodejních dokladech, můžete pomocí funkce Rozvržení sestavy definovat obsah specifický pro doklad, který se do těl emailů bude automaticky vkládat.

Chcete-li povolit zasílání e-mailů ze služby Dynamics NAV, spusťte **Nastavení e-mailů** k asistovanému nastavení na Domovské stránce. 

Jako přílohu k emailovým zprávám můžete zaslat prakticky všechny typy dokumentů, a to přímo z okna, ve kterém je dokument zobrazen. Kromě přílohy můžete nastavit těla emailů pro konkrétní doklady se základními informacemi z dokladu, kterým předchází standardní text, který pozdraví příjemce pošty a představí daný doklad. Chcete-li svým zákazníkům nabídnout platbu za prodej prostřednictvím elektronické platební služby, jako například prostřednictvím PayPal, můžete mít do těla emailu vložené i informace o PayPal a hypertextový odkaz.

Ve všech podporovaných dokumentech iniciujete zasílání e-mailů pro zaúčtované doklady výběrem akce **Odeslat** a pro nezaúčtované výběrem akce **Účtovat a Odeslat**.

Je-li pole **E-mail** v okně **Komu odeslat doklad** nastaveno na ** Ano (příkaz pro nastavení)**, pak se okno **Odeslat e-mail** otevře s již vyplněnou kontaktní osobou v poli **Komu:** a dokladem přiloženým jako soubor PDF.  V poli **Tělo zprávy** můžete buď zadat text ručně, nebo můžete mít pole vyplněné specifickým tělem e-mailu, které jste nastavili.

Následující postup popisuje, jak nastavit sestavu **Prodej - faktura**, která má být použita pro specifická těla emailů, když zasíláte zaúčtované prodejní faktury emailem.

## <a name="to-set-up-a-document-specific-email-body-for-sales-invoices"></a>Nastavení specifického těla e-mailu pro prodejní faktury
1. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, vložte **Výběry sestav – prodej**, a poté vyberte související odkaz. 
2. V okně **Výběry sestav – prodej** vyberte v poli **Použití** možnost **Faktura**.
3. Na novém řádku vyberte v poli **ID sestavy** například standardní sestavu 1306.
4. Zaškrtněte políčko **Použít pro předmět pošty**.
5. Zvolte pole **ID rozložení těla e-mailu** a poté z okna **Rozložení vlastní sestavy**  vyberte jedno z dostupných rozložení.
6. Rozložení sestavy definuje jak styl, tak obsah těla e-mailu, včetně standardního textu, který předchází základním informacím o  dokladu v těle e-mailu.
7. Chcete-li zobrazit nebo upravit rozložení, na kterém je tělo e-mailu založeno, v okně **Rozložení vlastní sestavy** zvolte akci **Upravit rozložení**.
8. Chcete-li nabídnout zákazníkům elektronické platby za prodej, můžete nastavit příslušnou platební službu, jako je například PayPal, a pak mít do těla emailu vložené i údaje o PayPal a hypertextový odkaz. Další informace naleznete v tématu: [Návod: Povolení plateb prostřednictvím služby PayPal zákazníkům](sales-how-enable-customer-payments-paypal.md).
9. Zvolte tlačítko **OK**.

Nyní, když zvolíte například akci Odeslat v okně **Účtované prodejní faktury**, bude tělo e-mailu obsahovat informace o dokladu sestavy 1306, kterému předchází stylizovaný standardní text podle rozložení sestavy, které jste vybrali v pátém kroku.

Následující postup popisuje odeslání zaúčtované prodejní faktury jako e-mailové zprávy s dokladem připojeným jako soubor PDF a tělem e-mailu specifickým pro doklad.
## <a name="to-send-documents-by-email"></a>Odeslání dokladů e-mailem
1. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Účtované prodejní faktury**, a pak vyberte související odkaz.
2. Vyberte příslušnou prodejní fakturu a vyberte akci **Odeslat**. Otevře se okno **Odeslat doklad**.
3. V poli **E-mail** vyberte možnost **Ano (příkaz pro nastavení)**. Další informace naleznete v tématu: [Návod: Nastavení profilů odesílaného dokladu](sales-how-setup-document-send-profiles.md).
4. Zvolte tlačítko **OK**. Otevře se okno **Odeslat e-mail**.
5. Do pole **Komu:** zadejte prosím platnou e-mailovou adresu. Výchozí hodnotou je e-mailová adresa zákazníka.
6. Do pole **Kopie:** zadejte e-mailovou adresu, aby byla kopie emailové zprávy odeslána jinému příjemci. 
7. Do pole **Skrytá kopie:** zadejte e-mailovou adresu, aby byla kopie e-mailu odeslána jinému příjemci, aniž by se tato e-mailová adresa a jméno zobrazovaly ostatním příjemcům.
8. Do pole **Předmět** zadejte popisný text o emailu. Výchozí nastavení je jméno zákazníka a číslo faktury.
9. V poli **Příloha** je vygenerovaná faktura, ve výchozím nastavení je připojena jako soubor PDF. Pokud chcete otevřít soubor nebo přidat další, pak zvolte tlačítko vyhledávání.
10. Do pole  **Tělo zprávy** napište krátkou zprávu příjemci.

    Je-li v okně **Výběr zpráv - prodej** nastaveno tělo e-mailu pro specifický doklad, pak se pole **Tělo zprávy** automaticky vyplní. Další informace o tomto tématu naleznete v sekci "Nastavení těla e-mailu pro specifický doklad pro prodejní faktury".
11. Zaškrtněte políčko **Upravit ve webové aplikaci Outlook** k otevření e-mailové zprávy v e-mailové aplikaci Office 365.
12. Zvolte tlačítko **OK** k odeslání e-mailové zprávy.

**Poznámka**: Pokud nepotřebujete zadávat nastavení e-mailu vždy, když odesíláte doklad e-mailem, můžete v okně **Odeslat dokument** v poli emailu vybrat možnost **Ano (Použít výchozí nastavení)**. V takovém případě se okno **Odeslat e-mail** neotevře. Viz krok 4. Další informace naleznete v tématu: [Návod: Nastavení profilů odesílání dokladů](sales-how-setup-document-send-profiles.md) .

## <a name="see-also"></a>Viz také  
[Práce s Dynamics NAV](ui-work-product.md)  
[Návod: Prodejní faktury.](sales-how-invoice-sales.md)

