<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Web</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  </head>
  <body>
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pendaftaran</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #b2e0f0; /* Warna biru muda */
        }
        label {
            display: block;
            margin-top: 10px;
        }
        input, select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
        }
        button {
            margin-top: 20px;
            padding: 10px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pendaftaran Sederhana</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #b2e0f0; /* Warna biru muda */
        }
        label {
            display: block;
            margin-top: 10px;
        }
        input, select {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
        }
        button {
            margin-top: 20px;
            padding: 10px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<h1>Pendaftaran Ekstrakurikuler</h1>
<form action="#" method="post" enctype="multipart/form-data">
    <label for="firstName">Nama Depan:</label>
    <input type="text" id="firstName" name="firstName" required>

    <label for="lastName">Nama Belakang:</label>
    <input type="text" id="lastName" name="lastName" required>

    <label for="dob">Tempat, Tanggal Lahir:</label>
    <input type="text" id="dob" name="dob" placeholder="Contoh: Jakarta, 1 Januari 2000" required>

    <label for="city">Kota:</label>
    <input type="text" id="city" name="city" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="gender">Jenis Kelamin:</label>
    <select id="gender" name="gender" required>
<option value="">
        </option>
        <option value="male">Laki-laki</option>
        <option value="female">Perempuan</option>
    </select>

    <label for="phone">Nomor HP:</label>
    <input type="tel" id="phone" name="phone" required>

    <label for="fatherName">Nama Ayah:</label>
    <input type="text" id="fatherName" name="fatherName" required>

    <label for="fatherPhone">Nomor HP Ayah:</label>
    <input type="tel" id="fatherPhone" name="fatherPhone" required>

    <label for="motherName">Nama Ibu:</label>
    <input type="text" id="motherName" name="motherName" required>

    <label for="motherPhone">Nomor HP Ibu:</label>
    <input type="tel" id="motherPhone" name="motherPhone" required>

    <label for="extracurricular">Ekstrakurikuler yang Diminati:</label>
    <select id="extracurricular" name="extracurricular" required>
        <option value="">
        </option>
        <option value="basketball">Basket</option>
        <option value="soccer">Sepak Bola</option>
        <option value="volleyball">Voli</option>
        <option value="music">Musik</option>
        <option value="art">Seni</option>
        <option value="scouts">Pramuka</option>
        <option value="debate">Debat</option>
        <option value="drama">Teater</option>
        <option value="science_club">Klub Sains</option>
        <option value="computer_club">Klub Komputer</option>
    </select>

    <label for="photo">Input Foto:</label>
    <input type="file" id="photo" name="photo" accept="image/*" required>

    <button type="submit">Daftar</button>
</form>

</body>
</html>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
</html>
