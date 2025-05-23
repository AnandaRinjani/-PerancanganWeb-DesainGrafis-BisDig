# -PerancanganWeb-DesainGrafis-BisDig

file:///C:/xampp/htdocs/xampp/nandacantik/rinjani%203%20.html

# PerancanganWeb-DesainGrafis-BisDig

Repositori ini berisi contoh implementasi sederhana untuk fitur "Tampilkan/Sembunyikan Komentar" menggunakan HTML dan JavaScript murni.

## Penjelasan Fitur "Tampilkan/Sembunyikan Komentar"

Fitur ini dirancang untuk meningkatkan pengalaman pengguna pada sebuah blog, di mana komentar tidak langsung terlihat saat halaman dimuat. Pengguna memiliki opsi untuk menampilkan atau menyembunyikan komentar dengan mengklik sebuah tombol.

### Bagaimana Cara Kerjanya?

1.  **Struktur HTML:** Konten komentar dibungkus dalam sebuah elemen `div` dengan ID spesifik (`komentarContainer`). Secara default, `div` ini memiliki kelas CSS yang menyembunyikannya (`komentar-tersembunyi`).
2.  **Styling CSS:** Kelas `komentar-tersembunyi` menerapkan properti `display: none;` untuk menyembunyikan elemen.
3.  **Logika JavaScript:**
    * Sebuah tombol (`tombolTampilkanKomentar`) disiapkan untuk memicu interaksi.
    * Ketika tombol diklik, sebuah fungsi JavaScript akan dieksekusi.
    * Fungsi ini memeriksa keberadaan kelas `komentar-tersembunyi` pada `komentarContainer`.
    * Jika kelas tersebut ada (komentar tersembunyi), JavaScript akan menghapusnya, sehingga komentar menjadi terlihat. Teks tombol juga diubah menjadi "Sembunyikan Komentar".
    * Jika kelas tersebut tidak ada (komentar terlihat), JavaScript akan menambahkannya kembali, menyembunyikan komentar. Teks tombol diubah kembali menjadi "Tampilkan Komentar".

### Cara Menggunakan

Cukup buka file `index.html` di browser web Anda. Klik tombol "Tampilkan Komentar" untuk melihat bagaimana fitur ini bekerja.

### File dalam Repositori

* `index.html`: Berisi struktur HTML, styling CSS internal, dan skrip JavaScript untuk fungsionalitas ini.
