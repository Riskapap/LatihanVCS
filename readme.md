# Latihan VCS

Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.
Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya pernyimpanan database Git tidak hanya berada dalam satu tempat saja.

Cara penggunaan GIT dan langkah-langkahnya

1. Buka software “Git Bash”
2. Konfigurasi Git Bash awal dengan membuat name dan email dengan comand "git config --global user.name "nama"" "git config --global user.email contoh@gmail.com
3. Masuk ke penyimpanan file yang akan dibuat misal akan dibuat di direktori C dengan command "cd /c”
4. Buat file terlebih dahulu dengan command "mkdir Latihan1"
5. Masuk ke dalam file yg telah dibuat dengan command "cd /c/latihan1"
6. Command “git init”. Git init untuk meng-set folder yang digunakan tersebut sebagai repo local git. Bisa di bilang ini instalasi git pertama kali.
7. Buat file README.md dengan command “echo “# Latihan1” > README.md"
8. Setelah itu isi file readme.md dengan tugas yang sudah diberikan dengan command “nano readme.md”
9. Langkah selanjutnya adalah mengkomit file dengan command “git commit -m “isi commit”. Git commit untuk menambahk keterangan atau status perubahaan saat upload ke repo online.
10. Kemudian meremot repositori yang sudah dibuat di github dengan command “git remote add origin https://github.com/Riskapap/LatihanVCS.git (bisa diganti link repositori kalian sendiri”
11. Kemudian upload file readme.md ke repositori online dengan command “git push -u origin master”
12. Kemudian command “git pull origin master”. Git pull untuk mengambil commit terbaru lalu otomatis menggaubungkan (merge) dengan branch yang aktif.
13. Terakhir mengecek file yang readme.md yang sudah diupload dengan command “ll”

