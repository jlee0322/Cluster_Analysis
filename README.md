## 專案概述

透過群聚分析方法，深入研究 IRIS 資料集和自選的 UCI ML repository 資料集。並採用 K-means、階層式分群、DBSCAN 這三種群聚分析方法，從效率和品質的角度進行比較。

## 資料集一 - IRIS 資料集

**1. 資料集介紹：**
   - 使用 [IRIS 資料集](https://archive.ics.uci.edu/ml/datasets/iris)。

**2. 分群分析：**
   - 運用 K-means、階層式分群、DBSCAN 進行 3 群的分群。
   - 評估分群所需時間。
   - 利用 Purity 指標評估分群品質。

**3. 階層式分群可視化：**
   - 以 Dendrogram 展示階層式分群結果。

## 資料集二 - 自選 UCI ML repository 資料集

**1. 資料集選擇：**
   - 從 [UCI ML repository](https://archive.ics.uci.edu/ml/index.php) 中自選一資料集，筆數需超過 2000。
   - 此選擇使用"bank"資料集。

**2. 分群分析：**
   - 使用 K-means、階層式分群、DBSCAN 進行群聚分析。
   - 評估分群所需時間。
   - 選擇兩個品質衡量指標，深入比較分群結果。

**3. 階層式分群可視化：**
   - 利用 Dendrogram 呈現階層式分群結構。

## 專案成果

- 分析不同群聚分析方法的效能和品質。
- 提供直觀的階層樹視覺化。
