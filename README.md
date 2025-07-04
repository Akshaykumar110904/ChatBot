# 🤖 Chatbot using Python, Keras, and NLTK

This is a simple rule-based chatbot implemented using Python. It utilizes natural language processing (NLP) techniques and a neural network (trained using Keras) to respond to user queries based on predefined intents.

## 📁 Project Structure

```
.
├── chatgui.py           # GUI interface for interacting with the chatbot
├── train_chatbot.py     # Script to preprocess data and train the model
├── intents.json         # Training data with sample inputs and intents
├── words.pkl            # Pickled vocabulary generated during training
├── classes.pkl          # Pickled intent classes
├── chatbot_model.h5     # Trained Keras model
```

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/chatbot-python.git
cd chatbot-python
```

### 2. Install dependencies
Make sure you have Python 3.x installed. Then install the required packages:

```bash
pip install nltk tensorflow numpy
```

### 3. Train the model (optional)
You can retrain the model using:
```bash
python train_chatbot.py
```

### 4. Run the chatbot
```bash
python chatgui.py
```

A GUI window will open where you can interact with the chatbot.

## 🧠 How It Works

- The `intents.json` file contains predefined categories (intents), patterns (user inputs), and responses.
- The model is trained using a bag-of-words approach and a simple neural network.
- Once trained, the chatbot can classify user input and respond accordingly.

## 📌 Dependencies

- Python 3.x
- TensorFlow
- NLTK
- NumPy
- Tkinter (usually pre-installed with Python)
