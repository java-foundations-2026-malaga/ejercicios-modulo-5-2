# JFo 5.2 - Actividad 09

## Interés por una película

Te interesa una película si el precio (`price`) es como máximo 15.0 **y** su valoración (`rating`) es de al menos 4. Comprueba ambas condiciones con `&&`: imprime `Me interesa ver la película` o, en caso contrario, `No me interesa ver la película`.

## Objetivo

- Leer el código base y corregirlo o completarlo.
- Ejecutar el programa y comprobar el resultado.
- Ejecutar los tests JUnit para confirmar la autocorrección.
- Hacer `git add`, `git commit` y `git push`.

## Salida esperada

```text
Me interesa ver la película
```

## Instrucciones para Eclipse

1. Importa este proyecto como proyecto Maven.
2. Abre `src/main/java/modulo5_2_actividad09/Actividad09.java`.
3. Corrige o completa el código.
4. Ejecuta `Run As > Java Application`.
5. Ejecuta `Actividad09Test.java` con `Run As > JUnit Test`.
6. Haz commit y push cuando la actividad funcione.

## GitHub Actions

- Sube tu trabajo a **tu rama** (no a `main`): el workflow `Autocorrección` compila y ejecuta los tests de cada actividad que hayas modificado.
- En la pestaña **Actions** del repositorio verás ✅ si la actividad está aprobada o ❌ si hay errores de compilación o tests que fallan.
