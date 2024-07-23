---
title: Verantwoord Melden van Kwetsbaarheden (Responsible Disclosure)
---
**Algemeen**

Bij DIVD heeft de veiligheid van onze systemen de hoogste prioriteit. Ondanks onze inspanningen kunnen er kwetsbaarheden in onze systemen voorkomen. Als u toch een kwetsbaarheid ontdekt, informeer ons dan zodat we actie kunnen ondernemen om deze te verhelpen. Wij waarderen je hulp bij het beschermen van onze systemen. 

**Doe het volgende:**

Stuur de bevindingen naar ons toe via de volgende URL: <https://app.zerocopter.com/en/rd/f9afbf32-ce59-48ed-96f2-ac4410595aa4.>

 **Do's:**

* Rapporteer de kwetsbaarheid zo snel mogelijk om het risico te beperken dat kwaadwillenden de kwetsbaarheid vinden en misbruiken.
* Rapporteer de kwetsbaarheid op een wijze die de confidentialiteit van het rapport beschermt, zodat anderen geen toegang krijgen tot de informatie.
* Geef voldoende details om het probleem te reproduceren zodat we het effectief kunnen aanpakken. Meestal is het IP-adres of de URL van het getroffen systeem en een beschrijving van de kwetsbaarheid voldoende. Complexere kwetsbaarheden kunnen echter extra uitleg nodig hebben.

**Don'ts:**

* Maak de kwetsbaarheid of het probleem niet bekend aan anderen totdat het is opgelost.
* Creëer geen eigen backdoor in het systeem om de kwetsbaarheid aan te tonen, want dit kan extra schade veroorzaken en onnodige veiligheidsrisico's introduceren.
* Maak niet meer misbruik van de kwetsbaarheid dan nodig is om het bestaan ervan te bevestigen.
* Kopieer, wijzig of verwijder geen gegevens op het kwetsbare systeem. Maak in plaats daarvan een directory listing van het systeem als alternatief.
* Breng geen wijzigingen aan op het kwetsbare systeem.
* Maak niet herhaaldelijk gebruik van het kwetsbare systeem en deel de toegang niet met anderen.
* Het gebruik van brute force aanvallen, fysieke beveiligingsinbreuken, social engineering, distributed denial of service (ddos) aanvallen, spam of applicaties van derden om toegang te krijgen tot het kwetsbare systeem is verboden.
* Probeer geen toegang te krijgen tot gegevens of informatie die niet van jou zijn.
* Vernietig, beschadig of probeer geen gegevens of informatie te vernietigen of beschadigen die niet van jou zijn.

**Wat DIVD belooft:**

* We reageren liefst binnen drie werkdagen op je melding en geven je een evaluatie van de melding en een geschatte oplostijd.
* Als je je hebt gehouden aan de richtlijnen van ons Responsible Disclosure-beleid, zullen we geen juridische stappen tegen je ondernemen met betrekking tot het rapport.
* We zullen je persoonlijke informatie niet delen met derden zonder je toestemming, behalve wanneer dit nodig is om te voldoen aan een wettelijke verplichting.
* Meldingen kunnen onder een pseudoniem of anoniem worden gedaan.
* We houden je op de hoogte van de voortgang van het oplossen van het probleem.
* In alle openbare informatie over het gemelde probleem zullen we je vermelden als de ontdekker (tenzij je een andere voorkeur hebt).
* We streven ernaar alle problemen zo snel mogelijk op te lossen en willen graag meewerken aan het openbaar maken van het probleem zodra het is opgelost.
* Deze Responsible Disclosure policy is gebaseerd op een voorbeeld van Floor Terra en de Responsible Disclosure Guideline van het NCSC.

**In-Scope Systemen**

De volgende systemen vallen expliciet binnen de scope van DIVD. Als je een kwetsbaarheid ontdekt in een systeem waarvan je denkt dat het ons toebehoort maar niet hier is vermeld, zullen wij dit per geval beoordelen.

* ```
  as50559.com
  ```
* ```
  divd.nl
  ```
