# pertemuan-12
pertemuan 12
# Tugas Praktikum

Buat program sederhana dengan mengaplikasikan penggunaan class. Buatlah
class untuk menampilkan daftar nilai mahasiswa, dengan ketentuan:
• Method tambah() untuk menambah data
• Method tampilkan() untuk menampilkan data
• Method hapus(nama) untuk menghapus data berdasarkan nama
• Method ubah(nama) untuk mengubah data berdasarkan nama

• Buat diagram class, flowchart dan penjelasan programnya pada
README.md.
• Commit dan push repository ke github.

# jawab
DIAGRAM


![diagramClass](https://user-images.githubusercontent.com/93035757/147145532-e5061762-5ef6-4cc9-8ffd-6582d5f65d9c.png)

langkah pertama saya membuat sebuah class daftar nilai

class daftarNilai()
selanjutnya membuat method method fungsinya

def tambah(self)
def ubah(self)
def lihat(self)
def hapus(self)

kemudian mengisi setiap method dengan elemen elemen nya

nama= input("masukan nama: ")
nim= input("masukan nim :")                                         
nilaiTugas= int(input("Masukkan Nilai Tugas: "))
nilaiUts= int(input("Masukkan Nilai UTS\t: "))            
nilaiUas= int(input("Masukkan Nilai UAS\t: "))             
nilaiAkhir= (0.30 * nilaiTugas) + (0.35 * nilaiUts) + (0.35 * nilaiUas)
dt[nama]=nim,nilaiTugas,nilaiUts,nilaiUas,nilaiAkhir

selanjutnya membuat sebuah looping

while True:
    input('tambah   (1)
           ubah     (2)
           lihat    (3)
           hapus    (4)
           ')
           c = input("\nsilahkan masukan pilihan : ")
           
kemudian membuat fungsi if else untuk menjalankan method

if (c=="1"):
    data.tambah()
elif (c=="2"):
    data.ubah()
elif (c=="3"):
    data.lihat()
elif (c=="4"):
    data.hapus()
else:
    data.keluar()
    break
    
 # hasil screenshot coding
 ![capture 1](https://user-images.githubusercontent.com/93035757/147146585-b9e71f21-b8fc-4091-9b34-fccc0452986d.PNG)
![capture 2](https://user-images.githubusercontent.com/93035757/147194542-39eace0f-bae9-49a1-8ecd-ddf79e3be079.PNG)
![capture 3](https://user-images.githubusercontent.com/93035757/147146608-22ae16af-a7f9-4e40-a421-335d2d6e6e2f.PNG)


# hasil output
jika memilih tambah
![memlih tambah](https://user-images.githubusercontent.com/93035757/147147454-0bb915b8-ac24-4772-9c05-a04d89c86e37.PNG)

jika memilih ubah
![jika memilih ubah](https://user-images.githubusercontent.com/93035757/147147439-1e4523a8-3a31-4316-9bd4-fedd4eb6625f.PNG)

jika memilih lihat
![jika memilih lihat](https://user-images.githubusercontent.com/93035757/147147434-503c42cc-bdf1-4ab1-9580-37f8e2f70285.PNG)

jika memilih hapus
![jika memilih hapus](https://user-images.githubusercontent.com/93035757/147147428-48871cc4-74e6-42bf-8baa-3b2d9fdf9ec1.PNG)


