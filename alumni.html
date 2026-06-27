# PERANCANGAN CMS YAYASAN PENDIDIKAN NUSANTARA SEJAHTERA

## 📋 Identitas Kelompok
- **Mata Kuliah**: Pemrograman Web 1 (Client-Side Programming)
- **Topik**: CMS Company Profile / Website Profil Sekolah
- **Yayasan**: Yayasan Pendidikan Nusantara Sejahtera (YPNS)
- **Jenjang**: TK, SD, SMP, SMA, Kuliah (5 unit dalam 1 yayasan)
- **Nama Kelompok**: 8
- **Anggota**: 
  - [Athaya Reka]
  - [Amelia Putri]
  - [Salsabila]

---

## 🗂️ Hirarki Menu (Sidebar/Navbar) Admin Panel
📊 Dashboard
├── Statistik Total Yayasan
├── Grafik Tren Penerimaan Siswa
├── Grafik Distribusi Siswa per Jenjang
└── Aktivitas Terbaru Admin

🏛️ Profil Yayasan
├── Informasi Dasar (Nama, Logo, Tahun Berdiri)
├── Visi & Misi
├── Sejarah & Tujuan
└── Motto Yayasan

📊 Struktur Organisasi
├── Pengurus Yayasan Pusat
└── Kepala Unit Pendidikan

🏫 Kelola Sekolah
├── Data 5 Unit Sekolah (TK, SD, SMP, SMA, Universitas)
├── CRUD Sekolah (Tambah/Edit/Hapus)
├── Informasi Akreditasi
└── Statistik Siswa & Guru per Unit

👨‍🏫 Data Guru & Dosen
├── CRUD Data Guru/Dosen
├── Filter berdasarkan Unit
├── Filter berdasarkan Jabatan
├── Upload Foto Profil
└── Statistik per Unit

👨‍🎓 Data Siswa & Mahasiswa
├── CRUD Data Siswa/Mahasiswa
├── Filter Unit & Kelas/Prodi
├── Filter Status (Aktif/Cuti/Lulus)
├── Upload Foto Profil
└── Validasi NIS/NIM Unik

⚽ Ekstrakurikuler
├── CRUD Data Ekskul
├── Filter Unit & Hari
├── Upload Foto Kegiatan
└── Informasi Jadwal & Pembina

🏆 Prestasi
├── CRUD Data Prestasi
├── Filter Unit, Medali, Tingkat
├── Upload Foto/Sertifikat
└── Badge Medali (Emas/Perak/Perunggu)

🏛️ Fasilitas
├── CRUD Data Fasilitas
├── Filter Unit & Kategori
├── Upload Foto Fasilitas
└── Informasi Kapasitas & Lokasi

📸 Galeri
├── Upload Foto/Video
├── Filter Unit & Tipe
├── Lightbox Preview
└── Thumbnail YouTube Otomatis

📢 Pengumuman
├── CRUD Pengumuman
├── Filter Unit & Prioritas
├── Prioritas (Penting/Biasa/Terbatas)
└── Periode Tanggal

🎓 Alumni
├── CRUD Data Alumni
├── Filter Unit & Tahun Lulus
├── Upload Foto Profil
└── Testimoni Alumni

📰 Berita & Artikel
├── CRUD Berita
├── Filter Status & Unit
├── Upload Gambar Sampul
├── Status (Published/Draft)
└── Tags & Views Counter

📞 Kontak
├── Informasi Telepon, Email, WA, Website
├── Alamat & Maps
├── Jam Operasional
├── Media Sosial (5 Platform)
└── Form Kirim Pesan

📊 Laporan
├── 8 Jenis Laporan (Ringkasan, Sekolah, Guru, Siswa, Prestasi, Ekskul, Fasilitas, Alumni)
├── Grafik Visualisasi (Chart.js)
├── Filter Tahun
└── Export Excel/PDF/Cetak

