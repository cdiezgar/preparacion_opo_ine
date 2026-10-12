# Tema 40: Producto Interior Bruto (PIB): Vías de la Producción, el Gasto y las Rentas

**Asignatura / Bloque:** Bloque III. Economía y Cuentas Nacionales (Sub-bloque III.1 / III.2)  
**Cuerpo:** Cuerpo de Diplomados en Estadística del Estado (Subgrupo A2)  
**Marco Metodológico de Referencia:** Sistema Europeo de Cuentas Nacionales y Regionales (SEC 2010) — Instituto Nacional de Estadística (INE) / Eurostat  

---

## 1. Introducción y Marco Conceptual del SEC 2010

### 1.1. Definición Formal del PIB
El **Producto Interior Bruto (PIB)** es el agregado cuantitativo sintético fundamental de la Contabilidad Nacional. Mide el resultado final de la actividad de producción de las unidades productivas residentes en un territorio económico determinado durante un período de tiempo concreto (anual o trimestral).

Matemáticamente y contablemente representa la suma del valor monetario de todos los **bienes y servicios finales** producidos, evitando la doble contabilización de los bienes intermedios consumidos en el proceso.

### 1.2. El Significado del Término «Bruto»
En el lenguaje del SEC 2010, el término **Bruto** indica que el agregado de producción se calcula **sin deducir el Consumo de Capital Fijo ($CCF / P.51c$)**. 

* **Consumo de Capital Fijo ($CCF$):** Representa la cantidad de activo fijo consumido o depreciado durante el período considerado como resultado del desgaste normal, la obsolescencia previsible o los daños accidentales normales.
* **Transición a Términos Netos:**
  $$\text{Producto Interior Neto (PIN)} = \text{PIB} - CCF$$

### 1.3. Frontera de Producción y Principio de Residencia
* **Territorio Económico:** Espacio geográfico administrado por el gobierno nacional dentro del cual circulan libremente personas, bienes y capitales (incluye zonas francas, espacio aéreo, aguas territoriales y enclaves territoriales en el extranjero como embajadas y bases).
* **Unidad Institucional Residente:** Aquella unidad económica que mantiene un **centro de interés económico predominante** en el territorio económico del país, es decir, realiza actividades económicas durante un año o más.
* **Diferencia entre PIB y PNB (RNB):**
  * **PIB (Interior):** Mide la producción realizada **dentro de las fronteras** del territorio económico, independientemente de la nacionalidad de los factores de producción.
  * **PNB / RNB (Nacional):** Mide la renta generada por los **factores de producción nacionales / residentes**, independientemente de dónde estén ubicados geográficamente.
  $$\text{RNB} = \text{PIB} + \text{Rentas primarias recibidas del resto del mundo} - \text{Rentas primarias pagadas al resto del mundo}$$

### 1.4. La Identidad Contable Fundamental
En una economía cerrada o ajustada por el saldo exterior, existe una equivalencia estricta entre las tres dimensiones del flujo circular de la renta:

$$\text{Producción Total (VAB)} \equiv \text{Gasto Agregado (Demanda)} \equiv \text{Renta Agregada (Distribución)}$$

---

## 2. Principios de Valoración y Precios en el SEC 2010

El SEC 2010 establece dos niveles principales de valoración monetaria en función del agente contable y la fase de la transacción:

### 2.1. Precios Básicos ($pb$) vs. Precios de Adquisición ($pa$)

1. **Precio Básico ($pb$):** Es el precio recibido por el **productor** por unidad de un bien o servicio producido.
   * **INCLUYE:** Los costes directos de producción, la remuneración de factores y los *otros impuestos sobre la producción* ($D.29$) netos de *otras subvenciones a la producción* ($D.39$).
   * **EXCLUYE:** Los impuestos sobre los productos ($D.21$, como el IVA o impuestos especiales) y los márgenes de comercialización y transporte distribuidos por separado. Incluye las subvenciones sobre los productos ($D.31$).

2. **Precio de Adquisición ($pa$):** Es el precio efectivamente pagado por el **comprador o consumidor final**.
   * **Relación analítica:**
     $$\text{Precio de Adquisición} = \text{Precio Básico} + \text{Márgenes Comerciales y de Transporte} + \text{Impuestos s/ Productos } (D.21) - \text{Subvenciones s/ Productos } (D.31)$$

