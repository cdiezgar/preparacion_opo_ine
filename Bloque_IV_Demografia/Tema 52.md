# Tema 1. Demografía y principios generales

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

* **Edad Cumplida ($x$):** Número entero de años completados por un individuo ($x \le \text{edad} < x+1$). En datos agrupados por edades simples, el intervalo continuo es $[x, x+1)$ y su marca de clase es $x + 0.5$.
* **Edad Exacta ($x$):** Momento puntual preciso en que una persona alcanza exactamente el aniversario de su nacimiento (ej. cumplir exactamente 18 años).
* **Cohorte:** Conjunto de individuos que experimentan un mismo suceso origen durante un período de tiempo idéntico (normalmente un año civil).
* **Generación:** Caso particular de cohorte en el que el suceso origen es el **nacimiento**. Relación matemática de la generación $g$:

$$g = t - x$$

Donde $t$ es el año de calendario y $x$ es la edad cumplida alcanzada durante dicho año.

---

## 3. El Esquema o Diagrama de Lexis

El **Diagrama de Lexis** (diseñado por Wilhelm Lexis, 1837-1914) es un plano cartesiano bidimensional que permite representar simultáneamente las dos coordenadas temporales de los fenómenos demográficos: el **tiempo cronológico ($t$)** en abscisas y la **duración o edad ($x$)** en ordenadas.

