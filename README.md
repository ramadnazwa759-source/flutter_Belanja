#  Konsep Navigasi dan Rute Dari Layout Belanja

## Praktikum 5: Membangun Navigasi di Flutter
- Langkah 1 : Siapkan project baru
<img width="160" height="263" alt="image" src="https://github.com/user-attachments/assets/1019e835-2ff5-4c33-8668-7053707706b8" />

- Mendefinisikan Router
<img width="161" height="84" alt="image" src="https://github.com/user-attachments/assets/8b8f5b82-232b-4de8-a8ab-e489e10b9367" />

- Melengkapi Kode pada main
- Membuat data pada folder model
<img width="936" height="250" alt="image" src="https://github.com/user-attachments/assets/dd24e55f-6358-4113-8579-32084b22ed80" />

- Lengkapi kode di class HomePage dan Membuat ListView dan itemBuilder
hasil akhir
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/72066536-90f8-478f-90b3-5fd1d8216aab" />

## Tugas Praktikum 2
1. Untuk melakukan pengiriman data ke halaman berikutnya, cukup menambahkan informasi arguments pada penggunaan Navigator.
Navigator.pushNamed(context, '/item', arguments: item);
<img width="1464" height="1564" alt="carbon" src="https://github.com/user-attachments/assets/36c7ddb6-316f-4b9a-b808-1ac0d9af0966" />

2. Tambahkan kode berikut pada blok fungsi build dalam halaman ItemPage.
final itemArgs = ModalRoute.of(context)!.settings.arguments as Item;
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/717decf6-e48c-42fc-b16e-ca709d51abae" />

4. Tambahkan atribut foto produk, stok, dan rating. Ubahlah tampilan menjadi GridView seperti di aplikasi marketplace pada umumnya.
Ubahlah tampilan menjadi GridView yaitu tampilan menjadi 2 kolom
<img width="794" height="1000" alt="image" src="https://github.com/user-attachments/assets/bfb28134-0dcb-4627-b7c2-9acc4c21942e" />

5. 








 

