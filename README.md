<!doctype html>
<html lang="id">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Portofolio — Bintang Parmadinata (dengan CV)</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
<style>
  :root{
    --bg1:#0c0022;
    --bg2:#12002b;
    --neon1:#ff4dff;
    --neon2:#8a3cff;
    --muted: #cfc6ff;
    --card: rgba(255,255,255,0.03);
  }
  *{box-sizing:border-box}
  body{
    margin:0;padding:36px;font-family:"Inter",system-ui,Segoe UI,Roboto,Arial;color:#efeaff;
    background:
      radial-gradient(900px 400px at 10% 10%, rgba(138,60,255,0.10), transparent),
      radial-gradient(700px 350px at 95% 90%, rgba(255,0,230,0.08), transparent),
      linear-gradient(180deg,var(--bg1),var(--bg2));
    -webkit-font-smoothing:antialiased;
  }

  .container{
    max-width:1200px;margin:0 auto;display:grid;grid-template-columns:320px 1fr;gap:28px;
  }

  .card-left{
    background:var(--card);border-radius:14px;padding:20px;border:1px solid rgba(255,255,255,0.04);
    box-shadow: 0 10px 30px rgba(0,0,0,0.6);
    position:relative;overflow:hidden;
  }

  .avatar{width:100%;height:340px;border-radius:12px;overflow:hidden;margin-bottom:14px;border:2px solid rgba(255,255,255,0.03)}
  .avatar img{width:100%;height:100%;object-fit:cover;display:block}

  .glow-left{
    position:absolute;left:-40px;top:-40px;width:160px;height:160px;border-radius:50%;
    background:radial-gradient(circle at 30% 30%, rgba(255,77,255,0.16), transparent 30%);mix-blend-mode:screen;pointer-events:none;
  }

  h2{margin:0;font-size:20px;color:var(--neon1)}
  p.small{margin:6px 0;color:var(--muted);font-size:13px}

  .skill-pill{display:inline-block;padding:6px 10px;border-radius:999px;margin:6px 6px 0 0;background:rgba(255,255,255,0.02);font-size:12px;color:var(--muted);border:1px solid rgba(255,255,255,0.03)}

  .card-right{
    background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
    border-radius:14px;padding:22px;border:1px solid rgba(255,255,255,0.04);
    box-shadow:0 10px 30px rgba(0,0,0,0.6);
  }

  .header-title{display:flex;align-items:center;justify-content:space-between;gap:12px}
  .header-title h3{margin:0;color:var(--neon1);font-size:18px}
  .btn-download{
    background:linear-gradient(90deg,var(--neon1),var(--neon2));padding:10px 14px;border-radius:10px;color:#12002b;font-weight:700;border:none;cursor:pointer;
    box-shadow:0 8px 30px rgba(155,93,255,0.18);
    text-decoration:none;
  }

  .section{margin-top:16px}
  .section h4{margin:0 0 8px 0;color:var(--neon2);font-size:15px}
  .section p{margin:0;color:var(--muted);line-height:1.6}

  /* CV embed area */
  .cv-area{
    margin-top:18px;border-radius:12px;overflow:hidden;border:1px solid rgba(255,255,255,0.04);
    background: linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.00));
    padding:10px;
  }
  .cv-img{
    width:100%;height:auto;display:block;max-height:920px;object-fit:contain;border-radius:8px;
  }
  .cv-wrapper{max-height:780px;overflow:auto;padding:8px;background:linear-gradient(180deg, rgba(255,255,255,0.00), rgba(255,255,255,0.00))}

  /* icons list */
  .list-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:10px;margin-top:10px}
  .item{display:flex;gap:10px;align-items:flex-start}
  .icon{width:36px;height:36px;border-radius:8px;display:flex;align-items:center;justify-content:center;background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border:1px solid rgba(255,255,255,0.03);color:var(--neon2);font-size:16px}

  @media (max-width:900px){
    .container{grid-template-columns:1fr;padding:20px}
    .avatar{height:260px}
    .cv-wrapper{max-height:500px}
  }
