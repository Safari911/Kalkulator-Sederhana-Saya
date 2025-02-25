# Kalkulator Sederhana

Ini adalah kalkulator berbasis web sederhana yang dibangun menggunakan HTML, CSS, dan JavaScript. Kalkulator ini mendukung operasi aritmatika dasar seperti penjumlahan, pengurangan, perkalian, dan pembagian. Tampilan diatur menggunakan CSS untuk memberikan antarmuka yang bersih dan terpusat, sementara fungsionalitasnya didukung oleh JavaScript.

## Fitur
- Operasi aritmatika dasar: `+`, `-`, `*`, `/`
- Menghapus layar (AC)
- Menghapus karakter terakhir (C)
- Mendukung titik desimal
- Penanganan kesalahan untuk input yang tidak valid

## Teknologi
- **HTML**: Struktur halaman
- **CSS**: Desain dan tata letak
- **JavaScript**: Interaktivitas dan perhitungan

## Cara Penggunaan
1. Buka file `index.html` di browser pilihan Anda.
2. Klik tombol angka atau operator untuk menambahkan nilai ke layar.
3. Tekan tombol `=` untuk menghitung hasil dari ekspresi yang dimasukkan.
4. Gunakan tombol `AC` untuk membersihkan layar, atau tombol `C` untuk menghapus karakter terakhir yang dimasukkan.

## Struktur Kode
1. **HTML**:
    - `<input>` digunakan untuk menampilkan angka dan hasil perhitungan.
    - `<button>` digunakan untuk tombol angka dan operator.
2. **CSS**:
    - Menggunakan Flexbox untuk memusatkan kalkulator di layar.
    - Desain tombol dan layar kalkulator dengan border dan padding.
3. **JavaScript**:
    - `appendToDisplay(value)` untuk menambah angka/operator ke layar.
    - `ClearDisplay()` untuk menghapus layar.
    - `backspace()` untuk menghapus karakter terakhir.
    - `calculateResult()` untuk menghitung hasil perhitungan menggunakan `eval()`.

## Contoh Penggunaan
- Untuk menghitung 5 + 3, tekan `5`, `+`, `3`, dan `=`.
- Untuk menghapus nilai terakhir, tekan `C`.
- Untuk membersihkan layar, tekan `AC`.
                                                             ##...........Dibuat OLeh Safari.............##
