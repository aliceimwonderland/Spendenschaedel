<h1>
  <bold>Navigation</bold>
 
</h1>
  
  1.  Das Projekt <br>
    I   <a href="#Ideenfindung">Ideenfindung</a><br>
    II  <a href="#Konzeption">Konzeption</a><br>
    III <a href="#Wahl der Hardware">Wahl der Hardware</a><br>
    IV  <a href="#Wahl der Software">Wahl der Software</a><br>
 2. Entwicklung<br>
    I   <a href="#Stundenprotokoll">Stundenprotokoll</a><br>
    II  <a href="#Code">Code</a><br>
    III <a href="#Bau- und Schaltplan">Bau- und Schaltplan</a><br>
    IV  <a href="#Multimediaproduktion">Multimediaproduktion</a><br>
 3. Evaluation
    I   <a href="#Besucherreaktionen an Halloween">Besucherreaktionen an Halloween</a><br>
    II  <a href="#Technische Evaluation">Technische Evaluation</a><br>
    III <a href="#Persönliches Wachstum">Persönliches Wachstum</a><br>
 4. Quellen und Eigenständigkeitserklärung
  
<h1> 
<bold>Das Projekt</bold>
  
  <h2 id="Ideenfindung">Ideenfindung</h2><br>
  
Die Gestalter des Projektes, Alicia Gärtner und Rosalie Muchow, sind beide Teammitglieder des Halloweenhaus Schmalenbeck. In dem seit 10 Jahren stetig wachsenden, interdisziplinären & jungen Team bekommen beide einen vielfältigen Eindruck in den Themenbereichen Show- und Bühnendesign, Veranstaltungstechnik oder dem Bau von Audio Animatronics. Die Begeisterung für Audio Animatronics wurde neben dem Halloweenhaus auch bei gemeinsamen Freizeitparkbesuchen geformt. Besonders die unpräzisen 
Bewegungen günstiger Animatronics gefällt dem Duo gar nicht. Schnell wurde den Freunden klar, dass dieses Projekt eine hervorragende Möglichkeit ist, das Halloweenhaus mit einer technischen Neuheit zu bereichern. Bei einem kurzen Brainstorming Prozess erinnert sich das Team an den seit 2016 genutzten Spendenschädel, welchen Rosalie als unästhetisch und unauffällig empfindet. Zusätzlich ist dieser durch das Loch am Boden sehr unsicher gegen Diebstahl und für die steigenden Spendengelder zu klein.An diesem Punkt beschließt das Team, eine neue Version des Schädels zu bauen. Inspiriert von den Mülleimern im niederländischen Freizeitpark Efteling, welche „Papier hier“ rufen und sich nach dem erfolgreichen Einwurf bedanken, wird ein Konzept entworfen, welches alle Probleme des alten Schädels eliminieren soll. Bild 
vom alten Schädel, Link zu Papier hier von Efteling

  <h2 id="Konzeption">Konzeption</h2><br>
  
Der Spendenschädel ist eine interaktive Spendenbox in Form eines Schädels. Dieser hat eine eigene Persönlichkeit und wirkt durch seine sich bewegenden Augen lebendig. Karl-Leopold fragt mit seinem beweglichen Kiefer in zufälligen Abständen nach Spenden oder erzählt Teile seiner Lebensgeschichte. Wenn ein Besucher Geld durch einen Münzschlitz im Kopf wirft, bedankt sich der Schädel mit einem zufälligen Spruch, sodass der Mensch animiert wird, mehr Geld zu spenden. Damit der Schädel nicht übersehen wird, ist er ansprechend gestaltet und mit LEDs in Augen Kopf ausgestattet. Das Konstrukt aus Schädel, dem darunterstellenden Buch und Netzteil ist per Kabel mit einer Stromquelle verbunden. In Kombination mit einem Gesamtgewicht von über 1,8kg und einer mit Magneten und Kabel gesichteten Schädeldecke ist die Gefahr von einem Diebstahl deutlich geringer als in den vergangenen Jahren. <br>

Persönlichkeit des Schädels:<br>
  Der fiktive Charakter des Schädels ist der von Héctor Rivera (Deuteragonist aus Pixar’s Coco) inspirierte Künstler Karl-Leopold. Er lebte zwischen 1813 und 1834, bis er tragisch durch den Gebrauch von giftiger Farbe verstarb. Um Geld zu sparen, nutzt er sein Gesicht als Leinwand, auch viele Jahre nach seinem Tod. Wie er zu seinem Status als lebendiger Schädel kam, weiß er selber nicht, doch durch seine sarkastische Art wird er von den Menschen an Halloween akzeptiert.

