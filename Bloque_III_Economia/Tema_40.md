# Tema 40: Producto Interior Bruto (PIB)
## Vías de la Producción, el Gasto y las Rentas en el Marco del SEC 2010

**Programa:** Oposiciones al Cuerpo de Diplomados en Estadística del Estado (Subgrupo A2)  
**Bloque:** Bloque III. Economía y Cuentas Nacionales  
**Referencia Metodológica:** Sistema Europeo de Cuentas Nacionales y Regionales (SEC 2010) / INE / Eurostat  

---

## 1. Marco Conceptual del SEC 2010

### 1.1 Definición Rigurosa del PIB
El **Producto Interior Bruto (PIB)** es la magnitud macroeconómica sintética central de la Contabilidad Nacional. Cuantifica el resultado final de la actividad productiva de las unidades institucionales residentes en el territorio económico de un país a lo largo de un período temporal determinado (trimestral o anual).

Se define como la suma del valor monetario de todos los **bienes y servicios finales** generados, excluyendo íntegramente los consumos intermedios para eludir el fenómeno de la doble imposición o duplicidad contable.

---

### 1.2 Significado de «Bruto» vs. «Neto» y Consumo de Capital Fijo ($CCF$)
En la terminología estandarizada del SEC 2010, el calificativo **Bruto** denota que el agregado no descuenta el desgaste del capital productivo:

$$
\begin{aligned}
PIN &= PIB - CCF \\
PIN_{pm} &= PIB_{pm} - P.51c
\end{aligned}
$$

#### Desglose de términos:
* **$PIN$ (Producto Interior Neto / $B.1b$):** Mide la producción neta disponible para el consumo o la ampliación real del stock de capital sin comprometer la capacidad productiva instalada.
* **$PIB$ (Producto Interior Bruto / $B.1g$):** Producción total antes de deducir depreciaciones.
* **$CCF$ o $P.51c$ (Consumo de Capital Fijo):** Valor de la depreciación o pérdida de valor que experimentan los activos fijos durante el ejercicio como consecuencia del desgaste físico normal, la obsolescencia técnica previsible o deterioros accidentales ordinarios.
  * *Punto clave de examen:* El $CCF$ **no** incluye la destrucción fortuita por catástrofes naturales, guerras ni la obsolescencia imprevista extraordinaria, las cuales se registran en la *Cuenta de otras variaciones del volumen de activos* ($K.1 / K.2$).

---

### 1.3 Territorio Económico, Residencia y Relación con la Renta Nacional Bruta ($RNB$)
* **Territorio Económico:** Ámbito geográfico tutelado por la administración central del Estado en el que circulan libremente personas, factores, bienes y servicios (abarca el espacio aéreo, aguas jurisdiccionales, enclaves en el exterior como embajadas, consulados y bases científicas, y zonas francas).
* **Unidad Institucional Residente:** Entidad que mantiene un **centro de interés económico predominante** en el territorio; es decir, realiza operaciones económicas significativas dentro del mismo durante un período igual o superior a un año.
* **Diferencia entre PIB (Criterio Territorial) y PNB / RNB (Criterio de Residencia):**

$$
\begin{aligned}
RNB &= PIB + RPRM - RPPM \\
B.5g &= B.1g + D.1_{\text{rec}} + D.4_{\text{rec}} - D.1_{\text{pag}} - D.4_{\text{pag}}
\end{aligned}
$$

#### Desglose de términos:
* **$RNB$ ($B.5g$):** Renta Nacional Bruta. Remuneración total percibida por los factores de producción residentes, con independencia del lugar geográfico donde hayan operado.
* **$RPRM$:** Rentas Primarias Recibidas del Resto del Mundo por factores de producción residentes (trabajo transfronterizo $D.1$ y rentas de la propiedad $D.4$: dividendos, intereses, rentas de la tierra).
* **$RPPM$:** Rentas Primarias Pagadas al Resto del Mundo a factores de producción no residentes que han operado en el territorio nacional.

---

### 1.4 La Identidad Contable Fundamental del Flujo Circular
En equilibrio contable cerrado o compensado con el exterior, las tres ópticas de estimación arrojan idéntico valor:

