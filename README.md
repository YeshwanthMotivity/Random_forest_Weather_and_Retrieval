### Date-Based Weather Forecaster with Groq 🌤️
This project is a machine learning application that predicts weather based on historical data and provides friendly, AI-generated advice. It combines a Random Forest Regressor for numerical temperature forecasting and a Groq LLM for conversational, real-time weather interpretation. The entire application is served through an interactive Gradio interface.

---

### 🚀 Features
• 📈 **Machine Learning Model**: Uses a Random Forest Regressor to predict the average temperature for a given date.

• 🤖 **AI-Powered Advice**: Integrates the Groq API to provide instant, human-readable advice on what to wear, suggested activities, and general tips based on the predicted temperature.

• 📊 **Data-Driven Forecasting**: The model trains on a provided data.csv file, making it adaptable to any historical weather dataset.

• 🌐 **Interactive UI**: A user-friendly web interface built with Gradio allows for easy date selection and displays both the numerical prediction and the AI advice.

• ⚡ **Streaming Responses**: The AI advice is streamed as it's being generated, providing a dynamic user experience.

---
### 🛠️ Tech Stack

|          Component   |                 Technology     |                      Purpose                       |
| -------------------- | ------------------------------ | ---------------------------------------------------|
| **Machine Learning** | `scikit-learn` (Random Forest) | Trains the forecasting model.                      |
| **LLM Integration**  | `Groq`                         | Provides fast, conversational AI responses.        |
| **Data Handling**    | `Pandas`                       | Manages and preprocesses the CSV data.             |
| **Web Interface**    | `Gradio`                       | Creates the interactive user interface.            | 
| **Core Libraries**   | `NumPy`, `datetime`            | Essential for data manipulation and date handling. |

---
### 💻 How to Run
To run this project, you will need a data.csv file with historical weather data and a Groq API key.

#### Prerequisites
• Python: Version 3.9 or higher.

• Groq API Key: You need to get an API key from the Groq Console.

#### Setup & Execution

1. **Clone the Repository**:
   ```
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Add Your Files**:
   
     • Place your historical weather data in a file named data.csv in the root directory. It should contain columns for Date, Temp Max, and Temp Min.

     • Open the main script (Random_forest_Weather_and_Retrieval.py) and replace the placeholder GROQ_API_KEY with your actual key.

3. **Launch the notebook**:
   ```
    Open Rag_Chatbot.ipynb in Jupyter Notebook Execute the cells step by step. Follow step-by-step execution
   ```

---

### 📄 Project Workflow
1. **Model Training**: The script first loads data.csv, preprocesses it to create features like day, month, and year, and trains a Random Forest model.
2. **User Input**: The user selects a date from the Gradio interface.
3. **Numerical Prediction**: The trained model uses the date to predict an average temperature. This result is immediately displayed
4. **AI Interpretation**: The predicted temperature is sent to the Groq API along with a prompt.
5. **Live Streaming**: The Groq model streams back a user-friendly response, which appears in real time on the Gradio interface.
   
---

## 🙋‍♂️ Author

• Mentor / Manager: Mr. Venkata Ramana Sudhakar Polavarapu

• Mudimala Yeshwanth Goud

 🛠️ Passionate about AI/ML, NLP, RAG, Data Science, system programming, full-stack development, and intelligent assistant systems.

---

## 📬 Contact
For any questions or collaboration, feel free to reach out:

Email: yeshwanth.mudimala@motivitylabs.com

---
