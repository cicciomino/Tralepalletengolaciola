# 🎬 Braccio Accelerante + Esplosione

Una scena 3D interattiva in **Three.js** dove un personaggio sdraiato su un letto muove il braccio accelerando in modo progressivo per 5 secondi, per poi esplodere in pezzi che cadono con fisica realistica.

## ✨ Caratteristiche

- **Animazione del braccio** con frequenza che accelera non linearmente (da 6 Hz fino a 900 Hz)
- **Motion blur** simulato tramite "fantasmi" del braccio con opacità crescente
- **Esplosione fisica** con gravità, rimbalzi, attrito e rotazioni casuali
- **Rilevamento collisioni** con letto e pavimento
- **Camera responsive** ottimizzata per schermi portrait (mobile)
- **Reset automatico** dopo che i pezzi si sono fermati

## 🎮 Come si usa

1. Apri la pagina
2. Premi il pulsante **▶ Play**
3. Guarda il braccio accelerare per 5 secondi
4. 💥 Boom! Il personaggio esplode
5. La scena si resetta e puoi riprovare

## 🛠️ Tecnologie

- [Three.js](https://threejs.org/) `v0.160.0` (via CDN / importmap)
- JavaScript ES Modules nativo
- HTML5 / CSS3

Nessun build step necessario: è un singolo file HTML autonomo.

## 📦 Deploy su GitHub Pages

Il progetto è pubblicato automaticamente tramite **GitHub Actions** ad ogni push sul branch `main`.

Workflow: `.github/workflows/pages.yml`

## 📁 Struttura
