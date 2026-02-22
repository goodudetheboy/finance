# Demand and Supply

## Types of Markets

![alt text](image/1-types-of-markets-chart.png)

For Firms, if revenue > economic costs of production, then supply has.

Households are the ultimate owner of all equity and all debts of all firms.

Must be noted that all market interactions are voluntary

## Principles of Demand & Supply

### Demand

> Demand
>
> Definition: The willingness and ability of consumers to purchase a given amount of a good/service at a given price

We have:
> Demand function
>
> Definition: $Q^d_x = f(P_x, I, P_y...)$
> - $P_x$: price
> - $I$: your level of income
> - $P_y$: price of other products that can be substitue or complement

Demand is driven by something called **Law of Demand**.

> Law of Demand
>
> Definition: As $P_x$ goes up, $Q^d_x$ goes down, and vice versa. Layman terms, the higher the price increases, the lower the demand.

We have that: $$Q^d_x = Int - P_x + I - P_y$$

Here, $Int$ is intercept constant term.

$P_y$ if is:
- negative coefficients => complement product
- positive coefficients => substitute product

$I, P_y$ is usually exogenous variables, so typically hold these constant

Thus: $$Q^d_x = Int - coef P_x$$

$$coef P_x = Int - Q^d_x$$

$$P_x = Int/coef - Q^d_x / coef$$

This is called the **inverse demand function**. The price is solved for a given quantity

### Supply

> Supply
>
> Definition: The willingness and ability of sellers to offer a given quantity of a good/service at a given price.

We have:

> Supply function
>
> Definition: $Q^s_x = f(P_x, W...)$

Supply is driven by **Law of Supply**.

> Law of Supply
>
> Definition: As $P_x$ goes up, $Q^s_x$ goes up, and vice versa

We have that: $$Q^s_x = Int + P_x - W$$

(higher production cost will make $Q^s_x$ goes down, that means less people are willing to supply it)

$W$ is exogenous variable, so typically held constant.

Thus:

$$Q^s_x = Int + coef P_x$$

$$ -coefP_x = Int - Q^s_x$$
$$ coefP_x = -Int +Q^s_x$$
$$P_x = -Int/coef + Q^s_x/coef$$

Then:
$$P_x = -Int + coef Q^s_x$$

This is called the inverse supply function.

### Point of Equilibrium

![alt text](image/2-point-of-equilibrium.png)

Top chart is Demand curve, mid chart is Supply curve

The cross between demand and supply is called the equilibrium.

## Shifts vs Movements

Causes of shifts in and movements along the demand and supply curve.

### Price drops

As the price drops, demand should increase. We move down the demand curve => **Change in quantity demanded**

As the price increases, supply should increase. We move up the supply curve => **Change in quantity supplied**

### Change in any other variables

Shifts the in the curve result from a exchange in other exogeneous variables

#### Income increases

Demand will increase when our income increase, even without changes in price. When we have more disposable incomes, we wants more stuff => **Change in demand**

#### Wages increase

Supply will decrease when wages increase, even without changes in price. Naturally because it's more expensive producing the same shit. => **Change in supply**

Ex: Demand function / Demand curve

$$Q^d_x = 2 - .4P_x + .0005I + .15 P_y$$

where $P_x = 10.68$, $I=2300$, $P_y=21.40$

1. Find $Q^d_x$

$$Q^d_x = 2 - .4*(10.68) + .0005(2300) + .15(21.40) = 2.088$$

2. Find the inverse demand function

$$Q^d_x = 2 - .4P_x + .005(2300) + .15(21.40)$$

$$Q^d_x = 6.36 - .4P_x$$

$$P_x = 15.90 - 2.5 Q^d_x$$

3. What is the slope of the demand curve? -2.5

4. What is the intercept of demand curve if $I$ increases to $3000$?

$$Q^d_x = 2 - .4P_x + .0005(3000) + .15(21.40)$$

$$Q^d_x = 6.71 - .4P_x$$

$$P_x = 16.68 - 2.5Q^d_x$$

Same slope, but intercept increases.

Ex: Supply function / supply curve

$$Q^s_x = -64.5 + 37.5P_x - 7.5W$$

where $P_x = 10.68, W = 10$.

1. Find $Q^s_x$

