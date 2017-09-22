# Prak1_PSBO
Simple step
1. Pembaca dianggap telah memiliki akun github
2. lakukan fork terhadap repository (jika berhasil url akan berubah `https://github/USERNAME/Prak1_PSBO`)
3. lakukan push file nim.txt ke repository yang telah di fork (Jika menggunakan command line)
4. Jika gagal menggunakan command line gunakan fitur push yg ada pada github dan upload file secara manual (Tidak direkomendasikan)
5. pada repository klik "Pull Request"
6. Isi title dan description dan kirim pull request
Pengecekan requst akan dilakukan secara berkala mohon menunggu sehingga file anda muncul pada repository. tutorial lengkap dapat mengunjungi https://yangsu.github.io/pull-request-tutorial/

Bang nasrul step
Asumsi: lingkungan sistem Ubuntu 17.04, dan git sudah terinstal.
1. Dapatkan _fork link_ masing-masing, dengan mengklik tombol fork di pojok kanan-atas.
eg. fork link saya: was https://github.com/g64164017/Prak1_PSBO.git
2. Melalui terminal ketikan:
`git clone https://github.com/g64164017/Prak1_PSBO.git`
folder repo seharusnya terdownload di direktori aktif.
3. Masuk ke folder repo
`cd Prak1_PSBO`
4. Buat file masing-masing
`touch G64164017.txt`
5. Ketikkan detail seperti yang disepakati ke dalam file. Dapat menggunakan nano atau aplikasi pengolah teks lainnya.
`nano G64164017.txt`, tekan **Ctrl+X** dan jawab **Y** untuk keluar+simpan (hanya jika menggunakan nano).
6. Tambahkan file ke repo
`git add G64164017.txt`
7. Lakukan commit ke repo, dan ketikkan komentar setelah option parameter -m
`git commit -m "Nasrul G64164017 commmit."`
8. Periksa status repo
`git status`
9. push
`git push origin master`
10. Bandingkan status sebelumnya.
`git status`
11. Buka _fork link_, lalu klik tombol **New pull request**.
Perbandingan terhadap _base fork_ seharusnya diperlihatkan.
12. Klik tombol hijau **Create pull request**.
Lengkapi isian subjek dan komentar.
(selesai)

Command line step
* Tutorial git pull request https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github
* Jika ada kendala bisa menggunakan fitur issues atau WA grup 
