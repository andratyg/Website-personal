<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Nara Andra Tyaga</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    
    <style>
        /* CSS Ditingkatkan */
        :root {
            --primary-color: #007bff; /* Biru terang */
            --secondary-color: #343a40; /* Abu-abu gelap untuk teks */
            --background-color: #f8f9fa; /* Latar belakang sangat terang */
            --card-background: #ffffff; /* Latar belakang kartu putih */
        }

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--background-color);
            color: var(--secondary-color);
            line-height: 1.6;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            max-width: 700px;
            width: 90%;
            margin: 40px auto;
            background: var(--card-background);
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            padding: 0; /* Hapus padding awal */
            overflow: hidden; /* Penting untuk radius */
        }

        /* Header (Bagian Utama/Hero) */
        header {
            background-color: var(--primary-color);
            color: white;
            padding: 40px 30px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
            font-weight: 700;
        }

        header p {
            margin-top: 5px;
            font-weight: 300;
            font-size: 1.1em;
        }

        /* Konten Utama (Main Sections) */
        .content-sections {
            padding: 30px;
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
        }

        .section-title {
            color: var(--primary-color);
            font-size: 1.3em;
            font-weight: 600;
            margin-bottom: 15px;
            padding-bottom: 5px;
            border-bottom: 2px solid #e9ecef;
        }

        /* Daftar dan Detail */
        ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        li {
            margin-bottom: 10px;
            font-weight: 400;
            font-size: 0.95em;
        }

        strong {
            font-weight: 600;
            color: var(--secondary-color);
        }

        /* Keterampilan */
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skills-list li {
            background-color: #e9ecef;
            color: #333;
            padding: 5px 12px;
            border-radius: 4px;
            font-size: 0.85em;
            font-weight: 600;
        }

        /* Tautan Media Sosial */
        .social-links a {
            color: var(--primary-color);
            text-decoration: none;
            margin-right: 15px;
            font-weight: 600;
            transition: color 0.3s;
        }

        .social-links a:hover {
            color: #0056b3; /* Warna biru lebih gelap saat di-hover */
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px 30px;
            background-color: var(--secondary-color);
            color: #cccccc;
            font-size: 0.8em;
        }

        /* Responsif untuk tablet/desktop */
        @media (min-width: 600px) {
            .content-sections {
                grid-template-columns: 1fr 1fr; /* Dua kolom */
            }

            /* Bagian Ringkasan dan Tujuan mencakup dua kolom */
            #ringkasan, #tujuan, #pendidikan {
                grid-column: span 2;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Nara Andra Tyaga</h1>
            <p>Calon Pengembang Perangkat Lunak & Gim (PPLG)</p>
        </header>

        <div class="content-sections">
            
            <section id="ringkasan">
                <h2 class="section-title">Ringkasan</h2>
                <p>Siswa SMK Wikrama Bogor yang bersemangat dalam pengembangan web dan *game*. Aktif membangun dasar di **HTML** dan **CSS** untuk transisi ke pemrograman *backend* dan *full-stack*.</p>
            </section>

            <section id="pendidikan">
                <h2 class="section-title">Pendidikan</h2>
                <ul>
                    <li>**Institusi:** SMK Wikrama Bogor</li>
                    <li>**Target Jurusan:** PPLG (Pengembangan Perangkat Lunak dan Gim)</li>
                    <li>**Detail Kelas:** Rayon Cicurug-7 / Rombel P-3</li>
                </ul>
            </section>
            
            <section id="keterampilan">
                <h2 class="section-title">Keterampilan Teknis</h2>
                <ul class="skills-list">
                    <li>HTML (Dasar)</li>
                    <li>CSS (Dasar)</li>
                    <li>Logika Pemrograman Dasar</li>
                </ul>
            </section>

            <section id="informasi-dasar">
                <h2 class="section-title">Detail Pribadi</h2>
                <ul>
                    <li>**Tanggal Lahir:** 26 Mei 2010</li>
                    <li>**Domisili:** Griya Benda Asri 1</li>
                    <li>**Hobi/Minat:** Bermain game (meningkatkan analisis sistem)</li>
                </ul>
            </section>

            <section id="tujuan">
                <h2 class="section-title">Tujuan Jangka Pendek</h2>
                <p>Saat ini fokus pada penguasaan *styling* dasar dengan CSS. Target terdekat adalah menyelesaikan **satu proyek *landing page*** minimalis dan memulai belajar JavaScript.</p>
            </section>
            
            <section id="kontak">
                <h2 class="section-title">Media Sosial</h2>
                <div class="social-links">
                    <a href="https://www.instagram.com/andra_tyg?igsh=MWlmOHR6MWl6aTVrOQ==" target="_blank">Instagram</a>
                    <a href="https://www.tiktok.com/@andra.tyg?_r=1&_d=el8935dedalh39&sec_uid=MS4wLjABAAAAp0T8UWF6zR_TK6VymW7KnsxloDE1371vdjP7b8aXNFNkG_s-C9mqxYz5s25Eu1CR&share_author_id=6836983545128305666&sharer_language=id&source=h5_t&u_code=dcmdj9hj8flfgj&timestamp=1754308092&user_id=6836983545128305666&sec_user_id=MS4wLjABAAAAp0T8UWF6zR_TK6VymW7KnsxloDE1371vdjP7b8aXNFNkG_s-C9mqxYz5s25Eu1CR&item_author_type=1&utm_source=copy&utm_campaign=client_share&utm_medium=android&share_iid=7534153617323083541&share_link_id=eba78fdc-9186-411b-8833-d36cede9bb43&share_app_id=1180&ugbiz_name=ACCOUNT&ug_btm=b8727%2Cb7360&social_share_type=5&enable_checksum=1" target="_blank">TikTok</a>
                </div>
            </section>
            
        </div>
        
        <footer>
            <p>Kode ini dibuat dengan HTML, CSS, dan semangat PPLG.</p>
        </footer>
    </div>

</body>
</html>
