---
title: "La ley de los números grandes: Cuando los números dejan de ser intuitivos"
description: "Con pocas observaciones, el azar domina. Con muchas, el patrón real se hace visible."
pubDate: "2026-06-15"
heroImage: "/ley_de_los_numeros_grandes.webp"
badge: ""
tags: ["Probabilidad"]
---

La **Ley de los Grandes Números** es un principio de probabilidad que dice algo muy intuitivo: **mientras más veces repites un experimento aleatorio, más tienden los resultados promedio a acercarse a lo que teóricamente debería ocurrir**.

Imagina una moneda equilibrada. Tiene dos posibles resultados:  **Águila** o **Sol**

En teoría, cada uno tiene una probabilidad del **50%**. Pero si lanzas la moneda solo **2 veces**, podrías obtener: Águila, Águila
Eso daría **100% águila y 0% sol**. ¿Significa que la moneda está trucada? No. Simplemente hiciste muy pocos lanzamientos.

Si la lanzas **10 veces**, quizá obtengas: 6 águilas y 4 soles. Entonces tendríamos: **60% águila — 40% sol**

Todavía no es exactamente 50/50.

<img src="/aguila_o_sol.webp" alt="Aguila o sol">

Ahora imagina que la lanzas **100 veces**. Quizá obtengas: 52 águilas y 48 soles. Ya estamos mucho más cerca del 50%.

Y si hacemos **10,000 lanzamientos**, podríamos obtener algo como: 5,012 águilas y 4,988 soles. Eso representa aproximadamente:**50.12% águila — 49.88% sol**

Ahí aparece claramente la Ley de los Grandes Números: **al aumentar el número de observaciones, la proporción observada tiende a acercarse a la probabilidad real del fenómeno.**

Una forma sencilla de visualizarlo sería:

| Lanzamientos | Águila |   Sol | % Águila |
| -----------: | -----: | ----: | -------: |
|            2 |      2 |     0 |     100% |
|           10 |      6 |     4 |      60% |
|          100 |     52 |    48 |      52% |
|        1,000 |    493 |   507 |    49.3% |
|       10,000 |  5,012 | 4,988 |   50.12% |

Hay un detalle importante: **la ley no dice que los resultados tengan que quedar exactamente 50/50**. Tampoco significa que si han salido muchas águilas, ahora “tengan que salir soles” para compensar.

Por ejemplo, después de obtener cinco águilas consecutivas: **Águila – Águila – Águila – Águila – Águila**

el siguiente lanzamiento sigue teniendo aproximadamente: **50% águila — 50% sol**

La moneda no recuerda los resultados anteriores.

Lo que sucede es que, cuando acumulamos miles o millones de observaciones, las pequeñas rachas y fluctuaciones tienen cada vez menos peso sobre el resultado total.

Por eso esta ley es tan importante en **análisis de datos**. Una muestra pequeña puede producir resultados sorprendentes simplemente por azar. Una muestra más grande suele darnos una estimación más estable del comportamiento de una población.

Podríamos resumirlo así:

> **Con pocos datos, el azar puede dominar el resultado. Con muchos datos, el patrón real comienza a hacerse visible.**

Y eso da pie a una idea muy buena: **tener muchos datos no garantiza que un análisis sea correcto, pero tener muy pocos puede hacer que confundamos ruido con una tendencia real.**
