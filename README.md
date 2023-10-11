> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je, zoals altijd, in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Hand / Footprint ✋🌍
<!-- Geef je project een titel en schrijf in één zin wat het is -->
Een dashboard waar je als klein bedrijf in een oog opslag kunt zien wat je hand/footprint is.

## Inhoudsopgave

  * [📔Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [📚Bronnen](#bronnen)
  * [dLicentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->
Ontwerp een webapplicatie waarmee een relatief klein bedrijf (tot ongeveer 100 man personeel) op een makkelijke, leuke manier geholpen wordt om zijn eigen handprint en footprint inzichtelijk te maken. De feitelijke situatie moet zo goed mogelijk worden gevisualiseerd.

Als gebruiker wil ik in een oogopslag kunnen zien wat de status van mijn hand/footprint is. 

<img width="1614" alt="Screenshot 2023-10-11 at 10 42 14" src="https://github.com/Jason2426/the-client-website/assets/143999883/933c8188-777c-44f4-aa86-1aeeeaef79f7">

<img width="1614" alt="Screenshot 2023-10-11 at 10 40 19" src="https://github.com/Jason2426/the-client-website/assets/143999883/8a688490-e69a-4483-ae5b-5e01cd269939">



## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->
De website is gebouwd met HTML & CSS

Tools die ik heb gebruikt : VS Code en Figma

### Navigatiebar en Header
In dit stuk code zie je de HTML elementen die ik heb gebruikt voor de nav en de header.
```html

<nav>
        <a href="#">Logo</a>
        <a href="#">Home</a>
        <a href="#">Handprint</a>
        <a href="#">Footprint</a>
    </nav>

    <header>
        <h2>
            Goodmorning Solebox
            <span>22:22</span>
        </h2>
    </header>

```
### Header styling
In dit stuk code kun je zien hoe ik de header style met de hand van CSS.

```css
header {
    background: #1a7f86;
    grid-area: header;
    
    & h2{
      margin: 0.75em;
      padding: 0em 1.2em 0em 1.2em;
      color: #f2fdff;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
```

## Bronnen 

[Dribbble Shots](https://dribbble.com/tags/dribbble-shot)

[Voetafdruk van bedrijf uitrekenen](https://www.quentic.nl/vakbijdragen/co2-voetafdruk-bedrijven/)

[Workshop Dorien over CSS]

[Workshop Krijn Code Conventies] 



## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
