# Laboratori 05 — Micromon Schaefer-Smith (Grup 12E)

**Assignatura:** Simulació (SIM) · UPC · 12E  
**Membres:** Àngela Buxó, Pol Montanera  
**Professor:** Xavier Pi

Micromon del Lab 03: **Snap!** + **Insight Maker** + **visualització 2D** (MQTT).

---

## Com executar-ho

1. Obriu **`iface.html`** al navegador (doble clic o arrossegant-lo al navegador).

2. A Snap! (columna esquerra), importeu el projecte del repositori:

   **File → Open…** → `InsightMaker.xml`

3. Executeu els scripts del sprite **Sim**:

   - `connect insight channel upc`
   - `run model silent true`
   - `publish viz snapshot`

Insight Maker i la visualització 2D es carreguen sols a les altres columnes.

---

## Fitxers del repositori

| Fitxer | Descripció |
|--------|------------|
| `iface.html` | Interfície principal (3 columnes). |
| `InsightMaker.xml` | Projecte Snap! (export). |
| `viz.html` | Visualització 2D del model. |

---

## Visualització 2D (`viz.html`)

La visualització mostra l'oceà amb peixos i barques que representen les variables del model:

- **N (biomassa)** → nombre i mida dels peixos (més biomassa = més peixos, més grans)
- **E (esforç de captura)** → nombre i mida de les barques (més esforç = més barques, més grans)
- **K (capacitat de càrrega)** → es mostra a la barra superior i al gràfic

El **slider de temps** sobre el gràfic permet recórrer la simulació pas a pas. El marcador vertical indica l'instant seleccionat, amb punts sobre les corbes N i E.

---

## Lliurament

Zip amb `InsightMaker.xml`, `iface.html`, `viz.html` i un PDF breu amb captures i comentaris.

---

## Enllaços

- Repositori: [github.com/angelabuxo/SIM-Lab05](https://github.com/angelabuxo/SIM-Lab05)
- Model Insight Maker: [12E-Lab03-Base](https://insightmaker.com/insight/4uanRT82clj5QHRmZOUhRi/12E-Lab03-Base)
