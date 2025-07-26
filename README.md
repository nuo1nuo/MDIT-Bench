<div align="center">
  <h1>MDIT-Bench: Evaluating the Dual-Implicit Toxicity in Large Multimodal Models</h1>
  <span><strong><i> ⚠️ Warning: this paper includes data that maybe offensive or harmful. If you are interested in our work, please star ⭐ our project.</i></strong></span>

  <h4>  ⏬ <a href="https://huggingface.co/datasets/nuo1nuo/MDIT-Bench" target="_blank">Data</a> • 📃 <a href="https://aclanthology.org/2025.findings-acl.650/" target="_blank">Paper</a>
  </h4>
</div>

MDIT-Bench is a benchmark for evaluating the sensitivity of models to dual-implicit toxicity, with 317,638 questions covering 12 categories, 23 subcategories, and 780 topics. MDIT-Bench includes three difficulty levels, and we propose a metric to measure the toxicity gap exhibited by the model across them. Please check our [paper](https://aclanthology.org/2025.findings-acl.650/) for more details.

## News
**🎉 `2025/05/15`:** MDIT-Bench is accepted by the Findings of ACL 2025

## Data
The data is available at [huggingface](https://huggingface.co/datasets/nuo1nuo/MDIT-Bench).


## Citation
```
@inproceedings{jin-etal-2025-mdit,
    title = "{MDIT}-Bench: Evaluating the Dual-Implicit Toxicity in Large Multimodal Models",
    author = "Jin, Bohan  and
      Qi, Shuhan  and
      Chen, Kehai  and
      Guo, Xinyi  and
      Wang, Xuan",
    editor = "Che, Wanxiang  and
      Nabende, Joyce  and
      Shutova, Ekaterina  and
      Pilehvar, Mohammad Taher",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2025",
    month = jul,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.findings-acl.650/",
    pages = "12552--12574",
    ISBN = "979-8-89176-256-5",
    abstract = "The widespread use of Large Multimodal Models (LMMs) has raised concerns about model toxicity. However, current research mainly focuses on explicit toxicity, with less attention to some more implicit toxicity regarding prejudice and discrimination. To address this limitation, we introduce a subtler type of toxicity named dual-implicit toxicity and a novel toxicity benchmark termed MDIT-Bench: Multimodal Dual-Implicit Toxicity Benchmark. Specifically, we first create the MDIT-Dataset with dual-implicit toxicity using the proposed Multi-stage Human-in-loop In-context Generation method. Based on this dataset, we construct the MDIT-Bench, a benchmark for evaluating the sensitivity of models to dual-implicit toxicity, with 317,638 questions covering 12 categories, 23 subcategories, and 780 topics. MDIT-Bench includes three difficulty levels, and we propose a metric to measure the toxicity gap exhibited by the model across them. In the experiment, we conducted MDIT-Bench on 13 prominent LMMs, and the results show that these LMMs cannot handle dual-implicit toxicity effectively. The model{'}s performance drops significantly in hard level, revealing that these LMMs still contain a significant amount of hidden but activatable toxicity. The data will be released upon the paper{'}s acceptance."
}
```
