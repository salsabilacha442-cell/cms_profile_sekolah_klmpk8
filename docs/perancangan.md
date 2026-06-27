
# Perancangan CMS Profil Sekolah

## Deskripsi Sistem

CMS Profil Sekolah adalah sistem yang digunakan untuk mengelola informasi sekolah seperti profil, berita, galeri, fasilitas, dan data lainnya melalui halaman admin.

## Struktur Menu

- Dashboard
- Profil Sekolah
- Program
- Berita
- Galeri
- Fasilitas
- Prestasi
- Guru/Dosen
- PPDB
- Kontak
- Testimoni

## ERD

```mermaid
erDiagram

    ADMIN ||--o{ PROFIL : mengelola
    ADMIN ||--o{ PROGRAM : mengelola
    ADMIN ||--o{ GALERI : mengelola
    ADMIN ||--o{ BERITA : mengelola

    ADMIN {
        int id_admin
        string username
        string password
    }

    PROFIL {
        int id_profil
        string nama_instansi
        string visi
        string misi
    }

    PROGRAM {
        int id_program
        string nama_program
        string deskripsi
    }

    BERITA {
        int id_berita
        string judul
        string isi_berita
    }

    GALERI {
        int id_galeri
        string judul_foto
        string gambar
    }
```