![Diagrama General de Lexis](data:image/svg+xml;utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20640%20380%22%20width%3D%22100%25%22%20style%3D%22background%3A%23ffffff%3Bborder-radius%3A8px%3Bborder%3A1px%20solid%20%23e2e8f0%22%3E%3Cdefs%3E%3Cmarker%20id%3D%22ah%22%20viewBox%3D%220%200%2010%2010%22%20refX%3D%228%22%20refY%3D%225%22%20markerWidth%3D%226%22%20markerHeight%3D%226%22%20orient%3D%22auto-start-reverse%22%3E%3Cpath%20d%3D%22M0%201L9%205L0%209z%22%20fill%3D%22%231e293b%22%2F%3E%3C%2Fmarker%3E%3C%2Fdefs%3E%3Ctext%20x%3D%22320%22%20y%3D%2228%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2215%22%20font-weight%3D%22bold%22%20fill%3D%22%230f172a%22%3EEsquema%20Fundamental%20de%20Lexis%3C%2Ftext%3E%3Cg%20stroke%3D%22%23e2e8f0%22%20stroke-width%3D%221%22%3E%3Cline%20x1%3D%22180%22%20y1%3D%2260%22%20x2%3D%22180%22%20y2%3D%22300%22%2F%3E%3Cline%20x1%3D%22290%22%20y1%3D%2260%22%20x2%3D%22290%22%20y2%3D%22300%22%2F%3E%3Cline%20x1%3D%22400%22%20y1%3D%2260%22%20x2%3D%22400%22%20y2%3D%22300%22%2F%3E%3Cline%20x1%3D%22510%22%20y1%3D%2260%22%20x2%3D%22510%22%20y2%3D%22300%22%2F%3E%3Cline%20x1%3D%2270%22%20y1%3D%22220%22%20x2%3D%22570%22%20y2%3D%22220%22%2F%3E%3Cline%20x1%3D%2270%22%20y1%3D%22140%22%20x2%3D%22570%22%20y2%3D%22140%22%2F%3E%3Cline%20x1%3D%2270%22%20y1%3D%2260%22%20x2%3D%22570%22%20y2%3D%2260%22%2F%3E%3C%2Fg%3E%3Cline%20x1%3D%2270%22%20y1%3D%22300%22%20x2%3D%22600%22%20y2%3D%22300%22%20stroke%3D%22%231e293b%22%20stroke-width%3D%222%22%20marker-end%3D%22url(%23ah)%22%2F%3E%3Cline%20x1%3D%2270%22%20y1%3D%22300%22%20x2%3D%2270%22%20y2%3D%2240%22%20stroke%3D%22%231e293b%22%20stroke-width%3D%222%22%20marker-end%3D%22url(%23ah)%22%2F%3E%3Ctext%20x%3D%22595%22%20y%3D%22325%22%20text-anchor%3D%22end%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20font-weight%3D%22bold%22%20fill%3D%22%23475569%22%3ETiempo%20cronol%C3%B3gico%20(t)%3C%2Ftext%3E%3Ctext%20x%3D%2260%22%20y%3D%2240%22%20text-anchor%3D%22end%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20font-weight%3D%22bold%22%20fill%3D%22%23475569%22%3EEdad%20(x)%3C%2Ftext%3E%3Ctext%20x%3D%22180%22%20y%3D%22320%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%231e293b%22%3E2021%3C%2Ftext%3E%3Ctext%20x%3D%22290%22%20y%3D%22320%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%231e293b%22%3E2022%3C%2Ftext%3E%3Ctext%20x%3D%22400%22%20y%3D%22320%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%231e293b%22%3E2023%3C%2Ftext%3E%3Ctext%20x%3D%22510%22%20y%3D%22320%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%231e293b%22%3E2024%3C%2Ftext%3E%3Ctext%20x%3D%2255%22%20y%3D%22304%22%20text-anchor%3D%22end%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%231e293b%22%3E0%3C%2Ftext%3E%3Ctext%20x%3D%2255%22%20y%3D%22224%22%20text-anchor%3D%22end%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%231e293b%22%3E1%3C%2Ftext%3E%3Ctext%20x%3D%2255%22%20y%3D%22144%22%20text-anchor%3D%22end%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%231e293b%22%3E2%3C%2Ftext%3E%3Ctext%20x%3D%2255%22%20y%3D%2264%22%20text-anchor%3D%22end%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%231e293b%22%3E3%3C%2Ftext%3E%3Cline%20x1%3D%22290%22%20y1%3D%2260%22%20x2%3D%22290%22%20y2%3D%22300%22%20stroke%3D%22%2310b981%22%20stroke-width%3D%223%22%2F%3E%3Ctext%20x%3D%22296%22%20y%3D%22185%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%23047857%22%3EIs%C3%B3crona%20(Stock%201%2F1%2F2022)%3C%2Ftext%3E%3Cline%20x1%3D%2270%22%20y1%3D%22220%22%20x2%3D%22510%22%20y2%3D%22220%22%20stroke%3D%22%23f59e0b%22%20stroke-width%3D%223%22%2F%3E%3Ctext%20x%3D%22120%22%20y%3D%22212%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%23b45309%22%3EL%C3%ADnea%20de%20Aniversario%20(Cumplir%201%20a%C3%B1o)%3C%2Ftext%3E%3Cline%20x1%3D%22235%22%20y1%3D%22300%22%20x2%3D%22475%22%20y2%3D%2260%22%20stroke%3D%22%232563eb%22%20stroke-width%3D%223%22%2F%3E%3Ccircle%20cx%3D%22235%22%20cy%3D%22300%22%20r%3D%225%22%20fill%3D%22%232563eb%22%2F%3E%3Ccircle%20cx%3D%22475%22%20cy%3D%2260%22%20r%3D%225%22%20fill%3D%22%23dc2626%22%2F%3E%3Ctext%20x%3D%22240%22%20y%3D%22292%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%231d4ed8%22%3ENacimiento%3C%2Ftext%3E%3Ctext%20x%3D%22485%22%20y%3D%2265%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%23b91c1c%22%3EDefunci%C3%B3n%3C%2Ftext%3E%3Ctext%20x%3D%22390%22%20y%3D%22135%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%232563eb%22%20transform%3D%22rotate(-45%2C390%2C135)%22%3EL%C3%ADnea%20de%20Vida%20(45%C2%B0)%3C%2Ftext%3E%3C%2Fsvg%3E)

### Elementos Geométricos del Diagrama

1. **Líneas de Vida (o de Supervivencia):** Segmentos rectilíneos orientados a $45^\circ$ respecto a los ejes (paralelos a la bisectriz).
   * Su punto inicial se sitúa en la abscisa correspondiente a la fecha de incorporación (nacimiento $x=0$ o inmigración).
   * Su punto final se sitúa en la coordenada $(t_d, x_d)$ correspondiente a la fecha y edad de salida (defunción o emigración).
