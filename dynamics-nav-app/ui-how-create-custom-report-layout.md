---
title: "Vytvoření a úprava vlastních rozložení pro sestavy a doklady"
description: "Přečtěte si, jak vytvořit vlastní přizpůsobené rozložení pro přizpůsobení vzhledu sestavy při jejím prohlížení, tisku nebo uložení."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customized report, document layout, logo, personalize
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: ee614c44a17873591916bc97bd9b2a3f33fce21b
ms.contentlocale: cs-cz
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-create-and-modify-a-custom-report-or-document-layout"></a>Návod: Vytvoření vlastního rozvržení sestavy.
Ve výchozím nastavení bude mít sestava vestavěný rozvrh sestav, který může být RDLC, rozvržení sestavy aplikace Word nebo obojí. Nemůžete editovat vestavěné sestavy. Můžete však vytvořit vlastní rozvržení, které vám umožní změnit vzhled sestavy při jejím náhledu, tisku nebo uložení. Pro sestavu můžete vytvořit více rozvržení sestav a podle potřeby přepnout rozvržení, které sestava používá.

> [!NOTE]  
>   V [!INCLUDE[d365fin](includes/d365fin_md.md)] termín "sestava" se také zahrnuje doklady, které jsou na vnější straně, jako jsou prodejní faktury a potvrzení objednávek, které posíláte zákazníkům jako soubory PDF.

Chcete-li vytvořit vlastní rozvržení, můžete buď vytvořit kopii stávajícího vlastního rozvržení, nebo přidat nové vlastní rozvržení, které je ve většině případů založeno na vestavěném rozvržení. Když přidáte nové vlastní rozvržení, můžete přidat typ rozvržení sestavy RDLC, typ rozvržení sestavy aplikace Word nebo obojí. Nové vlastní rozvržení bude automaticky založeno na vestavěném, pokud je k dispozici. Není-li pro daný typ vestavěné rozvržení, vytvoří se nové prázdné rozvržení, které budete muset modifikovat a navrhnout od začátku. Další informace o rozvržení RDLC a Wordových sestav, vestavěných, vlastních rozvržení a dalších naleznete v tématu [Správa rozvržení sestav](ui-manage-report-layouts.md).  

## <a name="to-create-a-custom-layout"></a>Vytvoření vlastního rozvržení
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Výběr rozvržení sestavy** a pak vyberte související odkaz.  

    Okno **Výběr rozvržení sestav** obsahuje seznam všech sestav, které jsou k dispozici ve **Společnosti**, která je uvedena v poli Společnost v horní části okna.
2. Nastavte pole **Název společnosti**, ve které chcete vytvořit rozvržení sestavy.
3. Vyberte řádek se sestavou, pro kterou chcete vytvořit rozvržení, a poté zvolte akci **Vlastní rozložení**.  
   Zobrazí se okno **Vlastní rozvržení sestav** a zobrazí seznam všech vlastních rozvržení, které jsou k dispozici pro vybraný přehled.
4. Chcete-li vytvořit kopii existujícího vlastního rozvržení, vyberte existující vlastní rozložení v seznamu a zvolte akci **Kopírovat**.  
   Kopie vlastního rozvržení se zobrazí v okně **Vlastní rozvržení sestav** a v poli **Popis** obsahuje *Kopii* slova.
5. Pokud chcete přidat nové vlastní rozvržení založené na vestavěném rozvržení, postupujte takto:  
   1. Vyberte akci **Nový**. Objeví se okno **Vložit rozvržení sestav**, **ID** a **Název** se vyplní automaticky.
   2. Chcete-li přidat vlastní formát rozvržení sestavy z aplikace Word, vyberte zaškrtávací políčko **Vložit rozvržení Wordu**.
   3. Chcete-li přidat vlastní formát rozvržení sestavy z aplikace RDLC, vyberte zaškrtávací políčko **Vložit RDLC rozvržení**.
   4. Zvolte tlačítko **OK**.  
      Nové vlastní rozvržení se zobrazí v okně **Vlastní rozvržení sestav**. Pokud je nové rozvržení založeno na vestavěném rozvržení, má v poli **Popis** slova **Kopie vestavěného rozvržení**. Pokud pro sestavu neexistuje žádné vestavěné rozvržení, nové rozložení má v poli **Popis** výraz **Nové rozvržení**, což znamená, že vlastní rozvržení je prázdné.
6. Ve výchozím nastavení je pole **Název společnosti** prázdné, což znamená, že vlastní sestava bude k dispozici ve všech společnostech. Chcete-li vytvořit vlastní uspořádání pouze v konkrétní společnosti, zvolte možnost **Upravit** a poté pole **Název společnosti** k nastavení na požadované společnosti.

Vlastní rozložení bylo vytvořeno. Nyní můžete upravovat Vlastní rozložení podle potřeby.

