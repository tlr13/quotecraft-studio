# HANDOFF_1.md — Migrasi Proyek Freelance `QuoteCraft Studio`

> **Untuk Agent di Akun Baru (`quotecraft`):** Baca seluruh dokumen ini sebagai sumber kebenaran (*single source of truth*). Seluruh tahap strategi, validasi teknis, audit CV/portofolio, pemilihan niche, dan arsitektur pemisahan akun **sudah selesai dan disepakati**. **Jangan mengulang teori dasar freelance** — langsung lanjutkan ke tahap eksekusi sesuai permintaan user.

---

## 1. Tujuan Utama & Konteks Masalah

### Profil Founder
- **Nama Legal (KYC/Invoice/W-8BEN/Wise/Payoneer/Fiverr):** Wahyu Pamungkas
- **Nama Panggilan:** Imung
- **Lokasi & Zona Waktu:** Indonesia (WITA / UTC+8)
- **Bahasa:** Bahasa Indonesia (Native), **Bahasa Inggris (Professional Working / fasih komunikasi & negosiasi klien global)**, Bahasa Jepang (Intermediate speaking/listening).
- **Latar Pendidikan & Pengalaman:** Lulusan **D3 Perpajakan PKN STAN** (GPA 3.43/4.00, Brevet A & B, sertifikasi Penilaian/Pemeriksaan & Keberatan Pajak Daerah), 3+ tahun sebagai Pengolah Data & Informasi (Bapenda Kutai Barat). Kuat dalam logika angka, rumus perhitungan, Power BI, Excel/Google Sheets, serta menguasai Adobe Premiere Pro, After Effects, Illustrator, Photoshop, CapCut, dan Canva.
- **Bukti Teknis Nyata (*Live Production* — dari audit `Portfolio_Web_PPID_Wahyu_Pamungkas.pdf`):** Sudah berhasil merancang, membangun, dan men-deploy **2 aplikasi web produksi live dengan biaya server \$0/bulan** menggunakan **HTML5/CSS3/Vanilla JS (GitHub Pages) + Google Apps Script serverless backend (Fetch API)** lengkap dengan:
  - Dynamic conditional form validation
  - Client-side image/document compression via HTML5 `<canvas>`
  - Real-time status lookup & interactive filterable/groupable transparency data grid
  - Automated privacy masking, XSS-safe rendering, WCAG accessibility toolbar (font scaling, high contrast, Web Speech API voice narration), dan Cloudflare Turnstile.

### Tujuan Proyek & Batasan Operasional
- **Tujuan:** Membangun bisnis freelance global berbayaran tertinggi dengan waktu kerja seminimal mungkin per proyek, menggunakan **modal awal Rp 0**.
- **Model Kerja:** Mengotomatisasi **85–95% produksi teknis** memakai Antigravity (desain, coding, skrip backend, dokumentasi, revisi). Founder fokus pada akuisisi/komunikasi klien, QA, dan pengiriman akhir (**target 2–4 jam kerja efektif per klien** setelah Template Master selesai — cocok untuk jadwal malam/akhir pekan di luar jam kerja utama).
- **Status Usaha:** Berjalan sebagai solo freelancer (direct pribadi) memakai nama studio di website & invoice; rencana naik ke **PT Perorangan** saat omzet/klien korporasi stabil (siap memakai **W-8BEN** untuk klien AS).
- **Batasan Etis:** Patuh penuh terhadap aturan seluruh platform — **tanpa** bot auto-spam, auto-bid, atau bypass anti-bot/CAPTCHA.

---

## 2. Keputusan Desain, Strategi & Arsitektur yang Sudah Disepakati

