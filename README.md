HTML


1. **HTML-Struktur:**
   html
   <html lang="en">
   <head>
      <!-- Meta-Tags für Zeichensatz, Kompatibilität und Ansichtseinstellungen -->
      <meta charset="UTF-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      
      <!-- Titel der Webseite -->
      <title>IM5 - MEMES - Rebekka Pérez</title>
      
      <!-- Verweise auf externe Stylesheet- und JavaScript-Dateien -->
      <link rel="stylesheet" href="./styles.css">
      <script src="script.js"></script>
   </head>
   <body>
   
   - Die `html`-Tags umschliessen den gesamten HTML-Inhalt der Seite.
   - Die `head`-Tags enthalten Metadaten wie Zeichensatz, Kompatibilität und den Viewport für die responsive Darstellung auf verschiedenen Geräten.
   - Der `title`-Tag definiert den Titel der Webseite, der im Browser-Tab angezeigt wird.
   - Es gibt Verweise auf ein externes Stylesheet (`styles.css`) und eine externe JavaScript-Datei (`script.js`).


2. **Header-Bereich:**
   html
      <header class="container">
         <!-- Ein Bild und ein Haupttitel innerhalb eines Containers -->
         <img class="full" id="titelbild" src="./img/2.jpg" alt="fischer" >
         <h1 class="haupttitel">[miːm]</h1>
         <br class="nur-desktop">
      </header>
   
   - Der Header enthält ein Bild mit der ID "titelbild" und einen Haupttitel.
   - Der Zeilenumbruch `<br class="nur-desktop">` wird nur auf Desktop-Geräten angezeigt.


3. **Zurück nach oben-Link:**
   html
      <a href="#" class="to-top">
         <i class="fas fa-chevron-up"></i>
      </a>
   - Ein Link mit der Klasse "to-top" und einem Icon für den Zurück-nach-oben-Button.


4. **Textcontainer und Abschnitte:**
   html
      <div class="textcontainer">
         <!-- Ein Textabschnitt über Memes -->
         <p>Ich habe meine Bachelorarbeit und mein Lehrprojekt über Memes verfasst. ...</p>
      </div>
   
   - Ein Container für Text mit einem Abschnitt, der Informationen über die Bachelorarbeit und das Lehrprojekt enthält.


5. **Bildbeschreibungen und Bilder:**
   html
      <div class="bildbeschreibung">
         <!-- Ein Abschnitt mit einer Bildbeschreibung -->
         <p>Ich liebe das Spiderman Meme es ist sehr vielfältig brauchbar...</p>
      </div>
      <img class= "full" src="./img/1.jpg" alt="renovate" />
      <!-- Weitere Bilder mit Abschnitten und Bildbeschreibungen -->
   
   - Bildbeschreibungen und Bilder, die durch `<img>`-Tags eingebettet sind.


6. **Weitere Abschnitte, Bilder und Textcontainer:**
   html
      <!-- Weitere Abschnitte, Bilder und Textcontainer -->
   


7. **Kommentierte Bereiche (ausgeklammert):**
   html
      <!--<ul class="slides" id ="nur-fuer-mobile-2">
         <!-- Kommentierte Abschnitte, die für eine Bildergalerie oder Slideshow vorgesehen sind -->
      </ul>-->


   - Ein Bereich, der auskommentiert ist und für eine Bildergalerie oder Slideshow gedacht war, welche nicht responsive wurde und ich mich dann entschieden habe sie wegzulassen.


8. **Abschluss der Seite mit Credits und Footer:**
   html
      <div class="credits">
         <!-- Abschnitt für Credits -->
         <p>Memes und Text: Rebekka Pérez</p>
      </div>
      <footer>
         <!-- Footer-Bereich mit einem Zurück-nach-oben-Link -->
         <div class="backtotop">Zurück nach oben</div>
      </footer>
   </body>
   </html>
   
   - Der Abschnitt "credits" enthält Informationen über den Urheber der Memes und des Textes.
   - Der Footer enthält einen Link zum Zurückscrollen nach oben.


________________


Css


1. **Header Styles:**
   ```css
   header {
       text-align: center;
   }
   ```
   Dieser Abschnitt zentriert den Text im Header.


2. **Clearfix Styles:**
   ```css
   .clear {
       clear: both;
   }
   ```
   Die Klasse `.clear` wird wahrscheinlich als Clearfix verwendet, um floatende Elemente zu klären.


3. **Title Styles:**
   ```css
   .title {
       position: relative;
   }
   ```
   Dieser Abschnitt gibt einem Element mit der Klasse `.title` eine relative Position, was häufig für Positionierungszwecke verwendet wird.


4. **Body Styles:**
   ```css
   body {
       background-color: black;
       display: flex;
       flex-direction: column;
   }
   ```
   Der Hintergrund der Webseite wird auf Schwarz gesetzt, und der Hauptinhalt wird in einer Spalte (column) angezeigt.


5. **HTML Styles:**
   ```css
   html {
       scroll-behavior: smooth;
   }
   ```
   Das Scrollverhalten für die Webseite wird auf ein sanftes Scrollen (smooth) eingestellt.


6. **Link Styles:**
   ```css
   a {
       color: white;
   }
   ```
   Alle Links auf der Seite haben die Farbe Weiss.


7. **Textcontainer Styles:**
   ```css
   .textcontainer {
       /* ... */
   }
   ```
   Dieser Abschnitt enthält Stildefinitionen für einen Container, der Text enthält.


