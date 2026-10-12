# Tema 39: Estructuras de Mercado y Fijación de Precios
## Temario de Oposiciones: Teoría Integral, Formulario Analítico y Banco de Supuestos Prácticos Resueltos

---

# PARTE I: DESARROLLO TEÓRICO INTEGRAL DEL TEMA 39

## 1. Introducción y Tipología de Mercados

### 1.1 Decisiones de la Empresa y Restricciones Operativas
Toda unidad económica de producción orienta su toma de decisiones bajo el axioma del comportamiento racional, persiguiendo la **maximización del beneficio económico** ($\Pi$), definido como la diferencia estricta entre el flujo de ingresos totales derivados de la venta de su producción y el coste de oportunidad total imputado a los factores empleados:

$$\max_{q \ge 0} \Pi(q) = IT(q) - CT(q) = p(q) \cdot q - CT(q)$$

Para resolver este programa de optimización, la empresa se halla sujeta a un conjunto tridimensional de restricciones:
1. **Restricciones tecnológicas:** Representadas analíticamente por la función de producción $q = f(K, L)$, determinan las combinaciones físicamente eficientes de factores productivos.
2. **Restricciones económicas (de costes):** Expresadas en la función de costes $CT(q) = \min_{K, L} \{rK + wL \text{ s.a. } f(K, L) \ge q\}$, resumen el gasto monetario mínimo necesario para cada nivel de producto dados los precios de los factores.
3. **Restricciones de mercado (de demanda):** Condensadas en la curva de demanda del mercado o en la demanda residual que percibe la empresa:
   * Si la empresa es precio-aceptante, el precio $p$ viene dado por el mercado y la cantidad que venda no alterará dicha cotización.
   * Si la empresa posee poder de mercado, enfrenta una curva con pendiente negativa ($p'(q) < 0$): fijar la cantidad producida determina el precio de liquidación, o fijar el precio determina la cantidad máxima que el mercado absorberá.

### 1.2 Clasificación Morfológica de Eucken
La taxonomía clásica de Walter Eucken clasifica las configuraciones de mercado combinando la pluralidad o concentración relativa de oferentes y demandantes:

| Estructura | Oferentes | Demandantes | Control sobre el Precio | Barreras de Entrada |
| :--- | :--- | :--- | :--- | :--- |
| **Competencia Perfecta** | Infinitos (Atomizados) | Infinitos (Atomizados) | Nulo (Precio-aceptantes) | Inexistentes |
| **Monopolio de Oferta** | Único | Infinitos | Pleno (Fijador de precio) | Infranqueables (legales/tecnológicas) |
| **Oligopolio de Oferta** | Reducido número | Infinitos | Interdependencia estratégica | Significativas |
| **Competencia Monopolística** | Elevado número | Infinitos | Limitado (diferenciación de marca)| Nulas o reducidas |
| **Monopsonio** | Infinitos | Único demandante | Pleno sobre el precio del factor | Específicas |
| **Monopolio Bilateral** | Único | Único demandante | Negociación y poder de regateo | Absolutas |

---

## 2. Competencia Perfecta

### 2.1 Hipótesis Fundamentales
* **Atomización del mercado:** La cuota de mercado de cada agente es infinitesimal respecto al volumen total transaccionado.
* **Homogeneidad del producto:** Bienes idénticos sin diferenciación objetiva ni subjetiva.
* **Información perfecta y simétrica:** Transparencia absoluta en precios, calidades y funciones de coste.
* **Perfecta movilidad factorial y libre concurrencia:** Ausencia de costes de transacción y libre entrada y salida de empresas.

### 2.2 Equilibrio a Corto Plazo
Al ser el precio un parámetro exógeno ($IMg = p$), la condición de primer orden para maximizar beneficios es:

$$\frac{d\Pi}{dq} = p - CMg(q) = 0 \implies p = CMg(q)$$

La condición de segundo orden exige que $\frac{d^2\Pi}{dq^2} = -CMg'(q) < 0 \implies CMg'(q) > 0$ (tramo estrictamente creciente).

#### Puntos Geométricos Críticos a Corto Plazo
* **Mínimo del Coste Variable Medio ($\min CVMe$): Punto de Cierre.**
  * Si $p < \min CVMe$: la empresa no puede cubrir siquiera sus costes variables operativos; operando perdería más que cerrando. La producción óptima es $q^* = 0$, asumiendo únicamente la pérdida del Coste Fijo ($CF$).
  * La **curva de oferta a corto plazo** de la empresa individual coincide con el tramo creciente del coste marginal a partir del mínimo del coste variable medio:
    $$s(p) = \{\, q \mid p = CMg(q) \text{ con } p \ge \min CVMe \,\}$$
* **Mínimo del Coste Total Medio ($\min CTMe$): Óptimo de Explotación / Beneficio Cero.**
  * Si $\min CVMe \le p < \min CTMe$: la empresa opera a pérdidas asumibles a corto plazo ($\Pi < 0$), pues cubre íntegramente sus costes variables y una fracción de sus costes fijos.
  * Si $p > \min CTMe$: la empresa percibe **beneficios económicos extraordinarios** ($\Pi > 0$).

### 2.3 Equilibrio a Largo Plazo y Eficiencia Asignativa
A largo plazo, la existencia de beneficios extraordinarios induce la entrada masiva de competidores, desplazando la curva de oferta agregada hacia la derecha y reduciendo el precio de equilibrio. El proceso se detiene cuando los beneficios económicos se anulan:

$$p^* = CMg(q^*) = \min CTMe(q^*) \implies \Pi^* = 0$$

Este equilibrio garantiza la **eficiencia asignativa** ($p = CMg$) y la **eficiencia productiva** (producción en el mínimo de los costes medios a largo plazo), maximizando el excedente social agregado ($ET = EC + EP$).

---

## 3. Monopolio de Oferta

### 3.1 Planteamiento y Regla de Oro
El monopolista abastece a toda la demanda agregada ($p = p(Q)$). El ingreso total no es lineal respecto a la cantidad:

$$IT(Q) = p(Q) \cdot Q \implies IMg(Q) = \frac{dIT}{dQ} = p(Q) + Q \cdot \frac{dp(Q)}{dQ}$$

Dado que $\frac{dp}{dQ} < 0$, se cumple que $IMg(Q) < p(Q)$ para toda unidad positiva.

* **Condición de Primer Orden:**
  $$IMg(Q^*) = CMg(Q^*)$$
* **Fórmula de Amoroso-Robinson:**
  $$IMg = p \left( 1 - \frac{1}{\eta} \right)$$
  Donde $\eta = -\frac{dQ}{dp} \cdot \frac{p}{Q}$ es la elasticidad-precio de la demanda.
* **Implicación fundamental:** Como $CMg > 0$, el equilibrio del monopolio requiere necesariamente que $IMg > 0$, lo que implica:
  $$1 - \frac{1}{\eta} > 0 \iff \eta > 1$$
  *El monopolista nunca se situará voluntariamente en el tramo inelástico de su curva de demanda.*

### 3.2 Índice de Lerner de Poder de Mercado
A partir de la condición de óptimo $p \left(1 - \frac{1}{\eta}\right) = CMg$:

$$L = \frac{p - CMg}{p} = \frac{1}{\eta}$$

El margen porcentual de beneficio sobre el precio es inversamente proporcional a la elasticidad de la demanda.

### 3.3 Pérdida Irrecuperable de Eficiencia (PIE) y Excedentes
Al restringir la producción ($Q_M < Q_C$) y fijar un precio superior al coste marginal ($p_M > p_C$), se genera una transferencia neta de renta de los consumidores hacia el productor y una destrucción de bienestar social:

$$\Delta EC = -(A + B), \quad \Delta EP = A - C, \quad \text{PIE} = B + C$$

Donde $B$ representa el bienestar perdido de los consumidores que abandonan el mercado y $C$ el beneficio sacrificado que la empresa no percibe por las unidades no fabricadas.

```
       Precio (p)
           ^
       p_M |          /|
           |    A    / |
       p_C |--------/--+ (p = CMg)
           |        \B/|
           |       C \ |
           |          \| CMg
           +----------------------> Cantidad (Q)
                   Q_M  Q_C
```

### 3.4 Modalidades de Discriminación de Precios
1. **Primer Grado (Perfecta):** Cobro exacto del precio de reserva a cada consumidor. No hay pérdida irrecuperable de eficiencia ($\text{PIE} = 0$), pero todo el excedente social es capturado por el monopolista ($EP = ET$, $EC = 0$).
2. **Segundo Grado (Autoselección):** Tarifas no lineales, descuentos por bloques de volumen y venta en paquetes.
3. **Tercer Grado (Segmentación de Mercados):** Venta a diferentes grupos observables con elasticidades dispares ($\eta_1 \ne \eta_2$):
   $$IMg_1(q_1) = IMg_2(q_2) = CMg(q_1 + q_2) \implies p_1 \left(1 - \frac{1}{\eta_1}\right) = p_2 \left(1 - \frac{1}{\eta_2}\right)$$
   *Se cobra un precio superior al grupo con demanda más inelástica.*

---

## 4. Oligopolio e Interdependencia Estratégica

### 4.1 Cártel (Colusión Perfecta)
Las empresas coordinan sus niveles de producción para maximizar los beneficios conjuntos de la industria:

$$\max_{\{q_1, q_2\}} \Pi_{\text{cártel}} = p(q_1 + q_2)(q_1 + q_2) - CT_1(q_1) - CT_2(q_2)$$

* **Regla de asignación eficiente de cuotas:**
  $$IMg(Q) = CMg_1(q_1) = CMg_2(q_2)$$
* **Incentivo a la desviación:** Al precio del cártel $p_{\text{cártel}}$, cada empresa observa que $p_{\text{cártel}} > CMg_i(q_i)$, por lo que la producción clandestina de una unidad adicional reporta un beneficio marginal neto positivo.

### 4.2 Modelo de Cournot (Competencia Simultánea en Cantidades)
Dos empresas deciden simultáneamente sus cantidades ($q_1, q_2$) asumiendo como dada la cantidad del rival.
* El beneficio de la empresa $i$ es: $\Pi_i(q_i, q_j) = p(q_i + q_j) \cdot q_i - CT_i(q_i)$.
* Maximizando respecto a $q_i$ se obtienen las **Funciones de Reacción**:
  $$q_1 = FR_1(q_2), \quad q_2 = FR_2(q_1)$$
* El **Equilibrio de Nash-Cournot** se localiza en la intersección simultánea de ambas funciones.

### 4.3 Modelo de Stackelberg (Liderazgo en Cantidades)
Modelo secuencial donde una empresa **líder** (Empresa 1) decide su producción anticipando la respuesta racional de la empresa **seguidora** (Empresa 2).
* El líder introduce la función de reacción del seguidor $q_2 = FR_2(q_1)$ directamente en su propia función de beneficio:
  $$\max_{q_1} \Pi_1 = p(q_1 + FR_2(q_1)) \cdot q_1 - CT_1(q_1)$$
* **Resultado:** La empresa líder obtiene una ventaja del primer participante (*first-mover advantage*), produciendo una cantidad mayor y obteniendo más beneficios que en Cournot.

### 4.4 Modelo de Bertrand (Competencia Simultánea en Precios)
Las empresas con producto homogéneo y costes marginales constantes $c$ eligen precios de forma simultánea.
* Si $p_i < p_j$, la empresa $i$ absorbe todo el mercado.
* Si $p_i = p_j$, ambas se reparten la demanda al 50%.
* Si $p_i > p_j$, la demanda de $i$ es nula.
* **Paradoja de Bertrand:** La guerra de precios socava el margen comercial hasta que:
  $$p_1^* = p_2^* = c \implies Q_B = Q_C, \quad \Pi_1 = \Pi_2 = 0$$

### 4.5 Modelo de la Empresa Dominante con Franja Competitiva
Una gran empresa con liderazgo en costes abastece el mercado conviviendo con $m$ pequeñas empresas seguidoras tomadoras de precio que ofrecen conjuntamente $S_F(p)$.
* La líder enfrenta la **Demanda Residual**:
  $$D_L(p) = D_M(p) - S_F(p)$$
* Maximiza beneficios igualando $IMg_L = CMg_L$, determinando el precio del mercado $p^*$. Las seguidoras producen donde $p^* = CMg_j$.

---

## 5. Competencia Monopolística

Estructura definida por Edward Chamberlin:
1. Elevado número de empresas competidoras.
2. Libre entrada y salida de la industria a largo plazo.
3. **Diferenciación del producto:** Cada empresa goza de cierto monopolio sobre su marca o variedad específica, enfrentando una demanda individual decreciente.

* **Equilibrio a Corto Plazo:** Maximización mediante $IMg(q) = CMg(q)$. Puede haber beneficios extraordinarios ($\Pi > 0$).
* **Equilibrio a Largo Plazo y Teorema del Exceso de Capacidad:**
  La entrada de competidores con marcas sustitutivas desplaza y vuelve más elástica la demanda individual hasta que se vuelve tangente a la curva de Coste Total Medio:
  $$p^* = CTMe(q^*), \quad \text{con } \Pi^* = 0 \quad \text{y } p^* > CMg(q^*)$$
  Como la demanda tiene pendiente negativa, el punto de tangencia ocurre obligatoriamente en el **tramo decreciente del coste medio**, lo que implica que la empresa produce por debajo de su escala mínima eficiente ($\text{EME} = \min CTMe$). Dicha brecha productiva representa el **exceso de capacidad** que la sociedad asume a cambio de disfrutar de variedad de producto.

---

# PARTE II: FORMULARIO Y GUÍA DE RESOLUCIÓN ANALÍTICA

```
                                  MAPA DE RELACIONES ANALÍTICAS

    COMPETENCIA PERFECTA                 MONOPOLIO                       OLIGOPOLIO COURNOT
  +-----------------------+        +--------------------+              +---------------------+
  |   p = CMg             |        |    IMg = CMg       |              |    IMg_i = CMg_i    |
  |   p >= min CVMe (CP)  |        |    p = P(Q_M)      |              |   q_i = FR_i(q_j)   |
  |   p = min CTMe (LP)   |        |   L = (p-CMg)/p    |              |  Sistema FR_1 x FR_2|
  +-----------------------+        +--------------------+              +---------------------+
```

---

## Formulario Esencial de Economía Industrial y Mercados

| Concepto / Indicador | Expresión Matemática Analítica | Campo de Aplicación y Clave de Examen |
| :--- | :--- | :--- |
| **Ingreso Marginal (Demanda Lineal)** | Si $p(Q) = a - bQ \implies IMg(Q) = a - 2bQ$ | Monopolio, Cártel, Cournot (duplica la pendiente). |
| **Relación de Amoroso-Robinson** | $IMg = p \left(1 - \frac{1}{\eta}\right)$ | Relaciona ingreso marginal con elasticidad-precio. |
| **Índice de Lerner de Poder Monopolístico** | $L = \frac{p - CMg}{p} = \frac{1}{\eta}$ | Determina el poder de mercado relativo ($0 \le L \le 1$). |
| **Condición de Cierre (Corto Plazo)** | $p < \min CVMe \iff \frac{dCVMe}{dq} = 0$ | Define si una empresa competitiva interrumpe producción. |
| **Óptimo de Explotación (Beneficio Cero)** | $p = \min CTMe \iff CMg(q) = CTMe(q)$ | Determina el precio de equilibrio a largo plazo. |
| **Excedente del Consumidor ($EC$)** | $EC = \int_0^{Q^*} (p(Q) - p^*) \, dQ = \frac{(p_{\max} - p^*) Q^*}{2}$ | Bienestar neto de los compradores. |
| **Excedente del Productor ($EP$)** | $EP = \int_0^{Q^*} (p^* - CMg(q)) \, dq = IT - CVT$ | Bienestar de los productores (Beneficio + CF). |
| **Pérdida Irrecuperable Eficiencia ($\text{PIE}$)** | $\text{PIE} = \frac{1}{2} (p_M - CMg(Q_M)) (Q_C - Q_M)$ | Coste social de monopolios o impuestos con demanda lineal. |
| **Discriminación de Precios de 3.º Grado** | $IMg_1(q_1) = IMg_2(q_2) = CMg(q_1 + q_2)$ | Reparto óptimo de producción entre dos segmentos. |
| **Función de Reacción de Cournot** | $\frac{\partial \Pi_i(q_i, q_j)}{\partial q_i} = 0 \implies q_i = FR_i(q_j)$ | Respuesta óptima en cantidades ante la cuota rival. |
| **Liderazgo de Stackelberg** | $\max_{q_1} \Pi_1 = p(q_1 + FR_2(q_1)) q_1 - CT_1(q_1)$ | Decisión secuencial; se sustituye la reacción de la seguidora. |
| **Demanda Residual (Empresa Dominante)**| $D_L(p) = D_T(p) - S_F(p)$ | Deducción de la oferta competitiva sobre la total. |
| **Índice de Herfindahl-Hirschman (IHH)** | $\text{IHH} = \sum_{i=1}^n s_i^2 \quad (s_i \text{ en \% o tanto por uno})$| Medida de concentración para defensa de la competencia. |

---

# PARTE III: BANCO DE SUPUESTOS PRÁCTICOS RESUELTOS PASO A PASO

---

### Supuesto 1: Competencia Perfecta (Equilibrio a Corto Plazo, Cierre y Oferta Agregada)

**Enunciado:**  
En un mercado competitivo operan $N = 100$ empresas idénticas, cada una con la siguiente función de costes totales a corto plazo:
$$CT(q) = q^3 - 8q^2 + 30q + 50$$
La demanda agregada del mercado responde a la ecuación:
$$Q_D(p) = 2.400 - 40p$$

1. Determine analíticamente el **punto de cierre** y la ecuación de oferta individual a corto plazo.
2. Halle el **equilibrio de mercado** a corto plazo (precio, cantidad agregada y cantidad producida por cada firma).
3. Calcule el **beneficio económico** de cada empresa e interprete su sostenibilidad a largo plazo.

#### Solución analítica detallada:

**Paso 1: Identificación de componentes de coste y punto de cierre.**  
* Coste Fijo: $CF = 50$
* Coste Variable: $CV(q) = q^3 - 8q^2 + 30q$
* Coste Variable Medio:
  $$CVMe(q) = \frac{CV(q)}{q} = q^2 - 8q + 30$$
* Coste Marginal:
  $$CMg(q) = \frac{dCT(q)}{dq} = 3q^2 - 16q + 30$$

El punto de cierre se localiza donde el $CVMe$ alcanza su mínimo:
$$\frac{dCVMe(q)}{dq} = 2q - 8 = 0 \implies q_{\text{cierre}} = 4$$

Calculamos el precio de cierre evaluando el $CVMe$ en $q = 4$:
$$p_{\text{cierre}} = CVMe(4) = (4)^2 - 8(4) + 30 = 16 - 32 + 30 = 14$$

Por lo tanto, la curva de oferta individual viene dada por $p = CMg(q) = 3q^2 - 16q + 30$, válida exclusivamente para todo $p \ge 14$. Para $p < 14$, la oferta individual es $q = 0$.

**Paso 2: Determinación del equilibrio de mercado.**  
Supongamos que el precio de equilibrio supera el punto de cierre ($p \ge 14$). Igualamos la demanda agregada con la oferta total del mercado $Q_S(p) = N \cdot q = 100q$:

$$Q_D = 100q \implies 2.400 - 40p = 100q \implies 100q + 40p = 2.400 \implies p = \frac{2.400 - 100q}{40} = 60 - 2,5q$$

Como cada empresa iguala $p = CMg(q)$:
$$60 - 2,5q = 3q^2 - 16q + 30$$
$$3q^2 - 13,5q - 30 = 0$$

Dividiendo entre 3:
$$q^2 - 4,5q - 10 = 0$$

Aplicando la fórmula cuadrática:
$$q = \frac{4,5 \pm \sqrt{(-4,5)^2 - 4(1)(-10)}}{2} = \frac{4,5 \pm \sqrt{20,25 + 40}}{2} = \frac{4,5 \pm \sqrt{60,25}}{2} = \frac{4,5 \pm 7,762}{2}$$

Tomando la raíz económicamente admisible ($q > 0$):
$$q^* \approx 6,131 \text{ unidades}$$

Sustituyendo en la expresión del precio:
$$p^* = 60 - 2,5(6,131) = 44,67$$

Comprobación de viabilidad: $p^* = 44,67 > p_{\text{cierre}} = 14$. Las empresas operan en el tramo económicamente válido.
* Cantidad agregada intercambiada:
  $$Q^* = 100 \cdot q^* = 613,1 \text{ unidades}$$

**Paso 3: Cálculo del beneficio económico individual.**  
Calculamos el Coste Total por empresa:
$$CT(6,131) = (6,131)^3 - 8(6,131)^2 + 30(6,131) + 50$$
$$CT(6,131) \approx 230,48 - 300,71 + 183,93 + 50 = 163,70$$

Ingreso Total:
$$IT = p^* \cdot q^* = 44,67 \cdot 6,131 = 273,87$$

Beneficio:
$$\Pi = IT - CT = 273,87 - 163,70 = +110,17 > 0$$

*Interpretación a largo plazo:* Al existir beneficios extraordinarios positivos ($\Pi > 0$) y ausencia de barreras de entrada, nuevas firmas ingresarán en la industria, incrementando la oferta y reduciendo el precio hasta que $p = \min CTMe$.

---

### Supuesto 2: Monopolio Puro, Índice de Lerner y Pérdida Irrecuperable

**Enunciado:**  
Un monopolista abastece a un mercado cuya función inversa de demanda es:
$$p(Q) = 200 - 2Q$$
Su estructura productiva responde a la función de costes totales:
$$CT(Q) = 20Q + 2Q^2 + 100$$

1. Determine la cantidad producida, el precio de monopolio y los beneficios extraordinarios.
2. Calcule el **Índice de Lerner** y la **elasticidad-precio** de la demanda en el punto de óptimo.
3. Cuantifique la **Pérdida Irrecuperable de Eficiencia (PIE)** generada por el monopolio respecto al marco competitivo.

#### Solución analítica detallada:

**Paso 1: Maximización del beneficio del monopolio.**  
* Ingreso Total:
  $$IT(Q) = p(Q) \cdot Q = (200 - 2Q)Q = 200Q - 2Q^2$$
* Ingreso Marginal:
  $$IMg(Q) = \frac{dIT}{dQ} = 200 - 4Q$$
* Coste Marginal:
  $$CMg(Q) = \frac{dCT}{dQ} = 20 + 4Q$$

Condición de primer orden ($IMg = CMg$):
$$200 - 4Q = 20 + 4Q \implies 8Q = 180 \implies Q_M^* = 22,5$$

Sustituyendo en la demanda para fijar el precio:
$$p_M^* = 200 - 2(22,5) = 200 - 45 = 155$$

Beneficios del monopolista:
$$IT = 155 \cdot 22,5 = 3.487,5$$
$$CT = 20(22,5) + 2(22,5)^2 + 100 = 450 + 1.012,5 + 100 = 1.562,5$$
$$\Pi_M = 3.487,5 - 1.562,5 = 1.925$$

**Paso 2: Índice de Lerner y elasticidad-precio.**  
Evaluamos el coste marginal en la producción óptima:
$$CMg(22,5) = 20 + 4(22,5) = 110$$

Índice de Lerner:
$$L = \frac{p_M - CMg}{p_M} = \frac{155 - 110}{155} = \frac{45}{155} \approx 0,2903 \quad (29,03\%)$$

A partir de la relación $L = \frac{1}{\eta}$:
$$\eta = \frac{1}{L} = \frac{155}{45} \approx 3,444 > 1$$
*El monopolista opera en el tramo elástico de la demanda, verificando la consistencia teórica.*

**Paso 3: Cálculo de la Pérdida Irrecuperable de Eficiencia (PIE).**  
En el equilibrio competitivo de referencia se iguala el precio al coste marginal ($p = CMg$):
$$200 - 2Q = 20 + 4Q \implies 6Q = 180 \implies Q_C = 30$$
$$p_C = 200 - 2(30) = 140$$

La pérdida social se calcula como el área del triángulo de Harberger:
$$\text{PIE} = \frac{(p_M - CMg(Q_M)) \cdot (Q_C - Q_M)}{2} = \frac{(155 - 110) \cdot (30 - 22,5)}{2} = \frac{45 \cdot 7,5}{2} = 168,75$$

---

### Supuesto 3: Discriminación de Precios de Tercer Grado

**Enunciado:**  
Un monopolista puede segmentar a sus consumidores en dos mercados separados sin posibilidad de arbitraje:
* **Mercado 1 (Empresas):** $p_1(q_1) = 120 - q_1$
* **Mercado 2 (Particulares):** $p_2(q_2) = 80 - 0,5q_2$

La función de coste total de producción agregada es:
$$CT(Q) = 20Q + 0,25Q^2 + 500, \quad \text{donde } Q = q_1 + q_2$$

Determine la asignación óptima de producción, los precios fijados en cada mercado y compare las elasticidades resultantes.

#### Solución analítica detallada:

**Paso 1: Funciones de Ingreso Marginal de cada submercado.**  
* Submercado 1:
  $$IT_1(q_1) = (120 - q_1)q_1 \implies IMg_1(q_1) = 120 - 2q_1$$
* Submercado 2:
  $$IT_2(q_2) = (80 - 0,5q_2)q_2 \implies IMg_2(q_2) = 80 - q_2$$
* Coste Marginal conjunto:
  $$CMg(Q) = 20 + 0,5Q = 20 + 0,5(q_1 + q_2)$$

**Paso 2: Sistema de ecuaciones de equilibrio.**  
La regla de optimización con discriminación de tercer grado impone:
$$IMg_1(q_1) = CMg(q_1 + q_2) \quad \text{y} \quad IMg_2(q_2) = CMg(q_1 + q_2)$$

Igualando $IMg_1 = IMg_2$:
$$120 - 2q_1 = 80 - q_2 \implies q_2 = 2q_1 - 40$$

Sustituyendo $q_2$ en la condición $IMg_1 = CMg$:
$$120 - 2q_1 = 20 + 0,5\big(q_1 + (2q_1 - 40)\big)$$
$$120 - 2q_1 = 20 + 0,5(3q_1 - 40) = 20 + 1,5q_1 - 20 = 1,5q_1$$
$$120 = 3,5q_1 \implies q_1^* = \frac{120}{3,5} = \frac{240}{7} \approx 34,29$$

Calculamos $q_2^*$:
$$q_2^* = 2\left(\frac{240}{7}\right) - 40 = \frac{480 - 280}{7} = \frac{200}{7} \approx 28,57$$

Producción total:
$$Q^* = q_1^* + q_2^* = \frac{440}{7} \approx 62,86$$

**Paso 3: Fijación de precios en cada segmento.**  
$$p_1^* = 120 - \frac{240}{7} = \frac{600}{7} \approx 85,71$$
$$p_2^* = 80 - 0,5\left(\frac{200}{7}\right) = 80 - \frac{100}{7} = \frac{460}{7} \approx 65,71$$

**Paso 4: Análisis comparativo de elasticidades.**  
* Elasticidad en el mercado 1:
  $$\eta_1 = -\frac{dq_1}{dp_1} \cdot \frac{p_1^*}{q_1^*} = -(-1) \cdot \frac{85,71}{34,29} \approx 2,50$$
* Elasticidad en el mercado 2:
  $$\eta_2 = -\frac{dq_2}{dp_2} \cdot \frac{p_2^*}{q_2^*} = -(-2) \cdot \frac{65,71}{28,57} \approx 4,60$$

*Conclusión económica:* El monopolista cobra un precio superior al Mercado 1 ($p_1 = 85,71 > p_2 = 65,71$) debido a que su demanda es sustancialmente más inelástica ($\eta_1 = 2,50 < \eta_2 = 4,60$), corroborando el principio de discriminación de tercer grado.

---

### Supuesto 4: Duopolio de Cournot vs. Cártel Colusivo

**Enunciado:**  
Un mercado duopolístico presenta la función inversa de demanda:
$$P(Q) = 150 - Q, \quad \text{donde } Q = q_1 + q_2$$
Las empresas presentan estructuras de costes asimétricas:
$$CT_1(q_1) = 30q_1, \quad CT_2(q_2) = 0,5q_2^2$$

1. Obtenga las **funciones de reacción** de ambas firmas y determine el **Equilibrio de Cournot-Nash**.
2. Plantee el problema de maximización si deciden formar un **cártel colusivo** y calcule las cuotas óptimas de producción.

#### Solución analítica detallada:

**Paso 1: Derivación de funciones de reacción de Cournot.**  
* **Empresa 1:**
  $$\Pi_1(q_1, q_2) = [150 - (q_1 + q_2)]q_1 - 30q_1 = 120q_1 - q_1^2 - q_1 q_2$$
  $$\frac{\partial \Pi_1}{\partial q_1} = 120 - 2q_1 - q_2 = 0 \implies q_1 = \frac{120 - q_2}{2} = 60 - 0,5q_2 \quad (FR_1)$$

* **Empresa 2:**
  $$\Pi_2(q_1, q_2) = [150 - (q_1 + q_2)]q_2 - 0,5q_2^2 = 150q_2 - q_1 q_2 - 1,5q_2^2$$
  $$\frac{\partial \Pi_2}{\partial q_2} = 150 - q_1 - 3q_2 = 0 \implies q_2 = \frac{150 - q_1}{3} = 50 - \frac{q_1}{3} \quad (FR_2)$$

**Paso 2: Resolución del equilibrio de Nash.**  
Sustituimos $FR_2$ en $FR_1$:
$$q_1 = 60 - 0,5\left(50 - \frac{q_1}{3}\right) = 60 - 25 + \frac{q_1}{6} = 35 + \frac{q_1}{6}$$
$$\frac{5}{6}q_1 = 35 \implies q_1^* = \frac{35 \cdot 6}{5} = 42$$

Sustituyendo $q_1^* = 42$ en $FR_2$:
$$q_2^* = 50 - \frac{42}{3} = 50 - 14 = 36$$

Magnitudes del mercado de Cournot:
* Producción conjunta: $Q_{\text{Cournot}} = 42 + 36 = 78$
* Precio de mercado: $P_{\text{Cournot}} = 150 - 78 = 72$
* Beneficios individuales:
  $$\Pi_1 = (72 - 30) \cdot 42 = 42 \cdot 42 = 1.764$$
  $$\Pi_2 = 72(36) - 0,5(36)^2 = 2.592 - 648 = 1.944$$

**Paso 3: Solución de Cártel (Colusión conjunta).**  
La colusión maximiza:
$$\max_{\{q_1, q_2\}} \Pi_C = [150 - (q_1 + q_2)](q_1 + q_2) - 30q_1 - 0,5q_2^2$$

Condiciones de primer orden:
$$\frac{\partial \Pi_C}{\partial q_1} = 150 - 2(q_1 + q_2) - 30 = 0 \implies 120 - 2(q_1 + q_2) = 0 \implies Q_C = 60$$
$$\frac{\partial \Pi_C}{\partial q_2} = 150 - 2(q_1 + q_2) - q_2 = 0$$

Como $150 - 2(q_1 + q_2) = 30$ (por la primera condición):
$$30 - q_2 = 0 \implies q_{2, C}^* = 30$$

Por consiguiente:
$$q_{1, C}^* = Q_C - q_{2, C}^* = 60 - 30 = 30$$

Precio de cártel:
$$P_C = 150 - 60 = 90$$

Beneficio conjunto del cártel:
$$\Pi_C = 90(60) - 30(30) - 0,5(30)^2 = 5.400 - 900 - 450 = 4.050$$
*Comparación:* $\Pi_{\text{conjunto, Cournot}} = 1.764 + 1.944 = 3.708 < \Pi_C = 4.050$. El cártel eleva el beneficio conjunto mediante la restricción de la oferta agregada.

---

### Supuesto 5: Duopolio de Stackelberg (Liderazgo en Cantidades)

**Enunciado:**  
Considere un mercado duopolístico con demanda agregada $P(Q) = 100 - Q$, donde $Q = q_1 + q_2$.  
Ambas firmas tienen costes marginales constantes e idénticos:
$$CT_1(q_1) = 10q_1, \quad CT_2(q_2) = 10q_2$$
La **Empresa 1** asume el papel de líder de Stackelberg y la **Empresa 2** opera como seguidora.

1. Determine la función de reacción de la firma seguidora.
2. Obtenga el equilibrio de Stackelberg y compárelo con el resultado de Cournot simétrico.

#### Solución analítica detallada:

**Paso 1: Reacción de la seguidora (Empresa 2).**  
La empresa 2 optimiza tomando $q_1$ como dato fijo:
$$\Pi_2(q_2; q_1) = (100 - q_1 - q_2)q_2 - 10q_2 = 90q_2 - q_1 q_2 - q_2^2$$
$$\frac{\partial \Pi_2}{\partial q_2} = 90 - q_1 - 2q_2 = 0 \implies q_2 = \frac{90 - q_1}{2} = 45 - 0,5q_1 \quad (FR_2)$$

**Paso 2: Decisión estratégica de la líder (Empresa 1).**  
La empresa 1 incorpora $FR_2$ en su propia función de demanda percibida:
$$P(q_1) = 100 - q_1 - (45 - 0,5q_1) = 55 - 0,5q_1$$

Función de beneficio de la líder:
$$\Pi_1(q_1) = P(q_1) \cdot q_1 - CT_1(q_1) = (55 - 0,5q_1)q_1 - 10q_1 = 45q_1 - 0,5q_1^2$$

Condición de primer orden:
$$\frac{d\Pi_1}{dq_1} = 45 - q_1 = 0 \implies q_{1, S}^* = 45$$

**Paso 3: Determinación de las variables de equilibrio.**  
* Producción de la seguidora:
  $$q_{2, S}^* = 45 - 0,5(45) = 22,5$$
* Producción total del mercado:
  $$Q_S = 45 + 22,5 = 67,5$$
* Precio de equilibrio:
  $$P_S = 100 - 67,5 = 32,5$$
* Beneficios individuales:
  $$\Pi_{1, S} = (32,5 - 10) \cdot 45 = 22,5 \cdot 45 = 1.012,5$$
  $$\Pi_{2, S} = (32,5 - 10) \cdot 22,5 = 22,5 \cdot 22,5 = 506,25$$

**Comparación de referencia con Cournot Simétrico:**  
En el equilibrio simétrico de Cournot:
$$q_1 = q_2 = \frac{a - c}{3b} = \frac{100 - 10}{3} = 30 \implies Q_C = 60, \quad P_C = 40, \quad \Pi_1 = \Pi_2 = 900$$
*Conclusión analítica:* El líder de Stackelberg expande su producción de 30 a 45 unidades y eleva sus ganancias de 900 a 1.012,5, a expensas de la seguidora, cuya producción se retrae a 22,5 y su beneficio cae a 506,25.

---

### Supuesto 6: Empresa Dominante con Franja Competitiva

**Enunciado:**  
La demanda de mercado de un sector industrial es:
$$Q_D(p) = 1.000 - 10p$$
Existen 10 pequeñas empresas competitivas que conforman la franja seguidora, cada una con oferta individual:
$$q_f(p) = p - 10 \quad (\text{para } p \ge 10)$$
La empresa dominante posee la función de coste total:
$$CT_L(q_L) = 100 + 20q_L$$

1. Deduzca analíticamente la curva de **demanda residual** que abastece la empresa dominante.
2. Determine el precio fijado por la líder, el reparto de cuotas de mercado y el beneficio de la firma dominante.

#### Solución analítica detallada:

**Paso 1: Curva de oferta agregada de la franja competitiva.**  
La oferta combinada de las 10 firmas seguidoras es:
$$S_F(p) = 10 \cdot q_f(p) = 10(p - 10) = 10p - 100 \quad (\text{para } p \ge 10)$$

**Paso 2: Obtención de la Demanda Residual de la empresa dominante.**  
$$D_L(p) = Q_D(p) - S_F(p) = (1.000 - 10p) - (10p - 100) = 1.100 - 20p$$

Expresamos la función inversa de demanda residual de la empresa dominante:
$$20p = 1.100 - q_L \implies p = 55 - 0,05q_L$$

**Paso 3: Maximización de la empresa dominante.**  
* Ingreso Marginal de la líder:
  $$IMg_L(q_L) = 55 - 0,10q_L$$
* Coste Marginal de la líder:
  $$CMg_L(q_L) = 20$$

Condición de primer orden:
$$55 - 0,10q_L = 20 \implies 0,10q_L = 35 \implies q_L^* = 350$$

Precio de mercado:
$$p^* = 55 - 0,05(350) = 55 - 17,5 = 37,5$$

**Paso 4: Reparto de cuotas y beneficios.**  
* Oferta total de la franja seguidora:
  $$S_F(37,5) = 10(37,5) - 100 = 375 - 100 = 275$$
* Demanda total del mercado:
  $$Q_D(37,5) = 1.000 - 10(37,5) = 625$$
  *(Verificación de balance: $q_L^* + S_F = 350 + 275 = 625$)*.
* Cuotas de mercado:
  $$\text{Cuota Líder} = \frac{350}{625} = 56\%, \quad \text{Cuota Franja} = \frac{275}{625} = 44\%$$
* Beneficio de la empresa dominante:
  $$\Pi_L = p^* \cdot q_L^* - CT_L(q_L^*) = 37,5(350) - [100 + 20(350)] = 13.125 - 7.100 = 6.025$$

---

### Supuesto 7: Competencia Monopolística (Equilibrio de Chamberlin a Largo Plazo)

**Enunciado:**  
Una empresa en competencia monopolística enfrenta a corto plazo la demanda individual:
$$p(q) = 140 - 2q$$
Sus costes totales son $CT(q) = 20q + q^2 + 108$.
A largo plazo, la entrada de competidores contrae paralelamente la demanda que percibe la firma a una forma $p(q) = A - 2q$. Calcule:
1. El precio, la cantidad y el beneficio a corto plazo.
2. El valor del parámetro $A$, la producción y el precio de equilibrio a **largo plazo**.

#### Solución analítica detallada:

**Paso 1: Equilibrio a Corto Plazo.**  
* $IMg(q) = 140 - 4q$
* $CMg(q) = 20 + 2q$

Igualando $IMg = CMg$:
$$140 - 4q = 20 + 2q \implies 6q = 120 \implies q_{CP}^* = 20$$
$$p_{CP}^* = 140 - 2(20) = 100$$
$$CT(20) = 20(20) + (20)^2 + 108 = 400 + 400 + 108 = 908$$
$$\Pi_{CP} = (100 \cdot 20) - 908 = 2.000 - 908 = 1.092 > 0$$

**Paso 2: Equilibrio a Largo Plazo de Chamberlin.**  
El equilibrio de libre concurrencia a largo plazo exige simultáneamente dos condiciones:
1. Maximización de beneficios: $IMg_{LP}(q) = CMg(q)$
2. Anulación del beneficio extraordinario (tangencia): $p_{LP}(q) = CTMe(q)$

Expresamos el $CTMe$:
$$CTMe(q) = \frac{CT(q)}{q} = 20 + q + \frac{108}{q}$$

La condición de tangencia exige que la pendiente de la demanda individual iguale a la pendiente del $CTMe$:
$$\frac{dp}{dq} = \frac{dCTMe}{dq} \implies -2 = 1 - \frac{108}{q^2}$$
$$3 = \frac{108}{q^2} \implies q^2 = \frac{108}{3} = 36 \implies q_{LP}^* = 6$$

Determinamos el precio evaluando el $CTMe$ en $q = 6$:
$$p_{LP}^* = CTMe(6) = 20 + 6 + \frac{108}{6} = 26 + 18 = 44$$

Determinamos el parámetro de demanda $A$:
$$p_{LP}^* = A - 2q_{LP}^* \implies 44 = A - 2(6) \implies A = 56$$

Demanda residual a largo plazo: $p(q) = 56 - 2q$.
*Verificación de beneficio nulo:*
$$\Pi_{LP} = p_{LP}^* \cdot q_{LP}^* - CT(q_{LP}^*) = 44(6) - [20(6) + (6)^2 + 108] = 264 - [120 + 36 + 108] = 264 - 264 = 0$$

---

# PARTE IV: MATRIZ DE DECISIÓN RÁPIDA PARA EXÁMENES

```
¿Qué estructura te pide el enunciado?
│
├── 1. Competencia Perfecta:
│    └── Corto plazo: p = CMg (con p >= min CVMe).
│    └── Largo plazo: p = CMg = min CTMe (beneficio = 0).
│
├── 2. Monopolio:
│    └── Estándar: IMg = CMg -> p(Q).
│    └── Discriminación 3.º grado: IMg_1 = IMg_2 = CMg(Q_T).
│
├── 3. Duopolio / Oligopolio:
│    ├── ¿Deciden cantidades a la vez? -> Cournot: Sistema FR_1(q_2) y FR_2(q_1).
│    ├── ¿Deciden cantidades en secuencia? -> Stackelberg: Líder sustituye FR_seguidora en IT_1.
│    ├── ¿Compiten en precios (homogéneo)? -> Bertrand: p_1 = p_2 = CMg.
│    ├── ¿Colaboran? -> Cártel: Maximizar IT_T(Q) - CT_1 - CT_2 -> IMg = CMg_1 = CMg_2.
│    └── ¿Líder grande + muchas pequeñas? -> Empresa Dominante: Demanda Residual = D_Total - S_Franja.
│
└── 4. Competencia Monopolística:
     └── Largo plazo: Tangencia (p = CTMe y dp/dq = dCTMe/dq).
```