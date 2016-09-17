# TI-84 Statistics Programs

TI-84 calculator series is relatively popular choice for a lot of college-level math classes. Since programmers in general are lazy I wrote some small scripts to automate some calculations.
Programs in this repository are compiled in TI-83 Plus mode, but they were only tested on TI-84. In addition to compiled versions in `TI-84` directory you can also grab textul versions from `TXT` folder and type them manually.

## Available programs
#### FENCE
Fence calculates both Lower Fence & Upper Fence along with Interquartile Range (IQR). Program expects values of Q1 & Q3.  
If you have set of data type them into one of the lists and perform `1-Var Statistics` from STAT menu, than run FENCE and when program ask for Q1 and Q3 use `VARS` button and choose precalculated Q1 & Q3 from Statistics menu.

#### FILTER / FLTLT / FLTMT
That set of three programs filtrates data for values in given range. Additionally total number of values after filtration along with percentage value comparing to total are displayed.
 * FILTER filtrates values which are ≥ MIN and ≤ MAX
 * FLTLT filtrates values which are < MAX
 * FLTMT filtrate values which are > MIN
 
*All three programs utilize `L₆` for temporary storage & `L₅` as a storage for filtered values.*

#### RF
Program calculates relative frequency for each value from given data set (`LST` argument) optionally providing rounded values to defined places after decimal point (`R` argument).  
Since output values are presented as an decimal values you can also utilize that code to calculate probability of simple events.

*Program utilize `L₆` for of rounded values and `L₅` for values before rounding.*

#### RNG
This is more shortcut than a self contained program. Displays range using values from `1-Var Statistics` (so you have to run it first - otherwise you'll get an garbage or error).

#### VAR
This is more shortcut than a self contained program. Displays variance for sample (`SAM`) and population (`POP`) using values from `1-Var Statistics` (so you have to run it first - otherwise you'll get an garbage or error).

#### ZS / ZSRAW
Calculates z-score of given value in respect of data. Both programs display value rounded to specified number of places after decimal mark (`R` argument).
 * ZS - calculates z-score from mean and std-dev
 * ZSRAW - calculates z-score from given list (*uses `L₆` for temporary storage*)
 

## Other resources
Besides programs published in this repository I also highly recommend [`MATH200A` by Stan Brown](http://brownmath.com/ti83/math200a.htm).