# Blum Auto (Segala resiko ditanggung oleh pemakai)

# Fitur yang tersedia.

- [x] Otomatis Klaim Setiap 8 Jam
- [x] Otomatis CheckIn Harian (Login)
- [x] Otomatis Klaim Hasil Referral
- [x] Mendukung Penggunaan Proxy
- [x] Otomatis Menyelesaikan Tugas (Task)
- [x] Otomatis Bermain Game setelah Klaim 

# Cara Pemakaian

## Bot.py Argumen

| Nama Argument | Deskripsi                                                                          |
| ------------- | ---------------------------------------------------------------------------------- |
| --data        | Melakukan kustomisasi input file data / <br>query, secara bawaan adalah (data.txt) |
| --proxy       | Melakukan kustomisaasi input file proxy, secara bawaan adalah (proxies.txt)        |

## Tentang Config.json

Berikut adalah penjelasan tentang Nama (Key) dan Isi (Value) di dalam file config.json

| Nama (Key)         | Isi (Value)                                  | Deskripsi                                                                                                                                                                                                                                                   |
| ------------------ | -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| interval           | Angka Positif ( 1 - 9999)                    | Berfungsi untuk nilai jeda antara akun                                                                                                                                                                                                                      |
| auto_complete_task | Boolean ( true (aktif) / false (non-aktif) ) | Berfungsi untuk meng-aktifkan dan <br>meng-non-aktifkan fitur Otomatis Penyelesaiian Task                                                                                                                                                                   |
| auto_play_game     | Boolean ( true (aktif) / false (non-aktif))  | Berfungsi untuk meng-aktifkan dan <br>meng-non-aktifkan fitur Otomatis Memaikan game                                                                                                                                                                        |
| game_point         | Angka Positif ( 1 - 9999)                    | game_point mempunyai sub key bernama low dan high. Berfungsi untuk melakukan kustomisasi point game <br>low adalahnilai paling rendah yang akan didapatkan ketika bermain game<br> high adalah nilai paling tinggi yang akan didapatkan ketika bermain game |

## Tentang Proxy

Anda bisa menambahkan daftar proxy di file `proxies.txt` dan format proxynya seprti berikut :

Format :

```
http://host:port
http://user:pass@host:port
```

Contoh :

```
http://127.0.0.1:6969
http://user:pass@127.0.0.1:6969
socks5://127.0.0.1:6969
socks5://user:pass@127.0.0.1:6969
```

## Windows 

1. Pastikan komputer anda telah terinstall python dan git.

    Saran: Gunakan python versi 3.8+ (3.8 keatas atau terbaru)
   
   python site : [https://python.org](https://python.org)
   
   git site : [https://git-scm.com/](https://git-scm.com/)

2. Clone / Duplikasi repository ini.
   ```shell
   git clone https://github.com/0pitrebahan/blum.git
   ```

3. Masuk ke folder Blum
   ```
   cd blum
   ```

4. Install module / library yang dibutuhkan.
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit / ubah file `data.txt`, masukkan data query ke dalam file `data.txt`. Anda bisa mendapatkan query anda dengan cara [[Cara Mendapatkan Query]](https://github.com/user-attachments/assets/e71ae5f9-6829-40ec-aff6-23fab370ceb5). Satu baris untuk 1 akun, jika anda ingin menambah akun ke-2 maka isi di baris yang baru.

6. Jalankan program / scriptnya.
   ```
   python bot.py
   ```

## Linux/VPS 

1. Pastikan komputer anda telah terinstall python dan git.

    Saran: Gunakan python versi 3.8+ (3.8 keatas atau terbaru)
   
   python
   ```shell
   sudo apt install python3 python3-pip
   ```
   git
   ```shell
   sudo apt install git
   ```

2. Clone / Duplikasi repository ini.
   ```shell
   git clone https://github.com/0pitrebahan/blum.git
   ```

3. Masuk ke folder Blum
   ```
   cd blum
   ```

4. Install module / library yang dibutuhkan.
   ```
   python3 -m pip install -r requirements.txt
   ```

5. Edit / ubah file `data.txt`, masukkan data query ke dalam file `data.txt`. Anda bisa mendapatkan query anda dengan cara [[Cara Mendapatkan Query]](https://github.com/user-attachments/assets/e71ae5f9-6829-40ec-aff6-23fab370ceb5). Satu baris untuk 1 akun, jika anda ingin menambah akun ke-2 maka isi di baris yang baru.

6. Jalankan program / scriptnya. (pake screen)
   ```
   sudo apt-get install screen
   ```
   ```
   sudo ufw allow ssh
   ```
   ```
   sudo ufw enable
   ```
   ```
   screen -S blum
   ```
   ```
   python3 bot.py
   ```
**Kalo dah jalan tinggal CTRL + AD**
## Termux

1. Pastikan komputer anda telah terinstall python dan git.

    Saran: Gunakan python versi 3.8+ (3.8 keatas atau terbaru)
   
   python
   ```shell
   pkg install python3
   ```
   git
   ```shell
   pkg install git
   ```

2. Clone / Duplikasi repository ini.
   ```shell
   git clone https://github.com/0pitrebahan/blum.git
   ```

3. Masuk ke folder Blum
   ```
   cd blum
   ```

4. Install module / library yang dibutuhkan.
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit / ubah file `data.txt`, masukkan data query ke dalam file `data.txt`. Anda bisa mendapatkan query anda dengan cara [[Cara Mendapatkan Query]](https://github.com/user-attachments/assets/e71ae5f9-6829-40ec-aff6-23fab370ceb5). Satu baris untuk 1 akun, jika anda ingin menambah akun ke-2 maka isi di baris yang baru.

6. Jalankan program / scriptnya.
   ```
   python bot.py
   ```

# Join My Channel & Group Telegram
- [Channel](https://t.me/Aerdropmobile)
- [Group](https://t.me/AerdropmobileGroup)
