<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NextVision Digital | شريكك في النجاح الرقمي</title>
<link rel="icon" href="https://www.designarena.ai/u/6e32d12c-fbcc-4876-b8bd-974e1b3bd25b">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800;900&family=Tajawal:wght@400;500;700;800&display=swap" rel="stylesheet">
<style>
:root{
--blue:#0b46e1; --blue2:#0a2fa3; --blue-dark:#0a1f5e; --navy:#0b183a;
--green:#14c536; --green2:#0a9c26; --green-dark:#06721b;
--bg:#f4f7fe; --card:#ffffff; --ink:#0f1e42; --muted:#5d6d90; --line:#e3e9f7;
--gold:#ffb800; --red:#ff3b3b;
--grad-blue:linear-gradient(135deg,#1a5bff 0%,#0a2fa3 100%);
--grad-green:linear-gradient(135deg,#22e04a 0%,#0a8a24 100%);
--grad-mix:linear-gradient(135deg,#1a5bff 0%,#0abe3a 100%);
--shadow:0 20px 50px rgba(11,70,225,.12);
--shadow2:0 10px 30px rgba(0,0,0,.08);
--r:20px;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:'Cairo','Tajawal',sans-serif;background:var(--bg);color:var(--ink);overflow-x:hidden;line-height:1.7}
a{text-decoration:none;color:inherit}
img{max-width:100%;display:block}
button{font-family:inherit;cursor:pointer}
input,select,textarea{font-family:inherit}
::-webkit-scrollbar{width:10px}::-webkit-scrollbar-track{background:#eef2ff}::-webkit-scrollbar-thumb{background:linear-gradient(var(--blue),var(--green));border-radius:99px}
#progress{position:fixed;top:0;right:0;height:4px;width:0;background:var(--grad-mix);z-index:9999;border-radius:0 0 0 10px}
.topbar{background:linear-gradient(90deg,#081b58,#0b46e1,#0a9c26);color:#fff;font-size:.82rem;padding:8px 0;position:relative;z-index:60}
.topbar .wrap{max-width:1240px;margin:auto;padding:0 20px;display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap}
.topbar span{display:inline-flex;align-items:center;gap:7px}
.topbar .dot{width:8px;height:8px;background:#22ff66;border-radius:50%;box-shadow:0 0 10px #22ff66;animation:blink 1.5s infinite}
@keyframes blink{50%{opacity:.4}}
header{position:sticky;top:0;z-index:100;background:rgba(255,255,255,.9);backdrop-filter:blur(16px);border-bottom:1px solid var(--line);transition:.3s}
header.scrolled{box-shadow:0 10px 30px rgba(0,0,0,.1)}
.nav{max-width:1240px;margin:auto;padding:12px 20px;display:flex;align-items:center;justify-content:space-between;gap:16px}
.brand{display:flex;align-items:center;gap:12px}
.brand img{width:56px;height:56px;border-radius:50%;object-fit:cover;border:3px solid transparent;background:linear-gradient(#fff,#fff) padding-box,linear-gradient(135deg,var(--blue),var(--green)) border-box;box-shadow:0 6px 18px rgba(0,0,0,.15)}
.brand b{font-size:1.1rem;line-height:1.1;display:block}.brand b i{font-style:normal;color:var(--green)}.brand b em{font-style:normal;color:var(--blue)}
.brand small{letter-spacing:5px;font-size:.68rem;color:var(--blue2);font-weight:800}
.links{display:flex;gap:6px;align-items:center}
.links a{padding:9px 15px;border-radius:12px;font-weight:700;font-size:.92rem;color:#2a3a65;transition:.25s}
.links a:hover,.links a.active{background:#eef3ff;color:var(--blue)}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:9px;border:none;border-radius:14px;padding:13px 24px;font-weight:800;font-size:.95rem;transition:.25s;position:relative;overflow:hidden}
.btn-wa{background:var(--grad-green);color:#fff;box-shadow:0 10px 25px rgba(20,197,54,.35)}
.btn-wa:hover{transform:translateY(-2px);box-shadow:0 15px 35px rgba(20,197,54,.45)}
.btn-blue{background:var(--grad-blue);color:#fff;box-shadow:0 10px 25px rgba(11,70,225,.35)}
.btn-blue:hover{transform:translateY(-2px)}
.btn-ghost{background:#fff;border:2px solid var(--line);color:var(--ink)}
.btn-ghost:hover{border-color:var(--blue);color:var(--blue)}
.burger{display:none;width:48px;height:48px;border-radius:14px;border:1px solid var(--line);background:#fff;font-size:1.2rem}
.hero{position:relative;overflow:hidden;background:radial-gradient(900px 500px at 85% 10%,rgba(26,91,255,.15),transparent),radial-gradient(700px 500px at 10% 90%,rgba(20,197,54,.15),transparent),linear-gradient(180deg,#fff 0%,#eef3ff 100%);padding:34px 0 60px}
.hero .wrap{max-width:1240px;margin:auto;padding:0 20px;display:grid;grid-template-columns:1.05fr .95fr;gap:36px;align-items:center}
.badge{display:inline-flex;align-items:center;gap:8px;background:#fff;border:1px solid var(--line);padding:7px 14px;border-radius:99px;font-size:.82rem;font-weight:800;color:var(--blue2);box-shadow:var(--shadow2)}
.badge .pulse{width:10px;height:10px;background:var(--green);border-radius:50%;position:relative}.badge .pulse::after{content:'';position:absolute;inset:-5px;border:2px solid var(--green);border-radius:50%;animation:pulse 1.5s infinite}
@keyframes pulse{to{transform:scale(1.4);opacity:0}}
.hero h1{font-size:clamp(2rem,4.5vw,3.6rem);line-height:1.25;font-weight:900;margin:18px 0 12px}
.hero h1 .grad{background:var(--grad-mix);-webkit-background-clip:text;background-clip:text;color:transparent}
.hero h1 .under{position:relative;white-space:nowrap}.hero h1 .under::after{content:'';position:absolute;bottom:6px;right:0;left:0;height:12px;background:rgba(20,197,54,.25);z-index:-1;border-radius:6px;transform:skewX(-12deg)}
.hero p.sub{color:var(--muted);font-size:1.05rem;max-width:560px}
.hero-cta{display:flex;gap:12px;margin:22px 0;flex-wrap:wrap}
.trust{display:flex;gap:18px;flex-wrap:wrap;margin-top:10px}
.trust .t{display:flex;gap:10px;align-items:center;background:#fff;border:1px solid var(--line);padding:10px 16px;border-radius:16px;box-shadow:var(--shadow2)}
.trust .t strong{font-size:1.1rem;display:block;line-height:1}.trust .t span{font-size:.78rem;color:var(--muted)}
.stats-row{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-top:20px}
.stat{background:linear-gradient(180deg,#0b183a,#0a2fa3);color:#fff;border-radius:18px;padding:16px;text-align:center;position:relative;overflow:hidden}
.stat::after{content:'';position:absolute;top:-30px;left:-30px;width:90px;height:90px;background:rgba(255,255,255,.08);border-radius:50%}
.stat b{font-size:1.5rem;display:block}.stat span{font-size:.78rem;opacity:.85}
.hero-visual{position:relative;display:flex;justify-content:center;align-items:center;min-height:520px}
.ring{position:relative;width:min(440px,90vw);aspect-ratio:1;border-radius:50%;padding:14px;background:conic-gradient(from 20deg,var(--blue),#4da3ff,var(--green),#b6ff5e,var(--blue));box-shadow:0 30px 80px rgba(11,70,225,.25);animation:spinSlow 18s linear infinite}
@keyframes spinSlow{to{filter:hue-rotate(15deg)}}
.ring-inner{background:#fff;border-radius:50%;overflow:hidden;width:100%;height:100%;display:flex;align-items:center;justify-content:center;animation:spinRev 18s linear infinite}
@keyframes spinRev{to{transform:rotate(0)}}
.ring-inner img{width:92%;height:92%;object-fit:cover;border-radius:50%}
.float{position:absolute;background:#fff;border:1px solid var(--line);border-radius:16px;padding:10px 14px;box-shadow:0 15px 40px rgba(0,0,0,.14);display:flex;gap:10px;align-items:center;font-size:.82rem;font-weight:800;animation:float 3.5s ease-in-out infinite;z-index:3}
.float small{display:block;font-weight:600;color:var(--muted);font-size:.72rem}
.float .ic{width:42px;height:42px;border-radius:12px;display:grid;place-items:center;color:#fff;font-size:1.1rem;flex-shrink:0}
.f1{top:8%;right:0}.f2{bottom:18%;right:-10px;animation-delay:.8s}.f3{top:45%;left:-10px;animation-delay:1.6s}
@keyframes float{50%{transform:translateY(-12px)}}
.marquee{background:var(--navy);color:#fff;padding:14px 0;overflow:hidden;white-space:nowrap;position:relative}
.marquee-track{display:inline-flex;gap:34px;animation:mar 22s linear infinite;padding-inline:20px}
.marquee-track span{display:inline-flex;align-items:center;gap:10px;font-weight:800}
@keyframes mar{to{transform:translateX(50%)}}
section{padding:70px 0}.wrap2{max-width:1240px;margin:auto;padding:0 20px}
.sec-head{text-align:center;max-width:720px;margin:0 auto 36px}
.sec-head .kicker{display:inline-block;background:#e8f8ec;color:var(--green-dark);border:1px solid #b8e9c2;padding:6px 16px;border-radius:99px;font-weight:800;font-size:.8rem;margin-bottom:12px}
.sec-head .kicker.blue{background:#e8efff;color:var(--blue);border-color:#c2d2ff}
.sec-head h2{font-size:clamp(1.6rem,3vw,2.4rem);font-weight:900;line-height:1.4}
.sec-head p{color:var(--muted);margin-top:8px}
.filters{display:flex;gap:10px;justify-content:center;flex-wrap:wrap;margin-bottom:28px}
.filters button{border:1.5px solid var(--line);background:#fff;padding:10px 20px;border-radius:99px;font-weight:800;font-size:.88rem;transition:.25s}
.filters button.active,.filters button:hover{background:var(--ink);color:#fff;border-color:var(--ink)}
.grid6{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.scard{background:#fff;border:1px solid var(--line);border-radius:22px;padding:24px;position:relative;overflow:hidden;transition:.3s;display:flex;flex-direction:column}
.scard::before{content:'';position:absolute;top:0;right:0;left:0;height:5px;background:var(--gc,var(--grad-mix))}
.scard:hover{transform:translateY(-6px);box-shadow:var(--shadow)}
.scard .top{display:flex;justify-content:space-between;align-items:start;margin-bottom:14px}
.scard .icon{width:58px;height:58px;border-radius:16px;display:grid;place-items:center;font-size:1.5rem;color:#fff;background:var(--gc,var(--grad-mix));box-shadow:0 10px 20px rgba(0,0,0,.15)}
.scard h3{font-size:1.15rem;font-weight:900}.scard p{font-size:.9rem;color:var(--muted);margin:8px 0 12px}
.scard ul{list-style:none;margin:0 0 16px;display:grid;gap:7px;font-size:.85rem}
.scard ul li{display:flex;gap:8px;align-items:center}.scard ul li i{color:var(--green);font-size:.8rem}
.scard .price{margin-top:auto;display:flex;justify-content:space-between;align-items:center;background:#f6f8ff;border-radius:14px;padding:10px 14px}
.scard .price b{color:var(--blue)} .scard .row{display:flex;gap:8px;margin-top:12px}
.mini{flex:1;padding:10px;border-radius:12px;border:none;font-weight:800;font-size:.85rem}
.mini.o{background:#0f1e42;color:#fff}.mini.g{background:#e8f8ec;color:var(--green-dark)}
.calc{background:linear-gradient(135deg,#081b58 0%,#0b46e1 55%,#0a9c26 130%);border-radius:28px;padding:34px;color:#fff;position:relative;overflow:hidden;display:grid;grid-template-columns:1fr 1fr;gap:28px}
.calc::before{content:'';position:absolute;width:500px;height:500px;background:radial-gradient(circle,rgba(255,255,255,.15),transparent 70%);top:-150px;left:-150px}
.calc label{font-weight:800;font-size:.9rem;display:flex;justify-content:space-between;margin:16px 0 8px}
.calc label output{background:rgba(255,255,255,.2);padding:2px 12px;border-radius:99px}
.calc select,.calc input[type=text]{width:100%;padding:13px 15px;border-radius:14px;border:none;font-weight:700;color:var(--ink)}
input[type=range]{width:100%;accent-color:#22ff66;height:28px}
.calc-out{background:#fff;color:var(--ink);border-radius:22px;padding:24px;position:relative;z-index:1}
.calc-out .est{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin:16px 0}
.est div{background:#f3f6ff;border-radius:14px;padding:12px;text-align:center}
.est b{font-size:1.2rem;display:block;color:var(--blue)} .est span{font-size:.75rem;color:var(--muted)}
.store-bar{display:flex;gap:12px;flex-wrap:wrap;justify-content:space-between;align-items:center;margin-bottom:20px}
.search{display:flex;align-items:center;background:#fff;border:1.5px solid var(--line);border-radius:14px;padding:0 14px;flex:1;min-width:220px;max-width:380px}
.search input{border:none;outline:none;padding:13px 10px;width:100%;background:transparent;font-weight:700}
.pgrid{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
.pcard{background:#fff;border:1px solid var(--line);border-radius:20px;overflow:hidden;transition:.3s;display:flex;flex-direction:column}
.pcard:hover{transform:translateY(-5px);box-shadow:var(--shadow)}
.pcard .ph{height:130px;display:grid;place-items:center;font-size:3rem;color:#fff;position:relative}
.pcard .ph .stock{position:absolute;top:10px;right:10px;background:#fff;color:var(--green-dark);font-size:.7rem;font-weight:900;padding:4px 10px;border-radius:99px}
.pcard .pb{padding:16px}.pcard .pb h4{font-size:.95rem}.pcard .pb .pr{display:flex;align-items:center;gap:8px;margin:8px 0}.pcard .pb .pr b{font-size:1.15rem;color:var(--blue)}.pcard .pb .pr s{color:#9aa7c6;font-size:.85rem}
.add{width:100%;background:var(--ink);color:#fff;border:none;border-radius:12px;padding:11px;font-weight:800;transition:.25s}
.add:hover{background:var(--blue)}.add.added{background:var(--green)}
.topup-grid{display:grid;grid-template-columns:1fr 1fr;gap:22px;align-items:start}
.form-card{background:#fff;border:1px solid var(--line);border-radius:24px;padding:28px;box-shadow:var(--shadow2)}
.form-card h3{margin-bottom:6px}.field{margin:14px 0}.field label{display:block;font-weight:800;font-size:.88rem;margin-bottom:7px}
.field input,.field select,.field textarea{width:100%;border:1.5px solid var(--line);border-radius:14px;padding:13px 15px;font-weight:600;outline:none;transition:.2s;background:#fbfcff}
.field input:focus,.field select:focus,.field textarea:focus{border-color:var(--blue);box-shadow:0 0 0 4px rgba(11,70,225,.12);background:#fff}
.apps{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}
.app{border:2px solid var(--line);border-radius:14px;padding:10px;text-align:center;font-size:.8rem;font-weight:800;cursor:pointer;transition:.2s;background:#fff}
.app i{font-size:1.4rem;display:block;margin-bottom:4px}.app.sel{border-color:var(--green);background:#eefbef;transform:scale(1.03)}
.pay{display:flex;gap:10px;flex-wrap:wrap}.pay label{flex:1;min-width:120px;border:1.5px solid var(--line);border-radius:12px;padding:10px;text-align:center;font-weight:800;font-size:.85rem;cursor:pointer}.pay input{display:none}.pay label.sel{background:var(--ink);color:#fff;border-color:var(--ink)}
.courses{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.course{background:#fff;border-radius:22px;overflow:hidden;border:1px solid var(--line);transition:.3s;display:flex;flex-direction:column}
.course:hover{transform:translateY(-6px);box-shadow:var(--shadow)}
.course .ch{height:170px;position:relative;display:flex;align-items:flex-end;padding:18px;color:#fff;overflow:hidden}
.course .ch::after{content:'';position:absolute;inset:0;background:linear-gradient(180deg,transparent 20%,rgba(0,0,0,.75))}
.course .ch div{position:relative;z-index:1}.course .cb{padding:20px;flex:1;display:flex;flex-direction:column}
.meta{display:flex;gap:10px;flex-wrap:wrap;font-size:.75rem;color:var(--muted);margin:10px 0}
.meta span{background:#f2f5ff;padding:4px 10px;border-radius:99px;font-weight:700}
.results{background:var(--navy);color:#fff;border-radius:28px;padding:36px;position:relative;overflow:hidden}
.bars{display:grid;gap:14px;margin:20px 0}
.bar-row{display:grid;grid-template-columns:140px 1fr 70px;align-items:center;gap:12px;font-size:.85rem;font-weight:800}
.bar-bg{background:rgba(255,255,255,.15);border-radius:99px;height:14px;overflow:hidden}
.bar-fill{height:100%;border-radius:99px;width:0;transition:1.2s cubic-bezier(.2,.8,.2,1);background:linear-gradient(90deg,var(--blue),#4da3ff,var(--green))}
.testi{overflow:hidden;position:relative;border-radius:20px}
.testi-track{display:flex;transition:.5s}
.tcard{min-width:100%;background:#fff;color:var(--ink);border-radius:20px;padding:26px;display:flex;gap:16px;align-items:start}
.tcard img{width:58px;height:58px;border-radius:50%;object-fit:cover;flex-shrink:0}
.stars{color:var(--gold);font-size:.85rem}
.dots{display:flex;gap:8px;justify-content:center;margin-top:14px}.dots button{width:10px;height:10px;border-radius:99px;border:none;background:rgba(255,255,255,.4);transition:.3s}.dots button.on{width:32px;background:var(--green)}
.pricing{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.plan{background:#fff;border:2px solid var(--line);border-radius:24px;padding:28px;text-align:center;position:relative;transition:.3s}
.plan.pop{border-color:var(--green);transform:scale(1.03);box-shadow:0 20px 50px rgba(20,197,54,.2)}
.plan.pop::before{content:'الأكثر طلباً 🔥';position:absolute;top:-14px;right:50%;transform:translateX(50%);background:var(--grad-green);color:#fff;font-size:.75rem;font-weight:900;padding:5px 18px;border-radius:99px;white-space:nowrap}
.plan h3{font-size:1.2rem}.plan .p{font-size:2.2rem;font-weight:900;color:var(--blue);margin:10px 0}.plan .p small{font-size:.85rem;color:var(--muted)}
.plan ul{list-style:none;text-align:right;margin:18px 0;display:grid;gap:10px;font-size:.9rem}
.plan ul i{color:var(--green);margin-left:6px}
.faq{max-width:760px;margin:auto;display:grid;gap:12px}
.faq-item{background:#fff;border:1px solid var(--line);border-radius:16px;overflow:hidden}
.faq-q{width:100%;background:none;border:none;padding:18px 20px;display:flex;justify-content:space-between;align-items:center;font-weight:900;font-size:.95rem;text-align:right}
.faq-a{max-height:0;overflow:hidden;transition:.35s;color:var(--muted);font-size:.9rem}
.faq-a div{padding:0 20px 18px}.faq-item.open .faq-a{max-height:220px}.faq-item.open{border-color:var(--blue)}
.contact-grid{display:grid;grid-template-columns:.9fr 1.1fr;gap:22px}
.cinfo{background:linear-gradient(160deg,#0b183a,#0b46e1);color:#fff;border-radius:24px;padding:30px;display:flex;flex-direction:column;gap:16px}
.cinfo .row{display:flex;gap:12px;align-items:center;background:rgba(255,255,255,.1);padding:12px 14px;border-radius:14px}
.cinfo .row i{width:42px;height:42px;border-radius:12px;background:rgba(255,255,255,.2);display:grid;place-items:center;flex-shrink:0}
footer{background:#070f2b;color:#cbd5f3;padding:50px 0 20px;margin-top:40px}
footer .fgrid{max-width:1240px;margin:auto;padding:0 20px;display:grid;grid-template-columns:1.3fr 1fr 1fr 1fr;gap:26px}
footer h4{color:#fff;margin-bottom:12px}footer a{display:block;padding:5px 0;font-size:.9rem;opacity:.85}footer a:hover{opacity:1;color:#fff}
.copy{max-width:1240px;margin:30px auto 0;padding:18px 20px 0;border-top:1px solid rgba(255,255,255,.12);display:flex;justify-content:space-between;flex-wrap:wrap;gap:10px;font-size:.8rem}
.float-wa{position:fixed;bottom:20px;left:20px;z-index:500;display:flex;flex-direction:column;gap:10px;align-items:center}
.wa-btn{width:62px;height:62px;border-radius:50%;background:#25d366;display:grid;place-items:center;color:#fff;font-size:1.8rem;box-shadow:0 12px 30px rgba(37,211,102,.5);position:relative;transition:.25s}
.wa-btn:hover{transform:scale(1.08)}
.wa-btn::after{content:'';position:absolute;inset:-6px;border:2px solid #25d366;border-radius:50%;animation:pulse 1.6s infinite}
.wa-tip{background:#fff;border:1px solid var(--line);font-size:.75rem;font-weight:800;padding:6px 12px;border-radius:99px;box-shadow:var(--shadow2)}
.cart-fab{position:fixed;bottom:20px;right:20px;z-index:500;width:62px;height:62px;border-radius:50%;background:var(--ink);color:#fff;border:none;font-size:1.3rem;box-shadow:0 12px 30px rgba(0,0,0,.3)}
.cart-fab b{position:absolute;top:-4px;left:-4px;background:var(--red);width:24px;height:24px;border-radius:50%;font-size:.75rem;display:grid;place-items:center}
#toTop{position:fixed;bottom:92px;right:26px;width:48px;height:48px;border-radius:14px;background:#fff;border:1px solid var(--line);display:none;place-items:center;z-index:499;box-shadow:var(--shadow2)}
.drawer{position:fixed;top:0;bottom:0;left:0;width:min(400px,92vw);background:#fff;z-index:600;transform:translateX(-110%);transition:.35s;display:flex;flex-direction:column;box-shadow:20px 0 60px rgba(0,0,0,.2)}
.drawer.open{transform:none}
.drawer-head{padding:18px 20px;border-bottom:1px solid var(--line);display:flex;justify-content:space-between;align-items:center;font-weight:900}
.drawer-body{flex:1;overflow:auto;padding:16px;display:grid;gap:12px;align-content:start}
.citem{display:flex;gap:12px;align-items:center;border:1px solid var(--line);border-radius:14px;padding:10px}
.citem .ci{width:48px;height:48px;border-radius:12px;display:grid;place-items:center;color:#fff;font-size:1.3rem;flex-shrink:0}
.qty{display:flex;align-items:center;gap:8px}.qty button{width:28px;height:28px;border-radius:8px;border:1px solid var(--line);background:#f6f8ff;font-weight:900}
.drawer-foot{padding:18px;border-top:1px solid var(--line)}
.overlay{position:fixed;inset:0;background:rgba(5,12,35,.6);backdrop-filter:blur(4px);z-index:590;opacity:0;pointer-events:none;transition:.3s}
.overlay.show{opacity:1;pointer-events:auto}
.modal{position:fixed;inset:0;z-index:610;display:none;place-items:center;padding:18px}
.modal.open{display:grid}
.modal-box{background:#fff;border-radius:24px;max-width:560px;width:100%;max-height:90vh;overflow:auto;padding:28px;position:relative;animation:pop .3s}
@keyframes pop{from{transform:scale(.9) translateY(20px);opacity:0}}
.modal-x{position:absolute;top:14px;left:14px;width:36px;height:36px;border-radius:50%;border:none;background:#f1f4ff}
#toast{position:fixed;bottom:100px;right:50%;transform:translateX(50%) translateY(20px);z-index:700;display:flex;flex-direction:column;gap:10px;align-items:center;opacity:0;pointer-events:none;transition:.3s}
#toast.show{opacity:1;transform:translateX(50%) translateY(0)}
.toast-msg{background:var(--ink);color:#fff;padding:13px 22px;border-radius:14px;font-weight:800;font-size:.9rem;display:flex;gap:10px;align-items:center;box-shadow:0 15px 40px rgba(0,0,0,.3)}
.toast-msg.ok{background:var(--green-dark)}.toast-msg.err{background:#b91c1c}
.reveal{opacity:0;transform:translateY(26px);transition:.7s}
.reveal.vis{opacity:1;transform:none}
.acc{border:1px solid var(--line);border-radius:12px;margin:8px 0;overflow:hidden}
.acc button{width:100%;background:#f7f9ff;border:none;padding:12px 14px;font-weight:800;font-size:.85rem;display:flex;justify-content:space-between}
.acc .ac-body{max-height:0;overflow:hidden;transition:.3s;font-size:.83rem;color:var(--muted)}
.acc.open .ac-body{max-height:200px}.acc .ac-body div{padding:0 14px 12px}
@media(max-width:1024px){.grid6,.pgrid,.courses,.pricing{grid-template-columns:repeat(2,1fr)}.hero .wrap{grid-template-columns:1fr}.hero-visual{min-height:420px}.calc,.topup-grid,.contact-grid{grid-template-columns:1fr}footer .fgrid{grid-template-columns:1fr 1fr}.links{display:none}.burger{display:grid;place-items:center}.links.mobile{display:flex;position:absolute;top:100%;right:12px;left:12px;background:#fff;border:1px solid var(--line);border-radius:18px;flex-direction:column;padding:12px;box-shadow:var(--shadow)}}
@media(max-width:600px){.grid6,.pgrid,.courses,.pricing{grid-template-columns:1fr}.stats-row{grid-template-columns:repeat(2,1fr)}.float{font-size:.7rem;padding:8px 10px}.f2{right:0}.f3{left:0}section{padding:48px 0}.calc{padding:22px}.bar-row{grid-template-columns:90px 1fr 55px}}
</style>
</head>
<body>
<div id="progress"></div>
<div class="topbar"><div class="wrap">
<div style="display:flex;gap:16px;flex-wrap:wrap"><span><span class="dot"></span> متواجدون الآن — رد خلال دقائق</span><span><i class="fa-solid fa-location-dot"></i> نواكشوط، موريتانيا</span></div>
<div style="display:flex;gap:14px;align-items:center"><span><i class="fa-brands fa-whatsapp"></i> <b dir="ltr">36 46 26 66</b></span><span style="opacity:.7">|</span><span><i class="fa-solid fa-clock"></i> 7/7 من 9ص إلى 11م</span></div>
</div></div>

<header id="header"><nav class="nav">
<div class="brand"><img src="https://www.designarena.ai/u/6e32d12c-fbcc-4876-b8bd-974e1b3bd25b" alt="NextVision"><div><b>Next<i>Vision</i> <em>Digital</em></b><small>DIGITAL • موريتانيا</small></div></div>
<div class="links" id="navLinks">
<a href="#home" class="active">الرئيسية</a><a href="#services">خدماتنا</a><a href="#calc">حاسبة الإعلانات</a><a href="#store">المتجر</a><a href="#courses">الكورسات</a><a href="#pricing">الأسعار</a><a href="#faq">الأسئلة</a><a href="#contact">اتصل بنا</a>
<a class="btn btn-wa" style="padding:10px 18px" href="https://wa.me/22236462666?text=%D8%A7%D9%84%D8%B3%D9%84%D8%A7%D9%85%20%D8%B9%D9%84%D9%8A%D9%83%D9%85%20NextVision%20%F0%9F%91%8B%20%D8%A3%D8%B1%D9%8A%D8%AF%20%D8%A7%D9%84%D8%A7%D8%B3%D8%AA%D9%81%D8%B3%D8%A7%D8%B1" target="_blank"><i class="fa-brands fa-whatsapp"></i> واتساب</a>
</div>
<button class="burger" id="burger"><i class="fa-solid fa-bars"></i></button>
</nav></header>

<section class="hero" id="home"><div class="wrap">
<div>
<div class="badge"><span class="pulse"></span> وكالة موريتانية 🇲🇷 • +850 عميل يثق بنا • تقييم 4.9/5</div>
<h1>شريكك في <span class="grad">النجاح الرقمي</span><br>إعلانات تبيع، <span class="under">ومتجر يخدمك</span> 🚀</h1>
<p class="sub">إعلانات ممولة احترافية على <b>فيسبوك وتيك توك وانستغرام</b>، بيع بطاقات <b>Apple Store و Play Store</b>، شحن التطبيقات والألعاب، استشارات رقمية وكورسات أونلاين في الإعلانات والتجارة الإلكترونية — كل هذا في مكان واحد.</p>
<div class="hero-cta">
<a class="btn btn-wa" href="https://wa.me/22236462666?text=%D9%85%D8%B1%D8%AD%D8%A8%D8%A7%20NextVision%20%F0%9F%9A%80%20%D8%A3%D8%B1%D9%8A%D8%AF%20%D8%A8%D8%AF%D8%A1%20%D8%AD%D9%85%D9%84%D8%A9%20%D8%A5%D8%B9%D9%84%D8%A7%D9%86%D9%8A%D8%A9" target="_blank"><i class="fa-brands fa-whatsapp" style="font-size:1.3rem"></i> اطلب عبر واتساب — 36462666</a>
<a class="btn btn-ghost" href="#services"><i class="fa-solid fa-layer-group"></i> استكشف خدماتنا</a>
</div>
<div class="trust">
<div class="t"><i class="fa-solid fa-shield-halved" style="color:var(--green);font-size:1.3rem"></i><div><strong>دفع آمن 100%</strong><span>Bankily • Sedad • Masrivi</span></div></div>
<div class="t"><i class="fa-solid fa-bolt" style="color:var(--gold);font-size:1.3rem"></i><div><strong>تسليم فوري</strong><span>بطاقات وشحن خلال دقائق</span></div></div>
<div class="t"><i class="fa-solid fa-headset" style="color:var(--blue);font-size:1.3rem"></i><div><strong>دعم بالحسانية</strong><span>عربية / فرنسية</span></div></div>
</div>
<div class="stats-row">
<div class="stat"><b><span class="count" data-to="850">0</span>+</b><span>عميل سعيد</span></div>
<div class="stat"><b><span class="count" data-to="2400">0</span>+</b><span>حملة ممولة</span></div>
<div class="stat"><b><span class="count" data-to="32">0</span>M+</b><span>مشاهدة محققة</span></div>
<div class="stat"><b>4.9 ★</b><span>متوسط التقييم</span></div>
</div>
</div>
<div class="hero-visual">
<div class="ring"><div class="ring-inner"><img src="https://www.designarena.ai/u/6e32d12c-fbcc-4876-b8bd-974e1b3bd25b" alt="NextVision Digital"></div></div>
<div class="float f1"><div class="ic" style="background:linear-gradient(135deg,#1a5bff,#00c6ff)"><i class="fa-solid fa-chart-line"></i></div><div>ROAS 4.8x<small>حملة متجر نواكشوط — آخر 30 يوم</small></div></div>
<div class="float f2"><div class="ic" style="background:linear-gradient(135deg,#22e04a,#06721b)"><i class="fa-solid fa-check"></i></div><div>تم الشحن بنجاح ✅<small>Apple $25 • قبل دقيقتين</small></div></div>
<div class="float f3"><div class="ic" style="background:#000"><i class="fa-brands fa-tiktok"></i></div><div>+120K مشاهدة<small>حملة TikTok — مطعم تيك توك</small></div></div>
</div>
</div></section>

<div class="marquee"><div class="marquee-track" id="marquee">
<span><i class="fa-brands fa-facebook" style="color:#4da3ff"></i> Facebook Ads</span><span>•</span><span><i class="fa-brands fa-tiktok"></i> TikTok Ads</span><span>•</span><span><i class="fa-brands fa-instagram" style="color:#ff5aa5"></i> Instagram Ads</span><span>•</span><span><i class="fa-brands fa-apple"></i> Apple Store</span><span>•</span><span><i class="fa-brands fa-google-play" style="color:#22e04a"></i> Google Play</span><span>•</span><span>🔥 شحن Free Fire</span><span>•</span><span>🎓 كورسات التجارة الإلكترونية</span><span>•</span>
<span><i class="fa-brands fa-facebook" style="color:#4da3ff"></i> Facebook Ads</span><span>•</span><span><i class="fa-brands fa-tiktok"></i> TikTok Ads</span><span>•</span><span><i class="fa-brands fa-instagram" style="color:#ff5aa5"></i> Instagram Ads</span><span>•</span><span><i class="fa-brands fa-apple"></i> Apple Store</span><span>•</span><span><i class="fa-brands fa-google-play" style="color:#22e04a"></i> Google Play</span><span>•</span><span>🔥 شحن Free Fire</span><span>•</span><span>🎓 كورسات التجارة الإلكترونية</span><span>•</span>
</div></div>

<section id="services"><div class="wrap2">
<div class="sec-head reveal"><span class="kicker blue">💼 خدماتنا الرقمية الشاملة</span><h2>كل ما تحتاجه لتنمو رقمياً في موريتانيا</h2><p>من الإعلان الممول إلى البطاقات والشحن والتدريب — فريق واحد يرافقك من الفكرة إلى البيع.</p></div>
<div class="filters reveal"><button class="active" data-f="all">الكل</button><button data-f="ads">📢 الإعلانات الممولة</button><button data-f="shop">🎁 البطاقات والشحن</button><button data-f="edu">🎓 استشارات وكورسات</button></div>
<div class="grid6" id="servicesGrid"></div>
</div></section>

<section id="calc" style="padding-top:0"><div class="wrap2">
<div class="calc reveal">
<div>
<span style="background:rgba(255,255,255,.2);padding:6px 14px;border-radius:99px;font-size:.8rem;font-weight:800">🧮 حاسبة ذكية — احسب نتائجك قبل الدفع</span>
<h2 style="font-size:1.8rem;margin:12px 0;line-height:1.4">كم سيحقق إعلانك من وصول ومبيعات؟</h2>
<p style="opacity:.85;font-size:.92rem">حرّك المؤشرات وشاهد تقديراً واقعياً مبنياً على متوسط نتائج +2400 حملة أدرناها في موريتانيا.</p>
<label>📍 المنصة <output id="oPlat">TikTok — الأعلى وصولاً 🔥</output></label>
<select id="inPlat"><option value="tiktok">TikTok — تيك توك (وصول ضخم)</option><option value="fb">Facebook — فيسبوك (مبيعات ورسائل)</option><option value="insta">Instagram — انستغرام (براند وفاشن)</option></select>
<label>💰 الميزانية اليومية <output id="oBud">2,000 أوقية / يوم</output></label>
<input type="range" id="inBud" min="500" max="20000" step="100" value="2000">
<label>📅 مدة الحملة <output id="oDur">7 أيام</output></label>
<input type="range" id="inDur" min="3" max="30" value="7">
<label>🎯 هدف الحملة</label>
<select id="inGoal"><option value="msg">رسائل واتساب ومبيعات</option><option value="reach">مشاهدات وانتشار</option><option value="follow">متابعين وبراند</option></select>
</div>
<div class="calc-out">
<h3>📊 النتائج المتوقعة لحملتك</h3>
<p style="font-size:.82rem;color:var(--muted)">تقديرات تقريبية • النتائج الفعلية غالباً أفضل مع استهدافنا الاحترافي</p>
<div class="est">
<div><b id="eReach">—</b><span>👁️ وصول متوقع</span></div>
<div><b id="eClick">—</b><span>🖱️ نقرات</span></div>
<div><b id="eMsg">—</b><span>💬 رسالة واتساب</span></div>
<div><b id="eCost">—</b><span>💵 إجمالي الاستثمار</span></div>
</div>
<div style="background:#eefbef;border:1px dashed var(--green);border-radius:14px;padding:12px;font-size:.85rem;font-weight:700;color:var(--green-dark)" id="calcTip">💡 نصيحة: ميزانيتك مثالية للاختبار + التوسع.</div>
<div style="display:flex;gap:10px;margin-top:14px;flex-wrap:wrap">
<button class="btn btn-wa" style="flex:1" onclick="orderCalc()"><i class="fa-brands fa-whatsapp"></i> أطلق هذه الحملة الآن</button>
<button class="btn btn-ghost" onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">استشارة مجانية</button>
</div>
</div>
</div>
</div></section>

<section id="store" style="padding-top:10px"><div class="wrap2">
<div class="sec-head reveal"><span class="kicker">🎁 متجر البطاقات والشحن الفوري</span><h2>بطاقات Apple و Play وشحن الألعاب</h2><p>أكواد أصلية 100% • تسليم واتساب خلال 5-15 دقيقة • دفع عبر Bankily و Sedad</p></div>
<div class="store-bar reveal">
<div class="search"><i class="fa-solid fa-magnifying-glass" style="color:var(--muted)"></i><input id="storeSearch" placeholder="ابحث: آبل، فري فاير، تيك توك..."></div>
<div class="filters" style="margin:0"><button class="active" data-c="all">الكل</button><button data-c="apple">🍎 آبل</button><button data-c="play">▶️ جوجل بلاي</button><button data-c="game">🎮 شحن ألعاب</button></div>
</div>
<div class="pgrid" id="productGrid"></div>
</div></section>

<section id="topup"><div class="wrap2">
<div class="sec-head reveal"><span class="kicker blue">⚡ شحن التطبيقات المدفوعة</span><h2>اشحن أي تطبيق في 3 خطوات</h2><p>تيك توك، فري فاير، ببجي، جواهر، شدات، عملات — فقط أدخل الـ ID واستلم الشحن.</p></div>
<div class="topup-grid">
<div class="form-card reveal">
<h3>🎯 اختر التطبيق والباقة</h3><p style="font-size:.85rem;color:var(--muted)">الأسعار تشمل العمولة • تنفيذ فوري بعد تأكيد الدفع</p>
<label style="font-weight:800;font-size:.88rem;margin-top:14px;display:block">1️⃣ التطبيق:</label>
<div class="apps" id="appList" style="margin-top:8px">
<div class="app sel" data-app="TikTok" data-icon="fa-brands fa-tiktok" data-base="350"><i class="fa-brands fa-tiktok"></i>تيك توك<br><small>Coins</small></div>
<div class="app" data-app="Free Fire" data-icon="fa-solid fa-fire" data-base="300"><i class="fa-solid fa-fire" style="color:#ff6a00"></i>فري فاير<br><small>💎 جواهر</small></div>
<div class="app" data-app="PUBG" data-icon="fa-solid fa-crosshairs" data-base="400"><i class="fa-solid fa-crosshairs"></i>ببجي<br><small>UC شدات</small></div>
<div class="app" data-app="Instagram" data-icon="fa-brands fa-instagram" data-base="500"><i class="fa-brands fa-instagram" style="color:#e1306c"></i>انستغرام<br><small>ترويج + متابعين</small></div>
<div class="app" data-app="Netflix / Shahid" data-icon="fa-solid fa-clapperboard" data-base="600"><i class="fa-solid fa-clapperboard" style="color:#c00"></i>نتفليكس / شاهد<br><small>اشتراكات</small></div>
<div class="app" data-app="PlayStation" data-icon="fa-brands fa-playstation" data-base="800"><i class="fa-brands fa-playstation" style="color:#0b46e1"></i>بلايستيشن<br><small>PS Plus</small></div>
</div>
<div class="field"><label>2️⃣ الباقة:</label><select id="packSel"></select></div>
<div style="display:grid;grid-template-columns:1fr 1fr;gap:12px">
<div class="field"><label>🆔 معرف اللاعب / الحساب:</label><input id="playerId" placeholder="مثال: 512345678"></div>
<div class="field"><label>👤 الاسم:</label><input id="playerName" placeholder="اسمك الكريم"></div>
</div>
<div class="field"><label>💳 طريقة الدفع:</label><div class="pay" id="payRow"><label class="sel"><input type="radio" name="pay" checked> Bankily 🏦</label><label><input type="radio" name="pay"> Sedad 💳</label><label><input type="radio" name="pay"> Masrivi 💸</label><label><input type="radio" name="pay"> نقداً 🤝</label></div></div>
</div>
<div>
<div class="form-card reveal" style="background:linear-gradient(180deg,#0b183a,#0a2fa3);color:#fff;border:none">
<h3>🧾 ملخص الطلب</h3>
<div style="display:flex;justify-content:space-between;margin:14px 0;background:rgba(255,255,255,.1);padding:14px;border-radius:14px"><span>التطبيق</span><b id="sApp">TikTok</b></div>
<div style="display:flex;justify-content:space-between;margin:14px 0;background:rgba(255,255,255,.1);padding:14px;border-radius:14px"><span>الباقة</span><b id="sPack">—</b></div>
<div style="display:flex;justify-content:space-between;margin:14px 0;background:rgba(255,255,255,.1);padding:14px;border-radius:14px"><span>السعر الإجمالي</span><b id="sPrice" style="font-size:1.4rem;color:#5bff7e">—</b></div>
<div style="font-size:.82rem;opacity:.85">✅ ضمان الاستلام أو استرداد كامل<br>✅ تنفيذ خلال 5-30 دقيقة<br>✅ تواصل مباشر واتساب مع متابعة</div>
<button class="btn btn-wa" style="width:100%;margin-top:16px;font-size:1.05rem" onclick="orderTopup()"><i class="fa-brands fa-whatsapp" style="font-size:1.4rem"></i> تأكيد الشحن عبر واتساب</button>
<p style="text-align:center;font-size:.78rem;margin-top:10px;opacity:.7">بالضغط سيتم تحويلك لواتساب 36462666 مع تفاصيل طلبك جاهزة</p>
</div>
<div class="form-card reveal" style="margin-top:16px;display:flex;gap:12px;align-items:center"><div style="width:52px;height:52px;border-radius:50%;background:#e8f8ec;display:grid;place-items:center;font-size:1.5rem">🛡️</div><div style="font-size:.85rem"><b>لماذا NextVision؟</b><br><span style="color:var(--muted)">+3200 عملية شحن ناجحة • تقييم 4.9 • دعم يرد في دقائق.</span></div></div>
</div>
</div>
</div></section>

<section id="courses" style="background:#fff;border-top:1px solid var(--line);border-bottom:1px solid var(--line)"><div class="wrap2">
<div class="sec-head reveal"><span class="kicker">🎓 أكاديمية NextVision</span><h2>كورسات أونلاين تصنع منك مسوّقاً محترفاً</h2><p>دروس بالعربية والحسانية • مباشر + مسجلة • شهادة + متابعة واتساب • دفع بالتقسيط</p></div>
<div class="courses" id="courseGrid"></div>
</div></section>

<section><div class="wrap2">
<div class="results reveal">
<div style="display:grid;grid-template-columns:1.1fr .9fr;gap:28px" class="res-grid">
<div>
<span style="background:rgba(255,255,255,.15);padding:6px 14px;border-radius:99px;font-size:.8rem;font-weight:800">🏆 نتائج حقيقية من السوق الموريتاني</span>
<h2 style="font-size:1.9rem;margin:12px 0">أرقام تتكلم عنا</h2>
<div class="bars" id="bars">
<div class="bar-row"><span>وصول الحملات</span><div class="bar-bg"><div class="bar-fill" data-w="94%"></div></div><b>94%</b></div>
<div class="bar-row"><span>زيادة المبيعات</span><div class="bar-bg"><div class="bar-fill" data-w="86%"></div></div><b>86%</b></div>
<div class="bar-row"><span>رضا العملاء</span><div class="bar-bg"><div class="bar-fill" data-w="98%"></div></div><b>98%</b></div>
<div class="bar-row"><span>التسليم الفوري</span><div class="bar-bg"><div class="bar-fill" data-w="99%"></div></div><b>99%</b></div>
</div>
<div style="display:flex;gap:10px;flex-wrap:wrap"><button class="btn btn-wa" onclick="openModal('audit')"><i class="fa-solid fa-magnifying-glass-chart"></i> اطلب تحليل مجاني لحسابك</button><button class="btn" style="background:#fff;color:var(--ink)" onclick="nextTesti(1)">شاهد آراء العملاء ←</button></div>
</div>
<div>
<div class="testi"><div class="testi-track" id="testiTrack"></div></div>
<div class="dots" id="testiDots"></div>
</div>
</div>
<style>@media(max-width:900px){.res-grid{grid-template-columns:1fr!important}}</style>
</div>
</div></section>

<section id="pricing" style="padding-top:0"><div class="wrap2">
<div class="sec-head reveal"><span class="kicker blue">💎 باقات إدارة الإعلانات</span><h2>اختر الباقة المناسبة لطموحك</h2><p>بدون التزام طويل • تقارير أسبوعية • يمكنك الإلغاء في أي وقت</p>
<div style="display:inline-flex;background:#fff;border:1px solid var(--line);border-radius:99px;padding:5px;margin-top:14px"><button id="tA" class="mini o" style="border-radius:99px;padding:10px 22px" onclick="setBill('m')">شهرية 🔁</button><button id="tB" class="mini" style="border-radius:99px;padding:10px 22px;background:transparent" onclick="setBill('o')">حملة واحدة ⚡</button></div>
</div>
<div class="pricing reveal" id="pricingGrid"></div>
<p style="text-align:center;margin-top:16px;font-size:.85rem;color:var(--muted)">💡 كل الباقات لا تشمل ميزانية الإعلان المدفوعة للمنصة • نوفر خدمة كتابة المحتوى والتصميم +1500 أوقية</p>
</div></section>

<section id="faq" style="padding-top:10px"><div class="wrap2">
<div class="sec-head reveal"><span class="kicker">❓ الأسئلة الشائعة</span><h2>عندك سؤال؟ عندنا الجواب</h2></div>
<div class="faq reveal" id="faqList"></div>
</div></section>

<section id="contact" style="padding-top:0"><div class="wrap2">
<div class="contact-grid">
<div class="cinfo reveal">
<h2>📞 تواصل معنا مباشرة</h2><p style="opacity:.85;font-size:.9rem">فريقنا يرد خلال دقائق من 9 صباحاً حتى 11 مساءً، 7 أيام في الأسبوع.</p>
<a href="https://wa.me/22236462666" target="_blank" class="row"><i class="fa-brands fa-whatsapp"></i><div><b dir="ltr">+222 36 46 26 66</b><br><small style="opacity:.7">واتساب — الرد الأسرع ⚡</small></div></a>
<div class="row"><i class="fa-solid fa-location-dot"></i><div><b>نواكشوط — تفرغ زينة</b><br><small style="opacity:.7">التوصيل واللقاء بالموعد</small></div></div>
<div class="row"><i class="fa-solid fa-envelope"></i><div><b>contact@nextvision.mr</b><br><small style="opacity:.7">للشركات والعروض الرسمية</small></div></div>
<div style="display:flex;gap:10px;margin-top:6px"><a href="#" class="row" style="flex:1;justify-content:center"><i class="fa-brands fa-facebook"></i></a><a href="#" class="row" style="flex:1;justify-content:center"><i class="fa-brands fa-tiktok"></i></a><a href="#" class="row" style="flex:1;justify-content:center"><i class="fa-brands fa-instagram"></i></a><a href="#" class="row" style="flex:1;justify-content:center"><i class="fa-brands fa-youtube"></i></a></div>
<img src="https://www.designarena.ai/u/132e5923-65c4-4e26-b788-bed7b698c7e8" alt="" style="border-radius:16px;opacity:.9;margin-top:6px;border:2px solid rgba(255,255,255,.2)">
</div>
<div class="form-card reveal">
<h3>📝 اطلب خدمتك الآن</h3><p style="font-size:.85rem;color:var(--muted)">املأ النموذج وسيصلك تأكيد فوري على واتساب</p>
<div style="display:grid;grid-template-columns:1fr 1fr;gap:12px">
<div class="field"><label>الاسم الكامل *</label><input id="fName" placeholder="مثال: محمد الأمين"></div>
<div class="field"><label>رقم الهاتف / واتساب *</label><input id="fPhone" placeholder="مثال: 36462666"></div>
</div>
<div class="field"><label>الخدمة المطلوبة *</label><select id="fService"><option>📢 إعلان ممول — فيسبوك</option><option>📢 إعلان ممول — تيك توك</option><option>📢 إعلان ممول — انستغرام</option><option>🍎 بطاقة Apple Store</option><option>▶️ بطاقة Google Play</option><option>🎮 شحن لعبة / تطبيق</option><option>💡 استشارة رقمية</option><option>🎓 التسجيل في كورس</option></select></div>
<div class="field"><label>الميزانية التقريبية</label><select id="fBudget"><option>أقل من 2000 أوقية</option><option selected>2000 — 5000 أوقية</option><option>5000 — 15000 أوقية</option><option>أكثر من 15000 أوقية</option></select></div>
<div class="field"><label>اشرح لنا احتياجك</label><textarea id="fMsg" rows="4" placeholder="مثال: عندي متجر ملابس في نواكشوط وأريد زيادة المبيعات عبر تيك توك..."></textarea></div>
<button class="btn btn-wa" style="width:100%;font-size:1.05rem" onclick="submitForm()"><i class="fa-solid fa-paper-plane"></i> إرسال الطلب عبر واتساب</button>
<p id="fErr" style="color:#c00;font-size:.82rem;font-weight:700;margin-top:8px"></p>
</div>
</div>
</div></section>

<footer><div class="fgrid">
<div><div class="brand" style="margin-bottom:12px"><img src="https://www.designarena.ai/u/6e32d12c-fbcc-4876-b8bd-974e1b3bd25b" alt=""><div><b style="color:#fff">Next<i style="color:var(--green)">Vision</i></b><br><small style="color:#8ea0d0">DIGITAL • شريكك في النجاح الرقمي</small></div></div><p style="font-size:.88rem">وكالة موريتانية متخصصة في الإعلانات الممولة، المتجر الرقمي، والتدريب. نخدم الأفراد والشركات في كل الولايات.</p><div style="display:flex;gap:8px;margin-top:12px"><input id="newsIn" placeholder="بريدك للعروض 🎁" style="flex:1;padding:11px 14px;border-radius:12px;border:none;outline:none"><button class="btn btn-wa" style="padding:11px 16px" onclick="subscribe()">اشترك</button></div></div>
<div><h4>🚀 خدماتنا</h4><a href="#services">إعلانات فيسبوك</a><a href="#services">إعلانات تيك توك</a><a href="#services">إعلانات انستغرام</a><a href="#store">بطاقات آبل وبلاي</a><a href="#topup">شحن التطبيقات</a></div>
<div><h4>🔗 روابط سريعة</h4><a href="#calc">حاسبة الإعلانات</a><a href="#courses">الكورسات</a><a href="#pricing">الأسعار</a><a href="#faq">الأسئلة الشائعة</a><a href="#contact">اتصل بنا</a></div>
<div><h4>💳 الدفع المتاح</h4><a>🏦 Bankily</a><a>💳 Sedad</a><a>💸 Masrivi</a><a>🤝 نقداً — نواكشوط</a><a style="margin-top:8px;background:rgba(255,255,255,.1);border-radius:12px;padding:10px;text-align:center;font-weight:800;color:#fff">📞 <span dir="ltr">+222 36 46 26 66</span></a></div>
</div><div class="copy"><span>© 2026 NextVision Digital — جميع الحقوق محفوظة 🇲🇷</span><span>صُنع بحب في نواكشوط 💚💙</span></div></footer>

<div class="float-wa"><div class="wa-tip">💬 تحتاج مساعدة؟ اضغط هنا</div><a class="wa-btn" href="https://wa.me/22236462666?text=%D9%85%D8%B1%D8%AD%D8%A8%D8%A7%20%D8%A3%D8%B1%D9%8A%D8%AF%20%D9%85%D8%B3%D8%A7%D8%B9%D8%AF%D8%A9%20%F0%9F%99%8F" target="_blank"><i class="fa-brands fa-whatsapp"></i></a></div>
<button class="cart-fab" onclick="toggleCart(true)">🛒<b id="cartCount">0</b></button>
<button id="toTop" onclick="window.scrollTo({top:0,behavior:'smooth'})"><i class="fa-solid fa-arrow-up"></i></button>
<div class="overlay" id="overlay" onclick="toggleCart(false);closeModal()"></div>
<div class="drawer" id="cartDrawer"><div class="drawer-head"><span>🛒 سلة المشتريات</span><button class="modal-x" onclick="toggleCart(false)">✕</button></div><div class="drawer-body" id="cartBody"></div><div class="drawer-foot"><div style="display:flex;justify-content:space-between;font-weight:900;margin-bottom:12px"><span>الإجمالي:</span><span id="cartTotal" style="color:var(--blue);font-size:1.3rem">0 أوقية</span></div><button class="btn btn-wa" style="width:100%" onclick="checkoutWA()"><i class="fa-brands fa-whatsapp"></i> إتمام الطلب عبر واتساب</button><button class="btn btn-ghost" style="width:100%;margin-top:8px" onclick="clearCart()">تفريغ السلة</button></div></div>
<div class="modal" id="modal"><div class="modal-box"><button class="modal-x" onclick="closeModal()">✕</button><div id="modalBody"></div></div></div>
<div id="toast"></div>

<script>
const WA='22236462666';
const services=[
{id:1,cat:'ads',icon:'fa-brands fa-facebook',g:'linear-gradient(135deg,#1877f2,#0a2a8a)',t:'إعلانات فيسبوك الممولة',d:'حملات رسائل ومبيعات باستهداف دقيق للجمهور الموريتاني + إعادة الاستهداف ومتابعة يومية.',f:['استهداف بالولاية والعمر والاهتمام','تصميم + كتابة إعلانية مجانية','تقرير واتساب يومي'],p:'ابتداءً من 1500 أوقية',btn:'الأعلى مبيعاً'},
{id:2,cat:'ads',icon:'fa-brands fa-tiktok',g:'linear-gradient(135deg,#000,#444)',t:'إعلانات تيك توك',d:'انتشار فيروسي ومشاهدات ضخمة بأقل تكلفة. مثالي للمطاعم، المتاجر، والبراندات الشبابية.',f:['فيديوهات UGC + ترندات','وصول 50K-500K حقيقي','إدارة Spark Ads'],p:'ابتداءً من 1800 أوقية'},
{id:3,cat:'ads',icon:'fa-brands fa-instagram',g:'linear-gradient(135deg,#f58529,#dd2a7b,#8134af)',t:'إعلانات انستغرام',d:'براند راقٍ للفاشن، التجميل، والعقارات. ريلز + ستوري + تعاون مع مؤثرين.',f:['هوية بصرية راقية','مؤثرين موريتانيين','متجر انستغرام متكامل'],p:'ابتداءً من 1500 أوقية'},
{id:4,cat:'shop',icon:'fa-brands fa-apple',g:'linear-gradient(135deg,#000,#555)',t:'بطاقات Apple Store',d:'بطاقات أمريكية أصلية $5 إلى $100 — تسليم الكود صور + فيديو توثيق خلال دقائق.',f:['أكواد أصلية مضمونة','تسليم 5-15 دقيقة','تعويض فوري لأي خلل'],p:'من 240 أوقية',btn:'تسليم فوري ⚡'},
{id:5,cat:'shop',icon:'fa-brands fa-google-play',g:'linear-gradient(135deg,#0abe3a,#0a5a3a)',t:'بطاقات Google Play',d:'اشحن ألعابك وتطبيقاتك واشتراكاتك. متوفر كل الفئات مع شرح التفعيل بالفيديو.',f:['كل الفئات متوفرة','شرح تفعيل بالحسانية','دعم بعد البيع'],p:'من 230 أوقية'},
{id:6,cat:'shop',icon:'fa-solid fa-gamepad',g:'linear-gradient(135deg,#ff6a00,#b30000)',t:'شحن الألعاب والتطبيقات',d:'Free Fire 💎 • PUBG UC • TikTok Coins • جواهر، شدات، واشتراكات — بالـ ID فقط.',f:['بدون كلمة سر — آمن 100%','أسعار منافسة للكميات','عروض يومية على واتساب'],p:'من 150 أوقية'},
{id:7,cat:'edu',icon:'fa-solid fa-lightbulb',g:'linear-gradient(135deg,#ffb800,#ff6a00)',t:'استشارات رقمية 1:1',d:'جلسة 60 دقيقة عبر Zoom أو واتساب: نحلل مشروعك ونعطيك خطة 90 يوم واضحة.',f:['تحليل حساباتك مجاناً','خطة PDF + تسجيل الجلسة','متابعة 7 أيام واتساب'],p:'2500 أوقية / جلسة'},
{id:8,cat:'edu',icon:'fa-solid fa-graduation-cap',g:'linear-gradient(135deg,#1a5bff,#00c6ff)',t:'كورسات أونلاين',d:'إعلانات + تجارة إلكترونية من الصفر للاحتراف. مباشر + مسجل + شهادة معتمدة.',f:['12-20 ساعة تدريبية','مشروع تخرج حقيقي','مجموعة واتساب خاصة'],p:'من 4900 أوقية',btn:'خصم 30% 🎓'},
{id:9,cat:'ads',icon:'fa-solid fa-store',g:'linear-gradient(135deg,#0abe3a,#0b46e1)',t:'إدارة المتاجر والcontent',d:'نمسك صفحتك بالكامل: تصاميم، ريلز، رد على الرسائل، وإعلانات شهرية.',f:['30 تصميم + 12 ريلز شهرياً','رد آلي + إدارة رسائل','تقرير نمو شهري'],p:'من 8900 أوقية / شهر'}
];
let curFilter='all';
function renderServices(){
const g=document.getElementById('servicesGrid');g.innerHTML='';
services.filter(s=>curFilter==='all'||s.cat===curFilter).forEach(s=>{
g.innerHTML+=`<div class="scard reveal vis" style="--gc:${s.g}">
<div class="top"><div class="icon"><i class="${s.icon}"></i></div>${s.btn?`<span style="background:#e8f8ec;color:#06721b;font-size:.72rem;font-weight:900;padding:5px 12px;border-radius:99px">${s.btn}</span>`:''}</div>
<h3>${s.t}</h3><p>${s.d}</p>
<ul>${s.f.map(f=>`<li><i class="fa-solid fa-circle-check"></i> ${f}</li>`).join('')}</ul>
<div class="price"><b>${s.p}</b><span style="font-size:.75rem;color:var(--muted)">⭐ 4.9</span></div>
<div class="row"><button class="mini o" onclick="quickOrder('${s.t}')">اطلب واتساب</button><button class="mini g" onclick="serviceDetail(${s.id})">التفاصيل +</button></div>
</div>`});
}
document.querySelectorAll('[data-f]').forEach(b=>b.onclick=()=>{document.querySelectorAll('[data-f]').forEach(x=>x.classList.remove('active'));b.classList.add('active');curFilter=b.dataset.f;renderServices();});
function quickOrder(t){window.open(`https://wa.me/${WA}?text=${encodeURIComponent('مرحبا NextVision 👋 أريد خدمة: '+t)}`,'_blank');toast('تم تحويلك لواتساب ✅','ok')}
function serviceDetail(id){const s=services.find(x=>x.id===id);openModal(`<div style="text-align:center"><div class="icon" style="width:70px;height:70px;border-radius:20px;display:grid;place-items:center;color:#fff;font-size:1.8rem;margin:auto;background:${s.g}"><i class="${s.icon}"></i></div><h2 style="margin:12px 0 6px">${s.t}</h2><p style="color:var(--muted);font-size:.9rem">${s.d}</p><div style="background:#f3f6ff;border-radius:14px;padding:14px;text-align:right;margin:14px 0">${s.f.map(f=>`<div style="padding:5px 0;font-weight:700;font-size:.88rem">✅ ${f}</div>`).join('')}<div style="padding:5px 0;font-weight:700;font-size:.88rem">⏱️ التنفيذ: خلال 24 ساعة • 📊 تقرير شفاف</div></div><div style="display:flex;gap:10px"><button class="btn btn-wa" style="flex:1" onclick="quickOrder('${s.t}')">اطلب الآن — ${s.p}</button></div></div>`)}

// CALC
const plat=document.getElementById('inPlat'),bud=document.getElementById('inBud'),dur=document.getElementById('inDur'),goal=document.getElementById('inGoal');
function fmt(n){return n>=1000000?(n/1000000).toFixed(1)+'M':n>=1000?(n/1000).toFixed(1)+'K':Math.round(n).toString()}
function calc(){
const b=+bud.value,d=+dur.value;let f=plat.value==='tiktok'?52:plat.value==='fb'?35:40;
if(goal.value==='reach')f*=1.4;if(goal.value==='follow')f*=0.8;
const total=b*d,reach=total*f,click=reach*0.045,msg=click*(plat.value==='fb'?0.22:0.12);
document.getElementById('oBud').textContent=b.toLocaleString('ar-MR')+' أوقية / يوم';
document.getElementById('oDur').textContent=d+' أيام';
document.getElementById('oPlat').textContent=plat.value==='tiktok'?'TikTok — الأعلى وصولاً 🔥':plat.value==='fb'?'Facebook — الأعلى مبيعاً 💰':'Instagram — الأرقى برانداً ✨';
document.getElementById('eReach').textContent=fmt(reach);
document.getElementById('eClick').textContent=fmt(click);
document.getElementById('eMsg').textContent=fmt(msg);
document.getElementById('eCost').textContent=total.toLocaleString()+' MRU';
document.getElementById('calcTip').textContent=total<5000?'💡 نصيحة: زد المدة لـ 7+ أيام لتحسين خوارزمية المنصة.':total<20000?'💡 نصيحة: ميزانيتك مثالية للاختبار + التوسع.':'💡 ممتاز! ميزانية توسعية — ننصح بتقسيمها على 2-3 إعلانات.';
}
[plat,bud,dur,goal].forEach(e=>e.oninput=calc);calc();
function orderCalc(){const t=`طلب حملة جديدة 🚀%0Aالمنصة: ${plat.options[plat.selectedIndex].text}%0Aالميزانية: ${bud.value} × ${dur.value} يوم = ${bud.value*dur.value} أوقية%0Aالهدف: ${goal.options[goal.selectedIndex].text}%0Aالوصول المتوقع: ${document.getElementById('eReach').textContent}`;window.open(`https://wa.me/${WA}?text=${t}`,'_blank')}

// STORE
const products=[
{id:'a5',cat:'apple',name:'بطاقة Apple Store — $5',price:240,old:290,bg:'linear-gradient(135deg,#000,#444)',ic:'fa-brands fa-apple',badge:'تسليم فوري'},
{id:'a15',cat:'apple',name:'بطاقة Apple Store — $15',price:690,old:790,bg:'linear-gradient(135deg,#000,#333)',ic:'fa-brands fa-apple',badge:'الأكثر مبيعاً'},
{id:'a25',cat:'apple',name:'بطاقة Apple Store — $25',price:1150,old:1290,bg:'linear-gradient(135deg,#111,#0b46e1)',ic:'fa-brands fa-apple',badge:'خصم 10%'},
{id:'a50',cat:'apple',name:'بطاقة Apple Store — $50',price:2250,old:2500,bg:'linear-gradient(135deg,#000,#0a9c26)',ic:'fa-brands fa-apple',badge:'VIP'},
{id:'g5',cat:'play',name:'بطاقة Google Play — $5',price:230,old:280,bg:'linear-gradient(135deg,#0abe3a,#065)',ic:'fa-brands fa-google-play',badge:'تسليم فوري'},
{id:'g10',cat:'play',name:'بطاقة Google Play — $10',price:460,old:520,bg:'linear-gradient(135deg,#1a5bff,#0abe3a)',ic:'fa-brands fa-google-play',badge:'الأكثر مبيعاً'},
{id:'g25',cat:'play',name:'بطاقة Google Play — $25',price:1120,old:1250,bg:'linear-gradient(135deg,#0a2fa3,#00c6ff)',ic:'fa-brands fa-google-play',badge:'جديد'},
{id:'ff100',cat:'game',name:'Free Fire — 100 💎 جوهرة',price:180,old:220,bg:'linear-gradient(135deg,#ff6a00,#7a0000)',ic:'fa-solid fa-fire',badge:'🔥 عرض'},
{id:'ff500',cat:'game',name:'Free Fire — 510 💎 جوهرة',price:750,old:890,bg:'linear-gradient(135deg,#ff6a00,#000)',ic:'fa-solid fa-gem',badge:'الأفضل قيمة'},
{id:'pubg60',cat:'game',name:'PUBG — 60 UC شدة',price:200,old:240,bg:'linear-gradient(135deg,#3a3a00,#b89b00)',ic:'fa-solid fa-crosshairs',badge:'فوري'},
{id:'tt70',cat:'game',name:'TikTok — 70 Coins',price:150,old:190,bg:'linear-gradient(135deg,#000,#ff0050)',ic:'fa-brands fa-tiktok',badge:'⚡'},
{id:'tt350',cat:'game',name:'TikTok — 350 Coins',price:700,old:820,bg:'linear-gradient(135deg,#000,#333)',ic:'fa-brands fa-tiktok',badge:'للمشاهير'}
];
let storeCat='all',cart={};
function renderProducts(){
const q=document.getElementById('storeSearch').value.trim();
const g=document.getElementById('productGrid');g.innerHTML='';
products.filter(p=>(storeCat==='all'||p.cat===storeCat)&&p.name.includes(q)||(storeCat==='all'||p.cat===storeCat)&&q==='').forEach(p=>{
const inCart=cart[p.id]?` <span style="color:var(--green)">(${cart[p.id]} في السلة)</span>`:'';
g.innerHTML+=`<div class="pcard"><div class="ph" style="background:${p.bg}"><span class="stock">${p.badge}</span><i class="${p.ic}"></i></div><div class="pb"><h4>${p.name}${inCart}</h4><div class="pr"><b>${p.price} MRU</b><s>${p.old}</s></div><button class="add" onclick="addCart('${p.id}',this)">+ أضف للسلة 🛒</button></div></div>`});
if(!g.innerHTML)g.innerHTML='<p style="grid-column:1/-1;text-align:center;color:var(--muted);padding:30px">😕 لا توجد نتائج — جرّب كلمة أخرى أو اطلب عبر واتساب</p>';
}
document.querySelectorAll('[data-c]').forEach(b=>b.onclick=()=>{document.querySelectorAll('[data-c]').forEach(x=>x.classList.remove('active'));b.classList.add('active');storeCat=b.dataset.c;renderProducts();});
document.getElementById('storeSearch').oninput=renderProducts;
function addCart(id,btn){cart[id]=(cart[id]||0)+1;updateCart();if(btn){btn.textContent='✓ تمت الإضافة';btn.classList.add('added');setTimeout(()=>{btn.textContent='+ أضف للسلة 🛒';btn.classList.remove('added');renderProducts()},900)}toast('تمت الإضافة للسلة 🛒','ok')}
function updateCart(){let c=0,t=0,body=document.getElementById('cartBody');body.innerHTML='';
Object.entries(cart).forEach(([id,q])=>{const p=products.find(x=>x.id===id);c+=q;t+=p.price*q;
body.innerHTML+=`<div class="citem"><div class="ci" style="background:${p.bg}"><i class="${p.ic}"></i></div><div style="flex:1"><b style="font-size:.82rem">${p.name}</b><div style="font-size:.8rem;color:var(--blue);font-weight:800">${p.price} MRU</div><div class="qty"><button onclick="chQty('${id}',-1)">−</button><b>${q}</b><button onclick="chQty('${id}',1)">+</button><button onclick="delItem('${id}')" style="color:red;border-color:#fcc">🗑️</button></div></div></div>`});
if(c===0)body.innerHTML='<div style="text-align:center;padding:30px;color:var(--muted)">🛒 سلّتك فارغة<br><small>اختر بطاقة أو شحن وستصل هنا</small></div>';
document.getElementById('cartCount').textContent=c;document.getElementById('cartTotal').textContent=t.toLocaleString()+' أوقية';}
function chQty(id,d){cart[id]+=d;if(cart[id]<=0)delete cart[id];updateCart();renderProducts()}
function delItem(id){delete cart[id];updateCart();renderProducts()}
function clearCart(){cart={};updateCart();renderProducts()}
function toggleCart(o){document.getElementById('cartDrawer').classList.toggle('open',o);document.getElementById('overlay').classList.toggle('show',o||document.getElementById('modal').classList.contains('open'))}
function checkoutWA(){const e=Object.entries(cart);if(!e.length)return toast('السلة فارغة! أضف منتجاً أولاً','err');let msg='طلب جديد من المتجر 🛒%0A%0A';let tot=0;e.forEach(([id,q])=>{const p=products.find(x=>x.id===id);tot+=p.price*q;msg+=`• ${p.name} ×${q} = ${p.price*q} MRU%0A`});msg+=`%0Aالإجمالي: ${tot} أوقية%0Aالاسم: %0Aطريقة الدفع: `;window.open(`https://wa.me/${WA}?text=${msg}`,'_blank')}

// TOPUP
const packs={'TikTok':[['70 Coins — 150 MRU',150],['350 Coins — 700 MRU',700],['700 Coins — 1350 MRU',1350],['1400 Coins — 2600 MRU',2600]],'Free Fire':[['100 💎 — 180 MRU',180],['310 💎 — 450 MRU',450],['510 💎 — 750 MRU',750],['1060 💎 — 1450 MRU',1450]],'PUBG':[['60 UC — 200 MRU',200],['325 UC — 950 MRU',950],['660 UC — 1850 MRU',1850]],'Instagram':[['1000 متابع — 500 MRU',500],['ترويج ريلز — 1200 MRU',1200]],'Netflix / Shahid':[['شهر — 600 MRU',600],['3 أشهر — 1500 MRU',1500]],'PlayStation':[['PS Plus شهر — 800 MRU',800],['PS Plus سنة — 4500 MRU',4500]]};
let curApp='TikTok';
function renderPacks(){const s=document.getElementById('packSel');s.innerHTML=packs[curApp].map(p=>`<option value="${p[1]}">${p[0]}</option>`).join('');updSum()}
function updSum(){document.getElementById('sApp').textContent=curApp;const sel=document.getElementById('packSel');document.getElementById('sPack').textContent=sel.options[sel.selectedIndex].text;document.getElementById('sPrice').textContent=sel.value+' أوقية';}
document.querySelectorAll('#appList .app').forEach(a=>a.onclick=()=>{document.querySelectorAll('#appList .app').forEach(x=>x.classList.remove('sel'));a.classList.add('sel');curApp=a.dataset.app;renderPacks()});
document.getElementById('packSel').onchange=updSum;renderPacks();
document.querySelectorAll('#payRow label').forEach(l=>l.onclick=()=>{document.querySelectorAll('#payRow label').forEach(x=>x.classList.remove('sel'));l.classList.add('sel')});
function orderTopup(){const id=document.getElementById('playerId').value.trim(),nm=document.getElementById('playerName').value.trim();if(!id)return toast('⚠️ أدخل معرف الحساب / الـ ID','err');const pack=document.getElementById('packSel').options[document.getElementById('packSel').selectedIndex].text;const pay=document.querySelector('#payRow label.sel').textContent.trim();window.open(`https://wa.me/${WA}?text=${encodeURIComponent(`طلب شحن جديد ⚡\nالتطبيق: ${curApp}\nالباقة: ${pack}\nID: ${id}\nالاسم: ${nm||'-'}\nالدفع: ${pay}`)}`,'_blank');toast('تم إرسال طلب الشحن ✅','ok')}

// COURSES
const courses=[
{bg:'linear-gradient(135deg,#1877f2,#0a1b5e)',tag:'🔥 الأكثر مبيعاً',t:'احتراف إعلانات فيسبوك وتيك توك',d:'من إنشاء الحساب الإعلاني إلى حملات ROAS عالي — تطبيق عملي على مشاريع موريتانية حقيقية.',m:['6 أسابيع • 18 حصة مباشرة','شهادة + تجربة حملة حقيقية بميزانيتنا','مجموعة واتساب دعم مدى الحياة'],price:7900,old:11900,rate:'4.9 (320 طالب)',mods:['أساسيات الحساب الإعلاني والبيكسل','الاستهداف المتقدم + الجمهور الموريتاني','الكريتيف الذي يبيع: فيديو + كتابة','التحليل والتوسع Scaling']},
{bg:'linear-gradient(135deg,#0abe3a,#063)',tag:'🛒 للمتاجر',t:'التجارة الإلكترونية من الصفر',d:'ابنِ متجرك، اربط الدفع، وأطلق أول مبيعاتك خلال 30 يوم — حتى بدون رأس مال كبير.',m:['4 أسابيع • 12 حصة + قوالب جاهزة','متجر Shopify / YouCan جاهز','موردون + شركات توصيل في موريتانيا'],price:5900,old:8900,rate:'4.8 (210 طالب)',mods:['اختيار المنتج الرابح','بناء المتجر والهوية','إعلانات + COD','خدمة العملاء والتوسع']},
{bg:'linear-gradient(135deg,#7c3aed,#ec4899)',tag:'✨ جديد',t:'صناعة المحتوى والريلز',d:'تعلم التصوير بالهاتف، المونتاج، والريلز الفيروسية التي تجلب عملاء بدون إعلانات.',m:['3 أسابيع • 9 حصص عملية','30 فكرة محتوى لمجالك','أدوات AI للتصميم والمونتاج'],price:4900,old:6900,rate:'5.0 (95 طالب)',mods:['الهوية والبراند الشخصي','التصوير والمونتاج بالهاتف','سكريبتات تبيع','النمو والربح من المحتوى']}
];
function renderCourses(){const g=document.getElementById('courseGrid');g.innerHTML=courses.map((c,i)=>`<div class="course"><div class="ch" style="background:${c.bg}"><div><span style="background:#fff;color:#111;font-size:.72rem;font-weight:900;padding:4px 12px;border-radius:99px">${c.tag}</span><h3 style="margin-top:8px">${c.t}</h3></div></div><div class="cb"><div class="meta"><span>⭐ ${c.rate}</span><span>🎥 مباشر + مسجل</span><span>📜 شهادة</span></div><p style="font-size:.86rem;color:var(--muted)">${c.d}</p><ul style="list-style:none;margin:10px 0;display:grid;gap:6px;font-size:.83rem">${c.m.map(m=>`<li>✅ ${m}</li>`).join('')}</ul><div class="acc"><button onclick="this.parentElement.classList.toggle('open')">📚 البرنامج الدراسي <span>+</span></button><div class="ac-body"><div>${c.mods.map((m,k)=>`الوحدة ${k+1}: ${m}<br>`).join('')}</div></div></div><div style="display:flex;align-items:center;gap:10px;margin:12px 0"><b style="font-size:1.4rem;color:var(--blue)">${c.price.toLocaleString()} MRU</b><s style="color:#999">${c.old.toLocaleString()}</s></div><div style="display:flex;gap:8px;margin-top:auto"><button class="mini o" onclick="enroll(${i})">سجّل الآن 🎓</button><button class="mini g" onclick="quickOrder('كورس: ${c.t}')">استفسر</button></div></div></div>`).join('')}
function enroll(i){const c=courses[i];openModal(`<h2>🎓 التسجيل: ${c.t}</h2><p style="color:var(--muted);font-size:.88rem">املأ بياناتك وسنتواصل واتساب لتأكيد المقعد + رابط الدفع</p><div class="field"><label>الاسم الكامل *</label><input id="eName" placeholder="اسمك"></div><div class="field"><label>رقم واتساب *</label><input id="ePhone" placeholder="36..."></div><div class="field"><label>مستواك الحالي</label><select id="eLvl"><option>مبتدئ تماماً</option><option>عندي فكرة بسيطة</option><option>عندي مشروع وأريد التوسع</option></select></div><div style="background:#eefbef;border-radius:12px;padding:12px;font-weight:800;color:var(--green-dark)">💰 السعر بعد الخصم: ${c.price.toLocaleString()} MRU <s style="color:#888;font-weight:400">${c.old.toLocaleString()}</s> — تقسيط على دفعتين متاح ✅</div><button class="btn btn-wa" style="width:100%;margin-top:14px" onclick="doEnroll('${c.t}',${c.price})">تأكيد التسجيل عبر واتساب</button>`)}
function doEnroll(t,p){const n=document.getElementById('eName').value.trim(),ph=document.getElementById('ePhone').value.trim();if(!n||!ph)return toast('أكمل الاسم ورقم الهاتف','err');window.open(`https://wa.me/${WA}?text=${encodeURIComponent(`تسجيل كورس 🎓\nالكورس: ${t}\nالسعر: ${p} MRU\nالاسم: ${n}\nالهاتف: ${ph}\nالمستوى: ${document.getElementById('eLvl').value}`)}`,'_blank');closeModal();toast('تم حجز مقعدك مبدئياً 🎉','ok')}

// TESTI + PRICING + FAQ
const testis=[
{n:'محمد لمين — متجر LM للإلكترونيات',img:'https://i.pravatar.cc/100?img=12',t:'كنت أصرف على الإعلانات بدون نتيجة. مع NextVision أول شهر بعت 340 طلب! التقارير اليومية والمتابعة شيء ما شفته من قبل. يستاهلو كل أوقية.',s:'Facebook Ads • ROAS 4.2x'},
{n:'عائشة منت أحمد — صالون لمسة',img:'https://i.pravatar.cc/100?img=47',t:'حملة تيك توك جابتلي 85 ألف مشاهدة في أسبوع والحجوزات امتلات لشهر! والبنات اللي يردو على واتساب محترمات وسريعات.',s:'TikTok Ads • +85K views'},
{n:'الشيخ التراد — مطعم شنقيط',img:'https://i.pravatar.cc/100?img=33',t:'شحن سريع، بطاقات أصلية، وإعلانات زادت مبيعات التوصيل 3 أضعاف. أفضل وكالة تعاملت معاها في نواكشوط بلا منازع.',s:'إدارة شاملة • ×3 مبيعات'},
{n:'مريم منت سيدي — بوتيك مريم',img:'https://i.pravatar.cc/100?img=45',t:'أخذت كورس التجارة الإلكترونية وفتحت متجري الخاص. الشرح بالحسانية سهّل علي كلش. اليوم عندي دخل خاص بي الحمد لله.',s:'كورس التجارة • ⭐⭐⭐⭐⭐'}];
let ti=0;
function renderTesti(){document.getElementById('testiTrack').innerHTML=testis.map(x=>`<div class="tcard"><img src="${x.img}"><div><div class="stars">★★★★★</div><p style="font-size:.9rem;margin:8px 0">“${x.t}”</p><b style="font-size:.85rem">${x.n}</b><br><small style="color:var(--green);font-weight:800">${x.s}</small></div></div>`).join('');document.getElementById('testiDots').innerHTML=testis.map((_,i)=>`<button class="${i===0?'on':''}" onclick="goTesti(${i})"></button>`).join('')}
function goTesti(i){ti=(i+testis.length)%testis.length;document.getElementById('testiTrack').style.transform=`translateX(${ti*100}%)`;document.querySelectorAll('#testiDots button').forEach((d,k)=>d.classList.toggle('on',k===ti))}
function nextTesti(d){goTesti(ti+d)}setInterval(()=>goTesti(ti+1),6000);
let bill='m';
const plans=[
{t:'🌱 انطلاقة',dm:'9900',do:'3500',f:['حملة واحدة (FB أو TikTok)','إعداد الاستهداف + 2 تصاميم','تقرير نهائي + توصيات','دعم واتساب 7 أيام'],c:false},
{t:'🚀 احترافية',dm:'18900',do:'6500',f:['3 حملات + إعادة استهداف','6 تصاميم + 2 فيديو ريلز','تحسين يومي + تقرير أسبوعي','مدير حساب خاص واتساب','جلسة استشارية مجانية'],c:true},
{t:'🏢 شركات',dm:'34900',do:'12000',f:['حملات غير محدودة (3 منصات)','محتوى شهري كامل (30 بوست)','إدارة الرسائل والتعليقات','اجتماع Zoom أسبوعي','أولوية التنفيذ الفوري'],c:false}];
function renderPlans(){document.getElementById('pricingGrid').innerHTML=plans.map(p=>`<div class="plan ${p.c?'pop':''}"><h3>${p.t}</h3><div class="p">${bill==='m'?Number(p.dm).toLocaleString():Number(p.do).toLocaleString()} <small>MRU ${bill==='m'?'/ شهر':'/ حملة'}</small></div><ul>${p.f.map(f=>`<li><i class="fa-solid fa-circle-check"></i>${f}</li>`).join('')}</ul><button class="btn ${p.c?'btn-wa':'btn-blue'}" style="width:100%" onclick="quickOrder('باقة ${p.t} — ${bill==='m'?'شهرية':'حملة واحدة'}')">اختر هذه الباقة ✅</button></div>`).join('')}
function setBill(v){bill=v;document.getElementById('tA').style.background=v==='m'?'#0f1e42':'transparent';document.getElementById('tA').style.color=v==='m'?'#fff':'#0f1e42';document.getElementById('tB').style.background=v==='o'?'#0f1e42':'transparent';document.getElementById('tB').style.color=v==='o'?'#fff':'#0f1e42';renderPlans()}
const faqs=[
['💳 كيف أدفع؟ هل الدفع آمن؟','نقبل Bankily و Sedad و Masrivi والكاش في نواكشوط. الدفع بعد الاتفاق وقبل الإطلاق، وتصلك فاتورة واتساب + إثبات لكل عملية.'],
['⏱️ متى أستلم البطاقة أو الشحن؟','فور تأكيد الدفع: البطاقات 5-15 دقيقة، شحن الألعاب 5-30 دقيقة. في أوقات الذروة كحد أقصى ساعتين مع إبقائك على اطلاع.'],
['📢 هل تضمنون نتائج الإعلانات؟','نضمن الإعداد الاحترافي والتحسين اليومي والشفافية الكاملة. متوسط عملائنا ROAS 3-5x، وإذا لم تحقق الحملة الحد الأدنى نعيد التشغيل مجاناً.'],
['🎓 الكورسات حضورية أم أونلاين؟','أونلاين 100% (Zoom + واتساب) مع تسجيلات تبقى معك مدى الحياة. الشرح بالعربية مع تبسيط بالحسانية، ومناسب للمبتدئين تماماً.'],
['🆔 هل تحتاجون كلمة سر حساباتي للشحن؟','أبداً! الشحن يتم بالـ ID فقط. لا نطلب كلمة سر أبداً — وهذا معيار أماننا. احذر أي جهة تطلبها.'],
['↩️ ما سياسة الاسترجاع؟','البطاقات والأكواد بعد التسليم غير قابلة للاسترجاع (لطبيعتها)، لكن أي كود غير صالح يُعوَّض فوراً. الإعلانات: استرداد الميزانية غير المصروفة في أي وقت.']];
function renderFaq(){document.getElementById('faqList').innerHTML=faqs.map(f=>`<div class="faq-item"><button class="faq-q" onclick="this.parentElement.classList.toggle('open')">${f[0]}<i class="fa-solid fa-chevron-down"></i></button><div class="faq-a"><div>${f[1]}<br><a href="https://wa.me/${WA}" target="_blank" style="color:var(--blue);font-weight:800">اسألنا واتساب ←</a></div></div>`).join('')}

// FORMS + MODAL + TOAST + NAV
function submitForm(){const n=document.getElementById('fName').value.trim(),p=document.getElementById('fPhone').value.trim(),e=document.getElementById('fErr');if(n.length<3){e.textContent='⚠️ المرجو إدخال الاسم الكامل';return}if(!/^[234]\d{7}$/.test(p.replace(/\s/g,''))){e.textContent='⚠️ أدخل رقماً موريتانياً صحيحاً (8 أرقام يبدأ بـ 2/3/4)';return}e.textContent='';const msg=`طلب جديد 📝%0Aالاسم: ${n}%0Aالهاتف: ${p}%0Aالخدمة: ${document.getElementById('fService').value}%0Aالميزانية: ${document.getElementById('fBudget').value}%0Aالتفاصيل: ${document.getElementById('fMsg').value||'-'}`;window.open(`https://wa.me/${WA}?text=${msg}`,'_blank');toast('تم إرسال طلبك بنجاح 🎉','ok')}
function subscribe(){const v=document.getElementById('newsIn').value;if(!v||!v.includes('@'))return toast('أدخل بريداً صحيحاً','err');document.getElementById('newsIn').value='';toast('تم الاشتراك! كود خصمك: NV10 🎁','ok')}
function openModal(html){document.getElementById('modalBody').innerHTML=html;document.getElementById('modal').classList.add('open');document.getElementById('overlay').classList.add('show')}
function closeModal(){document.getElementById('modal').classList.remove('open');if(!document.getElementById('cartDrawer').classList.contains('open'))document.getElementById('overlay').classList.remove('show')}
function toast(m,type){const t=document.createElement('div');t.className='toast-msg '+(type||'');t.innerHTML=(type==='ok'?'✅ ':type==='err'?'⚠️ ':'💬 ')+m;const w=document.getElementById('toast');w.innerHTML='';w.appendChild(t);w.classList.add('show');setTimeout(()=>w.classList.remove('show'),2800)}
document.getElementById('burger').onclick=()=>document.getElementById('navLinks').classList.toggle('mobile');
document.querySelectorAll('#navLinks a').forEach(a=>a.onclick=()=>document.getElementById('navLinks').classList.remove('mobile'));
window.addEventListener('scroll',()=>{document.getElementById('header').classList.toggle('scrolled',scrollY>10);const h=document.documentElement;document.getElementById('progress').style.width=(scrollY/(h.scrollHeight-innerHeight)*100)+'%';document.getElementById('toTop').style.display=scrollY>600?'grid':'none';
document.querySelectorAll('#navLinks a[href^="#"]').forEach(a=>{const s=document.querySelector(a.getAttribute('href'));if(s&&scrollY>s.offsetTop-140&&scrollY<s.offsetTop+s.offsetHeight-140){document.querySelectorAll('#navLinks a').forEach(x=>x.classList.remove('active'));a.classList.add('active')}})});
const obs=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add('vis');if(e.target.querySelector('.count')||e.target.classList.contains('count')){}document.querySelectorAll('.bar-fill').forEach(b=>b.style.width=b.dataset.w)}}),{threshold:.15});
document.querySelectorAll('.reveal').forEach(el=>obs.observe(el));
const cObs=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){const el=e.target,to=+el.dataset.to;let cur=0;const iv=setInterval(()=>{cur+=Math.ceil(to/60);if(cur>=to){cur=to;clearInterval(iv)}el.textContent=cur.toLocaleString()},25);cObs.unobserve(el)}}),{threshold:.5});
document.querySelectorAll('.count').forEach(el=>cObs.observe(el));
// touch swipe for testi
let sx=0;document.querySelector('.testi').addEventListener('touchstart',e=>sx=e.touches[0].clientX);document.querySelector('.testi').addEventListener('touchend',e=>{const dx=e.changedTouches[0].clientX-sx;if(dx<-40)nextTesti(1);if(dx>40)nextTesti(-1)});
renderServices();renderProducts();renderCourses();renderTesti();renderPlans();renderFaq();updateCart();goTesti(0);
setTimeout(()=>toast('👋 مرحباً بك في NextVision! خصم 10% اليوم بكود NV10','ok'),1500);
</script>
</body>
</html>
