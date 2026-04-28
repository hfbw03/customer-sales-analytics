# Customer Analytics & Sales Dashboard

End-to-end Data Analytics Portfolio Project menggunakan dataset Online Retail II.

## Overview

Proyek ini menganalisis data transaksi sebuah UK-based online retail untuk menjawab dua pertanyaan bisnis utama:
1. **Siapa pelanggan paling valuable, dan bagaimana cara mempertahankan mereka?**
2. **Bagaimana tren performa penjualan, dan di mana peluang untuk meningkatkannya?**

## Dataset

- **Sumber**: [Online Retail II — UCI Machine Learning Repository](https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)
- **Periode**: Desember 2009 — Desember 2011
- **Ukuran**: 1.067.371 transaksi, 8 kolom
- Setelah download, simpan file di: `data/raw/online_retail_II.csv`

## Tech Stack

| Kategori | Tools |
|---|---|
| Language | Python 3.10+ |
| Data Manipulation | Pandas, NumPy |
| Database | SQLite |
| Visualization | Matplotlib, Seaborn, Plotly |
| Machine Learning | Scikit-learn |
| Dashboard | Tableau Public |
| Version Control | Git + GitHub |
| Environment | VS Code + Jupyter Extension |

## Struktur Proyek
```
customer-sales-analytics/
├── data/
│   └── cleaned/          ← cleaned CSV files
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_sql_exploration.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_customer_analytics.ipynb
│   └── 05_sales_analytics.ipynb
├── reports/              ← output visualisasi (.png)
├── requirements.txt
└── README.md
```

## Alur Analisis

| Phase | Deskripsi | Status |
|---|---|---|
| 1 | Business Understanding | ✅ |
| 2 | Data Collection & Setup | ✅ |
| 3 | Data Cleaning & Preprocessing | ✅ |
| 4 | SQL Exploration & Querying | ✅ |
| 5 | Exploratory Data Analysis | ✅ |
| 6 | Customer Analytics (RFM, K-Means, Cohort) | ✅ |
| 7 | Sales Analytics | ✅ |
| 8 | Dashboard Development | 🔄 In Progress |
| 9 | Documentation & Publishing | 🔄 In Progress |

## Key Findings

- **Champions (22.1%)** menghasilkan rata-rata £9.143 per customer
- **At Risk segment (10.5%)** adalah prioritas retensi - pernah bertransaksi £4.244 tapi sudah 359 hari tidak aktif
- **Top 21.7% produk** menghasilkan 80% total revenue (Pareto Principle)
- **Peak season Q4** konsisten di kedua tahun - Oktober & November tertinggi
- **Cancellation rate 18.32%** namun hanya berdampak 8.08% terhadap revenue
- **Japan (41.1%)** memiliki cancellation rate tertinggi - lebih dari 2x rata-rata

## Setup & Instalasi
```bash
# Clone repository
git clone https://github.com/username/customer-sales-analytics.git
cd customer-sales-analytics

# Install dependencies
pip install -r requirements.txt

# Download dataset dan simpan di:
# data/raw/online_retail_II.csv

# Jalankan notebook secara berurutan:
# 01 → 02 → 03 → 04 → 05
```

## Slide Presentasi
[Slide untuk proyek dapat diakses di link ini.](https://www.canva.com/design/DAHEGWqurCI/y1wu5YKT5ylNbpC3O2usng/view?utm_content=DAHEGWqurCI&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hddf695896b)

## Dashboard

Dashboard interaktif telah berhasil dipublish di Tableau Public, menampilkan hasil analisis Sales Overview dalam satu halaman yang komprehensif. [Dashboard bisa diakses di link ini.](https://public.tableau.com/app/profile/hanz.wewengkang/viz/RetailAnalyticsSalesDashboard/SalesOverviewFloat) 

---

*Proyek ini dibuat sebagai bagian dari portfolio Data Analytics.*
