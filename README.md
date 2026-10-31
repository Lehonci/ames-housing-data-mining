# Ames Housing Data Mining Analysis (CRISP-DM Approach)

Project ini berisi analisis Data Mining untuk memprediksi harga rumah menggunakan dataset Ames Housing dengan mengimplementasikan metodologi **CRISP-DM** (Cross-Industry Standard Process for Data Mining).

## Live Interactive Report
Laporan lengkap hasil analisis dan visualisasi dapat diakses secara langsung melalui link berikut:
[**Lihat Laporan Interactive HTML**](https://lehonci.github.io/ames-housing-data-mining/)

## Tech Stack & Tools
* **Language**: R
* **Framework/Format**: R Markdown (Pandoc)
* **Methodology**: CRISP-DM (Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, Deployment)

## Struktur Repositori
* `notebooks/`: Kode sumber R Markdown (`.Rmd`).
* `docs/`: Output render HTML yang di-host via GitHub Pages.

## Data Source
Dataset tidak diunggah langsung ke repositori ini karena diakses secara programmatic menggunakan package R [`AmesHousing`](https://cran.r-project.org/package=AmesHousing):

```R
# Memuat dataset langsung di R
install.packages("AmesHousing")
library(AmesHousing)
ames_data <- make_ames()
