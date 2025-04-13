---
tags:
  -Brazil
  -Finance
  -Development
categories:
  -Blog
math: true
title: "The Irrationally High Interest Rates in Brazil"
---
<!--more-->
The central bank interest rate is an economic variable of critical importance in the economic development of a nation. It determines the returns of all government securities, and every investor uses it as a benchmark when making risky investment decisions. No investment will be made unless its expected rate of return is higher than the central bank interest rate by a margin large enough to compensate for the riskyness of the investment. Put simply, **increasing the interest rate decreases the viability of real investments in the economy.**

Brazilian interest rates are incredibly high, and have been a drag on investments for a long time. In order to put this into perspective, I have plotted the nominal returns in the Brazilian stock market (Ibovespa) versus the Brazilian central bank interest rate (Selic). The comparison can give an idea of how profitable investing in real economic activity versus the risk-free government subsidy. Over a sufficiently long time period of time, the stock market *should* outperform the central bank rate, as investors require compensation for the higher risk of stock market positions, as any introductory finance text book will tell you. The intuition is simple, higher risk -> higher reward.

It turns out that in Brazil, the opposite is the case: **the risk-free investment outperforms the risky investment!** The first plot below shows the development of a R$100 investment made in August 1994 (the early months after the Brazilian Real was adopted as currency) up to August 2023. After 29 years the investment in the security that tracks the central bank interest rate grew to ~6800 Reais while the stock market investment grew to ~2200 Reais. The total return of the investment was 3 times that of the risky stock market investment!

![](/assets/images/2023-12-28-the-irrationally-high-interest-rates-in-brazil/image1.png)

This second plot shows the rolling annual rate of return of the two investments, highlighting the risk differential. I know that I would prefer to enjoy the smooth ride on the orange line (earning 3 times as much) than the bumpy ride of the bovespa)

![](/assets/images/2023-12-28-the-irrationally-high-interest-rates-in-brazil/image2.png)

It is not surprising that depending on the measure, studies often estimate a negative equity risk premium for the Brazilian economy, such as [Walter Gonçalves, et al (2011)](https://www.proquest.com/openview/3ca1cba8c4d6cf0478b751d98367201c/1?pq-origsite=gscholar&cbl=2028896).

The problem lies not in the bad performance of the stock market, but in the absurdly high interest rate. Over the entire period, the Stock market return has been around 11.1% per year (a normal rate of return), while the central bank rate has been around 15.7% per year.

So finally, the remaing question is: **Why would any investor in this country actually want to invest real productive activities instead of earning a rent from the central bank?**

The absurdity of the past 30 years is undeniable. As of writing, Brazil still has one of the highest real rates of interest in the world ([Second place in this list of 40 countries](https://web.archive.org/web/20250413164339/https://g1.globo.com/economia/noticia/2023/12/13/ranking-mundial-taxa-de-juros-reais.ghtml)) and I do not have high hopes a structural shift any time soon. Why are they so high? Beyond being a stable source of income for rentiers, the high rate keeps the Real appreciated (by keeping demand for Brazilian currency high for foreign investors) and thus sustains the real purchasing power of Brazilians that have to buy industrial goods produced abroad. Lowering the interest rate significantly and permanently would not be a policy decision free of costs and risks.


<iframe src="https://data.worldbank.org/share/widget?indicators=NE.GDI.FTOT.ZS&locations=BR" width='700' height='450' frameBorder='0' scrolling="no" ></iframe>



Brazil has a lot to do in its path to economic development. Investment (as a % of GDP) has been declining in the past decade, slowing down the growth in Brazil's productive capacity. It would be wise to remove the breaks on the economy placed by the central bank and let capital be employed where it can actually enable the development of the nation

---  

**Sources**   
* IBOVESPA INDEX  
Yahoo finance
link: https://finance.yahoo.com/quote/%5EBVSP/history?guccounter=1  
direct download link: https://query1.finance.yahoo.com/v7/finance/download/%5EBVSP?period1=735868800&period2=1693008000&interval=1d&events=history&includeAdjustedClose=true  

* SELIC  
Banco Central do Brasil  
Code: 1178  
Full name: Interest rate - Selic in annual terms (basis 252)  
link: https://www3.bcb.gov.br/sgspub/localizarseries/localizarSeries.do?method=prepararTelaLocalizarSeries

* Gross fixed capital formation  
  World Bank  
  link: https://data.worldbank.org/indicator/NE.GDI.FTOT.ZS?locations=BR
