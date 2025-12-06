# 🚀 Koleksi Skill untuk AI Agents

Transformasikan Droids menjadi ahli spesialis dengan skill modular yang mempercepat alur kerja pengembangan.

## 🎯 Mulai Cepat

```bash
# Instal semua skill sekaligus (14 total skill)
cp -r skills/* ~/.factory/skills/

# Atau pilih yang Anda butuhkan
cp -r skills/svelte-design ~/.factory/skills/

# Instal skill baru spesifik
cp -r skills/security-auth ~/.factory/skills/
cp -r skills/api-builder ~/.factory/skills/
cp -r skills/devops-deployer ~/.factory/skills/
cp -r skills/qa-tester ~/.factory/skills/
cp -r skills/database-manager ~/.factory/skills/
cp -r skills/observability-monitor ~/.factory/skills/
cp -r skills/mobile-devops ~/.factory/skills/
```

## 🔍 Temukan Skill yang Sempurna

### **Membangun Antarmuka Pengguna?**
- [`svelte-design`](./skills/svelte-design) - Buat antarmuka yang khas dan berkualitas produksi untuk Svelte/SvelteKit
- [`svelte-ui-animator`](./skills/svelte-ui-animator) - Tambahkan animasi bermakna dengan Svelte transitions dan actions
- [`svelte-ui-integration`](./skills/svelte-ui-integration) - Bangun workflow SvelteKit dengan form actions dan load functions
- [`shadcn-svelte-management`](./skills/shadcn-svelte-management) - Kelola library komponen Svelte (shadcn-svelte, Skeleton UI, Melt UI)
- [`sveltekit-data-optimizer`](./skills/sveltekit-data-optimizer) - Optimasi performa SvelteKit dengan progressive enhancement

### **Membangun Aplikasi Mobile?**
- [`flutter-enterprise`](./skills/flutter-enterprise) - Bangun aplikasi Flutter enterprise dengan arsitektur clean dan berbasis fitur
- [`flutter-ui-ux`](./skills/flutter-ui-ux) - Buat UI Flutter yang indah dan responsif dengan animasi dan tema kustom

### **Mengembangkan Sistem Backend?**
- [`backend-dev`](./skills/backend-dev) - Alur kerja lengkap dari desain API hingga deployment

### **Perencanaan & Dokumentasi?**
- [`product-management`](./skills/product-management) - Tulis PRD, analisis fitur, rencanakan roadmap
- [`task-generator`](./skills/task-generator) - Buat daftar tugas terstruktur dari persyaratan
- [`agents-md-generator`](./skills/agents-md-generator) - Buat struktur dokumentasi yang dioptimalkan AI

### **Membangun Aplikasi Aman?**
- [`security-auth`](./skills/security-auth) - Implementasi autentikasi, otorisasi, dan praktik keamanan terbaik

### **Mengembangkan API?**
- [`api-builder`](./skills/api-builder) - Desain, bangun, dan dokumentasikan RESTful API dan endpoint GraphQL

### **Deploy ke Produksi?**
- [`devops-deployer`](./skills/devops-deployer) - Siapkan pipeline CI/CD, kontainerisasi, dan deployment cloud

### **Jaminan Kualitas?**
- [`qa-tester`](./skills/qa-tester) - Buat suite tes komprehensif, otomasi pengujian, dan pastikan kualitas kode

### **Mengelola Data?**
- [`database-manager`](./skills/database-manager) - Desain skema, optimasi query, dan kelola sistem database

### **Monitoring Produksi?**
- [`observability-monitor`](./skills/observability-monitor) - Implementasi logging, metrik, dan monitoring untuk sistem produksi

### **Deploy Mobile?**
- [`mobile-devops`](./skills/mobile-devops) - Build, tes, dan deploy aplikasi mobile ke app store

### **Automasi & Alat?**
- [`browser`](./skills/browser) - Otomasi Chrome DevTools dan web scraping
- [`skill-creator`](./skills/skill-creator) - Buat skill AI Anda sendiri
- [`template-skill`](./skills/template-skill) - Titik awal untuk skill baru

