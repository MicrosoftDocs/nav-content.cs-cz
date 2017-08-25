---
title: "Návod: Odsouhlasení plateb pomocí automatického vyrovnání"
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
ms.openlocfilehash: bde263424bb8e5b60d2c9a139ddc8bfef0a90062
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-payments-using-automatic-application"></a>Návod: Odsouhlasení plateb pomocí automatického vyrovnání
Okno **Deník odsouhlasení plateb** specifikuje platby, příchozí i odchozí, které byly zaznamenány jako transakce na vašem online bankovním účtu a můžete vyrovnat jejich související otevřené zákazníky, dodavatele a položky knihy bankovního účtu. Řádky v deníku jsou vyplněny importováním bankovního výpisu jako bankovního zdroje nebo souboru.

Deník odsouhlasení plateb se týká jednoho bankovního účtu v Dynamics NAV, který odráží online bankovní účet, kde jsou zaznamenány platební transakce. Veškeré otevřené položky bankovního účtu, které se vztahují k položkám knih zákazníků nebo dodavatelů budou uzavřeny, když zvolíte akci **Účtování plateb a odsouhlasení bankovních účtů**. To znamená, že bankovní účet je automaticky odsouhlasen pro platby, které zaúčtujete do deníku.

Chcete-li importovat bankovní výpisy jako bankovní zdroje, musíte nejprve povolit službu Envestnet Yodlee Bank Feeds a poté propojit bankovní účet s jeho souvisejícím online bankovním účtem. Deník odsouhlasení plateb pak automaticky detekuje bankovní kanály, když zvolíte akci **Import bankovních transakcí**. Kromě toho můžete nastavit bankovní účet až po automatické importování nových zdrojů výpisů z banky každou hodinu. Transakce pro platby, které již byly zaúčtovány jako vyrovnané a/nebo odsouhlasené nebudou importovány. Další informace naleznete v tématu [Návod: ](bank-how-setup-bank-statement-service.md)Nastavení služby Envestnet Yodlee Bank.

**Poznámka**: Služba Envestnet Yodlee Bank Feeds nebo jiná služba bankovního doručovatele nemusí být ve vašem systému k dispozici. Obraťte se na svého partnera Microsoft, chcete-li pro import bankovních výpisů použít bankovní službu.

Pomocí akce **Mapovat text na účet** můžete nastavit mapování mezi textem plateb a konkrétními MD, Dal a zůstatkovými účty tak, aby byly tyto platby zaúčtovány do uvedených účtů, když jste zaúčtovali deník odsouhlasení plateb. Viz krok 9. Další informace naleznete v tématu [Návod: Mapovat text periodických plateb na účtech pro automatické odsouhlasení](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md).

Podobné funkce existují k tomu, aby se odsouhlasily přebytečné částky na řádcích deníku odsouhlasení plateb v základním ad-hoc. Další informace naleznete v tématu [Návod: Odsouhlasení plateb, které nelze vyrovnat.](receivables-how-reconcile-payments-cannot-apply-auto.md)

Použijete funkci **Automatické vyrovnání** a to buď automaticky při importu bankovního souboru nebo zdroje s platebními transakcemi nebo při jeho aktivaci k vyrovnání plateb na jejich souvisejících otevřených položkách na základě shody dat na řádku deníku s daty v jedné nebo více otevřených položkách.

Na řádcích deníku, kde byla platba automaticky vyrovnána na jednu nebo více otevřených položek, má pole **Spolehlivost shody** hodnotu mezi Nízká a Vysoká, která označuje kvalitu shody dat, na které je založena navrhovaná vyrovnávací platba. Navíc pole **Typ účtu** a **Číslo účtu** obsahuje informace o zákazníkovi nebo dodavateli, u kterých je platba vyrovnána. Pokud jste nastavili textové mapování účtů, automatické vyrovnání může mít za následek spolehlivost shody **Vysoká - Textové mapování účtů**.

Pro každý řádek deníku v okně **Deník odsouhlasení plateb** můžete otevřít okno **Vyrovnání plateb**, abyste viděli všechny kandidáty otevřených položek pro platbu a detailní pohled na informace pro každou položku o shodě dat, na kterou je vyrovnání plateb založeno. Zde můžete ručně použít vyrovnání plateb nebo znovu vyrovnat platby, které byly automaticky vyrovnány na nesprávnou položku. Další informace naleznete v tématu [Návod: Pohled nebo vyrovnání plateb po automatickém vyrovnání](receivables-how-review-apply-payments-auto-application.md).

