# gai-bai-bo-games
As my dicoding submission in a machine learning class for beginners, I'm trying to create a game to read hand-drawn input using the CNN model architecture. This game is usually called the "suit" game aka Gai Bai Bo!!! to read hand input such as photographs of rock, paper, or scissors. The reference dataset used comes from https://www.kaggle.com/drgfreeman/rockpaperscissors . The dataset contains thousands of hand-drawn shapes of various sizes, skin tones, positions, and hand directions.

This game is intended to predict hand-drawn input which can later be used in a reinforcement learning system in a "suit" game against a computer system. This model works by processing hand image input with different hand shape coverage but has a uniform image color background, then proceeds with input testing based on evaluation metrics to measure the accuracy of the model that has been made.

This model is built using the Python programming language with the CNN Algorithm Neural Network architecture.

- version 1.0 = using optimizer = Adam, loss_function = categorical_crossentropy
- version 2.0 = using optimizer = RMSprop, loss_function = categorical_crossentropy
