# JFo 5.2 - Actividad 13

## Validador de compra online

Una compra está permitida si el usuario tiene cuenta (`hasAccount`), el total del carrito (`cartTotal`) es de al menos 20.0 **y** el envío **no** está bloqueado (`shippingBlocked`). Combina las tres condiciones con `&&` y `!` en una variable `boolean` e imprime `Compra permitida: <valor>`.

## Objetivo

- Leer el código base y corregirlo o completarlo.
- Ejecutar el programa y comprobar el resultado.
- Ejecutar los tests JUnit para confirmar la autocorrección.
- Hacer `git add`, `git commit` y `git push`.

## Salida esperada

```text
Compra permitida: true
```

## Instrucciones para Eclipse

1. Importa este proyecto como proyecto Maven.
2. Abre `src/main/java/modulo5_2_actividad13/Actividad13.java`.
3. Corrige o completa el código.
4. Ejecuta `Run As > Java Application`.
5. Ejecuta `Actividad13Test.java` con `Run As > JUnit Test`.
6. Haz commit y push cuando la actividad funcione.

## GitHub Actions

- Sube tu trabajo a **tu rama** (no a `main`): el workflow `Autocorrección` compila y ejecuta los tests de cada actividad que hayas modificado.
- En la pestaña **Actions** del repositorio verás ✅ si la actividad está aprobada o ❌ si hay errores de compilación o tests que fallan.
