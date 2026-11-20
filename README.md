[README.md](https://github.com/user-attachments/files/35188676/README.md)
# Python for Your Thesis - companion material

Notebooks and data for the book *Python for Your Thesis: From Raw Lab Data to
Thesis-Ready Results* by Dr. Aamir Manzoor.

## Contents

- `notebooks/chapterNN.ipynb` - all code of each chapter, with empty "Your turn"
  cells for the exercises. Cells marked "shows an error on purpose" stop
  "Run all"; run the notebook cell by cell, or continue after them.
- `solutions/chapterNN_solutions.ipynb` - the answers (also printed in Appendix D).
  Each repeats the chapter's code first, so it runs on its own.
- `data/raw/` - the raw files of the pot trial, with their deliberate faults
  (pots.csv, balance.csv, lab_report.xlsx, photometer.csv). Never edit them.
- `data/clean/trial.csv` - the clean dataset produced in Chapter 14.
- `data/extra/` - plant height, weather, skylark and plate-reader data.
- `requirements.txt` - the package versions the book was tested with.

## How to run

Open the notebooks from this top folder, so that paths such as
`data/raw/pots.csv` work. In Google Colab, upload this folder to your Google
Drive and mount it (Chapter 11), or clone the repository:

    !git clone <repository URL>
    %cd <repository folder>

Locally: `python -m pip install -r requirements.txt`, then `python -m jupyterlab`.

## Data and licences

All datasets are simulated for teaching and describe no real experiment.
Code: MIT licence. Data: CC BY 4.0.
