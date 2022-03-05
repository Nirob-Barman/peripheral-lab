#### Experiment number - 01
###### Experiment Name - Write and execute a machine language in MTS86 trainer board solve the mathematical expression X=A+B where A=01 and B=F0

###### Objectives:- The 8086 kit MTS-86C is used to perform machine language programns on it to solve any operations. This kit has I/O facility and build in with different interfacing devices such as 8255,8251,8259,8253,3254 etc.

###### Specifications:- 
                         CPU : 8086
                         Display Unit : LCD(16*2 Line)
                         Main RAM : 64 KB
                         Monitors ROM : 64 KB
                         User Memory : 64 KB

###### I/O: ADC 8089, DAC 0808, 8255, Interrupt controller 8259, Trainer/Counter Controller-8253, Keyboard/Display controller-8279, serial port-8251,24,keyboard

###### Procedure:-
| Assembly Language | Machine Language |
| :-:        |     :-:      |
|MOV AL,  01 <br> ADD AL,  F0|B0  01 <br> 04 F0|

###### Input:-
                A=01
                B=F0
###### Output:-
                A=01---->0000 0001
                ######B=F0---->1111 0000
                

#### Experiment number - 02
###### Experiment Name - Write and execute a machine language in MTS86 trainer board solve the mathematical expression X=A-B where A=07 and B=02
| Assembly Language | Machine Language |
| :-:        |     :-:      |
|MOV AL,  01 <br> SUB AL,  F0|B0  01 <br> 2C F0|


#### Experiment number - 03
###### Experiment Name - Write and execute a machine language in MTS86 trainer board solve the logical operator AND,  OR, NOT, X-OR,  Shift left AND Shift right operation
| Assembly Language | Machine Language |
| :-        |     :-:      |
|MOV AL,  02 <br> AND AL,  A3 <bR> OR AL, A3 <BR> NOT AL <BR> XOR AL, A3  <BR> SHL AL, 01 <BR> SHR AL, 01|B0  02 <br> 24 A3 <BR> 0C A3 <BR> F6 D0 <BR> 34 A3 <BR> D0 E0 <BR> D0 E8|
