NAMA : IWAN SANTOSO
NIM : 1814321037

Cara kerja program:
Pastikan sudah menginstall php dan folder phpnya sudah dimasukkan ke dalam path environment.

create.php => digunakan untuk membuat hmac

Run program dengan cara ketik php create.php pada terminal atau cmd.
Masukkan nama file yang akan dienkripsi. File yang akan dienkripsi harus berada dalam folder yang sama. Disini saya menggunakan file validate.php.
Kemudian masukkan password yang diinginkan.
Jika file yang dimasukkan tidak ada dalam folder, maka akan mengeluarkan pesan “File Tidak Valid”.
JIka file yang dimasukkan ada dalam folder, maka akan mengeluarkan hasil hmacnya.

validate.php => digunakan untuk memvalidasi mac yang sudah dibuat.

1. Run program dengan cara ketik php validate.php pada terminal atau cmd.
2. Caranya hampir sama dengan saat create hmac. Masukkan nama file yang akan dienkripsi.
3. Kemudian masukkan password.
4. Lalu masukkan MAC yang ingin dicek.
5. Jika file yang dimasukkan tidak ada dalam folder, maka mengeluarkan pesan “File Tidak Valid”. Jika ada maka akan melakukan proses selanjutnya.
6. Kemudian, jika MAC yang dimasukkan tidak cocok maka akan muncul pesan “File Tidak Terotentikasi”.
7. Jika MAC cocok makan akan muncul pesan “File Terotentikasi”.
