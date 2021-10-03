
# _Toy Model Implementation of the Piston Ball Multi-Agent Problem_

### Project Description 
The multi-agent piston ball game requires several pistons (or agents) to work together to move a ball from one side to the other. The original method uses images and a CNN policy to optimise the pistons to find a solution. Images are large and even after resizing, they contain a lot of redundant information. The scope of this project is to construct a toy model that simplifies this problem, being able to be solved quicker and with less computational demand. Please read the report for a more detailed analysis.
### Contents

> [Report](https://github.com/OJL96/Piston-Ball-Toy-Model/files/7219483/20316736_PHYS4037.pdf) (Warning! Its long. Please refer to Chapter 4 and beyond for details about new proposed methodology)  

> Toy Model 1.0 
* Binary states

> Toy Model 2.0
* Multi-value states
* Agent states can only deviate by 1

> Toy Model 2.1
* Ball can now take position in between pistons

> Toy Model 2.2
* Backward motion added
* Random ball rolling added when neighbouring pistons are less than the piston that holds the ball
