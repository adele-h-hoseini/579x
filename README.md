# **Introduction:**
This project is a WikiNER — A brutal force NER approach. 
Simply crawl all NEs from Wikidata and use string match or a vector approach to find NEs crawled in a query text.
The code reads a .csv file, performs various operations on the data, and then exports the results to a .csv file.

# **Dependencies:**
Before running the code, make sure you have the following libraries installed:

torch
numpy==1.16.0
mxnet-cu92
mxnet
TensorFlow
bert-embedding
transformers
tqdm
pandas
itertools
operator
sklearn.metrics
nltk
argparse
spacy
zmq
contextlib
pathlib
re
subprocess
ast

To install these libraries, run one of the following commands in the terminal:

```
!pip install -r requirements.txt
```

Or:

```
!pip install torch
!pip install numpy==1.16.0
!pip install mxnet-cu92
!pip install mxnet
!pip install TensorFlow
!pip install bert-embedding
!pip install transformers
!pip install tqdm
!pip install pandas
!pip install itertools
!pip install operator
!pip install sklearn.metrics
!pip install nltk
!pip install argparse
!pip install spacy
!pip install zmq
!pip install contextlib
!pip install pathlib
!pip install re
!pip install subprocess
!pip install ast
```

# **Input:**
The code reads a .csv file called qrank.csv located in the main directory. The file should contain two columns: Qnumber and Qrank.


# **Output:**
The code exports the results to a .csv file called output.csv located in the main directory. The file contains three columns: Qnumber, Qrank, and Lable.


# **Additional Information:**
For more information about the code, refer to the comments in the code. If you have any questions or suggestions, feel free to contact me.