### 2.2. Clasificación de Impuestos y Subvenciones en el SEC 2010
* **Impuestos sobre la Producción e Importaciones ($D.2$):**
  * **Impuestos sobre los productos ($D.21$):** Impuestos pagables por unidad de bien o servicio (IVA $D.211$, impuestos sobre importaciones $D.212$, impuestos sobre productos excluidos IVA e importaciones $D.214$).
  * **Otros impuestos sobre la producción ($D.29$):** Impuestos independientes de la cantidad producida (IAE, IBI de inmuebles afectos a producción, licencias de actividad, impuesto sobre vehículos de empresa).
* **Subvenciones ($D.3$):**
  * **Subvenciones sobre los productos ($D.31$):** Pagos por unidad producida o importada.
  * **Otras subvenciones a la producción ($D.39$):** Ayudas no vinculadas a la cantidad (subvenciones a la contratación, fomento del empleo, tipo de interés).

### 2.3. Transición de PIB a Precios Básicos a PIB a Precios de Mercado ($PIB_{pm}$)
El Valor Añadido Bruto de las ramas de actividad se valora a precios básicos. Para obtener el $PIB$ a precios de mercado ($PIB_{pm}$), se deben añadir los impuestos netos sobre los productos de toda la economía:

$$PIB_{pm} = \sum VAB_{pb} + \text{Impuestos sobre los productos } (D.21) - \text{Subvenciones sobre los productos } (D.31)$$

---

## 3. Vía de la Producción (de la Oferta o del Valor Añadido)

Esta vía calcula el PIB agregando las aportaciones netas de cada rama de actividad productiva al valor total de la economía.

### 3.1. Ecuación Fundamental
$$PIB_{pm} = \sum_{k=1}^{N} VAB_{pb, k} + (D.21 - D.31)$$

### 3.2. Cálculo del Valor Añadido Bruto ($VAB_{pb}$)
El $VAB$ de cada rama $k$ se define como el saldo entre la producción total obtenida y los insumos intermedios consumidos en el proceso:

$$VAB_{pb} = \text{Producción a precios básicos } (P.1) - \text{Consumo Intermedio a precios de adquisición } (P.2)$$

### 3.3. Tipología de la Producción ($P.1$) en el SEC 2010
1. **Producción de Mercado ($P.11$):** Bienes y servicios vendidos o destinados a la venta a precios económicamente significativos (aquellos que cubren más del 50% de los costes de producción).
2. **Producción para Uso Final Propio ($P.12$):** Bienes y servicios que una unidad conserva para su propio consumo final (autoconsumo agrario) o para su propia formación bruta de capital fijo (software o construcción realizada por la propia empresa).
3. **Producción No de Mercado ($P.13$):** Servicios suministrados gratuitamente o a precios económicamente no significativos por las **Administraciones Públicas ($S.13$)** y las **Instituciones Sin Fines de Lucro al Servicio de los Hogares ($S.15$)**.
   * **Regla de Valoración de la Producción No de Mercado ($P.13$):** Al no existir precio de mercado, se valora **por la suma de sus costes de producción**:
     $$P.13 = \text{Consumo Intermedio } (P.2) + \text{Remuneración de Asalariados } (D.1) + \text{Consumo de Capital Fijo } (P.51c) + \text{Otros Impuestos netos s/ Producción } (D.29 - D.39)$$

### 3.4. Desagregación por Ramas de Actividad (CNAE-2009)
El INE presenta la vía de la producción estructurada según la Clasificación Nacional de Actividades Económicas:
* **Agricultura, ganadería, silvicultura y pesca** (Sección A)
* **Industria extractiva y manufacturera, energía y agua** (Secciones B a E)
* **Construcción** (Sección F)
* **Servicios** (Secciones G a T): Comercio, hostelería, transportes, información, actividades financieras, educación, sanidad, Administraciones Públicas.

---

## 4. Vía del Gasto (de la Demanda Agregada o del Destino)

Esta vía calcula el PIB sumando todos las utilizaciones finales de bienes y servicios realizadas por los agentes económicos residentes, más las exportaciones netas.

### 4.1. Ecuación Fundamental
$$PIB_{pm} = C + I + G + (X - M) = P.3 + P.5 + P.6 - P.7$$

### 4.2. Gasto en Consumo Final ($P.3$)
Comprende el gasto realizado por las unidades institucionales residentes en bienes y servicios destinados a la satisfacción directa de necesidades humanas individuales o colectivas.

