# STOD-GEN: STOchastic Downscaling GENerator

[![License](https://img.shields.io/badge/license-Academic_Research_Only-blue.svg)](#license)
[![Release](https://img.shields.io/badge/release-v1.1.1-green.svg)](https://github.com/zulkarnainh/STOD-GEN/releases)

**STOD-GEN** is a standalone desktop tool for stochastic downscaling of Global Climate Model (GCM) rainfall data. It generates future rainfall ensembles using a Markov Chain occurrence model coupled with a Gamma distribution for intensity, supporting hydrological and hydraulic impact assessments under CMIP6 climate scenarios.

> **Status Notice:** STOD-GEN is currently undergoing peer review alongside our research manuscript. Software features and documentation are continuously updated to support academic reproducibility.

> **Formerly known as ZH-RainSim v1.1.0.**  
> Version v1.1.1 is a minor release focused on rebranding, documentation alignment, and stability improvements.

---

## Download & Installation

The software, user manual, and sample datasets are available in the [Releases](https://github.com/zulkarnainh/STOD-GEN/releases) section.

### 👉 Download the Latest Version (v1.1.1)

Direct installer download:  
[STOD-GEN_v1.1.1.exe](https://github.com/zulkarnainh/STOD-GEN/releases/download/STOD-GEN_v1.1.1/STOD-GEN_v1.1.1.exe)

### Installation Steps

1. Download the installer executable (`STOD-GEN_v1.1.1.exe`) from the link above.  
2. Run **STOD-GEN_v1.1.1.exe**.  
3. Choose your preferred destination directory.  
4. The self-extracting installer will unpack all required dependencies into that folder.  
5. Open the target folder and run **STOD-GEN.exe** to start the application.

> **Note:** Portable build — no administrative rights or complex environment setups required.

---

### 📘 Documentation & Sample Files

- **User Guide (PDF):** [Download STOD-GEN v1.1.1 User Guide](https://github.com/zulkarnainh/STOD-GEN/releases/download/STOD-GEN_v1.1.1/STOD-GEN.v1.1.1.User.Guide.pdf)
- **Sample Datasets (ZIP):** [Download Test Samples](https://github.com/zulkarnainh/STOD-GEN/releases/download/STOD-GEN_v1.1.1/Data.Samples.zip)

---

## Key Features

- **Automated Bias Correction:** Uses observational data to correct CMIP6 GCM biases.
- **Stochastic Ensemble Generation:** Generates up to 500 rainfall scenarios via Markov Chain + Gamma distribution.
- **Built-in Visual Analytics:** Instant plotting for histograms, monthly trends, and annual totals.
- **Data Export:** Saves generated ensembles directly to CSV for seamless integration with Excel, MATLAB, Python, R, and OriginLab.

---

## What’s New in v1.1.1

### 1. Rebranding & Identity Update
- Software renamed from **ZH-RainSim** to **STOD-GEN** (*STOchastic Downscaling GENerator*).
- Repository URL updated with automatic redirection from legacy links.

### 2. Interface & Usability
- Synchronized application window headers and menu workflows.
- Adjusted interface alignment for higher-DPI displays.

### 3. Stability & Engine Fixes
- Fixed deprecated Pandas offset parameters (updated `'Y'` to `'YE'`).
- Improved exception handling for corrupted or missing input CSV files.
- Optimized executable folder structure for faster startup and improved antivirus compatibility.

---

## License

**Copyright:** MyIPO (Reference: `LY2026P00740`)

- **Academic Research:** Free to use with proper attribution/citation.
- **Funded Research Projects:** Requires a dedicated user license.
- **Commercial Use:** Prohibited without written approval.

---

## Citation

If you use **STOD-GEN** in your academic work, please cite the repository below *(peer-reviewed manuscript citation pending acceptance)*:

```bibtex
@software{stod_gen_2026,
  author       = {Zulkarnain Hassan},
  title        = {STOD-GEN: STOchastic Downscaling GENerator},
  year         = {2026},
  publisher    = {GitHub},
  journal      = {GitHub repository},
  howpublished = {\url{https://github.com/zulkarnainh/STOD-GEN}}
}