## 🛠️ Anatomi Skill

Setiap skill adalah paket lengkap:

```
skill-name/
├── SKILL.md              # Instruksi & alur kerja inti
├── references/           # Dokumen detail & pola
├── scripts/              # Utilitas otomasi
└── assets/               # Template & sumber daya
```

## 💡 Kombinasi Skill Populer

### **Pengembangan Full-Stack**
```bash
# Sempurna untuk membangun aplikasi lengkap
skills/backend-dev + skills/svelte-design + skills/svelte-ui-integration
```

### **Pengembangan Aplikasi Mobile**
```bash
# Aplikasi Flutter lengkap dari arsitektur hingga UI
skills/flutter-enterprise + skills/flutter-ui-ux
```

### **Peluncuran Produk**
```bash
# Dari ide hingga deployment
skills/product-management + skills/backend-dev + skills/svelte-design
```

### **Optimasi Performa**
```bash
# Percepat aplikasi yang ada
skills/sveltekit-data-optimizer + skills/svelte-ui-animator
```

### **Pengembangan API Aman**
```bash
# Bangun API yang aman dan teruji dengan monitoring
skills/api-builder + skills/security-auth + skills/qa-tester + skills/observability-monitor
```

### **Deployment Full-Stack Produksi**
```bash
# Aplikasi lengkap dari pengembangan hingga monitoring produksi
skills/backend-dev + skills/security-auth + skills/devops-deployer + skills/observability-monitor
```

### **Pipeline Produksi Aplikasi Mobile**
```bash
# Dari pengembangan hingga deployment ke app store
skills/flutter-enterprise + skills/mobile-devops + skills/qa-tester
```

### **Aplikasi Berbasis Data**
```bash
# Aplikasi dengan manajemen data dan monitoring yang kuat
skills/database-manager + skills/api-builder + skills/observability-monitor
```

## 🎨 Showcase Skill

### Keunggulan Frontend
- **Sistem Desain**: Buat antarmuka yang kohesif dan skalabel untuk Svelte/SvelteKit
- **Perpustakaan Animasi**: Svelte transitions, actions, dan pola animasi kustom
- **Performa**: Optimasi server-side rendering SvelteKit dengan progressive enhancement
- **Manajemen Komponen**: Alur kerja library komponen Svelte yang disederhanakan

### Pengembangan Mobile
- **Arsitektur Enterprise**: Clean architecture berbasis fitur untuk aplikasi Flutter yang skalabel
- **Keunggulan UI/UX**: Antarmuka Flutter responsif dengan animasi dan tema kustom
- **Cross-Platform**: Basis kode tunggal untuk iOS dan Android dengan optimasi spesifik platform
- **Performa**: Animasi 60fps dan rendering yang dioptimalkan untuk pengalaman mobile yang lancar

### Penguasaan Backend
- **Sistem Multi-Ahli**: Arsitek + Keamanan + DevOps + Spesialis Database
- **Keamanan Pertama**: Pola autentikasi dan perlindungan bawaan
- **CI/CD Siap**: Otomasi pengujian dan deployment
- **Arsitektur Skalabel**: Pola desain tingkat enterprise

### Presisi Perencanaan
- **Persyaratan Terstruktur**: Integrasi kerangka kerja RICE/ICE
- **Otomasi Tugas**: Pemecahan tugas yang ramah untuk junior developer
- **Dokumentasi**: Struktur hierarkis yang dioptimalkan AI
- **Sintesis Riset**: Dari wawasan pengguna ke rencana yang dapat ditindaklanjuti

### Keamanan & Autentikasi
- **Arsitektur Zero-Trust**: Pola autentikasi modern seperti JWT dan OAuth2
- **Praktik Keamanan Terbaik**: Validasi input, enkripsi, dan perlindungan kerentanan
- **Sistem Otorisasi**: Kontrol akses berbasis peran dan manajemen izin
- **Pengujian Keamanan**: Pemindaian keamanan otomatis dan workflow pengujian penetrasi

