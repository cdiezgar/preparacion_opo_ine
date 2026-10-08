# Tema 5. Estructura y Crecimiento de la Población: Pirámides, Envejecimiento y Poblaciones Teóricas

---

## 1. Visión General e Indicadores de Estructura Poblacional

La **estructura de una población** representa la distribución de sus efectivos según características demográficas y socioeconómicas en un instante de tiempo determinado (magnitud de *stock*). Las variables estructurales primarias son el **sexo** y la **edad**, de las cuales se derivan las pautas de mortalidad, fecundidad, nupcialidad, actividad económica y dependencia.

```
                    ┌─────────────────────────────────────────┐
                    │        ESTRUCTURA DE LA POBLACIÓN       │
                    └────────────────────┬────────────────────┘
                                         │
                 ┌───────────────────────┴───────────────────────┐
                 ▼                                               ▼
    ┌───────────────────────────┐                   ┌───────────────────────────┐
    │    COMPOSICIÓN POR SEXO   │                   │    COMPOSICIÓN POR EDAD   │
    │   (Dimensión biológica)   │                   │   (Dimensión temporal)    │
    └────────────┬──────────────┘                   └────────────┬──────────────┘
                 │                                               │
      ┌──────────┴──────────┐                         ┌──────────┴──────────┐
      ▼                     ▼                         ▼                     ▼
┌───────────┐         ┌───────────┐             ┌───────────┐         ┌───────────┐
│ RATIO DE  │         │PROPORCIÓN │             │MEDIDAS DE │         │ ÍNDICES DE│
│MASCULINID.│         │DE HOMBRES/│             │ TENDENCIA │         │ENVEJECIM. │
│   (RM)    │         │  MUJERES  │             │CENTRAL(EM)│         │ DEPENDEN. │
└───────────┘         └───────────┘             └───────────┘         └───────────┘
```

---

### 1.1. Composición por Sexo

El análisis por sexo mide la proporción entre hombres y mujeres. Biológicamente nacen más varones que mujeres, pero la **sobremortalidad masculina** diferencial a lo largo de la vida invierte esta relación en las edades avanzadas.

#### A) Ratio o Razón de Masculinidad ($RM_t$)
Mide el número de hombres por cada 100 mujeres en la población a $1$ de enero del año $t$:

$$RM_t = \frac{P_{hombres,t}}{P_{mujeres,t}} \cdot 100$$

* **Ratio de Masculinidad al Nacimiento ($RMN_t$):** Presenta una constancia biológica entre $105$ y $107$ niños por cada $100$ niñas (en España el promedio histórico se sitúa en torno a $107$).
* **Ratio de Feminidad ($RF_t$):** Indicador inverso que expresa el número de mujeres por cada 100 hombres:

$$RF_t = \frac{P_{mujeres,t}}{P_{hombres,t}} \cdot 100 = \frac{10000}{RM_t}$$

#### B) Proporciones por Sexo
Expresan el peso relativo de cada sexo respecto a la población total ($P_t$):

$$\text{PROP}_{hombres,t} = \frac{P_{hombres,t}}{P_t} \cdot 100 \qquad \text{y} \qquad \text{PROP}_{mujeres,t} = \frac{P_{mujeres,t}}{P_t} \cdot 100$$

> **Regla de Examen:** En poblaciones jóvenes o con fuerte inmigración económica masculina, el $RM_t$ es superior a $100$. En poblaciones envejecidas, la sobremortalidad masculina acumulada hace que el $RM_t$ descienda muy por debajo de $100$ en los grandes grupos de edad superior ($65$ y más años).

---

### 1.2. Composición por Edad

La edad es una variable cuantitativa continua que estadísticamente se discretiza en **años cumplidos** (redondeo a la baja de la edad exacta).

#### A) Edad Media de la Población ($\text{EMedia}_t$)
Media aritmética de las edades de los individuos de la población a $1$ de enero del año $t$. Considerando datos de edades simples de amplitud un año, la marca de clase es $x + 0{,}5$:

$$\text{EMedia}_t = \frac{\sum_x \left(x + 0{,}5\right) \cdot P_{x,t}}{\sum_x P_{x,t}}$$

Donde $P_{x,t}$ representa la población residente con $x$ años cumplidos a $1$ de enero del año $t$.

