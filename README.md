
The beautiful dataset is sourced from a statistics course by 360 Careers. It has data on car variables that we intend to use in establishing causality effects on the selling price. This is done through an Ordinary Least Squares linear regression model. The variables put to test are: Engine volume, Mileage, Year of make, and Brand

**FINDINGS**

**Mileage**

We observed mileage has a negative relationship with price, an increase in mileage leads to a price decrease of -1.3 units. You can only imagine what 300-mileage units would translate to.
This can be visualized more by referencing a drop in Ksh currency value to the dollar, increasing the debt amounts held in dollars.

However, there are a few cars with high mileage and a higher asking price.

Mileage affects 34% of car prices.

**Engine volume**

High engine volumes attracted higher selling prices.
The volume affects a 20.7% change in car price.

An increase in volume causes prices to shoot 1.2 times. A 4.4 will be 1.2 times costlier than a 4.3

**Year of make**

The newer a car by year of manufacture, the higher the price.
Year causes a 56.1% change in price, the heaviest we have seen so far. That means more than half of the selling price is caused by Year.
A 2023 manufactured car is likely to be 1.35 times costlier than a 2022 one.

**Brand**

Since brand data is categorical, we create dummy variables denoted by binary numbers 0 & 1. Say if a car is a Benz=1, ELSE=0.

A rule of dummies is n-1 which means subtract one variable from your dummies, which will be used as a reference car to others. If a car is not a 'Mercedes-Benz', 'Toyota', 'BMW', 'Volkswagen', 'Mitsubishi' or 'Renault', then it's an AUDI.

A BMW for example will be 0.6% more expensive than an Audi. We observed only BMW and Mercedes are costlier than Audi, the rest have -ve coefficients meaning they are (n units) cheaper than Audi.

**The Model Summary**

It is a significant model that translates 80% of car prices in the shop.

Prices predicted using this model will be 80% significant, gaining a competitive edge on realistic pricing.

The model will also help respond to updated inventory management that meets customers' needs. Cash flow may also be predicted using the model and that information is used as needed.
The constant value to use in the linear regression formula will be 4.3265.

Dive in the notebook for enlightenment!

