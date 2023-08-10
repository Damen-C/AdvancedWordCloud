# Making an advanced Word Cloud

For normal word clouds, colors are randomly assigned. Advanced word clouds that map meaningful attributes (like coefficient values or token frequencies) to visual characteristics can provide a lot more insight. 


## Visualization 
Figure: Word Cloud for Amazon reviews 
![](https://raw.githubusercontent.com/Damen-C/AdvancedWordCloud/main/word_cloud.png)

## Access to the file 
To get the customer review file, go check the link below:   
https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products?resource=download

## Explanation
1. Size of the Words: The size of the words in the word cloud is directly proportional to the coefficient estimates from the linear regression model. Larger words have higher coefficient magnitudes, meaning they play a more significant role in the model's prediction. In linear regression, the coefficient represents the change in the dependent variable for a one-unit change in the predictor variable, holding all other predictors constant. So, larger words indicate predictors with larger impacts on the outcome variable.

2. Darkness of Color: The intensity or darkness of the color of the words is based on their frequency. Darker words appear more frequently, while lighter words are less frequent.

## In summary
Words that are **large and dark** have both a **significant impact** on the model's prediction and are **frequently mentioned** in the dataset.  
Words that are **small and light** have a **minor impact** on the prediction and are **mentioned less** often.  
Words that are **large but light** have a **significant impact** on the model's prediction but are **mentioned less** frequently.  
Words that are **small but dark** are frequently mentioned but have a **minor impact** on the prediction.

