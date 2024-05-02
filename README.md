# LP11DPBO2024C1
## JANJI 
```bash
Saya Nur Ainun 2202046 mengerjakan LATIHAN PRAKTIKUM 11 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek 
untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin. 

```
# Model View Presenter (MVP) 

## Deskripsi
MVP adalah pola desain yang digunakan dalam pengembangan perangkat lunak untuk memisahkan tanggung jawab dari tiga komponen utama: Model, View, dan Presenter. Dalam pola ini, Model bertanggung jawab untuk mengelola data dan logika bisnis, View bertanggung jawab untuk menampilkan antarmuka pengguna (UI), sedangkan Presenter bertindak sebagai perantara antara Model dan View.

## Struktur Program
- **Model**: Dalam program ini, Model direpresentasikan oleh kelas `ProsesPasien`, yang mengelola data pasien dan operasi CRUD terkait.
- **View**: View direpresentasikan oleh kelas `TampilPasien` dan mencakup tampilan HTML yang menampilkan data pasien dan formulir untuk menambahkan atau mengedit data.
- **Presenter**: Presenter direpresentasikan oleh kelas `TampilPasien`, yang bertanggung jawab atas logika bisnis terkait tampilan dan berinteraksi dengan Model dan View.

## Alur Kerja Program
1. Pengguna berinteraksi dengan tampilan HTML (View).
2. View mengirimkan input pengguna ke Presenter.
3. Presenter mengambil data yang diperlukan dari Model (`ProsesPasien`).
4. Presenter memproses data dan menyiapkannya untuk ditampilkan kepada pengguna.
5. Presenter mengirimkan data yang telah diproses kembali ke View.
6. View menampilkan data kepada pengguna atau mengirimkan formulir ke Presenter untuk pemrosesan lebih lanjut.

## Demo Program

https://github.com/Nurainunlubis/LP11DPBO2024C1/assets/113582460/98376929-c3cd-495b-ab5d-7962689e0a55


