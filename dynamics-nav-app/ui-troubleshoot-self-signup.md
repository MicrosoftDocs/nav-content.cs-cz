---
title: "Způsoby řešení potíží nebo práce kolem problémů se samoobslužným přihlášením"
description: "Informace o nejčastějších příčinách, proč pravděpodobně nebudete moci dokončit registraci do služby Dynamics NAV, a způsoby, jak se nimi vypořádat."
documentationcenter: 
author: SusanneWindfeldPedersen
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 24cee72ab3e6769d885f294c2e52fa01e192d384
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="troubleshooting-self-service-sign-up"></a>Řešení problémů s registrací do samoobslužné služby
Registrace do [!INCLUDE[d365fin](includes/d365fin_md.md)] je snadná a lze ji provést velmi rychle. Můžete si vytvořit bezplatný účet, a to i v případě, že jste stávající organizací. Tento článek popisuje problémy, které můžete mít během registrace.

## <a name="what-email-address-can-i-use-with-dynamics-nav"></a>Jakou e-mailovou adresu mohu používat s Dynamics NAV?
[!INCLUDE[d365fin](includes/d365fin_md.md)] vyžaduje, abyste se zaregistrovali pomocí pracovní nebo školní e-mailové adresy. [!INCLUDE[d365fin](includes/d365fin_md.md)] nepodporuje e-mailové adresy poskytované spotřebitelskými e-mailovými službami nebo poskytovateli telekomunikačních služeb. To zahrnuje outlook.com, hotmail.com, gmail.com a další.

Pokud se pokusíte zaregistrovat pomocí osobní e-mailové adresy, obdržíte zprávu, ve které je uvedeno, že byste měli použít pracovní nebo školní e-mailovou adresu.

## <a name="troubleshooting"></a>Odstraňování problémů
V mnoha případech lze registrace do [!INCLUDE[d365fin](includes/d365fin_md.md)] dosáhnout následujícím procesem registrace. Existuje však několik důvodů, proč možná nebudete schopni dokončit registraci do samoobslužné služby. Níže uvedená tabulka shrnuje některé z nejčastějších důvodů, proč možná nebudete schopni dokončit registraci a způsoby, jak tyto problémy vyřešit.

| Příznak / Chybová zpráva | Příčina a řešení |
| --- | --- |
| U e-mailových adres Office 365, které nejsou registrovány v USA, se při registraci zobrazí obdobná zpráva jako jsou následující:<br /><br />**To nefungovalo, ještě nepodporujeme vaši zemi ani oblast.** |[!INCLUDE[d365fin](includes/d365fin_md.md)] v současné době podporuje pouze registrované e-mailové účty Office 365 v USA. |
| Osobní e-mailové adresy, jako například nancy@gmail.com nejsou podporovány. Při registraci obdržíte obdobnou zprávu jako jsou následující:<br /><br />**Zadali jste osobní e-mailovou adresu: Prosím zadejte svou pracovní e-mailovou adresu, abychom mohli bezpečně ukládat data vaší společnosti.**<br> nebo <br> **To vypadá jako osobní e-mailová adresa. Zadejte svou pracovní adresu, abychom vás mohli spojit s ostatními ve vaší společnosti. A nemějte strach. Vaši adresu s nikým sdílet nebudeme.** |[!INCLUDE[d365fin](includes/d365fin_md.md)] nepodporuje e-mailové adresy poskytované spotřebitelskými e-mailovými službami nebo poskytovateli telekomunikačních služeb. Chcete-li dokončit registraci, zkuste to znovu pomocí e-mailové adresy přidělené vaší prací nebo školou. Pokud se stále nemůžete zaregistrovat a jste ochotní dokončit registraci pomocí pokročilejšího instalační procesu, můžete se přihlásit k novému zkušebnímu odběru služby Office 365 a zaregistrovat se pomocí této e-mailové adresy. |
| Emailové adresy.gov nebo .mil Při registraci obdržíte obdobnou zprávu jako jsou následující:<br /><br />**[!INCLUDE[d365fin](includes/d365fin_md.md)] nedostupná: [!INCLUDE[d365fin](includes/d365fin_md.md)] není v současné době k dispozici pro uživatele s e-mailovými adresami .gov nebo .mil. Použijte jinou pracovní e-mailovou adresu nebo znovu zkontrolujte později.** <br>nebo <br>**Nemůžeme dokončit vaši registraci. Zdá se, že [!INCLUDE[d365fin](includes/d365fin_md.md)] není momentálně k dispozici pro vaši práci nebo školu.** |[!INCLUDE[d365fin](includes/d365fin_md.md)] momentálně nepodporuje adresy .gov nebo .mil. |
| Přihlášení pomocí samoobslužné služby není povoleno. Při registraci obdržíte obdobnou zprávu jako jsou následující:<br /><br />**Nemůžeme dokončit vaši registraci. Vaše IT oddělení vypnulo registraci pro [!INCLUDE[d365fin](includes/d365fin_md.md)]. Obraťte se na ně k dokončení registrace.** <br>nebo <br> **To vypadá jako osobní e-mailová adresa. Zadejte svou pracovní adresu, abychom vás mohli spojit s ostatními ve vaší společnosti. A nemějte strach. Vaši adresu s nikým sdílet nebudeme.** |IT správce vaší organizace zakázal registraci pro službu [!INCLUDE[d365fin](includes/d365fin_md.md)]. Chcete-li dokončit registraci, obraťte se na IT správce a požádejte jej, aby postupoval podle pokynů na níže uvedené stránce, a umožnil tak stávajícím uživatelům registraci do služby [!INCLUDE[d365fin](includes/d365fin_md.md)], a novým uživatelům připojení ke stávajícímu klientovi. S tímto problémem se také můžete setkat, pokud jste se pro sadu Office 365 zaregistrovali prostřednictvím partnera. |
| E-mailová adresa není ID Office 365. Při registraci obdržíte obdobnou zprávu jako jsou následující:<br /><br />**Nemůžeme vás najít na contoso.com. Používáte jiné identifikační číslo v práci nebo ve škole? Pokuste se přihlásit pomocí něj a pokud to nebude fungovat, obraťte se na IT oddělení.** |Vaše organizace používá ID k přihlášení do Office 365 a do dalších služeb společnosti Microsoft, které je odlišné od vaší e-mailové adresy. Vaše emailová adresa například může být Nancy.Smith@contoso.com ale vaše ID je nancys@contoso.com. Chcete-li dokončit registraci, použijte ID, které vám vaše organizace přidělila k přihlášení do Office 365 nebo do jiných služeb společnosti Microsoft. Pokud nevíte, co to je, kontaktujte IT správce. Pokud se stále nemůžete zaregistrovat a jste schopni dokončit pokročilejší proces registrace, můžete se přihlásit k novému zkušebnímu odběru Office 365 a zaregistrovat se pomocí této e-mailové adresy. |

## <a name="see-also"></a>Viz také
[Vítejte v [!INCLUDE[d365fin](includes/d365fin_long_md.md)]](index.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)


