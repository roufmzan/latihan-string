# Latihan-String-

**Program akan meminta kita untuk memasukkan jumlah karakter, karakter terakhir, karakter index ke-2 sampai index ke-4, teks tanpa spasi, teks dalam huruf besar, teks dalam huruf kecil :**

![Output 1](https://github.com/user-attachments/assets/4e717ff0-5f66-40c1-b642-bf0f6ade3bb2)

**Penjelasan Code**

```
txt = 'Hello World'

# Hitung jumlah karakternya
jumlah_karakter = len(txt)
print("Jumlah karakter:", jumlah_karakter)

# Ambil karakter terakhir
karakter_terakhir = txt[-1]
print("Karakter terakhir:", karakter_terakhir)

# Ambil karakter index ke-2 sampai index ke-4 (llo)
substring = txt[2:5]
print("Karakter index ke-2 sampai index ke-4:", substring)

# Hilangkan spasi pada teks tersebut (HelloWorld)
tanpa_spasi = txt.replace(" ", "")
print("Teks tanpa spasi:", tanpa_spasi)

# Ubah teks menjadi huruf besar
huruf_besar = txt.upper()
print("Teks dalam huruf besar:", huruf_besar)

# Ubah teks menjadi huruf kecil
huruf_kecil = txt.lower()
print("Teks dalam huruf kecil:", huruf_kecil)

# Ganti karakter H dengan karakter J
ganti_h = txt.replace("H", "J")
print("Teks setelah mengganti H dengan J:", ganti_h)
```

**Penjelasan Latihan 1**
inisialisasi variabel txt: Mendefinisikan variabel txt yang berisi string 'Hello World'
Menghitung jumlah karakter: Fungsi len(txt) menghitung panjang string txt, termasuk spasi.
Output: Jumlah karakter: 11
Mengambil karakter terakhir: Menggunakan indeks negatif -1, yang mereferensikan karakter terakhir pada string.
Output: Karakter terakhir: d
Menghilangkan spasi pada teks: Fungsi replace(" ", "") mengganti semua spasi (" ") dengan string kosong (""), menghasilkan string tanpa spasi.
Output: Teks tanpa spasi: HelloWorld
Mengubah teks menjadi huruf besar: Fungsi upper() mengubah semua karakter dalam string menjadi huruf besar.
Output: Teks dalam huruf besar: HELLO WORLD
Mengubah teks menjadi huruf kecil: Fungsi lower() mengubah semua karakter dalam string menjadi huruf kecil.
Output: Teks dalam huruf kecil: hello world
Mengganti karakter 'H' dengan 'J': Fungsi replace("H", "J") mengganti semua kemunculan karakter 'H' dalam string dengan 'J'.
Output: Teks setelah mengganti H dengan J: Jello

**Program akan meminta kita untuk memasukkan Hello, nama saya john, dan umur saya adalah 24 tahun:**

![Output 2](https://github.com/user-attachments/assets/4eba82b6-77e2-457f-a991-90af7bcc71b9)

**Penjelasan Code**

```
umur = 24
txt = 'Hello, nama saya john, dan umur saya adalah {} tahun'

print(txt.format(umur))
```

**Penjelasan Latihan 2**
Deklarasi Variabel umur:
Variabel umur diberikan nilai 24, yang merupakan bilangan integer.
Variabel ini menyimpan informasi umur yang nantinya akan dimasukkan ke dalam teks.
Deklarasi Variabel txt:
Variabel txt adalah sebuah string dengan teks 'Hello, nama saya john, dan umur saya adalah {} tahun'.
Tanda kurung kurawal {} di dalam string adalah placeholder, yaitu tempat di mana nilai dari variabel (seperti umur) akan dimasukkan.
Pemanggilan Metode .format():
Fungsi print() digunakan untuk mencetak teks ke layar.
Metode .format(umur) menggantikan placeholder {} pada string txt dengan nilai variabel umur.
Dalam hal ini, {} akan digantikan oleh nilai 24.
Hasil Eksekusi:
Setelah .format(umur) dijalankan, string berubah menjadi:
Hello, nama saya john, dan umur saya adalah 24 tahun
Fungsi print() akan mencetak teks ini ke layar.
Metode .format() sangat berguna untuk menggabungkan string dan variabel tanpa perlu menggabungkan dengan operator +.
