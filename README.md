# QuestionAnsweringSystem
A simple question-answering system built in Google Colab using PyTorch and RNN. Trained on a small custom dataset of QA pairs, this model demonstrates how basic NLP with deep learning can be used for intelligent response generation. Easily extendable to larger datasets for more powerful performance.





## Features

- RNN-based question answering using PyTorch
- Implemented entirely in a Google Colab notebook
- Custom tokenizer and vocabulary builder
- Trained on a CSV-based QA dataset
- Easily extendable and customizable

---

## How to Run

1. Open the Colab notebook:
   [Link to Colab Notebook](https://colab.research.google.com/drive/1NZrFCLhez9CP3rMnGgPgIGLUfrN9LV2I#scrollTo=IUy9v4JmRucp)

2. Upload your dataset (`100_Unique_QA_Dataset.csv`) to the Colab environment.

3. Run each cell in order to:
   - Load the dataset
   - Tokenize the data
   - Build the vocabulary
   - Define the RNN model
   - Train the model
   - Test the model on custom questions

---

## Dataset

The dataset used is a simple CSV file named `100_Unique_QA_Dataset.csv` with two columns:

- `question`
- `answer`

You can expand this file by adding more QA pairs. A larger dataset will improve the model’s performance.

---

## Model Details

- **Embedding Layer**: Converts words into vectors (embedding dim = 50)
- **RNN Layer**: Basic RNN with hidden size of 64
- **Fully Connected Layer**: Maps RNN output to vocabulary size for prediction

---

## Future Improvements

- Replace RNN with LSTM or GRU for better context handling
- Add attention mechanism for long questions
- Train on larger QA datasets like SQuAD
- Save the trained model using `torch.save()` and load with `torch.load()`
- Export as a web app using Gradio, Flask, or FastAPI

---

## License

This project is open source under the MIT License.

---

## Author

Prince Bhattrai

