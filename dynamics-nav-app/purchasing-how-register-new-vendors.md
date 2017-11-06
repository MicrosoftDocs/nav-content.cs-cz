---
title: "Vytvoření karty dodavatele k registraci nového dodavatele"
description: "Přečtěte si, jak vytvořit kartu dodavatele pro registraci nového dodavatele nebo zásobitele."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supplier
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c7fee8b43940fc5e5fb020b4ca1ac9b27b90decd
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-register-new-vendors"></a>Návod: Registrace nového dodavatele
Dodavatelé poskytují produkty, které prodáváte. Každý dodavatel, od kterého jste nakoupili, musí být zaregistrován jako karta dodavatele.

Než budete moci registrovat nové dodavatele, musíte nastavit různé nákupní kódy, které si můžete vybrat od okamžiku, kdy vyplníte karty dodavatele. Když jsou vytvořeny všechny požadovaná data, můžete provést dodatečnou konfiguraci dodavatele, například upřednostnit dodavatele pro platební účely a položky seznamu, které dodavatel a ostatní dodavatelé mohou dodat. Další skupinou úloh pro dodavatele je zaznamenat vaše dohody týkající se slev, cen a platebních metod. Další informace naleznete v tématu: [Nastavení nákupů](purchasing-setup-purchasing.md).

Prodejní karty obsahují informace, které jsou potřebné k nákupu produktů od dodavatele. Další informace naleznete v tématu [Návod: Zaznamenávání nákupů](purchasing-how-record-purchases.md) a [Návod: Registrovat nového zboží](inventory-how-register-new-items.md).

> [!NOTE]  
>   Pokud existují šablony dodavatele pro různé typy dodavatele, objeví se okno při vytváření nové karty dodavatele, odkud můžete vybrat vhodnou šablonu. Pokud existuje pouze jedna šablona dodavatele, pak nové karty dodavatele vždy použijí tuto šablonu.

## <a name="to-create-a-new-vendor-card"></a>Vytvoření nové karty dodavatele
1. Na domovské stránce vyberte akci **Dodavatelé** pro otevření seznamu existujících dodavatelů.  
2. V okně **Dodavatelé** vyberte možnost **Nový**.

    Pokud existuje více než jedna šablona dodavatele, otevře se okno, z něhož můžete vybrat šablonu dodavatele. V tomto případě, následujte další dva kroky.
3. V okně **Vybrat šablonu pro nového dodavatele** vyberte šablonu, kterou chcete použít pro novou kartu dodavatele.
4. Zvolte tlačítko **OK**. Otevře se nová karta dodavatele s některými poli vyplněnými informacemi ze šablony.
5. Postupujte podle potřeby tak, že vyplníte nebo změníte pole na kartě dodavatele. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   Pokud neznáte fakturační adresu, která bude použita u každé faktury od dodavatele, nevyplňujte pole **věřitel**. Namísto toho zvolte číslo věřitele po založení nákupní nabídky, objednávky nebo hlavičky faktury.

Dodavatel je nyní zaregistrován a karta dodavatele je připravena k použití v nákupních dokladech.

Chcete-li tuto kartu dodavatele použít jako šablonu při vytváření nových karet dodavatele, můžete ji uložit jako šablonu. Pro další informace se podívejte na následující sekci.

## <a name="to-save-the-vendor-card-as-a-template"></a>Uložení karty dodavatele jako šablony
1. V okně **Karta dodavatele**, vyberte akci **Uložit jako šablonu**. Okno **Šablona dodavatele** otevírá kartu dodavatele jako šablonu.
2. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. K opětovnému použití dimenzí v šablonách zvolte tlačítko **Dimenze**. Okno **Šablony dimenzí** otevírá jakékoli kódy dimenzí, které jsou pro daného dodavatele nastaveny.
4. Upravte nebo zadejte kódy dimenzí, které se budou vztahovat na nové karty dodavatele vytvořené pomocí šablony.
5. Po dokončení nové šablony dodavatele vyberte tlačítko **OK**.  
   Šablona dodavatele je přidána do seznamu šablon dodavatele, takže ji můžete použít k vytvoření nových karet zboží.

## <a name="see-also"></a>Viz také
[Nákup](purchasing-manage-purchasing.md)  
[Návod: Zaznamenávání nákupu](purchasing-how-record-purchases.md)   
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

