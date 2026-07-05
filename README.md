<h1 align="center">Hi, I'm Henrique 👋</h1>

<h3 align="center">Data Engineer · pipelines, cloud ETL & real-time data</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/henrique-batistuzzo/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:hbatistuzzo@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="http://api.whatsapp.com/send?phone=5511981126990"><img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a>
</p>

<p align="left">
🔹 :ocean: I have an **Ocean/Environmental Sciences** academic background; BSc in **Oceanography** from the University of São Paulo <br>
🔹 ⚓ <b>Data Engineer at the Brazilian Navy (CHM)</b> - Automated data pipelines: real-time ingestion from telemetry, quality control, and APIs<br>
🔹 📋 DataViz and dashboards for monitoring and analysis<br>
🔹 :bar_chart: I've worked as a TA/Specialist Instructor and as an Oceanographic Data Analyst in BC, Canada <br>
🔹 :desktop_computer: Started delving into Data Science through the **Ironhack** bootcamp <br>
🔹 🤘 Certified Glider and Sailbuoy pilot
</p>

---

As an oceanographer I've focused mostly on remote sensing and large-to-meso-scale Geophysical Fluid Dynamics. I started programming with C, MATLAB and R in a physical-oceanography lab, and Python became my daily tool for everything from remote sensing to data engineering. Along the way the toolbox grew into standard practice: **Pyenv, Pip/Venv, Poetry and Git** for reproducibility; **NumPy, Pandas, Matplotlib, Seaborn** for analysis; **XArray + Dask** for large HDF5/NetCDF/Zarr datasets and lazy computation; and orchestration with **CRON, Airflow and Docker** as scripts grew into pipelines - all in a Linux environment.

Git is a given for coding work, and GitHub doubles as a portfolio, so I've grouped some projects below in case you're curious.
Boris Cherny from Claude Code has famously said that *"coding is largely solved."* So if you're a client or recruiter wondering *"why would I need a data engineer, then?"* - here's my honest answer:

- **Writing code syntax was never the hard part*: it's mechanical, and yes, AI does a lot of it now.
- **The hard part is modelling the problem correctly**: defining boundaries, understanding data flow, anticipating failure modes, and designing systems that *survive change*.
- Understanding a system deeply (why a function exists, what assumptions it makes, what happens when inputs are invalid) is what keeps a pipeline reliable at 3 a.m.

<br>

<h1 align="center">Featured Projects</h1>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4 align="center">🏃 runsight - Garmin activity analytics</h4>
      <div align="center">

