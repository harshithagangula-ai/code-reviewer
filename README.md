# 💻 AI Code Reviewer

An AI-powered Code Reviewer built with **Streamlit**, **LangChain**, and **Google Gemini 2.5 Flash**. This application analyzes source code and provides intelligent feedback on code quality, bugs, security issues, performance improvements, best practices, and overall maintainability.

---

## 🚀 Features

* Review code written in:

  * Python
  * Java
  * JavaScript
  * C
  * C++
  * SQL
* Multiple review modes:

  * Basic Review
  * Detailed Review
  * Security Review
* Adjustable AI creativity using the temperature slider.
* Instant AI-generated feedback.
* Clean and interactive Streamlit interface.

---

## 🛠️ Tech Stack

* Python
* Streamlit
* LangChain
* Google Gemini 2.5 Flash API
* python-dotenv

---

## 📂 Project Structure

```
AI_Code_Reviewer/
│── app.py
│── code_reviewer.py
│── prompt.py
│── utils.py
│── .env
│── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/AI_Code_Reviewer.git
cd AI_Code_Reviewer
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Create a `.env` file

```env
GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY
```

### 4. Run the application

```bash
streamlit run app.py
```

---

## 📌 How to Use

1. Launch the Streamlit application.
2. Select the programming language.
3. Choose the review type.
4. Adjust the temperature (optional).
5. Paste your source code into the text area.
6. Click **Review Code**.
7. View the AI-generated review and suggestions.

---

## 📊 AI Review Includes

* Overall Code Score
* Code Summary
* Bug Detection
* Security Analysis
* Performance Suggestions
* Code Smells
* Best Practices
* Improvement Recommendations

---

## 🔮 Future Enhancements

* File upload support
* GitHub repository integration
* Syntax highlighting
* Download review as PDF
* Multi-file project analysis
* Support for additional programming languages
* Code complexity metrics

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request with improvements or new features.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

Developed by **Harshitha**.