* **Gasto en Consumo Final de los Hogares ($P.3$ Hogares):** Compras de bienes duraderos, no duraderos y servicios. *(Atención examen: excluye la compra de vivienda principal, que se considera Formación Bruta de Capital Fijo $P.51g$)*.
* **Gasto en Consumo Final de las ISFLSH ($P.3$ ISFLSH):** Valor de su producción no de mercado destinada a consumo individual de los hogares.
* **Gasto en Consumo Final de las AA.PP. ($P.3$ AA.PP.):** Se divide en:
  * **Consumo Individual:** Servicios prestados a hogares individualizables (sanidad, educación, servicios sociales).
  * **Consumo Colectivo:** Servicios prestados a la sociedad en su conjunto (defensa, justicia, seguridad ciudadana, diplomacia).

#### Distinción Teórica: Gasto en Consumo Final ($P.3$) vs. Consumo Final Efectivo ($P.4$)
* **Gasto en Consumo Final ($P.3$):** Mide quién **paga** el consumo.
* **Consumo Final Efectivo ($P.4$):** Mide quién **disfruta** el consumo.
* **Transferencias Sociales en Especie ($D.632$):** Bienes y servicios proporcionados por las AA.PP. e ISFLSH a los hogares de forma individual.
$$\text{Consumo Efectivo de los Hogares } (P.4) = P.3_{\text{Hogares}} + D.632$$
$$\text{Consumo Efectivo de las AA.PP. } (P.4) = P.3_{\text{AA.PP.}} - D.632_{\text{emitidas}}$$
$$\mathbf{P.3_{\text{Total}} \equiv P.4_{\text{Total}}}$$

### 4.3. Formación Bruta de Capital ($P.5$)
Representa la inversión bruta de la economía y se descompone en tres rúbricas:

1. **Formación Bruta de Capital Fijo ($P.51g$):** Valor de los activos fijos producidos (tangibles e intangibles) adquiridos por los productores residentes para ser utilizados en procesos de producción durante más de un año. Incluye: maquinaria, equipo de transporte, construcciones residenciales y no residenciales, I+D, programas informáticos y exploración minera.
2. **Variación de Existencias ($P.52$):** Valor de las entradas de existencias menos las salidas y las pérdidas de bienes mantenidos en stock (materias primas, productos en curso y productos terminados).
3. **Adquisiciones menos Cesiones de Objetos Valiosos ($P.53$):** Bienes no financieros que no se utilizan para la producción ni el consumo, sino que se mantienen como depósito de valor (obras de arte, joyas, metales preciosos).

### 4.4. Sector Exterior: Exportaciones ($P.6$) e Importaciones ($P.7$)
* **Exportaciones de Bienes y Servicios ($P.6$):** Operaciones por las cuales los residentes entregan bienes y servicios a no residentes.
* **Importaciones de Bienes y Servicios ($P.7$):** Operaciones por las cuales los no residentes entregan bienes y servicios a residentes.

#### Reglas de Valoración en la Balanza Exterior
* **En los Agregados Nacionales de la Vía del Gasto:** Tanto las exportaciones ($P.6$) como las importaciones ($P.7$) se valoran en frontera aduanera de exportación **FOB (Free On Board / Franco a Bordo)**.
* **En las Tablas de Origen y Destino (TOD) por productos:** Las importaciones se registran **CIF (Cost, Insurance, Freight)** y requieren un ajuste CIF/FOB global para alinearse con las cuentas nacionales agregadas.

### 4.5. Demanda Interna vs. Demanda Externa Neta
$$\text{Demanda Interna} = C + I + G = P.3 + P.5$$
$$\text{Demanda Externa Neta} = X - M = P.6 - P.7$$
$$PIB_{pm} = \text{Demanda Interna} + \text{Demanda Externa Neta}$$

---

## 5. Vía de la Renta (de la Distribución Primaria)

Esta vía calcula el PIB agregando las remuneraciones primarias pagadas a los factores de producción participantes en la actividad productiva dentro del territorio nacional.

### 5.1. Ecuación Fundamental
$$PIB_{pm} = D.1 + (EBE / RMB) + (D.29 - D.39) + (D.21 - D.31)$$

### 5.2. Remuneración de los Asalariados ($D.1$)
Comprende toda la retribución bruta, en efectivo o en especie, pagada por los empleadores a los trabajadores asalariados por el trabajo realizado.

* **Sueldos y Salarios ($D.11$):**
  * Salarios básicos, complementos, horas extraordinarias, gratificaciones, comisiones.
  * Valor de los bienes y servicios entregados gratuitamente o a precio reducido como retribución en especie (comedor, coche de empresa, vivienda).
