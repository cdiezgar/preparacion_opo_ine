# Tema 9. Fuentes Demográficas: Censo de Población, Padrón Municipal y MNP

---

## 1. Visión General y Clasificación de las Fuentes Demográficas

El análisis demográfico clasifica sus fuentes de información atendiendo a dos criterios fundamentales: la **naturaleza del dato** (stock frente a flujo) y la **finalidad institucional** (estadística frente a administrativa).

```
                    ┌─────────────────────────────────────────┐
                    │          FUENTES DEMOGRÁFICAS           │
                    └────────────────────┬────────────────────┘
                                         │
                 ┌───────────────────────┴───────────────────────┐
                 ▼                                               ▼
    ┌───────────────────────────┐                   ┌───────────────────────────┐
    │     MAGNITUDES STOCK      │                   │    MAGNITUDES DE FLUJO    │
    │      (Fotografía)         │                   │         (Vídeo)           │
    └────────────┬──────────────┘                   └────────────┬──────────────┘
                 │                                               │
      ┌──────────┴──────────┐                                    │
      ▼                     ▼                                    ▼
┌───────────┐         ┌───────────┐                        ┌───────────┐
│ CENSO DE  │         │  PADRÓN   │                        │    MNP    │
│POBLACIÓN  │         │MUNICIPAL  │                        │(HECHOS    │
│(Estadís.) │         │(Administ.)│                        │ VITALES)  │
└───────────┘         └───────────┘                        └───────────┘
```

### Clasificación Analítica

* **Magnitudes de Stock (Estáticas):** Miden el volumen y la estructura de la población en un instante temporal preciso (imagen fija).
  * **Censo de Población y Viviendas:** Fuente de naturaleza **estadística** sujeta al **secreto estadístico**.
  * **Padrón Municipal de Habitantes:** Registro de naturaleza **administrativa** de carácter público a nivel local.
* **Magnitudes de Flujo (Dinámicas):** Contabilizan la ocurrencia continua de acontecimientos o hechos demográficos durante un intervalo de tiempo (normalmente un año civil).
  * **Movimiento Natural de la Población (MNP):** Registra nacimientos, defunciones y matrimonios derivados del Registro Civil.

> **Regla de Examen:** La diferencia esencial entre Censo y Padrón estriba en su naturaleza jurídica. El Padrón es un **registro administrativo** regulado por la Ley de Bases del Régimen Local; el Censo es una **operación estadística** tutelada por la Ley de la Función Estadística Pública que garantiza el anonimato estricto.

---

## 2. El Censo de Población y Viviendas

### 2.1. Marco Legal, Objetivos y Periodicidad

* **Definición:** Es la operación estadística de mayor envergadura, complejidad y tradición de los institutos de estadística. Proporciona el **marco muestral** para la totalidad de las encuestas por muestreo a hogares.
* **Periodicidad:** Se realiza con carácter **decenal**.
  * En España, tras los antecedentes del Conde de Aranda (1768), Floridablanca (1787) y Godoy (1797), la serie oficial se inicia en **1857**. Desde 1900 se ejecutó en los años terminados en **0** hasta 1970, y desde 1981 en los años terminados en **1** (el Censo de 2021 fue el decimoctavo censo oficial).
* **Marco Internacional y Europeo:**
  * Sigue las directrices y recomendaciones del programa mundial de Censos de **Naciones Unidas**.
  * En el ámbito comunitario se rige por el **Reglamento (CE) 763/2008 del Parlamento Europeo y del Consejo**, que establece la obligatoriedad decenal y la homogeneidad de conceptos y metadatos en la Unión Europea.

### 2.2. Definiciones de Población de Referencia

Para adscribir la población a un territorio se aplican tres criterios conceptuales:

1. **Residencia Habitual (*Población de Jure* o de Derecho):**
   Criterio regulado por el Reglamento (CE) 763/2008. Se define como el lugar donde una persona pasa normalmente el período diario de descanso. Requiere cumplir una de las siguientes condiciones:
   * Haber residido ininterrumpidamente en el lugar al menos **12 meses** antes de la fecha de referencia.
   * Haber llegado al lugar en los **12 meses anteriores** con la **intención de permanecer en él al menos un año**.
