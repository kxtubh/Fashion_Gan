# Fashion Gan

## A simple Generative Adversarial Network that uses the Fashion MNST dataset and outputs clothing items. 
---
## Overview
This project aims to set the foundation of Generative Adversial Networks.Once you are able to completely comprehend this model you can further build upon it and explore more complex models such as Conditional GANs,Deep Convoultion GANs,Cycle GANs,Style GANs and so on.
 


---

## Generative Adversarial Network
A Genative Adversarial Network is a type of deep learning model that's really good at generating new data that's similar to the data it was trained on.Think of it like an artist learning to paint by studying the works of the masters, and then creating their own original paintings in a similar style.GANs consits of two seperate neural networks which work hand in hand.

The Generator's job is to create new data that looks like the real data.This data could be anything from images to videos to text and music.The Discriminator judges the data and tells the difference between the real data and the fake data created by the generator.

The generator and discriminator are constantly competing with each other.The generator tries to create better and better fake data to fool the discriminator,while the discriminator tries to get better at spotting the fakes. Through this competition,both the networks improve and the generator eventually becomes good at creating fake realstic fake data.

---
## Code Structure

### 1. **Libraries and Dataset**
- **Tensorflow**: Trains the neural Network.
- **MatplotLib**: Plots all graphs.
- **Numpy**: Performs complex calculations.

### 2. **Generator**
This 

![image](https://github.com/user-attachments/assets/e1205056-5da9-40d6-a42d-b2149492c67b)



### 3. **Discriminator**


Model Summary : 

![image](https://github.com/user-attachments/assets/ecc045ca-6abe-4ff5-a545-0f0327917f40)

### 4. **Training Loop**
---

## Usage Instructions 

### 1.**Setup**


### 2.**Testing**

  
### 3.**Evaluate**


--- 

## Prerequisites
Ensure the following libraries and dependencies are installed:
- Python 3.7 or higher
- Required Python libraries:
  ```bash
  pip install tensorflow tensorflow-gpu matplotlib tensorflow-datasets ipywidgets
  ```
---
## License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code.

---
Feel free to reach out with suggestions or improvements! 
<br>
[Reference Video](https://www.youtube.com/watch?v=AALBGpLbj6Q)
