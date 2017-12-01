---
title: "Nastavení obsahu určitého dokladu a příloh pro e-mailové zprávy"
description: "Můžete definovat obsah, který chcete vložit do těla e-mailové zprávy, například odkaz PayPal. Dokumenty můžete také připojit k e-mailovým zprávám."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: SMTP, mail, Office 365, cover, body, PayPal, layout
ms.date: 03/30/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 06c8eeb49cc02533314192cb089dc8786c226095
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-send-documents-by-email"></a>Návod: Odesílání dokladů e-mailem
Chcete-li rychle informovat své obchodní partnery o obsahu obchodních dokumentů, například pokud chcete svým zákazníkům sdělit platební informace na prodejních dokladech, můžete pomocí funkce Rozvržení sestavy definovat obsah specifický pro doklad, který se do těl emailů bude automaticky vkládat. Pro další informace jděte na [Správa rozložení sestav a dokladů](ui-manage-report-layouts.md).

Chcete-li povolit zasílání e-mailů z [!INCLUDE[d365fin](includes/d365fin_md.md)], spusťte **Nastavení e-mailů** k asistovanému nastavení na Domovské stránce.

Jako přílohu k emailovým zprávám můžete zaslat prakticky všechny typy dokumentů, a to přímo z okna, ve kterém je dokument zobrazen. Kromě přílohy můžete nastavit těla emailů pro konkrétní doklady se základními informacemi z dokladu, kterým předchází standardní text, který pozdraví příjemce pošty a představí daný doklad. Chcete-li svým zákazníkům nabídnout platbu za prodej prostřednictvím elektronické platební služby, jako například prostřednictvím PayPal, můžete mít do těla emailu vložené i informace o PayPal a hypertextový odkaz.

Ve všech podporovaných dokumentech iniciujete zasílání e-mailů pro zaúčtované doklady výběrem akce **Odeslat** a pro nezaúčtované výběrem akce **Účtovat a Odeslat**.

Je-li pole **E-mail** v okně **Komu odeslat doklad** nastaveno na ** Ano (příkaz pro nastavení)**, pak se okno **Odeslat e-mail** otevře s již vyplněnou kontaktní osobou v poli **Komu:** a dokladem přiloženým jako soubor PDF. V poli **Tělo zprávy** můžete buď zadat text ručně, nebo můžete mít pole vyplněné specifickým tělem e-mailu, které jste nastavili.

Následující postup popisuje, jak nastavit sestavu **Prodej - faktura**, která má být použita pro specifická těla emailů, když zasíláte zaúčtované prodejní faktury emailem.

## <a name="to-set-up-a-document-specific-email-body-for-sales-invoices"></a>Nastavení specifického těla e-mailu pro prodejní faktury
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Výběry sestav – prodej** a pak vyberte související odkaz.
2. V okně **Výběry sestav – prodej** vyberte v poli **Použití** možnost **Faktura**.
3. Na novém řádku vyberte v poli **ID sestavy** například standardní sestavu 1306.
4. Zaškrtněte políčko **Použít pro tělo E-mailu**.
5. Zvolte pole **Kód rozložení těla e-mailu** a v rozevíracím seznamu vyberte rozložení.

    Rozložení sestavy definuje jak styl, tak obsah těla e-mailu, včetně standardního textu, který předchází základním informacím o  dokladu v těle e-mailu. Pokud vyberete v rozevíracím seznamu tlačítko **Vybrat z úplného seznamu**, zobrazí se všechny dostupné rozvržení sestav.
6. Chcete-li zobrazit nebo upravit rozložení, na kterém je tělo e-mailu založeno, v okně **Rozložení vlastní sestavy** A zvolte akci **Upravit rozložení**.
7. Chcete-li nabídnout zákazníkům elektronické platby za prodej, můžete nastavit příslušnou platební službu, jako je například PayPal, a pak mít do těla emailu vložené i údaje o PayPal a hypertextový odkaz. Další informace naleznete v [Návod: Povolení plateb prostřednictvím služby PayPal zákazníkům](sales-how-enable-payment-service-extensions.md).
8. Zvolte tlačítko **OK**.

Nyní, když zvolíte například akci Odeslat v okně **Účtované prodejní faktury**, bude tělo e-mailu obsahovat informace o dokladu sestavy 1306, kterému předchází stylizovaný standardní text podle rozložení sestavy, které jste vybrali v pátém kroku.

Následující postup popisuje odeslání zaúčtované prodejní faktury jako e-mailové zprávy s dokladem připojeným jako soubor PDF a tělem e-mailu specifickým pro doklad.

## <a name="to-send-documents-by-email"></a>Odeslání dokladů e-mailem
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zaúčtované prodejní faktury** a pak vyberte související odkaz.
2. Vyberte příslušnou zaúčtovanou prodejní fakturu a vyberte akci **Odeslat**. Otevře se okno **Odeslat doklad**.
3. V poli **E-mail** vyberte možnost **Ano (příkaz pro nastavení)**. Další informace naleznete v [Návod: Nastavení profilů odesílaného dokladu](sales-how-setup-document-send-profiles.md).
4. Zvolte tlačítko **OK**. Otevře se okno **Odeslat e-mail**.
5. Do pole **Komu:** zadejte prosím platnou e-mailovou adresu. Výchozí hodnotou je e-mailová adresa zákazníka.
6. Do pole **Předmět** zadejte popisný text o emailu. Výchozí nastavení je jméno zákazníka a číslo faktury.
7. V poli **Příloha** je vygenerovaná faktura, ve výchozím nastavení je připojena jako soubor PDF. Pokud chcete otevřít soubor nebo přidat další, pak zvolte tlačítko vyhledávání.
8. Do pole  **Tělo zprávy** napište krátkou zprávu příjemci.

    Je-li v okně **Výběr zpráv - prodej** nastaveno tělo e-mailu pro specifický doklad, pak se pole **Tělo zprávy** automaticky vyplní. Další informace o tomto tématu naleznete v sekci "Nastavení těla e-mailu pro specifický doklad pro prodejní faktury".
9. Zvolte tlačítko **OK** k odeslání e-mailové zprávy.

> [!NOTE]  
>   Pokud nechcete zadávat nastavení e-mailu vždy, když odesíláte doklad e-mailem, můžete v okně **Odeslat dokument** v poli **E-mail** vybrat možnost **Ano (Použít výchozí nastavení)**. V takovém případě se okno **Odeslat e-mail** neotevře. Viz krok 4. Další informace naleznete v [Návod: Nastavení profilů odesílaného dokladu](sales-how-setup-document-send-profiles.md).

## <a name="see-also"></a>Viz také
[Správa rozložení sestav a dokladů](ui-manage-report-layouts.md)  
[Návod: Nastavení e-mailu](madeira-how-setup-email.md)  
[Návod: Prodejní faktury](sales-how-invoice-sales.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

