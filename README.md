# LP7C2DPBO2022
Saya Bayu Wicaksono NIM 2106836 mengerjakan Latihan 7 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Design Program
Program ini memiliki 7 class dan 1 interface, antara lain :
1. class Controller, berfungsi untuk mengontrol objek dalam sebuah game. Class Controller memiliki dua atribut yaitu game dan handler, yang berturut-turut merupakan objek Game dan Handler. Metode utama pada class Controller adalah keyPressed() dan keyReleased(). Method keyPressed() dipanggil ketika pengguna menekan tombol pada keyboard dan method keyReleased() dipanggil ketika pengguna melepaskan tombol pada keyboard

2. class Display, berfungsi sebagai tampilan utama dalam permainan. Class Display memiliki dua metode publik yaitu open dan close. Metode open menerima objek Game dan menambahkannya ke dalam frame, kemudian menampilkan frame dan memulai permainan sedangkan metode close menutup frame permainan. 

3. class Game, class ini memiliki beberapa metode yang digunakan untuk mengontrol jalannya permainan, termasuk metode start() dan stop() untuk memulai dan menghentikan game, metode render() untuk merender tampilan game, dan metode loop() untuk menjalankan loop utama game.

4. class GameObject, class yang mengimplementasikan interface GameInterface. Kelas ini memiliki beberapa atribut seperti posisi (x dan y), dimensi (lebar dan tinggi), kecepatan (velX dan velY), serta jenis objek (type). Class ini juga memiliki beberapa method getter dan setter untuk atribut-atribut tersebut, dan sebuah method getBoundingBox() yang mengembalikan objek Rectangle yang merepresentasikan kotak pembatas objek tersebut.

5. class Handler, 
6. class Player
7. class Synchronization
8. interface GameInterface
