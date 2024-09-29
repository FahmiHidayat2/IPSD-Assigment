# <h1 align="center">Laporan Praktikum Modul Dasar-Dasar Python untuk Sains Data</h1>
<p align="center">Fahmi Hidayat</p>

## Dasar Teori
### Variabel dan Tipe Data
#### Variabel
  Variabel dalam pemrograman digunakan untuk menyimpan data sementara di memori yang akan digunakan oleh program. Setiap variabel memiliki nama dan nilai. Nama variabel harus mendeskripsikan tujuan variabel tersebut, sehingga mudah dipahami saat membaca kode. Variabel sangat berguna karena memungkinkan kita untuk menyimpan nilai yang dapat diubah-ubah, baik berupa angka, teks, atau tipe data lainnya. Variabel juga memudahkan program untuk menjadi lebih dinamis, di mana nilai dalam variabel dapat diubah selama program berjalan.

  Variabel bersifat case-sensitive, artinya nama variabel dengan huruf besar dan kecil berbeda, seperti nama dan Nama akan dianggap variabel yang berbeda. Selain itu, variabel di Python bersifat dynamic typing, artinya kita tidak perlu menyebutkan tipe data secara eksplisit saat mendeklarasikan variabel; Python akan menentukannya secara otomatis berdasarkan nilai yang diberikan.
#### Tipe Data
  Tipe data adalah klasifikasi data yang memberitahu compiler atau interpreter bagaimana programmer berniat untuk menggunakan data. Kebanyakan bahasa pemrograman mendukung berbagai jenis data, misalnya: nyata , bulat atau Boolean.
Python memiliki beberapa tipe data dasar seperti:

1.Integer (int): Tipe data ini digunakan untuk menyimpan bilangan bulat, baik positif maupun negatif. Biasanya digunakan dalam perhitungan yang tidak melibatkan pecahan.
Contoh: age = 25

2.Float: Digunakan untuk menyimpan bilangan desimal atau pecahan. Biasanya digunakan untuk nilai yang lebih presisi seperti hasil perhitungan matematika yang melibatkan desimal.
Contoh: height = 1.75

3.String (str): Merupakan tipe data untuk menyimpan teks atau rangkaian karakter. String bisa berisi huruf, angka, simbol, dan lain-lain.
Contoh: name = "Agung"

4.Boolean (bool): Menyimpan nilai logika yang hanya bisa bernilai True atau False. Boolean biasanya digunakan dalam pengkondisian dan logika program.
Contoh: is_student = True

### Operator dan Logika
  Operator dan Logika adalah bagian penting dari pemrograman yang memungkinkan kita untuk melakukan operasi dan membuat keputusan berdasarkan kondisi tertentu. Operator adalah simbol atau kata kunci yang digunakan untuk melakukan operasi pada nilai atau variabel. Sedangkan logika digunakan untuk menentukan alur pengambilan keputusan dalam program. Ada beberapa jenis operator yang umum digunakan, termasuk operator aritmatika, perbandingan, logika, dan penugasan.

#### Operator Aritmatika 
  Digunakan untuk melakukan operasi matematika seperti penjumlahan, pengurangan, perkalian, dan pembagian. Contoh operator aritmatika meliputi + (penjumlahan), - (pengurangan), * (perkalian), dan / (pembagian). Operator ini berperan penting dalam pemrosesan data numerik di dalam program, misalnya untuk menghitung nilai atau hasil tertentu.

#### Operator Perbandingan 
  Digunakan untuk membandingkan dua nilai dan mengembalikan hasil berupa nilai boolean (True atau False). Operator ini termasuk == (sama dengan), != (tidak sama dengan), > (lebih besar), < (lebih kecil), >= (lebih besar atau sama dengan), dan <= (lebih kecil atau sama dengan). Operator ini penting dalam pengkondisian karena membantu menentukan apakah suatu kondisi terpenuhi atau tidak.

#### Operator Logika
  Digunakan untuk menggabungkan beberapa kondisi logika. Contoh operator logika adalah and (dan), or (atau), dan not (tidak). Operator and mengembalikan True hanya jika kedua kondisi bernilai True, sementara or mengembalikan True jika salah satu kondisi bernilai True. Operator not digunakan untuk membalikkan nilai logika; misalnya, not True akan menghasilkan False.

