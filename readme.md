# php-Modul

## Aufgaben Skript

### 13.1 

#### 2)

Der Satz des Pythagoras lautet `a² + b² = c²`. Erstellen Sie ein Programm zur Berechnung der Seite C nach Eingabe der Werte für a und b. Für die Wurzelberechnung können Sie die Funktion `sqrt()`" benutzen.

#### 5)
Ein Programm soll den Benzinverbrauch eines Kfz auf 100 km berechnen. 

Dies lässt sich nach folgender Formel durchführen: `Treibstoffmenge * 100 / gefahrene Strecke = Verbrauch pro 100km` 

Die gefahrene Strecke ergibt sich aus der Differenz vom KM-Stand beim letzten Tanken und neuen KM-Stand beim Auftanken. Erstellen Sie das dazugehörige Programm, das nach Eingabe von Anfangskilometerstand, Endkilometerstand und getankten Litern den Verbrauch berechnet und ausgibt.

### 13.2

#### 2)

Früher wurde das Normalgewicht berechnet aus der Körpergröße in Zentimetern - 100, das dazugehörige Idealgewicht lag bei Männern 10% darunter, bei Frauen minus 15%. 

Erstellen Sie ein Programm, das Größe und Geschlecht (m/w) abfragt und dann Normal- und Idealgewicht ausgibt. 

#### 6)

Für einen einfachen Taschenrechner soll es 3 (drei!) einzelne Eingaben geben: 
- Zahl1 
- Operator (+, -, x, /) 
- Zahl2 

Das Programm soll dann anhand des Operators die richtige Berechnung durchführen und das Ergebnis auf dem Bildschirm ausgeben. 

Achtung: Eine Division durch 0 ist nicht erlaubt und ist mit einer Fehlermeldung zu quittieren, es darf dann kein Ergebnis ausgegeben werden.

#### 8)

Nach Eingabe eines Gehalts und eines Kennbuchstabens (`S`tunde oder `W`oche oder `M`onat) wird das entsprechende Jahresgehalt ausgerechnet und ausgegeben. Das Jahr hat 52 Wochen, 12 Monate und 2080 Arbeitsstunden/Jahr sind zu leisten.

#### 12)

Es gelte folgende vereinfachte Steuertabelle: 
- 20% Steuern bei mehr als 10.000€ Einkommen; 
- 30% Steuern bei mehr als 25.000€ Einkommen; 
- 50% Steuern bei mehr als 50.000€ Einkommen; 
- Geringverdiener zahlen nur 10% Steuern. 

Eingegeben wird (nur) das Bruttogehalt. Erstellen Sie ein Programm zur Ermittlung und Ausgabe der Steuerlast und des Nettogehalts.

### 13.3

#### 2)

Geben Sie eine Liste der Umrechnungswerte für Temperaturen von Celsius in Fahrenheit `F = C° * 1,8 + 32` aus. Benutzen Sie dabei den Bereich von -50° bis +70° Celsius in 5°-Schritten.

#### 3)

Geben Sie die Quadratzahlen bis 10 aus, also 
- 1 x 1 = 1 
- 2 x 2 = 4 
- etc.

#### 4)

Erweitern Sie die vorige Aufgabe, dass daneben das jeweilige Kubik ausgegeben wird: 

- 1 x 1 x 1 = 1 
- 2 x 2 x 2 = 8 
- etc

#### 13)

Es sollen ein Anlagebetrag, ein Zinssatz (in %) und eine Stehzeit eingegeben werden. Das Programm gibt dann in einer Tabelle die Entwicklung des Kapitalzuwachses anschaulich in einer Tabelle aus. (Auf die Zahlenformatierung brauchen Sie noch nicht Rücksicht zu nehmen.) Beispiel: Kapital 1000 Euro, Zinssatz 3 % auf 5 Jahre angelegt

<table>
  <tr>
    <th>Jahre</th>
    <th>Kapital</th>
    <th>Zinsen</th>
    <th>Neues Kapital</th>
  </tr>
<tr>
  <td>1</td>
  <td>1000,00</td>
  <td>30,00</td>
  <td>1030,00</td>
</tr>
<tr>
  <td>2</td>
  <td>1030,00</td>
  <td>30,90</td>
  <td>1060,90</td>
