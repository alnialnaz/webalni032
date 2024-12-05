<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MATERI KELAS 7</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        /* Mengatur desain global */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center; /* Agar konten di tengah secara horizontal */
            padding: 20px;
        }

        /* Mengatur lebar konten utama */
        .container {
            max-width: 900px;
            width: 100%;
            margin: 0 auto; /* Margin otomatis agar konten di tengah */
            background-color: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }

        /* Header */
        header {
            text-align: center;
            margin-bottom: 10px;
        }

        h1 {
            font-size: 22px;
            color: #ff9305;
            margin-bottom: 20px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        }

        /* Section konten utama */
        h2 {
            font-size: 20px;
            margin-bottom: 10px;
            color: #ff9305;
            border-bottom: 2px solid #a05c04e7;
            padding-bottom: 5px;
        }

        h3 {
            font-size: 18px;
            margin-bottom: 10px;
            color: #a05c04e7;
        }

        p {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 10px;
            text-align: justify;
            color: #000000;
        }

        ul {
            margin-left: 20px;
            margin-bottom: 20px;
        }

        li {
            font-size: 16px;
            margin-bottom: 5px;
            color: #000000;
        }

        /* Responsif untuk tampilan mobile */
        @media (max-width: 768px) {
            body {
                padding: 10px;
            }

            h1 {
                font-size: 22px;
            }

            h2 {
                font-size: 20px;
            }

            h3 {
                font-size: 18px;
            }

            p, li {
                font-size: 14px;
            }

            .container {
                padding: 10px;
            }

            iframe {
                width: 100%;
                height: auto;
                min-height: 200px;
                border-radius: 8px;
            }
        }

        /* Responsif untuk iframe video */
        iframe {
            max-width: 100%;
            height: auto;
            border: 0;
            border-radius: 8px;
        }

        /* Footer diatur dengan flexbox agar selalu di tengah halaman */
        footer {
            text-align: center;
            margin: 20px auto;
            font-size: 14px;
            color: #000;
            width: 100%;
            display: flex;
            justify-content: center; /* Menempatkan konten footer di tengah secara horizontal */
            align-items: center; /* Menempatkan konten footer di tengah secara vertikal */
            flex-shrink: 0; /* Memastikan footer tidak mengecil */
        }
        
    </style>
</head>
<body>
    <!-- Navbar Responsif -->
    <nav class="navbar navbar-expand-lg bg-warning w-100">
        <div class="container-fluid">
            <a class="navbar-brand" href="ProyekWeb.html">HOME</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link" href="materibilbul.html">MATERI</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="mediabilbul.html">MEDIA</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="lkpdbilbul.html">LEMBAR KERJA</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="tgsbilbul.html">TUGAS</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="kontak.html">KONTAK</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <header>
        <h1>Bilangan Bulat</h1>
    </header>

    <div class="container">
        <main>
            <section id="pengertian">
                <h2>A. Pengertian Bilangan Bulat</h2>
                <p>Bilangan bulat adalah himpunan bilangan yang mencakup bilangan bulat positif, nol, dan bilangan bulat negatif.</p>
                <p>Bilangan bulat ditulis sebagai: Z = {..., −3, −2, −1, 0, 1, 2, 3, ...}</p>
                <ul>
                    <li>Bilangan bulat positif: 1, 2, 3, 4, ...</li>
                    <li>Nol: 0 (bilangan netral)</li>
                    <li>Bilangan bulat negatif: -1, -2, -3, -4, ...</li>
                </ul>
                <p><strong>Tips:</strong> Gunakan garis bilangan untuk mempermudah penjumlahan dan pengurangan bilangan bulat.</p>
                <img src="bilbul.jpeg" alt="" class="img-fluid border border-primary border-2 rounded border" />
            </section>

            <section id="video">
                <h2>B. Video Pembelajaran Bilangan Bulat</h2>
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/mRy5nXHrHQk?si=4WpLEdhowgwKn2dw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                </div>
            </section>

            <section id="sifat">
                <h2>C. Sifat-Sifat Bilangan Bulat</h2>
                <ul>
                    <li>Tertutup terhadap penjumlahan dan pengurangan.</li>
                    <li>Komutatif pada penjumlahan dan perkalian.</li>
                    <li>Asosiatif pada penjumlahan dan perkalian.</li>
                    <li>Distribusi perkalian terhadap penjumlahan.</li>
                </ul>
            </section>

            <section id="operasi">
                <h2>D. Operasi pada Bilangan Bulat</h2>
                <h3>1. Penjumlahan Bilangan Bulat </h3>
                <ul>
                    <li>Positif + Positif: Hasilnya positif. (Contoh: 4 + 5 = 9)</li>
                    <li>Negatif + Negatif: Hasilnya negatif. (Contoh: -3 + (-6) = -9)</li>
                    <li>Positif + Negatif: Hasil tergantung nilai absolut. (Contoh: 6 + (-4) = 2)</li>
                </ul>

                <h3>2. Pengurangan Bilangan Bulat</h3>
                <ul>
                    <li>Positif - Positif: Hasilnya positif atau negatif. (Contoh: 5 - 3 = 2)</li>
                    <li>Negatif - Positif: Hasilnya negatif. (Contoh: -4 - 3 = -7)</li>
                    <li>Positif - Negatif: Sama dengan menambahkan bilangan positif. (Contoh: 6 - (-2) = 6 + 2 = 8)</li>
                </ul>
            </section>
        </main>
    </div>

    <footer>
        <p>Materi Bilangan Bulat Alni_032</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

