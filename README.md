# static

## Requirements

- Python 3.11 (notebooks were last run with 3.11.14)
- Jupyter Notebook or JupyterLab
- Google Cloud credentials configured for services used by the notebooks

## Setup

1. Create and activate a virtual environment.
2. Install required packages:

   ```bash
   pip install jupyter ipython google-cloud-storage
   ```

## Testing

This repository uses notebook-based end-to-end checks instead of a pytest suite.

1. Start Jupyter:

   ```bash
   jupyter notebook
   ```

2. Open and run all cells in `story_generation_e2e_demo.ipynb`.
3. Confirm the notebook completes without errors and ends with a success message.
4. Open and run all cells in `tts_e2e_demo.ipynb`.
5. Confirm the notebook completes without errors and ends with a success message.