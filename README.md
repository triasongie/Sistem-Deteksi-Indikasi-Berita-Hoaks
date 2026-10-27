Sistem Deteksi Indikasi Awal Berita Hoaks Berbahasa Indonesia

Aplikasi berbasis web untuk mendeteksi indikasi awal berita hoaks berbahasa Indonesia menggunakan algoritma Multinomial Naïve Bayes dengan pembobotan kata TF-IDF.

Aplikasi ini dikembangkan sebagai sarana untuk membantu pengguna mengenali indikasi berita hoaks berdasarkan pola teks yang dipelajari dari dataset. Hasil analisis bukan merupakan verifikasi kebenaran berita secara faktual, sehingga pengguna tetap perlu melakukan pemeriksaan lebih lanjut terhadap sumber dan isi berita.

🌐 Demo Aplikasi

Coba aplikasi secara langsung melalui tautan berikut:

Sinyal Hoaks — Buka Aplikasi

✨ Fitur

Deteksi Indikasi Berita: Mengklasifikasikan teks berita ke dalam kategori hoaks atau bukan hoaks.

Input Judul dan Isi Berita: Pengguna dapat memasukkan judul berita secara opsional dan isi berita sebagai teks utama untuk dianalisis.

Confidence Score: Menampilkan skor keyakinan model terhadap hasil klasifikasi.

Riwayat Analisis Sesi: Menyimpan hasil analisis selama sesi aplikasi berlangsung.

Reset Analisis: Memungkinkan pengguna menghapus input dan memulai analisis baru.

🛠️ Teknologi yang Digunakan

Python — bahasa pemrograman.

Streamlit — framework pengembangan aplikasi web.

Pandas — pengolahan dataset.

Scikit-learn — implementasi TF-IDF, algoritma Multinomial Naïve Bayes, dan evaluasi model.

Sastrawi — preprocessing teks bahasa Indonesia, termasuk stemming.

Pickle — penyimpanan dan pemuatan model klasifikasi serta vectorizer TF-IDF.
