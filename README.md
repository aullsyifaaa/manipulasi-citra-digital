# Manipulasi Citra Digital Menggunakan OpenCV
Project ini dibuat untuk memenuhi Tugas Individu mata kuliah **Pengolahan Sinyal Digital**.Di dalam project ini, dilakukan serangkaian eksperimen manipulasi dasar citra digital menggunakan bahasa pemrograman Python dan beberapa library populer seperti OpenCV, NumPy, dan Matplotlib.

## 👤 Identitas Mahasiswa
* **Nama:** Syifa Aulia Khairunnisa
* **NIM:** 452024618102
* **Mata Kuliah:** Pengolahan Sinyal Digital
* **Topik Tugas:** Manipulasi Citra Digital 

---

## 📝 Deskripsi Singkat Project
Project ini berfokus pada implementasi operasi matematika sederhana pada tingkat pixel citra dan analisis dampaknya terhadap kualitas visual, nilai pixel, kecerahan (*brightness*), kontras (*contrast*), serta detail citra. Eksperimen yang dilakukan meliputi:
1. Membaca citra asli dan konversi warna dari format BGR ke RGB.
2. Mengubah ukuran (*resize*) dua citra berbeda agar memiliki dimensi yang sama.
3. Penggabungan dua citra (*image blending*) dengan variasi kombinasi bobot.
4. Pembuatan citra negatif beserta analisis histogramnya.
5. Penerapan transformasi non-linier Logaritmik.
6. Penerapan transformasi non-linier Gamma (Power-Law).

---

## 🖼️ Citra yang Digunakan
Project ini menggunakan minimal dua citra berbeda dengan karakteristik spasial yang berlainan:
* `image1.jpg`: Digunakan sebagai citra utama dalam eksperimen transformasi spasial (Negative, Log, Gamma).
* `image2.jpg`: Digunakan sebagai citra tekstur/komplemen untuk proses blending.

---

## 🛠️ Library yang Digunakan
Pastikan library berikut sudah terinstall di dalam environment Python Anda:
* **OpenCV (opencv-python):** Untuk operasi I/O citra, konversi warna, resize, dan blending.
* **NumPy:** Untuk manipulasi array matriks pixel dan operasi matematika logaritmik/gamma.
* **Matplotlib:** Untuk visualisasi citra luaran dan plotting histogram.

---

## 📂 Struktur Folder Project
Repositori GitHub ini diatur dengan struktur minimal sebagai berikut:

```text
manipulasi-citra-digital/
├── notebook/
│   └── image_manipulation.ipynb   # File notebook utama eksperimen
├── images/
│   ├── image1.jpg                  # Citra sampel 1
│   └── image2.jpg                  # Citra sampel 2
└── report/
    ├── laporan.pdf                 # Laporan resmi hasil analisis
    ├── README.md                   # Dokumentasi project
    └── requirements.txt            # Daftar dependensi library
