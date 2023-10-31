---
title:  "Unsupervised Learning Basics"
search: true
categories: 
  - Unsupervised Learning
use_math: true
last_modified_at: 2023-10-31T10:51:34-05:00
---
https://www.youtube.com/watch?v=V9HcvXliJmw
위 강의의 내용을 정리하였다.

## 1. Basic Probability
### 조건부 확률
* $P(y|x) = \frac{P(x, y)}{P(x)}$
* $P(x,y) = P(y|x) P(x) = P(x|y) P(y)$

* $P(x_1,x_2,x_3) = P(x_1|x_2,x_3)P(x_2|x_3)P(x_3)$ 
    ###### Note: $P(x_2, x_3) = P(x_2|x_3)P(x_3)$
* $P(x_1,x_2, ..., x_n) = P(x_1|x_2,...,x_n)P(x_2|x_3,...,x_n) ...P(x_{n-1}|x_n)\cdot P(x_n)$

### Bayes Rule
* $P(y|x) = \frac{P(x|y)P(y)}{P(x)}$

### 전체 확률의 법칙(이산형)