$$
\begin{aligned}
\text{Óptica de la Oferta} &\equiv \text{Óptica de la Demanda} \equiv \text{Óptica de la Renta} \\
\sum VAB_{pb} + (D.21 - D.31) &\equiv C + I + G + (X - M) \\
&\equiv D.1 + EBE/RMB + T_{\text{netos}}
\end{aligned}
$$

---

## 2. Niveles de Valoración y Estructura Impositiva

El SEC 2010 distingue tres escalones sucesivos de valoración monetaria para garantizar la coherencia entre las operaciones de los productores y las de los adquirentes finales.

```
  Coste de Factores (cf)
         + [Otros Impuestos sobre la Producción (D.29)]
         - [Otras Subvenciones a la Producción (D.39)]
  ======================================================
  = Precios Básicos (pb)   <--- Punto de partida de la PRODUCCIÓN
         + [Impuestos sobre los Productos (D.21)]
         - [Subvenciones sobre los Productos (D.31)]
         + [Márgenes Comerciales y de Transporte]
  ======================================================
  = Precios de Adquisición (pa / pm) <--- Valoración del GASTO FINAL
```

### 2.1 Ecuaciones de Conversión de Precios

$$
\begin{aligned}
VAB_{pb} &= VAB_{cf} + D.29 - D.39 \\
p_a &= p_b + M_{CT} + D.21 - D.31
\end{aligned}
$$

#### Desglose de términos:
* **$VAB_{cf}$ (Valor Añadido Bruto al Coste de Factores):** Retribución estricta de los factores directos de producción (trabajo y capital): $D.1 + EBE + RMB$.
* **$D.29$ (Otros Impuestos sobre la Producción):** Tributos obligatorios no vinculados a la cantidad o valor de los bienes producidos ni importados.
  * *Ejemplos:* Impuesto sobre Actividades Económicas (IAE), Impuesto sobre Bienes Inmuebles (IBI) de inmuebles afectos a la explotación, tasas por licencias de actividad, impuesto de matriculación de vehículos de empresa.
* **$D.39$ (Otras Subvenciones a la Producción):** Transferencias corrientes sin contrapartida que las Administraciones Públicas conceden a los productores sin vincularse al volumen producido.
  * *Ejemplos:* Subvenciones al fomento del empleo, ayudas a la contratación de colectivos vulnerables, bonificaciones en tipos de interés.
* **$p_b$ (Precio Básico):** Importe neto unitario que retiene el productor:
  * **Incluye:** Costes productivos directos y $(D.29 - D.39)$.
  * **Excluye:** Impuestos directos sobre el producto facturado ($D.21$) y costes de transporte o márgenes facturados por terceros.
* **$M_{CT}$:** Márgenes de comercio y transporte aplicados a lo largo de la cadena de distribución hasta la entrega al adquirente.
* **$D.21$ (Impuestos sobre los Productos):** Gravámenes monetarios que gravan cada unidad física o porcentaje del valor producido o vendido.
  * *Subconceptos:* IVA que grava los productos ($D.211$), impuestos sobre las importaciones ($D.212$, aranceles) e impuestos sobre productos excluidos IVA e importaciones ($D.214$: tabaco, hidrocarburos, alcohol, electricidad).
* **$D.31$ (Subvenciones sobre los Productos):** Ayudas por unidad física producida o importada (ej. subvenciones directas por litro de carburante o billete de transporte público).
* **$p_a$ (Precio de Adquisición / Precio de Mercado):** Coste monetario final desembolsado por el adquirente efectivo.

---

## 3. Vía de la Producción (Oferta o Valor Añadido)

Mide la aportación neta de cada unidad productiva agrupada en ramas homogéneas de actividad económica según la clasificación CNAE-2009.

### 3.1 Formulación Matemática

$$
\begin{aligned}
PIB_{pm} &= \sum_{k=1}^{N} VAB_{pb, k} + D.21 - D.31 \\
VAB_{pb, k} &= P.1_k - P.2_k
\end{aligned}
$$