### Fungsi dan Perulangan
  Fungsi dan Perulangan adalah dua konsep penting dalam pemrograman yang membantu membuat kode lebih terorganisir, efisien, dan mudah dipahami. Kedua konsep ini digunakan untuk mengurangi pengulangan kode dan meningkatkan modularitas serta fleksibilitas dalam pengembangan aplikasi.
#### Fungsi
  Fungsi adalah blok kode yang dirancang untuk melakukan tugas tertentu dan dapat digunakan kembali kapan saja di dalam program. Fungsi membantu mengelompokkan logika yang berhubungan, sehingga kode menjadi lebih terstruktur dan lebih mudah dipelihara. Fungsi juga memungkinkan kita untuk menghindari pengulangan kode dengan menulis satu blok kode yang bisa digunakan berulang kali dengan memanggilnya.

  Fungsi di Python didefinisikan menggunakan kata kunci def diikuti dengan nama fungsi, parameter (opsional), dan blok kode yang akan dieksekusi ketika fungsi dipanggil. Setelah didefinisikan, fungsi dapat dipanggil kapan saja dalam program.
#### Perulangan
1.For Loop
Perulangan FOR merupakan sebuah pernyataan mengulang suatu proses yang telah diketahui jumlah perulangannya.Perulangan for juga digunakan untuk mengiterasi (mengulang) sebuah koleksi, seperti list, tuple, atau string, serta rentang angka. Setiap item dalam koleksi tersebut akan diproses satu per satu.
2.While Loop
Perulangan while terus berjalan selama kondisi yang ditentukan adalah True. Loop ini sangat berguna ketika kita tidak tahu berapa kali perulangan harus dilakukan, tetapi kita tahu kondisi kapan perulangan harus berhenti.
3.List comprehension 
Adalah cara singkat dan efisien dalam Python untuk membuat list baru dari list yang sudah ada. Dengan list comprehension, kita bisa membuat list baru dengan menggunakan perulangan dan kondisi dalam satu baris kode. Ini membuat kode lebih ringkas dan mudah dibaca.
4.If, Elif, Else 
Adalah struktur pengkondisian dalam Python yang digunakan untuk membuat keputusan berdasarkan kondisi tertentu. Dengan menggunakan pengkondisian ini, kita dapat mengarahkan alur program untuk melakukan tindakan berbeda tergantung pada apakah kondisi yang diberikan terpenuhi atau tidak.
5.Nested conditionals 
Adalah struktur pengkondisian di mana sebuah pernyataan if, elif, atau else ditempatkan di dalam pernyataan if, elif, atau else yang lain. Ini memungkinkan kita untuk membuat keputusan yang lebih kompleks dengan memeriksa beberapa kondisi secara berurutan dan bersarang. Dalam nested conditionals, setelah kondisi pertama diperiksa, kondisi lain di dalamnya juga dapat diperiksa tergantung hasil dari kondisi sebelumnya.

## Guided 

### 1. 
```python
nama = "Fahmi Hidayat"
umur = 20
print(f"Nama : {nama} \nUmur : {umur}")
```
Kode ini menyimpan informasi tentang seseorang bernama "Fahmi Hidayat" yang berusia 20 tahun. Variabel nama dan umur menyimpan nilai tersebut, dan perintah print menggunakan f-string untuk menampilkan informasi dengan format yang rapi, termasuk baris baru untuk memisahkan nama dan umur. Saat dijalankan, kode ini menghasilkan output yang menampilkan nama dan usia secara jelas.
#### Output
<img width="134" alt="image" src="https://github.com/user-attachments/assets/cb5b6301-2647-4e92-aa55-7ad93e3a103e">
### 2.

```python
from math import pi

jari = 8
luas = pi *jari**2
keliling = 2*pi*jari
print(f"Luas Lingkaran : {luas} \nKeliling Lingkaran : {keliling}")
```
Kode ini menghitung luas dan keliling lingkaran dengan jari-jari 8. Menggunakan nilai π dari modul `math`, luas dihitung dengan rumus \( \text{luas} = \pi \times \text{jari}^2 \) dan keliling dengan rumus \( \text{keliling} = 2 \times \pi \times \text{jari} \). Hasil perhitungan ditampilkan menggunakan f-string dalam perintah `print`, sehingga menghasilkan output yang jelas mengenai luas dan keliling lingkaran.
#### Output
<img width="227" alt="image" src="https://github.com/user-attachments/assets/30d5c431-ddf4-41d1-ab0b-e8a8a7e50cd2">

