---
title: "Návod: Proces prodejní vratky nebo zrušení."
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
ms.openlocfilehash: 92b65379f2ec633712a2b2c0f06615c6de61cc6e
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-process-sales-returns-or-cancellations"></a>Návod: Proces prodejní vratky nebo zrušení.
Pokud Váš zákazník chce vrátit nebo získat náhradu za zboží a služby, které jste mu prodali a obdrželi jste platu, musíte vytvořit a zaúčtovat prodejní dobropis, který specifikuje požadovanou změnu. Chcete-li zahrnou správné informace z prodejních faktur, můžete vytvořit prodejní dobropis z účtovaných prodejních faktur nebo použít funkci kopírování.

Kromě původní účtované prodejní faktury, můžete použít prodejní dobropis na prodejní dokumenty, například: na jinou účtovanou prodejní fakturu, protože zákazník také vrací položky dodané s touto fakturou.

Vrácení nebo refundace se mohou týkat pouze některého zboží nebo služeb na původní prodejní faktuře. V takovém případě musíte upravit údaje na řádcích v prodejním dobropisu. Když zaúčtujete prodejní dobropis, prodejní doklady, které jsou touto změnou ovlivněny, jsou zrušeny a pro zákazníka může být vytvořena platba na vrácení peněz.

Můžete zákazníkovi odeslat účtovaný prodejní dobropis za účelem potvrzení vrácení nebo zrušení a sdělit mu, že příslušná částka bude uhrazena. Například za zboží, které vrátil.

## <a name="to-create-a-sales-credit-memo-from-a-posted-sales-invoice"></a>Vytvoření prodejního dobropisu z účtované prodejní faktury.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účtované prodejní faktury** a poté vyberte příslušný odkaz.  
2. V okně **Účtované prodejní faktury** vyberte účtovanou fakturu, kterou chcete vrátit a vyberte tlačítko **Vytvořit opravný dobropis**.

    Většina políček v hlavičce prodejního dobropisu bude naplněna údaji z účetované prodejní faktury. Můžete editovat všechny políčka, například nové informace reflektující na vrácení.
3. Upravte informace na řádcích vzhledem k dohodě, jako je počet položek vráceného zboží nebo částku jaká má být vrácena.
4. Vyberte tlačítko **Vyrovnat položky**.
5. V okně **Vyrovnat položky zákazníka** vyberte řádky s účtovanými dokumenty, které chcete použít na prodejní dobropis a poté zvolte **ID vyrovnání**.

    Číslo prodejního dobropisu je vloženo do políčka **ID vyrovnání**.  
6. V poli **Částka k vyrovnání** vložte částku, kterou chce vyrovnat pokud je menší než původní částka.

    V dolní části okna **Vyrovnat položky zákazníka** můžete vidět celkový součet k částky k vyrovnání všech položek, jmenovitě, pokud políčko **Zůstatek** je nulové.  
7. Zvolte tlačítko **OK**. Pokud účtujete prodejní dobropis, bude se vztahovat na specifické účtované prodejní dokumenty.

    Pokud jste vytvořili nebo upravili potřebné řádky prodejního dobropisu a jsou určena jednoduchá nebo násobná vyrovnání, můžete pokračovat v procesu účtování prodejního dobropisu.
8. Vyberte tlačítko **Účtovat a Odeslat**.

Zobrazí se dialogové okno **Potvrzení účtování a odeslání** s uvedením preferovaného způsobu odeslání zákazníkovi. Způsob odesílání můžete změnit výběrem vyhledávacího tlačítka pro pole **Odeslat dokument do**. Další informace naleznete v tématu [Návod: Nastavení Profilů odesílání dokumentů](sales-how-setup-document-send-profiles.md).

Účtované prodejní dokumenty, na které jste vytvořili prodejní dobropis jsou nyní stronovány a platba vrácení peněž může být vytvořena. Prodejní dobropis je smazán a nahrazen novým dokumentem v seznamu účtovaných prodejních dobropisů.

## <a name="to-create-a-sales-credit-memo-from-scratch"></a>Vytvoření prodejního dobropisu od začátku.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Prodejní dobropisy** a poté vyberte příslušný odkaz.
2. Zvolte tlačíko **Nový** k otevření prázdného prodejního dobropisu.
3. V políčku **Zákazník** napište jméno existujícího zákazníka.
4. Vyberte tlačíko **Kopírovat doklad..l**.
5. V okně **Kopie prodejního dokladu** v poli **Typ dokladu** vyberte **Účtované faktury**.
6. Vyberte políčko **Číslo dokladu**  o otevření okna **Účtované prodejní faktury** a vyberte fakturu, obsahující řádky které chce vrátit.
7. Zaškrtněte políčko **Přepočítat řádky** pokud chce, aby řádky účtované prodejní faktury byly aktualizovány s jakoukoli změnou ceny položky a jednotkovými náklady od účtování faktury.
8. Zvolte tlačítko **OK**. Zkopírované řádky faktury jsou vloženy do prodejního dobropisu.
9. Dokončete dobropis, tak jak je vysvětleno v „Vytvoření prodejního dobropisu z účtované prodejní faktury“.

## <a name="see-also"></a>Viz také  
[Správa prodeje](sales-manage-sales.md)  
[Nastavení prodeje](sales-setup-sales.md)  
[Návod: Posílání dokumentů pomocí Emailu.](ui-how-send-documents-email.md)  
[Práce s Dynamics NAV](ui-work-product.md)

