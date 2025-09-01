# Content Detection Analysis: Differentiating Human vs. AI-Generated Text
Project Overview
Proyek ini bertujuan untuk menganalisis dan mengidentifikasi fitur-fitur pembeda antara konten teks yang ditulis oleh manusia dan yang dihasilkan oleh kecerdasan buatan (AI). Dengan menggunakan dataset yang berisi berbagai jenis teks beserta metrik linguistiknya, kami melakukan analisis data eksplorasi (EDA) untuk menemukan pola dan wawasan yang dapat digunakan sebagai dasar untuk membangun model deteksi konten AI. Analisis mencakup perbandingan distribusi data, keragaman leksikal, dan skor sentimen.

Dataset yang digunakan dalam proyek ini adalah ai_human_content_detection_dataset.csv. Anda dapat mengakses file mentahnya melalui link berikut di dalam repository ini.
Link: ai_human_content_detection_dataset.csv 

Dataset ini terdiri dari kolom-kolom berikut:
text_content: Teks asli.
content_type: Kategori konten (misalnya, blog_post, news_article).
word_count, character_count, sentence_count: Metrik dasar teks.
lexical_diversity: Ukuran keragaman kosakata.
flesch_reading_ease, gunning_fog_index: Skor keterbacaan teks.
sentiment_score: Skor sentimen teks (positif, negatif, netral).
label: Label klasifikasi, di mana 0 adalah Human-Written dan 1 adalah AI-Generated. 

Insight & Findings

Berdasarkan analisis data eksplorasi yang telah dilakukan yaitu:
Dataset Sangat Seimbang: Jumlah sampel antara teks buatan manusia (684 sampel) dan buatan AI (683 sampel) hampir sama. Ini merupakan kondisi ideal untuk melatih model machine learning yang tidak bias.

Distribusi Konten Merata: Tidak ada jenis konten yang mendominasi dataset. Jenis tulisan seperti academic paper, news article, dan blog post memiliki proporsi yang relatif setara, membuat analisis lebih general.

Keragaman Leksikal Manusia Sedikit Lebih Unggul: Teks yang ditulis oleh manusia cenderung memiliki keragaman kosakata (lexical_diversity) yang sedikit lebih tinggi dan bervariasi dibandingkan dengan teks buatan AI. Teks AI tampak lebih konsisten dalam penggunaan kosakatanya.

Pola Sentimen Serupa: Tidak ditemukan perbedaan signifikan dalam distribusi skor sentimen antara teks buatan AI dan manusia. Keduanya mayoritas memiliki sentimen yang netral hingga sedikit positif.


AI Support Explanation
Dalam pengerjaan proyek ini, saya mendapatkan dukungan dari IBM skilbuild, sebuah Large Language Model dari IBM:

Brainstorming & Ideasi: Membantu memberikan ide-ide visualisasi data yang relevan untuk menggali wawasan dari dataset.

Code Generation: Menulis kode Python menggunakan library pandas, matplotlib, dan seaborn untuk memuat data, membersihkannya, dan membuat berbagai grafik visualisasi seperti bar chart, box plot, dan histogram.

Analisis & Interpretasi: Membantu menafsirkan hasil dari visualisasi data untuk merumuskan insight & findings yang disajikan di atas.

Problem Solving: Memberikan solusi untuk masalah teknis yang muncul, seperti mengatasi kegagalan otentikasi git push ke GitHub dengan Personal Access Token (PAT).


