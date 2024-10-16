# Praktikum-3-Programan-web
Repositori ini berisi latihan dan tugas yang telah diselesaikan sebagai bagian dari Lab 3: CSS Dasar untuk mata kuliah Pemrograman Web di Universitas Pelita Bangsa. Praktikum ini mencakup dasar-dasar penggunaan HTML, seperti pembuatan List, Table dan Form.
## Pendahuluan
Tujuan dari praktikum ini adalah untuk memperkenalkan dasar-dasar HTML kepada mahasiswa. Dengan latihan ini, mahasiswa akan mempelajari cara menggunakan HTML secara internal, eksternal, dan inline, serta bagaimana memilih elemen HTML yang akan digunakan.
## Langkah-Langkah
### 1. Membuat Daftar
HTML Mendukung tiga jenis daftar, yaitu:
- Daftar Tidak Berurutan (<`ul`>)
- Daftar Berurutan (<`ol`>)
- Daftar Definisi (<`dl`>)

Membuat ke 3 jenis daftar html seperti berikut:
```html
<!-- Daftar Tidak Berurutan -->
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>

<!-- Daftar Berurutan -->
<ol>
  <li>Item Pertama</li>
  <li>Item Kedua</li>
  <li>Item Ketiga</li>
</ol>

<!-- Daftar Definisi -->
<dl>
  <dt>Istilah 1</dt>
  <dd>Penjelasan 1</dd>
  <dt>Istilah 2</dt>
  <dd>Penjelasan 2</dd>
</dl>
```
### 2. Membuat Table
Tabel dibuat menggunakan elemen <`table`>, dengan baris (<`tr`>), header (<`th`>), dan sel data (<`td`>).
```html
<table border="1">
  <thead>
    <tr>
      <th>Nama</th>
      <th>Umur</th>
      <th>Pekerjaan</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>miya</td>
      <td>30</td>
      <td>Insinyur</td>
    </tr>
    <tr>
      <td>layla</td>
      <td>25</td>
      <td>Desainer</td>
    </tr>
    <tr>
      <td>aldous</td>
      <td>35</td>
      <td>Guru</td>
    </tr>
  </tbody>
</table>
```
### 3. Membuat Formulir
Formulir dibuat menggunakan elemen <`form`>, dengan berbagai jenis input seperti <`input`>, <`textarea`> dan, <`select`>.
```html
<form action="/submit" method="POST">
  <label for="name">Nama:</label>
  <input type="text" id="name" name="name" required><br><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required><br><br>

  <label for="message">Pesan:</label><br>
  <textarea id="message" name="message" rows="4" cols="50"></textarea><br><br>

  <label for="gender">Jenis Kelamin:</label>
  <select id="gender" name="gender">
    <option value="male">Laki-laki</option>
    <option value="female">Perempuan</option>
    <option value="other">Lainnya</option>
  </select><br><br>

  <input type="submit" value="Kirim">
</form>
```
## Screenshot/Hasil
1. Tampilan ke 3 daftar yang telah di terapkan di HTML.

![Cuplikan layar 2024-10-16 085358](https://github.com/user-attachments/assets/f7ea4b0f-6b52-4ed3-beb9-a1a495f7c886)

2. Tampilan table data yang telah di terapkan di HTML.

![Cuplikan layar 2024-10-16 090233](https://github.com/user-attachments/assets/856b83ac-86e3-493d-ae89-632f39930699)

3. Tampilan folmulir yang telah di terapkan di HTML.

![Cuplikan layar 2024-10-16 090454](https://github.com/user-attachments/assets/c79a2412-d18b-403b-a266-545a2ec75d28)

## Kesimpulan
Panduan ini menunjukkan dasar-dasar cara membuat daftar, tabel, dan formulir di HTML. Elemen-elemen ini penting untuk menyusun konten di halaman web dan membuat formulir interaktif untuk menerima input dari pengguna.
