---
title: "Vytváření karty zboží pro zboží a služby"
description: "Můžete vytvořit kartu zboží pro fyzické zboží nebo služby, které prodáváte v hodinách. Například, sestavení produktů, hotové zboží, komponenty a suroviny, které můžete prodávat ze skladu."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: item, finished good, component, raw material, assembly item
ms.date: 08/31/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f26207e07539da790a0ffab38a0fd2b732231300
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-register-new-items"></a>Návod: Registrovat nového zboží.
Výrobky jsou základem vašeho podnikání, zboží nebo služeb, se kterými obchodujete. Každé zboží musí být registrováno jako karta zboží.

Karty zboží obsahují informace, které jsou nutné k nákupu, skladování, prodeji, doručení a pro účet zboží.

Zboží může být strukturované jako nadřazená položka se základními podřazenými položkami v kusovníku. V [!INCLUDE[d365fin](includes/d365fin_md.md)] může být kusovník buď montážní kusovník nebo výrobní kusovník v závislosti na jeho použití. Další informace naleznete v tématu [Návod: Práce s kusovníky](inventory-how-work-BOMs.md)

> [!NOTE]  
>   Pokud existují šablony zboží pro různé typy zboží, objeví se okno při vytváření nové karty zboží, odkud můžete vybrat vhodnou šablonu. Pokud existuje pouze jedna šablona zboží, pak nové karty zboží používají vždy tuto šablonu.

Pokud zakoupíte stejné zboží od více než jednoho dodavatele, můžete ho přiřadit k dané kartě zboží. Dodavatelé se zobrazí v okně **Katalog zboží dodavatele**, takže můžete jednoduše vybrat alternativního dodavatele.

## <a name="to-create-a-new-item-card"></a>K vytvoření nové karty zboží
1. Na domovské stránce vyberte akci **Zboží** pro otevření seznamu existujícího zboží.  
2. V okně **Zboží** vyberte akci **Nový**.

    Pokud existuje pouze jedna šablona zboží, otevře se nová karta zboží s několika poli vyplněnými informacemi ze šablony.
3. V okně **Vybrat šablonu pro nové zboží** vyberte šablonu, kterou chcete použít pro novou kartu zboží.
4. Zvolte tlačítko **OK**. Otevře se nová karta zboží s některými poli vyplněnými informacemi ze šablony.
5. Postupujte podle potřeby tak, že vyplníte nebo změníte pole na kartě zboží. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]
> V poli **Metoda ocenění**, nastavíte jak bude zboží oceněno pomocí předpokladů o toku zboží ve vaší společnosti. Existuje pět způsobů ocenění, které se odvyjí na typu zboží. Další informace naleznete v tématu [Návrh detailů Metody ocenění](design-details-costing-methods.md)
>
> Pokud zvolíte **Průměrná cena** budou jednotkové náklady vypočítány jako průměr nákladů pro každý okamžik v čase po prodeji. Zásoby se oceňují za předpokladu, že jsou všechny zásoby prodávany současně. S tímto nastavením, můžete zvolit pole **Pořizovací cena** k zobrazení historie transkací odkud jsou vypočítány prlměrné náklady v okně** Přehled výpočtu průměrné pořizovací ceny**.

Na záložce s náhledem **Ceny a účtování** můžete zobrazit zvláštní ceny nebo slevy, které udělujete za dané zboží, pokud jsou splněna určitá kritéria, jako je zákazník, minimální objednávkové množství nebo datum ukončení. Každý řádek představuje speciální slevu nebo řádkovou slevu. Každý sloupec představuje kritérium, které musí platit, aby se zaručila speciální cena, kterou zadáte do pole **Jednotková cena**, nebo řádkovou slevu, kterou zadáte do pole **Řádková sleva**. Další informace naleznete v tématu: [Zaznamenání Prodejní ceny, slevy a platební podmínky](sales-how-record-sales-price-discount-payment-agreements.md).

Položka je nyní zaregistrována a karta zboží je připravena k použití v nákupních a prodejních dokladech.

Chcete-li tuto kartu zboží použít jako šablonu při vytváření nových karet zboží, můžete ji uložit jako šablonu. Pro více informací, sledujte následující sekci.

## <a name="to-save-the-item-card-as-a-template"></a>K uložení karty zboží jako šablony
1. V okně **Karta zboží**, vyberte akci **Uložit jako šablonu**. Okno **Šablona zboží** otevírá kartu zboží jako šablonu.
2. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]
3. K opětovnému použití dimenzí v šablonách zvolte tlačítko **Dimenze**. Okno **Šablony dimenzí** otevírá jakékoli kódy dimenzí, které jsou pro dané zboží nastaveny.
4. Upravte nebo zadejte kódy dimenzí, které se budou vztahovat na nové karty zboží vytvořené pomocí šablony.
5. Po dokončení nové šablony zboží vyberte tlačítko **OK**.

Šablona zboží je přidána do seznamu šablon zboží, takže ji můžete použít k vytvoření nových karet zboží.

## <a name="to-set-up-multiple-vendors-for-an-item"></a>Nastavení více dodavatelů pro zboží  
Pokud nakupuje zboží od více než jednoho dodavatele, musíte vložit informace ke každému z nich, jako jsou ceny, dodací lhůta, slevy a tak dále.  

1.  Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Zboží** a vyberte související odkaz.  
2.  Vyberte příslušný projekt a poté vyberte akci **Upravit**.  
3.  Zvolte akci **Dodavatelé**.  
4.  Vyberte pole **Číslo dodavatele** a zvolte dodavatele, kterého chcete nastavit pro dané zboží.  
5.  Volitelně vyplňte zbývající pole  
6.  Opakujte kroky 2 až 5 pro každého dodavatele, od kterého chcete nakupovat zboží.

Dodavatelé se zobrazí v okně **Katalog zboží dodavatele**, které se otevře z karty zboží a poté můžete jednoduše vybrat alternativního dodavatele.

## <a name="see-also"></a>Viz také
  [Sklady](inventory-manage-inventory.md)  
  [Nákup](purchasing-manage-purchasing.md)  
  [Prodej](sales-manage-sales.md)  
  [Práce s [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](ui-work-product.md)

##