![top](https://img.shields.io/github/languages/top/hbatistuzzo/runsight)
![size](https://img.shields.io/github/languages/code-size/hbatistuzzo/runsight)
![last commit](https://img.shields.io/github/last-commit/hbatistuzzo/runsight)

</div>
      <p>A production-grade Python package that pulls Garmin activity data and turns it into analytics. Proper <code>src/</code> layout, tests, CI, and a packaged CLI - the way I structure real projects.</p>
      <p align="center"><strong>Python · pytest · CI · packaging</strong></p>
      <p align="center">
        <a href="https://github.com/hbatistuzzo/runsight"><img src="https://img.shields.io/static/v1?label=|&message=CODE&color=05F718&style=plastic&logo=github"/></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">⚡ 1 Billion Rows Challenge</h4>
      <div align="center">

![top](https://img.shields.io/github/languages/top/hbatistuzzo/1-billion-rows-challenge)
![size](https://img.shields.io/github/languages/code-size/hbatistuzzo/1-billion-rows-challenge)
![last commit](https://img.shields.io/github/last-commit/hbatistuzzo/1-billion-rows-challenge)

</div>
      <p>Aggregating one billion rows - and benchmarking how far you can push it with pure Python vs Pandas, Polars, DuckDB and Dask. Performance engineering and knowing the right tool for scale.</p>
      <p align="center"><strong>Python · Polars · DuckDB · Dask</strong></p>
      <p align="center">
        <a href="https://github.com/hbatistuzzo/1-billion-rows-challenge"><img src="https://img.shields.io/static/v1?label=|&message=CODE&color=05F718&style=plastic&logo=github"/></a>
      </p>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h4 align="center">🛰️ CMEMS Altimetry - Rossby waves</h4>
      <div align="center">

![top](https://img.shields.io/github/languages/top/hbatistuzzo/CMEMS-altimetry)
![size](https://img.shields.io/github/languages/code-size/hbatistuzzo/CMEMS-altimetry)
![last commit](https://img.shields.io/github/last-commit/hbatistuzzo/CMEMS-altimetry)

</div>
      <div align="center"><img src="images/vgos.gif" height="230" width="300" alt="geostrophic velocity"/></div>
      <p>Global monthly climatologies of geostrophic velocities from CMEMS altimetry, plus Hovmöller diagrams that make first-mode baroclinic Rossby waves visible. Large NetCDF handling with XArray + Dask.</p>
      <p align="center"><strong>Python · XArray · Dask · NetCDF</strong></p>
      <p align="center">
        <a href="https://github.com/hbatistuzzo/CMEMS-altimetry"><img src="https://img.shields.io/static/v1?label=|&message=CODE&color=05F718&style=plastic&logo=github"/></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">🐍 FastAPI + TDD</h4>
      <div align="center">

![top](https://img.shields.io/github/languages/top/hbatistuzzo/DIO_FastAPI_TDD)
![size](https://img.shields.io/github/languages/code-size/hbatistuzzo/DIO_FastAPI_TDD)
![last commit](https://img.shields.io/github/last-commit/hbatistuzzo/DIO_FastAPI_TDD)

</div>
      <p>An async REST API built test-first with FastAPI, Pydantic and pytest - clean structure, typed schemas, and tests driving the design. How I build the API layer that sits on top of a pipeline.</p>
      <p align="center"><strong>FastAPI · Pydantic · pytest · async</strong></p>
      <p align="center">
        <a href="https://github.com/hbatistuzzo/DIO_FastAPI_TDD"><img src="https://img.shields.io/static/v1?label=|&message=CODE&color=05F718&style=plastic&logo=github"/></a>
      </p>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h4 align="center">📊 Ironhack Final Project - data bank</h4>
      <div align="center">

![top](https://img.shields.io/github/languages/top/hbatistuzzo/Ironhack-FinalProject)
![size](https://img.shields.io/github/languages/code-size/hbatistuzzo/Ironhack-FinalProject)
![last commit](https://img.shields.io/github/last-commit/hbatistuzzo/Ironhack-FinalProject)

</div>
      <div align="center"><img src="images/databank_structure.png" height="230" width="300" alt="data bank"/></div>
      <p>A fintech case (AME-Digital / Stack Overflow 2018 Dev Survey): designed the data bank, ran the SQL, visualized the answers and built a predictive model - end to end.</p>
      <p align="center"><strong>Python · MySQL · Tableau</strong></p>
      <p align="center">
        <a href="https://github.com/hbatistuzzo/Ironhack-FinalProject"><img src="https://img.shields.io/static/v1?label=|&message=CODE&color=05F718&style=plastic&logo=github"/></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">🦠 COVID-19 SQL</h4>
      <div align="center">

![top](https://img.shields.io/github/languages/top/hbatistuzzo/Covid_SQL)
![size](https://img.shields.io/github/languages/code-size/hbatistuzzo/Covid_SQL)
![last commit](https://img.shields.io/github/last-commit/hbatistuzzo/Covid_SQL)

</div>
      <div align="center"><img src="images/example.png" height="230" width="300" alt="covid sql"/></div>
      <p>Exploratory analysis of a COVID-19 dataset in SQL - joins, CTEs, temp tables, window &amp; aggregate functions, views and type conversions. The SQL fundamentals a data role runs on.</p>
      <p align="center"><strong>SQL · MS SQL Server · Tableau</strong></p>
      <p align="center">
        <a href="https://github.com/hbatistuzzo/Covid_SQL"><img src="https://img.shields.io/static/v1?label=|&message=CODE&color=05F718&style=plastic&logo=github"/></a>
      </p>
    </td>
  </tr>

  <tr>
    <td width="50%" valign="top">
      <h4 align="center">🔬 PHYSAT - honours thesis</h4>
      <div align="center">

![top](https://img.shields.io/github/languages/top/hbatistuzzo/PHYSAT_data)
![size](https://img.shields.io/github/languages/code-size/hbatistuzzo/PHYSAT_data)
![last commit](https://img.shields.io/github/last-commit/hbatistuzzo/PHYSAT_data)

</div>
      <div align="center"><img src="images/dovidio_2010.png" height="230" width="300" alt="PHYSAT"/></div>
      <p>Code from my honours thesis - "1st-mode baroclinic Rossby waves modify the composition of Phytoplankton Functional Groups" - pairing altimetry with a bio-algorithm that classifies phytoplankton by spectral signature.</p>
      <p align="center"><strong>MATLAB · remote sensing</strong></p>
      <p align="center">
        <a href="https://github.com/hbatistuzzo/PHYSAT_data"><img src="https://img.shields.io/static/v1?label=|&message=CODE&color=05F718&style=plastic&logo=github"/></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4 align="center">💎 Linear Regression - diamond prices</h4>
      <div align="center">

![top](https://img.shields.io/github/languages/top/hbatistuzzo/Machine_Learning-Linear_Regression)
![size](https://img.shields.io/github/languages/code-size/hbatistuzzo/Machine_Learning-Linear_Regression)
![last commit](https://img.shields.io/github/last-commit/hbatistuzzo/Machine_Learning-Linear_Regression)

</div>
      <div align="center"><img src="images/heatmap.png" height="230" width="300" alt="heatmap"/></div>
      <p>Predicting diamond prices with a linear-regression pipeline - EDA, feature engineering, model fitting and evaluation on a clean, documented workflow.</p>
      <p align="center"><strong>Python · scikit-learn · Pandas</strong></p>
      <p align="center">
        <a href="https://github.com/hbatistuzzo/Machine_Learning-Linear_Regression"><img src="https://img.shields.io/static/v1?label=|&message=CODE&color=05F718&style=plastic&logo=github"/></a>
      </p>
    </td>
  </tr>
</table>

---

<details>
<summary align="center"><b>so what's your deal, man? 🤔 (a bit of personality)</b></summary>

<br>

My deal is **mindmaps** - from literature reviews of scientific papers to organizing how I learn new tech. There's good evidence that this leverages spatial and visual memory in complementary ways ([Dresler et al., 2018](https://pmc.ncbi.nlm.nih.gov/articles/PMC5439266/)). Listen, Geophysical Fluid Dynamics is hard enough, and I'm not particularly savvy, but my _sister_ is, so I'll take a hint from someone who has a postdoc in neurobiology and take any advantage I can get. Cognitive architecture is a vibrant field and I suspect they're on to something.

<div align="center"><img src="images/mindmaps.gif" width="700" alt="mindmap"/></div>

</details>

---

<div>
  <h1 align="center">Tech Stack</h1>

  <table align="center" style="width: 100%; table-layout: fixed; border-spacing: 10px;">
    <tr>
      <td style="width: 50%; vertical-align: top;">
        <h2 align="center">Programming & Data Processing</h2>
        <div align="center">
          <img alt="python" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" />
          <img alt="pandas" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" />
          <img alt="numpy" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" />
          <img alt="scipy" height="60" width="60" src="https://upload.wikimedia.org/wikipedia/commons/b/b2/SCIPY_2.svg" />
          <img alt="jupyter" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" />
          <img alt="xarray" height="60" width="60" src="https://raw.githubusercontent.com/pydata/xarray/026aa7c073d03fb6d749c216be1d829816583fac/doc/_static/logos/Xarray_Icon_Final.svg" />
          <img alt="matlab" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" />
        </div>
      </td>
      <td style="width: 50%; vertical-align: top;">
        <h2 align="center">Databases</h2>
        <div align="center">
          <img alt="PostgreSQL" height="60" width="55" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" />
          <img alt="MySQL" height="60" width="55" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" />
          <img alt="MongoDB" height="60" width="55" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original-wordmark.svg" />
          <img alt="SQLalchemy" height="60" width="55" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlalchemy/sqlalchemy-original.svg" />
          <img alt="DBeaver" height="60" width="55" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dbeaver/dbeaver-original.svg" />
        </div>
      </td>
    </tr>
    <tr>
      <td style="width: 50%; vertical-align: top;">
        <h2 align="center">Data Engineering & Automation</h2>
        <div align="center">
          <img alt="Docker" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" />
          <img alt="Airflow" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apacheairflow/apacheairflow-original.svg" />
          <img alt="dask" height="60" width="60" src="https://docs.dask.org/en/stable/_images/dask_icon.svg" />
          <img alt="Selenium" height="60" width="60" src="https://raw.githubusercontent.com/detain/svg-logos/780f25886640cef088af994181646db2f6b1a3f8/svg/selenium-logo.svg" />
          <img alt="GitHub Actions" height="60" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" />
        </div>
      </td>
      <td style="width: 50%; vertical-align: top;">
        <h2 align="center">Cloud & APIs</h2>
        <div align="center">
          <img alt="AWS" height="65" width="65" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" />
          <img alt="FastAPI" height="55" width="55" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" />
          <img alt="Postman" height="55" width="55" src="https://www.svgrepo.com/show/354202/postman-icon.svg" />
        </div>
      </td>
    </tr>
    <tr>
      <td style="width: 50%; vertical-align: top;">
        <h2 align="center">Visualization & BI</h2>
        <div align="center">
          <img alt="Power BI" height="55" width="55" src="images/Power-BI.svg" />
          <img alt="Tableau" height="55" width="55" src="images/tableau.png" />
          <img alt="Matplotlib" height="55" width="55" src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" />
          <img alt="Seaborn" height="55" width="55" src="https://seaborn.pydata.org/_static/logo-tall-lightbg.svg" />
        </div>
      </td>
      <td style="width: 50%; vertical-align: top;">
        <h2 align="center">Systems & Tools</h2>
        <div align="center">
          <img alt="Ubuntu" height="55" width="55" src="https://upload.wikimedia.org/wikipedia/commons/9/9e/UbuntuCoF.svg" />
          <img alt="Bash" height="55" width="55" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" />
          <img alt="Git" height="55" width="55" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />
          <img alt="VS Code" height="55" width="55" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" />
          <img alt="LaTeX" height="55" width="55" src="images/latex-1.svg" />
        </div>
      </td>
    </tr>
  </table>

  <table align="center" style="width: 80%; table-layout: fixed;">
    <tr>
      <td style="text-align: center; padding: 15px;">
        <h2 align="center">Currently exploring…</h2>
        <div align="center">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-original.svg" alt="Kubernetes" height="60" width="60"/>
          <img src="https://cdn.brandfetch.io/idSUrLOWbH/theme/dark/symbol.svg?c=1bfwsmEH20zzEfSNTed" alt="databricks" height="60" width="60"/>
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original-wordmark.svg" alt="React" height="60" width="60"/>
        </div>
      </td>
    </tr>
  </table>
</div>

---

<h1 align="center">GitHub Stats</h1>

<table align="center">
  <tr>
    <td>
      <img src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=hbatistuzzo&theme=transparent" />
    </td>
    <td>
      <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=hbatistuzzo&theme=transparent" />
    </td>
  </tr>
</table>

<p align="center">📫 Reach me: <a href="mailto:hbatistuzzo@gmail.com">hbatistuzzo@gmail.com</a> · <a href="https://www.linkedin.com/in/henrique-batistuzzo/">LinkedIn</a> · <a href="http://api.whatsapp.com/send?phone=5511981126990">WhatsApp</a></p>
