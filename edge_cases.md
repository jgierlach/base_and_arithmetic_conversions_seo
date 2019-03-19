#**Edge Cases For Form Validation**

* Value that is going to be converted to decimal that is not binary (all 1's or 0's) currently returns 0
* value that is going to be converted to IEEE that is not a floating point value
* Value that is a floating point being converted to binary should not work
* Floating point value with just nothing before or after the decimal point should not work