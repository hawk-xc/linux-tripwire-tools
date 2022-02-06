# linux-tripwire-tools
IDS (Intrusion Detection System) adalah sebuah mekanisme deteksi intrusi, dimana mekanisme ini akan melakukan pengawasan baik melalui jaringan maupun pada perangkat host. pada modul kali ini kita akan membahas mengenai penggunaan Tripwire HIDS (Host Intrusion Detection System) dimana mekanisme ini akan mengawasi intrusi yang terjadi pada perangkat Host. Intrusi disini mengacu pada kegiatan-kegiatan yang mencurigakan/anomali, mulai dari hilangnya data, data yang berubah/dimodifikasi, proses yang berjalan, adanya malware, dan lain sebagainya. <br />
<br />
Type IDS sendiri secara garis besar dibagi menjadi 2 yaitu hostbase (HIDS) dan networkbase (NIDS) IDS. Snort termasuk kedalam NIDS base, salah satu HIDS base ialah tools Tripware.<br />
<br />
Program tripwire berfungsi untuk menjaga integritas file system dan direktori, dengan mencatat setiap perubahan yang terjadi pada file dan direktori. Konfigurasi tripwire meliputi pelaporan melalui email, bila menemukan perubahan file yang tidak semestinya dan secara otomatis melakukan pemeriksaan file melalui cron. Penggunaan tripwire biasanya digunakan untuk mempermudah pekerjaan yang dilakukan oleh System Administrator dalam mengamankan System. Cara kerja tripwire adalah melakukan perbandingan file dan direktori yang ada dengan database sistem. Perbandingan tersebut meliputi perubahan tanggal, ukuran file, penghapusan dan lain-lainnya. Setelah tripwire dijalankan, secara otomatis akan melakukan   pembuatan   database   sistem.   Kemudian   secara   periodik   akan   selalu melaporkan setiap perubahan pada file dan direktori.<br />
<br />
![flow praktikum](https://user-images.githubusercontent.com/92193431/152704200-f12a2497-dc8e-484c-b149-6228cd61a1fc.png)
<br />
### Langkah kerja