### 3.
```python
a = "123"
print(f"Tipe Data a : {type(a)}")
a = int(a)
print(f"Tipe Data a : {type(a)}")
```
Kode ini menunjukkan konversi tipe data dari string ke integer di Python. Variabel `a` awalnya berisi string "123", dan `print` menampilkan tipe datanya sebagai `<class 'str'>`. Setelah mengubah `a` menjadi integer menggunakan `int(a)`, tipe datanya diperbarui menjadi `<class 'int'>`. Kode ini menggambarkan kemampuan Python untuk mengubah tipe data agar dapat melakukan operasi numerik.
#### Output 
<img width="176" alt="image" src="https://github.com/user-attachments/assets/0fc99df9-25ee-4fdb-a085-e38ffbe56471">

## Unguided 

### 1. Buatlah program yang dapat menghasilkan pola berbentuk angka seperti di bawah ini, dengan syarat angka yang ditampilkan adalah hasil dari penjumlahan bilangan prima sebelumnya:
1
2 3
5 7 11
13 17 19 23
Jumlah angka pada setiap baris bertambah 1, dan bilangan yang ditampilkan adalah bilangan prima.

```python
def is_prime(n):
    if n < 2:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True
def generate_primes(limit):
    primes = []
    num = 2
    while len(primes) < limit:
        if is_prime(num):
            primes.append(num)
        num += 1
    return primes
def print_prime_pattern(rows):
    total_numbers_needed = sum(range(1, rows + 1))
    primes = generate_primes(total_numbers_needed)
    index = 0
    for row in range(1, rows + 1):
        for col in range(row):
            print(primes[index], end=" ")
            index += 1
        print() 
print_prime_pattern(5)
```
Kode ini berfungsi untuk mencetak pola bilangan prima dalam bentuk segitiga. Terdapat tiga fungsi utama. Pertama, fungsi is_prime(n) digunakan untuk memeriksa apakah sebuah angka adalah bilangan prima atau tidak. Kedua, fungsi generate_primes(limit) menghasilkan sejumlah bilangan prima yang dibutuhkan. Ketiga, fungsi print_prime_pattern(rows) mencetak pola segitiga dengan jumlah baris sesuai yang diminta. Pada setiap baris, jumlah bilangan prima yang dicetak bertambah sesuai nomor baris, misalnya baris pertama mencetak 1 bilangan prima, baris kedua mencetak 2 bilangan prima, dan seterusnya. Contohnya, jika diminta mencetak pola dengan 5 baris, maka bilangan prima akan dicetak dalam format segitiga dengan 5 baris bertingkat.

#### Output:
<img width="118" alt="image" src="https://github.com/user-attachments/assets/c1e2fe4e-1d2f-49f4-b33c-de691fa41172">

### 2.Buatlah sebuah fungsi yang menerima dua input berupa list angka. Fungsi ini harus mengembalikan sebuah list baru yang berisi elemen dari dua list input yang memiliki indeks ganjil. List baru tersebut juga harus diurutkan secara menurun berdasarkan nilai elemen.
```python
def gabung_ganjil_urut(list1, list2):
    hasil = [x for i, x in enumerate(list1 + list2) if i % 2 != 0]
    return sorted(hasil, reverse=True)

list1 = [1, 3, 5]
list2 = [7, 5, 9, 10, 11,]

hasil = gabung_ganjil_urut(list1, list2)
print(hasil)
```
Kode ini berfungsi untuk menggabungkan dua list dan mengembalikan elemen-elemen yang berada di posisi ganjil, diurutkan secara menurun. Pertama, fungsi gabung_ganjil_urut(list1, list2) menggabungkan list1 dan list2 menjadi satu list. Kemudian, dengan menggunakan list comprehension, fungsi ini memilih elemen-elemen yang berada di indeks ganjil (yaitu, yang memiliki indeks 1, 3, 5, dan seterusnya) dari list yang sudah digabung. Hasilnya adalah list baru yang berisi elemen-elemen tersebut. Setelah itu, list ini diurutkan dalam urutan menurun menggunakan fungsi sorted() dengan parameter reverse=True. Dalam contoh ini, ketika fungsi dipanggil dengan list1 = [1, 3, 5] dan list2 = [7, 5, 9, 10, 11], hasilnya adalah list yang berisi elemen di posisi ganjil dari gabungan kedua list tersebut, dicetak dalam urutan menurun. Sebagai output, program akan menampilkan hasil yang sesuai dengan proses ini.