</tr>
<tr>
  <td>3</td>
  <td>1060,90</td>
  <td>31,83</td>
  <td>1092,73</td>
</tr>
<tr>
  <td>4</td>
  <td>1092,73</td>
  <td>32,78</td>
  <td>1125,51</td>
</tr>
<tr>
  <td>5</td>
  <td>1125,51</td>
  <td>33,77</td>
  <td>1159,27</td>
</tr>
</table>

### 13.5

#### 1)

Ein Array `werte` hat folgende Inhalte: 
```php
$werte = array(13, -4, 82, 17);
```

 Erzeugen Sie ein zweites Array `doppelt`, in derselben Größe wie `werte` und weisen Sie jedem Element in `doppelt` den doppelten Wert des entsprechenden Elementes in `werte` zu.

#### 2)

Jetzt Werte in umgekehrter Reihenfolge in das Ergebnis-Array kopieren `werte={13,-22,82,17}` ➡️ `ergebnis={… ? …}`

#### 3)

Schreiben Sie ein Programm, das in einem Array die Zahl 13 (oder eine beliebige Eingabe) sucht. 

Als Ergebnis soll die Position in dem Array bestimmt werden. Sollte das Programm die Zahl nicht finden, soll das Ergebnis der Suche -1 sein. 
Beispielarray: `werte={2,4,13,-4,82,17}`

#### 4)

Füllen Sie ein Array mit 50 Zufallszahlen (zum Beispiel zwischen 1 und 100). Erstellen Sie ein Programm, dass die Summe aller geraden Werte, die Summe aller ungeraden Werte und die Summe aller Werte berechnet.

## Vorlesung

### 11.29

Variablen und Laufzeitzuweisung des Datentyps

### 11.30

- Kleines 1x1, Ausgabe in Tabellenform
- Formularverarbeitung
- Ausgabe der Kubikzahlen in Tabellenform
- Ausgabe der Quadratzahlen in Tabellenform

### 12.01

- Array...
  - mit unterschiedlichen Datentypen
  - mit Zufallszahlen
  - sortieren
  - Minimum, Maximum und Durchschnitt

### 12.04

- assoziative Arrays...
  - iterieren
  - index suchen, value ausgeben
  - sortieren

#### Aufgaben

##### 1)

Füllen Sie ein Array mit 100 Zufallszahlen zwischen 10 und 1579 und geben Sie diese sortiert wieder aus in einer HTML-Tabelle, dabei soll jede zweite Zeile einen farbigen Hintergrund haben.

##### 2)

Geben Sie Schlüssel und Werte des Systemarrays $_SERVER aus; je Schlüssel/Wert eine Zeile!

##### 3)

Ein assoziatives Array enthält Autokennzeichen und die dazugehörigen Zulassungsbezirke. Nach Eingabe des Autokennzeichens wird der komplette Name des Zulassungsbezirkes ausgegeben oder eine Fehlermeldung, dass der Wert nicht gefunden wurde. br Erstellen Sie den HTML-Code für die Seite mit dem Formular und das PHP-Programm.

Beispiel:
- HH für "Hansestadt Hamburg"
- OWL für "Ostwestfalen-Lippe"

##### 4)

Es sollen für neue User initiale Passworte generiert werden. Füllen Sie dazu ein Array mit Buchstaben (ideal: große und kleine Buchstaben, aber z.B. kein i/l/O/0 wegen Verwechselungsgefahr) und Zahlen und "ziehen" Sie je 10 Zeichen (oder eine beliebige Zahl zwischen 8 und 15) daraus für ein systemgeneriertes Passwort. <br><br>
Tipp:
Für das schnelle Erstellen von Arrays eignet sich die Funktion `explode()` extrem gut!

##### 5)

Der User gibt (in einem HTML-Formular) einen Satz ein.
Ihr Programm zerlegt den Satz in einzelne Worte und gibt den Satz wortweise wieder aus, je
Zeile ein Wort.

##### 6)

Der User gibt (in einem HTML-Formular) einen Satz ein.
Ihr Programm zerlegt den Satz in einzelne Worte und gibt den Satz wortweise wieder aus, je
Zeile ein Wort. <br>
Der Satz der vorherigen Aufgabe wird wortweise rückwärts ausgegeben,
Beispiel: "das ist ein haus" wird "haus ein ist das"

