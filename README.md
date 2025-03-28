Mensch-Computer-Interaktion Übungsblatt 4 Sommersemester 2018 bei Dr. Bastian Pfleging an der Universität Stuttgart. Aufgabenstellung waren wie folgt:
## B) Fitts’ Gesetz: Experiment gestalten

## B.1) [exercise04_task_b1.html](exercise04_task_b1.html)

Programmieren Sie ein **1D** Fitts’ Gesetz Experiment in JavaScript oder
ProcessingJS. Das Experiment soll ein rotes Rechteck (kein Quadrat) als
Zielpunkt anzeigen auf einer mittig platzierten horizontalen Linie anzeigen
(siehe Abbildung 1). Die Breite der Linie soll hierbei der minimalen
Browserbreite ihres (gedrehten) Smartphones oder Ihres
Desktoprechners/Laptops entsprechen.
Der Benutzer soll mittels Zeigegerät das Ziel auswählen. Wenn der Benutzer das
Ziel ausgewählt hat, soll das nächste Ziel an einer zufälligen Position auf der
schwarzen Linie auf dem Bildschirm erscheinen, jedoch soll ein Mindestabstand
zum vorherigen Ziel von 30 Pixeln eingehalten werden. Wiederholen Sie diese
Prozedur für 50 Ziele. Verfehlt der Benutzer das Ziel soll nichts geschehen.
Implementieren Sie zudem eine Logging-Funktion, mit der die notwendigen
Daten gespeichert (und später ausgegeben) werden, um später Ihr Experiment
auswerten zu können.

Weiterhin sollen die Ziele immer vollständig auf dem Bildschirm erscheinen und
nicht durch den Bildschirmrand abgeschnitten werden. Untersuchen Sie fünf
**verschiedene Zielgrößen [Breite x Höhe]** : 20x10px, 40x20px, 60x30px,
80x40px und 100x50px. Jedes dieser Ziele soll 10 - mal während der 50
Wiederholungen erscheinen. Nach jedem erkannten Ziel soll das neue
erscheinende Ziel eine zufällige gewählte Zielgröße (20x10px, 40x20px,
60x30px, 80x40px oder 100x50px) haben.

## B.2) [exercise04_task_b2.html](exercise04_task_b2.html)

Programmieren Sie ein **2D** Fitts’ Gesetz Experiment in JavaScript oder
ProcessingJS. Das Experiment soll ein rotes Rechteck (kein Quadrat) als
Zielpunkt anzeigen (siehe Abbildung 2 ). Die Größe des Fensters soll der
minimalen Browserauflösung Ihres Smartphones oder Ihres Desktoprechners /
Laptops entsprechen. Der Benutzer soll mittels Zeigegerät das Ziel auswählen.
Wenn der Benutzer das Ziel ausgewählt hat, soll das nächste Ziel an einer
zufälligen Position auf dem Bildschirm erscheinen, jedoch soll ein
Mindestabstand zum vorherigen Ziel von 30 Pixeln eingehalten werden.
Wiederholen Sie diese Prozedur für 5 0 Ziele. Verfehlt der Benutzer das Ziel soll
nichts geschehen.
Implementieren Sie zudem eine Logging-Funktion, mit der die notwendigen
Daten gespeichert (und später ausgegeben) werden, um später Ihr Experiment
auswerten zu können.

Weiterhin sollen die Ziele immer vollständig auf dem Bildschirm erscheinen und
nicht durch den Bildschirmrand abgeschnitten werden. Untersuchen Sie fünf
**verschiedene Zielgrößen [Breite x Höhe]** : 20x10px, 40x20px, 60x30px,
80x40px und 100x50px. Jedes dieser Ziele soll 10 - mal während der 50
Wiederholungen erscheinen. Nach jedem erkannten Ziel soll das neue
erscheinende Ziel eine zufällige gewählte Zielgröße (20x10px, 4 0 x20px,
60 x30px, 80x40px oder 10 0 x50px) haben.
