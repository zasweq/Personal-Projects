# Personal-Projects
These are two Personal Projects that I coded this summer to help teach myself code.

The message classifier simply loops through multiple
classification methods from the Scikit Learn package of Python. The data of messages was pulled from Kaggle.com, which I split into train
and test cases in an 80/20 split. Then, I "vectorized" the messages, which converts the text message to a multidimensional vector. Once the
text is represented in this vector format, you can then apply the Scikit models to help classify. I looped through both the "vectorizers" and
the "classifiers", and chose the one with the best accurarcy. I could not tell you in detail what each of the models does, but I knew how to
implement them into Python, with a little help from Google for some of the parameters. After I chose the one with the best accuracy, I used that
to write a script that allows users to type their own message and see if the message is spam or not spam.

