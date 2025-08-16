# 🔎 LinkedIn Job Scraper

Automate LinkedIn job searches with filters and export results in **CSV/JSON** for easy analysis.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-3670A0?style=for-the-badge&logo=python&logoColor=yellow" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" />
  <a href="https://github.com/Hemant-Karpe-777/LinkedIn-Job-Scraper/stargazers">
    <img src="https://img.shields.io/github/stars/Hemant-Karpe-777/LinkedIn-Job-Scraper?style=social" />
  </a>
</p>

---


<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-3670A0?style=for-the-badge&logo=python&logoColor=yellow" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" />
  <a href="https://github.com/Hemant-Karpe-777/LinkedIn-Job-Scraper/stargazers">
    <img src="https://img.shields.io/github/stars/Hemant-Karpe-777/LinkedIn-Job-Scraper?style=social" />
  </a>
</p>

---

## 📌 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Tech Stack](#tech-stack)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License & Contact](#license--contact)

---

## 📖 Overview
**LinkedIn Job Scraper** is a Python-based automation tool that helps you search LinkedIn job postings by **keywords** and **locations**.  
You can apply filters such as **date posted, remote/on-site, and experience level**.  
Results are exported in **CSV** or **JSON** formats for further analysis.

---

## ✨ Features
- Search jobs with **keywords & location**
- Apply filters:
  - 📅 Date posted  
  - 🌍 Remote / On-site  
  - 🎯 Experience level
- Extract job details: **title, company, location, date, job link**
- Export results as **CSV/JSON**
- Run via **scripts** or **Jupyter notebooks**

---

## 🎥 Demo
Add screenshots or sample outputs here:  
- Example notebook: `notebook/example_usage.ipynb`  
- Sample outputs available in `output/`

---

## ⚙️ Tech Stack
- **Python 3.8+**  
- **Libraries:** Selenium / BeautifulSoup / Pandas (depending on implementation)  
- **Interface:** Jupyter Notebooks  
- **Output:** CSV & JSON  

---

## 📂 Repository Structure


## ⚡ Installation

1. Clone the repo  
   ```bash
   git clone https://github.com/Hemant-Karpe-777/LinkedIn-Job-Scraper.git
   cd LinkedIn-Job-Scraper

2. (Optional) Create virtual environment

python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


3. Install dependencies

pip install -r requirements.txt


---

---

## 🚀 Usage

Run via Script

python src/scraper.py \
  --keywords "Data Analyst" \
  --location "Mumbai, India" \
  --date_posted "Past 7 days" \
  --experience "Entry level" \
  --remote_only True \
  --output-format csv \
  --output-file results.csv

Run via Jupyter Notebook

- 1. Open notebook/example_usage.ipynb
- 2. Set search parameters
- 3. Run all cells
- 4. Check results in output/




---

## 🤝 Contributing

Contributions are welcome! 🎉

Fork the repo

Create your feature branch (git checkout -b feature/YourFeature)

Commit your changes (git commit -m 'Add feature')

Push to the branch (git push origin feature/YourFeature)

Open a Pull Request



---

## 📜 License & Contact

This project is under the MIT License.

### 👤 Author: Hemant Karpe
📧 hemant777.karpe@gmail.com

- 🔗 LinkedIn
- 🖥 GitHub
