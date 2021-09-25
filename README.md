## Bangla News Headlines Categorization Using Gated Recurrent Unit (GRU): Project Overview
Created a tool that can categorizes the Bengali news headlines into six category (National, Politics, International, Sports, Amusement, IT) using deep recurrent neural network.<br />
A dataset of 0.13 Million news headlines is used which has been forked from [Eftekhar-Hossain's Git Repository](https://github.com/eftekhar-hossain/Bangla-News-Headlines-Categorization). <br />
News headlines are from different Bengali online news portals such as Dainik Jugantor, Dainik Ittefaq, Dainik Kaler Kontho and so on. <br /><br/>
Word embeeding feature represtations technique **(Bengali Glove 300d)** is used for extracting the semantic meaning of the words. <br /><br />
A deep learning model has been built by using a 1 layer Unidirectional Recurrent Neural Network LSTM. <br /><br />
Finally, the model performance is evaluated using various evaluation measures such as confusion matrix, accuracy , precision, recall and f1-score.<br />
## Resources Used
**Developement Environment** : Jupyter Notebook <br />
**Python Version** : 3.8 <br />
**Framework and Packages** : PyTorch, Scikit-Learn, Pandas, Numpy, Matplotlib, Seaborn <br />
