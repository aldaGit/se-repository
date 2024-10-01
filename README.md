# Das Software Engineering Literatur-Repro

Auf diesem Repository finden Sie viele nützliche Links, Publikationen und Hinweise rund um meine 
Vorlesungsreihe Software Engineering. Diese Quellen-Sammmlung wird kontinuierlich 
und semesterübergreifend von mir gepflegt. Die aktuellen Folien zu der Vorlesung im aktuellen 
Semester finden Sie auf dem LEA-Kurs der jeweiligen Veranstaltung.

## Inhaltsverzeichnis
Das vorliegende Inhaltsverzeichnis orientiert sich an der thematischen Gliederung meiner 
Lehrveranstaltungen Software Engineering 1 und 2, welche ich an der Hochschule Bonn-Rhein-Sieg 
unterrichte.  
<!-- TOC -->
  * [Inhaltsverzeichnis](#inhaltsverzeichnis)
  * [Software-Prozessmodelle im Software Engineering](#software-prozessmodelle-im-software-engineering)
  * [Modellierung und Erhebung von Anforderungen (Requirements Engineering Teil 1)](#modellierung-und-erhebung-von-anforderungen-requirements-engineering-teil-1)
  * [Objektorientierte Analyse von Anforderungen](#objektorientierte-analyse-von-anforderungen)
    * [Objektorientiertes Analyse-Modell (OOA)](#objektorientiertes-analyse-modell-ooa)
  * [System Design (Grundlagen von Software-Architekturen)](#system-design-grundlagen-von-software-architekturen)
  * [Objektorientiertes Design (Grundlagen und Entwurfsmuster (Design Pattern))](#objektorientiertes-design-grundlagen-und-entwurfsmuster-design-pattern)
    * [Design Pattern (Entwurfsmuster)](#design-pattern-entwurfsmuster)
  * [Testen von Software (Grundlagen, Methoden und Tools)](#testen-von-software-grundlagen-methoden-und-tools)
    * [Testfall-Erzeugung](#testfall-erzeugung-)
  * [Nachhaltigkeit von Software (Refactoring und Software-Wartung)](#nachhaltigkeit-von-software-refactoring-und-software-wartung)
  * [Wichtige SE-Tools (Case Tools)](#wichtige-se-tools-case-tools-)
    * [Tools zur Modellierung von UML-basierten Diagrammen](#tools-zur-modellierung-von-uml-basierten-diagrammen)
  * [Literaturverzeichnis](#literaturverzeichnis)
<!-- TOC -->

c/o Prof. Dr. Sascha Alda, H-BRS. Ist ein Link "kaputt"? Dann bitte E-Mail an mich: sascha.alda [at]
h-brs.de

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
tba

## Objektorientierte Analyse von Anforderungen
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

## Wichtige SE-Tools (Case Tools) 
### Tools zur Modellierung von UML-basierten Diagrammen

**Draw.io (heißt mittlerweile: Diagrams)**<br>
Schlankes browser-basiertes Tool, keine Installation auf ihrem Rechner notwendig! Abspeicherung der Dokumente in verschiedenen Formen möglich (Lokal, Cloud). Läuft nativ ohne Plugin auf allen gängigen Browsern.
<br>
Quelle: https://app.diagrams.net/


## Literaturverzeichnis

Brass, L. et al.: Software Architecture in Practice. Second Edition. 2003.
<br>
Bruegge, B.; Dutoit, A.H.: Object-Oriented Software Engineering. 3. Auflage, Prentice-Hall, 2013.
<br>
Sommerville, Ian: Software Engineering 8. Addison-Wesley. 2007
<br>
Starke, Gernot: Effektive Software-Architekturen – Ein praktischer Leitfaden. 10. Auflage, Hanser 
Verlag, 2024. (gelegentlich werden auch frühere Auflagen zitiert)
<br>



