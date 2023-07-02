# Essay-Evaluator
Automatic Essay Grader/ Evaluator

## Essay Grader / Evaluator , Method - 1 
This uses language-tool-python to check a given essay text (in form of string) for mistakes and errors. Different types of errors are identified, such as; grammar error, syntax error, redundancy error, word limit constraints, etc. All these different errors are assigned deduction marks based on the significance of these mistakes. The total deduction is calculated, which is them subtracted from the maximum score. If the resultant is great than the minimun possible score, the relevant grade is assigned, else the minimum score is assigned.

## Essay Grader / Evaluato , Method - 2
This uses LSTM neural networks. The trianing dataset used contains several sample essays and their scores on differnt criterias, such as; grammar, vocabulary, syntax, etc. This data is preprocessed, after which the model is trained on the dataset. The test essay is then given as input to the trained model which outputs it's score on the given different criterias. 
