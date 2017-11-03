---
title: "Instalace rozšíření k úpravě Dynamics NAV"
description: "Naučte se o přidávání funkcí a přizpůsobení Dynamics NAV instalací rozšíření."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: app, add-in, manifest, customize
ms.date: 07/07/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: eebf2005d6317e4e2bf328b5a4b13584e3c96c5f
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="customizing-dynamics-nav-using-extensions"></a>Přizpůsobení Dynamics NAV pomocí Rozšíření
můžete změnit [!INCLUDE[d365fin](includes/d365fin_md.md)] instalací rozšíření, které přidávají funkce, mění chování nebo například umožňují přístup k novým online službám.
Při prvním spuštění služby [!INCLUDE[d365fin](includes/d365fin_md.md)] jsou pro vás některá rozšíření již nainstalována. Postupem času mohou být k dispozici další rozšíření a poté můžete zvolit, zda chcete rozšíření použít, nebo ne.

Například společnost Microsoft poskytuje rozšíření, které umožňuje integraci s platebním standardem PayPal. Toto rozšíření je standardně nainstalováno.
Pokud je dispozici další rozšíření, které nabízí integraci s jinou platební službou, můžete nainstalovat nové rozšíření a vybrat, kterou z těchto dvou služeb použijete.  

Spravujete rozšíření v okně **Správa rozšíření**. K tomuto oknu můžete přistupovat z domovské stránky. Alternativně zvolte ikonu **Vyhledat stránku nebo sestavu**(media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Rozšíření** a vyberte související odkaz.  

> [!NOTE]  
>   Pokud si myslíte, že máte mít práva k rozšíření, ale nemůžete najít jeho funkcionalitu, zkontrolujte **Správu rozšíření** - Pokud zde nebude rozšíření, můžete si ho nainstalovat, tak jak je to popsáno v následující sekci.  

## <a name="installing-an-extension"></a>Instalace rozšíření
Nové rozšíření si můžete nainstalovat z marketplace v [AppSource.Microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1) Zde uvidíte všechny dostupné rozšíření pro [!INCLUDE[d365fin](includes/d365fin_md.md)] a získáte aplikace, rozšíření a obsahové balíčky pro ostatní produkty do Microsoftu. Nastavte relevantní filtry a podívejte se na informace o každém rozšíření, případně získejte rozšíření pro váš [!INCLUDE[d365fin](includes/d365fin_md.md)].  
> [!NOTE]  
>   Přihlašte se do [AppSource.microsoft.com](https://appsource.microsoft.com/) použitím emailového účtu do vašeho [!INCLUDE[d365fin](includes/d365fin_md.md)]. Používejte stejný emailový účet pro ostatní služby a produkty pro lepší zkušenost.  

Do marketplace se můžete dostat ze vnitř aplikace [!INCLUDE[d365fin](includes/d365fin_md.md)]. V okně **Správa rozšíření** můžete vidět rozšíření, která jsou momentálně nainstalovaná a odtud můžete otevřít stránku **Extension Marketplace**, která zobrazí rozšíření dostupná v AppSource pro [!INCLUDE[d365fin](includes/d365fin_md.md)]. Pokud zvolíte odkaz *Více aplikací*, budete přesměrování do [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1).  

Pokud vyberete rozšíření, můžete si přečíst co rozšíření dělá, dále získat přístup k nápovědě pro rozšíření, kde se dozvíte více. Pokud se rozhodnete pro rozšíření, musíte souhlasit s podmínkami používání. Pokud získáte rozšíření z webu AppSource, budete přihlášení do [!INCLUDE[d365fin](includes/d365fin_md.md)] pro dokončení instalace.  

Při instalaci rozšíření budete možná muset zadat nastavení, například zadat účet pro použití s **Rozšíření Platební Standard PayPal pro [!INCLUDE[d365fin](includes/d365fin_md.md)] **.
Ostatní rozšíření jednoduše přidávají pole na existující stránku nebo přidávají například novou stránku.   

Pokud se rozhodnete odinstalovat rozšíření a poté se rozhodnete, že ho opět chcete, stačí ho znovu nainstalovat. Když odinstalujete rozšíření, které jste použili, data jsou zachována, takže pokud znovu nainstalujete rozšíření, jsou vaše data stále k dispozici.  

Některé rozšíření jsou pokytnuty Microsoftem a některé jsou od [Ostatních Společností](ui-extensions-other.md). Všechna rozšíření jsou testovaná předtím než jsou pro vás k dipozici. Doporučujeme získat přístup k poskytovali a naučit se více o daném rozšíření, než se ho rozhodnete nainstalovat.  

Společnost Microsoft poskytuje následující rozšíření:  

* [Migrace dat pomocí Dynamics GP](ui-extensions-dynamicsgp-data-migration.md)  
* [Microsoft Pay](ui-extensions-microsoft-pay-payments.md)
* [Platební standard PayPal](ui-extensions-paypal-payments-standard.md)  
* [Migrace dat QuickBooks](ui-extensions-quickbooks-data-migration.md)  
* [Prodej a prognóza zásob](ui-extensions-sales-forecast.md)  
* [Ceridian Payroll](ui-extensions-ceridian-payroll.md)  
* [Quickbooks Payroll File Import](ui-extensions-quickbooks-payroll.md)  
* [WorldPay Payments Standard](ui-extensions-worldpay-payments-standard.md)
* [GetAddress.io UK Postcodes](ui-extensions-getaddressio.md)
* [QuickBooks Online Data Migration](ui-extensions-quickbooks-online-data-migration.md)
* [Accountant Portal](ui-extensions-accountant-portal.md)  
* [Image Analyzer](ui-extensions-image-analyzer.md)

> [!NOTE]  
>  Nové rozšíření nejsou dostupné v AppSource ihned, po tom co nahlásíme aktualizaci. Můžete sledovat rozšíření na [AppSource.microsoft.com](https://appsource.microsoft.com/en-us/marketplace/apps?product=dynamics-365%3Bdynamics-365-for-financials&page=1).

## <a name="see-also"></a>Viz také
[Návod: Povolení plateb zákazníka pomocí PayPalu](sales-how-enable-payment-service-extensions.md)  
[migrování obchodních dat z jiných finančních systémů](upload-data.md)  
[Nastavení GetAddress.io UK Postal Code extension](LocalFunctionality/UnitedKingdom/uk-setup-postal-code-service.md)  
[[!INCLUDE[d365fin](includes/d365fin_md.md)] Rozšíření od jiných poskytovatelů](ui-extensions-other.md)  
[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  

##