#### Desglose de términos:
* **$PIB_{pm}$:** Producto Interior Bruto a precios de mercado.
* **$k$:** Índice que identifica cada una de las ramas productivas (Agricultura, Industria, Construcción, Servicios).
* **$VAB_{pb, k}$:** Valor Añadido Bruto de la rama $k$ valorado a precios básicos.
* **$P.1_k$ (Producción Total de la rama $k$ a precios básicos):** Valor global de los bienes y servicios elaborados por la rama durante el período contable.
* **$P.2_k$ (Consumo Intermedio de la rama $k$ a precios de adquisición):** Valor de los bienes y servicios consumidos, transformados o incorporados íntegramente durante el proceso productivo (materias primas, energía, suministros, servicios de consultoría o asesoría jurídica).

---

### 3.2 Tipos de Producción ($P.1$) y Regla de Valoración de Servicios No de Mercado
El SEC 2010 descompone la producción en tres categorías operativas:

1. **Producción de Mercado ($P.11$):** Bienes y servicios transaccionados a *precios económicamente significativos* (aquellos que cubren como mínimo el 50% de los costes de producción unitarios).
2. **Producción para Uso Final Propio ($P.12$):** Bienes o servicios que la unidad conserva para su propio consumo final (autoconsumo de agricultores) o para su propia formación bruta de capital fijo (software desarrollado internamente por la plantilla de la empresa, autopromoción inmobiliaria).
3. **Producción No de Mercado ($P.13$):** Servicios suministrados de forma gratuita o a precios simbólicos por las **Administraciones Públicas ($S.13$)** y las **Instituciones Sin Fines de Lucro al Servicio de los Hogares ($S.15$)** (sanidad pública, defensa, educación reglada gratuita).

#### Valoración de la Producción No de Mercado ($P.13$):
Al carecer de contrapartida de mercado directa, se computa sumando sus costes elementales de producción:

$$
\begin{aligned}
P.13 &= P.2 \\
&\quad + D.1 \\
&\quad + P.51c \\
&\quad + (D.29 - D.39)
\end{aligned}
$$

Donde:
* **$P.2$:** Consumos intermedios de la entidad pública o ISFLSH.
* **$D.1$:** Remuneración total de sus empleados y funcionarios.
* **$P.51c$:** Consumo de capital fijo de las instalaciones e infraestructuras públicas.
* **$D.29 - D.39$:** Otros impuestos netos sobre la producción soportados.
* *Atención Examen:* En el cálculo de $P.13$ **el Excedente Neto de Explotación ($ENE$) es contractualmente nulo** ($ENE = 0$), por lo que $EBE = P.51c$.

---

## 4. Vía del Gasto (Demanda Agregada)

Agrega los destinos finales que los agentes económicos dan a los bienes y servicios disponibles en el período, distinguiendo entre demanda interna y demanda externa neta.

### 4.1 Formulación Matemática

$$
\begin{aligned}
PIB_{pm} &= P.3 + P.5 + P.6 - P.7 \\
PIB_{pm} &= \underbrace{(P.3 + P.5)}_{\text{Demanda Interna}} + \underbrace{(P.6 - P.7)}_{\text{Demanda Externa Neta}}
\end{aligned}
$$

---

### 4.2 Desglose Pormenorizado del Gasto en Consumo Final ($P.3$)

$$
\begin{aligned}
P.3 &= P.3_{\text{Hogares}} \\
&\quad + P.3_{\text{ISFLSH}} \\
&\quad + P.3_{\text{AA.PP.}}
\end{aligned}
$$

#### Desglose de términos:
* **$P.3_{\text{Hogares}}$ (Gasto en Consumo Final de los Hogares):** Compras de bienes duraderos (automóviles, electrodomésticos), perecederos (alimentos) y servicios (ocio, hostelería, transporte).
  * *Alerta de Test:* **La compra de vivienda por un particular NO es consumo final ($P.3$)**; se contabiliza como Formación Bruta de Capital Fijo ($P.51g$). El gasto asociado a la vivienda habitual computado en $P.3$ son los alquileres reales pagados o los alquileres imputados para los propietarios ocupantes.