2. **Isócronas (Líneas Verticales):** Rectas $t = \text{constante}$. Miden magnitudes **stock**: el número de líneas de vida que cortan la vertical representa la población viva en esa fecha exacta.
3. **Líneas de Aniversario (Líneas Horizontales):** Rectas $x = \text{constante}$. Miden un **flujo de aniversario (unidimensional)**: número de individuos que cumplen exactamente la edad $x$ a lo largo del tiempo.
4. **Líneas de Generación:** Franjas diagonales a $45^\circ$ delimitadas por las líneas de vida de las personas nacidas entre el 1 de enero y el 31 de diciembre de un mismo año.

> **Regla de Examen:** Las dos dimensiones temporales ($t$ y $x$) avanzan a la misma velocidad constante: transcurrir un año en el calendario implica cumplir exactamente un año más de edad. Por ello, las líneas de vida tienen siempre una **pendiente matemática exacta de $+1$ ($45^\circ$)**.

---

## 4. Recintos y Tipos de Flujo en el Diagrama de Lexis

Los acontecimientos demográficos de flujo se clasifican e integran dentro de cuatro figuras geométricas:

![Las Cuatro Formas Geométricas en Lexis](data:image/svg+xml;utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20700%20270%22%20width%3D%22100%25%22%20style%3D%22background%3A%23ffffff%3Bborder-radius%3A8px%3Bborder%3A1px%20solid%20%23e2e8f0%22%3E%3Ctext%20x%3D%22350%22%20y%3D%2224%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2214%22%20font-weight%3D%22bold%22%20fill%3D%22%230f172a%22%3EClasificaci%C3%B3n%20de%20Recintos%20y%20Flujos%20en%20Lexis%3C%2Ftext%3E%3C!--%201.%20Triangulos%20--%3E%3Cg%20transform%3D%22translate(25%2C45)%22%3E%3Crect%20x%3D%220%22%20y%3D%220%22%20width%3D%22145%22%20height%3D%22205%22%20rx%3D%226%22%20fill%3D%22%23f8fafc%22%20stroke%3D%22%23cbd5e1%22%2F%3E%3Ctext%20x%3D%2272%22%20y%3D%2222%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2212%22%20font-weight%3D%22bold%22%20fill%3D%22%231e293b%22%3E1.%20Tri%C3%A1ngulos%3C%2Ftext%3E%3Cpolygon%20points%3D%2230%2C45%20120%2C45%20120%2C135%22%20fill%3D%22%23fed7aa%22%20stroke%3D%22%23ea580c%22%20stroke-width%3D%221.5%22%2F%3E%3Cpolygon%20points%3D%2230%2C45%2030%2C135%20120%2C135%22%20fill%3D%22%23fef08a%22%20stroke%3D%22%23ca8a04%22%20stroke-width%3D%221.5%22%2F%3E%3Ctext%20x%3D%2295%22%20y%3D%2275%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%23c2410c%22%3ET_sup%3C%2Ftext%3E%3Ctext%20x%3D%2250%22%20y%3D%22115%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%23a16207%22%3ET_inf%3C%2Ftext%3E%3Ctext%20x%3D%2272%22%20y%3D%22160%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20fill%3D%22%23475569%22%3EGen.-Per%C3%ADodo-Edad%3C%2Ftext%3E%3Ctext%20x%3D%2272%22%20y%3D%22178%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%23ea580c%22%3EObservaci%C3%B3n%20Pura%3C%2Ftext%3E%3C%2Fg%3E%3C!--%202.%20Romboide%20--%3E%3Cg%20transform%3D%22translate(190%2C45)%22%3E%3Crect%20x%3D%220%22%20y%3D%220%22%20width%3D%22145%22%20height%3D%22205%22%20rx%3D%226%22%20fill%3D%22%23f8fafc%22%20stroke%3D%22%23cbd5e1%22%2F%3E%3Ctext%20x%3D%2272%22%20y%3D%2222%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2212%22%20font-weight%3D%22bold%22%20fill%3D%22%231e293b%22%3E2.%20Romboide%3C%2Ftext%3E%3Cpolygon%20points%3D%2230%2C135%2080%2C45%20125%2C45%2075%2C135%22%20fill%3D%22%23bbf7d0%22%20stroke%3D%22%2316a34a%22%20stroke-width%3D%221.5%22%2F%3E%3Cline%20x1%3D%2230%22%20y1%3D%2290%22%20x2%3D%22125%22%20y2%3D%2290%22%20stroke%3D%22%2315803d%22%20stroke-dasharray%3D%223%22%2F%3E%3Ctext%20x%3D%2272%22%20y%3D%22160%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20fill%3D%22%23475569%22%3ECohorte-Per%C3%ADodo%3C%2Ftext%3E%3Ctext%20x%3D%2272%22%20y%3D%22178%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%2316a34a%22%3EPerspectiva%20(1%20a%C3%B1o)%3C%2Ftext%3E%3C%2Fg%3E%3C!--%203.%20Inclinado%20--%3E%3Cg%20transform%3D%22translate(355%2C45)%22%3E%3Crect%20x%3D%220%22%20y%3D%220%22%20width%3D%22145%22%20height%3D%22205%22%20rx%3D%226%22%20fill%3D%22%23f8fafc%22%20stroke%3D%22%23cbd5e1%22%2F%3E%3Ctext%20x%3D%2272%22%20y%3D%2222%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2212%22%20font-weight%3D%22bold%22%20fill%3D%22%231e293b%22%3E3.%20Inclinado%3C%2Ftext%3E%3Cpolygon%20points%3D%2220%2C125%2065%2C50%20125%2C50%2080%2C125%22%20fill%3D%22%23ddd6fe%22%20stroke%3D%22%237c3aed%22%20stroke-width%3D%221.5%22%2F%3E%3Cline%20x1%3D%2265%22%20y1%3D%2250%22%20x2%3D%2265%22%20y2%3D%22125%22%20stroke%3D%22%236d28d9%22%20stroke-dasharray%3D%223%22%2F%3E%3Ctext%20x%3D%2272%22%20y%3D%22160%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20fill%3D%22%23475569%22%3ECohorte-Edad%3C%2Ftext%3E%3Ctext%20x%3D%2272%22%20y%3D%22178%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%237c3aed%22%3EBienio%20(t%20y%20t%2B1)%3C%2Ftext%3E%3C%2Fg%3E%3C!--%204.%20Cuadrado%20--%3E%3Cg%20transform%3D%22translate(520%2C45)%22%3E%3Crect%20x%3D%220%22%20y%3D%220%22%20width%3D%22145%22%20height%3D%22205%22%20rx%3D%226%22%20fill%3D%22%23f8fafc%22%20stroke%3D%22%23cbd5e1%22%2F%3E%3Ctext%20x%3D%2272%22%20y%3D%2222%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2212%22%20font-weight%3D%22bold%22%20fill%3D%22%231e293b%22%3E4.%20Cuadrado%3C%2Ftext%3E%3Crect%20x%3D%2225%22%20y%3D%2245%22%20width%3D%2295%22%20height%3D%2290%22%20fill%3D%22%23bae6fd%22%20stroke%3D%22%230284c7%22%20stroke-width%3D%221.5%22%2F%3E%3Cline%20x1%3D%2225%22%20y1%3D%2245%22%20x2%3D%22120%22%20y2%3D%22135%22%20stroke%3D%22%230369a1%22%20stroke-dasharray%3D%223%22%2F%3E%3Ctext%20x%3D%2272%22%20y%3D%22160%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20fill%3D%22%23475569%22%3EPer%C3%ADodo-Edad%3C%2Ftext%3E%3Ctext%20x%3D%2272%22%20y%3D%22178%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20font-weight%3D%22bold%22%20fill%3D%22%230284c7%22%3ETransversal%20(2%20cohortes)%3C%2Ftext%3E%3C%2Fg%3E%3C%2Fsvg%3E)

