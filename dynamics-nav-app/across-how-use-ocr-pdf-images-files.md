---
title: "Návod: Použití funkce OCR k převedení souborů PDF a obrázkových souborů do elektronických dokladů"
author: SorenGP
ms.custom: na
ms.date: 10/06/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 96b1baf3554d3647e75223bb4cb1ee08dc21eb6d
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-use-ocr-to-turn-pdf-and-image-files-into-electronic-documents"></a>Návod: Použití funkce OCR k převedení souborů PDF a obrázkových souborů do elektronických dokladů
Ze souborů PDF nebo obrázkový souborů, které obdržíte od svých obchodních partnerů, můžete pomocí externí službu OCR (Optical Character Recognition) generovat elektronické doklady, které lze převést na záznamy dokladů v Dynamics NAV. Pokud například od dodavatele obdržíte fakturu ve formátu PDF, můžete ji odeslat do služby OCR z okna **Došlé doklady**. Toto je popsáno v první proceduře.

Jako alternativu k odeslání souboru z okna **Došlé doklady**, můžete odeslat soubor službě OCR e-mailem. Poté, když obdržíte elektronický doklad zpět, automaticky se vytvoří související záznam došlého dokladu. Toto je popsáno v druhé proceduře.

Po několika sekundách obdržíte soubor zpět od služby OCR jako elektronickou fakturu, kterou lze převést na nákupní fakturu dodavatele. Toto je popsáno v třetí proceduře.

Vzhledem k tomu, že OCR je založen na optickém rozpoznávání, je pravděpodobné, že služba OCR interpretuje znaky ve vašem souboru PDF nebo obrázkových souborů nesprávně, když například nejprve zpracuje doklady konkrétního dodavatele. Nemusí správně interpretovat logo společnosti jako jméno prodejce, nebo může nesprávně interpretovat celkovou částku na příjemce kvůli jejímu rozložení. Chcete-li se těmto chybám vyhnout, můžete chyby opravit v samostatné verzi v okně **Došlé doklady**.  Poté odešlete opravy zpět do služby OCR, aby se mohli správně interpretovat specifické znaky při příštím zpracování dokumentu PDF nebo obrázkového souboru pro stejného dodavatele. Další informace naleznete v části „Zlepšení služby OCR k vyhnutím se chybám“.

Přenos souborů do a ze služby OCR je zpracována položka vyhrazená frontou úloh, která se automaticky vytvoří při povolení příslušného připojení služby. Další informace naleznete v [Návod: Nastavení došlých dokladů](across-how-setup-income-documents.md).

## <a name="to-send-a-pdf-or-image-file-to-the-ocr-service-from-the-incoming-documents-window"></a>Odeslání souboru PDF nebo obrázkového souboru do služby OCR z okna **Došlé doklady**
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Došlé doklady** a pak vyberte související odkaz. 
2. Vytvořte nový záznam došlého dokladu a připojte soubor. Další informace naleznete v [Návod: Vytvořit záznamy došlého dokladu](across-how-create-income-document-records.md).  
3. V okně **Došlé doklady** vyberte jeden nebo více řádků a pak zvolte akci **Odeslat do fronty úloh**.

    Hodnota pole **Stav OCR** se změní na **Připraveno**. Odešle se přiložený soubor PDF nebo obrázkový soubor do služby OCR frontou úloh podle plánu za předpokladu, že se nevyskytnou žádné chyby.
5. Případně v okně **Došlé doklady** vyberte jeden nebo více řádků a poté zvolte akci **Odeslat do služby OCR**.

Hodnota v poli **Stav OCR** se změní na Odesláno, pokud neexistují žádné chyby.

## <a name="to-send-a-pdf-or-image-file-to-the-ocr-service-by-email"></a>Odeslání souboru PDF nebo obrázkového souboru do služby OCR e-mailem
Z vaší e-mailové aplikace můžete odeslat e-mailové zprávy poskytovateli služby OCR s připojeným souborem PDF nebo obrázkovým souborem. Informace o e-mailové adrese, na kterou chcete odeslat, naleznete na webu poskytovatele služeb OCR.

Protože žádný záznam došlého dokladu neexistuje pro soubor, nový záznam se automaticky vytvoří v okně  **Došlé doklady**, jakmile obdržíte výsledný elektronický doklad ze služby OCR. Další informace naleznete v [Návod: Vytvořit záznamy došlého dokladu](across-how-create-income-document-records.md).

**Poznámka**: Pokud pracujete s tabletem nebo telefonem, můžete soubor odeslat službě OCR, jakmile pořídíte fotografii dokladu nebo můžete vytvořit došlý doklad přímo. Další informace naleznete v části "Vytvoření záznamu došlého dokladu pořízením fotografie" [Návod: Vytvořit záznamy došlého dokladu](across-how-create-income-document-records.md).

