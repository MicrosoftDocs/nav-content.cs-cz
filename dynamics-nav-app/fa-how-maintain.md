---
title: "Návod: Údržba DM"
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
ms.openlocfilehash: 58077a38433a73b981a6f3d05ce7ed106acf32f4
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-maintain-fixed-assets"></a>Návod: Údržba DM
Náklady na údržbu jsou rutinní pravidelné náklady na zachování hodnoty DM. Na rozdíl od kapitálu nezvyšují hodnotu.

Můžete si zaznamenat a udržovat aktualizovaný soubor o údržbě a servisu svého DM, abyste měli k dispozici kompletní záznamy o údržbě DM, které jsou snadno dostupné. Pokaždé, když je dlouhodobý majetek poslán do servisu, zaznamenáváte všechny relevantní informace, jako je datum servisu, číslo prodejce a telefonní číslo servisního agenta. Registrace údržby se zaznamenává pro každý dlouhodobý majetek z příslušné karty DM.

Odsazení slouží k úpravě hodnot pro obecné změny cenové hladiny. Dávková úloha **Indexovat DM** může být použita k vypočítání nákladů na údržbu.

## <a name="to-record-maintenance-work-on-a-fixed-asset"></a>Záznam prací k údržbě DM  
Pokaždé, když byla provedena údržba, například návštěva servisu, můžete ji zaznamenat pro příslušný dlouhodobý majetek v okně **Registrace údržby**.  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.  
2. Vyberte dlouhodobý majetek, u kterého chcete zobrazit údržbu a pak vyberte akci **Registrace údržby**.
3. V okně **Registrace údržby** vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.  

## <a name="to-post-maintenance-costs-from-a-fixed-asset-gl-journal"></a>Zaúčtování nákladů na údržbu z finančního deníku DM
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Seznam odpisových knih** a pak vyberte související odkaz.  
2. Vyberte odpisovou knihu, kde chcete zobrazit dlouhodobý majetek a poté vyberte akci **Upravit**.
3. V okně **Karta odpisové knihy** zkontrolujte, zda není zaškrtnuto políčko **Údržba**. Tím je zajištěno, že náklady na údržbu nejsou zaúčtovány do hlavní knihy.
4. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Finanční deník** a pak vyberte související odkaz.  
5. Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby.
6. Do pole **Typ zaúčtování DM** vyberte **Údržba**.
7. Zvolte **Vložit DM Bal. Akce Účet**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování údržby.

    **Poznámka**: Krok 7 funguje pouze v případě, že jste nastavili následující: V okně **Karta skupiny zaúčtování DM** pro zaúčtovací skupinu DM pole **Účet údržby** obsahuje účet MD v hlavní knize a **Údržba Bal. pole Účet** obsahuje účet hlavní knihy, na který chcete zaúčtovat zůstatkové položky za účelem zhodnocení. Další informace naleznete v části "Nastavení skupin zaúčtování DM“[Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).
8. Zvolte akci **Zaúčtovat**.

## <a name="to-follow-up-on-fixed-assets-service-visits"></a>Pokračování servisu na dlouhodobém majetku
Můžete vytisknout hlášení **Údržba - další servis**, abyste zjistili, který majetek jste pro službu použili. Tento přehled můžete také použít při aktualizaci pole **Následující servisní datum** na kartách DM.  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Další servisní údržba** a pak vyberte související odkaz.  
2. Vyplňte pole **Počáteční datum** a **Datum ukončení**.  
3. Zvolte tlačítko **Tisk** nebo **Náhled**.

## <a name="to-monitor-maintenance-costs"></a>Monitorování nákladů na údržbu  
Náklady na údržbu můžete zobrazit, když se podíváte na statistiky DM.  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, u kterého chcete zobrazit náklady na údržbu a pak vyberte akci **Odpisové knihy**.
3. V okně **Odpisové knihy DM** vyberte příslušnou odpisovou knihu DM a poté zvolte akci **Statistiky** .
4. V okně **Statistiky DM** vyberte pole **Údržba** .

Okno **Údržba položek knihy** zobrazuje položky, které tvoří částku v poli **Údržba**.

## <a name="to-view-or-print-maintenance-costs-for-multiple-fixed-assets"></a>Zobrazení nebo tisk nákladů na údržbu více DM  
Ve zprávě **Údržba - analýza** můžete zvolit, zda chcete zobrazit údržbu na základě jednoho, dvou nebo tří kódů údržby pro zadané datum nebo období. Můžete vidět součet všech vybraných majetků nebo celkový součet každého majetku.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Analýza údržby** a pak vyberte související odkaz.
2. Vyplňte pole podle potřeby.
3. Zvolte tlačítko **Tisk** nebo **Náhled**.

## <a name="to-view-maintenance-ledger-entries"></a>Zobrazení položek údržby
Náklady na údržbu si můžete prohlédnout také prostřednictvím prohlížení položek údržby.  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, u kterého chcete zobrazit položky a pak vyberte akci **Odpisové knihy**.
3. V okně **Odpisové knihy DM** vyberte příslušnou odpisovou knihu DM a poté zvolte akci **Údržba položek**.

## <a name="to-view-or-print-maintenance-ledger-entries-for-multiple-fixed-assets"></a>Zobrazení nebo tisk položek údržby pro více DM  
V přehledu **Údržba - podrobnosti** můžete zobrazit nebo vytisknout položky o údržbě jednoho nebo více DM.  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Podrobnosti údržby** a pak vyberte související odkaz.
2. Vyplňte pole podle potřeby.
3. Zvolte tlačítko **Tisk** nebo **Náhled**.

## <a name="see-also"></a>Viz také
[Správa DM](fa-manage.md)  
[Nastavení DM](fa-setup.md)  
[Finance](finance-setup.md)  
[Vítejte v Dynamics NAV](across-get-started.md)
