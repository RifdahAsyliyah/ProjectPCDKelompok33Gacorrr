KLASIFIKASI JENIS JAMUR AGARICUS DAN AMANITA MENGGUNAKAN EKSTRAKSI FITUR GLCM DAN METODE KNN, SVM, SERTA RANDOM FOREST

Jamur merupakan organisme eukariotik heterotrof yang termasuk ke dalam Kingdom Fungi dan tidak memiliki klorofil sehingga memperoleh nutrisi dengan cara menyerap zat organik dari lingkungannya. Jamur banyak dimanfaatkan sebagai bahan pangan karena kandungan protein, serat, dan mineralnya, namun tidak semua jamur aman untuk dikonsumsi karena beberapa jenis mengandung racun yang berbahaya bagi tubuh.

Jamur Agaricus merupakan genus jamur yang umumnya dapat dikonsumsi dan banyak ditemukan di alam liar maupun dibudidayakan. Sementara itu, jamur Amanita dikenal sebagai salah satu genus jamur paling berbahaya karena mengandung senyawa racun yang dapat memengaruhi sistem saraf, ginjal, dan hati hingga bersifat mematikan. Kedua genus ini memiliki kemiripan morfologi yang tinggi sehingga sulit dibedakan secara kasat mata, dan kesalahan identifikasi dapat berakibat fatal bagi kesehatan manusia.

Oleh karena itu, diperlukan sistem klasifikasi otomatis berbasis pengolahan citra digital. Projek ini menggunakan Gray Level Co-occurrence Matrix (GLCM) sebagai metode ekstraksi fitur tekstur citra untuk menghasilkan fitur seperti kontras, homogenitas, korelasi, dan energi. Fitur tersebut kemudian diklasifikasikan menggunakan tiga algoritma machine learning, yaitu K-Nearest Neighbor (KNN) yang bekerja berdasarkan kedekatan jarak antar data, Support Vector Machine (SVM) yang mencari hyperplane terbaik untuk memisahkan kelas, dan Random Forest yang menggabungkan banyak pohon keputusan untuk menghasilkan prediksi yang lebih akurat. Perbandingan ketiga metode ini bertujuan untuk menemukan pendekatan terbaik dalam mengklasifikasikan jamur Agaricus dan Amanita secara otomatis dan efisien.

Dalam proyek ini, citra jamur akan diproses melalui serangkaian tahapan preprocessing untuk meningkatkan kualitas citra dan menonjolkan fitur-fitur penting. Tahap ini melibatkan tiga kali percobaan dengan metode sebagai berikut:
- Percobaan 1: Resize (480 x 640) dan Grayscale
- Percobaan 2: Resize (480 x 640), Grayscale, Sharpening, dan Smoothing
- Percpbaan 3: Resize (480 x 640), Grayscale, Sharpening, Smoothing, Prewitt dan Thresholding
