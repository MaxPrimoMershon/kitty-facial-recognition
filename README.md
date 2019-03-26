# Kitty Facial Recognition


The goal of this weekend project was to attempt to develop a facial recongition model for my cat, Mischa (see left). To achieve this, I had to learn about "deep learning", which I didn't have any prior knowledge of. Additionally, I had to collect data, so I took over 250 pictures of Mischa and collected 250 images of random cats on the internet. These images were used to train a model using the convolutional neural network algorithm, the best deep learning method for image analysis (so the internet says).

Two different approaches were tried: (1) created a model from scratch and (2) customized a pre-existing model. The results show model #1 was 44% - 56% accurate, while model #2 was 50 - 66% accurate. Since a random guess would be 50% accurate in this case, customizing a pre-existing model is the best solution and performs slightly better than guessing.

To improve the model in future iterations I would: (1) learn more about deep learning, (2) gather more pictures of Mischa and random cats, and (3) use a machine with GPU to increase computational power.