#### B) Edad Mediana de la Población ($\text{EMediana}_t$)
Medida de posición que divide a la distribución de la población en dos partes numéricamente iguales (el $50\%$ tiene una edad igual o inferior a la mediana y el otro $50\%$ una edad superior). Se calcula mediante la interpolación:

$$\text{EMediana}_t = \text{EDAD}_{med,t} + \frac{\frac{P_t}{2} - P_{[0, med-1],t}}{P_{med,t}}$$

Donde:
* $\text{EDAD}_{med,t}$: Edad entera cumplida donde la población acumulada alcanza o supera por primera vez el $50\%$ de la población total ($P_t / 2$).
* $P_{[0, med-1],t}$: Población acumulada con edad inferior a $\text{EDAD}_{med,t}$.
* $P_{med,t}$: Población de la edad simple $\text{EDAD}_{med,t}$.

> **Regla de Examen:** En la serie histórica reciente de España, la Edad Mediana ha crecido a mayor velocidad que la Edad Media debido al fuerte estrechamiento de la base por la caída de la natalidad, superando a la Edad Media a partir del año 2016.

---

### 1.3. Indicadores Sintéticos de Envejecimiento y Dependencia

Para la evaluación analítica de la estructura por edad se definen los grandes grupos funcional-laborales: **jóvenes ($0$ a $15$ años)**, **potencialmente activos ($16$ a $64$ años)** y **mayores ($65$ y más años)**.

#### A) Proporción de Personas Mayores ($\text{PROP}_{x+},t$)
Porcentaje de personas de $x$ o más años respecto al total poblacional:

$$\text{PROP}_{65+,t} = \frac{P_{65+,t}}{P_t} \cdot 100 \qquad \text{y} \qquad \text{PROP}_{84+,t} = \frac{P_{84+,t}}{P_t} \cdot 100$$

#### B) Índice de Envejecimiento
Cociente entre la población de $65$ y más años y la población menor de $16$ años:

$$\text{Índice de Envejecimiento}_t = \frac{P_{65+,t}}{P_{0-15,t}} \cdot 100$$

Un valor superior a $100$ indica que la población mayor supera numéricamente a la población infantil. En España, este índice rebasó el $100\%$ en el año $2000$ y alcanzó el $129{,}2\%$ en $2021$.

#### C) Tasas de Dependencia Económico-Demográfica
Miden la relación entre la población potencialmente inactiva por razón de edad y la población en edad de trabajar ($16$ a $64$ años):

1. **Tasa de Dependencia Total ($TD_t$):**
   $$TD_t = \frac{P_{0-15,t} + P_{65+,t}}{P_{16-64,t}} \cdot 100$$

2. **Tasa de Dependencia de Jóvenes ($TD_{joven,t}$):**
   $$TD_{joven,t} = \frac{P_{0-15,t}}{P_{16-64,t}} \cdot 100$$

3. **Tasa de Dependencia de Mayores ($TD_{mayor,t}$):**
   $$TD_{mayor,t} = \frac{P_{65+,t}}{P_{16-64,t}} \cdot 100$$

$$\text{Propiedad de aditividad:} \qquad TD_t = TD_{joven,t} + TD_{mayor,t}$$

---

## 2. Pirámides de Población

### 2.1. Definición y Construcción Técnica

La **pirámide de población** es la representación gráfica fundamental de la estructura por edad y sexo. Consiste en dos histogramas de barras horizontales adosados:
* **Eje Vertical (Ordenadas):** Edades simples o grupos quinquenales de edad (de menor a mayor altura).
* **Eje Horizontal (Abscisas):** Efectivos de hombres a la izquierda y de mujeres a la derecha.
* **Escala de Barras:** Para permitir la comparabilidad entre poblaciones de distinto tamaño, la superficie de los rectángulos se expresa en **proporciones o porcentajes sobre la población total** ($\text{PROP}_{x,x+a}^m$ y $\text{PROP}_{x,x+a}^f$), verificándose:

$$\sum_x \left(\text{PROP}_{x,x+a}^m + \text{PROP}_{x,x+a}^f\right) = 1 \quad (\text{o } 100\%)$$

---

### 2.2. Tipología Clásica de Pirámides Poblacionales

