UMNLife – Kelompok 2

- Edward Nathan Samuel (00000060182).
- Kafijaya (00000061651).
- Muhammad Abidzar Awwalin (00000060520).
- Muhamad Farhan Fadillah (00000061559).
- Raja Mahesya Abdul Fatah Efendi (00000060984).

Fitur yang diterapkan dalam game :

1. Terdapat beberapa karakter yang ada pada game ini yang dapat dipilih pada saat awal 
melakukan permainan. Pemilihan karakter dapat dipilih sesuai dengan apa yang player ingin 
gunakan.

2. Peraturan waktu dalam game ini adalah 1 menit di dalam game = 1 detik di dunia nyata. Logika 
dari penerapan waktu dan jam pada game akan di ambil dan dilanjutkan bedasarkan saat terakhir 
kali user melakukan login.

3. Ada 6 status yang harus dilihat yaitu, makan, minum, tidur, main, olahraga dan belajar dengan nilai minimumnya 0 dan nilai maksimum 10. Tiap status 
direpresentasikan oleh status bar yang dapat berkurang seiring waktu berjalan atau berkurang dan 
bertambah tergantung dari aktivitas yang dilakukan pemain.
	- Makan : Pada saat player melakukan aktivitas makan, maka status progress bar makan akan 
	bertambah +5. Saat progress bar makan kurang dari <1, maka akan terdapat peringatan bahwa 
	kamu sedang lapar dan mengharuskan kamu untuk segera makan.

	- Tidur : Status bar ini dapat bertambah +5 ketika player melalukan aktivitas tidur. Progress ini 
	akan terus berkurang selama player tidak tidur dan melakukan aktivitas lain. Ketika progress ini 
	mencapai kurang dari <1, maka karakter dalam game akan mengantuk dan diharuskan untuk 
	beristirahat.

	- Main : Progress bar ini akan bertambah +5 ketika player melakukan aktivitas bermain. 
	Progress bar ini juga akan berkurang ketika melakukan aktivitas lain. Karakter akan merasa 
	bosan dan membutuhkan permainan ketika progress bar yang kurang dari <1.

	- Belajar : Progress bar ini akan bertambah +2,5 ketika player melakukan aktivitas belajar. 
	Progress bar ini juga akan berkurang ketika melakukan aktivitas lain. Ketika karakter sudah lama 
	tidak belajar hingga progress bar kurang dari <1, maka karakter diharuskan untuk belajar. 
	Kemudian Ketika progress bar sudah penuh, maka kamu telah menyelesaikan semester tersebut, 
	kemudian akan naik ke semester berikutnya. Namun akan terjadi game over ketika status belajar 
	kosong dalam waktu yang lama, maka seluruh progress permainan akan hilang dan player akan 
	mengulang dari awal.

	- Olahraga : Progress bar ini akan bertambah +5 ketika berolahraga. Progress bar ini juga akan 
	berkurang ketika melakukan aktivitas lain. Ketika progress bar olahraga kurang dari <1, maka 
	karakter akan merasa lemah dan mudah sakit karena kurangnya olahraga, jadi kamu harus segera 
	olahraga agar tubuh merasa lebih sehat dan bugar.
	
	- Minum : Progress bar ini akan bertambah +5 ketika player melakukan aktivitas minum. 
	Progress bar ini juga akan berkurang ketika melakukan aktivitas lain. Ketika progress bar kurang 
	dari <1, maka karakter akan haus dan diharuskan untuk segera minum agar tidak dehidrasi.

4. Background image dan ucapan salam untuk karakter pada game akan ikut berubah sesuai dengan waktu yang berjalan 
pada game. 
	- Pagi pada pukul 06:00-10:59 
	- Siang pada pukul 11:00-14:59
	- Sore pada pukul 15:00-17:59
	- Malam pada pukul 18:00 hingga 5:59 

5. Ketika pemain naik level (semester) maka status bar akan direset seperti di awal (eat=5, sleep=5, play=5, drink=5, sport=5, study=0).

6. Ucapan selamat lulus ketika pemain sudah sampai Semester 8 dan menanyakan kepada pemain apa ingin mengulang permainan lagi atau tidak.

7. Ketika semua status bernilai 0 maka permainan akan menampilkan Game Over dan menanyakan kepada pemain apa ingin mengulang lagi atau tidak.

8. Ada rules yang dapat dilihat oleh pemain sebelum memulai permainan.

Cara memainkan game UMNLife:

1. Jalankan game dengan membuka file mulaiMain.html
2. Masuk kedalam character selection untuk memilih karakter yang kamu suka.
3. Silahkan input nama player yang anda inginkan.
4. Tekan tombol play untuk masuk ke permainan.
5. Player diminta untuk menjaga 6 progress bar yang ada pada interface agar karakter tetap hidup
dan sehat.
6. Player akan naik ke level (semester) selanjutnya jika mengisi penuh bar belajar dan status bar direset seperti di awal.
7. Ketika progress bar 0, maka akan terjadi game over dan permainan akan menanyakan pemain apa ingin bermain lagi atau tidak.
8. Tujuan game ini adalah menyelesaikan level (sampai level 8) dan akan lulus dari game ini (Yayy!!).