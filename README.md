<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Nara Andra Tyaga</title>
    
    <style>
        /* Reset CSS Dasar */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4; /* Latar belakang abu-abu muda */
            color: #333; /* Warna teks gelap */
        }

        /* Header */
        header {
            background-color: #007bff; /* Warna biru profesional */
            color: white;
            padding: 40px 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0 0 5px 0;
            font-size: 2.5em;
        }

        header p {
            margin: 0;
            font-size: 1.1em;
        }

        /* Konten Utama */
        main {
            max-width: 900px;
            margin: 20px auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: 1fr; /* Satu kolom di tampilan kecil */
            gap: 20px;
        }

        /* Kartu (Sections) */
        .card {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
        }

        .card h2 {
            color: #007bff;
            border-bottom: 2px solid #007bff;
            padding-bottom: 5px;
            margin-top: 0;
        }

        /* Daftar (List) */
        ul {
            list-style: none;
            padding: 0;
        }

        li {
            margin-bottom: 8px;
            line-height: 1.5;
        }

        /* Keterampilan */
        .skills li {
            display: inline-block;
            background-color: #e9ecef;
            color: #333;
            padding: 5px 10px;
            margin: 0 10px 10px 0;
            border-radius: 4px;
            font-size: 0.9em;
        }

        /* Tautan */
        a {
            color: #007bff;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 30px;
            background-color: #333;
            color: white;
            font-size: 0.9em;
        }

        /* Media Query untuk Desktop (membuat tata letak 2 kolom) */
        @media (min-width: 768px) {
            main {
                /* Dua kolom di tampilan desktop */
                grid-template-columns: 2fr 1fr; 
            }
            
            /* Posisikan Ringkasan dan Pendidikan di kolom kiri (2/3) */
            #ringkasan, #pendidikan {
                grid-column: 1 / 3; 
            }

            /* Informasi Dasar, Keterampilan, Tujuan, dan Kontak bisa berbagi kolom */
            #informasi-dasar {
                grid-column: 1 / 2;
            }
            
            #keterampilan {
                grid-column: 2 / 3;
            }
            
            #tujuan {
                grid-column: 1 / 2;
            }

            #kontak {
                grid-column: 2 / 3;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Nara Andra Tyaga</h1>
        <p>Calon Pengembang Perangkat Lunak & Gim (PPLG)</p>
    </header>

    <main>
        <section id="ringkasan" class="card">
            <h2>Ringkasan Singkat</h2>
            <p>Siswa SMK Wikrama Bogor dengan fokus di jurusan PPLG. Saat ini sedang aktif membangun dasar pemrograman web dengan fokus pada HTML dan CSS.</p>
        </section>

        <section id="informasi-dasar" class="card">
            <h2>Informasi Dasar</h2>
            <ul>
                <li>Nama: Nara Andra Tyaga</li>
                <li>Tanggal Lahir: 26 Mei 2010</li>
                <li>Domisili: Griya Benda Asri 1</li>
                <li>Minat: Bermain game, pengembangan software.</li>
            </ul>
        </section>

        <section id="pendidikan" class="card">
            <h2>Pendidikan</h2>
            <ul>
                <li>**Sekolah:** SMK Wikrama Bogor</li>
                <li>**Target Jurusan:** PPLG</li>
                <li>**Rayon/Rombel:** Cicurug-7 / P-3</li>
            </ul>
        </section>

        <section id="keterampilan" class="card">
            <h2>Keterampilan Teknis</h2>
            <ul class="skills">
                <li>HTML (Dasar)</li>
                <li>CSS (Dasar)</li>
            </ul>
        </section>

        <section id="tujuan" class="card">
            <h2>Tujuan Jangka Pendek</h2>
            <p>Fokus pada penguasaan fundamental web. Target membuat satu halaman web statis responsif.</p>
        </section>

        <section id="kontak" class="card">
            <h2>Hubungi Saya</h2>
            <p>
                <a href="https://www.instagram.com/andra_tyg?igsh=MWlmOHR6MWl6aTVrOQ==" target="_blank">Instagram</a> | 
                <a href="https://www.tiktok.com/@andra.tyg?_r=1&_d=el8935dedalh39&sec_uid=MS4wLjABAAAAp0T8UWF6zR_TK6VymW7KnsxloDE1371vdjP7b8aXNFNkG_s-C9mqxYz5s25Eu1CR&share_author_id=6836983545128305666&sharer_language=id&source=h5_t&u_code=dcmdj9hj8flfgj&timestamp=1754308092&user_id=6836983545128305666&sec_user_id=MS4wLjABAAAAp0T8UWF6zR_TK6VymW7KnsxloDE1371vdjP7b8aXNFNkG_s-C9mqxYz5s25Eu1CR&item_author_type=1&utm_source=copy&utm_campaign=client_share&utm_medium=android&share_iid=7534153617323083541&share_link_id=eba78fdc-9186-411b-8833-d36cede9bb43&share_app_id=1180&ugbiz_name=ACCOUNT&ug_btm=b8727%2Cb7360&social_share_type=5&enable_checksum=1" target="_blank">TikTok</a>
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Nara Andra Tyaga. Dibangun dengan HTML dan CSS.</p>
    </footer>

</body>
</html>
