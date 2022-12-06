# Abschlussprojekt des 4 wöchigen Kurses - Data Analytics

Du arbeitest als Data Scientist bei der P-2-P-Plattform https://www.kiva.org/, die vor einem Jahr gegründet wurde. Nun wollt ihr euer Geschäft erweitern. Euer Team hat sich aufgeteilt und jeder Analyst hat einen Teilbereich der Daten. Deine Aufgabe ist es in einer explorativen Datenanalyse Insights für eure Plattform herauszufinden.

#### Anforderungen:
* vollständige Datenanalyse
* Dokumentation der Arbeitsschritte
* nachvollziehbare Erläuterungen über Vorgehensweise/Entscheidungen
* für die Bewertung: 3 verschiedenartige Plots (Plotfunktionen) benennen
* Customizing der Plots
* Analyse der Plots
* Coding

Die Dokumentation kann in englisch oder deutsch erfolgen.

Am Freitag erfolgt die Vorstellung der 3 Plots innerhalb des Zeitrahmens von 5min - (+-1min) ist dabei ok. Bewertet wird die Einhaltung des Zeitrahmes - dass das Anliegen innerhalb eines vorgegebenen Zeitrahmens vorgetragen wird.

## CRISP DM: Business Understanding
Euer Geschäftsmodell ist das Betreiben einer Plattform (crowd-investing) bei der sich Personen die eine Geschäftsidee haben, aber nicht das benötigte Geld, anmelden und für ihr Projekt innerhalb einer vorgegebenen Zeit Geld sammeln können.

Auf der anderen Seite habt ihr Geldgeber, die gern ihr Geld in Projekte anlegen möchten und nach Investitionen suchen.

Als Vermittler bringt eure Plattform also Geldnehmer und Geldgeber zusammen.

Deine Datenbasis ist die Historie eurer Plattform.

### Erweiterung Geschäftsmodell

Alle Projekte sind abgeschlossene Projekte, d.h. die Zeit, um für sein Projekt Geld zu sammeln ist abgelaufen. Euer Geschäftsmodell sieht es vor, dass die gesammelten Gelder ausgezahlt werden, auch wenn der Zielbetrag nicht erreicht wurde.

Ihr verdient euer Geld mit einer Provision für jedes Projekt was auf eurer Plattform landet.

Der Geldgeber erhält einen Zins für die Geldleihe

## CRISP DM: Data Understanding

* funded_amount ... mit Ablauf der "Crowding"zeit erhaltener Betrag/ ausgezahlter Betrag in USD
* loan_amount ... Zielbetrag (Betrag dem man für das Projekt erreichen wollte) in USD
* activity ... Unterkategory zu dem das Ziel des Crowdprojektes thematisch gehört
* sector ... Oberkategory in den das Crowdprojektes Thema fällt
* use ... Kurzbeschreibung wofür das Geld verwendet werden soll
* country_code ... Ländercode nach ISO Norm
* country ... Ländername nach ISO Norm
* region ... Region
* currency ... Währung in den der funded_amount dann ausgezahlt wurde
* term in months ... Dauer über die der Kredit ausgezahlt werden soll
* lender_count ...Darlehensgeber (also wieviele Personen Geld für das Projekt gegeben haben)
* borrower_genders ... Geschlecht und Anzahl der Darlehensnehmer, also diejenigen die das Crowdprojekt initiiert haben       
* repayment interval ... vertraglich vereinbarte Rückzahlungsmodalitäten/-rhythmus
