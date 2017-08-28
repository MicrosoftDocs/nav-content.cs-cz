---
title: "Řešení problémů s registrací do samoobslužné služby"
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
ms.openlocfilehash: 1090be6b706d2e8edbad01e8303463b257299ffa
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="troubleshooting-self-service-sign-up"></a>Řešení problémů s registrací do samoobslužné služby
Registrace do Dynamics NAV je snadná a lze ji provést velmi rychle.   Můžete si vytvořit bezplatný účet, a to i v případě, že jste stávající organizací. Tento článek popisuje problémy, které můžete mít během registrace.

## <a name="what-email-address-can-i-use-with-dynamics-nav"></a>Jakou e-mailovou adresu mohu používat s Dynamics NAV?
Dynamics NAV vyžaduje, abyste se zaregistrovali pomocí pracovní nebo školní e-mailové adresy. Dynamics NAV nepodporuje e-mailové adresy poskytované spotřebitelskými e-mailovými službami nebo poskytovateli telekomunikačních služeb. To zahrnuje outlook.com, hotmail.com, gmail.com a další.

Pokud se pokusíte zaregistrovat pomocí osobní e-mailové adresy, obdržíte zprávu, ve které je uvedeno, že byste měli použít pracovní nebo školní e-mailovou adresu.

## <a name="troubleshooting"></a>Odstraňování problémů
V mnoha případech lze registrace do Dynamics NAV dosáhnout následujícím procesem registrace.  Existuje však několik důvodů, proč možná nebudete schopni dokončit registraci do samoobslužné služby. Níže uvedená tabulka shrnuje některé z nejčastějších důvodů, proč možná nebudete schopni dokončit registraci a způsoby, jak tyto problémy vyřešit.

|Příznak / Chybová zpráva                                                                             |Příčina a řešení|
|--------------------------------------------------------------------------------------------------|--------------------|
|U e-mailových adres Office 365, které nejsou registrovány v USA, se při registraci zobrazí obdobná zpráva jako jsou následující: <br>**To nefungovalo, ještě nepodporujeme vaši zemi ani oblast.**<br> |Dynamics NAV v současné době podporuje pouze registrované e-mailové účty Office 365 v USA.|
|Osobní e-mailové adresy, jako například nancy@gmail.com nejsou podporovány. Při registraci obdržíte obdobnou zprávu jako jsou následující: <br>**Zadali jste osobní e-mailovou adresu: Prosím zadejte svou pracovní e-mailovou adresu, abychom mohli bezpečně ukládat data vaší společnosti.**<br> nebo <br> **To vypadá jako osobní e-mailová adresa. Zadejte svou pracovní adresu, abychom vás mohli spojit s ostatními ve vaší společnosti. A nemějte strach. Vaši adresu s nikým sdílet nebudeme.** | Dynamics NAV nepodporuje e-mailové adresy poskytované spotřebitelskými e-mailovými službami nebo poskytovateli telekomunikačních služeb. Chcete-li dokončit registraci, zkuste to znovu pomocí e-mailové adresy přidělené vaší prací nebo školou. Pokud se stále nemůžete zaregistrovat a jste ochotní dokončit registraci pomocí pokročilejšího instalační procesu, můžete se přihlásit k novému zkušebnímu odběru služby Office 365 a zaregistrovat se pomocí této e-mailové adresy.
|Emailové adresy.gov nebo .mil Při registraci obdržíte obdobnou zprávu jako jsou následující: <br>**Dynamika NAV nedostupná: Dynamics NAV není v současné době k dispozici pro uživatele s e-mailovými adresami .gov nebo .mil. Použijte jinou pracovní e-mailovou adresu nebo znovu zkontrolujte později.** <br>nebo <br>**Nemůžeme dokončit vaši registraci. Zdá se, že Dynamics NAV není momentálně k dispozici pro vaši práci nebo školu.**|Dynamics NAV momentálně nepodporuje adresy .gov nebo .mil.|
|Přihlášení pomocí samoobslužné služby není povoleno. Při registraci obdržíte obdobnou zprávu jako jsou následující: <br>**Nemůžeme dokončit vaši registraci. Vaše IT oddělení vypnulo registraci pro Dynamics NAV. Obraťte se na ně k dokončení registrace.** <br>nebo <br> **To vypadá jako osobní e-mailová adresa. Zadejte svou pracovní adresu, abychom vás mohli spojit s ostatními ve vaší společnosti. A nemějte strach. Vaši adresu nebudeme s nikým sdílet.**|IT správce vaší organizace zakázal registraci pro službu Dynamics NAV. Chcete-li dokončit registraci, obraťte se na IT správce a požádejte jej, aby postupoval podle pokynů na níže uvedené stránce, a umožnil tak stávajícím uživatelům registraci do služby Dynamics NAV, a  novým uživatelům připojení ke stávajícímu klientovi. S tímto problémem se také můžete setkat, pokud jste se pro sadu Office 365 zaregistrovali prostřednictvím partnera.|
|E-mailová adresa není ID Office 365. Při registraci obdržíte obdobnou zprávu jako jsou následující: <br>**Nemůžeme vás najít na contoso.com. Používáte jiné identifikační číslo v práci nebo ve škole? Pokuste se přihlásit pomocí něj a pokud to nebude fungovat, obraťte se na IT oddělení.**|Vaše organizace používá ID k přihlášení do Office 365 a do dalších služeb společnosti Microsoft, které je odlišné od vaší e-mailové adresy. Vaše emailová adresa například může být Nancy.Smith@contoso.com ale vaše ID je nancys@contoso.com. Chcete-li dokončit registraci, použijte ID, které vám vaše organizace přidělila k přihlášení do Office 365 nebo do jiných služeb společnosti Microsoft. Pokud nevíte, co to je, kontaktujte IT správce. Pokud se stále nemůžete zaregistrovat a jste schopni dokončit pokročilejší proces registrace, můžete se přihlásit k novému zkušebnímu odběru Office 365 a zaregistrovat se pomocí této e-mailové adresy.|


## <a name="see-also"></a>Viz také
[Vítejte v Dynamics NAV](across-get-started.md)  
[Práce s Dynamics NAV](ui-work-product.md)