---

### Descripción Detallada y Ejemplos de las Cuatro Formas

#### Forma 1: Triángulo de Lexis (Observación Elemental / Pura)
* **Definición geométrica:** Superficie triangular delimitada por una isócrona, una línea de aniversario y una línea de vida.
* **Composición del cuadrado:** Todo cuadrado de período-edad $[t, t+1] \times [x, x+1]$ contiene dos triángulos:
  * **Triángulo Superior ($T_{\text{sup}}$):** Los sucesos ocurren a la generación anterior ($g = t - x - 1$). El individuo experimenta el evento **después de haber cumplido los años** en el calendario de ese año.
  * **Triángulo Inferior ($T_{\text{inf}}$):** Los sucesos ocurren a la generación más reciente ($g = t - x$). El individuo experimenta el evento **antes de su aniversario** en ese año.
* **Ejemplo Real:** Defunciones registradas durante el año **2023** a la edad de **20 años cumplidos**:
  * Nacidos en **2003** que fallecen en 2023 antes de cumplir los 21 años $\rightarrow$ **$T_{\text{inf}}$**.
  * Nacidos en **2002** que ya cumplieron los 20 en 2022 y fallecen en 2023 antes de cumplir los 21 $\rightarrow$ **$T_{\text{sup}}$**.

