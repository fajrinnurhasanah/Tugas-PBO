    class Mahasiswa:
        nim = 0
        nama = ""
    
        def __init__(self, nama, nim): 
            self.nama = nama
            self.nim = nim
    
    
    mhs = Mahasiswa("Fajrin", "14022500079")
    print(mhs.nama)
    print(mhs.nim)
