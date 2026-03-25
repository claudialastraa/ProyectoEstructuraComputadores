# Proyecto Estructura de Computadores

Proyecto de programación en ensamblador realizado para la asignatura **Estructura de Computadores** del **Grado en Ingeniería Informática (UPM)**.

## Descripción

Este proyecto consiste en la implementación, en **ensamblador Motorola 88110**, de un conjunto de subrutinas para la **compresión y descompresión sin pérdida de texto en memoria**. El objetivo de la práctica es trabajar la programación a bajo nivel, el uso de pila, el paso de parámetros, la manipulación de memoria y la depuración de programas en ensamblador.

El enunciado planteaba desarrollar distintas rutinas que, en conjunto, permitieran comprimir un texto, descomprimirlo posteriormente y verificar que el resultado final coincidía exactamente con el original.

## Subrutinas implementadas

En el proyecto se trabajan las siguientes subrutinas:

- `LongCad`
- `BuscaCar`
- `CoincidenCad`
- `BuscaMax`
- `PoneBitA1`
- `LeeBit`
- `Comprime`
- `Descomprime`
- `Verifica`

## Resultado

Proyecto calificado con un **9,42/10**.

El código **superó todas las pruebas** teniendo un 10 en esta parte, incluyendo las correspondientes a las subrutinas principales y auxiliares del proyecto. Además, la **memoria del trabajo aportó valor adicional a la calificación**, al documentar el proceso de desarrollo, los casos de prueba utilizados y los errores corregidos durante la implementación, lo unico que me prejudico de forma sutil fue el examen.

## Pruebas y validación

La práctica incluía una evaluación basada en pruebas sobre distintas subrutinas, con hitos intermedios y validación específica de rutinas como `Comprime`, `Descomprime` y `Verifica`. En la memoria del proyecto se recogen casos de prueba representativos, comprobando valores devueltos, efectos en memoria y consistencia entre compresión y descompresión. :contentReference[oaicite:3]{index=3} :contentReference[oaicite:4]{index=4}

Entre los casos documentados aparecen pruebas para `LeeBit`, `Comprime`, `Descomprime` y `Verifica`, así como incidencias detectadas y corregidas durante el desarrollo, especialmente en `Comprime` y `Verifica`. :contentReference[oaicite:5]{index=5} :contentReference[oaicite:6]{index=6}

## Memoria

La memoria no se limita a describir el proyecto, sino que también recoge el trabajo realizado, el proceso de depuración, los casos de prueba empleados y las decisiones tomadas durante la implementación. Se documentan tanto pruebas proporcionadas por el departamento como pruebas adicionales diseñadas para comprobar mejor el comportamiento de las subrutinas. :contentReference[oaicite:7]{index=7}

## Tecnologías utilizadas

- Ensamblador **Motorola 88110**
- Emulador / entorno de trabajo **e88110** :contentReference[oaicite:8]{index=8} :contentReference[oaicite:9]{index=9}

## Estructura del repositorio

```text
.
├── README.md
├── src/    # Código fuente en ensamblador
├── bin/    # Archivos binarios
└── docs/   # Memoria y documentación
