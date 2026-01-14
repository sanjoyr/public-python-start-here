# Python – Start Here

Public Companion Repository

This repository contains the official **hands-on resources** for the book  
_Python – Start Here_.

It is designed to be used **alongside the book**, not independently.

You should always:

1. Read the book chapter
2. Open the matching notebook from `src/`
3. Work through both together

---

## Repository Structure

```

public-python-start-here/
├── data/        # All datasets (raw → staging → processed)
├── src/         # Chapter notebooks (primary working area)
├── outputs/     # Tables, figures, and generated results
├── venv/        # Local Python environment (not tracked)
├── requirements.txt
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

## How to Use This Repository

### Local Machine

1. Copy or clone this repository to your system
2. Create and activate a virtual environment (`venv`)
3. Install dependencies:

```

pip install -r requirements.txt

```

4. Launch JupyterLab and Open notebooks from `src/`

Chapter 16 of the book explains this setup step by step.

---

### Google Colab (No Local Setup)

Use this option if you cannot install Python locally.

Google Colab runs in a temporary virtual machine, so **all project files must live in Google Drive**, not in Colab’s local filesystem.

> **Important:**
> When working with notebooks stored in Google Drive, **how you open the notebook matters**.
> Opening notebooks from inside an already-running Colab session can cause Drive-sync issues.

---

#### One-Time Setup (Required Only Once)

1. Download or `git clone` this repository to your computer.

2. Upload the repository to Google Drive under the following path:

   ```text
   My Drive/DataScience/
   ```

3. **Rename the repository root folder to exactly:**

   ```text
   census-education-analysis
   ```

   This folder name is assumed by all notebooks in the book.

After this step, your project root must exist at:

```text
MyDrive/DataScience/census-education-analysis/
```

Do not move or rename this folder again.

---

#### Every Study Session (Correct Way to Open Notebooks)

**Do not start from Google Colab directly.**

Instead, always open notebooks **from Google Drive**:

1. Open **Google Drive in your browser**

2. Navigate to:

   ```text
   MyDrive/DataScience/census-education-analysis/src/
   ```

3. Right-click the chapter notebook you want to work on

4. Select:

   ```text
   Open with → Google Colaboratory
   ```

This launches Colab with:

- The correct Drive context
- Proper file permissions
- A clean link between the notebook and Drive

Once opened this way, Colab will automatically handle Drive access correctly.

---

#### Why This Works (And the Other Way Doesn’t)

- Opening Colab first and then navigating Drive from inside the VM can result in
  broken or partial Drive mounts.
- Opening the notebook **from Drive itself** ensures Colab attaches the notebook
  to Drive _before_ the runtime starts.
- This is a known Colab behavior and not related to notebook format or content.

---

#### Non-Negotiable Rules for Colab Users

- Always open notebooks via **Google Drive → Open with → Google Colaboratory**
- Never rely on Colab’s temporary filesystem
- Treat Google Drive as your permanent project workspace
- Do not move notebooks out of the project folder

Following this process guarantees that:

- Notebooks open reliably
- Paths resolve correctly
- Work is never lost
- Your workflow matches professional practice

---

## Critical Rules

- Never edit files inside `data/raw/`
- Always read data from `data/staging/`
- Write outputs only to `outputs/`
- Run the first cell of every notebook before anything else
- Do not hardcode paths

These rules are not optional. They reflect real professional practice.

---

## License

Code in this repository is released under the MIT License.
See `LICENSE` for details.

---

## Data Usage

Some datasets are derived from public government sources (including Census of India data) and are used strictly for educational purposes.

See `DATA_NOTICE.md` for full details.

---

## 5. `requirements.txt` (Minimal, Intentional)

```text
pandas
openpyxl
matplotlib
scikit-learn
```

No version pinning yet — correct for a learning repository.

---

## 6. About `venv/` (Important Rule)

You should **not commit** `venv/`.

Add this to `.gitignore` (even if not shown yet in the repo):

```text
venv/
```

This reinforces the lesson:

> environments are disposable, structure is permanent
