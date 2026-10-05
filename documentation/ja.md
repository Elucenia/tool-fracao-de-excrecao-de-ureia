<!-- ELUCENIA technical documentation · fracao-de-excrecao-de-ureia · ja · no clinical/professional/rights approval -->

# 尿素排泄分画（FEUr）

[条件・出典・許諾](https://elucenia.org/ja/tools/fracao-de-excrecao-de-ureia)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 尿中尿素

`uur`

mg/dL · 範囲: 10–5000

### 血清尿素

`pur`

mg/dL · 範囲: 10–600

### 尿中クレアチニン

`ucr`

mg/dL · 範囲: 1–500

### 血清クレアチニン

`pcr`

mg/dL · 範囲: 0.2–20

## 方法の版

FEUrea/Carvounis 2002：100×Uurea×PCr/(Purea×UCr)；尿素/BUNの量を統一

## 記載された計算式

FEUrea (%) = (尿中尿素 × 血清クレアチニン) ÷ (血清尿素 × 尿中クレアチニン) × 100。

血液と尿で同じ量を使えば，尿素でもBUNでも同じ結果。

## 限界・対象集団

2002年の研究は、利尿薬使用の有無がある腎前性の原因と尿細管壊死を含め、急性腎不全のエピソードを評価しました。この比較では尿素排泄分画は利尿薬の影響が少なかったものの、全ての干渉から独立することにはならず、閾値だけで原因も確定できません。

## 参考文献

- [Carvounis CP, Nisar S, Guro-Razuman S. Significance of the fractional excretion of urea in the differential diagnosis of acute renal failure. Kidney Int, 2002.](https://doi.org/10.1046/j.1523-1755.2002.00683.x)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
