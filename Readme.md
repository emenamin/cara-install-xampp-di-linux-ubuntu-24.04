# Cara Install XAMPP di Linux Ubuntu 24.04

1. Download file XAMPP [di sini](https://www.apachefriends.org/download.html). Pilih XAMPP for Linux.
2. Buka terminal di Ubuntu dengan perintah `Ctrl + Alt + T`.
3. Masuk ke direktori di mana file instalasi XAMPP berada dengan command `cd Downloads`. Ingat ini case sensitive, jadi kapitalisasi ngaruh.
4. Pastikan file instalasi XAMPP berada di sana dengan command `ls`. Di sini contoh nama filenya xampp-linux-x64-5-5.37-0-installer.run.
5. Jalankan command `chmod 755 xampp-linux-x64-5-5.37-0-installer.run`.
6. Masukkan password.
7. Jalankan perintah `sudo ./xampp-linux-x64-5-5.37-0-installer.run`.
8. Ikuti proses instalasi hingga selesai.

# Cara Membuka/Menjalankan XAMPP di Linux Ubuntu 24.04

1. Buka terminal di Linux dengan perintah `Ctrl + Alt + T`.
2. Jalankan perintah `ls` untuk menemukan file .run dari XAMPP. Contoh file saya di sini adalah `manager-linux-x64.run`.
3. Jalankan perintah `sudo chmod 755 manager-linux-64.run`.
4. Masukkan password.
5. Jalankan perintah `sudo ./manager-linux-x64.run`.
6. Selesai.

# Cara Uninstall XAMPP di Linux Ubuntu 24.04

1. Buka terminal di Linux dengan perintah `Ctrl + Alt + T`
2. Jalankan perintah `sudo chmod +x/opt/lampp/uninstall`.
3. Masukkan password.
4. Jalankan perintah `sudo /opt/lampp/uninstall`.
5. Lanjutkan proses uninstall hingga selesai.

## Command yang Digunakan
| Command | Arti | Fungsi |
|---------|------|--------|
| cd | Change Directory | Berpindah dari satu direktori ke direktori lain |
| chmod | Change Mode | Mengubah permission terkait file dan direktori |
| ls | List | Menunjukkan nama-nama file dan direktori dalam direktori saat itu |
| sudo | Super User Do | This command prefix allows a regular user to execute a command with the privileges of the root user. It's a security mechanism to prevent accidental damage by regular users |

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
