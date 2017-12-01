---
title: "Vytvořit kartu zákazníka k registraci nového zákazníka"
description: "Popisuje, jak vytvořit kartu zákazníka pro registraci informací o každém novém zákazníkovi nebo klientovi, kterému prodáváte."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: client
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c97412269cdac3f4ba1616b14e294e18599e93aa
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-register-new-customers"></a>Návody Registrace nového zákazníka
Zákazníci jsou zdrojem příjmů. Každého zákazníka, kterému prodáváte, musíte zaregistrovat jako zákaznickou kartu. Karty zákazníků udržují informace, které jsou potřebné k prodeji produktů zákazníkům. Další informace naleznete v [Návod: Fakturování prodeje](sales-how-invoice-sales.md) nebo [Návod: Registrace nového zboží](inventory-how-register-new-items.md).  

Než budete moci registrovat nové zákazníky, musíte nastavit různé prodejní kódy, které si můžete vybrat od okamžiku, kdy vyplníte zákaznické karty. Další informace naleznete v tématu: [Nastavení prodeje](sales-setup-sales.md).

> [!NOTE]  
>   Pokud existují šablony zákazníků pro různé typy zákazníků, objeví se okno při vytváření nové zákaznické karty, kde můžete vybrat vhodnou šablonu. Pokud existuje jediná šablona zákazníka, potom nová karta zákazníka vždy použije tuto šablonu.

## <a name="to-create-a-new-customer-card"></a>Vytvoření nové karty zákazníka
1. Na domovské stránce, vyberte tlačítko **Zákazníci** k otevření seznamu existujících zákazníků.  
2. V okně **Zákazníci** zvolte **Nový**.

    Pokud existuje pouze jedna šablona zákazníka, otevře se nová zákaznická karta s několika předvyplněnými poli s informacemi ze šablony.

    Pokud existuje více než jedna šablona zákazníka, otevře se okno, z něhož můžete vybrat šablonu zákazníka. V tomto případě následujte další 2 kroky.
3. Ve okně **Výběr šablony pro nového zákazníka** vyberte šablonu, kterou chcete použít pro novou kartu zákazníka.
4. Zvolte tlačítko **OK**. Otevře se nová zákaznická karta s několika předvyplněnými poli s informacemi ze šablony.  
5. Pokračujte ve vyplňování nebo změně polí na kartě zákazníka podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

V záložce **Prodejní ceny** můžete zobrazit zvláštní ceny nebo slevy, které udělujete zákazníkovi, pokud jsou splněna určitá kritéria, jako je položka, minimální objednané množství nebo datum ukončení. Každý řádek představuje speciální slevu nebo řádkovou slevu. Každý sloupec představuje kritérium, které musí platit, aby se zaručila speciální cena, kterou zadáte do pole **Jednotková cena**, nebo řádkovou slevu, kterou zadáte do pole **Řádková sleva**. Další informace naleznete v tématu: [Zaznamenání Prodejní ceny, slevy a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).

Zákazník je nyní zaregistrován a zákaznická karta je připravena k použití v prodejních dokumentech.

Chcete-li tuto kartu použít jako šablonu pro vytváření nových zákaznických karet, můžete ji uložit jako šablonu. Pro více informací sledujte následující sekci

## <a name="to-save-the-customer-card-as-a-template"></a>Uložení zákaznické karty pro vytvoření šablony.
1. V okně **Karta zákazníka** zvolte **Uložit jako šablonu**. Otevře se okno **Šablona zákazníka**, která zobrazuje kartu zákazníka jako šablonu.
2. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. K opětovnému použití dimenzí v šablonách zvolte tlačítko **Dimenze**. Okno **Šablony dimenzí** zobrazí kódy dimenzí, které jsou nastaveny u daného zákazníka.
4. Upravte nebo zadejte kódy dimenzí, které se budou vztahovat na nové zákaznické karty vytvořené pomocí šablony.  
5. Po dokončení nové šablony zákazníka zvolte tlačítko **OK**.

Šablona zákazníka je přidána do seznamu šablon zákazníků, takže ji můžete použít k vytvoření nových zákaznických karet.

## <a name="see-also"></a>Viz také
[Prodej](sales-manage-sales.md)    
[Nastavení prodeje](sales-setup-sales.md)    
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

