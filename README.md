Tugas Analisis 1: Nilai hp dari hero1 akan berubah menjadi 500, sehingga ketika diprint dengan print(hero1.hp), outputnya adalah 500.

Tugas Analisis 2: Parameter lawan menerima objek utuh agar kita bisa mengakses semua atribut dan method dari objek tersebut, seperti hp atau method lain. Jika hanya berupa string, kita tidak bisa melakukan interaksi langsung dengan data lawan.

Tugas Analisis 3: Error yang muncul adalah Mage object has no attribute 'name' karena constructor dari class Hero tidak dijalankan. Fungsi super() berperan untuk memanggil constructor class induk agar atribut seperti name dan hp bisa diwariskan ke class anak.

Tugas Analisis 4:

Nilai HP tetap muncul saat mengakses hero1._Hero__hp karena Python menggunakan konsep Name Mangling. Namun, cara ini tidak dianjurkan karena melanggar prinsip enkapsulasi dan bisa menyebabkan inkonsistensi data. Jika validasi dihapus dan dijalankan hero1.set_hp(-100), maka HP akan menjadi -100. Ini menunjukkan bahwa method setter penting untuk menjaga data tetap valid agar tidak merusak logika game.

Tugas Analisis 5:

Error yang muncul adalah Can't instantiate abstract class Hero with abstract method serang. Artinya class Hero belum lengkap karena belum mengimplementasikan method yang wajib. Jika kita lupa membuat method tersebut, program akan error. Class GameUnit tidak bisa dibuat objek karena merupakan abstract class. Fungsinya sebagai kerangka atau template bagi class lain agar memiliki struktur yang sama.

Tugas Analisis 6:

Program tetap berjalan lancar saat menambahkan class Healer tanpa mengubah kode looping. Ini menunjukkan bahwa polimorfisme memudahkan penambahan fitur atau karakter baru tanpa mengubah kode lama. Jika nama method serang diubah menjadi tembak_panah, program akan error karena dalam polimorfisme nama method harus sama agar bisa dipanggil secara konsisten.
