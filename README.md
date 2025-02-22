# Instalasi-Windows-10
Penjelasan dan Langkah-langkah

1. Persyaratan Sistem Minimum Windows 10
Sebelum melakukan instalasi, pastikan komputer memenuhi spesifikasi minimum:
	•	Motherboard: Minimal dengan Slot RAM DDR2 atau lebih tinggi.
	•	Prosesor: 1 GHz atau lebih cepat, dengan 2 atau lebih core pada prosessor.
	•	Bit: 32-bit atau 64-bit / arsitektur x86 atau arsitektur x64
	•	RAM: Minimal 2 GB untuk 32-bit dan 4 GB untuk 64-bit dengan Tipe DDR2 atau lebih tinggi.
	•	Harddisk Conventional / SSD: Minimal memiliki 64 Gb ruang kosong setelah installasi.
	•	Kartu Grafis (VGA): DirectX 9 atau lebih baru dengan driver WDDM 1.0., VRAM 32 Mb atau lebih besar.
	•	Layar: Resolusi minimal 800x600 atau lebih besar.
	•	Koneksi Internet: Dibutuhkan untuk aktivasi dan pembaruan Windows.
2. Persiapan Instalasi
Alat yang Dibutuhkan
	•	File ISO Windows 10 (dapat diunduh dari situs resmi Microsoft).
	•	Rufus atau Media Creation Tool untuk membuat bootable USB.
	•	Flashdisk minimal 8GB.

# Membuat Bootable USB
1.	Gunakan Media Creation Tool
	o	Unduh Media Creation Tool dari situs Microsoft.
	o	Jalankan aplikasi dan pilih "Create installation media for another PC".
	o	Pilih bahasa, edisi, dan arsitektur sesuai spesifikasi komputer.
	o	Pilih "USB flash drive" dan pilih flashdisk yang akan digunakan.
	o	Tunggu proses selesai dan flashdisk siap digunakan.
2.	Gunakan Rufus
	o	Unduh Rufus dari situs resminya.
	o	Hubungkan flashdisk ke komputer.
	o	Buka Rufus dan pilih flashdisk di bagian "Device".
	o	Klik "Select" dan pilih file ISO Windows 10.
	o	Pastikan "Partition Scheme" menjadi UEFI: GPT atau Legacy: MBR
	o	Klik "Start" dan tunggu hingga proses selesai.

3. Proses Instalasi Windows 11
	Langkah-langkah Instalasi
	1.	Masuk ke BIOS
		o	Sambungkan bootable USB/DVD.
		o	Nyalakan komputer dan tekan tombol F2, F12, Del, atau Esc untuk masuk BIOS (tergantung merek laptop/PC).
		o	Ubah Boot Order agar USB/DVD menjadi prioritas pertama.
		o	Simpan perubahan dan keluar dari BIOS / Save Change & Exit.
	2.	Memulai Instalasi
		o	Tekan Enter Ketika muncul Press any key to boot from CD/DVD or USB…
		o	Tunggu hingga layar instalasi Windows 10 muncul.
	3.	Proses Instalasi Windows 10
		o	Pilih bahasa, waktu, dan metode input keyboard, lalu klik Next.
		o	Klik Install Now.
		o	Jika diminta, masukkan Product Key, atau klik I don’t have a product key untuk melanjutkan tanpa aktivasi.
		o	Pilih edisi Windows 11 yang akan diinstal, lalu klik Next.
		o	Centang I accept the license terms, lalu klik Next.
		o	Pilih Custom: Install Windows only (advanced).
		o	Pilih partisi tempat Windows akan diinstal: 
				Jika ada partisi lama, hapus dan buat partisi baru. "Hati-hati jika ada partisi yang tidak ingin di hapus"
				Pilih partisi yang telah disiapkan, lalu klik Next.
		o	Tunggu proses instalasi selesai (PC akan restart beberapa kali).
	4.	Konfigurasi Awal Windows 10
		o	Pilih negara dan layout keyboard.
		o	Hubungkan ke WiFi jika diperlukan.
		o	Pilih Pengaturan Akun: 
				Masuk dengan akun Microsoft atau gunakan akun lokal.
		o	Atur Pengaturan Privasi.
		o	Tunggu Windows menyelesaikan pengaturan.
	4. Instalasi Driver dan Software Pendukung
		Setelah Windows 10 terinstal:
			•	Periksa driver yang belum terinstal melalui Device Manager.
			•	Unduh dan instal driver resmi dari situs produsen laptop/PC.
			•	Instal aplikasi penting, seperti browser, Office, WinRAR, dll.
			•	Lakukan update Windows untuk memastikan sistem terbaru.
	5. Troubleshooting Umum
		•	Windows 10 tidak bisa diinstal: Periksa apakah mode boot sesuai dengan partisi (UEFI/GPT atau Legacy/MBR).
		•	USB boot tidak terdeteksi: Pastikan flashdisk terbaca di BIOS dan gunakan port USB lain.
		•	PC restart berulang kali: Coba ulangi proses instalasi dengan menghapus partisi lama.
________________________________________