##### 7)

Die Phrasendreschmaschine (hatten wir schonmal)
Füllen Sie drei Arrays mit jeweils den Satzteilen Subjekt, Prädikat, Objekt. Ein Programm
kombiniert daraus über zufällige Zugriffe auf die Arrays ganze Sätze.

##### 8)

Geben Sie die 6 Lottozahlen und die Superzahl der nächsten Ziehung in einer HTML-Tabelle sortiert aus.

### 12.05

- Datum
  - Verarbeitung Deutsches Format

#### Aufgaben

##### 1)

Geben Sie das Monatsarray aus unserer Datumaufgabe sortiert nach Werten aus als HTML-"Bullet-List"

##### 2)

Geben Sie das Wochentagsarray aus unserer Datumaufgabe nach Indexen sortiert aus als nummerierte Liste in HTML.

##### 3)

Geben Sie das Wochentagsarray aus unserer Datumaufgabe nach werten rückwärts sortiert aus als nummerierte Liste in HTML, dabei sollen alle Texte in GROSSBUCHSTABEN rückwärts ausgeben werden. (Tipp: Stringfunktionen in PHP)

##### 4)

Erstellen Sie ein einfaches User-Login-Formular (als HTML-Datei) mit Passworteingabe für mehrere User.
Dazu werden Username und Passwort in der PHP-Datei in einem assoziativen Array gespeichert:
- Index: Username /
- Wert: Passwort.

Bei erfolgreichem Login werden die User begrüßt, und es werden 2 Verweise zu anderen Seiten
angezeigt; im Fehlerfalle ist eine entsprechende Meldung auszugeben und ein Zurück-Verweis zurück auf
die Loginseite.

##### 5)

Speichern Sie 5 Pfade zu Bildern (lokal oder Web) in einem Array und erstellen Sie daraus eine
Bildergalerie. Dazu soll aus jedem Array-Element ein HTML-IMG-Tag generiert werden.

##### 6)

Sie finden im Skript "php-kurs-ebook..." etwas besseres:
Eine Bildergalerie dynamisch aus einem Verzeichnis auf dem Server erstellen. Auch hier werden die
Dateiname Strings in einem Array eingelesen.

### 12.06

- Funktionen

#### Aufgaben

##### 1)

Erstellen Sie den Code für die Funktion "euro()" zur Umrechnung eines DM-Betrages in Euro; ein Euro entspricht 1,95583 DM

##### 2)

Eine (eigene) Funktion `fakul()` berechnet die Fakultät einer übergebenen Zahl

##### 3)

Eine Funktion soll das Teilen mit Rest (z.B. 14 : 3 = 4 Rest 2) realisieren. Dazu werden zwei Zahlen übergeben und die Funktion gibt einen String als Ergebnis zurück.

Eine Division durch 0 soll mit einer Fehlermeldung (als Rückgabe!) quittiert werden.

##### 4)

Erstellen Sie eine Funktion "Pruef", welche true zurückgibt, wenn eine übergebene Zahl
eine gerade Zahl ist. <br>
<b>Hinweis:</b> true/false-Werte können nur indirekt über ein "IF" ausgeben werden.

##### 5)

Erstellen Sie eine Funktion `test_ipv4()`, die Ihnen eine zufällige IP für Tests generiert.
Hilfe: 192.168.2.124 = 4 "Oktetts, jeweils mit Werten von 0-255.

##### 6)

Eine Funktion "WorteZaehlen() bekommt einen Satz übergeben und gibt die Anzahl der Wörter in dem Satz zurück.

##### 8)

Eine Funktion "intervall" bekommt zwei ganze Zahlen a und b übergeben und gibt
dann die Summe aller ganzen Zahlen in diesem Bereich (intervall) zurück. <br>
Beispiel: <br>
intervall(3, 7) ➡️ 3 + 4 + 5 + 6 + 7 = 25 <br>
intervall(20, 24) ➡️ 20 + 21 + 22 + 23 + 24 = 110

##### 9)

Eine Funktion "umrechnen()" soll zu einer übergebenen Zahl die Binär, Oktal und Hexdezimal-Werte zurückgeben (als Text/String) <br>
Beispiel:
- Aufruf: umrechnen(5)
- Rückgabe: 5 ist binär

