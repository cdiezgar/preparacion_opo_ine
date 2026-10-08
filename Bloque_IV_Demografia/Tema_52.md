# Tema 1. analisis transversal y longitudinal. Diagrama de Lexis, lineas de vida y cohortes

---

## 1. Definición y Objeto de la Demografía

La **demografía** es la ciencia social que aborda el estudio estadístico de las poblaciones humanas considerando su dimensión, estructura y estado en un instante temporal determinado, así como su evolución histórica a lo largo del tiempo.

```
                    ┌─────────────────────────────────────────┐
                    │               DEMOGRAFÍA                │
                    └────────────────────┬────────────────────┘
                                         │
                 ┌───────────────────────┴───────────────────────┐
                 ▼                                               ▼
    ┌───────────────────────────┐                   ┌───────────────────────────┐
    │  ANÁLISIS DE ESTRUCTURA   │                   │   ANÁLISIS DE DINÁMICA    │
    │       ("Foto Fija")       │                   │          ("Vídeo")        │
    └────────────┬──────────────┘                   └────────────┬──────────────┘
                 │                                               │
                 ▼                                               ▼
    ┌───────────────────────────┐                   ┌───────────────────────────┐
    │     MAGNITUDES STOCK      │                   │    MAGNITUDES DE FLUJO    │
    │  (Composición por edad,   │                   │ (Sucesos demográficos en  │
    │  sexo, estado civil en t) │                   │   un intervalo [t, t+1])  │
    └───────────────────────────┘                   └───────────────────────────┘
```

### El Doble Enfoque Analítico

* **Enfoque Estructural (Estático):** Analiza la composición cuantitativa de la población en una fecha dada según variables clave (edad, sexo, estado civil, nivel educativo, actividad profesional). Equivale a una **fotografía fija** del colectivo.
* **Enfoque Dinámico (Evolutivo):** Estudia la ocurrencia de **fenómenos demográficos** que alteran continuamente la dimensión o estructura de la población. Equivale a la proyección en **vídeo** de la dinámica poblacional.

### Fenómenos y Sucesos Demográficos

* **Fenómeno Demográfico:** Proceso o flujo colectivo caracterizado por la llegada continua de acontecimientos de una misma categoría que modifican el volumen o la composición poblacional.
* **Suceso o Acontecimiento Demográfico:** Evento individual biológico o administrativo que materializa el fenómeno en un sujeto concreto.

| Fenómeno Demográfico | Acontecimiento / Suceso | Efecto sobre la Población |
| :--- | :--- | :--- |
| **Mortalidad** | Defunción | Salida biológica (Reducción de stock) |
| **Natalidad / Fecundidad** | Nacimiento | Entrada biológica (Incremento de stock) |
| **Nupcialidad / Divorcialidad** | Matrimonio / Divorcio | Cambio de estado civil (Reestructuración) |
| **Migración** | Inmigración / Emigración | Entrada / Salida espacial (Cambio de residencia) |

> **Regla de Examen:** Un suceso es el hecho individual registrable (ej. una defunción), mientras que el fenómeno es la agregación estadística del conjunto de sucesos observados en la población durante un período (ej. la mortalidad).

---

## 2. Magnitudes y Dimensiones Temporales en Demografía

### 2.1. Magnitudes Stock y Magnitudes Flujo

El análisis demográfico clasifica las variables cuantitativas según su referencia temporal:

* **Magnitudes Stock (Variables de Estado):** Cuantifican el número de efectivos o personas presentes en un **instante de tiempo preciso** $t$ (ej. número de personas de 65 años cumplidos en España a 1 de enero de 2024).
* **Magnitudes Flujo (Variables de Ocurrencia):** Medición de los sucesos demográficos que afectan a la población durante un **intervalo de tiempo** $[t, t+1]$ (ej. total de defunciones o nacimientos registrados durante el año 2023).

### 2.2. Las Dos Dimensiones Temporales

El tiempo es el parámetro estructurador básico en demografía y se contempla bajo dos coordenadas independientes:

