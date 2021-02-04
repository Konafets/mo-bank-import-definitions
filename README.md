# Monkey Office Bank-Importdefinitionen 

## Einleitung

Die Buchhaltungs-Software "Monkey Office" bietet den Import von Kontobewegungen an, um aus diesen Buchungen zu erstellen. Anders als die Wettbewerber, kann das Konto jedoch nicht direkt angebunden werden, sondern die Kontobewegungen müssen von der Bank oder aus einen Online-Bankingtool heraus exportiert werden. Üblicherweise werden die Daten in ein CSV-Format exportiert. 

Obwohl es standardisierte Formate dafür gibt, werden diese nicht von allen Banken verwendet und so existieren eine Vielzahl von verschiedenen Exportformaten für Kontobewegungen. 

Um diese Vielzahl an Formaten zuverlässig in Monkey Office importieren zu können, verwendet das Programm eine Art Dolmetcher, der von dem jeweiligen Bank-eigenen Format in das Monkey-Office Format übersetzt. Bei Monkey Office heißt das _Importdefinitionen_. Das sind reguläre Textdateien, in denen mittels einer einfachen Syntax die CSV-Dateien einlesen und verschiedene Operationen auf den Daten zulassen.

Monkey Office liefert Importdefinitionen für gängige Online-Banking-Programme mit; für die Erstellung von Bank-spezifischen Formate kann ProSaldo (die Firma hinter Monkey Office) beauftragt werden oder sie können auch selbst erstellt werden. Die Dokumentation bietet dazu ausreichend Information.

## Warum diese Sammlung?

Im [Supportforum](https://prosaldo.zendesk.com/hc/de/community) von ProSaldo kommt öfters die Frage nach einer Importdefintion für eine spezifische Bank auf. Diese Sammlung will all die unterschiedlichen Definitionen an einer zentralen Stelle vereinen, die Mitarbeit daran transparent machen und somit eine Quelle für Importdefinitionen sein.

Das Forken des Repositories ist ausdrücklich erwünscht. 


## Hinweise zum Urheberrecht

Die folgenden Importdefinitionen sind im Lieferumfang von Monkey Office dabei und sollen als Lehrmaterial und als Ausgangspunkt eigener Definitionen dienen. Mit freundlicher Genehmigung von ProSaldo darf ich diese hier veröffentlichen. 

* [BankX](BankX.txt)
* [Lexware Finanzmanager](Lexware_Finanzmanager.txt)
* [MacGiro](MacGiro.txt)
* [MoneyMoney](MoneyMoney.txt)
* [Sparkasse_CSV-CAMT](Sparkasse_CSV-CAMT.txt)