##### 10)

Erstellen Sie eine eigene Schaltjahresfunktion, die anhand einer übergebenen Jahreszahl ein True (für Schaltjahr) oder False (kein Schaltjahr) zurückgibt.

### 12.07

- Funktionen mit variabler Parameteranzahl

#### Aufgaben

##### 1)

Es fehlt in PHP leider eine Funktion `array_avg()`, die aus mehreren übergebenen Werten denDurchschnitt berechnet. Erstellen Sie bitte die Funktion.

##### 2)

Erstellen Sie eine Funktion `datum()`, die Ihnen eine zufällige Datumswerte in der Form tt.mm.jjjj für Tests generiert. <br> 
<b>Erweiterung:</b><br> Alle Datumswerte müssen gültig sein, es darf also beispielsweise keinen 31.04, 31.11.2023 oder einen 30.02.1999 geben.

##### 3)

Erstellen Sie eine Funktion `uhrzeit()`, die Ihnen eine zufällige Uhrzeit für spätere Testdaten generiert. Eine Gültige Uhrzeit liegt zwischen 00:00 Uhr und 23:59 Uhr.

##### 4)

Die PHP-Funktion "is_numeric" kann immer nur eine Variable auf einen gültigen Inhalt prüfen. Erstellen Sie eine Funktion `arr_numeric()`, die prüft, ob in einem übergebenen Array alle Werte numerisch sind. <br>
Im Erfolgsfall gibt die Funktion `true` zurück, sonst `false` <br>
<b>Hinweis:</b>
true/false-Rückgabewerte können (im Hauptprogramm) nur indirekt über eine IF-Bedingung
ausgeben werden.

##### 5)

Erstellen Sie eine Funktion `Caesar(text, schluessel)`, die einen übergeben Text nach der cäsarischen Verschlüsselung codiert zurückgibt. <br>
<b>Beispiel:</b> caesar("affe",3) liefert "diih", d.h. zum Ascii-Wert von a werden 3 addiert und danndas Zeichen zurückgegeben, das gleiche jeweils für f und e... <br>
Beachten Sie aber den "Sprung" nach vorn bei der Verschlüsselung von "z" etc.

##### 6)

Erstellen Sie eine Funktion `checkit()`. Diese soll folgendes leisten: <br>
<ul>
<li>Wird eine Zahl übergeben, ist aus dieser Zahl die Wurzel zu ziehen und zurückzugeben.</li>
<li>Wird ein Text übergeben, so ist die Anzahl Zeichen in diesem Text zu zählen und zurück-
zugeben.</li>
<li>Werden 2 oder mehr Zahlen übergeben, ist der Durchschnitt zurück zu geben.</li>
<li>Wird nichts übergeben, ist der Wochentag (deutsch ausgeschrieben) von Weihnachten
zurückzugeben <br> Beispiel: "Der 24.12. fällt dieses Jahr auf einen Mittwoch."</li>
</ul>

##### 7)

Erstellen Sie eine Funktion `super()`. Diese soll folgendes leisten:
<ul>
<li>Wird nichts übergeben, ist das Tagesdatum in "deutscher Form" mit ausgeschriebenem
Monat zurückzugeben.</li>
<li>Wird eine Zahl übergeben, ist aus dieser Zahl die Wurzel zu ziehen und zurückzugeben.</li>
<li>Werden 2 Zahlen übergeben, ist die erste Zahl durch die zweite zu teilen und das Ergebnis zurückzugeben.</li>
<li>Werden mehr als 2 bis 5 Zahlen übergeben, ist das Minimum zurück zu geben.</li>
</ul>

### 12.08

- Begrüßen Sie den Besucher Ihrer Webseite mit Namen und tageszeitabhängigem Gruß:
Guten Morgen / Guten Tag/ Guten Abend / Nanu, immer noch wach?
- Geben Sie in einem Formularfeld beliebig viele Zahlen durch Komma getrennt ein, 
und lassen Sie von einem Programm zählen, wie viele Werte es waren.

### 12.11

- Gaestebuch
- Zähler
- i|o in Textdatei

#### Aufgaben

##### 1)