</style>
</head>
<body>

  <div class="container">

    <!-- LEFT: Photo + Quick Info -->
    <aside class="card-left" aria-label="Profil singkat">
      <div class="glow-left" aria-hidden="true"></div>

      <div class="avatar">
        <!-- FOTO PROFIL -->
        <img src="/mnt/data/IMG_6704.jpeg" alt="Foto Bintang Parmadinata">
      </div>

      <h2>Bintang Parmadinata</h2>
      <p class="small">Kelas XI — Teknik Komputer & Jaringan (TKJ)</p>

      <div style="height:10px"></div>

      <div class="section">
        <h4>Kontak</h4>
        <p class="small"><strong>TTL:</strong> Tangerang, 7 Agustus 2009<br/>
        <strong>Email:</strong> <a href="mailto:parmadinatabintang@gmail.com" style="color:var(--neon1);text-decoration:none">parmadinatabintang@gmail.com</a><br/>
        <strong>Telp:</strong> <a href="tel:+6285770806136" style="color:var(--neon1);text-decoration:none">085770806136</a><br/>
        <strong>Instagram:</strong> <a href="https://instagram.com/bnntngparma_" target="_blank" style="color:var(--neon1);text-decoration:none">@bnntngparma_</a></p>
      </div>

      <div class="section">
        <h4>Keahlian Singkat</h4>
        <div>
          <span class="skill-pill">Perakitan PC</span>
          <span class="skill-pill">Jaringan LAN</span>
          <span class="skill-pill">Router & Switch</span>
          <span class="skill-pill">Linux & Windows</span>
        </div>
      </div>

    </aside>

    <!-- RIGHT: Content + CV -->
    <main class="card-right" aria-label="Portofolio dan CV">

      <div class="header-title">
        <div>
          <h3>Curriculum Vitae</h3>
          <p style="margin:4px 0 0;color:var(--muted);font-size:13px">CV lengkap & detail pendidikan, pengalaman, dan kemampuan.</p>
        </div>

        <!-- DOWNLOAD BUTTON: mengarah ke file CV -->
        <a class="btn-download" href="/mnt/data/IMG_7384.jpeg" download="CV_Bintang_Parmadinata.jpeg">Download CV</a>
      </div>

      <div class="section">
        <h4>Ringkasan</h4>
        <p class="small">Pelajar kelas XI SMK jurusan Teknik Komputer dan Jaringan. Aktif mempelajari jaringan, perakitan PC, konfigurasi router, dan manajemen server lokal. Terbiasa bekerja tim dan cepat belajar.</p>
      </div>

      <div class="section">
        <h4>Keahlian</h4>
        <div class="list-grid">
          <div class="item"><div class="icon">🖥️</div><div><strong>Perakitan</strong><div class="small" style="color:var(--muted)">Merakit PC & instal OS</div></div></div>
          <div class="item"><div class="icon">🌐</div><div><strong>Jaringan</strong><div class="small" style="color:var(--muted)">LAN/WLAN, subnetting, kabel UTP</div></div></div>
          <div class="item"><div class="icon">⚙️</div><div><strong>Routing</strong><div class="small" style="color:var(--muted)">IP, DHCP, basic routing</div></div></div>
          <div class="item"><div class="icon">🛠️</div><div><strong>Troubleshoot</strong><div class="small" style="color:var(--muted)">Hardware & software</div></div></div>
        </div>
      </div>

      <div class="section">
        <h4>Preview CV (Scroll untuk melihat seluruh halaman)</h4>
        <div class="cv-area">
          <div class="cv-wrapper">
            <!-- GAMBAR CV (DITAMBAHKAN) -->
            <img class="cv-img" src="/mnt/data/IMG_7384.jpeg" alt="CV Bintang Parmadinata">
          </div>
        </div>
      </div>

    </main>

  </div>

  <script>
    // Efek hover pada foto
    const avatarImg = document.querySelector('.avatar img');
    if(avatarImg){
      avatarImg.addEventListener('mouseenter', ()=> avatarImg.style.filter = 'drop-shadow(0 20px 50px rgba(197,95,255,0.45)) saturate(1.08)');
      avatarImg.addEventListener('mouseleave', ()=> avatarImg.style.filter = 'none');
    }
  </script>
</body>
</html>


