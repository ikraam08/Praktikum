# Tugas Pertemuan 5
## Pemrograman Orientasi Objek

````
Nama   : Ikram Ramadhan
Nim    : 312110478
Matkul : Pemrograman Orientasi Objek

### 1.file Main.java
* *CODINGAN
package tugas;

public class Main {
    private String nama;
    private String jenisKelamin;
    private int umur;

    public Main() {
    }

    public void setNama(String warna) {
        this.nama = warna;
    }

    public void setJenisKelamin(String jenisKelamin) {
        this.jenisKelamin = "laki-laki";
    }

    public void setUmur(int umur) {
        this.umur = 21;
    }

    public String getNama() {
        return this.nama;
    }

    public String getJenisKelamin() {
        return this.jenisKelamin;
    }

    public int getUmur() {
        return this.umur;
    }

    public static void main(String[] args) {
        Main person = new Main();
        person.setNama("jaki");
        person.setJenisKelamin("Laki-Laki");
        person.setUmur(24);
        System.out.println("Nama : " + person.getNama());
        System.out.println("jenis kelamin : " + person.getJenisKelamin());
        System.out.println("Umur : " + person.getUmur());
    }
}


````````
* *Hasil output program:*
![Gambar](screenshoot/ss1.jpg
)