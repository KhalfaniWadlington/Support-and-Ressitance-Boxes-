# Support-and-Ressitance-Boxes-
######This is an indicator for the forex market, an indicator is a tool that helps traders and analyzers get a estimation as too whether the market will go up or down. A few months ago I wanted to make my own strategy for trading the forex market so I created an indicator that  creates a signal once a asset makes a specific pattern.

This indicator is based the MetaTrader platform:  Metatrader is an application that displays currency market data, it also has its own programming language MQL4. MQL4 is comparable to C++. 

This is based of the ZigZag indicator which makes points on the market chart at the top and bottoms of prices.

 In the following example I only created the blue boxes and the purple line.

[This is what it looks like in action](https://github.com/KhalfaniWadlington/Support-and-Ressitance-Boxes-/blob/master/Screenshot%20from%202016-06-30%2020:20:47.png)
this example is pretty dull


I create a range from each point. 
From these ranges I apply some tests to see if they are in my strategy. 
If they pass all the tests I draw them expilicitly.

The puple line on the y axis in this image is the line of death.The purple line moves wtih time as new prices are graphed. After enough time passes and the purple line reaches a box then it will be deleted. 

It checks if price stays in the box when a new bar is created and uses the  MQL4 tool to create an alert.


*when looking at the source it is better to look at in a c++ ide so it color codes it.



