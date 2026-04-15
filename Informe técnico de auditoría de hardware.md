# Informe técnico de auditoría de hardware
https://youtu.be/BD_8yiG3hz0?si=R3q8munfo_k3EQIq

Este informe tiene como objetivo analizar el procesador del equipo, comprobar sus características reales y compararlas con las especificaciones oficiales del fabricante. También se realiza una pequeña prueba de rendimiento para verificar si el comportamiento del hardware es el esperado.

---

## 1. Ficha de identificación por software

La información del procesador se ha obtenido mediante CPU-Z.

Datos detectados en el sistema:

- Modelo del procesador: AMD Ryzen 5 5500U
- Número de núcleos: 6
- Número de hilos: 12
- Frecuencia base: 2.1 GHz
- Frecuencia boost: 4.0 GHz
- Caché L3: 8 MB

Estos datos corresponden al hardware detectado por el sistema operativo.

---

## 2. Ficha técnica oficial del fabricante

La información oficial del procesador se ha consultado en la web de AMD (Product Specifications).

Datos oficiales del AMD Ryzen 5 5500U:

- Modelo: AMD Ryzen 5 5500U
- Núcleos: 6
- Hilos: 12
- Frecuencia base: 2.1 GHz
- Frecuencia boost: hasta 4.0 GHz
- Caché L3: 8 MB

Fuente oficial: https://www.amd.com/en/products/apu/amd-ryzen-5-5500u

En este caso, los datos del sistema coinciden con los datos oficiales del fabricante.

---

## 3. Tabla comparativa de especificaciones

| Característica   | Detectado por el sistema | Datos oficiales | ¿Coincide? |
|------------------|--------------------------|-----------------|------------|
| Modelo           | Ryzen 5 5500U           | Ryzen 5 5500U   | Sí         |
| Núcleos          | 6                        | 6               | Sí         |
| Hilos            | 12                       | 12              | Sí         |
| Frecuencia base  | 2.1 GHz                  | 2.1 GHz         | Sí         |
| Frecuencia boost | 4.0 GHz                  | 4.0 GHz         | Sí         |
| Caché L3         | 8 MB                     | 8 MB            | Sí         |

No se han detectado discrepancias entre el hardware reportado y el oficial.

---

## 4. Resultados del benchmark

Se ha realizado un test de rendimiento con CPU-Z Benchmark.

Resultados obtenidos:

- Single Core: 430 puntos
- Multi Core: 2800 puntos

Comparativa con CPU Monkey (valores medios):

- Single Core medio: 450 puntos
- Multi Core medio: 3000 puntos

Diferencia aproximada:

- Single Core: -4.4%
- Multi Core: -6.6%

Los resultados están dentro de un rango normal de variación, por lo que el rendimiento del procesador es correcto.

---

## 5. Conclusión y análisis de veracidad

Tras analizar los datos obtenidos, se puede concluir que el procesador AMD Ryzen 5 5500U funciona correctamente y coincide tanto en especificaciones como en rendimiento con los valores oficiales del fabricante.

No se han encontrado anomalías ni discrepancias entre lo reportado por el sistema y lo indicado por AMD. Además, el rendimiento en las pruebas de benchmark se mantiene dentro de los márgenes normales.

Este tipo de análisis es útil para detectar posibles diferencias entre lo que el sistema muestra y lo que realmente tiene el hardware, como ocurrió en el caso del “Corebook X”, donde se detectaron discrepancias entre el modelo anunciado y el procesador real.

En este caso, no se observa ningún indicio de manipulación ni limitación anormal del rendimiento.

---

## Fin del informe
