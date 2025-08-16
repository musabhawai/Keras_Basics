# Keras Basics – Sequential Model

## 🧠 Overview
This project demonstrates the *basic workflow of building a neural network using Keras with TensorFlow backend*.  
It covers creating a simple model, compiling, training, evaluating, plotting training history, and saving the model for future use.  

## 📖 About Keras Sequential Model
The *Sequential API* in Keras is the easiest way to build deep learning models.  
It allows stacking layers like Dense, Activation, etc. in a linear order to form a neural network.  
This project introduces the foundation of building neural networks with Keras.  

## 🛠 Technologies Used
- Python  
- TensorFlow  
- Keras  
- NumPy, Pandas  
- Matplotlib (for visualization)  

## ⚙️ Workflow
1. *Model Creation*  
   - Used keras.models.Sequential() to build the model.  
   - Added layers with keras.layers.Dense and activation functions.  

2. *Model Compilation*  
   - Optimizer: RMSprop  
   - Loss Function: Mean Squared Error (MSE)  

3. *Training*  
   - Model trained for multiple epochs.  
   - Training history captured (model.history.history).  

4. *Evaluation*  
   - Evaluated model performance using *MSE*.  
   - Visualized training loss across epochs.  

5. *Model Saving*  
   - Saved trained model using model.save() for later use.  

## 📂 Code Included
- Creating a Sequential model  
- Adding Dense & Activation layers  
- Compiling with optimizer & loss  
- Training with epochs and history tracking  
- Plotting training history  
- Evaluating with MSE  
- Saving the trained model
