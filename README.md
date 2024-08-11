1. Black-Scholes Model
The Black-Scholes model is a closed-form solution for pricing European options. It assumes that the underlying asset follows a geometric Brownian motion with constant volatility and interest rate. This model is suitable for pricing European-style options which can only be exercised at maturity.

2. Monte Carlo Simulation
The Monte Carlo method uses random sampling to estimate the value of an option. It simulates the underlying asset's price paths over time and calculates the option payoff for each path. The final option price is the average of all simulated payoffs, discounted at the risk-free rate.

3. Binomial Model
The Binomial model breaks down the time to expiration into multiple steps or intervals. At each step, the price of the underlying asset can move up or down by a certain factor. The option price is calculated by working backwards from the expiration to the present, considering the possible paths the asset price could take.
