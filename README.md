# kriptografi13

# Encrypt-ECB Program

Program ini merupakan implementasi sederhana enkripsi Electronic CodeBook (ECB) dalam Python. Program meminta input dari pengguna berupa plaintext dalam format heksadesimal dan kunci enkripsi dalam format biner, kemudian mengenkripsi plaintext tersebut menggunakan metode ECB.

Encrypt-ECB Program
Fungsi encrypt_ecb:
plaintext_hex adalah parameter yang mewakili teks yang akan dienkripsi dalam format heksadesimal.
key_binary adalah parameter yang mewakili kunci enkripsi dalam format biner.
Program pertama-tama mengonversi plaintext dari format heksadesimal ke biner.
Kemudian, blok-blok 4 bit dibentuk dari biner plaintext.
Setiap blok dienkripsi menggunakan XOR dengan kunci dan dilakukan pergeseran satu bit ke kiri.
Hasil akhirnya dikonversi kembali ke desimal dan disimpan dalam list encrypted_blocks.
List tersebut kemudian dikembalikan sebagai hasil dari fungsi.
Fungsi main:
plaintext_hex diinisialisasi dengan input pengguna yang diminta dalam format heksadesimal.
key_binary diinisialisasi dengan input pengguna yang diminta dalam format biner.
Fungsi encrypt_ecb dipanggil dengan menggunakan input pengguna sebagai argumen.
Hasil enkripsi dicetak ke layar.
Program Utama:
Program utama memastikan bahwa main hanya dijalankan jika file ini dijalankan langsung (bukan diimpor sebagai modul).
Program meminta pengguna untuk memasukkan plaintext dan kunci.
Hasil enkripsi ECB dicetak ke layar sebagai output akhir.
Dengan cara ini, program memungkinkan pengguna untuk memberikan input mereka sendiri saat menjalankan program, memasukkan plaintext dalam format heksadesimal dan kunci dalam format biner. Program kemudian mengenkripsi plaintext tersebut menggunakan metode ECB dan mencetak hasil enkripsi.

## Contoh Penggunaan

### Input:

```plaintext
Masukkan Plaintext (hex): A23A9
Masukkan Kunci (binary): 1011

 
