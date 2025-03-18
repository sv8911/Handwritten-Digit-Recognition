# Handwritten-Digit-Recognition

## **What’s This All About?**
Hey there! This project is my take on teaching a computer to read handwritten digits (0-9) using a **Convolutional Neural Network (CNN)**. I’m working with the **MNIST dataset**, a classic stash of 70,000 tiny grayscale images—60,000 to train the model and 10,000 to test it. The goal? Get the machine to spot those digits like a pro and see how well it does!

## **What It Does**
- Grabs and preps the MNIST dataset for action.
- Builds a CNN to figure out what each digit is.
- Checks how good it is with accuracy stats, some cool graphs, and a confusion matrix.
- Saves the trained model so I don’t have to start from scratch next time.

## **Tools I Used**
- **TensorFlow/Keras**: The brainpower behind the CNN.
- **NumPy**: My go-to for juggling numbers.
- **Matplotlib**: For sketching graphs and peeking at images.
- **Seaborn**: Makes my confusion matrix look sharp.
- **Scikit-learn**: Helps me see where the model trips up.

## **How It Works**
- **GPU Check**: Sees if I’ve got a graphics card to make things zippy.
- **Data Prep**: Tweaks the images (shrinking numbers from 0-255 to 0-1) and shapes them for the CNN.
- **Building the CNN**: Stacks layers to spot patterns—think of it like teaching the model to “see” edges and shapes.
- **Training**: Feeds it 60,000 images over 10 rounds (epochs) to learn the digits.
- **Checking Results**:  
  - Tests it on 10,000 images.  
  - Draws graphs of accuracy and loss (how wrong it is).  
  - Shows a confusion matrix to spot mix-ups (like 7s looking like 1s).
- **Saving**: Stores the model so I can reuse it anytime.

