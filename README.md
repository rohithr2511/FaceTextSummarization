````markdown
# 📝 Text Summarizer using Hugging Face Transformers

A command-line Python tool that summarizes long text documents using the BART model from Hugging Face Transformers. Designed to handle documents up to 10,000 words with efficient chunking and clean output. Ideal for students, researchers, journalists, and developers who want quick summaries of long-form content.

---

## 📌 Features

- ✅ Summarize large text files (up to 10,000 words)
- ⚙️ Uses `facebook/bart-large-cnn` for high-quality summarization
- 🧠 Automatic chunking for long input
- 💬 Simple command-line interface (CLI)
- 💾 Saves summaries to `.txt` files
- 🚫 Handles file errors and missing input gracefully

---

## 🛠️ Technologies Used

- Python 3.8+
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- PyTorch (for model backend)
- tqdm (for progress bars)

---

## 🚀 Setup Instructions

1. **Clone the Repository**

```bash
git clone https://github.com/rohithr2511/FaceTextSummarization.git
cd FaceTextSummariztion
````

2. **Create a Virtual Environment (Optional but Recommended)**

```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

3. **Install Requirements**

```bash
pip install -r requirements.txt
```

---

## 💡 Usage

```bash
python summarizer.py path/to/input.txt path/to/output.txt
```

### ✅ Example

```bash
python summarizer.py samples/input1.txt samples/summary1.txt
```

The program will load the BART model, summarize the file content, and save the output to `summary1.txt`.

---

## 📂 Folder Structure

```
FaceTextSummarizer/
├── summarizer.py         # Main Python script
├── requirements.txt      # Python dependencies
├── README.md             # This file
└── samples/              # Input and output samples
    ├── input1.txt
    ├── summary1.txt
    ├── ...
```

---

## 🧪 Sample Outputs

We included 5 sample documents and their corresponding summaries in the `samples/` directory, covering:

1. Artificial Intelligence in Healthcare
2. India's Independence History
3. Climate Change Report
4. Business Annual Report
5. Scientific Research Abstract

---

## 📈 Model Used

* **Model:** [`facebook/bart-large-cnn`](https://huggingface.co/facebook/bart-large-cnn)
* **Framework:** Hugging Face Transformers
* Fine-tuned specifically for summarization tasks

---

## 🛠 Future Enhancements (Bonus Features)

* [ ] Gradio Web Interface
* [ ] Batch file processing
* [ ] Adjustable summary length
* [ ] Language detection support

---

## ✍️ Author

**P Rohith Raveendran**
[LinkedIn]([https://www.linkedin.com/in/yourprofile](https://www.linkedin.com/in/p-rohith-raveendran-dataanalyst/)) | [GitHub](https://github.com/rohithr2511)

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

* [Hugging Face](https://huggingface.co/)
* [Transformers Documentation](https://huggingface.co/docs/transformers/index)
* [BART Model Card](https://huggingface.co/facebook/bart-large-cnn)

