# PositionSizing

A javascript simulation demonstrating the effect of position sizing on the outcomes of a series of bets.

* For this demo the odds of winning are 51%, and of losing are 49%.  
* The reward for winning is +75%, and you risk losing 50%.    
* The optimal position size given by the Kelly Criterion is f* = (0.51/0.50) - (0.49/0.75) = 0.3666667. 

Watch the <a href="https://youtu.be/4XPpC8KcttE">YouTube video covering this topic here!</a>

DISCLAIMER: Nothing in this repository, code or accompanying video is financial advice. If you place bets, trades or investments in real life, you do so at your own risk. This demonstration is NOT a solicitation to buy, trade, or bet anything, and is for educational purposes ONLY.

## Why Position Sizing is Important

A lot of people mainly consider odds and the risk vs. reward when placing bets or trading assets, but fail to understand the importance of position sizing (the fraction of their allotted money/resource to place on that bet). While choosing good bets or being able to find good trading opportunities is a precursor to a successful long term strategy, it is only half the story. 

### An example run of three competing strategies: 
![image](https://user-images.githubusercontent.com/127203032/223408786-3fb65b4b-bfd7-48f0-8a94-43633e80276d.png)

(1) "Bet the Farm"   (100% Position Size)  
(2) "Smaller Bets"   (15% Position Size)    
(3) "Kelly Optimized" (Calculated dynamically, 36.7% in this case)  

### Simulation run details are logged in the console:
<br/>
<p align="center">
<img width="500" src="https://user-images.githubusercontent.com/127203032/223412128-0671fb37-bed4-4b38-8e64-bb205f8584ca.png">
</p>
<br/>
Long term success will largely be determined by sizing positions correctly, which ends up having a large effect since results are compounded. Even a strategy that exclusively places bets with a positive average percent gain can lose big over the long run (with avg. percent gain calculated arithmetically i.e. avg = win_prob * amount_to_win% - loss_prob * amount_to_lose% > 0). It is therefore important to think in terms of geometric gain expectency which for high risk bets can be negative if sized incorrectly even when arithmetic gain expectency is positive.

### Additional Resources:

Wikipedia Entry on the Kelly Criterion: https://en.wikipedia.org/wiki/Kelly_criterion <br/>
Paper on Position Sizing Experiment: https://arxiv.org/pdf/1701.01427.pdf