#### Output
<img width="101" alt="image" src="https://github.com/user-attachments/assets/a743189e-c5f2-4042-bc74-9f78ed1f3b59">

### 3.Buat sebuah program untuk mensimulasikan transaksi ATM. Program harus:
1. Meminta pengguna memasukkan PIN (dibatasi 3 kali percobaan).
2. Setelah PIN benar, meminta jumlah penarikan.
3. Jika saldo kurang dari jumlah yang ditarik, munculkan pesan kesalahan.
4. Jika penarikan berhasil, tampilkan saldo akhir.

```python
def atm_simulation():
    correct_pin = "1234"
    saldo = 1000000
    max_attempts = 3
    attempts = 0
    while attempts < max_attempts:
        pin = input("Masukkan PIN Anda: ")
        if pin == correct_pin:
            print("PIN benar!")
            break
        else:
            attempts += 1
            print(f"PIN salah. {max_attempts - attempts} percobaan tersisa.")
    else:
        print("Anda telah mencapai batas percobaan. Kartu diblokir.")
        return
    while True:
        try:
            tarik = int(input("Masukkan jumlah penarikan: "))
            if tarik > saldo:
                print(f"Saldo tidak mencukupi. Saldo Anda: {saldo}")
            else:
                saldo -= tarik
                print(f"Penarikan berhasil. Saldo akhir Anda: {saldo}")
                break
        except ValueError:
            print("Masukkan jumlah penarikan yang valid.")
atm_simulation()
```
Kode ini mensimulasikan penggunaan mesin ATM dengan fitur verifikasi PIN dan penarikan saldo. Pertama, fungsi atm_simulation() menetapkan PIN yang benar dan saldo awal pengguna. Pengguna diberikan tiga kali kesempatan untuk memasukkan PIN yang benar. Jika PIN yang dimasukkan salah setelah tiga percobaan, program akan memberi tahu bahwa kartu telah diblokir. Jika PIN benar, pengguna kemudian diminta untuk memasukkan jumlah yang ingin ditarik. Program memeriksa apakah jumlah yang diminta melebihi saldo yang tersedia. Jika saldo mencukupi, penarikan berhasil dan saldo diperbarui; jika tidak, pengguna diberi tahu tentang saldo yang tidak mencukupi. Selain itu, jika pengguna memasukkan input yang tidak valid untuk jumlah penarikan, program akan meminta pengguna untuk memasukkan jumlah yang valid. Dengan demikian, program ini menciptakan pengalaman yang realistis dalam menggunakan mesin ATM.

#### Output
<img width="253" alt="image" src="https://github.com/user-attachments/assets/f17b0bd6-6fcf-4dff-b27c-5233368489ec">

### 4.Anda diberikan file CSV berisi data nilai ujian mahasiswa. Tugas Anda adalah menulis sebuah program yang:
1. Membaca file CSV dan menyimpan datanya ke dalam dictionary.
2. Menghitung rata-rata nilai tiap mahasiswa.
3. Menampilkan mahasiswa dengan nilai tertinggi dan terendah.

