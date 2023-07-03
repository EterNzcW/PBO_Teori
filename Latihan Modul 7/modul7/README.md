
# Modul 7

# Array dalam Java

## Deskripsi

Array adalah struktur data yang digunakan untuk menyimpan sekumpulan nilai dengan tipe data yang sama dalam satu variabel. Dalam Java, array adalah objek yang memiliki panjang tetap dan dapat menyimpan elemen-elemen dengan tipe data primitif atau objek.

Array dalam Java memiliki beberapa karakteristik penting:

- Array memiliki panjang yang tetap saat dideklarasikan dan tidak dapat diubah setelahnya.
- Elemen-elemen array ditempatkan secara berurutan dalam memori.
- Indeks array dimulai dari 0, yang berarti elemen pertama memiliki indeks 0, elemen kedua memiliki indeks 1, dan seterusnya.
- Array dapat diinisialisasi dengan nilai awal saat deklarasi, atau elemen-elemen array dapat diisi setelah deklarasi menggunakan indeks.

## Cara Pengambilan Value dari Array

Untuk mengambil nilai dari array, kita menggunakan indeks array yang merujuk ke posisi elemen yang ingin diambil. Dalam Java, kita menggunakan tanda kurung siku `[]` dengan indeks di dalamnya untuk mengakses elemen-elemen array.

Berikut adalah contoh pengambilan nilai dari array dalam Java:

```java
public class Main {
    public static void main(String[] args) {
        // Deklarasi dan inisialisasi array
        int[] angka = {5, 10, 15, 20, 25};

        // Mengambil nilai dari array menggunakan indeks
        int nilaiPertama = angka[0];
        int nilaiKedua = angka[1];
        int nilaiTerakhir = angka[angka.length - 1];

        System.out.println("Nilai pertama: " + nilaiPertama);
        System.out.println("Nilai kedua: " + nilaiKedua);
        System.out.println("Nilai terakhir: " + nilaiTerakhir);
    }
}
```

Dalam contoh di atas, kita memiliki array `angka` yang berisi nilai-nilai integer. Untuk mengambil nilai dari array, kita menggunakan indeks array dalam tanda kurung siku `[]`. Misalnya, `angka[0]` mengambil nilai pertama dari array `angka`, yaitu 5.

Kita juga dapat menggunakan variabel atau ekspresi sebagai indeks array. Dalam contoh di atas, kita menggunakan `angka.length - 1` untuk mengambil nilai terakhir dari array `angka`. Properti `length` mengembalikan panjang (jumlah elemen) dari array.

Pastikan untuk memeriksa batasan indeks saat mengambil nilai dari array untuk menghindari _ArrayIndexOutOfBoundsException_.



## Authors

- [@EterNzcW](https://github.com/EterNzcW)

