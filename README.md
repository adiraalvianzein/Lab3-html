# Lab3-html
# Lab3Web - Praktikum 3
**Membuat List, Table, dan Form**

## Langkah-langkah
1. Membuat Ordered List, Unordered List, dan Description List di file  `lab3_list.html`.
2. Membuat Unordered List  `lab3_list.html`.
3. Membuat Description List `lab3_list.html`.
4. Membuat Tabel sederhana di file `lab3_tabel.html`.
5. Membuat Form sederhana di file `lab3_form.html`.

## Membuat ordered list
  
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List Example</title>
</head>
<body>
    <header>
        <h1>Contoh List</h1>
    </header>

    <!-- Ordered List -->
    <section id="ordered-list">
        <h2>Ordered List</h2>
        <ol>
            <li>Pemrograman Web</li>
            <li>Sistem Informasi</li>
            <li>Basis Data</li>
        </ol>
    </section>!

```
![ordered list](https://github.com/user-attachments/assets/0d08dd42-e681-4b50-a3e5-a100203a5876)

## Membuat unordered list
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List Example</title>
</head>
<body>
    <header>
        <h1>Contoh List</h1>
    </header>

    <!-- Unordered List -->
    <section id="unordered-list">
        <h2>Unordered List</h2>
        <ul>
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma & Pemrograman</li>
        </ul>
    </section>
```
## Membuat Description List

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>List Example</title>
</head>
<body>
    <header>
        <h1>Contoh List</h1>
    </header>
    <!-- Description List -->
    <section id="description-list">
        <h2>Description List</h2>
        <dl>
            <dt>Fakultas Teknik</dt>
            <dd>Teknik Informatika</dd>
            <dd>Teknik Industri</dd>
        </dl>
    </section>
</body>
</html>
```
## Membuat Table
```html
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>HTML Lanjutan</title>
</head>
<body>
   <header>
       <h1>Membuat Table</h1>
   </header>
</body>
</html>
<table border="1" cellpadding="4" cellspacing="0">
   <thead>
       <tr>
          <th>No.</th>
          <th>Fakultas</th>
          <th>Program Studi</th>
      </tr>
  </thead>
  <tbody>
      <tr>
         <td>1.</td>
         <td>Teknik</td>
         <td>Teknik Informatika</td>
     </tr>
     <tr>
         <td>2.</td>
         <td>Teknik</td>
         <td>Teknik Industri</td>
    </tr>
    <tr>
         <td>3.</td>
         <td>Teknik</td>
         <td>Teknik Lingkungan</td>
    </tr>
</tbody>
</table>
```

## Membuat Form
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
  <header>
    <h1>Membuat Form</h1>
  </header>
</body>
</html>
<form action="proses.php" method="post">
  <fieldset>
    <legend>Data Pelanggan</legend>
    <p>
      <label for="nama">Nama</label>
      <input type="text" id="nama" name="nama">
    </p>
    <p>
      <label for="alamat">Alamat</label>
      <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
    <p>
      <label>Jenis Kelamin</label>
      <input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
      <input id="jk_p" type="radio" name="kelamin" value="P" /><label
    </p>
```
