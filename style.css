:root{
  --bg:#f4f6f9; --card:#fff; --text:#0b1220; --muted:#5b6475;
  --primary:#001f3f; --primary2:#003366; --accent:#ffd700;
  --border:rgba(0,0,0,.08); --shadow:0 10px 25px rgba(0,0,0,.10);
}
[data-theme="dark"]{
  --bg:#0b1020; --card:#121a33; --text:#eef2ff; --muted:#b9c0d4;
  --primary:#0e204d; --primary2:#173065; --accent:#ffd700;
  --border:rgba(255,255,255,.10); --shadow:0 12px 30px rgba(0,0,0,.35);
}
*{box-sizing:border-box;margin:0;padding:0;font-family:system-ui,Segoe UI,Arial}
body{background:var(--bg);color:var(--text);min-height:100vh}
a{text-decoration:none;color:inherit}
.header{background:linear-gradient(135deg,var(--primary),var(--primary2));color:#fff;
  padding:16px;position:sticky;top:0;z-index:10;box-shadow:var(--shadow)}
.header-inner{max-width:1100px;margin:0 auto;display:flex;align-items:center;gap:12px}
.brand h1{font-size:18px}
.brand p{font-size:12px;opacity:.9;letter-spacing:1.4px}
.navbar{margin-left:auto;display:flex;align-items:center;gap:10px}
.navbar a{padding:8px 10px;border-radius:12px;font-weight:700}
.navbar a:hover{background:rgba(255,255,255,.12)}
.icon-btn{border:1px solid rgba(255,255,255,.25);background:rgba(255,255,255,.10);
  color:#fff;padding:8px 10px;border-radius:12px;cursor:pointer;font-weight:800}
.hamburger{display:none}
.mobile-menu{display:none;max-width:1100px;margin:10px auto 0;gap:8px;flex-wrap:wrap;padding:0 16px}
.mobile-menu a{background:rgba(255,255,255,.12);color:#fff;padding:10px 12px;border-radius:12px;font-weight:800}
.container{max-width:1100px;margin:0 auto;padding:24px 16px}
.card{background:var(--card);border:1px solid var(--border);border-radius:18px;
  box-shadow:var(--shadow);padding:18px}
.grid{display:grid;grid-template-columns:repeat(12,1fr);gap:16px}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:10px;
  padding:12px 14px;border-radius:14px;border:1px solid var(--border);
  background:linear-gradient(135deg,var(--primary),var(--primary2));color:#fff;
  font-weight:900;cursor:pointer}
.btn.secondary{background:transparent;color:var(--text)}
.btn.small{padding:9px 10px;border-radius:12px;font-size:14px}
.row{display:flex;gap:12px;flex-wrap:wrap;align-items:center}
.muted{color:var(--muted)}
.hero{border-radius:22px;overflow:hidden;
  background:linear-gradient(135deg,rgba(0,0,0,.55),rgba(0,0,0,.35)),
  url("https://images.unsplash.com/photo-1509062522246-3755977927d7?auto=format&fit=crop&w=1600&q=60");
  background-size:cover;background-position:center;min-height:420px;
  display:flex;align-items:center;padding:28px}
.hero-inner{max-width:740px;color:#fff}
.hero h2{font-size:42px;line-height:1.05;margin-bottom:10px}
.features{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:16px}
.feature{padding:16px;border-radius:18px;background:rgba(255,255,255,.92);
  border:1px solid rgba(255,255,255,.35)}
[data-theme="dark"] .feature{background:rgba(18,26,51,.85);border:1px solid rgba(255,255,255,.12)}
.counter-wrap{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.counter{text-align:center}
.counter .num{font-size:34px;font-weight:950;color:var(--primary2)}
.gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
.gallery img{width:100%;height:210px;object-fit:cover;border-radius:16px;border:1px solid var(--border);cursor:pointer}
.modal{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(0,0,0,.75);z-index:50}
.modal.open{display:flex}
.modal img{max-width:min(92vw,1000px);max-height:86vh;border-radius:18px}
.slider{position:relative;overflow:hidden;border-radius:18px}
.slide{display:none;padding:18px}
.slide.active{display:block}
.form{display:grid;gap:10px}
.input, select, textarea{width:100%;padding:12px;border-radius:14px;border:1px solid var(--border);
  background:var(--card);color:var(--text)}
table{width:100%;border-collapse:separate;border-spacing:0 10px}
th{font-size:12px;color:var(--muted);text-align:left;padding:0 10px}
td{background:var(--card);border:1px solid var(--border);padding:12px 10px}
td:first-child{border-radius:14px 0 0 14px}
td:last-child{border-radius:0 14px 14px 0}
.footer{margin-top:24px;padding:18px 16px;color:#fff;
  background:linear-gradient(135deg,var(--primary2),var(--primary))}
.footer-inner{max-width:1100px;margin:0 auto;display:flex;justify-content:space-between;gap:10px;flex-wrap:wrap}
@media(max-width:900px){
  .features,.counter-wrap,.gallery{grid-template-columns:1fr}
  .navbar{display:none}.hamburger{display:inline-flex}
  .mobile-menu{display:flex}
  .hero h2{font-size:32px}
}