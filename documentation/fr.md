<!-- ELUCENIA technical documentation · fracao-de-excrecao-de-ureia · fr · no clinical/professional/rights approval -->

# Fraction d’excrétion de l’urée (FEUrée)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/fracao-de-excrecao-de-ureia)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Urée urinaire

`uur`

mg/dL · intervalle: 10–5000

### Urée sérique

`pur`

mg/dL · intervalle: 10–600

### Créatinine urinaire

`ucr`

mg/dL · intervalle: 1–500

### Créatinine sérique

`pcr`

mg/dL · intervalle: 0,2–20

## Édition de la méthode

FEUrea/Carvounis 2002 : 100×Uurea×PCr/(Purea×UCr) ; grandeurs urée/BUN cohérentes

## Formule documentée

FEUrea (%) = (urée urinaire × créatinine sérique) ÷ (urée sérique × créatinine urinaire) × 100.

Urée ou BUN donnent le même résultat si la même grandeur est utilisée dans le sang et l’urine.

## Limites et population

L’étude de 2002 a évalué des épisodes d’insuffisance rénale aiguë, dont des causes prérénales avec ou sans diurétiques et une nécrose tubulaire. La fraction d’excrétion de l’urée était moins influencée par les diurétiques dans cette comparaison ; cela ne la rend pas indépendante de toutes les interférences ni ne confirme une étiologie par le seul seuil.

## Références

- [Carvounis CP, Nisar S, Guro-Razuman S. Significance of the fractional excretion of urea in the differential diagnosis of acute renal failure. Kidney Int, 2002.](https://doi.org/10.1046/j.1523-1755.2002.00683.x)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
