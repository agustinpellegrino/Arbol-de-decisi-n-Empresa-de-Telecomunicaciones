# Arbol-de-decisi-n-Empresa-de-Telecomunicaciones

##  Descripción

Trabajo práctico de **Aprendizaje Automático** en el que se construyó un árbol de decisión utilizando el algoritmo **ID3**, con el objetivo de predecir si un cliente de una empresa de telecomunicaciones aceptaría una oferta de datos móviles.

##  Desarrollo

Se analizó un conjunto de datos de 10 clientes, considerando tres atributos:

- **Edad:** agrupada en joven, adulto y mayor.
- **Uso de datos:** clasificado en bajo, medio y alto.
- **Línea fija:** indica si el cliente posee una línea fija.

Se calculó la entropía inicial del conjunto y la ganancia de información de cada atributo para determinar cuál era el más adecuado para construir el árbol.

##  Resultados

| Atributo | Ganancia de información |
|---|---|
| Edad | 0.449 |
| Uso de datos | 0.600 |
| Línea fija | 1.000 |

El atributo **Línea fija** obtuvo la mayor ganancia de información, por lo que fue seleccionado como raíz del árbol.

##  Conclusión

El árbol de decisión permitió clasificar correctamente el **100 % de los datos analizados**, estableciendo que los clientes con línea fija aceptaron la oferta y aquellos sin línea fija la rechazaron.

Este trabajo permitió aplicar los conceptos de **entropía, ganancia de información y clasificación supervisada** mediante el algoritmo ID3.