1. **Tiempo Cronológico o de Calendario ($t$):** Representa la fecha oficial de observación en el calendario (ej. 1 de enero de 2015, 20 de abril de 2020). Corresponde al eje horizontal en el esquema de Lexis.
2. **Duración o Tiempo Transcurrido ($x$):** Tiempo transcurrido desde la ocurrencia de un suceso origen (ej. el nacimiento para la edad, el matrimonio para la duración del matrimonio, la graduación para la inserción laboral). Corresponde al eje vertical.

### 2.3. Definiciones de Edad y Generación

* **Edad Cumplida ($x$):** Número entero de años completados por un individuo ($x \leq \text{edad} < x+1$). En datos agrupados por edades simples, el intervalo continuo es $[x, x+1)$ y su marca de clase es $x + 0{,}5$.
* **Edad Exacta ($x$):** Momento puntual preciso en que una persona alcanza exactamente el aniversario de su nacimiento (ej. cumplir exactamente 18 años).
* **Cohorte:** Conjunto de individuos que experimentan un mismo suceso origen durante un período de tiempo idéntico (normalmente un año civil).
* **Generación:** Caso particular de cohorte en el que el suceso origen es el **nacimiento**. Relación matemática de la generación $g$:

$$g = t - x$$

Donde $t$ es el año de calendario y $x$ es la edad cumplida alcanzada durante dicho año.

---

## 3. El Esquema o Diagrama de Lexis

El **Diagrama de Lexis** (diseñado por el estadístico alemán Wilhelm Lexis, 1837-1914) es un plano cartesiano bidimensional que permite representar simultáneamente las dos coordenadas temporales de los fenómenos demográficos: el **tiempo cronológico ($t$)** en abscisas y la **duración o edad ($x$)** en ordenadas.

<div class="my-6 flex justify-center not-prose">
<svg viewBox="0 0 500 320" class="w-full max-w-md bg-white rounded-xl border border-slate-200 p-4 shadow-sm" xmlns="http://www.w3.org/2000/svg">
  <!-- Title -->
  <text x="250" y="22" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="13" fill="#1e293b">Esquema Fundamental de Lexis</text>
  
  <!-- Axes -->
  <line x1="60" y1="260" x2="450" y2="260" stroke="#334155" stroke-width="2" marker-end="url(#arrow)"/>
  <line x1="60" y1="260" x2="60" y2="40" stroke="#334155" stroke-width="2" marker-end="url(#arrow)"/>
  
  <!-- Axis Labels -->
  <text x="450" y="280" text-anchor="end" font-family="sans-serif" font-size="10" font-weight="semibold" fill="#475569">Tiempo cronológico (t)</text>
  <text x="50" y="35" text-anchor="end" font-family="sans-serif" font-size="10" font-weight="semibold" fill="#475569">Edad / Duración (x)</text>
  
  <!-- Ticks & Grid Lines -->
  <!-- Years: 2020, 2021, 2022 -->
  <line x1="150" y1="260" x2="150" y2="50" stroke="#cbd5e1" stroke-width="1" stroke-dasharray="3"/>
  <line x1="270" y1="260" x2="270" y2="50" stroke="#cbd5e1" stroke-width="1" stroke-dasharray="3"/>
  <line x1="390" y1="260" x2="390" y2="50" stroke="#cbd5e1" stroke-width="1" stroke-dasharray="3"/>
  
  <text x="150" y="275" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#0f172a">2020</text>
  <text x="270" y="275" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#0f172a">2021</text>
  <text x="390" y="275" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#0f172a">2022</text>
  
  <!-- Ages: 0, 1, 2 -->
  <line x1="60" y1="190" x2="420" y2="190" stroke="#cbd5e1" stroke-width="1" stroke-dasharray="3"/>
  <line x1="60" y1="120" x2="420" y2="120" stroke="#cbd5e1" stroke-width="1" stroke-dasharray="3"/>
  
  <text x="48" y="264" text-anchor="end" font-family="sans-serif" font-size="10" fill="#0f172a">0</text>
  <text x="48" y="194" text-anchor="end" font-family="sans-serif" font-size="10" fill="#0f172a">1</text>
  <text x="48" y="124" text-anchor="end" font-family="sans-serif" font-size="10" fill="#0f172a">2</text>
  
  <!-- Life Line -->
  <!-- Birth at A (mid 2020), Death at B (mid 2022 at age ~1.8) -->
  <line x1="210" y1="260" x2="390" y2="80" stroke="#2563eb" stroke-width="3"/>
  <circle cx="210" cy="260" r="5" fill="#2563eb"/>
  <circle cx="390" cy="80" r="5" fill="#dc2626"/>
  
  <text x="210" y="250" text-anchor="end" font-family="sans-serif" font-size="10" font-weight="bold" fill="#2563eb">A (Nacimiento)</text>
  <text x="400" y="75" text-anchor="start" font-family="sans-serif" font-size="10" font-weight="bold" fill="#dc2626">B (Defunción)</text>

  <!-- Element Annotations -->
  <!-- Isochrone (vertical line t=2021) -->
  <line x1="270" y1="260" x2="270" y2="50" stroke="#059669" stroke-width="2"/>
  <text x="275" y="160" font-family="sans-serif" font-size="9" font-weight="bold" fill="#059669">Isócrona (Stock t)</text>

  <!-- Anniversary Line (horizontal line x=1) -->
  <line x1="60" y1="190" x2="420" y2="190" stroke="#d97706" stroke-width="2"/>
  <text x="100" y="183" font-family="sans-serif" font-size="9" font-weight="bold" fill="#d97706">Línea de Aniversario (x=1)</text>

  <!-- Arrow definition -->
  <defs>
    <marker id="arrow" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#334155" />
    </marker>
  </defs>
