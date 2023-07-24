# game-tetris.github.io
link Priview: https://asep38.github.io/game-tetris.github.io/

# deskripsi
Tetris adalah permainan video klasik dan ikonik yang menantang, menghibur, dan mengasah kemampuan pemain dalam strategi dan refleks. Dalam permainan ini, 
pemain harus mengatur dan menyusun berbagai bentuk geometris yang disebut tetrominoes, yang terdiri dari empat kotak yang berbeda, saat jatuh dari atas layar. 
Tujuan utama pemain adalah untuk membentuk baris horizontal penuh dengan tetrominoes, sehingga baris tersebut akan hilang dan memberi ruang kosong untuk mengisi 
lebih banyak tetrominoes.

# Cerita
Tetris pertama kali dibuat oleh seorang programmer asal Rusia bernama Alexey Pajitnov. Pada tahun 1984, saat bekerja di Akademi Ilmu Pengetahuan di Moskow, Pajitnov menciptakan permainan ini sebagai bagian dari proyek penelitiannya di bidang kecerdasan buatan. Dia menggunakan komputer elektronika 60-an, Electronika 60, untuk mengembangkan permainan tersebut.

Nama "Tetris" berasal dari kata "Tetra" yang berarti "empat" dalam bahasa Yunani. Nama ini mencerminkan fakta bahwa semua bentuk atau blok dalam permainan terdiri dari empat kotak (tetrominoes).

Pada tahun 1986, Tetris dirilis secara resmi oleh perusahaan perangkat lunak Soviet, Elektronorgtechnica (ELORG). Game ini menjadi sangat populer di kalangan pemain komputer Soviet. Namun, popularitasnya tidak berhenti di wilayah Soviet saja.

# Fungsi Yang di Gunakan
1. checkBottom(): Fungsi ini digunakan untuk memeriksa apakah bentuk tetromino saat ini dapat bergerak ke bawah atau telah mencapai batas bawah papan permainan.

2. getTruncedPosition(): Fungsi ini mengembalikan posisi tetromino saat ini dalam format bilangan bulat (truncated) untuk digunakan dalam perhitungan posisi tetromino.

3. checkLeft(): Fungsi ini memeriksa apakah bentuk tetromino saat ini dapat bergerak ke kiri atau telah mencapai batas kiri papan permainan.

4. checkRight(): Fungsi ini memeriksa apakah bentuk tetromino saat ini dapat bergerak ke kanan atau telah mencapai batas kanan papan permainan.

5. moveRight(): Fungsi ini memindahkan bentuk tetromino saat ini ke kanan jika memungkinkan.

6. moveLeft(): Fungsi ini memindahkan bentuk tetromino saat ini ke kiri jika memungkinkan.

7. moveBottom(): Fungsi ini memindahkan bentuk tetromino saat ini ke bawah jika memungkinkan, dan juga meningkatkan skor pemain.

8. changeRotation(): Fungsi ini digunakan untuk mengubah rotasi dari bentuk tetromino saat ini.

9. deleteCompleteRows(): Fungsi ini menghapus baris penuh dari papan permainan jika ada dan menambahkan skor pemain sesuai dengan jumlah baris yang dihapus.

10. drawRect(x, y, width, height, color): Fungsi ini digunakan untuk menggambar persegi dengan warna yang ditentukan pada kanvas.

11. drawBackground(): Fungsi ini digunakan untuk menggambar latar belakang papan permainan.

12. drawCurrentTetris(): Fungsi ini digunakan untuk menggambar bentuk tetromino saat ini di atas kanvas permainan.

13. drawSquares(): Fungsi ini digunakan untuk menggambar semua tetromino yang telah tertumpuk di papan permainan.

14. drawNextShape(): Fungsi ini digunakan untuk menggambar bentuk tetromino selanjutnya yang akan muncul di sebelah kanan kanvas permainan.

15. drawScore(): Fungsi ini digunakan untuk menggambar skor pemain di kanvas skor.

16. drawGameOver(): Fungsi ini digunakan untuk menggambar pesan "Game Over" ketika permainan berakhir.

17. draw(): Fungsi ini menggabungkan beberapa fungsi penggambaran untuk menggambar elemen-elemen permainan di kanvas.

18. getRandomShape(): Fungsi ini digunakan untuk mendapatkan bentuk tetromino acak dari daftar bentuk yang telah ditentukan.

19. resetVars(): Fungsi ini digunakan untuk mengatur ulang variabel-variabel yang terlibat dalam permainan Tetris untuk memulai permainan baru.

20. gameLoop(): Fungsi ini mengatur interval untuk memperbarui dan menggambar permainan secara berkala.
