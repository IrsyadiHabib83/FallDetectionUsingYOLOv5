# FallDetectionUsingYOLOv5
Tugas Besar Viskom 

Fall Detection menggunakan YOLOv5

YOLOv5 dari Ultralytics merupakan model terkini yang memanfaatkan teknologi mutakhir (state-of-the-art/SOTA), membangun atas keberhasilan versi YOLO sebelumnya dan menghadirkan fitur-fitur baru serta perbaikan untuk meningkatkan kinerja dan fleksibilitas lebih lanjut. Desain YOLOv5 didasarkan pada prinsip menjadi cepat, akurat, dan mudah digunakan, menjadikannya pilihan yang sangat baik untuk berbagai tugas seperti deteksi objek, segmentasi instan, dan klasifikasi gambar.

YOLO v5 menggunakan arsitektur yang lebih kompleks bernama EfficientDet (arsitektur ditampilkan di bawah), yang berasal dari struktur jaringan EfficientNet. Pemilihan arsitektur yang lebih kompleks dalam YOLO v5 memungkinkannya mencapai tingkat akurasi yang lebih tinggi serta generalisasi yang lebih baik untuk berbagai kategori objek. Perbedaan mendasar antara YOLO dan YOLO v5 adalah pada data pelatihan yang digunakan untuk mengajari model deteksi objek. YOLO dilatih menggunakan dataset PASCAL VOC yang terdiri dari 20 kategori objek, sedangkan YOLO v5 dilatih pada dataset yang lebih besar dan beragam bernama D5, mencakup total 600 kategori objek.

Metode baru yang diperkenalkan oleh YOLO v5 dalam menghasilkan kotak anchor disebut "dynamic anchor boxes." Proses ini melibatkan penggunaan algoritma pengelompokan untuk mengelompokkan kotak pembatas ground truth ke dalam klaster, dan kemudian menggunakan pusat massa dari klaster tersebut sebagai kotak anchor. Pendekatan ini memungkinkan agar kotak anchor lebih akurat sesuai dengan ukuran dan bentuk objek yang terdeteksi.

YOLO v5 juga memperkenalkan konsep "spatial pyramid pooling" (SPP), yaitu jenis lapisan pooling yang digunakan untuk mereduksi resolusi spasial peta fitur. Penggunaan SPP bertujuan untuk meningkatkan kinerja deteksi pada objek-objek kecil dengan memungkinkan model melihat objek pada berbagai skala. Meskipun YOLO v4 juga menggunakan SPP, YOLO v5 hadir dengan sejumlah perbaikan pada arsitektur SPP yang menghasilkan hasil yang lebih baik.

Meskipun YOLO v4 dan YOLO v5 menggunakan fungsi kerugian yang serupa untuk melatih model, YOLO v5 memperkenalkan istilah baru bernama "CIoU loss." Istilah ini merupakan varian dari fungsi kerugian IoU yang dirancang untuk meningkatkan kinerja model pada dataset yang memiliki ketidakseimbangan.
Nama Kelompok : 
Irsyadi Habib    1301204327
Surya Abadi      13012
