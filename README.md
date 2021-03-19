<h1>TUGAS FRAGMENT VIEW MODEL</h1>
<h5>Pada Aplikasi MyFragment App ini, saya membuat berupa Splash Screen dan 2 Fragment. Sebelum itu saya akan menjelaskan tentang apa itu Splash Screen dan Fragment </h5>

<h2>Lifecycle Fragment</h2>
<img src="fragment lifecycle.jpg" height="600px" width="300px">
<h4>Keterangan</h4>

<h5>• onAttach() dipanggil saat sebuah fragment terhubung ke activity.	</h5>  
<h5>•	onCreate() adalah kondisi awal saat Activity baru diciptakan, biasanya dilakukan inisialisasi pada tahapan ini.</h5>  
<h5>•	onCreateView() dipanggil saat fragment sudah siap membaca sebuah layout.</h5> 
<h5>•	onViewCreated() dipanggil setelah onCreateView() dan memastikan layout yang dibaca fragment adalah non-null. Semua pengaturan view seperti pembacaan findViewById, menambah onClickListener dapat dilakukan di sini</h5> 
<h5>•	onActivityCreated() dipanggil setelah activity pembaca sudah menyelesaikan onCreate()-nya.</h5> 
<h5>•	onStart() adalah saat Activity dimulai.</h5>  
<h5>•	onResume() adalah saat Activity dibuka kembali, biasanya dieksekusi setelah onPause().</h5>  
<h5>•	onPause() akan dipanggil saat ada Activity lain yang terbuka.</h5>  
<h5>•	onDestroyView() dipanggil saat layout sebuah fragment akan dihapus dari memori, namun fragmentnya masih ada di memori.</h5> 
<h5>•	onDestroy() adalah kondisi saat Activity dihancurkan pada memori.</h5>  
<h5>•	onDetach() dipanggil saat fragment tidak lagi terhubung ke sebuah activity.</h5> 
