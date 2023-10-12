# Options-Pricing
we present an elegant way of solving the Black-Scholes partial differ- ential equation using numerical methods. We begin by posing the simplest prob- lem of pricing a vanilla European option, whose PDE is explicitly solvable. We apply central, forward, and backward differences covering different orders of pre- cision and sparse matrix TDMA techniques to arrive at the solution. We compare the error for different step-sizes and choose metaparameters that implement the most numerically stable solution. We then proceed to modify the Black-Scholes equation to price early-exercise (American) options, a model whose partial differential equations need not have explicit solutions and use the numerically stable algorithms proposed to solve them.