$Q^s_x = -64.5 + 37.5 (10.68) - 7.5(10) = 261$$

2. Find the inverse supply function

$$Q^s_x = -64.5 + 375P_x - 7.5(10)$$

$$Q^s_x = -139.5 + 37.5P_x$$

$$P_x = 3.72 + .0267 Q^s_x$$

3. What is the slope of the supply curve? $0.267$

4. Find Int if $w=15$

$$Q^s_x = -64.5 + 37.5 P_x - 7.5(15)$$

$$Q^s_x = -177 + 37.5P_x$$

Then intercept is $-177$.

## Aggregation

### Aggregating demand curve

To get a demand curve for a bigger scale, just add up all the demand curve of all sub products.

Demand curve: $Q^d_x = Int - coef\cdot P_x$

- add all the buyers together
- assume $n$ buyers

$Q^d_x = 6.36 - .4P_x$ with $n = 1000$ buyers. Then

$$Q^d_x = 1000(6.36 - .4P_x) = 6360 - 400P_x$$

$$P_x = 15.90 - .0025 Q^d_x$$

### Aggregating supply curve

Supply curve: $Q^s_x = Int + coef P_x$

- add all sellers together
- assume $n$ sellers

$Q^s_x = -139.5 + 37.5P_x$ with $n=8$

$$Q^s_x = 8(-139.5+37.5P_x) = -1116 + 300P_x$$

$$P_x = 3.72 + .0033Q^s_x$$


## Equilibrium

### Equlibrium analysis

![alt text](image/3-excess-supply-demand.png)

- Prices will adjust until there is no excess supply or demand (market mechanism)
- If you leave market to their own devices, suppliers will reprice signals in the market
  - If inventory is building up at a certain price, will decrease price until inventory is going out
  - If inventory is slowing down at a certain price, will have more supply and increase price until inventory is not slowing down as much

Market equilibrium: $$Q^d_x = Q^s_x$$

$$6360 - 400P_x = -1116 + 300P_x$$
$$7476 = 700P_x$$
$$P_x = 7476/700 = 10.68$$

$$Q^d_x = 6360 - 400 (10.68) = 2088$$

This means that, if Product X is priced at 10.68, there will be demand for $2088$ of X and supply for $2088$ of X.

