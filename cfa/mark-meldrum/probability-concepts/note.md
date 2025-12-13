# Probability Concepts

[Video link](https://www.markmeldrum.com/courses/2018-level-i/lessons/2018-quantitative-methods/topic/2018-probability-concepts/)

## Probability

> Random Variable
>
> Definition: A quantity whose outcomes (possible values) are unknown

> Event
>
> Definition: A specified set of outcomes (either a point or a range), denoted by capital letter e.g. $A$, $B$

> Probability of an event
>
> Definition: $P(A)$, such that $0 \leq P(A) \leq 1$ and $\sum^n_{i=1} P(A_i) = 1$, for any set of:
>
> - mutually exclusive events: if one happens, another can't
> - exhaustive events: covers all possible outcomes

With all these setup, we only need 2 elements:

1. Set of all distinct possible outcomes
1. The probability distribution

### Types of probability

> Empirical probability
>
> Definition: probability based on historical observations
>
> - Past is assumed to be representative of the future
> - Historical period must include occurrences of the event
>   - If no event happens in the past, then the probability of that happens must be $0$
>

> Subjective probability
>
> Definition: Adjust an **empirical probability** based on intuition or experience. When to use?
>
> - When there is a complete lack of empirical observations
> - Make a personal assessment
>
> Note: People's subjective probability tends to OVERWEIGHT events, which means OVERWEIGHT probability of that events happening.

> A priori probability
>
> Definition: Probability at based on deductive reasoning, with no subjective whatsoever.

## Odds

Expression of probability, but NOT probability

> Odds for E
>
> Definition: Odds for E is $$Odds_{for}(E) = \frac{P(E)}{1-P(E)}$$

Ex: $P(E) = 10\%$. Then the odds for E is $\frac{.1}{.9}$ or **1 to 9** (a to b). What does 1 to 9 mean?

- For each occurence of event E, we should expect **9 events of non-occurence**.
- NOTE: this is NOT **1 in 9**. 1 in 9 implies in **9 events, there is 1 event E occurring**.

Ex: Find $P(E)$ given odds of 1 to 9.

$$P(E) = \frac{1}{1+9} = 0.1 = 10\%$$

> Odds against E
>
> Definition: $$Odds_{against}(E) = \frac{1-P(E)}{P(E)}$$

Ex: Use example above, odds against E is $\frac{.9}{.1}$ is **9 to 1**.

- This means for every 9 non-occurences of $E$, we should expect 1 occurence of $E$.

Ex: EPS estimate: $3.98-4.25

$P(EPS > 4.25)$: there are two analyst opinions

- Odds of 1 to 7 **for** $P(E) = \frac{1}{1+7} = \frac{1}{8} = .125$
- Odds of 15 to 1 **against** $P(E) = \frac{1}{15+1} = \frac{1}{16}$

## Conditional Probability

### Unconditional

> Unconditional probability
>
> Definition: $P(E)$ - what is the probability of an event $E$ happening as is.

Ex: $E$ is event of an investment manager has a portfolio return more than risk free rate $r_p > r_f$. Then:

$$P(E) = \frac{Numerator}{Denominator}$$

- Numerator: no. of observations of $r_p > r_f$
- Denominator: no. of observations of $r_p$ (this is our probability space)

### Conditional

> Conditional probability
>
> Defintion: $P(E | B)$ - what is the probability of an event $E$ happening given $B$ happens.

Ex: Same example as above, but given that $r_p > 0\%$. Then:

$P(E | B)$

- Numerator: # of obs of $r_p > r_f$
- Denominator: # of obs of $r_p > 0$ (this is our probability space)

When we look at a probability, we should try to determine what kind of conditions the possible events can happen. This gives us more confidence in the probability more than the unconditional probability

> Formal statement of conditional probability:
>
> Definition: First requires "joint probability": $P(A \wedge B)$. Then, for $P(B) \neq 0$: $$P(A|B) = \frac{P(AB)}{P(B)}$$
> 

Rearranging the above formula and using the multiplication rules, we have

$$P(AB) = P(A|B) P(B)$$
$$P(BA) = P(B|A) P(A)$$

Then

$$P(AB) = P(BA)$$
$$P(A|B)P(B) = P(B|A)P(A)$$

For the $A$ OR $B$ case:

$$P(A\vee B) = P(A) + P(B) - P(AB)$$

Ex:

-- | Period 2 win ($C$) | Period 2 loss ($D$)
-- | -- | --
Period 1 win ($A$) | $52.7\%$ (1) | $47.3\%$ (3)
Period 1 loss ($B$) | $47.3\%$ (2) | $52.7\%$ (4)

Then we have the following event:

- (1): $P(C|A)$
- (2): $P(C|B)$
- (3): $P(D|A)$
- (4): $P(D|B)$

Question: Calculate $P(BD)$

$$P(BD) = P(D|B) P(B) = 52.7\% \cdot 50\% = 26.4\%$$

Ex: $P(A) = .35$ and $P(B) = .25$, where $A$ is limit order filled at 10, and $B$ is limit order filled at 9.75

$$P(A \vee B) = P(A) + P(B) - P(AB) = .35 + .25 - P(AB) (*)$$

How do we get $P(AB)$?

- Notice that logically, if $A$ happens then $B$ won't, but if $B$ happens, then $A$ definitely will! So $P(AB) = P(B)$

![alt text](image/1-conditional-probability-example.png)

Then $P(A \vee B) = (*) = .25$

How do we get $P(B|A)$?

$$P(B|A) = \frac{P(BA)}{P(A)} = \frac{.25}{.35} = .714$$

### Independence

> Independence
>
> Definition: Occurence of one event says nothing about the occurence of another
>

Ex: A coin toss. If you get heads the first toss, doesn't tell me anything about the second toss => Independent event. So we have:

$$P(A|B) = P(A)$$

so

$$P(AB) = P(A)P(B)$$

Continue at 40:10

Ex: We have two events:

- A: $EPS_{t+1} > EPS_t$ and $P(A) = .55$ based on historical observation
- B: $EPS_{t+1} < EPS_t$ and $P(B) = .45$ based on historical observation

These are called empirical probabilities because they are independent events

Calculate

$$P(EPS_{Q3} > EPS_{Q2} | EPS_{Q2} > EPS_{Q1})$$

$$= P(EPS_{t+1} > EPS_{t}) = .55$$

since the two events are independent.

Calculate

$$P(EPS_{t+2} < EPS_{t+1} \wedge EPS_{t+1} < EPS_t)$$

$$= P(EPS_{t+2} < EPS_{t+1}) \cdot P(EPS_{t+1} < EPS_t) = .45 \times .45 = .2025$$

since the two events are independent.

## Total Probability Rule

Let's say we have a scenario:

![alt text](image/2-total-probability-rule-example.png)

We have:

$$P(A) = P(ABC_{up} \wedge Expansion) + P(ABC_{up} \wedge Recession) (*)$$

Let:

- A: the probability of $ABC$ going up ($ABC_{up}$)
- S: the probability of an expansion ($Expansion$)
- S^c: the probability of a recession ($Recession$), the compliment of $S$

It must be true that

$$P(S) + P(S^c) = 1$$

Then:

$$(*) = P(AS) + P(AS^c) = P(A|S)P(S) + P(A|S^c) P(S^c)$$

Now, note that the probability we get for $ABC$ going up or down is empirical, but the probability of an $Expansion$ or $Recession$ is subjective.


> Total Probability Rule
>
> Definition: Probability of $A$ is the total probability of $A$ given all scenarios $S_1, S_2\cdots S_n$ for a finite $n$
>
> $$P(A) = P(A|S_1)P(S_1) + P(A|S_2)P(S_2) + \cdots P(A|S_n)P(S_n)$$
>
> In the case that $A$ is independent from $S_i$, then:
>
> $$P(A) = P(A)P(S_1) + P(A)P(S_2) + \cdots P(A)P(S_n)$$
> $$= P(A) [P(S_1) + P(S_2) + \cdots P(S_n)]$$
> $$= P(A)$$

## Expected Value

> Expected Value
>
> Definition: For $\sum^n_{i=1} P(X_i) = 1$,
>
> $$E(X) = P(X_1)X_1 + P(X_2)X_2 + \cdots + P(X_n)X_n$$
> $$ = \sum^n_{i=1} P(X_i)X_i$$

Ex: EPS forecast

EPS | P(x)
-- | --
2.60 | .15
2.45 | .45
2.20 | .24
2.00 | .16

Then

$$E(X) = .15(2.6) + .45(2.45) + .24(2.2) + .15(2) = 2.3405$$

### Variability of distribution of probability

We can use Variance:

$$\sigma^2(X) = E\left\{[X-E(X)]^2\right\}$$

Continue at 1:12:34
