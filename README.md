# MohaCapthone
Script dan tamplate capsthone
LANGKAH PEMBUATAN WEB APPS PENDIDIKAN DENGAN MARKETPLACE (VM DAN MOODLE)
1. Buat VM menggunakan marketplace + moodle (Bintami LMS)
2. Membuat label DNS melalui IP public pada menu nama label "Nama Bebas"
3. Membuat DNS melalui "catatan zona, nama, jenis dan TTL DNS"
4. Mengkonfigurasikan DNS melalui nama label DNS "pilih konfigurasikan"
5. Mencari username dan pasword melalui "Boot diagnostik dan serial log"
6. Membuka web apps menggunakan ip public pada browser or google crhome
7. Masuk admin web apps menggunakan username dan pasword terkait
8. Mendaftarkan Domain melalui site administrasi "registrasi"
9. Mendesain web apps memlaui menu "Appreance (tema, logo dan lain-lain)"
10. Menambahkan Course dan konten pendidikan

LANGKAH PEMBUATAN WEB APPS PENDIDIKAN DENGAN VM DAN DOPLER
*Instalsi menggunakan VM + Docker Container
1. Buat VM menggunakan Image Linux (bebas mau os apa), recommend Ubuntu 20.0 LTS
2. Akses VM melalui CMD/Putty atau terminal lainnya ( SSH username@ip )
3. Lakukan Update repository dengan perintah "sudo apt update"
4. Lakukan instalasi Docker dengan perintah "sudo apt install docker.io"
5. Lakukan download file script Moode melalui perintah "curl -sSL https://raw.githubusercontent.com/bitnami/bitnami-docker-moodle/master/docker-compose.yml > docker-compose.yml"
6. Lakukan Instalasi tools docker-compose dengan perintah "sudo apt install docker-compose"
7. Lakukan eksekusi script dengna perintah "sudo docker-compose up -d"
8. Tunggu sampai eksekusi selesai
9. Akses web LMS Moodle dengan melalui IP
10. lakukan seting DNS sesuai peyedia DNS masing masing
