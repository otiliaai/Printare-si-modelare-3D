# 🐣 Hatching Chick Automaton — Jucarie mecanica imprimata 3D

## 1. Descriere generala

**Hatching Chick Automaton** este o jucarie mecanica actionata manual, care simuleaza iesirea unui pui dintr-un ou. Proiectul nu foloseste motoare, senzori sau componente electronice, ci doar piese imprimate 3D si un mecanism mecanic pus in miscare prin rotirea unei manivele.

Prin rotirea manivelei, miscarea circulara este transmisa catre mecanismul intern, care transforma rotatia intr-o miscare verticala alternativa. Astfel, puiul se ridica si coboara in interiorul oului, creand efectul vizual de eclozare.

Proiectul combina modelarea 3D decorativa cu principii de mecanica aplicata, precum transmisia miscarii, angrenajele, mecanismele cu cama si ghidarea miscarii liniare.

---

## 2. Scopul proiectului

Scopul proiectului este proiectarea, asamblarea si reproducerea unei jucarii mecanice cinematice, realizata prin imprimare 3D.

Obiectivele principale sunt:

* intelegerea functionarii unui mecanism actionat manual;
* reproducerea pieselor principale in Fusion 360;
* realizarea unui ansamblu 3D functional;
* simularea miscarii mecanismului;
* pregatirea pieselor pentru imprimare 3D;
* documentarea procesului de proiectare si asamblare.

---

## 3. Principiul de functionare

Mecanismul transforma miscarea de rotatie a manivelei intr-o miscare liniara alternativa, folosita pentru ridicarea si coborarea puiului.

Fluxul miscarii este urmatorul:

```text
Utilizatorul roteste manivela
        ↓
Manivela transmite miscarea catre axul mecanismului
        ↓
Axul roteste piesele mecanice interne
        ↓
Cama transforma rotatia in miscare verticala
        ↓
Follower-ul este impins in sus si revine in jos
        ↓
Puiul se ridica si coboara in interiorul oului
        ↓
Se creeaza iluzia ca puiul iese din coaja
```

Miscarea principala a proiectului este o miscare alternativa sus-jos. In functie de modul de asamblare, se poate adauga si o usoara rotatie sau balansare a puiului pentru un efect vizual mai natural.

---

## 4. Elemente mecanice folosite

Proiectul foloseste urmatoarele concepte mecanice:

| Element mecanic | Rol in proiect                                         |
| --------------- | ------------------------------------------------------ |
| Manivela        | Permite actionarea manuala a mecanismului              |
| Ax rotativ      | Transmite miscarea de rotatie catre mecanismul intern  |
| Cama            | Transforma miscarea de rotatie in miscare verticala    |
| Follower        | Urmareste profilul camei si se deplaseaza sus-jos      |
| Ghidaj liniar   | Mentine miscarea follower-ului pe directie verticala   |
| Cadru fix       | Sustine toate piesele mecanismului                     |
| Oul si puiul    | Elemente decorative care evidentiaza miscarea mecanica |

---

## 5. Componentele proiectului

### 5.1. Piese principale

| Piesa                        | Cantitate | Rol                                      |
| ---------------------------- | --------: | ---------------------------------------- |
| Baza / rama fixa             |         1 | Sustine intregul mecanism                |
| Pereti laterali              |         2 | Tin axul si ghidajele mecanismului       |
| Manivela                     |         1 | Este rotita manual de utilizator         |
| Ax principal                 |         1 | Transmite miscarea de rotatie            |
| Cama                         |         1 | Genereaza miscarea alternativa           |
| Follower                     |         1 | Se deplaseaza vertical pe profilul camei |
| Suport mobil                 |         1 | Ridica puiul                             |
| Jumătatea inferioara a oului |         1 | Partea in care sta puiul                 |
| Jumătatea superioara a oului |         1 | Sugereaza coaja sparta                   |
| Figurina pui                 |         1 | Elementul vizual principal al jucariei   |

### 5.2. Culori recomandate

