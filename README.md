<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata & Portfolio Saya</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333333;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1em;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            background-color: #333333;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 1em;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 0.5em 1em;
            display: block;
        }
        nav ul li a:hover {
            background-color: #333333;
        }
        section {
            padding: 2em;
            margin: 1em;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #333333;
            border-bottom: 2px solid #333;
            padding-bottom: 0.5em;
        }
        .cv {
            max-width: 600px;
            margin: 0 auto;
        }
        .cv-info {
            background-color: #f9f9f9;
            padding: 1em;
            border-radius: 5px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1em;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .multimedia video, .multimedia audio {
            width: 20%;
            max-width: 100px;
            margin: 1em 0;
        }
        form {
            display: grid;
            gap: 1em;
            max-width: 500px;
        }
        input, textarea {
            padding: 0.5em;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background-color: #333333;
            color: white;
            padding: 0.5em 1em;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #333333;
        }
        .messages {
            background-color: #e9f7ef;
            padding: 1em;
            border-left: 4px solid #000;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
            margin-top: 2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Biodata & Portfolio Saya</h1>
        <p>Selamat datang di situs pribadi saya!</p>
    </header>

    <nav>
        <ul>
            <li><a href="#biodata">Biodata/CV</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#multimedia">Multimedia</a></li>
            <li><a href="#kontak">Kontak</a></li>
            <li><a href="#pesan">Pesan</a></li>
        </ul>
    </nav>

    <section id="biodata">
        <h2>Biodata / CV</h2>
        <div class="cv">
            <div class="cv-info">
                <h3>Informasi Pribadi</h3>
                <p><strong>Nama:</strong> Fajar Tri Maulana</p>
                <p><strong>Umur:</strong> 14 tahun</p>
                <p><strong>Alamat:</strong> jawa barat, Indonesia</p>
                <p><strong>Email:</strong> fajartrimaulana@example.com</p>
                <p><strong>Telepon:</strong> +62 123 456 789</p>
                <img src="apjarmodeganteng.jpg" alt="Foto Profil" style="width:100%; border-radius:50%;">
            </div>
        </div>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <p>Galeri foto kegiatan saya.</p>
        <div class="gallery">
            <img src="https://via.placeholder.com/300x200?text=Gambar+1" alt="Gambar 1">
            <img src="https://via.placeholder.com/300x200?text=Gambar+2" alt="Gambar 2">
            <img src="https://via.placeholder.com/300x200?text=Gambar+3" alt="Gambar 3">
            <img src="content://com.android.externalstorage.documents/tree/primary%3AHtml%20apjar::primary:Html apjar/IMG-20250905-WA0296.jpg/300x200?text=Gambar+4" alt="Gambar 4">
        </div>
    </section>

    <section id="Multimedia">
    <h2>Multimedia</h2>
    <p>Disney favorit & Music favorit</p>
    <div class="video-box">
      <video controls>
        <source src="modelamineyamal.mp4" alt="modelamineyamal.mp4">
      </video>

            <h3>Audio Podcast</h3>
            <audio controls>
                <source src="sis puella magica.mp3" type="audio/mpeg">
                Browser Anda tidak mendukung audio.
            </audio>
            <!-- Ganti dengan file audio Anda -->
        </div>
    </section>

    <section id="kontak">
        <h2>Kontak</h2>
        <p>Hubungi saya melalui form di bawah ini atau email langsung ke fajartrimaulana@example.com.</p>
        <form action="#" method="post">
            <label for="nama">Nama:</label>
            <input type="text" id="nama" name="nama" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="pesan">Pesan:</label>
            <textarea id="pesan" name="pesan" rows="5" required></textarea>
            
            <button type="submit">Kirim Pesan</button>
        </form>
    </section>

    <section id="pesan">
        <h2>Pesan-Pesan</h2>
        <p>Beberapa pesan atau testimoni dari klien/teman.</p>
        <div class="messages">
            <p><strong>Dari: Fajar</strong> - "HATUR THANK YOU! Sangat sudah mampir pak dani."</p>
        </div>
        <div class="messages">
            <p><strong>Dari: Fajar</strong> - tetap berjuang meski tidak akan jadi miliki ia</p>
        </div>
        <!-- Tambahkan lebih banyak pesan jika diperlukan -->
    </section>

    <footer>
        <p>&copy; 2025 Fajar Tri Maulana.</p>
    </footer>

    <script>
        // JavaScript sederhana untuk smooth scroll pada navigasi
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
