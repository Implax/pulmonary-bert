# Pulmonary Disease Classification using ClinicalBERT

This project fine-tunes a ClinicalBERT model on clinical notes to classify pulmonary diseases.

## How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/Implax/pulmonary-bert.git
cd pulmonary-bert

pip install -r requirements.txt
```
2. **Open the Notebook:**
After running, a Gradio web interface will launch where you can test the model by entering comprehensive clinical notes related to pulmonary conditions and diseases.

### Alternative
If you prefer not to run locally, you can test our live deployed model here:
[Pulmonary-BERT Gradio Demo on Hugging Face Spaces
](https://huggingface.co/spaces/implax/Pulmonary-BERT)

### Notes
The trained model file (trained_clinicalbert/) is not included due to GitHub file size limits.
You can retrain the model from scratch by running the notebook.


## Requirements
Python 3.8+
PyTorch
Hugging Face Transformers
Datasets
Scikit-learn
Jupyter Noteboo