* ```
  as50559.org
  ```
* ```
  divd.academy
  ```
* ```
  as50559.nl
  ```
* ```
  divd.network
  ```
* ```
  divdfonds.nl
  ```
* ```
  divd.fund
  ```
* ```
  csirt.global
  ```
* ```
  divd.charity
  ```
* ```
  divd.club
  ```
* ```
  divd.space
  ```
* ```
  divd.community
  ```
* ```
  cyber-wear.nl
  ```
* ```
  divd.today
  ```
* ```
  divd.global
  ```
* ```
  divd.family
  ```
* ```
  divd.org
  ```



* ```
  divd.observer
  ```

**Buiten-Scope** 

* Het gebruik van spam, social engineering en fysieke inbraak vallen buiten de scope. Hieronder vallen ook pogingen tot phishing.
* DoS/DDoS-aanvallen of brute force-aanvallen.
* Kwetsbaarheden die alleen invloed hebben op niet-geupdate browsers (ouder dan 3 versies).
* Aanvallen die het gebruik van gedeelde computers, man in the middle of reeds gecompromitteerde accounts of apparaten vereisen.
* Onlangs geopenbaarde zero-day kwetsbaarheden in producten waarvoor geen patch of een recente patch beschikbaar is.
* Aanvallen die onrealistische hoeveelheden gebruikersinteractie vereisen.
* Rapporten van geautomatiseerde scanners die geen specifieke tests voor dit programma bevatten.
* Het niet volgen van industriestandaarden.
* Ontbrekende best practices.

**Kwetsbaarheden die niet in aanmerking komen**

Meldingen voor kwetsbaarheden uit de lijst worden niet geaccepteerd.

* Self-XSS die niet kan worden gebruikt om andere gebruikers aan te vallen.
* Verbose berichten, bestanden of directory listings die geen gevoelige informatie vrijgeven.
* CORS-misconfiguratie op niet-gevoelige eindpunten.
* Ontbrekende cookie-flags of ontbrekende security headers.
* Cross-Site Request Forgery (CSRF) met geen of minimale impact.
* Aanwezigheid van het autocomplete attribute op web foms.
* Reverse tabnabbing.
* Omzeilen van rate limits of afwezigheid van rate limits.
* Overtredingen van best practices (bijv. wachtwoordcomplexiteit, verlopen, hergebruik).
* Clickjacking op pagina's zonder gevoelige acties.
* CSV Injection.
* Host Header Injection.
* Sessies worden niet ongeldig gemaakt (bijv. uitloggen, wachtwoord opnieuw instellen).
* Sessiecookies worden niet ongeldig gemaakt na uitloggen of opnieuw instellen wachtwoord.
* Oudere browsersessies blijven actief na een wachtwoordwijziging.
* Hyperlink injection or takeovers.
* Mixed content type issues.
* Cross-domain referrer leakage.
* Alles gerelateerd aan e-mailspoofing, SPF, DMARC of DKIM.
* Injectie van inhoud (content injection).
* Username/email enumeration.
* Email bombing.
* HTTP Request smuggling zonder aantoonbare impact.
* Homograph attacks.
* XMLRPC enabled.
* Banner grabbing or version disclosure.
* Weak SSL configurations and SSL/TLS scan reports (Zwakke SSL-configuraties en SSL/TLS scanrapporten).
* Metadata in afbeeldingen wordt niet gestript.
* Openbaar maken van API-keys zonder bewezen impact.
* Same-site scripting.
* Subdomeinovername zonder het subdomein daadwerkelijk over te nemen.
* Willekeurig uploaden van bestanden zonder bewijs van het bestaan van het geüploade bestand.
* Bekende kwetsbaarheden in gebruikte technieken zonder een werkend proof-of-concept.

Wat moet je doen als je een kwetsbaarheid vindt bij een van onze leveranciers of partners?

Kwetsbaarheden moeten idealiter worden gerapporteerd aan de partijen die ze kunnen verhelpen. Als je problemen tegenkomt of hulp nodig hebt, helpen we je graag.
