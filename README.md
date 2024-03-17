# Licence-Blogger-Template
Kode Licence template blogger tanpa enkirpsi, diperuntukan untuk pembelajaran saja.

Menggunakan algoritma kriptografi modern yaitu Advanced Encryption Standard (AES). AES adalah salah satu algoritma kriptografi simetris yang paling umum digunakan dan dianggap aman. 

nilai yang dihasilkan dari proses enripsi akan selalu berbeda walaupun nilai yang di encripsi tetap sama, tetapi ketika proses dekripsi berjalan apapun nilai yang dihasilkan dari proses enripsi dengan AES tersebut akan bisa di dekripsi kembali menjadi nilai semua sebelum di encripsi.

sebagai contoh nilai awal adalah 8638980540121071022
dan setelah dienkripsi pertama kali menjadi U2FsdGVkX1/rmcH2t01RzpXXG4vt2/aKC1QYzpa82dyITb/+ksBDQlhtBfXykLxN

lalu encripsi kedua menjadi U2FsdGVkX18QlkQ95H3L1655Zf4YnAKEfyDk4zvhFHD3F4nQxyTtEBK4TzzityE4

kedua nilai encripsi tersebut jika didekripsi kembali menggunakan source code yang sudah kami buat akan kembali menjadi nilai awal yaitu 8638980540121071022

keterangan:
1. Licence template blogger menggunakan metode blogid yang di encripsi terlebih dahulu.
2. pada bagian js menggunakan algoritma AES dan salt dengan nilai tetap sebagai kunci tambahan.
3. hasil decripted dicocokkan dengan blogid, jika sama maka true, jika berbeda maka false.
4. jika true maka licence berhasil, jika false licence gagal.

catatan:
1. licence tidak akan berhasil jika langsung memasukan blogid.
2. lisence hanya akan berhasil jika blogid di encripted terlebih dahulu dengan script encripted khusus yang telah disediakan pada repository ini.