```python
import csv

def baca_data_csv(file_name):
    data_mahasiswa = {}
    with open(file_name, mode='r') as file:
        reader = csv.reader(file)
        header = next(reader)
        
        for row in reader:
            nama = row[0]
            nilai = list(map(float, row[1:]))
            data_mahasiswa[nama] = nilai
            
    return data_mahasiswa

def hitung_rata_rata(data_mahasiswa):
    rata_rata = {}
    for nama, nilai in data_mahasiswa.items():
        rata_rata[nama] = sum(nilai) / len(nilai)
    return rata_rata

def mahasiswa_tertinggi_terendah(rata_rata):
    mahasiswa_tertinggi = max(rata_rata, key=rata_rata.get)
    mahasiswa_terendah = min(rata_rata, key=rata_rata.get)
    return mahasiswa_tertinggi, mahasiswa_terendah

def main():
    file_name = 'Nilai Siswa.csv'
    data_mahasiswa = baca_data_csv(file_name)
    rata_rata = hitung_rata_rata(data_mahasiswa)
    mahasiswa_tertinggi, mahasiswa_terendah = mahasiswa_tertinggi_terendah(rata_rata)
    print("Rata-rata nilai tiap mahasiswa:")
    for nama, rata in rata_rata.items():
        print(f"{nama}: {rata:.2f}")
    
    print(f"\nMahasiswa dengan nilai tertinggi: {mahasiswa_tertinggi} ({rata_rata[mahasiswa_tertinggi]:.2f})")
    print(f"Mahasiswa dengan nilai terendah: {mahasiswa_terendah} ({rata_rata[mahasiswa_terendah]:.2f})")
if __name__ == "__main__":
    main()
```
Kode ini berfungsi untuk membaca data dari file CSV yang berisi informasi nilai mahasiswa, menghitung rata-rata nilai, serta menentukan mahasiswa dengan nilai tertinggi dan terendah. Fungsi baca_data_csv(file_name) digunakan untuk membuka file CSV, membaca data, dan menyimpannya dalam sebuah dictionary, di mana nama mahasiswa menjadi kunci dan nilai-nilai mereka disimpan sebagai list. Setelah itu, fungsi hitung_rata_rata(data_mahasiswa) menghitung rata-rata nilai setiap mahasiswa dan mengembalikannya dalam dictionary baru. Fungsi mahasiswa_tertinggi_terendah(rata_rata) mengidentifikasi mahasiswa dengan rata-rata tertinggi dan terendah menggunakan fungsi max() dan min(). Fungsi main() mengatur alur program dengan memanggil ketiga fungsi di atas, kemudian mencetak rata-rata nilai setiap mahasiswa serta menyebutkan siapa yang memiliki nilai tertinggi dan terendah. Program ini dirancang untuk memberikan ringkasan nilai mahasiswa dengan cara yang terstruktur dan mudah dimengerti.
#### Output
<img width="188" alt="image" src="https://github.com/user-attachments/assets/5cc3c5f9-2898-4981-89cd-519381b3c2ba">
<img width="131" alt="image" src="https://github.com/user-attachments/assets/11a79f3b-b131-4c9a-9e40-3070a9106af9">
<img width="134" alt="image" src="https://github.com/user-attachments/assets/b93dd6a4-6d31-47ff-a778-144a53807048">
<img width="285" alt="image" src="https://github.com/user-attachments/assets/27a3c3e4-cde0-4809-be6f-a2293a4a2265">

### 5.Buatlah permainan sederhana menggunakan Python, di mana komputer akan memilih sebuah angka secara acak antara 1 hingga 100, dan pengguna harus menebak angka tersebut. Setiap tebakan yang salah akan memberikan petunjuk apakah angka yang ditebak lebih besar atau lebih kecil dari angka sebenarnya. Batasi jumlah percobaan menjadi 5 kali. Setelah permainan selesai, tampilkan apakah pemain menang atau kalah.
```python
import random

def tebak_angka():
    angka_rahasia = random.randint(1, 100)
    percobaan = 5

    print("Selamat datang di permainan Tebak Angka!")
    print("Saya telah memilih sebuah angka antara 1 hingga 100.")
    print(f"Anda memiliki {percobaan} percobaan untuk menebak angka tersebut.")

    for i in range(percobaan):
        try:
            tebakan = int(input(f"Tebakan ke-{i + 1}: "))
            
            if tebakan < 1 or tebakan > 100:
                print("Tebakan harus antara 1 dan 100. Silakan coba lagi.")
                continue
            
            if tebakan < angka_rahasia:
                print("Tebakan Anda terlalu kecil.")
            elif tebakan > angka_rahasia:
                print("Tebakan Anda terlalu besar.")
            else:
                print(f"Selamat! Anda berhasil menebak angka {angka_rahasia}!")
                break
        except ValueError:
            print("Masukkan angka yang valid.")

    else:
        print(f"Maaf, Anda telah kehabisan percobaan. Angka yang benar adalah {angka_rahasia}.")

tebak_angka()
```
Kode ini merupakan permainan sederhana bernama "Tebak Angka" di mana pemain diminta untuk menebak angka rahasia yang dipilih secara acak antara 1 hingga 100. Fungsi tebak_angka() dimulai dengan memilih angka rahasia menggunakan random.randint(), kemudian memberikan pemain lima percobaan untuk menebak angka tersebut. Pemain diminta untuk memasukkan tebakan mereka, dan program akan memberikan umpan balik apakah tebakan terlalu kecil, terlalu besar, atau benar. Jika tebakan berada di luar rentang yang ditentukan (1 hingga 100), pemain akan diberi tahu untuk mencoba lagi. Jika pemain berhasil menebak angka dengan benar, program akan memberi selamat; jika tidak, setelah lima percobaan, program akan mengungkapkan angka rahasia yang sebenarnya. Program ini mengedepankan interaksi pengguna dan penanganan kesalahan input dengan memberikan instruksi yang jelas kepada pemain.
#### Output
<img width="374" alt="image" src="https://github.com/user-attachments/assets/78ccac87-d944-4b33-8d4f-891d9241c74b">

