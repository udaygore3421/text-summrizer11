# 📝 Text Summarization Using Python, NLP & Machine Learning

An interactive Text Summarization application developed using Python, Natural Language Processing (NLP), and Streamlit.

This project explores different text summarization techniques to convert lengthy text into shorter, meaningful summaries while preserving the important information.

It includes traditional frequency-based summarization, LexRank, Latent Semantic Analysis (LSA), and TextRank algorithms, along with additional experiments using Transformers and LangChain.

## 🚀 Project Overview

Reading large documents, articles, and reports can be time-consuming.

This project aims to simplify the reading process by automatically extracting the most important information from lengthy text.

Users can enter their text, select a summarization algorithm, and specify the desired number of sentences. The application then generates a concise summary using the selected technique.

## ✨ Key Features

- **Text Summarization:** Converts lengthy text into concise summaries.
- **Multiple Algorithms:** Supports different extractive summarization techniques.
- **Frequency-Based Summarization:** Identifies important sentences using word frequency and sentence ranking.
- **LexRank:** Uses sentence similarity and graph-based ranking.
- **LSA (Latent Semantic Analysis):** Identifies important semantic relationships in text.
- **TextRank:** Ranks sentences based on their importance and relationships.
- **Custom Summary Length:** Allows users to specify the number of sentences in the output.
- **Interactive Interface:** Provides an easy-to-use Streamlit application.
- **NLP Processing:** Uses NLTK for text tokenization and preprocessing.
- **Experimental Approaches:** Includes additional Jupyter Notebook implementations using Transformers and LangChain.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Interactive web interface |
| NLTK | Natural Language Processing |
| Sumy | Extractive text summarization |
| LangChain | Experimental text summarization |
| Transformers | Experimental transformer-based summarization |
| Jupyter Notebook | Development and experimentation |

## 🧠 Summarization Techniques

### 1. Frequency-Based Summarization (Python)

- Converts text into lowercase.
- Tokenizes the text into words and sentences.
- Calculates word frequency.
- Removes common English stopwords.
- Assigns importance scores to sentences.
- Selects important sentences to generate a summary.

### 2. LexRank

- Uses sentence similarity.
- Represents sentences as nodes in a graph.
- Calculates sentence importance using graph-based ranking.
- Selects the most relevant sentences.

### 3. Latent Semantic Analysis (LSA)

- Identifies important concepts and relationships in the text.
- Uses mathematical techniques to understand the underlying structure.
- Selects sentences representing important information.

### 4. TextRank

- Uses graph-based ranking techniques.
- Identifies relationships between sentences.
- Ranks sentences according to their importance.
- Generates summaries using the highest-ranked sentences.

### 5. Transformer-Based Summarization (Experimental)

- Explores transformer-based language models.
- Includes an experimental Google Pegasus summarization implementation.
- Uses pre-trained language model concepts.

## 🔄 Project Workflow

1. User enters lengthy text.
2. User selects a summarization algorithm.
3. User specifies the desired number of sentences.
4. The application processes the input text.
5. The selected summarization algorithm identifies important sentences.
6. The application generates and displays the final summary.

## 📂 Project Structure

```text
text-summrizer11/
│
├── helper.py
├── python_algo.py
├── sumy_lib_based_summary.py
├── transformers_based_summary.py
├── streamlit.py
│
├── Text Summary based on sumy lib.ipynb
├── Text Summary using Langchain.ipynb
├── Text summary based on transformers.ipynb
├── Text summary based on training a pre existing model.ipynb
├── Text summary using python.ipynb
│
├── requirements.txt
├── README.md
├── .gitignore
└── .gitattributes
```

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

### Step 1: Clone the Repository

```bash
git clone https://github.com/udaygore3421/text-summrizer11.git
```

### Step 2: Navigate to the Project Directory

```bash
cd text-summrizer11
```

### Step 3: Create a Virtual Environment

```bash
python -m venv venv
```

### Step 4: Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### Step 5: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 6: Run the Streamlit Application

```bash
streamlit run app.py
```

If your main application file is still named `streamlit.py`, rename it to `app.py` before running the command.

Open the local URL displayed in your terminal to access the application.

## 📦 Requirements

- Python 3.x
- NLTK
- Streamlit
- Sumy
- Internet connection for installing dependencies and downloading NLTK resources.

## 🎯 Example Usage

**Input Text:**

"Artificial Intelligence is transforming modern industries. Businesses are using machine learning to automate processes, improve efficiency, and make better decisions. Natural Language Processing allows computers to understand and process human language. Text summarization helps users extract important information from lengthy documents."

**Selected Algorithm:** TextRank

**Desired Summary Length:** 2 sentences

**Expected Output:**

A concise summary containing the most important information from the original text.

*Note: Actual summary output depends on the selected algorithm and input text.*

## 🔮 Future Enhancements

- Add abstractive summarization using advanced transformer models.
- Integrate Google Pegasus and BART models into the application.
- Add PDF and DOCX document summarization.
- Add URL-based article summarization.
- Implement summarization quality evaluation.
- Compare different algorithms based on execution time and summary quality.
- Improve the user interface and add downloadable summaries.
- Deploy the application online.

## 👨‍💻 Author

**Uday Gore**

GitHub: https://github.com/udaygore3421

Project Repository: https://github.com/udaygore3421/text-summrizer11

---

⭐ If you find this project useful, consider giving the repository a star!

**Built with Python, NLP, and Streamlit.**