* **$P.3_{\text{ISFLSH}}$:** Servicios directos prestados sin contrapartida individual a los hogares por ONG, sindicatos, partidos políticos o fundaciones.
* **$P.3_{\text{AA.PP.}}$:** Consumo público dividido en:
  * *Consumo Individual:* Prestaciones sanitarias, educativas y asistenciales dirigidas a beneficiarios concretos.
  * *Consumo Colectivo:* Seguridad nacional, defensa exterior, justicia, infraestructuras legislativas.

#### La Correspondencia entre Gasto de Consumo ($P.3$) y Consumo Efectivo ($P.4$):
Mientras $P.3$ atiende a **quién financia** el consumo, $P.4$ identifica a **quién lo disfruta físicamente**:

$$
\begin{aligned}
P.4_{\text{Hogares}} &= P.3_{\text{Hogares}} + D.631 + D.632 \\
P.4_{\text{AA.PP.}} &= P.3_{\text{AA.PP.}} - (D.631 + D.632) \\
P.4_{\text{ISFLSH}} &= 0 \\
\mathbf{P.3_{\text{Total}}} &\equiv \mathbf{P.4_{\text{Total}}}
\end{aligned}
$$

Donde **$D.631 / D.632$** son las **Transferencias Sociales en Especie** (bienes y servicios de sanidad, educación y servicios sociales canalizados directamente a familias concretas por el Estado o ISFLSH).

---

### 4.3 Formación Bruta de Capital ($P.5$)

$$
\begin{aligned}
P.5 &= P.51g + P.52 + P.53
\end{aligned}
$$

#### Desglose de términos:
* **$P.51g$ (Formación Bruta de Capital Fijo - FBCF):** Activos tangibles e intangibles adquiridos por unidades productivas residentes para emplearlos reiteradamente en la actividad económica durante más de 1 año.
  * *Incluye:* Construcción residencial (viviendas), obra civil, maquinaria, equipo de transporte, I+D (capitalizada según SEC 2010), prospección minera, software y bases de datos, recursos biológicos cultivados.
* **$P.52$ (Variación de Existencias):** Saldo entre entradas, salidas y mermas en almacén:
  $$\Delta \text{Stock} = \text{Existencias Finales} - \text{Existencias Iniciales}$$
* **$P.53$ (Adquisiciones menos Cesiones de Objetos Valiosos):** Bienes conservados exclusivamente como depósito de valor intrínseco (oro amonedado no financiero, piedras preciosas, obras de arte y antigüedades).

---

### 4.4 Sector Exterior ($P.6$ y $P.7$) y la Regla FOB/CIF

$$
\begin{aligned}
\text{Saldo Exterior Neto} &= P.6 - P.7 \\
&= X_{\text{FOB}} - M_{\text{FOB}}
\end{aligned}
$$

* **$P.6$ (Exportaciones):** Entregas de bienes y servicios por residentes a no residentes. Se valoran siempre **FOB** (*Free On Board*: libres a bordo en la frontera del país exportador).
* **$P.7$ (Importaciones):** Entregas de no residentes a residentes. En el cuadro agregado del PIB se valoran en frontera aduanera **FOB**.
  * *Matiz analítico:* En las Tablas de Origen y Destino (TOD) por productos, las importaciones se recogen inicialmente valoradas a precios **CIF** (*Cost, Insurance, Freight*), requiriendo un ajuste global contable $(\text{Ajuste CIF/FOB})$ para concordar con la cifra macroeconómica oficial del PIB.

---

## 5. Vía de la Renta (Distribución Primaria)

Cuantifica los flujos de remuneración primaria generados en la actividad de producción y percibidos por los factores trabajo, capital y el sector público en calidad de autoridad tributaria.

### 5.1 Formulación Matemática

$$
\begin{aligned}
PIB_{pm} &= D.1 \\
&\quad + (EBE + RMB) \\
&\quad + (D.29 - D.39) \\
&\quad + (D.21 - D.31)
\end{aligned}
$$

Agrupando impuestos y subvenciones:

