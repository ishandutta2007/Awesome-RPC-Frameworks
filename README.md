# Awesome-RPC-Frameworks

## Top Scientific Computing Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Numerical Arrays, Symbolic Mathematics & Statistical Analysis*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Scientific Computing**. These tools provide the numerical foundations for research, engineering, and data analysis — array manipulation, linear algebra, symbolic mathematics, optimization, statistics, signal processing, and visualization.

**Examples** include MATLAB, Wolfram Mathematica, Maple, SAS, IBM SPSS, OriginLab, Mathcad Prime, RStudio Workbench, JMP, and Stata (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, reproducible research, and transparent numerical methods — ideal for researchers, engineers, and data scientists who need verifiable computation without proprietary licensing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[MATLAB](https://www.mathworks.com/products/matlab.html)**  
  **The dominant commercial numerical computing environment** with matrix-based language, extensive toolboxes, Simulink for model-based design, and hardware deployment support. Standard in engineering education and industry. Per-seat licensing with toolbox add-ons.

- **[Wolfram Mathematica](https://www.wolfram.com/mathematica/)**  
  **The most comprehensive symbolic computation system** — the Wolfram Language powers symbolic algebra, calculus, differential equations, and knowledge-based computation with curated data. Notebook interface and Wolfram Cloud deployment.

- **[Maple](https://www.maplesoft.com/)**  
  **Symbolic and numeric computing environment** popular in academia and engineering for advanced mathematics, with strong technical documentation tools.

- **[SAS](https://www.sas.com/)**  
  **Enterprise statistical analysis system** widely used in clinical trials, pharmaceutical research, and regulatory submissions. Proprietary language with comprehensive statistical procedures and validation documentation.

- **[IBM SPSS](https://www.ibm.com/products/spss-statistics)**  
  **Point-and-click statistical analysis software** for social sciences, market research, and survey analysis. Menu-driven interface lowers barrier for non-programmers.

- **[OriginLab Origin](https://www.originlab.com/)**  
  **Scientific graphing and data analysis software** widely used in physics, chemistry, and materials science for publication-quality figures and curve fitting.

- **[Mathcad Prime](https://www.ptc.com/en/products/mathcad)**  
  **Engineering calculation software** with live mathematical notation, units-aware computation, and documentation integration.

- **[RStudio Workbench](https://posit.co/products/enterprise/workbench/)**  
  **Enterprise R environment** with centralized server deployment, project sharing, and commercial support. The open-source RStudio IDE remains free.

- **[JMP](https://www.jmp.com/)**  
  **Statistical discovery software from SAS** with interactive visualization and design of experiments (DOE) capabilities. Popular in Six Sigma and quality engineering.

- **[Stata](https://www.stata.com/)**  
  **Statistical software for economists and social scientists** with panel data methods, survey analysis, and reproducible research workflows.

## Open-Source GitHub Projects

- **[NumPy](https://github.com/numpy/numpy)**  
  **The fundamental package for scientific computing in Python** — BSD-3-Clause licensed, **30,000+ GitHub stars**. Provides **n-dimensional array objects**, broadcasting, linear algebra, Fourier transforms, random number generation, and **vectorized operations** that avoid Python loop overhead. **The foundation the entire Python data ecosystem builds on** — SciPy, pandas, Matplotlib, scikit-learn, PyTorch, and TensorFlow all depend on NumPy arrays. **Best for anyone doing numerical work in Python** — it's not optional.

- **[SciPy](https://github.com/scipy/scipy)**  
  **The scientific computing library for Python** — BSD-3-Clause licensed. **Optimization, integration, interpolation, signal processing, linear algebra, statistics, and spatial algorithms** built on NumPy. Includes `scipy.optimize` (minimize, curve_fit, linprog), `scipy.integrate` (solve_ivp, quad), `scipy.interpolate` (interp1d, splines), `scipy.signal` (filtering, spectral analysis), and `scipy.stats` (distributions, hypothesis tests). **The numerical methods layer for Python research code.**

- **[SymPy](https://github.com/sympy/sympy)**  
  **Symbolic mathematics and computer algebra library for Python** — BSD-3-Clause licensed, 13,000+ GitHub stars. **Exact symbolic computation** for algebra, calculus, differential equations, matrices, discrete math, and physics. **Code generation** to C, Fortran, and other languages. **The open-source alternative to Mathematica and Maple** for symbolic work — integrates with NumPy and SciPy for hybrid numeric-symbolic pipelines.

- **[pandas](https://github.com/pandas-dev/pandas)**  
  **The data analysis library for Python** — BSD-3-Clause licensed. **DataFrame and Series structures** for labeled, heterogeneous tabular data. **Time series analysis, groupby aggregations, joins, reshaping, and missing data handling**. **The workhorse for data wrangling** in research and industry alike.

- **[Matplotlib](https://github.com/matplotlib/matplotlib)**  
  **The foundational plotting library for Python** — PSF-based license. **Publication-quality 2D figures** with full control over every visual element. **Backends** for interactive (Qt, Tkinter), notebook (Jupyter), and file export (PNG, PDF, SVG). **The reference for reproducible figures** in papers and reports.

- **[Jupyter](https://github.com/jupyter/notebook)**  
  **Interactive computing environment for reproducible research** — BSD-3-Clause licensed. **Notebooks mixing code, equations (LaTeX), visualizations, and narrative text**. **JupyterLab** provides a full IDE-like interface; **JupyterHub** deploys multi-user environments for teams and classrooms. **The standard for exploratory data analysis and teaching.**

- **[scikit-learn](https://github.com/scikit-learn/scikit-learn)**  
  **Machine learning library for Python** — BSD-3-Clause licensed, 60,000+ GitHub stars. **Classification, regression, clustering, dimensionality reduction, model selection, and preprocessing** with a consistent API. **The reference implementation for classical ML methods** used across scientific disciplines.

- **[statsmodels](https://github.com/statsmodels/statsmodels)**  
  **Statistical modeling and econometrics for Python** — BSD-3-Clause licensed. **Linear models, generalized linear models, mixed effects, time series (ARIMA, VAR, state space), survival analysis, and hypothesis testing** with R-style formula API. **The complement to scikit-learn for inference-focused statistics.**

- **[R (The R Project)](https://github.com/wch/r-source)**  
  **The statistical computing language** — GPL-2.0 licensed. **CRAN** hosts **20,000+ packages** for statistics, bioinformatics, econometrics, and visualization. **The reference for statistical methodology** — new methods often appear in R first. **RStudio/Posit** provides the IDE ecosystem.

- **[Julia](https://github.com/JuliaLang/julia)**  
  **The high-performance dynamic language for technical computing** — MIT licensed. **Combines Python-like syntax with C-like speed** via JIT compilation. **Multiple dispatch** enables expressive mathematical code that compiles to efficient machine instructions. **The strongest contender to replace MATLAB in numerical research** — used at MIT, NASA, and financial institutions.

- **[GNU Octave](https://github.com/gnu-octave/octave)**  
  **The open-source MATLAB alternative** — GPL-3.0 licensed. **MATLAB-compatible syntax** for most numerical code. **Signal processing, control systems, and optimization** with community packages. **Best for students and researchers** wanting MATLAB-style workflows without licensing costs.

- **[SageMath](https://github.com/sagemath/sage)**  
  **The comprehensive open-source mathematics software system** — GPL-3.0 licensed. **Integrates NumPy, SciPy, SymPy, Maxima, GAP, PARI/GP, Singular, and more** into a unified interface. **Algebra, number theory, cryptography, combinatorics, and calculus** at research level. **The open-source alternative to Magma, Maple, Mathematica, and MATLAB combined.**

- **[GNUPlot](https://github.com/gnuplot/gnuplot)**  
  **Portable command-line plotting utility** — GPL licensed. **Scriptable plotting** for publications, with output to dozens of formats. **The veteran tool** still widely used in physics and engineering for reproducible figures.

### Additional Strong Open-Source Options

- **NetworkX** — Graph and network analysis library for Python.
- **PyMC** — Bayesian statistical modeling and probabilistic programming.
- **Stan** — Probabilistic programming language for Bayesian inference with interfaces in R, Python, Julia, and command line.
- **Dask** — Parallel computing library scaling NumPy/pandas workloads beyond memory.
- **Numba** — JIT compiler bringing C-like speed to Python numerical functions.
- **CuPy** — NumPy-compatible GPU array library for CUDA acceleration.
- **Zarr** — Chunked, compressed N-dimensional arrays for parallel and cloud-native storage.
- **xarray** — Labeled multi-dimensional arrays for climate, geoscience, and imaging data.

**Frameworks for building custom systems**: Combine **NumPy** for array primitives, **SciPy** for numerical methods, **SymPy** for symbolic derivation, **pandas** for tabular data, **Matplotlib** for publication figures, **Jupyter** for reproducible notebooks, **scikit-learn** and **statsmodels** for machine learning and inference, and **Julia** or **GNU Octave** for MATLAB-style high-performance numerical work — to build a complete scientific computing environment that runs entirely on open-source foundations.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Scientific computing tools differ significantly in licensing model, language ecosystem, and scope of numerical methods. **MATLAB and Mathematica remain dominant in engineering education and symbolic mathematics** respectively — open-source alternatives are functionally capable but may lack specific toolboxes, curated data, or vendor support . **Julia is the strongest contender to replace MATLAB** in numerical research but has a smaller ecosystem . **GNU Octave runs most MATLAB code** with syntax compatibility but incomplete toolbox coverage . **R remains the reference for statistical methodology** — new methods often appear in R first . **SageMath integrates multiple specialized systems** but has a steeper learning curve than MATLAB or Mathematica . **Reproducibility depends on more than tool choice** — pin package versions, seed random generators, and document environment specifications.
- Self-hosted open-source solutions require proper package environment management (conda, venv, or Docker) and awareness of numerical precision, floating-point behavior, and BLAS/LAPACK backend differences across systems.

---

**Made for researchers, engineers, data scientists, and anyone doing numerical computing.**
Let's make scientific computing more open, reproducible, and numerically transparent.
