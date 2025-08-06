### **Backpropagation**

**Backpropagation** is the learning process of a neural network. When the network makes a mistake, it goes back and adjusts the weights of the neurons to improve. It’s like a student learning from their mistakes by reviewing what went wrong and adjusting their approach.

---

### **Activation Functions (ReLU, etc.)**

After a neuron receives information, it uses an **activation function** to decide if it should pass the information forward or not.

- **ReLU (Rectified Linear Unit)**: A popular activation function. It passes values greater than 0 unchanged and sets negative values to 0. This helps the network learn faster and avoid some problems like vanishing gradients.

  Example: If a neuron gets the value -3, it sends 0; if it gets 5, it sends 5.

---

### **Loss Function (Entropy, etc.)**

A **loss function** tells the network how well or poorly it is doing. The goal is to minimize the loss (make it as small as possible).

- **Entropy**: A specific type of loss function that measures how "surprising" or "uncertain" the network's predictions are. Lower entropy means better predictions.

---

### **Convolutional Neural Networks (CNN)**

**CNNs** are a special type of neural network used for tasks like image recognition. They work by scanning images in small parts (called **convolutions**) and looking for patterns (like edges, shapes, etc.) to recognize objects.

---

### **Recurrent Neural Networks (RNN)**

**RNNs** are used for **sequential data** (like time series or text). They can remember information from previous steps in the sequence to make predictions for the next steps. It’s like reading a sentence word by word and understanding the context.

---

### **Long Short-Term Memory (LSTM)**

**LSTMs** are a type of RNN designed to better remember important information over long periods. Regular RNNs can forget useful information, but LSTMs are like memory-enhanced RNNs that can decide which information to keep or forget.

---

### **Gradient Descent**

To make neural networks learn, we use **gradient descent**, an optimization technique that helps the network slowly improve by making small adjustments to the weights. It’s like climbing down a hill to find the lowest point (the optimal solution).

---

### **Overfitting**

**Overfitting** happens when a neural network becomes too specialized to the data it has seen and performs poorly on new data. It's like memorizing answers instead of understanding the material.
