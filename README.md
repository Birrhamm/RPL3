# FORM UNTUK LOGIN 
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Login</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }

    .login-container {
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      width: 300px;
    }

    .login-container h2 {
      text-align: center;
      color: #333;
    }

    .login-form {
      display: flex;
      flex-direction: column;
    }

    .form-group {
      margin-bottom: 15px;
    }

    .form-group label {
      font-size: 14px;
      color: #555;
      margin-bottom: 5px;
      display: block;
    }

    .form-group input {
      width: 100%;
      padding: 8px;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }

    .form-group button {
      background-color: #4caf50;
      color: #fff;
      padding: 10px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }

    .form-group button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

<div class="login-container">
  <h2>Login</h2>
  <form class="login-form">
    <div class="form-group">
      <label for="username">Username:</label>
      <input type="text" id="username" name="username" required>
    </div>
    <div class="form-group">
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>
    </div>
    <div class="form-group">
      <button type="submit">Login</button>
    </div>
  </form>
</div>

</body>
</html>
```
![Screenshot (224)](https://github.com/Birrhamm/RPL3/assets/115520530/31023419-7cbb-4801-ab7e-0c5fe900ccd2)

# MENU UTAMA
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu Pembayaran SPP</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 15px;
    }

    nav {
      background-color: #0b7502;
      padding: 10px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      padding: 10px;
      margin: 0 10px;
      font-weight: bold;
    }

    nav a:hover {
      background-color: #777777;
    }

    section {
      padding: 20px;
    }

    h2 {
      color: #333;
    }
  </style>
</head>
<body>

<header>
  <h1>Pembayaran SPP</h1>
</header>

<nav>
  <a href="#">Beranda</a>
  <a href="#">Pembayaran</a>
  <a href="#">Cetak Kwitansi</a>
  <a href="#">Laporan</a>
  <a href="#">Hubungi Kami</a>
  <a href="#">Logout</a>
</nav>

<section>
  <h2>Selamat datang di Sistem Pembayaran SPP</h2>
  <p>Di sini Anda dapat melakukan pembayaran SPP dengan mudah dan cepat. Pilih menu yang diinginkan dari navigasi di atas.</p>
</section>

</body>
</html>
```
![Screenshot (225)](https://github.com/Birrhamm/RPL_PembayaranSPP/assets/115520530/a4cc36be-8111-4cd3-8e94-144112bc0d1d)