### 6.Buat fungsi rekursif yang menerima input bilangan bulat `n` dan menghasilkan urutan bilangan seperti berikut ini:
Input: n = 4
Output: 1, 1, 2, 6, 24

```python
def factorial_sequence(n):
    if n == 0:
        return [1]
    else:
        seq = factorial_sequence(n-1)
        seq.append(seq[-1] * n)
        return seq

n = 4
print(factorial_sequence(n))
```
Kode ini berfungsi untuk menghasilkan urutan faktorial dari angka yang diberikan menggunakan pendekatan rekursif. Fungsi factorial_sequence(n) menerima satu argumen, yaitu n, dan menghasilkan sebuah list yang berisi faktorial dari semua bilangan bulat dari 0 hingga n. Jika n adalah 0, fungsi mengembalikan list yang berisi nilai faktorial 0, yaitu 1. Jika n lebih besar dari 0, fungsi memanggil dirinya sendiri dengan argumen n-1 untuk mendapatkan urutan faktorial dari angka sebelumnya. Setelah mendapatkan urutan tersebut, faktorial dari n dihitung dengan mengalikan faktorial dari n-1 dengan n, dan hasilnya ditambahkan ke list. Dalam contoh ini, ketika n diatur ke 4, fungsi akan mengembalikan list [1, 1, 2, 6, 24], yang masing-masing merupakan faktorial dari 0, 1, 2, 3, dan 4. Program ini menunjukkan cara penggunaan rekursi untuk menyelesaikan masalah yang melibatkan perhitungan berulang.
#### Output
<img width="109" alt="image" src="https://github.com/user-attachments/assets/682810b3-d576-479b-8944-a4de5e443266">

### 7.Buatlah program untuk memecahkan masalah "minimum coin change". Diberikan jumlah uang dan daftar nilai koin yang tersedia (misalnya, 1, 5, 10, 25), tentukan kombinasi minimum koin yang diperlukan untuk mencapai jumlah uang tersebut. Namun, program Anda harus bisa menangani koin-koin yang nilai dan jumlahnya ditentukan pengguna.
```python
def minimum_coin_change(coins, amount):
    dp = [float('inf')] * (amount + 1)
    dp[0] = 0  

    for coin in coins:
        for x in range(coin, amount + 1):
            dp[x] = min(dp[x], dp[x - coin] + 1)

    if dp[amount] == float('inf'):
        return -1
    
    return dp[amount]

def main():
    try:
        amount = int(input("Masukkan jumlah uang yang ingin dicapai: "))
        coins = list(map(int, input("Masukkan daftar nilai koin (pisahkan dengan spasi): ").split()))
        
        result = minimum_coin_change(coins, amount)
        
        if result == -1:
            print("Tidak ada kombinasi koin yang dapat mencapai jumlah uang tersebut.")
        else:
            print(f"Kombinasi minimum koin yang diperlukan: {result}")
    except ValueError:
        print("Masukkan angka yang valid.")
main()
```
Kode ini berfungsi untuk menentukan jumlah minimum koin yang dibutuhkan untuk mencapai jumlah uang tertentu menggunakan pendekatan dinamis. Fungsi minimum_coin_change(coins, amount) menerima dua argumen: daftar nilai koin dan jumlah uang yang ingin dicapai. Pertama, fungsi menginisialisasi array dp dengan ukuran amount + 1, di mana setiap elemen diisi dengan nilai tak terhingga (menggunakan float('inf')), kecuali dp[0] yang diatur ke 0, menunjukkan bahwa tidak diperlukan koin untuk mencapai jumlah 0. Fungsi kemudian menggunakan dua loop untuk memeriksa setiap koin dan memperbarui nilai di array dp dengan menentukan jumlah koin minimum yang diperlukan untuk mencapai jumlah x. Jika setelah proses ini nilai dp[amount] tetap tak terhingga, berarti tidak ada kombinasi koin yang dapat mencapai jumlah tersebut, dan fungsi akan mengembalikan -1. Jika tidak, fungsi mengembalikan jumlah koin minimum yang diperlukan. Fungsi main() mengatur alur program dengan meminta input dari pengguna, memanggil fungsi minimum_coin_change, dan menampilkan hasilnya, termasuk penanganan kesalahan jika input tidak valid. Program ini efektif dalam memecahkan masalah kombinatorial terkait koin dan jumlah uang.
#### Output
<img width="440" alt="image" src="https://github.com/user-attachments/assets/05a43206-b38a-4e3c-8114-a3ba44b8f48f">

