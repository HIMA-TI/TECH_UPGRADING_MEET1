1. Langkah-langkah Push ke GitHub
Persiapan Awal1. Persiapan Awal
Sebelum Anda dapat melakukan push ke repositori GitHub, pastikan Anda telah memiliki Git yang terinstal di komputer Anda .yang terinstal di komputer Anda. Anda bisa mendownloadnya di sini .

3. Menambahkan Repositori Jarak Jauh
Jika Anda sudah memiliki repositori yang akan digunakan, Anda harus menghubungkannya dengan proyek Git lokal. Jika belum, Anda perlu membuat repositori terlebih dahulu di GitHub.

Menambahkan repositori jarak jauh menggunakan URL HTTPS:

git remote add origin https://github.com/HIMA-TI/TECH_UPGRADING_MEET1.git
4. Membuat Komitmen Pertama
Jika Anda belum membuat commit pertama di proyek Anda, ikuti langkah-langkah berikut:

Inisialisasi Git di Proyek Anda
Buka terminal di direktori proyek dan jalankan perintah berikut untuk menginisialisasi Git:

git init
Menambahkan Semua File ke Git
Tambahkan semua file di proyek Anda ke dalam staging area:

git add .
Membuat Commit
Buat commit pertama dengan pesan yang jelas:

git commit -m "Initial commit"
5. Push ke GitHub
Setelah melakukan, Anda dapat melakukan push ke repositori GitHub. Jika repositori Anda menggunakan cabang master, gunakan perintah berikut:

git push -u origin master
Namun, jika Anda menggunakan default cabang main, gunakan perintah ini:

git push -u origin main
Saat pertama kali melakukan push, Git akan meminta Anda untuk memasukkan nama pengguna dan Personal Access Token (PAT) sebagai kata sandi. Masukkan nama pengguna GitHub Anda dan gunakan token yang telah Anda buat sebagai kata sandi.
.

6. Verifikasi Push
Setelah berhasil melakukan push, Anda dapat memverifikasi apakah perubahan Anda telah muncul di repositori GitHub dengan membuka repositori GitHub Anda .

Cara Berkontribusi (Bagi Kolaborator)
Jika Anda ingin orang lain berkontribusi pada repositori ini, berikut langkah-langkah yang bisa diikuti:

Fork dan Clone Repositori
Untuk mulai berkontribusi, orang lain perlu fork repositori ini terlebih dahulu melalui halaman repositori GitHub. Setelah itu, mereka dapat mengkloning repositori ke komputer mereka dengan perintah berikut:

git clone https://github.com/HIMA-TI/TECH_UPGRADING_MEET1.git
Menambahkan Perubahan
Setelah melakukan perubahan pada file, tambahkan file yang diubah ke staging area:

git add .
Membuat Commit
Commit perubahan dengan pesan yang sesuai:

git commit -m "Pesan commit yang menjelaskan perubahan"
Dorong ke GitHub
Dorong perubahan ke repositori fork mereka:

git push origin master
Buat Pull Request
Setelah melakukan push, mereka dapat membuat pull request di GitHub untuk menyarankan perubahan mereka ke repositori utama.
