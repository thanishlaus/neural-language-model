# Neural Language Model using RNNs/Transformers

## Overview

This project implements a **Neural Language Model (NLM)** using **Recurrent Neural Networks (RNNs)** or **Transformers**. The model is trained on a large text corpus and evaluated based on **perplexity** and **text generation quality**.

## Features
- Implementation of a Neural Language Model
- Uses **RNNs (LSTMs/GRUs) or Transformers**
- Trained on a large text corpus
- Evaluates model performance using **perplexity**
- Generates coherent text sequences

## Dataset
The model is trained on a large text corpus, which can be sourced from:
- Wikipedia
- OpenAI GPT dataset
- Custom datasets

## Dependencies
Ensure you have the following installed:
```bash
pip install torch transformers datasets nltk
```

## Usage
### Gradio Interface
The model can be interacted with using a Gradio-based UI.
Run the following command to launch the Gradio demo:
```bash
python gradio_app.py
```
After running, open the provided link to interact with the model.

### Running the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/neural-language-model.git
   cd neural-language-model
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook I132_SLP_Assignment_1.ipynb
   ```
3. Run all cells to train and evaluate the model.

## Model Evaluation
- **Perplexity Score**: Measures how well the model predicts a sample text.
- **Generated Text**: Assesses coherence and fluency.

## Example Output
![Output Example](output_example.jpg)
```text
Input: "Artificial intelligence is"
Output: "Artificial intelligence is transforming the future of technology and human interactions."
```

## Repository Link
[GitHub Repository](https://github.com/MONISH-RAJ-T/neural-language-model.git)

## License
This project is open-source and available under the MIT License.
