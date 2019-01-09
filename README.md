# PlotPI
<br>
Begin by changing the variable "DigitCount =  10000" to the number of digits you want to plot.<br>
<br>
Plot PI() to nth number of digits.  The direction of the plot will be like a 10 digit clock with zero (0) straight up.
<br>
<br>Plot direction will be defined by the dictionary xDict and yDict

<br>xDict = {0: 0, 1: 1.2, 2: 2.4, 3: 2.4, 4: 1.2, 5: 0, 6: -1.2, 7: -2.4, 8: -2.4, 9: -1.2}
<br>yDict = {0: 3, 1: 1.8, 2: 0.6, 3: -0.6, 4: -1.8, 5: -3, 6: -1.8, 7: -0.6, 8: 0.6, 9: 1.8}
<br><br>
So for 3.1415<br><br>
  Plot starts out at coordinate x=0, y=0<br>
  the three (3) will be defined as x=2.4 y=-0.6 from previous location<br>
      - Decimal is skipped -<br>
  the one (1) will be defined as x=1.2 y=-1.8 from previous location<br>
  the four (4) will be defined as x=1.2 y=-1.8 from previous location<br>
  the one (1) will be defined as x=1.2 y=-1.8 from previous location<br>
  the five (5) will be defined as x=0 y=-3 from previous location<br>
<img src="PlotDirection.png" alt="Plot Direction" style="width:143px;height:150px;">
<br>
The Pi_Plot(pyQtGraph)Color.py just adds dynamic color to the plot.  The total number of digits of PI() calculated is split into 10 data buckets and each bucket is assigned a different color.  So, once plotted, the trace will have ten (10) different colors.<BR><BR>
<img src="MillionDigitsOfPI.gif" alt="Million Digits of PI()" style="width:143px;height:150px;"><BR>
<table>
 <tr>
  <th>Date/Time</th> <th>Comment</th>
 </tr>
 <tr>
  <td>2019-01-09 13:48:09.521180</td> <td>Begin Calculating PI().</td>
 </tr>
 <tr>
  <td>2019-01-09 13:52:41.791404</td> <td>PI() is calculated.</td>
 </tr>
 <tr>
  <td>00:04:32.270224</td> <td>Total Calc Time</td>
 </tr>
 <tr>
  <td>2019-01-09 13:52:41.803406</td> <td>Begin Plotting PI()</td>
 </tr>
 <tr>
  <td>2019-01-09 13:52:42.870512</td> <td>PI() Plot Completed</td>
 </tr>
 <tr>
  <td>00:00:01.067106</td> <td>Total Plot Time</td>
 </tr>
</table>
