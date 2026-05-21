# 🚀 N8N AI Workflows & Automation Collection

[![n8n](https://img.shields.io/badge/Automation-n8n-orange?style=for-the-badge&logo=n8n)](https://n8n.io/)
[![LangChain](https://img.shields.io/badge/Framework-LangChain-green?style=for-the-badge)](https://python.langchain.com/)
[![Gemini](https://img.shields.io/badge/AI-Google_Gemini-blue?style=for-the-badge&logo=google)](https://deepmind.google/technologies/gemini/)
[![Supabase](https://img.shields.io/badge/Database-Supabase-emerald?style=for-the-badge&logo=supabase)](https://supabase.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

Selamat datang di repositori **n8n AI Workflows Collection** oleh **Aulia Hakim**. Repositori ini berisi kumpulan alur kerja (*workflows*) automasi menggunakan n8n yang terintegrasi dengan kecerdasan buatan (AI) untuk berbagai studi kasus bisnis seperti Keuangan (*Finance*), Pemasaran (*Marketing*), Sumber Daya Manusia (*SDM/HR*), serta pembuatan Agen AI tanpa koding (*No-Code AI Agents*).

Repositori ini disusun secara rapi dan sistematis berdasarkan materi perkuliahan/pelatihan implementasi AI di dunia industri.

---

## 📌 Daftar Isi
1. [Struktur Repositori](#-struktur-repositori)
2. [Detail Kategori Alur Kerja](#-detail-kategori-alur-kerja)
   - [1. Implementasi AI Keuangan (Finance)](#1-implementasi-ai-keuangan-finance)
   - [2. Implementasi AI Pemasaran (Marketing)](#2-implementasi-ai-pemasaran-marketing)
   - [3. Implementasi AI SDM (Human Resources)](#3-implementasi-ai-sdm-human-resources)
   - [4. Pengembangan Agent AI Tanpa Koding (No-Code AI Agents)](#4-pengembangan-agent-ai-tanpa-koding-no-code-ai-agents)
3. [Panduan Penggunaan & Import](#-panduan-penggunaan--import)
4. [Keamanan & Sanitasi Kredensial](#-keamanan--sanitasi-kredensial)
5. [Lisensi](#-lisensi)

---

## 📂 Struktur Repositori

Berkas-berkas diatur berdasarkan mata kuliah dan pertemuan tugas:

```text
├── 📂 (Root Directory)
│   ├── 📄 README.md                                  # Dokumentasi utama proyek
│   ├── 📄 Latihan Data Flow Lanjutan.docx           # Panduan dokumen data flow lanjutan
│   ├── 📄 TUGAS 1 pengembangan agent ai tanpa koding.pdf # Laporan analisis Agen AI
│   │
│   ├── 📂 [Implementasi AI Keuangan]
│   │   ├── Pertemuan 1 tugas 1 implementasi ai keuangan.json
│   │   ├── Tugas 2 pertemuan 2 implementasi ai keuangan.json
│   │   ├── Tugas 3 pertemuan 3 implementasi ai keuangan.json
│   │   ├── tugas 4 pertemuan 4 implementasi ai keuangan.json
│   │   ├── tugas 5 pertemuan 5 implementasi ai keuangan.json
│   │   ├── Tugas 1 pertemuan 6 implementasi ai keuangan.json
│   │   ├── Tugas 2 pertemuan 6 implementasi ai keuangan.json
│   │   ├── Tugas pertemuan 7 implementasi ai keuangan.json
│   │   └── Tugas pertwmuan 8 implementasi ai keuangan.json
│   │
│   ├── 📂 [Implementasi AI Pemasaran]
│   │   ├── Tugas 1 pertemuan 1 implementasi ai pemasaran.json
│   │   ├── Tugas 2 pertemuan 1 implementasi ai pemasaran.json
│   │   ├── tugas 3 pertemuan 2 implementasi ai pemasaran.json
│   │   ├── Tugas 4 pertemuan 3 implementasi ai pemasaran.json
│   │   ├── Tugas 4 Implementasi AI Pemasaran.json
│   │   ├── Tugas 5 pertemuan 4 Implementasi AI Pemasaran.json
│   │   ├── Tugas 6 pertemuan 5 AI untuk Pemasaran.json
│   │   └── Tugas 7 pertemuan 6 implementasi ai pemasaran.json
│   │
│   ├── 📂 [Implementasi AI SDM / HR]
│   │   ├── Tugas 1 pertemuan 1 implementasi ai sdm.json
│   │   ├── tugas 2 pertemuan 2 implementasi ai sdm.json
│   │   ├── Tugas 3 pertemuan 3 implementasi ai sdm.json
│   │   ├── Tugas 4 pertemuan 4 Implementasi AI sdm.json
│   │   ├── Tugas 5 pertemuan 5 implementasi AI sdm.json
│   │   ├── tugas 6 pertemuan 6 implementasi ai sdm.json
│   │   ├── Tugas 7 pertemuan 7 implementasi ai sdm.json
│   │   └── Tugas 8 pertemuan 8 implementasi ai sdm.json
│   │
│   └── 📂 [Pengembangan Agent AI Tanpa Koding]
│       ├── TUGAS 1 pengembangan agent ai tanpa koding.json
│       ├── TUGAS 2 pengembangan agent ai tanpa koding.json
│       ├── Tugas 4 ai agent tanpa koding.json
│       └── Tugas 5 Ai agent tanpa koding.json
```

---

## 🛠 Detail Kategori Alur Kerja

### 1. Implementasi AI Keuangan (Finance)
Kategori ini berfokus pada automasi data keuangan, pelacakan pengeluaran, pengkategorian transaksi, serta integrasi pemrosesan laporan keuangan berbasis email/notifikasi.
* **Fitur Utama:**
  * Router transaksi otomatis berbasis pengirim email (misalnya memisahkan email tagihan dari Grab, Tokopedia, dan IDCloudHost).
  * Pembuatan ringkasan laporan neraca dan pengeluaran menggunakan model bahasa besar (LLM).
  * Sinkronisasi data ke Google Sheets untuk pencatatan otomatis.
* **Nodes Terkait:** `Switch`, `HTTP Request`, `Google Sheets`, `Gmail Trigger`.

### 2. Implementasi AI Pemasaran (Marketing)
Kategori ini mencakup pembuatan konten otomatis, penulisan artikel SEO, pembuatan video promosi menggunakan AI, dan automasi media sosial.
* **Fitur Utama:**
  * Integrasi dengan **Kie.ai** untuk menghasilkan aset video promosi berbasis teks secara otomatis.
  * Integrasi dengan **imgBB** API untuk hosting aset gambar iklan instan.
  * Pembuatan artikel blog pemasaran otomatis menggunakan API PDFShift untuk konversi HTML ke dokumen PDF profesional.
* **Nodes Terkait:** `HTTP Request (Kie AI, PDFShift, imgBB)`, `Google Drive`, `HTML Parser`.

### 3. Implementasi AI SDM (Human Resources)
Fokus pada automasi rekrutmen, pelacakan kinerja karyawan, sistem pengajuan cuti, reimbursement, serta notifikasi Telegram Chatbot untuk karyawan.
* **Fitur Utama:**
  * Telegram Chatbot interaktif menggunakan Inline Keyboard untuk pengajuan reimbursement, cuti, klaim kesehatan, dan info lembur.
  * Penyaringan resume/CV pelamar kerja secara otomatis menggunakan AI extractor.
  * Pemrosesan data karyawan baru ke database perusahaan.
* **Nodes Terkait:** `Telegram Trigger`, `Telegram Node`, `Set`, `If`.

### 4. Pengembangan Agent AI Tanpa Koding (No-Code AI Agents)
Studi kasus tingkat lanjut dalam merancang sistem RAG (Retrieval-Augmented Generation) menggunakan LangChain di dalam n8n.
* **Fitur Utama:**
  * Desain chatbot pintar RAG yang terhubung dengan **Supabase Vector Store** untuk pencarian data dokumen (seperti kriteria penulisan tugas akhir ilmiah).
  * Penggunaan **Embeddings Google Gemini** untuk representasi teks berdimensi tinggi.
  * Penyimpanan memori obrolan interaktif menggunakan PostgreSQL Chat Memory.
* **Nodes Terkait:** `AI Agent (LangChain)`, `Google Gemini Chat Model`, `Supabase Vector Store`, `Postgres Chat Memory`, `Google Drive (Download PDF)`.

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

## 📄 Lisensi

Repositori ini dilisensikan di bawah lisensi MIT. Silakan gunakan, modifikasi, dan bagikan alur kerja ini untuk kebutuhan akademis maupun komersial Anda.

---
*Dibuat dengan 💻 dan 🤖 oleh [Aulia Hakim](https://github.com/AuliaHakim1).*
