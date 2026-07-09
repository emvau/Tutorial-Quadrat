# Quadrat fahren @tutorial
##   @fullscreen
In diesem Tutorial programmieren wir den Maqueen Plus V2 so,
dass er auf Knopfdruck ein Quadrat fährt! ⬛🤖
Denke daran, zuerst die Erweiterung zu installieren.
## 
Zuerst initialisieren wir den Roboter.
Füge den Block ``||MaqueenPlusV2:initialisiere Maqueen Plus V2||`` ein.
##  
Jetzt reagieren wir auf einen Knopfdruck.
Füge den Block ``||input:wenn Knopf A gedrückt||`` ein.
##  
Ein Quadrat hat **4 Seiten** – also wiederholen wir die Bewegung 4 mal.
Füge eine ``||loops:4 mal wiederholen||`` Schleife in den ``||input:wenn Knopf A gedrückt||`` Block ein.
##  
Jetzt programmieren wir eine Seite des Quadrats.
Füge innerhalb der Schleife folgende Blöcke ein:
- ``||MaqueenPlusV2:steuere beide Räder vorwärts Geschwindigkeit 100||``
- ``||basic:pausiere 1000 ms||``
- ``||MaqueenPlusV2:stop beide Räder||``
##  
Jetzt drehen wir den Roboter um 90°.
Füge nach dem Stopp-Block ein:
- ``||MaqueenPlusV2:steuere rechtes Rad vorwärts Geschwindigkeit 100||``
- ``||basic:pausiere 500 ms||``

##    @fullscreen

Fertig! 🎉

Drücke den **Knopf A** auf dem Micro:bit und schau zu wie der Maqueen ein Quadrat fährt!

💡 **Aufgaben zum Ausprobieren:**
- Ändere die Pausenzeit von **1000ms** – was passiert mit der Seitenlänge?
- Ändere die Drehzeit von **500ms** – was passiert mit den Ecken?
- Kannst du statt einem Quadrat ein **Dreieck** fahren lassen? 🤔
