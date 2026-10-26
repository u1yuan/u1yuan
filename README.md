<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./logo-dark.svg">
    <img src="./logo.svg" alt="U1 abacus logo" width="200">
  </picture>
</p>

<h1 align="center">Hi, I'm Juan Whitty 👋</h1>

<p align="center">
  <b>Computer Science (Data Science) student at FEU Institute of Technology, Manila</b><br>
  <sub>President, ACM FEU Tech Student Chapter</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/juanbwhitty"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:juanangeloroy.whitty@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<br>

### 📓 `u1yuan.ipynb`

![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-1F3A68?style=flat-square&logo=jupyter&logoColor=white)
![Kernel](https://img.shields.io/badge/kernel-Python_3-3776AB?style=flat-square&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/status-seeking_data_analytics_internships-2EA043?style=flat-square)

---

`In [1]:`

```python
from u1yuan import Juan

juan = Juan()
juan.about()
```

`Out[1]:`

I turn messy data into clear, evidence-based insights with Python, SQL, and statistics, and I build practical tools that people actually use, not side projects built just for the sake of building.

> [!NOTE]
> 🔎 **Currently seeking data analytics internships.** Reach me on [LinkedIn](https://www.linkedin.com/in/juanbwhitty) or at [juanangeloroy.whitty@gmail.com](mailto:juanangeloroy.whitty@gmail.com).

---

`In [2]:`

```python
juan.working_on()
```

`Out[2]:`

- **Machine learning coursework (CS 0075):** model tuning with scikit-learn and Optuna
- **Workflow automation:** a daily Canvas-to-Notion task sync built on MCP and GitHub Actions
- **AI engineering:** harness and context engineering through custom agent skills, MCP tool integrations, and scheduled agent routines
- **Leading ACM FEU Tech:** 21 officers, 5 chapter projects, 402 members enrolled in the first term

---

`In [3]:`

```python
juan.projects(kind="data")  # -> pandas.DataFrame
```

`Out[3]:`

| | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | project | what_it_does | stack |
| --: | :-: | :-- | :-- | :-- |
| **0** | <img src="./assets/logos/philippine-earthquakes-analytics.svg" width="32" height="32" alt="Philippine Earthquakes Analytics logo"> | **Philippine Earthquakes Analytics** | Cleaned 35,541 seismic records (1996–2026) and built a Poisson-based 30-day probability model; walk-forward backtest (2019–2024) beat the 0.25 Brier random baseline | Python · Pandas · GeoPandas · Folium · Plotly |
| **1** | <img src="./assets/logos/instagram-usage-and-well-being-case-study.svg" width="32" height="32" alt="Instagram Usage & Well-Being logo"> | [**Instagram Usage & Well-Being**](https://github.com/u1yuan/instagram-usage-and-well-being-case-study) | Analyzed a 1.5M+ record synthetic dataset with 8 engineered features; found a strong usage–stress link (ρ = 0.84), written up as an APA research report | Python · pandas · SciPy · seaborn |
| **2** | <img src="./assets/logos/ml-ta3.svg" width="32" height="32" alt="ML team lab (CS 0075) logo"> | [**ML team lab (CS 0075)**](https://github.com/u1yuan/ml-ta3) | Tuned Random Forests with grid and Bayesian search: heart-disease F1 from 0.571 to 0.628, housing regression R² 0.89 | Python · scikit-learn · Optuna |
| **3** | <img src="./assets/logos/canvas-to-notion.svg" width="32" height="32" alt="Canvas-to-Notion Task Automation logo"> | **Canvas-to-Notion Task Automation** | Daily automated sync across 7 courses and 193 assignments; idempotent re-runs, 33 tests, and a dry-run mode | Python · GitHub Actions · MCP · Notion API |

<sub>4 rows × 3 columns</sub>

---

`In [4]:`

```python
juan.projects(kind="builds")  # -> pandas.DataFrame
```

`Out[4]:`

| | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | project | description |
| --: | :-: | :-- | :-- |
| **0** | <img src="./assets/logos/protektahanan.svg" width="32" height="32" alt="Protektahanan logo"> | [**Protektahanan**](https://github.com/u1yuan/protektahanan)<br><sub>[live ↗](https://protektahanan.vercel.app)</sub> | Bilingual, senior-friendly scam-pattern checker that works without an API key |
| **1** | <img src="./assets/logos/revwi.svg" width="32" height="32" alt="DevNet Reviewer logo"> | [**DevNet Reviewer**](https://github.com/u1yuan/revwi)<br><sub>[live ↗](https://revwi.vercel.app)</sub> | Local exam reviewer with 122 verified questions curated from 149 exported source items |
| **2** | <img src="./assets/logos/remento.svg" width="32" height="32" alt="Remento logo"> | [**Remento**](https://github.com/u1yuan/remento)<br><sub>[live ↗](https://remento.vercel.app)</sub> | Keeps event moments and new connections together, then returns them as a private recap |
| **3** | <img src="./assets/logos/pastely.svg" width="32" height="32" alt="Pastely logo"> | [**Pastely**](https://github.com/u1yuan/pastely)<br><sub>[live ↗](https://pastely-six.vercel.app)</sub> | Photograph a sticker, remove its background on-device, and arrange it in a shareable library |
| **4** | <img src="./assets/logos/site-ccsma.svg" width="32" height="32" alt="CCSMA Scrollytelling logo"> | [**CCSMA Scrollytelling**](https://github.com/u1yuan/site-ccsma)<br><sub>[live ↗](https://site-ccsma.vercel.app)</sub> | Unofficial, statically exported Next.js concept site for FEU Tech's College of Computer Studies and Multimedia Arts |

<sub>5 rows × 2 columns</sub>

---

`In [5]:`

```python
juan.stack()
```

`Out[5]:`

| Languages | Data & ML | Notebooks, Web & Tools |
| :-- | :-- | :-- |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white) | ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square) ![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=geopandas&logoColor=white) | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=black) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |

---

`In [6]:`

```python
juan.contributions(view="3d")
```

`Out[6]:`

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile-3d-contrib/profile-u1-dark.svg">
    <img src="./profile-3d-contrib/profile-u1-light.svg" alt="Juan's 3D GitHub contribution calendar">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=u1yuan&hide_border=true&background=0D1117&ring=6A8CC7&fire=6A8CC7&currStreakNum=E6EDF3&currStreakLabel=6A8CC7&sideNums=E6EDF3&sideLabels=8B949E&dates=8B949E&stroke=30363D">
    <img src="https://streak-stats.demolab.com/?user=u1yuan&hide_border=true&background=FFFFFF&ring=1F3A68&fire=1F3A68&currStreakNum=1F2328&currStreakLabel=1F3A68&sideNums=1F2328&sideLabels=59636E&dates=59636E&stroke=D0D7DE" alt="Juan's GitHub contribution streak">
  </picture>
</p>

<details>
<summary><b>📈 <code>juan.stats()</code></b></summary>
<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=u1yuan&show_icons=true&hide_border=true&count_private=true&theme=github_dark&icon_color=6A8CC7">
  <img src="https://github-readme-stats.vercel.app/api?username=u1yuan&show_icons=true&hide_border=true&count_private=true&icon_color=1F3A68" alt="Juan's GitHub stats">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=u1yuan&layout=compact&hide_border=true&theme=github_dark">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=u1yuan&layout=compact&hide_border=true" alt="Top languages">
</picture>

</details>

---

`In [7]:`

```python
juan.connect()
```

`Out[7]:`

[![LinkedIn](https://img.shields.io/badge/LinkedIn-juanbwhitty-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juanbwhitty)
[![Email](https://img.shields.io/badge/Email-juanangeloroy.whitty%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:juanangeloroy.whitty@gmail.com)

`In [ ]:`

```python

```
