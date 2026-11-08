# JFo 5.2 - Descripción de la ejecución condicional

Esta carpeta contiene 15 actividades autocorregibles.

## Actividades

01. Corrige el operador AND incorrecto
02. Corrige el operador OR incorrecto
03. Corrige el uso de NOT
04. Corrige una condición de beca
05. Corrige una condición con división entre cero
06. Comprueba si un estudiante obtiene beca
07. Comprueba si un estudiante entra en el equipo
08. Comprueba si un estudiante recibe tutoría gratuita
09. Interés por una película
10. Usa operador ternario para singular/plural
11. Calcula tarifa por edad
12. Clasificador de notas
13. Validador de compra online
14. Calculadora de impuestos por tramos
15. Descuento por tipo de televisión y tamaño

Cada subcarpeta `actividadNN` es un proyecto Maven independiente con tests JUnit 5 y workflow de GitHub Actions.

## Cómo entregar las actividades

La rama `main` está protegida: contiene los enunciados originales y no se puede modificar.
Cada alumno trabaja en **su propia rama**, con su nombre.

1. Clona el repositorio:
   `git clone https://github.com/java-foundations-2026-malaga/REPOSITORIO.git`
2. Crea tu rama con tu nombre y apellido, en minúsculas y sin tildes ni espacios (por ejemplo `juan-perez`):
   `git checkout -b juan-perez`
   (En Eclipse: botón derecho sobre el proyecto > `Team > Switch To > New Branch...`).
3. Importa en Eclipse la carpeta `actividadNN` que vayas a hacer (`File > Import... > Maven > Existing Maven Projects`), resuélvela y comprueba los tests con `Run As > JUnit Test`.
4. Haz commit y sube **tu rama**:
   `git add .` → `git commit -m "Actividad NN"` → `git push -u origin juan-perez`
   (En Eclipse: `Git Staging` > `Commit and Push...`).
5. En la pestaña **Actions** del repositorio verás el resultado de la autocorrección de cada actividad que hayas modificado: ✅ aprobada o ❌ con los errores.

Si al hacer push te aparece un error sobre `main`, es que estás en la rama equivocada: cambia a tu rama con `git checkout juan-perez`.
