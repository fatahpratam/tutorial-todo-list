# Chapter 13: Buat aplikasi todo list
- Mempraktikan context API dari chapter sebelumnya.

## GitHube Pages
Link: [Todo List](https://fatahpratam.github.io/tutorial-todo-list/)

## Youtube Tutorial
- Link: [Full Stack React Developer Course with Appwrite](https://www.youtube.com/watch?v=Bvwq_S0n2pk)
- Creator: [HiteshCodeLab](https://www.youtube.com/@HiteshCodeLab)

## Tips
- Buat juga index.js pada folder context sebagai indexing untuk memudahkan import.
- Untuk mempermudah indexing, dapat menggunakan sintaks:
  `export [daftar fungsi dan variabel] from [jalur file];`
- Trik cepat untuk membuat id adalah cukup dengan memanggil `Date.now()`

## Cara kerja aplikasi
- Pada tampilan terdapat sebuah judul "Manage Your Todos". Di bawahnya terdapat sebuah container yang mengandung sebuah input box dan tombol "Add".
- Ketika User mengetikkan pesan todo di input box lalu menekan tombol "Add". Maka pesan akan disimpan dan ditampilkan sebagai box di bawah container.
- Di dalam box tersebut, User dapat:
  - Mengedit pesan todo di dalam box
  - Menghapus box tersebut
  - User dapat men-checked box tersebut
- Jika User menambahkan todo baru, maka box tersebut akan muncul di bawah box sebelumnya.