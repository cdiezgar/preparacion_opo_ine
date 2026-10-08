# Tema 51. Estructura por edad y sexo. Piramides de población e indices de envejecimiento

---

## 1. Visión General, Fuentes e Indicadores Básicos de Estructura

El estudio de la población comienza por analizar su volumen, velocidad de crecimiento y composición estructural. Dos poblaciones con idéntico número de habitantes pueden presentar dinámicas y necesidades socioeconómicas radicalmente distintas si su composición por sexo, edad u otras variables es diferente.

```
                  ┌─────────────────────────────────────────┐
                  │    ESTRUCTURA Y DINÁMICA POBLACIONAL    │
                  └────────────────────┬────────────────────┘
                                       │
               ┌───────────────────────┴───────────────────────┐
               ▼                                               ▼
  ┌─────────────────────────┐                     ┌─────────────────────────┐
  │   PROCESOS DE ENTRADA   │                     │   PROCESOS DE SALIDA    │
  │ (Fecundidad / Inmigr.)  │                     │ (Mortalidad / Emigr.)   │
  └────────────┬────────────┘                     └────────────┬────────────┘
               │                                               │
               └───────────────────────┬───────────────────────┘
                                       ▼
                       ┌───────────────────────────────┐
                       │   CAMBIO Y ESTRUCTURA A1/JAN  │
                       │   (Sexo, Edad, Nacionalidad)  │
                       └───────────────────────────────┘
```

### Fuentes Estadísticas Principales en España (INE)

* **Cifras de Población:** Operación estadística del INE que proporciona la medición cuantitativa oficial de la población residente en España (referencia en todas las operaciones del INE).
* **Estadística del Padrón Continuo:** Proporciona los datos de población a nivel municipal (utilizada en municipios de más de 50.000 habitantes y capitales de provincia).
* **Estadísticas del Movimiento Natural de la Población (MNP):** Recoge los hechos vitales (nacimientos, defunciones, matrimonios).
* **Estadística de Migraciones:** Mide los flujos migratorios interautonómicos, interprovinciales y con el extranjero.
* **Indicadores Demográficos Básicos (IDB):** Operación sintética del INE que integra las fuentes anteriores para calcular los indicadores de estructura y crecimiento a escala nacional, autonómica y provincial.

---

## 2. Indicadores de Estructura Demográfica

### 2.1. Composición por Sexo

El sexo es una variable biológica clave. Nacen más hombres que mujeres (relación de masculinidad al nacer entre 104 y 106 varones por 100 mujeres), pero la sobremortalidad masculina a lo largo de todas las edades invierte esta relación en las edades avanzadas.

#### Ratio o Razón de Masculinidad ($RM_t$)
Mide el número de hombres por cada 100 mujeres a 1 de enero del año $t$:

$$RM_t = \frac{P_{hombres, t}}{P_{mujeres, t}} \cdot 100$$

#### Ratio de Feminidad ($RF_t$)
Es la inversa de la Ratio de Masculinidad:

$$RF_t = \frac{P_{mujeres, t}}{P_{hombres, t}} \cdot 100$$

> **Regla de Examen:** La proporción de hombres en la población total se calcula dividiendo el total de hombres entre la población total ($P_{hombres} / P_t$), mientras que la Ratio de Masculinidad relaciona hombres frente a mujeres ($P_{hombres} / P_{mujeres} \cdot 100$). No confundir proporción con razón/ratio.

---

### 2.2. Composición por Edad

La edad se maneja habitualmente como variable discreta expresada en **años cumplidos** (redondeo a la baja de la edad exacta). Para grupos quinquenales, la marca de clase es el punto medio del intervalo ($x + 0{,}5$ para edades simples).

```
┌────────────────────────────────────────────────────────────────────────┐
│                   GRANDES GRUPOS DE EDAD FUNCIONAL                     │
├──────────────────────────┬──────────────────────────┬──────────────────┤
│ Jóvenes (0 - 15 años)    │ Activos (16 - 64 años)   │ Mayores (65+)    │
│ Población Potenc. Inact. │ Potencialmente Activos   │ Potenc. Inactiva │
└──────────────────────────┴──────────────────────────┴──────────────────┘
```

