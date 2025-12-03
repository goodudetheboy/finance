
# Discounted Cash Flow Application

## Net Present Value (NPV) 

A company has an inflow and outflow of cash. We want to get the Net Present Value of what they have currently. Discount rate $r$ is usually refred to as opportunity cost of capital, typically the Weighted Average Cost of Capital (WACC, will see more in Corporate Finance).

> Investment Rule: when considering which project to do, if NPV > 0 => Accept, else Reject

> How to calculate NPV? 2 step process:
>
> 1. Calculate $PV(inflows)$
> 1. Calculate $PV(outflows)$
>
> Then $NPV = PV(inflows) - PV(outflows)$

Ex: Let's say we have a project that have an inflow of $.5$, $.75$, $1.35$ at $t=1,2,3$ respectively, with a WACC of $10\%$. We have a one-time outflow of $-2$. We want to see if this is worth it:

$$NPV = PV(inflows) - PV(outflows) = 2,088,655 - 2,000,000 > 0$$

Looks like this will be a profitable one, so acccept.

Ex: We can make an investment at $t=0$ of $\$1M$, which provides a perpetuity of $150k$ every payment, with a WACC = $10\%$. We have that

$$PV(inflows) = \frac{A}{r} = \frac{150k}{0.1} = \$1.5M$$
$$PV(outflows) = \$1M$$
$$NPV = PV(inflows) - PV(outflows) = 1.5M - 1M = \$0.5M > 0$$

So we accept this investment.

Ex: What if WACC = $15\%$?

$$PV(inflows) = 1M$$

Then $NPV=0$, covers cost of capital but create $0 shareholder wealth. So nah, not so profitable. Usually if the closer $NPV$ is to 0, then think twice

## Internal Rate of Return (IRR)

> Def: The discount rate that results in $NPV = 0$

This is usually used in Fixed-Income to get the Yield-to-Maturity (only valid if coupons can be reinvested at the YTM rate).

IRR assumes that cash flow, when realized, can be reinvested at the project same IRR, but this is not always realistic.

So for IRR, we have

$$0 = \frac{CF_0}{1+IRR}^0 + \frac{CF_1}{1+IRR}^1 + \cdots + + \frac{CF_N}{1+IRR}^N$$

Usually, the first cashflow is the investment $CF_0$. So, to fin IRR, we can usually just solve from:

$$Investment = PV (CF)$$

### Maintenance investment

Let's say for our project/investment, we have maintenance paid every some period of time.
![alt text](image/1-maintenance-investment-for-irr.png)

This will usually mean there will be more than 1 IRR. In this case, IRR won't work, **go with NPV** instead.

> Investment Rule: If IRR > WACC, Accept, else Reject

### Examples
Ex: Let's say we invest $\$1M$ for a perpetuity of $\$150k$, with a WACC of $10\%$. What's the IRR?

To find IRR, let

$$Inv = PV(inflows) = A$$

$$ 1M = \frac{150k}{IRR}$$

$$IRR = 150k/1M = 15\%$$

this is more than the WACC, so not worth it. REJECT

Ex: Investment $\$1,000$ at $t=0$, pays $\$294.8$ from $t=1$ to $t=5$. What if WACC is $11\%$, is this investment worth it?

Find NPV:

$$PV_i = 294.8\left[\frac{1-(1.11)^5}{.11}\right] = 1089.55$$

$$PV_o = 1000$$

Then

$$NPV = 1089.55 - 1000 = 89.55 > 0$$

Accept!

What about the IRR? Let

$$Inv = A\left[\frac{1-(1+IRR)^{-5}}{IRR}\right]$$

$$1000 = 294.8\left[\frac{1-(1+IRR)^{-5}}{IRR}\right]$$

Then
$$IRR = 14.5\% < 15\% = WACC$$

Accept!

## Caveats

> These two rules using NPV and IRR to decide an investment is worth it are NOT interchangeable. Good rule of thumb: When IRR & NPV differs, choose the NPV side!

Continue at 18:45

## Portfolio Return

Let's say we buy an asset at price $P_0$, and sell at price $P_1$, then Holding Period Return $HPR = \frac{P_1-P_0}{P_0}$.

Let's say while we're holding that asset, we receive CF of D_1, then $HPR = \frac{P_1 - P_0 + D_1}{P_0}$.

Question: How to calculate HPR if:

- payment spans several periods: Called money-weighted rate of return
- P_0 includes multiple additions/withdrawals: Called time-weighted rate of return

Solution: Use IRR, accounts for timing/amounts of in/outflows

### Money-weighted rate of return

More emphasis on year with more funds invested. BUT: investors decide that, not management.

### Time-weighted rate of return

> Def: measures the compounded rate of growth of $1 over the measurement period

![alt text](image/2-time-weighted-return-ex.png)

We then have

$$(1+twrr)^n = (1+HPR_1)(1+HPR_2)\cdots(1+HPR_n)$$

Ex: Year 1, we make 15%, year 2, we make 6.67%.

We have:

$$(1+twrr)^2 = (1+HPR_1)(1+HPR_2)$$
$$(1+twrr)^2 = (1.15)(1.0667)$$
$$ twrr = \sqrt{(1.15)(1.0667)} - 1 = 10.76\%$$

This is more preferred than MWRR.

Continue at 30:50
