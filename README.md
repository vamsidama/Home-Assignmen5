# Home-Assignmen5

CS5720 Home Assignment 5 - Neural Networks and Deep Learning
Student Name: Dama Vamsi 
Course: CS5720 Neural Networks and Deep Learning,
Id : 700771673

Overview
This repository contains the code and deliverables for Home Assignment 5, covering two programming tasks:

Q3: Basic GAN Implementation - A Generative Adversarial Network (GAN) to generate handwritten digits from the MNIST dataset using TensorFlow.
Q4: Data Poisoning Simulation - A simulation of a data poisoning attack on a sentiment classifier trained on the IMDB dataset, targeting reviews mentioning "UC Berkeley".

Non-programming answers (Q1, Q2, Q5, Q6) are documented separately and submitted as a PDF or docx file.
Files

gan_mnist_corrected.py: Implements the GAN for Q3. Outputs include generated images at epochs 0, 50, 100 (image_at_epoch_0001.png, image_at_epoch_0051.png, image_at_epoch_0100.png) and a loss plot (gan_losses.png).
poisoning_simulation.py: Implements the data poisoning simulation for Q4. Outputs include an accuracy comparison plot (accuracy_comparison.png) and confusion matrices (cm_clean_model.png, cm_poisoned_model.png).
[Other Files]: Non-programming answers (Q1, Q2, Q5, Q6) are in a separate submission document.

Setup Instructions
Environment

Use Google Colab or a local Python environment with TensorFlow 2.x, NumPy, Matplotlib, and Scikit-learn.
Ensure GPU is enabled in Colab (Edit > Notebook Settings > GPU) for faster training.

Colab Setup

Upload gan_mnist_corrected.py and poisoning_simulation.py to Colab.
Install dependencies in a Colab cell:!pip install tensorflow matplotlib scikit-learn


Running the Code:
Q3: Execute gan_mnist_corrected.py to train the GAN for 100 epochs (~15-20 minutes on GPU). Download the generated images and loss plot.
Q4: Execute poisoning_simulation.py to train the classifier and simulate poisoning (~2-3 minutes). Download the accuracy plot and confusion matrices.


Download output files from Colab’s file explorer.

Deliverables
Q3: Basic GAN Implementation

Generated Images: image_at_epoch_0001.png (noisy output), image_at_epoch_0051.png (digit-like shapes), image_at_epoch_0100.png (clearer digits).
Loss Plot: gan_losses.png (shows Generator and Discriminator losses over 100 epochs).
Optional: Saved models generator_model.keras and discriminator_model.keras (if included).

Q4: Data Poisoning Simulation

Accuracy Plot: accuracy_comparison.png (compares clean and poisoned model accuracy, e.g., ~0.85 to ~0.80).
Confusion Matrices: cm_clean_model.png (clean model performance) and cm_poisoned_model.png (post-poisoning performance).
Console Output: Displays accuracy values and number of poisoned reviews.

** THE END **  


