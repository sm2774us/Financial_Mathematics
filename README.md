# Finance_and_AI_ML
Personal Repository for Quantitative Finance and AI/ML topics

## Table Of Contents <a name="top"></a>

1. [Rules of Numbers](#rules-of-numbers)  
2. [Rules of Exponents](#rules-of-exponents)
3. [Rules of Logarithms](#rules-of-logarithms)
4. [Calculating Returns](#calculating-returns)

### Rules of Numbers

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

### Rules of Exponents

* **Rule 1 (Product Rule):** $a^m*a^n = a^{m+n}$
* **Rule 2 (Quotient Rule):** $a^m/a^n = a^{m-n}$
* **Rule 3 (Power of a Power Rule):** $(a^m)^n = a^{mn}$

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>

### Rules of Logarithms

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

### Calculating Returns

A return, also known as a financial return, in its simplest terms, is the money made or lost on an investment over some period of time.

A return is a percentage defined as the change of price expressed as a fraction of the initial price.

Returns exhibit more attractive statistical properties than asset prices themselves. Therefore it also makes more statistical sense to analyze return data rather than price series.

One-period return
Holding an asset from time $t − 1$ to $t$, the value of the asset changes from  $P{_{t−1}}$
  to  $P{_t}$. Assuming that no dividends paid are over the period.

Then the one-period simple return is defined as:

$$R_{t} = \frac{P_{t} - P_{t-1}}{P_{t-1}} \ \ (a)$$

The one period gross return is defined as:

$$\frac{P_{t}}{P_{t-1}} = {R_{t}} + 1$$
 
It is the ratio of the new market value at the end of the holding period over the initial market value.

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
```

```R
# load the "dplyr" package
library(dplyr)
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

# Do the same calculation above as a data frame.
dat <- AAPL
df <- as.data.frame(sapply( names(dat), function(x) coredata(dat[[x]])[,6] ))

## Note that this takes the Adjusted close values (see: dat[[x]])[,6]), the Objects have more, e.g.:

## names(dat[["AAPL"]])
## [1] "AAPL.Open"     "AAPL.High"     "AAPL.Low"      "AAPL.Close"
## [5] "AAPL.Volume"   "AAPL.Adjusted"

rownames(df) <-
    as.data.frame( sapply( names(dat), function(x) as.character(index(dat[[x]])) ) )[,1]

df %>% 
  mutate(lagged = lag(AAPL)) %>% 
  mutate(simple_rtn = (AAPL - lagged) / lagged) %>% 
  select(-lagged)
```

<div align="right"><a href="#top" target="_blacnk"><img src="https://img.shields.io/badge/Back To Top-orange?style=for-the-badge&logo=expo&logoColor=white" /></a></div>