#### A) Edad Media de la Población ($EMedia_t$)
Promedio aritmético de las edades de los individuos a 1 de enero del año $t$. Al trabajar con edades cumplidas simples, la marca de clase es $x + 0{,}5$:

$$EMedia_t = \frac{\sum_{x} (x + 0{,}5) \cdot P_{x,t}}{\sum_{x} P_{x,t}}$$

Donde $x$ es la edad cumplida y $P_{x,t}$ es la población de edad cumplida $x$ a 1 de enero del año $t$.

#### B) Edad Mediana de la Población ($EMediana_t$)
Edad exacta que divide a la distribución poblacional en dos grupos numéricamente iguales (el 50% tiene una edad menor o igual y el otro 50% una edad mayor o igual):

$$EMediana_t = EDAD_{med,t} + \frac{(P_t / 2) - P_{[0, med-1],t}}{P_{med,t}}$$

Donde:
* $EDAD_{med,t}$: Edad en años cumplidos en la que se alcanza o supera la mitad de la población.
* $P_t$: Población total a 1 de enero del año $t$.
* $P_{[0, med-1],t}$: Población acumulada con edad cumplida estrictamente inferior a $EDAD_{med,t}$.
* $P_{med,t}$: Población con edad cumplida igual a $EDAD_{med,t}$.

> **Regla de Examen:** En la población española, la **Edad Mediana** se mantuvo históricamente por debajo de la **Edad Media**, pero debido al intenso envejecimiento por la base y la cúspide, la Edad Mediana creció más rápidamente y **superó a la Edad Media a partir del año 2016**.

#### C) Proporción de Mayores e Índice de Envejecimiento

* **Proporción de Personas Mayores ($PROP_{x+,t}$):**

$$PROP_{x+,t} = \frac{P_{x+,t}}{P_t} \cdot 100 \quad (x = 65, 70, \dots, 85+)$$

* **Índice de Envejecimiento ($IE_t$):** Porcentaje que representa la población de 65 y más años sobre la población menor de 16 años a 1 de enero del año $t$:

$$IE_t = \frac{P_{65+,t}}{P_{0-15,t}} \cdot 100$$

#### D) Tasas de Dependencia Demográfica

Miden la relación cuantitativa entre la población potencialmente inactiva por razón de edad y la población potencialmente activa (16 a 64 años):

* **Tasa de Dependencia Global ($TD_t$):**

$$TD_t = \frac{P_{0-15,t} + P_{65+,t}}{P_{16-64,t}} \cdot 100$$

* **Tasa de Dependencia de Jóvenes ($TD_{jov,t}$):**

$$TD_{jov,t} = \frac{P_{0-15,t}}{P_{16-64,t}} \cdot 100$$

* **Tasa de Dependencia de Mayores ($TD_{may,t}$):**

$$TD_{may,t} = \frac{P_{65+,t}}{P_{16-64,t}} \cdot 100$$

$$\text{Propiedad aditiva:} \quad TD_t = TD_{jov,t} + TD_{may,t}$$

---

### 2.3. Composición por Nacionalidad y Lugar de Nacimiento

* **Proporción de Población Nacida en el Extranjero:**

$$PROP_{nacido\_ext, t} = \frac{P_{nacido\_ext, t}}{P_t} \cdot 100$$

* **Proporción de Población Extranjera (Nacionalidad):**

$$PROP_{ext, t} = \frac{P_{ext, t}}{P_t} \cdot 100$$

---

## 3. Pirámides de Población

### 3.1. Definición y Reglas de Construcción

La pirámide de población es una representación gráfica formada por dos histogramas de barras horizontales superpuestos y contrapuestos:
* **Eje Vertical (Ordenadas):** Edades cumplidas (año a año) o grupos de edad (quinquenales).
* **Eje Horizontal (Abscisas):** Efectivos de población (en valores absolutos o relativos/porcentajes sobre el total).
* **Convención:** Hombres a la **izquierda** (azul/oscuro) y Mujeres a la **derecha** (rojo/claro).
* Al construirla a 1 de enero, cada barra horizontal coincide exactamente con una **cohorte o generación de nacimiento** ($g = t - x$).

