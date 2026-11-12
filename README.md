# 🌻 Fibonacci a la Natura — App Interactiva PCMAT

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/Llicència-MIT-blue.style=for-the-badge)

Una aplicació web interactiva i gamificada dissenyada per explorar la **Proposta 6: Fibonacci a la Natura** del programa **PCMAT** (*Programa de Competència Matemàtica*). Aquesta eina permet a l'alumnat i docents investigar les connexions entre la successió de Fibonacci, la geometria, l'angle d'or a la natura, la fil·lotaxi i la programació robòtica.

---

## 🚀 Característiques Principals

- 🧠 **Qüestionari Gamificat de 10 Preguntes**: Cobreix des de piràmides numèriques, la regla de la successió, escales i esglaons, sumes acumulades i divisibilitat, fins a l'espiral geomètrica, l'angle d'or i el rusc hexagonal de les abelles.
- 🎨 **Visualització Dinàmica (SVG/Canvas)**: Gràfics interactius integrats en cada pregunta per facilitar la comprensió intuïtiva dels conceptes matemàtics.
- 🌻 **Laboratori Virtual de Fil·lotaxi (Simulador del Gira-sol)**: Un simulador en temps real (*HTML5 Canvas*) on els usuaris poden modificar l'angle de gir entre llavors i comprovar visualment per què l'**Angle d'Or ($137{,}5^\circ$)** optimitza l'espai sense superposicions.
- 🏆 **Sistema de Puntuació i Rangs**: feedback pedagògic immediat, càlcul de percentatges d'encert, assignació de rangs matemàtics (*Mestre/a de l'Espiral Daurada*, etc.) i revisió detallada de totes les respostes.
- 📱 **Disseny Responsive i Immersiu**: Creat amb Tailwind CSS i un estil visual modern (*glassmorphism*) adaptat a pantalles de tauletes, ordinadors i mòbils.

---

## 📂 Estructura del Projecte

El projecte està estructurat com una aplicació d'un sol fitxer (*Single-File Web App*), la qual cosa en facilita l'execució i el desplegament immediat sense necessitat de servidors ni eines de compilació complexes:

```text
.
├── index.html       # Codi font principal (HTML + Tailwind via CDN + JS)
└── README.md        # Documentació del repositori
```

---

## 💻 Com Executar el Projecte

### Opció 1: Execució Local Directa
1. Clona aquest repositori o descarrega els fitxers:
   ```bash
   git clone https://github.com/el-teu-usuari/fibonacci-natura-pcmat.git
   ```
2. Obre el fitxer `index.html` directament en qualsevol navegador web modern (Chrome, Firefox, Edge, Safari). No cal cap instal·lació prèvia de `node.js` o `npm`.

### Opció 2: Desplegament a GitHub Pages
Aquest projecte és 100% compatible amb **GitHub Pages**:
1. Ves a la pestanya **Settings** del teu repositori a GitHub.
2. Navega fins a la secció **Pages** (al menú lateral).
3. A **Source**, selecciona la branca `main` i la carpeta `/ (root)`.
4. Fes clic a **Save**. En un minut tindràs l'aplicació publicada en línia!

---

## 📚 Blocs Pedagògics de la Proposta (PCMAT)

Aquesta aplicació aborda els 5 blocs fonamentals de la proposta didàctica:

| Bloc | Títol | Descripció Matemàtica |
| :--- | :--- | :--- |
| **1** | **Piràmides Numèriques** | Relació de suma entre caselles inferiors i optimització del cim segons la posició dels nombres. |
| **2** | **Successió i Esglaons** | Pas de la piràmide a la línia ($1, 1, 2, 3, 5, 8\dots$) i combinatòria de camins en una escala. |
| **3** | **Sumes i Divisibilitat** | Propietats algebraiques ($1+1+\dots+F_n = F_{n+2}-1$) i periodicitat dels divisibles per 2, 3 i 5. |
| **4** | **Espiral Geomètrica i Angle d'Or** | Construcció geomètrica d'arcs de $90^\circ$ sobre quadrats de Fibonacci i l'angle de $137{,}5^\circ$ en plantes. |
| **5** | **El Rusc i la Robòtica** | Comptatge de recorreguts en cel·les hexagonals i el cicle de pensament computacional (*Programa → Prova → Observa → Ajusta → Torna-hi*). |

---

## 🛠️ Tecnologies Utilitzades

- **HTML5 & Vanilla JavaScript (ES6+)**: Per a la lògica de l'aplicació, el gestor d'estat del qüestionari i la manipulació del Canvas.
- **Tailwind CSS (via CDN)**: Per als estils visuals, disseny adaptatiu i efectes de vidre (*backdrop-filter*).
- **Google Fonts**: Tipografies *Outfit* (títols i accents) i *Inter* (text de lectura).

---

## 📄 Llicència

Aquest projecte està distribuït sota la llicència **MIT**. Consulta el fitxer `LICENSE` per a més informació.

---

✨ *Desenvolupat per al suport digital del Programa de Competència Matemàtica (PCMAT).*