### A. Identitas Brand, Positioning & Privasi
- **Nama Brand/Studio:** **`QuoteCraft Studio`**
  - Tanda tangan komunikasi: **`Wahyu Pamungkas — Founder, QuoteCraft Studio`**
  - Dokumen legal, rekening pembayaran (Wise/Payoneer), Fiverr/Upwork, Invoice, & W-8BEN wajib memakai nama asli **`Wahyu Pamungkas`** (header invoice tetap `QuoteCraft Studio`).
  - **Hindari inisial `WP`** (di pasar web global otomatis dipersepsikan sebagai jasa WordPress biasa).
- **Positioning Profesional:** **`Serverless Web, Interactive Quote Calculators & Workflow Automation Builder`**
  - **ATURAN KERAS:** **JANGAN** gunakan istilah **`"Vibe Coding"`** di profil, CV global, website, atau materi penawaran klien AS (menurunkan persepsi kualitas engineering & harga jual).
- **Pemisahan Privasi Total (WAJIB — Status ASN):**
  - Seluruh akun QuoteCraft Studio (akun Antigravity `quotecraft`, Email Bisnis, Instagram Bisnis, GitHub/Cloudflare studio, Cal.com, Fiverr) **dipisahkan 100%** dari akun pribadi (`instagram.com/imungcobacoba`, email pribadi `wahyupamungkaspml@gmail.com`, LinkedIn pribadi) dan **dilarang keras memakai atribut/file instansi Bapenda**.
  - **1 Akun Sosmed Lintas Niche:** Tidak perlu membuat akun Instagram baru saat ekspansi ke niche lain selama masih satu rumpun solusi (Conversion Pages, Quote Calculators, Dashboards, Workflow Tools) — cukup pisahkan URL halaman demonya.

### B. Target Pasar, Niche #1 & Pricing
- **Target Pasar Utama:** **Amerika Serikat (English, USD)** — willingness-to-pay tertinggi; aset langsung kompatibel untuk ekspansi ke Australia & UK.
- **Niche #1 (Eksekusi Pertama):** **High-Ticket US Home Services — Roofing & Home Remodeling (Kitchen/Bath)**.
  - *Alasan menang:* Nilai 1 proyek klien AS **\$15.000–\$65.000** (ROI kalkulator sangat jelas), prospek melimpah di Google Maps & Meta Ad Library, keputusan owner cepat (1–7 hari), **nol hambatan regulasi data sensitif**, dan 1 aset demo dapat langsung membuka 3 jalur pendapatan (Direct Contractor + White-Label Agensi Iklan AS + Upsell Workflow Automation).
- **Struktur Paket Harga (USD):**
  - **Starter (\$850):** High-Converting Landing Page + Interactive Multi-Step Instant Quote Calculator.
  - **Growth (\$1.400):** Starter + Serverless Google Apps Script Backend (Auto-Log Lead CRM ke Google Sheets + Instant Email Alerts — **\$0/bulan biaya SaaS**).
  - **Pro (\$2.100):** Growth + Project Photo Upload dengan `<canvas>` auto-compression ke Google Drive + Custom Tracking / A-B Variant.
  - **Upsell Retainer:** Monthly Care & Optimization (**\$150–\$300/bulan**).
  - **White-Label Agency Bulk:** **\$500–\$1.000/halaman** atau paket bulanan **\$2.000–\$3.500/bulan** (4 halaman).
- **Strategi Akuisisi Utama ("Show, Don't Tell"):**
  1. Ambil prospek kontraktor AS dari Google Maps / Meta Ad Library → kustomisasi Template Master 5–10 menit via `CLIENT_CONFIG` → deploy link preview gratis → kirim pesan sopan (dapat disertai video screen-recording 30–45 detik memanfaatkan skill editing founder) minta izin mengirim link preview.
  2. Gunakan demo yang sama untuk pitch **White-Label** ke agensi iklan Home Services AS.
  3. Kanal marketplace Rp 0: **Fiverr** (prioritas pertama karena gratis daftar; Upwork opsional nanti karena membutuhkan biaya beli Connects).

