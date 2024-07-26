# Cara Install XAMPP di Linux Ubuntu 24.04

Disclaimer: Di sini saya menggunakan XAMPP versi 8.x.x

1. Download file XAMPP [di sini](https://www.apachefriends.org/download.html). Pilih XAMPP for Linux.
2. Buka terminal di Ubuntu dengan perintah `Ctrl + Alt + T`.
3. Masuk ke direktori di mana file instalasi XAMPP berada dengan command `cd Downloads`. Ingat ini case sensitive, jadi kapitalisasi ngaruh.
4. Pastikan file instalasi XAMPP berada di sana dengan command `ls`. Di sini contoh nama filenya xampp-linux-x64-5-5.37-0-installer.run.
5. Jalankan command `chmod 755 xampp-linux-x64-5-5.37-0-installer.run`.
6. Masukkan password.
7. Jalankan perintah `sudo ./xampp-linux-x64-5-5.37-0-installer.run`.
8. Ikuti proses instalasi hingga selesai.

## Command yang digunakan
| Command | Arti | Fungsi |
|---------|------|--------|
| cd | Change Directory | Berpindah dari satu direktori ke direktori lain |
| chmod | Change Mode | Mengubah permission terkait file dan direktori |
| ls | List | Menunjukkan nama-nama file dan direktori dalam direktori saat itu |

Kenapa ada 775? Apa maksudnya?
This is a numerical representation of file permissions, broken down into three parts:
First digit (7): Permissions for the file owner.
- 4 represents read permission.
- 2 represents write permission.
- 1 represents execute permission.
- So, 7 means the owner has all permissions (read, write, and execute).

Second digit (5): Permissions for the file group.
- 4 represents read permission.
- 1 represents execute permission.
- So, 5 means the group has read and execute permissions.

Third digit (5): Permissions for others (anyone else).
- 4 represents read permission.
- 1 represents execute permission.
- So, 5 means others have read and execute permissions.
