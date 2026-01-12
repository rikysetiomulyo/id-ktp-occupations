# 🇮🇩 Indonesia KTP Occupations

![Data](https://img.shields.io/badge/Data-JSON%20%7C%20CSV-green)
![Standard](https://img.shields.io/badge/Standard-Dukcapil-blue)

Repository ini berisi **Daftar Pilihan Pekerjaan Standar** yang digunakan dalam Kartu Tanda Penduduk (KTP) dan Kartu Keluarga (KK) di Indonesia, mengacu pada standar **Dukcapil (Kependudukan dan Pencatatan Sipil)**.

Data ini sangat berguna untuk developer yang membuat:
* Form Biodata / Registrasi User.
* Sistem HRIS (Human Resource Information System).
* Aplikasi Fintech / Perbankan (KYC).
* Validasi input data kependudukan.

## 📂 Download Data

| Format | Filename | Link Raw (CDN) |
| :--- | :--- | :--- |
| **JSON** | `ktp_occupations.json` | [Klik di sini](https://raw.githubusercontent.com/rikysetiomulyo/id-ktp-occupations/main/ktp_occupations.json) |
| **CSV** | `ktp_occupations.csv` | [Klik di sini](https://raw.githubusercontent.com/rikysetiomulyo/id-ktp-occupations/main/ktp_occupations.csv) |





## 🧩 Struktur Data
Terdapat **88 Jenis Pekerjaan** standar.

```json
[
  {
    "id": 1,
    "name": "Belum/Tidak Bekerja"
  },
  {
    "id": 88,
    "name": "Wiraswasta"
  }
]

