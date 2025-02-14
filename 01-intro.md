
> [!definition] Econometría
> Medición económica.

## Metodología clásica

1. Planteamiento de teoría (hipótesis)
2. Especificación del modelo matemático
3. Especificación del modelo econométrico
4. Obtención de datos
5. Estimación de parámetros del modelo
6. Pruebas de hipótesis
7. Pronóstico (predicción)
8. Modelo para fines de control/política

### **Ej. Función consumo keynesiana**

$$

c = \alpha + \beta y \quad \forall \ 0<\beta<1

$$

Las relaciones entre variables económicas son **inexactas**, dada la injerencia de otras variables:

$$ \underset{\text{Modelo econométrico} }{c = \alpha + \beta y + u}

$$

$$ \underset{ \text{Variable aleatoria con propiedades probabilísticas} }{ u = \text{Error (perturbación estocástica)} } $$

$u$ incluye todos los factores que afectan **consumo** pero no están en la ecuación: tamaño de familia, edades, etc.

El modelo requiere ser estimado: obtener valores $\alpha$ y $\beta$ a partir de **datos.**

### **Ej. Gasto en** **consumo personal**

- Regresión: técnica estadística para el estudio de una **variable dependiente** que está en función de una o más **variables independientes.**
- Usando los datos de consumo y PIB de BUA se obtiene:

$$ \hat c = -231.8 + 0.7194 y

$$

Donde $\alpha = -231.8, \beta = 0.7194, \hat c = \text{Consumo (estimado)}, y = \text{PIB}$.

La interpretación consiste en que un incremento de tasa en el ingreso incrementa (en promedio) el consumo en 0.72 USD.

Se debe probar si los valores estimados:

1. Son estadísticamente significativos $(\alpha, \beta \neq 0)$
2. Confirman la teoría (hipótesis) que está siendo probada $(0<\beta<1)$

Si el modelo confirma la teoría (hipótesis), se pueden **pronosticar** valores futuros de la variable dependiente.

Ej. Suponer un PIB esperado para 1995 de $6,000 mmd, ¿cuál es el pronóstico de consumo?

$$

\begin{align*} \hat c &= -231.8 + 0.7194(6,000) \\ &= 4,084.6 \end{align*}

$$

Suponer que el gobierno considera que un gasto de \$4,000 mmd mantendrá la tasa de desempleo en 6.5%. ¿Cuál nivel de ingreso garantizará esta meta de consumo?

$$

\begin{aligned} \hat c &= -231.8 + 0.7194y \\ 4,000 &= -231.8 + 0.7194y \\ 0.7194y &= 4,000 + 231.8 \\ y &= \frac{4,231.8}{0.7194} \\ y^* &= 5,882.40 \end{aligned}

$$

Un modelo estimado puede ser usado para fines de control o de política económica (fiscal y monetaria).