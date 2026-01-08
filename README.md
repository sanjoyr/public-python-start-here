# 📘 public-python-start-here

**Companion Code & Data Repository for the book _Python – Start Here_**

This repository contains **public learning resources** that accompany the book
**_Python – Start Here_**.

It is intended for **readers, learners, and practitioners** who want to:

- Run the example code used in the book
- Work with the same datasets referenced in chapters
- Practice Python, SQL, and data analysis workflows hands-on

---

## 🎯 Purpose of This Repository

This repository exists to provide:

- ✅ **Executable code examples**
- ✅ **Sample datasets and input files**
- ✅ **Chapter-wise learning resources**
- ✅ **Reproducible practice material**

It is **not** the book itself.

> 📌 **The book text, manuscripts, translations, and publishing workflow live in a separate private repository.**

---

## 🧭 How This Repository Is Used

- This repository is added as a **git submodule** inside the private book repository
- All updates are made **from within that private repository**
- Each book edition references a specific commit of this repo
- This guarantees **reproducibility** and **version stability** for readers

Readers can clone or download this repository independently to follow along.

---

## 📂 Repository Structure (Overview)

```
public-python-start-here/
├── README.md
├── LICENSE
├── DATA_NOTICE.md
│
├── assets/              # Shared assets (images, inputs, etc.)
│
├── chapters/            # Chapter-wise resources
│   ├── 101_intro/
│   │   ├── code/
│   │   ├── data/
│   │   └── README.md
│   ├── 201_data-types/
│   └── ...
│
├── setup/               # Environment setup
│   ├── requirements.txt
│   ├── environment.yml
│   └── README.md
│
└── versions/            # Optional version snapshots
```

Each chapter folder corresponds to a chapter in the book and contains:

- Code examples
- Input datasets
- Notes on how to run the examples

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/sanjoyr/public-python-start-here.git
cd public-python-start-here
```

### 2️⃣ Set up Python environment

See:

```
setup/README.md
```

Typically:

```bash
pip install -r setup/requirements.txt
```

or:

```bash
conda env create -f setup/environment.yml
```

### 3️⃣ Navigate to a chapter

```bash
cd chapters/101_intro/code
python example.py
```

---

## 📜 License & Usage (IMPORTANT)

### Code License

> **Code examples in this repository are licensed under the MIT License.**

You are free to:

- Use
- Modify
- Share
- Reuse
- Incorporate into projects (including commercial ones)

See `LICENSE` for full text.

---

### Data Usage Notice (VERY IMPORTANT)

> **Datasets in this repository are subject to their original source terms.**

Some datasets included here are derived from **publicly available government data**, including:

- **Census of India**
  Office of the Registrar General & Census Commissioner, India
  [https://censusindia.gov.in/](https://censusindia.gov.in/)

Key points:

- Ownership of Census data remains with the **Government of India**
- Data is used **only for educational and illustrative purposes**
- Modified or processed datasets are **not official publications**

📄 **See `DATA_NOTICE.md` for full details and attributions.**

---

## ⚠️ What This Repository Does NOT Contain

- ❌ Book text or chapters
- ❌ Manuscripts or translations
- ❌ Publishing templates
- ❌ Private scripts or workflows
- ❌ Any proprietary book content

Those are intentionally kept separate.

---

## 🔁 Versioning & Book Editions

- Book editions reference a specific commit or tag of this repository
- Tags (e.g. `v1.0`, `v1.1`) may be used to align with book editions
- Readers are encouraged to use the version matching their book edition

---

## 👤 Maintainer

**Sanjoy Roy**

This repository is maintained as part of an educational book series and may evolve over time to improve clarity, examples, and learning outcomes.

---

## ✅ One-Line Summary (Bookmark This)

> **This repository provides open, reusable code and datasets for readers of _Python – Start Here_, licensed under MIT for code and respecting original data source rights.**

---
