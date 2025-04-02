# Tumi Mundo - Like Button

![afbeelding](https://github.com/user-attachments/assets/547176c8-d798-49e7-bdd8-fefe012e9ccc)
![afbeelding](https://github.com/user-attachments/assets/720e5859-ac88-4616-911b-50c492aabe59)



## Projectdoel
In dit project heb ik een interactieve like-button toegevoegd aan de playlists. Deze functie maakt het mogelijk voor gebruikers om playlists te liken.

## Oplevering
Geef hier aan wat je concreet hebt gemaakt tijdens de sprint:
- Een werkende like-knop toegevoegd aan playlists.
- Bij het klikken op de knop komt de gelikte playlist in de liked section.
- De knop is visueel herkenbaar en geeft feedback als het geliked is.

## Technologieën
Noem hier de gebruikte technologieën:
- **Express.js & Node.js** – voor de backend en routing
- **Liquid** – voor het genereren van dynamische HTML
- **HTML, CSS & JavaScript** – voor de opbouw, styling en interactie aan de frontend

## Kenmerken

### HTML & Liquid Templates
Ik heb de onderdelen die ik nodig heb verdeeld in partials, zodat ik die apart kan inladen als ik die nodig heb in mijn pagina.
#### Partials voor playlists
https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/35f54988cd2e6917713a7b39c48a7cc3678d5761/views/partials/playlists.liquid#L1-L32

#### Partials voor liked playlists
https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/35f54988cd2e6917713a7b39c48a7cc3678d5761/views/partials/likedplaylist.liquid#L1-L33

### CSS
Ik heb in mijn css gebruik gemaakt van custom proerties om de huisstijl van Tumi Mundo te behouden.
https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/4bb42a34a2f3d2b7d0de49eb3beaf2d20db11d6a/public/styles/style.css#L3-L99

Verder heb ik gebruik gemaakt van nesting in de css, zodat de code makkelijker lezen en veranderen is.
https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/4bb42a34a2f3d2b7d0de49eb3beaf2d20db11d6a/public/styles/style.css#L180-L267

### JavaScript

#### De GET
Om de data kunnen ophalen van de directus data base heb ik get request uitgevierd in mijn [server.js](https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/main/server.js)
https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/4b341bbe56527ed4b8a015aa6d524832c81b05ca/server.js#L54-L94
https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/4b341bbe56527ed4b8a015aa6d524832c81b05ca/server.js#L97-L105

#### De POST
https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/4b341bbe56527ed4b8a015aa6d524832c81b05ca/server.js#L107-L121


# [Website link](https://the-web-is-for-everyone-interactive-vlrt.onrender.com/)
