# Digital Literacy & Cyber Safety Analytics — Keemti Kushwah

**Student:** Keemti Kushwah  
**Roll Number:** 24118187  
**Course:** Bachelor of Arts (BA)  
**College:** Government P.G. College, Dholpur  
**University:** Maharaja Surajmal Brij University

## Project overview
This project demonstrates a Python data analytics workflow about online-safety practices and digital literacy in a student-like context. It includes data-quality checks, exploratory analysis, visualisations, a simple derived practice score, and a logistic-regression classification demonstration.

> **Data transparency:** `digital_literacy_cyber_safety_dataset.csv` is a synthetic educational dataset generated for this project. It is not collected from real students and cannot support empirical claims about a real college or population. The model is for instructional demonstration, not real student screening or decision-making.

## Files
- `KeemtiKushwah_Digital_Literacy_Analytics.ipynb` — runnable notebook.
- `digital_literacy_cyber_safety_dataset.csv` — 1,500 synthetic records and 19 columns.
- `requirements.txt` — Python dependencies.
- `KeemtiKushwah_ProjectReport.docx` — full report.

## Run locally
1. Keep the notebook and CSV in the same directory.
2. Create a virtual environment if desired.
3. Install dependencies:
   ```bash
   python -m pip install -r requirements.txt
   ```
4. Open the notebook in Jupyter Notebook/JupyterLab and run cells from top to bottom.

## Dataset fields
There are 19 columns: record ID, age, gender, course, study year, residence type, device access, daily internet hours, digital-payment use and frequency, awareness of cybercrime helpline 1930, five safety practices, derived safety score, derived awareness group, and preferred learning channel.

## Score definition
`Safety_Practice_Score` sums five Yes/No practices (strong unique passwords, two-factor authentication, phishing recognition, app-permission review, privacy-setting review) and ranges from 0 to 5. `Safety_Awareness_Level` is `Higher awareness` when the score is at least 3 and `Needs support` otherwise. This is an instructional definition, not a validated instrument.

## Suggested GitHub repository
`KeemtiKushwah_Digital_Literacy_Cyber_Safety_Analytics`

## Limitations and ethical note
Synthetic observations can have patterns caused by the generator. Do not present them as actual survey results. A real study should use an appropriate sampling plan, institutional approval if required, informed consent, data minimisation, privacy safeguards, and a documented retention policy. Check current official guidance before sharing real cybercrime-reporting instructions.

## Further reading
- National Cyber Crime Reporting Portal: https://cybercrime.gov.in/
- CERT-In: https://www.cert-in.org.in/
- Reserve Bank of India: https://www.rbi.org.in/
- UNESCO Media and Information Literacy: https://www.unesco.org/en/media-information-literacy
- pandas: https://pandas.pydata.org/docs/
- scikit-learn: https://scikit-learn.org/stable/user_guide.html