2. **Población de Hecho (*De Facto*):**
   Conjunto de personas presentes en el ámbito territorial en el momento o noche de referencia, independientemente de si son residentes habituales o visitantes temporales.
3. **Residencia Legal o Registrada:**
   Criterio normativo recogido en el Reglamento europeo cuando no se pueden verificar empíricamente los plazos de 12 meses de permanencia, tomando como residencia la inscripción formal en el Padrón Municipal.

### 2.3. Evolución Metodológica del Censo en España

<div class="my-6 flex justify-center not-prose">
<svg viewBox="0 0 500 320" class="w-full max-w-md bg-white rounded-xl border border-slate-200 p-4 shadow-sm" xmlns="http://www.w3.org/2000/svg">
  <text x="250" y="24" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="14" fill="#1e293b">Evolución de los Modelos Censales en España</text>
  
  <rect x="20" y="50" width="130" height="90" rx="8" fill="#f1f5f9" stroke="#cbd5e1" stroke-width="2"/>
  <text x="85" y="72" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="11" fill="#0f172a">TRADICIONAL</text>
  <text x="85" y="88" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#475569">(Hasta 2001)</text>
  <text x="85" y="108" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#334155">Recuento exhaustivo</text>
  <text x="85" y="122" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#334155">Agentes censales</text>

  <rect x="185" y="50" width="130" height="90" rx="8" fill="#e0f2fe" stroke="#38bdf8" stroke-width="2"/>
  <text x="250" y="72" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="11" fill="#0369a1">MIXTO</text>
  <text x="250" y="88" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#0284c7">(Censo 2011)</text>
  <text x="250" y="108" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#0369a1">Fichero Precensal</text>
  <text x="250" y="122" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#0369a1">Encuesta del 9%</text>

  <rect x="350" y="50" width="130" height="90" rx="8" fill="#dcfce7" stroke="#4ade80" stroke-width="2"/>
  <text x="425" y="72" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="11" fill="#15803d">REGISTROS</text>
  <text x="425" y="88" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#16a34a">(2021 en adelante)</text>
  <text x="425" y="108" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#15803d">Padrón + Registros</text>
  <text x="425" y="122" text-anchor="middle" font-family="sans-serif" font-size="9" fill="#15803d">Encuesta ECEPOV 1%</text>

  <path d="M 150 95 L 185 95" stroke="#94a3b8" stroke-width="2" marker-end="url(#arrow)"/>
  <path d="M 315 95 L 350 95" stroke="#94a3b8" stroke-width="2" marker-end="url(#arrow)"/>

  <rect x="110" y="180" width="280" height="100" rx="10" fill="#f8fafc" stroke="#0284c7" stroke-width="2" stroke-dasharray="4"/>
  <text x="250" y="205" text-anchor="middle" font-family="sans-serif" font-weight="bold" font-size="12" fill="#0f172a">SISTEMA ACTUAL (Desde 2022)</text>
  <text x="250" y="230" text-anchor="middle" font-family="sans-serif" font-size="11" font-weight="semibold" fill="#0369a1">Registro Estadístico de Población y Viviendas</text>
  <text x="250" y="252" text-anchor="middle" font-family="sans-serif" font-size="10" fill="#64748b">Actualización continua sin censos decenales clásicos</text>

  <path d="M 425 140 L 425 160 L 250 160 L 250 180" stroke="#16a34a" stroke-width="2" fill="none"/>

  <defs>
    <marker id="arrow" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#94a3b8" />
    </marker>
  </defs>
</svg>
</div>

1. **Censos Tradicionales (hasta 2001):**
   Basados en un recorrido exhaustivo del territorio con agentes censales y cuestionarios cumplimentados en cada hogar.
2. **Censo de 2011 (Modelo Mixto):**
   * **Fichero Precensal:** Se elaboró a partir del Padrón Continuo cruzado con registros administrativos (Seguridad Social, Agencia Tributaria, DNI, MNP).
   * **Factor de Recuento:** Probabilidad de residencia asignada a cada registro:
     * $w_i = 1$: Residencia confirmada en registros (97% de los casos).
     * $w_i = 0$: Defunciones u homologaciones erróneas.
     * $w_i = 0{,}424$: Factor medio ponderado aplicado a la **población dudosa** (inferior al 3%, estimada estadísticamente mediante grupo de calibración).
   * **FCFP (Fichero Censal Final Ponderado):** Combinación del recuento con una encuesta dirigida al **9% de la población** para variables de detalle.
