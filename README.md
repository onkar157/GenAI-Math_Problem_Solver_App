# 🧮 GenAI Math Problem Solver App


A powerful application for solving math-related questions, logic-based problems, and reasoning queries. Built using Google Gamma 2 and advanced tools, this app provides accurate answers and maintains a chat history for enhanced user experience.



## 🚀 Features

- **Solve Math Problems**: Handles complex calculations and mathematical queries.
- **Logic and Reasoning**: Accurately processes and answers logic-based and reasoning questions.
- **Advanced Tools**:
  - **WikipediaAPIWrapper**: Fetches relevant information to support reasoning.
  - **LLMMathChain**: Executes mathematical queries efficiently.
  - **Custom Prompt and Chain**: Ensures seamless query handling.
  - **Agent Initialization**: Combines tools like Wikipedia, calculator, and reasoning into a unified agent using LangChain.
- **Chat History**: Keeps a record of interactions for better context and user convenience.
- **Streamlit Interface**: Provides a user-friendly frontend for easy interaction.



## 🛠️ Tech Stack

- **Python**: Core programming language.
- **LangChain**: Framework for integrating tools and managing prompts.
- **Google Gamma 2**: The underlying engine for logical and mathematical processing.
- **Groq API**: Handles secure key management and API access.
- **Streamlit**: Framework for building the interactive frontend.

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-repo/math-problem-solver.git
cd math-problem-solver
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Set Up API Keys
- Obtain your Groq API key and add it to a `.env` file:
  ```env
  GROQ_API_KEY=your-api-key
  ```

### 4. Run the Application
```bash
streamlit run app.py
```



## 🧩 How It Works

1. **Input Queries**:
   - Users can ask math-related, logic-based, or reasoning questions in natural language.

2. **Tool Integration**:
   - **WikipediaAPIWrapper**: Retrieves supporting data from Wikipedia.
   - **Calculator Tool**: Handles calculations.
   - **Reasoning Tool**: Processes logical reasoning queries.

3. **Agent Initialization**:
   - Combines tools into an intelligent assistant using `initialize_agent()` with LangChain's `ZERO_SHOT_REACT_DESCRIPTION` agent type.

4. **Output Results**:
   - The app returns accurate answers and explanations for the queries.

5. **Chat History**:
   - Displays the previous conversation history for better context.



## ⚡ Benefits

- Combines multiple tools for comprehensive query resolution.
- Handles diverse types of questions, including complex math and logic-based queries.
- Saves time by providing concise and accurate answers.
- Maintains chat history for improved user experience.



## 🚧 Future Enhancements

- Add support for step-by-step solutions for complex problems.
- Provide downloadable chat history in `.txt` or `.pdf` format.
- Integrate advanced visualization for mathematical results.
- Expand toolset to include more reasoning frameworks.



## 🤝 Contribution

Contributions are welcome! Feel free to fork the repository and submit pull requests with your improvements or suggestions.


## 🌟 Acknowledgments

- **LangChain** for its robust integration framework.
- **Groq API** for enabling secure and efficient API access.
- **Google Gamma 2** for powering the logical and mathematical computations.
- **Streamlit** for creating an intuitive user interface.