| Culoare                              | Piese                                    |
| ------------------------------------ | ---------------------------------------- |
| Verde                                | Rama, suporturile si piesele structurale |
| Alb                                  | Coaja oului                              |
| Galben                               | Corpul puiului                           |
| Portocaliu                           | Ciocul puiului                           |
| Negru                                | Ochii puiului                            |
| Albastru / alta culoare contrastanta | Manivela sau piese de actionare          |

---

## 6. Structura repository-ului

```text
Hatching-Chick-Automaton/
│
├── README.md
│
├── fusion360/
│   └── hatching_chick_automaton.f3d
│
├── stl/
│   ├── frame_base.stl
│   ├── frame_left.stl
│   ├── frame_right.stl
│   ├── crank.stl
│   ├── shaft.stl
│   ├── cam.stl
│   ├── follower.stl
│   ├── egg_bottom.stl
│   ├── egg_top.stl
│   └── chick.stl
│
├── step/
│   ├── frame_base.step
│   ├── frame_left.step
│   ├── frame_right.step
│   ├── crank.step
│   ├── shaft.step
│   ├── cam.step
│   ├── follower.step
│   ├── egg_bottom.step
│   ├── egg_top.step
│   └── chick.step
│
├── media/
│   ├── images/
│   │   ├── model_view.png
│   │   ├── mechanism_view.png
│   │   └── exploded_view.png
│   │
│   └── demo/
│       └── animation.gif
│
└── documentation/
    ├── assembly_steps.md
    └── printing_settings.md
```

---

## 7. Software folosit

Pentru realizarea proiectului au fost folosite urmatoarele aplicatii:

* **Autodesk Fusion 360** — modelare 3D, asamblare si simulare mecanica;
* **PrusaSlicer** — pregatirea pieselor pentru imprimare 3D;
* **Printables** — sursa de inspiratie pentru modelul mecanic;
* **GitHub** — organizarea si documentarea proiectului.

---

## 8. Pasi de realizare

Procesul de lucru este impartit in mai multe etape:

1. Analiza modelului de referinta si identificarea pieselor principale.
2. Importarea sau reconstruirea pieselor in Fusion 360.
3. Organizarea pieselor in componente separate.
4. Realizarea cadrului fix al mecanismului.
5. Modelarea manivelei, axului, camei si follower-ului.
6. Adaugarea oului si a figurinei puiului.
7. Definirea joint-urilor in Fusion 360.
8. Testarea miscarii prin simulare.
9. Exportarea pieselor in format STL.
10. Pregatirea pieselor pentru imprimare 3D.
11. Asamblarea fizica a mecanismului.
12. Documentarea rezultatului final.

---

## 9. Joint-uri folosite in Fusion 360

| Componente                 | Tip joint      | Rol                                  |
| -------------------------- | -------------- | ------------------------------------ |
| Rama fata de origine       | Ground         | Fixeaza ansamblul                    |
| Piesele ramei intre ele    | Rigid Joint    | Rama devine un corp fix              |
| Manivela fata de rama      | Revolute Joint | Permite rotirea manivelei            |
| Ax fata de manivela        | Rigid Joint    | Axul se roteste impreuna cu manivela |
| Cama fata de ax            | Rigid Joint    | Cama se roteste impreuna cu axul     |
| Follower fata de ghidaj    | Slider Joint   | Permite miscarea verticala           |
| Pui fata de suportul mobil | Rigid Joint    | Puiul urca si coboara cu suportul    |
| Oul fata de suport / rama  | Rigid Joint    | Pozitioneaza elementele decorative   |

---

## 10. Setari recomandate pentru imprimare 3D

Setarile pot varia in functie de imprimanta si material, dar pentru un prototip functional se pot folosi urmatoarele valori:

| Parametru                    | Valoare recomandata                               |
| ---------------------------- | ------------------------------------------------- |
| Material                     | PLA                                               |
| Inaltime strat               | 0.20 mm                                           |
| Infill                       | 15–20%                                            |
| Perimetre                    | 2–3                                               |
| Suporturi                    | Doar unde este necesar                            |
| Toleranta intre piese mobile | 0.2–0.4 mm                                        |
| Orientare                    | Piesele se orienteaza pentru a reduce suporturile |