Erstellen Sie ein Gästebuch, so dass User auf Ihrer Webseite Kommentare
hinterlassen können. Die User sollen in einem HTML-Formular ihren Namen,
Mailadresse und einen Kommentar (textarea!) eingeben, zusätzlich speichern Sie
bitte Datum, Uhrzeit und die (virtuelle) IP zu jedem Eintrag.

##### 2)

Stellen Sie das Gästebuch chronologisch rückwärts (aktuelle Einträge vorn) auf
der Webseite in optisch ansprechender Form dar.

##### 3)

Die externen Links in einer Webseite sollen dynamisch aus einer Vorlagendatei
erstellt werden. Dazu wird eine Textdatei mit 2 Feldern erstellt: Text, Ziel. <br>
Diese Datei ist mit PHP auszulesen und in einer Webseite sind die Links dann
daraus zu erstellen. <br>
<b>Beispiel:</b><br>
`Mein Haus#http://www.neuschwanstein.de/` <br>
`Mein Garten#http://www.plantenunblomen.de/` <br>
`Mein Auto#http://www.maybach.de/`

##### 4)

Geben Sie die Datei `kfz.csv` in einer zweispaltigen HTML-Tabelle (Spalten:
Kennzeichen, Zulassungsbezirk) aus.

##### 5)

Geben Sie die KFZ-Liste nach Zulassungsbezirken sortiert aus.

### 12.12

- csvDatei auslesen und Html-Datei Erzeugen
- Array key/value 

#### Aufgaben

##### 1)

Leider hat sich in der Datei <b>"Liste-Staedte-in-Deutschland.txt"</b> beim Speichern der Städte ein
Fehler eingeschlichen, bei Postleitzahlen mit führender Null fehlt genau diese Zahl, also statt
01067;Dresden steht dort nur 1067;Dresden ... <br>
Erstellen Sie ein PHP-Skript, dass die PLZ-Liste in eine neue, saubere Datei exportiert.

##### 2)

Geben Sie Plz, Ort und Bundesland der neuen Städteliste in einer übersichtlichen HTML-Tabelle aus.

##### 3)

Erstellen Sie eine Liste der deutschen Monatsnamen in einer Datei "monate.de", diese Datei soll für die Ausgabe des Monatstextes in ein Array eingelesen werden.

##### 4)

Erstellen Sie ebenfalls eine Datei für die Wochentage. Für diese Tage gilt allerdings der Zusatz, dass das entsprechende Array assoziativ sein soll und daher die englischen Tageskürzel mit im Datensatz sein müssen!

##### 5)

User können zur "Monatsnamenausgabe" die Sprache wählen und es wird eine entsprechende Datei benutzt. Erstellen Sie dazu Listen mit den Monatsnamen in jeweils einer anderen Sprache in einer Datei, also z.b. Dänisch.txt , Tuerkisch.txt, Franzoesisch.txt, Ungarisch.txt, etc. <br><br>
Alternativ kann man auch einen geschickten Datensatz basteln und wegschreiben bzw. auslesen <br>
<b>Beispiel:</b>
Januar#january#janvier#jannar#eanáir
Die jeweiligen Sprachen stehen dann immer in der gleichen Spalte...

### 12.13

- Login
- captcha-Verarbeitung
- Session-Verarbeitung

### 12.14

- Datenbankverarbeitung MySql

#### Aufgaben

1. SELECT-statement selbst eingeben
2. Artikelname (oder ein Teil wird eingegeben) und die passenden Daten angezeigt
3. optional:Tabelle kann gewählt werden

### 12.15

- Datenbankabfragen in Textdatei exportieren
- Datensätze anlegen

### 12.18

- MySql Datenbank
  - Datenbanund mit Tabellen und Spalten anlegen
  - Fremdschlüssel erstellen und mit Primärschlüssel verbinden
  - Abfragen mit `UNION` verknüpfen

#### Aufgaben

##### 1)

Erinnern Sie sich an die Postleitzahlendatei (stadtneu.txt), die Sie mit rein fünftselligen PLZ neu erstellt haben? Diese Datei importieren Sie bitte in unsere Nordwind-DB.
Dazu müssen Sie zuerst allerdings eine passende Tabelle erstellen, natürlich mit
"CREATE TABLE" per PHP-Skript!

##### 2)

Erstellen Sie die Datei `umsatz.txt`, die die Umsätze <b>aller</b> Kunden enthält.

