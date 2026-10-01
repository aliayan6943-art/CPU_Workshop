# CPUR Agentic AI Learning Archive

A working record of an Agentic AI in-house internship at Career Point University. This repository brings together dated Python lessons, Jupyter notebooks, data-analysis exercises, cleaned datasets, machine-learning experiments, and personal NumPy practice.

It is a learning archive rather than one installable application. Each folder may have different notebooks, data files, assumptions, and dependencies. Start with the README closest to the material you want to run.

## What is here

The material follows a practical progression:

1. Python foundations and problem-solving
2. NumPy, Pandas, and visualization
3. Exploratory analysis using real datasets
4. Introductory machine-learning projects
5. Personal practice notebooks and experiments

The repository is intentionally hands-on. Some notebooks are polished demonstrations, while others are working notes or experiments with names such as `Untitled.ipynb`.

## Repository map

| Location | Contents |
| --- | --- |
| [`01_Phase/`](./01_Phase/) | Python fundamentals from Day 1 to Day 5: syntax, operators, loops, data structures, functions, recursion, generators, and file handling. |
| [`02_Phase/`](./02_Phase/) | NumPy, Pandas, Matplotlib, data loading, exploratory analysis, capstone work, and introductory ML from Day 6 to Day 14. |
| [`03_Phase/`](./03_Phase/) | Later experiments, including a Day 17 notebook and house-model work. |
| [`CLEAN_DATASETS/`](./CLEAN_DATASETS/) | Cleaned CSV files prepared for analysis and model notebooks. |
| [`ML_MODELS/`](./ML_MODELS/) | Notebook-based prediction and analysis projects across several domains. |
| [`NUMPY_PRACTICE_BY_ME/`](./NUMPY_PRACTICE_BY_ME/) | Independent NumPy practice notebooks and saved `.npy` arrays. |

## Learning route

### Phase 1: Python foundations

| Day | Focus | Open |
| --- | --- | --- |
| 1 | Python introduction, variables, types, input/output, and basic inspection | [`01_Day_10-06-2026`](./01_Phase/01_Day_10-06-2026/) |
| 2 | Operators, type conversion, formatting, and introductory collections | [`02_Day_11-06-2026`](./01_Phase/02_Day_11-06-2026/) |
| 3 | Loops, nested loops, patterns, and a cricket score analyzer | [`03_Day_12-06-2026`](./01_Phase/03_Day_12-06-2026/) |
| 4 | Lists, tuples, sets, frozensets, dictionaries, indexing, and copying | [`04_Day_13-06-2026`](./01_Phase/04_Day_13-06-2026/) |
| 5 | Functions, lambda expressions, recursion, generators, and file handling | [`05_Day_15-06-2026`](./01_Phase/05_Day_15-06-2026/) |

Each day includes a local `Readme.md` with the most specific notes and links for that lesson.

### Phase 2: Data work and machine learning

| Day | Focus | Open |
| --- | --- | --- |
| 6 | Data-science lifecycle and NumPy arrays, broadcasting, slicing, and aggregation | [`06_Day_16-06-2026`](./02_Phase/06_Day_16-06-2026/) |
| 7 | NumPy revision, Pandas Series/DataFrames, filtering, sorting, and selection | [`07_Day_17-06-2026`](./02_Phase/07_Day_17-06-2026/) |
| 8 | Loading CSV, Excel, JSON, TSV, XML, HTML, and SQL data; Matplotlib charts | [`08_Day_18-06-2026`](./02_Phase/08_Day_18-06-2026/) |
| 9 | Matplotlib practice notebooks | [`09_Day_19-06-2026`](./02_Phase/09_Day_19-06-2026/) |
| 10 | House, student, mall-customer, and Netflix analysis | [`10_Day_20-06-2026`](./02_Phase/10_Day_20-06-2026/) |
| 11 | IPL analysis and capstone work | [`11_Day_22-06-2026`](./02_Phase/11_Day_22-06-2026/) |
| 12 | House-sales and student-marks ML practice | [`12_Day_23-06-2026`](./02_Phase/12_Day_23-06-2026/) |
| 13 | COVID, credit score, Iris, loan approval, sample-data, and World Cup prediction | [`13_Day_24-06-2026`](./02_Phase/13_Day_24-06-2026/) |
| 14 | Additional notebook experiments | [`14_Daya_25-06-2026`](./02_Phase/14_Daya_25-06-2026/) |