## <a name="to-receive-the-resulting-electronic-document-from-the-ocr-service"></a>Získání výsledného elektronického dokladu ze služby OCR.
Elektronický doklad, který je vytvořen službou OCR ze souboru PDF nebo obrázkového souboru, je automaticky přijat do okna **Došlé doklady** položkou fronty úloh, která je nastavena při aktivaci služby OCR.

Pokud nepoužíváte frontu úloh nebo chcete přijmout dokončený doklad OCR dřív, než je v rozvrhu fronty úloh, můžete zvolit tlačítko **Příjmout ze služby OCR**.  Získáte tak všechny doklady, které jsou dokončeny službou OCR.

**Poznámka**: Pokud je služba OCR nastavena tak, aby vyžadovala manuální ověření zpracovávaných dokladů, potom pole **Stav OCR** bude obsahovat **Čeká na ověření**. V takovém případě proveďte následující kroky pro přihlášení k webové stránce služby OCR, abyste ručně ověřili dokument OCR.

1. V poli **Stav OCR** zvolte hypertextový odkaz **Čeká na ověření**. Případně zvolte na domovské stránce tlačítko **Čeká na ověření**.
2. Na webu služby OCR se přihlaste pomocí přihlašovacích údajů vašeho účtu služby OCR. Toto jsou pověření, která jste použili při nastavení služby. Další informace naleznete v části "Nastavení služby OCR" [Návod: Nastavení došlých dokladů](across-how-setup-income-documents.md).

    Pokud přistupujete z pole **Stav OCR** k webu, zobrazí se daný dokument bezprostředně po přihlášení. Pokud přistupujete k webu výběrem dlaždice na domovské stránce, na první stránce služby OCR, která se otevře, musíte zvolit tlačítko **Start** na kartě **Kontrola** nebo dvakrát kliknout na doklad, který chcete ověřit.

    Zobrazí se informace o dokladu OCR, které zobrazují zdrojový obsah souboru PDF nebo obrázkového souboru a výsledné hodnoty pole OCR.
3. Zkontrolujte různé hodnoty polí a ručně upravte nebo zadejte hodnoty v polích, které služba OCR označila za nejisté.
4. Zvolte tlačítko **OK**. Proces OCR je dokončen a výsledný elektronický doklad je odeslán do okna **Došlé doklady** v Dynamics NAV podle plánu fronty úloh.

    Pokud přistupujete k webové stránce pomocí výběru dlaždice na domovské stránce, automaticky se na webových stránkách zobrazí další doklad OCR, který má být ověřen.
5. Opakujte krok 4 pro ověření jakéhokoliv jiného dokladu OCR.

Nyní můžete manuálně nebo automaticky vytvářet záznamy dokladu pro přijaté elektronické doklady v Dynamics NAV. Další informace naleznete v části "Vytvoření záznamu dokladu v programu Dynamics NAV z dokladu přijatého OCR". Nový záznam došlého dokladu můžete také připojit k existujícímu zaúčtovanému či nezaúčtovanému dokladu, takže zdrojový soubor je snadno přístupný z aplikace Dynamics NAV. Další informace naleznete v části [Proces došlých dokladů](across-process-income-documents.md).

## <a name="to-create-a-purchase-invoice-from-an-electronic-document-received-from-the-ocr-service"></a>Vytvoření nákupní faktury z elektronického dokladu obdrženého od služby OCR
Následující postup popisuje, jak vytvořit záznam o nákupní faktuře z faktury dodavatele obdržené jako elektronický doklad od služby OCR. Postup je stejný, jako když vytvoříte například řádek finančního deníku z výdajů příjemky.

**Poznámka**: Pole **Popis** a **Číslo** na vytvořených řádcích dokladu budou vyplněny pouze tehdy, pokud jste poprvé namapovali text v dokumentu OCR na dvě pole v aplikaci Dynamics NAV. Můžete to udělat buď jako křížové odkazy položky pro řádky dokladů typu Zboží nebo jako mapování textu k účtům pro doklad nebo řádky finančního deníku. Další informace naleznete v popisu tlačítka akce **Křížové odkazy** na kartách položek a související procedury [Návod: Mapovat text o opakovaných platbách na účtech pro automatické odsouhlasení](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md).

U došlých dokladů typicky použijete **Mapovat text na účet**, abyste definovali, že určitý text na faktuře dodavatele je přijatý ze služby OCR a je mapován na určitý účet dodavatele. Jakákoliv část popisu došlého dokladu, která existuje jako mapovací text, znamená, že pole **Číslo** na výsledných dokumentech nebo řádcích finančního deníku je vyplněno dotyčným prodejcem.

