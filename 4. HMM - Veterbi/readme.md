![alt-text](https://github.com/shrebox/Natural-Language-Processing/blob/master/4.%20HMM%20-%20Veterbi/Problem_Statement.jpg)

## Walkthrough:

```
Code: code.py, train_test_files/create_test.py
Data files: train_test_files/train.txt, train_test_files/test.txt, train_test_files/test_output.txt
Models: models/start_dic.pkl, models/transition_dic.pkl, models/emission_dic.pkl
Report: NLP Assignment 4, HMM_Report.pdf
```

To run python files, ```$ python 'filename'```

'code.py' is used to create the models using train dataset and predict the tags for the test dataset.\n
'create_test.py' is used to create the 'train_test_files/test.txt' data file for testing the training accuracy.

### Data files:

'train.txt' is train data on which models are trained.\n
'test.txt' is used for testing the train accuracy.\n
'test_output.txt' is the result for the predicted output tags on the 'test.txt' file.

### Models:

'start_dic.pkl' --> start probability dictionary\n
'transition_dic.pkl' --> transition probability dictionary\n
'emission_dic.pkl' --> emission probability dictionary

### Report:

Contains the detailed analysis and results for the problem.