<div class="my-6 flex justify-center not-prose">
<svg viewBox="0 0 500 320" class="w-full max-w-md bg-white rounded-xl border border-slate-200 p-4 shadow-sm" xmlns="http://www.w3.org/2000/svg">
  <text x="250" y="22" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="13" fill="#1e293b">Tipologías Estructurales de Pirámides de Población</text>
  
  <!-- 1. Pagoda -->
  <g transform="translate(20, 45)">
    <rect x="0" y="0" width="135" height="230" rx="6" fill="#f8fafc" stroke="#cbd5e1" stroke-width="1.5"/>
    <text x="67.5" y="20" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="10" fill="#0f172a">EXPANSIVA (PAGODA)</text>
    <!-- Pyramid shape -->
    <polygon points="67.5,35 15,200 120,200" fill="#ef4444" opacity="0.7"/>
    <line x1="67.5" y1="35" x2="67.5" y2="200" stroke="#b91c1c" stroke-width="1.5"/>
    <text x="67.5" y="218" text-anchor="middle" font-family="sans-serif" font-size="8.5" fill="#475569">Alta natalidad/mortalidad</text>
  </g>

  <!-- 2. Campana -->
  <g transform="translate(182, 45)">
    <rect x="0" y="0" width="135" height="230" rx="6" fill="#f8fafc" stroke="#cbd5e1" stroke-width="1.5"/>
    <text x="67.5" y="20" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="10" fill="#0f172a">ESTACIONARIA (CAMPANA)</text>
    <!-- Bell shape -->
    <path d="M 67.5,35 C 40,80 30,140 30,200 L 105,200 C 105,140 95,80 67.5,35 Z" fill="#3b82f6" opacity="0.7"/>
    <line x1="67.5" y1="35" x2="67.5" y2="200" stroke="#1d4ed8" stroke-width="1.5"/>
    <text x="67.5" y="218" text-anchor="middle" font-family="sans-serif" font-size="8.5" fill="#475569">Natalidad/mortalidad estables</text>
  </g>

  <!-- 3. Bulbo -->
  <g transform="translate(345, 45)">
    <rect x="0" y="0" width="135" height="230" rx="6" fill="#f8fafc" stroke="#cbd5e1" stroke-width="1.5"/>
    <text x="67.5" y="20" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="10" fill="#0f172a">REGRESIVA (BULBO)</text>
    <!-- Urn/Bulb shape -->
    <path d="M 67.5,35 C 30,70 15,110 30,150 C 40,175 50,190 50,200 L 85,200 C 85,190 95,175 105,150 C 120,110 105,70 67.5,35 Z" fill="#10b981" opacity="0.7"/>
    <line x1="67.5" y1="35" x2="67.5" y2="200" stroke="#047857" stroke-width="1.5"/>
    <text x="67.5" y="218" text-anchor="middle" font-family="sans-serif" font-size="8.5" fill="#475569">Base estrecha/Envejecimiento</text>
  </g>
</svg>
</div>

1. **Expansiva (Forma de Pagoda o Triangular):**
   * **Características:** Base muy ancha y cúspide afilada.
   * **Régimen:** Elevada natalidad y alta mortalidad infantil/general.
   * **Perfil:** Población joven de rápido crecimiento (propia de países en desarrollo).
2. **Estacionaria (Forma de Campana):**
   * **Características:** Base moderada y bordes rectos escalonados.
   * **Régimen:** Natalidad y mortalidad controladas y estables.
   * **Perfil:** Reemplazo generacional garantizado sin envejecimiento extremo.
3. **Regresiva (Forma de Bulbo, Urna o Constrictiva):**
   * **Características:** Base estrecha (menor anchura que el tronco central) y cúspide ensanchada.
   * **Régimen:** Natalidad en declive continuo y elevada esperanza de vida.
   * **Perfil:** Población envejecida con crecimiento natural nulo o negativo (propia de España, Japón, Italia).

---

### 2.3. Huellas Históricas en la Pirámide de la Población Española

