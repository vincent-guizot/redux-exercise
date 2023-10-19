# articles-page

## Front End

1. React Redux

2. Tailwind CSS

## Back End


Pembuatan Back End dapat 2 cara :

1. Buat database, controller dan routing menggunakan PG

2. Buat dengan `json-server`

**Bisa pilih salah 1, jika sanggup 2 2 nya boleh**

---
## Programming Test

Buatlah 4 page: 

a. login & register : page bisa untuk register dan login

b. home

c. about 

d. posting 

e. contact us

dengan default page adalah home, atur masing-masing page menggunakan react-router-dom

## Keterangan

Page home berisi postingan dari halaman posting yang status posting = 1, adapun data yang akan ditampilkan adalah title dan content.

Page posting berisi form input, button submit, dan list postingan

a. Form input terdiri dari title, content, dan posting(0 = draft, 1 = posting, secara default di set 0)

b. Button submit digunakan untuk menyimpan

c. List postingan berisi postingan yang berasal dari local back end check box yang apabila checkbox di centang maka postingan akan muncul di halaman home

--- 
Halaman posting akan bisa diakses apabila sudah login

Page login beris form dan button submit

a. Form berisi input text username dan password

b. Button submit

c. Untuk data user di hardcode

Page about berisi cv dari pembuat, minimal berisi data pribadi (nama, alamat), data pendidikan (sd, smp, sma, diploma, sarjana, dst), data organisasi (pernah mengikuti organisasi apa saja dan sebagai apa), pengalaman kerja (perusahaan apa, sebagai apa, short description pekerjaan)

### Penilaian:

Semua page bisa tampil = score 15

Page home berisi postingan = score 10

Page posting = score 20

Halaman posting baru bisa di buka apabila sudah login = score 15

Page login = socre 10

Page about = score 10

Tampilan = score 20

Apabila menggunakan redux = 20
