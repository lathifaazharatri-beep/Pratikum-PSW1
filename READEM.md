Nama : Azharatri Lathifa
NIM :41426022
Prodi : DIV TRPL 1

langkah langkah :
Pertama Form pendaftaran di awali dengan menyiapkan file index.html dan struktur dasar HTML 5, lalu semuanya di bungkus di dalam tag. Setelah itu masukin kolon input data diri seperti nama, email, nomor telfon dan jumlah tiket. Selanjutnya, menambahkan pilihan ptodi  <select> dan membuat grup radio button di dalam <fieldset> buat memnentukan mode kehadiran dan membuat <fieldset> khusus untuk checkbox piliahn minat  topik html dan aksesibitas. Terakhir, masukkan kolon catatan dan tutup formnya pakai tombil di paling bawah.

Jawaban Pengamatan :
1. Mengapa telepon bukan kuantitas number?
   Di karenkan nomor telfon adalah data teks/identifikasi, bukan nilai matematis. nomor telfon juga bisa di awali dengan angka 0.

2. Apa beda label pilihan dan legend kelompok?
   label = untuk memberikan keterangan pada satu elemen input spesifik 
   legend = untuk memberi judul/keterangan pada sekelompok form control yang berada di dalam tag

3. Apa beda id dan name?
   id = untuk mengenal uni elemen di sisi client/browser
   name = di gunakan sebagai kunci dari data yang di kirimkan ke server saat form di submit.

4. Apa yang terjadi pada checkbox tidak dicentang?
   nama dan nilai dari checkbox tersebut tidak akan di kirimkan sama sekali dalam data form submission ke server.

   Hasil pengujian :
   Berdasarkan pengujian formulir yang di lakukan, seluruh fitur berjalan dengan lancar dan sesuai dengan yang di harapkan. ketika label di klik, kursor atau pilihan otomatis aktif dan seluruh  data dari kontrol terisi- termasuk pilihan checkbox topik berhasil terkirim dan muncul secara tepat sebagai parameter pada URL browser.

   Hasil nyata :
   1. saat klik tulisan label = kursor langsung aktif 
   2. saat milih radio button = otomatis berpindah ( hanya bisa pilih satu )
   3. saat isi tiket lebih dari 5 = browser langsung nampilin pesan eror ( karen amksimal hanya 5 tiket )
   4. saat klik tombol "Daftar" = halaman ter refresh dan data isian nya langsung muncul di alamat URL browse bagian atas setelah tanda.