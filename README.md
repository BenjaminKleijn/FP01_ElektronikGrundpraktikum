**Überblick**:\
Elektronik_Grundpraktikum.pdf = Protokoll vom Versuch\
FP_ElektronikGrundpraktikum_Gottwald,Kleijn_compressed.pdf = LaTeX Auswertung\
Dimensionierung.jpynb = Dimensionierung Berechnung, Ergebnisse sind auch in LaTeX Anhang

**Wie die TeX Datei funktioniert**:\
in latex_class ist die cls Datei mit allen packages und globale tex dateien, die man immer braucht, sonst einfach im Auswertung_TeX Ordner schauen, dort führt main.tex alles zusammen. 

**Wie wir Github benutzt haben**:\
local main = main\
remote main = origin/main\
local branch = Benjamin\
remote branch = origin/Benjamin  dient nur als Cloud Backup für die lokalen Änderungen\

Arbeitsablauf:\
In git graph schauen ob origin/main neu ist:\
  Ja - main auswählen und rightclick origin/main -> "Pull into current branch" anklicken (Neuer stand des origin/main wird auf main geschrieben, main wird also geupdatet)\
  Dann Benjamin auswählen und rightclick main -> "Merge into current branch" (main Stand (neuer) wird auch auf Benjamin übetragen)

Dann ist man in seinem Branch auf dem aktuellen Stand und kann weiterarbeiten.\
Nach der Arbeit Stage changes und commit&push um Benjamin zu updaten und origin/Benjamin als Backup zu nutzen

Ergebnisse hochladen:\
in main wechseln, rightclick Benjamin -> "Merge into current branch" (lädt Benjamin Änderungen auf main hoch)\
wenn man dann links sync drückt, dann kann man sich den folgenden schritt sparen\
  rightclick main -> "Push branch" (origin/main wird auf main Stand gebracht)

zurück auf Benjamin wechseln und weiterarbeiten
