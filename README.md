Tugas  4   OAk

1.Jelaskan Struktur antar Hubungan dan beri contohnya

Jawaban  :

Dalam komputer, berbagai komponen seperti prosesor, memori, dan perangkat input-output harus bisa saling berkomunikasi agar sistem dapat bekerja dengan baik. Cara komponen-komponen ini terhubung dan bertukar data disebut sebagai struktur antar hubungan. Salah satu metode utama dalam komunikasi ini adalah menggunakan bus, yaitu jalur yang menghubungkan berbagai perangkat dalam komputer untuk mentransfer data atau daya.

Bus berfungsi sebagai jalan utama bagi informasi yang berpindah dari satu komponen ke komponen lainnya. Misalnya, saat kita mengetik di keyboard, data yang kita masukkan dikirim ke prosesor melalui bus sebelum akhirnya ditampilkan di layar. Begitu juga dengan komponen lain seperti kartu grafis dan kartu suara, yang menggunakan bus untuk berkomunikasi dengan sistem utama komputer.

Ada berbagai jenis bus yang digunakan dalam komputer, tergantung pada kebutuhan kecepatan dan jenis perangkat yang terhubung. Contohnya adalah bus PCI, yang sering digunakan untuk perangkat keras berkecepatan tinggi seperti kartu grafis, serta USB, yang memungkinkan perangkat eksternal seperti mouse, keyboard, dan flash drive terhubung dengan mudah. Setiap jenis bus memiliki kelebihan dan kekurangannya sendiri, tetapi semuanya berfungsi untuk memastikan bahwa komputer dapat bekerja secara efisien dan semua komponen dapat berkomunikasi dengan baik.

2.Bila Terlalu banyak modul atau perangkat dihubungkan pada bus maka akan terjadi penurunan kinerja, Sebutkan Penyebabnya ?

Jawaban  :

jika terlalu banyak perangkat atau modul yang terhubung ke bus dalam sebuah sistem komputer, maka kinerjanya bisa menurun. Hal ini terjadi karena beberapa faktor utama.

Pertama, kapasitas transfer bus bisa habis. Setiap bus memiliki batas maksimal dalam mentransfer data. Jika terlalu banyak data dikirim melewati bus dalam waktu bersamaan, maka kecepatannya akan berkurang, menyebabkan keterlambatan dalam pengiriman informasi.

Kedua, antrian penggunaan bus menjadi lebih panjang. Semakin banyak perangkat yang terhubung dan menggunakan bus secara bersamaan, semakin lama waktu tunggu bagi setiap perangkat untuk bisa mentransfer data. Ini seperti jalan raya yang semakin padat, sehingga kendaraan harus menunggu lebih lama untuk melintas.

Ketiga, waktu koordinasi penggunaan bus semakin lama. Dalam sistem komputer, ada mekanisme untuk mengatur giliran perangkat dalam menggunakan bus. Jika terlalu banyak perangkat yang terhubung, maka sistem membutuhkan waktu lebih lama untuk mengoordinasikan akses ke bus, yang akhirnya memperlambat proses komunikasi data.

Keempat, konflik akses bus bisa terjadi. Jika beberapa perangkat mencoba mengakses bus dalam waktu bersamaan tanpa sistem pengaturan yang baik, maka bisa terjadi tabrakan data yang menyebabkan gangguan atau bahkan kegagalan dalam transfer informasi.

Kelima, kinerja bus sangat bergantung pada frekuensi clock. Bus dengan frekuensi clock yang lebih rendah akan memiliki kecepatan transfer data yang lebih lambat dibandingkan dengan bus yang memiliki clock lebih tinggi.

Terakhir, jenis arsitektur bus yang digunakan juga berpengaruh. Bus yang lebih lama seperti ISA memiliki kecepatan jauh lebih rendah dibandingkan dengan standar yang lebih baru seperti PCIe. Oleh karena itu, memilih jenis bus yang sesuai dengan kebutuhan sangat penting untuk menjaga kinerja sistem tetap optimal.
   

3.Umumnya perangkat berprioritas paling rendah memiliki waktu tunggu rata-rata yang paling singkat. Dengan dasar ini biasanya CPU diberi perioritas tertinggi pada SBI. Sebutkan alasan perangkat berprioritas 16 memiliki waktu tunggu rata-rata paling rendah ? Di bawah      kondisi Seperti apa keadaan diatas tidak berlaku ?

Jawaban  :

Perangkat dengan prioritas 16 memiliki waktu tunggu rata-rata paling rendah karena perangkat dengan prioritas lebih tinggi sering kali memiliki lebih banyak tugas yang harus diselesaikan lebih dulu. Akibatnya, perangkat dengan prioritas lebih rendah dapat segera diproses tanpa banyak penundaan. Namun, kondisi ini tidak berlaku jika sistem menggunakan metode penjadwalan berbeda seperti Round Robin, jika beban kerja tidak merata, atau jika terjadi konflik akses yang membuat perangkat prioritas tinggi terus mendominasi penggunaan bus. Dalam kondisi tersebut, perangkat dengan prioritas lebih rendah bisa tetap mengalami waktu tunggu yang lebih lama.








  