</svg>
</div>

### Elementos Geométricos del Diagrama

1. **Líneas de Vida (o de Supervivencia):** Segmentos rectilíneos orientados a $45^\circ$ respecto a los ejes (paralelos a la bisectriz).
   * Su punto inicial se sitúa en la abscisa correspondiente a la fecha de incorporación (nacimiento $x=0$ o inmigración).
   * Su punto final se sitúa en la coordenada $(t_d, x_d)$ correspondiente a la fecha y edad de salida (defunción o emigración).
2. **Isócronas (Líneas Verticales):** Rectas $t = \text{constante}$. Miden magnitudes **stock**: el número de líneas de vida que cortan la vertical representa la población viva en esa fecha exacta.
3. **Líneas de Aniversario (Líneas Horizontales):** Rectas $x = \text{constante}$. Miden un **flujo de aniversario (unidimensional)**: número de individuos que cumplen exactamente la edad $x$ a lo largo del tiempo.
4. **Líneas de Generación:** Franjas diagonales a $45^\circ$ delimitadas por las líneas de vida de las personas nacidas entre el 1 de enero y el 31 de diciembre de un mismo año.

> **Regla de Examen:** Puesto que las dos dimensiones temporales ($t$ y $x$) avanzan a la misma velocidad constante (un año de tiempo cronológico implica cumplir exactamente un año de edad), las líneas de vida tienen siempre una pendiente matemática rígida de $+1$ ($45^\circ$).

---

## 4. Recintos y Tipos de Flujo en el Diagrama de Lexis

Los acontecimientos demográficos de flujo se contabilizan dentro de figuras geométricas específicas según los criterios de clasificación disponibles:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    FIGURAS GEOMÉTRICAS EN LEXIS                         │
└────────────────────────────────────┬────────────────────────────────────┘
                                     │
     ┌──────────────────┬────────────┴─────────────┬──────────────────┐
     ▼                  ▼                          ▼                  ▼
┌──────────────┐ ┌──────────────┐          ┌──────────────┐    ┌──────────────┐
│  TRIÁNGULO   │ │  ROMBOIDE    │          │  PARALELOG.  │    │   CUADRADO   │
│  DE LEXIS    │ │ (PARALELOG.) │          │  INCLINADO   │    │   DE LEXIS   │
└──────┬───────┘ └──────┬───────┘          └──────┬───────┘    └──────┬───────┘
       │                │                         │                   │
       ▼                ▼                         ▼                   ▼
 Generación-       Cohorte-                   Cohorte-             Período-
 Período-Edad      Período                    Edad                 Edad
 (Puro / MNP)      (Perspectiva)              (Bienio)             (Transversal)
