
# Modul 8

# Operasi Aritmatik dan Mencetak Argumen dalam Java

## Deskripsi

Operasi Aritmatik adalah operasi matematika yang digunakan untuk melakukan perhitungan pada angka. Dalam Java, terdapat beberapa operator aritmatik yang dapat digunakan, antara lain:

- Penjumlahan (`+`) : Menambahkan dua nilai.
- Pengurangan (`-`) : Mengurangkan satu nilai dari nilai yang lain.
- Perkalian (`*`) : Mengalikan dua nilai.
- Pembagian (`/`) : Membagi satu nilai dengan nilai yang lain.
- Modulo (`%`) : Menghasilkan sisa dari pembagian dua nilai.

Mencetak argumen atau output adalah cara untuk menampilkan hasil atau nilai dari program ke konsol atau output lainnya. Dalam Java, kita dapat menggunakan perintah `System.out.println()` atau `System.out.print()` untuk mencetak argumen ke output.

## Contoh Penggunaan Operasi Aritmatik dan Mencetak Argumen

Berikut adalah contoh penggunaan operasi aritmatik dan mencetak argumen dalam Java:

```java
public class Main {
    public static void main(String[] args) {
        int angka1 = 10;
        int angka2 = 5;

        // Operasi Aritmatik
        int penjumlahan = angka1 + angka2;
        int pengurangan = angka1 - angka2;
        int perkalian = angka1 * angka2;
        int pembagian = angka1 / angka2;
        int modulo = angka1 % angka2;

        // Mencetak Argumen
        System.out.println("Hasil Penjumlahan: " + penjumlahan);
        System.out.println("Hasil Pengurangan: " + pengurangan);
        System.out.println("Hasil Perkalian: " + perkalian);
        System.out.println("Hasil Pembagian: " + pembagian);
        System.out.println("Hasil Modulo: " + modulo);
    }
}
```

Dalam contoh di atas, kita memiliki dua variabel `angka1` dan `angka2` yang berisi angka-angka integer. Kemudian, kita melakukan operasi aritmatik seperti penjumlahan, pengurangan, perkalian, pembagian, dan modulo menggunakan operator aritmatik yang sesuai. Hasil operasi tersebut kemudian dicetak menggunakan `System.out.println()`.

Hasil dari program di atas akan dicetak ke output sebagai berikut:

```
Hasil Penjumlahan: 15
Hasil Pengurangan: 5
Hasil Perkalian: 50
Hasil Pembagian: 2
Hasil Modulo: 0
```

Pastikan untuk memeriksa tipe data yang sesuai dengan operasi aritmatik yang dilakukan, terutama dalam pembagian, untuk menghindari hasil yang tidak diinginkan seperti pembagian dengan nol.

## Authors

- [@EterNzcW](https://github.com/EterNzcW)