$$
\begin{aligned}
PIB_{pm} &= D.1 + EBE + RMB + D.2 - D.3
\end{aligned}
$$

---

### 5.2 Desglose de la Remuneración de Asalariados ($D.1$)

$$
\begin{aligned}
D.1 &= D.11 + D.12 \\
D.12 &= D.121 + D.122
\end{aligned}
$$

#### Desglose de términos:
* **$D.11$ (Sueldos y Salarios):** Retribución íntegra en dinero o en especie devengada por los trabajadores por cuenta ajena (salario base, pagas extraordinarias, incentivos, uso particular de vehículo de empresa, vales de comida, vivienda cedida).
* **$D.12$ (Cotizaciones Sociales a cargo de los Empleadores):**
  * **$D.121$ (Cotizaciones sociales efectivas):** Aportaciones empresariales obligatorias transferidas a los sistemas de Seguridad Social y regímenes mutualistas.
  * **$D.122$ (Cotizaciones sociales imputadas):** Contrapartida de prestaciones sociales directas asumidas por las empresas en favor de sus propios empleados sin intermediario asegurador (complementos salariales por incapacidad temporal a cargo directo del empleador).

---

### 5.3 Excedente Bruto de Explotación ($EBE / B.2g$) vs. Renta Mixta Bruta ($RMB / B.3g$)

* **$EBE$ ($B.2g$):** Excedente de explotación de las sociedades de capital (no financieras $S.11$ y financieras $S.12$), Administraciones Públicas ($S.13$) e ISFLSH ($S.15$). Mide la retribución del capital antes de impuestos sobre la renta y amortizaciones.
* **$RMB$ ($B.3g$):** Saldo correspondiente al sector institucional de los **Hogares ($S.14$)** derivado de actividades productivas como autónomos, negocios familiares y profesionales independientes.
  * *¿Por qué se llama «Mixta»?:* Porque fusiona de forma indisoluble dos componentes:
    1. La compensación por el **trabajo personal** aportado por el titular y su familia (análoga a $D.1$).
    2. El **beneficio del capital y riesgo empresarial** invertido en el negocio (análogo a $EBE$).

---

## 6. Cuadro de Correspondencias y Fórmulas de Enlace en las TOD

Para resolver supuestos prácticos de Contabilidad Nacional en el segundo ejercicio, debe manejarse con precisión la matriz de enlaces entre las tres vías:

```
  +--------------------------------------------------------------------------+
  |              VÍA DE LA PRODUCCIÓN (Oferta a precios básicos)             |
  |              VAB_pb = P.1 (pb) - P.2 (pa)                                |
  +--------------------------------------------------------------------------+
                                      |
                     + (D.21 - D.31) [Impuestos netos s/ productos]
                                      v
  +--------------------------------------------------------------------------+
  |                 PRODUCTO INTERIOR BRUTO (PIB a precios de mercado)       |
  +--------------------------------------------------------------------------+
          /                                                          \
         v                                                            v
+-------------------------------+                     +-------------------------------+
|     VÍA DEL GASTO (Demanda)   |                     |     VÍA DE LA RENTA (Costes)  |
|                               |                     |                               |
| C_final (P.3)                 |                     | Rem. Asalariados (D.1)        |
| + FBC (P.51g + P.52 + P.53)   |                     | + EBE / RMB (B.2g / B.3g)     |
| + Exportaciones (P.6 FOB)     |                     | + (D.29 - D.39)               |
| - Importaciones (P.7 FOB)     |                     | + (D.21 - D.31)               |
+-------------------------------+                     +-------------------------------+
```

### Tabla de Ajustes entre Agregados de Producción y Renta

