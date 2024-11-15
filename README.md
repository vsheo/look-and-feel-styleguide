# Styleguide

Zie hier de stylesheet: https://vsheo.github.io/look-and-feel-styleguide/.

## Kleuren
De kleuren van de huisstijlen van de verschillende zenders zijn gecategoriseerd als: `brand` `background` en `text`. 

Zie onderstaande afbeeldingen voor de juiste toepassingen (Radio Veronica als voorbeeld). 

Zie hier het overzicht van de kleuren voor alle radiozenders: https://vsheo.github.io/look-and-feel-styleguide/.

<img src="https://github.com/user-attachments/assets/2a592a7f-eee9-4bbd-9724-11a273241aa6" width="350">
<img src="https://github.com/user-attachments/assets/9cf589eb-b4ea-48fe-a02e-75deb1cf24ed" width="350">

### Toepassen
Voeg in HTML 2 `class`es toe: 
* "brand-primary" dit verwijst naar de toepassing van de kleur (bijvoorbeeld de kleur van de zender)
* "brand-primary-veronica" dit verwijst naar de kleur van de juiste zender (in dit voorbeeld dus de blauwe kleur van Veronica)

```html
    <figure>
      <code class="brand-primary brand-primary-veronica">#0091FF</code>
      <figcaption>Brand-kleur Veronica</figcaption>
    </figure>
```

## Typografie
Het font is <em>Brutal Type</em> en deze wordt voor de hele pagina gebruikt. Zie onderstaande afbeeldingen voor de juiste toepassingen. 

<img src="https://github.com/user-attachments/assets/07b79183-0f82-4aff-8648-b72f4bbafad7" width="350">
<img src="https://github.com/user-attachments/assets/161ae635-449f-43ae-be32-b4319cba0826" width="350">

### Toepassen
Voeg in HTML 1 `class` toe, van het font dat je wilt toepassen: 
* "font-title" verwijst naar de gewilde styling van het font

```html
  <p class="font-title"> <strong>Titels van artikelen</strong><br>Lorem ipsum dolor sit amet</p> 
```

## Forms
Voor forms kunnen de classes `input-placeholder` en `button-highlight` gebruikt worden. Zie onderstaande afbeelding voor de juiste toepassing. 

<img src="https://github.com/user-attachments/assets/80969049-5b08-4ecc-bfdc-2507e8536813" width="350">

### Toepassen
Voeg in HTML 1 `class` toe, van het element dat je wilt toepassen: 
* "button-highlight" verwijst bijvoorbeeld naar de juiste styling van de knop

## Afspraken
Er gelden een aantal afspraken m.b.t. aanpassen en/of aanvullingen doen van deze stylesheet: 
1. Bij een aanpassing en/of aanvulling dient er een issue gemaakt te worden met toelichting over de wijziging of toevoeging. Hierbij moet een visueel voorbeeld weergegeven worden en de nieuwe code. Ook moeten de overige teamleden getagd worden en toestemming geven en/of aanvullingen geven. Daarna kan de code gewijzigd en gepusht worden.
2. Iedereen moet het met de aanpassing en/of aanvulling eens zijn.
3. Alleen de persoon die de wijziging heeft voorgesteld wijzigt de code en pusht dit, om merge conflicten te voorkomen.
4. Wanneer er gepusht is, worden de andere teamleden ingelicht, zodat zij de actuele code kunnen pullen en met de juiste versie van de stylesheet kunnen werken.
5. <strong>Naamgeving</strong>: [naam element]-[element]-[beschrijving wat de property doet]


## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

