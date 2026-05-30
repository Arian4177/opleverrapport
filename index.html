[opleverrapport-badkamer1.html](https://github.com/user-attachments/files/28418935/opleverrapport-badkamer1.html)
<!DOCTYPE html>
<html lang="nl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0">
<title>Opleverrapport Badkamer — WBP Oortvliet</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
<style>
  :root {
    --green: #1D9E75;
    --green-light: #E1F5EE;
    --green-dark: #0F6E56;
    --red: #E24B4A;
    --red-light: #FCEBEB;
    --amber: #BA7517;
    --amber-light: #FAEEDA;
    --gray-50: #F8F8F6;
    --gray-100: #F0EFEA;
    --gray-200: #E2E1DA;
    --gray-400: #9A9990;
    --gray-600: #5F5E5A;
    --gray-900: #1C1C1A;
    --radius: 10px;
    --radius-lg: 14px;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
  html { font-size: 16px; }
  body { font-family: 'DM Sans', sans-serif; background: var(--gray-50); color: var(--gray-900); min-height: 100vh; }

  .app { max-width: 480px; margin: 0 auto; min-height: 100vh; background: #fff; position: relative; }

  /* Header */
  .header { background: #fff; border-bottom: 1px solid var(--gray-100); padding: 14px 20px 10px; position: sticky; top: 0; z-index: 100; }
  .header-top { display: flex; align-items: center; justify-content: space-between; }
  .header-logo { font-size: 13px; font-weight: 600; color: var(--green-dark); letter-spacing: 0.03em; }
  .header-title { font-size: 16px; font-weight: 600; color: var(--gray-900); }
  .progress-wrap { margin-top: 10px; }
  .progress-bar { height: 3px; background: var(--gray-100); border-radius: 2px; }
  .progress-fill { height: 100%; background: var(--green); border-radius: 2px; transition: width 0.4s cubic-bezier(.4,0,.2,1); }
  .step-info { display: flex; justify-content: space-between; margin-top: 5px; }
  .step-name { font-size: 12px; color: var(--gray-400); }
  .step-count { font-size: 12px; color: var(--gray-400); }

  /* Steps */
  .step { display: none; padding-bottom: 100px; }
  .step.active { display: block; }

  /* Sections */
  .section { padding: 20px 20px 4px; }
  .section + .section { border-top: 1px solid var(--gray-100); }
  .section-title { font-size: 11px; font-weight: 600; color: var(--gray-400); text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 14px; }

  /* Fields */
  .field { margin-bottom: 14px; }
  .field label { display: block; font-size: 13px; color: var(--gray-600); margin-bottom: 5px; font-weight: 500; }
  .field input[type=text],
  .field input[type=date],
  .field select,
  .field textarea {
    width: 100%; padding: 11px 14px;
    border: 1px solid var(--gray-200); border-radius: var(--radius);
    font-size: 15px; font-family: 'DM Sans', sans-serif;
    background: #fff; color: var(--gray-900);
    -webkit-appearance: none; appearance: none;
    transition: border-color 0.15s;
    outline: none;
  }
  .field input:focus, .field select:focus, .field textarea:focus { border-color: var(--green); }
  .field textarea { min-height: 80px; resize: vertical; line-height: 1.5; }

  /* Checklist */
  .check-row { display: flex; align-items: center; gap: 10px; padding: 11px 20px; border-bottom: 1px solid var(--gray-100); }
  .check-label { flex: 1; font-size: 14px; color: var(--gray-900); line-height: 1.3; }
  .status-btns { display: flex; gap: 5px; flex-shrink: 0; }
  .sbtn {
    width: 38px; height: 38px; border-radius: var(--radius);
    border: 1px solid var(--gray-200); background: #fff;
    cursor: pointer; display: flex; align-items: center; justify-content: center;
    font-size: 15px; transition: all 0.12s; flex-shrink: 0;
  }
  .sbtn:active { transform: scale(0.92); }
  .sbtn.ok.active { background: var(--green-light); border-color: var(--green); color: var(--green-dark); }
  .sbtn.nok.active { background: var(--red-light); border-color: var(--red); color: var(--red); }
  .sbtn.pm.active { background: var(--amber-light); border-color: var(--amber); color: var(--amber); }
  .note-input {
    width: 88px; flex-shrink: 0;
    padding: 7px 9px; border: 1px solid var(--gray-200); border-radius: 8px;
    font-size: 12px; font-family: 'DM Sans', sans-serif; background: var(--gray-50);
    color: var(--gray-900); outline: none;
  }
  .note-input:focus { border-color: var(--green); }

  .legend { display: flex; gap: 14px; padding: 10px 20px 6px; }
  .leg { display: flex; align-items: center; gap: 5px; font-size: 12px; color: var(--gray-400); }
  .leg-dot { width: 8px; height: 8px; border-radius: 50%; }

  /* Photos */
  .photo-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; padding: 20px; }
  .photo-card {
    border: 1.5px dashed var(--gray-200); border-radius: var(--radius-lg);
    aspect-ratio: 1; display: flex; flex-direction: column;
    align-items: center; justify-content: center; gap: 7px;
    cursor: pointer; background: var(--gray-50); position: relative; overflow: hidden;
    transition: border-color 0.15s;
  }
  .photo-card:active { opacity: 0.8; }
  .photo-card.taken { border-style: solid; border-color: var(--green); }
  .photo-card img { width: 100%; height: 100%; object-fit: cover; border-radius: calc(var(--radius-lg) - 2px); }
  .photo-card .photo-icon { font-size: 28px; color: var(--gray-200); }
  .photo-card .photo-label { font-size: 13px; color: var(--gray-400); font-weight: 500; }
  .photo-card .taken-badge {
    position: absolute; top: 8px; right: 8px;
    width: 24px; height: 24px; border-radius: 50%;
    background: var(--green); display: flex; align-items: center; justify-content: center;
    color: white; font-size: 13px;
  }
  .photo-card input[type=file] { position: absolute; inset: 0; opacity: 0; cursor: pointer; }

  /* Signature */
  .sig-wrap { padding: 0 20px 16px; }
  .sig-canvas {
    width: 100%; height: 150px; display: block;
    border: 1px solid var(--gray-200); border-radius: var(--radius);
    background: #fff; touch-action: none; cursor: crosshair;
  }
  .sig-canvas.signed { border-color: var(--green); }
  .sig-hint { font-size: 12px; color: var(--gray-400); margin-top: 5px; }
  .sig-clear-btn {
    background: none; border: none; cursor: pointer;
    font-size: 12px; color: var(--gray-400); padding: 4px 0; font-family: 'DM Sans', sans-serif;
  }

  /* Navigation */
  .nav-bar {
    position: fixed; bottom: 0; left: 50%; transform: translateX(-50%);
    width: 100%; max-width: 480px;
    background: #fff; border-top: 1px solid var(--gray-100);
    padding: 12px 20px; display: flex; gap: 10px;
    z-index: 200;
  }
  .btn-primary {
    flex: 1; padding: 15px; background: var(--green); color: white;
    border: none; border-radius: var(--radius); font-size: 16px; font-weight: 600;
    cursor: pointer; font-family: 'DM Sans', sans-serif; transition: opacity 0.15s;
  }
  .btn-primary:active { opacity: 0.85; }
  .btn-secondary {
    padding: 15px 20px; background: var(--gray-100); color: var(--gray-900);
    border: none; border-radius: var(--radius); font-size: 16px;
    cursor: pointer; font-family: 'DM Sans', sans-serif;
  }

  /* Overzicht */
  .ov-card { background: #fff; border: 1px solid var(--gray-100); border-radius: var(--radius-lg); margin: 0 20px 12px; overflow: hidden; }
  .ov-head { padding: 11px 14px; background: var(--gray-50); display: flex; align-items: center; gap: 8px; font-size: 13px; font-weight: 600; color: var(--gray-600); border-bottom: 1px solid var(--gray-100); }
  .ov-row { display: flex; justify-content: space-between; align-items: center; padding: 10px 14px; border-bottom: 1px solid var(--gray-100); font-size: 14px; }
  .ov-row:last-child { border-bottom: none; }
  .ov-key { color: var(--gray-400); }
  .ov-val { font-weight: 500; text-align: right; max-width: 58%; }
  .check-item { display: flex; align-items: center; justify-content: space-between; padding: 8px 14px; border-top: 1px solid var(--gray-100); font-size: 13px; gap: 8px; }
  .foto-row { display: flex; flex-wrap: wrap; gap: 8px; padding: 12px 14px; }
  .foto-thumb { width: 60px; height: 60px; border-radius: 8px; object-fit: cover; border: 1px solid var(--gray-100); }
  .foto-empty { width: 60px; height: 60px; border-radius: 8px; background: var(--gray-100); display: flex; align-items: center; justify-content: center; font-size: 10px; color: var(--gray-400); text-align: center; padding: 4px; }

  /* Tags */
  .tag { display: inline-flex; align-items: center; gap: 3px; padding: 3px 9px; border-radius: 20px; font-size: 12px; font-weight: 500; }
  .tag-ok { background: var(--green-light); color: var(--green-dark); }
  .tag-nok { background: var(--red-light); color: var(--red); }
  .tag-pm { background: var(--amber-light); color: var(--amber); }
  .tag-neu { background: var(--gray-100); color: var(--gray-400); }
  .pill { display: inline-block; padding: 4px 12px; border-radius: 20px; font-size: 13px; font-weight: 600; }
  .pill-ok { background: var(--green-light); color: var(--green-dark); }
  .pill-pm { background: var(--amber-light); color: var(--amber); }
  .pill-nok { background: var(--red-light); color: var(--red); }

  /* Sending / Done */
  .center-screen { display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 3rem 2rem; text-align: center; min-height: 60vh; }
  .spinner { width: 44px; height: 44px; border: 3px solid var(--gray-100); border-top-color: var(--green); border-radius: 50%; animation: spin 0.7s linear infinite; margin-bottom: 1.5rem; }
  @keyframes spin { to { transform: rotate(360deg); } }
  .done-icon { width: 64px; height: 64px; border-radius: 50%; background: var(--green-light); display: flex; align-items: center; justify-content: center; margin-bottom: 1rem; font-size: 28px; }
  .ai-card { background: var(--gray-50); border: 1px solid var(--gray-100); border-radius: var(--radius-lg); padding: 16px 18px; text-align: left; margin-top: 1.5rem; font-size: 14px; line-height: 1.65; color: var(--gray-900); width: 100%; }
  .ai-card-title { font-size: 12px; font-weight: 600; color: var(--gray-400); text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 10px; }

  /* Setup screen */
  .setup-screen { padding: 2rem 20px; }
  .setup-logo { font-size: 22px; font-weight: 700; color: var(--green-dark); margin-bottom: 4px; }
  .setup-sub { font-size: 14px; color: var(--gray-400); margin-bottom: 2rem; }
  .info-box { background: var(--green-light); border-radius: var(--radius-lg); padding: 14px 16px; margin-bottom: 1.5rem; font-size: 14px; color: var(--green-dark); line-height: 1.5; }
  .info-box strong { font-weight: 600; }
  .setup-btn { width: 100%; padding: 15px; background: var(--green); color: white; border: none; border-radius: var(--radius); font-size: 16px; font-weight: 600; cursor: pointer; font-family: 'DM Sans', sans-serif; margin-top: 1rem; }

  /* EmailJS config notice */
  .config-notice { background: #FFF9E6; border: 1px solid #F0D060; border-radius: var(--radius); padding: 12px 14px; margin: 0 20px 16px; font-size: 13px; color: #7A5C00; line-height: 1.5; }

  @media (max-width: 400px) {
    .note-input { width: 72px; }
  }
</style>
</head>
<body>

<div class="app">

<!-- SETUP SCREEN -->
<div id="setup-screen" class="setup-screen">
  <div class="setup-logo">WBP Oortvliet</div>
  <div class="setup-sub">Opleverrapport Badkamer</div>
  <div class="info-box">
    <strong>Welkom!</strong><br>
    Doorloop de stappen om het rapport in te vullen. Aan het einde wordt alles automatisch verstuurd naar <strong>baderie@wbpoortvliet.nl</strong>.
  </div>
  <div class="field">
    <label>Jouw naam (installateur)</label>
    <input type="text" id="setup-naam" placeholder="Voornaam achternaam">
  </div>
  <button class="setup-btn" onclick="startApp()">Starten →</button>

  <div style="margin-top:2rem;padding:14px;background:var(--gray-50);border-radius:var(--radius);font-size:13px;color:var(--gray-400);line-height:1.6">
    <strong style="color:var(--gray-600)">⚙️ Eenmalige instelling nodig</strong><br>
    Voor het versturen van e-mail via EmailJS heb je een gratis account nodig op <strong>emailjs.com</strong>. Vervang in de code de waarden <code>YOUR_PUBLIC_KEY</code>, <code>YOUR_SERVICE_ID</code> en <code>YOUR_TEMPLATE_ID</code> door jouw eigen gegevens. Zie de instructies onderaan dit bestand.
  </div>
</div>

<!-- MAIN APP -->
<div id="main-app" style="display:none">

  <!-- Header -->
  <div class="header">
    <div class="header-top">
      <div class="header-logo">WBP Oortvliet</div>
      <div class="header-title" id="header-title">Gegevens</div>
    </div>
    <div class="progress-wrap">
      <div class="progress-bar"><div class="progress-fill" id="progress-fill" style="width:16%"></div></div>
      <div class="step-info">
        <span class="step-name" id="step-name">Stap 1 van 6</span>
        <span class="step-count" id="step-count"></span>
      </div>
    </div>
  </div>

  <!-- Step 1: Gegevens -->
  <div class="step active" id="step-1">
    <div class="section">
      <div class="section-title">Projectgegevens</div>
      <div class="field"><label>Project / klant</label><input type="text" id="klant" placeholder="Naam klant of project"></div>
      <div class="field"><label>Ordernummer WBP</label><input type="text" id="order" placeholder="WBP-0000"></div>
      <div class="field"><label>Datum oplevering</label><input type="date" id="datum"></div>
      <div class="field"><label>Aannemer</label><input type="text" id="aannemer" placeholder="Bedrijfsnaam"></div>
      <div class="field"><label>Opdrachtgever aanwezig?</label>
        <select id="opdrachtgever"><option value="">Kies...</option><option>Ja</option><option>Nee</option></select>
      </div>
    </div>
    <div class="nav-bar">
      <button class="btn-primary" onclick="goStep(2)">Volgende →</button>
    </div>
  </div>

  <!-- Step 2: Checklist -->
  <div class="step" id="step-2">
    <div class="legend">
      <div class="leg"><div class="leg-dot" style="background:var(--green)"></div>OK</div>
      <div class="leg"><div class="leg-dot" style="background:var(--red)"></div>Niet OK</div>
      <div class="leg"><div class="leg-dot" style="background:var(--amber)"></div>Aandachtspunt</div>
    </div>
    <div id="checklist-container"></div>
    <div class="nav-bar">
      <button class="btn-secondary" onclick="goStep(1)">←</button>
      <button class="btn-primary" onclick="goStep(3)">Volgende →</button>
    </div>
  </div>

  <!-- Step 3: Photos -->
  <div class="step" id="step-3">
    <div style="padding:16px 20px 4px;font-size:14px;color:var(--gray-400)">Tik op een vak om een foto te maken.</div>
    <div class="photo-grid" id="photo-grid"></div>
    <div class="nav-bar">
      <button class="btn-secondary" onclick="goStep(2)">←</button>
      <button class="btn-primary" onclick="goStep(4)">Volgende →</button>
    </div>
  </div>

  <!-- Step 4: Signatures -->
  <div class="step" id="step-4">
    <div class="section">
      <div class="section-title">Opmerkingen / afspraken</div>
      <div class="field"><textarea id="opmerkingen" placeholder="Noteer hier eventuele afspraken of restpunten..."></textarea></div>
    </div>
    <div class="section">
      <div class="section-title">Handtekening opdrachtgever</div>
      <div class="field"><input type="text" id="naam-opdrachtgever" placeholder="Naam opdrachtgever"></div>
    </div>
    <div class="sig-wrap">
      <canvas class="sig-canvas" id="sig-opdrachtgever"></canvas>
      <div style="display:flex;justify-content:space-between;align-items:center;margin-top:5px">
        <span class="sig-hint">Teken met vinger of stylus</span>
        <button class="sig-clear-btn" onclick="clearSig('sig-opdrachtgever')">✕ Wissen</button>
      </div>
    </div>
    <div class="section">
      <div class="section-title">Handtekening uitvoerder</div>
      <div class="field"><input type="text" id="naam-uitvoerder" placeholder="Naam uitvoerder"></div>
    </div>
    <div class="sig-wrap">
      <canvas class="sig-canvas" id="sig-uitvoerder"></canvas>
      <div style="display:flex;justify-content:space-between;align-items:center;margin-top:5px">
        <span class="sig-hint">Teken met vinger of stylus</span>
        <button class="sig-clear-btn" onclick="clearSig('sig-uitvoerder')">✕ Wissen</button>
      </div>
    </div>
    <div class="nav-bar">
      <button class="btn-secondary" onclick="goStep(3)">←</button>
      <button class="btn-primary" onclick="goStep(5)">Bekijk overzicht →</button>
    </div>
  </div>

  <!-- Step 5: Overzicht -->
  <div class="step" id="step-5">
    <div style="padding:16px 20px 12px;font-size:14px;color:var(--gray-400)">Controleer alles voor verzending.</div>
    <div id="overzicht-content"></div>
    <div class="nav-bar">
      <button class="btn-secondary" onclick="goStep(4)">←</button>
      <button class="btn-primary" onclick="submitForm()">Versturen ✓</button>
    </div>
  </div>

  <!-- Step 6: Done -->
  <div class="step" id="step-6">
    <div id="sending-view" class="center-screen">
      <div class="spinner"></div>
      <div style="font-size:16px;font-weight:600;color:var(--gray-900)">Rapport wordt verstuurd...</div>
      <div style="font-size:14px;color:var(--gray-400);margin-top:6px">Claude stelt de samenvatting op</div>
    </div>
    <div id="done-view" class="center-screen" style="display:none">
      <div class="done-icon">✓</div>
      <div style="font-size:20px;font-weight:700;color:var(--gray-900)">Verstuurd!</div>
      <div style="font-size:14px;color:var(--gray-400);margin-top:4px">Rapport is verzonden naar baderie@wbpoortvliet.nl</div>
      <div class="ai-card">
        <div class="ai-card-title">Samenvatting door Claude</div>
        <div id="ai-summary">Laden...</div>
      </div>
      <button class="btn-primary" style="margin-top:1.5rem;width:100%" onclick="nieuwRapport()">Nieuw rapport starten</button>
    </div>
  </div>

</div><!-- /main-app -->
</div><!-- /app -->

<script>
// ============================================================
// EMAILJS CONFIGURATIE
// Stap 1: Maak gratis account op https://emailjs.com
// Stap 2: Maak een Email Service aan (Gmail werkt goed)
// Stap 3: Maak een Email Template aan met variabelen zoals hieronder
// Stap 4: Vervang de drie waarden hieronder
// ============================================================
const EMAILJS_PUBLIC_KEY  = 'VVXTaM0RjM-x8Njve';
const EMAILJS_SERVICE_ID  = 'service_jyohpkp';
const EMAILJS_TEMPLATE_ID = 'template_rf04x57';

// EmailJS template variabelen die je kunt gebruiken:
// {{to_email}}     → baderie@wbpoortvliet.nl
// {{subject}}      → onderwerp
// {{klant}}        → klantnaam
// {{order}}        → ordernummer
// {{datum}}        → datum
// {{opleveraar}}   → naam installateur
// {{status}}       → Goedgekeurd / Goedgekeurd met punten / Afgekeurd
// {{samenvatting}} → AI samenvatting
// {{checklist}}    → volledige checklijst tekst
// {{opmerkingen}}  → opmerkingen
// ============================================================

const ONTVANGER = 'baderie@wbpoortvliet.nl';

const checkItems = [
  'Tegelwerk wanden','Tegelwerk vloer','Voegwerk','Kitnaden (nat/droog)',
  'Douche / bad (montage)','Douchegoot / afvoer','Afschot & waterafvoer test',
  'Kranen & bediening','Wastafel(meubel)','Toilet (spoeling/afwerking)',
  'Spiegel / accessoires','Verlichting','Ventilatie',
  'Elektra (stopcontacten/schakelaars)','Verwarming (radiator/vloerverwarming)',
  'Schoonmaak & opleverstaat','Schade huis en haard'
];
const photoNames = ['Meubel','Douche','Toilet','Bad','Algemeen aanzicht'];

const checkData = {};
const photoData = {};
let installateurNaam = '';

// Init
checkItems.forEach(i => checkData[i] = { status: '', note: '' });
photoNames.forEach(n => photoData[n] = null);

function startApp() {
  const naam = document.getElementById('setup-naam').value.trim();
  if (!naam) { alert('Vul eerst je naam in.'); return; }
  installateurNaam = naam;
  document.getElementById('setup-screen').style.display = 'none';
  document.getElementById('main-app').style.display = 'block';
  buildChecklist();
  buildPhotos();
  // Set today as default date
  const t = new Date();
  const y = t.getFullYear(), m = String(t.getMonth()+1).padStart(2,'0'), d = String(t.getDate()).padStart(2,'0');
  document.getElementById('datum').value = `${y}-${m}-${d}`;
  document.getElementById('naam-uitvoerder').value = naam;
}

function buildChecklist() {
  const c = document.getElementById('checklist-container');
  c.innerHTML = '';
  checkItems.forEach(item => {
    const s = checkData[item].status;
    const row = document.createElement('div');
    row.className = 'check-row';
    row.innerHTML = `
      <div class="check-label">${item}</div>
      <div class="status-btns">
        <button class="sbtn ok${s==='ok'?' active':''}" onclick="setStatus('${item}','ok',this)" title="OK">✓</button>
        <button class="sbtn nok${s==='nok'?' active':''}" onclick="setStatus('${item}','nok',this)" title="Niet OK">✗</button>
        <button class="sbtn pm${s==='pm'?' active':''}" onclick="setStatus('${item}','pm',this)" title="Punt">!</button>
      </div>
      <input class="note-input" type="text" placeholder="Opmerking" value="${checkData[item].note||''}" oninput="checkData['${item}'].note=this.value">
    `;
    c.appendChild(row);
  });
}

function setStatus(item, status, btn) {
  btn.closest('.check-row').querySelectorAll('.sbtn').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
  checkData[item].status = status;
}

function buildPhotos() {
  const g = document.getElementById('photo-grid');
  g.innerHTML = '';
  photoNames.forEach(name => {
    const card = document.createElement('div');
    card.className = 'photo-card' + (photoData[name] ? ' taken' : '');
    card.id = 'pc-' + name;
    if (photoData[name]) {
      card.innerHTML = `<img src="${photoData[name]}" alt="${name}"><div class="taken-badge">✓</div><input type="file" accept="image/*" capture="environment" onchange="handlePhoto('${name}',this)">`;
    } else {
      card.innerHTML = `<div class="photo-icon">📷</div><div class="photo-label">${name}</div><input type="file" accept="image/*" capture="environment" onchange="handlePhoto('${name}',this)">`;
    }
    g.appendChild(card);
  });
}

function handlePhoto(name, input) {
  if (!input.files[0]) return;
  const reader = new FileReader();
  reader.onload = e => { photoData[name] = e.target.result; buildPhotos(); };
  reader.readAsDataURL(input.files[0]);
}

const sigCtx = {};
function initSig(id) {
  const canvas = document.getElementById(id);
  if (!canvas || sigCtx[id]) return;
  const dpr = window.devicePixelRatio || 1;
  canvas.width = canvas.offsetWidth * dpr;
  canvas.height = 150 * dpr;
  const ctx = canvas.getContext('2d');
  ctx.scale(dpr, dpr);
  sigCtx[id] = { ctx, drawing: false };
  const pos = e => {
    const r = canvas.getBoundingClientRect();
    const src = e.touches ? e.touches[0] : e;
    return { x: src.clientX - r.left, y: src.clientY - r.top };
  };
  canvas.addEventListener('mousedown', e => { sigCtx[id].drawing = true; const p = pos(e); ctx.beginPath(); ctx.moveTo(p.x, p.y); });
  canvas.addEventListener('mousemove', e => { if (!sigCtx[id].drawing) return; const p = pos(e); ctx.lineTo(p.x, p.y); ctx.strokeStyle='#1C1C1A'; ctx.lineWidth=2; ctx.lineCap='round'; ctx.lineJoin='round'; ctx.stroke(); canvas.classList.add('signed'); });
  canvas.addEventListener('mouseup', () => sigCtx[id].drawing = false);
  canvas.addEventListener('touchstart', e => { e.preventDefault(); sigCtx[id].drawing = true; const p = pos(e); ctx.beginPath(); ctx.moveTo(p.x, p.y); }, {passive:false});
  canvas.addEventListener('touchmove', e => { e.preventDefault(); if (!sigCtx[id].drawing) return; const p = pos(e); ctx.lineTo(p.x, p.y); ctx.strokeStyle='#1C1C1A'; ctx.lineWidth=2; ctx.lineCap='round'; ctx.lineJoin='round'; ctx.stroke(); canvas.classList.add('signed'); }, {passive:false});
  canvas.addEventListener('touchend', () => sigCtx[id].drawing = false);
}

function clearSig(id) {
  const canvas = document.getElementById(id);
  canvas.getContext('2d').clearRect(0, 0, canvas.width, canvas.height);
  canvas.classList.remove('signed');
}

const stepMeta = [
  null,
  { title: 'Gegevens', name: 'Stap 1 van 6', pct: 16 },
  { title: 'Checklist', name: 'Stap 2 van 6', pct: 33 },
  { title: "Foto's", name: 'Stap 3 van 6', pct: 50 },
  { title: 'Handtekeningen', name: 'Stap 4 van 6', pct: 67 },
  { title: 'Overzicht', name: 'Stap 5 van 6', pct: 83 },
  { title: 'Klaar', name: 'Stap 6 van 6', pct: 100 },
];

function goStep(n) {
  document.querySelectorAll('.step').forEach(s => s.classList.remove('active'));
  document.getElementById('step-' + n).classList.add('active');
  const m = stepMeta[n];
  document.getElementById('header-title').textContent = m.title;
  document.getElementById('step-name').textContent = m.name;
  document.getElementById('progress-fill').style.width = m.pct + '%';
  const ok = checkItems.filter(i => checkData[i].status === 'ok').length;
  const nok = checkItems.filter(i => checkData[i].status === 'nok').length;
  const pm = checkItems.filter(i => checkData[i].status === 'pm').length;
  document.getElementById('step-count').textContent = n === 2 ? `${ok}✓ ${nok}✗ ${pm}!` : '';
  if (n === 4) setTimeout(() => { initSig('sig-opdrachtgever'); initSig('sig-uitvoerder'); }, 80);
  if (n === 5) buildOverzicht();
  window.scrollTo(0, 0);
}

function tagHtml(s) {
  if (s === 'ok')  return '<span class="tag tag-ok">✓ OK</span>';
  if (s === 'nok') return '<span class="tag tag-nok">✗ Niet OK</span>';
  if (s === 'pm')  return '<span class="tag tag-pm">! Punt</span>';
  return '<span class="tag tag-neu">—</span>';
}

function buildOverzicht() {
  const ok  = checkItems.filter(i => checkData[i].status === 'ok').length;
  const nok = checkItems.filter(i => checkData[i].status === 'nok').length;
  const pm  = checkItems.filter(i => checkData[i].status === 'pm').length;
  let pillCls = 'pill-ok', pillTxt = 'Goedgekeurd';
  if (nok > 0) { pillCls = 'pill-nok'; pillTxt = 'Afgekeurd'; }
  else if (pm > 0) { pillCls = 'pill-pm'; pillTxt = 'Goedgekeurd met punten'; }

  const datum = document.getElementById('datum').value;
  const datumTxt = datum ? new Date(datum).toLocaleDateString('nl-NL', {day:'numeric',month:'long',year:'numeric'}) : '—';

  let checkRows = checkItems.map(item => {
    const d = checkData[item];
    return `<div class="check-item">
      <span style="flex:1;color:var(--gray-900)">${item}</span>
      ${tagHtml(d.status)}
      ${d.note ? `<span style="font-size:12px;color:var(--gray-400);margin-left:6px">${d.note}</span>` : ''}
    </div>`;
  }).join('');

  let fotoItems = photoNames.map(n =>
    photoData[n]
      ? `<img class="foto-thumb" src="${photoData[n]}" alt="${n}" title="${n}">`
      : `<div class="foto-empty">${n}</div>`
  ).join('');

  document.getElementById('overzicht-content').innerHTML = `
    <div class="ov-card">
      <div class="ov-head">📋 Projectgegevens</div>
      <div class="ov-row"><span class="ov-key">Klant</span><span class="ov-val">${document.getElementById('klant').value||'—'}</span></div>
      <div class="ov-row"><span class="ov-key">Order</span><span class="ov-val">${document.getElementById('order').value||'—'}</span></div>
      <div class="ov-row"><span class="ov-key">Datum</span><span class="ov-val">${datumTxt}</span></div>
      <div class="ov-row"><span class="ov-key">Installateur</span><span class="ov-val">${installateurNaam}</span></div>
      <div class="ov-row"><span class="ov-key">Aannemer</span><span class="ov-val">${document.getElementById('aannemer').value||'—'}</span></div>
      <div class="ov-row"><span class="ov-key">Opdrachtgever aanwezig</span><span class="ov-val">${document.getElementById('opdrachtgever').value||'—'}</span></div>
    </div>
    <div class="ov-card">
      <div class="ov-head">✅ Checklist <span style="margin-left:auto"><span class="pill ${pillCls}">${pillTxt}</span></span></div>
      <div class="ov-row">
        <span class="ov-key">Score</span>
        <span class="ov-val" style="display:flex;gap:4px;flex-wrap:wrap">
          <span class="tag tag-ok">${ok} OK</span>
          <span class="tag tag-pm">${pm} punt</span>
          <span class="tag tag-nok">${nok} niet OK</span>
        </span>
      </div>
      ${checkRows}
    </div>
    <div class="ov-card">
      <div class="ov-head">📷 Foto's (${photoNames.filter(p=>photoData[p]).length} van ${photoNames.length})</div>
      <div class="foto-row">${fotoItems}</div>
    </div>
    <div class="ov-card">
      <div class="ov-head">📝 Opmerkingen</div>
      <div class="ov-row"><span style="font-size:14px">${document.getElementById('opmerkingen').value||'Geen opmerkingen'}</span></div>
    </div>
    <div class="ov-card">
      <div class="ov-head">✍️ Handtekeningen</div>
      <div class="ov-row"><span class="ov-key">Opdrachtgever</span><span class="ov-val">${document.getElementById('naam-opdrachtgever').value||'—'}</span></div>
      <div class="ov-row"><span class="ov-key">Uitvoerder</span><span class="ov-val">${document.getElementById('naam-uitvoerder').value||'—'}</span></div>
    </div>
  `;
}

async function submitForm() {
  goStep(6);
  document.getElementById('sending-view').style.display = 'flex';
  document.getElementById('done-view').style.display = 'none';

  const ok  = checkItems.filter(i => checkData[i].status === 'ok');
  const nok = checkItems.filter(i => checkData[i].status === 'nok');
  const pm  = checkItems.filter(i => checkData[i].status === 'pm');
  const fotosMade = photoNames.filter(p => photoData[p]);
  let statusTxt = nok.length > 0 ? 'Afgekeurd' : pm.length > 0 ? 'Goedgekeurd met punten' : 'Goedgekeurd';

  const checklistTxt = checkItems.map(i => {
    const s = checkData[i].status === 'ok' ? '✓' : checkData[i].status === 'nok' ? '✗' : checkData[i].status === 'pm' ? '!' : '-';
    return `${s} ${i}${checkData[i].note ? ': '+checkData[i].note : ''}`;
  }).join('\n');

  // 1. Vraag AI samenvatting
  let samenvatting = 'Rapport verwerkt.';
  try {
    const res = await fetch('https://api.anthropic.com/v1/messages', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({
        model: 'claude-sonnet-4-20250514',
        max_tokens: 1000,
        messages: [{ role: 'user', content: `Je bent een bouwopzichter bij WBP Oortvliet. Schrijf een professionele Nederlandse samenvatting van dit opleverrapport badkamer.

Klant: ${document.getElementById('klant').value||'onbekend'}
Order: ${document.getElementById('order').value||'-'}
Datum: ${document.getElementById('datum').value||'-'}
Installateur: ${installateurNaam}

Checklist:
- OK (${ok.length}): ${ok.join(', ')||'geen'}
- Niet OK (${nok.length}): ${nok.join(', ')||'geen'}
- Aandachtspunten (${pm.length}): ${pm.join(', ')||'geen'}

Foto's gemaakt: ${fotosMade.join(', ')||'geen'}
Opmerkingen: ${document.getElementById('opmerkingen').value||'geen'}

Schrijf 3-5 zinnen. Benoem de opleverstatus: ${statusTxt}. Wees concreet en zakelijk.` }]
      })
    });
    const data = await res.json();
    samenvatting = data.content?.map(b => b.text||'').join('') || samenvatting;
  } catch(e) { /* fallback */ }

  // 2. Verstuur e-mail via EmailJS
  try {
    emailjs.init(EMAILJS_PUBLIC_KEY);
    await emailjs.send(EMAILJS_SERVICE_ID, EMAILJS_TEMPLATE_ID, {
      to_email:     ONTVANGER,
      subject:      `Opleverrapport badkamer – ${document.getElementById('klant').value||'onbekend'} – ${statusTxt}`,
      klant:        document.getElementById('klant').value || '—',
      order:        document.getElementById('order').value || '—',
      datum:        document.getElementById('datum').value || '—',
      opleveraar:   installateurNaam,
      aannemer:     document.getElementById('aannemer').value || '—',
      status:       statusTxt,
      samenvatting: samenvatting,
      checklist:    checklistTxt,
      opmerkingen:  document.getElementById('opmerkingen').value || 'Geen',
    });
  } catch(e) {
    console.warn('EmailJS niet geconfigureerd of fout:', e);
  }

  // 3. Toon resultaat
  document.getElementById('ai-summary').textContent = samenvatting;
  document.getElementById('sending-view').style.display = 'none';
  document.getElementById('done-view').style.display = 'flex';
}

function nieuwRapport() {
  checkItems.forEach(k => checkData[k] = { status: '', note: '' });
  photoNames.forEach(k => photoData[k] = null);
  Object.keys(sigCtx).forEach(id => { delete sigCtx[id]; });
  ['klant','order','opmerkingen','naam-opdrachtgever','naam-uitvoerder'].forEach(id => {
    const el = document.getElementById(id); if (el) el.value = '';
  });
  document.getElementById('aannemer').value = '';
  document.getElementById('opdrachtgever').value = '';
  document.getElementById('naam-uitvoerder').value = installateurNaam;
  const t = new Date();
  const y = t.getFullYear(), m = String(t.getMonth()+1).padStart(2,'0'), d = String(t.getDate()).padStart(2,'0');
  document.getElementById('datum').value = `${y}-${m}-${d}`;
  document.getElementById('sending-view').style.display = 'flex';
  document.getElementById('done-view').style.display = 'none';
  buildChecklist(); buildPhotos();
  goStep(1);
}
</script>

<!--
=================================================================
INSTALLATIE-INSTRUCTIES
=================================================================

STAP 1 — Gratis EmailJS account aanmaken
  1. Ga naar https://emailjs.com en maak een gratis account
  2. Klik op "Add New Service" en koppel je Gmail of ander e-mailadres
  3. Noteer je Service ID (bijv. service_abc123)

STAP 2 — E-mail template aanmaken
  1. Ga naar "Email Templates" > "Create New Template"
  2. Stel in:
     - To email: baderie@wbpoortvliet.nl
     - Subject:  {{subject}}
     - Body (tekst):
       Opleverrapport Badkamer

       Klant:       {{klant}}
       Order:       {{order}}
       Datum:       {{datum}}
       Installateur: {{opleveraar}}
       Status:      {{status}}

       Samenvatting:
       {{samenvatting}}

       Checklist:
       {{checklist}}

       Opmerkingen:
       {{opmerkingen}}

  3. Noteer je Template ID (bijv. template_xyz789)

STAP 3 — API key ophalen
  1. Ga naar Account > API Keys
  2. Kopieer je Public Key

STAP 4 — Dit bestand aanpassen
  Vervang bovenin de code:
    YOUR_PUBLIC_KEY   → jouw Public Key
    YOUR_SERVICE_ID   → jouw Service ID
    YOUR_TEMPLATE_ID  → jouw Template ID

STAP 5 — Online zetten via Netlify (gratis, 2 minuten)
  1. Ga naar https://netlify.com en maak gratis account
  2. Klik "Add new site" > "Deploy manually"
  3. Sleep dit HTML bestand naar het upload vlak
  4. Netlify geeft je een link, bijv: https://jolly-fox-123.netlify.app
  5. Stuur die link naar je installateurs — klaar!

=================================================================
-->
</body>
</html>
