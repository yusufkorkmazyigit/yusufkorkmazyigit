# Hi, I'm Yusuf Korkmazyiğit 👋

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1500&center=true&vCenter=true&width=680&lines=Swarm+Intelligence+%C3%97+Machine+Learning;Reliable+ML+for+aerospace+%E2%80%94+aero-rul;Author+of+abcopt+and+aerorul+on+PyPI;ML+for+Neutrino+Physics+%40+ENRG" alt="Swarm Intelligence × Machine Learning" />
</p>

Computer Engineering student at **Erciyes University**, Türkiye. I build machine-learning and optimization tools that can be trusted: measured uncertainty, fair comparisons, reproducible results. My work spans **swarm-intelligence optimization** (the Artificial Bee Colony algorithm), **predictive maintenance for aerospace**, and **ML for particle physics** as an undergraduate researcher in the Erciyes Neutrino Research Group, a member institution of the **ANNIE** (Fermilab) and **EOS** (UC Berkeley) experiments.

## ✈️ Featured

<table>
<tr>
<td width="56%" valign="top">

### [aero-rul](https://github.com/yusufkorkmazyigit/aero-rul)

**How many flights does this engine have left, and how far can that answer be trusted?** Remaining-useful-life prediction for turbofan engines on NASA's N-CMAPSS data, with conformal prediction intervals whose coverage is measured on engines the model has never seen.

```bash
pip install aerorul
```

- 90 % interval covers **90.4 %** of test flights; plain quantile regression delivers 82.2 %
- **10.1 flights** RMSE, engine-level splits, no label leakage, five seeds

[![PyPI](https://img.shields.io/pypi/v/aerorul)](https://pypi.org/project/aerorul/)
[![CI](https://github.com/yusufkorkmazyigit/aero-rul/actions/workflows/ci.yml/badge.svg)](https://github.com/yusufkorkmazyigit/aero-rul/actions/workflows/ci.yml)
[![Docs](https://img.shields.io/badge/docs-online-blue)](https://yusufkorkmazyigit.github.io/aero-rul/)

</td>
<td width="44%" valign="top">
<a href="https://github.com/yusufkorkmazyigit/aero-rul"><img src="https://raw.githubusercontent.com/yusufkorkmazyigit/aero-rul/main/docs/assets/bands_cv_90.png" alt="Predicted RUL with 90% conformal interval" width="100%"></a>
</td>
</tr>
<tr>
<td width="56%" valign="top">

### [abcopt](https://github.com/yusufkorkmazyigit/abc-optimizer-lib)

Canonical Artificial Bee Colony optimization for Python, with `ABCSearchCV`, a drop-in alternative to scikit-learn's `GridSearchCV`.

```bash
pip install abcopt
```

- Verified step for step against the Erciyes University reference implementation
- Continuous, integer and categorical search spaces, `cv_results_`, caching
- 54 tests, CI on Python 3.9–3.12, benchmark against Optuna TPE

[![PyPI](https://img.shields.io/pypi/v/abcopt)](https://pypi.org/project/abcopt/)
[![tests](https://github.com/yusufkorkmazyigit/abc-optimizer-lib/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/yusufkorkmazyigit/abc-optimizer-lib/actions/workflows/tests.yml)

</td>
<td width="44%" valign="top">
<a href="https://github.com/yusufkorkmazyigit/abc-optimizer-lib"><img src="https://raw.githubusercontent.com/yusufkorkmazyigit/abc-optimizer-lib/main/docs/abc_animation.gif" alt="ABC solving the Rastrigin function" width="100%"></a>
</td>
</tr>
</table>

## 🛠️ Selected Projects

| Project | What it is |
|---|---|
| [**aero-rul**](https://github.com/yusufkorkmazyigit/aero-rul) | Turbofan engine RUL with calibrated conformal intervals (N-CMAPSS), on PyPI as `aerorul` |
| [**ArıKes**](https://github.com/yusufkorkmazyigit/arikes) | ABC-powered panel cutting for furniture workshops (Climathon 2026): **−59 % scrap** vs a craftsman baseline on 35 ROADEF/EURO 2018 industrial orders |
| [**abcopt**](https://github.com/yusufkorkmazyigit/abc-optimizer-lib) | Canonical ABC + scikit-learn hyperparameter search, on PyPI |
| [**cherenkov-abc-hpo**](https://github.com/yusufkorkmazyigit/cherenkov-abc-hpo) | ABC vs Grid / Random / Optuna TPE for Cherenkov–scintillation photon separation (TÜBİTAK 2209-A) |
| [**classical-otoc-estimation**](https://github.com/yusufkorkmazyigit/classical-otoc-estimation) | Duke × BlueQubit Quantum Hackathon 2026: classical estimation of Google's *Quantum Echoes* OTOCs with statevector, an own Pauli-path simulator and MPS (40th place) |
| [**steel-defect-detection**](https://github.com/yusufkorkmazyigit/steel-defect-detection) | YOLOv8n-seg segmentation of steel surface defects with a Streamlit app |
| [**fedLearningwithABC**](https://github.com/yusufkorkmazyigit/fedLearningwithABC) | ABC-learned aggregation weights for FedAvg on non-IID medical images |

## 🔬 Research & Experience

- **Erciyes Neutrino Research Group** · Undergraduate Researcher, TÜBİTAK 2247-C scholar
  Cherenkov / scintillation photon separation in water-based liquid scintillator detectors: ROOT-to-ML data pipelines and a benchmark of 20 classifiers, where a tuned ensemble reached 95.75% accuracy versus ~90% for the classical time-cut method. Administrator of the group's Linux CPU/GPU servers.
- **TÜBİTAK 2209-A** · Project Leader
  Hyperparameter optimization of photon-separation models with ABC, compared with Grid Search, Random Search and Optuna TPE under equal budgets ([code & results](https://github.com/yusufkorkmazyigit/cherenkov-abc-hpo)).
- **POSCO Assan TST Steel** · Data Science & Software Engineering Intern
  Defect-driver analysis on production sensor data (XGBoost, GroupKFold, SHAP) and a YOLOv8 segmentation model for steel surface defects.
- **Graduation thesis: KOVAN** · in progress
  LLM-guided Artificial Bee Colony for discovering interpretable algorithms, with applications in optimization and particle physics.

## 🤝 Community

- **CS50x Türkiye** · core team member
- **NASA Space Apps Challenge Kayseri** · mentor (November 2026)

## 🧰 Tech Stack

- **Languages:** Python · TypeScript · Java · SQL · C/C++
- **ML & optimization:** PyTorch · scikit-learn · XGBoost · LightGBM · Optuna · SHAP · Ultralytics YOLOv8 · conformal prediction · metaheuristics (ABC)
- **Data & tools:** NumPy · Pandas · ROOT (CERN) · PostgreSQL · Git · GitHub Actions · MkDocs · Streamlit · React · Gemini API · Linux server administration

## 🌍 Currently

- Building **KOVAN** for my graduation thesis
- Preparing for a research-oriented **Master's in AI/ML in Germany**
- Former **Erasmus+** student at Częstochowa University of Technology, Poland

## 📫 Contact

[Website](https://yusufkorkmazyigit.com) · [LinkedIn](https://www.linkedin.com/in/yusufkorkmazyigit) · [Email](mailto:yusuf.korkmazyigit@gmail.com) · [X](https://twitter.com/imkorkmazyigit)

<sub>*Working to give direction to science and technology, from the present to the future.*</sub>
