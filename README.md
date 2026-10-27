# dago-butik-
tugas dpk jobseet coud computing menggunakan HTML dan CSS
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Katalog Baju Cantik</title>
    <style>
        /* CSS ini yang bertugas menghias halaman agar tampak cantik */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #faf5f5;
            margin: 0;
            padding: 40px 20px;
            display: flex;
            justify-content: center;
        }
        .kartu-baju {
            background: white;
            border-radius: 16px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
            max-width: 350px;
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s;
        }
        .kartu-baju:hover {
            transform: translateY(-5px);
        }
        .foto-baju {
            width: 100%;
            height: 400px;
            object-fit: cover;
        }
        .konten {
            padding: 25px;
        }
        .kategori {
            color: #e06987;
            font-size: 12px;
            text-transform: uppercase;
            letter-spacing: 2px;
            font-weight: bold;
            margin-bottom: 8px;
        }
        .nama-baju {
            font-size: 22px;
            color: #333;
            margin: 0 0 10px 0;
        }
        .harga {
            font-size: 18px;
            color: #666;
            font-weight: 600;
            margin-bottom: 20px;
        }
        .tombol-beli {
            background-color: #e06987;
            color: white;
            border: none;
            padding: 12px 30px;
            font-size: 14px;
            border-radius: 25px;
            cursor: pointer;
            font-weight: bold;
            transition: background 0.2s;
        }
        .tombol-beli:hover {
            background-color: #c95270;
        }
    </style>
</head>
<body>

    <!-- HTML ini yang bertugas memasukkan data baju dan foto -->
    <div class="kartu-baju">
        <!-- Anda bisa mengganti URL gambar di bawah ini dengan foto baju milik Anda -->
        <img class="foto-baju" src="https://unsplash.com" alt="Baju Cantik">
        <div class="konten">
            <div class="kategori">Gaun Musim Panas</div>
            <h2 class="nama-baju">Elegant Floral Dress</h2>
            <div class="harga">Rp 249.000</div>
            <button class="tombol-beli">Lihat Detail</button>
        </div>
    </div>

</body>
</html>
