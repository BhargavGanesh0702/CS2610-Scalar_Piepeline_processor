# CS2610_Pipeline_Processor
## Directory structure
```
CS22B087-CS22B028_LAB8
├── input
│   ├── ICache.txt
│   ├── DCache.txt
│   └── RF.txt
├── output
│   ├── DCache.txt
│   ├── Output.txt
│   └── RF.txt
├── main.cpp
└── README.md
```
## Commands to run the code
We are also creating a RF.txt file in output folder which show contents of register after execution.

We used long options to run the code.
| Options | Arguments | 
| -------- | -------- |
| in | folder name that contains 'ICache.txt' , 'DCache.txt' , 'RF.txt' | 
| out | folder name that contains 'Output.txt' , 'DCache.txt' , 'RF.txt' |

### Example Usage
To compile use `g++ main.cpp`.

To Run use `./a.out --in input --out output`. 

Make sure to use correct folder names in run command.

Before running the code make sure to create folders 'input' and 'output'.

Here 'input' folder contains files 'ICache.txt' , 'DCache.txt' , 'RF.txt'.

And 'output' folder contains files 'Output.txt' , 'DCache.txt' , 'RF.txt' after execution of code.
