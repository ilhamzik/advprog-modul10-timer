Adpro - Modul 10 - Timer

### Muhammad Ilham Zikri - 2206083533 - Adpro A 

## 1.2
*screenshot akan menyusul karena error*
Dapat dilihat pada screenshot diatas, "halohalo" muncul lebih dahulu daripada statement lain. Ini disebabkan karena aku menggunakan perintah print untuk statement "halohalo" diluar asynchronus task dan langsung diampu oleh main thread. Jadi program akan mengerjakan urut sesuai baris dulu, kemudian baru menjalankan asynchronus.