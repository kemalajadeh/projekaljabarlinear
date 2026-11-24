# projekaljabarlinear
repository untuk projek matkul Aljabar Linear

LATAR BELAKANG:

Perkembangan teknologi informasi membuat jumlah data teks yang dihasilkan setiap hari terus bertambah, mulai dari artikel berita, dokumen akademik, ulasan produk, sampai pesan di media sosial. Dalam bidang Teknik Informatika, jumlah data sebesar ini menimbulkan satu kebutuhan yang sering muncul: bagaimana sebuah sistem bisa menentukan seberapa mirip dua teks. Kebutuhan ini dijumpai pada mesin pencari yang mengurutkan dokumen berdasarkan kecocokannya dengan kata kunci, sistem deteksi plagiarisme, sistem rekomendasi konten, pengelompokan dokumen, dan chatbot yang mencari jawaban paling relevan.

Komputer tidak memahami teks seperti manusia, sehingga teks harus diubah dulu ke bentuk numerik. Salah satu pendekatan yang umum adalah representasi vektor. Setiap dokumen dinyatakan sebagai vektor, dengan setiap komponennya menunjukkan frekuensi kemunculan sebuah kata. Dengan cara ini, persoalan membandingkan teks berubah menjadi persoalan membandingkan vektor di ruang berdimensi tinggi, dan di titik inilah aljabar linear berperan.

Salah satu ukuran kemiripan yang paling banyak dipakai adalah cosine similarity. Ukuran ini dibangun dari konsep dasar aljabar linear, yaitu hasil kali titik (dot product) dan norm vektor. Kemiripan dua vektor u dan v dihitung dari nilai cosinus sudut di antara keduanya:

cos θ = (u · v) / (‖u‖ ‖v‖)

Pendekatan ini punya dasar matematis yang kuat. Ketaksamaan Cauchy-Schwarz menjamin bahwa nilai cosinus selalu berada di antara -1 dan 1, sehingga hasilnya konsisten dan mudah ditafsirkan. Dua vektor yang saling tegak lurus (ortogonal) menandakan dua dokumen yang tidak punya kesamaan. Selain itu, karena yang dibandingkan adalah arah vektor dan bukan panjangnya, dokumen yang panjang dan dokumen yang pendek dengan topik sama tetap bisa dinilai mirip.

Konsep-konsep tersebut dipelajari dalam mata kuliah Aljabar Linear, khususnya pada materi vektor, hasil kali titik, norm, dan ruang hasil kali dalam. Namun, materi itu sering dipelajari hanya sebagai teori dan latihan hitung, sehingga hubungannya dengan permasalahan nyata di bidang informatika belum terlihat jelas. Karena itu, project ini dibuat untuk menunjukkan bagaimana konsep vektor dan hasil kali dalam diterapkan pada cosine similarity untuk mengukur kemiripan teks, sehingga pemahaman teori dan penerapannya dalam bidang Teknik Informatika bisa terhubung.