### C. Arsitektur Teknis Produk Niche #1 (Biaya Server \$0/Bulan)
- **Frontend:** 1 file self-contained **HTML5/CSS3/Vanilla JS** (modern, mobile-first, cepat, XSS-safe, siap deploy gratis ke Cloudflare Pages / GitHub Pages / Vercel).
  - **Konfigurasi Terpusat (`CLIENT_CONFIG`):** 1 objek JS di bagian atas kode untuk mengganti nama perusahaan, kota/state, warna brand, nomor telepon, daftar layanan, parameter rumus estimasi harga, review, dan URL endpoint Google Apps Script dalam **5–10 menit**.
  - **Fitur Inti:** Multi-Step Instant Quote Calculator (rentang harga real-time + rincian transparan) + **Optional Project Photo Upload dengan `<canvas>` client-side compression** + Lead Capture Form dengan **2 mode** (Mode Demo bawaan tanpa backend untuk link preview outreach; Mode Live terhubung ke Google Apps Script milik klien).
- **Backend Starter (`Code.gs` — Google Apps Script):**
  - Menerima payload JSON + foto terkompresi via Fetch API → simpan foto ke Google Drive klien, catat data lead & hasil estimasi ke Google Sheets klien, dan kirim notifikasi email instan ke pemilik bisnis (**\$0/bulan biaya SaaS**).

