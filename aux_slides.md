---
marp: true
theme: default
paginate: true
backgroundColor: #ffffff
#transition: fade   
#footer: "Astronomía Galáctica y Extragaláctica - 2026-II"
allowLocalFiles: true

title: Introducción a la Astronomía Galáctica y Extragaláctica
description: Intro a la Astronomía Galáctica y Extragaláctica
author: Prof. J.E. García-Farieta <joegarciafa@unal.edu.co>
keywords: Astronomía
url: https://google.com

style: |
  :root {
    --color-spartan-green: #18453B;
    --color-msu-gold: #C1B000;
    --color-light-gray: #f5f5f5;
    --color-dark-text: #1a1a1a;
    --color-accent-green: #2d5f4f;
  }
  
  @font-face {
    font-family: 'Noto Sans';
    src: url('../fonts/Inter-VariableFont_opsz,wght.ttf') format('truetype');
    font-weight: 100 900;
    font-style: normal;
  }

  @font-face {
    font-family: 'Noto Sans';
    src: url('../fonts/Inter-Italic-VariableFont_opsz,wght.ttf') format('truetype');
    font-weight: 100 900;
    font-style: italic;
  }

  body {
    /*font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;*/
    font-family: 'Liberation Sans', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    /*font-family: 'Noto Sans', sans-serif;*/
    background-color: #ffffff;
    color: var(--color-dark-text);
  }  

  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    text-align: left;
  }

  section.center {
    justify-content: center !important;
    align-items: center !important;
    text-align: center !important;
  }

  section.center h1 {
    font-size: 3.5rem !important;
  }

  h1, h2, h3 {
    color: var(--color-spartan-green);
    font-weight: 500;
  }
  
  h1 {
    font-size: 2.2rem;
    margin-bottom: 0rem;
  }
  
  h2 {
    font-size: 1.55rem;
    margin-bottom: 1.0rem;
    border-bottom: 4px solid var(--color-spartan-green);
    padding-bottom: 0.5rem;
  }
  
  h3 {
    font-size: 1.15rem;
    margin-top: 1rem;
    margin-bottom: 0.75rem;
  }

  /*
  section {
    padding: 2rem;
    background-color: #ffffff;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
  }
  */

  section {
    /*font-family: sans-serif;*/
    font-family: 'Liberation Sans', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    padding: 2rem;
    background-color: #ffffff;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
  }

  section.title {
    background-color: #ffffff !important;
    color: var(--color-spartan-green) !important;
    border-top: 12px solid var(--color-spartan-green) !important;
    border-bottom: 4px solid var(--color-msu-gold) !important;
    padding: 3rem !important;
  }

  section.title h1, section.title h2 {
    color: var(--color-spartan-green) !important;
    font-size: 1.8rem !important;
    margin-bottom: 0.8rem !important;
    font-weight: 700 !important;
  }

  section.title p {
    color: var(--color-dark-text) !important;
    font-size: 1.0rem !important;
  }

  section.title .equation {
    background-color: var(--color-light-gray) !important;
    color: var(--color-dark-text) !important;
    border-left: 6px solid var(--color-msu-gold) !important;
    padding: 1.5rem !important;
    margin: 1.5rem 0 !important;
  }

  section.title .footnote {
    color: #666666 !important;
    font-size: 1rem !important;
    margin-top: 2rem !important;
  }

  section.title strong {
    color: var(--color-spartan-green) !important;
    font-weight: 700 !important;
  }

  .equation {
    background-color: var(--color-light-gray);
    padding: 1.5rem;
    border-left: 4px solid var(--color-msu-gold);
    margin: 1.5rem 0;
    font-size: 1.3rem;
    text-align: center;
    color: var(--color-dark-text);
  }

  p {
    font-size: 1.15rem;
    line-height: 1.4;
    margin-bottom: 0.5rem;
  }
  
  ul, ol {
    font-size: 1.15rem;
    line-height: 1.4;
    margin-left: 0.5rem;
  }

  ul ul, ol ol, ul ol, ol ul {
    margin-left: 0.1rem;
  }
  
  li {
    margin-bottom: 0rem;
    line-height: 1.4;
  }
  
  strong {
    color: var(--color-spartan-green);
    font-weight: 600;
  }
  
  em {
    color: var(--color-accent-green);
  }

  .highlight {
    background-color: var(--color-light-gray);
    padding: 1.5rem;
    border-left: 4px solid var(--color-spartan-green);
    margin: 1.5rem 0;
  }
  
  .physics-concept {
    background-color: #f0f8f7;
    border: 2px solid var(--color-spartan-green);
    padding: 1.25rem;
    border-radius: 6px;
    margin: 1rem 0;
  }

  .activity {
    background-color: #fff8e1;
    border: 2px solid var(--color-msu-gold);
    padding: 1.25rem;
    border-radius: 6px;
    margin: 1rem 0;
  }

  blockquote {
    background-color: #f9f9f9;
    border-left: 4px solid var(--color-accent-green);
    padding: 1rem 1.5rem;
    margin: 1rem 0;
    font-style: italic;
  }

  table {
    margin-left: auto;
    margin-right: auto;
    border-collapse: collapse;
    font-size: 1.0rem;
  }

  table th, table td {
    padding: 0.25rem;
    text-align: left;
    border: 3px solid #ddd;
  }

  table th {
    background-color: var(--color-light-gray);
    color: var(--color-spartan-green);
    font-weight: 600;
  }
  
  footer {
    font-size: 0.8rem;
    color: #999;
  }

  .footnote {
    font-size: 0.8rem;
    color: #999;
    margin-top: 1.5rem;
    border-top: 1px solid #ddd;
    padding-top: 0.75rem;
  }

  section.compact {
    padding: 1.2rem 2rem;
  }

  section.compact h1 {
    font-size: 1.9rem;
    margin: 0 0 0.3rem;
  }

  section.compact blockquote {
    font-size: 0.95rem;
    line-height: 1.2;
    padding: 0.55rem 0.9rem;
    margin: 0.45rem 0 0.65rem;
  }

  section.compact table {
    width: fit-content;
    max-width: 100%;
    margin: 0.2rem auto 0;
    font-size: 0.85rem;
    line-height: 1.15;
  }

  section.compact table th,
  section.compact table td {
    padding: 0.22rem 0.4rem;
  }  

  section img[alt~="center"] {
    display: block;
    margin: 0 auto;
  }

  section.medium-text {
    font-size: 0.85rem !important;
  }
  section.medium-text h1 { font-size: 2.8rem !important; }
  section.medium-text h2 { font-size: 1.4rem !important; }
  section.medium-text h3 { font-size: 1.2rem !important; }
  section.medium-text p, 
  section.medium-text li, 
  section.medium-text td { font-size: 1.7rem !important; }

  section.small-text {
    font-size: 0.7rem !important;
  }
  section.small-text h1 { font-size: 2.2rem !important; }
  section.small-text h2 { font-size: 1.2rem !important; }
  section.small-text h3 { font-size: 1.0rem !important; }
  section.small-text p, 
  section.small-text li, 
  section.small-text td { font-size: 1.3rem !important; }

  section.title-clean {
    background-color: #ffffff;
    color: #18453B;
    border-top: 12px solid #18453B;
    border-bottom: 4px solid #C1B000;
    padding: 3rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  section.title-clean h1 {
    color: #18453B;
    font-size: 2.2rem;
    font-weight: 700;
    margin-bottom: 0.8rem;
  }
  section.title-clean p.intro {
    color: #1a1a1a;
    font-size: 1.0rem;
    margin-bottom: 1rem;
  }
  section.title-clean em {
    font-size: 0.75rem;
    color: #555555;
    line-height: 1.2;
    display: block;
    margin-top: 1rem;
  }
  section.title-clean footer {
    color: #666666;
    font-size: 0.9rem;
    border-top: 1px solid #ddd;
    padding-top: 0.75rem;
  }

  .card-container {
      display: flex;
      flex-direction: column;
      gap: 0.2rem;
      margin-top: 0.0rem;
    }
    .card {
      background: #f8f9fa;
      padding: 0.4rem 0.4rem;
      border-radius: 4px;
    }
    .card strong {
      display: block;
      font-size: 0.7rem;
    }
    .card span {
      font-size: 0.6rem;
      color: #444;
    }
    .card-green {
      border-left: 4px solid #18453B;
    }
    .card-green strong {
      color: #18453B;
    }
    .card-gold {
      border-left: 4px solid #C1B000;
    }
    .card-gold strong {
      color: #1a1a1a;
    }
  code {
    background-color: #e2e8f0;
    color: #0f172a;
  }
  .highlight {
    background-color: #dbeafe;
    padding: 12px 20px;
    border-left: 5px solid #2563eb;
    border-radius: 4px;
  }
  .math-box {
    background-color: #ffffff;
    border: 1px solid #cbd5e1;
    border-radius: 8px;
    padding: 15px;
    margin: 10px 0;
    box-shadow: 0 1px 3px rgba(00,00.05);
  }

  .giant-paren {
    font-size: 23rem;
    line-height: 1;
    color: #ffa88d;
    user-select: none;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-60%, -60%);
  }  

