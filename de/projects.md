{% include _init_page_variables.html %}
{% assign fig-count = 0 %}
# Meine Projekte aus den Bereichen Forschung &amp; Entwicklung (Auswahl)

Einige meiner Projekte habe ich online gestellt.  Insbesondere die
folgend aufgelisteten Projekte sind auf GitHub verfügbar.  Zu beachten
ist, dass diese Liste nur eine sehr kleine Auswahl aller meiner
Projekte darstellt, weil ich zum jetzigen Zeitpunkt noch nicht
sämtliche meiner Projekte für einer Veröffentlichung im Web
aufbereitet habe.

* [Kipppunkte](https://github.com/soundpaint/tipping-points)<br />
  Analyse und Visualisierung des Hystereseeffekts von Kippunkten, wie
  sie etwa beim Klimawandel relevant sind.  Implementiert als Java
  Swing-Anwendung.  Beitrag zum Begleitprogramm der ZKM-Ausstellung <a
  href="https://zkm.de/en/exhibition/2020/05/critical-zones">Critical
  Zones</a>.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/tipping-points/master/doc/images/screenshot_v0_1.png"
   caption="Bildschirmfoto „Tipping Points App, Version 0.1“"
%}

* [ML-Bibliothek](https://github.com/soundpaint/ml)<br /> Meine
  persönliche Variante einer minimalen, an TensorFlow angelehnten
  Bibliothek für maschninelles Lernen und mehr, implementiert in Java
  (in frühem Stadium; noch nicht produktiv einsetzbar).

* [VZ200/Z80-Emulator](https://github.com/soundpaint/VZ200-Emulator)<br
  /> Softwareemulation des 80er-Jahre-Homecomputers VZ200 mit Z80-CPU,
  implementiert in Java.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/VZ200-Emulator/master/src/doc/screenshots/screen.png"
   caption="Bildschirmfoto „VZ200 Emulator“"
%}

* [Kunstrahmen](https://github.com/soundpaint/art-frame)<br /> Eine
  kleine C++- / Qt-Anwendung, auf der eine (verfälschte)
  Partikelsimulation läuft.  Nützlich für die künstlerische
  Manipulation beliebig vorgegebener Ausgangsbilder.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/art-frame/master/doc/images/art-frame_at_poly.png"
   caption="Art Frame @ Poly Galerie"
%}

* [Respektomat](https://github.com/soundpaint/respektomat)<br /> Der
  _Respektomat_ ist (ein wenig in Anlehnung an ELIZA, aber deutlich
  einfacher gehalten) eine Implementierung eines Prozessors zur
  Verarbeitung natürlicher Sprache.  In der Kommunikation mit einem
  menschlichen Bediener der Software antworted das Programm stets mit
  Sätzen, die sich in irgendeiner Weise auf das Wort _Respekt_
  beziehen, dem Motto der Kunstausstellung, für die dieser Apparat
  ersonnen wurde.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/respektomat/master/doc/screenshots/screenshot_0001.png"
   caption="Bildschirmfoto „Respektomat V1.0“"
%}

* [Diskrete spektrale Transformation
  (DST)](https://github.com/soundpaint/dst)<br /> A Java-Bibliothek
  (und kleine Beispielanwendungen), die meine diskrete spektrale
  Transformation (DST) implementieren.  Meine DST ist konzipiert als
  Ersatz für die DFT in Situationen, in denen schnelle Veränderungen
  im Spektrum relevant sind.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/dst/master/media/spectrum_dst_0.99999.png"
   caption="Einschwingvorgang der DST"
%}

* [Maze](https://github.com/soundpaint/maze)<br /> Ursprünglich
  geplant als voll ausgearbeiteter Gegenentwurf des originalen, für
  den RaspBerry Pi erschienenen gleichnamigen kurzen Beispielprogramms
  zur Demonstration der Möglichkeiten des _Raspberry Pi Sense Hat_,
  führt diese Anwendung die Verwendung impliziter Funktionen als
  praktische and effiziente, doch zugleich unkonventionelle
  Herangehensweise ein, um das Spielfeld auf Basis komplexer Formen zu
  spezifizieren.  Implementiert in C++ and Qt.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/maze/master/docs/playing_field.png"
   caption="Bildschirmfoto „Maze“"
%}

* [Sphärische
  Ausdehnung](https://github.com/soundpaint/SphericalPropagation)<br
  /> Ein zellulärer Automat, in dem sich – im Gegensatz zu praktisch
  allen bekannten gängigen Automaten – ein anfänglicher Impuls gemäß
  euklidischer Norm ausbreitet, statt gemäß der sonst üblich
  anzutreffenden Summennorm.  Ursprünglich hatte ich diesen zellularen
  Automaten um das Jahr 1986 herum entwickelt mit dem erreichten Ziel,
  eine sphärische Ausdehnung in einer kartesichen Anordnung der Zellen
  zu erzielen.  Der Code der originalen Implementierung (auf
  Cassettenband) ging verloren, jedoch konnte ich den Algorithmus im
  Jahr 2007 rekonstruieren.  Der überraschend einfache Algorithmus
  weist Parallelen zu Ideen in den Maxwellschen Gleichungen auf
  (konkret: das gegenseitige Verhältnis von magnetischem zu
  elektrischem Feld).  Implementiert als Java Swing-Anwendung.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/SphericalPropagation/master/src/doc/screenshot.png"
   caption="Bildschirmfoto der Simulation der sphärischen Ausdehnung"
%}

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

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/imgsnd/master/doc/examples/1848-49/Verdruss.gif"
   caption="Graphische Notation des Stücks „Verdruss“"
%}

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

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/QuadCopHack/master/doc/images/img02.png"
   caption="Hardware-Modifikationen am Quadrocopter"
