
# Modul 5
# Deskripsi
InputStreamReader dan BufferedReader adalah dua kelas yang umum digunakan dalam pemrograman Java untuk membaca input dari aliran masukan (input stream) dengan cara yang efisien.

# InputStreamReader
Kelas InputStreamReader adalah kelas yang membaca byte dari aliran masukan dan menerjemahkannya menjadi karakter menggunakan set encoding tertentu. Ini berguna ketika kita ingin membaca input yang berupa byte (seperti dari file atau soket) dan mengubahnya menjadi karakter yang dapat dibaca oleh program.

Beberapa metode penting dalam kelas InputStreamReader antara lain:

InputStreamReader(InputStream inputStream, Charset charset) : Membuat objek InputStreamReader yang membaca byte dari inputStream dan menerjemahkannya menggunakan charset yang ditentukan.
int read() : Membaca satu karakter dari aliran masukan dan mengembalikan nilainya sebagai integer. Jika telah mencapai akhir aliran masukan, maka akan mengembalikan -1.
void close() : Menutup InputStreamReader dan melepaskan sumber daya yang terkait.
# BufferedReader
BufferedReader adalah kelas yang membaca teks dari input stream dengan melakukan buffering data. Dengan melakukan buffering, BufferedReader mengurangi jumlah panggilan ke sistem operasi untuk membaca data, yang dapat meningkatkan efisiensi operasi pembacaan.

Beberapa metode penting dalam kelas BufferedReader antara lain:

BufferedReader(Reader reader) : Membuat objek BufferedReader yang membaca input dari reader yang diberikan.
String readLine() : Membaca satu baris teks dari input stream dan mengembalikan baris tersebut sebagai objek String. Jika telah mencapai akhir aliran masukan, maka akan mengembalikan nilai null.
void close() : Menutup BufferedReader dan melepaskan sumber daya yang terkait.
Penggunaan
Dalam penggunaan umum, InputStreamReader dan BufferedReader dapat digunakan bersama-sama untuk membaca teks dari aliran masukan dengan lebih efisien. Berikut adalah contoh penggunaan kombinasi keduanya:



## Authors

- [@EterNzcW](https://github.com/EterNzcW)