##### 3)

Es sollen die Adressen (Firma, Straße, Plz, Ort, Land) aller Kunden aus Brasilien in die Datei `br.txt` exportiert werden. Trennzeichen zwischen den Feldern soll
die Raute `#` sein.

##### 4)


  Die externen Links in einer Webseite sollen dynamisch aus einer DB-Tabelle
  erstellt werden. Dazu wird eine Datenbanktabelle mit 2 Text-Feldern erstellt: Text
  varchar(30), Ziel varchar(200). <br>
  `Mein Haus#http://www.neuschwanstein.de/#Title`<br>
  `Mein Garten#http://www.plantenunblomen.de/#Title` ... <br>
  `Mein Auto#http://www.maybach.de/#Title` ... <br>


##### 5)

  Zur vorigen Aufgabe erstellen Sie natürlich eine Webseite, die die Links dann
  anzeigt ...

### 12.19

#### Aufgaben

##### 3)


Gegeben ist folgender Code
```php
$versuch [2] = 69;
$versuch [7] = 42;
$versuch [44] = 47. 11;
$versuch [12] = date ("Y");
$versuch [9] = 26;
```

Ist ein solches Array in PHP gültig?
- Geben Sie alle Elemente in einer "Bullet List" aus!
- Geben Sie das Array (Schlüssel und Werte) nach Inhalt numerisch sortiert
als HTML-Tabelle aus.

##### 4)


Was ist falsch am Funktionsaufruf:
```php
$huch()=69; 
```

Ist folgende Anweisungsfolge erlaubt?
```php
$hach=69;
$hach=true;
$hach = "7";
```

Was steht auf dem Bildschirm nach folgender Anweisung:
(Wert von $hach aus der vorigen Aufgabe!)
```php
echo "Wert von $hach: " ;
echo '$hach Euro' ;
```

##### 5)

Erstellen Sie NUR eine Funktion `km( )` die Schritte in Kilometer umrechnet. Die Anzahl der Schritte ist der erste Übergabeparameter, optional kann ein zweiter Wert mit der Schrittlänge (in cm) an die Funktion übergeben werden. <br>
Wird kein zweiter Wert übergeben, ist mit einer Default-Schrittlänge von 75 cm zu rechnen!

##### 6)

Erstellen Sie eine Funktion `vol()`
die aus 1 oder 3 übergebenen Werten das Volumen eines Quaders berechnet. <br> (Formel für das Volumen: `V = a * b * c`) <br><br>
Wird dabei nur 1 Wert übergeben, ist von einem Würfel auszugehen,
bei 3 Werten sei es ein Quader. <br><br>
Werden keiner, zwei oder mehr als drei Werte übergeben, ist `"Fehler"` zurückzugeben,
sonst das korrekte Ergebnis. <br> Eine zusätzliche Prüfung auf Übergabe von 0, negativen Werten
oder gar Texten ist nicht verlangt. <br><br>
<b>Aufrufbeispiele:</b>

```php
$z = vol($_GET["a"], $_GET["b"], $_GET["c"]);
echo vol($y);
echo vol();      // liefert "#Fehler"
$x = vol(1, $e); // liefert "#Fehler"
```


##### 7)

Füllen Sie ein ARRAY mit einigen Autokennzeichen und Städtenamen:
- B => Berlin
- HH => Hansestadt Hamburg
- HWI => Hansestadt Wismar
- MD => Magdeburg
- S => Stuttgart
- HRO => Hansestadt Rostock
- M => München
- MZ => Mainz
<ul>
<li>
  Geben Sie die Städtenamen alphabetisch aufsteigend sortiert wieder aus,
  je Stadt 1 Zeile. (als HTML "Bullet-List" oder nummerierte Liste)
</li>
<li>
  Geben Sie Autokennzeichen und Städtenamen nach Kennzeichen sortiert in einer kleinen HTML-Tabelle (mit 2 Spalten logischerweise) wieder aus.
</li>
<li>
  Exportieren Sie die Daten aus der Datei in eine sequentielle Datei "Kfz.txt",
  Feldtrenner soll die Raute("#") sein.
</li>
<li>
  <b>Extras:</b><br>
  Suchen Sie den Ort "Hamburg" (was sonst?!?) in dem Array, im Erfolgsfalle soll
  "Hummel Hummel!" ausgeben werden, ansonsten "So\'n Schiet aber ook!"
