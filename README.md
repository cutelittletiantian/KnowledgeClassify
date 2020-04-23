# KnowledgeClassify
This project is a classification of knowledge about deep learning
*****************************************************************
## Environment
### operator system
operator system == Windows10
### python
python == 3.6.5
### tensorflow
tensorflow == 1.14.0
### keras
keras == 2.2.5
### numpy
numpy == 1.16.2
### pandas
pandas == 0.25.0
### scikit-learn
scikit-learn == 0.21.3
### jieba
jieba == 0.39
### matplotlib
matplotlib == 3.1.1
*****************************************************************
## File Struction
### init_model
init_model: Implementing the attention model
### model
model: About training models and model files with png
### input
input: The file includes datasets, dictionaries and stop words
*****************************************************************
## Start File
### choose model
Select the main models you need, including traditional models and deep learning models. Then select the actual model. This example selects the Text-CNN model (one of the deep learning models). The function call sequence is: main-> data_detail_deep ()-> text_cnn ()
### run file
run model_build.py
*****************************************************************
Because convert the English of computer knowledge is too big to upload GitHub, so we provide the origin web to download this data by yourself. Then you can use the convert.py to extract the knowledge text and it will store in the ./input/DataConvert.csv file. if your need the other data, you should look up the txt file and write rules to get you to want data.
SciKG:https://static.aminer.org/g/SciKG/SciKG_min_jsonld_1.0.tar.gz
origin data url:https://www.aminer.org/scikg
