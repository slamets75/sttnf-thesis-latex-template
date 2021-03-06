Template Naskah Skripsi LaTeX STT Nurul Fikri
============================================

Template naskah skripsi untuk STT Nurul Fikri dengan typesetting LaTeX, diforking dari [https://github.com/gtrdp/template-skripsi](https://github.com/gtrdp/template-skripsi) yang sebelumnya dibuat untuk JTETI Universitas Gadjah Mada. Template ini merupakan hasil modifikasi dari versi pak Pekik Nurwantoro (FMIPA) dan mas Yohan (JTETI 2008). Template latex di repo ini sudah disesuaikan dengan template standar STT Nurul Fikri.

Anda dapat turut berkontribusi dalam proyek ini dengan *Fork*, *Pull Request*, *Create New Issue*, atau turut menjadi kontributor repo ini.

Quick Start
-----------
1. Siapkan LaTeX environment pada komputer Anda, begitu pula LaTeX editornya :
	- [*Windows*](https://www.google.com/search?q=windows+setup+latex)
	- [*Linux*](https://www.google.com/search?q=linux+setup+latex)
	- [*Mac OS X*](https://www.google.com/search?q=mac+setup+latex)
	- [*Web dengan Sharelatex*](https://www.sharelatex.com)

2. Clone repository ini dengan [Git](https://www.google.com/search?q=setup+git).
3. Mulai tulis naskah Anda, keterangan dari masing-masing file dalam template ini ada di bawah.
4. Pertama kali pakai LaTeX? Butuh bantuan? Pergunakanlah Google dengan baik dan bijak.

Contents
--------
Berikut penjelasan dari file-file utama dalam template ini. File lain yang tidak tercantum hanya pelengkap dalam repository ini.

		template-skripsi/
			├── logosttnf.png
			├── bab1.tex
			├── bab2.tex
			├── bab3.tex
			├── bab4.tex
			├── bab5.tex
			├── daftar-pustaka.bib
			├── template-skripsi.pdf
			├── template-skripsi.tex
			└── sttnfskripsi.cls

### bab1.tex - bab5.tex
Konten utama dari skripsi, mulai dari BAB I (pendahuluan) sampe BAB V (kesimpulan). Silakan disesuaikan dengan jumlah bab skripsi Anda, hapus file yang tidak perlu atau tambahkan file baru untuk bab baru.

### daftar-pustaka.bib
File yang berisi daftar referensi-referensi yang Anda gunakan dalam skripsi. File ini penting guna menyusun daftar pustaka Anda. Dengan file ini menyusun daftar pustaka menjadi sangat sangat sangat mudah.

File ini adalah hasil export dari aplikasi *reference management* seperti Mendeley, Zotero, EndNote, dll. Biasakan mengorganisir referensi skripsi Anda menggunakan aplikasi *reference management*.

### template-skripsi.tex
File ini template-skripsi.tex adalah file utama (kepala) dari template. Berisi informasi-informasi dasar, seperti judul skripsi, nama penulis, nama pembimbing, dll.

### template-skripsi.pdf
File ini adalah skripsi Anda dalam bentuk matang. Sudah rapi dan dapat dicetak untuk dijilid. File ini di-*generate* secara otomatis menggunakan LaTeX.

### sttnfskripsi.cls
File yang berisi aturan-aturan format skripsi. Contoh, format cover, halaman pengesahan, daftar isi, daftar pustaka, dan konten skripsi.

Jika Anda ingin memodifikasi template skripsi ini, ubahlah file *sttnfskripsi.cls* ini.

Lisensi
-------

MIT
