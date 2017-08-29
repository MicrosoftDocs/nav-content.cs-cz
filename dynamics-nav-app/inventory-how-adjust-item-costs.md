---
title: "Návod: Upravení nákladů položky"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 59db38c159dd2810656edc668ee431c6414b9d90
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-adjust-item-costs"></a>Návod: Upravení nákladů položky   
Náklady na položku (hodnotu zásob), kterou si koupíte a později prodáváte, se mohou během své životnosti měnit, například proto, že náklady na dopravu jsou po prodeji položky přidány k nákupním nákladům. Aby byla vždy známá správná hodnota skladu, je třeba pravidelně upravovat náklady na položky.
To zajišťuje, že statistiky prodeje a zisku jsou aktuální a že finanční ukazatele KPI jsou správné.

**Poznámka**: Náklady na položky jsou upraveny pouze metodou FIFO. To znamená, že jednotková cena položky je skutečná hodnota každého přijetí položky a skladové položky se oceňují za předpokladu, že první položky zařazené do zásob jsou prodány jako první.

Funkce úpravy nákladů zpracovává pouze hodnoty, které ještě nebyly upraveny. Pokud se funkce setká se situací, kdy je třeba přenést změněné příchozí náklady do přidružených odchozích položek, vytvoří se nové upravené položky, které jsou založeny na informacích v položkách původní hodnoty, ale obsahují upravenou částku. Funkce úpravy nákladů používá datum zaúčtování položky původní hodnoty do upravené položky, pokud se toto datum nenachází v uzavřeném období zásob. V takovém případě program používá datum zahájení dalšího otevřeného období zásob. Pokud se nepoužije doba zásob, pak bude definováno v poli **Povolit účto od** v okně **Nastavení Financí**, kdy bude zaúčtována upravená položka.

**Poznámka**: Po úpravě nákladů na položku musí být náklady na zásoby účtovány do hlavní knihy buď automaticky, nebo ručně. Další informace naleznete v tématu [Návod: Zaúčtování nákladů na zásoby do hlavní knihy](inventory-how-post-inventory-cost-gl.md).

Náklady na položky lze upravit dvěma způsoby:
 - Automaticky tím, že systém bude upravovat jakékoli změny nákladů pokaždé, když dojde k transakcím se zásobami.
 - Ručně spuštěním dávkové úlohy **Upravit náklady/ceny zboží** pro jednu nebo více položek, pokud víte, že se jejich náklady změnily.  

## <a name="to-adjust-item-costs-automatically"></a>Automatické upravení nákladů položky
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení zásob** a zvolte související odkaz.
2. V okně **Nastavení zásob** v poli **Automatická adjustace nákladů** vyberte jednu z následujících hodnot.

|Volba |Chování |
|-------|---------|
|Nikdy|Při odesílání se náklady neupravují|
|Den|Náklady jsou upraveny, pokud dojde k zaúčtování v rozmezí jednoho dne od pracovního data.|
|Týden|Náklady jsou upraveny, pokud dojde k zaúčtování v rozmezí jednoho týdne od pracovního data.|
|Měsíc|Náklady jsou upraveny, pokud dojde k zaúčtování v rozmezí jednoho měsíce od pracovního data.|
|Čtvrtletí|Náklady jsou upraveny, pokud dojde k zaúčtování v rozmezí jednoho čtvrtletí od pracovního data.|
|Rok|Náklady jsou upraveny, pokud dojde k zaúčtování v rozmezí jednoho roku od pracovního data.|
|Vždy|Náklady jsou vždy přizpůsobeny při účtování bez ohledu na datum účtování|

## <a name="to-adjust-item-costs-manually"></a>Ruční úpravy položek
1. V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Upravit náklady/ceny zboží** a pak zvolte související odkaz.
2. V okně **Upravit náklady/ceny zboží** zadejte, které položky upravují náklady a zda budou upravené náklady účtovány do hlavní knihy současně.

## <a name="see-also"></a>Viz také
[Správa skladů](inventory-manage-inventory.md)  
[Návod: Zaúčtování nákladů na zásoby do hlavní knihy.](inventory-how-post-inventory-cost-gl.md)  
[Správa prodeje](sales-manage-sales.md)  
[Správa nákupu](purchasing-manage-purchasing.md)

