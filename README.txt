Aus Schattenaufnahmen von einem Objekt unter unterschiedlichen Winkeln rekonstruieren wir die 3d-Struktur des Objekts.
Wir erzeugen außerdem Animationen und Abbildungen zur Illustration des Rekonstruktionsprozesses.

JUPYTER NOTEBOOKS:

Erzeugen der Rekonstruktion.jpynb:
Aus den Schattenbildern wird die 3d-Struktur des Objekts rekonstruiert.
Die Schattenbilder müssen im Verzeichnis source_images stehen.
Ggf. müssen die Dateinamen und der Bildausschnitt im Code (Abschnitt Crop) angepasst werden.
Das Ergebnis steht als nimiertes gif im Verzeichnis "result". Das animierte GIF zeigt das 3d-Objekt, das 2x um seine eigene Achse gedreht wird.

Erzeugen der erläuternden Illustrationen.jypnb:
Zusätzlich zur Rekonstruktion des 3d-Objekts wird eine Animation erzeugt, in der dargestellt ist, wie das Objekt durch Ausschneiden aus einem gefüllten Quader mit den Schattenbildern als "Abstreifform" erzeugt wird.
Das Ergebnis steht im Verzeichnis "result"
Außerdem werden Illustrationen erzeugt, die die Schattenräume des Objekts mit dem (vollständig) darin liegenden Objekt zeigen
Das Ergebnis (animiertes GIF) steht in result/Illustration.


VERZEICHNISSE:
source_images:
Enthält die Schattenaufnahmen von dem Objekt unter verschiedenen Winkeln. Bei uns 0°, 30°, 60°, 90°, 120°, 150°

animation_images:
Die Ergebnisbilder, aus denen die Animation zusammengesetzt wird.


IMG_0032.JPG:
Foto von unserem Aufbau zur Aufnahme der Schattenbilder.