# Meine Projekte aus den Bereichen Forschung &amp; Entwicklung

Einige meiner Projekte habe ich online gestellt.  Insbesondere die
folgend aufgelisteten Projekte sind auf GitHub verfügbar.  Zu beachten
ist, dass diese Liste nur eine sehr kleine Auswahl aller meiner
Projekte darstellt, weil ich zum jetzigen Zeitpunkt noch nicht
sämtliche meiner Projekte für einer Veröffentlichung im Web
aufbereitet habe.

* [Kipppunkte](https://github.com/soundpaint/tipping-points)<br />
  Analyse und Visualisierung des Hystereseeffekts von Kippunkten, wie
  sie etwa beim Klimawandel relevant sind.  Implementiert als Java
  Swing-Anwendung.

* [ML-Bibliothek](https://github.com/soundpaint/ml)<br /> Meine
  persönliche Variante einer minimalen, an TensorFlow angelehnte
  Bibliothek für maschninelles Lernen und mehr, implementiert in Java
  (in frühem Stadium; noch nicht produktiv einsetzbar).

* [VZ200/Z80-Emulator](https://github.com/soundpaint/VZ200-Emulator)<br
  /> Softwareemulation des 80er-Jahre-Homecomputers VZ200 mit Z80-CPU,
  implementiert in Java.

* [Kunstrahmen](https://github.com/soundpaint/art-frame)<br /> Eine
  kleine C++- / Qt-Anwendung, auf der eine (verfälschte)
  Partikelsimulation läuft.  Nützlich für die künstlerische
  Manipulation beliebig vorgegebener Ausgangsbilder.

* [Respektomat](https://github.com/soundpaint/respektomat)<br /> Der
  _Respektomat_ ist (ein wenig in Anlehnung an ELIZA, aber deutlich
  einfacher gehalten) eine Implementierung eines Prozessors zur
  Verarbeitung natürlicher Sprache.  In der Kommunikation mit einem
  menschlichen Bediener der Software antworted das Programm stets mit
  Sätzen, die sich in irgendeiner Weise auf das Wort _Respekt_
  beziehen, dem Motto der Kunstausstellung, für die dieser Apparat
  ersonnen wurde.

* [Diskrete spektrale Transformation
  (DST)](https://github.com/soundpaint/dst)<br /> A Java-Bibliothek
  (und kleine Beispielanwendungen), die meine diskrete spektrale
  Transformation (DST) implementieren.  Meine DST ist konzipiert als
  Ersatz für die DFT in Situationen, in denen schnelle Veränderungen
  im Spektrum relevant sind.

* [Maze](https://github.com/soundpaint/maze)<br /> Ursprünglich
  geplant als voll ausgearbeiteter Gegenentwurf des originalen, für
  den RaspBerry Pi erschienenen gleichnamigen kurzen Beispielprogramms
  zur Demonstration der Möglichkeiten des _Raspberry Pi Sense Hat_,
  führt diese Anwendung die Verwendung impliziter Funktionen als
  praktische and effiziente, doch zugleich unkonventionelle
  Herangehensweise ein, um das Spielfeld auf Basis komplexer Formen zu
  spezifizieren.  Implementiert in C++ and Qt.

* [Sphärische
  Ausdehnung](https://github.com/soundpaint/SphericalPropagation)<br
  /> A zellulärer Automat, in dem sich – im Gegensatz zu praktisch
  allen bekannten gängigen Automaten – ein anfänglicher Impuls sich
  gemäß euklidischer Norm ausbreitet, statt gemäß der sonst üblich
  anzutreffenden Summennorm.  Ursprünglich hatte ich diesen zellularen
  Automaten um das Jahr 1986 herum entwickelt mit dem erreichten Ziel,
  eine sphärische Ausdehnung in einer kartesichen Anordnung der Zellen
  zu erzielen.  Der Code der originalen Implementierung (auf
  Cassettenband) ging verloren, jedoch konnte ich den Algorithmus im
  Jahr 2007 rekonstruieren.  Der überraschend einfache Algorithmus
  weist Parallelen zu Ideen in den Maxwellschen Gleichungen auf
  (konkret: das gegenseitige Verhältnis von magnetischem zu
  elektrischem Feld).  Implementiert als Java Swing-Anwendung.

* [ImageSound](https://github.com/soundpaint/imgsnd)<br /> ImageSound
  war die (nun schon seit langer Zeit nicht mehr weiter entwickelten)
  ursprüngliche Version einer Serie von Algorithmen zur
  Bild-zu-Ton-Wandlung, entwickelt um 1997 herum, in freier Anlehnung
  an bestehende Systeme graphischer Musiknotation.  Die Umwandlung
  berücksichtigt ausschließlich die Helligkeitsinformation im Bild,
  ignoriert aber Farbton und Farbsättigung.  ImageSound war die Basis
  für spätere Projekte, darunter der direkte Nachfolger _SoundPaint_,
  der eine sinnvolle Nutzung der vollständigen Farbinformation durch
  die Verwendung einer linearen Matrixtransformation für die
  Umwandlung zwischen Farbraum und einem dreidimensionalem Raum von
  Klangeigenschaften nutzte, wie auch die später folgende _Klangsäule_
  (_SoundColumn_), die den weiteren Schritt vom flachen Bild zur
  Analyse der Bildprojektion auf eine sich zyklisch drehenden Säule
  ging.

* [QuadCopHack](https://github.com/soundpaint/QuadCopHack)<br />
  Dieses Projekt ergab sich quasi als ein sportlicher Wettstreit, bei
  dem ich herausgefordert war, einen billigen 15$-Quadrocopter von
  Hand zu steuern, was fürchterlich schief ging.  Daraufhin
  modifizierte ich den Quadrocopter durch Anflanschen einer
  Steuerschnittstelle, die ich mit einem Arduino für die
  Signalverarbeitung auf Hardwareebene verband sowie einen damit
  verbundenen RaspBerry Pi als Anwedungsrechner ergänzte, auf dem eine
  von mir entwickelte Steuerungssoftware zur Aufzeichnung von
  Flugbewegungen über den Joystick des Quadrocopters sowie der
  Wiedergabe der aufgezeichneten Flugbewegungen läuft.

* [SynGraph](https://github.com/soundpaint/syngraph)<br /> SynGraph
  ist ein Datenerfassungswerkzeug zur Sammlung von Daten zur Erfassung
  und Beschreibung personenindividueller graphemischer Synästhesie in
  der Form von Farbzuordnungen zu graphischen Symbolen (wie etwa
  Buchstaben oder Ziffern).  Das Werkzeug war gedacht für
  tiefergehende statistische Untersuchen im Bereich der
  humanbiologischen Synästhesie insbesondere auch mit dem
  längerfristigen Ziel, für mein Projekt SoundPaint Hinweise für
  sinnvolle Zuordnungen von Farben zu Klängen zu gewinnen.

* [SoundOntology](https://github.com/soundpaint/SoundOntology)<br />
  Die von mir aufgestellte Klangontologie geht zurück auf das Jahr
  2005 und dürfte eine der ersten Bemühungen dieser Art sein.  Ziel
  war der Versuch, ein geeignetes semantisches Modell des in der Regel
  hochkomplexen technischen Synthesizer-Parks eines Musikers aus dem
  Bereich der elektronischen Musik zu schaffen, dessen beschreibender
  Charakter den effizienten und zielgerichten Umgang des Musikers mit
  seinen Anlagen auch bei nur durchschnittlichem Verständnis für die
  in den Synthesizern verbaute Technik ermöglicht, einschließlich des
  gezielten und reproduzierbaren Zugriffs auf einzelne Synthesizer,
  Instrumente, Klangpatches, Stimmen, Klangfarben, etc.  Die Ontologie
  ist in OWL (Web Ontology Language) implementiert.

Für eine vollständige Liste aller meiner derzeit auf GitHub
verfügbaren Projekte siehe die [Liste meiner Repositories auf
GitHub](https://github.com/soundpaint?tab=repositories).
