#  **Apa itu GIT?**

**GIT** adalah sebuah  _tools_ bagi para _programmer_  dan  _developer_  yang berfungsi sebagai _control system_  untuk menjalankan proyek pengembangan  _software_. GIT adalah singkatan dari  _**Group Inclusive Tour.**_  Tujuan penggunaan GIT yakni untuk mengelola versi  _source code_  program dengan menentukan baris serta kode yang akan ditambahkan atau diganti.

Saat ini, Git merupakan  _version control system_  paling populer digunakan. Ada ratusan proyek  _software_  yang mengandalkan Git sebagai  _version control system_  mereka termasuk proyek komersial serta  _open source_.

Git terkategori dalam **DVCS (_Distributed Version Control System_)**, yang artinya kode tidak hanya memiliki satu tempat penyimpanan sejarah lengkap sebuah  _software_. Di Git, setiap salinan kode kerja  _developer_  juga berperan sebagai repositori yang dapat berisi riwayat lengkap dari semua perubahan. Selain didistribusikan, Git telah dirancang dengan kinerja, keamanan, dan fleksibilitas yang maksimal.

## Apa itu GitHub?

GitHub adalah website  yang digunakan untuk menyimpan dan mengelola kode suatu project. Anda dapat membuat atau mengupload kode Anda ke server  GitHub dan kemudian melakukan  coding secara online.

Hal tersebut dimungkinkan karena GitHub dibangun atas dua sistem utama, yaitu  **version control** dan  **Git**.

_Version control_  adalah sistem yang mencatat semua perubahan kode pada project. Sistem ini penting agar Anda bisa melihat semua riwayat perubahan kode.

## Perintah dasar GIT

-   **git config**  
    Salah satu perintah git yang paling banyak digunakan adalah  **git config**, yang bisa digunakan untuk mengatur konfigurasi tertentu sesuai keinginan pengguna, seperti email, algoritma untuk diff, username, format file, dll. Contohnya, perintah berikut bisa digunakan untuk mengatur email:
    
    git config --global user.email elanstidian29@gmail.com
    
-   **git init**  
    Perintah ini digunakan untuk membuat repositori baru. Caranya:
    
    git init
    
-   **git add**  
    Perintah git add bisa digunakan untuk menambahkan file ke index. Contohnya, perintah berikut ii akan menambahkan file bernama temp.txt yang ada di direktori lokal ke index:
    
    git add temp.txt
    
-   **git clone**  
    Perintah git clone digunakan untuk checkout repositori. Jia repositori berada di remove server, gunakan:
    
    git clone alex@93.188.160.58:/path/to/repository
    
    Jika salinan repositori lokal ingin dibuat, gunakan:
    
    git clone /path/to/repository
    
-   **git commit**  
    Perintah git commit digunakan untuk melakukan commit pada perubahan ke head. Ingat bahwa perubahan apapun yang di-commit tidak akan langsung ke remote repository. Gunakan:
    
    git commit –m “Isi dengan keterangan untuk commit”
    
-   **git status**  
    Perintah git status menampilkan daftar file yang berubah bersama dengan file yang ingin di tambahkan atau di-commit. Gunakan:
    
    git status
    
-   **git push**  
    git push adalah perintah git dasar lainnya. Push akan mengirimkan perubahan ke master branch dari remote repository yang berhubungan dengan direktori kerja Anda. Misalnya:
    
    git push origin master
    
-   **git checkout**  
    Perintah git checkout bisa digunakan untuk membuat branch atau untuk berpindah diantaranya. Misalnya, perintah berikut ini akan membuat branch baru dan berpindah ke dalamnya:
    
    command git checkout -b <nama-branch>
    
    Untuk berpindah dari branch satu ke lainnya, gunakan:
    
    git checkout <branch-name>
    
-   **git remote**  
    Perintah git remote akan membuat user terhubung ke remote repository. Perintah berikut ini akan menampilkan repository yang sedang dikonfigurasi:
    
    git remote -v
    
    Perintah ini membuat user bisa menghubungkan repository lokal ke remote server:
    
    git remote add origin <93.188.160.58>
    
-   **git branch**  
    Perintah git branch bisa digunakan untuk me-list, membuat atau menghapus branch. Untuk menampilkan semua branch yang ada di repository, gunakan:
    
    git branch
    
    Untuk menghapus branch:
    
    git branch -d <branch-name>
    
-   **git pull**  
    Untuk menggabungkan semua perubahan yang ada di remote repository ke direktori lokal, gunakan perintah pull:
    
    git pull upstream master
    
-   **git merge**  
    Perintah merge digunakan untuk menggabungkan sebuah branch ke branch aktif. Gunakan:
    
    git merge <nama-branch>
    
-   **git diff**  
    Perintah git diff digunakan untuk menampilkan conflicts. Untuk melihat conflicts dengan file dasar, gunakan:
    
    git diff --base <nama-file>
    
    Perintah berikut digunakan untuk menampilkan conflicts diantara branch yang akan di-merge:
    
    git diff <source-branch> <target-branch>
    
    Untuk menampilkan semau conflict yang ada, gunakan:
    
    git diff
    
-   **git tag**  
    Tagging digunakan untuk menandai commits tertentu. Contohnya:
    
    git tag 1.1.0 <insert-commitID-here>
