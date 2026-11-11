# APA 7th Custom (CSL)

Style sitasi **APA 7th edition** yang dimodifikasi untuk Mendeley Cite. Dasarnya adalah `apa.csl` resmi dari [citation-style-language/styles](https://github.com/citation-style-language/styles).

## Perbedaan dengan APA 7th asli

Perubahan hanya pada pemformatan huruf miring di daftar pustaka untuk artikel jurnal:

| Elemen | APA 7th asli | APA 7th Custom |
|---|---|---|
| Judul artikel | Normal | *Miring* |
| Nama jurnal | *Miring* | Normal |
| Volume | *Miring* | Normal |

Contoh hasil:

```
Nurhasanah, N., Rafi, M. Y., & Rosyani, P. (2023). *Keamanan Data Menggunakan Teknik Steganografi*. Jurnal Jaringan Sistem Informasi Robotik, 7(2), 232–240. https://doi.org/10.58486/jsr.v7i2.300
```

Sitasi dalam teks, urutan unsur, dan aturan lainnya tidak diubah.

## Cara pakai di Mendeley Cite

1. Salin URL Raw file style ini:
   ```
   https://raw.githubusercontent.com/onlyf4n/csl-styles/main/apa-custom.csl
   ```
   (sesuaikan `onlyf4n` dan `csl-styles` kalau username atau nama repo berbeda)
2. Di Word, buka tab **Mendeley Cite** lalu klik **Citation Style**.
3. Pilih **More Styles** dan cari opsi menambahkan style lewat URL (*Add custom style*). Nama menu bisa berbeda tergantung versi.
4. Tempel URL tadi, lalu pilih **APA 7th Custom**.
5. Klik **Refresh** supaya daftar pustaka menyesuaikan.

## Cara pakai di Zotero

1. Unduh `apa-custom.csl`.
2. Buka **Edit → Settings → Cite → Styles → +** dan pilih file tersebut.

## Catatan

- Repositori ini harus **Public**, kalau tidak Mendeley tidak bisa membaca file-nya.
- Setiap kali file `.csl` diubah dan di-commit, klik **Refresh** di Mendeley Cite. Kalau tampilan belum berubah, pilih ulang style-nya.
- Hyphenation otomatis dan pemotongan link DOI di akhir baris diatur di Word, bukan di file style ini.

## Lisensi

Turunan dari APA Style 7th edition oleh Brenton M. Wiernik dan Andrew Dunning, dilisensikan di bawah [Creative Commons Attribution-ShareAlike 3.0](http://creativecommons.org/licenses/by-sa/3.0/). Karena lisensinya ShareAlike, file turunan ini memakai lisensi yang sama.
