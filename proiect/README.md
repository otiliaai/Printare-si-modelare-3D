# 🐣 Hatching Chick Automaton — Jucărie Mecanică cu Pui care Eclozează
O jucărie mecanică fără electronice care simulează ecloziunea unui pui din ou, acționată printr-un mecanism manual cu manetă rotativă. Răsucind maneta, oul se **ridică** și se **rotește alternativ stânga-dreapta**, creând iluzia că puiul iese viu din coajă.

---

## 🎯 Descrierea proiectului

Scopul proiectului este de a proiecta, modela și printa 3D o jucărie mecanică cinematică, fără niciun element electronic. Toată mișcarea este generată exclusiv prin rotirea unei manete și transmisă printr-un lanț cinematic format dintr-un **angrenaj cu roți dințate (gear train)** și un **mecanism cu camă pe axul central**.

Proiectul îmbină design decorativ cu inginerie mecanică, demonstrând conversia mișcării de rotație în mișcare compusă (translație verticală + oscilație unghiulară).

---

## ⚙️ Principiul de funcționare

### Lanțul cinematic

```
Utilizatorul rotește maneta
        ↓
Maneta antrenează roata dințată mică (albastră)
        ↓
Roata mică se angrenează cu roata mare (verde)
→ reducție de viteză: 1 rotație manetă = ~½ rotație ax central
        ↓
Axul central se rotește
        ↓
Cama de pe ax convertește rotația în mișcare verticală
→ oul urcă și coboară ritmic (~20 mm cursă)
        ↓
Simultan, profilul camei generează oscilație stânga-dreapta
        ↓
Jumătatea inferioară a oului urcă și se rotește cu axul
Jumătatea superioară (coajă spartă) rămâne fixă
        ↓
Puiul "iese" și "intră" ritmic, rotindu-se în același timp
```

### Cele două mișcări simultane

| Mișcare | Mecanism | Amplitudine |
|---|---|---|
| Verticală (sus-jos) | Camă pe ax central | ~20 mm cursă |
| Rotație stânga-dreapta | Profil excentric al camei | ~±15° față de centru |

---

## 🧩 Componente

### Piese printate 3D

| Piesă | Cantitate | Descriere |
|---|---|---|
| Ramă fixă (baza) | 1 | Corpul principal care adăpostește mecanismul |
| Roată dințată mare | 1 | Angrenată cu roata mică, solidară cu axul central |
| Roată dințată mică | 1 | Antrenată de manetă |
| Ax central + camă | 1 | Transmite rotația și generează mișcarea sus-jos |
| Manetă (crank) | 1 | Acționată manual, albastră |
| Jumătatea inferioară a oului | 1 | Fixată pe ax, se mișcă cu el |
| Jumătatea superioară (coajă spartă) | 1 | Fixă, rămâne pe loc |
| Figurina pui | 1 | Fixată în interiorul oului inferior |

### Culori recomandate

- **Verde** — rama fixă și roata dințată mare
- **Albastru** — maneta și roata dințată mică
- **Alb** — oul (ambele jumătăți) și axul central
- **Galben** — figurina pui

---

## 🎨 Inspirație

Proiectul este inspirat din:
- [Cute Hatching Chick Automaton — Printables](https://www.printables.com/model/1253400-cute-hatching-chick-automaton-crank-operated-mecha)

---

## 📁 Structura repository-ului

```
proiect/
├── README.md               ← acest fișier
├── stl/
│   ├── rama_fixa.stl
│   ├── roata_mare.stl
│   ├── roata_mica.stl
│   ├── ax_cama.stl
│   ├── maneta.stl
│   ├── ou_inferior.stl
│   ├── ou_superior.stl
│   └── pui.stl
├── fusion360/
│   └── hatching_chick.f3d  ← fișierul de modelare original
└── media/
    ├── demo.gif
    └── poze_asamblare/
```

---

## 🔧 Software folosit

- **Modelare 3D:** Autodesk Fusion 360
- **Slicing:** Ultimaker Cura / PrusaSlicer
- **Versionare:** Git + GitHub
