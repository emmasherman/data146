## Extra Credit Write-Up ##

On Tuesday, Claire Heinbaugh gave an interesting talk about transfer learning, stacked generalization, and Keras. She started the talk by discussing neural networks. Claire explained that neural networks are a type of machine learning model that is used to classify data. Then she got into her first example of trying to predict a true genre. She used different sonic variable inputs and tested the top four genres. Then, Claire explained that she would take one artist’s genre and expand it into a vector to test it. For this example, she used train and test split. She was able to see how accurate the model is based on artists that the model was not trained on and get the model accuracy.

Her next topic of the presentation was Keras. Keras is a python library that wraps a lot of linear algebra that she used. This library makes work faster when trying to do linear algebra. Then her talk led to the example of a picture of a tomato. She explained that the picture can be represented as matrices and you can use a convolutional neural network to identify relevant features of the image to assign and then assign importance weight. For this example, you can identify the tomato-based on rounded edges. 

Claire then discussed transfer learning. This process allows users to take the weight that has already been trained to recognize images on the image net and apply it to our model. Claire explained that Keras made these models available from an image net competition for the convenience of the user. For this topic, her example came from her road quality model. She used three different transfer learning models to run the data using the classifiers, good roads, and bad roads. 
Finally, Claire discussed the topic of stacked generalization. She explained that stacked generalization is when you have several models, and you get predictions from each of them. Once you have the predictions, you use them as inputs for another model to try and get the best overall prediction. Claire used good roads, medium roads, and bad roads for her project when she used stacked generalization. This procedure helps improve accuracy. 

These three topics are very useful for Claire’s projects, but they would also be useful for any recognition project. The use of transfer learning, Keras, and stacked generalization makes model predicting a lot easier and faster. Being able to use already created models with weights already in the model. This process allows the user to train their model much faster, as Claire did with the good road and bad road project. Keras also is super useful because it makes linear algebra faster and does it for you. It is also the library where all the models are stored, and just by importing Keras, the user can pick which library will work best for their project and create a model in a faster time. Finally, using stacked generalization allows the user to get the best outcome possible for the given models, making the prediction more accurate. Using all three topics altogether seems like the user would get faster, better fit, and more accurate predictions when to use classifiers such as road quality. These processes could be used for different projects and make it a lot easier for anyone to get started. Overall, Claire’s talk was very insightful about these three data science practices that can be used for machine learning. 