#### Forma 2: Romboide / Paralelogramo Vertical (Cohorte - Período)
* **Definición geométrica:** Paralelogramo delimitado verticalmente por las isócronas $t$ y $t+1$, y diagonalmente por las líneas de vida que marcan los extremos de una sola generación $g$.
* **Significado:** Observa a una única generación a lo largo de un año de calendario completo. Al inicio del año tienen edad cumplida $x-1$ y al final del año tienen edad cumplida $x$. Por tanto, el suceso ocurre en torno a la **edad exacta $x$** (edad media promedio $x.0$ años).
* **Ejemplo Real:** Estudiar a la generación nacida en el año **2000** durante el año **2023**:
  * Durante el primer tramo de 2023 tienen 22 años cumplidos.
  * Durante el segundo tramo de 2023 tienen 23 años cumplidos.
  * La edad media de los que sufren el evento en ese paralelogramo es de **23.0 años exactos**.

#### Forma 3: Paralelogramo Inclinado (Cohorte - Edad)
* **Definición geométrica:** Superficie delimitada horizontalmente por las líneas de aniversario $x$ y $x+1$, y diagonalmente por las líneas de vida de la cohorte.
* **Significado:** Sigue a una misma generación durante todo el tiempo en que sus miembros mantienen una edad cumplida específica $x$. Debido al avance temporal, este seguimiento exige observar **dos años de calendario consecutivos** ($t$ y $t+1$).
* **Ejemplo Real:** Seguir a los nacidos en **2000** exclusivamente mientras tienen **20 años cumplidos**:
  * Comienza el día en que cada miembro cumple exactamente 20 años (a lo largo de 2020).
  * Finaliza el día en que cumple 21 años (a lo largo de 2021).
  * La edad media al momento del evento es exactamente **$20.5$ años**.

#### Forma 4: Cuadrado de Lexis (Período - Edad / Transversal)
* **Definición geométrica:** Superficie delimitada por dos isócronas consecutivas ($t$ y $t+1$) y dos líneas de aniversario consecutivas ($x$ y $x+1$).
* **Significado:** Registra todos los acontecimientos ocurridos durante un año de calendario a personas que comparten una misma edad cumplida. Incluye a personas de **dos generaciones distintas**.
* **Ejemplo Real:** Total de personas fallecidas en España durante el año **2023** con **65 años cumplidos**:
  * Abarca a los nacidos en **1957** (que fallecieron antes de cumplir los 66).
  * Abarca a los nacidos en **1958** (que fallecieron tras cumplir los 65).

---

### Cuadro Resumen Comparativo de Recintos

| Figura Geométrica | Denominación del Flujo | Dimensiones Delimitadas | Edad Media Implícita | Cohortes Afectadas |
| :--- | :--- | :--- | :--- | :--- |
| **Triángulo** | Generación-Período-Edad | Período $t$, Edad $x$, Generación $g$ | $x + 0.33$ o $x + 0.67$ | 1 Cohorte |
| **Romboide** | Cohorte-Período (Perspectiva) | Período $t$, Generación $g$ | Edad exacta $x$ (Promedio $x$) | 1 Cohorte |
| **Inclinado** | Cohorte-Edad | Generación $g$, Edad cumplida $x$ | $x + 0.5$ años | 1 Cohorte (2 Años) |
| **Cuadrado** | Período-Edad (Transversal) | Período $t$, Edad cumplida $x$ | $x + 0.5$ años | 2 Cohortes |

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

