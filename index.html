<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Buku Catatan Hormon & Emosi</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --cream: #f5f0e8;
    --ink: #1a1410;
    --sepia: #8b6f47;
    --rust: #c0392b;
    --sage: #5a7a5a;
    --gold: #b8860b;
    --lavender: #6b5b8a;
    --steel: #3d5a6b;
    --warm-gray: #8a7d6e;
    --paper: #fdf8f0;
    --shadow: rgba(26,20,16,0.12);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: #2c1f14;
    background-image:
      radial-gradient(ellipse at 20% 50%, #3d2b1a 0%, transparent 60%),
      radial-gradient(ellipse at 80% 20%, #1a0f08 0%, transparent 50%);
    min-height: 100vh;
    font-family: 'DM Sans', sans-serif;
    color: var(--ink);
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 40px 20px;
  }

  .book-cover {
    background: var(--paper);
    background-image:
      url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%238b6f47' fill-opacity='0.04'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
    max-width: 680px;
    width: 100%;
    border-radius: 4px 12px 12px 4px;
    box-shadow:
      -8px 0 0 #c8a87a,
      -10px 0 0 #a08050,
      0 20px 60px rgba(0,0,0,0.5),
      inset 0 0 0 1px rgba(139,111,71,0.2);
    overflow: hidden;
    position: relative;
  }

  /* Spine */
  .book-cover::before {
    content: '';
    position: absolute;
    left: 0; top: 0; bottom: 0;
    width: 30px;
    background: linear-gradient(to right, #a08050, #c8a87a, #e8c898);
    box-shadow: inset -3px 0 6px rgba(0,0,0,0.2);
  }

  .book-header {
    padding: 48px 48px 32px 68px;
    border-bottom: 2px solid var(--sepia);
    position: relative;
  }

  .book-header::after {
    content: '';
    position: absolute;
    bottom: -6px; left: 48px; right: 48px;
    height: 2px;
    background: var(--sepia);
    opacity: 0.3;
  }

  .book-label {
    font-family: 'DM Sans', sans-serif;
    font-size: 10px;
    font-weight: 500;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--sepia);
    margin-bottom: 12px;
  }

  .book-title {
    font-family: 'Playfair Display', serif;
    font-size: clamp(26px, 5vw, 38px);
    line-height: 1.2;
    color: var(--ink);
    margin-bottom: 8px;
  }

  .book-subtitle {
    font-size: 13px;
    color: var(--warm-gray);
    font-style: italic;
    line-height: 1.6;
  }

  .ornament {
    font-size: 24px;
    margin-top: 16px;
    opacity: 0.4;
  }

  /* Tab Navigation */
  .tabs {
    display: flex;
    padding: 0 48px 0 68px;
    gap: 4px;
    background: var(--cream);
    border-bottom: 1px solid rgba(139,111,71,0.2);
    overflow-x: auto;
    -webkit-overflow-scrolling: touch;
  }

  .tabs::-webkit-scrollbar { display: none; }

  .tab-btn {
    flex-shrink: 0;
    padding: 14px 16px;
    border: none;
    background: transparent;
    font-family: 'DM Sans', sans-serif;
    font-size: 12px;
    font-weight: 500;
    color: var(--warm-gray);
    cursor: pointer;
    border-bottom: 2px solid transparent;
    margin-bottom: -1px;
    transition: all 0.2s;
    white-space: nowrap;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 4px;
  }

  .tab-btn .tab-emoji { font-size: 16px; }

  .tab-btn:hover { color: var(--ink); }

  .tab-btn.active {
    color: var(--ink);
    border-bottom-color: var(--ink);
    font-weight: 600;
  }

  /* Content */
  .content {
    padding: 0 48px 48px 68px;
    min-height: 500px;
  }

  .hormone-page {
    display: none;
    animation: fadeIn 0.3s ease;
  }

  .hormone-page.active { display: block; }

  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(8px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .page-header {
    padding: 32px 0 24px;
    border-bottom: 1px solid rgba(139,111,71,0.2);
    margin-bottom: 28px;
    display: flex;
    align-items: flex-start;
    gap: 20px;
  }

  .hormone-icon {
    font-size: 40px;
    line-height: 1;
    flex-shrink: 0;
  }

  .hormone-name {
    font-family: 'Playfair Display', serif;
    font-size: 28px;
    font-weight: 700;
    color: var(--ink);
    line-height: 1.1;
  }

  .hormone-nickname {
    font-size: 12px;
    font-weight: 500;
    letter-spacing: 2px;
    text-transform: uppercase;
    margin-top: 6px;
    padding: 4px 10px;
    border-radius: 2px;
    display: inline-block;
  }

  .hormone-desc {
    font-size: 14px;
    color: var(--warm-gray);
    line-height: 1.7;
    margin-top: 6px;
    font-style: italic;
  }

  /* Sections */
  .section {
    margin-bottom: 28px;
  }

  .section-title {
    font-size: 10px;
    letter-spacing: 2.5px;
    text-transform: uppercase;
    font-weight: 600;
    color: var(--sepia);
    margin-bottom: 14px;
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .section-title::after {
    content: '';
    flex: 1;
    height: 1px;
    background: rgba(139,111,71,0.2);
  }

  /* Emotion Tags */
  .emotion-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
  }

  .emotion-tag {
    padding: 6px 14px;
    border-radius: 100px;
    font-size: 13px;
    font-weight: 500;
    border: 1.5px solid;
  }

  /* Example Box */
  .example-box {
    background: var(--cream);
    border-left: 3px solid var(--sepia);
    border-radius: 0 8px 8px 0;
    padding: 16px 18px;
    font-size: 13.5px;
    line-height: 1.7;
    color: var(--ink);
    position: relative;
  }

  .example-box::before {
    content: '"';
    font-family: 'Playfair Display', serif;
    font-size: 48px;
    color: var(--sepia);
    opacity: 0.3;
    position: absolute;
    top: -8px;
    left: 12px;
    line-height: 1;
  }

  .example-text {
    padding-left: 8px;
  }

  /* Two column cards */
  .cards-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
  }

  @media (max-width: 520px) {
    .cards-grid { grid-template-columns: 1fr; }
  }

  .card {
    border-radius: 8px;
    padding: 16px;
    border: 1px solid rgba(139,111,71,0.15);
  }

  .card-title {
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    margin-bottom: 10px;
  }

  .card-list {
    list-style: none;
  }

  .card-list li {
    font-size: 13px;
    line-height: 1.6;
    padding: 4px 0;
    padding-left: 16px;
    position: relative;
    color: var(--ink);
  }

  .card-list li::before {
    content: '→';
    position: absolute;
    left: 0;
    font-size: 11px;
    top: 5px;
    opacity: 0.5;
  }

  /* Warning box */
  .warning-box {
    background: rgba(192,57,43,0.06);
    border: 1px solid rgba(192,57,43,0.2);
    border-radius: 8px;
    padding: 14px 16px;
    font-size: 13px;
    line-height: 1.6;
    color: #8b2e22;
    margin-top: 16px;
  }

  .warning-box strong { font-weight: 600; }

  /* Page numbers */
  .page-number {
    text-align: right;
    font-family: 'Playfair Display', serif;
    font-size: 12px;
    color: var(--warm-gray);
    padding-top: 24px;
    border-top: 1px solid rgba(139,111,71,0.15);
    margin-top: 32px;
    font-style: italic;
  }

  /* Color themes per hormone */
  .theme-dopamin .hormone-nickname { background: rgba(184,134,11,0.12); color: var(--gold); }
  .theme-dopamin .card.trigger { background: rgba(184,134,11,0.05); }
  .theme-dopamin .card.control { background: rgba(90,122,90,0.05); }
  .theme-dopamin .emotion-tag { border-color: var(--gold); color: var(--gold); background: rgba(184,134,11,0.07); }

  .theme-serotonin .hormone-nickname { background: rgba(90,122,90,0.12); color: var(--sage); }
  .theme-serotonin .card.trigger { background: rgba(90,122,90,0.05); }
  .theme-serotonin .card.control { background: rgba(61,90,107,0.05); }
  .theme-serotonin .emotion-tag { border-color: var(--sage); color: var(--sage); background: rgba(90,122,90,0.07); }

  .theme-endorfin .hormone-nickname { background: rgba(192,57,43,0.1); color: var(--rust); }
  .theme-endorfin .card.trigger { background: rgba(192,57,43,0.05); }
  .theme-endorfin .card.control { background: rgba(107,91,138,0.05); }
  .theme-endorfin .emotion-tag { border-color: var(--rust); color: var(--rust); background: rgba(192,57,43,0.07); }

  .theme-oksitosin .hormone-nickname { background: rgba(107,91,138,0.12); color: var(--lavender); }
  .theme-oksitosin .card.trigger { background: rgba(107,91,138,0.05); }
  .theme-oksitosin .card.control { background: rgba(61,90,107,0.05); }
  .theme-oksitosin .emotion-tag { border-color: var(--lavender); color: var(--lavender); background: rgba(107,91,138,0.07); }

  .theme-kortisol .hormone-nickname { background: rgba(61,90,107,0.12); color: var(--steel); }
  .theme-kortisol .card.trigger { background: rgba(61,90,107,0.05); }
  .theme-kortisol .card.control { background: rgba(90,122,90,0.05); }
  .theme-kortisol .emotion-tag { border-color: var(--steel); color: var(--steel); background: rgba(61,90,107,0.07); }

  .theme-adrenalin .hormone-nickname { background: rgba(139,50,20,0.1); color: #8b3214; }
  .theme-adrenalin .card.trigger { background: rgba(139,50,20,0.04); }
  .theme-adrenalin .card.control { background: rgba(90,122,90,0.04); }
  .theme-adrenalin .emotion-tag { border-color: #8b3214; color: #8b3214; background: rgba(139,50,20,0.06); }

  .theme-melatonin .hormone-nickname { background: rgba(45,35,70,0.1); color: #4a3a6b; }
  .theme-melatonin .card.trigger { background: rgba(45,35,70,0.04); }
  .theme-melatonin .card.control { background: rgba(61,90,107,0.04); }
  .theme-melatonin .emotion-tag { border-color: #4a3a6b; color: #4a3a6b; background: rgba(45,35,70,0.06); }

  /* Card titles color per theme */
  .theme-dopamin .card-title { color: var(--gold); }
  .theme-serotonin .card-title { color: var(--sage); }
  .theme-endorfin .card-title { color: var(--rust); }
  .theme-oksitosin .card-title { color: var(--lavender); }
  .theme-kortisol .card-title { color: var(--steel); }
  .theme-adrenalin .card-title { color: #8b3214; }
  .theme-melatonin .card-title { color: #4a3a6b; }

  /* Active tab colors */
  .tab-btn[data-tab="dopamin"].active { border-bottom-color: var(--gold); color: var(--gold); }
  .tab-btn[data-tab="serotonin"].active { border-bottom-color: var(--sage); color: var(--sage); }
  .tab-btn[data-tab="endorfin"].active { border-bottom-color: var(--rust); color: var(--rust); }
  .tab-btn[data-tab="oksitosin"].active { border-bottom-color: var(--lavender); color: var(--lavender); }
  .tab-btn[data-tab="kortisol"].active { border-bottom-color: var(--steel); color: var(--steel); }
  .tab-btn[data-tab="adrenalin"].active { border-bottom-color: #8b3214; color: #8b3214; }
  .tab-btn[data-tab="melatonin"].active { border-bottom-color: #4a3a6b; color: #4a3a6b; }

  /* Spine label */
  .spine-label {
    position: absolute;
    left: 0;
    top: 50%;
    transform: translateX(-50%) translateY(-50%) rotate(-90deg);
    white-space: nowrap;
    font-size: 9px;
    letter-spacing: 2px;
    text-transform: uppercase;
    color: #6a4a2a;
    font-weight: 600;
    width: 120px;
    text-align: center;
  }

  @media (max-width: 600px) {
    .book-header, .content { padding-left: 52px; padding-right: 24px; }
    .tabs { padding-left: 52px; padding-right: 24px; }
    .cards-grid { grid-template-columns: 1fr; }
  }
</style>
</head>
<body>

<div class="book-cover">
  <span class="spine-label">Hormon & Emosi</span>

  <div class="book-header">
    <div class="book-label">Catatan Ilmu Jiwa</div>
    <h1 class="book-title">Hormon & Emosi<br><em>Manusia</em></h1>
    <p class="book-subtitle">Panduan memahami kimia di balik perasaanmu sehari-hari</p>
    <div class="ornament">✦ ✦ ✦</div>
  </div>

  <div class="tabs">
    <button class="tab-btn active" data-tab="dopamin">
      <span class="tab-emoji">⚡</span> Dopamin
    </button>
    <button class="tab-btn" data-tab="serotonin">
      <span class="tab-emoji">🌿</span> Serotonin
    </button>
    <button class="tab-btn" data-tab="endorfin">
      <span class="tab-emoji">💪</span> Endorfin
    </button>
    <button class="tab-btn" data-tab="oksitosin">
      <span class="tab-emoji">🤝</span> Oksitosin
    </button>
    <button class="tab-btn" data-tab="kortisol">
      <span class="tab-emoji">😰</span> Kortisol
    </button>
    <button class="tab-btn" data-tab="adrenalin">
      <span class="tab-emoji">🚨</span> Adrenalin
    </button>
    <button class="tab-btn" data-tab="melatonin">
      <span class="tab-emoji">🌙</span> Melatonin
    </button>
  </div>

  <div class="content">

    <!-- DOPAMIN -->
    <div class="hormone-page active theme-dopamin" id="page-dopamin">
      <div class="page-header">
        <div class="hormone-icon">⚡</div>
        <div>
          <div class="hormone-name">Dopamin</div>
          <span class="hormone-nickname">Hormon Pencapaian & Reward</span>
          <p class="hormone-desc">Meledak saat kamu mendapat sesuatu yang kamu inginkan — tapi cepat hilang, sehingga kamu terus mencari lagi.</p>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Emosi yang ditimbulkan</div>
        <div class="emotion-tags">
          <span class="emotion-tag">Senang meledak</span>
          <span class="emotion-tag">Semangat</span>
          <span class="emotion-tag">Motivasi tinggi</span>
          <span class="emotion-tag">Euforia</span>
          <span class="emotion-tag">Ketagihan</span>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Contoh nyata dalam kehidupan</div>
        <div class="example-box">
          <div class="example-text">Notifikasi Instagram-mu tiba-tiba ramai di-like setelah posting foto — sensasi "yes!" yang bikin kamu langsung cek HP lagi. Atau saat pengumuman lulus CPNS keluar dan namamu ada di sana. Itu dopamin meledak.</div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Cara memicu & mengendalikan</div>
        <div class="cards-grid">
          <div class="card trigger">
            <div class="card-title">✦ Cara Memicu</div>
            <ul class="card-list">
              <li>Pecah target besar jadi langkah kecil — rayakan tiap pencapaian kecil</li>
              <li>Olahraga rutin, terutama yang ada progresnya</li>
              <li>Dengarkan musik favorit</li>
              <li>Makan makanan lezat yang kamu nantikan</li>
              <li>Buat to-do list dan centang satu per satu</li>
            </ul>
          </div>
          <div class="card control">
            <div class="card-title">✦ Cara Mengendalikan</div>
            <ul class="card-list">
              <li>Batasi scroll medsos — dopamin instan dari notif itu adiktif</li>
              <li>Tunda gratifikasi: tahan diri sebelum memberi reward</li>
              <li>Sadari pola "ketagihan" — dopamin bisa jebak kamu di loop</li>
              <li>Digital detox berkala, minimal 1 jam sehari</li>
            </ul>
          </div>
        </div>
        <div class="warning-box"><strong>⚠ Perlu tahu:</strong> Dopamin yang terus-menerus dipicu tanpa jeda (seperti scroll TikTok berjam-jam) membuat ambang batas kesenangan naik — hal normal jadi terasa membosankan.</div>
      </div>

      <div class="page-number">Halaman 1 dari 7 — Dopamin</div>
    </div>

    <!-- SEROTONIN -->
    <div class="hormone-page theme-serotonin" id="page-serotonin">
      <div class="page-header">
        <div class="hormone-icon">🌿</div>
        <div>
          <div class="hormone-name">Serotonin</div>
          <span class="hormone-nickname">Hormon Kepuasan & Ketenangan Stabil</span>
          <p class="hormone-desc">Bukan euforia — tapi rasa cukup dan damai yang membuat kamu merasa "hidup ini oke."</p>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Emosi yang ditimbulkan</div>
        <div class="emotion-tags">
          <span class="emotion-tag">Puas</span>
          <span class="emotion-tag">Tenang</span>
          <span class="emotion-tag">Percaya diri</span>
          <span class="emotion-tag">Bersyukur</span>
          <span class="emotion-tag">Stabil secara emosi</span>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Contoh nyata dalam kehidupan</div>
        <div class="example-box">
          <div class="example-text">Perasaan damai setelah makan siang bareng keluarga di hari libur, atau habis jalan pagi dan sarapan enak sendiri. Tidak ada yang "wah", tapi kamu merasa cukup. Itulah serotonin — beda dari dopamin yang meledak-ledak.</div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Cara memicu & mengendalikan</div>
        <div class="cards-grid">
          <div class="card trigger">
            <div class="card-title">✦ Cara Memicu</div>
            <ul class="card-list">
              <li>Kena sinar matahari pagi minimal 15–20 menit</li>
              <li>Olahraga teratur — jogging, jalan kaki sudah cukup</li>
              <li>Makan makanan tinggi triptofan: telur, pisang, kacang, tempe</li>
              <li>Meditasi atau ibadah yang rutin</li>
              <li>Jurnal rasa syukur — tulis 3 hal baik setiap pagi</li>
            </ul>
          </div>
          <div class="card control">
            <div class="card-title">✦ Cara Mengendalikan</div>
            <ul class="card-list">
              <li>Hindari isolasi sosial terlalu lama</li>
              <li>Kurangi makanan ultra-proses yang mengganggu produksi serotonin di usus</li>
              <li>Tidur cukup — serotonin adalah bahan baku melatonin</li>
              <li>Jaga ritme harian yang konsisten</li>
            </ul>
          </div>
        </div>
        <div class="warning-box"><strong>⚠ Perlu tahu:</strong> 90% serotonin diproduksi di usus, bukan di otak. Makanya pola makan buruk dan gangguan pencernaan bisa langsung mempengaruhi mood — ini disebut <em>gut-brain axis.</em></div>
      </div>

      <div class="page-number">Halaman 2 dari 7 — Serotonin</div>
    </div>

    <!-- ENDORFIN -->
    <div class="hormone-page theme-endorfin" id="page-endorfin">
      <div class="page-header">
        <div class="hormone-icon">💪</div>
        <div>
          <div class="hormone-name">Endorfin</div>
          <span class="hormone-nickname">Hormon Pereda Nyeri Alami</span>
          <p class="hormone-desc">Morfin bikinan tubuh sendiri — muncul saat tubuh menghadapi rasa sakit fisik atau emosional.</p>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Emosi yang ditimbulkan</div>
        <div class="emotion-tags">
          <span class="emotion-tag">Lega setelah nyeri</span>
          <span class="emotion-tag">Euforia olahraga</span>
          <span class="emotion-tag">Bahagia setelah nangis</span>
          <span class="emotion-tag">Kuat menanggung beban</span>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Contoh nyata dalam kehidupan</div>
        <div class="example-box">
          <div class="example-text">Habis lari 5 km, capek banget tapi tiba-tiba mood naik drastis dan merasa "hidup itu indah." Atau setelah nangis puas karena masalah menumpuk, tiba-tiba lega dan lebih ringan. Keduanya dipicu endorfin — bukan lebay, itu kimia otak.</div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Cara memicu & mengendalikan</div>
        <div class="cards-grid">
          <div class="card trigger">
            <div class="card-title">✦ Cara Memicu</div>
            <ul class="card-list">
              <li>Olahraga intensitas sedang–tinggi minimal 30 menit</li>
              <li>Tertawa keras — nonton komedi atau ngobrol seru dengan teman</li>
              <li>Makan makanan pedas (capsaicin memicu endorfin)</li>
              <li>Menangis saat memang perlu — jangan ditahan</li>
              <li>Musik yang menggelegar atau bikin merinding</li>
            </ul>
          </div>
          <div class="card control">
            <div class="card-title">✦ Cara Mengendalikan</div>
            <ul class="card-list">
              <li>Jangan cari "sakit fisik" untuk memicu endorfin — itu tidak sehat</li>
              <li>Olahraga berlebihan juga bisa merusak — ada "exercise addiction"</li>
              <li>Beri jeda recovery yang cukup setelah olahraga intens</li>
            </ul>
          </div>
        </div>
        <div class="warning-box"><strong>⚠ Perlu tahu:</strong> Obat-obatan opioid (morfin, heroin) bekerja dengan meniru endorfin. Ini kenapa keduanya sangat adiktif — tubuh berhenti memproduksi endorfin alami karena sudah "disuplai dari luar."</div>
      </div>

      <div class="page-number">Halaman 3 dari 7 — Endorfin</div>
    </div>

    <!-- OKSITOSIN -->
    <div class="hormone-page theme-oksitosin" id="page-oksitosin">
      <div class="page-header">
        <div class="hormone-icon">🤝</div>
        <div>
          <div class="hormone-name">Oksitosin</div>
          <span class="hormone-nickname">Hormon Kedekatan & Kepercayaan</span>
          <p class="hormone-desc">Muncul saat ada kontak emosional atau fisik yang hangat — membuat kamu merasa aman dan terhubung.</p>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Emosi yang ditimbulkan</div>
        <div class="emotion-tags">
          <span class="emotion-tag">Hangat</span>
          <span class="emotion-tag">Aman</span>
          <span class="emotion-tag">Percaya</span>
          <span class="emotion-tag">Terhubung</span>
          <span class="emotion-tag">Lega setelah curhat</span>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Contoh nyata dalam kehidupan</div>
        <div class="example-box">
          <div class="example-text">Dipeluk ibu setelah lama merantau di kota lain — perasaan hangat dan aman itu bukan imajinasi. Atau ngobrol ngalor-ngidul sampai larut malam sama sahabat lama, tiba-tiba semua beban terasa ringan. Oksitosin juga kenapa bayi langsung tenang saat digendong ibunya.</div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Cara memicu & mengendalikan</div>
        <div class="cards-grid">
          <div class="card trigger">
            <div class="card-title">✦ Cara Memicu</div>
            <ul class="card-list">
              <li>Peluk orang yang kamu percaya — minimal 20 detik</li>
              <li>Curhat dan berbagi cerita dengan sahabat</li>
              <li>Bermain dengan hewan peliharaan</li>
              <li>Melakukan kebaikan kecil untuk orang lain</li>
              <li>Kontak mata yang tulus saat berbicara</li>
            </ul>
          </div>
          <div class="card control">
            <div class="card-title">✦ Cara Mengendalikan</div>
            <ul class="card-list">
              <li>Waspadai — oksitosin bisa membuatmu terlalu percaya orang yang salah</li>
              <li>Jaga batasan sehat dalam hubungan agar oksitosin tidak menciptakan ketergantungan</li>
              <li>Pilih lingkungan sosial yang positif dan saling mendukung</li>
            </ul>
          </div>
        </div>
        <div class="warning-box"><strong>⚠ Perlu tahu:</strong> Oksitosin disebut "hormon cinta" tapi juga bisa memicu rasa protektif berlebihan terhadap kelompok sendiri dan kecurigaan terhadap orang luar — ini yang sering jadi akar <em>in-group vs out-group</em> dalam konflik sosial.</div>
      </div>

      <div class="page-number">Halaman 4 dari 7 — Oksitosin</div>
    </div>

    <!-- KORTISOL -->
    <div class="hormone-page theme-kortisol" id="page-kortisol">
      <div class="page-header">
        <div class="hormone-icon">😰</div>
        <div>
          <div class="hormone-name">Kortisol</div>
          <span class="hormone-nickname">Hormon Stres</span>
          <p class="hormone-desc">Dilepaskan saat otak mendeteksi ancaman atau tekanan. Berguna jangka pendek — berbahaya kalau terus-menerus.</p>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Emosi yang ditimbulkan</div>
        <div class="emotion-tags">
          <span class="emotion-tag">Cemas</span>
          <span class="emotion-tag">Tertekan</span>
          <span class="emotion-tag">Waspada berlebihan</span>
          <span class="emotion-tag">Mudah marah</span>
          <span class="emotion-tag">Lelah tapi susah tidur</span>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Contoh nyata dalam kehidupan</div>
        <div class="example-box">
          <div class="example-text">Deadline besok tapi kerjaan belum dimulai — jantung berdebar, pikiran kalut, susah fokus tapi juga susah istirahat. Atau nunggu hasil SNBT/wawancara kerja berjam-jam. Kalau kondisi ini berlangsung berbulan-bulan (misal: kerjaan tidak pasti, hubungan toxic), kortisol kronisnya bisa merusak kesehatan fisik.</div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Cara memicu & mengendalikan</div>
        <div class="cards-grid">
          <div class="card trigger">
            <div class="card-title">✦ Pemicu Utama</div>
            <ul class="card-list">
              <li>Tekanan pekerjaan atau akademik yang terus-menerus</li>
              <li>Kurang tidur — kortisol naik drastis</li>
              <li>Konflik sosial yang tidak terselesaikan</li>
              <li>Konsumsi kafein berlebihan</li>
              <li>Scrolling berita negatif tanpa henti</li>
            </ul>
          </div>
          <div class="card control">
            <div class="card-title">✦ Cara Menurunkan</div>
            <ul class="card-list">
              <li>Napas dalam: tarik 4 detik, tahan 4, buang 6 detik</li>
              <li>Olahraga ringan — jalan kaki 20 menit sangat efektif</li>
              <li>Tidur 7–9 jam secara konsisten</li>
              <li>Batasi kafein setelah jam 2 siang</li>
              <li>Bicarakan masalah — jangan pendam sendiri</li>
            </ul>
          </div>
        </div>
        <div class="warning-box"><strong>⚠ Perlu tahu:</strong> Kortisol tinggi jangka panjang menekan sistem imun, merusak memori, mengganggu sistem pencernaan, dan menekan produksi serotonin dan dopamin — itulah kenapa orang yang stres kronis susah merasa bahagia meski tidak ada alasan spesifik.</div>
      </div>

      <div class="page-number">Halaman 5 dari 7 — Kortisol</div>
    </div>

    <!-- ADRENALIN -->
    <div class="hormone-page theme-adrenalin" id="page-adrenalin">
      <div class="page-header">
        <div class="hormone-icon">🚨</div>
        <div>
          <div class="hormone-name">Adrenalin</div>
          <span class="hormone-nickname">Hormon Panik & Respons Darurat</span>
          <p class="hormone-desc">Muncul dalam hitungan detik saat bahaya mendadak — membuat tubuh siap lari atau melawan seketika.</p>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Emosi yang ditimbulkan</div>
        <div class="emotion-tags">
          <span class="emotion-tag">Panik</span>
          <span class="emotion-tag">Deg-degan</span>
          <span class="emotion-tag">Siaga total</span>
          <span class="emotion-tag">Grogi</span>
          <span class="emotion-tag">Sensasi memacu</span>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Contoh nyata dalam kehidupan</div>
        <div class="example-box">
          <div class="example-text">Hampir ketabrak motor di jalan — reflek loncat sebelum sempat berpikir, tangan gemetar, jantung kencang. Setelah aman baru sadar betapa paniknya tadi. Atau momen pertama naik wahana roller coaster: takut tapi juga seru — itu adrenalin yang sama, cuma konteksnya berbeda.</div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Cara memicu & mengendalikan</div>
        <div class="cards-grid">
          <div class="card trigger">
            <div class="card-title">✦ Pemicu Utama</div>
            <ul class="card-list">
              <li>Bahaya atau ancaman tiba-tiba</li>
              <li>Olahraga ekstrem atau kompetisi</li>
              <li>Berbicara di depan umum / tampil di panggung</li>
              <li>Kabar mengejutkan — baik maupun buruk</li>
              <li>Film horor atau wahana seru</li>
            </ul>
          </div>
          <div class="card control">
            <div class="card-title">✦ Cara Menurunkan</div>
            <ul class="card-list">
              <li>Napas lambat dan dalam — ini sinyal ke otak bahwa aman</li>
              <li>Gerakkan tubuh — adrenalin butuh "dibakar" secara fisik</li>
              <li>Bicara dalam hati: "Aku aman sekarang"</li>
              <li>Dinginkan wajah dengan air — membantu sistem saraf tenang</li>
            </ul>
          </div>
        </div>
        <div class="warning-box"><strong>⚠ Perlu tahu:</strong> Adrenalin dan kortisol sering muncul bersamaan tapi berbeda kecepatan. Adrenalin = detik pertama (fight-or-flight). Kortisol = menit dan jam berikutnya (mempertahankan siaga). Orang yang sering panic attack mengalami lonjakan adrenalin tanpa bahaya nyata.</div>
      </div>

      <div class="page-number">Halaman 6 dari 7 — Adrenalin</div>
    </div>

    <!-- MELATONIN -->
    <div class="hormone-page theme-melatonin" id="page-melatonin">
      <div class="page-header">
        <div class="hormone-icon">🌙</div>
        <div>
          <div class="hormone-name">Melatonin</div>
          <span class="hormone-nickname">Hormon Tidur & Ritme Malam</span>
          <p class="hormone-desc">Diproduksi saat gelap tiba — memberi sinyal ke tubuh bahwa sudah waktunya istirahat dan memulihkan diri.</p>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Emosi yang ditimbulkan</div>
        <div class="emotion-tags">
          <span class="emotion-tag">Mengantuk</span>
          <span class="emotion-tag">Rileks</span>
          <span class="emotion-tag">Tenang alami</span>
          <span class="emotion-tag">Siap istirahat</span>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Contoh nyata dalam kehidupan</div>
        <div class="example-box">
          <div class="example-text">Kenapa rebahan di kamar gelap bikin ngantuk dalam beberapa menit, tapi scroll HP sampai jam 2 malam malah bikin melek dan susah tidur? Karena cahaya biru layar HP "menipu" otak bahwa masih siang, sehingga melatonin tidak diproduksi. Ini yang disebut <em>blue light disruption.</em></div>
        </div>
      </div>

      <div class="section">
        <div class="section-title">Cara memicu & mengendalikan</div>
        <div class="cards-grid">
          <div class="card trigger">
            <div class="card-title">✦ Cara Memicu</div>
            <ul class="card-list">
              <li>Redupkan lampu 1–2 jam sebelum tidur</li>
              <li>Aktifkan mode malam / filter cahaya biru di HP</li>
              <li>Tidur di jam yang sama setiap malam — ritme penting</li>
              <li>Konsumsi ceri, kiwi, atau pisang — mengandung melatonin alami</li>
              <li>Suhu kamar yang sedikit sejuk membantu produksi melatonin</li>
            </ul>
          </div>
          <div class="card control">
            <div class="card-title">✦ Hindari Penghambatnya</div>
            <ul class="card-list">
              <li>Jauhi layar terang minimal 30–60 menit sebelum tidur</li>
              <li>Jangan minum kafein setelah jam 3 sore</li>
              <li>Hindari tidur siang terlalu lama (lebih dari 30 menit)</li>
              <li>Alkohol merusak kualitas tidur meski terasa membantu tidur</li>
            </ul>
          </div>
        </div>
        <div class="warning-box"><strong>⚠ Perlu tahu:</strong> Serotonin adalah bahan baku melatonin. Artinya, kalau serotonin rendah (kurang olahraga, kurang sinar matahari, pola makan buruk), produksi melatonin malam hari juga terganggu — tidur susah, bangun tidak segar, mood keesokan harinya buruk. Ini siklus yang bisa terus berulang.</div>
      </div>

      <div class="page-number">Halaman 7 dari 7 — Melatonin</div>
    </div>

  </div>
</div>

<script>
  const tabs = document.querySelectorAll('.tab-btn');
  const pages = document.querySelectorAll('.hormone-page');

  tabs.forEach(tab => {
    tab.addEventListener('click', () => {
      tabs.forEach(t => t.classList.remove('active'));
      pages.forEach(p => p.classList.remove('active'));
      tab.classList.add('active');
      document.getElementById('page-' + tab.dataset.tab).classList.add('active');
    });
  });
</script>

</body>
</html>