3. **Censo de 2021 (Basado Íntegramente en Registros):**
   * Eliminación del recuento directo por cuestionario.
   * **Esqueleto poblacional:** Padrón Municipal Continuo.
   * **Esqueleto de viviendas:** Base de datos de Catastro y Censo de Edificios 2011.
   * **Encuesta ECEPOV (1% de la población):** Encuesta sobre Características Esenciales de la Población y las Viviendas como estudio sociológico complementario para variables no registradas (lenguas, movilidad cotidiana, etc.).
   * Implanta a partir de **2022** el **Registro Estadístico de Población y Viviendas** de carácter continuo.

---

## 3. Clasificación Censal de Viviendas, Hogares y Edificios

El marco censal analiza de forma interconectada tres unidades básicas:

```
┌─────────────────────────────────────────────────────────────────────────┐
│                           EDIFICIO CENSAL                               │
│  (Se dejó de censar de forma específica en el Censo de 2021)            │
└────────────────────────────────────┬────────────────────────────────────┘
                                     │
           ┌─────────────────────────┴─────────────────────────┐
           ▼                                                   ▼
┌─────────────────────────────────────┐             ┌─────────────────────┐
│         VIVIENDAS FAMILIARES        │             │   ESTABLECIMIENTOS  │
└──────────────────┬──────────────────┘             │      COLECTIVOS     │
                   │                                │ (Residencias,       │
        ┌──────────┴──────────┐                     │  cuarteles, etc.)   │
        ▼                     ▼                     └─────────────────────┘
┌──────────────┐       ┌──────────────┐
│CONVENCIONALES│       │ ALOJAMIENTOS │
│(Principales, │       │  (Cuevas,    │
│Secundarias,  │       │  chabolas)   │
│ Vacías)      │       └──────────────┘
└──────────────┘
```

### 3.1. Tipología de Viviendas

* **Vivienda Familiar:** Edificación destinada a ser habitada por una o varias personas que no constituyen un colectivo.
  * **Convencionales:**
    * **Principal:** Vivienda que constituye la residencia habitual del hogar.
    * **Secundaria:** Destinada al uso ocasional o vacacional.
    * **Vacía:** Vivienda desocupada que permanece sin residentes habituales ni usos secundarios.
  * **Alojamientos (No convencionales):** Estructuras fijas o móviles (cuevas, chabolas, vagones, caravanas) ocupadas como residencia en la fecha censal.
* **Establecimientos Colectivos (Viviendas Colectivas):** Inmuebles donde reside un conjunto de personas sujetas a una autoridad o régimen común no familiar (residencias de ancianos, prisiones, cuarteles, conventos).

### 3.2. Concepto de Hogar

Se establecen dos aproximaciones conceptuales en la praxis estadística:
* **Hogar-Presupuesto:** Conjunto de personas que comparten una vivienda principal y ponen en común sus ingresos y gastos.
* **Hogar-Vivienda (Aproximación Censal):** Conjunto de personas que residen en la misma vivienda convencional principal o alojamiento, con independencia de la existencia de lazos familiares o independencia de presupuesto.

$$\text{Nº de Hogares Censales} = \text{Viviendas Convencionales Principales} + \text{Alojamientos Ocupados}$$

---

## 4. El Padrón Municipal de Habitantes

### 4.1. Naturaleza Jurídica y Padrón Continuo

* **Definición:** Es el registro administrativo donde constan los vecinos residentes en cada término municipal. Su formación y mantenimiento corresponde a los **Ayuntamientos**.
* **Gestión Coordinada (Padrón Continuo):** Desde la reforma legislativa de **1996**, el Instituto Nacional de Estadística (INE) coordina los padrones de todos los municipios españoles mediante un sistema informático continuo e integrado.
* **Evolución Histórica de la Regulación:**
  * Anteriormente, la actualización se realizaba mediante **Rectificaciones Padronales** anuales y **Renovaciones Padronales** quinquenales (la última renovación fue en **1986**).
  * Desde **1996**, el Padrón Continuo sustituye las renovaciones por modificaciones y cruces de datos en tiempo real.

