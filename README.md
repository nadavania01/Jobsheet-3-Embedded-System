# Jobsheet-3-Embedded-System
Jobsheet 3 : TOPOLOGI JARINGAN LOKAL DAN WIFI



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