Das Halloweenhaus Schmalenbeck:<br>
  Das junge Team des Halloweenhaus Schmalenbeck lässt Dekorationen, Musik, Lichtdesign, Informatik, Schauspiel, Robotik, Film und viele weitere Fähigkeiten zusammentreffen, um jährlich an Halloween eine etwa 5-minütige, interaktive Show zu gestalten.Der Fokus der Show ist ein familienfreundlicher Wow-Effekt, welcher unteranderem durch selbstkomponierte Musik, eigens erbauten Animatronics, aufwendigen Lichtinstallationen, Projektionen und Soundsystemen, Kurzfilmen und einem kostenlosen Eintritt erreicht wird.Seit 2012 wachsen Team und Besucherzahlen stetig, sodass an Halloween über 500 Menschen das sonst unscheinbare Haus im Dorf besuchen. 
2022 gelang dem Haus der Durchbruch im deutschen Fernsehen. Mit einem Fernsehbeitrag von SAT.1, ständig wiederholten Radiointerviews bei NDR2, dem Hamburger Abendblatt, der SHZ, unzähligen Websites, mehreren Beiträgen im NDR und darunter sogar einer Liveschalte wurde das Haus auch über den norddeutschen Grenzen bekannt.

Gamification:<br>
  Gamification, also Spielifikation, beschreibt die Übertragung spieltypischer Elemente in spielfremde Zusammenhänge. Das Ziel ist eine Motivationssteigerung des Nutzers. Genau das Ziel hat auch der Spendenschädel, da er die Spendemotivation erhöhen soll. Die Aufgabe des Besuchers ist das Spenden. Die Belohnung ist eine Reaktion, welche durch das ständige Reden und andere Besucher bekannt ist. Die Gäste haben gesehen, dass immer was Neues kommt und wollen wissen, was noch alles passieren kann. Diese Ungewissheit bildet die Grundlage der verwendeten Gamification.

  <h2 id="Wahl der Hardware">Wahl der Hardware</h2>
  
Arduino UNO - der Arduino ist das Herzstück des Spendenschädels und bietet alle für das Projekt benötigten Anwendungsmöglichkeiten. Das Mikrocontroller-Board steuert die restliche technische Hardware und wurde wegen der anfängerfreundlichen Oberfläche und der Verfügbarkeit in der Schule ausgewählt.
  
Servomotoren - Die drei verbauten Servomotoren bewegen beide Augen und den Kiefer. Diese Motoren sind können präzise gesteuert werden, das bedeutet, dass wir je nach Bedarf den Winkel, die Beschleunigung oder die Drehgeschwindigkeit verändern können. Diese grundlegenden Eigenschaften sind für unseren Anwendungszweck elementar. Da bereits vor dem Projekt die Kurzform „Servo“ war und die in der Schule vorrätig sind, wurden die Motoren nach einer kurzen Recherche ausgewählt.
  
LEDs - LEDs sind allseitsbekannte, lichtausstrahlende Bauelemente und beleuchten den Spendenschädel. Zwei gelbe LEDs in den Augen beleben Karl-Leopold, während eine rote und eine blaue im Schädelinnenraum eine einladend-violette Stimmung erzeugen. Eine weitere, weiße LED stellt sicher, dass der Fotowiderstand genug Lichtdifferenz erfährt. 
Die LEDs sind preisgünstig, klein und unkompliziert zu verbauen, weshalb auch diese ohne zu zögern ausgewählt wurden.
  
Fotowiderstand - Die zwei Fotowiderstände am Geldschlitz des Schädels haben die Eigenschaft, ihre Widerstandsfähigkeit anhand des Lichteinfalles zu verändern. Mit der Information, dass der Lichteinfall sich deutlich verringert, kann so ein Einwurf erkannt werden und der Schädel bedankt sich. Mit diesem Kerngedanken wird sich bei einer kurzen Recherche für den Fotowiderstand entschieden. Bei einem Test fällt auf, dass zwei Widerstände zusammen genauere Werte erbringen, weshalb zwei im Schädel zu finden sind. Glücklicherweise hat ein Teammitglied des Halloweenhaus Schmalenbeck noch 
einige übrig, sodass diese nicht neu gekauft werden müssen.
  
DFPlayer Mini mit Micro SD - Der DFPlayer Mini ist ein MP3-Modul, welcher für den Arduino UNO oder andere Boards mit RX/TX entwickelt wurde. Er ist klein, kompakt und für wenige Euro zu erwerben. Nach einer simplen Montage kann der Ton, welcher einfach in den von uns benutzten Formaten MP3 oder WAV auf einer Micro SD gespeichert wird, abgespielt werden.Durch den günstigen Preis, der Popularität und der Kompatibilität mit dem Arduino UNO kaufen wir diesen für unser Projekt. 
  
AuxPort - The Show must go on. Der AuxPort ist eine Sicherheitsmaßnahme für den Fall, dass der Lautsprecher versagen sollte oder wir den Ton verstärken wollen. Allerdings wird dieser im Regelfall nicht benutzt, weshalb er auch keine weitere Bedeutung im Verlauf unserer Arbeit bekommt. Aux ist der Standard für den Anwendungszweck und bereits bei uns vorhanden, dementsprechend ist auch hier keine lange Bedenkzeit nötig.
  
