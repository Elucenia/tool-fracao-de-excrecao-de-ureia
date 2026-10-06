<!-- ELUCENIA technical documentation · fracao-de-excrecao-de-ureia · es · no clinical/professional/rights approval -->

# Fracción de excreción de urea (FEUrea)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/fracao-de-excrecao-de-ureia)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Urea urinaria

`uur`

mg/dL · intervalo: 10–5000

### Urea sérica

`pur`

mg/dL · intervalo: 10–600

### Creatinina urinaria

`ucr`

mg/dL · intervalo: 1–500

### Creatinina sérica

`pcr`

mg/dL · intervalo: 0,2–20

## Edición del método

FEUrea/Carvounis 2002: 100×Uurea×PCr/(Purea×UCr); magnitudes urea/BUN coherentes

## Fórmula documentada

FEUrea (%) = (urea urinaria × creatinina sérica) ÷ (urea sérica × creatinina urinaria) × 100.

Urea o BUN dan igual resultado si se usa la misma magnitud en sangre y orina.

## Límites y población

El estudio de 2002 evaluó episodios de insuficiencia renal aguda, incluidas causas prerrenales con y sin diuréticos y necrosis tubular. La fracción de excreción de urea se vio menos influida por los diuréticos en esa comparación; esto no la hace independiente de todas las interferencias ni confirma la etiología por un punto de corte aislado.

## Referencias

- [Carvounis CP, Nisar S, Guro-Razuman S. Significance of the fractional excretion of urea in the differential diagnosis of acute renal failure. Kidney Int, 2002.](https://doi.org/10.1046/j.1523-1755.2002.00683.x)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

FEUr ≤ 35%: sugiere azotemia prerrenal

| Detalles del resultado | |
| --- | --- |
| Referencia (Carvounis 2002) | prerrenal: media de 25 a 28% · NTA: media de 58,6% |


### 2

FEUr ≤ 35%: sugiere azotemia prerrenal

| Detalles del resultado | |
| --- | --- |
| Referencia (Carvounis 2002) | prerrenal: media de 25 a 28% · NTA: media de 58,6% |


### 3

FEUr > 35%: sugiere lesión tubular (necrosis tubular aguda)

| Detalles del resultado | |
| --- | --- |
| Referencia (Carvounis 2002) | prerrenal: media de 25 a 28% · NTA: media de 58,6% |

