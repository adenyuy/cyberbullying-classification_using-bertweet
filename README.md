# 💬 Klasifikasi Cyberbullying Menggunakan BERTweet

Proyek ini bertujuan untuk membangun dan melatih model *deep learning* canggih untuk mendeteksi dan mengklasifikasikan teks yang mengandung perundungan siber (*cyberbullying*) di media sosial. Dengan memanfaatkan **BERTweet**, sebuah model Transformer yang secara spesifik dilatih pada data Twitter, proyek ini mampu memahami nuansa, slang, dan konteks unik dari percakapan online.

## 📝 Deskripsi Proyek

Perundungan siber merupakan masalah serius di era digital dengan dampak psikologis yang mendalam. Deteksi otomatis menjadi krusial untuk platform online dalam memoderasi konten secara efektif. Proyek ini mengatasi tantangan tersebut dengan mengimplementasikan model klasifikasi teks yang dapat membedakan antara konten yang mengandung perundungan dan yang tidak.

Fokus utama proyek ini adalah pada penggunaan **BERTweet (`vinai/bertweet-base`)** dari Hugging Face, karena model ini memiliki pemahaman superior terhadap teks informal, tagar (#), dan sebutan (@) yang umum dijumpai di platform seperti Twitter.

## ✨ Fitur Utama

* **Model State-of-the-Art:** Menggunakan arsitektur Transformer (BERTweet) yang telah terbukti unggul untuk tugas pemahaman bahasa alami (NLU).
* **Preprocessing Teks Khusus Media Sosial:** Menerapkan teknik pembersihan teks yang dirancang untuk menangani *noise* seperti URL, *emoticon*, dan karakter berulang.
* **Pipeline End-to-End:** Mencakup semua tahapan mulai dari pemrosesan data, pelatihan model, hingga evaluasi performa yang detail.
* **Fokus pada Metrik yang Relevan:** Evaluasi tidak hanya menggunakan akurasi, tetapi juga **F1-Score** dan *Confusion Matrix* yang lebih informatif untuk dataset yang mungkin tidak seimbang.

## 🛠️ Tech Stack & Library

* **Bahasa:** Python 3.9+
* **Model & Tokenisasi:** Hugging Face Transformers
* **Analisis & Manipulasi Data:** Pandas, NumPy
* **Visualisasi & Evaluasi:** Scikit-learn, Matplotlib, Seaborn
* **Lingkungan Eksekusi:** Kaggle Notebooks (dengan akselerasi GPU)

