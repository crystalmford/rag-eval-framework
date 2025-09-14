# RAG Evaluation Framework

**Author:** Crystal M. Ford  
**Target Role:** Data Scientist II — Microsoft M365 Core  

This notebook demonstrates a lightweight evaluation framework for Retrieval-Augmented Generation (RAG) systems.  
It measures:

- Retrieval accuracy (precision@k)
- Answer quality (semantic similarity to reference answers)
- Hallucination risk (faithfulness to retrieved context and IDK rate)

The framework uses FAISS for meaning-based retrieval, FLAN-T5 for answer generation, and a custom evaluation pipeline with automated metrics and visual reporting.

---

## How to View

- **Notebook (GitHub):** [evalforge_clean.ipynb](./evalforge_clean.ipynb)  
- **nbviewer (rendered view):** <ADD_YOUR_NBVIEWER_LINK_HERE>  
- **PDF work sample:** Included with job application
