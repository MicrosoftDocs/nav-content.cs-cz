---
title: "Správa rozvržení sestav"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 0aa247891ce66880da308209f9da84072f5b9d64
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---
    
# <a name="manage-report-layouts"></a>Správa rozvržení sestav
Rozvržení sestavy řídí obsah a formát sestavy, včetně toho, která datová pole datové sady sestavy se objeví v sestavě a jak budou uspořádány, včetně stylu textu, obrázků a dalších. Z klientů [!INCLUDE[navnow](includes/navnow_md.md)] můžete změnit, které rozvržení se použije na sestavu, vytvořit nové rozvržení nebo modifikovat existující rozvržení.  

Sady rozvržení zejména nastavují následující:

- Popisky a datová pole, která mají být zahrnuta z datové sady sestavy [!INCLUDE[navnow](includes/navnow_md.md)].
- Formát textu, například typ písma, velikost a barva.
- Logo společnosti a její postavení.
- Nastavení obecné stránky, jako například okraje a obrázky na pozadí. 

[!INCLUDE[navnow](includes/navnow_md.md)] lze nastavit s více rozvrženími sestavy, mezi kterými můžete  podle potřeby přepínat. Můžete použít jedno z vestavěných rozvržení sestavy, nebo můžete vytvořit vlastní rozvržení sestavy a podle potřeby je přiřadit k sestavám.

Existují dva typy rozvržení sestavy, které můžete použít v sestavách: Aplikace Word a RDLC.

## <a name="word-report-layout-overview"></a>Přehled rozvržení sestavy aplikace Word
Rozvržení sestavy aplikace Word je založeno na dokumentu aplikace Word (typ souboru .docx). Rozvržení sestavy aplikace Word umožňují navrhnout rozvržení sestavy pomocí aplikace Microsoft Word 2013 nebo novější. Rozvržení sestavy aplikace Word určuje obsah sestavy - kontroluje, jak jsou uspořádány a jak vypadají prvky obsahu. Dokument rozvržení sestavy aplikace Word obvykle používá tabulky k uspořádání obsahu, kde mohou buňky obsahovat datová pole, text nebo obrázky.

## <a name="rdlc-layout-overview"></a>Přehled rozvržení RDLC
Rozvržení RDLC jsou založeny na rozvržení definice sestavy klienta (typy souborů typu .rdlc nebo .rdl). Tato rozvržení jsou vytvořena a upravena pomocí nástroje Microsoft SQL Server – Tvůrce sestav. Koncept návrhu rozvržení RDLC je podobný jako rozvržení aplikace Word, kde rozvržení definuje obecný formát sestavy a určuje pole z datové sady. Návrh rozvržení RDLC je mnohem pokročilejší než rozvržení aplikace Word.

## <a name="built-in-and-custom-report-layouts"></a>Vestavěné a vlastní rozvržení sestavy
[!INCLUDE[navnow](includes/navnow_md.md)] obsahuje několik vestavěných rozvržení. Vestavěné rozvržení jsou předdefinované rozvržení, které jsou určeny pro konkrétní sestavy. Sestavy [!INCLUDE[navnow](includes/navnow_md.md)] budou mít vestavěnou sestavu jako rozvržení sestavy RDLC, rozvržení sestavy aplikace Word nebo v některých případech i v obou. V aplikaci [!INCLUDE[navnow](includes/navnow_md.md)] nelze vestavěné rozvržení upravovat, ale používáte jej jako výchozí bod pro vytváření vlastních rozvržení sestav. 

Vlastní rozvržení jsou rozvržení sestavy, které navrhujete, abyste změnili vzhled sestavy. Obvykle vytvoříte vlastní rozvržení založené na vestavěném rozvržení, ale můžete je vytvořit od začátku nebo z kopie existujícího vlastního rozvržení. Vlastní rozvržení umožňují vytvořit více rozvržení pro stejnou sestavu, mezi kterými můžete podle potřeby přepínat. Například můžete mít různé rozvržení pro každou společnost [!INCLUDE[navnow](includes/navnow_md.md)], nebo můžete mít různé rozvržení pro stejnou společnost pro určité příležitosti nebo události, jako je speciální kampaň nebo prázdninová sezóna.

## <a name="deciding-whether-to-use-a-word-or-rdlc-report-layout"></a>Rozhodování, zda použít rozvržení sestavy aplikace Word nebo RDLC 
Rozvržení sestavy může být založeno buď na dokumentu aplikace Word nebo souboru RDLC. Rozhodování, zda chcete použít rozvržení sestavy aplikace Word nebo rozvržení sestavy RDLC, bude záviset na tom, jak chcete, aby vygenerovaná sestava vypadala a na znalostech o aplikacích Word a Microsoft SQL Server – Tvůrce sestav. 

Obecné koncepty návrhu pro rozvržení aplikace Word a RDLC jsou velmi podobné. Každý typ má však určité funkce návrhu, které ovlivňují, jak se vygenerovaná sestava zobrazuje v [!INCLUDE[navnow](includes/navnow_md.md)]. To znamená, že stejný přehled může vypadat jinak, pokud používáte rozvržení sestavy aplikace Word oproti rozvržení sestavy RDLC.

Proces nastavení rozvržení sestavy aplikace Word a RDLC v sestavách je stejný. Hlavní rozdíl je v tom, jak upravujete rozvržení. Rozvržení sestav aplikace Word jsou obvykle jednodušší k vytvoření a úpravám  než rozvržení sestav RDLC, protože můžete použít aplikaci Word. Rozvržení sestavy RDLC se upravuje pomocí nástroje SQL Server – Tvůrce sestav, který je určen pro pokročilejší uživatele. 

Pro více informací o tom, jak změnit rozvržení, které chcete použít, viz [Návod: Změna aktuálně používaného rozvržení v sestavě](ui-how-change-layout-currently-used-report.md)

## <a name="see-also"></a>Viz také
[Práce s [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md)  
[Návod: Vytvoření vlastního rozvržení sestavy](ui-how-create-custom-report-layout.md)  
[Návod: Odesílání dokladů e-mailem](ui-how-send-documents-email.md)

