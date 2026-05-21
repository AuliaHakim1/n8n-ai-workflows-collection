# 🚀 N8N AI Workflows & Automation Collection

[![n8n](https://img.shields.io/badge/Automation-n8n-orange?style=for-the-badge&logo=n8n)](https://n8n.io/)
[![LangChain](https://img.shields.io/badge/Framework-LangChain-green?style=for-the-badge)](https://python.langchain.com/)
[![Gemini](https://img.shields.io/badge/AI-Google_Gemini-blue?style=for-the-badge&logo=google)](https://deepmind.google/technologies/gemini/)
[![Supabase](https://img.shields.io/badge/Database-Supabase-emerald?style=for-the-badge&logo=supabase)](https://supabase.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

Selamat datang di repositori **n8n AI Workflows Collection** oleh **Aulia Hakim**. Repositori ini berisi kumpulan alur kerja (*workflows*) automasi menggunakan n8n yang terintegrasi dengan kecerdasan buatan (AI) untuk berbagai studi kasus bisnis seperti Keuangan (*Finance*), Pemasaran (*Marketing*), Sumber Daya Manusia (*SDM/HR*), serta pembuatan Agen AI tanpa koding (*No-Code AI Agents*).

Seluruh berkas workflow dalam repositori ini telah dinamai ulang dengan mencantumkan **fungsi/tujuan workflow di awal nama berkas** untuk memudahkan navigasi.

---

## 📌 Daftar Isi
1. [Struktur Repositori](#-struktur-repositori)
2. [Detail Kategori Alur Kerja](#-detail-kategori-alur-kerja)
   - [1. Implementasi AI Keuangan (Finance)](#1-implementasi-ai-keuangan-finance)
   - [2. Implementasi AI Pemasaran (Marketing)](#2-implementasi-ai-pemasaran-marketing)
   - [3. Implementasi AI SDM (Human Resources)](#3-implementasi-ai-sdm-human-resources)
   - [4. Pengembangan Agent AI Tanpa Koding (No-Code AI Agents)](#4-pengembangan-agent-ai-tanpa-koding-no-code-ai-agents)
   - [5. Latihan & Utilitas Umum](#5-latihan--utilitas-umum)
3. [Panduan Penggunaan & Import](#-panduan-penggunaan--import)
4. [Keamanan & Sanitasi Kredensial](#-keamanan--sanitasi-kredensial)
5. [Lisensi](#-lisensi)

---

## 📂 Struktur Repositori

Berkas-berkas diatur secara modular berdasarkan fungsinya:

```text
├── 📂 (Root Directory)
│   ├── 📄 README.md                                  # Dokumentasi utama proyek
│   ├── 📄 Latihan Data Flow Lanjutan.docx           # Panduan dokumen data flow lanjutan
│   ├── 📄 TUGAS 1 pengembangan agent ai tanpa koding.pdf # Laporan analisis Agen AI
│   │
│   ├── 📂 [Implementasi AI Keuangan]
│   │   ├── 📄 workflow form to pdf invoice Pertemuan 1 tugas 1 implementasi ai keuangan.json
│   │   ├── 📄 workflow transaction router sheet Tugas 2 pertemuan 2 implementasi ai keuangan.json
│   │   ├── 📄 workflow sheet analytics telegram Tugas 2 pertemuan 6 implementasi ai keuangan.json
│   │   ├── 📄 workflow sheets deduplication Tugas 3 pertemuan 3 implementasi ai keuangan.json
│   │   ├── 📄 workflow bank data reconciliation tugas 4 pertemuan 4 implementasi ai keuangan.json
│   │   ├── 📄 workflow stock news aggregator telegram tugas 5 pertemuan 5 implementasi ai keuangan.json
│   │   ├── 📄 workflow email parser llm telegram Tugas 1 pertemuan 6 implementasi ai keuangan.json
│   │   ├── 📄 workflow transactions analysis telegram Tugas pertemuan 7 implementasi ai keuangan.json
│   │   └── 📄 workflow stock prices watcher Tugas pertwmuan 8 implementasi ai keuangan.json
│   │
│   ├── 📂 [Implementasi AI Pemasaran]
│   │   ├── 📄 workflow form email response Tugas 1 pertemuan 1 implementasi ai pemasaran.json
│   │   ├── 📄 workflow image generation telegram Tugas 2 pertemuan 1 implementasi ai pemasaran.json
│   │   ├── 📄 workflow image generation drive tugas 3 pertemuan 2 implementasi ai pemasaran.json
│   │   ├── 📄 workflow sheet notifications telegram Tugas 4 pertemuan 3 implementasi ai pemasaran.json
│   │   ├── 📄 workflow scheduled pdf report Tugas 4 Implementasi AI Pemasaran.json
│   │   ├── 📄 workflow scheduled pdf report Tugas 4 Implementasi AI Pemasaran (1).json
│   │   ├── 📄 workflow scheduled pdf report Tugas 5 pertemuan 4 Implementasi AI Pemasaran.json
│   │   ├── 📄 workflow marketing analytics telegram Tugas 6 pertemuan 5 AI untuk Pemasaran.json
│   │   └── 📄 workflow interactive content generator telegram Tugas 7 pertemuan 6 implementasi ai pemasaran.json
│   │
│   ├── 📂 [Implementasi AI SDM / HR]
│   │   ├── 📄 workflow employee onboarding Tugas 1 pertemuan 1 implementasi ai sdm.json
│   │   ├── 📄 workflow batch resume screener telegram tugas 2 pertemuan 2 implementasi ai sdm.json
│   │   ├── 📄 workflow resume parser pdfco Tugas 3 pertemuan 3 implementasi ai sdm.json
│   │   ├── 📄 workflow interactive hr agent telegram Tugas 4 pertemuan 4 Implementasi AI sdm.json
│   │   ├── 📄 workflow telegram hr request router Tugas 5 pertemuan 5 implementasi AI sdm.json
│   │   ├── 📄 workflow employee leave validator tugas 6 pertemuan 6 implementasi ai sdm.json
│   │   ├── 📄 workflow resume screening pipeline Tugas 7 pertemuan 7 implementasi ai sdm.json
│   │   └── 📄 workflow batch employee evaluator Tugas 8 pertemuan 8 implementasi ai sdm.json
│   │
│   ├── 📂 [Pengembangan Agent AI Tanpa Koding]
│   │   ├── 📄 workflow chatbot groq TUGAS 1 pengembangan agent ai tanpa koding.json
│   │   ├── 📄 workflow chatbot sheet agent TUGAS 2 pengembangan agent ai tanpa koding.json
│   │   ├── 📄 workflow chatbot rag supabase Tugas 4 ai agent tanpa koding.json
│   │   └── 📄 workflow chatbot rag postgres memory Tugas 5 Ai agent tanpa koding.json
│   │
│   └── 📂 [Latihan & Utilitas Umum]
│       ├── 📄 workflow chatbot sheets 13 maret.json
│       ├── 📄 workflow chatbot sheets 30 maret.json
│       ├── 📄 workflow telegram monitoring capaian.json
│       ├── 📄 workflow error handler telegram notifier eror triger.json
│       ├── 📄 workflow latihan data merging merge.json
│       ├── 📄 workflow latihan merging data My workflow (2).json
│       ├── 📄 workflow rss reader loop My workflow 3.json
│       └── 📄 workflow simple gemini chatbot tugas 7.json
```

---

## 🛠 Detail Kategori Alur Kerja

### 1. Implementasi AI Keuangan (Finance)
Kategori ini berfokus pada automasi data keuangan, pelacakan pengeluaran, pengkategorian transaksi, serta integrasi pemrosesan laporan keuangan berbasis email/notifikasi.
* **Fitur Utama:**
  * **Router Transaksi Otomatis:** Memisahkan email tagihan (Grab, Tokopedia, dan IDCloudHost) dan mencatatnya ke Google Sheets.
  * **Analisis Data & Konsiliasi:** Pembersihan data bank dan rekonsiliasi pengeluaran secara terjadwal.
  * **Notifikasi Saham:** Pelacak harga saham berkala (AAPL, MSFT) yang dikirim langsung ke Telegram.
* **Berkas Penting:**
  * `workflow transaction router sheet Tugas 2 pertemuan 2 implementasi ai keuangan.json`
  * `workflow stock prices watcher Tugas pertwmuan 8 implementasi ai keuangan.json`

### 2. Implementasi AI Pemasaran (Marketing)
Kategori ini mencakup pembuatan konten otomatis, penulisan artikel SEO, pembuatan video promosi menggunakan AI, dan automasi media sosial.
* **Fitur Utama:**
  * **Video & Image Generation:** Integrasi dengan **Kie.ai** dan **imgBB** API untuk memproses video & gambar promosi secara otomatis berdasarkan data formulir.
  * **Laporan PDF Otomatis:** Mengubah HTML marketing menjadi dokumen PDF profesional menggunakan API PDFShift.
  * **Chatbot Konten Interaktif:** Membuat draf ide konten pemasaran melalui perintah di Telegram Chatbot.
* **Berkas Penting:**
  * `workflow video generation Tugas 2 Implementasi AI untuk Pemasaran.json`
  * `workflow interactive content generator telegram Tugas 7 pertemuan 6 implementasi ai pemasaran.json`

### 3. Implementasi AI SDM (Human Resources)
Fokus pada automasi rekrutmen, pelacakan kinerja karyawan, sistem pengajuan cuti, reimbursement, serta notifikasi Telegram Chatbot untuk karyawan.
* **Fitur Utama:**
  * **Telegram HR Bot:** Chatbot interaktif menggunakan Inline Keyboard untuk pengajuan reimbursement, cuti, klaim kesehatan, dan info lembur.
  * **Resume Screener:** Membaca dokumen PDF lamaran (via PDF.co) dan melakukan scoring kecocokan kandidat secara otomatis menggunakan OpenRouter LLM.
  * **Validasi Cuti Karyawan:** Webhook otomatis untuk memvalidasi sisa cuti karyawan di Google Sheets dan mengirimkan notifikasi persetujuan via Email.
* **Berkas Penting:**
  * `workflow telegram hr request router Tugas 5 pertemuan 5 implementasi AI sdm.json`
  * `workflow resume screening pipeline Tugas 7 pertemuan 7 implementasi ai sdm.json`

### 4. Pengembangan Agent AI Tanpa Koding (No-Code AI Agents)
Studi kasus tingkat lanjut dalam merancang sistem RAG (Retrieval-Augmented Generation) menggunakan LangChain di dalam n8n.
* **Fitur Utama:**
  * **Sistem RAG Pintar:** Menghubungkan **Supabase Vector Store** dengan dokumen PDF untuk pencarian dokumen pintar (seperti kriteria penulisan karya ilmiah).
  * **Memory PostgreSQL:** Menyimpan riwayat obrolan pengguna di database PostgreSQL secara terintegrasi.
* **Berkas Penting:**
  * `workflow chatbot rag supabase Tugas 4 ai agent tanpa koding.json`
  * `workflow chatbot rag postgres memory Tugas 5 Ai agent tanpa koding.json`

---

## 📥 Panduan Penggunaan & Import

Untuk menggunakan salah satu workflow di atas pada instansi n8n lokal atau cloud Anda:

1. **Unduh File JSON:** Pilih berkas `.json` dari repositori ini yang ingin Anda gunakan.
2. **Import ke n8n:**
   * Buka *dashboard* n8n Anda.
   * Buat workflow baru.
   * Klik ikon menu tiga titik di pojok kanan atas, lalu pilih **Import from File**.
   * Pilih berkas `.json` yang sudah Anda unduh.
3. **Konfigurasi Kredensial:**
   * Atur kembali kredensial (API Key) untuk layanan yang digunakan (seperti Google Gemini, Supabase, Google Drive, Telegram, PDFShift, dll.) pada masing-masing node yang bersangkutan.
4. **Jalankan:** Klik **Active** untuk mengaktifkan alur kerja secara terus-menerus.

---

## 🔐 Keamanan & Sanitasi Kredensial

> [!IMPORTANT]
> Seluruh alur kerja dalam repositori ini telah melalui proses pembersihan (**sanitization**). Semua kunci API sensitif seperti PDFShift Key, Kie AI Key, dan imgBB Token telah disensor dan digantikan dengan placeholder seperti:
> * `YOUR_PDFSHIFT_API_KEY`
> * `YOUR_KIE_AI_API_KEY`
> * `YOUR_IMGBB_API_KEY`
>
> Pastikan untuk mengisi nilai-nilai ini dengan kunci API pribadi Anda sebelum menjalankan workflow di lingkungan n8n Anda sendiri.

---


*Dibuat oleh [Aulia Hakim](https://github.com/AuliaHakim1).*