Lautsprecher - Dieser wandelt die elektrischen Signale des DFPlayers in Schall um. Dessen Verwendung ist bei dem Projekt damit unumgänglich. Das Lautsprechermodell kann beliebig sein. Der von uns genutzte wurde aus einem gebrauchten Objekt ausgebaut und neu von uns eingebaut. Die Vorteile des Modells sind die kleine Größe und der Fakt, dass er ohne das Projekt weggeworfen werden würde. Damit fallen keine Kosten an und es wird kein neuer Elektroschrott produziert.
  
Netzgerät - Dieses versorgt den Schädel mit Strom. Durch die konstante Verbindung zu einer Steckdose muss sich niemand Sorgen über einen leerwerdenden Akku machen. Das Gewicht schützt den Kopf vor Diebstahl. Mit wenig Arbeit kann der Schädel vom darüberliegenden Buch abgelöst werden, sodass das Netzteil einfach abgebaut werden kann. Dieses musste das Team ebenfalls nicht neu erwerben.
  
Widerstände - Die sieben verbauten Widerstände begrenzen die Strommenge und garantieren, dass die verbundenen Bauelemente funktionieren und nicht durchbrennen. Sie sind Teil eines jeden Arduinoprojektes und natürlich auch in der Schule vorhanden.
  
Kabel mit und ohne Steckverbindungen - Um alle Bauelemente miteinander zu Verbinden werden verschiedenste Kabel verwendet. Diese sind großenteils von Elektroschrott, um auch hier unseren ökologischen Fußabdruck gering zu halten. Ein paar der neuen Kabel haben Steckverbindungen, damit angeschlossene Objekte mobil bleiben. Um zu gewährleisten, dass diese Mobilität trotz mehrfacher Verbindungen in einen Arduino Pin möglich bleibt, sind Mehrfachstecker verbaut.
  
Schädel - Das sichtbare Gehäuse des Schädels ist mit Amazon 3D gedruckt. Ein Objekt mit unseren speziellen Wünschen kann natürlich nicht einfach im Internet bestellt werden, weshalb sich der Druck anbietet. Da Rosalie selbst einen Ender-3 Max besitzt, konnte das Projekt zügig angegangen werden. Der genaue Prozess wird in Multimediaproduktion erläutert.
  
Falsches Buch - Um den Bewegungsfreiraum des Kiefers zu gewährleisten, muss der Schädel auf einem Objekt stehen. Hier kommt eine russische Pralinenverpackung zum Einsatz, welche schon seit Jahren für so einen Gebrauch gelagert wird.
  
Gewichte - Im Buch liegen Gewichte einer analogen Waage, um Stabilität zu Gewährleisten. Ein positiver Nebeneffekt ist auch hier die Diebstahlprävention.
  
Magnetschnäpper - Die Schädeldecke ist vom Hauptschädel trennbar und liegt im geschlossenen Zustand nur mit den dünnen Rändern auf. Der Magnetschnäpper hält alles am Platz und ist ebenfalls zur Prävention von Diebstahl da.
  
Druckfehler für Magnetschnäpper - Ein Plastikteil eines vorherigen, fehlerhaften Druckprojektes dient als Unterlage für den Magnetschnäpper, welcher sich im 
Fundus eines jeden Heimwerkers befindet.
  
Steine für Augen - Damit die Augen nicht sofort als LEDs identifiziert werden können, haben wir Plastiksteine aus eigener Bastelsammlung darauf geklebt.
  
Holzspieße - Sie bringen Stabilität in Augen und Buch und in jedem Haushalt zu finden.
  
Schwarzes Ducktape - Neben der Befestigung von Kabelverbindungen und Hardware dient dieses auch als Hülle für das Netzteil.
  
Teserfilm - Genau wie das Ducktape dichtet es wenige Kabelverbindungen ab, ist aber schlechter für diesen Anwendungszweck geeignet. 
  
Malertape - Für den Fall, dass ein Objekt kaputt geht, soll es schnell und einfach ausgebaut werden können. Arduino und DFPlayer haben deshalb einen Rahmen aus Heißklebe, mit welchem sie am Platz gehalten werden. Das Malertape schützt die Technikgeräte vor der Klebe. Zusätzlich wurde es zur Erkennbarkeit der mit dem Netzteil verbundenen Kabel genutzt.
  
Heisskleber - Der beste Freund eines jeden Bastlers ist nicht leitfähig, ist einfach verform und korrigierbar, trocknet zügig und hat ein hohes Volumen. Fast alles wurde so verklebt, Kabelverbindungen damit gedichtet und auch der Rahmen für Arduino und DFPlayer wurde damit geschaffen.
  
Draht - Mit seiner guten Stabilität und schönen Flexibilität hält er den Lautsprecher am Platz.
  
Faden - Der verbaute Faden strukturiert die vielen Kabel im Kopf.
  