</li>
</ul>

### 12.20

#### Aufgaben

##### 4)

Erstellen Sie eine PHP-Funktion `divrest(a, b)`,
die das gute alte Teilen mit Rest, z.B. 14 : 3 = 4 Rest 2, realisiert. <br>

Dazu werden zwei Zahlen übergeben und die Funktion gibt einen String als Ergebnis zurück. Eine Prüfung auf negative Werte ist nicht verlangt, aber bei Division durch 0 ist "#DivByZero" zurückzugeben! <br>

Beispiele: 
```php
$erg = divrest(12, 5);	// 2 Rest 2
$erg = divrest(12, 4);	// 3 Rest 0 
echo divrest(8, 9);	    // 0 Rest 9 
echo divrest(888,0);	  //	"#DivByZero"
```


##### 6)

Erstellen Sie NUR eine Funktion `km()`, die Schritte in Kilometer umrechnet. Die Anzahl der Schritte ist der erste Übergabeparameter, optional kann ein zweiter Wert mit der Schrittlänge (in Meter) an die Funktion übergeben werden. <br>

Wird kein zweiter Wert übergeben, ist mit einer Default-Schrittlänge von 0,8 m zu rechnen! Weitere Fehlerprüfungen sind nicht verlangt.

##### 7)

Es wurden in einem HTML-Formlar beliebig viele Zahlen, durch Komma getrennt, eingegeben. Diese Werte werden über das Formularfeld "werte" an Ihr PHP-Programm übergeben. <br> <br>

Beispiel:	$_GET["werte"] enthält "8,14,37,4.571,964,47,28.5" <br><br>

Erstellen Sie je ein PHP-Skript-Fragment, das <br><br>

a)	das Feld $_GET["werte"] in ein neues Array $arrZ überträgt <br> <br>

b)	Den größten Wert, den kleinsten Wert und den Durchschnitt der Zahlen aus dem Array $ arrZ ermittelt und alle drei Werte ausgibt. <br>
(Betrachten Sie das Array als gefüllt, wenn Sie Teil 1 nicht gemacht haben!) <br> <br>

c)	Das neue Array $arrZ numerisch aufsteigend sortiert
und in einer "Bullet List"(je Element ein Aufzählungspunkt) wieder ausgibt <br>
(Betrachten Sie das Array als gefüllt, wenn Sie Teil 1 nicht gemacht haben!) <br><br>

Hinweis:	- Die Aufgabenteile können auch unabhängig voneinander gelöst werden!
- Fehlerprüfungen sind nicht gefordert. 

##### 8)

Wir möchten Kunden und Freunde unserer Unternehmung in Zukunft mit einem monatlichen Newsletter beglücken. Dazu können die User sich bei uns per HTML-Formular eintragen. <br> <br>

Die Daten sollen zeilenweise in die sequentielle Textdatei "adress.csv" eingetragen werden, je Eintrag eine Zeile, Feldseparator soll die Raute ("#") sein. Neben Name und Email soll auto- matisch auch das Eintragsdatum in der Form "tt.mm.jj – hh:mm" und die IP-Adresse gespei- chert werden. Erstellen Sie den dazugehörigen Code für die Datei "eintragen.php". <br><br>

Hilfe: Die IP der User liegt in `$_SERVER["REMOTE_ADDR"]`

##### 9)

Gegeben ist das folgende assoziative PHP-Array <br><br>

```php
$kurz = array(
  "de" => "Deutschland",
  "tv" => "Tuvalu",
  "ch" => "Schweiz",
  "hu" => "Ungarn",
  "es" => "Spanien",
  "uk" => "Großbritannien",
  "lv" => "Lettland"
);
```


a)	Erstellen Sie den PHP-Code zur Sortierung des Arrays $kurz
nach den Indexwerten (aufsteigend)
und <br><br>
b)	Erstellen Sie den PHP-Code zur Ausgabe der Indexe und Werte untereinander in einer einfachen HTML-Bullet-List aus. <br> <br>

c)	Das Array wird mit dem Befehl "sort($kurz);" sortiert. <br>

<b>Geben Sie Schlüssel und Inhalte an!
