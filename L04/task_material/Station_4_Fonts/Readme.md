# Station "Custom Fonts"

Positionierung und grundlegende Herangehensweise wie in Station 1.
Auf dieser Xmas Card sollen eigene Schriften verwerdet werden. Die Schrift-Dateien finden Sie im Ordner fonts/.


![Designvorlage](designvorlage.png)

Folgendes Vorgehen ist möglich:

1. Hintergrundmuster für den Body und Hintergrundbild für den Wrapper sind vorgegeben. Die vorgegeben Elemente „bg.png“ und „wrapperbg.png“ können jetzt schon einmal als Hintergrundgrafiken in CSS gesetzt werden (mit Eigenschaft „background-image“). Dazu natürlich erst einmal die Grundhtml-Struktur + Wrapper erstellen.
2. Suchen Sie sich eine passendene Schriftart (z.B. auf dafont.com) oder nehmen Sie die Schrift aus dem Arbeitspaket im Order „fonts“.
3. Die Schrift muss jetzt für sämtliche Browser in ein passendes Format gebracht werden. Gehen Sie dazu auf http://www.fontsquirrel.com/fontface/generator und konvertieren Sie die Schrift in verschiedene Formate. Bei Schrift ist es wie mit Videos, Audio usw... Die Browser unterstützen immer nur ganz bestimmte Formate, deshalb müssen sämtliche Schriftformate (SVG, TTF usw.) vorbereitet werden, um möglichst viele Browser zu bedienen (siehe auch https://caniuse.com/#feat=fontface).
4. Laden Sie das Schriftpaket herunter und fügen Sie die generierten Schriften-Dateien in den Ordner „fonts“ (nur die Schriften, nicht die mitgelieferten Beispieldateien)
5. Das Einbinden in CSS erfolgt mit einem langen Import-Script. Recherchieren Sie dafür in der W3Schools Dokumentation nach "@font-face“.
6. Die Pfade und Namen in Einbettungscode anpassen (Ordner und Schriftart-Name).
7. Jetzt können Textelemente im Container erstellt werden (mit h1, h2, p usw.)
8. Schließlich in CSS die Text-Tags mit der Eigenschaft font-family stylen. Der erste Wert ist dabei der Name der neuen Schrift, mit Komma werden alternative Schriften dem Browser angeboten, falls er keine eigenen Fonts unterstützt (ältere Browser).