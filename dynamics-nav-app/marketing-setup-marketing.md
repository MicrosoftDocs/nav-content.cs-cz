---
title: "Nastavení marketingu a správy informací kontaktů"
description: "Můžete nastavit marketing a správu kontaktů v Dynamics NAV k optimalizaci vztahů s potenciálními zákazníky nebo zákazníky a zlepšení kampaní a propagace."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect, client, customer, campaign, promo
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 9ff95940c7418bf7cc1265eb128e0c9ccf4fb6c4
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-relationship-management"></a>Nastavení Správy vztahů
Než začnete pracovat s vašimi kontakty a marketingovými zájmy, existuje několik rozhodnutí a kroků, které byste měli podniknout, abyste nastavili, jak bude marketingová oblast spravovat určité aspekty vašich kontaktů. Můžete se například rozhodnout, zda chcete kartu kontaktu synchronizovat s kartou zákazníka, kartou dodavatele a kartou bankovního účtu, jak jsou definovány číselné řady nebo jaké by mělo být standardní oslovení při psaní vašim kontaktům.

Správa kontaktů a zavedení strategie pro identifikaci, přilákání a udržení zákazníků pomůže optimalizovat vaše podnikání a zvýšit spokojenost zákazníků. Použití dobrého systému správy kontaktů vám také pomůže vytvořit a udržovat vztahy s vašimi zákazníky. Komunikace je klíčem k těmto vztahům. Být schopen přizpůsobit komunikaci s potenciálními a stávajícími zákazníky, dodavateli a obchodními partnery podle svých potřeb je pro podniky nezbytné, aby uspěly. Vytvoření strategie a definování toho, jak vaše společnost používá kontaktní informace, je primárním krokem. Tyto informace budou ve vaší firmě zobrazeny mnoha různými skupinami, a tak dobrý systém pomůže všem být produktivnější.

Nastavíte marketing a správu kontaktů z okna **Nastavení marketingu**. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení marketingu** a vyberte související odkaz.

## <a name="automatically-copying-specific-information-from-the-contact-companies-to-the-contact-persons"></a>Automatické kopírování konkrétních informací od kontaktních společností ke kontaktním osobám
Některé informace o kontaktních společnostech jsou shodné s informacemi o kontaktních osobách, které v těchto společnostech pracují, například údaje o adrese. V sekci **Dědičnost** v okně **Nastavení marketingu** můžete aplikaci nastavit tak, aby automaticky kopírovala specifická pole z kontaktní karty na kartu kontaktní osoby při každém vytvoření kontaktní osoby pro kontaktní firmu. Můžete například vybrat ke zkopírování kód prodejce, údaje o adrese (adresa, adresa 2, město, PSČ a kraj), podrobnosti o komunikaci (faxové číslo, zpětná odpověď telexu a telefonní číslo) a další.

Pokud změníte jedno z těchto polí na kartě kontaktu společnosti, program automaticky upraví pole na kartě kontaktní osoby (pokud nemáte ručně upravená pole na kartě kontaktní osoby).

Další informace naleznete v tématu [Návod: Vytvořit kontaktní osoby.](marketing-how-create-contact-persons.md)

## <a name="using-predefined-defaults-on-new-contacts"></a>Použití předdefinované výchozí hodnoty pro nové kontakty
Můžete se rozhodnout, že aplikace automaticky přidělí jako výchozí každému novému vytvořenému kontaktu určitý kód jazyka, kód země, kód prodejce a kód země/regionu. Můžete také zadat výchozí kód prodejního cyklu, který program automaticky přiřadí každé nové příležitosti, kterou vytvoříte.

Dědičnost polí přepíše výchozí hodnoty, které jste nastavili. Například pokud jste nastavili angličtinu jako výchozí jazyk, ale jazyk kontaktu společnosti je němčina, program automaticky přidělí německý jazyk jako kód pro kontaktní osoby zaznamenané pro tuto společnost.

<!--You can also setup a default salutation that the program automatically assigns to your contacts. You can use these salutations in your interaction template attachments (for example, Microsoft Word documents). When setting up a default salutation, you can enter a salutation text and a salutation format. For example, if the salutation text is Dear, and the salutation format is Salutation Text + Title + Name, the program will automatically enter Dear Mr. John Smith as a salutation for a contact called John Smith.-->

## <a name="automatically-recording-interactions"></a>Automatické zaznamenávání interakcí
[!INCLUDE[d365fin](includes/d365fin_md.md)] dokáže automaticky zaznamenávat prodejní a nákupní doklady jako interakce (například objednávky, faktury, příjmy atd.), Stejně jako e-maily, telefonní hovory a průvodní stránky.

Další informace naleznete v tématu [Automatické zaznamenávání interakcí s kontakty](marketing-auto-record-interactions.md).

## <a name="synchronizing-contacts-with-customers-and-more"></a>Synchronizace kontaktů se zákazníky a dalšími
Chcete-li synchronizovat kartu kontaktu s kartou zákazníka, kartou dodavatele a kartou bankovního účtu, musíte vybrat kód obchodních vztahů pro zákazníky, dodavatele a bankovní účty. Můžete například propojit kontakt s existujícím zákazníkem v případě, že jste v okně **Nastavení marketingu** zvolili pro zákazníky kód pro obchodní vztahy.

Další informace naleznete v tématu [Synchronizace kontaktů se zákazníky, dodavateli a bankovními účty](marketing-synchronize-contacts-customers-vendors-bank-accounts.md).

## <a name="assigning-a-number-series-to-contacts-and-opportunities"></a>Přiřazení číselné řady ke kontaktům a příležitostem
Můžete nastavit číselnou řadu pro kontakty a příležitosti. Pokud jste vytvořili číselnou řadu pro kontakty při vytváření kontaktu, tak stiskněte klávesu Enter v poli číslo na kartě kontaktu, program automaticky zadá další dostupné kontaktní číslo.

Pro více informací o automatickém vyrovnání jděte na [ Návod: Vytváření číselných řad.](ui-create-number-series.md)

## <a name="searching-for-duplicate-contacts-when-contacts-are-created"></a>Nalezení duplicitních kontaktů při jejich vytváření
Můžete si vybrat, zda program automaticky vyhledá duplikáty při každém vytvoření kontaktní společnosti, nebo si můžete zvolit ruční vyhledávání po vytvoření kontaktů. Můžete také nastavit, aby program aktualizoval vyhledávací řetězce automaticky při každém úpravě kontaktních informací nebo vytvoření kontaktů. Můžete určit procento úspěšnosti hledání, tedy procento stejných řetězců, které musí mít dva kontakty, aby je program považoval za duplikáty.

## <a name="see-also"></a>Viz také
[Správa kontaktů](marketing-contacts.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

