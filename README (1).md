<div align="center">

# Nasreddine El Mammeri

**Data science projects, end to end** — SQL · predictive modelling · computer vision

📍 Nice, France · 📫 [LinkedIn](https://www.linkedin.com/in/nassreddine-elmammeri/)

</div>

---

### Hi, I'm Nasreddine 👋

I build data science projects end to end, and I document my decisions —
including the ones I discarded after testing them.

**What I work with**

- **SQL** — joins, aggregations, window functions (DuckDB, PostgreSQL)
- **Python** — pandas, scikit-learn, matplotlib
- **Machine learning** — regression, time-based validation, business metrics, clustering (KMeans, PCA)
- **Computer vision** — TensorFlow/Keras, transfer learning and fine-tuning, OpenCV

---

### Projects

| Project | What it covers | Result |
| --- | --- | --- |
| [**rossmann-sales**](https://github.com/Nasreddine-EL-MAMMERI/rossmann-sales) | Sales forecasting and store segmentation on 1.1M rows, from SQL exploration to KMeans clustering | RMSPE **19.1%** on temporal validation · **0.174** private on Kaggle · **3** store profiles validated against hold-out variables |
| [**Sport-images-classification**](https://github.com/Nasreddine-EL-MAMMERI/Sport-images-classification) | 73-class sports image classification. EfficientNetB0 frozen, then partially fine-tuned — both phases compared with exact McNemar tests | **0.9355** private (frozen baseline **0.9176**) · fine-tuning worth **+0.75 pt** at **p = 0.003** · unfreezing 30 or 100 layers made no measurable difference |
| [**Image-Classifier**](https://github.com/Nasreddine-EL-MAMMERI/Image-Classifier) | CNN trained from scratch, no pretrained weights, 4 animal classes | **84.8%** on Kaggle · run-to-run noise measured at ~4 points before comparing runs |

Every one of those repos carries its decision log: what I tried, what I measured,
and what I dropped because the numbers did not support it.

---

### Earlier work

Computer vision projects kept as-is — learning projects, not maintained:

- [face-detection-app](https://github.com/Nasreddine-EL-MAMMERI/face-detection-app) — real-time face detection with OpenCV
- [image-restoration-app](https://github.com/Nasreddine-EL-MAMMERI/image-restoration-app) — image restoration with convolutional networks

---

### Currently

Going deeper into computer vision: data augmentation, object detection, and
evaluation protocols that survive a grouped validation split. Next: NLP on
French corpora and time series.

---

**En bref (français).** Je construis des projets de data science de bout en bout — SQL, modélisation prédictive, vision par ordinateur — et je documente mes choix, y compris ceux que j'ai rejetés après vérification. Trois projets principaux : prévision des ventes de 1 115 magasins (RMSPE 19,1 % en validation temporelle, 0,174 au classement privé Kaggle), classification d'images sportives en 73 classes avec un EfficientNetB0 (0,9355 au classement privé après fine-tuning partiel, contre 0,9176 avec le backbone gelé), et un CNN entraîné de zéro (84,8 %). Chaque dépôt contient son journal de décisions.
