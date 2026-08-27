# 🤖 AI Student Support Services

### An AI-Based Student Query Classification and Support Chatbot

---

## 📌 Project Overview

**AI Student Support Services** is a machine learning-based chatbot developed to provide automated assistance for common student queries.

The system uses **Natural Language Processing (NLP)** and **Machine Learning** techniques to understand student questions, classify them into predefined intent categories, and provide an appropriate response.

The project demonstrates how AI and machine learning can be applied to automate basic student support services and make information access faster and more convenient.

---

## 🎯 Project Objectives

The main objectives of this project are:

* To develop an AI-based chatbot for student support.
* To understand and classify student queries automatically.
* To use NLP techniques for processing text-based queries.
* To convert textual data into numerical features using TF-IDF.
* To train a machine learning model for intent classification.
* To provide relevant responses to student queries.
* To reduce manual effort in handling frequently asked questions.

---

## 💡 Problem Statement

Students regularly have questions related to admission, fees, examinations, courses, library, hostel, and other university services.

Finding answers manually can take time and may require assistance from university staff. Therefore, an automated student support system can help students receive quick responses to commonly asked questions.

This project aims to develop a simple AI-powered chatbot that can automatically classify student queries and provide relevant responses.

---

## 🛠️ Technologies Used

| Technology                      | Purpose                                 |
| ------------------------------- | --------------------------------------- |
| **Python**                      | Programming language                    |
| **Pandas**                      | Dataset handling and data analysis      |
| **NumPy**                       | Numerical operations                    |
| **Scikit-learn**                | Machine learning and text processing    |
| **TF-IDF Vectorizer**           | Converting text into numerical features |
| **Machine Learning Classifier** | Student query intent classification     |
| **Joblib**                      | Saving and loading the trained model    |
| **Google Colab**                | Development and execution environment   |

---

## 📂 Project Structure

```text
AI-Student-Support-Services/
│
├── AI_Student_Support_Services.ipynb
├── student_support_dataset.csv
├── README.md
│
└── screenshots/
    ├── dataset.png
    ├── preprocessing.png
    ├── tfidf.png
    ├── model_evaluation.png
    └── chatbot_output.png
```

---

## 📊 Dataset

The dataset contains student queries along with their corresponding intent categories.

The dataset is used to train the machine learning model so that it can recognize the intent of a new student question.

### Example Intent Categories

* Admission
* Fees
* Examination
* Courses
* Library
* Hostel
* General Student Support

### Example Dataset Format

| Query                                | Intent      |
| ------------------------------------ | ----------- |
| What are the admission requirements? | Admission   |
| How can I pay my fees?               | Fees        |
| When is the examination?             | Examination |
| What courses are available?          | Courses     |
| What are the library timings?        | Library     |

---

## 🔄 Project Workflow

The project follows the following workflow:

```text
Dataset
   ↓
Data Understanding
   ↓
Text Cleaning
   ↓
TF-IDF Vectorization
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Chatbot Development
   ↓
Student Query
   ↓
Intent Prediction
   ↓
Response Generation
```

---

## 🧹 1. Data Preprocessing

The raw student queries are cleaned and prepared before being given to the machine learning model.

The preprocessing stage helps remove unnecessary text variations and prepares the queries for further analysis.

### Main purpose:

* Clean the text data.
* Standardize the queries.
* Prepare text for machine learning.
* Improve the quality of classification.

---

## 🔢 2. TF-IDF Vectorization

Since machine learning models cannot directly understand text, the student queries are converted into numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)**.

TF-IDF identifies the importance of words within the student queries and represents the text numerically.

This numerical representation is then provided to the machine learning model for training and prediction.

---

## 🤖 3. Machine Learning Model

A supervised machine learning classification model is trained using the processed student queries and their corresponding intent categories.

The model learns patterns from the training data and predicts the appropriate intent when a new student query is entered.

### Model Process

```text
Student Query
      ↓
Text Cleaning
      ↓
TF-IDF Features
      ↓
Trained ML Model
      ↓
Predicted Intent
```

---

## 📈 4. Model Evaluation

The trained model is evaluated using test data to determine how accurately it can classify unseen student queries.

The evaluation helps measure the effectiveness of the trained classification model.

### Evaluation Metric

**Accuracy:**
The actual accuracy obtained by the model is reported in the project notebook.

> **Note:** The accuracy value should be updated here according to the final result obtained from the project.

---

## 💬 5. Chatbot Working

The chatbot works by following a simple prediction and response process.

When a student enters a question:

1. The chatbot receives the student's query.
2. The query is cleaned using the preprocessing function.
3. The cleaned query is converted into TF-IDF features.
4. The trained machine learning model predicts the intent.
5. The system identifies the response associated with that intent.
6. The chatbot displays the response to the student.

### Chatbot Architecture

```text
              Student
                 │
                 ▼
          Student Query
                 │
                 ▼
         Text Preprocessing
                 │
                 ▼
          TF-IDF Vectorizer
                 │
                 ▼
       Machine Learning Model
                 │
                 ▼
         Intent Prediction
                 │
                 ▼
        Response Selection
                 │
                 ▼
          Chatbot Response
```

