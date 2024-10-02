# Das Software Engineering Literatur-Repro

Auf diesem Repository finden Sie viele nützliche Links, Publikationen und Hinweise rund um meine 
Vorlesungsreihe Software Engineering. Diese Quellen-Sammmlung wird kontinuierlich 
und semesterübergreifend von mir gepflegt. Die aktuellen Folien zu der Vorlesung im aktuellen 
Semester finden Sie auf dem LEA-Kurs der jeweiligen Veranstaltung.
<br>
Diese Seite ist im Aufbau.

## Inhaltsverzeichnis
Das vorliegende Inhaltsverzeichnis orientiert sich an der thematischen Gliederung meiner 
Lehrveranstaltungen Software Engineering 1 und 2, welche ich an der Hochschule Bonn-Rhein-Sieg 
unterrichte.  
<!-- TOC -->
  * [Einführung ins Software Engineering](#einführung-ins-software-engineering)
  * [Software-Prozessmodelle im Software Engineering](#software-prozessmodelle-im-software-engineering)
  * [Modellierung und Erhebung von Anforderungen (Requirements Engineering Teil 1)](#modellierung-und-erhebung-von-anforderungen-requirements-engineering-teil-1)
    * [Modellierung von Use-Cases mit UML](#modellierung-von-use-cases-mit-uml)
  * [Objektorientierte Analyse von Anforderungen](#objektorientierte-analyse-von-anforderungen)
    * [Modellierung von Klassendiagrammen mit UML](#modellierung-von-klassendiagrammen-mit-uml)
    * [Objektorientiertes Analyse-Modell (OOA)](#objektorientiertes-analyse-modell-ooa)
  * [System Design (Grundlagen von Software-Architekturen)](#system-design-grundlagen-von-software-architekturen)
  * [Objektorientiertes Design (Grundlagen und Entwurfsmuster (Design Pattern))](#objektorientiertes-design-grundlagen-und-entwurfsmuster-design-pattern)
    * [Design Pattern (Entwurfsmuster)](#design-pattern-entwurfsmuster)
  * [Testen von Software (Grundlagen, Methoden und Tools)](#testen-von-software-grundlagen-methoden-und-tools)
    * [Testfall-Erzeugung](#testfall-erzeugung)
  * [Nachhaltigkeit von Software (Refactoring und Software-Wartung)](#nachhaltigkeit-von-software-refactoring-und-software-wartung)
  * [KI im Bereich Software Engineering](#ki-im-bereich-software-engineering)
  * [Wichtige SE-Tools (Case Tools)](#wichtige-se-tools-case-tools-)
    * [Tools zur Modellierung von UML-basierten Diagrammen](#tools-zur-modellierung-von-uml-basierten-diagrammen)
  * [Literaturverzeichnis](#literaturverzeichnis)
<!-- TOC -->

c/o Prof. Dr. Sascha Alda, H-BRS. Ist ein Link "kaputt"? Dann bitte E-Mail an mich: sascha.alda [at]
h-brs.de

## Einführung ins Software Engineering
Die in der Vorlesung erwähnten Zitate rund um agile Software-Entwicklung ("Speed is everything", 
"[The end of agile!](https://janbosch.com/blog/index.php/2023/08/07/summer-reflections-the-end-of-agile/)" stammen von [Prof. Dr. Jan Bosch](https://www.chalmers.se/en/persons/janbo/), einem bekannten Professor aus der Chalmers 
University of Technology in Schweden. Viele gute Beiträge von ihm kann man aus seinem [Blog](https://janbosch.com/blog/) entnehmen. 

## Software-Prozessmodelle im Software Engineering

Das Wasserfallmodell wurde in einer ursprünglichen Version von den Software-Entwickler Royce 
vorgestellt [(Royce, 1970)](/papers/Royce,%201970.pdf). Das hier beschriebene Ablaufmodell mit 
dem Charakter eines Wasserfalls wird 
im Prinzip heute noch verwendet, lediglich haben sich die Bezeichnungen der Phasen geändert. 
Rücksprünge sind tatsächlich bei Royce schon vorgesehen - anders als in Industrie-Projekten, bei 
denen aus organisatorischen Gründen ein Rücksprung nicht mehr vorgesehen werden kann.  

Ein sehr guter und aktueller Vergleich zwischen Wasserfallmodell und modernen agilen 
Entwicklungsmodellen findet sich in dem guten Aufsatz von [(Mishra und Alzoubi, 2023)](/papers/Mishra%20und%20Azoubi%202023.pdf)).

## Modellierung und Erhebung von Anforderungen (Requirements Engineering Teil 1)
### Modellierung von Use-Cases mit UML
Für die Modellierung von Use-Cases (dt: Anwendungsfälle) haben sich UML-basierte 
Use-Case-Diagramme bewährt. Einen sehr guten Überblick liefert das Buch von Christin Rupp (Rupp, 
2012). 

## Objektorientierte Analyse von Anforderungen
### Modellierung von Klassendiagrammen mit UML
Für die Modellierung von Klassen haben sich UML-basierte
Klassen-Diagramme bewährt. Einen sehr guten Überblick liefert das Buch von Christin Rupp (Rupp,
2012).

### Objektorientiertes Analyse-Modell (OOA)
Das OOA abstrahiert von Anforderungen und liefert ein erstes Modell in Richtung der 
Implementierung. Das OOA wird auch als [Robustness Diagram](https://en.wikipedia.org/wiki/Entity-control-boundary) bezeichnet.
Assoziationen zwischen den Analyse-Klassen werden bei Brügge und Dutoit (2013) auf S. 211 
eingeführt, dies allerdings eher auf einem abstraken Niveau. Für eine praktische Anwendung muss man weitere Regeln beachten, die 
sich aus der Verwendung von [DTOs](https://martinfowler.com/eaaCatalog/dataTransferObject.html), 
aus den Annahmen von [Robustness-Diagrammen](https://en.wikipedia.org/wiki/Entity-control-boundary)
sowie aus der Praxis z.B. durch die Verwendung von 
[ORM-Technologien](https://de.wikipedia.org/wiki/Objektrelationale_Abbildung) ergeben. Diese Regeln führe ich meiner Vorlesung in Kapitel 4 ein.

## System Design (Grundlagen von Software-Architekturen)
Der Klassiker im Bereich Software-Architekturen ist und bleibt das sehr gute Buch von Gernot 
Starke, welches mittlerweile in der 10. Auflage erschienen ist (Starke, 2024). Dies sollte in 
jedem gut sorierten Bücherregal zu finden sein ;-) Falls kein Bücherregal vorhanden, dann kann man sich auch eine Online-Version 
anschauen ([Link in Bib](https://bib-discover.bib.h-brs.de/permalink/49HBZ_BRS/1hl68vi/alma991001257049706452)).


Einer der ersten Artikel über Software-Architekturen: [(Garlan and Shawn, 1994)](papers/Garlan%20and%20Shaw%201994.pdf).

## Objektorientiertes Design (Grundlagen und Entwurfsmuster (Design Pattern))


### Design Pattern (Entwurfsmuster)
Das primäre Werk um die Thematik Design Pattern ist das berühmte Buch der [GoF](https://springframework.guru/gang-of-four-design-patterns/)-Autoren, allen voran 
[Erich Gamma](https://de.wikipedia.org/wiki/Erich_Gamma). Leider gibt es von dem Buch nur die 
erste Version, weitere Versionen wurden nie veröffentlicht. Es gibt aber eine Vielzahl von guten 
Sekundar-Quellen und Online-Quellen:

- [Seite](https://refactoring.guru/design-patterns) von Refacotoring Guru (sehr gute Darstellung 
  mit gute Code-Beispielen)


## Testen von Software (Grundlagen, Methoden und Tools)
### Testfall-Erzeugung
Die Anzahl Testfälle kann bei komplexen Anwendungssystemen aufgrund von vielfachen
Eingabe-Möglichkeiten (z.B. bei der Registrierung eines Benutzers) enorm groß werden. Eine Methode
zur Reduktion der Eingabe-Werte und somit zur Reduktion der Testfälle ist die Bildung von [Äquivalenzklassen](https://de.wikipedia.org/wiki/%C3%84quivalenzklassentest). Aus Äquivalenzklassen, welche
Eingabe-Werte zu einem Eingabe-Datum unterteilen, werden dann im nächsten Schritt konkrete
Testfälle abgeleitet.  Dazu werden sowohl gültige als auch ungültige Eingabe-Werte betrachtet.
Daraus können dann [Positiv-Testfälle](https://www.techtarget.com/searchsoftwarequality/tip/Positive-vs-negative-testing-Differences-and-examples) und [Negativ-Testfälle](https://de.wikipedia.org/wiki/Negativtest) abgeleitet werden. Eine sehr gute
Beschreibung liefert das Buch von Spillner und Linz (2019), hier vor allem
der [(Abschnitt 5.1)](/papers/Spillner%20und%20Linz,%202019,%20Kapitel%205-1%20Black%20Box%20Test.pdf)

## Nachhaltigkeit von Software (Refactoring und Software-Wartung)
tbc

## KI im Bereich Software Engineering
Ein kompletter Roundtrip von der Analyse von Anforderugen bis hin zur Auslieferung von Software 
mit Hilfe von KI-Tools wie [ChatGPT](https://chatgpt.com/auth/login) oder diverser Co-Pilot-Tools (z.B. [GitHub-CoPilot](https://github.com/features/copilot)) ist 
aktuell noch eine Illusion. Die Abbildung von informellen Wissen aus "den Köpfen der Kunden" auf 
formale Konstrukte (z.B. UML oder Java-Code) wird auf in Zukunft viele manuelle Aufgabe mit sich 
ziehen, die man im Software Engineering lernen muss. Ein visionäres Paper, wie so ein 
KI-unterstützer RoundTrip eines Software-Projektes aussehen könnte, liefert das Paper 
([Abdelfattah et al., 2024](/papers/Roadmap_for_Software_Engineering_Education_using_ChatGPT.pdf)).   

## Wichtige SE-Tools (Case Tools) 
### Tools zur Modellierung von UML-basierten Diagrammen

**Draw.io (heißt mittlerweile: Diagrams)**<br>
Schlankes browser-basiertes Tool, keine Installation auf ihrem Rechner notwendig! Abspeicherung der Dokumente in verschiedenen Formen möglich (Lokal, Cloud). Läuft nativ ohne Plugin auf allen gängigen Browsern.
<br>
Quelle: https://app.diagrams.net/


## Literaturverzeichnis

Hier eine Auflistung der wichtigen Quellen, die für das Software Engineering relevant sind. 

Brass, L. et al.: _Software Architecture in Practice_. Addison Wesley; 4. Edition. 2021.
<br>
Bruegge, B.; Dutoit, A.H.: _Object-Oriented Software Engineering_. 3. Auflage, Prentice-Hall, 2013.
<br>
Rupp, Christin: _UML 2 glasklar: Praxiswissen für die UML-Modellierung_. Carl Hanser Verlag GmbH & 
Co. KG; 4 Edition, 2012.
<br>
Sommerville, Ian: _Software Engineering_. Pearson Studium; 10., aktualisierte Edition, 2018.
<br>
Starke, Gernot: _Effektive Software-Architekturen – Ein praktischer Leitfaden_. 10. Auflage, Hanser 
Verlag, 2024. (Anmerkung: auch die früheren Auflagen sind sehr gut und werden häufig verwendet)
<br>



