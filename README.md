# Document Summarizer

A lightweight Python project for generating concise summaries from text using multiple summarization techniques. The project includes a simple Streamlit interface and modular implementations for experimentation and development.

---

# Features

* Multiple summarization approaches
* Streamlit-based web interface
* Modular and easy-to-understand code structure
* Jupyter notebooks for testing and experimentation
* Easy to extend with additional summarization methods

---

# Project Structure

```text
.
├── dev_container/
├── helper_file/
├── py_notebooks/
├── python_algo.py
├── streamlit.py
├── sumy_lib_based_summary.py
├── transformers_based_summary.py
├── requirements.txt
├── LICENSE
└── README.md
```

---

# Getting Started

## Clone the Repository

```bash
git clone https://github.com/your-username/document-summarizer.git
cd document-summarizer
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Application

Launch the Streamlit application:

```bash
streamlit run streamlit.py
```

After running the command, open the local URL displayed in the terminal.

---

# Project Files

| File                            | Description                       |
| ------------------------------- | --------------------------------- |
| `python_algo.py`                | Main summarization workflow       |
| `sumy_lib_based_summary.py`     | Sumy-based summarization          |
| `transformers_based_summary.py` | Transformer-based summarization   |
| `streamlit.py`                  | Streamlit web application         |
| `py_notebooks/`                 | Development and testing notebooks |

---

# Requirements

* Python 3.9 or later
* pip

Install all required packages using:

```bash
pip install -r requirements.txt
```

---

# Technologies Used

* Python
* Streamlit
* Transformers
* Sumy
* Jupyter Notebook

---

# Future Enhancements

* PDF document support
* DOCX document support
* Batch summarization
* Download summary as a text file
* Performance improvements
* Additional summarization algorithms

---

# Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your work.
5. Open a Pull Request.

---

# License

This project is distributed under the MIT License. See the `LICENSE` file for more information.
