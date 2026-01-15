# Python – Start Here

**Public Companion Repository**

This repository contains the official **hands-on resources** for the book
**_Python – Start Here_**.

It is designed to be used **alongside the book**, not independently.

You should always:

1. Read the book chapter
2. Open the matching notebook from `src/`
3. Work through both together

---

## Repository Structure

```text
public-python-start-here/
├── data/        # All datasets (raw → staging → processed)
├── src/         # Chapter notebooks (primary working area)
├── outputs/     # Tables, figures, and generated results
├── venv/        # Local environment (not tracked, if used)
├── requirements.txt
├── Practice.md
├── LICENSE
├── DATA_NOTICE.md
└── README.md
```

### Folder Responsibilities

- **data/raw/**
  Original source files. Never edited. Never read directly in analysis.

- **data/staging/**
  Cleaned, renamed, standardized intermediate files.

- **data/processed/**
  Analysis-ready datasets reused across chapters.

- **src/**
  All chapter notebooks and scripts.

- **outputs/**
  Generated tables, charts, and reports.

---

## How This Repository Is Used in the Book

- **Chapters 1–15**
  This repository is optional. You may type code manually if you prefer.

- **From Chapter 16 onward**
  This repository becomes **mandatory**.
  All chapters assume:

  - a fixed folder structure
  - stable file paths
  - reproducible execution

Do **not** change folder names, move notebooks, or restructure files once you begin Part 2.

---

## Setup Options (Choose One)

You can use this repository in **one of two supported ways**:

1. **Local machine (Jupyter-based workflow)**
2. **Google Drive + Google Colaboratory (no local installation required)**

Both lead to the **same learning outcome**.

---

## Option 1: Local Machine (Folder-Based Workflow)

Use this option if you already have Python and Jupyter available on your system.

### Step 1: Download the Repository (ZIP Only)

1. Click **Code → Download ZIP**
2. Extract the ZIP file on your computer
3. Rename the extracted folder to exactly:

```text
census-education-analysis
```

This folder name is assumed by notebooks from **Chapter 16 onward**.

---

### Step 2: Where to Place the Folder

Place the folder anywhere convenient on your system, for example:

```text
Documents/DataScience/census-education-analysis/
```

Do not rename or move this folder after setup.

---

### Step 3: How to Start Working

1. Navigate to the `census-education-analysis/src` folder
2. Open JupyterLab or Jupyter Notebook
3. Open the required chapter notebook.

From Chapter 16 onward, **always run the first cell of every notebook before anything else**.

---

## Option 2: Google Drive + Google Colaboratory (No Local Setup)

Use this option if you cannot set up Python locally.

Google Colaboratory runs in a temporary environment, so **all project files must live permanently in Google Drive**.

---

### One-Time Setup (Required Once)

#### Step 1: Download the Repository

1. Click **Code → Download ZIP**
2. Extract the ZIP file on your computer

#### Step 2: Upload to Google Drive

1. Open **Google Drive**
2. Create this folder path if it does not exist:

```text
My Drive/DataScience/
```

3. Upload the extracted repository folder into this location
4. Rename the folder to exactly:

```text
census-education-analysis
```

Your final path must be:

```text
MyDrive/DataScience/census-education-analysis/
```

Do not rename or move this folder again.

---

### Every Study Session (Critical Rule)

**Do NOT open Google Colaboratory first.**

Always open notebooks **from Google Drive**:

1. Open **Google Drive in your browser**
2. Navigate to:

```text
MyDrive/DataScience/census-education-analysis/src/
```

3. Right-click the chapter notebook
4. Select:

```text
Open with → Google Colaboratory
```

This ensures:

- Google Drive is mounted correctly
- File paths resolve consistently
- Outputs are saved safely

---

### Why This Matters

Opening Colab first and browsing files from inside it can lead to:

- broken Drive mounts
- missing files
- lost outputs

Opening notebooks **directly from Drive** attaches the notebook to Drive **before** the runtime starts.
This is the only reliable workflow.

---

## Critical Rules (Apply Everywhere)

- Never edit files in `data/raw/`
- Always read data from `data/staging/`
- Write outputs only to `data/processed/` or `outputs/`
- Always run the **first cell** of every notebook
- Never hardcode file paths

These rules reflect **real professional practice**.

---

## License

Code in this repository is released under the **MIT License**.
See `LICENSE` for details.

---

## Data Usage

Some datasets are derived from public government sources (including Census of India data) and are used strictly for educational purposes.

See `DATA_NOTICE.md` for details.
