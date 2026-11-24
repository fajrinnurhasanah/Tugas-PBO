# PEMOGRAMAN BERORIENTASI OBJECT (PBO)


# Pertemuan 1 (satu) CLASS_AND_OBJECT.PY
class adalah cetakan atau rancangan untuk membuat objek, berisi atribut (data) dan method (fungsi).
Object adalah hasil dari class yang memiliki data dan fungsi sesuai rancangan class.
contoh:

class Mahasiswa:
    nim = 0
    nama = ""

    def perkenalan(self):
        print(f" nama kamu siapa?")

    def hello(self, nama):
        print(f"Halo {self.nama}, nama saya {nama}")

mahasiswa = Mahasiswa()
mahasiswa.nama = "fajrin"
mahasiswa.perkenalan()
mahasiswa.hello("angel")

Output:
Halo, nama saya Fajrin Nh
NIM saya 1402250079
Status: Mahasiswa
Jurusan: Sistem Informasi
Saya adalah mahasiswa jurusan Sistem Informasi
 nama kamu siapa?
Halo fajrin, nama saya angel

# Pertemuan 2 (Dua) CONSTRUCTOR.PY






