# Text Summarizer

A **Text Summarizer** tool built to condense lengthy text documents into concise summaries using advanced Natural Language Processing (NLP) techniques. This repository is designed for developers and researchers who are interested in exploring text summarization methods and building practical applications around it.

---

## Features

- Extractive summarization to retain key sentences from the text.
- Support for various text file formats.
- Configurable summarization length.
- Easy-to-integrate modular design.
- Scalable architecture for large documents.

---

## Requirements

Make sure you have the following installed:

- Python 3.8 or higher
- pip (Python package manager)

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

---

## Usage

### Clone the Repository

```bash
git clone https://github.com/rudransh-rai/TextSummarizer.git
cd TextSummarizer
```

### Run the Summarizer

1. Add the text file you want to summarize to the `input` directory.
2. Execute the script:

```bash
python summarizer.py --input input/yourfile.txt --output output/summary.txt --ratio 0.2
```

#### Arguments:
- `--input`: Path to the input text file.
- `--output`: Path to save the summary.
- `--ratio`: Proportion of the original text to retain in the summary (default is 0.2).

### Example

```bash
python summarizer.py --input input/article.txt --output output/summary.txt --ratio 0.3
```

---

## File Structure

```plaintext
TextSummarizer/
├── input/         # Directory for input text files
├── output/        # Directory for output summaries
├── summarizer.py  # Main script for text summarization
├── utils.py       # Helper functions and utilities
├── requirements.txt  # Python dependencies
└── README.md      # Documentation
```

---

## How It Works

1. **Preprocessing**: The input text is tokenized and cleaned for better summarization.
2. **Sentence Scoring**: Each sentence is scored based on importance using statistical and linguistic metrics.
3. **Summary Generation**: Top-ranked sentences are selected and arranged to form the summary.

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or feedback, feel free to contact:

- **Author**: Rudransh Rai
- **GitHub**: [rudransh-rai](https://github.com/rudransh-rai)

---

Happy Summarizing!