### 4.2. Contenido Legal Mínimo

Por imperativo legal, la inscripción padronal únicamente contiene los datos personales estrictamente indispensables:

1. Nombre y apellidos.
2. Sexo.
3. Domicilio habitual.
4. Nacionalidad.
5. Lugar y fecha de nacimiento.
6. Número de DNI / NIE.
7. Nivel de instrucción o título académico básico.

### 4.3. Las Dos Series Oficiales de Población en España

Debido a la dualidad entre la norma administrativa y la cuantificación estadística, el INE publica dos series independientes:

| Dimensión / Propiedad | Cifras Oficiales de Población del Padrón Continuo | Cifras de Población (Serie Estadística) |
| :--- | :--- | :--- |
| **Origen del Dato** | Conteo directo de las inscripciones del Padrón Continuo. | Base censal actualizada con los flujos del MNP y de migraciones. |
| **Carácter Operativo** | Cifra legal y administrativa oficial de cada municipio a **1 de enero**. | Cifra científica ajustada para investigación sociodemográfica. |
| **Periodicidad** | Anual. | Semestral. |
| **Criterio Poblacional** | Población empadronada / registrada. | Residencia habitual real ajustada. |

---

## 5. El Movimiento Natural de la Población (MNP)

### 5.1. Definición y Hechos Vitales

El **Movimiento Natural de la Población** es la operación estadística encargada de registrar las variables de **flujo** que alteran la dinámica biológica y el estado civil de la población. 

Se elabora anualmente por el INE a partir de los boletines estadísticos de los **Registros Civiles**:
* **Nacimientos** (Fenómeno de la natalidad / fecundidad).
* **Defunciones** (Fenómeno de la mortalidad).
* **Matrimonios** (Fenómeno de la nupcialidad).

### 5.2. Integración en la Ecuación Compensadora

El MNP aporta el componente biológico a la **ecuación fundamental de la dinámica poblacional**:

$$P_t = P_0 + (N - D) + (I - E)$$

Donde:
* $P_t$: Población en el momento $t$.
* $P_0$: Población inicial en el momento $0$.
* $N$: Nacimientos ocurridos en el período (Flujo MNP).
* $D$: Defunciones ocurridas en el período (Flujo MNP).
* $I$: Inmigraciones (Flujo migratorio padronal/estimado).
* $E$: Emigraciones (Flujo migratorio padronal/estimado).

El **Saldo Vegetativo** o Crecimiento Natural ($S_v$) queda determinado por:

$$S_v = N - D$$

> **Regla de Examen:** Los acontecimientos del MNP constituyen los **numeradores** de las principales tasas demográficas (Tasa Bruta de Natalidad $TBN$, Tasa Bruta de Mortalidad $TBM$), mientras que los **denominadores** de stock (población media o a 1 de julio) proceden del Censo o Padrón.

---

## 6. Cuadro Comparativo de Síntesis

| Criterio | Censo de Población y Viviendas | Padrón Municipal de Habitantes | Movimiento Natural de la Población (MNP) |
| :--- | :--- | :--- | :--- |
| **Naturaleza** | Operación estadística. | Registro administrativo público. | Estadística de hechos vitales. |
| **Tipo de Magnitud** | Stock (Estructura puntual). | Stock (Gestión continua). | Flujo (Contabilización de eventos). |
| **Periodicidad** | Decenal (Ronda europea). | Actualización continua (Cifras a 1 de enero). | Continuo (Publicación anual). |
| **Garantía Jurídica** | Secreto estadístico (Anonimato). | Registro administrativo local público. | Registro Civil / Secreto estadístico. |
| **Desagregación** | Máxima profundidad (Sección censal, edificio, hogar). | Municipal, provincial y nacional. | Municipal, provincial y nacional. |
| **Unidad de Análisis** | Persona, vivienda, hogar y edificio. | Persona (Vecino del municipio). | Evento biológico/jurídico. |
