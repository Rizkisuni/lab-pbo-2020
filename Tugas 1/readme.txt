

1. Mendeskripsikan program
   > Class Penumpang
-   Class ini mewakili entitas penumpang bus
-   Satu objek penumpang mewakili satu penumpang
-   Setiap penumpang mempunyai attribut nama, umur, dan status hamil
-   Method Penumpang() merupakan method constructor yang akan memberikan nilai awal kepada attribute.
-   Method getNama(), getUmur(), dan getHamil() adalah method accessor yang mengembalikan nilai yang diminta.

2.  Class Bus
-   Class ini mewakili bus
-   Class ini memiliki attribute berupa objek dari Class Penumpang
-    Method getPenumpang….() mengembalikan list penumpang yang diminta.
-   Method getJumlahPenumpang….() mengembalikan jumlah penumpang yang diminta.
-   Method NaikPenumpang() berfungsi untuk menambahkan penumpang ke dalam Bus (jika ada kursi     untuk penumpang tsb). 
-   Method ini mengembalikan true jika penumpang berhasil naik dan menambahkan penumpang tsb     ke dalam Array penumpang, dan mengembalikan false jika penumpang tidak bias naik.
    Note : ikuti aturan penumpang seperti hasil observasi di atas,
-   Method turunkanPenumpang(nama) menerima parameter nama penumpag. Jika nama penumpang     ditemukan, maka hapus penumpang tersebut dari Array penumpang dan kembalikan nilai true.     Sebaliknya, kembalikan false.

3.  Class Main
•   Pada method main() dideklarasikan sebuah objek Bus. Pada method ini anda akan mensimulasikan proses naik dan turunnya penumpang dari bus.


INSTALISASI

$ cd Tugas 1

$ ls
  Bus.java
  Penumpang.java
  Main.java

*//Compile
$javac Main.java

*//Run
$java Main

Run program
1. Pertama membuka cmd
2. buka folder file yang telah disimpan (cd ....)
3. compile file main.java
4. setelah itu kita Run
5. dari output yang keluar kita pilih menu yang ditampilkan
6. selesai