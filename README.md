![Biden & Warren](https://github.com/johannesfritz/electoddility/blob/master/pics/190819/3%20Biden%20%26%20Warren.png)

# electoddility
How electable is a candidate, then?

## backing out electability (= head-to-head odds for candidate X vs Trump)

I operationalise 'electability' as the probability of a presidential candidate to win the presidency given that s/he is nominated. There are other ways to think about this, but this is mine.

In short, one can back this electability out from the odds implied by three `Betfair` betting markets ([Presidency](https://www.betfair.com/exchange/plus/politics/market/1.128151441) | [Democratic nomination](https://www.betfair.com/exchange/plus/politics/market/1.128161111) | [Republican nomination](https://www.betfair.com/exchange/plus/politics/market/1.128999265)) plus a few assumptions. 

The probability of a `presidential candidate to win the presidency` is the conditional probabilty `p(win|nominated) = p(presidency)/p(nominated)`. Simply dividing two of the Betfair marekets' odds would *only* give you the probability of a candidate for winning against some composite opponent. 


To get the head-to-head probability of candidate X vs President Donald Trump, the main necessary assumption is the `average probability of a Republican winning the presidency given that s/he's nominated instead of Trump` (p(Repulican wins|Republican nominee != Trump). I asumme `30%` but could make arguments for other values below ~50%. All that does is shift around the Democrats' lines vertically, though. 

Longer version to follow, if necessary.
