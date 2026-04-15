# Informe técnico de auditoría de hardware

Este informe tiene como objetivo analizar el procesador del equipo, comparar sus características reales con las especificaciones oficiales del fabricante y realizar una pequeña prueba de rendimiento para comprobar si el hardware funciona como debería.  
La actividad está basada en el caso estudiado de posibles discrepancias de hardware como el “caso Chuwi”.

---

## 1. Ficha de identificación por software

Para obtener la información del procesador se ha utilizado (CPU-Z / HWInfo64 / lscpu en Linux).

Los datos obtenidos del sistema son los siguientes:

- Modelo del procesador: (ESCRIBIR MODELO REAL)
- Número de núcleos: X
- Número de hilos: X
- Frecuencia base: X GHz
- Frecuencia boost: X GHz
- Caché L3: X MB

Estos datos reflejan lo que el sistema operativo detecta del hardware instalado en el equipo.

---

## 2. Ficha técnica oficial del fabricante

Después de identificar el procesador, se ha buscado la información oficial en la web del fabricante (Intel ARK o AMD Product Specifications).

Datos oficiales del procesador:

- Modelo: (MISMO MODELO)
- Núcleos: X
- Hilos: X
- Frecuencia base: X GHz
- Frecuencia boost: X GHz
- Caché L3: X MB

Fuente oficial: (pegar enlace de Intel ARK o AMD)

En esta parte es importante fijarse especialmente en la caché L3 y en las frecuencias máximas, ya que son datos clave para comparar el rendimiento real del procesador.

---

## 3. Tabla comparativa de especificaciones

A continuación se comparan los datos detectados por el sistema con los datos oficiales del fabricante:

| Característica | Detectado por el sistema | Datos oficiales | ¿Coincide? |
|----------------|--------------------------|-----------------|------------|
| Modelo         | X                        | X               | Sí / No    |
| Núcleos        | X                        | X               | Sí / No    |
| Hilos          | X                        | X               | Sí / No    |
| Frecuencia base| X GHz                    | X GHz           | Sí / No    |
| Frecuencia boost| X GHz                   | X GHz           | Sí / No    |
| Caché L3       | X MB                     | X MB            | Sí / No    |

En caso de que haya diferencias, puede deberse a limitaciones del equipo, configuración del sistema o incluso a posibles errores en la identificación del hardware, como ocurrió en el caso analizado del Ryzen 5 7430U que realmente correspondía a un 5500U con menor caché L3.

---

## 4. Resultados del benchmark

Se ha realizado una prueba de rendimiento utilizando (CPU-Z Benchmark / Geekbench).

Resultados obtenidos:

- Single Core: X puntos
- Multi Core: X puntos

Comparación con valores de referencia (CPU Monkey):

- Single Core medio: X puntos
- Multi Core medio: X puntos

Diferencia aproximada:

- Single Core: X %
- Multi Core: X %

En caso de una diferencia superior al 10-20%, puede indicar que el equipo no está rindiendo al nivel esperado para ese procesador, lo cual puede deberse a temperatura, limitaciones de hardware o configuración del sistema.

---

## 5. Conclusión y análisis de veracidad

Después de analizar todos los datos, se puede concluir que el procesador del equipo:

(ESCRIBIR CONCLUSIÓN PERSONAL)

En caso de que los resultados no coincidan completamente con lo esperado, puede deberse a diferentes factores como:
- Uso de memoria RAM en un solo canal
- Limitaciones térmicas (throttling)
- Configuración del sistema operativo
- Diferencias entre hardware real y el modelo anunciado

Este tipo de análisis es importante porque permite detectar si el hardware realmente corresponde con lo que dice el fabricante o si existe alguna anomalía en el rendimiento o en la identificación del procesador.

También es relevante mencionar que, en casos extremos como el “Corebook X”, fue necesario comprobar físicamente el chip mediante su código OPN para verificar su autenticidad, ya que el software podía mostrar información incorrecta o manipulada.

---

## Fin del informe
