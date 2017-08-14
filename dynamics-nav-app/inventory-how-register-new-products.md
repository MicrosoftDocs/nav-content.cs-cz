---
title: "Návody: Zaregistrujte nové produkty"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: df84a4d3e15035cd956c7612a12069844f5601d2
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-register-new-products"></a>Návody: Zaregistrujte nové produkty

Výrobky jsou základem vašeho podnikání, zboží nebo služeb, se kterými obchodujete. Každý produkt musí být registrován jako karta zboží.

**Poznámka**: V Dynamics NAV se produkt označuje výrazem "zboží".

Karty zboží obsahují informace, které jsou nutné k nákupu, skladování, prodeji, doručení a účet produktů.

Karta zboží může být typu Zásoba nebo Služba, která určuje, zda je produkt fyzickou jednotkou nebo jednotkou času. Kromě některých polí, které se vztahují k fyzickým aspektům položky, všechny políčka na kartě zboží fungují stejně jako skladové položky a služby. Další informace o prodeji zboží naleznete v [Návody: Prodat produkty](sales-how-sell-products.md) nebo [Návody: Prodejní faktury](sales-how-invoice-sales.md).

**Poznámka**: Pokud existují šablony zboží pro různé typy zboží, objeví se okno při vytváření nové karty zboží, odkud můžete vybrat vhodnou šablonu. Pokud existuje pouze jedna šablona zboží, pak nové karty zboží používají vždy tuto šablonu.

## <a name="to-create-a-new-item-card"></a>K vytvoření nové karty zboží
1. Na domovské stránce vyberte akci **Zboží** pro otevření seznamu existujícího zboží.  
2. V okně **Zboží** vyberte akci **Nové**.

    Pokud existuje pouze jedna šablona zboží, otevře se nová karta zboží s několika poli vyplněnými informacemi ze šablony.
3. V okně **Vybrat šablonu pro nové zboží** vyberte šablonu, kterou chcete použít pro novou kartu zboží.
4. Vyberte tlačítko **OK**. Otevře se nová karta zboží s některými poli vyplněnými informacemi ze šablony.
5. Postupujte podle potřeby tak, že vyplníte nebo změníte pole na kartě zboží. Vybrat pole k zobrazení krátkého popisu nebo odkazu pro více informací.

Na záložce s náhledem **Prodejní ceny** můžete zobrazit zvláštní ceny nebo slevy, které udělujete za dané zboží, pokud jsou splněna určitá kritéria, jako je zákazník, minimální objednávkové množství nebo datum ukončení. Každý řádek představuje zvláštní cenu nebo řádkovou slevu. Každý sloupec představuje kritérium, které musí platit, aby se zaručila zvláštní cena, kterou zadáte do pole **Jednotková cena**, nebo řádková sleva, kterou zadáte do pole **Řádková sleva %**. Další informace naleznete v [Zaznamenat prodejní cenu, slevu a platební smlouvy](sales-how-record-sales-price-discount-payment-agreements.md).

Položka je nyní zaregistrována a karta zboží je připravena k použití v nákupních a prodejních dokladech.

Chcete-li tuto kartu zboží použít jako šablonu při vytváření nových karet zboží, můžete ji uložit jako šablonu. Pro další informace se podívejte na následující sekci.

## <a name="to-save-the-item-card-as-a-template"></a>K uložení karty zboží jako šablony
1. V okně **Karta zboží**, vyberte akci **Uložit jako šablonu**. Okno **Šablona zboží** otevírá kartu zboží jako šablonu.
2. Vyplňte pole podle potřeby. Vybrat pole k zobrazení krátkého popisu nebo odkazu pro více informací.
3. Chcete-li znovu použít dimenze v šablonách, zvolte akci **Dimenze**. Okno **Šablony dimenzí** otevírá jakékoli kódy dimenzí, které jsou pro dané zboží nastaveny.
4. Upravte nebo zadejte kódy dimenzí, které se budou vztahovat na nové karty zboží vytvořené pomocí šablony.
5. Po dokončení nové šablony zboží vyberte tlačítko **OK** .

Šablona zboží je přidána do seznamu šablon zboží, takže ji můžete použít k vytvoření nových karet zboží.

## <a name="see-also"></a>Viz také
  [Spravovat zásoby](inventory-manage-inventory.md)  
  [Správa nákupu](purchasing-manage-purchasing.md)  
  [Spravovat prodej](sales-manage-sales.md)

