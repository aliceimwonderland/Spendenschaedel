<h1>
  <bold>1. Stunde (22.08.2022)</bold>
  
  </h1>
  
Zusammen erstellten wir unsere GitHub Accounts, sowie unsere Projektseite. Anschließend haben wir uns über ein mögliches Projekt gedanken gemacht. Unsere erste Idee war es, eine beleuchtete Stadt zu konstruieren, dessen LEDs über ein LCD Display einzeln ansteuerbar sind. Zusätzlich sollen mit einprogrammierten Routinen kleine Lichtshows möglich gemacht werden. Das Projekt soll selbstständig Tag und Nacht unterscheiden und die Routinen demensprechend anpassen.
Da das Projekt so zu wenig Programierung erfordert wurde der Plan verworfen.
Unser aktueller Plan sieht vor, dass wir einen Soundwavegenerator programieren. Dieser soll ein aus der Grundfrequenz und selbst eingegebenen Obertönen Töne generieren. Selbstverständlich sollen diese Töne auch exportiert werden können.

<details>
  <summary>Skizze</summary>
  
  ![](74703F7D-FAD9-4B21-8016-8272D528E488.jpeg)
  
  </details>
 
<h1>
  <bold>2. Stunde (25.08.2022)</bold> 
  
  </h1>

  



Die letzten Tage habe wir festgestellt, dass wir mit dem Projekt einen Soundwavegeneratror zu programieren nicht glücklich sind. Jedoch sind wir uns einig, dass uns Physical Computing und damit die Arbeit mit einem Arduino interessiert. Wir haben uns zuhause mit den Möglichkeiten, Programmen und Hardware  auseinandergesetzt und im Unterricht besprochen. Dabei kam uns unsere Projektidee:

Das Halloweenhaus Schmalenbeck (www.halloweenhaus-schmalenbeck.de) nutzt traditionell einen Spendenschädel (Spendendose in Schädelform). Dieser billige Plastikschädel mit Münzloch ist relativ klein und unsauber verarbeitet.  Das ist für uns die Gelegenheit, einen neuen zu Gestalten. Inspiriert von den Mülleimern im niederländischen Freizeitpark Efteling haben wir folgendes Konzept erarbeitet:

- Schädel, der sprechen kann (motorisierter Kiefer mit Servo)
- Soundkarte und Lautsprechern (DFPlayer Mini)
- leuchtende Augen, welche in verschiedene Richtungen schauen können (LEDs, Servos)
- Sensor für Geld (Lichtschranke)

-> Arduino mit Arduino IDE

Features:
- Schädel fragt nach Spenden (Audio synchron mit Kiefer)
- Bei Geldeinwurf bedankt sich der Schädel
- Mute Schalter

Optional: 
Diebstahlschutz

Anschließend haben wir wir Rücksprache mit Herrn Buhl. Dieser gab uns den Tipp, eine Prioritätenliste anzulegen, denn so können wir jederzeit bei Zeitdruck aufhören. Diese Liste sieht wie folgt aus:

- Lautsprecher -> um nach Spenden zu fragen -> Aufnahmen stellt das Halloweenhaus Schmalenbeck
- Bewegung im Kiefer
- Erkennung des Münzeinwurfs -> Schädel bedankt sich
- leuchtende Augen
- Mute Schalter
- sich bewegende leuchtende Augen
- Diebstahlschutz



<h1>
  <bold>3. Stunde (29.08.2022)</bold> 
  
  </h1>
  
  
  Über das Wochenende haben wir einen Ordner auf Rosalies NAS erstellt, um dort sicher und einfach Daten zu sichern und teilen. Außerdem hat Rosalie das Lager des Halloweenhaus Schmalenbeck nach Hardware gesichtet und LEDs, einen Az-Delivery Mini MP3 Player DFPlayer Master Module für Arduino und einen AZ-Delivery Fotowiderstand (Photo Resistor) Dioden 150V 5mm LDR5528 GL5528 5528 50pcs für unser Projekt genommen.
  Da Alicia in dieser Stunde leider fehlte, hat Rosalie alleine angefangen, einen Schaltplan zu erstellen. Der Sinn dabei ist, Fehlbauten zu verhindern und schonmal eine Vorstellung von benötigten Kabeln, Wiederständen usw zu bekommen. In der Stunde kamen netterweise schon erste Hinweise von Klassenkameraden, beispielsweise der benötigte Wiederstand an den LEDs.
  Quellen:
  
  https://www.youtube.com/watch?v=GnGv21v7h8s
  https://blog.robberg.net/wp-content/uploads/2017/10/DFPlayer.jpg
  https://wolles-elektronikkiste.de/wp-content/uploads/2019/07/UNO_2.jpg
  https://www.arduino.cc/en/Tutorial/BuiltInExamples/Blink
  https://www.youtube.com/watch?v=cYOft1rEBYw
  https://de.wikipedia.org/wiki/Fotowiderstand
  

 
 
 <h1>
  <bold>4. Stunde (05.09.2022)</bold> 
  
  </h1>
  
  In dieser Stunde haben wir den noch Fehlenden Fotowiederstand in die Skizze aufgenommen und diese auf Fehler überprüft. Dank einiger Tipps konnten wir 
  diese finalisieren.
  https://www.c-sharpcorner.com/UploadFile/d15fb8/ldr-with-arduino/Images/LDR.jpg
  
Danach haben wir mit dem programmieren unseres Codes angefangen, welcher eine LED zum leuchten bringen soll. Anschließend haben wir unsere LED mit dem Arduino und diesen wiederrum mit dem Computer verbunden. Dies hat dann auch funktioniert. Als wir es erneut probierten klappte es leider nicht mehr. Der Fehler lag bei den losen Kabeln, welche keine Verbindung mehr herstellten. Bisher konnten wir das Problem noch nicht lösen und haben ums erstmal wieder dem Code zugewendet.

<h1>
  <bold>5. Stunde (08.09.2022)</bold>
     </h1>
  
 servo
 programmiert
 charakter schädel
 was soll er sprechen
 
 
 <h1>
  <bold>6. Stunde (12.09.2022)</bold>
     </h1>
