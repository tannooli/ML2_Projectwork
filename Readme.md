# Project work for Machine Learning II

## Student
**Name:** Oliver Tanno <br />
**E-mail:** tannooli@students.zhaw.ch <br />
**Class:** WIN.21HS.TZDSa <br />

## Module
**Module name:** Machine Learning II <br />
**Semester:** 2023-FS <br />
**Lecturer:** Elena Gavagnin <br />

## Project work

### Problem
Nowadays it is easier and easier to create content such as texts or images and distribute them via the internet. For example, statements are spread quickly via social media and reach a large number of people. However, time and again there are newspaper reports that contain false or incomplete statements. This can happen because newspapers are forced to publish news faster and faster so that they are the first to do so. Likewise, reports from other newspapers are taken over and reused more and more often. If a false report is published, it is spread by other newspapers and social media in no time at all. For readers, it is thus becoming increasingly difficult to find out whether a report is true or not.

### Solution idea
Using NLP methods, I want to find out whether I can train a model to find out whether a message is correct or incorrect based on an existing data set.

### Not part of the solution
The determination of whether a message is correct or false is made on the basis of an existing data set. Thus, news must always be classified as "true" or "false" and the model must be trained before the model itself can make statements about them. Thus, the model is not suitable for the latest news or news that are not clearly identifiable thematically, and this is not part of this solution.

### Data set
I have used two dataset from Kaggle. The first dataset "True.csv" contains News, which has been labeled as real news. The second dataset "False.csv" contains news, which has been labeled as fake. Both datasets contain the same columns and same data structure.

### Inputs and support
To generate this model I have used the whitepapers from the lessons in the first weeks of the module, like https://pub.towardsai.net/simple-text-classifier-with-basic-machine-learning-model-fa414791d26e or https://medium.com/analytics-vidhya/nlp-tutorial-for-text-classification-in-python-8f19cd17b49e. I have also used the documentation of the libraries I have used, like https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html or https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html. Besides that I have also checked some other Kaggle projects, like https://www.kaggle.com/parulpandey/getting-started-with-nlp-a-general-intro or https://www.kaggle.com/parulpandey/getting-started-with-nlp-feature-vectors. To implement and change some code from other projects and models and  to solve errors I have also used ChatGPT with different prompts. 

### First model creation
To prepare the notebook and check the code I created the model with 10 Epochs and saved it in "ML2_Projectwork\30_train_model\31_trained_model\first_trained_model".

Accuracy and Loss with 10 Epochs:
<iframe src="https://drive.google.com/file/d/18ht04k9ISJaGU5MMspdQSHhvDHyWEwcc/preview" allow="autoplay"></iframe>

Analysis of it:
<iframe src="https://drive.google.com/file/d/1N-ZPCOQI42IGLOuUCEJvZvjs4rKDRMp5/preview" allow="autoplay"></iframe>

For the project I would recommend to use only three epochs to save time and ressources.





