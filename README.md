**Überblick**:\
Elektronik_Grundpraktikum.pdf = Protokoll vom Versuch\
main_klein.pdf = LaTeX Auswertung\
Dimensionierung.jpynb = Dimensionierung Berechnung, Ergebnisse sind auch in LaTeX Anhang

**Wie die TeX Datei funktioniert**:\
in Auswertung__TeX/latex_class ist die cls Datei mit allen packages und globale tex dateien, die man immer braucht, sonst einfach im Auswertung_TeX Ordner schauen, dort führt main.tex alles zusammen. 

**Wie wir Github benutzt haben**:\
local main = main\
remote main = origin/main\
local branch = Benjamin\
remote branch = origin/Benjamin  dient nur als Cloud Backup für die lokalen Änderungen\

**Arbeitsablauf**:\
natürlich erstmal miktex, perl, latex-workshop (VS Code) als TeX-Installation für VS Code einrichten. Geht auch anders, hauptsache texen in VS Code.\
Fürs Arbeiten mit Github anstelle von Overleaf:\
Initial: Erstmal in VS Code gitgraph Erweiterung holen und git auf PC herunterladen. Dann leeres Repo (FP01_ElektronikGrundpraktikum) auf github erstellt, den Hauptordner (z.B. Studium/FP) im Explorer anklicken, als Terminal öffnen (oder in VS Code FP als Ordner öffnen, strg+ö für Terminal) und sich in das repo reinklonen mit `git clone <repo-URL>`, dann wird der Ordner Studium/FP/FP01_ElektronikGrundpraktikum erstellt. Den dann in VS Code öffnen, alle schon existierenden Dateien reinziehen, neu erstellen,..; dann mit gitgraph stagen, commit & pushen und fertig. Fürs Arbeiten zu zweit, siehe unten, muss man erstmal zwei branches erstellen, keine Ahnung mehr wie das ging.  

actual progress/arbeiten:\
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
