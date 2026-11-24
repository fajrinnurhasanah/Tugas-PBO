# TUGAS NO 1 (PROJECT PERKENALAN)


    # Class PasienTHT
    class PasienTHT:

    # Class Attribute
    rumah_sakit = "RS Sari asih"
    poli = "Poli THT"

    # Constructor
    def __init__(self, nama, umur, keluhan):
        self.nama = nama
        self.umur = umur
        self.keluhan = keluhan

    # Method perkenalan
    def perkenalan(self):
        print(f"Halo, nama saya {self.nama}.")
        print(f"Umur saya {self.umur} tahun.")
        print(f"Keluhan saya adalah {self.keluhan}.")

    # Method percakapan
    def berbicara(self, lawan_bicara, kalimat):
        print(f"{self.nama}: {kalimat}")
        
    # Membuat Object
    fajrin = PasienTHT(
    "Fajrin", 20, "Telinga terasa sakit dan berdengung"
    )

    angel = PasienTHT(
    "Angel", 21, "Hidung tersumbat dan tenggorokan sakit"
    )


    # Memulai Percakapan
    print("====================================")
    print(" PERCAKAPAN PASIEN DI POLI THT")
    print("====================================")
    print("Rumah Sakit:", PasienTHT.rumah_sakit)
    print("Ruangan:", PasienTHT.poli)
    print()
    
    print("--- PERKENALAN ---")
    fajrin.perkenalan()
    print()
    angel.perkenalan()
    
    print()
    print("--- PERCAKAPAN ---")

    fajrin.berbicara("Angel",
        "Halo, apakah kamu juga sedang menunggu pemeriksaan THT?")
    
    angel.berbicara("Fajrin",
        "Iya, saya sedang menunggu giliran pemeriksaan.")
    
    fajrin.berbicara("Angel",
        "Kalau boleh tahu, apa keluhan yang kamu rasakan?")
    
    angel.berbicara("Fajrin",
        "Hidung saya tersumbat dan tenggorokan terasa sakit. "
        "Kalau kamu sendiri bagaimana?")
    
    fajrin.berbicara("Angel",
        "Telinga saya terasa sakit dan terkadang berdengung.")
    
    angel.berbicara("Fajrin",
        "Sepertinya kita perlu memeriksakan keluhan ini "
        "agar tahu penyebabnya.")

    fajrin.berbicara("Angel",
        "Benar, saya juga ingin tahu apa penyebab tenggorokan "
        "saya terasa sakit.")
    
    angel.berbicara("Fajrin",
        "Apakah kamu sudah mendaftar di bagian pendaftaran?")
    
    fajrin.berbicara("Angel",
        "Sudah, saya tinggal menunggu nama saya dipanggil.")
    
    angel.berbicara("Fajrin",
        "Bagus, semoga pemeriksaannya berjalan lancar.")
    
    print()
    print("--- PROSES PEMERIKSAAN ---")
    
    angel.berbicara("Fajrin",
    "Sepertinya nama saya sudah dipanggil. "
    "Saya masuk dulu untuk diperiksa.")
    
    fajrin.berbicara("Angel",
        "Silakan, semoga hasil pemeriksaannya baik.")
    
    angel.berbicara("Fajrin",
        "Terima kasih. Dokter sudah memeriksa hidung "
        "dan tenggorokan saya.")
    
    fajrin.berbicara("Angel",
        "Bagaimana hasil pemeriksaannya?")
    
    angel.berbicara("Fajrin",
        "Dokter sudah menjelaskan kondisi saya dan memberikan "
        "saran pengobatan serta anjuran untuk kontrol.")
    
    fajrin.berbicara("Angel",
        "Syukurlah. Sekarang giliran saya untuk diperiksa.")
    
    print()
    print("--- PENUTUP ---")
    
    angel.berbicara("Fajrin",
        "Semoga pemeriksaanmu juga berjalan lancar.")
    
    fajrin.berbicara("Angel",
        "Terima kasih. Saya juga berharap bisa segera sembuh.")
    
    angel.berbicara("Fajrin",
        "Jangan lupa mengikuti anjuran dokter dan menjaga kesehatan.")
    
    fajrin.berbicara("Angel",
        "Tentu. Senang bisa berkenalan denganmu. Sampai jumpa!")
    
    angel.berbicara("Fajrin",
        "Sampai jumpa, semoga kita selalu sehat.")
    
    print()
    print("====================================")
    print("PERCAKAPAN SELESAI")
    print("Kedua pasien selesai menjalani proses pemeriksaan.")
    print("====================================")

OUTPUT:
====================================
 PERCAKAPAN PASIEN DI POLI THT
====================================
    Rumah Sakit: RS Sari asih
    Ruangan: Poli THT
    
    --- PERKENALAN ---
    Halo, nama saya Fajrin.
    Umur saya 20 tahun.
    Keluhan saya adalah Telinga terasa sakit dan berdengung.
    
    Halo, nama saya Angel.
    Umur saya 21 tahun.
    Keluhan saya adalah Hidung tersumbat dan tenggorokan sakit.
    
    --- PERCAKAPAN ---
    Fajrin: Halo, apakah kamu juga sedang menunggu pemeriksaan THT?
    Angel: Iya, saya sedang menunggu giliran pemeriksaan.
    Fajrin: Kalau boleh tahu, apa keluhan yang kamu rasakan?
    Angel: Hidung saya tersumbat dan tenggorokan terasa sakit. Kalau kamu sendiri bagaimana?
    Fajrin: Telinga saya terasa sakit dan terkadang berdengung.
    Angel: Sepertinya kita perlu memeriksakan keluhan ini agar tahu penyebabnya.
    Fajrin: Benar, saya juga ingin tahu apa penyebab tenggorokan saya terasa sakit.
    Angel: Apakah kamu sudah mendaftar di bagian pendaftaran?
    Fajrin: Sudah, saya tinggal menunggu nama saya dipanggil.
    Angel: Bagus, semoga pemeriksaannya berjalan lancar.
    
    --- PROSES PEMERIKSAAN ---
    Angel: Sepertinya nama saya sudah dipanggil. Saya masuk dulu untuk diperiksa.
    Fajrin: Silakan, semoga hasil pemeriksaannya baik.
    Angel: Terima kasih. Dokter sudah memeriksa hidung dan tenggorokan saya.
    Fajrin: Bagaimana hasil pemeriksaannya?
    Angel: Dokter sudah menjelaskan kondisi saya dan memberikan saran pengobatan serta anjuran untuk kontrol.
    Fajrin: Syukurlah. Sekarang giliran saya untuk diperiksa.
    
    --- PENUTUP ---
    Angel: Semoga pemeriksaanmu juga berjalan lancar.
    Fajrin: Terima kasih. Saya juga berharap bisa segera sembuh.
    Angel: Jangan lupa mengikuti anjuran dokter dan menjaga kesehatan.
    Fajrin: Tentu. Senang bisa berkenalan denganmu. Sampai jumpa!
    Angel: Sampai jumpa, semoga kita selalu sehat.
    
    ====================================
    PERCAKAPAN SELESAI
    Kedua pasien selesai menjalani proses pemeriksaan.
    ====================================
    Proses perkenalan selesai.



