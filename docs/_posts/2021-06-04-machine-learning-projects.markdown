---
layout: post
title:  "Machine Learning projects"
date:   2021-06-04 23:48:16 +0800
categories: course projects
---

In the last semester (Spring 2021), I have taken a Machine Learning course that teaches all the basic concepts in the machine learning sector, including regression, deep neural networks and reinforced learning. The course instructor required us to work on a few assignments on deep neural networks, and two self-conducted projects on self-selected topics. I can't be more proud of my own finished work in this course, so I decided to add it here. You can see my code and my final product by clicking the links and download the jupyter notebook files.

If you're currently taking the course, please refrain from copying the codes, as you will never know if they will fit in your instructor's standards in your semester (Also you'll never know what grades I got) ;).

Disclaimer: All codes available here only serves the purpose of result-sharing, and should not be used to other academic work such as assignments or projects without my permission. Train data and test data will not released for copyright reasons. Please pardon the fact that the results in the notebook files cannot be recreated without any data. 

First assignment: <a href="./documents/pa1.ipynb" download>Regression</a>

In this assignment, I was instructed to consturct several Linear Regression models on different combinations of wine features given some data on wine quality. I also needed to code a Logistic Regression model to classfy good/bad wine, so I familiarized myself with coding these models using Python and scikit-learn. I was also instructed to perform some hyperparameters tuning by brute-force experiments (trying different parameters and see which ones yield the best results), and using the Grid Search algorithm.

Second assignment: <a href="./documents/pa2.ipynb" download>CNN</a>

This assignment utilizes a face image database, and guides us to constuct a Siamese Convolutional Network to determine if the same face appears in two images using PyTorch. The model returns a similarity score, and I was instructed to find the optimal similarity threshold that yields the best validation accuracy when classifying if the two images contain the same face. Similar to the first assignment, I tried to improve the model with hyperparameter tuning, and this time also with data augmentation to increase the training data size.

Third assignment: <a href="./documents/pa3.ipynb" download>RNN, Natural Language Processing</a>

We were required to build an RNN model on fake news dectection in this assignment. This time, since it is a text-related task, we were instructed to try pre-trained weights like GloVe to optimize the model. I also tried some hyperparameter tuning again, and also model

First project: <a href="./documents/p1.ipynb" download>Experiements with RNN on Tweet Sentiment Classification</a>

This is a collorated project with another student in the course. We chose a Tweet Sentiment dataset, and tried building a model to predict a tweet's sentiment using its metadata (like tweet text, hashtags, usernames). Similar to the assignments, we tried model improving with various methods. But since this is a project, there are much more experiments conducted here. Contrary to using PyTorch in the assignments, my partner suggested trying out TensorFlow since there is more support available for TensorFlow, and the instructor did not restrict us on modules.

Second project: <a href="./documents/p2_slides.pptx" download>30-min presentation on Gradient Boosting Tree</a>

Since this is an introductory machine learning course, the course cannot cover all topics in every area. We were told to pick a topic, self learn the principles behind, and conduct a presentation explaining the concepts in an academically formal way. I picked Gradient Boosting Tree since the concept Decision Tree taught in lectures is rather simple, and I wish to learn more about how to improve the decision trees. The presentation can be divided into 4 parts, an brief summary of decision tree, a simple intorduction to gradient boosting, tedious explanation of maths, and a brief section on AdaBoost. (The download link is a pptx file. If you want to see my presentation, you can find a YouTube link of that in the first slide.)

To be honest, the assignments are more tedious and harder than it looks. All the machine learning codes seem simple on paper when the TA provided us with examples, but they get confusing when we are required to customize as bugs like syntax errors or dimension mismatch appear. Also, I completely underestimated the time needed to train the models in the 2nd and the 3rd assignment, which added unnecessary stress in the process. Nevertheless this was a fun experience as I get to constuct actual models on my own that can run predictions at a high accuracy. In the future I will be working on a speech biometrics project in my final year, and this course provided me with valuable experience for it. (Maybe I will upload my FYP in this website later when I finish it!)

[pa1]: https://potatohy.github.io/docs/_posts/documents/pa1.ipynb
[pa2]: https://potatohy.github.io/docs/_posts/documents/pa2.ipynb
[pa3]: https://potatohy.github.io/docs/_posts/documents/pa3.ipynb
[p1]: https://potatohy.github.io/docs/_posts/documents/p1.ipynb
[p2]: https://potatohy.github.io/docs/_posts/documents/p2_slides.pptx
