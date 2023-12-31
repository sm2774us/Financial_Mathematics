# Finance_and_AI_ML
Personal Repository for Quantitative Finance and AI/ML topics

## Table Of Contents <a name="top"></a>

1. [Rules of Numbers](#rules-of-numbers)  
2. [Rules of Exponents](#rules-of-exponents)
3. [Rules of Logarithms](#rules-of-logarithms)
4. [The Time Value of Money](#the-time-value-of-money)
    - 4.1. [Future value, present value and simple interest](#future-value-present-value-and-simple-interest)
    - 4.2. [Multiple compounding periods](#multiple-compounding-periods)
    - 4.3. [Effective annual rate](#effective-annual-rate)
5. [Asset Return Calculations](#asset-return-calculations)
    - 5.1. [Simple Returns](#simple-returns)
        - 5.1.1. [Simple Returns - Python Example](#simple-returns---python-example)
        - 5.1.2. [Simple Returns - R Example](#simple-returns---r-example)
        - 5.1.3. [Reference: Introduction To Computational Finance And Financial Econometrics With R](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/IntroductionToComputationalFinanceAndFinancialEconometricsWithR.pdf)
    - 5.2. [Cumulative Returns (or, Multiperiod Returns)](#cumulative-returns-or-multiperiod-returns)
        - 5.2.1. [Cumulative Returns (or, Multiperiod Returns) - Python Example](#cumulative-returns-or-multiperiod-returns---python-example)
        - 5.2.2. [Cumulative Returns (or, Multiperiod Returns) - R Example](#cumulative-returns-or-multiperiod-returns---r-example)
        - 5.2.3. [Reference: Introduction To Computational Finance And Financial Econometrics With R](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/IntroductionToComputationalFinanceAndFinancialEconometricsWithR.pdf)
    - 5.3. [Log Returns](#log-returns)
        - 5.3.1. [Log Returns - Python Example](#log-returns---python-example)
        - 5.3.2. [Log Returns - R Example](#log-returns---r-example)
        - 5.3.3. [Reference: Introduction To Computational Finance And Financial Econometrics With R](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/IntroductionToComputationalFinanceAndFinancialEconometricsWithR.pdf)
    - 5.4. [Matching Log Returns With Cumulative Returns - Python Example](#matching-log-returns-with-cumulative-returns---python-example)
    - 5.5. [Matching Log Returns With Cumulative Returns - R Example](#matching-log-returns-with-cumulative-returns---r-example)
6. [Linear Algebra With Python](#linear-algebra-with-python)
    - 6.1. [Chapter 1 - Linear Equation System](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%201%20-%20Linear%20Equation%20System.ipynb)
    - 6.2. [Chapter 2 - Basic Matrix Algebra.ipynb](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%202%20-%20Basic%20Matrix%20Algebra.ipynb)
    - 6.3. [Chapter 3 - Determinant](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%203%20-%20Determinant.ipynb)
    - 6.4. [Chapter 4 - LU Factorization](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%204%20-%20LU%20Factorization.ipynb)
    - 6.5. [Chapter 5 - Vector Addition, Subtraction and Scalar Multiplication](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%205%20-%20Vector%20Addition%2C%20Subtraction%20and%20Scalar%20Multiplication.ipynb)
    - 6.6. [Chapter 6 - Linear Combination](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%206%20-%20Linear%20Combination.ipynb)
    - 6.7. [Chapter 7 - Linear Independence](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%207%20-%20Linear%20Independence.ipynb)
    - 6.8. [Chapter 8 - Vector Space and Subspace](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%208%20-%20Vector%20Space%20and%20Subspace.ipynb)
    - 6.9. [Chapter 9 - Basis and Dimension](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%209%20-%20Basis%20and%20Dimension.ipynb)
    - 6.10. [Chapter 10 -Null Space vs Col Space, Row Space and Rank](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2010%20-Null%20Space%20vs%20Col%20Space%2C%20Row%20Space%20and%20Rank.ipynb)
    - 6.11. [Chapter 11 - Linear Transformation](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2011%20-%20Linear%20Transformation.ipynb)
    - 6.12. [Chapter 12 - Eigenvalues and Eigenvectors](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2012%20-%20Eigenvalues%20and%20Eigenvectors.ipynb)
    - 6.13. [Chapter 13 - Diagonalization](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2013%20-%20Diagonalization.ipynb)
    - 6.14. [Chapter 14 - Applications to Dynamic System](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2014%20-%20Applications%20to%20Dynamic%20System.ipynb)
    - 6.15. [Chapter 15 - Inner Product and Orthogonality](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2015%20-%20Inner%20Product%20and%20Orthogonality.ipynb)
    - 6.16. [Chapter 16 - Gram-Schmidt Process and QR Decomposition](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2016%20-%20Gram-Schmidt%20Process%20and%20QR%20Decomposition.ipynb)
    - 6.17. [Chapter 17 - Symmetric Matrices , Quadratic Form and Cholesky Decomposition](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2017%20-%20Symmetric%20Matrices%20%2C%20Quadratic%20Form%20and%20Cholesky%20Decomposition.ipynb)
    - 6.18. [Chapter 18 - The Singular Value Decomposition](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2018%20-%20The%20Singular%20Value%20Decomposition.ipynb)
    - 6.19. [Chapter 19 - Multivariate Normal Distribution](https://github.com/sm2774us/Finance_and_AI_ML/blob/main/Linear%20Algebra%20With%20Python/Chapter%2019%20-%20Multivariate%20Normal%20Distribution.ipynb)
7. [Covariance and Correlation Matrix of Stock Returns](#covariance-and-correlation-matrix-of-stock-returns)

## Rules of Numbers

* **Commutative Laws:** $a + b  =  b + a \ \ \ \ a * b  =  b * a \ \ \ \ {a \ \ \\% \ \ of \ \ b}  =  {b \ \ \\% \ \ of \ \ a}$
  * The "Commutative Laws" say we can swap numbers over and still get the same answer
  * Why "commutative" ... ? Because the numbers can travel back and forth like a commuter
  * The Commutative Law does not work for subtraction or division
    * 12 / 3 = 4, but
    * 3 / 12 = 1/4
* **Associative Laws:** $(a + b) + c  =  a + (b + c) \ \ \ \ (a × b) × c  =  a × (b × c)$
  * The "Associative Laws" say that it doesn't matter how we group the numbers (i.e. which we calculate first) ...
  * The Associative Law does not work for subtraction or division:
    * (9 – 4) – 3 = 5 – 3 = 2, but
    * 9 – (4 – 3) = 9 – 1 = 8  
* **Distributive Laws:** $a × (b + c)  =  a × b  +  a × c$
  * We get the same answer when we => multiply a number by a group of numbers added together, or do each multiply separately then add them
  * The Distributive Law does not work for division:
    * 24 / (4 + 8) = 24 / 12 = 2, but
    * 24 / 4 + 24 / 8 = 6 + 3 = 9 

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

## Rules of Exponents

* **Rule 1 (Product Rule):** $a^m*a^n = a^{m+n}$
* **Rule 2 (Quotient Rule):** $a^m/a^n = a^{m-n}$
* **Rule 3 (Power of a Power Rule):** $(a^m)^n = a^{mn}$

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

## Rules of Logarithms

* **Rule 1 (Product Rule):** $\log{_b}(M*N) = \log{_b}M + \log{_b}N$ [ b, M and N are positive integers and b ≠ 1 ]
* **Rule 2 (Quotient Rule):** $\log{_b}(M/N) = \log{_b}M - \log{_b}N$ [ b, M and N are positive integers and b ≠ 1 ]
* **Rule 3 (Power Rule):** $\log{_b}(M^k) = k*\log{_b}M$ [ b and M are positive numbers, b ≠ 1 and $k \ \epsilon \ \mathbb{R}$ ]
* **Rule 4 (Change of Base Rule):** $\log{_b}(M) = \log{_k}M / \log{_k}b$ [ M, b and k are positive numbers and b ≠ 1, k ≠ 1 ]
* **Rule 5 (Reciprocal Rule):** $\log{_b}(M) = 1 / \log{_M}b$ [ M and b are the positive numbers other than 1 ]
* **Rule 6:** $\log{_b}(1) = 0$ [ $b \gt 0$ and $b \neq 1$ ]
* **Rule 7:** $\log{_b}(b) = 1$ [ $b \gt 0$ and $b \neq 1$ ]
* **Rule 8:** $\log{_b}(b^k) = k$ [ $b \gt 0$ and $b \neq 1$ and $k \ \epsilon \ \mathbb{R}$ ]
* **Rule 9:** $b^{\log{_b}(k)} = k$ [ $b \gt 0$ and $b \neq 1$ and $k \ \epsilon \ \mathbb{R}$ ]

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

## Asset Return Calculations

This section reviews basic time value of money calculations. The concepts of future value,
present value and the compounding of interest are defined and discussed.

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

### Future value, present value and simple interest

Consider an amount `$V` invested for `n` years at a simple interest rate of `R` per annum (where
R is expressed as a decimal). If compounding takes place only at the end of the year, the
future value after n years is:

$$FV{_n} = \$V(1 + R) \ * \ . . . \ * \ (1 + R) = \$V \ . \ (1 + R)^{n}$$

Over the first year, `$V` grows to

$$\$V(1 + R) = \$V + \$V \ * \ R$$

which represents the initial principal `$V` plus the payment of simple interest `$V * R` for the year. Over the second year, the new principal

$$\$V \ * \ (1 + R)$$

grows to

$$\$V \ * \ (1 + R) \ * \ (1 + R) = \$V \ * \ (1 + R)^{2}$$

, and so on.

`Example 1.1. Future value with simple interest.`

Consider putting $1000 in an interest checking account that pays a simple annual percentage
rate of 3%. The future value after n = 1, 5 and 10 years is, respectively,

`F V1 = $1000 · (1.03)1 = $1030,`

`F V5 = $1000 · (1.03)5 = $1159.27,`

`F V10 = $1000 · (1.03)10 = $1343.92.`

Over the first year, $30 in interest is accrued; over three years, $159.27 in interest is accrued;
over five years, $343.92 in interest is accrued. These calculations are easy to perform in R

```R
V = 1000
R = 0.03
FV1 = V * (1 + R)
FV5 = V * (1 + R)^5
FV10 = V * (1 + R)^10
c(FV1, FV5, FV10)

## [1] 1030 1159 1344
```

The future value formula (1.1) defines a relationship between four variables: $FV{_n}$, $V$ , $R$ and
$n$. Given three variables, the fourth variable can be determined. For example, given $FV{_n}$, $R$ and $n$ 
and solving for $V$ gives the present value formula:

$$V = \frac{FV{_n}}{(1 + R)^{n}}. \ \ \ \ (1.2)$$

Taking $FV{_n}$, $n$ and $V$ as given, the annual interest rate on the investment is defined as:

$$R = (\frac{FV{_n}}{V})^{1/n} − 1. \ \ \ \ (1.3)$$

Finally, given $FV{_n}$, $V$ and $R$ we can solve for $n$:

$$n = \frac{ln(\frac{FV{_n}}{V})}{ln(1 + R)}. \ \ \ \ (1.4)$$

The expression (1.4) can be used to determine the number years it takes for an investment
of $\$V$ to double. Setting $FV{_n} = 2V$ in (1.4) gives:

$$n = \frac{ln(2)}{ln(1 + R)} \approx \frac{0.7}{R},$$

which uses the approximations ln(2) = 0.6931 ≈ 0.7 and ln(1 + R) ≈ R for R close to zero.
The approximation n ≈ 0.7/R is called the `rule of 70`.

`Example 1.2. Using the rule of 70.`

The rule of 70 gives a good approximation as long as the interest rate is not too high.

```R
R = seq(0.01, 0.1, by = 0.01)
nExact = log(2)/log(1 + R)
nRule70 = 0.7/R
cbind(R, nExact, nRule70)

##          R nExact nRule70
## [1,]  0.01  69.66   70.00
## [2,]  0.02  35.00   35.00
## [3,]  0.03  23.45   23.33
## [4,]  0.04  17.67   17.50
## [5,]  0.05  14.21   14.00
## [6,]  0.06  11.90   11.67
## [7,]  0.07  10.24   10.00
## [8,]  0.08   9.01    8.75
## [9,]  0.09   8.04    7.78
## [10,] 0.10   7.27    7.00
```

For R values between 1% and 10% the approximation error in the rule of 70 is never more
than half a year

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

### Multiple compounding periods

If interest is paid `m` times per year, then the future value after `n` years is:

$$F{V{_n}}^{m} = \$V \ * \ (1 + \frac{R}{m})^{m*n} \ .$$

$\frac{R}{m}$ is often referred to as the `periodic interest rate`. As `m`, the frequency of compounding,
increases, the rate becomes continuously compounded and it can be shown that the future value becomes:

$$F{V{_n}}^{c} =$$

$$\lim_{m \to \infty}\ \$V * (1 + \frac{R}{m})^{m*n} = \$V * e^{R-n} \ ,$$

where $e^{(.)}$ is the exponential function and $e^{1} = 2.71828$.

`Example 1.3. Future value with different compounding frequencies.`

For a simple annual percentage rate of 10%, the value of $1000 at the end of one year (n = 1)
for different values of m is calculated below.

```R
V = 1000
R = 0.1
m = c(1, 2, 4, 356, 10000)
FV = V * (1 + R/m)^(m)
print(cbind(m, FV), digits = 7)

##          m       FV
## [1,]     1 1100.000
## [2,]     2 1102.500
## [3,]     4 1103.813
## [4,]   356 1105.155
## [5,] 10000 1105.170
```

The result with continuous compounding is

```R
print(V * exp(R), digits = 7)

## [1] 1105.171
```

The continuously compounded return analogues to the present value, annual return and
horizon period formulas (1.2), (1.3) and (1.4) are:

$$V = e^{−R{_n}}FV{_n} \ ,$$

$$R = \frac{1}{n}ln(\frac{FV{_n}}{V}) \ ,$$

$$n = \frac{1}{R}ln(\frac{FV{_n}}{V}) \ .$$

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

### Effective annual rate

We now consider the relationship between simple interest rates, periodic rates, effective annual rates and continuously compounded rates. Suppose an investment pays a periodic interest rate of 2% each quarter. This gives rise to a simple annual rate of 8% (2%×4 quarters). At the end of the year, $1000 invested accrues to:

$$\$1000 * (1 + \frac{0.08}{4})^{4.1} = \$1082.40.$$

The `effective annual rate`, $R{_A}$, on the investment is determined by the relationship:

$$\$1000 · (1 + R{_A}) = \$1082.40.$$

Solving for $R{_A}$ gives:

$$R{_A} = \frac{\$1082.40}{\$1000} − 1 = 0.0824,$$

or $R{_A}$ = 8.24%. Here, the effective annual rate is the simple interest rate with annual compounding that gives the same future value that occurs with simple interest compounded four times per year. The effective annual rate is greater than the simple annual rate due to the payment of interest on interest.

The general relationship between the simple annual rate $R$ with payments $m$ times per year and the effective annual rate, $R{_A}$, is:

$$(1 + R{_A}) = (1 + \frac{R}{m})^{m}.$$

Given the simple rate $R$, we can solve for the effective annual rate using:

$$R{_A} = (1 + \frac{R}{m})^{m} − 1. \ \ \ \ (1.5)$$

Given the effective annual rate $R{_A}$, we can solve for the simple rate using:

$$R = m[(1 + R{_A})^{\frac{1}{m}} − 1].$$

The relationship between the effective annual rate and the simple rate that is compounded continuously is:

$$(1 + R{_A}) = e^{R}.$$

Hence,

$$R{_A} = e^{R} − 1,$$

$$R = ln(1 + R{_A}).$$

`Example 1.4. Determine effective annual rates.`

The effective annual rates associated with the investments in example 1.2 are calculated
below.

```R
RA = FV/V - 1
print(cbind(m, FV, RA), digits = 7)

##          m       FV        RA
## [1,]     1 1100.000 0.1000000
## [2,]     2 1102.500 0.1025000
## [3,]     4 1103.813 0.1038129
## [4,]   356 1105.155 0.1051554
## [5,] 10000 1105.170 0.1051704
```

The effective annual rate with continuous compounding is

```R
print(exp(R) - 1, digits = 7)

## [1] 0.1051709
```

`Example 1.5. Determine continuously compounded rate from effective annual rate.`

Suppose an investment pays a periodic interest rate of 5% every six months ($m = 2$, $\frac{R}{2} = 0.05$). In the market this would be quoted as having an annual percentage rate, $R{_A}$, of 10%. An investment of $100 yields $100 · (1.05)2 = $110.25 after one year. The effective annual rate, $R{_A}$, is then 10.25%. To find the continuously compounded simple rate that gives the same future value as investing at the effective annual rate we solve:

$$R = ln(1.1025) = 0.09758.$$

That is, if interest is compounded continuously at a simple annual rate of 9.758% then $100 invested today would grow to 

$$\$100 \ * \ e^{0.09758} = \$110.25$$

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

## Asset Return Calculations

In this section, we review asset return calculations given initial and future prices associated
with an investment. We first cover simple return calculations, which are typically reported
in practice but are often not convenient for statistical modeling purposes. We then describe
continuously compounded return calculations, which are more convenient for statistical modeling purposes.

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

### Simple Returns

Consider purchasing an asset (e.g., stock, bond, ETF, mutual fund, option, etc.) at time $t_{0}$ for the price $P_{t_{0}}$ , and then selling the asset 
at time $t_{1}$ for the price $P_{t_{1}}$ . If there are no intermediate cash flows (e.g., dividends) between $t{_0}$ and $t{_1}$, the rate of return over the period $t{_0}$ to $t{_1}$ is the percentage change in price:

$$R(t_{0}, t_{1}) = \frac{P_{t_{1}} - P_{t_{0}}}{P_{t_{0}}}. \ \ \ (1.6)$$

The time between $t{_0}$ and $t{_1}$ is called the holding period and equation (1.6) is called the holding period return. In principle, 
the holding period can be any amount of time: one second; five minutes; eight hours; two days, six minutes and two seconds; fifteen years. 
To simplify matters, in this chapter we will assume that the holding period is some increment of calendar time; e.g., one day, 
one month or one year. In particular, we will assume a default holding period of one month in what follows.

Let $P_{t}$ denote the price at the end of month $t$ of an asset that pays no dividends and let $P_{t-1}$ denote the price at the end of month $t-1$. Then the one-month simple net return on an investment in the asset between months $t-1$ and $t$ is defined as:

$$R_{t} = \frac{P_{t} - P_{t-1}}{P_{t-1}} = %\Delta P_{t}. \ \ \ (1.7)$$

Writing 

$$\frac{P_{t} - P_{t-1}}{P_{t-1}} = \frac{P_{t}}{P_{t-1}} - 1,$$

we can define the simple gross return as:

$$1 + R_{t} = \frac{P_{t}}{P_{t-1}}. \ \ \ (1.8)$$

The one-month gross return has the interpretation of the future value of $1 invested in the asset for one-month with simple interest rate Rt. Solving (1.8) for $P_{t}$ gives $P_{t} = P_{t-1}(1 + R_{t})$,

which shows $P_{t}$ can be thought of as the future value of $P_{t-1}$ invested for one month with simple return $R_{t}$. Unless otherwise stated, 
when we refer to returns we mean net returns. Since asset prices must always be non-negative (a long position in an asset is a limited liability investment), the smallest value for $R_{t}$ is -1 or -100%.

`Example 1.6. Simple return calculation.`

Consider a one-month investment in Microsoft stock. Suppose you buy the stock in month $t−1$ at $P_{t−1}$ = $85 and sell the stock the next month for 
$P_{t}$ = $90. Further assume that Microsoft does not pay a dividend between months $t−1$ and $t$ . The one-month simple net and gross returns are then:

$$R_{t} = \frac{\$90 - \$85}{\$85} = \frac{\$90}{\$85} − 1 = 1.0588 − 1 = 0.0588,$$

$$1 + R_{t} = 1.0588.$$

The one-month investment in Microsoft yielded a 5.88% per month return. Alternatively, $1 invested in Microsoft stock in month $t−1$ grew 
to $1.0588 in month $t$. The calculations using R are:

```R
P0 = 90
Pm1 = 85
R0 = (P0 - Pm1)/Pm1
c(R0, 1 + R0)

## [1] 0.0588 1.0588
```

#### Simple Returns - Python Example

Python: We will use formula (a) and pandas built in function pct_change to compute the simple returns for each day, for AAPL.

```python
import pandas as pd 
import numpy as np
import yfinance as yf

df = yf.download('AAPL', 
                 start='2000-01-01', 
                 end='2010-12-31',
                 progress=False)

df = df.loc[:, ['Adj Close']]
df.rename(columns={'Adj Close':'adj_close'}, inplace=True)

df['simple_rtn'] = df.adj_close.pct_change()

# remove redundant data
df.drop('adj_close', axis=1, inplace=True)
# Returns cannot be computed for the first observation, as there is no previous observation to use. R returns NA in this case. Clean the data.
df.dropna(axis=0, inplace=True)
```

#### Simple Returns - R Example

```R
## load the "dplyr" package
#library(dplyr)
# load the "quantmod" package
library(quantmod)

# Get Apple stock quotes (daily).
AAPL <- getSymbols('AAPL',
                   from = '2016/12/31',
                   to = '2018/12/31',
                   periodicity = 'daily')
## 'getSymbols' currently uses auto.assign=TRUE by default, but will
## use auto.assign=FALSE in 0.5-0. You will still be able to use
## 'loadSymbols' to automatically load data. getOption("getSymbols.env")
## and getOption("getSymbols.auto.assign") will still be checked for
## alternate defaults.
## 
## [1] "AAPL"

# shift the series back by one period and compute returns
r <- df$AAPL.Adjusted/lag(df$AAPL.Adjusted, k = 1) - 1

# drop NA from data
# Returns cannot be computed for the first observation, as there is no previous observation to use. R returns NA in this case. Clean the data.
r <- na.omit(r)

# build a data.frame containing simple returns
df <- data.frame(r)
colnames(df) <- c('simple_rtn')

## Do the same calculation above as a data frame.
#dat <- AAPL
#df <- as.data.frame(sapply( names(dat), function(x) coredata(dat[[x]])[,6] ))
#
### Note that this takes the Adjusted close values (see: dat[[x]])[,6]), the Objects have more, e.g.:
#
### names(dat[["AAPL"]])
### [1] "AAPL.Open"     "AAPL.High"     "AAPL.Low"      "AAPL.Close"
### [5] "AAPL.Volume"   "AAPL.Adjusted"
#
#rownames(df) <-
#    as.data.frame( sapply( names(dat), function(x) as.character(index(dat[[x]])) ) )[,6]
#
#df %>% 
#  mutate(lagged = lag(AAPL)) %>% 
#  mutate(simple_rtn = (AAPL - lagged) / lagged) %>% 
#  select(-lagged)
#
## remove redundant data
#df <- df[, (names(df) %in% c('simple_rtn'))]
```

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

### Cumulative Returns (or, Multiperiod Returns)

The simple two-month return on an investment in an asset between months $t−2$ and $t$ is defined as:

$$R_{t}(2) = \frac{P_{t} - P_{t-2}}{P_{t-2}} = \frac{P_{t}}{P_{t-2}} − 1.$$

Writing $\frac{P_{t}}{P_{t-2}} = \frac{P_{t}}{P_{t-1}} * \frac{P_{t-1}}{P_{t-2}}$ the two-month return can be expressed as:

$$R_{t}(2) = \frac{P_{t}}{P_{t-1}} * \frac{P_{t-1}}{P_{t-2}} - 1$$

$$ \ \ \ \ \ \ \ \ \ \ \ = (1 + R_{t})(1 + R_{t-1}) - 1$$

Then the simple two-month gross return becomes:

$$1 + R_{t}(2) = (1 + R_{t})(1 + R_{t-1}) = 1 + R_{t-1} + R_{t} + R_{t-1}R_{t} ,$$

which is a product of the two simple one-month gross returns and not one plus the sum of
the two one-month returns. Hence,

$$R_{t}(2) = R_{t-1} + R_{t} + R_{t-1}R_{t} .$$

If, however, $R_{t-1}$ and $R_{t}$ are small then $R_{t-1}R_{t} \approx 0$ and $1 + R_{t}(2) \approx 1 + R_{t−1} + R_{t}$ so that
$R_{t}(2) \approx R_{t−1} + R_{t}$ .

`Example 1.7. Computing two-period returns.`

Continuing with the previous example, suppose that the price of Microsoft stock in month $t−2$ is $80 and no dividend is paid between 
months $t−2$ and $t$. The two-month net return is:

$$R_{t}(2) = \frac{\$90 - \$80}{\$80} = \frac{\$90}{\$80} − 1 = 1.1250 − 1 = 0.1250 ,$$

or 12.50% per two months. The two one-month returns are:

$$R_{t−1} = \frac{\$85 - \$80}{\$80} = 1.0625 − 1 = 0.0625 ,$$

$$R_{t} = \frac{\$90 - \$85}{\$85} = 1.0588 − 1 = 0.0588 ,$$

and the geometric average of the two one-month gross returns is:

$$1 + R_{t}(2) = 1.0625 × 1.0588 = 1.1250 .$$

The calculations can be vectorized in R as follows:

```R
Pm2 = 80
# create vector of prices
P = c(Pm2, Pm1, P0)
# calculate vector of 1-month returns from vector of prices
R = (P[2:3] - P[1:2])/P[1:2]
R
## [1] 0.0625 0.0588
# calculate 2-month return from 2 1-month returns
(1 + R[1]) * (1 + R[2]) - 1
## [1] 0.125
# same calculation vectorized using R function cumprod()
cumprod(1 + R) - 1
## [1] 0.0625 0.1250
```

In general, the k-month gross return is defined as the product of k one-month gross returns:

$$1 + R_{t}(k) = (1 + R_{t})(1 + R_{t-1})...(1 + R_{t-k+1}) \ \ \ \ (1.9)$$

$$ \ \ \ \ \ = \prod_{j=0}^{k-1}(1 + R_{t-j}) .$$


#### Cumulative Returns (or, Multiperiod Returns) - Python Example

```python
import pandas as pd 
import numpy as np
import yfinance as yf

df = yf.download('AAPL', 
                 start='2000-01-01', 
                 end='2010-12-31',
                 progress=False)

df = df.loc[:, ['Adj Close']]
df.rename(columns={'Adj Close':'adj_close'}, inplace=True)

df['simple_rtn'] = df.adj_close.pct_change()
df['cumulative_rtn'] = (1 + df['simple_rtn']).cumprod() - 1

# remove redundant data
df.drop(columns=['adj_close', 'simple_rtn'], inplace=True)
```


#### Cumulative Returns (or, Multiperiod Returns) - R Example

```R
## load the "dplyr" package
#library(dplyr)
# load the "quantmod" package
library(quantmod)

# Get Apple stock quotes (daily).
AAPL <- getSymbols('AAPL',
                   from = '2016/12/31',
                   to = '2018/12/31',
                   periodicity = 'daily')
## 'getSymbols' currently uses auto.assign=TRUE by default, but will
## use auto.assign=FALSE in 0.5-0. You will still be able to use
## 'loadSymbols' to automatically load data. getOption("getSymbols.env")
## and getOption("getSymbols.auto.assign") will still be checked for
## alternate defaults.
## 
## [1] "AAPL"

# shift the series back by one period and compute returns
r <- df$AAPL.Adjusted/lag(df$AAPL.Adjusted, k = 1) - 1

# calculate cumulative returns
r.cum <- cumprod(1+r) - 1

# build a data.frame containing simple returns
df <- data.frame(r.cum)
colnames(df) <- c('cumulative_rtn')
```

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

### Log Returns

We calculate log returns as

$$r_{t} = \frac{log(P_{t})}{log(P_{t-1})} = log(P_{t}) - log(P_{t-1})

where $P$ is the price of an asset and t is a time period.

#### Log Returns - Python Example

Python: We will use formula (a) and pandas built in function pct_change to compute the simple returns for each day, for AAPL.

```python
import pandas as pd 
import numpy as np
import yfinance as yf

df = yf.download('AAPL', 
                 start='2000-01-01', 
                 end='2010-12-31',
                 progress=False)

df = df.loc[:, ['Adj Close']]
df.rename(columns={'Adj Close':'adj_close'}, inplace=True)

df['simple_rtn'] = df.adj_close.pct_change()
df['log_rtn'] = np.log(1 + df['simple_rtn'])
#or, we can calculate directly as follows:
#df['log_ret'] = np.log(df.adj_close) - np.log(df.adj_close.shift(1))

# remove redundant data
df.drop(columns=['adj_close', 'simple_rtn'], inplace=True)
```

#### Log Returns - R Example

```R
## load the "dplyr" package
#library(dplyr)
# load the "quantmod" package
library(quantmod)

# Get Apple stock quotes (daily).
AAPL <- getSymbols('AAPL',
                   from = '2016/12/31',
                   to = '2018/12/31',
                   periodicity = 'daily')
## 'getSymbols' currently uses auto.assign=TRUE by default, but will
## use auto.assign=FALSE in 0.5-0. You will still be able to use
## 'loadSymbols' to automatically load data. getOption("getSymbols.env")
## and getOption("getSymbols.auto.assign") will still be checked for
## alternate defaults.
## 
## [1] "AAPL"

# shift the series back by one period and compute returns
r <- df$AAPL.Adjusted/lag(df$AAPL.Adjusted, k = 1) - 1

# shift the series back by one period and compute log-returns
r.log <- log(AAPL$AAPL.Close) - log(lag(AAPL$AAPL.Close, k = 1))

# drop NA from data
# Returns cannot be computed for the first observation, as there is no previous observation to use. R returns NA in this case. Clean the data.
r <- na.omit(r)
# drop NA from data
r.log <- na.omit(r.log)

# build a data.frame containing simple returns
df <- data.frame(r.log)
colnames(df) <- c('log_rtn')
```

#### Matching Log Returns with Cumulative Returns - Python Example

**Cumulative Returns**

Compute the standard returns with respect to the first observation at each point in time ($R_{t,0}$ for every $t$). Use the following approaches:

  * (RIGHT) cumulate standard daily returns
  * (RIGHT) cumulate log-returns and convert to standard return using the following property: $r=ln(1+R)→R=exp(r)−1$
  * (WRONG) cumulate log-returns as if they were standard returns. This holds approximately, and the error becomes larger and larger when cumulating more and more returns

Python: We will use formula (a) and pandas built in function pct_change to compute the simple returns for each day, for AAPL.

```python
import pandas as pd 
import numpy as np
import yfinance as yf

df = yf.download('AAPL', 
                 start='2000-01-01', 
                 end='2010-12-31',
                 progress=False)

df = df.loc[:, ['Adj Close']]
df.rename(columns={'Adj Close':'adj_close'}, inplace=True)

df['simple_rtn'] = df.adj_close.pct_change()
df['log_rtn'] = np.log(1 + df['simple_rtn'])
#or, we can calculate directly as follows:
#df['log_ret'] = np.log(df.adj_close) - np.log(df.adj_close.shift(1))
df['cumulative_rtn'] = (1 + df['simple_rtn']).cumprod() - 1
df['log_rtn_vs_cumulative_rtn'] = np.exp(np.log(1 + df['simple_rtn']).cumsum())-1

# remove redundant data
df.drop(columns=['adj_close', 'simple_rtn', 'log_rtn'], inplace=True)
```

#### Matching Log Returns with Cumulative Returns - R Example

**Cumulative Returns**

Compute the standard returns with respect to the first observation at each point in time ($R_{t,0}$ for every $t$). Use the following approaches:

  * (RIGHT) cumulate standard daily returns
  * (RIGHT) cumulate log-returns and convert to standard return using the following property: $r=ln(1+R)→R=exp(r)−1$
  * (WRONG) cumulate log-returns as if they were standard returns. This holds approximately, and the error becomes larger and larger when cumulating more and more returns

```R
## load the "dplyr" package
#library(dplyr)
# load the "quantmod" package
library(quantmod)

# Get Apple stock quotes (daily).
AAPL <- getSymbols('AAPL',
                   from = '2016/12/31',
                   to = '2018/12/31',
                   periodicity = 'daily')
## 'getSymbols' currently uses auto.assign=TRUE by default, but will
## use auto.assign=FALSE in 0.5-0. You will still be able to use
## 'loadSymbols' to automatically load data. getOption("getSymbols.env")
## and getOption("getSymbols.auto.assign") will still be checked for
## alternate defaults.
## 
## [1] "AAPL"

# shift the series back by one period and compute returns
r <- df$AAPL.Adjusted/lag(df$AAPL.Adjusted, k = 1) - 1

# shift the series back by one period and compute log-returns
r.log <- log(AAPL$AAPL.Close) - log(lag(AAPL$AAPL.Close, k = 1))

# drop NA from data
# Returns cannot be computed for the first observation, as there is no previous observation to use. R returns NA in this case. Clean the data.
r <- na.omit(r)
# drop NA from data
r.log <- na.omit(r.log)
# calculate cumulative returns
r.cum <- cumprod(1+r) - 1

# cumulate log-returns and convert to standard returns
r.log.cum.right <- exp(cumsum(r.log)) - 1
# cumulate log-returns as if they were standard returns
r.log.cum.wrong <- cumprod(1+r.log) -1 

# create a unique xts object 
x <- merge(r.cum, r.log.cum.wrong, r.log.cum.right)
colnames(x) <- c('R', 'r.wrong', 'r.right')
# plot and compare
plot(x, legend.loc = 'topleft', main = 'Cumulative return computation')
```

![cumulative return computation](./assets/log-vs-cumulative-returns.png)

The green line coincides with the black one. This can be checked printing the values.

```R
# print values
head(x)
##                     R    r.wrong    r.right
## 2007-01-04 0.02219568 0.02195294 0.02219568
## 2007-01-05 0.01491643 0.01464939 0.01491643
## 2007-01-08 0.01992836 0.01964767 0.01992836
## 2007-01-09 0.10465392 0.10101525 0.10465392
## 2007-01-10 0.15751779 0.15248306 0.15751779
## 2007-01-11 0.14319811 0.13813675 0.14319811
```

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>