## <a name="ModifyCustomLayout"></a>Úprava vlastního rozložení
Chcete-li upravit rozložení sestavy, musíte nejprve exportovat rozložení sestavy jako soubor do umístění v počítači nebo síti a poté otevřít exportovaný dokument a provést změny. Po dokončení změn importujete rozvržení sestavy.

### <a name="to-modify-a-custom-layout"></a>Úprava vlastního rozložení
1.  Exportujete vlastní rozložení z okna **Vlastní sestavy**. Pokud toto okno již není otevřené, vyhledejte a otevřete okno **Výběr rozložení sestavy**, vyberte sestavu, která má rozložení, kterou chcete upravit, a poté vyberte akci **Vlastní rozložení**.  
2.  V okně **Rozložení uživatelských sestav** vyberte rozložení, které chcete upravit, zvolte akci **Exportovat rozložení** a potom vyberte možnost **Uložit** nebo **Uložit jako** a uložte dokument rozložení sestavy do umístění v počítači nebo síti.  

3.  Otevřete dokument rozložení sestavy, který jste právě uložili, a pak proveďte změny.

      Pokud měníte rozložení aplikace Word, otevřete dokument rozložení v aplikaci Word. Podrobnosti o úpravách naleznete v další části [Vytváření změn rozložení sestavy](ui-how-create-custom-report-layout.md#MakeChangesToLayout).

      Návrh rozložení RDLC je mnohem pokročilejší než rozvržení aplikace Word. Další informace o úpravě rozložení sestavy RDLC naleznete v tématu [Návrh rozložení výkazu RDLC](https://msdn.microsoft.com/en-us/dynamics-nav/designing-rdlc-report-layouts).

      Nezapomeňte uložit změny po dokončení.

4.  Vraťte se do okna **Vlastní rozložení sestavy,** vyberte rozložení sestavy, které jste exportovali a upravili, a pak zvolte akci **Importovat rozložení**.  

5. V dialogovém okně **Import** vyberte možnost **Vybrat**, chcete-li vyhledat a vybrat dokument rozložení sestavy, a poté zvolte **Otevřít**.

##  <a name="MakeChangesToLayout"></a> Změna rozložení sestavy aplikace Word  
Chcete-li provést obecné změny formátování a rozložení, jako je změna písma, přidávání a úprava tabulky nebo odebrání datového pole, stačí použít základní funkce úprav aplikace Word stejně jako u všech dokumentů aplikace Word.

Pokud navrhujete rozložení sestavy aplikace Word od začátku nebo přidáte nové datová pole, začněte přidáním tabulky, která obsahuje řádky a sloupce, které budou eventuelně držet datová pole.

> [!TIP]  
>  Zobrazte mřížky tabulky, abyste viděli hranice buněk tabulky. Nezapomeňte skrýt mřížky po dokončení úprav. Chcete-li zobrazit nebo skrýt mřížky tabulky, vyberte tabulku a v části **Rozložení** na kartě **Tabulka** vyberte možnost **Zobrazit mřížky**.  

###  <a name="RemoveField"></a> Odebrání popisků a datových polí v rozložení aplikace Word  
 Popisek a datová pole sestavy jsou obsaženy v ovládacích prvcích obsahu v aplikaci Word. Následující figura znázorňuje ovládací prvek obsahu, pokud je vybrán v dokumentu aplikace Word.  

 ![Kontrola obsahu pro pole v rozložení sestavy aplikace Word](media/nav_wordreportlayouts_contentcontrol.png "NAV_WordReportLayouts_ContentControl")  

 Název názvu popisku nebo datového pole se zobrazí v ovládacím prvku obsahu. V příkladu jméno pole je CompanyAddr1.  

### <a name="to-remove-a-label-or-data-field"></a>Pro odstranění popisku nebo datového pole  

1.  Pravým tlačítkem vyberte pole, které chcete odstranit, a poté zvolte možnost **Odebrat ovládací prvek obsahu**.  

     Ovládací prvek obsahu je odebrán, ale název pole zůstává jako text.  

2.  Odstraňte zbývající text podle potřeby.  

### <a name="adding-data-fields"></a>Přidání datových polí
Přidávání datových polí z datové sady sestav je pokročilejší a vyžaduje určité znalosti datového souboru sestav. Informace o přidávání polí pro data, popisky a obrázky naleznete v tématu [Návod: Přidat pole do rozložení sestavy aplikace Word](ui-how-add-fields-word-report-layout.md).  


## <a name="see-also"></a>Viz také
[Správa rozvržení sestav](ui-manage-report-layouts.md)  
[Návod: Změna využívaného rozvržení pro danou sestavu](ui-how-change-layout-currently-used-report.md)  
[Návod: Import a export vlastního rozvržení sestavy nebo dokladu](ui-how-import-and-export-report-layout.md)  
[Práce se sestavami](ui-work-report.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