Pentru piesele aflate in miscare este important sa existe tolerante suficiente, astfel incat mecanismul sa nu se blocheze dupa imprimare.

---

## 11. Probleme posibile si solutii

| Problema                          | Cauza posibila                    | Solutie                                                      |
| --------------------------------- | --------------------------------- | ------------------------------------------------------------ |
| Manivela se roteste greu          | Frecare prea mare intre piese     | Marirea tolerantelor sau slefuirea axului                    |
| Follower-ul se blocheaza          | Ghidaj prea stramt                | Latirea canalului de ghidare                                 |
| Puiul nu se ridica suficient      | Cama are excentricitate prea mica | Marirea diferentei dintre raza minima si raza maxima a camei |
| Ansamblul se misca in Fusion 360  | Rama nu este fixata               | Aplicarea comenzii Ground pe baza                            |
| Miscarea nu este transmisa corect | Joint-uri gresite                 | Verificarea joint-urilor Revolute, Slider si Rigid           |

---

## 12. Inspiratie si sursa modelului

Proiectul este inspirat din modelul:

**Cute Hatching Chick Automaton — Crank Operated Mechanical Toy Model**
Disponibil pe Printables:
https://www.printables.com/model/1253400-cute-hatching-chick-automaton-crank-operated-mecha

Modelul a fost folosit ca referinta pentru intelegerea principiului mecanic si pentru reproducerea unui automat mecanic in scop educational.

---

## 13. Concluzie

Hatching Chick Automaton demonstreaza modul in care miscarea de rotatie poate fi transformata intr-o miscare alternativa printr-un mecanism simplu, dar expresiv. Proiectul este potrivit pentru intelegerea principiilor de baza ale mecanismelor, pentru exersarea modelarii 3D in Fusion 360 si pentru realizarea unui obiect functional prin imprimare 3D.

Rezultatul final este o jucarie mecanica decorativa, actionata manual, care imbina partea tehnica a mecanismelor cu un design vizual atractiv.
# 🐣 Hatching Chick Automaton — Jucarie mecanica imprimata 3D

## 1. Descriere generala

**Hatching Chick Automaton** este o jucarie mecanica actionata manual, care simuleaza iesirea unui pui dintr-un ou. Proiectul nu foloseste motoare, senzori sau componente electronice, ci doar piese imprimate 3D si un mecanism mecanic pus in miscare prin rotirea unei manivele.

Prin rotirea manivelei, miscarea circulara este transmisa catre mecanismul intern, care transforma rotatia intr-o miscare verticala alternativa. Astfel, puiul se ridica si coboara in interiorul oului, creand efectul vizual de eclozare.

Proiectul combina modelarea 3D decorativa cu principii de mecanica aplicata, precum transmisia miscarii, angrenajele, mecanismele cu cama si ghidarea miscarii liniare.

---

## 2. Scopul proiectului

Scopul proiectului este proiectarea, asamblarea si reproducerea unei jucarii mecanice cinematice, realizata prin imprimare 3D.

Obiectivele principale sunt:

* intelegerea functionarii unui mecanism actionat manual;
* reproducerea pieselor principale in Fusion 360;
* realizarea unui ansamblu 3D functional;
* simularea miscarii mecanismului;
* pregatirea pieselor pentru imprimare 3D;
* documentarea procesului de proiectare si asamblare.

---

## 3. Principiul de functionare

Mecanismul transforma miscarea de rotatie a manivelei intr-o miscare liniara alternativa, folosita pentru ridicarea si coborarea puiului.

Fluxul miscarii este urmatorul:

```text
Utilizatorul roteste manivela
        ↓
Manivela transmite miscarea catre axul mecanismului
        ↓
Axul roteste piesele mecanice interne
        ↓
Cama transforma rotatia in miscare verticala
        ↓
Follower-ul este impins in sus si revine in jos
        ↓
Puiul se ridica si coboara in interiorul oului
        ↓
Se creeaza iluzia ca puiul iese din coaja
```

