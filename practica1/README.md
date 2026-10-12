# Práctica 1 · La serie de Maclaurin y el criterio de paro

**UEA 1151039 · Métodos Numéricos en Ingeniería · Trimestre 26-O · UAM Azcapotzalco**
**Profesor:** M. en C. Gabriel Hurtado Avilés

| | |
|---|---|
| Equipo: Trabajo individual| |
| Integrantes: Zaragoza López Alexander, 2173037782, ingeniería mecánica | |
| Repositorio de la Tarea 1 de [Alexaner Zaragoza López](https://github.com/alexzaragozalpz-hash/Metodos-numericos-Alexander-ZL-UAM-AZC-26O)| |
| Fecha: 12 de octubre de 2026| |

## 1. Octave y Python

Compilación en Octave:

![Octave](image.png)

Compilación en Python:

![Python](image-1.png)

Tabla de la lámina 25:

![Lámina 25](image-2.png)

¿Coinciden con la lámina 25 de la unidad I?

Las tablas mostradas por los programas compilados son idénticas pero se observa que sifras significativas en la tabla de la lámina 25 son menores a los presentados por los programas, por lo que se redondean los valores esperados, además, se observa que los programas solo muestran 6 columnas de datos mientras que la lámina muestra una fila extra.

## 2. Las dos líneas que completamos en `maclaurin.c`

```c
/* termino = (termino*X)/n; */
/* ea = fabs((aprox - anterior) / aprox) * 100.0; */
```

![C](image-3.png)

## 3. Más cifras significativas

| Cifras | εs (%) | Términos | Aproximación | Error verdadero (%) |
|---|---|---|---|---|
| 3 | | | | |
| 6 | | | | |
| 17 | | | | |

1. ¿Cuántos términos hacen falta en cada caso?
2. En cada fila de la tabla, ¿εa es mayor o menor que εt? ¿Por qué conviene detenerse con εa?
3. Con 17 cifras el programa termina. ¿Cuántas cifras del resultado son correctas en realidad?
   Relaciónenlo con 0.1 + 0.2 de la Tarea 1.

## Uso de inteligencia artificial

Ninguno / Cuál y para qué.

## Referencias

