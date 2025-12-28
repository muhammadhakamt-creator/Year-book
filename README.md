<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Memori Kelas XII-A</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Playfair+Display:ital,wght@0,700;1,700&display=swap" rel="stylesheet">
</head>
<body>

    <header>
        <div class="overlay">
            <h1>Satu Masa, <br><span>Seribu Cerita.</span></h1>
            <p>E-Yearbook Kelas XII-A | Angkatan 2024</p>
        </div>
    </header>

    <section class="container">
        <h2 class="section-title">Wajah-Wajah Pengukir Sejarah</h2>
        <div class="grid-murid">
            
            <div class="card">
                <div class="photo-frame">
                    <img src="https://via.placeholder.com/300x400" alt="Foto Murid">
                </div>
                <div class="info">
                    <h3>Andi Wijaya</h3>
                    <p class="quote">"Datang telat, pulang cepat, nilai tetap selamat."</p>
                    <span class="social">@andiwijaya</span>
                </div>
            </div>

            <div class="card">
                <div class="photo-frame">
                    <img src="https://via.placeholder.com/300x400" alt="Foto Murid">
                </div>
                <div class="info">
                    <h3>Siti Aminah</h3>
                    <p class="quote">"Diam itu emas, tapi kalau ditanya guru itu horor."</p>
                    <span class="social">@sitiaminah_</span>
                </div>
            </div>

            <div class="card">
                <div class="photo-frame">
                    <img src="https://via.placeholder.com/300x400" alt="Foto Murid">
                </div>
                <div class="info">
                    <h3>Budi Santoso</h3>
                    <p class="quote">"Hidup itu seperti matematika, sulit dipahami."</p>
                    <span class="social">@busan_real</span>
                </div>
            </div>

            </div>
    </section>

    <footer>
        <p>Dibuat dengan ❤️ untuk Kenangan yang Tak Terlupakan</p>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    background-color: #f4f7f6;
    color: #333;
    line-height: 1.6;
}

/* Header / Hero */
header {
    height: 60vh;
    background: url('https://images.unsplash.com/photo-1523050853064-dbad350e701e?auto=format&fit=crop&w=1350&q=80') no-repeat center center/cover;
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
}

.overlay {
    background: rgba(0, 0, 0, 0.5);
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

header h1 {
    font-family: 'Playfair Display', serif;
    font-size: 3.5rem;
}

header h1 span {
    font-style: italic;
    color: #ffd700;
}

/* Container */
.container {
    max-width: 1100px;
    margin: 50px auto;
    padding: 0 20px;
}

.section-title {
    text-align: center;
    margin-bottom: 40px;
    font-family: 'Playfair Display', serif;
    font-size: 2rem;
    position: relative;
}

.section-title::after {
    content: '';
    width: 80px;
    height: 3px;
    background: #ffd700;
    display: block;
    margin: 10px auto;
}

/* Grid System */
.grid-murid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
}

/* Card Style */
.card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
}

.card:hover {
    transform: translateY(-10px);
}

.photo-frame img {
    width: 100%;
    height: 350px;
    object-fit: cover;
    display: block;
}

.info {
    padding: 20px;
    text-align: center;
}

.info h3 {
    margin-bottom: 10px;
    color: #2c3e50;
}

.info .quote {
    font-style: italic;
    font-size: 0.9rem;
    color: #7f8c8d;
    margin-bottom: 15px;
}

.info .social {
    display: block;
    font-size: 0.8rem;
    color: #3498db;
    font-weight: bold;
}

/* Footer */
footer {
    text-align: center;
    padding: 40px 0;
    background: #2c3e50;
    color: white;
    margin-top: 50px;
}