---

 
# Factor de Escala $a(t)$ y Expansión Métrica

En la Métrica de Friedmann-Lemaître-Robertson-Walker (FLRW), la distancia entre dos puntos comóviles evoluciona con el tiempo mediante el factor de escala $a(t)$:

<div class="formula">

$$1 + z = \frac{a(t_{\text{observado}})}{a(t_{\text{emitido}})}$$

</div>

* Esta ecuación demuestra directamente que el redshift $z$ mide cuánto se ha expandido el espacio desde que la luz fue emitida por la galaxia distante.
 

---

# El Fondo Cósmico de Microondas (CMB)

* **Fotografía Primordial ($z \approx 1100$):** Luz emitida cuando el Universo tenía solo 380,000 años y los electrones se re-combinaron con protones.
* **Anisotropías de Temperatura:** Pequeñísimas fluctuaciones de temperatura ($\Delta T / T \sim 10^{-5}$) registradas por satélites (COBE, WMAP, Planck).
* **Semillas de la Red Cósmica:** Esas diferencias de densidad primordiales son los "gérmenes" que la gravedad convirtió en los filamentos y galaxias de hoy.

---


# La Constante Cosmológica ($\Lambda$)

* **Ecuaciones de Campo de Einstein con $\Lambda$:**
  $$R_{\mu\nu} - \frac{1}{2}R g_{\mu\nu} + \Lambda g_{\mu\nu} = \frac{8\pi G}{c^4} T_{\mu\nu}$$
