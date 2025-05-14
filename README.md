# module-10

1.2
![Hasil penambahan "Michael's Laptop: hey hey" tepat setelah `spawner.spawn(...)`](./static/image/1_2.png)
Pada gambar terlihat bahwa string "Michael's Laptop: hey hey" (akan disebut sebagai string A untuk mempersingkat) berada di atas "Michael's Laptop: howdy!" (akan disebut sebagai string B untuk mempersingkat). Hal ini dikarenakan kode yang berada pada fungsi yang asynchronous membutuhkan waktu untuk dijadwalkan terlebih dahulu sebelum dieksekusi, sedangkan kode yang berada langsung tanpa fungsi asynchronous dapat langsung dijalankan. Inilah yang menyebabkan string A berada di atas string B. Meskipun program yang menghasilkan string B sudah dijalankan, namun masih dijadwalkan dan belum dieksekusi.