<div class="my-6 flex justify-center not-prose">
<svg viewBox="0 0 500 320" class="w-full max-w-md bg-white rounded-xl border border-slate-200 p-4 shadow-sm" xmlns="http://www.w3.org/2000/svg">
  <!-- Title -->
  <text x="250" y="22" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="13" fill="#1e293b">Tipología de Pirámides de Población</text>
  
  <!-- Pyramid 1: Expansiva (Pagoda) -->
  <g transform="translate(10, 45)">
    <text x="65" y="15" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="10" fill="#0369a1">Expansiva (Pagoda)</text>
    <!-- Left (Men) -->
    <path d="M 65 30 L 65 180 L 10 180 Z" fill="#38bdf8" opacity="0.8"/>
    <!-- Right (Women) -->
    <path d="M 65 30 L 65 180 L 120 180 Z" fill="#f43f5e" opacity="0.8"/>
    <line x1="65" y1="30" x2="65" y2="185" stroke="#475569" stroke-width="1.5"/>
    <text x="65" y="200" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#475569">Alta natalidad</text>
    <text x="65" y="212" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#64748b">Países en desarrollo</text>
  </g>

  <!-- Pyramid 2: Estacionaria (Campana) -->
  <g transform="translate(175, 45)">
    <text x="65" y="15" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="10" fill="#0f766e">Estacionaria (Campana)</text>
    <!-- Left -->
    <path d="M 65 30 C 50 70 30 130 25 180 L 65 180 Z" fill="#2dd4bf" opacity="0.8"/>
    <!-- Right -->
    <path d="M 65 30 C 80 70 100 130 105 180 L 65 180 Z" fill="#fb7185" opacity="0.8"/>
    <line x1="65" y1="30" x2="65" y2="185" stroke="#475569" stroke-width="1.5"/>
    <text x="65" y="200" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#475569">Natalidad estable</text>
    <text x="65" y="212" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#64748b">Poblaciones maduras</text>
  </g>

  <!-- Pyramid 3: Regresiva (Bulbo) -->
  <g transform="translate(340, 45)">
    <text x="65" y="15" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="10" fill="#b91c1c">Regresiva (Bulbo)</text>
    <!-- Left -->
    <path d="M 65 30 C 40 80 20 110 45 180 L 65 180 Z" fill="#818cf8" opacity="0.8"/>
    <!-- Right -->
    <path d="M 65 30 C 90 80 110 110 85 180 L 65 180 Z" fill="#f43f5e" opacity="0.8"/>
    <line x1="65" y1="30" x2="65" y2="185" stroke="#475569" stroke-width="1.5"/>
    <text x="65" y="200" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#475569">Base estrecha</text>
    <text x="65" y="212" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#64748b">Países desarrollados</text>
  </g>

  <!-- Base Label -->
  <rect x="50" y="260" width="400" height="35" rx="6" fill="#f8fafc" stroke="#cbd5e1"/>
  <text x="250" y="281" text-anchor="middle" font-family="sans-serif" font-size="10" font-weight="semibold" fill="#334155">Perfil Población Española Actual: Regresiva (Bulbo / Urna)</text>
</svg>
</div>

### 3.2. Clasificación Tipológica de Pirámides

1. **Expansiva o Pagoda:** Base ancha y rápida reducción hacia la cúspide. Propia de poblaciones jóvenes con alta natalidad y alta mortalidad.
2. **Estacionaria o Campana:** Base moderada y mortalidad concentrada en edades avanzadas. Mantenimiento del reemplazo generacional.
3. **Regresiva, Bulbo o Urna:** Base estrecha (denota denatalidad) y abultamiento en las edades centrales y avanzadas. Población envejecida.

### 3.3. Huellas Históricas en la Pirámide de España

La pirámide española refleja eventos históricos clave que han afectado a cohortes específicas:
* **Guerra Civil Española (1936-1939):**
  * Sobremortalidad en varones nacidos entre 1911 y 1921 (combatientes).
  * Caída estrecha de nacimientos durante la guerra y posguerra inmediata (generaciones de **1937 a 1942**), destacando la base mínima del año **1940** ("hueco de la generación vacía").
* **Baby-Boom Español (1958-1977):** Abultamiento central máximo de la pirámide (actuales cohortes de 45 a 65 años).
* **Eco del Baby-Boom y Repunte Migratorio (2000-2008):** Incremento de nacimientos observable en la cohorte de 2008.

---

## 4. Indicadores y Tasas de Crecimiento Demográfico