* **Naturaleza de la Energía Oscura:**
  * Presión negativa e isotrópica ($p = -\rho c^2$).
  * Densidad de energía constante por unidad de volumen del espacio-tiempo.
  * Conforme el espacio se expande, la cantidad total de energía oscura aumenta proporcionalmente al volumen.

---

# Evidencias Empíricas de la Materia Oscura

1. **Curvas de Rotación Galáctica (Vera Rubin, 1970s):**
   * Las velocidades orbitales de estrellas externas se mantienen planas ($v \approx \text{constante}$), indicando un halo masivo invisible:
   $$v(r) = \sqrt{\frac{G M(r)}{r}}$$
2. **Lentes Gravitacionales:**
   * La deformación de la luz de galaxias de fondo en cúmulos revela más masa de la visible.
3. **El Cúmulo de la Bala (*Bullet Cluster*):**
   * Separación observacional entre el gas bariónico (Rayos X) y el centro de masa gravitacional (Lentes).

---

# Simulaciones $N$-Cuerpos y Formación de Estructura

* **Simulaciones Computacionales:** Millennium, Illustris, Eagle, Indra.
* **Proceso de Evolución:**
  1. Se introducen las fluctuaciones primordiales de densidad medidas en el CMB ($z \approx 1100$).
  2. La gravedad amplifica linealmente las sobre-densidades.
  3. Ocurre colapso no lineal, formando halos de materia oscura.
  4. El gas se enfria, condensa y enciende las primeras estrellas y galaxias.

---

<!-- Slide 35 -->
# Sloan Digital Sky Survey (SDSS)

* **Ubicación:** Observatorio Apache Point (Nuevo México, EE.UU.), telescopio de $2.5 \text{ m}$.
* **Impacto:** Ha cartografiado más de 3 millones de objetos celestes, creando el mapa 3D más detallado del Universo durante las últimas dos décadas.
* **Tecnología Didáctica:**
  * Plataforma **SDSS Voyages** con actividades interactivas para colegios.
  * Placas metálicas perforadas para fibra óptica utilizadas en las fases SDSS-I a IV.

---

<!-- Slide 36 -->
# Dark Energy Spectroscopic Instrument (DESI)

* **Ubicación:** Telescopio Mayall de $4 \text{ m}$ en Kitt Peak (Arizona).
* **Tecnología:** 5,000 posicionadores robóticos de fibra óptica en el plano focal.
* **Objetivo:**
  * Medir espectros de más de 40 millones de galaxias y cuásares.
  * Construir el mapa tridimensional más grande del Universo para medir la ecuación de estado de la energía oscura mediante Oscilaciones Acústicas de Bariones (BAO).

![bg right:40% w:450](img/esquema_plano_focal_desi_9.png)

---

<!-- Slide 37 -->
# Observatorio Vera C. Rubin (LSST)

* **Ubicación:** Cerro Pachón, Chile ($8.4 \text{ m}$ de apertura).
* **Cámara LSST:** La cámara digital más grande jamás construida ($3.2$ Gigapíxeles).
* **Encuesta LSST (Legacy Survey of Space and Time):**
  * Fotografiará todo el cielo del hemisferio sur cada pocas noches durante 10 años.
  * Registrará miles de millones de galaxias y descubrirá millones de supernovas Tipo Ia y transitorios en tiempo real.

