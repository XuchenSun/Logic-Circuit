# Logic-Circuit

4bit Full adder
Input: X4X3X2X1X0,  Y4Y3Y2Y1Y0.   X4andY4 is special.
Output: Z4Z3Z2Z1Z0

Z0=X0⊕Y0
C0=X0*Y0

Z1=X1⊕Y1⊕C0+X1Y1C0
C1=X1Y1+X1C0+Y1C0+X1Y1C0
.....
