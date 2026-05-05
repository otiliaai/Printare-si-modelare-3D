# 🐣 Cute Hatching Chick Automaton

> O jucarie care simulează ecloziunea unui pui din ou, acționat printr-un mecanism mecanic manual cu manetă rotativă.

---

## 💡 Ideea


Scopul este de a crea o **jucărie mecanică fără electronice**, unde mișcarea este produsă exclusiv prin rotirea unei manete și transmisă printr-un lanț cinematic.

Răsucind maneta continuu, puiul "iese" și "intră" ritmic în ou — creând o animație mecanică infinită.

---

## ⚙️ Funcționare

Mecanismul convertește **rotația continuă** a manetei în **mișcare verticală** (sus-jos) a oului:

```
Utilizatorul rotește maneta albastră (crank)
        ↓
Pin-ul excentric de pe maneță descrie un cerc
        ↓
Biela (connecting rod) transformă rotația în translație
        ↓
Platforma superioară urcă și coboară ritmic
        ↓
Jumătatea inferioară a oului urcă cu platforma
        ↓
Jumătatea superioară (coaja spartă) rămâne fixă
        ↓
Puiul "iese" și "intră" în ou în mod repetat
```


## 🧩 Componente

| **Manetă (crank) albastră** | Input — rotație continuă 360° | Revolute |
| **Pin excentric** | Translatează rotația în mișcare orbitală | Rigid pe maneță |
| **Bielă (connecting rod)** | Leagă pin-ul de platformă | Cylindrical la ambele capete |
| **Platformă superioară** | Susține oul, urcă/coboară | Slider vertical |

### Oul


### Puiul
| Componentă | Rol |
|---|---|
| **Corp galben** | Fix în interiorul jumătății inferioare |
| **Cioc portocaliu** | Detaliu decorativ, insert separat |
| **Ochi negri** | Inserții presate sau lipite |

---

## ✨ Inspirație

https://www.printables.com/model/1253400-cute-hatching-chick-automaton-crank-operated-mecha



