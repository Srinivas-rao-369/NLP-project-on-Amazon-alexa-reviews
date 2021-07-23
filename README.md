# NLP-project-on-Amazon-alexa-reviews

Need to apply NLP techniques in order to clean the data and train model in order to perform rating prediction  .
Amazon_alexa.tsv

https://www.kaggle.com/sid321axn/amazon-alexa-reviews?select=amazon_alexa.tsv

1)	How cleaning/EDA was performed:

      a)	removing stop words
      b)	removing punctuations
      c)	tokenization
      d)	lemmatization
      e)	bow (Bag-of-words model)
      f)	Tf-idf (Term Frequency(TF) — Inverse Dense Frequency(IDF) )

2)	Your independent and dependent feature
      a)	 independent feature: review (review text + summary)

      b)	Dependent feature :  overall (rating)

3)	Why and how selection/engineering/scaling was performed

      a)	 Text cleaning
      b)	Feature selection : review text , summary , overall rating these features are used foe modeling fitting and prediction.

4)	Which activation function was chosen and why:
      a)	It is used to determine the output of neural network like yes or no. It maps the resulting values in between 0 to 1 or -1 to 1 etc. (depending upon the function).
       b)	Here we are using Logistic function (sigmoid function).
       c)	The main reason why we use sigmoid function is because it exists between (0 to 1).
5)	Which optimizer was chosen and why?
      a)	 optimizers shape and mold your model into its most accurate possible form by futzing with the weights.
      b)	Optimizers are related to model accuracy.

6)	Which neural network and why? Describe how your neural structuring? 
      a)	  sigmoid neuron
      b)	In the sigmoid neuron, a small change in the input only causes a small change in the output as opposed to the stepped output.
      c)	 The used function is the logistic function.
 
            Model	          Accuracy Score
        Naïve bayes	      0.7428571428571429
