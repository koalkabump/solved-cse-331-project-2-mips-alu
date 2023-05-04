Download Link: https://assignmentchef.com/product/solved-cse-331-project-2-mips-alu
<br>
CSE 331 Computer OrganizationProject 2 – MIPS ALUIn this project you will design the exact same ALU as in the lecture notes. Your design will include:1. 4×1 MUX module2. 1-bit ALU3. 32-bit ALU module1-bit ALU module will be designed same as shown below:

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/114.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/114.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

32-bit ALU module will be constructed using 1-bit ALU modules as shown below:

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/282.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/282.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>You have to write your own testbench on Verilog and show that the project is working right.The ALU must support AND, OR, ADD, SUBTRACT and SET ON LESS THAN operations.Write a report that explains your Verilog modules and the testbench results. You should test all operations that ALU allows. Also report how many logic gates you used for the ALU.RULES!!!1. You cannot use any other logic gates than AND, OR and NOT. (For instance XOR is not allowed.)2. You can only use structural Verilog. No dataflow, no assign statement no behavioral Verilog.3. Any other ALU design than explained above will not be accepted and means 0pts.4. Any not simulating Verilog project gets at most 20pts.5. Any cheating means -100pts whether giving or taking the design.6. You have to use hierarchy and different modules as described here.7. The project will be explained in PS. So attend the PS.8. If you can show your design working on actual FPGA board than you get 30 extra pts.




<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/996.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/04/996.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>