Miscarea principala a proiectului este o miscare alternativa sus-jos. In functie de modul de asamblare, se poate adauga si o usoara rotatie sau balansare a puiului pentru un efect vizual mai natural.

---

## 4. Elemente mecanice folosite

Proiectul foloseste urmatoarele concepte mecanice:

| Element mecanic | Rol in proiect                                         |
| --------------- | ------------------------------------------------------ |
| Manivela        | Permite actionarea manuala a mecanismului              |
| Ax rotativ      | Transmite miscarea de rotatie catre mecanismul intern  |
| Cama            | Transforma miscarea de rotatie in miscare verticala    |
| Follower        | Urmareste profilul camei si se deplaseaza sus-jos      |
| Ghidaj liniar   | Mentine miscarea follower-ului pe directie verticala   |
| Cadru fix       | Sustine toate piesele mecanismului                     |
| Oul si puiul    | Elemente decorative care evidentiaza miscarea mecanica |

---

## 5. Componentele proiectului

### 5.1. Piese principale

| Piesa                        | Cantitate | Rol                                      |
| ---------------------------- | --------: | ---------------------------------------- |
| Baza / rama fixa             |         1 | Sustine intregul mecanism                |
| Pereti laterali              |         2 | Tin axul si ghidajele mecanismului       |
| Manivela                     |         1 | Este rotita manual de utilizator         |
| Ax principal                 |         1 | Transmite miscarea de rotatie            |
| Cama                         |         1 | Genereaza miscarea alternativa           |
| Follower                     |         1 | Se deplaseaza vertical pe profilul camei |
| Suport mobil                 |         1 | Ridica puiul                             |
| Jumătatea inferioara a oului |         1 | Partea in care sta puiul                 |
| Jumătatea superioara a oului |         1 | Sugereaza coaja sparta                   |
| Figurina pui                 |         1 | Elementul vizual principal al jucariei   |

### 5.2. Culori recomandate

| Culoare                              | Piese                                    |
| ------------------------------------ | ---------------------------------------- |
| Verde                                | Rama, suporturile si piesele structurale |
| Alb                                  | Coaja oului                              |
| Galben                               | Corpul puiului                           |
| Portocaliu                           | Ciocul puiului                           |
| Negru                                | Ochii puiului                            |
| Albastru / alta culoare contrastanta | Manivela sau piese de actionare          |

---

## 6. Structura repository-ului

```text
Hatching-Chick-Automaton/
│
├── README.md
│
├── fusion360/
│   └── hatching_chick_automaton.f3d
│
├── stl/
│   ├── frame_base.stl
│   ├── frame_left.stl
│   ├── frame_right.stl
│   ├── crank.stl
│   ├── shaft.stl
│   ├── cam.stl
│   ├── follower.stl
│   ├── egg_bottom.stl
│   ├── egg_top.stl
│   └── chick.stl
│
├── step/
│   ├── frame_base.step
│   ├── frame_left.step
│   ├── frame_right.step
│   ├── crank.step
│   ├── shaft.step
│   ├── cam.step
│   ├── follower.step
│   ├── egg_bottom.step
│   ├── egg_top.step
│   └── chick.step
│
├── media/
│   ├── images/
│   │   ├── model_view.png
│   │   ├── mechanism_view.png
│   │   └── exploded_view.png
│   │
│   └── demo/
│       └── animation.gif
│
└── documentation/
    ├── assembly_steps.md
    └── printing_settings.md
```

---

## 7. Software folosit

Pentru realizarea proiectului au fost folosite urmatoarele aplicatii:

* **Autodesk Fusion 360** — modelare 3D, asamblare si simulare mecanica;
* **PrusaSlicer** — pregatirea pieselor pentru imprimare 3D;
* **Printables** — sursa de inspiratie pentru modelul mecanic;
* **GitHub** — organizarea si documentarea proiectului.

---

## 8. Pasi de realizare

Procesul de lucru este impartit in mai multe etape:

