# 🦸‍♂️ Superhero Predictor

This Python project uses logistic regression to predict a superhero's name based on various attributes. It utilizes **Pandas** for data manipulation, **Matplotlib** for visualization (if needed), and **Scikit-learn** for machine learning.

---

## ✨ Features

- 🧹 Cleans and preprocesses a dataset of superheroes.
- 🔄 Splits the data into training and testing sets.
- 📈 Fits a logistic regression model to predict the name of a superhero.
- 🎮 Accepts user input to predict a superhero's name based on their attributes.
- 📊 Evaluates the model using accuracy and a confusion matrix.

---

## 📂 Dataset

The project expects a CSV file [Download Dataset](test.csv) containing the following columns:

- 🦸 `name`: Name of the superhero.
- 🌟 `overall_score`: Overall score of the superhero.
- 🧠 `intelligence_score`: Intelligence score.
- ⚡ `speed_score`: Speed score.
- 💪 `power_score`: Power score.
- 🥋 `combat_score`: Combat score.
- 🛡️ `has_mind_control_resistance`: Binary value indicating resistance to mind control (1 for Yes, 0 for No).
- 🌀 `has_telepathy_resistance`: Binary value indicating resistance to telepathy (1 for Yes, 0 for No).

---

## ⚙️ Requirements

Install the required Python libraries before running the project:

```bash
pip install pandas matplotlib scikit-learn

```
# 🛠️ How It Works

### 1. Data Preprocessing  
🧹 The program reads a dataset from a CSV file.  
🚫 Missing values are dropped to ensure clean data.  

### 2. Training the Model  
📋 The features (`X`) and target (`Y`) are extracted from the dataset.  
✂️ The data is split into training and testing sets using an 80-20 split.  
🤖 A logistic regression model is trained on the training set.  

### 3. Making Predictions  
🧮 The model predicts superhero names for the test set and calculates the accuracy.  

### 4. User Input  
🎤 Users can input superhero attributes (e.g., scores, resistances) to predict the superhero's name.  

---

# 🚀 How to Run the Project

### 1. Download the CSV Dataset  
📥 Place the dataset in the specified location  

### 2. Run the Python Script  
▶️ Execute the script to train the model and make predictions.  

### 3. Interact with the Program  
🖱️ Follow the prompts to input superhero attributes. The program will predict and display the superhero's name.  


