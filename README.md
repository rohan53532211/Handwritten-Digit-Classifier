# 🧠 Handwritten-Digit-Classifier

## 🧩 Concepts Used:

- **Neural Network Architecture**:  
  Built using a simple step-by-step (**Sequential**) model with different layers and activation functions.

- **Softmax Function**:  
  Two versions used:  
  - A custom softmax function (`my_softmax`)  
  - TensorFlow’s built-in one (`tf.nn.softmax`)

- **Loss Function**:  
  Used **sparse categorical cross-entropy**, which is suitable when each image belongs to one of many classes (like 0–9).

- **Optimizer**:  
  Used the **Adam optimizer** to help the model learn better during training.

- **Data Preparation**:  
  The dataset (images of digits) is cleaned and reshaped so the model can understand and work with it.

- **Visualization**:  
  Used **Matplotlib** to show digit images and results visually.

---

## 📚 Libraries Used:

- **NumPy**: Helps with working on arrays and numbers.  
- **TensorFlow / Keras**: Used to build, train, and test the neural network.  
- **Matplotlib**: Used to show digit images and predictions.

---

## 📁 Project Structure:

- Code is organized clearly into:  
  **Model Building → Training Model → Visualizing Results**  
- Includes instructions to load the dataset and run the model easily.
