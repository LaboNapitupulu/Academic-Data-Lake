
---

# 📂 Centralized Data Lake: Academic & Research Archive
> **Status:** Active Data Hub | **Focus:** Seamless Cloud Integration & Reproducibility

### 🚀 Filosofi Repositori
Selamat datang di **Centralized Data Lake** saya. Repositori ini dirancang bukan sebagai tempat penyimpanan pasif, melainkan sebagai **Single Source of Truth (SSOT)** untuk berbagai alur kerja analisis data yang saya lakukan di lingkungan *cloud-computing*. 

Dalam pengembangan model *Machine Learning* dan analisis statistik, akses data yang cepat dan stabil adalah kunci. Repositori ini menyediakan *endpoint* data statis yang memungkinkan integrasi langsung ke *environment* seperti Google Colab, RStudio Server, atau Jupyter Notebook tanpa hambatan *local upload*.

---

### 🛠 Arsitektur & Kegunaan
Dataset yang diarsipkan di sini mencakup berbagai domain data yang saya pelajari selama studi **Sains Data**, antara lain:
*   **Time-Series Data:** Digunakan untuk proyek peramalan (Forecasting).
*   **Tabular Structures (CSV/XLSX):** Data mentah untuk pemodelan klasifikasi dan klastering.
*   **Operational Data:** Kumpulan data pendukung untuk simulasi analitik bisnis dan optimasi.

---

### 💻 Cara Mengakses (Direct Link Integration)
Saya menggunakan metode *GitHub Raw Fetching* untuk menjaga konsistensi skrip analisis saya. Berikut adalah contoh bagaimana data dari repositori ini dikonsumsi secara programatis:

**Di Python (Pandas):**
```python
import pandas as pd

# Contoh pemanggilan data raw
url = "https://github.com/LaboNapitupulu/Academic-Data-Lake/raw/refs/heads/main/insurance.csv"
df = pd.read_csv(url)
print(df.head())
```

**Di R (readr):**
```r
library(readr)

# Memuat data langsung dari lake
url <- "https://github.com/LaboNapitupulu/Academic-Data-Lake/raw/refs/heads/main/insurance.csv"
data <- read_csv(url)
head(data)
```

---

### 📊 Domain Konten
Secara garis besar, file-file di sini merepresentasikan perjalanan eksplorasi saya di bidang:
1.  **Analitik Bisnis:** Data transaksional dan operasional.
2.  **Data Mining:** Dataset untuk pengujian algoritma seperti K-Means, SVM, dan Hierarchical Clustering.
3.  **Komputasi Statistik:** Data mentah untuk pengujian distribusi dan uji hipotesis.

---

### ⚠️ Disclaimer
Sebagian besar dataset di sini bersifat **Public/Academic Use**. Jika terdapat dataset yang berasal dari pihak ketiga, hak cipta tetap milik penyedia data asli. Repositori ini ditujukan semata-mata untuk mendukung efisiensi riset dan pembelajaran mandiri.

---

### 📬 Kontak & Portofolio
Ingin melihat bagaimana data-data ini diolah menjadi *insight*? Silakan kunjungi portofolio utama saya di:
👉 **[https://github.com/LaboNapitupulu]**

---
