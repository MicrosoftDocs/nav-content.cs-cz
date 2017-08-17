---
title: "Zpracování prodejních příležitostí"
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
ms.openlocfilehash: 00f316dd3032d41239a75c0f40e6db6dc54601fe
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---
# <a name="processing-sales-opportunities"></a>Zpracování prodejních příležitostí
Po vytvoření příležitosti existuje několik funkcí pro správu příležitostí a přesunutí k dokončení.

## <a name="view-opportunities"></a>Zobrazit příležitosti
Existující prodejní příležitosti jsou k dispozici v okně **Seznam příležitostí**. Existují různé způsoby přístupu k tomuto oknu pro zpracování prodejních příležitostí:

|Chcete-li zobrazit příležitosti pro |Pak |
|--------------------------|-----|
|Všichni prodejci a kontakty|V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Seznam příležitostí**, a pak vyberte související odkaz.|
|Konkrétní prodejce|V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Prodejci** a zvolte související odkaz. Vyberte prodejce, vyberte možnost **Příležitosti** a vyberte akci **Seznam**.|
|Konkrétní kontakt|V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Kontakty** a zvolte související odkaz. Vyberte kontakt ze seznamu a pak zvolte akci **Příležitosti**.|

Každá z těchto úloh otevře okno **Seznam příležitostí** 

## <a name="close-opportunities"></a>Zavřít příležitosti
Můžete ukončit příležitosti, až jednání skončí. Při uzavření příležitosti můžete určit, zda byla získána nebo ztracena, a důvody jejího uzavření. Chcete-li určit důvod, musíte nastavit uzavřené kódy příležitostí.

1. V okně **Seznam příležitostí** vyberte příležitost a vyberte akci **Zavřít**. Otevře se okno **Zavřít příležitost**.
2. Vyplňte odpovídající pole a poté klepněte na tlačítko **OK**.

  Pole **Zavřít kód příležitosti** a **Datum uzavření** jsou povinná pole a musí být vyplněna předtím, než můžete zvolit tlačítko **OK**.

  V poli **Zavřít kód příležitosti** můžete vybrat jeden z existujících kódů uzavření příležitostí nebo přidat nový kód. Chcete-li přidat nový kód, vyberte v rozevíracím seznamu možnost **Vybrat z úplného seznamu** a poté vyberte **Nové**. Na novém prázdném řádku vyplňte pole **Kód**, **Typ** a **Popis** a potom klepněte na tlačítko **OK**.

## <a name="create-quotes-for-opportunities"></a>Vytvořte nabídky příležitostí
Můžete vytvořit prodejní nabídky pro kontakty, které nejsou zaznamenány jako zákazníci.

1. V okně **Seznam příležitostí** vyberte příležitost a pak vyberte akci **Přiřadit prodejní navídku**. Zobrazí se okno **Prodejní nabídka**.
2. Vyplňte příslušná pole.

## <a name="create-sales-orders-for-opportunities"></a>Vytvořte prodejní objednávky pro příležitosti
Prodejní objednávky můžete učinit z prodejních nabídek, které jste vytvořili pro své příležitosti. Než vytvoříte prodejní objednávky pro vaše kontakty, musíte vytvořit kontakt jako zákazníka. Další informace naleznete v [Vytvořit zákazníka, dodavatele nebo bankovní účet z kontaktu](marketing-how-create-contacts-new-customers-vendors-bank-accounts.md).

1. V okně **Seznam příležitostí** najděte příležitost, pro kterou jste vytvořili prodejní nabídku.
2. Zvolte akci přiřadit prodejní nabídku. Zobrazí se okno **Prodejní nabídka**, aby se zobrazila prodejní nabídka, kterou jste přiřadili příležitosti.
3. Vyplňte odpovídající pole a poté klepněte na tlačítko **Objednat**.

Při vyřizování prodejních příležitostí možná budete muset vytvořit nabídku pro kontakt, ke kterému je příležitost propojena.

## <a name="delete-opportunities"></a>Odstranit příležitosti
Příležitosti můžete odstranit například po uzavření smlouvy. Můžete však odstranit pouze uzavřené příležitosti. Existují dva způsoby odstranění uzavřených příležitostí. Můžete odstranit jednotlivé uzavřené příležitosti z okna **Seznam příležitostí** nebo můžete spustit dávkovou úlohu **Odstranit uzavřené příležitosti** a odstranit několik příležitostí na základě zadaných kritérií.

Chcete-li odstranit uzavřené příležitosti z okna **Seznam příležitostí**, vyberte příležitost a vyberte akci **Odstranit** 

Chcete-li odstranit uzavřené příležitosti pomocí dávkové úlohy **Odstranit uzavřené příležitosti**, postupujte takto:

1. V pravém horním rohu vyberte ikonu **Hledat stránku nebo sestavu**, zadejte **Odstranit příležitosti**, a pak vyberte související odkaz.
2. V části **Příležitost** nastavte filtry, které určují uzavřené příležitosti k odstranění.
3. Zvolte tlačítko **OK**.

Po odstranění příležitosti jej odstraníte z okna **Seznam příležitostí**.

## <a name="move-an-opportunity-through-sales-cycle-stages"></a>Přeneste příležitost fází prodejních cyklů
Pokud příležitost navazuje na prodejní cyklus, můžete je přesunout dopředu nebo zpět v různých fázích, jako je posunutí další nebo předchozí fáze a dokonce přeskočení fáze.

1. V okně **Seznam příležitostí** zvolte akci **Aktualizovat**. Otevře se možnost **Aktualizovat příležitost**,
2. Použijte pole **Typ akce** k přesunutí příležitosti prostřednictvím fází prodejního cyklu:
  * **Další** posouvá příležitost dopředu o jednu fázi.
  * **Přeskočit** posouvá příležitost dopředu o jednu či několik fází v jednom prodejním cyklu, který specifikujete v poli **Prezentace**. Můžete přeskočit pouze fáze, které byly nastaveny, aby je bylo možné přeskočit.
  * **Předchozí** posouvá příležitost o jednu fázi zpět.
  * **Skočit** přenese příležitost zpět o jednu nebo více fází v prodejním cyklu, který jste zadali v poli **Prezentace**.
  * **Aktualizovat** vám umožňuje měnit informace (například měnit hodnocení svých šancí na úspěch a odhadované hodnoty) bez přesunu do další fáze.
3. Vyplňte ostatní pole a poté klepněte na tlačítko **OK**.

##<a name="see-also"></a>Viz také  
[Správa prodeje](sales-manage-sales.md)  
[Vytvořit a spravovat kontakty](marketing-contacts.md)  
[Pracujte s Dynamics NAV](ui-work-product.md)

