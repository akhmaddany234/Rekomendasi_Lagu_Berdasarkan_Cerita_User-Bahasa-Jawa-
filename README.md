# 🎵 Rekomendasi Lagu Berdasarkan Cerita User (Bahasa Jawa)

Proyek ini merupakan sistem rekomendasi lagu berbasis cerita yang dibuat untuk mata kuliah *Pemrosesan Teks* di Program Studi S1 Sains Data, Universitas Negeri Surabaya. Sistem ini memungkinkan pengguna menuliskan cerita pendek dalam Bahasa Jawa, lalu akan diberikan rekomendasi lagu-lagu Jawa yang sesuai berdasarkan lirik dan suasana cerita tersebut.

## Tujuan

- Membangun sistem rekomendasi lagu yang memahami konteks emosional cerita pengguna.
- Mempromosikan dan memanfaatkan kekayaan budaya lagu-lagu berbahasa Jawa.
- Mengintegrasikan teknik NLP seperti TF-IDF, Word2Vec, K-Means dan Cosine Similarity untuk mencocokkan cerita dengan lirik lagu.


## Teknologi dan Teknik yang Digunakan

- **Web Scraping**: Mengambil data dari [liriklaguindonesia.net](https://liriklaguindonesia.net) (judul lagu, pencipta, lirik berbahasa Jawa).
- **Preprocessing Teks**: Lower casing, stopword removal, stemming/lemmatization, normalisasi angka, dan spelling correction.
- **Feature Engineering**: TF-IDF, Word2Vec, Bag of Words.
- **Clustering**: K-MEANS digunakan untuk mengelompokkan 3 jenis lagu untuk mengetahui hasil inputan user masuk tergolong cluster berapa
- **Similarity Matching**: Menggunakan Cosine Similarity untuk mencocokkan cerita dengan lirik lagu yang paling relevan.



