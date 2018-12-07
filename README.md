# Toxic-Comments-Classifier


Keeping online conversations constructive and inclusive is a crucial task for platform providers. Automatic classification of toxic comments, such as hate speech, threats, and insults, can help in keeping discussions fruitful. In addition, new regulations in certain European countries have been established enforcing to delete illegal content in less than 72 hours..
This is a multi-label classification problem. The different classes are: 
toxic
severe_toxic
obscene
threat
insult
Identity_hate
clean

Difference between multi-class classification & multi-label classification is that in multi-class problems the classes are mutually exclusive, whereas for multi-label problems each label represents a different classification task, but the tasks are somehow related.
In multi-label classification, data can belong to more than one label simultaneously. For example, in our case, a comment may be toxic and insulting at the same time. It may also happen that the comment is non-toxic and hence will be classified as clean.
