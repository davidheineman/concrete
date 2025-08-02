Replication of [Data-driven material screening of secondary and natural cementitious precursors](https://www.nature.com/articles/s43246-025-00820-4) (Nature Communications, 2025)

### Setup

```
pip install -r requirements.txt
```

### Dataset Description

- DATASET 1: Literature Mining Dataset
    - Extracted chemical compositions and material types for over 14,000 cementitious materials from 4312 academic papers using fine-tuned large language models (LLMs), forming the foundation for mapping reactivity variations.

- DATASET 2: Fine-tuning Table Extraction Dataset
    - Manually curated dataset of 200 tables used to fine-tune large language models for accurate extraction sof chemical compositions and material names from academic paper tables.

- DATASET 3: Fine-tuning Material Type Extraction Dataset
    - Manually curated dataset of 200 material descriptions used to fine-tune large language models for hierarchical classification of materials into 19 predefined cementitious material types.

- DATASET 4: R³ Test Dataset
    - Compilation of 318 materials and 1,850 experimental data points from R³ tests (heat release, Ca(OH)₂ consumption, bound water), used to train machine learning models for reactivity prediction.

- DATASET 5: Amorphous Content of Rocks Dataset
    - Literature-collected dataset of ∼160 natural rock samples with measured amorphous contents,supporting imputation and reactivity prediction for natural cementitious precursors.
