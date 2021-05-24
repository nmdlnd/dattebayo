# 📖 Dattebayo

> Petunjuk melakukan sebuah commit agar lebih mudah terbaca

## 🛠 Kebutuhan
- Basic penggunaan `(CLI) command line interface`
- Git 

## ⚙️ Konfigurasi

## 🎒 Menspesifikkan tipe commit 

Format untuk melakukan sebuah commit  

```
<type>(<scope>): <subject>

<body>

<footer>
```

Line pertama memiliki format dan nilai seperti berikut :

Nilai dari `<type>` dapat berupa

- `feat` digunakan ketika menambah fitur baru dalam sebuah project, misal menambah fitur seperti login, order, register
- `chore` digunakan apabila sebuah fitur melakukan penambahan fungsi, misal dalam fitur login ingin menambahkan fungsi validasi
- `fix` digunakan untuk memperbaiki bug kecil, semisal seperti typo
- `refactor` digunakan untuk melakukan `refactor` pada `code` yang sudah ada agar mudah dibaca pengembang lain
- `docs` digunakan utuk menuliskan dokumentasi
- `dx` digunakan untuk mengorganisir DX(Developer Experience) pada project, seperti konfigurasi `eslint`, `babel` dll
- `style` digunakan untuk melakukan styling pada project

Nilai dari `<scope>` adalah cakupan yang akan digunakan ketika akan commit, contoh seperti :
- `auth`
- `middleware`
- dll

Nilai dari <body> merupakan detail commit yang akan dideskripsikan, detailnya dapat dibaca di
- https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
- https://365git.tumblr.com/post/3308646748/writing-git-commit-messages

## 👨🏻‍🔬 Implementasi

Dari beberapa keterangan diatas dapat diimplementasikan seperti berikut

Subject

```
chore(auth): menambahkan expired pada token
```
Body

```
Pada proses autentikasi menambahkan fungsi untuk token yang dapat expired selama seminggu
```
Footer
```
Issue #8
```


## 📚 Inpirasi
 - https://github.com/angular/angular.js/commits/master
 - http://karma-runner.github.io/6.3/dev/git-commit-msg.html
 - https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide

