# Tema 38. Microeconomía: oferta, demanda y equilibrio de mercado. Elasticidades de precio y renta

---

## 1. Funciones de oferta y demanda

### 1.1 La demanda del consumidor
El análisis de la demanda parte del problema de optimización del agente económico representativo: maximizar su utilidad sujeto a su restricción presupuestaria.

* **Curvas de indiferencia y Utilidad Marginal ($UMg$):**  
  Representan combinaciones de bienes $(X, Y)$ que reportan el mismo nivel de satisfacción.
  $$\text{UMg}_X = \frac{\partial U}{\partial X}, \quad \text{UMg}_Y = \frac{\partial U}{\partial Y}$$
  Bajo preferencias regulares, la utilidad marginal es decreciente.

* **Relación Marginal de Sustitución ($RMS$):**  
  Tasa a la que el consumidor está dispuesto a intercambiar un bien por otro manteniendo constante su nivel de utilidad (pendiente de la curva de indiferencia):
  $$\text{RMS}_{Y,X} = -\frac{\Delta Y}{\Delta X} = \frac{\text{UMg}_X}{\text{UMg}_Y}$$

* **Restricción presupuestaria y condición de equilibrio:**  
  Delimita el conjunto presupuestario factible dada la renta nominal ($M$) y los precios ($p_X, p_Y$):
  $$M = p_X X + p_Y Y$$
  El óptimo se alcanza en el punto de tangencia donde la pendiente de la curva de indiferencia coincide con el cociente de precios:
  $$\text{RMS}_{Y,X} = \frac{p_X}{p_Y} \iff \frac{\text{UMg}_X}{p_X} = \frac{\text{UMg}_Y}{p_Y}$$

---

### 1.2 La oferta de la empresa competitiva
La empresa competitiva opera como agente **precio-aceptante**. Su objetivo es la maximización del beneficio ($\pi$):

$$\pi(y) = p \cdot y - C(y)$$

* **Condición de primer orden (C.P.O.):**
  $$\frac{d\pi}{dy} = 0 \implies p = \text{CMg}(y)$$
  El óptimo debe situarse siempre en el tramo ascendente de la curva de Coste Marginal.

* **Curva de oferta individual:**  
  Coincide con la curva de Coste Marginal ($\text{CMg}$) en el tramo en que es superior al **Coste Variable Medio** ($\text{CVMe}$).
  * **Punto de cierre ($p < \min \text{CVMe}$):** A la empresa le compensa no producir para no perder más que sus costes fijos.
  * **Mínimo de explotación ($p = \min \text{CVMe}$):** Nivel a partir del cual empieza a ofrecer producto.
  * **Óptimo de explotación ($p = \min \text{CTMe}$):** Beneficio económico nulo ($\pi = 0$).

---

## 2. Equilibrio y desplazamientos del mercado

### 2.1 Determinación del equilibrio competitivo
El equilibrio se alcanza cuando la cantidad demandada agregada iguala a la cantidad ofrecida agregada:

$$Q_d(P^*) = Q_s(P^*)$$

<div class="my-6 flex justify-center not-prose">
<svg viewBox="0 0 500 320" class="w-full max-w-md bg-white rounded-xl border border-slate-200 p-4 shadow-sm" xmlns="http://www.w3.org/2000/svg">
<line x1="50" y1="280" x2="460" y2="280" stroke="#64748b" stroke-width="2" />
<line x1="50" y1="280" x2="50" y2="20" stroke="#64748b" stroke-width="2" />
<text x="440" y="305" font-size="12" fill="#475569" font-family="sans-serif">Cantidad (Q)</text>
<text x="20" y="35" font-size="12" fill="#475569" font-family="sans-serif">Precio (P)</text>
<line x1="80" y1="50" x2="420" y2="250" stroke="#ef4444" stroke-width="3" stroke-linecap="round" />
<text x="425" y="255" font-size="12" font-weight="bold" fill="#ef4444" font-family="sans-serif">Demanda (D)</text>
<line x1="80" y1="250" x2="420" y2="50" stroke="#1d63ed" stroke-width="3" stroke-linecap="round" />
<text x="425" y="55" font-size="12" font-weight="bold" fill="#1d63ed" font-family="sans-serif">Oferta (S)</text>
<circle cx="250" cy="150" r="5" fill="#0f172a" />
<line x1="50" y1="150" x2="250" y2="150" stroke="#94a3b8" stroke-dasharray="4" />
<line x1="250" y1="150" x2="250" y2="280" stroke="#94a3b8" stroke-dasharray="4" />
<text x="25" y="154" font-size="11" font-weight="bold" fill="#0f172a" font-family="sans-serif">P*</text>
<text x="244" y="298" font-size="11" font-weight="bold" fill="#0f172a" font-family="sans-serif">Q*</text>
<rect x="180" y="85" width="140" height="24" rx="4" fill="#fef2f2" stroke="#fecaca" />
<text x="195" y="101" font-size="11" font-weight="600" fill="#dc2626" font-family="sans-serif">Exceso de Oferta</text>
<rect x="175" y="195" width="150" height="24" rx="4" fill="#eff6ff" stroke="#bfdbfe" />
<text x="186" y="211" font-size="11" font-weight="600" fill="#1d4ed8" font-family="sans-serif">Exceso de Demanda</text>
</svg>
</div>

