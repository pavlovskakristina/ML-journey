# ML Journey — Kristina Pavlovska

> Roadmap od zera do stażu ML/Data Science w 8 miesięcy  

---

## O mnie

Studentka II roku Telekomunikacji na Politechnice Wrocławskiej.

**Stack wejściowy:** Python · Pandas · NumPy · React/TypeScript · Linux · Git   
**Stack docelowy:** scikit-learn · PyTorch · XGBoost · HuggingFace · FastAPI · Streamlit · Docker · SQL

---

## Postęp

| Faza | Temat | Status | Projekty |
|------|-------|--------|----------|
| Faza 1 | Fundamenty ML | 🔄 W trakcie | Titanic pipeline |
| Faza 2 | Modele i ewaluacja | ⏳ Planowana | Anomaly detection, Churn |
| Faza 3 | Deep Learning + NLP | ⏳ Planowana | CNN, AIOps NLP |
| Faza 4 | Deployment + rekrutacja | ⏳ Planowana | FinMind+ML, aplikacje |

---

## Faza 1 — Fundamenty ML (maj–czerwiec 2026)

**Czas:** 8 tygodni · ~46h łącznie · 6h/tydzień

### Umiejętności

- Pełny ML pipeline: EDA → feature engineering → model → ewaluacja
- scikit-learn: Pipeline, ColumnTransformer, GridSearchCV, cross-validation
- Klasyfikacja: DecisionTree, LogisticRegression
- Regresja: LinearRegression, Ridge, Lasso
- Metryki: accuracy, precision, recall, F1, MAE, RMSE, R²
- Wizualizacja: Matplotlib, Seaborn
- Interpretowalność: SHAP values

### Plan tygodniowy

| Tydzień | Daty | Temat | Godziny |
|---------|------|-------|---------|
| 1 | 5–9 maj | Środowisko + Python recap | 6h |
| 2 | 12–16 maj | Pandas i EDA — Titanic | 6h |
| 3 | 19–23 maj | Pierwszy model — klasyfikacja | 6h |
| 4 | 26–30 maj | Regresja — ceny mieszkań | 5h |
| 5 | 2–6 cze | Cross-validation i hiperparametry | 6h |
| 6 | 9–13 cze | Sesja letnia (min. 2h) | 2h |
| 7 | 16–20 cze | Sesja letnia (min. 2h) | 2h |
| 8 | 23–27 cze | Projekt #1 — Titanic finale + GitHub | 7h |

### Materiały

- **Kurs Udemy:** Python for Data Science · ML Fundamentals · Regression · Model Evaluation (wybrane sekcje, ~8–10h)
- **StatQuest (YouTube):** Decision Trees · Logistic Regression · Linear Regression · Ridge/Lasso · Cross-Validation
- **Kaggle Learn:** Intro to ML · Intermediate ML
- **Dokumentacja:** scikit-learn Getting Started · Seaborn gallery · SHAP docs

### Projekt #1 — Titanic Survival Prediction

**Cel:** accuracy >79% (cross-validated)  
**Technologie:** Pandas · scikit-learn Pipeline · GridSearchCV · SHAP  
**Elementy:**
- EDA z wizualizacją (5+ wykresów)
- Feature engineering: tytuły z imion, FamilySize, IsAlone
- Pipeline: ColumnTransformer + Imputer + Encoder + Classifier
- GridSearchCV z cross-validation
- SHAP waterfall plot — interpretowalność modelu

---

## Faza 2 — Modele i ewaluacja (lipiec–sierpień 2026)

**Czas:** 8 tygodni · ~54h łącznie · 7h/tydzień (wakacje)

### Umiejętności

- Ensemble: RandomForest, GradientBoosting, XGBoost
- Unsupervised: K-Means, DBSCAN, PCA
- SQL dla Data Science: window functions, sqlalchemy
- Niezbalansowane dane: SMOTE, class\_weight
- MLflow: experiment tracking

### Projekty

**Projekt #2 — Anomaly Detection w sieci**
- Dataset: KDD Cup 1999 / NSL-KDD (network intrusion)
- Model: Isolation Forest + K-Means
- Kontekst: zastosowanie w telekomunikacji i cybersecurity
- Metryki: Precision@k, confusion matrix dla niezbalansowanych klas

**Projekt #3 — Telco Churn Prediction**
- Dataset: IBM Telco Customer Churn (Kaggle, 7k rekordów)
- Model: XGBoost + SHAP values
- Business framing: ROI retencji klientów, cost of misclassification
- Output: Notebook + 1-stronowy summary PDF

---

## Faza 3 — Deep Learning + NLP (wrzesień–październik 2026)

**Czas:** 8 tygodni · ~52h łącznie · 6h/tydzień

### Umiejętności

- PyTorch: tensors, autograd, training loop
- CNN: Conv2d, MaxPool, BatchNorm, transfer learning (ResNet)
- NLP: tokenizacja, transformers (intuicja), HuggingFace pipeline
- Fine-tuning: DistilBERT na własnych danych
- Docker basics: Dockerfile dla aplikacji ML

### Projekty

**Projekt #4 — CNN klasyfikacja usterek sprzętowych**
- Dataset: MVTec Anomaly Detection
- Model: ResNet18 fine-tuned + Grad-CAM wizualizacja
- Demo: Streamlit app — upload zdjęcia → predykcja
- Kontekst: Quality Assurance w telco/hardware (Nokia I&T)

**Projekt #5 — AIOps: NLP na logach sieciowych**
- Dataset: Loghub (github.com/logpai/loghub)
- Task: klasyfikacja zdarzeń + anomaly detection
- Model: DistilBERT fine-tuned lub TF-IDF + LogReg baseline
- Kontekst: ML dla operacji sieciowych (AIOps)

---

## Faza 4 — Deployment i rekrutacja (listopad 2026–styczeń 2027)

**Czas:** 8 tygodni · aktywna rekrutacja

### Umiejętności

- FastAPI: REST endpoint dla modelu ML (/predict)
- Streamlit: aplikacje demo
- Docker: konteneryzacja pipeline'u ML
- Time series: Prophet / LSTM

### Projekt #6 — FinMind + ML (projekt flagowy)

Rozszerzenie istniejącej aplikacji osobistych finansów (React/TypeScript/Vite) o backend ML:
- Model: Prophet / LSTM do prognozowania miesięcznych wydatków
- Architektura: FastAPI backend → React frontend → Recharts wizualizacja
- Full-stack: jedyny projekt łączący frontend i ML w portfolio


## Portfolio — projekty do oddania

| # | Projekt | Technologie | Status |
|---|---------|-------------|--------|
| 1 | Titanic Survival Prediction | sklearn · SHAP · Pipeline | 🔄 W trakcie |
| 2 | Network Anomaly Detection | Isolation Forest · KDD Cup | ⏳ Planowany |
| 3 | Telco Churn Prediction | XGBoost · SHAP · IBM dataset | ⏳ Planowany |
| 4 | CNN Defect Detection | PyTorch · ResNet · Streamlit | ⏳ Planowany |
| 5 | AIOps NLP Log Analysis | HuggingFace · DistilBERT | ⏳ Planowany |
| 6 | FinMind + ML (flagship) | FastAPI · Prophet · React | ⏳ Planowany |

---


*Ostatnia aktualizacja: maj 2026*