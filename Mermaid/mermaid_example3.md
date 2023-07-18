1. フローチャート
```mermaid
graph LR
    A[開始] --> B{条件1}
    B -- 条件1が真 --> C[処理1]
    B -- 条件1が偽 --> D{条件2}
    D -- 条件2が真 --> E[処理2]
    D -- 条件2が偽 --> F[終了]
    E --> B
``` 

#####例
```mermaid
graph LR
    A[起床] --> B{朝}
    B -- 条件1が真 --> C[準備]
    B -- 条件1が偽 --> D{条件2:夜中}
    D -- 条件2が真 --> E[睡眠　1時間後に起床]
    D -- 条件2が偽 --> F[睡眠]
    E --> B
``` 
---
ノードの作成
```mermaid
graph LR
    A
```
```
#code
graph LR
    A
```
---
ノードをひし形にする
```mermaid
graph LR
    A{"おはよう"}
```
```
#code
graph LR
    A{"おはよう"}
```
---
矢印で結ぶ
```mermaid
graph LR
    A-->B
```
```
#code
graph LR
    A-->B
```
---
矢印の上にテキストを作成
```mermaid
graph LR
    A--"こんにちは"-->B
```
```
#code
graph LR
    A--"こんにちは"-->B
```