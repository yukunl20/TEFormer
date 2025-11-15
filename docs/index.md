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
<figure style="text-align:center;">
  <img src="assets/best_model.png" alt="Predicted vs. actual citation performance for 488 test papers" style="width:40%; max-width:100px;">
  <figcaption style="font-size:0.9rem; color:#666;">
    The model was tested on 488 thermoelectric papers. RMSE is computed on log(1 + citations / years since publication), normalizing for publication age. The diagonal line represents ideal prediction parity.
  </figcaption>
</figure>

---

## Latest Recommended Papers
Below are the **newest papers** predicted by TEFormer as high-impact thermoelectric studies.

These are automatically generated from the TEFormer arXiv ingestion pipeline.  
For the complete list of recommended papers, see:

👉 **[Full Recommended Papers List](papers.md)**

<!-- AUTO_UPDATE_BEGIN -->

<!-- AUTO_UPDATE_END -->

---

## Contact
Developed by [Yukun Liu](https://github.com/yukunl20).  
Feel free to open issues or contribute via pull requests!
