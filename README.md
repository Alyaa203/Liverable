<div align="center">

# SchrödArt: Technical Documentation

**The written deliverables for SchrödArt, a Python app that solves the Schrödinger equation and turns the results into art.**

[App source code (P2i)](https://github.com/Alyaa203/P2i) · [Live demo](https://gnm4pxwnrpb6cy3syst6sn.streamlit.app)

![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)

</div>

---

## Overview

This repository holds the documentation handed in with **SchrödArt**, an individual engineering project at ENSC (Bordeaux INP). The code itself lives in **[Alyaa203/P2i](https://github.com/Alyaa203/P2i)**.

**Why it exists:** the reports explain the maths behind each numerical method and how it is implemented, so that the work can be reviewed and reproduced without reading the code.

---

## What's inside

| Document | Content |
| --- | --- |
| [`modale.pdf`](modale.pdf) | **Modal method** (5 pages): finite-difference discretisation, 2D Hamiltonian built with a Kronecker product, sparse diagonalisation with ARPACK, truncation errors, 1D time evolution and norm conservation |
| [`fourier.pdf`](fourier.pdf) | **Split-Step Fourier method** (5 pages): second-order Strang scheme, initial wave packet, three potentials (barrier, harmonic oscillator, double well), implementation and conservation checks |
| [`installation.pdf`](installation.pdf) | **User guide** (1 page): how to open the online app or run it locally |

---

## Skills shown

- Numerical analysis: finite differences, sparse eigenvalue problems, operator splitting, FFT
- Quantum mechanics: stationary states, time evolution, tunnelling
- Scientific writing: clear technical reports with equations and diagrams

---

## Tech stack

| Area | Tools |
| --- | --- |
| Documents | LaTeX (pdfTeX) |
| Project described | Python, NumPy, SciPy, Matplotlib, Streamlit |

---

## How to run the app

**Online:** open the [live demo](https://gnm4pxwnrpb6cy3syst6sn.streamlit.app). No installation is needed; it may take a minute to wake up.

**Locally** (Python 3.9+):

```bash
git clone https://github.com/Alyaa203/P2i.git
cd P2i
pip install -r requirements.txt
streamlit run streamlit_app.py
```

Then open http://localhost:8501.

---

## Screenshots

> _Screenshots coming soon._

| Modal method report | Split-Step Fourier report | App |
| :---: | :---: | :---: |
| ![Modal method report](docs/screenshots/modale.png) | ![Split-Step Fourier report](docs/screenshots/fourier.png) | ![App](docs/screenshots/app.png) |

<!-- Add images to docs/screenshots/ using the file names above. -->

---

**Author:** Alyaa Saab, engineering student at ENSC (Bordeaux INP)
