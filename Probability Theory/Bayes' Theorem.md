# 貝氏定理

描述在已知一些條件$$E$$下，某事件$$H$$的發生概率。

$$
P(H|E) = \frac{P(E|H)P(H)}{P(E)}
$$

$$P(E|H)$$：已知有事件H後，條件E的發生概率。

$$P(H)$$：事件H的發生概率。

$$P(E)$$：條件E的發生概率。

$$P(H|E)$$：已知有條件E後，發生事件H的概率。

## 陰性陽性

真陽性(True Positive)

$$
P(H = YES|E = Positive) = \frac{P(E = Positive | H = YES)(P(H = YES))}{P(E = Positive)}
$$

假陽性(False Positive)

$$
P(H = NO|E = Positive) = \frac{P(E = Positive | H = NO)(P(H = NO))}{P(E = Positive)}
$$

真陰性(True Negative)

$$
P(H = NO|E = Negative) = \frac{P(E = Negative | H = NO)(P(H = NO))}{P(E = Negative)}
$$

假陰性(True Negative)

$$
P(H = YES|E = Negative) = \frac{P(E = Negative | H = YES)(P(H = YES))}{P(E = Negative)}
$$