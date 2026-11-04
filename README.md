# Dataset Narkotika dan Psikotropika

> Kumpulan dokumen putusan Pengadilan Negeri Purwokerto dengan klasifikasi Narkotika dan Psikotropika.

## About Dataset

Dataset ini berisi **50 dokumen putusan pengadilan** yang berasal dari **Pengadilan Negeri Purwokerto**. Seluruh dokumen termasuk dalam klasifikasi **Narkotika dan Psikotropika** dan tersedia dalam format PDF.

Dataset mencakup putusan dari tahun **2023 sampai 2025**, dengan rincian:

- **2023:** 15 dokumen
- **2024:** 18 dokumen
- **2025:** 17 dokumen
- **Total:** 50 dokumen

Dokumen diperoleh dari **Direktori Putusan Mahkamah Agung Republik Indonesia**.

## Dataset Contents

Dataset terdiri dari dua bagian utama, yaitu kumpulan dokumen putusan dalam format PDF dan file `Overview.xlsx` yang berisi ringkasan informasi dari setiap dokumen.

### Putusan PDF

File `Narkotika.zip` berisi **50 dokumen putusan** dari Pengadilan Negeri Purwokerto.

Setiap dokumen putusan dapat memuat informasi mengenai:

- identitas dan nomor perkara;
- uraian atau kronologi perkara;
- tuntutan;
- pertimbangan hakim;
- barang bukti; dan
- amar putusan.

### Overview.xlsx

File `Overview.xlsx` merupakan **ringkasan dari 50 dokumen putusan** yang terdapat dalam dataset.

Tujuan file ini adalah untuk memudahkan pengguna melihat informasi utama setiap putusan tanpa harus membuka seluruh dokumen PDF satu per satu.

File `Overview.xlsx` memiliki lima kolom utama:

| Kolom | Keterangan |
| --- | --- |
| **No** | Nomor urut data dari 1 sampai 50. |
| **No Putusan** | Nomor perkara atau nomor putusan yang terdapat pada dokumen. |
| **Lembaga Peradilan** | Nama lembaga peradilan yang mengeluarkan putusan. |
| **Barang Bukti** | Barang bukti yang tercantum dalam perkara. |
| **Amar Putusan** | Hasil atau keputusan hakim yang tercantum dalam amar putusan. |

Secara sederhana, **dokumen PDF merupakan dokumen lengkap**, sedangkan **Overview.xlsx merupakan tabel ringkasannya**.

## Repository Structure

```text
Dataset-Narkotika_147_113/
├── Dataset/
│   └── Narkotika.zip
├── Overview/
│   └── Overview.xlsx
└── README.md
```

### Dataset

Folder `Dataset` berisi `Narkotika.zip` yang menyimpan 50 dokumen putusan dalam format PDF.

### Overview

Folder `Overview` berisi `Overview.xlsx`, yaitu tabel ringkasan informasi dari seluruh dokumen putusan.

## Data Selection

Dokumen dalam dataset dipilih berdasarkan kriteria berikut:

- berasal dari **Pengadilan Negeri Purwokerto**;
- memiliki klasifikasi **Narkotika dan Psikotropika**;
- berada pada rentang tahun **2023–2025**;
- tersedia dalam format **PDF**; dan
- sesuai dengan cakupan perkara dalam dataset.

## Data Source

Sumber dokumen adalah **Direktori Putusan Mahkamah Agung Republik Indonesia**.

Dokumen dalam repository merupakan dokumen putusan yang diperoleh dari sumber tersebut.

## Usage

Dataset dapat digunakan sebagai kumpulan dokumen untuk pengolahan, pencarian, dan analisis informasi dari putusan perkara Narkotika dan Psikotropika.

Untuk menggunakan dataset:

1. Unduh `Narkotika.zip` dari folder `Dataset`.
2. Ekstrak file ZIP untuk memperoleh 50 dokumen PDF.
3. Gunakan `Overview.xlsx` untuk melihat ringkasan informasi setiap putusan.
4. Gunakan nomor putusan pada `Overview.xlsx` untuk menemukan dokumen PDF yang sesuai.

## Notes

- Dataset terdiri dari **50 dokumen putusan**.
- Seluruh dokumen berasal dari **Pengadilan Negeri Purwokerto**.
- Rentang tahun dokumen adalah **2023–2025**.
- `Overview.xlsx` berisi ringkasan informasi dari 50 dokumen.
- Informasi lengkap mengenai suatu perkara dapat dilihat pada dokumen PDF yang bersangkutan.
- Dokumen putusan bersumber dari Direktori Putusan Mahkamah Agung Republik Indonesia.

## Source

**Direktori Putusan Mahkamah Agung Republik Indonesia**

https://putusan3.mahkamahagung.go.id/direktori.html
