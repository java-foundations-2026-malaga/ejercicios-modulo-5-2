# JFo 5.2 - Actividad 10

## Usa operador ternario para singular/plural

Imprime `I scored N goal` si `numberOfGoals` es 1 y `I scored N goals` en cualquier otro caso. Elige entre singular y plural con el operador ternario `?:`, sin usar `if`.

## Objetivo

- Leer el código base y corregirlo o completarlo.
- Ejecutar el programa y comprobar el resultado.
- Ejecutar los tests JUnit para confirmar la autocorrección.
- Hacer `git add`, `git commit` y `git push`.

## Salida esperada

```text
I scored 3 goals
```

## Instrucciones para Eclipse

1. Importa este proyecto como proyecto Maven.
2. Abre `src/main/java/modulo5_2_actividad10/Actividad10.java`.
3. Corrige o completa el código.
4. Ejecuta `Run As > Java Application`.
5. Ejecuta `Actividad10Test.java` con `Run As > JUnit Test`.
6. Haz commit y push cuando la actividad funcione.

## GitHub Actions

- Sube tu trabajo a **tu rama** (no a `main`): el workflow `Autocorrección` compila y ejecuta los tests de cada actividad que hayas modificado.
- En la pestaña **Actions** del repositorio verás ✅ si la actividad está aprobada o ❌ si hay errores de compilación o tests que fallan.
