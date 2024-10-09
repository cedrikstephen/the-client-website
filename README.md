# The Client - Website

## Inhoudsopgave Readme

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->
Link naar website: https://cedrikstephen.github.io/the-client-website/leden

Voor De Voorhoede zijn wij bezig met het bouwen van de site van de Dutch Digital Agencies.

Bij dit project ben ik voornamelijk bezig met de "onze leden" pagina.

![coverleden](https://github.com/user-attachments/assets/35625f0f-43dc-4c74-821e-6711c37024e5)


*Dutch Digital Agencies*

DDA verbindt sinds 2002 toonaangevende digitale bureaus in Nederland. Met 167 leden delen zij kennis en stimuleren innovatie door evenementen zoals de Dutch Digital Day, waar digitalisering en technologie vanuit nieuwe invalshoeken worden belicht. DDA richt zich op samenwerking en talentontwikkeling, en zet zich in om de digitale industrie continu vooruit te helpen.

*Doel van de sprint review*

- Feedback krijgen op werk. Wat is goed, wat is slecht en wat kan beter.
- Hoe verder?

*Vragen/feedback*

1. Header en filter (niet clickable) (Moet deze clickable zijn? + subsecties)
2. Cards + Label (is er al extra informatie voor de labels?)
3. Ticker: Moet deze langzamer of is het goed zo?
4. Er is geen mobiel ontwerp. Kunnen wij deze gewoon maken zoals de events pagina

*Dingen om te negeren*
- Responsiveness

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

Deze website is gebouwd in HTML & CSS

Alle knoppen werken (nog) niet.

De pagina is gemaakt zonder grid. Voor de cards is flexbox gebruikt om deze netjes naast elkaar te zetten.

![image](https://github.com/user-attachments/assets/bc537916-5c8d-444d-ae70-d5f564997f91)

Ticker is volledig toegankelijk gemaakt voor screenreaders. De screenreader leest niet de hele ticker af maar alleen 1x de logos.

![image](https://github.com/user-attachments/assets/93619a05-4178-45a3-8a74-d0032e41cc6a)


~~~
<div class="img-ticker-container">
          <div class="img-ticker">
            <img
              class="tickerlogo"
              src="assets/ictrecht.png"
              alt="logo ictrecht"
            />
            <img class="tickerlogo" src="assets/amac.png" alt="logo amac" />
            <img
              class="tickerlogo"
              src="assets/rootnet.png"
              alt="logo rootnet"
            />

            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/ictrecht.png"
            />
            <img aria-hidden="true" class="tickerlogo" src="assets/amac.png" />
            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/rootnet.png"
            />

            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/ictrecht.png"
            />
            <img aria-hidden="true" class="tickerlogo" src="assets/amac.png" />
            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/rootnet.png"
            />

            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/ictrecht.png"
            />
            <img aria-hidden="true" class="tickerlogo" src="assets/amac.png" />
            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/rootnet.png"
            />

            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/ictrecht.png"
            />
            <img aria-hidden="true" class="tickerlogo" src="assets/amac.png" />
            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/rootnet.png"
            />

            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/ictrecht.png"
            />
            <img aria-hidden="true" class="tickerlogo" src="assets/amac.png" />
            <img
              aria-hidden="true"
              class="tickerlogo"
              src="assets/rootnet.png"
            />
          </div>
        </div>
~~~
          
## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
