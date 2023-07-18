This is a pipeline model which works in 4 stages:
Stage 1: Read two 16 bit numbers from the registers specified.
Stage 2: Perform ALU operation on A and B specified by "func" and store it in Z.
Stage 3: Write the value of Z in the register specified by "rd".
Stage 4: Write the value of Z in memory location.
