---
title: Mahjoig Calc3
mermaid: true
---

```mermaid
graph TD;
    S["麻雀得点計算"] --- Q1{"５翻以上？"};
    Q1 -->|"はい"| M["満貫計算"];
    Q1 -->|"いいえ"| Q2{"`ピンフ型？"};
```
