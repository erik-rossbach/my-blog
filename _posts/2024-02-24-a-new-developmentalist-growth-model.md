---
title: A New-Developmentalist Growth Model
categories:
- Blog
tags:
- Brazil
- Macroeconomics
- Development
- Modelling
math: true
---
<!--more-->
The slow-down of economic development experienced by Brazil and other middle-income countries can be well explained by "New Developmentalism". New Developmentalism is a macroeconomic framework (or school of thought) originated by Luiz Carlos Bresser-Pereira that puts international trade at the heart of the explanation of the middle income trap. For a short introduction to the framework, see [this paper by Bresser-Pereira](https://www.bresserpereira.org.br/papers/2017/299-New%20Developmentalism-DOC-Format.pdf).

In this framework the industrial sector plays a key role in economic development. The reason for this is, at the simplest level, that industrial sector tends to have higher levels of labor productivity, and thus can support a higher GDP per capita. Additionally, it is a dynamic sector, responsible for innovation through research and development, and demands skilled employees working high-paying jobs. Thus, development is intrinsically linked to industrialization.

A simplistic summary of the main causal chain in the new-developmentalist explanation of the would be:
1. Brazil's low per-capita growth is caused by it's de-industrialization trend
2. The de-industrialization trend is caused by an "over-appreciated currency"
3. The over-appreciated currency is explained by dutch-disease and/or a strategy of "growth by external savings"

The new-developmentalist understanding involves three possible "equilibria" for the exchange rate (measured as the price of foreign currecy in domestic currency, i.e. BRL/USD):
1. The industrial equilibrium exchange rate: the exchange rate at which industrial companies operating with state-of-the-art technology remain competitive in international markets
2. The current-account equilibrium exchange rate: the exchange rate at which imports equal exports
3. The market exchange rate: the exchange rate solved for in competitive currency markets (which include the potential effects of high interest rates set to attract external savings)

Through the new-developmentalist lens, the macroeconomic problem of middle-income countries is that the industrial equilibrium can be above (more depreciated) than the current-account equilibrium rate due to dutch-disease (high productivity of commodity sector causing high exports and appreciating the currency). Additionally, the market rate can be abouve the current-account equilibrium rate due to the government imposing a high interest rate trying o attract foreign capitals.

The relationship is summarized in the equation below:
$$
e^{market} = e^{ind} + \underset{\text{Dutch disease}}{(e^{CAB} - e^{ind})} + \underset{\text{External savings strategy}}{(e^{market} - e^{CAB})}
$$

The first new-developmentalist, quantitative growth model has only been published in 2020, by [Oreiro, da Silva and Dávila-Fernández (2020)](https://www.sciencedirect.com/science/article/abs/pii/S0954349X20303830). As I am working through new-developmentalist ideas, I decided to reproduce their model in python, and share it with anyone who might be interested in playing with it. See here the [Github repository for the model](https://github.com/riktross/new-developmentalist-macro-model.git)

I will share some of the results here. The model starts in a steady-state growth path, and a change to the parameter $\beta_1$, that regulates the sensitivity of the share of manufacturing to the exchange rate. This parameter captures the effect of policies that protect the national industry, such as import tariffs. The change, interpreted as a reduction in industry protection, introduces the dutch disease to the model, and a slow de-industrialization process. We analyze three scenarios, each with a different response by government toward the exchange rate (managed through interest rate policy). 

![](/assets/images/2024-02-24-a-new-developmentalist-growth-model/image1.png)

**Exchange rate**
The three scenarios differ according to how the exchange rate is set after the appearance of the dutch disease:
1. The market exchange rate is set at the industrial equilibrium (neutralization of dutch disease)
2. The market exchange rate is set at current-account balance equilibrium
3. The market exchange rate is set below the current-account equilibrium due to the government targetting external savings

![](/assets/images/2024-02-24-a-new-developmentalist-growth-model/image2.png)

**De-industrialization:** 

In the blue curve, the dutch disease is neutralized, and thus the share of manufacturing remains stable. The other curves see a decrease in the share of manufacturing in output.

![](/assets/images/2024-02-24-a-new-developmentalist-growth-model/image3.png)

**Interest rates:** 

A mirror image of the exchange rate graph, due to the inverse relationship between exchange rates and interest rates

![](/assets/images/2024-02-24-a-new-developmentalist-growth-model/image4.png)

**Output:** 

Output grows fastest when dutch disease is neutralized, because productivity grows faster when the share of industry is higher, due to the innovative nature of the sector.

![](/assets/images/2024-02-24-a-new-developmentalist-growth-model/image5.png)

**Labor productivity:** 

There is a brief increase in output and employment after the appreciation of the exchange rate, since the lower exchange rate reduces the propensity to import. This lower unemployment in that period increases productivity through the labor market channel. But that increase is short-lived, as the effect of de-industrialization dominates in the long-run

![](/assets/images/2024-02-24-a-new-developmentalist-growth-model/image6.png)

**Real wage:** 

The real wage initially rises in the scenario of an appreciated exchange rate, and decreases in the scenario where the dutch disease is neutralized through depreciation. This is because of the imported goods consumed by workers. But only the neutralization scenario can maintain the real wage growth in the long run, as the other two scenarios are dragged down by de-industrialization and the consequent slow-down in productivity growth. The practice of appreciating the currency to keep real wages high in the short-term is called "exchange rate populism".

**Conclusions**


The model by [Oreiro, et. al (2020)](https://www.sciencedirect.com/science/article/abs/pii/S0954349X20303830) is a great addition to the literature on new-developmentalism, as it makes its interpretation of the key dynamics of the middle-income trap completely explicit. Hopefully my reproduction of the model can help you, the reader, to investigate the new-developmentalist propositions further.

---  

**Sources**   
[Bresser-Pereira (2017)](https://www.bresserpereira.org.br/papers/2017/299-New%20Developmentalism-DOC-Format.pdf)

[Oreiro, da Silva and Dávila-Fernández (2020)](https://www.sciencedirect.com/science/article/abs/pii/S0954349X20303830)