Kromě mapování na účet prodejce nebo na finanční účet můžete také mapovat na bankovní účet. To je praktické například u elektronických dokladů o výdajích, které jsou již zaplaceny, vytvořeny na řádcích finančního deníku a připraveny k zaúčtování na bankovní účet.

1. Vyberte řádek došlého dokladu pro elektronický doklad dodavatele přijatý službou OCR.
2. Chcete-li namapovat text v dokladu v účtu dodavatele MD, zvolte akci **Mapovat text na účet** a pak vyplňte okno **Mapování textu na účet** s informacemi, které se budou vztahovat na předávajícího dodavatele. Další informace naleznete v [Návod: Mapovat text o opakovaných platbách na účtech pro automatické odsouhlasení](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md).
3. Chcete-li namapovat čísla zboží na dokladu do popisu položek dodavatele, otevřete kartu každé položky a potom vyberte akci **Křížové odkazy** a nastavte křížové odkazy mezi vašimi popisy zboží a těmi u prodejce.
4. V okně **Došlé doklady** zvolte akci **Vytvořit dokument**.

V Dynamics NAV bude vytvořena nákupní faktura na základě informací v elektronickém dokladu dodavatele, který jste obdrželi od služby OCR.

Jakékoliv chyby ověřování, které se typicky týkají nesprávných nebo chybějících hlavních dat v Dynamics NAV, se zobrazí v záložce s náhledem **Chyby a varování**. Další informace naleznete v části „Vypořádání se s chybami při přijímání elektronických dokladů.“

## <a name="to-handle-errors-when-receiving-electronic-documents"></a>Vypořádání se s chybami při přijímání elektronických dokladů
1. V okně **Došlé doklady** vyberte řádek pro elektronický doklad přijatý službou OCR s chybami. Toto je indikováno hodnotou Error v poli **Stav OCR**.
2. Zvolte akci **Upravit** a otevřete okno **Došlé doklady**.
3. V záložce s náhledem **Chyby a varování** vyberte zprávu a poté zvolte akci **Otevřít související záznam**.
4. Zobrazí se okno, které obsahuje nesprávná nebo chybějící data, například karta dodavatele s chybějící hodnotou pole.
5. Opravte chybu nebo chyby popsané v každé chybové zprávě.
6. Pokračujte ve zpracování příchozího elektronického dokladu výběrem možnosti **Vytvořit ručně**.
7. Opakujte kroky 5 a 6 pro všechny zbývající chyby, dokud nebude elektronický doklad úspěšně přijat.

## <a name="to-train-the-ocr-service-to-avoid-errors"></a>Zlepšení služby OCR, abyste předešli chybám
Vzhledem k tomu, že OCR je založen na optickém rozpoznávání, je pravděpodobné, že služba OCR interpretuje znaky ve vašem souboru PDF nebo obrázkovém souboru nesprávně, když například nejprve zpracuje doklady konkrétního dodavatele. Nemusí správně interpretovat logo společnosti jako jméno prodejce nebo může nesprávně interpretovat celkovou částku na příjemce kvůli jejímu rozložení. Chcete-li zabránit takovým chybám, můžete opravit data přijatá službou OCR a poslat službě zpětnou vazbu.

Okno **Oprava dat OCR**, které otevřete v okně **Došlé doklady**, zobrazuje pole ze záložky s náhledem **Finanční informace** ve dvou sloupcích, z nichž jedna může být upravitelná pomocí OCR a jedna pouze pro čtení. Pokud zvolíte tlačítko **Poslat zpětnou vazbu OCR**, obsah okna **Oprava dat OCR** je odeslána do služby OCR.  Příště, vždy když služba zpracuje soubory PDF nebo obrázkové soubory, které obsahují dotyčná data, budou vaše opravy začleněny, aby se předešlo stejným chybám.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Došlé doklady** a pak vyberte související odkaz.
2. Otevřete záznam došlého dokladu, který obsahuje data přijatá službou OCR, které chcete opravit.
3. V okně **Došlé doklady** zvolte akci **Opravit data OCR**.
4. V okně **Oprava dat OCR** přepište data v upravitelném sloupci pro každé pole, které má nesprávnou hodnotu.
5. Zrušte opravy, které jste provedli od otevření okna **Oprava dat OCR** a zvolte akci **Resetovat data OCR**.
6. Chcete-li opravy odeslat do služby OCR, zvolte akci **Odeslat zpětnou vazbu OCR**.
7. Chcete-li uložit opravy, zavřete okno **Oprava dat OCR**. 

Pole záložky s náhledem **Finanční informace** v okně **Došlé doklady** jsou aktualizovány novými hodnotami, které jste zadali v kroku 4.

## <a name="see-also"></a>Viz také  
[Proces došlých dokladů](across-process-income-documents.md)  
[Došlé doklady](across-income-documents.md)  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Práce s Dynamics NAV](ui-work-product.md)