Papier - Papier hat keinen weiteren Sinn für den Schädel, doch wird zur Vollständigkeit mit aufgeführt. Es wurde zum Kommentieren von Verbindungen im Schädel gebraucht.
  
<h2 id="Wahl der Software">Wahl der Software</h2>
 
Arduino IDE - Es ist das offizielle Programm zum Programmieren eines Arduinos und kostenlos nutzbar.
  
GitHub - Der webbasierte Dienst hilft Entwickeln, Code auszutauschen und Projekte im Internet vorzustellen.
  
Synology Drive - Das Programm verwandelt einen NAS zu einer privaten Cloud, in welcher jegliche Dokumente und Dateien gespeichert sind. 
  
GoodNotes5 - Diese App zur Erstellung von handgeschriebenen Notizen wird von beiden im Schulalltag und dementsprechend auch für das Projekt verwendet. Neben ersten Skizzen entsteht auch der Schaltplan in diesem Programm.
  
Procreate - Mit Hilfe der Zeichen-App erstehen Skizzen.
  
Pages - Das auf iOS, MacOS und iPadOS vorinstallierte Tool zum Erstellen von Textdokumenten schafft Überblick über die verwendeten Anschlüsse am Arduino.
  
Blender - Mit diesem open-source Programm zur Erstellung von 3D Modellen wird der Schädel erstellt.
  
Ultimaker Cura - Das Programm wandelt das 3D Modell in den für den Drucker auslesbaren G-Code um. Dieser Slicer ist ebenfalls open Source und kostenlos.
  
Logic Pro X - Mit der Digital Audio Workstation von Apple werden die Tonaufnahmen getätigt. 
  
  <h1><bold>Entwicklung</bold></h1>
  <h2 id="Stundenprotokoll">Stundenprotokoll</h2>
  
  <h3>
  <bold>1. Stunde (22.08.2022)</bold>
  
  </h3>
  
Zusammen erstellten wir unsere GitHub Accounts, sowie unsere Projektseite. Anschließend haben wir uns über ein mögliches Projekt gedanken gemacht. Unsere erste Idee war es, eine beleuchtete Stadt zu konstruieren, dessen LEDs über ein LCD Display einzeln ansteuerbar sein sollen. Zusätzlich sollen mit einprogrammierten Routinen kleine Lichtshows möglich gemacht werden. Das Projekt soll selbstständig Tag und Nacht unterscheiden und die Routinen demensprechend anpassen.
Da das Projekt nicht dem angemessenen Programmierumfang enspricht wurde die Idee verworfen.
Unser aktueller Plan sieht vor, dass wir einen Soundwavegenerator programieren. Dieser soll mit einer Grundfrequenz und variablen Obertönen Töne generieren, sodass verschiedenste Klänge synthetisiert und als mp3 exportiert werden können. 

<details>
  <summary>Skizze</summary>
  
  ![](74703F7D-FAD9-4B21-8016-8272D528E488.jpeg)
  
  </details>
 
<h3>
  <bold>2. Stunde (25.08.2022)</bold> 
  
  </h3>

  
In den letzten Tagen habe wir festgestellt, dass wir mit dem Projekt nicht zufrieden sind. Jedoch sind wir uns einig, dass uns Physical Computing und damit die Arbeit mit einem Arduino interessiert. Wir haben uns zuhause mit den Möglichkeiten, Programmen und Hardware  auseinandergesetzt und im Unterricht besprochen. Dabei kam uns unsere Projektidee:

Das Halloweenhaus Schmalenbeck (www.halloweenhaus-schmalenbeck.de) nutzt traditionell einen Spendenschädel (Spendendose in Schädelform). Der aktuelle Schädel ist zu .  Das ist für uns die Gelegenheit, einen neuen zu Gestalten. Inspiriert von den Mülleimern im niederländischen Freizeitpark Efteling haben wir ein Konzept erarbeitet.

<details>
  <summary>Konzept</summary>
  
- Schädel, der sprechen kann (motorisierter Kiefer mit Servo)
- Soundkarte und Lautsprechern (DFPlayer Mini)
- euchtende Augen, welche in verschiedene Richtungen schauen können (LEDs, Servos)
- Sensor für Geld (Lichtschranke)
- arbeiten mit Arduiono (Arduiono IDE)
</details>

<details>
  <summary>Features</summary>
  
- Schädel fragt nach Spenden (Audio synchron mit Kiefer)
- Bei Geldeinwurf bedankt sich der Schädel
- Mute Schalter
</details>

<details>
  <summary>Optional</summary> 
  
- Diebstahlschutz
</details>  

Anschließend haben wir wir Rücksprache mit Herrn Buhl. Dieser gab uns den Tipp, eine Prioritätenliste anzulegen, denn so können wir jederzeit bei Zeitdruck aufhören. 
<details>
  <summary>Prioritätenliste</summary>
  
