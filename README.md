# 4BIT_SYNCHRONOUS_UP_COUNTER
![image](https://github.com/RESMIRNAIR/4BIT_SYNCHRONOUS_UP_COUNTER/assets/154305926/4d676d34-2f12-420a-9c55-befa279f5ec0)
# Truth Table
# <img width="362" alt="image" src="https://github.com/RESMIRNAIR/4BIT_SYNCHRONOUS_UP_COUNTER/assets/154305926/2be84c5a-099f-4418-8d0b-ace34f734342">
# Timing diagram of the synchronous counter
![image](https://github.com/RESMIRNAIR/4BIT_SYNCHRONOUS_UP_COUNTER/assets/154305926/62c47758-b0a4-4fe0-842f-5c4245a88ff2)
 program
 ```
module synchronous_up_counter(

input wire clk, // Clock input

input wire reset, // Reset input

output reg [3:0] count // 4-bit output );

// Reset the counter to 0 when reset is active

always @(posedge clk or posedge reset)

begin

if (reset)

count <= 4'b0000;
else

count <= count + 1; // Increment the count on each clock cycle
end

endmodule
```
output
![image](https://github.com/lavakumaryadhava/4BIT_SYNCHRONOUS_UP_COUNTER/assets/162088994/3db0b772-1b4e-497e-84c1-9fb0caeeb4d3)
Result:
Thus the verilog program for 4bit synchronous upcounter has been simulated and verified successfully.Thus the verilog program for 4bit synchronous upcounter has been simulated and verified successfully.

