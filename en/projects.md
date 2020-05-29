{% include _init_page_variables.html %}
{% assign fig-count = 0 %}
# My R&amp;D Projects (Selection)

I have put some of my projects online.  In particular, I have made
available the following projects on GitHub.  Note that this is just a
small selection of all of my projects, since I do not yet have made
online available all projects.

* [Tipping Points](https://github.com/soundpaint/tipping-points)<br />
  An analysis and visualization of the hysteresis effect in tipping
  points as they appear in climate change.  Implemented as Java Swing
  application.  Contribution to the supporting programme of the ZKM
  exhibition <a
  href="https://zkm.de/en/exhibition/2020/05/critical-zones">Critical
  Zones</a>.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/tipping-points/master/doc/images/screenshot_v0_1.png"
   caption="Screenshot of Tipping Points App, Version 0.1"
%}

* [ml Library](https://github.com/soundpaint/ml)<br /> My own flavour
  of a minimal TensorFlow-like machine language library implemented in
  the Java language (work in progress; not yet useful) and beyond.

* [VZ200/Z80
  Emulator](https://github.com/soundpaint/VZ200-Emulator)<br /> A
  software emulation of the 1980's VZ200 computer with Z80 CPU,
  implemented in Java.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/VZ200-Emulator/master/src/doc/screenshots/screen.png"
   caption="Screenshot of VZ200 Emulator Screen"
%}

* [Art Frame](https://github.com/soundpaint/art-frame)<br /> A small
  C++ / Qt application running a fake particles simulation.  Useful
  for artful manipulation of arbitrary image content.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/art-frame/master/doc/images/art-frame_at_poly.png"
   caption="Art Frame @ Poly Galerie"
%}

* [respektomat](https://github.com/soundpaint/respektomat)<br /> The
  _Respektomat_ is a (ELIZA-inspired, but rather simple-minded)
  implementation of a natural language processor that communicates
  with a human, always anwering with sentences that somehow refer to
  the word _Respekt_, which was the title of the arts exhibition that
  this application was devised for.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/respektomat/master/doc/screenshots/screenshot_0001.png"
   caption="Respektomat V1.0 Screenshot"
%}

* [Discrete Spectral Transform
  (DST)](https://github.com/soundpaint/dst)<br /> A Java library (and
  small example applications) that implements my discrete spectral
  transformation (DST).  My DST is intended as DFT replacement
  particularly for situations when fast changes in spectrum _do_
  matter.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/dst/master/media/spectrum_dst_0.99999.png"
   caption="Transient Oscillation of DST"
%}

* [Maze](https://github.com/soundpaint/maze)<br /> Originally planned
  as a fully elaborated version of the RaspBerry Pi's original Maze
  demo application for the RPI's sense hat, this project features
  implicit functions as a convenient and efficient, yet quite
  unconventional method of specifying the game field's terrain with
  complex shapes.  Implemented in C++ and Qt.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/maze/master/docs/playing_field.png"
   caption="Maze Screenshot"
%}

* [SpheralPropagation](https://github.com/soundpaint/SphericalPropagation)<br
  /> A cellular automaton that – in contrast to almost all established
  cellular automaton – features spreading an initial pattern
  approximating Euclidian norm rather than sum norm.  I originally
  devised this cellular automaton around 1986, while looking how to
  approximate creation of perfect circles with cellular automatons,
  but then lost the original code, and re-invented it in 2007.  The
  automaton's rather simple set of rules somewhat resemble certain
  aspects of Maxwell's laws.  Implemented as Java Swing application.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/SphericalPropagation/master/src/doc/screenshot.png"
   caption="Screenshot of Spheric Propagation Simulation"
%}

* [imgsnd](https://github.com/soundpaint/imgsnd)<br /> ImageSound was
  the (now for long time abandoned) original version of my series of
  image-to-audio conversion algorithms, devised around 1997, somewhat
  mimicking graphical notation.  It only considered brightness, but
  ignored hue and saturation.  ImageSound was the origin for later
  projects, among them its immediate successor SoundPaint that
  featured full color information by using a linear matrix transform
  for conversion between color space and a three-dimensional space of
  sound properties, or SoundColumn, which made transition from flat
  on-screen image scan to cyclic scan of an image projected onto a
  rotating column.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/imgsnd/master/doc/examples/1848-49/Verdruss.gif"
   caption="Score Graphics of “Verdruss” (“Displeasure”) Item of Work"
%}

* [QuadCopHack](https://github.com/soundpaint/QuadCopHack)<br /> This
  project actually resulted from a contest when I was challenged to
  manually control a 15$-QuadCop, but heavily failed.  Instead, I
  hacked this QuadCop and pimped it with an interface to an Arduino
  for low-level signal processing and a RaspBerry Pi computer for
  high-level user control, including fully recording and replaying
  flight control actions applied to the original flight joystick.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/QuadCopHack/master/doc/images/img02.png"
   caption="Hardware Mods of QuadCop Hack"
%}

* [syngraph](https://github.com/soundpaint/syngraph)<br /> SynGraph is
  a data aquisition tool for collecting data about graphemic
  synesthete's individual mappings of characters (such as letters or
  digits) to colors.  It was devised as a tool for further research
  into synesthesia.  Note that the above mentioned SoundPaint project
  heavily depends on a useful color to sound mapping, which itself is
  also an issue in the field of synesthesia.

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/syngraph/master/src/doc/images/misc.png"
   caption="Screenshot of SynGraph"
%}

* [SoundOntology](https://github.com/soundpaint/SoundOntology)<br />
  The sound ontology, dating back to as early as 2005, was an attempt
  to properly model a musician's potentially complex and heterogenous
  set of synthesizer equipment in a way to efficiently manage access
  to all available synthesizer resources, such as instruments, sound
  patches, voices / timbres, sounds, etc.  The ontology is specified
  using the Web Ontology Language (OWL).

{% include _figure.html
   link="https://raw.githubusercontent.com/soundpaint/SoundOntology/master/doc/images/SoundInstance.png"
   caption="Ontological Description of Specific Instance of Sound"
%}

For a complete list of my projects currently available on GitHub, see
[my repositories on
GitHub](https://github.com/soundpaint?tab=repositories).

## Project Contributions (Selection)

I was co-author of / contributor to the following projects:

* [GNU LilyPond](https://lilypond.org)<br /> My contributions: ancient
  notation (neumes, ligatures, fonts), contemporary notation
  (clusters, ambits, special font glyphs), and more.<br /><img
  src="https://lilypond.org/pictures/double-lily-modified3.png"
  alt="LilyPond Logo" style="width:160px" />

* [JavaParty](https://ps.ipd.kit.edu/english/180_461.php)<br /> My
  contributions: transparent threads, and more.<br /><img
  src="https://svn.ipd.kit.edu/trac/javaparty/chrome/site/jp-logo-64.png"
  alt="JavaParty Logo" />

* [RFC 3253](https://tools.ietf.org/html/rfc3253)<br /><img
  src="https://www.researchgate.net/profile/James_Hunt6/publication/221554542/figure/fig1/AS:668975277039628@1536507543484/Typical-DeltaV-revision-graph.png"
  alt="Typical DeltaV Revision Graph" style="width:270px" />
