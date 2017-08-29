---
title: "Návod: Proces vrácení nebo zrušení nákupu"
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
ms.openlocfilehash: 94067fb3d10975c1db29d2e3f1d5d6373fcbf9f2
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-process-purchase-returns-or-cancellations"></a>Návod: Proces vrácení nebo zrušení nákupu
Pokud chcete vrátit položky dodavateli nebo zrušit zakoupené služby, můžete vytvořit a zaúčtovat nákupní dobropis, který specifikuje požadovanou změnu ve vztahu k původní nákupní faktuře. Chcete-li zahrnout správné fakturační informace o nákupu, můžete si vytvořit nákupní dobropis ze zaúčtované nákupní faktury nebo použít funkci kopírování.

Obvykle vytvoříte nákupní dobropis v reakci na dobropis, který vám byl zaslán dodavatelem. Nákupní dobropis slouží jako interní dokumentace procesu dobropisů pro účetní účely.

Změna se může týkat všech produktů na původní nákupní faktuře nebo pouze některých produktů. V důsledku toho můžete částečně vrátit přijaté položky nebo požadovat částečnou úhradu přijatých služeb. V takovém případě musíte upravit kopírované informace nákupní faktury.

Kromě původní zaúčtované nákupní faktury můžete vyrovnat nákupní dobropis na jiné nákupní doklady například další zaúčtovanou nákupní fakturu, protože také vracíte položky dodané s touto fakturou.

## <a name="to-create-a-purchase-credit-memo-from-a-posted-purchase-invoice"></a>Vytvoření nákupního dobropis ze zaúčtované nákupní faktury
1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nákupní dobropisy** a pak vyberte související odkaz.  
2. V okně **Zaúčtované nákupní faktury** vyberte fakturu za nákup, kterou chcete vrátit zpět a poté vyberte akci **Vytvořit opravný dobropis**.

    Většina polí v záhlaví nákupního dobropisu je vyplněna informacemi ze zaúčtované nákupní faktury. Můžete upravit všechna pole například s novými informacemi, které odrážejí dohodu o vrácení.
3. Upravte informace o řádcích podle dohody například počet vrácených položek nebo částku, která má být vrácena.
4. Zvolte akci **Vyrovnat položky**.
5. V okně **Vyrovnat položky dodavatele** vyberte řádek se zaúčtovaným nákupním dokladem, na který chcete vyrovnat nákupní dobropis a poté vyberte akci **ID vyrovnání**. Číslo nákupního dobropisu se vloží do pole **ID vyrovnání**.
6. Do pole **Částka k vyrovnání** zadejte částku, kterou chcete vyrovnat, pokud je menší než původní částka.

    V dolní části okna **Vyrovnat položky dodavatele** můžete vidět celkovou částku, která má být použita k převedení všech zahrnutých položek a to v případě, že hodnota v poli **Zůstatek** je nula.
7. Zvolte tlačítko **OK**. Když zaúčtujete nákupní dobropis, bude vyrovnán na určené zaúčtované nákupní dokumenty.

    Když jste vytvořili nebo upravili řádky potřebného nákupního dobropisu a jsou specifikovány jednotlivé nebo více aplikací, můžete pokračovat v zaúčtování nákupního dobropisu.
8. Zvolte akci **Zaúčtovat**.

Zaúčtované nákupní faktury, na které vyrovnáte dobropis, jsou nyní zrušeny. Pokud jste již zaplatili původní fakturu, dodavatel by vám nyní měl vrátit platbu. Pokud je dobropis pouze pro část produktu na původní faktuře, můžete zaplatit zbývající částku pouze v původní nákupní faktuře.

Nákupní dobropis je odstraněn a nahrazen novým dokladem v seznamu zaúčtovaných dobropisů.

## <a name="to-create-a-purchase-credit-memo-from-scratch"></a>Vytvoření nákupního dobropisu od začátku
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účtované nákupní faktury** a pak vyberte související odkaz.
2. Chcete-li otevřít nový prázdný nákupní dobropis, zvolte akci **Nový**.
3. Do pole **Dodavatel** zadejte název existujícího dodavatele.
4. Zvolte akci **Kopírovat doklad**.
5. V okně **Kopírovat nákupní doklad** v poli **Typ dokumentu** vyberte **Účtovaná faktura**.
6. Zvolte pole **Číslo dokladu** pro otevření **Účtované nákupní faktury** a potom vyberte zaúčtovanou nákupní fakturu, která obsahuje řádky, které chcete vrátit zpět.
7. Zaškrtněte políčko **Přepočítat řádky**, pokud chcete, aby byly kopírované řádky zaúčtované nákupní faktury aktualizovány s jakýmikoliv změnami v ceně zboží a jednotkových cenách od zaúčtované faktury.
8. Zvolte tlačítko **OK**. Zkopírované řádky faktur jsou vloženy do nákupního dobropisu.
9. Dokončete nákupní dobropis, jak je vysvětleno v části "Vytvoření nákupního dobropisu ze zaúčtované nákupní faktury" v tomto tématu.

## <a name="see-also"></a>Viz také
[Správa nákupu](purchasing-manage-purchasing.md)  
[Návod: Nákupní záznamy](purchasing-how-record-purchases.md)  

