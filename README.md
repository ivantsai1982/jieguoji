# Jieguoji – Open‑Source Pretraining Corpus & Knowledge Base

## Overview
**Jieguoji** is an open‑source corpus and knowledge base tailored for large‑scale pre‑training and advanced model fine‑tuning.  
It focuses on small and low‑resource languages, providing researchers and developers with **unused, medium‑to‑high‑quality textual data** to expand linguistic coverage and boost model performance.

> **Important:** Only *sample files* (≈ 50 MB each) are hosted here.  
> Every language offers **more than 10 million high‑quality sentences** in total.  
> File naming pattern: `sample\XX\XX_sample.jsonl` (where `XX` is the ISO language code, e.g. `sample\lo\lo_sample.jsonl`).  
> To obtain the full datasets, follow the instructions below.

---

## Why We Open‑Source
We have observed serious problems in the data market:

1. **Open data** is often resold as “commercial” products at unreasonable prices.  
2. **Commercial datasets** are diluted by intermediaries with low‑quality, noisy, or synthetic text to maximise profit.  
3. End‑users pay high fees yet receive degraded or corrupted corpora.

To counter these practices, **we open‑source a portion of our medium‑to‑high‑quality data for public benefit** while distributing premium, customised datasets only through direct collaboration.  
All data—open or commercial—undergo rigorous cleaning, deduplication, cross‑validation and human review, ensuring minimal contamination and maximal utility for modern AI systems.

---

## Data Integrity & Quality Assurance
- **Unused Sources:** Samples and full sets have *never* been used to train any publicly released model.  
- **Multi‑Stage Cleaning Pipeline:** Language detection → heuristic + statistical filtering → deduplication → rule‑ & ML‑based noise removal.  
- **Cross‑Validation:** Compared against existing corpora to eliminate overlaps, copyrighted text and synthetic fragments.  
- **Manual Spot Checks:** Native reviewers judge fluency, consistency and topical diversity on stratified samples.  
- **Continuous Monitoring:** New data follow the same pipeline; earlier versions are archived for reproducibility.

---

## How to Obtain Full Datasets or Custom Builds
1. **Email us** at **caizhiyuan88@gmail.com** with  
   • Affiliation & project description  
   • Target language(s) & volume requirements  
   • Domain or quality constraints (e.g. conversational, formal, web‑only)  
2. **Verification & Agreement** – we review requests for ethical use and may issue a lightweight data‑use agreement.  
3. **Delivery** – secure download links (Google Drive, S3, or another endpoint) will be provided.  
   We also offer **paid custom corpora** (domain‑specific, style‑filtered, balanced, etc.) with transparent pricing.

---

## License (Samples Only)
The sample files in this repository are released under the  
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.  
You may **share** and **adapt** the sample data for any purpose, including commercial, provided proper attribution is given.  
Full datasets shared privately may be subject to separate terms.

---

## Contributing
We **do not accept external data contributions**.  
You are welcome to open issues for bug reports, quality feedback or language requests.

---

## Contact
- **Email:** caizhiyuan88@gmail.com  
- **GitHub Issues:** use the issue tracker for public questions.

---

### Our Commitment
We believe **high‑quality, transparent data** is the foundation of trustworthy AI.  
By freely releasing verified samples and distributing premium datasets directly—without exploitative middlemen—we aim to foster fair, effective, and **fraud‑free** data practices for the global AI community.

*Thank you for choosing Jieguoji. Together, let’s advance multilingual AI for everyone.*