![Perspectivas de Análisis Transversal y Longitudinal](data:image/svg+xml;utf8,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20viewBox%3D%220%200%20600%20300%22%20width%3D%22100%25%22%20style%3D%22background%3A%23ffffff%3Bborder-radius%3A8px%3Bborder%3A1px%20solid%20%23e2e8f0%22%3E%3Cdefs%3E%3Cmarker%20id%3D%22arr%22%20viewBox%3D%220%200%2010%2010%22%20refX%3D%228%22%20refY%3D%225%22%20markerWidth%3D%226%22%20markerHeight%3D%226%22%20orient%3D%22auto-start-reverse%22%3E%3Cpath%20d%3D%22M0%201L9%205L0%209z%22%20fill%3D%22%231e293b%22%2F%3E%3C%2Fmarker%3E%3C%2Fdefs%3E%3Ctext%20x%3D%22300%22%20y%3D%2226%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2214%22%20font-weight%3D%22bold%22%20fill%3D%22%230f172a%22%3EPerspectivas%20de%20An%C3%A1lisis%20en%20Lexis%3C%2Ftext%3E%3Cline%20x1%3D%2260%22%20y1%3D%22250%22%20x2%3D%22560%22%20y2%3D%22250%22%20stroke%3D%22%231e293b%22%20stroke-width%3D%222%22%20marker-end%3D%22url(%23arr)%22%2F%3E%3Cline%20x1%3D%2260%22%20y1%3D%22250%22%20x2%3D%2260%22%20y2%3D%2240%22%20stroke%3D%22%231e293b%22%20stroke-width%3D%222%22%20marker-end%3D%22url(%23arr)%22%2F%3E%3Ctext%20x%3D%22550%22%20y%3D%22272%22%20text-anchor%3D%22end%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%23475569%22%3ETiempo%20(t)%3C%2Ftext%3E%3Ctext%20x%3D%2250%22%20y%3D%2245%22%20text-anchor%3D%22end%22%20font-family%3D%22sans-serif%22%20font-size%3D%2211%22%20fill%3D%22%23475569%22%3EEdad%20(x)%3C%2Ftext%3E%3Crect%20x%3D%22110%22%20y%3D%2255%22%20width%3D%2265%22%20height%3D%22195%22%20fill%3D%22%23bbf7d0%22%20stroke%3D%22%2316a34a%22%20stroke-width%3D%222%22%2F%3E%3Ctext%20x%3D%22142%22%20y%3D%22155%22%20font-family%3D%22sans-serif%22%20font-weight%3D%22bold%22%20font-size%3D%2211%22%20fill%3D%22%2315803d%22%20text-anchor%3D%22middle%22%20transform%3D%22rotate(-90%2C142%2C155)%22%3EAN%C3%81LISIS%20TRANSVERSAL%3C%2Ftext%3E%3Cpolygon%20points%3D%22230%2C250%20295%2C250%20490%2C55%20425%2C55%22%20fill%3D%22%23bfdbfe%22%20stroke%3D%22%232563eb%22%20stroke-width%3D%222%22%2F%3E%3Ctext%20x%3D%22360%22%20y%3D%22150%22%20font-family%3D%22sans-serif%22%20font-weight%3D%22bold%22%20font-size%3D%2211%22%20fill%3D%22%231d4ed8%22%20text-anchor%3D%22middle%22%20transform%3D%22rotate(-45%2C360%2C150)%22%3EAN%C3%81LISIS%20LONGITUDINAL%3C%2Ftext%3E%3Ctext%20x%3D%22142%22%20y%3D%22268%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20fill%3D%22%2315803d%22%3EA%C3%B1o%20t%3C%2Ftext%3E%3Ctext%20x%3D%22262%22%20y%3D%22268%22%20text-anchor%3D%22middle%22%20font-family%3D%22sans-serif%22%20font-size%3D%2210%22%20fill%3D%22%231d4ed8%22%3ECohorte%20g%3C%2Ftext%3E%3C%2Fsvg%3E)

### 5.3. El Concepto de Cohorte Ficticia

Para obtener indicadores transversales sintéticos con significado interpretable (como el Indicador Coyuntural de Fecundidad o la Esperanza de Vida al Nacer), la demografía construye el modelo teórico de la **cohorte ficticia** (o generación hipotética):

> **Definición:** Una **cohorte ficticia** es una cohorte teórica sometida hipotéticamente a lo largo de toda su vida a las pautas y tasas específicas por edad observadas en una población real durante un único período transversal (un año o bienio).

---

## 6. Indicadores Demográficos: Tasas, Cocientes, Proporciones y Ratios

