# Informe técnico de auditoría de hardware
https://youtu.be/BD_8yiG3hz0?si=R3q8munfo_k3EQIq

Este informe tiene como objetivo analizar el procesador de un equipo, comprobar sus especificaciones reales mediante herramientas del sistema y compararlas con los datos oficiales del fabricante. Además, se realiza una prueba de rendimiento para verificar si el comportamiento del hardware es el esperado, tomando como referencia el análisis del “caso Chuwi”.

---

## 1. Ficha de identificación por software

La información del procesador se ha obtenido mediante la herramienta CPU-Z en Windows.

Datos detectados en el sistema:

- Modelo del procesador: AMD Ryzen 5 5500U
- Arquitectura: Zen 2
- Número de núcleos: 6
- Número de hilos: 12
- Frecuencia base: 2.1 GHz
- Frecuencia boost: hasta 4.0 GHz
- Caché L3: 8 MB

Estos datos representan la información que el sistema operativo reconoce del hardware instalado. En este caso se trata de un procesador de gama media orientado a portátiles, con un equilibrio entre consumo energético y rendimiento.

---

## 2. Ficha técnica oficial del fabricante

La información oficial ha sido consultada en la página de AMD (Product Specifications).

Datos oficiales del AMD Ryzen 5 5500U:

- Modelo: AMD Ryzen 5 5500U
- Arquitectura: Zen 2
- Núcleos: 6
- Hilos: 12
- Frecuencia base: 2.1 GHz
- Frecuencia boost: hasta 4.0 GHz
- Caché L3: 8 MB

Fuente oficial: https://www.amd.com/en/products/apu/amd-ryzen-5-5500u

En este caso, los datos del sistema coinciden completamente con los datos oficiales del fabricante, por lo que no se detectan inconsistencias en la identificación del procesador.

---

## 3. Tabla comparativa de especificaciones

| Característica    | Detectado por el sistema | Datos oficiales | ¿Coincide? |
|------------------|--------------------------|-----------------|------------|
| Modelo           | Ryzen 5 5500U            | Ryzen 5 5500U   | Sí         |
| Arquitectura     | Zen 2                    | Zen 2           | Sí         |
| Núcleos          | 6                        | 6               | Sí         |
| Hilos            | 12                       | 12              | Sí         |
| Frecuencia base  | 2.1 GHz                  | 2.1 GHz         | Sí         |
| Frecuencia boost | 4.0 GHz                  | 4.0 GHz         | Sí         |
| Caché L3         | 8 MB                     | 8 MB            | Sí         |

No se han encontrado discrepancias entre los datos del sistema y los datos oficiales del fabricante.

---

## 4. Resultados del benchmark

Se ha realizado una prueba de rendimiento utilizando CPU-Z Benchmark.

Resultados obtenidos:

- Single Core: 430 puntos
- Multi Core: 2800 puntos

Comparativa con CPU Monkey (valores medios del Ryzen 5 5500U):

- Single Core medio: 450 puntos
- Multi Core medio: 3000 puntos

Diferencia aproximada:

- Single Core: -4.4%
- Multi Core: -6.6%

Los resultados se encuentran dentro del margen normal de variación, por lo que el rendimiento del equipo es el esperado para este procesador.

---

## 5. Conclusión y análisis de veracidad

Tras el análisis realizado, se puede concluir que el procesador AMD Ryzen 5 5500U funciona correctamente y coincide tanto en especificaciones como en rendimiento con los datos oficiales del fabricante.

No se han detectado anomalías en la identificación del hardware ni diferencias significativas en el rendimiento. Esto indica que el sistema refleja correctamente las características del procesador instalado.

Este tipo de auditorías es importante porque permite comprobar si el hardware realmente coincide con lo que indica el fabricante o si existen posibles manipulaciones o limitaciones, como ocurrió en el “caso Chuwi”, donde se detectaron discrepancias entre el modelo anunciado y el rendimiento real del equipo.

En este caso concreto, no se observa ningún indicio de fraude ni de reducción anormal del rendimiento.

---

## Fin del informe
