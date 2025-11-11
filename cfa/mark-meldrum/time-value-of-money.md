# Interest rates

- Required rate of return: corporate finance  
- Discount rate: fixed income and equity evaluation  
- Opportunity cost: economics/corporate finance  
  - Choosing one project vs another  
- All points to interest rates here

Scenario:

- If we are offered to lend 1000 dollars and will receive 1500 in 2 years, and we want 10% to be interested, then would we take up this offer

Suppose I lend you $1000 for one year, I will want:  
R\_f

- Real risk-free rate for one year  
  - Rate I would get on very safe 1Y treasury  
  - But I would want more since price change  
+  inflation premium  
  - Preserve my purchasing power  
  - I want at least expected inflation for my money I lend you

- **These two combined make something called *nominal risk-free* rate**  
  - \[(1+r\_f)(1+inf)\] \- 1  
  - I don’t have to calculate this myself, I can take a look at the 1Y treasury market  
  - Market is reflecting these two components, and we can use this as-is  
  - Nominal risk-free rate basically means the bare minimum interest you can get *for a risk free investment*

+ default risk premium  
- I’m lending moolah to YOU, not the government  
- You might not pay me off at all  
- You ain’t risk-free, so I would want something extra for that  
- Varies by investment, credit, trust, bla bla  
- Depends on your risk profile

+ Liquidity premium  
- How easy can I exit?  
- How liquid is it?  
- I would also want extra buckies for taking on this risk too  
- I can buy marketable debts instead, why the hell would I buy from you?

+ Maturity premium  
- Higher my money is in the oven, the riskier it gets  
- This is higher the longer the investment period

- **These remaining threes: spread**  
  - Base \+ spread makes up the interest rate  
  - Specific to the borrower

Interest rates can change by a lot of things

- Inflation fluctuates  
- The borrower aint paying or the   
- More difficulty passing the bags  
- Can change a lot of reasons not only because of central banks

# Future Value

- P\_v: present value  
- F\_v: future value  
- R: interest rate  
- N: \# of compounding periods

- FV \= PV(1+r)^N: compounding  
- PV \= FV/(1+r)^N

- R & N must be compatible wrt t  
- Example: $100 for 5 years @ 6%  
  - Semi-annual  
  - Quarterly  
  - Etc….

Let’s do some exercise:

- $5M to invest @ 7% \=\> 5-yr annual CD  
- FV \= PV(1+r)^N \= 5M(1.07)^5 \= 7,012,58.65  
- PV should always be in negative form  
  - PV \= \-5M  
  - PMT \= 0  
  - Interest rate \= 7  
  - N \= 5  
  - Compute FV

- What if we have semi annual, then we can do:
    $$FV = 5M(1 + (0.07/2))^{10} = 5M(+$$

## Another example of Future Value
```
2.5M yen @ 8% for 6-years
```
$$FV = PV(1+r)^N = 2.5M(1.08)^6 = 3,967,186$$

This is pretty easy, let's do something more fun
```
$10M @ t_5, invested @9%. Find FV @ t_15 as of t_0.
```
We can just simply calculate for as long as the money is invested:
$$ FV = 10M(1.09)^{10} \approx 23.7M$$

Let's see if we are right. First find PV at $t_0$:
$$PV = \frac{FV}{(1+r)^N} = \frac{10M}{(1.09)^5} \approx 7M$$

then check:
$$FV = 7M (1.09)^{15} \approx 23.7M$$

basically the same, so we can just calculate as is at the start of $t_5$

# Compounding frequency

Stated annual interest rate $r_s$ (quoted interest rate)
$$ FV = PV(1+\frac{r_s}{m})^{mN}$$

Example:
```
2-yr CD @ 8% quarterly
```
We have:
$$10,000(1+.08/4)^{4\cdot 2} = 11,716.59$$

These will be very important when we comes to the quantitative section.

## Continuous compounding
Very common with derivatives, especially for futures and forwards. You have to use this because that's what the market uses.

```
$100 @ 5%
```

| Compounding Frequency| FV | Effective Annual Rate (EAR)|
|---|---|---|
| annually | $105 | 5% |
| semi-annual | $105.06 | 5.06% |
| quarterly | $105.09 | 5.09% |
| monthly | $105.12 | 5.12% |
| daily | $105.13 | 5.13% |
| **continuous** | $100e^{r_sN}$ = 105.13|  5.13%

Tips: continuous compounding yield very close to daily compounding

### EAR
How to calculate?
$$EAR = (1+\frac{r_s}{m})^m - 1$$

For continuous compounding, a little different:
$$ EAR = e^{r_s} - 1$$

if we know EAR, we can solve for $r_s$.

Continue at 41:31
