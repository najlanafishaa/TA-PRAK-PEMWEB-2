🌸 Portofolio Najlaa Nafisha Aulia
Website portofolio ini menampilkan profil pribadi Najlaa Nafisha Aulia, seorang mahasiswi Teknik Informatika Universitas Lampung yang memiliki ketertarikan pada dunia pengembangan web dan teknologi digital. Proyek ini dibuat sebagai media untuk memperkenalkan diri, menampilkan riwayat pendidikan, serta menampilkan berbagai proyek yang telah dikerjakan.

🧠 Deskripsi Proyek
•	Website portofolio ini berisi beberapa bagian utama, yaitu:
•	Tentang Saya (About) — Menampilkan profil singkat, latar belakang pendidikan, serta minat di bidang pengembangan web.
•	Pendidikan (Education) — Menampilkan riwayat pendidikan mulai dari SMA hingga perguruan tinggi.
•	Proyek Terbaru (Projects) — Berisi kumpulan proyek yang pernah dibuat seperti SiPerpus, Tasty Yum, Smart Farming, dan lainnya.
•	Kontak (Contact) — Formulir sederhana untuk menghubungi pembuat website secara langsung.

⚙️ Instalasi dan Penggunaan
1.	Clone repository
-	git clone https://github.com/najlanafishaa/TA-PRAK-PEMWEB-2.git
-	Masuk ke direktori proyek : cd TA-PRAK-PEMWEB-2
-	Buka file utama di browser

🔁 Workflow Git yang Diterapkan
Proyek ini dikelola menggunakan alur kerja Git yang terstruktur untuk menjaga keteraturan versi dan pengembangan fitur secara terpisah.

1️⃣ Inisialisasi Repositori
Repositori Git dibuat di folder proyek dengan perintah:
git init
Perintah ini menjadikan folder proyek sebagai repositori lokal yang siap digunakan untuk pelacakan perubahan.

2️⃣ Commit Bertahap (Atomic Commits)
Setiap section website seperti About, Education, Projects, dan Contact dikerjakan dan di-commit secara bertahap agar mudah dilacak.
git add . git commit -m "add: struktur halaman about dan education" git commit -m "add: menambahkan section project terbaru dan form kontak"

3️⃣ Pembuatan Branch (Branching)
Untuk eksperimen gaya tampilan dan tata letak, dibuat branch baru bernama feature-styling. Hal ini dilakukan agar branch utama (main) tetap stabil.
git branch feature-styling git checkout feature-styling
Perubahan warna, tata letak, dan penyesuaian desain dilakukan di branch ini tanpa mengganggu kode utama.

4️⃣ Penggabungan Branch (Merge)
Setelah proses styling selesai dan diuji, branch tersebut digabung ke branch utama:
git checkout main git merge feature-styling
Langkah ini memastikan perubahan yang sudah final ikut tersimpan di branch utama.

5️⃣ Push ke GitHub
Setelah semua commit tersimpan di lokal, proyek dikirim ke GitHub agar bisa diakses secara online:
git remote add origin https://github.com/najlanafishaa/TA-PRAK-PEMWEB-2.git git push origin main

6️⃣ Pembuatan README.md
File README.md ini dibuat sebagai dokumentasi utama proyek yang menjelaskan:
Deskripsi dan isi website
Langkah penggunaan
Workflow Git yang diterapkan
Dokumentasi ini memudahkan siapa pun untuk memahami struktur proyek tanpa harus membuka seluruh file di dalamnya.
