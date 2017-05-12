Source files for map_revocatoria
=====

## Description

Please provide a short description of this project

## Data
Please link to any external data used, as well as scripts for cleaning and analyzing that data, all of which should live in the `/data` directory.

## Installation
After cloning the repository run:
```
npm install
```

To start watching the project and opening in the browser run:
```
npm start
```

To deploy to GitHub pages run:
```
npm run deploy
```

---

## Embeding on LSV
To embed on a webpage use this code:
```html
<!-- START OF OUR INTERACTIVE -->
<script type="text/javascript">
window.map_revocatoria_data = {
  "name": "map_revocatoria"
}
</script>
<div class="lsv-interactive" id="map_revocatoria">
<img src="https://la-silla-vacia.github.io/map_revocatoria/screenshot.png" class="screenshot" style="width:100%;">
</div>
<script defer type="text/javascript" src="https://la-silla-vacia.github.io/map_revocatoria/script.js"></script>
<!-- END OF OUR INTERACTIE -->
```