- Lautsprecher -> um nach Spenden zu fragen -> Aufnahmen stellt das Halloweenhaus Schmalenbeck
- Bewegung im Kiefer
- Erkennung des Münzeinwurfs -> Schädel bedankt sich
- leuchtende Augen
- Mute Schalter
- sich bewegende leuchtende Augen
- Diebstahlschutz
</details>


<h3>
  <bold>3. Stunde (29.08.2022)</bold> 
  
  </h3>
  
  
Über das Wochenende haben wir einen Ordner auf Rosalies NAS erstellt, um dort sicher und einfach Daten zu sichern und teilen. Außerdem hat Rosalie das Lager des Halloweenhaus Schmalenbeck nach Hardware gesichtet und LEDs, einen Az-Delivery Mini MP3 Player DFPlayer Master Module für Arduino und einen AZ-Delivery Fotowiderstand (Photo Resistor) Dioden 150V 5mm LDR5528 GL5528 5528 50pcs für unser Projekt genommen.
Da Alicia in dieser Stunde leider fehlte, hat Rosalie alleine angefangen, einen Schaltplan zu erstellen. Der Sinn dabei ist, Fehlbauten zu verhindern und schonmal eine Vorstellung von benötigten Kabeln, Wiederständen usw zu bekommen. In der Stunde kamen netterweise schon erste Hinweise von Klassenkameraden, beispielsweise der benötigte Wiederstand an den LEDs.

<details>
  <summary>Quellen</summary>
  
 - https://www.youtube.com/watch?v=GnGv21v7h8s
 - https://blog.robberg.net/wp-content/uploads/2017/10/DFPlayer.jpg
 - https://wolles-elektronikkiste.de/wp-content/uploads/2019/07/UNO_2.jpg
 - https://www.arduino.cc/en/Tutorial/BuiltInExamples/Blink
 - https://www.youtube.com/watch?v=cYOft1rEBYw
 - https://de.wikipedia.org/wiki/Fotowiderstand
  
</details>
 
 
 <h3>
  <bold>4. Stunde (05.09.2022)</bold> 
  
  </h3>
  
  In dieser Stunde haben wir den noch Fehlenden Fotowiederstand in die Skizze aufgenommen und diese auf Fehler überprüft. Dank einiger Tipps konnten wir 
  diese finalisieren.

  
Danach haben wir mit dem programmieren unseres Codes angefangen, welcher eine LED zum leuchten bringen soll. Anschließend haben wir unsere LED mit dem Arduino und diesen wiederrum mit dem Computer verbunden. Dies hat dann auch funktioniert. Als wir es erneut probierten klappte es leider nicht mehr. Der Fehler lag bei den losen Kabeln, welche keine Verbindung mehr herstellten. Bisher konnten wir das Problem noch nicht lösen und haben ums erstmal wieder dem Code zugewendet.

<details>
  <summary>Quellen</summary>
  
- https://www.c-sharpcorner.com/UploadFile/d15fb8/ldr-with-arduino/Images/LDR.jpg
 
</details>

<h3>
  <bold>5. Stunde (08.09.2022)</bold>
     </h3>
  
In dieser Stunde haben wir uns mit einem Servo beschäftigt. Wir haben gelernt, wie man mithilfe eines Arduinos den Servo steuern kann und ein programm dazu geschrieben.
 
Außerdem haben wir uns mit dem Schädel befasst und sein Aussehen, sowie seinen Charakter festgelegt. Dieser Charakter legt auch die Sprechweise des spendenschädels fest. Wir haben uns darauf geeinigt, dass der Schädel männlich, lustig und schlau ist. Sein Name lautet Karl Leopold.

 
 
 <h3>
  <bold>6. Stunde (12.09.2022)</bold>
     </h3>
     
     
Heute haben wir uns näher mit dem Charakter und dem Hintergrund des Spendenschädels beschäftigt. Inspiration erhielten wir von der Figur Héctor Rivera aus dem Film "Coco". 
Karl leopold wurde 1813 geboren und war sein lebenlang ein armer, deutscher Künstler. Da er kaum Geld hatte nutzte er sein Gesicht als Leinwand. Sein Leben endete tragischerweise bei der Ausübung seiner Leidenschaft, da er sich giftige Farbe auf sein Gesicht auftug.
Ebenfalls haben wir die Sprüche festgelget, die der Spendenschädel sagen soll. In Klammern dahinter steht jeweils die Art, wie der Satz gesprochen werden soll.

<details> 
<summary>Allgemeine Sprüche</summary>

