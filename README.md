# Permainan-TicTacToe

## Tugas
Tuliskan semua Java Code diatas, kemudian pelajari code nya, dan ubahkan beberapa bagian untuk melihat perubahannya.

## Penjelasan Kode
![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/550db49e-2bae-4229-b193-691e2009a7bb)

Dalam skrip ini, modul tkinter digunakan untuk mengintegrasikan komponen antarmuka pengguna grafis (GUI) ke dalam program, memungkinkan pembuatan aplikasi dengan elemen-elemen seperti jendela, tombol, teks, dan lainnya. Ada juga penggunaan modul messagebox yang memungkinkan tampilan kotak pesan kepada pengguna dalam GUI, baik untuk pesan informasi, peringatan, atau konfirmasi. Gabungan modul-modul ini memfasilitasi pembuatan aplikasi dengan antarmuka interaktif dan kapabilitas memberikan umpan balik kepada pengguna.

![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/937bdf97-3907-4cb1-8538-5f37c527433a)

Kelas ini membantu dalam merepresentasikan berbagai kondisi yang mungkin terjadi dalam suatu permainan atau sistem yang memanfaatkan simbol-simbol ini. Misalnya, bisa jadi representasi dari kondisi sel di dalam permainan Tic-Tac-Toe (disebut juga sebagai permainan Batu Seremban atau Tiga Garis) di mana ada sel kosong, sel dengan tanda silang, dan sel dengan tanda lingkaran. Dengan menggunakan Enum, kita memastikan bahwa nilai-nilai yang diperbolehkan terbatas hanya pada nilai-nilai yang telah ditentukan.

![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/97ed02b6-da46-4cad-b5c4-8b26209cdd3c)

Potongan kode di atas mendefinisikan sebuah kelas bernama `GameState`. Kelas ini menggunakan modul `Enum` yang memungkinkan untuk membuat enumerasi atau daftar nilai yang dapat dipilih.  `GameState` digunakan untuk merepresentasikan kondisi-kondisi yang mungkin terjadi dalam permainan.

- `PLAYING` (0) menyatakan bahwa permainan sedang berlangsung.
- `DRAW` (1) menandakan bahwa permainan berakhir dalam kondisi imbang.
- `CROSS_WON` (2) artinya pemain yang menggunakan "X" menang.
- `NOUGHT_WON` (3) menandakan bahwa pemain yang menggunakan "O" menang.

Kode ini memudahkan untuk memeriksa dan mengelola status permainan dengan memeriksa nilai dari `GameState` yang sedang berlaku. Misalnya, jika permainan berakhir, kita bisa menggunakan `DRAW`, `CROSS_WON`, atau `NOUGHT_WON` untuk menentukan pemenang atau apakah permainan berakhir imbang.

![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/12c8235b-3e12-4a07-b8a1-a766980c7d54)

Kode ini berfungsi untuk mendefinisikan sebuah kelas Python bernama Cell yang memiliki tujuan untuk merepresentasikan sebuah sel dalam suatu struktur data yang mungkin digunakan untuk permainan papan.

![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/4ef9dabd-8a0a-4c88-8e3a-527c793dfe4a)
Kode di atas adalah representasi sederhana dari permainan Tic Tac Toe (Tic Tac Toe adalah permainan papan 3x3 dimana pemain mencoba untuk menempatkan simbol mereka (biasanya X atau O) secara bergantian di setiap kotak papan, tujuannya adalah untuk mencetak tiga dari simbol tersebut secara berurutan di baris, kolom, atau diagonal). 

![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/0c18f013-be47-44c6-a72f-f9321bd2bad2)
![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/046b2f98-50f2-409a-9a75-8de64310d606)
![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/58a36c61-71a1-4026-8b6f-e3a70438100c)
![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/dd1c866d-58e7-46d0-b89b-6f3d628ad299)

Kode tersebut sebagian besar berfokus pada antarmuka grafis pengguna (GUI) untuk permainan Tic-Tac-Toe, termasuk logika penggunaan canvas, pembuatan elemen-elemen visual, dan manipulasi status permainan.

![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/73d2777e-cb61-48d7-94af-e88667859d52)

Jadi, keseluruhan kode ini bertujuan untuk membuat jendela aplikasi "Tic Tac Toe" menggunakan Tkinter, menyiapkan logika permainan, menempatkan elemen-elemen GUI ke dalam jendela, dan menjalankan aplikasi sehingga dapat diakses dan dioperasikan oleh pengguna.

Setelah menjalankannya, program akan menghasilkan tampilan GUI Tic-Tac-Toe seperti yang terlihat di bawah ini:

![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/804bf486-b364-44c8-9de7-402af9d16c21)

Nanti dapat mengklik kolom, di mana klik pertama akan menampilkan simbol X, dan setiap klik kedua akan menampilkan simbol O, hingga terbentuk susunan X atau O yang sejajar baik secara vertikal, diagonal, maupun horizontal. Berikut adalah contoh hasil permainannya:


![image](https://github.com/cynthiarahma/Permainan-TicTacToe/assets/149099370/9170c667-1d73-442b-bf16-e1a59d907827)


