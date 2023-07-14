# Essay-Evaluator
Automatic Essay Grader/ Evaluator

## Essay Grader / Evaluator , Method - 1 
This uses language-tool-python to check a given essay text (in form of string) for mistakes and errors. Different types of errors are identified, such as; grammar error, syntax error, redundancy error, word limit constraints, etc. All these different errors are assigned deduction marks based on the significance of these mistakes. The total deduction is calculated, which is them subtracted from the maximum score. If the resultant is great than the minimun possible score, the relevant grade is assigned, else the minimum score is assigned.

## Essay Grader / Evaluato , Method - 2
This uses LSTM neural networks. The trianing dataset used contains several sample essays and their scores on differnt criterias, such as; grammar, vocabulary, syntax, etc. This data is preprocessed, after which the model is trained on the dataset. The test essay is then given as input to the trained model which outputs it's score on the given different criterias. 

## English Language Speaking Test
This notebook consists of following:
1. Essay Evaluator: Takes a string text as input and finds different types of grammatical, spelling and other mistakes in it and assigns marks accordingly. 
2. Text to Speech and Speech to Text: This is used for convert the ques to be asked into a voice and convert the student's voice response into text so that it can be processed by Essay Evaluator.
3. Live Voice Recording: This code in the Colab Notebook records live audio from the user and saves it in .wav format.
