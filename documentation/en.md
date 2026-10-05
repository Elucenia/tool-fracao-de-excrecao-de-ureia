<!-- ELUCENIA technical documentation · fracao-de-excrecao-de-ureia · en · no clinical/professional/rights approval -->

# Fractional excretion of urea (FEUrea)

[conditions, sources and permissions](https://elucenia.org/en/tools/fracao-de-excrecao-de-ureia)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Urine urea

`uur`

mg/dL · range: 10–5000

### Serum urea

`pur`

mg/dL · range: 10–600

### Urine creatinine

`ucr`

mg/dL · range: 1–500

### Serum creatinine

`pcr`

mg/dL · range: 0.2–20

## Method edition

FEUrea/Carvounis 2002: 100×Uurea×PCr/(Purea×UCr); consistent urea/BUN quantities

## Documented formula

FEUrea (%) = (urine urea × serum creatinine) ÷ (serum urea × urine creatinine) × 100.

Urea or BUN yields the same result if the same quantity is used in blood and urine.

## Limits and population

The 2002 study assessed episodes of acute renal failure, including prerenal causes with and without diuretics and tubular necrosis. Urea fractional excretion was less affected by diuretics in that comparison; this does not make it independent of all interference or confirm the cause from a cutoff alone.

## References

- [Carvounis CP, Nisar S, Guro-Razuman S. Significance of the fractional excretion of urea in the differential diagnosis of acute renal failure. Kidney Int, 2002.](https://doi.org/10.1046/j.1523-1755.2002.00683.x)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
