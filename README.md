# Portfolio Theory

The classic theory described there assumes that a decision maker completely trusts the statistical model that he posits to govern the joint distribution of returns on a list of available assets. </br>

Black and Litterman is a model that imputes to the decision maker distrust of historically estimated mean returns but still complete trust of estimated covariances of returns. </br>

The famous Black-Litterman (1992) portfolio choice model was motivated by the finding that with high frequency or moderately high frequency data, means are more difficult to estimate than variances.


# Mean-Variance Portfolio

Risk-free return is the theoretical return attributed to an investment that provides a guaranteed return with zero risk. The risk-free rate represents the interest on an investor's money that would be expected from a risk-free asset when invested over a specified period of time. For example, investors commonly use the interest rate on a three-month U.S. T-bill as a proxy for the short-term risk-free rate.


The risk-free return is the rate against which other returns are measured. Investors that purchase a security with some measure of risk higher than that of a risk-free asset (like a U.S. Treasury bill) will naturally demand a higher level of return, because of the greater chance they're taking. The difference between the return earned and the risk-free return represents the risk premium on the security. In other words, the return on a risk-free asset is added to a risk premium to measure the total expected return on an investment.

The mean-variance portfolio choice problem is to chose weights and maximize them : </br>
  
     
                                       U( μ,Σ,w) = w'μ - δ/2 w' Σ w 
                                       
- where  δ>0  is a risk-aversion parameter. The first-order condition for maximizing with respect to the vector of weights w  is : 

                                               μ=δΣw
- mean :  μ
- covariance matrix : Σ

### Estimating Mean and Variance

A standard way of estimating  μ  is maximum-likelihood or least squares; that amounts to estimating  μ  by a sample mean of excess returns and estimating  Σ  by a sample covariance matrix.

# Black-Litterman Model

 - Continues to chose an optimal portfolio weights w.
 - Continues to express your risk tolerance by setting δ.
 -  Leaving  Σ  at its maximum-likelihood value, they push  μ  away from its maximum-likelihood value.









