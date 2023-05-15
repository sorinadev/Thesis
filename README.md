# Thesis


CSV files:

* data.csv -> the original data obtained from OSF
* joint_comp_l2.csv -> the comprehension test results for each participant
* merged_comp_data.csv -> the analysed dataset in this research. it has only the data of the partipcipants that scored above 60% accuracy on the comprehension test. it additionaly contains the PoS tags of each word.
* merged_data.csv -> the original data merged with the PoS tag corresponding to each word
* texts.csv -> the 12 texts read by the participants

Code files:

* build_model.ipynb -> the machine learning model code to classify the merged_comp_data.csv dataset
* graphs.ipynb -> the code for creating the graphs and data analysing 
* preprocessing.ipynb -> the code for preprocessing, cleaning the data, and adding the corresponding PoS tags to the words 