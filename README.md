# Human Value Detection
Exam project for the information retrieval course.
Project report [here](https://github.com/antoniobelotti/HVD/blob/main/inforet_Belotti_960822.pdf).

[SemEval task 4: human value detection.](https://touche.webis.de/semeval23/touche23-web/) 
Given a textual argument and a human value category, classify whether or not the argument draws on that category. 

**Notebooks content:**
1. datasets:
    - Explore the original dataset.
    - Augment using masking, back-translation, and summarization.
    - Encode all datasets using DistilBERT.
2. Compare DistilBERT-based classifier performances: using only the premise vs. Premise, stance, and conclusion.
3. Compare DistilBERT-based classifier on the original dataset vs. augmented datasets.
4. scikit-learn classifiers.
5. Other transformers-based model: DeBerta, Roberta, XLnet.
6. Ensemble transformer models.