Though, this is just a **partial equilibrium analysis** (we haven't factored all elements yet i.e. incomes, wages...)

> Partial equilibrium analysis
>
> Definition: Find equilibrium in one market while taking the values of the exogenous variables as given

To have a more general look, we find the **general equilibrium analysis**.

> General equilibrium analysis
>
> Definition: Find equilibrium in all markets

### Stable vs Unstable Equilibria

### Stable Equilibrium

![alt text](image/4-stable-equi.png)

Condition for stability: As long as $m > 0$ supply curve and $m < 0$ demand curve. As long as this happens, even when we have excess demand (price below equilibrium) or excess supply (price above equilibrium), we will always have stable equilibrium.

Excess demand drives prices up, excess supply drives prices down.

![alt text](image/5-condition-stable.png)

- at prices > $p*$, hit demand before supply
- at prices < $p*$, hit supply before demand

### Unstable Equilibrium

![alt text](image/7-condition-unstable.png)

With this curve we have:

- Excess demand drives prices up
- Excess supply drives prices down

This creates an unstable demand-supply, which causes a **bubble**.

![alt text](image/6-unstable-equi.png)

>Bubbles
>
> Definition:
>
> - Buyers: keep buying, **not on value**, but on a rationalization that if they don't buy today, prices **will be higher** tomorow.
> - Sellers: hold back inventory to get higher prices tomorrow, which leads to another increase in price.

When this happens, sellers hold back, which leads to less supply, which increases price. This reinforces the beliefs that prices will go higher, which leads to more demand. Rinse and repeat, we have an expanding bubble.

This increase in price is not because of demand, but because of **lack of supply**.

Once the price goes down, sellers will shove their supplies out all at once, and this is when the normal rule of demand supply go into full force, and this will drive prices down HARD => The bubble bursts, and it bursts FAST.

Ex:

$$Q^d_x = 6360 - 400P_x$$
$$Q^s_x = -1116 + 300P_x$$

1. $P_x = 12$. What is the excess supply/demand? We have:

$$Q^d_x = 6360 - 400 (12) = 1560$$
$$Q^s_x = -1116 + 300(12) = 2484$$

$Q^d_x < Q^s_x$, so we have excess supply of $924$. Price has to come down.

2. $P_x = 8$

$$Q^d_x = 3160$$
$$Q^s_x = 1284$$

$Q^d_x > Q^s_x$, so we have excess demand of $1876$. Price will go up.

## Auctions

### Types of auctions

> Common value auction
>
> Definition: There's some actual value to what you're bidding on. Imagine there's a jar full of quarters and you bid on it, you won't know the value until you got it and count it up. e.g. oil/timber leases, Spectrum

> Private value auction
>
> Defintion: Value is subjective based on the thing bidding e.g. artworks

### Mechanisms

> Ascending Price Auction
>
> Defintion: Bids are given one people at a time where people keep bidding until no more bids, and the highest bidder wins

> Sealed Bid Auction
>
> Definition:
>
> 1. **First priced sealed bid auction**: Your bids are not public until the end of the auction. You put your bid in an envelope, hand in that envelope, and once everyone has submitted their bids, only then the envelopes are opened. **Highest bidder pays their bid**. This may actually result in a lower price, compared to the second price sealed bid auction
>  2. **Second price sealed bid auction** (Vickery auction): We know that the highest price tends to overprice, so everyone will write a lower price. A way to get a higher price, is to get the **highest bidder pay the second highest price**.

> Descending Price Auction (Dutch Auction)
>
> Definition: Price starts high and declines until the item is sold or the lot is cleared. If there are multiple items, highest bidder selects a quantity $Q$ they want, then bid drops until all $Q$ is gone. **First person to speak up, they pay the price**. Two types:
> - Single item
> - Multiple items: this is how Govt of Canada auction their bond

> Modified Dutch Auction (Single-price Dutch Auction)
>
> Definition: All bidders pay lowest bid that clears $Q$. This is how US Treasuries auction their bond. Why a little better? The highest bidder will start bidding will get, then people will start bidding down. They will get more value like this.

Competitive vs non-competitive bidders.

- Competitive bidders: specify prices/yields to win contracts or securities, driving market rates through direct price competition
- Non-competitive bidders: agree to accept the final market-determined price, simplifying participation for smaller investors but relying on the competitive process for pricing

The Dutch Auctions may include both competitive & non-competitive bids. Non-competitive bidders agree to pay the single price arrived at in the Dutch auction process.

Ex: $90B in T-Bills available, competitive + non-competitive bids

## Surplus

Q: Why is equilibrium desirable?


### Consumer surplus

> Consumer surplus
>
> Definition: This is the difference between what a buyer is willing to pay and what they actually pay

Can answer this with consumer surplus, that has to do with demand curve. We can think of a demand curve as a "marginal value curve" (diminishing marginal utility).

![alt text](image/8-consumer-surplus.png)

If the price is lower, than there would be more people willing to pay, creating consumer surplus.

Total expenditure = $P_1 \times Q_1$

AUC is the total value

Ex: $Q^d_x = 180 - 2P_x$. What is consumer surplus if $P_x = 65$.

$$Q^d_x = 180 - 2 (65) = 50$$

Intercept at $Q^d_x = 0$. $2P_x = 180$ then $P_x = 90$. Consumer surplus is:

$$1/2(50)(90-65) = 625$$

### Producer surplus

> Producer surplus
>
> Definition: This is the difference between what a seller receives and the minimum they'd accept (cost of production)

Supply curve can be interpreted as a "marginal cost curve" (marginal cost curve is the supply curve for any competitive seller)

**Economic profit** is another term for producer surplus

![alt text](image/9-producer-surplus.png)

Total Variables cost are under the curve. Then Total Revenue = $P_1 \times Q_1$. Producer surplus = $TR - TUC$

Ex: $Q^s_x = -15 + P_x$, what is total producer surplus at $P_1 = 65$?

$Q^s_x = -15 + P_x$, what is total producer surplus at $P_1 = 65$?

$Q^s_x = -15 + 65 = 50$, Intercept $Q^s_x = 0$. Then $15 = P_x$

### Surplus

> Surplus
>
> Definition: Total Surplus = consumer surplus + producer surplus (625 + 1250 = 1875)

The way total surplus is divided between consumers and producers depends on the steepness of the demand & supply curves.
- If $|m_d| > |m_s|$, then consumer surplus > producer surplus, and vice versa
- Whenever total surplus increases, society gains
- **Total surplus is maximized at equilibrium.**

ELI5: surplus measures how much of a deal each side _feel_ they get from the transaction. If the price makes both feel good, then everybody is happy. The equilibrium price is the price that maximizes the "deal" feeling for both side, maximizing everybody happiness.

## Market Interference

### Price Ceiling

> Price Ceiling
>
> Definition: When politicians decide a market is too high for consumers, for example, rent control. This has a tendency to reduce supply which reduces total surplus.

![alt text](image/10-price-ceiling.png)

- At equilibrium $p^*$:
  - consumer surplus = a + b
  - producer surplus = c + d + e
  - total surplus = a + b + c + d + e => max surplus

- At price ceiling $p_c$, you have less supply with way more demand.
  - consumer surplus = a+c
  - producer surplus = e
  - total surplus = a + c + e
  - We call b + d **deadweight loss** (benefit to society that is gone)

- Thought there can be extranelity:
  - Not accounted for by this market
  - Can be positive or negative


### Price Floor

> Price Floor
>
> Definition: When politicians decide that the market price is too low (e.g. minimum wage). This has a tendency to reduce demand which reduces total surplus

![alt text](image/11-price-floor.png)

- At equilibrium $p^*$:
  - consumer surplus = a + b + c
  - producer surplus = d + e
  - total surplus = a + b + c + d + e

- At price floor $p_c$:
  - consumer surplus = a
  - producer surplus = b + e
  - total surplus = a + b + e
  - deadweight loss = c + d

- There can be job loss, but more people has more to spend, this might have positive extranelity somewhere else


=> Conclusion: Government intervention, in a theoretical sense, brings deadweight loss to a market, BUT we have to also factor in many factors too. This deadweight loss might be applicable for one particular market, but in a general sense, it might not.

## Tax

### Tax on Buyers

Before tax:

- consumer surplus a + b + c
- producer surplus: d + e + f

After tax:

- consumer surplus a
- producer surplus f
- gov surplus b + d
- deadweight loss c + e

![alt text](image/12-tax-on-buyers.png)

### Tax on Sellers

After tax:

- consumer surplus: a
- producer suprplus: f
- government surplus: b + d
- deadweight loss: c + e

![alt text](image/13-tax-on-sellers.png)

Net result: Add intervention / regulation /tax = deadweight loss

Question though: Why do we tax the consumers?

- The consumer pays for it anyway
- Better to have it visible than invisible
  - If on the producer, the tax is not visible
  - If the consumer can see it, they can tell the government they are not happy with it
  - Can have intervention or less regulation or whatever
- The idea here is the consumers can have a say in adjusting their levels of surplus

## Elasticity

### Demand

> Elasticity (Demand)
>
> Definition: This measures how sensitive quantity demanded is to changes in price

Own price elasticity of demand:
$$E^d_{Px} = \frac{\% \Delta Q^d_x}{\% \Delta P_x} = \frac{\Delta Q^d_x / Q^d_x}{\Delta P_x / P_x} = \left(\frac{\Delta Q^d_x}{\Delta P_x}\right)\cdot \left(\frac{P_x}{Q^d_x}\right)$$

We have that $Q^d_x = Int - coef P_x$, and $Q^d_x$ is point dependent (this means that you'll have different value depending on what you are on the demand curve)

![alt text](image/14-elasticity-point-dependent.png)

How do we measure the elasticity of demand:
1. Choose a price $P_x$
1. Solve for $Q^d_x$
1. Calculate $P_x / Q^d_x$
1. Multiply by (-coef)

Ex: We have $Q^d_x = 11200 - 400P_x$. Calculate $E^d_{Px}$ at $P_x = 3$.

$$Q^d_x = 11200 - 400(3) = 10000$$
$$E^d_{Px} = -400(\frac{3}{10000}) = -0.12

This means that $1\%$ increase in $P_x$, quantity demanded will decrease by $.12\$$ for $Q^d_x$.

If our price is at equlibrium, the demand curve is called **unit elastic**.

If our price is above equilibrium, the demand curve will be called "elastic", at this point the demand will change very significantly.

If our price is below equilibrium, the demand curve will be called "inelastic", at this point, the demand will change very small.

If you have a product, ideally you'll want your product to be inelastic, which means that when you change your price, you'll want demand to change less.

Elasticity can tell you how competitive a market is: if you're disrupting, your product will be very elastic.

> Inelastic
>
> Definition: Demand is not very sensitive, or $|E^d_{Px}| < 1$

> Elastic
>
> Definition: Demand is very sensitive, or $|E^d_{Px}| > 1$

> Unit elastic
>
> Definition: Inflection point between inelasticity and elasticity. $|E^d_{Px}| = 1$

Usually, when in the real world, you are not just given a demand curve. You have to calculate the it from the data you collect yourself (no free lunch!). Here, you can use arc elasticity

> Arc elasticity
>
> Definition: When we don't know the slope of the demand curve, but you would want to know the rough elasticity. Do this by:
>
>$$E = \frac{\Delta Q / Q_{avg}}{\Delta P / D_{avg}}$$

Ex: $P_x = 5$, then $Q^d_x = 9200$. $P_x = 6$, then $Q^d_x = 8800$, then:

$$E = \frac{-400/9000}{1/5.50} = -0.244$$

### Perfectly inelastic demand

We call this perfectly inelastic demand.

![alt text](image/15-perfectly-inelastic-demand.png)

Ex: Pharmacy drugs. Whatever the price, you have to buy it anyway. A change in price $P_x$ will not change the demand $Q^d_x$, something like insulin.

### Perfectly elastic demand

We call this perfectly elastic demand.

![alt text](image/16-perfectly-elastic-demand.png)

Ex: Grains like corn, wheat. Farmer is a price takers at this point because there is a world market. You can't raise your price and expect market to buy it - market will just buy from millions of other farmers.

### Factors affecting elasticity

#### Availability of substitutes

High number of substitute leads to more elastic; low number leads to more inelastic. This is obvious, if the price of a product is prohibitive and there are many other cheaper substitute, then market will shove to that instead. 

#### Percentage of budget

If I'm not spending a lot for a product wrt my budget, more inelastic. E.g chocolate

If I'm spending a large percent of my budget, more elastic. We are very conscious of that

#### Needs

This is more inelastic. E.g. food as a category. You can't buy less food and then starve

#### Wants

This is more elastic. E.g. PC upgrades, entertainment.

#### Long-run demand

More elastic. E.g. investing. You think you don't need that now, so you are sensitive more against prices.

#### Short-run demand

More inelastic. E.g. gas. You need that gas to do things, you'll have to bite the price changes

=> It alls boil down to our behavior needs time to change

### Elastic curve

![alt text](image/17-elasticity-curve.png)

- When demand is elastic, a fall in $P_x$ results in a greater $Q^d_x$ demanded AND a rise in Total Expenditure
- When demand is inelastic, while a drop in $P_x$ results in an increase in demand $Q^d_x$, demand doesn't rise that much in equal proportion to the drop in price, which results in a drop in Total Expenditure.

### Income Elasticity of Demand
> Income elasticity of demand
>
> Definition: measures how responsive the quantity demanded of a good changes in response to a change in consumer income.
>
> $$E^d_I = \left(\frac{\Delta Q^d_x }{\Delta I}\right)\left(\frac{I}{Q^d_x}\right)$$
>
>- If $E^d_I > 0$, this is **normal good** (as incomes rise, demand rises) e.g. you buy better wine when you make more money
>- If $E^d_I < 0$, this is **inferior good** (as incomes rise, demand lowers) e.g. you don't buy those cheap wine when you make more money
>
> Ex: If $E^d_I = 0.8$, quantity demanded "at each price" increase by $.8\%$ for each $1\%$ increase in income, a shift of the demand curve

### Cross Price Elasticity of Demand

> Cross Price Elasticity of Demand
>
> Definition: measures how responsive the quantity demanded of one good (X) changes in response to a change in the price of another good (Y).
> $$E^d_{Py} = \left(\frac{\Delta Q^d_x}{\Delta P_y}\right)\left(\frac{P_y}{Q^d_x}\right)$$
>
> - If $E^d_{Py} > 0$, substitute product
> - If $E^d_{Py} < 0$, complement product
