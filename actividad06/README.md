# JFo 5.2 - Actividad 06

## Comprueba si un estudiante obtiene beca

Un estudiante obtiene la beca si su nota (`grade`) es de al menos 88 **y** no tiene ninguna ausencia (`numberDaysAbsent`). Usa `&&` en un `if`: imprime `You qualify for the scholarship` o, en caso contrario, `You do not qualify for the scholarship`.

## Objetivo

- Leer el código base y corregirlo o completarlo.
- Ejecutar el programa y comprobar el resultado.
- Ejecutar los tests JUnit para confirmar la autocorrección.
- Hacer `git add`, `git commit` y `git push`.

## Salida esperada

```text
You qualify for the scholarship
```

## Instrucciones para Eclipse

1. Importa este proyecto como proyecto Maven.
2. Abre `src/main/java/modulo5_2_actividad06/Actividad06.java`.
3. Corrige o completa el código.
4. Ejecuta `Run As > Java Application`.
5. Ejecuta `Actividad06Test.java` con `Run As > JUnit Test`.
6. Haz commit y push cuando la actividad funcione.

## GitHub Actions

- Sube tu trabajo a **tu rama** (no a `main`): el workflow `Autocorrección` compila y ejecuta los tests de cada actividad que hayas modificado.
- En la pestaña **Actions** del repositorio verás ✅ si la actividad está aprobada o ❌ si hay errores de compilación o tests que fallan.
