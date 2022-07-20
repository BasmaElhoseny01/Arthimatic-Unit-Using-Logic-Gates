# Arthimatic-Unit-Using-Logic-Gates
An arithmetic unit that is capable of adding, subtracting, multiplying, and dividing two 5-bit signed numbers and the result is dispalyed on 7 segement


Note: These files are .circ and I have provided the softaware for running them "logisim-win-2.7.1.exe"   (logisim).
The main file to run is "Main Project of Logic.circ" it has the main cicuit and the ALU.

-------------------------------------------------------------------------------------------------------------------------------------------------------------
The numbers' magnitude are 4-bit and the 5th bit is for sign where 1(-ve) and 0(+ve)

-------------------------------------------------------------------------------------------------------------------------------------------------------------
Inputs:
2-bit number which is the method of operation A and B
      ❑ A+B : 00
      ❑ A-B : 01
      ❑ A*B : 10
      ❑ A/B : 11
    
-------------------------------------------------------------------------------------------------------------------------------------------------------------
Output:
Flags:
      ❑ Zero flag indicating that the result of the operation is = 0.
      ❑sign falg indcating the sign of the result one if result is -ve else it is zero. 
      ❑ Divison by Zero flag on if the seconf operand (B) is =0 → indicating ERROR.
      
------------------------------------------------------------------------------------------------------------------------------------------------------------
The result is 3-digit decimal  number disalyed o  seven-segment display.

      
