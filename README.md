# 🧠 MMR Summarization Project

Proyek ini merupakan implementasi metode **Maximal Marginal Relevance (MMR)** untuk peringkasan teks otomatis berita berbahasa Indonesia. Fokus penelitian adalah **perbandingan Cosine Similarity dan Euclidean Distance** dalam MMR, serta evaluasi dengan **ROUGE Score, Precision, Recall, dan F-Measure**.

## 📂 Struktur Folder
## 📂 Struktur Folder

```
├── ringkasan_mmr_cosine.ipynb          # Peringkasan MMR dengan Cosine Similarity
├── ringkasan_mmr_euclidean.ipynb       # Peringkasan MMR dengan Euclidean Distance
├── evaluasi_peringkasan_mmr.ipynb      # Evaluasi hasil peringkasan
├── hasil_evaluasi.csv                  # File hasil evaluasi ROUGE, Precision, Recall, F1
├── README.md                           # Penjelasan proyek
└── .gitignore                          # File/folder yang tidak ikut di-push ke GitHub
```


## 📝 Metode

1. **Preprocessing** teks menggunakan tokenisasi, case folding, filtering, stemming (Sastrawi).
2. **TF-IDF** digunakan sebagai bobot untuk menghitung similaritas antar kalimat.
3. **MMR** diterapkan dengan dua pendekatan:
   - Cosine Similarity
   - Euclidean Distance
4. **Evaluasi** dilakukan menggunakan:
   - ROUGE-1, ROUGE-2, ROUGE-L
   - Precision, Recall, F-Measure

## 📊 Dataset

Dataset terdiri dari:
- 100 teks berita asli (sumber: Kompas)
- Ringkasan ahli (30% dari teks asli)

## 📈 Hasil Evaluasi

Disimpan dalam file `hasil_evaluasi.csv`, berisi skor ROUGE, Precision, Recall, dan F1 masing-masing metode.

## 🤖 Tools

- Python
- Google Colab
- Sastrawi
- Scikit-learn
- Rouge-score

## 👤 Author

- Nama: *Sicillia Putri Aisyah*  
- Institusi: *Institut Teknologi Sumatera*  

---

## 📌 Catatan

Proyek ini digunakan untuk keperluan tugas akhir/skripsi.  
Silakan fork, beri bintang ⭐, atau gunakan sebagai referensi.