El perfil de la pirámide de España refleja los acontecimientos demográficos y bélicos del siglo XX y XXI:
* **Muesca de la Guerra Civil (1936-1939):** Pérdida de efectivos en las generaciones nacidas entre $1911$ y $1921$ (fallecimientos en el frente, mayoritariamente masculinos) y una brusca **subnatalidad** entre $1937$ y $1942$ (con un hueco crítico en la generación de $1940$).
* **Abultamiento del Baby-Boom (1958-1977):** Etapa de intensa natalidad que constituye el abultamiento central de la pirámide actual (edades comprendidas entre $45$ y $65$ años).
* **Estreachamiento de la Base (1978 en adelante):** Caída libre del Índice Sintético de Fecundidad hasta niveles de $1{,}15$-$1{,}30$ hijos por mujer.
* **Repunte de 2008 y Crisis:** Ligero aumento de la natalidad impulsado por la inmigración previa a $2008$, seguido de una posterior contracción.

---

## 3. Crecimiento Demográfico y Ecuación Compensadora

### 3.1. Ecuación Compensadora Fundamental

El crecimiento total de una población en un intervalo $[0, t]$ responde a la interacción de los flujos biológicos y migratorios:

$$P_t = P_0 + \underbrace{(N - D)}_{\text{Saldo Vegetativo } (S_v)} + \underbrace{(I - E)}_{\text{Saldo Migratorio } (S_m)}$$

$$\text{Crecimiento Total Absoluto: } \qquad \Delta P = P_t - P_0 = S_v + S_m$$

---

### 3.2. Tasas e Indicadores de Crecimiento

#### A) Tasa de Crecimiento Natural o Vegetativo ($TCN$)
Diferencia entre la Tasa Bruta de Natalidad ($TBN$) y la Tasa Bruta de Mortalidad ($TBM$), expresada en tanto por ciento o por mil:

$$TCN = TBN - TBM = \frac{N - D}{\bar{P}} \cdot 1000$$

#### B) Ratio de Reemplazo Natural (Coeficiente de Vitalidad de Pearl)
Relación entre nacimientos y defunciones ocurridos en un año:

$$RND_t = \frac{N_t}{D_t} \cdot 1000$$

Si $RND_t > 1000$, los nacimientos superan a las defunciones ($S_v > 0$).

#### C) Modelos Matemáticos de Crecimiento Poblacional

| Modelo de Crecimiento | Ecuación de Evolución | Fórmula de la Tasa de Crecimiento ($r$) | Hipótesis del Modelo |
| :--- | :--- | :--- | :--- |
| **Aritmético** | $P_t = P_0 \cdot (1 + r \cdot t)$ | $r_{arit} = \frac{P_t - P_0}{P_0 \cdot t}$ | Crecimiento constante en volumen absoluto por unidad de tiempo. |
| **Geométrico** | $P_t = P_0 \cdot (1 + r)^t$ | $r_{geom} = \left(\frac{P_t}{P_0}\right)^{\frac{1}{t}} - 1$ | Crecimiento discreto acumulativo por intervalos anuales. |
| **Exponencial (Continuo)** | $P_t = P_0 \cdot e^{r \cdot t}$ | $r_{exp} = \frac{\ln\left(\frac{P_t}{P_0}\right)}{t}$ | Crecimiento continuo instantáneo (modelo estándar en demografía). |

---

## 4. El Envejecimiento Demográfico

El **envejecimiento poblacional** es el proceso de transformación estructural caracterizado por el aumento sostenido del peso relativo de las personas de edad avanzada ($65$ y más años) y la reducción del peso de los jóvenes.

### 4.1. Doble Dimensión Mecánica del Envejecimiento

```
                            ┌────────────────────────────────────────┐
                            │      MECANISMOS DE ENVEJECIMIENTO      │
                            └───────────────────┬────────────────────┘
                                                │
                      ┌─────────────────────────┴─────────────────────────┐
                      ▼                                                   ▼
         ┌─────────────────────────┐                         ┌─────────────────────────┐
         │ ENVEJECIMIENTO POR LA   │                         │ ENVEJECIMIENTO POR LA   │
         │          BASE           │                         │         CÚSPIDE         │
         └────────────┬────────────┘                         └────────────┬────────────┘
                      │                                                   │
     ┌────────────────┴────────────────┐                 ┌────────────────┴────────────────┐
     ▼                                 ▼                 ▼                                 ▼
┌───────────┐                     ┌───────────┐     ┌───────────┐                     ┌───────────┐
│ DESCENSO  │                     │EMIGRACIÓN │     │ AUMENTO  │                     │ CAÍDA DE  │
│ DE LA     │                     │ DE JÓVENES│     │ESPERANZA  │                     │MORTALIDAD │
│FECUNDIDAD │                     │  (RURAL)  │     │ DE VIDA   │                     │ AVANZADA  │
└───────────┘                     └───────────┘     └───────────┘                     └───────────┘
```

