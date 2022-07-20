# Arthimatic-Unit-Using-Logic-Gates
An arithmetic unit that is capable of adding, subtracting, multiplying, and dividing two 5-bit signed numbers and the result is displayed on 7 segment


Note: These files are .circ and I have provided the software for running them "logisim-win-2.7.1.exe"   (logisim).
The main file to run is "Main Project of Logic.circ" it has the main circuit and the ALU.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
The numbers' magnitude is 4-bit and the 5th bit is for sign were 1(-ve) and 0(+ve)

-------------------------------------------------------------------------------------------------------------------------------------------------------------
Inputs:
2-bit number which is the method of operation A and B
      ❑ A+B: 00
      ❑ A-B: 01
      ❑ A*B: 10
      ❑ A/B: 11
    
-------------------------------------------------------------------------------------------------------------------------------------------------------------
Output:
Flags:
      ❑ Zero flag indicating that the result of the operation is = 0.
      ❑sign flag indicating the sign of the result one if the result is -ve else it is zero. 
      ❑ Division by Zero flag on if the second operand (B) is =0 → indicating ERROR.
      
------------------------------------------------------------------------------------------------------------------------------------------------------------
The result is a 3-digit decimal number displayed on seven-segment display.
