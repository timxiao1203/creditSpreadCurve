# Credit Spread Curve

There is only one base interest rate per currency, corresponding to the bank’s unsecured lending/borrowing rate (such as LIBOR). The interest rate used to discount cashflows may include a credit spread above or below the base rate.

The risk-free discount factor is exp (-rT) where r is the interest rate and T is the maturity.

The risky discount factor is exp[-(r+s)T] where s is the credit spread.

Credit spread can be derived by either structural model or reduced-form (intensity) model. The structural approach regards default as an endogenous event by focusing on the capital structure of the firm. Whereas the reduced-form approach does not explain the event of default endogenously, but characterizes it exogenously by a jump process.

Structural models are derived from theory and often contain some unobservable assumptions, while reduced-form models use only market observable information. Therefore, many practitioners in the credit trading arena have tended to gravitate toward the reduced-from models given their mathematical tractability and market compatibility. 

Credit spread is the credit funding cost for a firm. For many products, credit spread is the major risk driver. Credit spread impacts discounting, default probability, and early termination.

Many researchers group similar credits. These groupings are loosely referred to as rating categories. Regardless of how the rating categories are constructed and of how many categories there are, it is necessary to specify the default likelihood for each category and provide a credit spread to correspond to each category.

FinPricing offer forward credit spread curves for various sectors and ratings. These curves are derived/bootstrapped through a compilation of market prices of credit-bearing instruments provided by major dealers.  We review the contributed information on a daily basis to ensure accuracy and consistency.



Reference

https://finpricing.com/lib/EqRangeAccrual.html

https://bitbucket.org/cmrm11/crcreditcurve/downloads/CrCreditSpread-16.pdf
