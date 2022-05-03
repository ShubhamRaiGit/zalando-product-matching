# zalando-product-matching
Matching two identical products between different providers can be achieved through barcode systems such as EAN, however reliable EAN information is not always available available due to practical shortcomings. The other way of identifying identical products is by making use of multi-modal data such as textual descriptions and product images that can uniquely identify the products. The major challenge lies in making intelligent use of textual data such as title, color and descriptions to find identical products, as these are not standardised between different providers and are often altered for marketing purposes. To address above we suggest machine learning pipeline to identify identical products between 2 different vendors i.e. Zalando and AboutYou. I also compared various existing machine learning solutions that best suits the task of identifying identical products and evaluate results based on their f1 scores

#Summary

## Product Matching is treated as classification problem where given a tuple of aboutyou and zalando, classifier predicts if it's a match or not a match</br>

## Machine Learning algorithms used: </br>

Bidirectional RNN: A hybrid model, which takes sequence context into account next performs alignment and finally
performs comparison
Support Vector Machines
Random Forest
Decision Tree
LogisticRegression
LinearRegression
Ensemble Method
