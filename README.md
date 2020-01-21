# IRIS 2020
## A novel, multi-model, data first, chrome extension and WhatsApp based approach to fake news

This is a repoistory storing the weights and scripts to reproduce the results presented at IRIS 2020. 
The results achieved and the methadologies used can be found at ```Final_Data_Book.pdf```
To reproduce the results, please follow the instructions below. 

1 - Download the SNLI and MultiNLI datasets from the two corresponding links:

https://nlp.stanford.edu/projects/snli/

http://www.nyu.edu/projects/bowman/multinli/

2 - Download and extract a set of features used as input to the model: https://mega.nz/#!08IyyKrT!rfsor4KQSPX0OCBAMhIzqhfOLkRZQBAN5BqqiIJXdrA

3 - Download the features generated from here: https://mega.nz/#!tlAG3abL!hoPZhr7X5M1ifuPaXSAaNExuAz8DdEHHdV3EC5PSojE

4 - Next download the weights for the two models: 
   Linguistics model - https://drive.google.com/open?id=1-symK6E-LRN_SW2Gnr0Z0xraA6FW0vC4
   
   Stance Detection model - https://drive.google.com/open?id=1-dYTRCO59vIjOMEaZYzhjbngxFvo-jsK

5 - Finally, run the code in ```Combined_models.ipynb```. 

Use the ```RealNet``` dataset to test and benchmark the results. 

