<!-- ELUCENIA technical documentation · fracao-de-excrecao-de-ureia · pt-BR · no clinical/professional/rights approval -->

# Fração de excreção de ureia (FEUr)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/fracao-de-excrecao-de-ureia)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Ureia urinária

`uur`

mg/dL · intervalo: 10–5000

### Ureia sérica

`pur`

mg/dL · intervalo: 10–600

### Creatinina urinária

`ucr`

mg/dL · intervalo: 1–500

### Creatinina sérica

`pcr`

mg/dL · intervalo: 0,2–20

## Edição do método

FEUrea/Carvounis 2002:100×Uureia×PCr/(Pureia×UCr); grandezasureia/BUNconsistentes

## Fórmula documentada

FEUr (%) = (ureia urinária × creatinina sérica) ÷ (ureia sérica × creatinina urinária) × 100.

Ureia ou BUN dão o mesmo resultado, desde que a mesma grandeza seja usada no sangue e na urina.

## Limites e população

O estudo de 2002 avaliou episódios de insuficiência renal aguda, incluindo causas pré-renais com e sem diuréticos e necrose tubular. A FE de ureia foi menos influenciada pelos diuréticos nessa comparação; isso não a torna independente de todas as interferências nem confirma etiologia pelo corte isolado.

## Referências

- [Carvounis CP, Nisar S, Guro-Razuman S. Significance of the fractional excretion of urea in the differential diagnosis of acute renal failure. Kidney Int, 2002.](https://doi.org/10.1046/j.1523-1755.2002.00683.x)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
