# adhewahyu
# Review Materi tgl 25
 
 

## SDLC
SOFTWARE DEVELOPMENT LIFE CYCLE merupakan proses struktural dalam membangun sebuah software yang menjamin kualitas dari software tersebut. Tujuan utama SDLC adalah menghasilkan sebuah software berkualitas tinggi yang dapat memenuhi harapan dan kebutuhan client.

#### SDLC Steps

1. Planning                       
2. Requirement Analysis
3. Design
4. Implementation / Coding
5. Testing 
6. Deployment
7. Maintenance

### Jenis Model SDLC
  - Waterfall
  - Agile
  - Literative
  - big bang
  
#### WATERFALL
![Gambar waterfall](https://2.bp.blogspot.com/-cfKijri3O4s/WPxkkBskF3I/AAAAAAAABtE/S6bysnvYlxA5xPrGoMlGM9w68AgeXvJ4ACLcB/s1600/software-development-life-cycle.png)

#### AGILE
![Gambar waterfall](https://miro.medium.com/max/470/0*8iTIy02s1w9dqloc.png)

## Project Management
Management project adalah praktek untuk memulai, merencanakan, mengendalikan dan menutup pekerjaan tim untuk mencapai tujuan yang sudah ditentukan di awal dalam waktu yang sudah ditentukan pula.

### Project Management Tools
- Asana
- YouTrack
- Trello

# Versioning Control with GIT
## What is GIT
Version Control System merupakan sebuah sistem yang mencatat setiap perubahan pada suatu file maupun berkas, dalam sebuah vcs yang disimpan hanyalah perubahannya bukan file secara utuh. Hal ini membuat file yang dilakukan perubahan bisa di reset perubahannya berdasarkan perubahan sebelumnya.
GIT merupakan salah satu jenis Version Control System yang bersifat distributed, yang berarti bahwa setiap perubahan disimpan secara lokal maupun terpusat (Local and Remote).

### Installation

Instalasi GIT

```sh
$ sudo apt install git
```

Configurasi GIT

```sh
$ git config --global user.name "Your name"
$ git config --global user.email “Your email” contoh: example@mail.com
```

Untuk melihat hasil konfigurasi yang sudah dijalankan, gunakan kode berikut:
```sh
$ git config --list 
```

Membuat repository
```sh
$ git init "nama repo" 
contoh : $ git init belajar1
```

Menambahkan berkas pada repo
```sh
$ git add "nama berkas"
```

Untuk meng- Commit
```sh
$ git commit -m "pesan commit"
```

Untuk mengirimkannya ke repositori
```sh
$ git push origin master
```


Jika repositori yang ada belum dikloning dan ingin dihubungkan ke server jarak-jauh, kamu perlu menambahkan
```sh
$ git remote add origin <server>
```

Membuat branch
```sh
$ checkout -b "nama branch"
contoh : $ checkout -b fitur_x
```
Beralih kembali ke master
```sh
$ git checkout master
```

Karena sudah kembali ke master, dan branch yang tadi telah dibuat tidak dibutuhkan lagi, maka branch dapat dihapus dengan kode berikut:
```sh
$ git branch -d "nama branch"
contoh : $ git branch -d fitur_x
```

### Mencoba berkontribusi ke projek orang lain

Meng-clone project orang lain yang akan diberi kontribusi
```sh
$ git clone "link"
contoh : $ git clone https://github.com/adhewahyu-dev/adhewahyu-dev.github.io
```

Membuat branch baru
```sh
$ checkout -b "nama branch"
contoh : $ checkout -b fitur_x
```

Menambah file ke branch
```sh
$ add "nama file"
contoh $ add index.html
```

Memberikan commit
```sh
$ git commit -m "pesan commit"
```


```sh
$ push origin "nama branch yang kita buat"
```




