<div align="center">

# Laura Ortega

**Machine Learning & AI Engineer · Python · Applied AI**

📍 Barcelona (open to remote) &nbsp;|&nbsp; ✉️ [laura.ortega.garre@gmail.com](mailto:laura.ortega.garre@gmail.com) &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/laura-ortega-338014357/) &nbsp;|&nbsp; [Website](https://lauraortegagarre.com/)

</div>

---

### About me

Machine learning and AI engineer in career transition from professional music and research. I build supervised, unsupervised and deep learning models, NLP pipelines with transformers and local LLMs, and machine learning for audio and EEG, with research-grade evaluation: leakage checks, piece-wise and temporal validation, permutation tests and honest reporting of limitations.

Currently completing the **Data Science with Machine Learning & AI Career Accelerator — University of Cambridge PACE**.

Background: Título Superior in Piano Performance (Musical Arts, Madrid, GPA 9/10), Master's in Advanced Artistic Studies in Flamenco — Flamenco Piano (ESMUC, GPA 9.5/10) and Master's in Neuromusic (UCAM, 60 ECTS). That domain knowledge shapes my research interest: machine learning for audio, music and the listening brain.

### Technical skills

- **Machine learning** — scikit-learn, XGBoost, PyTorch, Keras, transfer and metric learning, clustering, sequence models (GRU), cross-validation and model evaluation
- **NLP & LLMs** — BERTopic, LDA (Gensim), Hugging Face transformers, sentence-transformers, local LLM inference (Ollama, LM Studio), prompt engineering
- **Audio & EEG** — librosa, OpenL3, audio embeddings, MFCC, chroma, F0, spectral features, MNE-Python
- **Data** — Python, pandas, NumPy, SQL, PostgreSQL, PCA, t-SNE, UMAP, HDBSCAN, statistics
- **Engineering** — Flask, REST APIs, Pydantic, Docker and docker-compose, Git/GitHub, GitHub Actions CI, pytest, ruff, mypy, Celery, Redis, Streamlit

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black" alt="Hugging Face"/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white" alt="pandas"/>
<img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git"/>
</p>

### Featured projects

**Applied machine learning** (University of Cambridge coursework)

- 🎓 **Student dropout prediction** — XGBoost and a neural network on 25,059 students across three information stages. Traced a too-good stage-3 score (ROC-AUC 0.993) to leakage from imputed records; on the students still on course, the model finds 105 of 136 future dropouts (ROC-AUC 0.977). A temporal split gave ROC-AUC 0.891 / 0.904 / 0.980 and changed the recommended operational use. *Report not public.*
- 💬 **Customer review topic analysis** — tens of thousands of reviews from two platforms for a UK fitness chain (client under NDA). Compared BERTopic, transformer-based emotion classification, LDA tuned on c_v coherence and a local LLM (phi4-mini via Ollama) for theme labelling, consolidated into 20 themes; results reported as rates with minimum-volume thresholds. *Code not public (NDA).*
- 🔍 **[customer-segmentation-clustering](https://github.com/1lauraog15-cloud/customer-segmentation-clustering)** — 68,300 customer profiles built from 951,668 e-commerce transactions; K-Means (k = 5, silhouette peak; Davies-Bouldin marginally favoured k = 6), Ward hierarchical clustering, PCA and t-SNE, translated into a marketing strategy.

**Audio, music and the brain** (personal research)

- 🧠 **surprisal-eeg** *(in progress, code on request)* — does note-level musical surprise explain EEG responses to Bach? 24 GRU sequence models in PyTorch, temporal response functions in MNE with cross-validation nested by piece. Pitch surprisal from the augmented GRU improved EEG prediction in 16 of 20 listeners (Cohen's d = 1.15), more than IDyOM or IDyOMpy, and held across seeds; the rhythm result did not, and is reported as such.
- 🎸 **[flamenco-classifier](https://github.com/1lauraog15-cloud/flamenco-classifier)** — classification of four flamenco *palos* (soleares, seguiriyas, bulerías, alegrías) from audio, with features grounded in music theory: Phrygian mode and the Andalusian cadence, position of the metric close within the 12-beat compás. Random Forest, cross-validated **F1-macro 0.645 ± 0.115**. [**Live demo**](https://flamenco-palo-classifier.streamlit.app/) — upload a track and get the predicted palo with its probabilities.
- 🎤 **[cante-embeddings](https://github.com/1lauraog15-cloud/cante-embeddings)** — embeddings of a *cantaor*'s identity (who is singing, not which palo) from 109 recordings, built with a 512-256-128 triplet-loss projection head on pretrained OpenL3 features. Closed-set pairwise verification: **AUC 0.80**, with the dataset confound and small-sample limitations documented.

**Engineering**

- ✈️ **[disruption-api](https://github.com/1lauraog15-cloud/disruption-api)** — backend project modelled on an airline operations control centre (synthetic data): Flask REST API with Pydantic validation and API-key auth, SQLAlchemy 2.0 on PostgreSQL with Alembic migrations, a Celery worker that propagates delays along an aircraft rotation, Docker Compose, 96 pytest tests at 99% coverage and a GitHub Actions pipeline with an end-to-end run of the full stack.

---

<div align="center">
<sub>Open to machine learning and AI roles, and to PhD positions in machine learning for audio — let's connect on <a href="https://www.linkedin.com/in/laura-ortega-338014357/">LinkedIn</a>.</sub>
</div>