### Pengembangan API & Integrasi
- **Desain RESTful**: Arsitektur API yang bersih dengan metode HTTP dan status code yang tepat
- **Implementasi GraphQL**: Antarmuka query yang fleksibel dan desain skema
- **Dokumentasi API**: Spesifikasi OpenAPI/Swagger dan dokumentasi interaktif
- **Pola Integrasi**: Webhooks, arsitektur event-driven, dan integrasi pihak ketiga

### DevOps & Deployment
- **Pipeline CI/CD**: Workflow otomasi pengujian, building, dan deployment
- **Orkestrasi Kontainer**: Docker, Kubernetes, dan deployment microservices
- **Infrastruktur Cloud**: Otomasi deployment AWS, Azure, dan GCP
- **Infrastruktur sebagai Kode**: Template Terraform dan CloudFormation

### Jaminan Kualitas
- **Otomasi Pengujian**: Framework pengujian unit, integrasi, dan end-to-end
- **Pengujian Performa**: Load testing dan benchmarking performa
- **Kualitas Kode**: Analisis statis, linting, dan otomasi code review
- **Pengembangan Berbasis Tes**: Workflow TDD dan pengembangan berbasis perilaku

### Manajemen Database
- **Desain Skema**: Arsitektur database yang dinormalisasi dan denormalisasi
- **Optimasi Query**: Strategi indeks dan tuning performa
- **Migrasi Data**: Migrasi database yang dikontrol versi
- **Integrasi NoSQL**: Implementasi database dokumen, key-value, dan graf

### Observabilitas & Monitoring
- **Sistem Logging**: Logging terstruktur dan agregasi log
- **Pengumpulan Metrik**: Monitoring performa aplikasi dan metrik bisnis
- **Tracing Terdistribusi**: Pelacakan request di seluruh microservices
- **Sistem Alerting**: Monitoring proaktif dan respons insiden

### Mobile DevOps
- **Deployment App Store**: Build otomatis untuk iOS App Store dan Google Play
- **CI/CD Mobile**: Fastlane dan alat deployment mobile spesifik lainnya
- **Manajemen Versi**: Semantic versioning dan otomasi rilis
- **Pengujian Perangkat**: Pengujian otomatis di berbagai perangkat dan versi OS

## 🚀 Alur Kerja Dunia Nyata

### Membangun Aplikasi Flutter Enterprise
```
Pengguna: "Buat aplikasi manajemen inventory enterprise"

→ flutter-enterprise menganalisis persyaratan dan merancang arsitektur clean berbasis fitur
→ flutter-enterprise menyiapkan struktur modular dengan layer data, domain, dan presentasi
→ flutter-ui-ux membuat komponen UI responsif dengan tema kustom
→ flutter-ui-ux menambahkan animasi yang halus dan micro-interactions
→ Hasil: Aplikasi Flutter siap produksi dengan arsitektur yang dapat dipelihara dan UI yang indah
```

### Membuat Landing Page SvelteKit
```
Pengguna: "Bangun landing page modern"

→ svelte-design menganalisis brand dan menciptakan arah estetika untuk Svelte
→ svelte-ui-animator menambahkan Svelte transitions dan animasi scroll-reveal
→ shadcn-svelte-management menyediakan integrasi library komponen Svelte
→ sveltekit-data-optimizer memastikan server-side rendering instan
→ Hasil: Landing page SvelteKit beranimasi siap produksi dalam hitungan menit
```

### Meluncurkan API
```
Pengguna: "Buat API manajemen pengguna"

→ backend-dev mengkoordinasikan sistem ahli
→ Mendesain autentikasi aman dan skema database
→ Menyiapkan otomasi pengujian dan deployment
→ Hasil: API tingkat enterprise dengan CI/CD lengkap
```

