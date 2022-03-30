# Template für einen Lebenslauf auf der Webseite
Dieses Template ist gewiss nicht das schönste Template, dass die Welt je gesehen hat. Aber ich habe es mir so gebaut und warum soll ich es dann nicht mit anderen teilen 🙃?

Ich habe mich bemüht, alles so einfach wie möglich zu halten. Das besondere Feature steckt im CSS: Die Druckansicht ist anders formatiert als die Ansicht im Web. Und die Web-Ansicht ist responsive, skaliert also mit der Größe des Gerätes.

## Das Bild
Als Beispiel fungiert die Erika Mustermann. Das eigene Foto sollte eine Größe von ca. **640 x 1080 Pixel** haben. Das Template ist so eingerichtet, dass man auch gut in Gänze auf dem Bild zu sehen sein könnte. Damit der Bildausschnitt in der Druckansicht nicht angepasst werden muss, sollte das Gesicht in einer Höhe von 350 bis ca. 900 Pixeln von oben liegen. Das Bild sollte einen einfarbigen Hintergrund haben und mit dem Namen **cv.jpg** abgespeichert werden. Wenn der Name geändert wird, dann sind die Einträge im HTML (Zeile 13) und im CSS (Zeile 140) anzupassen.

## Der Text
Im HTML-Dokument werden die Daten in Blöcken eingetragen. Dazu muss das Dokument in einem normalen Text-Editor (zum Beispiel Notepad) geöffnet werden. Geändert werden nur die Texte, nicht die Tags (die Teile zwischen < und >)!

### Kopf in der Druckansicht: class="cv head"
Aus diesem Bereich sind nur die Überschrift Lebenslauf (H2) und der eigene Name (H1) in der Webansicht zu sehen. Die anderen Daten erscheinen lediglich in der Druckansicht. Warum? Weil ich das so wollte 😉.

Zu ändern sind:
* Name
* Adresse
* E-Mail (Zur Vermeidung von SPAM wird der Teil vor dem @ als **data-user** und der Teil dahinter als **data-website** eingetragen. Beides wird rückwärts geschrieben.)
* Webseite
* Staatsangehörigkeit
* Familienstand

### Die einzelnen Blöcke der Lebenslaufs: class="cv"
Von diesen Klassen kann und sollte es mehrere geben. Sinnvoll sind **Berufsleben**, **Engagement** und **Ausbildung**. Aber auch Hobbies und Fähigkeiten könnten hier stehen.
* H1: Das ist die Überschrift des gesamten Blocks
* H2: Das ist die Überschrift des jeweiligen Jobs. Die Firma steht zwischen den <span>-Tags
* class="time": Das ist die Verweildauer im Job.
* class="note": Das sind Notizen dazu.
  
Alle Blöcke können einfach ergänzt werden, indem die Bereiche von <div class="cvblock"> bis zum abschließenden </div> (Einrückungen beachten, dann kopiert es sich leichter) kopiert werden.
  