1. **Envejecimiento por la Base:** Se produce por la contracción de la natalidad (reducción del número de nacimientos que ingresan en la base de la pirámide). Genera un incremento porcentual reactivo de las cohorte maduras y mayores.
2. **Envejecimiento por la Cúspide:** Se origina por la ganancia sostenida en la esperanza de vida en edades avanzadas (reducción de la mortalidad de adultos mayores). Aumenta los efectivos absolutos en el tramo de $80$ y más años (envejecimiento del propio envejecimiento).

---

## 5. Poblaciones Teóricas: Población Estable y Población Estacionaria

La demografía matemática utiliza modelos teóricos de población para aislar los efectos de la mortalidad y la fecundidad sobre la estructura por edad.

### 5.1. Población Estable (Modelo de Alfred Lotka)

* **Definición:** Población hipotética cerrada a las migraciones ($I = E = 0$) sometida indefinidamente a **pautas constantes por edad de mortalidad** ($m_x$) y **fecundidad** ($f_x$).
* **Propiedades Matemáticas Fundamentales:**
  1. **Estructura por edad invariable:** Independientemente de la estructura inicial de partida, la población alcanza una distribución por edad fija y constante en el tiempo (Propiedad de Ergodicidad Demográfica).
  2. **Tasa intrínseca de crecimiento constante ($r$):** La población crece o decrece a una tasa intrínseca constante $r$, definida por la ecuación característica de Lotka:

$$\int_{\alpha}^{\beta} e^{-r \cdot x} \cdot l_x \cdot f_x \, dx = 1$$

Donde $\alpha$ y $\beta$ son los límites de la edad fértil, $l_x$ es la función de supervivencia y $f_x$ las tasas específicas de fecundidad.

---

### 5.2. Población Estacionaria

* **Definición:** Caso particular y límite de la **población estable** donde la tasa intrínseca de crecimiento natural es nula ($r = 0$).
* **Condiciones de Equilibrio:**
  * Número de nacimientos constante e igual al número de defunciones anuales ($N = D$).
  * Coincide exactamente con la población teórica de la **Tabla de Mortalidad** ($P_x = L_x$).
* **Relación Biométrica Fundamental:**
  En una población estacionaria, la Tasa Bruta de Natalidad ($TBN$) y la Tasa Bruta de Mortalidad ($TBM$) son idénticas e iguales a la **inversa de la Esperanza de Vida al Nacer ($e_0$)**:

$$TBN = TBM = \frac{1}{e_0}$$

---

## 6. Cuadro Comparativo de Síntesis

| Criterio | Población Estable | Población Estacionaria | Población Real (España 2021) |
| :--- | :--- | :--- | :--- |
| **Saldo Migratorio ($S_m$)** | $0$ (Población cerrada) | $0$ (Población cerrada) | $S_m \neq 0$ (Abierta) |
| **Tasas Específicas ($m_x, f_x$)** | Constantes en el tiempo | Constantes en el tiempo | Variables dinámicamente |
| **Tasa de Crecimiento ($r$)** | Constante ($r \neq 0$) | Nula ($r = 0$) | Variable ($\Delta P = S_v + S_m$) |
| **Estructura por Edad** | Invariable en el tiempo | Invariable ($P_x = L_x$) | Cambiante (Envejecida) |
| **Relación Natalidad / Esperanza Vida** | $TBN \neq TBM$ | $TBN = TBM = \frac{1}{e_0}$ | $TBN \neq TBM \neq \frac{1}{e_0}$ |

---

💡 **Siguiente paso recomendado:** Con este tema de Estructura y Crecimiento completado y publicado en tu panel de Studio, ¿te gustaría que pasemos a elaborar el resumen Markdown del **Tema 1 (Análisis transversal y longitudinal, Diagrama de Lexis y cohortes)**?
