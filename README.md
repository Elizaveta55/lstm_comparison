# LSTM comparison

[![Build Status](https://github.com/Gci04/AML-DS-2021/actions/workflows/setup.yml/badge.svg)](https://github.com/Gci04/AML-DS-2021/actions/workflows/setup.yml)
[![NN Model Test](https://github.com/Gci04/AML-DS-2021/actions/workflows/neuralNet.yml/badge.svg)](https://github.com/Gci04/AML-DS-2021/actions/workflows/neuralNet.yml)

This is a project for Advanced Machine Learning Course at innopolis university. It contains Seminars coding examples, homework exercises and Course project code.

## Repository Structure

```
├── .gitignore               	<- Files that should be ignored by git.
├── requirements.txt         	<- The requirements file for reproducing the analysis environment, e.g.
│                               	generated with `pip freeze > requirements.txt`. Might not be needed if using conda.
│
├── data                     	<- Data files directory
│   └── Data1                	<- Dataset 1 directory
│
├── notebooks                	<- Notebooks for analysis and testing
│   ├── eda                  	<- EDA Notebooks directory for
│   │   └──models            	<- Folder with original code and all files 
│   │      ├──lstm           	<- lstm model with one params configuration
│   │      │   ├─model.pt    	<- model weights
│   │      │   ├─events.out..	<- file from tensorboard
│   │      │   ├─Untitled7.ipynb<- notebook raw code
│   │      │   ├─Untitled7.py   <- script raw code
│   │      ├──lstm2          	<- lstm model with another params configuration
│   │      │   ├─model.pt    	<- model weights 
│   │      │   ├─events.out..	<- file from tensorboard
│   │      │   ├─Untitled7.ipynb<- notebook raw code
│   │      │   ├─Untitled7.py   <- script raw code
│   │      ├──simple          	<- simple model with linear layers
│   │      │   ├─model.pt    	<- model weights 
│   │      │   ├─events.out..	<- file from tensorboard 
│   │      │   ├─Untitled7.ipynb<- notebook raw code
│   │      │   ├─Untitled7.py   <- script raw code
│   │      ├──simple lstm       <- basic lstm model
│   │      │   ├─model.pt    	<- model weights 
│   │      │   ├─events.out..	<- file from tensorboard
│   │      │   ├─SimpleLSTM_ACTUAL.ipynb       <- notebook raw code
│   │      │   ├─SimpleLSTM_ACTUAL.py          <- script raw code└
│   │      └──comparison        <- folder with graphics for comparison
│   └── preprocessing        	<- Notebooks for Preprocessing

├── scripts                  	<- Standalone scripts
│   └── dataExtract.py       	<- Data Extraction script
│
├── src                      	<- Code for use in this project.
│   ├── train.py             	<- train script
│   └── test.py              	<- test script
│
└── tests                    	<- Test cases (named after module)
```

