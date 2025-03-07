# Resolución del Problema del Viajante con Algoritmos Genéticos

## 📌 Descripción
Este repositorio contiene la implementación de un algoritmo genético para resolver el **Problema del Viajante (TSP)**, optimizando la ruta más eficiente para recorrer un conjunto de ciudades y regresar al punto de partida.

Este proyecto fue desarrollado como trabajo final de la asignatura de Computacion en tercer curso del grado de Ingeniería Informática en la Universidad Pública de Navarra (UPNA).

## 🏆 Objetivos del Proyecto
- Aplicar **algoritmos genéticos** para la optimización de rutas.
- Comparar distintas estrategias de **selección, cruzamiento y mutación**.
- Evaluar el impacto de los parámetros del algoritmo en la calidad de las soluciones.

## 🚀 Tecnologías Utilizadas
- **Python** 🐍
- **NumPy** para la manipulación de datos.
- **Matplotlib** para la visualización de los resultados.
- **Algoritmos genéticos** implementados desde cero.

## 📂 Contenido del Proyecto
1. **Introducción y objetivos**: Descripción del problema y su relevancia.
2. **Algoritmos Genéticos**: Explicación del funcionamiento y operadores.
3. **Planteamiento del problema**:
   - Codificación de cromosomas.
   - Definición de la función de coste.
4. **Experimentación**:
   - Comparación de diferentes métodos de selección y cruzamiento.
   - Evaluación con y sin mutaciones.
5. **Resultados y análisis**.
6. **Conclusiones**.

## 📊 Experimentación
Se realizaron pruebas con distintas configuraciones del algoritmo:
- **Métodos de selección**: Ruleta, Torneo (k=2, k=5, k=10).
- **Métodos de cruzamiento**: PMX (Cruzamiento Parcialmente Mapeado), Orden.
- **Métodos de mutación**: Intercambio, Inserción.
- **Población inicial**: 100 individuos.
- **Número de generaciones**: 1000.

El mejor resultado obtenido fue **una ruta óptima de 4367 km** aplicando **Cruzamiento Basado en Orden y Selección por Ruleta**.