En demografía, las magnitudes absolutas (flujos y stocks) no permiten la comparación directa entre poblaciones de distinto tamaño. Se requiere el empleo de **medidas relativas**:

### 6.1. Definición de Tasa

Una **tasa** es un cociente que relaciona un flujo de sucesos demográficos ocurridos durante un período con la **población media expuesta al riesgo** durante dicho intervalo:

$$\text{Tasa}(t, t+1) = \frac{\text{Sucesos}(t, t+1)}{\text{Población Media}(t, t+1)}$$

* **Estimación de la Población Media:**
  * En la práctica oficial del INE, la población media se estima mediante la **población a mitad de período (1 de julio)**: $P_{01\text{-}07\text{-}t}$.
  * En su defecto, se calcula como la media aritmética simple de las poblaciones al inicio y fin de año:

$$\text{Población Media}(t, x) = \frac{P(t, x) + P(t+1, x)}{2}$$

* **Categorías de Tasas:**
  * **Tasas de $1.^{\mathrm{a}}$ Categoría:** Todos los componentes del denominador están expuestos a sufrir el suceso del numerador (ej. Tasa Bruta de Mortalidad).
  * **Tasas de $2.^{\mathrm{a}}$ Categoría:** En el denominador figuran individuos que no están expuestos a sufrir el suceso del numerador (ej. Tasa Bruta de Natalidad, donde la población total incluye hombres y ancianos).

### 6.2. Cocientes (Riesgos o Probabilidades)

En demografía formal, se define **cociente** como la división entre un flujo de sucesos y la **población inicial** del período de referencia ($P_t$), en lugar de la población media:

$$\text{Cociente}(t) = \frac{\text{Sucesos}(t, t+1)}{P_t}$$

Cuando es de $1.^{\mathrm{a}}$ categoría, el cociente mide la **probabilidad empírica** o **riesgo** de que los miembros de una cohorte experimenten el suceso (ej. el riesgo de muerte $q_x$ en las tablas de mortalidad).

### 6.3. Proporciones y Ratios (Razones)

* **Proporción:** Relación entre dos magnitudes de la misma naturaleza donde el numerador es un subconjunto del denominador:

$$\text{Proporción} = \frac{\text{Stock}_A}{\text{Stock}_{\text{Total}}} \quad (\text{rango } [0, 1] \text{ o } [0, 100\%])$$

* **Ratio o Razón:** Cociente entre dos subpoblaciones mutuamente excluyentes o disjuntas ($2.^{\mathrm{a}}$ categoría):

$$\text{Ratio de Masculinidad (RM)} = \frac{P_{\text{hombres}}}{P_{\text{mujeres}}} \times 100$$

### 6.4. Tasas Brutas frente a Tasas Específicas

* **Tasa Bruta:** Relaciona los sucesos totales con la población media total. Es una medida sintética influenciada fuertemente por la estructura por edad de la población.
* **Tasas Específicas:** Miden la intensidad del fenómeno en subgrupos homogéneos (desagregados por edad, sexo o cohorte).

### 6.5. Formulación Matemática de las Tasas Específicas en Lexis

#### a) Tasa Específica de Período-Edad (Transversal / Cuadrado)

Relaciona los sucesos $S(t,x)$ ocurridos en el año $t$ a personas con edad cumplida $x$ con la población media de esa misma edad:

$$m(t,x) = \frac{S(t,x)}{0.5 \cdot (P(t,x) + P(t+1,x))}$$

#### b) Tasa Específica de Período-Cohorte o Perspectiva (Romboide)

Relaciona los sucesos acaecidos en el año $t$ a los miembros de una misma generación $g$, divididos entre la población media de esa generación:

$$m(t,g) = \frac{S(t,x,g) + S(t,x+1,g)}{0.5 \cdot (P(t,x,g) + P(t+1,x+1,g))}$$

#### c) Tasa Específica de Cohorte-Edad (Inclinada / Bienio)

Relaciona los sucesos ocurridos a una generación $g$ al atravesar la edad cumplida $x$ durante dos años consecutivos ($t$ y $t+1$), divididos por la población al inicio del segundo año:

$$m(t,x,g) = \frac{S(t,x,g) + S(t+1,x,g)}{P(t+1,x)}$$

---

## 7. Caso Práctico Resuelto Completo (Ejemplo Oficial del INE)

