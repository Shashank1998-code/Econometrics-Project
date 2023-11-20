# Econometrics-Project

Project Outline: A study detailing the impact of Macroeconomic variables on US Inflation Rates.

## Variables of Interest: 
Inflation: Inflation rate (Consumer Price Index)
M2M2: Broad money supply
M1M1: Narrow money supply
RealGDPRealGDP: Real Gross Domestic Product
InterestRatesInterestRates: Interest rates (e.g., lending rate)
UnemploymentUnemployment: Unemployment rate

## Period of Interest: 
1990-01-01 - 2000-01-01

## Aproaches Used:

### 1) Regression Model Equation:
   The basic regression model to predict inflation based on the mentioned variables can be specified as follows:

   Inflationt=β0+β1×M2t+β2×M1t+β3×RealGDPt+β4×InterestRatest+β5×Unemploymentt+εtInflationt​=β0​+β1​×M2t​+β2​×M1t​+β3​×RealGDPt​+β4​×InterestRatest​+β5​×Unemploymentt​+εt​

   where:

    InflationtInflationt​ is the inflation rate in period t,
    M2t M1t RealGDPt InterestRatest and Unemployment​ are the values of the respective variables in period t,
    β0​ is the intercept term,
    β1,β2,β3,β4,β5​ are the coefficients to be estimated,
    εt is the error term.

### 2) Vector Autoregression (VAR) Model Equation:

    A time series modeling approach, VAR model with lagged variables:

    Yt=A0+A1Yt−1+A2Xt−1+εtYt​=A0​+A1​Yt−1​+A2​Xt−1​+εt​

    where:

    Yt​ is a vector of endogenous variables including Inflation​,
    Xt−1 is a vector of lagged exogenous variables including M2t−1​, M1t−1, RealGDPt−1, InterestRatest−1​, Unemploymentt−1,
    A0 is a constant vector,
    A1 and A2​ are coefficient matrices,
    εt is a vector of error terms.
