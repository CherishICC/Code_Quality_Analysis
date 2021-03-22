# Code Quality Analysis
The source code to be parsed resides in a c file <br />
The program cfg.py consists of the CFG data type. <br />
The CfgNode data type is the node in the CFG, you can agument this node with necessary data to compute relevant flow based metrics. <br />
The constructor of the CFG class takes AST returned form parse_file function. <br />
The file main.py consists of the main functon that executes the code. <br />

## To run
Write the program you want to find cyclomatic complexity in the c file and pass it as input to the main function. <br />
`python main.py`
