---
title: "Nastavení marketingu a správy kontaktů"
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ddeef7532db8e16652ecab06d1303869531be9b2
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---
# <a name="set-up-marketing-and-contact-management"></a>Nastavení marketingu a správy kontaktů
Než začnete pracovat s vašimi kontakty a marketingovými zájmy, existuje několik rozhodnutí a kroků, které byste měli podniknout, abyste nastavili, jak bude marketingová oblast spravovat určité aspekty vašich kontaktů. Můžete se například rozhodnout, zda chcete kartu kontaktu synchronizovat s kartou zákazníka, kartou dodavatele a kartou bankovního účtu, jak jsou definovány číselné řady nebo jaké by mělo být standardní oslovení při psaní vašim kontaktům.

Správa kontaktů a zavedení strategie pro identifikaci, přilákání a udržení zákazníků pomůže optimalizovat vaše podnikání a zvýšit spokojenost zákazníků. Použití dobrého systému správy kontaktů vám také pomůže vytvořit a udržovat vztahy s vašimi zákazníky. Komunikace je klíčem k těmto vztahům. Být schopen přizpůsobit komunikaci s potenciálními a stávajícími zákazníky, dodavateli a obchodními partnery podle svých potřeb je pro podniky nezbytné, aby uspěly. Vytvoření strategie a definování toho, jak vaše společnost používá kontaktní informace, je primárním krokem. Tyto informace budou ve vaší firmě budou zobrazeny mnoha různými skupinami, a tak dobrý systém pomůže všem být produktivnější.

Nastavíte marketing a správu kontaktů z okna **Nastavení marketingu**. K otevření okna **Nastavení marketingu**, v pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení marketingu** a zvolte související odkaz.

## <a name="automatically-copy-specific-information-from-the-contact-companies-to-the-contact-persons"></a>Automatické kopírování konkrétních informací od kontaktních společností ke kontaktním osobám
Některé informace o kontaktních společnostech jsou shodné s informacemi o kontaktních osobách, které v těchto společnostech pracují, například údaje o adrese. V sekci **Dědičnost** v okně **Nastavení marketingu** můžete aplikaci nastavit tak, aby automaticky kopírovala specifická pole z kontaktní karty na kartu kontaktní osoby při každém vytvoření kontaktní osoby pro kontaktní firmu. Můžete například vybrat ke zkopírování kód prodejce, údaje o adrese (adresa, adresa 2, město, PSČ a kraj), podrobnosti o komunikaci (faxové číslo, zpětná odpověď telexu a telefonní číslo) a další.

Pokud změníte jedno z těchto polí na kartě kontaktu společnosti, program automaticky upraví pole na kartě kontaktní osoby (pokud nemáte ručně upravená pole na kartě kontaktní osoby).

Další informace naleznete v tématu [Návod: Vytvořit kontaktní osoby](marketing-how-create-contact-persons.md).

## <a name="use-predefined-defaults-on-new-contacts"></a>Použití předdefinované výchozí hodnoty pro nové kontakty
Můžete se rozhodnout, že aplikace automaticky přidělí jako výchozí každému novému vytvořenému kontaktu určitý kód jazyka, kód země, kód prodejce a kód země/regionu. Můžete také zadat výchozí kód prodejního cyklu, který program automaticky přiřadí každé nové příležitosti, kterou vytvoříte.

Dědičnost polí přepíše výchozí hodnoty, které jste nastavili. Například pokud jste nastavili angličtinu jako výchozí jazyk, ale jazyk kontaktu společnosti je němčina, program automaticky přidělí německý jazyk jako kód pro kontaktní osoby zaznamenané pro tuto společnost.

<!--You can also setup a default salutation that the program automatically assigns to your contacts. You can use these salutations in your interaction template attachments (for example, Microsoft Word documents). When setting up a default salutation, you can enter a salutation text and a salutation format. For example, if the salutation text is Dear, and the salutation format is Salutation Text + Title + Name, the program will automatically enter Dear Mr. John Smith as a salutation for a contact called John Smith.-->

## <a name="automatically-record-interactions"></a>Automatické zaznamenávání interakcí
Dynamics NAV dokáže automaticky zaznamenávat prodejní a nákupní doklady jako interakce (například objednávky, faktury, příjmy atd.), Stejně jako e-maily, telefonní hovory a průvodní stránky.

Další informace naleznete v tématu [Automatické zaznamenávání interakcí s kontakty](marketing-auto-record-interactions.md).

## <a name="synchronize-contacts-with-customers-and-more"></a>Synchronizace kontaktů se zákazníky a dalšími
Chcete-li synchronizovat kartu kontaktu s kartou zákazníka, kartou dodavatele a kartou bankovního účtu, musíte vybrat kód obchodních vztahů pro zákazníky, dodavatele a bankovní účty. Můžete například propojit kontakt s existujícím zákazníkem v případě, že jste v okně **Nastavení marketingu** zvolili pro zákazníky kód pro obchodní vztahy.

Další informace naleznete v tématu [Synchronizace kontaktů se zákazníky, dodavateli a bankovními účty](marketing-synchronize-contacts-customers-vendors-bank-accounts.md).

## <a name="assign-a-number-series-to-contacts-and-opportunities"></a>Přiřazení řady čísel ke kontaktům a příležitostem
Můžete nastavit řadu čísel pro kontakty a příležitosti. Pokud jste vytvořili řadu čísel pro kontakty při vytváření kontaktu, tak stiskněte klávesu Enter v poli číslo na kartě kontaktu, program automaticky zadá další dostupné kontaktní číslo.

Pro další informace o řadách čísel se podívejte na [Vytvoření číselné řady](ui-create-number-series.md).

## <a name="search-for-duplicate-contacts-when-contacts-are-created"></a>Nalezení duplicitních kontaktů při jejich vytváření
Můžete si vybrat, zda program automaticky vyhledá duplikáty při každém vytvoření kontaktní společnosti, nebo si můžete zvolit ruční vyhledávání po vytvoření kontaktů. Můžete také nastavit, aby program aktualizoval vyhledávací řetězce automaticky při každém úpravě kontaktních informací nebo vytvoření kontaktů. Můžete určit procento úspěšnosti hledání, tedy procento stejných řetězců, které musí mít dva kontakty, aby je program považoval za duplikáty.

## <a name="set-up-email-logging"></a>Nastavení protokolování e-mailu
Můžete si vyměňovat e-mailové zprávy se svými kontakty, zákazníky, prodejci atd. Můžete posílat a přijímat své e-mailové zprávy buď z aplikace, nebo z aplikace Outlook. Předtím, než si budete moci vyměňovat zprávy tímto způsobem, ukládat systém a ukládat je do fronty, musíte nastavit některé parametry, například časový interval, ve kterém program zkontroluje, zda se čeká na zpracování e-mailů, jméno profilu e-mailu atd.

## <a name="see-also"></a>Viz také
[Správa kontaktů](marketing-contacts.md)  

