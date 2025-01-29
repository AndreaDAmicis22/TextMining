In case you want to execute the whole project from the beginning, the order of notebooks to be executed is:

1) Yelp dataset is available in the following page: https://business.yelp.com/data/resources/open-dataset/

2) Dataset_pre_processing.ipynb, this allow to pre-process the Yelp dataset to produce the 
  project dataset and the fine tuning dataset.

3) BERT_fine_tunig.ipynb, to perform the fine tuning of the sentence tranformer.

4) Clustering.ipynb or Topic_Modelling.ipynb, this according to the task that you want to perform.

Consideration to execute the single files:

* Dataset_pre_processing.ipynb
	- this require the installation of the library pandas with pip
	- to process the dataset in the same way take the samples specified in the report 
	  chapter 2.

* BERT_fine_tuning.ipynb
	- all the installation command are included into the notebook
	- check if the HF_TOKEN is correctly setted

* Clustering.ipynb:
	- all the installations are in the notebook
	- check the path to google drive based on the location of the dataset and the fine tuned model

* Topic_Modeling.ipynb:
	- all the installations are in the notebook
	- check the path to google drive based on the location of the dataset 
