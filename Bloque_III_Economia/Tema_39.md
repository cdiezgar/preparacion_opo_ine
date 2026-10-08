# Tema 39.  

## 1. Introducción y tipología de mercados

### 1.1 Decisiones de la empresa y restricciones

La empresa persigue como objetivo primordial la **maximización del beneficio** ($\Pi$), definido como la diferencia entre sus ingresos totales y sus costes económicos de oportunidad:

$$
\max_{q \ge 0} \Pi = p \cdot q - C(q)
$$

Para resolver este problema (fijar producción y precio), la empresa enfrenta tres restricciones:

1. **Restricciones tecnológicas:** Determinadas por su función de producción.
2. **Restricciones económicas:** Resumidas en sus funciones de costes.
3. **Restricciones de mercado:** Vienen dadas por la curva de demanda a la que se enfrenta la empresa.
   * Si fija el precio de venta, la cantidad vendida queda determinada por la curva de demanda.
   * Si fija el volumen de producción, la demanda determina el precio de venta de su producción.

El grado de control que la empresa tiene sobre el precio determina su **poder de mercado**, el cual oscila desde el caso nulo (competencia perfecta) hasta el máximo grado de control (monopolio).

### 1.2 Clasificación de las estructuras de mercado (Criterio de Eucken)

| Demanda \ Oferta | Concurrencia | Oligopolio | Monopolio |
| :--- | :--- | :--- | :--- |
| **Concurrencia** | **Competencia perfecta** | Oligopolio de oferta | Monopolio de oferta |
| **Oligopolio** | Oligopolio de demanda (Oligopsonio) | Oligopolio bilateral | Monopolio limitado de oferta |
| **Monopolio** | Monopolio de demanda (Monopsonio) | Monopolio limitado de demanda | **Monopolio bilateral** |

---

## 2. Competencia perfecta

### 2.1 Hipótesis y comportamiento precio-aceptante

En competencia perfecta, cada empresa es tan pequeña en relación al mercado que carece de capacidad para influir sobre el precio: es **precio-aceptante**.

* **Condiciones del modelo:**
  * **Atomización del mercado:** Elevado número de oferentes y demandantes.
  * **Homogeneidad del producto:** Bienes idénticos e indistinguibles.
  * **Información perfecta y simétrica:** Sin costes de transacción ni asimetrías de información.
  * **Libertad de entrada y salida:** Ausencia de barreras legales o económicas.
  * **Ausencia de externalidades:** No existen efectos externos ni bienes públicos.

### 2.2 Determinación del nivel de producción y resultados a corto plazo

Formalmente, al ser el precio $p$ un parámetro exógeno fijado por el mercado:

$$
\max_{q > 0} \Pi = p \cdot q - C(q)
$$

* **Condición de equilibrio:**

$$
\frac{d\Pi}{dq} = p - C'(q) = 0 \iff p = \text{CMg}(q)
$$

Siempre que se cumpla la condición de segundo orden ($\text{CMg}$ en tramo creciente) y la regla de no cierre ($p \ge \text{CVMe}$).

Designando $q_e$ como el nivel de producción óptimo de equilibrio:

| Resultado económico | Condición analítica | Implicación operativa |
| :--- | :--- | :--- |
| **Beneficio extraordinario** | $\Pi(q_e) > 0 \iff p > \text{CTMe}(q_e)$ | Atrae nuevas empresas a la industria a largo plazo. |
| **Beneficio normal (nulo)** | $\Pi(q_e) = 0 \iff p = \text{CTMe}(q_e)$ | Remunera todos los costes de oportunidad del capital. |
| **Pérdida asumible** | $\Pi(q_e) < 0 \text{ y } p \ge \text{CVMe}(q_e)$ | Produce a corto plazo: cubre costes variables y parte de fijos. |
| **Punto de cierre** | $p < \min \text{CVMe}(q_e)$ | La empresa cierra: pierde menos cerrando (solo costes fijos). |

### 2.3 Equilibrio a largo plazo y bienestar social

A largo plazo, la libre concurrencia anula cualquier beneficio extraordinario o pérdida económica:

* Si $\Pi > 0 \implies$ entran oferentes, la oferta agregada se expande y el precio se reduce.
* Si $\Pi < 0 \implies$ salen oferentes, la oferta se contrae y el precio se eleva.