- Nur mit deiner Spende können die Künstler weitermachen. (animierend)
- Halli, hallo! Ich bin Karl Leopold, auch Spendenschädel genannt. (glücklich, aufgeweckt)
- Ein kleiner Groschen oder ihr werdet verdroschen, hehe. (frech)
- Ein kleiner Groschen für eine Brilliantbrosche. (ernst, fröhlich) Scherz. Wisst ihr, wie teuer Lampen geworden sind? (scherzhaft)
- Ich verfluche euch zum Geld spenden. (ironisch)
- Rosi, dein ökologischer Fußabdruck ist eine Pfote. (ernst)
- Fantasie ist, dass Sie sich buntgespränkelte zebras vorstellen. (ernst, fröhlich)
- Ich bin ja Jahrgang 1813. Und ihr wisst doch sicherlich, was 1813 noch so alles passiert ist, oder? Richtig, da gab es die Befreiungskriege. Und ich         fordere euch nun dazu auf, euer Geld aus eurem Portemonaie zu befreien.
- Hilfe ich bin tot und brauche das geld
</details>

<details>
<summary>Danksagungen</summary>
  
- Vielen Dank Ihr holde Maid. Es ist mir eine ehre euch kennenzulernen. Ich hoffe Ihr sterbt bald. (zu tiefst berührt)
- Oha, großer Ehrenmensch! (beGEIStert)
- Möge der große, nicht der kleine Otto, ach was beide, mit dir sein. (dankend, fröhlich)
- Uff, das tat weh, obwohl ich gar keine Nerven mehr habe. Aber das ist wohl die uninterpretierbare Parodaxie meinersynthetischen Existenz. (nachdenklich)
  programm für kiefer geschriben
  kiefer auf sprüche anpassen festgelegt
- Oha, ich möchte aufrichtig danken, mögest du immer Chicken Nuggets im Haus haben! (ernst)
- Mögen meine Augen Euch erleutung bringen! (feierlich)
- Ich hab Geld im Kopf bin bei der FDP,
doch trozudem sage ich dir jetzt DANKEE

</details>

Außerdem wir das Programm für die Kieferbewegung geschrieben. Hier tauchte zunächst ein Fehler bei dem Uploud auf den Arduiono auf. Dieses konnte allerdings durch einen anderen Code gelöst werden. Dieser code wurde danach nicht wieder benötigt und taucht daher auch nicht in dem finalen Code auf.

<details>
  <summary>Quellen</summary>
  
- https://player.hu/uploads/2017/11/coco-hector.jpg
       
</details>

<h3>
  <bold>Wochenende (17&18.09.2022)</bold>
     </h3>
Am Samstag hat Rosalie den Spendenschädel mit einer weißen Holzpaste grundiert, damit der Schädel keine Kanten hat, die durch den 3D-Druck entstehen. Anschließend hat sie den SChädel mit weißer Acrylfarbe angemalt.  
Am Sonntag haben wir uns getroffen und zuerst eine Skizze angefertigt, wie der Schädel aussehen soll. Anschließend haben wir uns auf ein Farbschema geeinigt und mit einem Bleistift, die Formen vorgezeichnet. Der letzte Schritt bestand darin, den Schädel anzumalen.
   
   
<h3>
  <bold>7.Stunde (19.09.2022)</bold>
  </h3>
  
Wir haben weitere Sprüche entwickelt, welche in der Liste der letzten Stunde aufgeführt sind. Außerdem haben wir unsere Code-Struktur ausgefeilt, da diese noch einige Fehleraufwies und noch nicht vollständig war.

<details>
  <summary>Quellen</summary> 

- https://funduino.de/nr-6-fotowiderstand
- https://starthardware.org/dfplayer-mini-mp3-player-fuer-arduino/
- https://www.arduino.cc/reference/en/language/functions/communication/serial/println/
- http://www.gammon.com.au/interrupts

  
</details> 


   <h3>
  <bold>8. Stunde (06.10.2022)</bold> 
  
  </h3> 
Alicia beschäftigt sich damit, wie sie mit Hilfe eines Sensorwertes die Audiodateien steuern kann. Sobald Geld eingeworfen wird soll der Spendenschädel nämlich nicht mehr seine normalen Sprüche aufsagen sondern sich bedanken.
Rosalie setzt sich weiterhin mit der Hardware und dem dazugehörigen Schaltplan auseinandergesetzt.
  
  <details>
    <summary>Quellen</summary>
      
  - https://wolles-elektronikkiste.de/dfplayer-mini-ansteuerung-mit-dem-arduino
  - https://ardurobot.jimdofree.com/lehrgang/posten-12-lichtsensor/
  
  </details>
  
  <h3>
  <bold>9. Stunde (24.10.2022)</bold> 
  
  </h3> 
  
  Rosalie hat die Hardware überprüft und Alicia hat am Code weitergearbeitet.
  
<details>
  <summary>Quellen</summary>

- https://starthardware.org/dfplayer-mini-mp3-player-fuer-arduino/
- https://docplayer.org/176475379-Mp3-player-mit-dfplayer-mini.html

 </details>


  <h3>
  <bold>10. Stunde (03.11.2022)</bold> 
  
  </h3> 
  
  Alicia ist den Code durchgegangen und hat ihn auch Fehlerquellen überprüft.
  
  
  <h3>
  <bold>11. Stunde (07.11.2022)</bold> 
  
  </h3> 
  
