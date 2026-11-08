# JFo 5.2 - Actividad 15

## Descuento por tipo de televisión y tamaño

Calcula el descuento con `if` anidados: si `tvType` es `"color"`, el descuento es 12 cuando `size` es 30 o más y 8 en otro caso; si no es de color, el descuento es 5. Compara cadenas con `equals` y usa llaves para que cada `else` quede asociado al `if` correcto. Imprime `Descuento: <descuento>`.

## Objetivo

- Leer el código base y corregirlo o completarlo.
- Ejecutar el programa y comprobar el resultado.
- Ejecutar los tests JUnit para confirmar la autocorrección.
- Hacer `git add`, `git commit` y `git push`.

## Salida esperada

```text
Descuento: 8
```

## Instrucciones para Eclipse

1. Importa este proyecto como proyecto Maven.
2. Abre `src/main/java/modulo5_2_actividad15/Actividad15.java`.
3. Corrige o completa el código.
4. Ejecuta `Run As > Java Application`.
5. Ejecuta `Actividad15Test.java` con `Run As > JUnit Test`.
6. Haz commit y push cuando la actividad funcione.

## GitHub Actions

- Sube tu trabajo a **tu rama** (no a `main`): el workflow `Autocorrección` compila y ejecuta los tests de cada actividad que hayas modificado.
- En la pestaña **Actions** del repositorio verás ✅ si la actividad está aprobada o ❌ si hay errores de compilación o tests que fallan.
