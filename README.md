# PlotPI
Plot PI() to nth number of digits.  The direction of the plot will be like a 10 digit clock with zero (0) straight up.
<br>
<br>Plot direction will be defined by the dictionary xDict and yDict
<br>xDict = {0: 0, 1: 1.2, 2: 2.4, 3: 2.4, 4: 1.2, 5: 0, 6: -1.2, 7: -2.4, 8: -2.4, 9: -1.2}
<br>yDict = {0: 3, 1: 1.8, 2: 0.6, 3: -0.6, 4: -1.8, 5: -3, 6: -1.8, 7: -0.6, 8: 0.6, 9: 1.8}
<br><br>
So for 3.1415<br><br>
  Plot starts our at coordinate x=0, y=0<br>
  the three (3) will be defined as x=2.4 y=-0.6 from previous location<br>
      - Decimal is skipped -<br>
  the one (1) will be defined as x=1.2 y=-1.8 from previous location<br>
  the four (4) will be defined as x=1.2 y=-1.8 from previous location<br>
  the one (1) will be defined as x=1.2 y=-1.8 from previous location<br>
  the five (5) will be defined as x=0 y=-3 from previous location<br>