### 8.Buat sebuah program yang menerima string dari pengguna dan mengonversi string tersebut menjadi sebuah list berisi kata-kata terbalik. Misalnya:
Input: "Saya suka Python"
Output: ["ayaS", "akus", "nohtyP"]

```python
def reverse_words(input_string):
    words = input_string.split()
    reversed_words = [word[::-1] for word in words]
    return reversed_words
def main():
    user_input = input("Masukkan string: ")
    result = reverse_words(user_input)
    print(result)
main()
```
Kode ini berfungsi untuk membalik setiap kata dalam sebuah string yang diberikan oleh pengguna. Fungsi reverse_words(input_string) menerima satu argumen, yaitu input_string, yang merupakan string yang ingin diproses. Pertama, string tersebut dipecah menjadi daftar kata menggunakan metode split(). Selanjutnya, list comprehension digunakan untuk membalik setiap kata dalam daftar dengan menggunakan slicing (word[::-1]). Hasilnya adalah daftar yang berisi kata-kata yang telah dibalik. Fungsi main() mengatur alur program dengan meminta pengguna untuk memasukkan sebuah string, memanggil fungsi reverse_words dengan input tersebut, dan mencetak daftar kata yang telah dibalik. Program ini sederhana dan efektif untuk memanipulasi teks, memberikan hasil yang jelas kepada pengguna.
#### Output
<img width="229" alt="image" src="https://github.com/user-attachments/assets/5aae745b-77d6-4fec-a168-247faddf74f3">

### 9.Buat class bernama `Buku` yang memiliki atribut `judul`, `penulis`, dan `tahun_terbit`. Buat method dalam class untuk menampilkan informasi buku, serta method untuk menghitung usia buku berdasarkan tahun saat ini. Buatlah 3 objek dari class `Buku` dan tampilkan informasi serta usia masing-masing buku.
```python
class Buku:
    def __init__(self, judul, penulis, tahun_terbit):
        self.judul = judul
        self.penulis = penulis
        self.tahun_terbit = tahun_terbit

    def tampilkan_informasi(self):
        print(f"Judul: {self.judul}")
        print(f"Penulis: {self.penulis}")
        print(f"Tahun Terbit: {self.tahun_terbit}")

    def hitung_usia_buku(self):
        from datetime import datetime
        tahun_sekarang = datetime.now().year
        return tahun_sekarang - self.tahun_terbit
buku1 = Buku("Cara Bermain Mobile Legend", "Kasparov", 2020)
buku2 = Buku("Heavenly Demon can't normal live", "Jane Smith", 2018)
buku3 = Buku("One Piece", "Eichiro Oda", 2000)
for buku in [buku1, buku2, buku3]:
    buku.tampilkan_informasi()
    print(f"Usia Buku: {buku.hitung_usia_buku()} tahun")
    print()  # Menambahkan garis kosong untuk pemisah
```
Kode ini mendefinisikan sebuah kelas bernama Buku yang digunakan untuk merepresentasikan buku dengan atribut judul, penulis, dan tahun terbit. Metode __init__ bertugas untuk menginisialisasi objek baru dari kelas Buku dengan ketiga atribut tersebut. Metode tampilkan_informasi mencetak informasi tentang buku, termasuk judul, penulis, dan tahun terbit. Sementara itu, metode hitung_usia_buku menghitung usia buku berdasarkan tahun terbitnya dengan membandingkan tahun sekarang menggunakan modul datetime. Dalam contoh ini, tiga objek buku (buku1, buku2, dan buku3) dibuat dengan informasi yang berbeda. Program kemudian menggunakan loop untuk menampilkan informasi masing-masing buku dan menghitung serta mencetak usia buku. Kode ini memberikan cara yang terstruktur untuk mengelola informasi buku dan menghitung usia buku dengan jelas dan mudah dipahami.
#### Output
<img width="217" alt="image" src="https://github.com/user-attachments/assets/f64c5c00-ba1e-4a04-bd6b-8f3ce1b889fd">

