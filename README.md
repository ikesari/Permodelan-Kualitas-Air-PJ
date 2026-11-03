# CalVal_RS_Water

Materi pendamping buku **_Penginderaan Jauh untuk Pemodelan Kualitas Air: Konsep, Kalibrasi, Validasi, dan Praktik di Sungai, Danau, Waduk, dan Pesisir Indonesia_**.

Repositori ini berisi data latih dan notebook Google Colab untuk **Bab 7, subbab 7.6 (Latihan dengan Data Simulasi)** serta Lampiran A.

> ⚠️ **PERHATIAN: SEMUA DATA DI REPOSITORI INI ADALAH DATA SIMULASI.**
> Data dibangkitkan komputer dengan model bio-optik ilustratif. Data ini bukan pengukuran dan tidak menggambarkan Sungai Porong atau Waduk Sutami. Angka hasil olahannya **tidak boleh dikutip** sebagai kinerja algoritma di perairan nyata.

## Mulai cepat

1. Klik berkas `Latihan_Bab7_Simulasi.ipynb` di daftar berkas repositori ini.
2. Klik tombol **Open in Colab** di bagian atas tampilan notebook. Kalau tombolnya tidak ada, buka [colab.research.google.com](https://colab.research.google.com), pilih **File → Open notebook → GitHub**, lalu tempel alamat repositori ini.
3. Di Colab, klik **Runtime → Run all**.

Tanpa mengunggah apa pun, notebook akan membangkitkan ulang data latih dengan seed 2026. Hasilnya identik dengan berkas CSV di repositori ini.

## Isi repositori

| Berkas | Isi |
|---|---|
| `Latihan_Bab7_Simulasi.ipynb` | Notebook Colab: model bio-optik, pembangkit data, Kasus 1 dan 2, validasi silang, uji akhir, serta lima latihan |
| `kasus1_sungai_sintetik_SIMULASI.csv` | 90 baris matchup TSS sungai sintetik (10 ruas × 3 kampanye × 3 titik) |
| `kasus2_waduk_sintetik_SIMULASI.csv` | 48 baris matchup klorofil-a waduk sintetik (3 zona × 4 kampanye × 4 titik) |
| `Data_Latih_Bab7_SIMULASI.xlsx` | Data yang sama dalam Excel, dengan keterangan kolom (untuk dilihat; untuk analisis pakai CSV) |

Kolom `peran` menandai baris **pengembangan** dan **uji akhir**. Data uji akhir adalah ruas R03 dan R08 untuk sungai, dan kampanye H2 untuk waduk.

## Membaca data langsung dari GitHub

Di notebook (bagian 3), isi dua variabel berikut dengan link *raw* berkas CSV di repositori ini:

```python
URL_SUNGAI = "https://raw.githubusercontent.com/<akun>/CalVal_RS_Water/main/kasus1_sungai_sintetik_SIMULASI.csv"
URL_WADUK  = "https://raw.githubusercontent.com/<akun>/CalVal_RS_Water/main/kasus2_waduk_sintetik_SIMULASI.csv"
```

Ganti `<akun>` dengan nama akun GitHub pemilik repositori. Link *raw* juga bisa didapat dengan membuka berkas CSV di GitHub lalu klik tombol **Raw**.

## Lisensi

- **Kode** (notebook): MIT License, lihat berkas `LICENSE`.
- **Data** (folder ``): [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Silakan dipakai dan diubah dengan menyebutkan sumbernya.

## Cara mengutip

Kutip bukunya, lalu sebutkan repositori ini sebagai materi pendamping.