```

### Clasificación de Recintos

1. **Triángulo de Lexis (Flujo Generación-Período-Edad):**
   * **Límites:** Delimitado por una isócrona, una línea de aniversario y una línea de vida.
   * **Propiedad:** Es la unidad mínima de observación pura. Registra sucesos acaecidos durante un año de calendario $t$, a una edad cumplida $x$ y pertenecientes a una única generación $g$.
2. **Paralelogramo Romboide (Flujo Cohorte-Período o Perspectiva):**
   * **Límites:** Delimitado por dos isócronas ($t$ y $t+1$) y las dos líneas de vida extremas de una cohorte.
   * **Propiedad:** Unifica dos triángulos contiguos de un mismo año. Los sujetos pertenecen a una sola generación y sufren el suceso a la **edad exacta $x$** (en promedio $x$ años si la distribución es uniforme).
3. **Paralelogramo Inclinado (Flujo Cohorte-Edad):**
   * **Límites:** Delimitado por dos líneas de aniversario ($x$ y $x+1$) y las líneas de vida de una cohorte.
   * **Propiedad:** Observa a una única generación durante todo el tiempo en que mantiene una **edad cumplida $x$** (requiere observar dos años de calendario $t$ y $t+1$). Edad media de ocurrencia $x + 0{,}5$ años.
4. **Cuadrado de Lexis (Flujo Período-Edad):**
   * **Límites:** Delimitado por dos isócronas ($t$ y $t+1$) y dos líneas de aniversario ($x$ y $x+1$).
   * **Propiedad:** Registra los sucesos ocurridos en un año $t$ a la edad cumplida $x$. Abarca dos triángulos de Lexis pertenecientes a **dos generaciones distintas**.

### Cuadro Comparativo de Recintos

| Figura Geométrico | Denominación del Flujo | Dimensiones Delimitadas | Edad Media Implícita | Cohortes Afectadas |
| :--- | :--- | :--- | :--- | :--- |
| **Triángulo** | Generación-Período-Edad | Período $t$, Edad $x$, Generación $g$ | $x + 0{,}33$ o $x + 0{,}67$ | 1 Cohorte |
| **Romboide** | Cohorte-Período (Perspectiva) | Período $t$, Generación $g$ | Edad exacta $x$ (Promedio $x$) | 1 Cohorte |
| **Inclinado** | Cohorte-Edad | Generación $g$, Edad cumplida $x$ | $x + 0{,}5$ años | 1 Cohorte (2 Años) |
| **Cuadrado** | Período-Edad (Transversal) | Período $t$, Edad cumplida $x$ | $x + 0{,}5$ años | 2 Cohortes |

---

## 5. Análisis Longitudinal frente a Análisis Transversal

El estudio de un fenómeno demográfico se aborda desde dos perspectivas temporales alternativas:

### 5.1. Análisis Longitudinal (Diacrónico)

* **Definición:** Consiste en la observación continua de una **cohorte real** de individuos a lo largo de toda su vida o durante todo el tiempo en que permanece expuesta al riesgo del fenómeno.
* **Representación en Lexis:** Se representa mediante la **franja o barra inclinada a $45^\circ$**.
* **Ventajas:** Máximo rigor analítico. Permite evaluar la intensidad final y el calendario real de los fenómenos (ej. descendencia final de una cohorte de mujeres).
* **Inconvenientes:** Naturaleza **retrospectiva**. Para conocer la esperanza de vida o fecundidad final de una generación se debe esperar a su completa extinción o finalización de la vida fértil.

### 5.2. Análisis Transversal (Sincrónico)

* **Definición:** Consiste en la observación coyuntural de la incidencia del fenómeno en todas las cohortes presentes en la población durante un **período temporal limitado** (generalmente un año civil $t$).
* **Representación en Lexis:** Se representa mediante la **columna vertical** delimitada por dos isócronas.
* **Ventajas:** Disponibilidad inmediata con datos del presente para evaluar la **coyuntura demográfica**.

### 5.3. El Concepto de Cohorte Ficticia

Para obtener indicadores transversales sintéticos con significado interpretable (como el Indicador Coyuntural de Fecundidad o la Esperanza de Vida al Nacer), la demografía construye el modelo teórico de la **cohorte ficticia** (o generación hipotética):

> **Definición:** Una **cohorte ficticia** es una cohorte teórica sometida hipotéticamente a lo largo de toda su vida a las pautas y tasas específicas por edad observadas en una población real durante un único período transversal (un año o bienio).

<div class="my-6 flex justify-center not-prose">
<svg viewBox="0 0 500 280" class="w-full max-w-md bg-white rounded-xl border border-slate-200 p-4 shadow-sm" xmlns="http://www.w3.org/2000/svg">
  <!-- Title -->
  <text x="250" y="22" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="13" fill="#1e293b">Perspectivas de Análisis en Lexis</text>
  
  <!-- Axes -->
  <line x1="50" y1="230" x2="450" y2="230" stroke="#334155" stroke-width="2"/>
  <line x1="50" y1="230" x2="50" y2="40" stroke="#334155" stroke-width="2"/>
  <text x="440" y="248" font-family="sans-serif" font-size="10" fill="#475569">Tiempo (t)</text>
  <text x="45" y="35" font-family="sans-serif" font-size="10" fill="#475569">Edad (x)</text>

  <!-- Transversal Column (Green) -->
  <rect x="90" y="50" width="50" height="180" fill="#dcfce7" stroke="#16a34a" stroke-width="2"/>
  <text x="115" y="140" font-family="sans-serif" font-weight="bold" font-size="11" fill="#15803d" text-anchor="middle" transform="rotate(-90 115 140)">ANÁLISIS TRANSVERSAL</text>

  <!-- Longitudinal Band (Blue) -->
  <polygon points="190,230 240,230 390,50 340,50" fill="#dbeafe" stroke="#2563eb" stroke-width="2"/>
  <text x="290" y="145" font-family="sans-serif" font-weight="bold" font-size="11" fill="#1d4ed8" text-anchor="middle" transform="rotate(-40 290 145)">ANÁLISIS LONGITUDINAL</text>

  <!-- Legend -->
  <rect x="250" y="180" width="180" height="40" rx="6" fill="#f8fafc" stroke="#cbd5e1"/>
  <rect x="260" y="188" width="12" height="12" fill="#16a34a"/>
  <text x="280" y="198" font-family="sans-serif" font-size="9" fill="#0f172a">Transversal (Año t)</text>
  <rect x="260" y="204" width="12" height="12" fill="#2563eb"/>
  <text x="280" y="214" font-family="sans-serif" font-size="9" fill="#0f172a">Longitudinal (Cohorte g)</text>
</svg>
</div>

---

## 6. Indicadores Demográficos: Tasas, Cocientes, Proporciones y Ratios

En demografía, las magnitudes absolutas (flujos y stocks) no permiten la comparación directa entre poblaciones de distinto tamaño. Se requiere el empleo de **medidas relativas**:

### 6.1. Definición de Tasa

Una **tasa** es un cociente que relaciona un flujo de sucesos demográficos ocurridos durante un período con la **población media expuesta al riesgo** durante dicho intervalo:

$$\text{Tasa}(t, t+1) = \frac{\text{Sucesos}(t, t+1)}{\text{Población Media}(t, t+1)}$$

* **Estimación de la Población Media:**
  * En la práctica oficial del INE, la población media se estima mediante la **población a mitad de período (1 de julio)**: $P_{01-07-t}$.
  * En su defecto, se calcula como la media aritmética simple de las poblaciones al inicio y fin de año:

$$\text{Población Media}(t, x) = \frac{P(t, x) + P(t+1, x)}{2}$$

* **Categorías de Tasas:**
  * **Tasas de $1^{\text{a}}$ Categoría:** Todos los componentes del denominador están expuestos a sufrir el suceso del numerador (ej. Tasa Bruta de Mortalidad).
  * **Tasas de $2^{\text{a}}$ Categoría:** En el denominador figuran individuos que no están expuestos a sufrir el suceso del numerador (ej. Tasa Bruta de Natalidad, donde la población total incluye hombres y ancianos).

### 6.2. Cocientes (Riesgos o Probabilidades)

En demografía formal, se define **cociente** como el cociente entre un flujo de sucesos y la **población inicial** del período de referencia ($P_t$), en lugar de la población media:

$$\text{Cociente}(t) = \frac{\text{Sucesos}(t, t+1)}{P_t}$$

Cuando es de $1^{\text{a}}$ categoría, el cociente mide la **probabilidad empírica** o **riesgo** de que los miembros de una cohorte experimenten el suceso (ej. la probabilidad o riesgo de muerte $q_x$ en las tablas de mortalidad).

### 6.3. Proporciones y Ratios (Razones)

* **Proporción:** Relación entre dos magnitudes de la misma naturaleza (dos stocks o dos flujos). Es de $1^{\text{a}}$ categoría cuando el numerador está subconjuntado dentro del denominador:

$$\text{Proporción} = \frac{\text{Stock}_A}{\text{Stock}_{\text{Total}}} \quad (\text{rango } [0, 1] \text{ o } [0, 100\%])$$

* **Ratio o Razón:** Cociente entre dos magnitudes mutuamente excluyentes o procedentes de poblaciones disjuntas ($2^{\text{a}}$ categoría):

$$\text{Ratio de Masculinidad } (RM) = \frac{P_{\text{hombres}}}{P_{\text{mujeres}}} \cdot 100$$

### 6.4. Tasas Brutas frente a Tasas Específicas

* **Tasa Bruta:** Relaciona los sucesos totales con la población media total. Es una medida sintética influenciada fuertemente por la estructura por edad de la población.
* **Tasas Específicas:** Miden la intensidad del fenómeno en subgrupos homogéneos (desagregados por edad, sexo o cohorte).

### 6.5. Formulación Matemática de las Tasas Específicas en Lexis

#### a) Tasa Específica de Período-Edad (Transversal / Cuadrado)

Relaciona los sucesos $S(t,x)$ ocurridos en el año $t$ a personas con edad cumplida $x$ con la población media de esa misma edad:

$$m(t,x) = \frac{S(t,x)}{0{,}5 \cdot (P(t,x) + P(t+1,x))}$$

#### b) Tasa Específica de Período-Cohorte o Perspectiva (Romboide)

Relaciona los sucesos acaecidos en el año $t$ a los miembros de una misma generación $g$, divididos entre la población media de esa generación:

$$m(t,g) = \frac{S(t,x,g) + S(t,x+1,g)}{0{,}5 \cdot (P(t,x,g) + P(t+1,x+1,g))}$$

#### c) Tasa Específica de Cohorte-Edad (Inclinada / Bienio)

Relaciona los sucesos ocurridos a una generación $g$ al atravesar la edad cumplida $x$ durante dos años consecutivos ($t$ y $t+1$), divididos por la población al inicio del segundo año:

$$m(t,x,g) = \frac{S(t,x,g) + S(t+1,x,g)}{P(t+1,x)}$$

---

## 7. Caso Práctico Resuelto Completo (Ejemplo Oficial del INE)

A continuación se presenta la resolución completa del ejemplo numérico oficial sobre la integración de stocks, flujos y tasas en un esquema de Lexis:

### Datos de Partida (Sucesos y Stocks)

* **Poblaciones Iniciales a 01/01/2013:**
  * $P(2013, \text{edad } 0) = 453.294$ (Generación 2012)
  * $P(2013, \text{edad } 1) = 475.617$ (Generación 2011)
  * $P(2013, \text{edad } 2) = 481.415$ (Generación 2010)
  * $P(2013, \text{edad } 3) = 492.831$ (Generación 2009)
* **Nacimientos durante 2013:** $N(2013) = 424.440$
* **Eventos en 2013 y 2014 por Triángulos de Lexis:**

| Año Nacimiento | Edad | Defunciones 2013 ($D$) | Inmigraciones 2013 ($I$) | Emigraciones 2013 ($E$) | Defunciones 2014 ($D$) |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **2013** | 0 | 996 | 2.170 | 733 | 143 (a edad 1) |
| **2012** | 0 | 153 | 1.966 | 1.534 | - |
| **2012** | 1 | 53 | 1.773 | 2.278 | 42 |
| **2011** | 1 | 50 | 1.685 | 3.053 | - |
| **2011** | 2 | 42 | 1.613 | 3.118 | 28 |
| **2010** | 2 | 35 | 1.750 | 2.716 | - |
| **2010** | 3 | 19 | 1.604 | 2.479 | 23 |

### Pasos de Resolución

#### 1. Cálculo de Stocks Finales a 01/01/2014

Aplicando la **Ecuación Compensadora** en cada paralelogramo:

* **Población 0 años a 01/01/2014:**

$$P(2014, 0) = N(2013) - D + I - E = 424.440 - 996 + 2.170 - 733 = 424.881$$

* **Población 1 año a 01/01/2014:**

$$P(2014, 1) = 453.294 - (153 + 53) + (1.966 + 1.773) - (1.534 + 2.278) = 453.015$$

* **Población 2 años a 01/01/2014:**

$$P(2014, 2) = 475.617 - (50 + 42) + (1.685 + 1.613) - (3.053 + 3.118) = 472.652$$

* **Población 3 años a 01/01/2014:**

$$P(2014, 3) = 481.415 - (35 + 19) + (1.750 + 1.604) - (2.716 + 2.479) = 479.520$$

#### 2. Cálculo de Aniversarios en 2013

* **Aniversario 1 año:** $453.294 - 153 + 1.966 - 1.534 = 453.573$
* **Aniversario 2 años:** $475.617 - 50 + 1.685 - 3.053 = 474.199$
* **Aniversario 3 años:** $481.415 - 35 + 1.750 - 2.716 = 480.414$

#### 3. Cálculo de Tasas de Mortalidad

* **a) Tasas Período-Edad para el año 2013 ($m_x^{2013}$):**

$$m_1^{2013} = \frac{50 + 53}{0{,}5 \cdot (475.617 + 453.015)} = \frac{103}{464.316} = 0{,}0002218 \quad (0{,}22 \text{ \textperthousand})$$

$$m_2^{2013} = \frac{35 + 42}{0{,}5 \cdot (481.415 + 472.652)} = \frac{77}{477.033{,}5} = 0{,}0001614 \quad (0{,}16 \text{ \textperthousand})$$

$$m_3^{2013} = \frac{29 + 19}{0{,}5 \cdot (492.831 + 479.520)} = \frac{48}{486.175{,}5} = 0{,}0000987 \quad (0{,}10 \text{ \textperthousand})$$

* **b) Tasas Período-Cohorte o Perspectivas para 2013 ($m_g^{2013}$):**

$$m_{2012}^{2013} = \frac{153 + 53}{0{,}5 \cdot (453.294 + 453.015)} = \frac{206}{453.154{,}5} = 0{,}0004546 \quad (0{,}45 \text{ \textperthousand})$$

$$m_{2011}^{2013} = \frac{50 + 42}{0{,}5 \cdot (475.617 + 472.652)} = \frac{92}{474.134{,}5} = 0{,}0001940 \quad (0{,}19 \text{ \textperthousand})$$

$$m_{2010}^{2013} = \frac{35 + 19}{0{,}5 \cdot (481.415 + 479.520)} = \frac{54}{480.467{,}5} = 0{,}0001124 \quad (0{,}11 \text{ \textperthousand})$$

* **c) Tasas Cohorte-Edad para el bienio 2013-2014 ($mge_x^{2013-2014}$):**

$$mge_1^{2013-2014} = \frac{53 + 42}{453.015} = \frac{95}{453.015} = 0{,}0002097 \quad (0{,}21 \text{ \textperthousand})$$

$$mge_2^{2013-2014} = \frac{42 + 28}{472.652} = \frac{70}{472.652} = 0{,}0001481 \quad (0{,}15 \text{ \textperthousand})$$

$$mge_3^{2013-2014} = \frac{19 + 23}{479.520} = \frac{42}{479.520} = 0{,}0000876 \quad (0{,}09 \text{ \textperthousand})$$

---

💡 **Recomendación de estudio:** Tras dominar este tema conceptual y metodológico, estás preparado para abordar el estudio analítico de la **Mortalidad y Tablas de Vida (Tema 2 / Temas 53 y 54 Oficiales)**.
