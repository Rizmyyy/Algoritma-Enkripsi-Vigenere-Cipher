# Algoritma-Enkripsi-Vigen-re-Cipher
Proyek ini adalah implementasi program enkripsi dan dekripsi menggunakan algoritma Vigenère Cipher dalam bahasa Python, dibuat untuk memenuhi tugas mata kuliah pemrograman algoritma. Program ini dapat menerima input teks dan kunci dari pengguna, lalu melakukan proses enkripsi dan dekripsi secara otomatis.

Vigenère Cipher dalah metode enkripsi polialfabetik yang menggunakan kata kunci
untuk menggeser setiap huruf dari teks asli. Berbeda dengan Caesar Cipher yang menggunakan
pergeseran tunggal, Vigenère Cipher menggunakan serangkaian pergeseran yang berulang,
sesuai dengan huruf-huruf pada kunci. Ini membuat algoritma ini lebih kuat. Misalnya, untuk
plaintext kucing dan kunci ikan, kunci akan diulang menjadi ikanik agar panjangnya sama. Setiap
huruf plaintext kemudian digeser berdasarkan huruf kunci yang berpasangan. Huruf 'k' pada
plaintext digeser oleh huruf 'i' dari kunci, 'u' oleh 'k', dan seterusnya. Dengan menggunakan
perhitungan matematika sederhana, k(10) + i(8) menjadi 18, yang setara dengan huruf s. Proses
ini diulangi untuk setiap huruf, menghasilkan ciphertext secvvq.

## Fitur Utama

-   **Enkripsi Vigenère Cipher:** Mengubah *plaintext* menjadi *ciphertext* menggunakan kata kunci.
-   **Dekripsi Vigenère Cipher:** Mengembalikan *ciphertext* ke *plaintext* aslinya.
-   **Interaktif:** Program meminta *plaintext* dan kunci dari pengguna secara langsung.

## Cara Menjalankan

1.  **Instalasi:** Pastikan Anda memiliki Jupyter Notebook atau Google Colab.
2.  **Buka File:** Buka file `algoritma_vigenere.ipynb` di lingkungan Jupyter atau Colab Anda.
3.  **Jalankan:** Jalankan sel kode dari atas ke bawah. Program akan meminta input *plaintext* dan kunci di sel terakhir.

## Kontributor

Mohammad Satria Zacky Mudzaffar
