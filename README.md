Adpro - Modul 10 - Timer

### Muhammad Ilham Zikri - 2206083533 - Adpro A 

## 1.2
![image](https://github.com/ilhamzik/advprog-modul10-timer/assets/124953758/035cae8b-b8b8-4742-a10a-0598767dd36a)

Dapat dilihat pada screenshot diatas, "halohalo" muncul lebih dahulu daripada statement lain. Ini disebabkan karena aku menggunakan perintah print untuk statement "halohalo" diluar asynchronus task dan langsung diampu oleh main thread. Jadi program akan mengerjakan urut sesuai baris dulu, kemudian baru menjalankan asynchronus.


## 1.3
![image](https://github.com/ilhamzik/advprog-modul10-timer/assets/124953758/84a0221d-d59c-4b50-8fb8-2a2dc774173e)

Dapat diilihat pada screenshot diatas, program tidak berhenti setelah semua statement di print. Ini disebabkan oleh drop function yang telah dihapus dan tidak ada penanda untuk menghentikan program pada eksekutor. Urutan print juga tidak jelas, ini disebabkan eksekutor kesulitan memanage task banyak (tiap task yang dibuat spawner memakan resource).
