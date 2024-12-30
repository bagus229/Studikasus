# Studi kasus: Validasi Form Input
## Kode program dan langkah-langkahnya

### Langkah 1
langkah pertama validasi_form untuk menerima tiga yakni nama, nomer_telepon, dan email. membuat variabel error supaya kalau ada kesalahan dapat ditampung:
![Gambar 1](screenshot/lol3.png)

### Langkah 2
Membuat fungsi isalpha() untuk memeriksa semua karakter dalam string nama agar memastikan hanya hururf saja. jika ada kesalahan ditambahkan ke daftar error:
![Gambar 1](screenshot/lol4.png)

### Langkah 3
Fungsi isdigit() untuk memeriksa karakter dalam string adalah angka. jika mengandung karakter selain angka akan ditambahkan ke daftar error:
![Gambar 1](screenshot/lol5.png)

### Langkah 4
if validasi sederhana memeriksa string email mengandung karakter "@" dan ".". jika tidak ada akan ditambahkan ke daftar error:
![Gambar 1](screenshot/lol6.png)

### Langkah 5
menampilkan hasil validasi. if error, jika ada error pesan kesalahan akan dicetak. jika tidak pesan "Data pendaftaran vakid":
![Gambar 1](screenshot/lol7.png)

### Langkah 6
program meminta input dari pengguna yakni nama, nomor_telepon, dan email:
![Gambar 1](screenshot/lol8.png)

### Langkah 7
validasi_form untuk memproses data dan memberikan umpan balik sesuai validasi:
![Gambar 1](screenshot/lol9.png)

### hasil eksekusi
![Gambar 1](screenshot/lol1.png)

jika error:
![Gambar 1](screenshot/lol2.png)