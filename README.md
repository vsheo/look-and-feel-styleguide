# Stylesheet Mediahuis

## Inleiding

Deze Stylesheet is gemaakt voor de opdracht _[Mediahuis](https://github.com/fdnd-agency/triple)_ van _[Triple](https://www.wearetriple.com/en/)_

Wij maken een website met daarop een radioguide waarbij de programmering van verschillende radiozenders te zien is. Hiervoor betrekken wij de huisstijl van elke zender (Radio Veronica, SLAM!, 100%NL en Sublime). Deze stylesheet biedt een overzicht van alle huisstijlen en maakt het mogelijk om deze stijlen toe te passen in eigen werk. 

Zie [hier](https://vsheo.github.io/look-and-feel-styleguide/) de stylesheet

## Kleuren
In de stylesheet zijn de kleuren van de 4 verschillende radiozenders van het Mediahuis verwerkt. Zie onderstaande afbeeldingen voor het juiste gebruik van deze kleuren:

<img src="https://github.com/user-attachments/assets/b0d1e8d1-8c15-43fd-8041-a2f926be6b93" width="300">
<img src="https://github.com/user-attachments/assets/80fd41d7-6622-496a-821b-94400a9129bd" width="300">
<img src="https://github.com/user-attachments/assets/aaee5b2e-b725-4b53-8994-91f70c425f94" width="300">
<img src="https://github.com/user-attachments/assets/45ee68cb-1ac1-494e-8006-5636324a35e9" width="300">

### Kleuren - Toepassen
Om de kleuren toe te passen, moeten er 2 classes in HTML worden toegevoegd aan het element dat je kleur wilt geven. De eerste class geeft aan dát er een kleur wordt meegegeven en welke functie deze kleur heeft, en de tweede class geeft aan welke kleur van de verschillende radiozenders gebruikt moet worden.

In de stylesheet staan deze classes beschreven, zie onderstaand afbeelding: 

<img src="https://github.com/user-attachments/assets/6476ab18-8b2f-4c77-9ecb-a5cfc91d01f2" width="350">

Stel je bent aan het werken aan de `footer` van Radio Veronica, dan gebruik je dus deze classes: 

```html
<footer class="footer veronica-footer">
    <p>Dit is de footer</p>
<footer>
```

En als je de `footer` aan het maken bent van SLAM, dan pas je dus alleen `veronica-footer` aan, en wordt dit dus `slam-footer`:

```html
<footer class="footer slam-footer">
    <p>Dit is de footer</p>
<footer>
```

## Typografie
Het font is <em>Brutal Type</em> en deze wordt voor de hele pagina gebruikt. Zie onderstaande afbeeldingen voor de juiste toepassingen. 

<img src="https://github.com/user-attachments/assets/07b79183-0f82-4aff-8648-b72f4bbafad7" width="350">
<img src="https://github.com/user-attachments/assets/161ae635-449f-43ae-be32-b4319cba0826" width="350">

### Typografie - Toepassen
Voeg in HTML 1 `class` toe, van het font dat je wilt toepassen: 
* "font-title" verwijst naar de gewilde styling van het font

```html
  <p class="font-title"> <strong>Titels van artikelen</strong><br>Lorem ipsum dolor sit amet</p> 
```

## Buttons
Voor `button`s en `a` tags kunnen onderstaande classes gebruikt worden, hierin is ook een `:hover` verwerkt: 

<img src="https://github.com/user-attachments/assets/0af62436-f089-4875-92bd-0c779b0a8f6c" width="250">

## Forms
Voor forms kunnen de classes `input-placeholder` en `button-highlight` gebruikt worden. Zie onderstaande afbeelding voor de juiste toepassing. 

<img src="https://github.com/user-attachments/assets/80969049-5b08-4ecc-bfdc-2507e8536813" width="350">

## Afspraken
Er gelden een aantal afspraken m.b.t. aanpassen en/of aanvullingen doen van deze stylesheet: 
1. Bij een aanpassing en/of aanvulling dient er een issue gemaakt te worden met toelichting over de wijziging of toevoeging. Hierbij moet een visueel voorbeeld weergegeven worden en de nieuwe code. Ook moeten de overige teamleden getagd worden en toestemming geven en/of aanvullingen geven. Daarna kan de code gewijzigd en gepusht worden.
2. Iedereen moet het met de aanpassing en/of aanvulling eens zijn.
3. Alleen de persoon die de wijziging heeft voorgesteld wijzigt de code en pusht dit, om merge conflicten te voorkomen.
4. Wanneer er gepusht is, worden de andere teamleden ingelicht, zodat zij de actuele code kunnen pullen en met de juiste versie van de stylesheet kunnen werken.
5. <strong>Naamgeving</strong>: [naam element]-[element]-[beschrijving wat de property doet]


## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

