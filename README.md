# Jobsheet-3-Embedded-System
Jobsheet 3 : TOPOLOGI JARINGAN LOKAL DAN WIFI

A. ALAT DAN BAHAN

ESP32
Breadboard
Kabel jumper
Sensor DHT 11, RFID
LED (5) dan Push Button (3)
Servo
Resistor 330,1K, 10K Ohm (@ 3)
B. TEORI SINGKAT

Wireless Fidelity atau yang lebih awam kita sebut wifi adalah suatu teknologi yang menggunakan gelombang radio dalam rentang 2,4GHz sampai dengan 5GHz untuk menghubungkan perangkat seperti PC/laptop, smartphone, dan perangkat microcontroller seperti ESP32 dan ESP8266 ke jaringan lokal wireless untuk bisa mengakses internet. Untuk dapat melakukan akses internet tersebut,makaperangkat elektronik diatas perlu berada dalam satu titik akses atau hotspot jaringan nirkabel sehingga terhubung dengan wifi. Pada umumnya jaringan wifidapat menjangkau hingga 20 meter didalam ruangan dan lebih dari 20 meter untuk di luar ruangan. Pada awal kemunculannya, wifi hanya digunakan sebagaiperangkat nirkabel pada jaringan LAN (Local Area Network) akan tetapi karena pesatnya teknologi di zaman sekarang wifi menjadi kebutuhan sehari-hari untukakses jaringan internet dan IoT.Berbagai data yang kita minta atau kirimkan melalui wifi didistribusikanmelalui gelombang radio di udara. Supaya data tersebut bisa terbaca maka harusada yang namanya wireless adaptor yang menghubungkan ke wifi. Gelombang radio yang berwujud sinyal ini lalu dikirim menuju router yang fungsinya untukmemecahkan kode. Setelah terbaca maka data dikirim ke jaringan internet yang memanfaatkan koneksi ethernet. Karena jaringan wifi ini bekerja dua arah makatiap data yang diterima dalam waktu yang sama menjadi kode pada tiap paket datalalu dikirim kembali dalam bentuk sinyal radio yang diterima adaptor komputernirkabel.

Percobaan a.  ESP32 Wi-Fi Modes dan Wifi-Scan

Hasil Percobaan :

![A](https://user-images.githubusercontent.com/121012286/208874337-eb9c9139-7434-48d9-8a52-84abee81ab44.jpg)

Pada percobaan pertama mendapatkan hasil jaringan wifi, kita mencoba untuk melakukan pengecekan apabila koneksi Wi-Fi dimatikan. Pada pemrograman tertulis “// if WiFi is down, try reconnecting every CHECK_WIFI_TIME seconds if ((WiFi.status() != WL_CONNECTED) && (currentMillis - previousMillis >=interval)) { Serial.print(millis()); Serial.println("Reconnecting to WiFi..."); “ yang mana keika Wi-Fi down maka program akan mencoba untuk mencari kembali koneksi Wi-Fi dan akan bertuliskan ("Reconnecting to WiFi..." seperti yang ditunjukkan pada output di samping

Percobaan b. Menghubungkan ESP32 dengan Jaringan Wi-Fi

![B](https://user-images.githubusercontent.com/121012286/208874700-e432e53a-d3ff-4919-a8e5-def19ed588bc.png)

Pada percobaan kedua yaitu mencoba menyambungkan dengan wifi

Percobaan c.  Menghubungkan Kembali (Re-connect) ESP32 dengan Jaringan Wi-Fi

![C](https://user-images.githubusercontent.com/121012286/208875064-a44a8093-a67d-43d3-9434-ac648fe9e360.png)

Pada percobaan di atas dilakukan percobaan unntuk mengkoneksikan ulang ESP dengan jaringan wifi

Percobaan d.  Mengganti Hostname ESP32

![D](https://user-images.githubusercontent.com/121012286/208875320-ef7efc80-e3bf-4d1e-abda-fe510e9910ad.png)

![D 2](https://user-images.githubusercontent.com/121012286/209135500-c99e5fd7-828c-4165-b9d2-8cb5d1ae0326.png)


Pada percobaan di atas yaitu mencoba untuk mengganti nama hostname ESP

E. Mengirim Data Sensor ke Database

![E](https://user-images.githubusercontent.com/121012286/209135534-aa8a6153-49b5-4e8c-8920-e29794b50678.png)