* **Cotizaciones Sociales a cargo de los Empleadores ($D.12$):**
  * **Cotizaciones sociales efectivas ($D.121$):** Pagos realizados por empleadores a la Seguridad Social y mutuas.
  * **Cotizaciones sociales imputadas ($D.122$):** Valor de las prestaciones sociales pagadas directamente por las empresas a sus empleados sin intermediación de un fondo externo (p. ej., prestaciones por enfermedad a cargo del empleador).

### 5.3. Excedente Bruto de Explotación ($EBE / B.2g$) y Renta Mixta Bruta ($RMB / B.3g$)
Son los saldos contables que miden las rentas del capital y del trabajo no asalariado:

* **Excedente Bruto de Explotación ($EBE / B.2g$):** Renta residual del proceso de producción retenida por las sociedades no financieras ($S.11$), sociedades financieras ($S.12$), Administraciones Públicas ($S.13$) e ISFLSH ($S.15$). Corresponde a la remuneración del factor capital físico e intangible.
* **Renta Mixta Bruta ($RMB / B.3g$):** Renta obtenida por las empresas no constituidas en sociedad pertenecientes al sector de los **Hogares ($S.14$)** (autónomos, profesionales liberales, pequeños comerciantes). Se denomina *mixta* porque contiene de forma inseparable la remuneración del trabajo realizado por el propietario y los miembros de su familia, y el beneficio del empresario como propietario del capital.

### 5.4. Impuestos sobre la Producción e Importaciones Netos
1. **Otros impuestos sobre la producción netos de subvenciones ($D.29 - D.39$):** Se añaden para pasar del $VAB$ a coste de factores al $VAB$ a precios básicos.
2. **Impuestos sobre los productos netos de subvenciones ($D.21 - D.31$):** Se añaden para pasar de la suma de $VAB$ a precios básicos al $PIB$ a precios de mercado ($PIB_{pm}$).

---

## 6. Cuadro Sintético de Cuadre e Identidades del PIB en las TOD

En el marco de las **Tablas de Origen y Destino (TOD)** elaboradas por el INE, el PIB debe cuadrar exactamente por sus tres vías mediante las siguientes equivalencias:

| Vía de la Producción (Oferta) | Vía del Gasto (Demanda) | Vía de la Renta (Distribución) |
| :--- | :--- | :--- |
| $+ VAB_{pb}$ Agricultura, Pesca | $+ \text{Gasto Consumo Final Hogares } (P.3_H)$ | $+ \text{Remuneración Asalariados } (D.1)$ |
| $+ VAB_{pb}$ Industria y Energía | $+ \text{Gasto Consumo Final AA.PP. } (P.3_{AP})$ | $+ \text{Sueldos y Salarios } (D.11)$ |
| $+ VAB_{pb}$ Construcción | $+ \text{Gasto Consumo Final ISFLSH } (P.3_{ISFLSH})$ | $+ \text{Cotizaciones Sociales Empleadores } (D.12)$ |
| $+ VAB_{pb}$ Servicios | $+ \text{Formación Bruta Capital Fijo } (P.51g)$ | $+ \text{Excedente Bruto Explotación } (EBE / B.2g)$ |
| | $+ \text{Variación Existencias / Obj. Valiosos } (P.52+P.53)$ | $+ \text{Renta Mixta Bruta } (RMB / B.3g)$ |
| **$= \sum VAB_{pb}$ (a precios básicos)** | **$= \text{Demanda Interna Total}$** | $+ \text{Otros Impuestos netos s/ Producción } (D.29-D.39)$ |
| | | **$= \text{VAB a Precios Básicos}$** |
| $+ \text{Impuestos s/ Productos } (D.21)$ | $+ \text{Exportaciones de Bienes y Serv. } (P.6)$ | $+ \text{Impuestos s/ Productos } (D.21)$ |
| $- \text{Subvenciones s/ Productos } (D.31)$ | $- \text{Importaciones de Bienes y Serv. } (P.7)$ | $- \text{Subvenciones s/ Productos } (D.31)$ |
| **$= \mathbf{PIB_{pm}}$** | **$= \mathbf{PIB_{pm}}$** | **$= \mathbf{PIB_{pm}}$** |

---

## 7. Medición a Precios Corrientes vs. Precios Constantes (Volumen Encadenado)

Para evaluar el crecimiento real de una economía independientemente del efecto de la inflación, el SEC 2010 distingue entre magnitudes nominales y en volumen.

