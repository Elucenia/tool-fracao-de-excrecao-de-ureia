<!-- ELUCENIA technical documentation · fracao-de-excrecao-de-ureia · it · no clinical/professional/rights approval -->

# Frazione di escrezione dell’urea (FEUrea)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/fracao-de-excrecao-de-ureia)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Urea urinaria

`uur`

mg/dL · intervallo: 10–5000

### Urea sierica

`pur`

mg/dL · intervallo: 10–600

### Creatinina urinaria

`ucr`

mg/dL · intervallo: 1–500

### Creatinina sierica

`pcr`

mg/dL · intervallo: 0,2–20

## Edizione del metodo

FEUrea/Carvounis 2002: 100×Uurea×PCr/(Purea×UCr); grandezze urea/BUN coerenti

## Formula documentata

FEUrea (%) = (urea urinaria × creatinina sierica) ÷ (urea sierica × creatinina urinaria) × 100.

Urea o BUN danno lo stesso risultato se si usa la stessa grandezza in sangue e urine.

## Limiti e popolazione

Lo studio del 2002 ha valutato episodi di insufficienza renale acuta, incluse cause prerenali con e senza diuretici e necrosi tubulare. La frazione di escrezione dell’urea è stata meno influenzata dai diuretici in questo confronto; ciò non la rende indipendente da ogni interferenza né conferma l’eziologia dalla sola soglia.

## Riferimenti

- [Carvounis CP, Nisar S, Guro-Razuman S. Significance of the fractional excretion of urea in the differential diagnosis of acute renal failure. Kidney Int, 2002.](https://doi.org/10.1046/j.1523-1755.2002.00683.x)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
