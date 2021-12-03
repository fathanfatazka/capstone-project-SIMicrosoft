<div align="center">
  <img src="https://user-images.githubusercontent.com/62282651/144572430-76efdbb1-e04a-48f5-ad6c-f1cefd3229d0.png" width=300px>
  <h1>Mentari Kindergarten School</h1>
  <b>Capstone Project <br>
    Studi Independen Cloud Fundamental Microsoft <br>
  M Fathan Fatazka</b>
</div>


## A. Deskripsi Singkat Aplikasi
[`^ Kembali Keatas ^`](#)

&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; Mentari Kindergarten School merupakan sekolah taman kanak-kanak (TK) yang berlokasi di Pekayon Jaya, Bekasi Selatan, Jawa Barat. Kebutuhan sekolah terhadap proses pembelajaran online menuntut untuk adanya platform pembelajaran berbasis online untuk seluruh muridnya. Pembuatan aplikasi ini ditujukan untuk memberikan layanan pembelajaran kepada para murid TK Mentari agar proses pembelajaran terpusat pada platform ini. Platform berbasis web dengan fitur berupa akses pembelajaran mulai dari materi-materi yang dipelajari, pengerjaan soal-soal latihan, hingga diskusi online.

## B. Penjelasan Pengembangan Aplikasi
[`^ Kembali Keatas ^`](#)

* Moodle: Penggunaan moodle dilakukan dalam pengembangan aplikasi Mentari Kindergarten ini. Moodle merupakan sebuah learning management system (LMS) berbasis PHP dan open-source
* Azure VM: Aplikasi moodle di hosting pada Azure Virtual Machine dengan bantuan teknologi Docker
* Cloudflare: Aplikasi Mentari Kindergarten sudah memiliki DNS dengan bantuan hosting pada platform Cloudflare dengan alamat --> https://mentari-school.cf-002.space

## C. Proses Pengerjaan Aplikasi
[`^ Kembali Keatas ^`](#)

Instalasi aplikasi moodle menggunakan Azure VM dan DOcker Container

1. Create virtual machine pada Azure
2. Akses VM melalui CMD (SSH username@ip)
3. Lakukan Update repository dengan perintah "sudo apt update"
4. Lakukan instalasi Docker dengan perintah "sudo apt install docker.io"
5. Lakukan download file script Moode melalui perintah "curl -sSL https://raw.githubusercontent.com/bitnami/bitnami-docker-moodle/master/docker-compose.yml > docker-compose.yml"
6. Lakukan Instalasi tools docker-compose dengan perintah "sudo apt install docker-compose"
7. Lakukan eksekusi script dengna perintah "sudo docker-compose up -d"
8. Tunggu sampai eksekusi selesai
9. Akses web LMS Moodle dengan melalui IP
10. lakukan seting DNS sesuai peyedia DNS masing masing