Alicia hat erneut den Code auf Fehlerquellen überprüft. Der Code war an einer falschen Stelle gespeichert und konnte daher nicht auf die Librarie zugreifen. Als der Code an der vorgesehenen Stelle gespeichert war, hat alles funktioniert. Ein weiterer Fehler lag darin, dass die Formulierung für das Abspielen der Audiodateien falsch war. Diese Fehlermeldung konnte nach einer kurzen Internetrecherche behoben werden. Alicia hat außerdem eine weitere Funktion, die Audiodateien betreffend, eingebaut. Diese werden, sofern kein anderer Befehl vorliegt, alle abgepielt. So muss nicht jede Audiodatei enzeln eingefügt werden.
Außerdem hat sie mit HTML den Blog weiter strukturiert.
 
 
 <details>
  <summary>Quellen</summary>
  
 - https://www.theamplituhedron.com/articles/How-to-use-DFRobot-DFPlayer-Mini-Serial-MP3-Player-with-Arduino/
  
 </details>
  
  <h3>
  <bold>12. Stunde (14.11.2022)</bold> 
  
  </h3> 
  
 In dieser Stunde haben wir ohne Aufsicht gearbeitet. Alicia hat sich wieder mit dem Code beschäftigt. Relativ zum Ende der Stunde ist eine Fehlermeldung aufgetreten. Der fehlerhafte Befel soll dafür sorgen, dass der Servo zufällige Positionen, in festgelegten Grenzbereichen, ansteuert.
  

  
  <h3>
  <bold>13. Stunde (17.11.2022)</bold> 
  
  </h3> 


Alicia beschäftigt sich weiterhin mit dem Code. Die Fehlermerldung der letzten Stunde konnte gelöst werden. Eine benötigte Bibliothek war nicht installiert. Da diese allerdings auch nicht mehr verfügbar ist, musste der Befehl umgeschrieben werden.
Rosalie setzt sich mit dem GitHub Blog außeinander und wie wir im generellen unsere Projektseite gestallten wollen.
Wir befinden uns nun im Endspurt unseres Projektes und haben noch zwei Wochen, um dieses zu vollenden.

<h3>
  <bold>14. Stunde (21.11.2022)</bold> 
  
  </h3> 
  Buch stabilisiert, etwas github geschrieben. Fehler vom Ton gesucht, feher waren fehlende Tondateien
  
  
  
  <h3>
  <bold>15. Stunde (28.11.2022)</bold> 
  
  </h3> 
  
  
  <h3>
  <bold>16. Stunde (01.12.2022)</bold> 
  
  </h3> 
  
  <h2 id="Code">Code</h2>
  
  <h2 id="Bau- undmSchaltplan">Bau- und Schaltplan</h2>
  
Der Bau des Schädels beginnt Anfang Oktober und wird am 29.10.22 abgeschlossen (Ausnahme Stabilisierung Buch). In diesem Monat wird kontinuierlich, kleinschrittig und fast ausschließlich außerhalb der Unterrichtszeit gearbeitet. Damit ist er kein Teil des Stundenprotokolls und nicht täglich dokumentiert. Der Fortschritt kann mit kleinen Einblicken auf dem Instagramkanal des Halloweenhaus Schmalenbeck verfolgt werden.
  
Der Schaltplan zeigt neben den Verbindungen der einzelnen Elemente auch die 
Kabelfarben und die ungefähre Lage der Objekte im Schädel.
Zur besseren Orientierung beim Programmieren und einfachen Kontrolle der 
korrekten Pinbelegung entsteht folgende Tabelle:
  
  <h2 id="Multimediaproduktion">Multimediaproduktion</h2>
  
Ohne sein einzigartiges Auftreten wäre der Spendenschädel nichts. Um diesen Punkt zu erreichen, werden Fähigkeiten und Schritte außerhalb der Informatik gefordert.
  