### 10.Buatlah program yang mengimplementasikan algoritma pencarian biner, namun dengan modifikasi: algoritma harus bisa mencari nilai di list yang hanya berisi angka genap, dan jika nilai yang dicari adalah angka ganjil, program harus menampilkan pesan bahwa nilai tersebut tidak bisa ditemukan.
```python
def binary_search(sorted_list, target):
    left, right = 0, len(sorted_list) - 1
    
    while left <= right:
        mid = left + (right - left) // 2
        if sorted_list[mid] == target:
            return mid
        elif sorted_list[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
            
    return -1

def main():
    even_numbers = [0, 2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
    try:
        target = int(input("Masukkan angka yang ingin dicari: "))
        if target % 2 != 0:
            print("Nilai yang dicari adalah angka ganjil, tidak dapat ditemukan dalam list genap.")
        else:
            result = binary_search(even_numbers, target)
            
            if result != -1:
                print(f"Nilai {target} ditemukan pada indeks {result}.")
            else:
                print(f"Nilai {target} tidak ditemukan dalam list genap.")
    except ValueError:
        print("Masukkan angka yang valid.")
main()
```
Kode ini menerapkan algoritma pencarian biner untuk menemukan posisi angka dalam daftar genap yang sudah diurutkan. Fungsi binary_search(sorted_list, target) menerima dua argumen: sorted_list, yang merupakan daftar angka genap, dan target, angka yang ingin dicari. Algoritma ini bekerja dengan membagi daftar menjadi dua bagian dan menentukan apakah angka target ada di bagian kiri atau kanan, hingga ditemukan atau tidak ada. Fungsi ini mengembalikan indeks dari angka target jika ditemukan; jika tidak, ia mengembalikan -1. Dalam fungsi main(), program meminta pengguna untuk memasukkan angka yang ingin dicari. Jika angka yang dimasukkan adalah ganjil, program memberikan peringatan bahwa angka tersebut tidak dapat ditemukan dalam daftar genap. Jika angka genap dimasukkan, fungsi pencarian biner dipanggil, dan hasilnya dicetak, termasuk pesan jika angka tidak ditemukan. Program ini efektif untuk mencari angka dalam daftar dengan cepat dan mengedepankan penanganan input yang valid.
#### Output
<img width="441" alt="image" src="https://github.com/user-attachments/assets/340510b7-4f7e-4e23-b28b-0ae82d373908">

## Kesimpulan
  Kesimpulanya adalah bahwa praktikum modul dasar-dasar Python untuk sains data telah berhasil dilakukan dan dipahami. Praktikum ini mencakup dasar teori tentang variabel dan tipe data, operator dan logika, fungsi dan perulangan, serta beberapa contoh program yang dapat dibuat menggunakan Python. Hasil praktikum menunjukkan bahwa Python dapat digunakan untuk membuat program yang efektif dan efisien dalam menyelesaikan masalah-masalah yang berhubungan dengan sains data.
  Dalam keseluruhan, praktikum modul dasar-dasar Python untuk sains data ini sangat bermanfaat dalam memahami dasar-dasar pemrograman dan membuat program yang efektif dan efisien dalam menyelesaikan masalah-masalah yang berhubungan dengan sains data.

## Referensi
[1]	R. B. Wimawan, “Tipe Data Sederhana,” hal. 6, 2019.
[2]	D. Rahmat, S. A’zizah, dan S. Mulyani, “Perkalian Menggunakan Bahasa Pemrograman Perulangan (Looping) Berbantu Sublime Text Dan Xampp,” Djtechno J. Teknol. Inf., vol. 3, no. 2, hal. 149–155, 2022, doi: 10.46576/djtechno.v3i2.2417.