* **Exceso de oferta ($P > P^*$):** Las empresas desean producir más de lo que los compradores absorben; empuja el precio a la baja.
* **Exceso de demanda ($P < P^*$):** La demanda supera a la oferta; la competencia entre compradores empuja el precio al alza.

---

### 2.2 Desplazamientos vs. Movimientos a lo largo de la curva

| Tipo de cambio | Causa determinante | Efecto sobre el gráfico |
| :--- | :--- | :--- |
| **Movimiento a lo largo de la curva** | Variación exclusiva del **propio precio** del bien ($P$). | Modificación en la *cantidad demandada* o en la *cantidad ofertada*. |
| **Desplazamiento de la Demanda** | Variación de la renta ($M$), gustos o precio de sustitutivos/complementarios. | Toda la curva de demanda se desplaza hacia la derecha o izquierda. |
| **Desplazamiento de la Oferta** | Cambio en los costes de factores, tecnología o número de empresas. | Toda la curva de oferta se desplaza hacia la derecha o izquierda. |

---

## 3. Elasticidad-precio y elasticidad-renta

### 3.1 Elasticidad-precio de la demanda ($\epsilon_p$)
Mide la variación porcentual de la cantidad demandada en respuesta a una variación porcentual del precio:

$$\epsilon_p = \frac{\Delta q / q}{\Delta p / p} = \frac{p}{q} \cdot \frac{dq}{dp}$$

*(En economía suele expresarse en valor absoluto $|\epsilon_p|$).*

* **Elástica ($|\epsilon_p| > 1$):** La cantidad demandada varía más que proporcionalmente al precio.
* **Unitaria ($|\epsilon_p| = 1$):** La cantidad y el precio varían en la misma proporción.
* **Inelástica ($|\epsilon_p| < 1$):** La demanda responde poco a variaciones de precio.

<div class="my-6 flex justify-center not-prose">
<svg viewBox="0 0 460 260" class="w-full max-w-md bg-white rounded-xl border border-slate-200 p-4 shadow-sm" xmlns="http://www.w3.org/2000/svg">
<line x1="50" y1="220" x2="420" y2="220" stroke="#64748b" stroke-width="2" />
<line x1="50" y1="220" x2="50" y2="20" stroke="#64748b" stroke-width="2" />
<text x="390" y="240" font-size="11" fill="#475569" font-family="sans-serif">Cantidad (q)</text>
<text x="15" y="30" font-size="11" fill="#475569" font-family="sans-serif">Precio (p)</text>
<line x1="50" y1="30" x2="390" y2="220" stroke="#0284c7" stroke-width="3" />
<circle cx="50" cy="30" r="4" fill="#0284c7" />
<text x="60" y="35" font-size="11" font-weight="bold" fill="#0369a1" font-family="sans-serif">ε = ∞ (Corte ordenada)</text>
<circle cx="220" cy="125" r="4" fill="#0284c7" />
<text x="230" y="125" font-size="11" font-weight="bold" fill="#0369a1" font-family="sans-serif">ε = 1 (Punto medio)</text>
<circle cx="390" cy="220" r="4" fill="#0284c7" />
<text x="340" y="210" font-size="11" font-weight="bold" fill="#0369a1" font-family="sans-serif">ε = 0</text>
</svg>
</div>

> **Regla de Examen:** En una curva de demanda lineal, la pendiente es constante, pero la elasticidad varía punto a punto: es infinita en el corte vertical, 1 en el punto medio y 0 en el corte horizontal.

---

### 3.2 Elasticidad-renta y clasificación de bienes
Mide el efecto sobre la demanda al variar la renta disponible ($r$):

$$\epsilon_r = \frac{\Delta q / q}{\Delta r / r}$$

| Tipo de Bien | Valor de $\epsilon_r$ | Comportamiento ante un aumento de renta |
| :--- | :---: | :--- |
| **Bien Inferior** | $\epsilon_r < 0$ | Su demanda disminuye; se sustituye por bienes de más calidad. |
| **Bien Normal de 1ª Necesidad** | $0 < \epsilon_r \le 1$ | Su demanda aumenta, pero a menor ritmo que la renta (ej. alimentos). |
| **Bien Normal de Lujo** | $\epsilon_r > 1$ | Su demanda crece más que proporcionalmente con la renta (ej. viajes). |

---

## 4. Intervención pública: Controles de precios e Impuestos

### 4.1 Controles de precios (Precio Máximo)
* Si se fija un precio máximo por debajo del equilibrio ($P_{max} < P^*$):
  * Se genera un **exceso de demanda** estructural ($Q_d > Q_s$).
  * La cantidad intercambiada cae forzosamente a $Q_s$, apareciendo pérdidas de eficiencia y riesgo de **mercado negro**.

---

### 4.2 Incidencia de los impuestos y Excedentes del Mercado

$$\text{Pérdida Irrecuperable de Eficiencia} = \Delta \text{Excedente Total} - \text{Recaudación Fiscal}$$

* **Reparto de la carga fiscal según elasticidades:**
  * **Demanda inelástica / Oferta elástica:** La carga del impuesto recae mayoritariamente sobre los **consumidores**.
  * **Demanda elástica / Oferta inelástica:** La carga del impuesto recae mayoritariamente sobre los **productores**.