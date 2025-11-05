# TEFormer

Welcome to the **TEFormer** project!

TEFormer is a domain-specific transformer model designed for the thermoelectric materials research community.  
It automatically ingests new papers from arXiv, predicts their potential citation impact, and recommends emerging studies. 
Trained on thousands of arXiv publications using a custom BPE tokenizer and BERT encoder, it estimates log-normalized citation rates and classifies papers as “read” or “skip.” Deployed as an automated arXiv Evaluation API, it enables daily, data-driven literature triage. TEFormer improves RMSE over baseline models and quantifies researcher time savings. Future work includes expanding to other domains, integrating Large Language Models (LLMs) for enhanced reasoning, and building knowledge graphs to reveal emerging scientific connections.

---

## Features
- Automated arXiv paper ingestion  
- Citation impact prediction  
- High-impact paper recommendations  

---

## Model Test Results: Citation Prediction
<img src="assets/best_model.png" alt="TEFormer citation prediction results (test set) — scatter of predicted vs. actual citations" width="400">

---

## Contact
Developed by [Yukun Liu](https://github.com/yukunl20)  
Feel free to open issues or contribute via pull requests!

