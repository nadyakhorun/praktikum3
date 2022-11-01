Praktikum 3

Hallo nama saya Nadya Khairunnisa, disini saya akan memberikan tutorial cara menginstall Pycharm dan membuat project di Pycharm tersebut.

# Cara Installasi Pycharm #
Anda harus install Pycharm di https://www.jetbrains.com/pycharm/download/#section=windows  , Dan anda pilih yang Community

![198814989-ba36149f-cf88-492d-bb12-d00398751be4](https://user-images.githubusercontent.com/115801823/199205776-4856c833-6dc6-4e5f-87d8-204cb4d27a70.png)

next saja semua perintahnya 

![198933464-45381f87-f77d-4ace-bc48-0bef2d8e66a0](https://user-images.githubusercontent.com/115801823/199205892-e4dcef46-b637-4df9-97df-f46a38157538.png)

tunggu hingga selesai

![198933506-e6659704-6c9f-48ea-bdc9-5b44ceadc8a3](https://user-images.githubusercontent.com/115801823/199206001-a3a19826-5abc-4f44-a206-f6caa04b34a9.png)

Jika sudah selesai maka program siap di gunakan

# Cara Menjalankan Pycharm 
# Latihan 1 #

Pertama-tama anda harus Klik New project lalu kasih nama project anda(sesuai yang anda mau), Dan anda harus pilih yang Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter dan anda klik yang versi Python anda seperti gambar di bawah ini.

![198815436-8756894e-4eb0-4b58-81fe-165afda78652](https://user-images.githubusercontent.com/115801823/199206623-da8f146f-a959-4916-9b6a-c4116fc83a05.png)
![198815442-dbfb3a6e-1d2f-4fdf-b205-1f7ddfb8b16c](https://user-images.githubusercontent.com/115801823/199206702-8c1f921d-97c0-477c-811e-9093e2ffb408.png)

Selanjutnya anda membuat file Python baru di project anda tadi dan anda kasih nama file sesuai yang anda inginkan

![198815862-fbfc7ae9-dc11-4184-898a-4711596e2e7a](https://user-images.githubusercontent.com/115801823/199206930-86998bd7-f99a-420a-80ac-c272b72774b7.png)
![198815863-332a5b4f-c020-40b9-8331-4f98f5794ff9](https://user-images.githubusercontent.com/115801823/199206967-6734bdb9-3b23-42e4-aa1a-e19d0791de97.png)

masukan code dari latihan1 anda lalu Run

	# penggunaan end

	print('A', end='')
	print('B', end='')
	print('C', end='')
	print()
	print('X')
	print('Y')
	print('Z')

	# penggunaan separator
	w, x, y, z = 10, 15, 20, 25
	print(w, x, y, z)
	print(w, x, y, z, sep=',')
	print(w, x, y, z, sep='')
	print(w, x, y, z, sep=':')
	print(w, x, y, z, sep='-----')

	# string format
	print(0, 10 ** 0)
	print(1, 10 ** 1)
	print(2, 10 ** 2)
	print(3, 10 ** 3)
	print(4, 10 ** 4)
	print(5, 10 ** 5)
	print(6, 10 ** 6)
	print(7, 10 ** 7)
	print(8, 10 ** 8)
	print(9, 10 ** 9)
	print(10, 10 ** 10)

	# string format
	print('{0:>3} {1:>16}'.format(0, 10 ** 0))
	print('{0:>3} {1:>16}'.format(1, 10 ** 1))
	print('{0:>3} {1:>16}'.format(2, 10 ** 2))
	print('{0:>3} {1:>16}'.format(3, 10 ** 3))
	print('{0:>3} {1:>16}'.format(4, 10 ** 4))
	print('{0:>3} {1:>16}'.format(5, 10 ** 5))
	print('{0:>3} {1:>16}'.format(6, 10 ** 6))
	print('{0:>3} {1:>16}'.format(7, 10 ** 7))
	print('{0:>3} {1:>16}'.format(8, 10 ** 8))
	print('{0:>3} {1:>16}'.format(9, 10 ** 9))
	print('{0:>3} {1:>16}'.format(10, 10 ** 10))
  
![2022-10-31 (6)](https://user-images.githubusercontent.com/115801823/199207420-363167e4-8a29-4eff-a5ee-0cfd600efb5d.png)
![2022-10-31 (7)](https://user-images.githubusercontent.com/115801823/199207522-c8b0bb92-6937-44e0-a836-9afff3cda4e8.png)

lalu hasil run nya

![2022-10-31 (8)](https://user-images.githubusercontent.com/115801823/199207683-e12e6569-f47d-4436-8933-25b4ed84a25b.png)

# Latihan 2 #
buat latihan baru "latihan2"

lalu masukkan code program

	a=input("masukkan nilai a:")
	b=input("masukkan nilai b:")
	print("variabel a=",a)
	print("variabel b=",b)
	print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

	#konversi nilai variabel
	a=int(a)
	b=int(b)
	print("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
	print("hasil penjumlahan {1}/{0}=%s".format(a,b) %(a/b))
  
![2022-10-31 (13)](https://user-images.githubusercontent.com/115801823/199208529-e1839f74-89e9-45eb-b817-dedba4b1839c.png)

lalu hasil run nya menjadi

![hasil run latihan2](https://user-images.githubusercontent.com/115801823/199208863-f17e4364-2b67-4255-a7ea-21ef6ec14e4a.PNG)

# Latihan 3 #
buat file baru "latihan3"

masukkan code programnya

	string = ""

	x = int(input("Masukkan angka :"))
	bar = x
	# Looping Baris
	while bar >= 0:
	# Looping Kolom Spasi Kosong
	kol = bar
	while kol > 0:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 1
	while kiri < (x - (bar-1)):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = 1
	while kanan < kiri -1:
		string = string + " * "
		kanan = kanan + 1

	string = string + "\n\n"
	bar = bar - 1

	bar = 1
	# Looping Baris
	while bar <= x:
	kol = bar+1
	# Looping Kolom Spasi Kosong
	while kol > 1:
		string = string + "   "
		kol = kol - 1
	# Looping Kolom Bintang Sisi Kiri
	kiri = 0
	while kiri < (x - bar):
		string = string + " * "
		kiri = kiri + 1
	# Looping Kolom Bintang Sisi Kanan
	kanan = kiri
	while kanan > 1:
		string = string + " * "
		kanan = kanan - 1

	string = string + "\n\n"
	bar = bar + 1
	print (string)
  
![2022-10-31 (11)](https://user-images.githubusercontent.com/115801823/199209682-91675004-4ae8-43a9-8dac-0d8d84c08c35.png)
![2022-10-31 (12)](https://user-images.githubusercontent.com/115801823/199209729-6058fb05-b2af-45c3-ab6b-c7221b266f31.png)

Hasil Run

![2022-10-31 (14)](https://user-images.githubusercontent.com/115801823/199209855-5ad435f5-611e-40ec-8bd3-09e1bdbb3139.png)

# Menghitung Luas Dan Keliling Lingkaran #
buat file baru "praktikum3"

  	import math
  	def keliling():
    	global k
    	k = 2 * math.pi * r
  
  	def luas():
    	global l
    	r2 = r ** 2
	l = math.pi * r2

	  print("--------------------------------------------------------")
	  r = float(input("Masukkan nilai jari-jari lingkaran "))
	  keliling()
	  luas()
	  print("--------------------------------------------------------")
	  print("Besar keliling lingkaran dengan jari-jari", r, "adalah", k)
	  print("--------------------------------------------------------")
	  print("Besar luas lingkaran dengan jari-jari", r, "adalah", l)
	  print("--------------------------------------------------------")
  
![2022-10-31 (16)](https://user-images.githubusercontent.com/115801823/199210947-6138f7a8-9968-4ae8-b7a5-5770e7159f1d.png)

Hasil Run

![2022-10-31 (15)](https://user-images.githubusercontent.com/115801823/199211271-a39a8119-319c-45c0-b63b-058aa58c48c4.png)

# Flowchart Menghitung luas dan keliling lingkaran #

![198817259-154fec0b-f2b1-44e5-86c0-4c7ab1ad6142](https://user-images.githubusercontent.com/115801823/199211407-4ea34aa0-2d88-480c-ac4e-16e1bebc1ed6.png)

### Terima Kasih