El equilibrio de largo plazo converge al mínimo del coste total medio:

$$
p_e = \text{CMg}(q_e) = \min \text{CTMe}
$$

Garantizando la máxima eficiencia en la asignación de recursos y maximizando el excedente social total ($\text{ET} = \text{EC} + \text{EP}$).

---

## 3. El monopolio

### 3.1 Equilibrio del monopolista y condición de óptimo

Un único oferente abastece todo el mercado, por lo que su curva de demanda individual coincide con la **demanda agregada del mercado** ($p = p(q)$, con $p'(q) < 0$).

$$
\max_{q > 0} \Pi = p(q) \cdot q - C(q)
$$

* **Condición de Primer Orden (C.P.O.):**

$$
\frac{d\Pi}{dq} = p(q) + p'(q) \cdot q - C'(q) = 0
$$

Esto es equivalente a igualar el Ingreso Marginal con el Coste Marginal:

$$
\text{IMg}(q_e) = \text{CMg}(q_e)
$$

Donde el Ingreso Marginal ($\text{IMg}$) incorpora el efecto cantidad y el efecto precio:

$$
\text{IMg}(q) = p(q) + p'(q) \cdot q < p(q)
$$

Al vender una unidad adicional, el monopolista debe reducir el precio de todas las unidades anteriores vendidas en el mercado.

### 3.2 Índice de Lerner y elasticidad-precio

A partir de la condición de óptimo se deriva la expresión de Amoroso-Robinson:

$$
\text{IMg}(q_e) = p_e \cdot \left[ 1 - \frac{1}{\eta} \right] = \text{CMg}(q_e)
$$

Donde $\eta = -\frac{dq}{dp} \cdot \frac{p}{q} \ge 1$ es la elasticidad-precio de la demanda. Despejando se obtiene el **Índice de Lerner** ($L$), indicador directo del poder de monopolio:

$$
L = \frac{p_e - \text{CMg}(q_e)}{p_e} = \frac{1}{\eta}
$$

* Cuanto más inelástica es la demanda ($\eta \to 1$), mayor es el margen que el monopolio carga sobre sus costes y mayor el grado de explotación del mercado.

### 3.3 Pérdida de bienestar y discriminación de precios

El monopolio genera una ineficiencia asignativa intrínseca al fijar un precio superior al coste marginal y restringir la producción ($p_M > p_C$ y $Q_M < Q_C$):

$$
\text{Pérdida Irrecuperable de Eficiencia} = \Delta \text{Excedente Total} < 0
$$

* **Discriminación de precios:**
  * **Primer grado (perfecta):** El monopolista cobra a cada consumidor su precio de reserva exacto, capturando la totalidad del excedente del consumidor sin generar pérdida de peso muerto.
  * **Tercer grado:** Segmentación de los consumidores en submercados observables según su elasticidad (ej. tarifas reducidas para jóvenes o pensionistas).
  * **Condición indispensable:** Ausencia de arbitraje (imposibilidad técnica o jurídica de reventa entre clientes).

---

## 4. Modelos de oligopolio e interdependencia estratégica

En los mercados oligopolísticos impera la **interdependencia estratégica**: la decisión óptima de cada empresa depende directamente de las conjeturas que formule sobre el comportamiento de sus competidores.

### 4.1 Cártel (Colusión perfecta)

Acuerdo colusivo entre empresas para coordinar producción y precios emulando un monopolio:

$$
\max_{\{q_1, q_2, \dots, q_n\}} \Pi_{\text{conjunto}} = p(Q) \cdot Q - \sum_{i=1}^n C_i(q_i) \implies \text{IMg}(Q) = \text{CMg}_1(q_1) = \dots = \text{CMg}_n(q_n)
$$

* **Inestabilidad intrínseca:** Cada integrante tiene un incentivo privado a violar la cuota acordada ($p_{\text{cártel}} > \text{CMg}_i$), provocando la ruptura del pacto en ausencia de mecanismos punitivos creíbles.

### 4.2 Modelo de la empresa dominante

Una gran empresa con cuota mayoritaria convive con una franja de pequeñas empresas seguidoras competitivas que tienen una función de oferta agregada $F(p)$:

$$
\text{Demanda Residual Líder:} \quad D_{\text{residual}}(p) = D_{\text{merc}}(p) - F(p)
$$

El grado de explotación de la empresa líder viene expresado por el Índice de Lerner:

$$
\frac{p_e - c}{p_e} = \frac{1 - s_F}{\eta_D + \eta_F \cdot s_F}
$$

Donde $s_F = \frac{F}{D}$ es la cuota de mercado de las pequeñas empresas seguidoras. Si $s_F \to 0$, el índice converge exactamente al del monopolio puro.

### 4.3 Duopolio de Cournot (Competencia simultánea en cantidades)

Dos empresas deciden simultáneamente la cantidad a producir ($q_1, q_2$) de un bien homogéneo.

* **Función de reacción de la empresa 1 ($\text{FR}_1$):** Cantidad óptima de la empresa 1 ante cada volumen estimado de la empresa 2:

$$
q_1^{e} = \text{FR}_1(q_2)
$$

* **Función de reacción de la empresa 2 ($\text{FR}_2$):**

$$
q_2^{e} = \text{FR}_2(q_1)
$$

* **Equilibrio de Cournot-Nash:** Intersección de ambas funciones ($\text{FR}_1 \cap \text{FR}_2$), donde las conjeturas son mutuamente consistentes:

$$
Q_M < Q_{\text{Cournot}} < Q_C \quad \text{y} \quad p_C < p_{\text{Cournot}} < p_M
$$

### 4.4 Duopolio de Bertrand (Competencia simultánea en precios)

Dos empresas con costes marginales idénticos y constantes ($\text{CMg} = c$) compiten fijando precios sobre un bien homogéneo.

* Si una empresa reduce ligeramente su precio ($p_1 < p_2$), captura toda la demanda del mercado.
* Si fijan el mismo precio, se reparten el mercado en partes iguales.

La guerra de precios empuja las cotizaciones a la baja hasta alcanzar el equilibrio estable:

$$
p_1^{e} = p_2^{e} = \text{CMg} = c \implies Q_B = Q_C, \quad \Pi_1 = \Pi_2 = 0
$$

> **La Paradoja de Bertrand:** Dos únicas empresas son suficientes para obtener el mismo resultado que en competencia perfecta cuando compiten en precios sobre un bien homogéneo y sin límites de capacidad.

---

## 5. Competencia monopolística

### 5.1 Diferenciación y equilibrio a corto y largo plazo

Caracterizada por un gran número de empresas que comercializan **productos diferenciados** (marcas, patentes, diseño o sustitutivos cercanos).

* **Corto plazo:** Cada empresa actúa como un pequeño monopolio sobre su propia marca. Maximiza con $\text{IMg} = \text{CMg}$, pudiendo obtener beneficios extraordinarios ($\Pi > 0$).
* **Largo plazo:** La libre entrada atrae competidores con bienes sustitutivos, contrayendo la demanda individual hasta que se hace tangente a la curva de Coste Total Medio:

$$
\Pi = 0 \iff p_{lp} = \text{CTMe}(q_{lp}) > \text{CMg}(q_{lp})
$$

* **Teorema del exceso de capacidad:** La tangencia ocurre necesariamente en el tramo decreciente del $\text{CTMe}$, por lo que se produce por debajo del óptimo técnico (mínimo de los costes medios).

---

## 6. Gradación de estructuras y regulación económica

### 6.1 Espectro de explotación del consumidor

$$
\text{Menor explotación / Menor coste social} \longleftrightarrow \text{Mayor coste social}
$$

$$
[\text{Comp. Perfecta} \equiv \text{Bertrand}] \;\longrightarrow\; \text{Comp. Monopolística} \;\longrightarrow\; \text{Empresa Dominante} \;\longrightarrow\; \text{Cournot} \;\longrightarrow\; \text{Monopolio} \;\longrightarrow\; \text{Discrim. Perfecta}
$$

### 6.2 Política de defensa de la competencia

Las autoridades de competencia emplean el equilibrio competitivo como marco de referencia (*benchmark*) para tutelar el bienestar general:

* **Mecanismos de intervención:**
  * Persecución y desarticulación de cárteles y acuerdos colusivos.
  * Control preventivo de fusiones y adquisiciones que generen excesiva concentración.
  * Regulación de tarifas y condiciones de acceso en monopolios naturales.
  * Limitación temporal de patentes y marcas para proteger la innovación sin perpetuar barreras de entrada.