---

## 🧪 6. Testing the Chatbot

The chatbot can be tested by entering different types of student questions.

### Example

**Student Query:**

```text
What are the library timings?
```

**Chatbot:**

```text
[Relevant response based on the predicted intent]
```

Another example:

**Student Query:**

```text
How can I pay my fees?
```

**Chatbot:**

```text
[Relevant response based on the predicted intent]
```

The chatbot can be tested with multiple queries to verify whether the correct intent and response are generated.

---

# 📸 Project Screenshots

## 1. Dataset Preview

Add the screenshot of the dataset here.

```text
![Dataset Preview](screenshots/dataset.png)
```

**Description:**
This screenshot shows the student-support dataset containing queries and their corresponding intent categories.

---

## 2. Data Preprocessing

Add the preprocessing screenshot here.

```text
![Data Preprocessing](screenshots/preprocessing.png)
```

**Description:**
This screenshot demonstrates the text preprocessing stage used to prepare student queries for machine learning.

---

## 3. TF-IDF Vectorization

Add the TF-IDF screenshot here.

```text
![TF-IDF Vectorization](screenshots/tfidf.png)
```

**Description:**
TF-IDF converts the textual student queries into numerical features that can be processed by the machine learning model.

---

## 4. Model Evaluation

Add the model evaluation screenshot here.

```text
![Model Evaluation](screenshots/model_evaluation.png)
```

**Description:**
This screenshot presents the evaluation result of the trained machine learning model.

---

## 5. Chatbot Output

Add the final chatbot screenshot here.

```text
![Chatbot Output](screenshots/chatbot_output.png)
```

**Description:**
This screenshot demonstrates the chatbot responding to a student's query after predicting the appropriate intent.

---

## ✅ Results

The developed AI Student Support Services chatbot is capable of:

* Processing student queries.
* Identifying the intent of a query.
* Classifying queries into predefined categories.
* Providing an appropriate response.
* Automating basic student support interactions.

The project demonstrates the practical application of **Natural Language Processing and Machine Learning** for student support services.

---

## 🌟 Key Features

* AI-based student query classification
* NLP-based text processing
* TF-IDF text vectorization
* Machine learning-based intent prediction
* Automated response generation
* Simple and user-friendly chatbot interaction
* Easily extendable with additional intents and queries

---

## ⚠️ Project Limitations

Although the chatbot provides automated support, it has some limitations:

* It can respond only to intents included in the training dataset.
* It may not correctly understand completely new or unrelated questions.
* The quality of responses depends on the quality and size of the training dataset.
* It does not currently provide real-time university database information.
* The current system is designed mainly for predefined student-support queries.

---

## 🚀 Future Scope

The project can be further improved by adding:

* **Voice-based interaction**
* **Multilingual support**
* **Web-based chatbot interface**
* **Mobile application**
* **Real-time university database integration**
* **Larger and more diverse training datasets**
* **Advanced NLP and Generative AI**
* **Personalized student assistance**
* **24/7 automated student support**

---

## ▶️ How to Run the Project

### Step 1: Open Google Colab

Open the project notebook in Google Colab.

### Step 2: Upload Dataset

Upload the `student_support_dataset.csv` file into the Colab environment.

### Step 3: Run the Notebook

Run the notebook cells sequentially from beginning to end.

### Step 4: Train the Model

Execute the preprocessing, TF-IDF vectorization, model training, and evaluation steps.

### Step 5: Run the Chatbot

Execute the chatbot function after the model has been trained.

### Step 6: Enter a Query

Enter a student question and observe the chatbot's response.

---

## 📦 Project Deliverables

The project contains the following major components:

* Python/Google Colab Notebook
* Student Support Dataset
* Trained Machine Learning Model
* Chatbot Implementation
* Project Screenshots
* Project Documentation
* README File

---

## 🎓 Academic Context

**Project Title:** AI Student Support Services
**Program:** MBA – Business Analytics
**Project Type:** Machine Learning / NLP Based Chatbot
**Development Platform:** Google Colab
**Programming Language:** Python

---

## 📚 References

The project is based on concepts and documentation related to:

* Python Programming
* Natural Language Processing
* Machine Learning
* TF-IDF Text Vectorization
* Scikit-learn
* Pandas
* Google Colab

---

## 👩‍💻 Author

**Palak Yadav**

**MBA – Business Analytics**

**Shri Vaishnav Vidhyapeeth Vishwavidyalaya**

---

## 📝 Conclusion

The **AI Student Support Services** project demonstrates how Machine Learning and Natural Language Processing can be used to develop an automated student support chatbot.

The system processes student questions, predicts their intent using a trained machine learning model, and provides an appropriate response. The project provides a practical example of applying AI techniques to improve the efficiency and accessibility of basic student support services.

With future improvements such as voice interaction, multilingual support, real-time database integration, and advanced Generative AI, the system can be developed into a more comprehensive student assistance platform.
