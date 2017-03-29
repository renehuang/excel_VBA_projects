 *******************************************************
 * Copyright (C) 2017 MENGYU HUANG <renehuang0917@gmail.com>
 * 
 * This file is part of {Numerical Analysis}.
 * 
 * {Numerical Analysis} can not be copied and/or distributed without the express
 * permission of MENGYU HUANG
 *******************************************************/
 





=======================================================================================
					Read Me
=======================================================================================

These spreadsheets are made for my 'numerical analysis' coursework. 

1. Option Greeks:

Make an Excel spreadsheet that does the following: 
1). User inputs spot, domestic interest rate, foreign interest rate, volatility, strike, today’s date, expiration date 
2). The spreadsheet outputs (simultaneously or based on a user choice): Value, Delta, Gamma, Vega, Theta, Phi (rate of change of value with respect to change of foreign interest rate), Rho (rate of change of value with respect to change of domestic interest rate) of the call option 
3). The user can select one Greek from the list of the Greeks above, the starting spot, the end spot and the number of spots between the start and end value, (maybe then press a button), the spreadsheet gives the spot-Greek graph. 
Save your spreadsheet with the following data while exhibiting the spot-Theta graph (a USD/JPY call option, valued in JPY): 
Spot is 120, USD zero rate is 4%, JPY zero rate is 0.5%, strike is 119, vol is 10%, time to expiration is 92 calendar days. The user then wants to see the spot-Theta graph from spot = 100 to spot = 150 with 99 points in between. So graph is between from Theta with spot = 100, 100.5, 101, 101.5, …, 149.5, 150.  









2. Interpolation (Linear/ polynomial/ cubic spline)

Using the given market data of the volatility smile by delta for one year option:

Make an Excel spreadsheet that calculates  
1). the linear interpolated vol 
2). the polynomial interpolated vol using Neville’s algorithm 
3). the cubic spline interpolated vol 
for any given delta that lies between the smallest and largest delta  
In particular, calculate the value of the vol that corresponds to the Delta of 45 and save the spreadsheet showing the value and calculation (it is preferable to show some intermediate calculations in some cells) 

4). Produce a graph of the interpolated smile 

When you plot the graph, plot it in such a way that the values of Delta decreases when you look at the xaxis from left to right. This corresponds to increasing strikes for call options. 
The spreadsheet should have a toggle (or some control) to let user choose which interpolation he would like to use. And the graph shows the entire interpolated smile of his choice. The user should in general be able to change the values of the input Deltas, and the input vols (then spreadsheet would recalculated the interpolated vol upon request) 
For the purpose of this homework, you can assume that the user always gives you nine points, and will not change the number of given points. 
For the cubic spline, you should provide a choice for users to control the “2 degree of freedom” discussed in class. Please save the spreadsheet when handing in to default to the natural cubic spline if chosen. 