# Latihan-vcs1
# Masuk git
Untuk login ke Git, Anda bisa menggunakan akun GitHub, Gitlab, atau Bitbucket. Jika belum memiliki akun dari ketiga platform tersebut, Anda dapat mendaftarkan diri terlebih dahulu. Selanjutnya Anda dapat melakukan login awal pada Git menggunakan Command Prompt   (Windows) atau Command Line (Linux) . Kemudian masukkan perintah-perintah yang akan kami jelaskan di bawah ini.

Selanjutnya, masukkan username GitHub Anda menggunakan perintah di ini. Lalu tekan ENTER jika sudah benar.

$ git config --global user.name "UsernameAnda"
Kemudian masukkan email yang tercatat di GitHub Anda menggunakan perintah di ini. Lalu tekan ENTER jika sudah benar.

$ git config --global user.email IsiDenganEmailAnda@gmail.com
Selanjutnya untuk memastikan proses login Anda berhasil, masukkan perintah berikut.

$ git config --list
![2021-10-18](https://user-images.githubusercontent.com/92696202/137738597-7612fa33-7254-4855-b9c9-9bacb2885c49.png)
# Jalankan perintah git init.untuk membuat repositori lokal
git init
![2021-10-18 (1)](https://user-images.githubusercontent.com/92696202/137739925-3bc2cd0b-11f0-4d5a-ba8d-75415044cc51.png)
# untuk membuat file  dapat menggunakan teks editor , lalu simpan file nya pada repositori
echo "#latihan 1" >> README.md
![2021-10-18 (2)](https://user-images.githubusercontent.com/92696202/137740786-be45b5a1-d849-468f-9f99-8fb4cf374e6a.png)
# untuk menambahkan file yang sudah kita buat, gunakan perintah git add
![2021-10-18 (3)](https://user-images.githubusercontent.com/92696202/137741355-cf2636bb-c377-453a-9bf1-20055508ebc1.png)
# Untuk menyimpan perubahan yang ada dalam repositori database lokal, gunakan perintah git commit- m "nama projek"
git commit -m "menambahkan projek"

![2021-10-18 (4)](https://user-images.githubusercontent.com/92696202/137742680-25a32728-cad2-40c2-808a-cef07a88d1e8.png)
# Untuk menyimpan setiap perubahan pada repositort lokal , gunakan perintah git remote add origin (url)
git remote add origin https://github.com/Tjokroo/Latihan-vcs1
![2021-10-18 (5)](https://user-images.githubusercontent.com/92696202/137743457-6b0c3de8-6df9-4351-9914-342b58f49074.png)
