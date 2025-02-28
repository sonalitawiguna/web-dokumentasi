# Menulis Dokumentasi dengan GitBook

***

#### Menulis Dokumentasi dengan GitBook

````markdown
# Menulis Dokumentasi dengan GitBook

## 1️⃣ Format Markdown yang Digunakan
GitBook menggunakan **Markdown** untuk memformat teks. Berikut beberapa format penting:

| **Elemen**   | **Sintaks Markdown**  | **Contoh**                   |
|-------------|----------------------|------------------------------|
| **Header**  | `#` hingga `######`   | `# Judul Besar`             |
| **Teks Tebal** | `**teks**`         | **teks**                     |
| **Teks Miring** | `*teks*`         | *teks*                       |
| **Daftar** | `- Item` atau `1. Item` | - Item 1 <br> 1. Item 1    |
| **Kode** | `` `print("Hello")` ``  | `print("Hello")`            |
| **Gambar** | `![alt](url)`         | `![Logo](gambar.png)`        |

## 2️⃣ Menambahkan Halaman dan Bab Baru
Tambahkan halaman baru dengan:
1. Klik **New Page** di sidebar GitBook.
2. Masukkan **judul halaman**.
3. Simpan halaman dan edit kontennya.

Tambahkan halaman ke **SUMMARY.md**:
```markdown
* [Pendahuluan](README.md)
* [Instalasi](instalasi.md)
* [Panduan Penggunaan](panduan.md)
````
