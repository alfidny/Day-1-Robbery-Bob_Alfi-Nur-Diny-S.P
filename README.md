NAMA : ALFI NUR DINY SUNARTO PUTRI 

1. Deskripsi Singkat Mengenai Repository  
Repository adalah tempat penyimpanan terpusat untuk menyimpan, mengelola, dan 
melacak perubahan file atau kode sumber dalam sebuah proyek, terutama pada 
pengembangan perangkat lunak. Repository memungkinkan banyak orang bekerja 
secara kolaboratif, memantau versi, dan mengelola revisi kode dengan mudah. 
Contohnya, platform seperti GitHub atau GitLab menyediakan layanan repository 
berbasis Git.

2. Kegunaan Repository
   a. Tempat Penyimpanan: Menyimpan seluruh file, aset, dan kode program secara 
terpusat dan aman di cloud agar terhindar dari risiko kehilangan data. 
b. Kolaborasi Tim: Memungkinkan banyak pengembang untuk bekerja pada proyek 
yang sama secara bersamaan tanpa saling mengganggu. 
c. Version Control: Melacak setiap perubahan kode dari waktu ke waktu sehingga 
memudahkan untuk melihat riwayat atau kembali ke versi stabil sebelumnya 
(rollback). 
d. Branching: Memfasilitasi pembuatan cabang kode terpisah untuk menguji fitur 
baru atau memperbaiki bug tanpa merusak program utama. 
e. Portofolio & Publikasi: Menjadi sarana untuk memamerkan hasil karya atau 
mendokumentasikan kegiatan/proyek secara terbuka kepada publik.

4. Dokumentasi Kegiatan Workshop 
Materi ini terbagi dua topik besar: membuat dan mengembangkan sesuatu dengan 
bantuan AI, serta mengelola perubahan dan kolaborasi dengan Git dan GitHub. Capaian 
yang ingin diraih adalah mampu menjelaskan bagaimana prompt yang lebih spesifik 
menghasilkan hasil AI yang lebih baik, membedakan Git dan GitHub, mengidentifikasi 
repository, commit, branch, dan pull request, serta melakukan version control.

Bagian pertama membahas prompt engineering, yaitu cara merancang instruksi agar AI 
memberi jawaban yang tepat, relevan, dan layak dipakai. Prompt bisa berupa 
pertanyaan sederhana, kata kunci, instruksi rumit, hingga potongan kode. Kuncinya 
adalah konteks: prompt singkat seperti "Create student task planner" menghasilkan 
jawaban yang kurang terarah, sedangkan prompt yang lengkap memberi hasil jauh lebih 
baik. Prompt yang baik memiliki empat unsur, yaitu role (peran AI), task (tujuan yang 
diminta), context (kebutuhan dan batasan), dan format (bentuk keluaran). Contohnya, 
AI diminta membuat aplikasi task planner untuk mahasiswa baru dengan fitur daftar 
tugas, status selesai, dan filter, memakai HTML, CSS, dan JavaScript murni, disertai 
kode lengkap, cara menjalankan, dan cara menguji, serta tidak boleh mengklaim 
aplikasinya berfungsi sebelum diverifikasi. Taktik tambahan meliputi memakai kata 
kerja aksi, menentukan panjang dan format output, menyebut target audiens, 
menyertakan fakta dan data relevan, merujuk sumber tertentu, serta mendefinisikan 
istilah penting. Manfaat prompt engineering adalah meningkatkan performa model, 
mengurangi bias dan respons ofensif, meningkatkan kontrol dan prediktabilitas, serta 
memberi pengalaman yang lebih baik. 

Bagian kedua membahas Git, yaitu version control system yang melacak siapa, kapan, 
dan apa yang berubah pada suatu file. Alur kerjanya melalui tiga area: working 
directory (salinan versi proyek yang sedang dikerjakan di komputer), staging area atau 
index (tempat menyimpan informasi perubahan yang akan masuk ke commit 
berikutnya), dan git directory atau repository (tempat Git menyimpan metadata dan 
database objek proyek, yang disalin saat clone). Git adalah sistem version control 
terdistribusi yang bekerja secara lokal, sedangkan GitHub adalah platform berbasis web 
untuk menyimpan repository Git secara online dan mendukung kolaborasi. 
Perintah dasarnya: `git init` untuk memulai repo baru, `git add .` untuk memindahkan 
file ke staging area, `git commit -m 'message'` untuk menyimpan perubahan ke 
repository, `git remote add <name> <url>` untuk menghubungkan ke GitHub, `git push 
origin main` untuk mengirim perubahan, dan `git pull origin main` untuk mengambil 
lalu menggabungkan perubahan terbaru. Repository juga bisa didapat lewat `git clone 
"url"` dari repo yang dibuat di GitHub. Untuk staging, `git add --all` dan `git add -A` 
sama-sama menambahkan semua isi repository, `git add .` menambahkan semua file di 
direktori beserta isinya, sedangkan `git add *` hanya menambahkan file baru atau yang 
dimodifikasi, bukan yang dihapus. 

Persiapan lingkungan kerja meliputi memasang Git dan memeriksanya dengan `git -
version`, mengatur identitas dengan `git config --global user.name` dan `user.email`, 
serta memasang VS Code lengkap dengan perintah `code` di terminal. Koneksi aman 
ke GitHub dibuat dengan SSH key: buat kunci lewat `ssh-keygen -t ed25519 -C 
"email@domain.com"`, terima lokasi default, dan isi passphrase. Ed25519 adalah 
skema tanda tangan kurva eliptik yang menawarkan keamanan dan performa tinggi. Di 
macOS, kunci ditambahkan ke SSH agent dan Keychain lewat konfigurasi 
`~/.ssh/config` dan `ssh-add --apple-use-keychain`. Kunci publik lalu disalin dengan 
`pbcopy` dan didaftarkan di pengaturan SSH keys GitHub sebagai Authentication Key. 
Koneksi diverifikasi dengan `ssh -T git@github.com`, yang akan menampilkan pesan 
autentikasi berhasil. Pengecekan akhir mencakup versi Git, identitas Git, versi VS 
Code, dan koneksi GitHub.

5. Pendapat Tentang Kegiatan Day 1 Workshop 
Workshopnya sangat bermanfaat bagi mahasiswa yang newbie di bidang IT 
