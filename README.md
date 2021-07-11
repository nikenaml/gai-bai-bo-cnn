# gai-bai-bo-games
As my dicoding submission in a machine learning class for beginners, I'm trying to create a game to read finger and hand-drawn input using the CNN model architecture. This game is usually called the "suit jari" game aka Gai Bai Bo!!! (The type of the game is similar to that in South Korea) to read finger input such as photographs of rock, paper, or scissors. The reference dataset used comes from **https://www.kaggle.com/drgfreeman/rockpaperscissors**. The dataset contains hundreds of finger and hand-drawn shapes of various sizes, skin tones, positions, and hand directions.

This game is intended to predict finger-drawn input which can later be used in a reinforcement learning system in a "suit jari" game against a computer system. This model works by processing finger image input with different finger and hand shape coverage but has a uniform image color background, then proceeds with input testing based on evaluation metrics to measure the accuracy of the model that has been made.

This model is built using the Python programming language with the CNN Algorithm Neural Network architecture.

- version 1.0 = using optimizer = Adam, loss_function = categorical_crossentropy
- version 2.0 = using optimizer = RMSprop, loss_function = categorical_crossentropy
- version 2.0 = using optimizer = RMSprop, loss_function = categorical_crossentropy, adding dropout process for handle overfit problem, change learning rate, add callback statement