### D. Keputusan "TIDAK / TUNDA" yang Sudah Final
1. **Tunda CPA / Bookkeeping Document Upload Portal (AS):** Dokumen pajak klien AS (SSN, W-2, 1099, rekening bank) terikat regulasi ketat **IRS Publication 4557 & FTC Safeguards Rule**. Mayoritas CPA AS tidak boleh memakai custom Google Apps Script untuk upload dokumen pajak. Jika nanti masuk niche CPA/Bookkeeping (Niche #2/ekspansi), jual **khusus Marketing Landing Page + Bookkeeping/Fee Quote Calculator** tanpa upload dokumen sensitif.
2. **Skip Monetisasi AdSense Video Shorts (YouTube Shorts / Reels):** RPM terlalu tipis (\$0,05–\$0,15/1.000 views AS; butuh ~10 juta views/bulan + syarat 10 juta views/90 hari). Skill video editing (Premiere/AE/CapCut) dialihkan untuk membuat **video demo outreach 30–45 detik** QuoteCraft Studio (atau nanti upsell jasa edit iklan short-form B2B \$500–\$1.500/bulan).
3. **Skip Auto-Blast Lamaran Kerja *Full-Time Remote* Jam Kantor:** Berisiko bentrok jam dinas (standup/Slack real-time zona APAC/AU), time tracker layar (Hubstaff/Time Doctor), dan pelanggaran NDA data keuangan jika menggunakan AI pihak ketiga. Fokus utama adalah **bisnis freelance berbasis output (*output-based*)**.

### E. Struktur Pembagian Conversation di Akun Baru `quotecraft`
- **Conversation 1 (`Master Hub & Strategi`):** Konteks utama, tracking KPI outreach, evaluasi & ekspansi niche berikutnya.
- **Conversation 2 (`Setup Kontak, Privasi & Sosmed`):** Checklist akun Rp 0, copywriting profil/bio/signature, panduan deliverability email, & build Mini Contact Hub / Link-in-Bio HTML.
- **Conversation 3 (`Build Niche #1 — US Roofing & Remodeling`):** Build Template Master HTML/CSS/JS + `Code.gs` + Form Brief Klien + Sales & Acquisition Kit.
- **Conversation 4+:** **1 conversation = 1 klien sungguhan** agar rapi dan terisolasi.

---

## 3. Perubahan File & Artifact Penting yang Sudah Dibuat

> [!NOTE]
> **Belum ada kode aplikasi/produk yang ditulis di workspace `/home/antigravity`** karena user memutuskan untuk memindahkan eksekusi build langsung ke akun Antigravity baru (`quotecraft`). Seluruh hasil kerja di percakapan ini berupa audit dokumen, keputusan strategis, dan dokumen handoff/migrasi.

### Artifact yang Dibuat di Percakapan Ini
| File Artifact | Jenis | Status / Fungsi untuk Akun Baru |
| :--- | :--- | :--- |
| `HANDOFF_1.md` *(file ini)* | Markdown Handoff (`UserFacing: true`) | **Wajib dibawa ke akun baru `quotecraft`** sebagai ringkasan menyeluruh untuk agent penerus. |
| `QuoteCraft_Migration_Kit.md` | Markdown Migration Prompts (`UserFacing: true`) | **Sangat disarankan dibawa** — berisi checklist pemisahan akun + 3 prompt starter siap copy–paste (Master Hub, Setup Kontak/Sosmed, Build Niche #1). |
| `CV_Wahyu_Pamungkas_Tax_Finance_Data.url.json` | Passive Bookmark (`UserFacing: false`) | Referensi audit saja di akun lama (**jangan** hubungkan Drive pribadi ke akun `quotecraft`). |
| `CV_Wahyu_Pamungkas_AI_Ops_Automation.url.json` | Passive Bookmark (`UserFacing: false`) | Referensi audit saja di akun lama. |
| `CV_Wahyu_Pamungkas_Creative_Video_Design.url.json` | Passive Bookmark (`UserFacing: false`) | Referensi audit saja di akun lama. |
| `Portfolio_Web_PPID_Wahyu_Pamungkas.url.json` | Passive Bookmark (`UserFacing: false`) | Referensi audit bukti teknis live production (GitHub Pages + Apps Script). |
| `Auto_Lamaran_Kerja_Tracker.url.json` | Passive Bookmark (`UserFacing: false`) | Referensi audit Google Sheet lamaran kerja pribadi (terpisah dari bisnis QuoteCraft). |

*(Salinan unduhan sementara untuk keperluan audit tersimpan di folder `scratch/` percakapan lama dan tidak perlu dipindahkan ke akun `quotecraft`.)*

---

## 4. Status Terakhir, Hal yang Belum Selesai (Next Steps) & Catatan/Kendala Penting

### Status Terakhir
- **Selesai 100%:** Penetapan niche & pasar prioritas, audit CV/portofolio/kemampuan teknis, penetapan nama brand & aturan privasi, struktur harga USD, arsitektur teknis `$0/mo`, serta struktur 3 conversation di akun baru.
- **Belum Dikerjakan (Siap Langsung Dieksekusi di Akun `quotecraft`):** Seluruh aset produksi & pemasaran belum dibangun.

### Hal yang Belum Selesai (Next Steps Berurutan)
1. **Eksekusi Conversation 2 — Setup Identitas, Kontak & Sosmed (Rp 0):**
   - Susun blueprint pemisahan akun & checklist pembuatan akun (Email bisnis `quotecraft`, Instagram Bisnis etalase 3–6 post statis, GitHub/Cloudflare studio, Fiverr, Cal.com/Calendly gratis, Wise/Payoneer).
   - Buat rekomendasi handle konsisten lintas platform + bio IG (≤150 karakter), 4 Story Highlights, 6 konsep/caption post etalase, email signature (versi plain-text outreach & klien aktif), bio profil Fiverr (bebas "Vibe Coding"), dan panduan warm-up/deliverability email baru.
   - Bangun **1 file HTML Mini Contact Hub / Link-in-Bio** (`STUDIO_CONFIG` di bagian atas file, siap deploy gratis ke Cloudflare Pages / GitHub Pages).
2. **Eksekusi Conversation 3 — Build Niche #1 (US Roofing & Remodeling):**
   - Bangun **Template Master Interaktif** berkualitas komersial (HTML/CSS/JS self-contained + `CLIENT_CONFIG` + Multi-Step Instant Quote Calculator + `<canvas>` compressed photo upload + Mode Demo & Mode Live).
   - Bangun **Starter Backend Google Apps Script (`Code.gs`)** untuk simpan foto ke Drive, catat lead ke Sheets, dan kirim email alert instan.
   - Susun **Form Brief Klien (English)** siap salin ke Google Forms / Notion untuk mengisi seluruh parameter `CLIENT_CONFIG` dalam 1 kali jalan.
   - Susun **Sales & Acquisition Kit (English + catatan singkat ID):** Paket harga 3 tier USD (\$850 / \$1.400 / \$2.100 + retainer + white-label bulk), deskripsi Gig Fiverr & profil/proposal Upwork, serta script outreach *"Show, Don't Tell"* (Direct Contractor + follow-up + White-Label Agency).
3. **Peluncuran Awal:**
   - Deploy Contact Hub & 1 Demo Publik Roofing/Remodeling ke Cloudflare Pages / GitHub Pages.
   - Mulai rutinitas kirim **3–5 preview personal/hari** ke kontraktor AS (Google Maps / Meta Ad Library) + pasang Gig Fiverr.

### Catatan & Kendala Penting (Audit & Risiko yang Wajib Diingat)
1. **Kendala Privasi & Akun Google Drive:**
   - Di percakapan lama, akun Google Drive pribadi user sempat dihubungkan untuk audit CV & sheet lamaran kerja. Di akun baru `quotecraft`, **jangan** menghubungkan Drive pribadi/instansi — gunakan Google Drive bersih milik akun `quotecraft`.
2. **Temuan Kritis dari Audit Sheet Pribadi `Auto Lamaran Kerja — Tracker & Otomasi` *(hanya relevan jika user suatu saat masih ingin memakai sheet tersebut di akun pribadinya untuk peran Async/Part-Time/Contract)*:**
   - **Bounce rate 67% pada batch pertama:** 4 dari 6 email terkirim (`LAM-001`, `LAM-002`, `LAM-005`, `LAM-006`) mental (`550 NoSuchUser` / `Google Group Closed`); hanya 2 terkirim (`KIRIM.EMAIL` & `Nextcloud`).
   - **22 dari 68 baris `PENDING`** memakai email generik non-HR (`info@`, `support@`, `hello@`, `contact@`) — jangan langsung auto-kirim 20/hari dari Gmail utama (ubah ke `DRAFT`, saring 10–15 target email HR valid, turunkan batas ke 5–8/hari).
   - **Ketidakkonsistenan angka antara `Template_Email` vs CV PDF:** Template email menulis `300+ regional tax assessment notices` dan `30+ annual stakeholder sessions (~90+ sessions)`, sedangkan CV PDF menulis `10+ formal regional tax complaints/objection cases` dan `20+ regional tax socialization events` — wajib diselaraskan sebelum kirim lagi.
   - **Bug kecil di tab `Konfigurasi`:** Baris `2`, `12`, `18` menampilkan `#ERROR!` (teks pemisah dibaca formula rusak), dan baris `11` (`PORTFOLIO_PDF`) masih berisi link GitHub.
   - **Revisi CV Global (`CV_Wahyu_Pamungkas_AI_Ops_Automation.pdf`):** Hapus istilah `"Vibe Coding"` dari headline sebelum dikirim ke klien/HR global; dan pada `CV_Creative_Video_Design` belum ada link showreel video/desain.
3. **Aturan Teknis Wajib untuk Agent Penerus:**
   - Semua kode demo & produk klien harus mempertahankan prinsip **biaya server \$0/bulan** dan **waktu kustomisasi 5–10 menit** via 1 objek konfigurasi.
   - Jaga bahasa komunikasi dengan user dalam **Bahasa Indonesia yang ringkas, langsung ke eksekusi, tanpa teori dasar**, sementara seluruh aset client-facing (landing page, kalkulator, brief, gig, outreach) menggunakan **Bahasa Inggris natural pasar AS**.
