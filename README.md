# 🚖 Patrones de viajes en chicago

## 🔍 Introducción
Una base de datos con información sobre viajes en taxi en Chicago.  

## 🎯 Objetivo
Encontrar patrones en la información disponibl. Comprender las prefrencias de los pasajeros y el impacto de los factores externos en los viajes.    

## 🛠️ Tecnologías Utilizadas
- **Procesamiento de Datos**: pandas, numpy, Python  
- **Visualización**: matplotlib, seaborn  

## 📈 Pasos Clave (Metodología)
### 1️⃣ Análisis y Preparación de Datos
- Recopilación y limpieza de datos históricos de pedidos.  
- Análisis exploratorio de tendencias y estacionalidad en la demanda de taxis.  


## 📊 Resultados
La hipotésis nula fue con base a la duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare no cambia en los sábados lluviosos. Esto significa que no hay una diferencia significativa en la duración promedio de los viajes entre los sábados lluviosos y los sábados no lluviosos.

La hipotesis alternativa sería lo contrario es decir que la duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia en los sábados lluviosos. Aquí se postula que existe una diferencia significativa en la duración promedio de los viajes entre los sábados lluviosos y los no lluviosos. Si la hipótesis alternativa es cierta, entonces los sábados lluviosos afectan la duración del viaje.

El criterio usado para probar las hipótesis fue una prueba t de muestras independientes ya que una prueba t de muestras independientes compara las medias de dos grupos independientes, las duraciones de los viajes en sábados lluviosos y las duraciones en sábados no lluviosos. Queriamos comprobar si las medias de los dos son significativamente diferentes.

Click to add a cell.

## 🚀 Cómo Ejecutarlo
```bash
