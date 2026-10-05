<!-- ELUCENIA technical documentation · fracao-de-excrecao-de-ureia · zh · no clinical/professional/rights approval -->

# 尿素排泄分数（FEUr）

[条件、来源与许可](https://elucenia.org/zh/tools/fracao-de-excrecao-de-ureia)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 尿素（尿）

`uur`

mg/dL · 范围: 10–5000

### 血清尿素

`pur`

mg/dL · 范围: 10–600

### 尿肌酐

`ucr`

mg/dL · 范围: 1–500

### 血清肌酐

`pcr`

mg/dL · 范围: 0.2–20

## 方法版本

FEUrea/Carvounis 2002：100×Uurea×PCr/(Purea×UCr)；尿素/BUN测量量一致

## 已记录的公式

FEUrea (%) = (尿尿素 × 血清肌酐) ÷ (血清尿素 × 尿肌酐) × 100。

若血液和尿液使用同一测量量，尿素或BUN结果相同。

## 限制与适用人群

2002年的研究评估了急性肾衰竭事件，包括使用或未使用利尿剂的肾前性病因及肾小管坏死。在该比较中，尿素排泄分数受利尿剂的影响较小；这不意味着它不受任何干扰，也不能由单个阈值确认病因。

## 参考文献

- [Carvounis CP, Nisar S, Guro-Razuman S. Significance of the fractional excretion of urea in the differential diagnosis of acute renal failure. Kidney Int, 2002.](https://doi.org/10.1046/j.1523-1755.2002.00683.x)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
