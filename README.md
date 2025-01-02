# Aplikasi Eco Solve

**Eco Solve** adalah aplikasi Android yang dirancang untuk mendukung tujuan Sustainable Development Goal (SDG) 12, yaitu memastikan konsumsi dan produksi yang berkelanjutan. Aplikasi ini berfungsi sebagai media informatif dan persuasif yang mengajak pengguna untuk aktif berkontribusi dalam mewujudkan pola konsumsi dan produksi yang bertanggung jawab. Eco Solve hadir dengan berbagai fitur yang mudah digunakan dan tampilan yang menarik untuk meningkatkan pengalaman pengguna dalam mengakses informasi dan berpartisipasi dalam aksi pelestarian lingkungan.

## Latar Belakang  
Dengan terus meningkatnya jumlah populasi dan konsumsi yang tidak terkendali, dampak negatif terhadap lingkungan menjadi semakin besar. Di sisi lain, semakin banyak orang yang menyadari pentingnya keberlanjutan dan bagaimana tindakan individu dapat berkontribusi pada perubahan positif. **Eco Solve** dikembangkan untuk memberikan solusi praktis bagi pengguna yang ingin terlibat dalam menjaga lingkungan, dengan cara yang mudah dan menyenangkan. Aplikasi ini menyatukan edukasi tentang SDG 12 dengan aksi nyata melalui fitur-fitur interaktif, seperti donasi sampah dan chatbot berbasis AI, untuk memudahkan pengguna berpartisipasi dalam upaya pengelolaan sampah dan konsumsi yang bertanggung jawab.

## Tujuan
- **Edukasi dan Kesadaran:** Memberikan pemahaman yang lebih mendalam mengenai SDG 12, khususnya tentang konsumsi dan produksi yang berkelanjutan.  
- **Memberdayakan Pengguna:** Membantu pengguna untuk melakukan tindakan nyata yang dapat mengurangi jejak karbon dan mendukung keberlanjutan melalui donasi sampah dan penggunaan aplikasi secara aktif.  
- **Visualisasi Data:** Menyajikan data konsumsi dan produksi dalam bentuk grafik yang mudah dipahami, untuk memotivasi perubahan perilaku masyarakat.  
- **Membangun Komunitas:** Mengajak masyarakat untuk terlibat langsung dalam program dan inisiatif lingkungan dengan cara yang menyenangkan dan interaktif.

## Fitur Utama
### **Fitur untuk Pengguna (User):**
1. **Autentikasi Akun:**  
   Pengguna dapat membuat akun, login, dan melakukan pemulihan kata sandi menggunakan Firebase Authentication untuk menjamin keamanan data dan akses yang personal.

2. **Artikel Edukatif:**  
   Aplikasi ini menyediakan dua artikel utama yang membahas tentang SDG 12 dan cara-cara praktis untuk mewujudkannya, memberikan pengetahuan penting bagi pengguna mengenai keberlanjutan.

3. **Donasi Sampah (CRUD):**  
   Pengguna dapat dengan mudah mendonasikan sampah yang mereka miliki melalui sistem CRUD (Create, Read, Update, Delete). Fitur ini memungkinkan pengguna untuk memasukkan data jenis sampah, jumlah, dan berat, serta mengelola informasi tersebut sesuai kebutuhan.

4. **Chatbot AI:**  
   Chatbot berbasis AI yang dirancang untuk memberikan jawaban otomatis atas pertanyaan pengguna mengenai aplikasi, SDG 12, dan masalah terkait konsumsi dan produksi yang berkelanjutan. Chatbot ini bertujuan untuk mempermudah interaksi pengguna dengan aplikasi.

5. **Grafik Data Konsumsi:**  
   Eco Solve menyajikan data konsumsi dan produksi di Indonesia berdasarkan tahun 2022 dalam bentuk grafik yang mudah dipahami. Ini membantu pengguna untuk melihat tren dan pola konsumsi serta memberikan wawasan mengenai perubahan yang perlu dilakukan.

6. **Navigasi yang Mudah:**  
   Aplikasi ini dilengkapi dengan bottom navigation dan navigation drawer untuk memudahkan pengguna berpindah antar fitur aplikasi. Menu ini memungkinkan pengguna untuk mengakses halaman utama, chatbot, donasi sampah, artikel, dan informasi lebih lanjut tentang pengembang aplikasi.

### **Fitur untuk Admin:**
1. **Manajemen Data Pengguna dan Donasi:**  
   Admin dapat mengelola data pengguna dan informasi donasi sampah yang masuk melalui Firebase Firestore. Data ini bisa dipantau dan dianalisis untuk meningkatkan pengalaman pengguna dan efektivitas aplikasi.

2. **Penyimpanan Data Media:**  
   Admin dapat mengelola penyimpanan data gambar yang diunggah oleh pengguna, seperti gambar sampah yang didonasikan, menggunakan Firebase Storage.

3. **Laporan dan Statistik:**  
   Admin dapat melihat statistik penggunaan aplikasi, jumlah donasi sampah, dan grafik konsumsi untuk memonitor kontribusi pengguna terhadap tujuan keberlanjutan.

## Panduan Instalasi
Untuk mengimplementasikan dan menjalankan **Eco Solve**, berikut adalah langkah-langkah instalasi yang perlu diikuti:

1. **Clone Repository:**  
   Pertama, clone repository ini ke lokal Anda.  
   ```bash  
   git clone https://github.com/andrsginting/Eco-Solve-SDG-12.git  
   cd eco-solve  
   ```

2. **Konfigurasi Firebase:**
   - Buat proyek Firebase melalui [Firebase Console](https://console.firebase.google.com/).  
   - Aktifkan Firebase Authentication, Firestore Database, dan Firebase Storage di proyek Firebase Anda.  
   - Unduh file `google-services.json` dan letakkan di direktori `app/` pada proyek Android Anda.
   - Tambahkan dependensi Firebase pada file `build.gradle` sesuai petunjuk di dokumentasi Firebase.

3. **Menyinkronkan Gradle:**
   - Setelah mengonfigurasi Firebase, sinkronkan gradle untuk memastikan semua dependensi terinstal dengan benar.

4. **Menjalankan Aplikasi:**
   - Buka proyek di Android Studio.
   - Pastikan perangkat Android atau emulator Anda sudah siap.
   - Klik "Run" untuk memulai aplikasi.

5. **Verifikasi:**
   - Setelah aplikasi berjalan, verifikasi semua fitur seperti autentikasi akun, chatbot, donasi sampah, dan grafik data konsumsi untuk memastikan aplikasi berfungsi dengan baik.