### Merencanakan Fitur
```
Pengguna: "Rencanakan fitur pencarian baru"

→ product-management menyusun PRD dan user stories
→ task-generator memecah menjadi tugas yang dapat ditindaklanjuti
→ agents-md-generator membuat struktur dokumentasi
→ Hasil: Spesifikasi lengkap dengan roadmap implementasi
```

### Membangun API Aman
```
Pengguna: "Buat API pemrosesan pembayaran yang aman"

→ api-builder merancang endpoint RESTful dengan metode HTTP yang tepat
→ security-auth mengimplementasikan autentikasi JWT dan alur OAuth2
→ database-manager membuat skema aman dengan data sensitif terenkripsi
→ qa-tester membangun suite tes komprehensif termasuk tes keamanan
→ observability-monitor mengatur logging dan alerting untuk transaksi pembayaran
→ Hasil: API tingkat enterprise yang aman dengan monitoring dan cakupan pengujian penuh
```

### Deploy Aplikasi Full-Stack
```
Pengguna: "Deploy aplikasi SaaS kami ke produksi"

→ devops-deployer menyiapkan pipeline CI/CD dengan pengujian otomatis
→ security-auth mengimplementasikan SSL/TLS dan security headers
→ observability-monitor mengkonfigurasi monitoring aplikasi dan alerting
→ database-manager menangani migrasi database dan strategi backup
→ qa-tester menjalankan tes integrasi otomatis di lingkungan staging
→ Hasil: Deployment siap produksi dengan monitoring, keamanan, dan pengujian otomatis
```

### Pipeline Rilis Aplikasi Mobile
```
Pengguna: "Rilis aplikasi mobile kami ke iOS dan Android stores"

→ mobile-devops mengkonfigurasi build otomatis untuk kedua platform
→ qa-tester menjalankan tes spesifik perangkat dan benchmark performa
→ security-auth mengimplementasikan certificate pinning dan penyimpanan aman
→ observability-monitor mengatur crash reporting dan analytics
→ devops-deployer mengelola strategi rollback dan A/B testing
→ Hasil: Pipeline rilis mobile otomatis dengan monitoring dan keamanan
```

### Proyek Migrasi Database
```
Pengguna: "Migrasikan database kami ke arsitektur baru"

→ database-manager merancang skema baru dan strategi migrasi
→ api-builder memperbarui endpoint API untuk bekerja dengan struktur database baru
→ qa-tester membuat tes validasi data dan benchmark performa
→ observability-monitor mengatur monitoring performa database
→ devops-deployer mengoordinasikan proses migrasi zero-downtime
→ Hasil: Migrasi database yang seamless dengan integritas data dan optimasi performa
```

## 🛠️ Panduan Instalasi

### Pengguna Factory AI
```bash
# Salin semua skill
cp -r skills/* ~/.factory/skills/

# Salin skill tertentu
cp -r skills/skill-name ~/.factory/skills/
```

### Pengaturan Manual
1. Kloning repositori ini
2. Salin folder skill ke direktori agen AI Anda
3. Periksa README individual skill untuk dependensi

## 🤝 Berkontribusi

Membangun skill baru? Ikuti kerangka kerja kami:

1. **Struktur**: Gunakan anatomi standar (SKILL.md, references/, scripts/, assets/)
2. **Ringkas**: Pertahankan SKILL.md di bawah 500 baris
3. **Praktis**: Sertakan contoh nyata dengan path file aktual
4. **Diuji**: Validasi dengan skenario dunia nyata

## 📄 Lisensi

Setiap skill mungkin memiliki lisensi individual. Periksa direktori skill untuk spesifiknya.

## 📋 Maintainer

**Anaz S. Aji**
[GitHub Profile](https://github.com/ajianaz)

---

**Dibuat untuk [Factory AI](https://factory.ai) dan asisten coding AI yang kompatibel.**

*Transformasikan asisten AI Anda dari generalis menjadi spesialis dengan skill yang ditargetkan.*