### 4.1. La Ecuación Compensadora del Crecimiento

El tamaño de una población en el año $t+1$ es el resultado del balance de entradas (nacimientos $N_t$ e inmigraciones $I_t$) y salidas (defunciones $D_t$ y emigraciones $E_t$):

$$P_{t+1} = P_t + N_t - D_t + I_t - E_t$$

$$\text{Saldo Vegetativo (Natural):} \quad SV_t = N_t - D_t$$

$$\text{Saldo Migratorio:} \quad SM_t = I_t - E_t$$

$$\text{Crecimiento Total Absoluto:} \quad CT_t = SV_t + SM_t = P_{t+1} - P_t$$

---

### 4.2. Tasas Relativas de Crecimiento (por 1.000 habitantes)

Para comparar poblaciones de distinto tamaño, los indicadores se refieren a la **Población Media del periodo** ($P_{01-07-t}$, estimación del INE a 1 de julio):

#### A) Tasa de Crecimiento Natural / Saldo Vegetativo por 1.000 hab. ($TCN_t$)

$$TCN_t = \frac{N_t - D_t}{P_{01-07-t}} \cdot 1000 = TBN_t - TBM_t$$

#### B) Saldo Migratorio por 1.000 hab. / Tasa de Migración Neta ($SM_{1000,t}$)

$$SM_{1000,t} = \frac{I_t - E_t}{P_{01-07-t}} \cdot 1000 = TBI_t - TBE_t$$

#### C) Crecimiento de la Población por 1.000 hab. ($CT_{1000,t}$)

$$CT_{1000,t} = \frac{P_{01-01-(t+1)} - P_{01-01-t}}{P_{01-07-t}} \cdot 1000 = TCN_t + SM_{1000,t}$$

#### D) Nacidos por 1.000 Defunciones ($RND_t$)

$$RND_t = \frac{N_t}{D_t} \cdot 1000$$

> **Regla de Examen:** Cuando $RND_t > 1000$, la población presenta un saldo vegetativo positivo ($N_t > D_t$). Si $RND_t < 1000$, la población se encuentra en decrecimiento natural o vegetativo negativo.

---

## 5. El Envejecimiento Demográfico

El envejecimiento es un proceso estructural derivado de dos fuerzas actuando simultáneamente:

```
┌────────────────────────────────────────────────────────────────────────┐
│                   DOBLE DIMENSIÓN DEL ENVEJECIMIENTO                   │
├───────────────────────────────────┬────────────────────────────────────┤
│ ENVEJECIMIENTO POR LA BASE        │ ENVEJECIMIENTO POR LA CÚSPIDE      │
│ Caída de la natalidad y          │ Aumento de la esperanza de vida    │
│ fecundidad (menor % de jóvenes).  │ en edades avanzadas (crece % 65+). │
└───────────────────────────────────┴────────────────────────────────────┘
```

### Manifestaciones e Impacto Socioeconómico

1. **Aumento de la Tasa de Dependencia de Mayores:** Incremento sostenido del cociente entre pensionistas/inactivos y población activa.
2. **Feminización de la Vejez:** Derivada de la sobremortalidad masculina, provocando mayores proporciones de mujeres en las edades centenarias ($85+$ años).
3. **Pérdida de Capacidad de Reemplazo Laboral:** Envejecimiento de la masa de trabajadores en edad productiva.

---

## 6. Modelos Teóricos: Población Estable y Población Estacionaria

En el análisis teórico demográfico se recurre a modelos matemáticos simplificados cerrados a la migración ($I = 0, E = 0$):

```
┌────────────────────────────────────────────────────────────────────────┐
│                   POBLACIÓN ESTABLE (Modelo Lotka)                     │
│  - Población cerrada a la migración.                                   │
│  - Pautas constantes de mortalidad y fecundidad por edad.              │
│  - Crecimiento a una tasa constante $r$ (nacimientos $N_t = N_0 e^{rt}$).│
│  - Estructura por edad INVARIABLE en el tiempo.                        │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
                                    │ Caso particular ($r = 0$)
                                    ▼
┌────────────────────────────────────────────────────────────────────────┐
│                   POBLACIÓN ESTACIONARIA                               │
│  - Tasa de crecimiento nula ($r = 0 \implies N = D$).                  │
│  - Cifra de nacimientos constante e igual a defunciones.               │
│  - Volumen total $P$ y estructura por edad CONSTANTES.                 │
│  - Coincide con la función $L_x$ de la Tabla de Mortalidad.            │
└────────────────────────────────────────────────────────────────────────┘
```