### 7.1. PIB Nominal vs. PIB Real (Volumen Encadenado)
* **PIB Nominal (a precios corrientes):** Mide la producción del período $t$ valorada a los precios vigentes en el período $t$:
  $$V_t = \sum p_t \cdot q_t$$
  Acumula tanto el crecimiento real de la cantidad producida ($q$) como la variación de los precios ($p$).
* **PIB Real / en Volumen Encadenado:** Aísla la variación real de la producción. Siguiendo las directrices del SEC 2010, el INE utiliza el **método de los índices encadenados de volumen con año base móvil anterior** (referenciados a un año de referencia fijo, actualmente 2015 o 2020).

### 7.2. El Método de la Doble Deflación para el VAB Real
Para calcular el $VAB$ real de una rama de actividad, el SEC 2010 exige la aplicación de la **Doble Deflación**:
1. Se deflacta la **Producción a precios básicos ($P.1$)** utilizando el índice de precios de producción correspondiente ($IPP$).
2. Se deflacta el **Consumo Intermedio ($P.2$)** utilizando un índice de precios de los insumos o consumos intermedios.
3. El $VAB$ en volumen se obtiene como la diferencia directa:
   $$VAB_{\text{volumen}} = P.1_{\text{volumen}} - P.2_{\text{volumen}}$$

### 7.3. El Deflactor Implícito del PIB
Es el índice de precios implícito que resulta de comparar el PIB nominal con el PIB real. Mide la variación de precios de todos los bienes y servicios finales producidos en la economía.

$$\text{Deflactor del PIB}_t = \frac{PIB_{\text{Nominal}, t}}{PIB_{\text{Real}, t}} \times 100$$

#### Comparación de Examen: Deflactor del PIB vs. Índice de Precios de Consumo (IPC)
* **Estructura de Fórmula:** El Deflactor del PIB tiene una estructura ponderada de tipo **Paasche** (pondera según las cantidades producidas en el año corriente $t$), mientras que el IPC utiliza una estructura tipo **Laspeyres modificada** (ponderaciones fijas de la cesta de la compra del año base).
* **Cobertura de Bienes:** 
  * El **Deflactor del PIB** incluye solo los bienes y servicios producidos dentro del país (incluye bienes de inversión y exportaciones; excluye importaciones).
  * El **IPC** incluye únicamente los bienes y servicios consumidos por los hogares residentes (incluye bienes importados de consumo; excluye bienes de inversión y exportaciones).

---

## 8. Preguntas Frecuentes y Puntos Calientes de Examen (Test y Práctico)

###  Trampas Típicas en el 1.er Ejercicio (Test Teórico)
1. **Compra de Vivienda Habitual por un Hogar:** No es Consumo Final ($P.3$), sino Formación Bruta de Capital Fijo ($P.51g$). La compra de un vehículo por un particular sí es Consumo Final.
2. **Valoración de la Producción No de Mercado de las AA.PP.:** No tiene precio de mercado ni se valora por sus ventas. Se valora **por la suma de sus costes de producción** ($P.2 + D.1 + P.51c + D.29 \text{ netos}$).
3. **Consumo Final ($P.3$) vs. Consumo Efectivo ($P.4$):** Son idénticos a nivel de toda la economía ($P.3_{\text{Total}} \equiv P.4_{\text{Total}}$), pero difieren a nivel sectorial por las **Transferencias Sociales en Especie ($D.632$)**.
4. **Exportaciones e Importaciones en Cuentas Nacionales Agregadas:** Se valoran ambas **FOB/FOB**. Solo en las TOD por productos las importaciones se presentan **CIF**.
5. **Autónomos y Profesionales Liberales:** Su renta no va a Remuneración de Asalariados ($D.1$), sino a **Renta Mixta Bruta ($RMB / B.3g$)** dentro del sector Hogares ($S.14$).

### 📌 Claves para el 2.º Ejercicio (Práctico de Examen)
* En los supuestos contables, para pasar de $VAB$ a precios básicos a $PIB_{pm}$, **NUNCA** debes sumar los *otros impuestos sobre la producción* ($D.29$), porque ya están dentro del precios básico. Solo debes sumar los **impuestos sobre los productos ($D.21$) netos de subvenciones sobre productos ($D.31$)**.
* Recuerda la identidad contable para verificar tus ejercicios:
  $$\text{VAB}_{pb} + D.21 - D.31 = C + I + G + X - M = D.1 + EBE/RMB + D.29 - D.39 + D.21 - D.31$$
