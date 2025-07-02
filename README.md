# RAG Document Q&A with PDF and Message History

This project implements a **Retrieval-Augmented Generation (RAG)** system that allows users to upload a PDF file and ask context-aware questions. The system uses a language model to generate answers grounded in the PDF content and optionally a conversation history.

---

## 🔍 Features

- 📄 Upload any PDF document.
- 💬 Integrate chat history to provide contextual awareness (coming soon).
- 🧠 Ask questions and get answers from the combined knowledge base.
- 🚀 Built with **Streamlit**, easy to run and interact with.

---

## 🗂️ Project Structure

```
├── app.py              # Streamlit app for user interaction
├── temp.pdf            # Sample PDF file used for testing
├── requirements.txt    # Python dependencies
├── .gitignore          # Git exclusions
├── LICENSE             # MIT License
└── README.md           # This file
```

---

## ⚙️ Installation & Usage

### 1. Clone the repository

```bash
git clone https://github.com/shishiradk/RAG-document-Q-A-with-pdf-and-message-history.git
cd RAG-document-Q-A-with-pdf-and-message-history
```

### 2. Set up virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate         # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

---

## 📌 Example Use Cases

- Summarizing large research papers.
- Extracting answers from technical documentation.
- Combining previous user queries with document insights (chat history feature coming soon).

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Pull requests, suggestions, and feedback are welcome. Feel free to open an issue or submit a PR.

---

## 📬 Contact

Created by [@shishiradk](https://github.com/shishiradk) — feel free to reach out if you have questions or ideas.


---

![Screenshot 2025-07-02 002530](https://github.com/user-attachments/assets/493b7e7b-16ac-40a0-a2bb-da2b2fbbd900)


---

