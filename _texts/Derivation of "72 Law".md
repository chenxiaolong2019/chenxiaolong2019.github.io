---
layout: page
title: Derivation of "72 Law"
author: Chen Xiaolong
---
## What is "72 Law"

The so-called "72 law" is to calculate interest with 1% compound interest. After 72 years, the principal will double.

## Principle
The future value (FV) of periodic compound interest is:

<center>
	<img src="http://latex.codecogs.com/gif.latex?FV=PV(1+r)^t"> 
</center>

PV is the present value, t is the number of periods, and r is the interest rate for each period.

When the investment doubles, FV=2PV. After substituting the above formula, it can be simplified to:

<center>
<img src="http://latex.codecogs.com/gif.latex?2 = (1+r)^t"> 
</center>

Logarithm on both sides
<center>
<img src="http://latex.codecogs.com/gif.latex?ln2=t\times ln(1+r)"> 
</center>
<center>
<img src="http://latex.codecogs.com/gif.latex?\frac{ln2}{ln(1+r)}=t"> 
</center>

According to Taylor Series Approximation
<center>
<img src="http://latex.codecogs.com/gif.latex?ln(1+r) \approx r"> 
</center>
also because
<center>
<img src="http://latex.codecogs.com/gif.latex?ln2\approx0.69"> 
</center>
so
<center>
<img src="http://latex.codecogs.com/gif.latex?\frac{0.69}{r}\approx t"> 
</center>
End
