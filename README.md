# Monkey Office Bank-Importdefinitionen 

## Einleitung

Dieb Buchhaltungs-Software "Monkey Office" bietet einen Import von Bankauszügen<sup id="a1">[1](#f1)</sup> an. Aus diesen lassen sich Buchungen erzeugen; so spart man sich die fehleranfällige Arbeit des manuellen Übetragens der Buchungen. 

Anders als bei den Wettbewerber, bietet Monkey Office keine direkte Anbindung des Bankkontos an das Programm, sondern die Kontobewegungen müssen zunächst von der Bank oder aus einen Online-Bankingprogramm heraus exportiert werden. Üblicherweise kommt hier ein CSV-Format zum Einsatz. 

Obwohl es ein [standardisiertes Format](https://de.wikipedia.org/wiki/MT940) dafür gibt, wird dies nicht von allen Banken angeboten. Die Banken erfinden lieber das Rad neu und tragen so zur Formatvielfalt bei. 

## Importdefinitionen 

Um diese Vielzahl an Formaten zuverlässig in Monkey Office importieren zu können, bietet Monkey Office eine Art Dolmetcher an, der von dem jeweiligen Bank-eigenen Format in das Programm-eigene Format übersetzt. Bei Monkey Office heißt das _Importdefinitionen_. 

Dahinter verbergen sich gewöhnliche Textdateien, die in jedem Texteditor geöffnet werden können. Mittels des darin befindlichen Skripts (eine Art kleines Programm), lassen sich die CSV-Dateien anhand zu definierender Trennzeichen in Spalten aufteilen.

Monkey Office liefert Importdefinitionen für gängige Online-Banking-Programme mit; für die Erstellung von spezifischen Formate kann entweder ProSaldo (die Firma hinter Monkey Office) beauftragt werden oder selbst Hand angelegt werden. Die Dokumentation bietet dazu ausreichend [Informationen](https://www.monkey-office.de/doc/MonKey_Office_-_Importdefinitionen_fur_Bankauszuge.html#26708153).

## Warum diese Sammlung?

Im [Supportforum](https://prosaldo.zendesk.com/hc/de/community) von ProSaldo sehe ich immer wieder Beiträge von Menschen, die nach einer Importdefinition für eine bestimmte Bank suchen. Oft ist das dann so speziell, dass es diese nicht noch nicht gibt und die Anfrage im Sande verläuft. Meist wird dann auf den Service von ProSaldo verwiesen oder eben auf das Handbuch. Damit war dann auch schon die Idee geboren, eine zentrale Sammelstelle für Importdefinitionen auf GitHub anzulegen ... das Rad muss ja nicht immer neu erfunden werden.


## Warum Github?

Die Verwendung von Github hat einige Vorteile:

* Es muss keine Website aufgesetzt und unterhalten werden
* Die Mitmachschwelle ist verhältnismäßig niedrig - es braucht nur einen Github-Account um mitzumachen
* Das Repository kann beliebig kopiert (geforkt) werden
* Änderungen an Dateien können nachvollzogen werden

## Hinweise zum Urheberrecht

Die folgenden Importdefinitionen sind im Lieferumfang von Monkey Office dabei und können als Ausgangspunkt eigener Definitionen dienen. Mit freundlicher Genehmigung von ProSaldo darf ich diese hier bereitstellen. 

* [BankX](BankX.txt)
* [Lexware Finanzmanager](Lexware_Finanzmanager.txt)
* [MacGiro](MacGiro.txt)
* [MoneyMoney](MoneyMoney.txt)
* [Sparkasse_CSV-CAMT](Sparkasse_CSV-CAMT.txt)


---
* <b id="f1">1</b>Monkey Office unterscheidet hier zwischen _Bankauszug_ und _Kontoauszug_. Mit ersteren sind die handelsüblichen Auszüge der Bank gemeint und mit dem zweiten Begriff ist ein Auszug aus einem Buchhaltungskonto gemeint. [↩](#a1)