%}

* [SynGraph](https://github.com/soundpaint/syngraph)<br /> SynGraph
  ist ein Datenerfassungswerkzeug zur Sammlung von Daten zur Erfassung
  und Beschreibung personenindividueller graphemischer Synästhesie in
  der Form von Farbzuordnungen zu graphischen Symbolen (wie etwa
  Buchstaben oder Ziffern).  Das Werkzeug war gedacht für
  tiefergehende statistische Untersuchen im Bereich der
  humanbiologischen Synästhesie insbesondere auch mit dem
  längerfristigen Ziel, für mein Projekt SoundPaint Hinweise für
  sinnvolle Zuordnungen von Farben zu Klängen zu gewinnen.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/syngraph/master/src/doc/images/misc.png"
   caption="Bildschirmfoto „SynGraph“"
%}

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

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/SoundOntology/master/doc/images/SoundInstance.png"
   caption="Ontologische Beschreibung einer spezifischen Instanz eines Klangs"
%}

Für eine vollständige Liste aller meiner derzeit auf GitHub
verfügbaren Projekte siehe die [Liste meiner Repositories auf
GitHub](https://github.com/soundpaint?tab=repositories).

## Projektbeteiligungen (Auswahl)

Bei folgenden Projekten war ich Co-Autor bzw. mit inhaltlichen
Beiträgen beteiligt:

* [GNU LilyPond](https://lilypond.org)<br /> Meine Beiträge:
  u.a. historische Notation (Neumen, Ligaturen, Zeichensätze),
  zeitgenössische Notation (Clusters, Ambitus, Spezielle
  Notenzeichen).<br /><img
  src="https://lilypond.org/pictures/double-lily-modified3.png"
  alt="LilyPond Logo" style="width:160px" />

* [JavaParty](https://ps.ipd.kit.edu/english/180_461.php)<br /> Meine
  Beiträge: u.a. transparente Fäden.<br /><img
  src="https://svn.ipd.kit.edu/trac/javaparty/chrome/site/jp-logo-64.png"
  alt="JavaParty Logo" />

* [RFC 3253](https://tools.ietf.org/html/rfc3253)<br /><img
  src="https://www.researchgate.net/profile/James_Hunt6/publication/221554542/figure/fig1/AS:668975277039628@1536507543484/Typical-DeltaV-revision-graph.png"
  alt="Typical DeltaV Revision Graph" style="width:270px" />
