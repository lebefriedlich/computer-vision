# Handwritten Stenography Recognition with the LION Dataset

Repositori ini merupakan implementasi dan pengembangan ulang dari kode pada artikel [Handwritten stenography recognition and the LION dataset](https://doi.org/10.1007/s10032-024-00479-6) oleh Raphaela Heil dan Malin Nauwerck. Artikel ini memperkenalkan dataset LION dan baseline pertama untuk pengenalan tulisan tangan sistem stenografi Melin dalam bahasa Swedia.

Beberapa bagian kode yang disediakan dalam jurnal tersebut tidak lengkap. Oleh karena itu, saya melengkapinya agar keseluruhan pipeline dapat dijalankan dengan baik dan dapat direproduksi.

## 🔍 Latar Belakang

Stenografi adalah metode penulisan cepat yang digunakan dalam berbagai situasi seperti pencatatan persidangan atau wawancara. Sistem stenografi Melin adalah salah satu metode yang digunakan di Swedia. Dataset LION adalah kumpulan data tulisan tangan stenografi Melin yang ditulis oleh Astrid Lindgren, dan digunakan untuk melatih serta mengevaluasi sistem pengenalan tulisan tangan.

## 🚀 Fitur Utama

- Implementasi model pengenalan tulisan tangan berbasis data LION.
- Penggunaan empat skema encoding untuk menghubungkan tulisan stenografi ke teks biasa.
- Pre-training menggunakan data sintetis dan fine-tuning menggunakan data nyata.
- Evaluasi model menggunakan Character Error Rate (CER) dan Word Error Rate (WER).
- Perbaikan dan pelengkapan kode agar bisa direproduksi sepenuhnya.

## 🐍 Spesifikasi

- Bahasa pemrograman: **Python 3.9**
- Tidak perlu membuat virtual environment, cukup pastikan dependensi terinstal.

## 📦 Dataset

Silakan unduh dataset LION dari Zenodo melalui tautan berikut:

🔗 [https://zenodo.org/record/8249845](https://zenodo.org/record/8249845)

Setelah diunduh, ekstrak ke dalam direktori `data/lion_dataset/`.

## 🔧 Instalasi

Pastikan Python 3.9 telah terpasang, lalu instal dependensi dengan:

```bash
pip install -r requirements.txt