| Desde el Agregado de Partida | Operación Contable Requerida | Se obtiene el Agregado Destino |
| :--- | :--- | :--- |
| **$VAB_{cf}$ (Coste Factores)** | $+ (D.29 - D.39)$ | **$= VAB_{pb}$ (Precios Básicos)** |
| **$VAB_{pb}$ (Precios Básicos)** | $+ (D.21 - D.31)$ | **$= PIB_{pm}$ (Precios Mercado)** |
| **$PIB_{pm}$ (Precios Mercado)** | $- P.51c \text{ }(CCF)$ | **$= PIN_{pm}$ (Interior Neto)** |
| **$PIB_{pm}$ (Interior)** | $+ RPRM - RPPM$ | **$= RNB_{pm}$ (Renta Nacional Bruta)** |
| **$RNB_{pm}$ (Renta Nacional Bruta)** | $+ TPRM - TPPM$ | **$= RNDB_{pm}$ (Renta Nac. Disp. Bruta)** |

*Nota sobre transferencias:* **$TPRM$** y **$TPPM$** corresponden a las Transferencias Corrientes recibidas y pagadas al Resto del Mundo ($D.7$: remesas de emigrantes, cooperación internacional, aportaciones al presupuesto comunitario).

---

## 7. Medición a Precios Corrientes vs. Precios Constantes (Volumen Encadenado)

### 7.1 Magnitudes Nominales vs. Reales

$$
\begin{aligned}
\text{PIB Nominal}_t &= \sum_{i} p_{i, t} \cdot q_{i, t} \\
\text{PIB Volumen Encadenado}_t &= \text{Índice Encadenado} \times \text{PIB Nominal}_{\text{año ref}}
\end{aligned}
$$

* **PIB Nominal:** Valora la producción corriente a los precios del mismo período $t$, incorporando conjuntamente el efecto cantidad y el efecto precio.
* **PIB en Volumen (SEC 2010):** El SEC 2010 erradica el antiguo método de base fija constante y prescribe el uso del **método de índices encadenados de volumen con base móvil anual** (con ponderaciones del año anterior $t-1$), extrapolados respecto a un año de referencia fijo (actualmente 2015 o 2020).

---

### 7.2 El Método de la Doble Deflación para el $VAB$ Real
Para evitar las distorsiones causadas por la evolución asimétrica de los precios de venta y de los insumos, el SEC 2010 establece de forma obligatoria el método de la **Doble Deflación** para calcular el $VAB$ en términos reales:

$$
\begin{aligned}
VAB_{t, \text{volumen}} &= P.1_{t, \text{volumen}} - P.2_{t, \text{volumen}} \\
&= \frac{P.1_{t, \text{nominal}}}{I_{P.1}} - \frac{P.2_{t, \text{nominal}}}{I_{P.2}}
\end{aligned}
$$

#### Procedimiento técnico:
1. Se deflacta la producción bruta ($P.1$) con el Índice de Precios de Producción ($IPP$) específico de la rama.
2. Se deflactan los consumos intermedios ($P.2$) con el índice específico de precios de aprovisionamiento o insumos.
3. El $VAB$ real es la resta directa de ambas series deflactadas, no la deflación del saldo nominal mediante un índice general.

---

### 7.3 Deflactor Implícito del PIB vs. IPC

$$
\begin{aligned}
\text{Deflactor del PIB}_t &= \frac{PIB_{\text{Nominal}, t}}{PIB_{\text{Real}, t}} \times 100
\end{aligned}
$$

```
                           MATRIZ COMPARATIVA DE PRECIOS
  +----------------------+---------------------------+---------------------------+
  | Criterio             | Deflactor del PIB         | IPC (Índice Precios Cons) |
  +----------------------+---------------------------+---------------------------+
  | Tipo de Índice       | Paasche implícito         | Laspeyres encadenado      |
  | Ponderaciones        | Móviles del año actual t  | Fijas de la cesta base    |
  | Cobertura bienes     | Toda la producción final  | Cesta de consumo familiar |
  | Bienes de inversión  | Sí incluidos (FBCF)       | No incluidos              |
  | Gasto público        | Sí incluido               | No incluido               |
  | Importaciones        | No incluidas (se restan)  | Sí incluidas si se consumen|
  +----------------------+---------------------------+---------------------------+
```

---

## 8. Guía de Resolución de Supuestos Prácticos de Examen

### 8.1 Supuesto Numérico Tipo 1: Cuadre del PIB por las Tres Vías

**Enunciado:**  
A partir de los siguientes datos macroeconómicos de un país correspondientes a un ejercicio anual:

