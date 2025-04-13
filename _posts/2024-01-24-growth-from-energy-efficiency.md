---
tags:
- Growth
- Energy
- Decoupling
categories:
- Blog
title: Growth from Energy Efficiency
math: true
---
<!--more-->
A few weeks ago I have come across to a great blog called ["Do the Math"](https://dothemath.ucsd.edu/2011/07/galactic-scale-energy/), authored by astrophysicist Tim Murphy. It is an interesting blog, that uses simple back-of-the-envelope calculations to highlight the scale of our civilization, and the challenges that it faces and will continue to face due to its confinement to a finite planet. One of the most interesting blogposts is called "Galactic-Scale Energy", and shows that growth in energy consumption cannot continue forever. An update of the argument is present in Tim Murphy's freely available book [Energy and Human Ambitions on a Finite Planet](https://escholarship.org/uc/energy_ambitions). I highly recommend anyone to read it.

The main argument is an *reductio ad absurdum* type of argument, that illustrates that exponential growth rates quickly raise our level of energy consumption to absurd sizes. I will reproduce the two main points here:
Premises:
1. The world consumes energy at a scale of **~18TW**
2. We grow our energy consumption at least at a rate of **2.3%** p.a. 
3. The maximum amount of energy from sunlight on planet Earth with solar panels of 20% efficiency (highly efficient) is **~6000 TW**
4. The production of energy creates waste heat on the energy surface (Stefan-Boltzman Law)

Conclusions:
1. If we rely on solar energy, the entire solar potential would be reached within 250 years (and we will all live in shadow)
2. If we rely on some non-solar source (e.g. fusion energy) we will cause temperature increases of 1°C in 200 years, 9°C in 300 years, and 100°C (boiling temperatures) in less than 420 years
3. Energy growth must end in a matter of a few centuries

This is a striking conclusion, given that income and energy consumption are so closely related. The end of growth for energy has important implications for growth, given that energy is a vital input to all production processes, with no potential substitute. [This chart from Our World in Data](https://ourworldindata.org/grapher/energy-use-per-person-vs-gdp-per-capita) shows the tight relationship between energy consumption and GDP quite well.

<iframe src="https://ourworldindata.org/grapher/energy-use-per-person-vs-gdp-per-capita" loading="lazy" style="width: 100%; height: 600px; border: 0px none;"></iframe>

With this post, I want to decompose economic growth into two numbers
* Growth in GDP per unit energy [$/kWh] (inverse of energy intensity)
* Growth in energy consumption per capita [kWh/person]
  
i.e. decompose GDP into the simple identity:
$$ GDP_{per \ capita}=Energy_{per \ capita} \cdot \frac{GDP}{Energy}$$

And evaluate the relative size of both of these components in economic growth. I am looking at things from a global scale to avoid the issue of countries simply off-shoring energy-intensive production activities to other countries, and importing the resulting goods, hiding the true energy intensity of their lifestyle.  

Below you can see the decomposition of economic growth into the two components by decade. The 70's and 2000's saw the biggest growth in per capita energy consumption, of around 1.2-1.3%. In the 80's and 2010's the growth in per capita energy consumption has been much lower, below 0.5%. Surprisingly, energy consumption per capita has been virtually nil over the 90's. Still, GDP per capita grew by almost 2% over the period. This to me is a positive data point, that shows that to some extent there might be a possibility to grow GDP without growing energy consumption, especially if policies aim for that goal (which I am sure we should expect to happen)

![](/assets/images/2024-01-24-growth-from-energy-efficiency/contributions_to_growth.png)

Over the entire period, the decomposition is as shown below. Around 0.7% growth in energy consumption per capita, and a bit more than 1.2% of GDP per unit energy. If one were to read these numbers very naively, one could say that GDP per capita could have grown 1.2% over the period without any additional kWh being consumed per person, per year, since the 1970. But unfortunately this is not so simple, since much of the gains in productivity might only have been possible with increased scale.

![](/assets/images/2024-01-24-growth-from-energy-efficiency/growth_rates.png)

I personally am not that optimistic around our decoupling potential, but I strongly hope that I will be proven wrong in this respect. The numbers that quickly calculated here slightly improved my outlook on this matter, since I did not think that energy intensity has been dropping at twice the rate that energy consumption has been growing. Still, in order to truly become sustainable we need to end - and possibly reverse - the growth in energy consumption. How this can be done in an orderly and equitable manner is a vital question that requires a lot of collective thinking from our society.
