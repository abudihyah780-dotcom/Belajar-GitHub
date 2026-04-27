# Belajar-GitHub
4sepx16

1. Pentingnya Penggunaan Command Line (CLI)
Penggunaan CLI dalam Git sangat penting karena memberikan kontrol penuh dan presisi terhadap versi kode.
FUNGSI: Mempercepat alur kerja, memungkinkan otomatisasi (scripting), dan menyediakan akses ke fitur-fitur Git yang terkadang tidak tersedia atau tidak lengkap di aplikasi berbasis GUI (Graphic User Interface).

2. Langkah-Langkah Push Repository
Push digunakan untuk mengirimkan perubahan kode dari repositori lokal (komputer kamu) ke repositori remote (seperti GitHub/GitLab).

Langkah-langkah:

- git add . (Menyiapkan file yang diubah).

- git commit -m "Pesan perubahan" (Menyimpan perubahan dengan catatan).

- git push origin main (Mengirim ke server).

<img src="/image/image git push.png">

FUNGSI: Mengunggah hasil pekerjaan ke server agar tersimpan secara cloud dan bisa diakses/dilihat orang lain.

3. Langkah-Langkah Clone Repository
Clone adalah proses menyalin seluruh isi repositori dari remote ke komputer lokal.

Langkah-langkah:

- Salin URL repositori dari GitHub/GitLab.

- Buka terminal/CLI di folder tujuan.

- Ketik perintah: git clone [URL_REPOSITORI].

<img src="/image/image git clone.png">

FUNGSI: Mendapatkan salinan penuh dari sebuah proyek agar kamu bisa mulai bekerja atau memodifikasi kodenya secara lokal.

4. Langkah-Langkah Pull dan Push Repository
Ini adalah siklus kerja rutin untuk menjaga agar kode di komputer kamu selalu sinkron dengan tim.

- Pull (Mengambil): git pull origin main — Mengambil perubahan terbaru dari server agar kode lokal kamu tidak tertinggal. Selalu lakukan ini sebelum mengerjakan fitur baru.

- Push (Mengirim): git push origin main — Mengunggah kode yang sudah kamu kerjakan setelah ditarik dan digabungkan.

<img src="/image/image git pull dan push.png">

FUNGSI: Pull mencegah konflik kode dengan tim, sedangkan push membagikan hasil kerja kamu kepada tim.
