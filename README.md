# NLP-Sentiment-analysis
The goal of our analysis is to use sentiment analysis to build a model that will predict future consumer sentiment as either positive or negative.

## Research Question
By examining past reviews, can we predict future consumer sentiment as either positive or negative?

## Model Evaluation
The model performed fairly well, but we can see some overfitting. Especially with the model loss. This can be seen on the line graphs as the training dataset performed great, but the validation dataset did not. We did use an early stopping method to ensure there was less overfitting. We could have added more layers to our model and tested again to see if that addressed the overfitting. We could have also added more nodes to the layers to test if that helped.

##Summary and Recommendations
The analysis considered 1000 reviews of our customers to input and train. The neural language processor was used to analyze these customer reviews as sentiments and label those sentiments. I was able to validate and test the model and had an output of 83% accuracy, which is fairly good and means the model can be used to answer our research question and perform predictions on our customer reviews to determine if the sentiment is positive or negative. The impact of the network architecture used was that it helped me detect the review sentiment with an acceptable degree of accuracy. 
The question asked at the beginning of this analysis was: by examining past reviews, can we predict future consumer sentiment as either positive or negative? The answer to this question is yes, we can predict future consumer sentiment with the model we created. My recommendation is to take this model and use it to do just that. This model with then enable the organization to use that sentiment analysis to better their customer service and in turn, increase customer satisfaction.