8. **Horizontal Rule Styles:**
   ```css
   hr {
       width: 100%;
       color: white;
   }
   ```
   Horizontale Linien haben eine Breite von 100% und die Farbe Weiss.


9. **"To Top" Button Styles:**
   ```css
   .to-top {
       /* ... */
   }


   .to-top.active {
       /* ... */
   }
   ```
   Stildefinitionen für einen "To Top"-Button mit Animationseffekten beim Scrollen.


10. **Full Width Image Styles:**
   ```css
   .full {
       /* ... */
   }
   ```
   Dieser Abschnitt definiert Stilregeln für ein Bild, das die volle Breite des Containers einnimmt.


11. **Flexbox Container Styles:**
   ```css
   .flexboxcontainer {
       /* ... */
   }
   ```
   Ein Container mit flexibler Box-Anordnung für die Ausrichtung von Elementen.


12. **Image Borders Styles:**
   ```css
   .imageborders35 {
       /* ... */
   }
   ```
   Dieser Abschnitt definiert Stilregeln für Bilder mit Rändern.


13. **Container Styles:**
   ```css
   .container {
       /* ... */
   }
   ```
   Allgemeine Stildefinitionen für einen Container, der Text und Bilder enthält.


14. **Haupttitel Styles:**
   ```css
   .haupttitel {
       /* ... */
   }
   ```
   Definitionen für den Haupttitel, einschliesslich Schriftart, Grösse und Schatten.


15. **Bildbeschreibung Styles:**
   ```css
   .bildbeschreibung {
       /* ... */
   }
   ```
   Stilregeln für die Beschreibung eines Bildes, einschliesslich Rahmen und Hintergrund.


16. **Credits and Backtotop Styles:**
   ```css
   .credits,
   .backtotop {
       /* ... */
   }


   .credits {
       /* ... */
   }


   .backtotop {
       /* ... */
   }
   ```
   Stilregeln für Elemente mit den Klassen `.credits` und `.backtotop`.


17. **Footer Styles:**
   ```css
   footer {
       /* ... */
   }
   ```
   Definitionen für den Footer, einschliesslich Polstern und Hintergrundfarben.


18. **Slider Styles:**
   Die Slider-Stile sind auskommentiert, was bedeutet, dass sie deaktiviert wurden. Diese Stile steuern die Präsentation von Bildern oder Inhalten in einem Slider.


19. **Media Queries:**
   ```css
   @media only screen and (min-width: 200px) (max-width: 600px) {
       /* ... */
   }


   /* ... */


   @media only screen and (min-width: 800px) {
       /* ... */
   }
   ```
   Media Queries, die verschiedene Stilregeln je nach Bildschirmbreite anwenden. Zum Beispiel werden bei Bildschirmbreiten zwischen 200px und 600px bestimmte Stile angewendet.


Diese Kommentare bieten eine Zusammenfassung der verschiedenen Stilregeln und Klassen im bereitgestellten Css-Code.
Java Script


1. **Scroll-to-Top-Button-Logik:**
   ```javascript
   const toTop = document.querySelector(".to-top");


   window.addEventListener("scroll", () => {
      if (window.pageYOffset > 10) {
         toTop.classList.add("active");
      } else {
         toTop.classList.remove("active");
      }
   });
   ```
   Diese Abschnitte implementieren die Logik für einen "Zum Seitenanfang"-Button. Sobald der Benutzer 10 Pixel oder mehr nach unten scrollt, wird dem Button eine Klasse "active" hinzugefügt, was es ermöglicht, das Aussehen des Buttons zu ändern (z. B. die Farbe). Andernfalls wird die Klasse entfernt.


2. **Anzeigen des "Zurück nach oben"-Buttons beim Scrollen:**
   ```javascript
   let mybutton = document.getElementById("myBtn");


   window.onscroll = function() {
      scrollFunction();
   };


   function scrollFunction() {
      if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
         mybutton.style.display = "block";
      } else {
         mybutton.style.display = "none";
      }
   }
   ```
   Hier wird der "Zurück nach oben"-Button angezeigt, wenn der Benutzer 20 Pixel oder mehr nach unten scrollt. Andernfalls wird der Button ausgeblendet.


3. **Scrollen zum oberen Rand des Dokuments:**
   ```javascript
   function topFunction() {
      document.body.scrollTop = 0; // Für Safari
      document.documentElement.scrollTop = 0; // Für Chrome, Firefox, IE und Opera
   }
   ```
   Dies ist die Funktion, die aufgerufen wird, wenn der Benutzer auf den "Zurück nach oben"-Button klickt. Sie sorgt dafür, dass die Seite zum oberen Rand des Dokuments scrollt.


4. **Slideshow (auskommentiert):**
   Der letzte Abschnitt enthält Funktionen zur Implementierung einer Diashow mit Navigationssteuerelementen. Alle Funktionen sind auskommentiert und werden daher nicht aktiviert. Wenn du die Diashow verwenden möchtest, müsstest du die entsprechenden Kommentare entfernen.


Die Kommentare (`/* ... */`) dienen dazu, Codeblöcke auszukommentieren, was bedeutet, dass sie vom Interpreter ignoriert werden. In diesem Fall wurden die Diashow-Funktionen auskommentiert, sodass sie nicht ausgeführt werden. 




IM 5        -         Rebekka Pérez
