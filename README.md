# UTS-Pengenalan-Big-Data
1.	Tiga DBMS yang bisa digunakan untuk mengolah Big Data. <br>
•	Cassandra <br>
 atau lengkap APACHE CASSANDRA adalah salah satu produk open source untuk menajemen database yang didistribusikan oleh Apache yang sangat scalable (dapat diukur) dan dirancang untuk mengelola data terstruktur yang berkapasitas sangat besar (Big Data) yang tersebar di banyak server.<br>
•	MySQL <br>
adalah salah satu aplikasi yang termasuk vendor DBMS yang merupakan salah satu aplikasi umum dan paling banyak digunakan oleh pengguna data maupun para programmer. Salah satu alasan mengapa MySQL banyak digunakan karena aplikasi ini terkenal sebagai open source atau gratis. Jadi, Anda tidak akan dikenakan biaya apapun ketika mengunduh maupun juga mengoperasikannya.<br>
•	MariDB<br>
adalah aplikasi DBSM yang merupakan aplikasi database dari MySQL. Aplikasi ini tercipta melalui inisiatif oleh para pengembang atau developer yang mana sebelumnya mereka menggunakan MySQL. Alasan pembuatan MariaDB adalah karena telah diakuisisinya MySQL oleh pihak Oracle yang membuat produk ini menjadi produk properietary.<br>
2.	Mebuat sebuah database Hotel dengan acuan pencarian Points Of Interest.<br>
•	Desain database secara RDBMS.<br>
 ![](images/rdbms.png)<br>
•	Desain database secara model Cassandra.<br>
![](images/dbms.png)<br>
 
•	Proses instalasi apache Cassandra di Windows (10)<br>
•	Download java versi 1.8 sesuai dengan yang dibutuhkan Cassandra, apabila menggunakan versi yang lain akan terjadi error atau Cassandra tidak akan bisa dijalankan<br>
 ![](images/1.png)<br>
•	Kemudian download python dengan versi 2.7 <br>
 ![](images/2.png)<br>
•	Setelah java dan python sudah terinstal pastikan kembali sudah terdeteksi oleh sistem.<br>
 ![](images/3.png)<br>
•	Proses mendownload cassandra<br>
 ![](images/4.png)<br>
•	Setelah menginstal java, python, dan Cassandra sudah di download masukan directori file nya ke dalam PATH pada Envoirment System.<br>
 ![](images/5.png)<br>
•	Buat variable baru untuk JAVA dengan nama JAVA_HOME.<br>
  ![](images/6.png)<br>
•	Buat variable baru. Kemudian masukan direktori python kedalam path envoirment system.<br>
  ![](images/7.png)<br>
•	Buat juga variabel baru untuk memasukan direktori Cassandra dengan nama CASSANDRA_HOME.<br>
 ![](images/8.png)<br>
•	Setelah semua variable diubuat, buka Command Promt dengan admin. Jalankan perintah “cassandra” untuk menjalankan mesin apache Cassandra.
 ![](images/9.png)<br>
•	Setelah apache Cassandra terkoneksi, buka command promt lagi untuk menjalankan perintah Cqlsh ntuk memulai shell SQL. 
 ![](images/10.png)<br>
 •	Membuat tabel pada Cassandra<br>
 ![](images/11.png)<br>
 ![](images/12.png)<br>
 ![](images/13.png)<br>
•	Proses input data dan menampilkan data pada table yang sudah dibuat.<br>
 ![](images/14.png)<br>
 ![](images/15.png)<br>
 ![](images/16.png)<br>
 ![](images/17.png)<br>
 ![](images/18.png)<br>
•	Proses Update data dan menampilkan data pada tabel.<br>
Sebelum update<br>
![](images/19.png)<br>
Setelah di update<br>
![](images/20.png)<br>
•	Proses menghapus dan menampilkan data pada tabel.<br>
![](images/21.png)<br>
