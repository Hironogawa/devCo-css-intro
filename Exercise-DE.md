Anleitung:

1.  Verwende die bereitgestellte HTML-Datei als Ausgangspunkt für deine Übung.

2.  Erstelle eine CSS-Datei, nenne sie styles.css und verlinke sie mit deinem HTML-Dokument.

3.  Allgemeine Seitengestaltung:

- Setze die Hintergrundfarbe des body-Elements auf #9f9f9f. Verwende eine geeignete Schriftart für die gesamte Seite. Du kannst Verdana, Geneva, Tahoma oder eine serifenlose Schriftart verwenden.
- Entferne das margin und das padding des body-Elements, indem du beides auf 0 setzt.

4.  Gestaltung des main-Elements:

- Style den Hauptcontainer wie folgt (verwende das HTML-Element main):
- Zeige den Inhalt als Spalte an (display flex) mit der Eigenschaft flex-direction (column).
- Füge ein padding von 12px hinzu, um Platz um den Inhalt zu schaffen.

5.  Textgestaltung:

- Erstelle CSS-Regeln für Textelemente mit verschiedenen Klassen:
  - .title: Style mit einer Schriftgröße von 120px und in bold (font-weight). Stelle sicher, dass kein Rand (margin) vorhanden ist, indem du ihn auf 0 setzt.
  - .paragraph: Setze die Textfarbe (color) auf #000000.
  - .paragraph.dark-mode: Für diesen Kombinations-Selektor ändere die Textfarbe (color) in #eeeeee.
  - .text-size-small: Setze die Schriftgröße (font-size) (font-size) auf 16px.
  - .text-size-medium: Setze die Schriftgröße (font-size) auf 24px.
  - .text-size-large: Setze die Schriftgröße (font-size) auf 36px.

6.  Layout Container Styling:

- Erstelle einen Container mit der Klasse .container und lege die folgenden Eigenschaften fest:
  - Stelle die Child-Elmente als Zeile an (display und verwende flex-direction/Flexbox).
  - Richte die boxen horizonatl (justify content) mit space-between aus.
  - Richte die Elemente (align items) zentriert (center) an.
  - Füge einen Abstand (gap) von 12px zwischen den Child hinzu.
  - Setze eine Höhe (height) von 300px.
  - Lass ihn die volle Breite (width) einnehmen (Breite 100%).
  - Füge einen Abstand (margin) unten von 12px hinzu.

7.  Gestaltung der Boxen:

- Gestalte die Elemente mit der Klasse .box wie folgt: - Verwende box-sizing, um sicherzustellen, dass das Padding die Gesamtbreite und höhe (height) des Elements nicht beeinflusst (border-box). - Setze Höhe (height) und Breite (width) auf 100%.
  - Füge ein Padding von 12px hinzu.
  - Setze die Hintergrundfarbe (background-color) auf #00ffbf.
  - Erstelle einen Kombinations-Selektor .box h2, um h2-Elemente innerhalb von .box-Elementen zu gestalten, und setze den Rand (margin) auf 0.

8.  Klasse für Hintergrundfarbe:

- Erstelle eine Hintergrund-Klasse .bg-red, die die Hintergrundfarbe (background-color) auf #ff0000 setzt.

9.  Erstelle eindeutige IDs für Box 1 und Box 2. Die beiden Boxen sollten bis auf die Hintergrundfarbe identisch sein:

- box-1:
  - Verwende box-sizing, um festzulegen, dass das Padding in die Gesamtbreite und höhe des Elements einbezogen werden soll (border-box).
  - Setze Höhe (height) und Breite (width) von #box-1 auf 100%, sodass sie die volle Höhe und Breite des umgebenden Elements einnimmt.
  - Füge ein Padding von 12px hinzu, um Platz im Inneren des Elements zu schaffen.
  - Setze die Textfarbe (color) auf #eeeeee (Hellgrau).
  - Setze die Hintergrundfarbe (background-color) auf #0d2927 (ein dunkles Türkis oder Blaugrün).
- Gestaltung für #box-2:
  - Kopiere die Gestaltung von #box-1 und wende sie auf #box-2 an.
  - Ändere die Hintergrundfarbe (background-color) auf #515e78 (eine gedämpfte blaugraue Farbe).

10. Gestaltung der Überschriften:

- Gestalte alle h2-Elemente auf der Seite:
  - Entferne den Rand (margin), indem du ihn auf 0 setzt.
  - Setze die Schriftgröße (font-size) auf 32px.

