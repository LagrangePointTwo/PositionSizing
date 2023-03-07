# PositionSizing
A javascript simulation demonstrating the effect of position sizing on the outcomes of a series of bets.

* For this demo the odds of winning are 51%, and of losing are 49%.  
* The reward for winning is +75%, and you risk losing 50%.    
* The optimal position size given by the Kelly Criterion is f* = (0.51/0.50) - (0.49/0.75) = 0.3666667. 

### An example run of three competing strategies: 
![image](https://user-images.githubusercontent.com/127203032/223408786-3fb65b4b-bfd7-48f0-8a94-43633e80276d.png)

(1) "Bet the Farm"   (100% Position Size)  
(2) "Smaller Bets"   (15% Position Size)    
(3) "Kelly Optimized" (Calculated dynamically, 36.7% in this case)  

### The Kelly optimized position size + wins and losses for the simulation run are console logged:
![image](https://user-images.githubusercontent.com/127203032/223412128-0671fb37-bed4-4b38-8e64-bb205f8584ca.png)