---

<!-- Slide 39 -->
# Oscilaciones Acústicas de Bariones (BAO)

* **Regla Estándar Cósmica:**
  * En el plasma primordial, las ondas de sonido se propagaron hasta la recombinación, congelando una escala característica de $\approx 150 \text{ Mpc}$ comóviles ($\approx 490$ millones de al).
* **Firma en la Red Cósmica:**
  * Existe un exceso estadístico en la probabilidad de encontrar dos galaxias separadas por esa distancia fija.
  * Permite medir la geometría del Universo a diferentes redshifts.

---

<!-- Slide 42 -->
# Errores Frecuentes 2: Confusión entre $v$ y Tasa $H_0$

* **Error:** Interpretar que porque una galaxia lejana tenga mayor velocidad $v$ que una cercana, la masa o la expansión se está acelerando en el espacio local.
* **Explicación Didáctica:**
  * La mayor velocidad $v$ a mayor distancia $d$ es resultado de la acumulación del espacio en expansión (Ley lineal $v = H_0 \cdot d$).
  * La aceleración cosmológica real ($\Omega_\Lambda$) se detecta solo como **desviaciones no lineales** en la curva a redshifts muy altos ($z \gtrsim 0.5$) mediante supernovas.

---

<!-- Slide 43 -->
# Errores Frecuentes 3: Escalas de Expansión

* **Pregunta del Estudiante:** *Si el Universo se expande, ¿por qué la Tierra o el Sistema Solar no se agrandan?*
* **Respuesta Basada en Física:**
  * En escalas locales y galácticas ($< 10 \text{ Mpc}$), las fuerzas electromagnéticas y las fuerzas gravitacionales ligadas **superan con creces** la tasa de expansión métrica.
  * La expansión domina únicamente en escalas intergalácticas no ligadas ($\gtrsim 100 \text{ Mpc}$).

---


* **Error:** Considerar el Big Bang como una bomba que estalló en un lugar vacío preconcebido.
* **Estrategia Remediadora:**
  * Explicar que el Big Bang ocurrió **en todas partes simultáneamente**.
  * No hay "fuera" del Universo ni bordes físicos.
  * La expansión es un cambio en la métrica del espacio, no movimiento a través de un medio.

---

<!-- Slide 27 -->
# Materia Oscura: La Scaffolding Invisible

* **¿Por qué la llamamos "oscura"?**
  * No emite, absorbe ni refleja radiación electromagnética (no interactúa con la luz).
  * Interactúa principalmente mediante la fuerza gravitacional.
* **Efecto Cosmológico:**
  * Actúa como el pozo de potencial gravitacional inicial que permitió que la materia bariónica colapsara para formar galaxias y la Red Cósmica.

---

<!-- Slide 29 -->
# Energía Oscura y la Aceleración Cósmica

* **Descubrimiento (1998):** Riess, Perlmutter y Schmidt analizaron Supernovas Tipo Ia lejanas como "velas estándar".
* **Resultado Inesperado:** Las supernovas lejanas se observaron **más tenues (más distantes)** de lo predicho por un universo que desacelera por gravedad.
* **Premio Nobel 2011:** El Universo no solo se expande, ¡sino que la aceleración de su expansión está aumentando desde hace $\sim 5$ mil millones de años!

![bg right:40% w:450](img/esquema_supernova_7.png)

---

<!-- Slide 18 -->
# Líneas de Absorción y Emisión

* **Líneas de Absorción (Fraunhofer):** Producidas cuando la luz continua atraviesa gas frío.
* **Líneas de Emisión:** Producidas por gas caliente ionizado (ej. regiones HII de formación estelar).
* **Líneas Clave en Galaxias:**
  * Doblete de Calcio K y L ($\lambda_{\text{Rest}} = 3933.7 \text{ Å}, 3968.5 \text{ Å}$).
  * Hidrógeno Alfa ($H\alpha$, $\lambda_{\text{Rest}} = 6562.8 \text{ Å}$).

---

# La Fórmula del Corrimiento al Rojo ($z$)

El parámetro de corrimiento al rojo $z$ se define cuantitativamente como:

<div class="formula">

$$z = \frac{\lambda_{\text{observada}} - \lambda_{\text{emitida}}}{\lambda_{\text{emitida}}} = \frac{\Delta \lambda}{\lambda_{\text{emitida}}}$$

</div>