11. Transformations-Effekte:

- Erstelle eine Klasse .transform-width mit den folgenden Eigenschaften:
  - Setze eine Mindestbreite (min-width) von 600px.
  - Füge einen Übergangseffekt (transition) für die Mindestbreite (min-width) über 0,5s mit ease-in-out hinzu.
  - Erstelle eine Kombinationsklasse .transform-width:hover mit den folgenden Eigenschaften:
    - Verwende die :hover-Pseudo-Klasse, um die Mindestbreite (min-width) bei Hover auf 1200px zu erhöhen, und füge einen Cursor-Pfeil (cursor pointer) hinzu.

12. Animations-Effekte:

- Definiere Animations-Frames (keyframes) für die folgenden Klassen:

  - Erstelle eine Klasse .animate-text-color:

    - Füge die Farbe (color) #fff zur Klasse hinzu und den Animationsnamen (animation) "color" mit einer Dauer (duration) von 1s linear und unendlich (infinite).
    - Erstelle eine Animation (@keyframe) namens "color", die die Textfarbe übergeht:

      - Setze die Textfarbe (color) bei 0% auf #eeeeee (Hellgrau).
      - Setze die Textfarbe (color) bei 50% auf #000000 (Schwarz).
      - Setze die Textfarbe (color) bei 100% auf #eeeeee (Hellgrau).

  - Erstelle eine Klasse .animate-rotate:
    - Füge den Animationsnamen (animation) "rotate" mit einer Dauer von 5s linear und unendlich (infinite) hinzu.
    - Füge "transform-origin: center" zur Klasse hinzu.
    - Erstelle eine Animation (@keyframe) namens "rotate" für die Rotation:
      - Setze eine Transformationsrotation (tranform rotate) von 0 Grad bei 0%.
      - Setze eine Transformationsrotation (tranform rotate) von 180 Grad bei 50%.
      - Setze eine Transformationsrotation (tranform rotate) von 360 Grad bei 100%.
  - Erstelle eine Klasse .animate-wiggle:
    - Füge den Animationsnamen "wiggle" mit einer Dauer (duration) von 1s ease-in-out und unendlich (infinite) hinzu.
    - Erstelle eine Animation (@keyframe) namens "wiggle" für einen Wackeleffekt:
      - Setze eine Transformationsverschiebung (translateX) von 12px bei 0%.
      - Setze eine Transformationsverschiebung (translateX) von -12px bei 50%.
      - Setze eine Transformationsverschiebung (translateX) von 12px bei 100%.
  - Erstelle eine Kombinationsklasse .animate-shake:hover:
    - Füge einen Cursor-Pfeil (cursor pointer) zur Klasse hinzu.
    - Füge den Animationsnamen "shake" mit einer Dauer (duration) von 0,25s ease-in-out und unendlich (infinite) hinzu.
    - Erstelle eine Animation (@keyframe) namens "shake", die bei Hover einen Wackeleffekt auslöst:
      - Setze eine Transformationsverschiebung (transform translate) von 9px, 3px bei 0%.
      - Setze eine Transformationsverschiebung (transform translate) von -9px, -3px bei 50%.
      - Setze eine Transformationsverschiebung (transform translate) von 9px, 3px bei 100%.
  - Erstelle eine Klasse .animate-mix:
    - Füge "transform-origin: center" zur Klasse hinzu.
    - Füge beide Animationen (animation) "color" und "rotate" durch ein Komma getrennt zur Klasse hinzu.
    - "Color" hat eine Dauer (duration) von 1s linear und unendlich (infinite).
    - "rotate" hat eine Dauer (duration) von 5s             lich (infinite).

13. Testen und Anpassen:

- Teste deine Webseite, um sicherzustellen, dass sie wie beabsichtigt angezeigt wird.
- Füge Klassen zu den HTML-Elementen hinzu, um die von dir erstellten Styles anzuwenden, oder passe die CSS-Selektoren an, um sie an die HTML-Elemente anzupassen.
- Du kannst den Inhalt nach Belieben anpassen und deine eigene Kreativität anwenden, während du dich an die bereitgestellten Richtlinien hältst.

- Versuche, die Übung abzuschließen, ohne den endgültigen CSS-Code anzusehen. Nachdem du die Übung abgeschlossen hast, kannst du die Lösung mit deinem endgültigen CSS-Code vergleichen, um zu sehen, wie genau du die gewünschten Styles und Animationen erstellt hast.
