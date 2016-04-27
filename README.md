# WebTech

## Gliederung:

- Fallbeispiele
- Geschichte (Win/Apache/Wordpress/OS X)
- Funktionsweise
- Krypto Einführung
- Virenscanner Funktionsweise / Heuristik / Umgehung von Heuristiken
- Command and Control server
- Bitcoin (Michael?)
- Tor
- Klassifizierung diverser Ransomware-Varianten
- User Training
- Backups
- Zukünftige Gefahren in Anbetracht von Cloud-Diensten und IoT
- Fazit
- (Live-Demo?)

## Paper-Beispiel:

https://kowa.hs-augsburg.de/medium/text/publikationen/JP2-VIS05.pdf

## Links:

### Evolution von Ransomware:

- https://www.symantec.com/content/en/us/enterprise/media/security_response/whitepapers/the-evolution-of-ransomware.pdf
- https://blog.varonis.com/a-brief-history-of-ransomware/

### Locky

- https://nakedsecurity.sophos.com/2016/02/17/locky-ransomware-what-you-need-to-know/
- http://www.heise.de/security/artikel/Erpressungs-Trojaner-wie-Locky-aussperren-3120956.html
- https://blog.malwarebytes.org/intelligence/2016/03/look-into-locky/
- http://www.heise.de/security/meldung/Krypto-Trojaner-Locky-Batch-Dateien-infizieren-Windows-Tool-verspricht-Schutz-3118188.html
- www.heise.de/newsticker/meldung/l-f-Was-waere-wenn-Batch-Skript-simuliert-Locky-Infektion-3180132.html
- www.heise.de/newsticker/meldung/Nuclear-Exploit-Kit-bombardiert-hunderttausende-Rechner-mit-Locky-3181696.html

### TeslaCrypt

- http://blog.talosintel.com/2016/03/teslacrypt-301-tales-from-crypto.html
- http://www.heise.de/security/artikel/TeslaCrypt-2-0-entschluesselt-3094987.html
- http://www.engadget.com/2016/03/17/teslacrypt-can-no-longer-be-cracked/
- http://www.heise.de/newsticker/meldung/Erpresser-ruesten-nach-Verschluesselungs-Trojaner-TeslaCrypt-4-0-gesichtet-3145559.html
- www.heise.de/newsticker/meldung/Krypto-Trojaner-TeslaCrypt-erschwert-Desinfektion-des-Rechners-verschluesselt-weitere-Formate-3180711.html

### Ransomware - Fälle in der Presse

- http://www.heise.de/security/meldung/Online-Erpresser-verschluesseln-Datenbank-und-fordern-50-000-US-Dollar-Loesegeld-2535621.html
- http://www.engadget.com/2016/02/19/hospital-ransomware-a-chilling-wake-up-call/
- http://www.theguardian.com/technology/2016/mar/16/major-sites-new-york-times-bbc-ransomware-malvertising
- http://www.bankinfosecurity.com/imperva-a-8860/op-1
- http://blog.fox-it.com/2016/03/24/website-of-security-certification-provider-spreading-ransomware/

### Petya

- http://www.heise.de/newsticker/meldung/Erpressungs-Trojaner-Petya-riegelt-den-gesamten-Rechner-ab-3150917.html
- www.heise.de/newsticker/meldung/Petya-Den-Erpressungs-Trojaner-stoppen-bevor-er-die-Festplatten-verschluesselt-3153388.html
- http://www.bleepingcomputer.com/news/security/petya-ransomware-skips-the-files-and-encrypts-your-hard-drive-instead/
- https://labsblog.f-secure.com/2016/04/01/petya-disk-encrypting-ransomware/
- www.heise.de/newsticker/meldung/Erpressungs-Trojaner-Petya-Neue-Infektionswelle-rollt-an-Verschluesselung-bisher-nicht-knackbar-3160177.html
- www.heise.de/newsticker/meldung/Erpressungs-Trojaner-Petya-geknackt-Passwort-Generator-veroeffentlicht-3167064.html
- https://twitter.com/mikko/status/714158149352235009/photo/1
- Debugging Petya bootloader with IDA https://www.youtube.com/watch?v=7rtMX9zS55I
- Petya ECDH key exchange https://www.youtube.com/watch?v=nAx9QROI1h4 

### Sonstige Ransomware

- www.heise.de/newsticker/meldung/Erpressungs-Trojaner-mit-neuer-Taktik-Erst-schauen-dann-verschluesseln-3153767.html
- http://www.macrumors.com/2016/03/06/mac-ransomware-transmission/
- https://www.f-secure.com/weblog/archives/00002716.html
- https://www.f-secure.com/weblog/archives/00002704.html
- https://www.f-secure.com/weblog/archives/00002640.html
- http://www.techrepublic.com/article/mac-os-x-ransomware-how-keranger-is-a-shadow-of-malware-to-come/
- http://www.heise.de/newsticker/meldung/Nur-72-Stunden-Erpressungs-Trojaner-Jigsaw-droht-Dateien-zu-loeschen-3172217.html
- www.heise.de/newsticker/meldung/Erpressungs-Trojaner-CryptXXX-kostenlos-entschluesseln-3189766.html
- www.heise.de/newsticker/meldung/Dogspectus-Erste-Android-Geraete-im-Vorbeisurfen-mit-Exploit-Kit-verseucht-3190235.html
- www.heise.de/newsticker/meldung/BSI-Umfrage-Ein-Drittel-der-Unternehmen-ist-von-Erpressungs-Trojanern-betroffen-3189776.html

### Allgemein

- https://www.microsoft.com/security/portal/mmpc/shared/ransomware.aspx
- http://www.theguardian.com/technology/2016/mar/13/autonomous-cars-self-driving-hack-mikko-hypponen-sxsw
- https://labsblog.f-secure.com/2016/03/21/the-graphic-design-of-maktub-locker-ransomware/
- https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Cyber-Sicherheit/Themen/Ransomware.html
- http://blog.malwaremustdie.org/2013/11/tango-down-of-44-cryptolocker-cnc.html
- https://link.springer.com/article/10.1007/s11416-008-0092-2
- http://web.gccaz.edu/~dcost/cis105/ransomware-a-growing-menace.pdf
- https://books.google.de/books?hl=de&lr=&id=rE9yaepbeLIC&oi=fnd&pg=PT28&dq=ransomware&ots=b3TFIw-Iuo&sig=JdWVVerUv_ScUSMSbn5sjWgOsyY#v=onepage&q=ransomware&f=false
- https://link.springer.com/chapter/10.1007/978-3-319-20550-2_1
- https://twitter.com/abuse_ch/status/713709717449805824/photo/1
- http://blog.talosintel.com/2016/04/ransomware.html
- https://threatpost.com/latest-flash-zero-day-being-used-to-push-ransomware/117248/
- www.heise.de/newsticker/meldung/Entschluesselungs-Tool-verfuegbar-Webseite-identifiziert-Erpressungs-Trojaner-3173463.html
- http://www.heise.de/newsticker/meldung/Tool-RansomWhere-soll-Mac-Nutzer-vor-Erpressungstrojanern-schuetzen-3180128.html

### Gegenmaßnahmen

- https://www.f-secure.com/en/web/labs_global/removing-police-themed-ransomware
- http://www.tandfonline.com/doi/abs/10.1080/10658980701576412
- http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=7387902&newsearch=true&queryText=ransomware
- http://ieeexplore.ieee.org/xpl/articleDetails.jsp?arnumber=7336353&newsearch=true&queryText=ransomware