```

---

## 📊 ER-D Diagram (Mermaid.js)

```mermaid
erDiagram
    YAYASAN ||--o{ SEKOLAH : memiliki
    SEKOLAH ||--o{ GURU : mempekerjakan
    SEKOLAH ||--o{ SISWA : menampung
    SEKOLAH ||--o{ BERITA : mempunyai
    SEKOLAH ||--o{ PRESTASI : meraih
    SEKOLAH ||--o{ EKSTRAKURIKULER : menyediakan
    SEKOLAH ||--o{ FASILITAS : memiliki
    SEKOLAH ||--o{ GALERI : mempunyai
    SEKOLAH ||--o{ PENGUMUMAN : menerbitkan
    SEKOLAH ||--o{ ALUMNI : meluluskan
    
    YAYASAN {
        int id PK
        string name
        string short_name
        string vision
        text mission
        text history
        text motto
        string logo
        int founded_year
    }
    
    SEKOLAH {
        int id PK
        int yayasan_id FK
        string name
        enum level "TK/SD/SMP/SMA/Kuliah"
        string address
        enum accreditation "A/B/C"
        enum status "Negeri/Swasta"
        string principal
        string phone
        string email
        string website
        string logo
    }
    
    GURU {
        int id PK
        int school_id FK
        string name
        string nip
        string mapel
        string position
        string phone
        string email
        string address
        string photo
    }
    
    SISWA {
        int id PK
        int school_id FK
        string nis
        string name
        string class
        string semester
        enum status "Aktif/Cuti/Lulus"
        string parent_phone
        string email
        string address
        string photo
    }
    
    EKSTRAKURIKULER {
        int id PK
        int school_id FK
        string name
        string coach
        int members
        string schedule
        string venue
        text description
        string image
    }
    
    PRESTASI {
        int id PK
        int school_id FK
        string name
        string winner
        enum medal "Emas/Perak/Perunggu/Juara"
        enum tingkat "Kecamatan/Kota/Provinsi/Nasional/Internasional"
        int year
        text description
        string image
    }
    
    FASILITAS {
        int id PK
        int school_id FK
        string name
        enum kategori "Laboratorium/Olahraga/Perpustakaan/Ruang Kelas/Aula/Ibadah/Lainnya"
        string capacity
        string location
        text description
        string image
    }
    
    GALERI {
        int id PK
        int school_id FK
        string title
        enum type "foto/video"
        string image
        string video_url
        text description
        date date
    }
    
    PENGUMUMAN {
        int id PK
        int school_id FK
        string title
        enum priority "Penting/Biasa/Terbatas"
        text content
        date start_date
        date end_date
    }
    
    ALUMNI {
        int id PK
        int school_id FK
        string name
        int year
        string job
        text testimoni
        string photo
    }
    
    BERITA {
        int id PK
        int school_id FK
        string title
        text content
        enum status "published/draft"
        date created_at
        int views
        string tags
        string image
    }
    ## 🔗 Link Desain Figma

🔗 [Klik di sini untuk melihat desain Figma](https://www.figma.com/design/R5dueIy9dYcOzzsCy0FkFH/srikandi-cms-propil-sekolah-2?node-id=9-4391&t=JSC3TcFKVBfySHXs-1)

### Screenshot Wireframe
https://drive.google.com/drive/folders/1HBIL0pqs3jAXqDLO3EYAYo0bPpQZmy9G?usp=sharing


---

## 🎨 Design System (Figma)

### Color Palettes (Glassmorphism Theme)

| Role | Color Code | Usage |
|------|------------|-------|
| Primary | `#1a2a4f` | Dark blue - Sidebar |
| Secondary | `#2a5298` | Lighter blue - Gradients |
| Accent | `#667eea` | Buttons, Icons |
| Accent 2 | `#764ba2` | Secondary buttons |
| Success | `#34a853` | Positive indicators |
| Warning | `#fbbc04` | Warning alerts |
| Danger | `#ea4335` | Delete actions |
| Background | `#f5f7fb` | Main background |
| Card | `#ffffff` | Cards, Modals |

### Typography

| Element | Font | Weight | Size |
|---------|------|--------|------|
| Heading 1 | Inter | 700 | 26px |
| Heading 2 | Inter | 600 | 20px |
| Body Text | Inter | 400 | 14px |
| Small Text | Inter | 400 | 12px |

---

## 📱 Responsive Breakpoints

| Device | Breakpoint | Layout |
|--------|------------|--------|
| Desktop | > 1024px | Sidebar visible, full layout |
| Tablet | 768px - 1024px | Collapsible sidebar |
| Mobile | < 768px | Hamburger menu, stacked cards |

---

## 👥 Pembagian Tugas Kelompok

| Nama | Tugas | Kontribusi |
|------|-------|------------|
| Athaya Reka | Dashboard, Charts, Login, Laporan | 25% |
| Amelia Putri | CRUD Sekolah, Guru, Struktur | 25% |
| Salsabila | CRUD Siswa, Ekskul, Prestasi, Galeri | 25% |
| [Nama Anggota 4] | Fasilitas, Pengumuman, Alumni, Berita, Kontak, Dokumentasi | 25% |

---

## ✅ Fitur yang Diimplementasikan

- [x] Halaman Login dengan validasi
- [x] Dashboard dengan Chart.js
- [x] CRUD 5 Unit Sekolah (TK, SD, SMP, SMA, Kuliah)
- [x] CRUD Data Guru & Dosen
- [x] CRUD Data Siswa & Mahasiswa
- [x] CRUD Ekstrakurikuler
- [x] CRUD Prestasi
- [x] CRUD Fasilitas
- [x] CRUD Galeri (foto/video)
- [x] CRUD Pengumuman (prioritas)
- [x] CRUD Alumni
- [x] CRUD Berita (draft/publish)
- [x] Manajemen Kontak & Maps
- [x] Laporan Export Excel/PDF
- [x] Profil Yayasan
- [x] Struktur Organisasi
- [x] LocalStorage sebagai database
- [x] Responsive design
- [x] Glassmorphism UI theme
- [x] Upload gambar (Base64)

---