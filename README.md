# 🧠 Employee Burnout Risk Prediction System

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk mendeteksi risiko **Burnout** (kelelahan kerja) pada karyawan secara otomatis menggunakan algoritma **Machine Learning**. Sistem ini mengklasifikasikan karyawan ke dalam tiga tingkat risiko: **Low**, **Medium**, atau **High** berdasarkan pola jam kerja, tingkat stres, dan kualitas tidur.

Analisis ini membantu perusahaan melakukan deteksi dini agar kesejahteraan mental karyawan tetap terjaga sebelum produktivitas menurun.

## 📊 Dataset Overview
Dataset yang digunakan (`mental_health_productivity.csv`) mencakup indikator seperti:
- **Stress Level:** Skala stres karyawan (1-10).
- **Work Hours Per Week:** Total jam kerja dalam seminggu.
- **Sleep Hours:** Rata-rata waktu tidur harian.
- **Mental Health Support Access:** Akses ke dukungan kesehatan mental.
- **Burnout Risk (Target):** Kategori risiko yang ingin diprediksi.

## 🚀 Cara Menjalankan Proyek
Untuk mencoba program ini di komputer Anda sendiri, ikuti langkah mudah berikut:

1.  **Unduh File Utama:**
    Download dua file berikut dari repository ini:
    *   `klasifikasi_burnout_risk.py` (Script Python Utama)
    *   `mental_health_productivity.csv` (Dataset)
2.  **Letakkan dalam Satu Folder:**
    Pastikan kedua file tersebut berada di **folder yang sama**.
3.  **Instal Library (Jika Belum Ada):**
    Buka terminal/command prompt dan jalankan perintah:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
    ```
4.  **Jalankan Program:**
    Ketik perintah berikut di terminal:
    ```bash
    python klasifikasi_burnout_risk.py
    ```

## 🔍 Temuan Utama (Insights)
Berdasarkan hasil pemodelan menggunakan **Random Forest** dan teknik **SMOTE**:
*   **Stress Level** adalah faktor paling dominan yang menentukan apakah seseorang berisiko tinggi mengalami burnout.
*   **Sleep Hours** yang rendah berkontribusi besar terhadap peningkatan risiko kelelahan kerja.
*   Model ini mampu memberikan **prediksi otomatis** untuk membantu HRD mengambil tindakan pencegahan lebih awal.

---

### 👨‍💻 Disusun Oleh:
**[Annisa Tristanti]**

🔗 **Mari Terkoneksi di LinkedIn:**
[Klik di Sini untuk Profil LinkedIn Saya](https://www.linkedin.com/in/annisatristanti/)

---
*Proyek ini dikembangkan sebagai bagian dari portofolio Analisis Data dan Machine Learning.*