* Producción total a precios básicos ($P.1$): $3.500$
* Consumos intermedios a precios de adquisición ($P.2$): $1.700$
* Gasto en consumo final de los hogares ($P.3_H$): $1.000$
* Gasto en consumo final de las AA.PP. ($P.3_{AP}$): $400$
* Formación bruta de capital fijo ($P.51g$): $350$
* Variación de existencias ($P.52$): $50$
* Exportaciones de bienes y servicios ($P.6$): $450$
* Importaciones de bienes y servicios ($P.7$): $300$
* Remuneración de asalariados ($D.1$): $950$
* Otros impuestos sobre la producción ($D.29$): $60$
* Otras subvenciones a la producción ($D.39$): $20$
* Impuestos sobre los productos ($D.21$): $180$
* Subvenciones sobre los productos ($D.31$): $30$

Calcular:
1. $PIB_{pm}$ por la vía de la producción.
2. $PIB_{pm}$ por la vía del gasto.
3. El valor residual del Excedente Bruto de Explotación más Renta Mixta ($EBE + RMB$) mediante la vía de la renta.

---

#### Solución analítica detallada:

**1. Vía de la Producción:**
$$
\begin{aligned}
VAB_{pb} &= P.1 - P.2 = 3.500 - 1.700 = 1.800 \\
PIB_{pm} &= VAB_{pb} + (D.21 - D.31) \\
PIB_{pm} &= 1.800 + (180 - 30) \\
PIB_{pm} &= 1.800 + 150 = 1.950
\end{aligned}
$$

**2. Vía del Gasto:**
$$
\begin{aligned}
\text{Consumo Final Total } (P.3) &= P.3_H + P.3_{AP} = 1.000 + 400 = 1.400 \\
\text{Formación Bruta de Capital } (P.5) &= P.51g + P.52 = 350 + 50 = 400 \\
\text{Demanda Interna} &= P.3 + P.5 = 1.400 + 400 = 1.800 \\
\text{Saldo Exterior Neto } (X - M) &= P.6 - P.7 = 450 - 300 = +150 \\
PIB_{pm} &= 1.800 + 150 = 1.950 \quad \text{(Coincidencia exacta)}
\end{aligned}
$$

**3. Vía de la Renta y despeje de ($EBE + RMB$):**
La formulación de la renta establece:
$$
\begin{aligned}
PIB_{pm} &= D.1 + (EBE + RMB) + (D.29 - D.39) + (D.21 - D.31)
\end{aligned}
$$

Sustituyendo los valores conocidos:
$$
\begin{aligned}
1.950 &= 950 + (EBE + RMB) + (60 - 20) + (180 - 30) \\
1.950 &= 950 + (EBE + RMB) + 40 + 150 \\
1.950 &= 1.140 + (EBE + RMB) \\
EBE + RMB &= 1.950 - 1.140 = 810
\end{aligned}
$$

---

### 8.2 Puntos Críticos y Trampas Recurrentes en el Examen Oficial

1. **Impuestos $D.29$ vs. $D.21$ en el paso a $PIB_{pm}$:**  
   * **Error común:** Sumar $(D.29 - D.39)$ al $VAB_{pb}$ para hallar el $PIB_{pm}$.  
   * **Corrección:** El $VAB_{pb}$ **ya contiene** los impuestos netos de la producción $(D.29 - D.39)$. Para llegar a $PIB_{pm}$ solo se añaden los impuestos netos sobre los productos:
   $$PIB_{pm} = VAB_{pb} + (D.21 - D.31)$$

2. **Diferencia entre $P.51g$ y Gastos Corrientes:**  
   Las compras de software, proyectos de I+D y adquisición de inmuebles residenciales son siempre **inversión** ($P.51g$), no consumo intermedio ($P.2$) ni consumo final ($P.3$).

3. **Cálculo de la Renta Nacional Disponible Bruta ($RNDB$):**  
   Recordar que las transferencias del exterior alteran la renta disponible, no el PIB:
   $$RNDB = RNB + \text{Transferencias corrientes netas con el exterior}$$