Ohne die Hülle wäre Karl-Leopold niemals als Schädel zu erkennen. Ein Objekt mit unseren Anforderungen ist selbstverständlich nicht käuflich, darum wird der Kopf mit Rosalies Ender-3 max 3D-Drucker und weißem Amazon Basic Filament 3D gedruckt.
Das 3D-Modell für wird von Freund und Teammitglied Steffen Kahl gestaltet. Mit dem Konzept und einer passenden Skizze wird aus einer kostenfreien Datei 
(https://www.thingiverse.com/thing:518109) ein optimal passendes Endprodukt geschaffen.
Bei einem gemeinsamen Treffen wird ein Design für die Schädelbemalung entworfen und umgesetzt. Auf dem mit weißer Holzpaste grundierten Schädel können Formen mit Bleistift skizziert oder auf Papier ausgedruckt und aufgeklebt werden. Bei einem letzten Schritt, dem Auftragen von Acryl und Wandfarbe, wird Karl-Leopolds Hang zur Kunst visualisiert. Das komplementäre Farbschema harmoniert gewollt nicht mit dem Buch, um einen gruseligen Bruch im Schema zu erzeugen.
Die Farbe Violett symbolisiert Kreativität und das mystische, beides Kerneigenschaften des Künstlers. Gold hingegen bildet einen Widerspruch, denn er ist nicht wohlhabend. Doch genau diesen Punkt möchte er mit der Spende ändern. Die Perfekt Harmonie von Gleichheit und Gegensatz wird aktiv von seinem Verhalten zerstört. Dadurch kann alleine durch die Farbgebung seine teils böse und sarkastische Art und das Halloweenthema verkörpert werden. Aber natürlich auch seine harmonische, liebevolle Seite.
Auf seiner Stirn prangt eine Interpretation der Lotusblume, das mythische Gewächs für Transformation. Karl-Leopold transformierte sich vom Lebenden zum Schädel ohne logische Erklärung. Diese Flüchtigkeit wird zusätzlich mit den Symbolen vom Element Luft an Schläfen und Kiefer gezeigt.
Die Dabei ausgewählten Zeichen sind von der Live Action Adaptation des Romans „Grandmaster of Demonic Cultivation“ inspiriert. Für Kenner ein erster Hinweis darauf, dass eine Divergenz besteht. Die Symbole sind die Motive der Hauptclans des Protagonisten, welcher von seinem Adoptivbruder (Neunblättriger Lotus) 
verstoßen und von einem guten Freund (Fließende Wolken) neu aufgenommen wird.
  
Um diese leblose Hülle zum Sprechen zu bringen, werden insgesamt 32 Sprüche geschrieben und im MuchowMedia Tonstudio aufgenommen. Sprecher ist Freund 
und Langzeitmitglied Bennet Martins, welcher so die Aufnahme eines männlichen Sprechers ermöglichte.
Die 32 Sprüche bestehen mit 21 aufgenommenen Tonspuren größtenteils aus zufälligen Sprüchen. Bedanken kann sich der Schädel mit den restlichen 11.

  <details><summary>Sprüche</summary>
  
- Nur mit deiner Spende können die Künstler weitermachen.
- Halli Hallo! Ich bin Karl-Leopold, auch Spendenschädel genannt.
- Ein kleiner Groschen oder ihr werdet verdroschen. Hehe.
- Ein kleiner Groschen für eine Brilliantbrosche. Scherz. Wisst ihr, wie teuer Lampen geworden sind?
- Ich verfluche euch zum Geldspenden.
- Ich bin ja Jahrgang 1813, und ihr wisst doch sicherlich, was 1813 noch so alles passiert ist, oder? Richtig, da gab es die Befreiungskriege. Und ich fordere euch nun dazu   auf, das Geld aus eurem Portemonnaie zu befreien.
- Hilfe, ich bin tot und brauche das Geld…
- Diesen Aufwand könnte ich im Leben nicht bezahlen! Gut, dass ich tot bin.
- Kohle Kohle Kohle, Kohle Kohle Kohle, Kohle Kohle Kohle, Scha-Bidu!
- Sag mal Bennet, ist das richtig, dass hier niemand Eintritt bezahlt? Ach ja! Ist ja auf Spendenbasis!
- Als ich klein war war glaubte ich, Geld sei das wichtigste im Leben. Heute, da ich alt bin weiß ich, es stimmt.
- Es gibt Leute, die Laufen dem Geld nach. Ich bin hier und das Geld kommt zu mir.
- Meine Sprüche sind die Kunst auf den Kopf zu zielen und die Brieftasche zu treffen.
- Mögen euch die Ärmel beim Händewaschen runterrutschen, wenn ihr kein Geld einwerft.
- Verwechsle die Höhe deiner Gage niemand mit der große deines Talents.
- Lasst Applaus in Form von Geld da.
- Herrlich erfrischend, so eine kühle Münze!
- Das einzige was mir nicht passieren kann, ist den Kopf zu verlieren.
- Ich bin die schönste Blume hier!
- Spendenschädel meldet sich zum Dienst.
- Werde ich ein Skelett, wenn ich groß bin?
    
- Vielen Dank holde Maid! Es ist mir eine Ehre, euch kennenzulernen.
- Oha, großer Ehrenmensch!
- Möge der große, nicht der kleine Otto. Ach was, beide mit dir sein.
- Uff, das tat weh. Obwohl ich gar keine Nerven mehr habe. Aber das ist wohl die uninterpretierbare Paradoxie meiner synthetischen Existenz.
- Mögen meine Augen euch Erleuchtung bringen!
- Danke sehr, auch das man auch nach deinem Tode gut über dich sprechen mag.
- Ich bin von deiner Begeisterung be-geist-ert. Vielen Dank!
- Vielen Dank für die Spende, ich freue mich zu Tode.
- Ich bin vom Unterkiefer bis zum Gehörknöchelchen Entzückt!
- Ich würde vor Freunde fast in die Luft springen, wenn ich denn nur könnte. Danke!
- Danke Anke, Schankedön!

    </details>
