# JFo 5.2 - Actividad 14

## Calculadora de impuestos por tramos

Calcula el impuesto progresivo sobre `income` con `if` / `else if` / `else`: hasta 20000 no se paga nada; entre 20000 y 50000 se paga un 10 % de lo que supere 20000; por encima de 50000 se pagan 3000 más un 20 % de lo que supere 50000. Imprime `Impuesto: <impuesto>` (valor `double`).

## Objetivo

- Leer el código base y corregirlo o completarlo.
- Ejecutar el programa y comprobar el resultado.
- Ejecutar los tests JUnit para confirmar la autocorrección.
- Hacer `git add`, `git commit` y `git push`.

## Salida esperada

```text
Impuesto: 1500.0
```

## Instrucciones para Eclipse

1. Importa este proyecto como proyecto Maven.
2. Abre `src/main/java/modulo5_2_actividad14/Actividad14.java`.
3. Corrige o completa el código.
4. Ejecuta `Run As > Java Application`.
5. Ejecuta `Actividad14Test.java` con `Run As > JUnit Test`.
6. Haz commit y push cuando la actividad funcione.

## GitHub Actions

- Sube tu trabajo a **tu rama** (no a `main`): el workflow `Autocorrección` compila y ejecuta los tests de cada actividad que hayas modificado.
- En la pestaña **Actions** del repositorio verás ✅ si la actividad está aprobada o ❌ si hay errores de compilación o tests que fallan.
