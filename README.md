Nama: Aisha Zakia Cherelle 
kelas: Rekayasa Keamanan Siber 1A
Kelompok 06 - Super Mario

Prompt adalah instruksi atau perintah teks yang kamu berikan ke AI (seperti ChatGPT atau Claude) untuk mendapatkan kode pemogram.
Kuncinnya adalah Konteks: Jika kamu hanya meminta "Buat pembuat jadwal tugas mahasiswa", hasilnya akan sangat umum. 
Struktur Prompt yang Baik: Memberikan rumus struktur prompt yang bagus, yaitu harus mencakup Role (Peran AI), Task (Tugas utama), Context (Detail/Kebutuhan), dan Format (Hasil keluaran yang diinginkan).
Perbedaan antara Git dan GitHub 
Git = sebuah sistem (Software) lokal di komputermu untuk mencatat riwayat perubahan file (siapa, kapan, dan apa yang diubah). Git bekerja secara offline di laptop.
GitHub = sebuah Platform/Website online untuk menyimpan catatan Git tersebut di Internet agar bisa diakses bersama teman kelompokmu atau yang lain. 

MEMAHAMI ALUR KERJA GIT *GIT WORKFLOW*
Working Directory (Meja Kerja Kamu): Tempat kamu mengetik atau mengubah kode aplikasi di VS Code. File di sini masih berstatus belum dicatat
Staging Area (Kotak Kardus Paket): Tempat kamu mengumpulkan file-file yang siap untuk disimpan. Menggunakan perintah "git add". Ibarat memasukan barang-barang di meja ke dalam kardus paket.
Git Directory/Respository (Paket Sudah Dilakban dan Diberi Resi): Tempat Git resmi menyimpan riwayat perubahaan tersebut secara permanen. Menggunakan perintah "git commit -m 'pesan'" ibarat melakban kardus dan memberi catatan naskah resi (misal: "Fitur tombol selesai ditambahkan")

PERINTAH-PERINTAH DASAR (COMMANDS) YANG WAJIB DIINGAT
1. Perintah Git Lokal (Di Komputer Sendiri)
'git init': Mmembuat folder proyekmu resmi dipantau oleh Git (membuat rekaman baru)
'git add' atau 'git add --all': Memasukkan seluruh file baru/perubahan ke dalam Staging Area
'git commit -m "pesan"': Mengunci dan menyimpan perubahan tersebut ke dalam riwayat lokal 
2. Perintah Hubungan ke GitHub (Online)
'git remote add origin <url> : Menyambungkan folder Git di laptop dengan alamat website repositori GitHub-mu.
'git push origin main': Mengunggah (upload) seluruh catatan *commit* dari laptop ke GitHub.
'git pull origin main': Mengundah (download) perubahan terbaru yang ada di GitHub ke laptop.

RINGKASAN PRAKTIK HARI INI 
1. Kamu meminta bantuan AI untuk membuatkan kode dasar *Student Task Planner*
2. Kamu membuat repositori Git lokal dengan 'git init'.
3. Kamu mengunggah kode pertamamu ke GitHub memakai 'git add','git commit', dan 'git push'.
4. Jika kamu ingin menambah fitur baru atau mengubah tampilan lewat AI, kamu tinggal mengulangi proses edit file -> 'git add' -> 'git commit' -> 'git push'.
