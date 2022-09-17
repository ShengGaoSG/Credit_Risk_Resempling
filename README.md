[Module 12 Report](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/report-template.md)
- [Overview of the Analysis](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/report-template.md#overview-of-the-analysis)
- [Results](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/report-template.md#results)
- [Summary](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/report-template.md#summary)


# Credit Risk

Challenge_12

> "In this Challenge, I will assume the role of risk management data analyst and use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.
"


## Table of content
- [Overview of the project and project goals](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/README.md#overview-of-the-project-and-project-goals) 
- [Software version control](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/README.md#software-version-control)
    - [Libraries](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/README.md#libraries)
    - [Work with GitHub](https://github.com/ShengGaoSG/Credit_Risk_Resempling/bolb/main/README.md#work-with-github)
    - [How to install](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/README.md#how-to-install)
- [License](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/README.md#license)




## Overview of the project and project goals

Using my new knowledge of the imbalanced-learn library, the goal is to create a Jupyter notebook that  contains logistic regression model to compare two versions of the dataset. First - the original dataset. Second- resample the data by using the RandomOverSampler module from the imbalanced-learn library.

For both cases:
- get the count of the target classes
- train a logistic regression classifier
- calculate the balanced accuracy score
- generate a confusion matrix
- generate a classification report.




## Software version control


### Libraries 
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* Following libraries were imported

```
# Import the required libraries and dependencies
import numpy as np
import pandas as pd
from pathlib import Path
from sklearn.metrics import balanced_accuracy_score
from sklearn.metrics import confusion_matrix
from imblearn.metrics import classification_report_imbalanced

import warnings
warnings.filterwarnings('ignore')
```


 
### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* Our repository is organized, and includes Resources folder with CSV  project files, 
* Jupyter Notebook with code runs without errors.
* Answers on nesassary questions are included

### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/ShengGaoSG/Credit_Risk_Resempling.git
```

now you can find repo on your desktop


* Access the report [report-template.md](https://github.com/ShengGaoSG/Credit_Risk_Resempling/blob/main/report-template.md)
* Choose [ credit_risk_resempling.ipynb ] file to see the Jupyter Notebook with code.



## License

MIT
