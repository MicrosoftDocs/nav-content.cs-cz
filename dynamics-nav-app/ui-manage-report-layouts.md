---
title: "Správa rozložení sestav"
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
    
# <a name="manage-report-layouts"></a>Správa rozložení sestav
Rozložení sestavy řídí obsah a formát sestavy, včetně toho, která datová pole datové sady sestavy se objeví v sestavě a jak budou uspořádány, včetně stylu textu, obrázků a dalších. Z klientů Dynamics NAV můžete změnit, které rozložení se použije na sestavu, vytvořit nové rozložení nebo modifikovat existující rozložení.  

Sady rozložení zejména nastavují následující:

- Popisky a datová pole, která mají být zahrnuta z datové sady sestavy Dynamics NAV.
- Formát textu, například typ písma, velikost a barva.
- Logo společnosti a její postavení.
- Nastavení obecné stránky, jako například okraje a obrázky na pozadí. 

Dynamics NAV lze nastavit s více rozloženími sestavy, mezi kterými můžete  podle potřeby přepínat. Můžete použít jedno z vestavěných rozložení sestavy, nebo můžete vytvořit vlastní rozložení sestavy a podle potřeby je přiřadit k sestavám.

Existují dva typy rozložení sestavy, které můžete použít v sestavách: Aplikace Word a RDLC.

## <a name="word-report-layout-overview"></a>Přehled rozložení sestavy aplikace Word
Rozložení sestavy aplikace Word je založeno na dokumentu aplikace Word (typ souboru .docx). Rozložení sestavy aplikace Word umožňují navrhnout rozvržení sestavy pomocí aplikace Microsoft Word 2013 nebo novější. Rozložení sestavy aplikace Word určuje obsah sestavy - kontroluje, jak jsou uspořádány a jak vypadají prvky obsahu. Dokument rozložení sestavy aplikace Word obvykle používá tabulky k uspořádání obsahu, kde mohou buňky obsahovat datová pole, text nebo obrázky.

## <a name="rdlc-layout-overview"></a>Přehled rozložení RDLC
Rozložení RDLC jsou založeny na rozložení definice sestavy klienta (typy souborů typu .rdlc nebo .rdl). Tato rozložení jsou vytvořena a upravena pomocí nástroje Microsoft SQL Server – Tvůrce sestav. Koncept návrhu rozložení RDLC je podobný jako rozložení aplikace Word, kde rozložení definuje obecný formát sestavy a určuje pole z datové sady. Návrh rozložení RDLC je mnohem pokročilejší než rozvržení aplikace Word.

## <a name="built-in-and-custom-report-layouts"></a>Vestavěné a vlastní rozložení sestavy
Dynamics NAV obsahuje několik vestavěných rozložení. Vestavěné rozložení jsou předdefinované rozložení, které jsou určeny pro konkrétní sestavy. Sestavy Dynamics NAV budou mít vestavěnou sestavu jako rozložení sestavy RDLC, rozložení sestavy aplikace Word nebo v některých případech i v obou. V aplikaci Dynamics NAV nelze vestavěné rozložení upravovat, ale používáte jej jako výchozí bod pro vytváření vlastních rozložení sestav. 

Vlastní rozložení jsou rozložení sestavy, které navrhujete, abyste změnili vzhled sestavy. Obvykle vytvoříte vlastní rozložení založené na vestavěném rozložení, ale můžete je vytvořit od začátku nebo z kopie existujícího vlastního rozložení. Vlastní rozložení umožňují vytvořit více rozložení pro stejnou sestavu, mezi kterými můžete podle potřeby přepínat. Například můžete mít různé rozložení pro každou společnost Dynamics NAV, nebo můžete mít různé rozložení pro stejnou společnost pro určité příležitosti nebo události, jako je speciální kampaň nebo prázdninová sezóna.

## <a name="deciding-whether-to-use-a-word-or-rdlc-report-layout"></a>Rozhodování, zda použít rozložení sestavy aplikace Word nebo RDLC 
Rozložení sestavy může být založeno buď na dokumentu aplikace Word nebo souboru RDLC. Rozhodování, zda chcete použít rozložení sestavy aplikace Word nebo rozložení sestavy RDLC, bude záviset na tom, jak chcete, aby vygenerovaná sestava vypadala a na znalostech o aplikacích Word a Microsoft SQL Server – Tvůrce sestav. 

Obecné koncepty návrhu pro rozložení aplikace Word a RDLC jsou velmi podobné. Každý typ má však určité funkce návrhu, které ovlivňují, jak se vygenerovaná sestava zobrazuje v Dynamics NAV. To znamená, že stejný přehled může vypadat jinak, pokud používáte rozložení sestavy aplikace Word oproti rozložení sestavy RDLC.

Proces nastavení rozložení sestavy aplikace Word a RDLC v sestavách je stejný. Hlavní rozdíl je v tom, jak upravujete rozložení. Rozložení sestav aplikace Word jsou obvykle jednodušší k vytvoření a úpravám  než rozložení sestav RDLC, protože můžete použít aplikaci Word. Rozložení sestavy RDLC se upravuje pomocí nástroje SQL Server – Tvůrce sestav, který je určen pro pokročilejší uživatele. 

Pro více informací o tom, jak změnit rozložení, které chcete použít, viz [Návod: Změna aktuálně používaného rozložení v sestavě](ui-how-change-layout-currently-used-report.md)

## <a name="see-also"></a>Viz také
[Práce s Dynamics NAV](ui-work-product.md)  
[Návod: Vytvoření vlastního rozložení sestavy](ui-how-create-custom-report-layout.md)  
[Návod: Odesílání dokladů e-mailem](ui-how-send-documents-email.md)

