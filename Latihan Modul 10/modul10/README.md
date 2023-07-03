
# Modul 3

# Implementasi Kelas "Entry Buku Alamat" dan "Buku Alamat"

## Deskripsi

Kelas "Entry Buku Alamat" dan "Buku Alamat" adalah dua kelas terkait yang digunakan untuk mengimplementasikan sistem buku alamat sederhana dalam Java.

### Kelas "Entry Buku Alamat"

Kelas "Entry Buku Alamat" merepresentasikan entri tunggal dalam buku alamat. Setiap entri biasanya berisi informasi tentang seseorang, seperti nama, alamat, nomor telepon, dan alamat email.

Kelas ini memiliki atribut-atribut berikut:

- `nama` (String): Menyimpan nama dari entri buku alamat.
- `alamat` (String): Menyimpan alamat dari entri buku alamat.
- `nomorTelepon` (String): Menyimpan nomor telepon dari entri buku alamat.
- `email` (String): Menyimpan alamat email dari entri buku alamat.

Kelas "Entry Buku Alamat" menyediakan metode-metode berikut:

- Konstruktor: Menginisialisasi objek "Entry Buku Alamat" dengan nilai-nilai awal.
- Getter dan Setter: Metode untuk mengakses dan memperbarui nilai-nilai atribut.
- `toString()`: Metode untuk mengembalikan representasi string dari objek "Entry Buku Alamat".

### Kelas "Buku Alamat"

Kelas "Buku Alamat" merupakan kelas utama yang digunakan untuk mengelola entri-entri dalam buku alamat. Kelas ini bertanggung jawab untuk menambahkan entri baru, menghapus entri, dan mencetak semua entri dalam buku alamat.

Kelas ini memiliki atribut-atribut berikut:

- `daftarEntri` (ArrayList<EntryBukuAlamat>): Menyimpan daftar entri buku alamat.

Kelas "Buku Alamat" menyediakan metode-metode berikut:

- `tambahEntri()`: Metode untuk menambahkan entri baru ke dalam buku alamat.
- `hapusEntri()`: Metode untuk menghapus entri dari buku alamat berdasarkan nama.
- `cetakBukuAlamat()`: Metode untuk mencetak semua entri dalam buku alamat.

## Contoh Implementasi

Berikut adalah contoh implementasi kelas "Entry Buku Alamat" dan "Buku Alamat":

```java
import java.util.ArrayList;

public class EntryBukuAlamat {
    private String nama;
    private String alamat;
    private String nomorTelepon;
    private String alamatEmail;

    // Constructor
    public EntryBukuAlamat(String nama, String alamat, String nomorTelepon, String alamatEmail) {
        this.nama = nama;
        this.alamat = alamat;
        this.nomorTelepon = nomorTelepon;
        this.alamatEmail = alamatEmail;
    }

    // Accessor method
    public String getNama() {
        return nama;
    }

    public String getAlamat() {
        return alamat;
    }

    public String getNomorTelepon() {
        return nomorTelepon;
    }

    public String getAlamatEmail() {
        return alamatEmail;
    }

    // Mutator method
    public void setNama(String nama) {
        this.nama = nama;
    }

    public void setAlamat(String alamat) {
        this.alamat = alamat;
    }

    public void setNomorTelepon(String nomorTelepon) {
        this.nomorTelepon = nomorTelepon;
    }

    public void setAlamatEmail(String alamatEmail) {
        this.alamatEmail = alamatEmail;
    }
}

public class BukuAlamat {
    private String nama;
    private String alamat;
    private String notelp;
    private String email;
    
    public BukuAlamat(){
        
    }
    
    public BukuAlamat(String nama, String alamat, String notelp, String email){
        this.nama = nama;
        this.alamat= alamat;
        this.notelp = notelp;
        this.email = email;
    }
    
    public String getNama(){
        return nama;
    }
    
    public void setNama(String nama){
        this.nama = nama;
    }
    
    public String getAlamat(){
        return alamat;
    }
    
    public void setAlamat(String alamat){
        this.alamat = alamat;
    }
    
    public String getNotelp(){
        return notelp;
    }
    
    public void setNotelp(String notelp){
        this.notelp = notelp;
    }
    
    public String getEmail(){
        return email;
    }
    
    public void setEmail(String email){
        this.email = email;
    }
    
}
```

Dalam contoh di atas, kita memiliki kelas "Entry Buku Alamat" yang merepresentasikan entri dalam buku alamat dan kelas "Buku Alamat" yang mengelola entri-entri tersebut. Kelas "Buku Alamat" menggunakan `ArrayList` untuk menyimpan entri-entri dalam buku alamat.

Kelas "Entry Buku Alamat" memiliki atribut-atribut yang mewakili informasi dalam entri buku alamat dan menyediakan metode-metode untuk mengakses dan memperbarui atribut-atribut tersebut.

Kelas "Buku Alamat" memiliki metode-metode untuk menambahkan entri baru, menghapus entri, dan mencetak semua entri dalam buku alamat.


## Authors

- [@EterNzcW](https://github.com/EterNzcW)

