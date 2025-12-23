
## Supplementary Implementation

### `LLM_Nsai_sup.ipynb`

This notebook provides an alternative NSAI implementation with a stricter experimental design:
- Symbolic features are constructed **without using deposit-type labels from the target dataset**.
- Knowledge integration is performed in a label-independent manner consistent with realistic prediction scenarios.
- Model evaluation focuses on isolating the contribution of symbolic knowledge under constrained information settings.

This supplementary implementation is recommended for users interested in:
- Rigorous experimental design under label-independent settings
- Realistic model deployment scenarios
- Robust comparison between geochemistry-only and knowledge-enhanced models

---


## Requirements

Install the dependencies before running the notebooks:

Key dependencies:

Python 3.9+

Jupyter Notebook

pandas, numpy, scikit-learn
