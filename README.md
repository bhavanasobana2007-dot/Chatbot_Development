# Week 9 – Chatbot Development

## Project Title
**Education AI Chatbot using Python and Ollama**

## 1. Objective
The objective of this project is to develop an interactive AI chatbot that answers educational questions using Python and a locally running Large Language Model.

## 2. Technologies Used
- Python
- Ollama
- Llama 3.2 1B
- Pandas
- Jupyter Notebook
- CSV files

## 3. Features
1. Answers questions related to Python, Artificial Intelligence and DBMS.
2. Supports continuous conversation with users.
3. Uses a local AI model to generate responses.
4. Tests the chatbot using 20 sample questions.
5. Stores questions, responses and timestamps in CSV files.
6. Records chatbot conversations for analysis.

## 4. Project Structure
- `chatbot.py` – Main chatbot program.
- `requirements.txt` – Required Python libraries.
- `README.md` – Project documentation.
- `dataset/sample_questions.csv` – 20 sample questions.
- `dataset/chat_history.csv` – Conversation history.
- `dataset/responses.csv` – Chatbot testing results.
- `dataset/chatbot_logs.txt` – Chatbot activity logs.
- `notebook/Week9_Chatbot_Development.ipynb` – Jupyter Notebook containing the implementation and testing.

## 5. Installation
1. Install Python.
2. Install Ollama.
3. Download the model using:

   `ollama pull llama3.2:1b`

4. Install the Python libraries:

   `pip install ollama pandas jupyter`

## 6. Execution
Run the following command in the project terminal:

`python chatbot.py`

Enter a question to receive a response. Type `exit` to stop the chatbot.

## 7. Testing
The chatbot is tested using factual, reasoning, coding and general conversation questions. The responses are reviewed to identify incorrect or incomplete answers.

## 8. Strengths
- Easy to use.
- Supports educational questions.
- Saves responses for analysis.
- Runs using a locally available language model.

## 9. Limitations
- Some answers may be incorrect or incomplete.
- Response speed depends on the computer's hardware.
- Ollama must be running to generate responses.
- Further testing and prompt improvements may be required.

## 10. Conclusion
The Education AI Chatbot was developed using Python and Ollama. This project helped me understand chatbot development, prompt design, response testing and conversation logging using CSV files.