## 1.2 Understanding How It Works  
![](./img/1.2_UnderstandingHowItWorks.png)  
Ketika main dijalankan, task `howdy!` dan `done!` akan dibuat dan  dimasukkan ke dalam antrian tetapi tidak langsung dijalankan. Setelah task dibuat, `hey hey` akan langsung ditampilkan karena tidak dimasukkan antrian terlebih dahulu. Setelah executor dijalankan, barulah task `howdy!` dan `done!` dijalankan.