* Si $\lambda_{\text{observada}} > \lambda_{\text{emitida}} \Rightarrow z > 0$ (**Redshift** / Alejamiento).
* Si $\lambda_{\text{observada}} < \lambda_{\text{emitida}} \Rightarrow z < 0$ (**Blueshift** / Acercamiento).
* Para velocidades no relativistas ($v \ll c$): $v pprox z \cdot c$.

---


## Ranking: surveys más recientes y con mayor precisión

Orden recomendado para investigación en estructura a gran escala y evolución de galaxias, dando prioridad a instrumentos modernos, resolución espectral y calidad de redshifts.

| # | Survey | Generación / estado | Resolución espectral (R) | Área (deg²) | Rango de redshift |
| --- | --- | --- | --- | --- | --- |
| 1 | DESI | 2021–presente | 2,000–5,500 | \~14,000 | 0–4 |
| 2 | Euclid | 2023–presente | \~380 | \~14,000 | 0.9–1.8 (cosmología) |
| 3 | 4MOST | Nueva generación | 5,000 / 20,000 | \~15,000 | Variable |
| 4 | PFS | Nueva generación | 2,300–5,000 | \~1,400 | 0.6–2.4 |
| 5 | WEAVE | Nueva generación | 5,000 / 20,000 | \~10,000 | Variable |
| 6 | Roman | Próxima generación | Variable | \~2,000\* | \~1–3 |
| 7 | MOONS | Nueva generación | Variable | Variable | \~0.5–6+ |
| 8 | SDSS-V | 2020–presente | \~2,000 | \~14,000 | Variable |
| 9 | WAVES | Nueva generación | Variable | \~1,000 | 0–0.8 |
| 10 | LAMOST | 2011–presente | \~1,800 / 7,500 | \~20,000+ | Variable |
| 11 | VIPERS | Completado | \~220 | \~24 | 0.5–1.2 |
| 12 | GAMA | Completado | Variable | \~286 | 0–0.5 |
| 13 | VVDS | Completado | \~230 | \~1 | 0–5 |
| 14 | DEEP2 | Completado | \~6,000 | \~2.8 | 0.7–1.4 |
| 15 | LEGA-C | Completado | \~3,500 | \~1.6 | 0.6–1.0 |
| 16 | MOSDEF | Completado | \~3,000–3,600 | \~0.05 | 1.4–3.8 |
| 17 | FMOS-COSMOS | Completado | \~600 | \~2 | 1.4–1.7 |
| 18 | PRIMUS | Completado | \~40 | \~9 | 0.2–1.2 |
| 19 | zCOSMOS | Completado | \~600 | \~2 | 0–1.2 |
| 20 | WiggleZ | Completado | \~1,300 | \~1,000 | 0.2–1.0 |
| 21 | 2dF Galaxy Redshift Survey | Completado | \~1,000 | \~1,500 | 0–0.3 |
| 22 | 6dF Galaxy Survey | Completado | \~1,000 | \~17,000 | 0–0.15 |
| 23 | MaNGA | Completado | \~2,000 | \~7,500\* | 0.01–0.15 |
| 24 | SAMI | Completado | \~1,700 | \~3 | 0.004–0.1 |
| 25 | CALIFA | Completado | \~850 | \~1 | 0.005–0.03 |
| 26 | MUSE-Wide | Completado | Variable | \~0.028 | 0–6+ |
| 27 | MUSE HUDF | Completado | Variable | \~0.0025 | 0–6+ |

R = λ/Δλ, resolución espectral. Los valores son aproximados y dependen de la configuración instrumental. Las áreas marcadas con asterisco son aproximaciones de cobertura o huella observacional.

### Consideraciones sobre precisión

- DESI: resolución R = 2,000–5,500 y errores de redshift muy pequeños. Su DR1 es especialmente importante para cosmología.
  DESI Data
  +1
- Euclid: sus primeros datos espectroscópicos Q1 de 2026 muestran una precisión de redshift de aproximadamente $10^{-3}$ en su rango cosmológico.
  DOI
  +1
- 4MOST, PFS y WEAVE: ofrecen configuraciones espectroscópicas modernas, incluyendo modos de alta resolución.
  ChinaRxiv
- DEEP2: aunque es un survey antiguo, su resolución espectral es alta, lo que lo hace relevante para estudios detallados.

Mi selección para cosmología y evolución de galaxias: DESI, Euclid, PFS, 4MOST, WEAVE, VIPERS, GAMA y DEEP2.

Importante: el orden es una clasificación práctica por generación y capacidades, no un ranking absoluto de precisión de redshift. Para hacer ese ranking rigurosamente habría que comparar $\sigma_z/(1+z)$, tasa de redshifts correctos, completitud y resolución espectral por población de galaxias.

---