The spelling `14_Daya_25-06-2026` is retained because it is the existing folder name.

### Phase 3: continuing experiments

The current Phase 3 folder contains:

- [`17_Day_30-06-2026.ipynb`](./03_Phase/17_Day_30-06-2026.ipynb)
- [`house ai model.ipynb`](./03_Phase/house%20ai%20model.ipynb)
- [`Untitled.ipynb`](./03_Phase/Untitled.ipynb)

These are best treated as ongoing experiments; use the notebook cells themselves as the source of truth for their current workflow.

## Datasets

The shared dataset collection is in [`02_Phase/DataSet/`](./02_Phase/DataSet/). It includes material for Titanic, IPL, World Cups, Netflix, mall customers, house prices, Iris, student marks, loan approval, COVID, FIFA players, and education analysis, along with additional CSV, Excel, image, and Titanic files.

Reusable cleaned files are grouped in [`CLEAN_DATASETS/`](./CLEAN_DATASETS/):

- COVID-19
- IPL
- Iris
- house sales
- loan approval
- student marks
- practice data

Dataset filenames and notebook expectations are not completely standardized. If a notebook reports a missing file, check its local `DataSet` folder and the shared `02_Phase/DataSet` folder before changing code.

## Machine-learning notebooks

[`ML_MODELS/`](./ML_MODELS/) collects focused notebooks for:

- COVID-19 prediction
- house-price prediction
- mall-customer analysis
- Netflix analysis
- credit-score prediction
- FIFA player prediction
- IPL prediction
- Iris prediction
- student-marks prediction
- Titanic analysis and prediction

The notebooks demonstrate introductory workflows using techniques such as linear regression, logistic regression, and decision trees. They are study material, not production-ready model packages; results depend on preprocessing, dataset versions, and the environment used to run them.

## NumPy practice

[`NUMPY_PRACTICE_BY_ME/`](./NUMPY_PRACTICE_BY_ME/) contains four practice notebooks and saved arrays:

- `phase-1.ipynb` through `phase4.ipynb`
- `array1.npy`, `array2.npy`, `array3.npy`, and `numpy-logo.npy`
- [`requirements.txt`](./NUMPY_PRACTICE_BY_ME/requirements.txt)

That requirements file belongs to this practice area. It is not a repository-wide dependency lockfile.

## Getting started

There is no single root-level install command, `pyproject.toml`, or shared environment for the archive. A practical setup is:

```powershell
cd CPUR-Agentic-AI-main
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install jupyter numpy pandas matplotlib scikit-learn openpyxl
jupyter notebook
```

On macOS or Linux, activate the environment with `source .venv/bin/activate`. Add other packages only when the selected notebook requires them. For the NumPy practice folder, prefer its local `requirements.txt` when reproducing that specific environment.

### Running a notebook

1. Choose a day, dataset, or model from the map above.
2. Read the nearest local README.
3. Open the notebook in Jupyter or VS Code.
4. Check dataset paths near the first data-loading cells.
5. Run cells from top to bottom and keep generated outputs local.

Google Colab links, where present, are supplementary classroom material. They may use paths or files that are not identical to this checkout.

## Project boundaries and maintenance notes

- Notebook names and folder capitalization are preserved to avoid breaking existing links.
- Several notebooks are exploratory or unnamed, so their current cells are more reliable than a title-based description.
- Checkpoint folders and generated notebook output may be present; they are not learning prerequisites.
- Do not commit API keys, passwords, private student information, or machine-specific paths.
- Verify dataset redistribution rights and retain attribution for external material.
- Before sharing results, record the dataset, preprocessing choices, model assumptions, and relevant package versions.

## Contributing to the archive

Small, focused improvements are welcome: clearer notebook names, corrected paths, local READMEs, reproducible examples, cleaned outputs, and documented datasets. For a new topic or project, include:

- a short purpose statement;
- prerequisites and verified run steps;
- links to the relevant data and notebook;
- expected output or limitations; and
- attribution or licensing information where applicable.

Keep substantial projects in their own folder and update the nearest map or README when adding a new learning area. This repository currently has no root-wide license declaration, so confirm that you have permission to share code, datasets, images, and course material before contributing.

## Acknowledgement

This archive records coursework and practice from the Career Point University Agentic AI in-house internship. Instructor notes and external resources remain subject to their original ownership and terms.
#   C P U _ W o r k s h o p  
 #   C P U _ W o r k s h o p  
 #   C P U _ W o r k s h o p  
 