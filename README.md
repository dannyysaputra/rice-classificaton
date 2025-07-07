# Proyek UAS: Studi Perbandingan Model untuk Klasifikasi Jenis Padi

Repositori ini berisi *file-file* untuk Ujian Akhir Semester (UAS) mata kuliah **Praktik Pembelajaran Mesin**. Proyek ini berfokus pada perbandingan performa tiga model berbeda—*Convolutional Neural Network* (CNN), ResNet-50, dan *Support Vector Machine* (SVM)—dalam tugas klasifikasi lima jenis padi berdasarkan citra digital.

---

## 👨‍💻 Anggota Kelompok

| Nama Lengkap | NIM |
| :--- | :--- |
| Danny Suggi Saputra | 1227050033 |
| Alhan Husen | 1227050015 |
| Alif Firmansyah Putra | 1227050016 |

---

## 📖 Deskripsi Proyek

Tujuan dari proyek ini adalah untuk membangun, melatih, dan mengevaluasi tiga model *machine learning* untuk mengidentifikasi jenis padi secara akurat. Kelima jenis padi yang menjadi target klasifikasi adalah **Arborio, Basmati, Ipsala, Jasmine, dan Karacadag**.

Dengan membandingkan tiga pendekatan yang berbeda (CNN kustom, arsitektur *transfer learning* ResNet-50, dan SVM klasik), penelitian ini bertujuan untuk menentukan model mana yang memberikan performa terbaik untuk dataset ini.

---

## 🗂️ Struktur Repositori

### 📓 Notebook Implementasi Model

Repositori ini berisi tiga *notebook* Jupyter yang masing-masing mengimplementasikan satu model spesifik:

1.  **`CNN.ipynb`**: Berisi kode untuk membangun, melatih, dan mengevaluasi model CNN yang dirancang dari awal.
2.  **`ResNet-50.ipynb`**: Mengimplementasikan pendekatan *transfer learning* menggunakan arsitektur ResNet-50 yang sudah terlatih pada dataset ImageNet.
3.  **`SVM.ipynb`**: Mengimplementasikan model klasifikasi menggunakan *Support Vector Machine*, yang mewakili pendekatan *machine learning* klasik.

### 📄 Artikel Ilmiah (`Studi Perbandingan ResNet50, SVM, dan CNN...`)

Sebagai laporan akhir, kami menyusun sebuah artikel ilmiah yang merangkum keseluruhan proyek. Artikel ini berfungsi sebagai dokumen utama yang menjelaskan:

* **Pendahuluan**: Menjelaskan latar belakang, rumusan masalah, dan tujuan dari studi perbandingan ini.
* **Metode**: Merinci metodologi penelitian, termasuk deskripsi dataset, pra-pemrosesan data, desain arsitektur untuk setiap model, dan metrik evaluasi yang digunakan.
* **Hasil dan Pembahasan**: Menyajikan hasil performa dari ketiga model secara kuantitatif dan kualitatif, serta analisis perbandingan untuk membahas kelebihan dan kekurangan masing-masing model.
* **Kesimpulan**: Merangkum temuan utama dari penelitian dan memberikan rekomendasi model terbaik untuk kasus ini.
