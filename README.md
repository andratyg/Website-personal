<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Nara Andra Tyaga</title>
    <link href="https://fonts.googleapis.com/css2?family=Segoe+UI&display=swap" rel="stylesheet">
    
    <style>
        /* Konfigurasi Dasar */
        :root {
            --color-primary: #1e88e5; /* Biru tegas */
            --color-text: #212121; /* Hitam pekat */
            --color-background: #ffffff; /* Putih bersih */
            --color-divider: #e0e0e0; /* Garis abu-abu tipis */
        }

        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: var(--color-background);
            color: var(--color-text);
            line-height: 1.6;
        }

        .container {
            max-width: 800px;
            width: 90%;
            margin: 40px auto;
            border: 1px solid var(--color-divider);
            padding: 30px;
        }

        /* Judul Utama */
        header {
            border-bottom: 3px solid var(--color-primary);
            padding-bottom: 10px;
            margin-bottom: 25px;
        }

        header h1 {
            margin: 0;
            font-size: 2.2em;
            color: var(--color-text);
            font-weight: 700;
        }

        header p {
            margin: 5px 0 0 0;
            font-size: 1.1em;
            color: #616161;
        }

        /* Tata Letak Konten */
        main {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }

        /* Judul Bagian */
        h2 {
            font-size: 1.4em;
            color: var(--color-primary);
            margin-top: 0;
            margin-bottom: 10px;
        }

        /* Daftar Detail */
        ul {
            list-style: none;
            padding: 0;
            margin-top: 0;
        }

        li {
            margin-bottom: 5px;
        }

        /* Keterampilan */
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            padding-top: 5px;
            gap: 8px;
        }

        .skills-list li {
            background-color: #f1f1f1;
            padding: 4px 10px;
            border-radius: 3px;
            font-size: 0.9em;
            font-weight: 600;
        }

        /* Tautan */
        a {
            color: var(--color-primary);
            text-decoration: none;
            margin-right: 15px;
            font-weight: 600;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Footer */
        footer {
            margin-top: 40px;
            padding-top: 15px;
            border-top: 1px solid var(--color-divider);
            text-align: center;
            font-size: 0.85em;
            color: #757575;
        }

        /* Tata Letak Dua Kolom untuk Desktop */
        @media (min-width: 600px) {
            main {
                grid-template-columns: 2fr 1fr;
            }
            
            /* Bagian Detail Pendidikan, Keterampilan, dan Kontak di Kolom Kanan */
            #pendidikan, #keterampilan, #kontak {
                grid-column: 2 / 3;
            }

            /* Ringkasan dan Tujuan di Kolom Kiri */
            #ringkasan, #tujuan {
                grid-column: 1 / 2;
            }

            #informasi-dasar {
                grid-column: 1 / 3;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Nara Andra Tyaga</h1>
            <p>Calon Pengembang Perangkat Lunak dan Gim</p>
        </header>

        <main>
            
            <section id="ringkasan">
                <h2>Ringkasan</h2>
                <p>Siswa SMK Wikrama Bogor, fokus pada jurusan PPLG. Aktif membangun dasar di HTML dan CSS. Berkomitmen untuk transisi ke pemrograman *backend* dan *full-stack*.</p>
            </section>

            <section id="tujuan">
                <h2>Tujuan</h2>
                <p>Penguasaan *styling* dasar dengan CSS. Target terdekat adalah menyelesaikan satu proyek *landing page* minimalis dan memulai belajar JavaScript.</p>
            </section>
            
            <section id="pendidikan">
                <h2>Pendidikan</h2>
                <ul>
                    <li>**Institusi:** SMK Wikrama Bogor</li>
                    <li>**Jurusan:** PPLG</li>
                    <li>**Detail:** Rayon Cicurug-7, Rombel P-3</li>
                </ul>
            </section>
            
            <section id="keterampilan">
                <h2>Keterampilan</h2>
                <ul class="skills-list">
                    <li>HTML Dasar</li>
                    <li>CSS Dasar</li>
                </ul>
            </section>

            <section id="informasi-dasar">
                <h2>Detail Pribadi</h2>
                <ul>
                    <li>**Tanggal Lahir:** 26 Mei 2010</li>
                    <li>**Domisili:** Griya Benda Asri 1</li>
                    <li>**Minat:** Bermain *game* (menganalisis sistem dan desain)</li>
                </ul>
            </section>
            
            <section id="kontak">
                <h2>Media Sosial</h2>
                <div>
                    <a href="https://www.instagram.com/andra_tyg?igsh=MWlmOHR6MWl6aTVrOQ==" target="_blank">Instagram</a>
                    <a href="https://www.tiktok.com/@andra.tyg?_r=1&_d=el8935dedalh39&sec_uid=MS4wLjABAAAAp0T8UWF6zR_TK6VymW7KnsxloDE1371vdjP7b8aXNFNkG_s-C9mqxYz5s25Eu1CR&share_author_id=6836983545128305666&sharer_language=id&source=h5_t&u_code=dcmdj9hj8flfgj&timestamp=1754308092&user_id=6836983545128305666&sec_user_id=MS4wLjABAAAAp0T8UWF6zR_TK6VymW7KnsxloDE1371vdjP7b8aXNFNkG_s-C9mqxYz5s25Eu1CR&item_author_type=1&utm_source=copy&utm_campaign=client_share&utm_medium=android&share_iid=7534153617323083541&share_link_id=eba78fdc-9186-411b-8833-d36cede9bb43&share_app_id=1180&ugbiz_name=ACCOUNT&ug_btm=b8727%2Cb7360&social_share_type=5&enable_checksum=1" target="_blank">TikTok</a>
                </div>
            </section>
            
        </main>
        
        <footer>
            <p>Dibangun dengan HTML dan CSS, 2025.</p>
        </footer>
    </div>

</body>
</html>