**Poznámka**: Můžete zahájit import bankovních transakcí současně s otevřením okna **Deník odsouhlasení plateb** pro existující deník odsouhlasení plateb v okně **Deník odsouhlasení plateb**. Následující postup popisuje, jak lze importovat bankovní transakce do okna **Deník odsouhlasení plateb** poté, co jste vytvořili nový deník.

## <a name="to-reconcile-payments-using-automatic-application"></a>Odsouhlasení plateb pomocí automatického vyrovnání
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky odsouhlasení plateb** a pak vyberte související odkaz.
2. Chcete-li pracovat v novém deníku odsouhlasení plateb, zvolte akci **Nový deník**.
3. V okně **Seznam plateb bankovních účtů** vyberte bankovní účet, pro který chcete odsouhlasit platby a potom klepněte na tlačítko **OK**.
Okno **Deníky odsouhlasení plateb** se otevře pro vybraný bankovní účet.
4. Zvolte akci **Import bankovních transakcí**.
Pokud bankovní účet pro vybraný deník není nastaven pro import bankovních transakcí, otevře se dialogové okno, které vám pomůže vyplnit příslušná pole.
5. V okně **Vybrat soubor k importu** vyberte soubor, který obsahuje bankovní transakce pro platby, které chcete odsouhlasit a poté zvolte tlačítko **Otevřít**.  
6. Je-li služba bankovního výpisu povolena v okně **Filtr bankovních výpisů**, které se automaticky otevře, zadejte interval dat pro importování bankovních výpisů.

    Okno **Deníky odsouhlasení plateb** je vyplněno řádky pro platby představující bankovní transakce v importovaném bankovním výpisu.

    Na řádcích plateb, které byly automaticky vyrovnány na jejich související otevřené položky, má pole **Spolehlivost shody** hodnotu mezi **Nízká** a **Vysoká**, které označuje kvalitu shody dat, na které je založeno navrhované vyrovnání plateb. Navíc pole **Typ účtu** a **Číslo účtu** obsahuje informace o zákazníkovi nebo dodavateli, u kterých je platba vyrovnána.
7. Vyberte řádek deníku a potom zvolte akci **Ruční vyrovnání** k pohledu, znovu vyrovnání nebo vyrovnání platby ručně v okně **Vyrovnání plateb**. Další informace naleznete v tématu [Návod: Pohled nebo vyrovnání plateb po automatickém vyrovnání](receivables-how-review-apply-payments-auto-application.md).

    Po dokončení ručního vyrovnání pole **Spolehlivost shody** na řádku deníku, který jste zpracovali ručně obsahuje **Přijato**.
8. Vyberte nevyrovnaný řádek deníku pro opakující se příjem nebo výdajů hotovosti, jako je nákup automobilového benzínu a poté na kartě Domů ve skupině Pohled zvolte Mapovat text na účet. Další informace naleznete v tématu [Návod: Mapovat text periodických plateb na účtech pro automatické odsouhlasení](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md)
9. Jakmile dokončíte mapování textu platby na účty, zvolte akci **Vyrovnat ručně**.
10. Pokud jste spokojeni s tím, že všechny platby na řádcích deníku jsou správně vyrovnány nebo nastaveny na přímé zaúčtování, zvolte akci **Účtovat**.

Při zaúčtování deníku odsouhlasení plateb se uzavřou vyrovnané otevřené položky a související zákazník, dodavatel nebo účty hlavní knihy jsou aktualizovány. Pro platby na řádcích deníku založeném na textovém mapování účtů, se specifický zákazník, dodavatel a účty hlavní knihy aktualizují. Pro všechny řádky deníku jsou vytvořeny položky knihy bankovního účtu. Pokud zvolíte akci **Účtování plateb a odsouhlasení bankovních účtů**, budou uzavřeny všechny otevřené položky knihy bankovního účtu související s vyrovnáním položek knihy zákazníka nebo dodavatele. To znamená, že bankovní účet je automaticky odsouhlasen pro platby, které zaúčtujete do deníku.

Můžete porovnat hodnotu v poli **Zůstatek na bankovním účtu po zaúčtování** spolu s hodnotou v poli **Zůstatek konečného výpisu** pro sledování, když bankovní účet je odsouhlasen na základě platby, kterou zaúčtujete.

**Poznámka**: Pokud nechcete odsouhlasit bankovní účet z okna **Deníky odsouhlasení plateb**, musíte použít okno **Odsouhlasení bank. účtu**. Další informace naleznete v tématu [Odsouhlasení bankovních účtů zvlášť](bank-how-reconcile-bank-accounts-separately.md).

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Správa prodeje](sales-manage-sales.md)

