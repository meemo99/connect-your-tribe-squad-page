# Pantone Squad page

Ontwerp en maak met een team een website met NodeJS en JSON.

De instructie vind je in: [INSTRUCTIONS](https://github.com/fdnd-task/connect-your-tribe-squad-page/blob/main/docs/INSTRUCTIONS.md)

## Inhoudsopgave Squad page

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Gebruik](#gebruik)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
<!-- Voeg een mooie poster visual toe 📸 -->
<!-- Voeg een link toe naar Github Pages 🌐-->
Ik heb een Pantone-style squad page gemaakt. Elk persoon in de squads zit in zijn eigen pantone kleurkaart, de kleur is gebasseerd op de favoriete kleur die is ingeculd in de whois. Je kan voor nu alleen nog filteren op squad.

<img width="1371" height="787" alt="Scherm­afbeelding 2026-03-01 om 16 45 00" src="https://github.com/user-attachments/assets/bc0249e9-d852-4081-9a57-3efca292bdd5" />
<img width="1371" height="727" alt="Scherm­afbeelding 2026-03-01 om 16 47 11" src="https://github.com/user-attachments/assets/d68ba2dc-5617-4f74-89dc-6b0c5b4b821e" />

### Background Change + Mugshot Reveal


https://github.com/user-attachments/assets/633a388b-df29-41ec-9e9c-92fe3a58d89f


### Filtered State
<img width="1371" height="790" alt="Scherm­afbeelding 2026-03-01 om 16 56 58" src="https://github.com/user-attachments/assets/39e1b407-3c05-4f19-86f5-f37b3aa7c4af" />
<img width="1371" height="790" alt="Scherm­afbeelding 2026-03-01 om 16 57 27" src="https://github.com/user-attachments/assets/c407cbad-4880-403d-9e5d-c5ad5152326d" />


## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->
De HTML bestaat uit een nav voor de filterbuttons en een section voor de pantone-kaarten. De sections zijn ingevuld met informatie uit de whoisAPI. 
Met JacaScript zijn de backgroundcolour change 
https://github.com/meemo99/connect-your-tribe-squad-page/blob/28edd4e3c8271b4334369fdeb63872a1d1e9b919/views/partials/foot.liquid#L5-L9 
en een active state voor de filters gemaakt 
https://github.com/meemo99/connect-your-tribe-squad-page/blob/28edd4e3c8271b4334369fdeb63872a1d1e9b919/views/partials/foot.liquid#L11-L14

De mugshot reveal is gedaan met CSS. 
https://github.com/meemo99/connect-your-tribe-squad-page/blob/28edd4e3c8271b4334369fdeb63872a1d1e9b919/public/style.css#L82-L84
De opacity van de achtergrondkleur wordt verlaagd naar 0 wanneer er gehoverd wordt, waardoor de mugshot dus tevoorschijn komt.
## Installatie
<!-- Bij Installatie staat stap-voor-stap beschreven hoe je de development omgeving moet inrichten om aan de repository te kunnen werken. -->

## Gebruik

## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
