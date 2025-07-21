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

---

> **重要声明（中文）**
> 我们深耕人工智能训练数据行业已整整十年，从未招摇，却始终稳稳地为无数科研与商业项目提供高质量语料，默默支撑了大模型与 AI 生态的飞速发展。遗憾的是，行业里某些中间商却不思进取，以次充好、反复倒卖、甚至掺杂伪造与垃圾数据牟取暴利；出了问题便把责任一推了之，丝毫没有应有的担当，更无最起码的商业伦理可言！
> **从今日起，我们将陆续公开大量中高质量文本数据样例，供公益与学术界免费使用。** 所有开源数据均已嵌入不可见且不影响训练效果的“无痕水印”——既保证数据纯净，不会污染模型，也能在必要时溯源取证。任何机构或个人若胆敢将本项目开放数据打包高价售卖，我们保留一切法律追责的权利。
> 请记住：我们开源，是为了科技向善，而不是让投机者再次把公开资源裹上糖衣卖给真正需要的人。质量，我们已经替你们把关；良心，希望你们自己守住！


