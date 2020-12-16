# pwd-9
[![GitHub](https://img.shields.io/github/license/himawanTIF/pwd-9?style=flat-square)](https://github.com/himawanTIF/pwd-9/blob/main/LICENSE)
[![Maintenance](https://img.shields.io/maintenance/yes/2020?style=flat-square)](https://github.com/himawanTIF/pwd-9/graphs/commit-activity)

# Praktikum Pemrograman Web Dinamis Pertemuan 9
[Link Video Materi](https://youtu.be/ybPPP9uREco)

## Materi
__JSON__ & __XML__
> __XML__ (*Extensible Markup Language*) adalah format teks sederhana, sangat fleksibel yang berasal dari **SGML (ISO 8879)**. Awalnya dirancang untuk memenuhi tantangan penerbitan elektronik skala besar, XML juga memainkan peran yang semakin penting dalam pertukaran berbagai data di Web dan di tempat lain.

> __JSON__ (*Javascript Object Notation*) merupakan salah satu format yang digunakan untuk memfasilitasi pertukaran data antar bahasa pemrograman. Ketentuan dalam pertukaran ini adalah:
> 1. **Teks**. Format standar untu pertukaran data adalah teks, mengapa teks? karena teks, semua bahasa pemrograman dapat menerimanya.
> 2. **Antar bahasa pemrograman** (misal **PHP** ke **Javascript**). Setiap bentuk format pertukaran data, pasti ditunjukkan untuk berbagai bahasa pemrograman, meskipun juga dapat untuk satu bahasa pemrograman.

> **Struktur JSON**
>
> 1. Bentuk pasangan __*key:value*__ yang pada Javascript disebut objek, atau pada PHP disebut __*associative array*__. Contoh:
```json
{ 
   "nama":"Budi Santosa",
   "alamat":"Yogyakarta"
}
```
> Selanjutnya, dalam JSON bentuk di atas disebut **objek** (*Object*).
>
> 2. Bentuk sederetan *value* saja (meskipun *value* tersebut juga dapat berbentuk objek), yang dalam Javascript dan PHP disebut __*array*__. Contoh:
```array
 ["Budi Santosa","Yogyakarta"]
```
> Selanjutnya, dalam JSON bentuk di atas disebut __*array*__.

> **Tipe data JSON**
>
> Maksud tipe data di sini adalah jenis data yang dapat digunakan di dalam JSON, adapun tipe data yang dapat digunakan adalah sebagai berikut:
>
> 1. **Objek**. Objek merupakan kumpulan pasangan *key* dan *value* yang diapit dengan kurung buka dan kurung tutup. Karena objek ini mencerminkan *associative array*, maka direkomendasikan agar tidak menggunakan *key* dengan nilai sama (*key* sebaiknya unik). Objek ini bileh bernilai kosong dan cukup ditulis { }
> 2. **Array**. Sederetan *value* yang diapit oleh kurung siku. Antara *value* yang satu dengan yang lain dipisahkan tanda koma. *Array* boleh bernilai kosong dan cukup ditulis [ ]
> 3. **Number**. *Number* berupa digit 0-9 dan ditulis apa adanya tanpa perlu menggunakan tanda kutip. *Number* dapat berupa bilangan bulat maupaun desimal. Untuk desimal, karakter yang digunakan adalah titik bukan koma. Misal untuk menuliskan dua koma lima, bentuk angkanya adalah 2.5 bukan 2,5
> 4. **Boolean**. Boolean berupa teks __*true*__ dan __*false*__ tanpa tanda kutip.
> 5. **Null**. Null berupa teks null dan ditulis langsung tanpa tanda kutip.
> 6. **String**. String berupa semua karakter *Unicode* yang artinya semua karakter yang ada di dunia ini. String merupakan tipe data yang **paling sering digunakan**, dalam penulisannya, string **harus** diapit dengan dua tanda kutip ("), tidak boleh menggunakan satu tanda kutip (') atau tidak menggunakan tanda kutip sama sekali.