1. Analiza modelului de referinta si identificarea pieselor principale.
2. Importarea sau reconstruirea pieselor in Fusion 360.
3. Organizarea pieselor in componente separate.
4. Realizarea cadrului fix al mecanismului.
5. Modelarea manivelei, axului, camei si follower-ului.
6. Adaugarea oului si a figurinei puiului.
7. Definirea joint-urilor in Fusion 360.
8. Testarea miscarii prin simulare.
9. Exportarea pieselor in format STL.
10. Pregatirea pieselor pentru imprimare 3D.
11. Asamblarea fizica a mecanismului.
12. Documentarea rezultatului final.

---

## 9. Joint-uri folosite in Fusion 360

| Componente                 | Tip joint      | Rol                                  |
| -------------------------- | -------------- | ------------------------------------ |
| Rama fata de origine       | Ground         | Fixeaza ansamblul                    |
| Piesele ramei intre ele    | Rigid Joint    | Rama devine un corp fix              |
| Manivela fata de rama      | Revolute Joint | Permite rotirea manivelei            |
| Ax fata de manivela        | Rigid Joint    | Axul se roteste impreuna cu manivela |
| Cama fata de ax            | Rigid Joint    | Cama se roteste impreuna cu axul     |
| Follower fata de ghidaj    | Slider Joint   | Permite miscarea verticala           |
| Pui fata de suportul mobil | Rigid Joint    | Puiul urca si coboara cu suportul    |
| Oul fata de suport / rama  | Rigid Joint    | Pozitioneaza elementele decorative   |

---

## 10. Setari recomandate pentru imprimare 3D

Setarile pot varia in functie de imprimanta si material, dar pentru un prototip functional se pot folosi urmatoarele valori:

| Parametru                    | Valoare recomandata                               |
| ---------------------------- | ------------------------------------------------- |
| Material                     | PLA                                               |
| Inaltime strat               | 0.20 mm                                           |
| Infill                       | 15–20%                                            |
| Perimetre                    | 2–3                                               |
| Suporturi                    | Doar unde este necesar                            |
| Toleranta intre piese mobile | 0.2–0.4 mm                                        |
| Orientare                    | Piesele se orienteaza pentru a reduce suporturile |

Pentru piesele aflate in miscare este important sa existe tolerante suficiente, astfel incat mecanismul sa nu se blocheze dupa imprimare.

---

## 11. Probleme posibile si solutii

| Problema                          | Cauza posibila                    | Solutie                                                      |
| --------------------------------- | --------------------------------- | ------------------------------------------------------------ |
| Manivela se roteste greu          | Frecare prea mare intre piese     | Marirea tolerantelor sau slefuirea axului                    |
| Follower-ul se blocheaza          | Ghidaj prea stramt                | Latirea canalului de ghidare                                 |
| Puiul nu se ridica suficient      | Cama are excentricitate prea mica | Marirea diferentei dintre raza minima si raza maxima a camei |
| Ansamblul se misca in Fusion 360  | Rama nu este fixata               | Aplicarea comenzii Ground pe baza                            |
| Miscarea nu este transmisa corect | Joint-uri gresite                 | Verificarea joint-urilor Revolute, Slider si Rigid           |

---

## 12. Inspiratie si sursa modelului

Proiectul este inspirat din modelul:

**Cute Hatching Chick Automaton — Crank Operated Mechanical Toy Model**
Disponibil pe Printables:
https://www.printables.com/model/1253400-cute-hatching-chick-automaton-crank-operated-mecha

Modelul a fost folosit ca referinta pentru intelegerea principiului mecanic si pentru reproducerea unui automat mecanic in scop educational.

---

## 13. Concluzie

Hatching Chick Automaton demonstreaza modul in care miscarea de rotatie poate fi transformata intr-o miscare alternativa printr-un mecanism simplu, dar expresiv. Proiectul este potrivit pentru intelegerea principiilor de baza ale mecanismelor, pentru exersarea modelarii 3D in Fusion 360 si pentru realizarea unui obiect functional prin imprimare 3D.

Rezultatul final este o jucarie mecanica decorativa, actionata manual, care imbina partea tehnica a mecanismelor cu un design vizual atractiv.