<div class="my-6 flex justify-center not-prose">
<svg viewBox="0 0 500 280" class="w-full max-w-md bg-white rounded-xl border border-slate-200 p-4 shadow-sm" xmlns="http://www.w3.org/2000/svg">
  <!-- Title -->
  <text x="250" y="22" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="13" fill="#1e293b">Comparación de Modelos Teóricos de Población</text>

  <!-- Stable Population -->
  <g transform="translate(30, 45)">
    <text x="90" y="15" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="11" fill="#0369a1">Población Estable (r > 0)</text>
    <!-- Left -->
    <path d="M 90 30 L 15 170 L 90 170 Z" fill="#38bdf8" opacity="0.75"/>
    <!-- Right -->
    <path d="M 90 30 L 165 170 L 90 170 Z" fill="#38bdf8" opacity="0.75"/>
    <line x1="90" y1="30" x2="90" y2="175" stroke="#0284c7" stroke-width="1.5"/>
    <text x="90" y="195" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#334155">Base piramidal triangular</text>
    <text x="90" y="208" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#64748b">Crecimiento constante $r$</text>
  </g>

  <!-- Stationary Population -->
  <g transform="translate(250, 45)">
    <text x="90" y="15" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="11" fill="#15803d">Población Estacionaria (r = 0)</text>
    <!-- Left -->
    <path d="M 90 30 C 40 40 30 120 30 170 L 90 170 Z" fill="#4ade80" opacity="0.75"/>
    <!-- Right -->
    <path d="M 90 30 C 140 40 150 120 150 170 L 90 170 Z" fill="#4ade80" opacity="0.75"/>
    <line x1="90" y1="30" x2="90" y2="175" stroke="#16a34a" stroke-width="1.5"/>
    <text x="90" y="195" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#334155">Perfil rectangular (Tabla $L_x$)</text>
    <text x="90" y="208" text-anchor="middle" font-family="sans-serif" font-size="8" fill="#64748b">Nacimientos = Defunciones</text>
  </g>
</svg>
</div>

### Relación Matemática Fundamental en la Población Estacionaria

En una población estacionaria, la Tasa Bruta de Natalidad ($n = N / P$) es exactamente igual a la Tasa Bruta de Mortalidad ($m = D / P$), y ambas equivalen a la inversa de la **esperanza de vida al nacer** ($e_0$):

$$e_0 = \frac{1}{n} = \frac{1}{m}$$

$$P = N \cdot e_0$$

Donde:
* $P$: Población total de la comunidad estacionaria.
* $N$: Nacimientos anuales constantes.
* $e_0$: Esperanza de vida al nacer derivada de la tabla de mortalidad.

---

## 7. Cuadro Comparativo de Síntesis

| Criterio | Población Estable | Población Estacionaria |
| :--- | :--- | :--- |
| **Crecimiento Natural ($r$)** | Tasa constante ($r \neq 0$, positiva o negativa). | Tasa estrictamente nula ($r = 0$). |
| **Balance de Vitalidad** | Nacimientos y defunciones varían a la misma tasa $r$. | Nacimientos iguales a defunciones ($N = D$). |
| **Volumen de Población ($P$)** | Cambia a tasa constante $r$. | Invariable en el tiempo. |
| **Estructura por Edad** | Invariable en el tiempo. | Invariable en el tiempo. |
| **Relación con la Tabla de Vida** | Regulada por ley de mortalidad y tasa $r$. | Coincide exactamente con la función $L_x$ y $e_0 = 1 / n$. |

---

> **Regla de Examen Final:** Recuerda las tres fórmulas indispensables del Tema 5:
> 1. **Ecuación Compensadora:** $P_{t+1} = P_t + (N_t - D_t) + (I_t - E_t)$
> 2. **Edad Media:** $EMedia_t = \frac{\sum (x + 0{,}5) \cdot P_{x,t}}{\sum P_{x,t}}$
> 3. **Población Estacionaria:** $P = N \cdot e_0 \iff e_0 = \frac{1}{n} = \frac{1}{m}$
