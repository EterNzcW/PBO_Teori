
# Modul 3


# Apa Itu `public` dan `class` di Java?

## Deskripsi

Dalam bahasa pemrograman Java, `public` dan `class` adalah dua kata kunci yang digunakan untuk mendefinisikan visibilitas dan struktur dasar dari kode program.

### `public`

`public` adalah kata kunci yang digunakan untuk mengatur visibilitas suatu elemen program. Ketika suatu kelas, metode, atau variabel dideklarasikan dengan kata kunci `public`, elemen tersebut dapat diakses dari mana saja, baik dari dalam kelas yang sama, kelas yang berbeda di dalam paket yang sama, maupun dari paket yang berbeda.

Contoh penggunaan `public` dalam deklarasi kelas:

```java
public class MyClass {
    // kode program
}
```

Dalam contoh di atas, kelas `MyClass` dideklarasikan dengan kata kunci `public`, yang berarti kelas tersebut dapat diakses oleh kelas lain di dalam paket yang sama maupun di luar paket tersebut.

### `class`

`class` adalah kata kunci yang digunakan untuk mendefinisikan suatu kelas dalam Java. Kelas adalah entitas dasar dalam pemrograman berorientasi objek yang digunakan untuk mengelompokkan kode program menjadi satu unit yang terdiri dari variabel (data) dan metode (fungsi) terkait.

Contoh penggunaan `class`:

```java
public class MyClass {
    // kode program
}
```

Dalam contoh di atas, kita mendefinisikan kelas `MyClass` yang berisi kode program yang ingin kita buat.

## Contoh Penggunaan

Berikut ini adalah contoh penggunaan `public` dan `class` dalam kode program Java:

```java
public class Main {
    public static void main(String[] args) {
        // membuat objek dari kelas MyClass
        MyClass myObj = new MyClass();

        // memanggil metode pada objek
        myObj.myMethod();
    }
}

public class MyClass {
    public void myMethod() {
        System.out.println("Hello, world!");
    }
}
```

Dalam contoh di atas, kita mendefinisikan kelas `Main` yang memiliki metode `main()` sebagai titik awal eksekusi program. Di dalam metode `main()`, kita membuat objek dari kelas `MyClass` dan memanggil metode `myMethod()` pada objek tersebut. Metode `myMethod()` akan mencetak pesan "Hello, world!" ke konsol.


## Authors

- [@EterNzcW](https://github.com/EterNzcW)

