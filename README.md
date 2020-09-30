# square-root-design
This repo consists of a synthesizable square root design based on the Newton Raphson method. 
- This method tries to guess the square root of the given number *n* in 8 iterations starting from the MSB. This method sets the MSB to 1 and squares this number. 
- If the squared number is *greater* than the given number *n* then, it implies that the guess made in the first iteration is large. Hence, we restore the bit to 0 and make the next significant bit 1. 
- If the squared number is *lesser* than the the given number *n* then, it implies that the guess made in the first iteration is small. Hence, we hold the bit to 1 and make the next significant bit also 1 and repeat the process.