A continuación se presenta la resolución completa del ejemplo numérico oficial sobre la integración de stocks, flujos y tasas en un esquema de Lexis:

### Datos de Partida (Sucesos y Stocks)

* **Poblaciones Iniciales a 01/01/2013:**
  * $P(2013, \text{edad } 0) = 453\,294$ (Generación 2012)
  * $P(2013, \text{edad } 1) = 475\,617$ (Generación 2011)
  * $P(2013, \text{edad } 2) = 481\,415$ (Generación 2010)
  * $P(2013, \text{edad } 3) = 492\,831$ (Generación 2009)
* **Nacimientos durante 2013:** $N(2013) = 424\,440$
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

$$P(2014, 0) = N(2013) - D + I - E = 424\,440 - 996 + 2\,170 - 733 = 424\,881$$

* **Población 1 año a 01/01/2014:**

$$P(2014, 1) = 453\,294 - (153 + 53) + (1\,966 + 1\,773) - (1\,534 + 2\,278) = 453\,015$$

* **Población 2 años a 01/01/2014:**

$$P(2014, 2) = 475\,617 - (50 + 42) + (1\,685 + 1\,613) - (3\,053 + 3\,118) = 472\,652$$

* **Población 3 años a 01/01/2014:**

$$P(2014, 3) = 481\,415 - (35 + 19) + (1\,750 + 1\,604) - (2\,716 + 2\,479) = 479\,520$$

#### 2. Cálculo de Aniversarios en 2013

* **Aniversario 1 año:** $453\,294 - 153 + 1\,966 - 1\,534 = 453\,573$
* **Aniversario 2 años:** $475\,617 - 50 + 1\,685 - 3\,053 = 474\,199$
* **Aniversario 3 años:** $481\,415 - 35 + 1\,750 - 2\,716 = 480\,414$

#### 3. Cálculo de Tasas de Mortalidad

* **a) Tasas Período-Edad para el año 2013 ($m_x^{2013}$):**

$$m_1^{2013} = \frac{50 + 53}{0.5 \cdot (475\,617 + 453\,015)} = \frac{103}{464\,316} = 0.0002218 \quad (0.22 \text{ por mil})$$

$$m_2^{2013} = \frac{35 + 42}{0.5 \cdot (481\,415 + 472\,652)} = \frac{77}{477\,033.5} = 0.0001614 \quad (0.16 \text{ por mil})$$

$$m_3^{2013} = \frac{29 + 19}{0.5 \cdot (492\,831 + 479\,520)} = \frac{48}{486\,175.5} = 0.0000987 \quad (0.10 \text{ por mil})$$

* **b) Tasas Período-Cohorte o Perspectivas para 2013 ($m_g^{2013}$):**

$$m_{2012}^{2013} = \frac{153 + 53}{0.5 \cdot (453\,294 + 453\,015)} = \frac{206}{453\,154.5} = 0.0004546 \quad (0.45 \text{ por mil})$$

$$m_{2011}^{2013} = \frac{50 + 42}{0.5 \cdot (475\,617 + 472\,652)} = \frac{92}{474\,134.5} = 0.0001940 \quad (0.19 \text{ por mil})$$

$$m_{2010}^{2013} = \frac{35 + 19}{0.5 \cdot (481\,415 + 479\,520)} = \frac{54}{480\,467.5} = 0.0001124 \quad (0.11 \text{ por mil})$$

* **c) Tasas Cohorte-Edad para el bienio 2013-2014 ($mge_x^{2013-2014}$):**

$$mge_1^{2013-2014} = \frac{53 + 42}{453\,015} = \frac{95}{453\,015} = 0.0002097 \quad (0.21 \text{ por mil})$$

$$mge_2^{2013-2014} = \frac{42 + 28}{472\,652} = \frac{70}{472\,652} = 0.0001481 \quad (0.15 \text{ por mil})$$

$$mge_3^{2013-2014} = \frac{19 + 23}{479\,520} = \frac{42}{479\,520} = 0.0000876 \quad (0.09 \text{ por mil})$$

---

💡 **Recomendación de estudio:** Tras dominar este tema conceptual y metodológico, estás preparado para abordar el estudio analítico de la **Mortalidad y Tablas de Vida (Tema 2 / Temas 53 y 54 Oficiales)**.