# STOD-GEN: STOchastic Downscaling GENerator

[![License](https://img.shields.io/badge/license-Academic_Research_Only-blue.svg)](https://img.shields.io/badge/license-Academic_Research_Only-blue.svg)
[![Release](https://img.shields.io/badge/release-v1.1.1-green.svg)](https://img.shields.io/badge/release-v1.1.1-green.svg)

**STOD-GEN** is a standalone desktop tool for stochastic downscaling of Global Climate Model (GCM) rainfall data.  
It generates future rainfall ensembles using a Markov Chain occurrence model coupled with a Gamma distribution for intensity, supporting hydrological and hydraulic impact assessments under CMIP6 climate scenarios.

> **Formerly known as ZH-RainSim v1.1.0.**  
> Version v1.1.1 is a minor update focused on rebranding, documentation, and stability improvements.

---

## Download & Installation

The software, user manual, and sample datasets are available in the **Releases** section.

### 👉 Download the Latest Version (v1.1.1)

Download the STOD-GEN installer here:  
https://github.com/zulkarnainh/STOD-GEN/releases/download/STOD-GEN_v1.1.1/STOD-GEN_v1.1.1.exe

### Installation

1. Download the installer `.exe` file from the link above.  
2. Run **STOD-GEN_v1.1.1.exe**.  
3. Choose your preferred installation directory.  
4. The installer will automatically extract all required files into that directory.  
5. Open the folder and run **STOD-GEN.exe** to start the application.

> **No traditional installation required — the installer simply extracts the application files.**

---

### 📘 User Guide (PDF)

Download the official STOD-GEN v1.1.1 User Guide:  
https://github.com/zulkarnainh/STOD-GEN/releases/download/STOD-GEN_v1.1.1/STOD-GEN.v1.1.1.User.Guide.pdf

---

### 📦 Sample Data (ZIP)

Download sample datasets for testing and validation:  
https://github.com/zulkarnainh/STOD-GEN/releases/download/STOD-GEN_v1.1.1/Data.Samples.zip

---

## What’s New in v1.1.1

### 1. Rebranding & Identity Update

- Software renamed from **ZH-RainSim** to **STOD-GEN**  
- Acronym defined as **STOchastic Downscaling GENerator**  
- Updated titles, labels, and documentation to reflect new name  
- GitHub repository renamed with automatic redirection from the old URL

### 2. Interface & Usability Improvements

- Updated application title and window headers  
- Improved consistency of menu labels and workflow names  
- Minor layout and visual adjustments for better readability  

### 3. Stability Fixes

- Improved error handling for missing or invalid input files  
- Fixed minor GUI alignment issues  
- Updated deprecated Pandas `'Y'` offset to `'YE'`  
- Enhanced folder-based build for faster startup and better antivirus compatibility  

---

## Key Features

- Automated downscaling of CMIP6 GCM rainfall data  
- Stochastic simulation using Markov Chain + Gamma distribution  
- Ensemble-based future rainfall projections  
- User-friendly graphical interface  
- Built-in visualization tools for validation and projections  
- Export of ensembles to CSV for use in Excel, MATLAB, Python, R, and OriginLab  

---

## License

**Copyright:**  
MyIPO (Reference: LY2026P00740)

- **Academic Research:** Free with citation  
- **Funded Research Projects:** Requires a license  
- **Commercial Use:** Not permitted  

---

## Contact & Support

**Developer:** Zulkarnain Hassan  
**Email:** zulkarnainh@unimap.edu.my  
**Website:** http://zulk-unimap.blogspot.com 
**Institution:** Universiti Malaysia Perlis  

---

## Citation

If you use STOD-GEN in your research, please cite:

```bibtex
@software{stod_gen_2026,
  author       = {Zulkarnain Hassan},
  title        = {STOD-GEN: STOchastic Downscaling GENerator},
  year         = {2026},
  publisher    = {GitHub},
  journal      = {GitHub repository},
  howpublished = {https://github.com/zulkarnainh/STOD-GEN}
}
