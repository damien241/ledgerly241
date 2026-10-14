<!DOCTYPE html>
<html lang="fr" class="splashing">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Ledgerly</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700&family=Hanken+Grotesk:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#F2F5F8; --surface:#FFFFFF; --ink:#0E2238; --muted:#5B6B7D; --line:#DCE3EA;
  --primary:#0E2A47; --on-primary:#FFFFFF;
  --green:#0B8A54; --green-soft:#DDF3E7;
  --blue:#2F68B3; --blue-soft:#E0ECFA;
  --yellow:#FCD116; --yellow-soft:#FFF3BF;
  --danger:#B3372B; --danger-soft:#FBE4E1;
  --splash:#0A1F36;
  color-scheme:light;
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px);
  padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){
    --bg:#0B1622; --surface:#112133; --ink:#E8EEF4; --muted:#92A3B5; --line:#23374C;
    --primary:#3A75C4; --on-primary:#FFFFFF;
    --green:#3CC98B; --green-soft:#0F3527;
    --blue:#6FA3E6; --blue-soft:#14304F;
    --yellow-soft:#3F3510;
    --danger:#F08A7E; --danger-soft:#3E1E1A;
    color-scheme:dark;
  }
}
:root[data-theme="dark"]{
  --bg:#0B1622; --surface:#112133; --ink:#E8EEF4; --muted:#92A3B5; --line:#23374C;
  --primary:#3A75C4; --on-primary:#FFFFFF;
  --green:#3CC98B; --green-soft:#0F3527;
  --blue:#6FA3E6; --blue-soft:#14304F;
  --yellow-soft:#3F3510;
  --danger:#F08A7E; --danger-soft:#3E1E1A;
  color-scheme:dark;
}
*{box-sizing:border-box}
[hidden]{display:none!important}
html,body{height:100%;margin:0}
html.splashing{background:var(--splash)}
body{
  background:var(--bg);color:var(--ink);
  font-family:'Hanken Grotesk',system-ui,-apple-system,'Segoe UI',Roboto,sans-serif;
  font-size:15px;line-height:1.45;
  display:flex;flex-direction:column;
  -webkit-text-size-adjust:100%;
}
h1,h2,h3{font-family:'Bricolage Grotesque','Hanken Grotesk',system-ui,sans-serif;margin:0;letter-spacing:-.01em;line-height:1.15}
h1{font-size:25px;font-weight:700}
h2{font-size:18px;font-weight:700}
p{margin:0}
.muted{color:var(--muted)}
.small{font-size:13.5px}
button{font:inherit;cursor:pointer}
:focus-visible{outline:3px solid var(--blue);outline-offset:2px}

#stage{flex:1;min-height:0;position:relative;overflow:hidden}
.credit{
  flex:none;text-align:center;font-size:12px;color:var(--muted);
  padding:8px 12px;background:var(--surface);border-top:1px solid var(--line);
}
html.splashing .credit{background:var(--splash);color:#8FA7BF;border-top-color:transparent}

/* Écran de chargement */
#splash{
  position:absolute;inset:0;background:var(--splash);
  display:flex;flex-direction:column;align-items:center;justify-content:center;gap:26px;
  transition:opacity .45s ease;z-index:50;
}
#splash.out{opacity:0;pointer-events:none}
.ring-wrap{position:relative;width:132px;height:132px;display:grid;place-items:center}
.ring{position:absolute;inset:0;width:100%;height:100%;animation:spin 1.5s linear infinite}
.ring circle{fill:none;stroke-width:5;stroke-linecap:round}
.ring-wrap .mark svg{display:block}
.draw{stroke-dasharray:42;stroke-dashoffset:42;animation:draw 1.3s .25s ease forwards}
.word{font-family:'Bricolage Grotesque',system-ui,sans-serif;font-weight:700;font-size:36px;color:#fff;letter-spacing:-.02em}
@keyframes spin{to{transform:rotate(360deg)}}
@keyframes draw{to{stroke-dashoffset:0}}
@media (prefers-reduced-motion: reduce){
  .ring{animation:none}
  .draw{animation:none;stroke-dashoffset:0}
  #splash{transition:none}
}

/* Boutons et champs */
.btn{
  background:var(--primary);color:var(--on-primary);border:1px solid var(--primary);
  border-radius:10px;padding:10px 16px;font-weight:600;font-size:15px;min-height:44px;
}
.btn.ghost{background:transparent;color:var(--ink);border-color:var(--line)}
.btn.danger{background:transparent;color:var(--danger);border-color:var(--danger)}
.btn.solid-danger{background:var(--danger);border-color:var(--danger);color:#fff}
.btn.small{padding:6px 12px;min-height:36px;font-size:14px}
.btn.block{width:100%}
input,select{
  font:inherit;width:100%;padding:10px 12px;border:1px solid var(--line);border-radius:10px;
  background:var(--surface);color:var(--ink);min-height:44px;margin-top:6px;
}
label{display:block;font-size:14px;font-weight:500;color:var(--muted);margin-bottom:12px}
.row2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.err{color:var(--danger);font-size:14px;min-height:20px;margin-bottom:10px}
.actions{display:flex;gap:10px;justify-content:flex-end;flex-wrap:wrap;margin-top:14px}

/* Connexion */
#auth{position:absolute;inset:0;overflow-y:auto;display:flex;justify-content:center;padding:28px 20px}
.authbox{width:100%;max-width:400px;margin:auto 0}
.lockup{display:flex;align-items:center;gap:10px;margin-bottom:26px}
.wordmark{font-family:'Bricolage Grotesque',system-ui,sans-serif;font-weight:700;font-size:26px;letter-spacing:-.02em}
.authbox h1{margin-bottom:6px}
.authbox .muted{margin-bottom:20px}
.tabs{display:grid;grid-template-columns:1fr 1fr;border:1px solid var(--line);border-radius:10px;overflow:hidden;margin-bottom:18px}
.tabs button{border:0;background:var(--surface);color:var(--ink);padding:11px;font-weight:600;min-height:44px}
.tabs button.active{background:var(--primary);color:var(--on-primary)}
.note{margin-top:16px;font-size:13px;color:var(--muted);text-align:center}

/* Application */
#app{
  position:absolute;inset:0;display:grid;
  grid-template-columns:minmax(0,1fr);
  grid-template-rows:auto minmax(0,1fr) auto;
  grid-template-areas:"top" "main" "nav";
}
.topbar{
  grid-area:top;display:flex;align-items:center;justify-content:space-between;gap:12px;
  padding:10px 16px;background:var(--surface);border-bottom:1px solid var(--line);
}
.topbar .brand{display:flex;align-items:center;gap:8px}
.topbar .wordmark{font-size:20px}
.topbar .who{display:flex;align-items:center;gap:10px;min-width:0}
.topbar .who #userName{max-width:130px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;color:var(--muted);font-size:14px}
.link{background:none;border:0;color:var(--blue);font-weight:600;padding:8px 4px;min-height:36px}
.topbar .link{display:inline-flex;align-items:center;gap:6px}
.btn:disabled{opacity:.45;cursor:default}
@media (max-width:520px){#userName,.gear-l{display:none}}
main{grid-area:main;overflow-y:auto;padding:18px 16px 28px}
.wrap{max-width:900px;margin:0 auto}
.nav{
  grid-area:nav;display:flex;background:var(--surface);border-top:1px solid var(--line);
}
.nav button{
  flex:1;min-width:0;background:none;border:0;color:var(--muted);
  display:flex;flex-direction:column;align-items:center;gap:3px;padding:8px 2px 7px;
  font-size:10.5px;font-weight:600;min-height:54px;
  border-top:3px solid transparent;
}
.nav button svg{width:22px;height:22px;fill:none;stroke:currentColor;stroke-width:1.8;stroke-linecap:round;stroke-linejoin:round}
.nav button.active{color:var(--ink);border-top-color:var(--yellow)}
.nav .lbl-l{display:none}
.nav .soon{display:none}
@media (min-width:860px){
  #app{
    grid-template-columns:230px minmax(0,1fr);
    grid-template-rows:auto minmax(0,1fr);
    grid-template-areas:"top top" "nav main";
  }
  .nav{flex-direction:column;border-top:0;border-right:1px solid var(--line);padding:12px;gap:2px}
  .nav button{
    flex:none;flex-direction:row;gap:12px;font-size:15px;padding:10px 12px;
    border-top:0;border-left:3px solid transparent;border-radius:8px;min-height:44px;text-align:left;
  }
  .nav button.active{border-left-color:var(--yellow);background:var(--bg)}
  .nav .lbl-s{display:none}
  .nav .lbl-l{display:inline}
  .nav .soon{display:block;margin-top:auto;padding:12px;font-size:13px;color:var(--muted)}
  main{padding:26px 32px 36px}
  .topbar{padding:12px 24px}
}

.head{display:flex;justify-content:space-between;align-items:center;gap:12px;margin-bottom:18px;flex-wrap:wrap}
.head .muted{margin-top:4px}

/* Chiffres clés */
.figures{
  display:grid;grid-template-columns:1fr 1fr;border:1px solid var(--line);
  border-radius:14px;background:var(--surface);overflow:hidden;margin-bottom:8px;
}
.fig{padding:16px}
.fig.cash{grid-column:1/-1;border-bottom:1px solid var(--line)}
.fig:nth-child(3){border-left:1px solid var(--line)}
.fig .n{font-family:'Bricolage Grotesque',system-ui,sans-serif;font-weight:700;font-size:23px;font-variant-numeric:tabular-nums;line-height:1.2}
.fig.cash .n{font-size:34px}
.fig .l{display:flex;align-items:center;gap:7px;font-size:13.5px;color:var(--muted);margin-bottom:4px}
.dot{width:10px;height:10px;border-radius:50%;display:inline-block}
.dot.g{background:var(--green)}
.dot.b{background:var(--blue)}
.legend{display:flex;gap:16px;font-size:13px;color:var(--muted);margin-top:6px}
.legend span{display:flex;align-items:center;gap:6px}
.section{margin-top:28px}
.section>h2{margin-bottom:12px}
.panel{border:1px solid var(--line);border-radius:14px;background:var(--surface);padding:16px}
.alert{border:1px solid var(--yellow);background:var(--yellow-soft);border-radius:14px;padding:14px 16px;margin-top:20px}
.alert strong{display:block;margin-bottom:2px}
.alert .btn{margin-top:10px}
.empty{border:1px dashed var(--line);border-radius:14px;padding:22px 18px;text-align:center;color:var(--muted);margin-bottom:18px}
.empty h2{color:var(--ink);margin-bottom:6px}
.empty .actions{justify-content:center}

/* Listes */
.list{border:1px solid var(--line);border-radius:14px;background:var(--surface);overflow:hidden}
.item{padding:14px 16px;border-bottom:1px solid var(--line);display:grid;gap:10px}
.item:last-child{border-bottom:0}
.item .top{display:flex;justify-content:space-between;gap:12px;align-items:flex-start}
.item .t{font-weight:600;overflow-wrap:anywhere}
.item .s{color:var(--muted);font-size:13.5px;overflow-wrap:anywhere}
.item .amt{font-family:'Bricolage Grotesque',system-ui,sans-serif;font-weight:700;font-variant-numeric:tabular-nums;white-space:nowrap;text-align:right}
.item .acts{display:flex;gap:8px;flex-wrap:wrap;align-items:center}
.pos{color:var(--green)}
.neg{color:var(--blue)}
.chip{display:inline-block;padding:3px 10px;border-radius:99px;font-size:12.5px;font-weight:600;margin-top:4px;white-space:nowrap}
.chip.paid{background:var(--green-soft);color:var(--green)}
.chip.pending{background:var(--blue-soft);color:var(--blue)}
.chip.late{background:var(--danger-soft);color:var(--danger)}
.chip.soon{background:var(--yellow-soft);color:var(--ink)}
.seg{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:14px}
.seg button{border:1px solid var(--line);background:var(--surface);color:var(--ink);border-radius:99px;padding:7px 14px;font-weight:600;font-size:14px;min-height:36px}
.seg button.active{background:var(--primary);color:var(--on-primary);border-color:var(--primary)}
.msg{white-space:pre-wrap;font:inherit;font-size:14px;background:var(--bg);border-radius:10px;padding:12px;margin:0;overflow-wrap:anywhere}
.scroll{overflow-x:auto;border:1px solid var(--line);border-radius:14px;background:var(--surface)}
.tbl{width:100%;border-collapse:collapse;font-size:14px}
.tbl th{text-align:left;color:var(--muted);font-weight:500;padding:11px 14px;border-bottom:1px solid var(--line);white-space:nowrap}
.tbl td{padding:11px 14px;border-bottom:1px solid var(--line);font-variant-numeric:tabular-nums;white-space:nowrap}
.tbl tr:last-child td{border-bottom:0}
.tbl .num{text-align:right}
.expform{display:grid;grid-template-columns:1fr 1fr;gap:12px;align-items:end}
.expform .full{grid-column:1/-1}
.expform label{margin-bottom:0}

/* Fenêtres */
#modal{position:absolute;inset:0;background:rgba(6,16,28,.55);display:none;align-items:flex-end;justify-content:center;z-index:40}
#modal.open{display:flex}
.sheet{background:var(--surface);color:var(--ink);width:100%;max-width:580px;max-height:92%;overflow-y:auto;border-radius:18px 18px 0 0;padding:20px}
.sheet h2{margin-bottom:14px}
@media (min-width:700px){#modal{align-items:center}.sheet{border-radius:18px;max-height:90%}}
.line{display:grid;grid-template-columns:1fr 1fr auto;gap:8px;align-items:end;padding:10px 0;border-bottom:1px solid var(--line)}
.line .l-desc-wrap{grid-column:1/-1}
.line label{margin-bottom:0}
.line .rm{min-height:44px}
.totals{margin:14px 0;padding:12px 14px;background:var(--bg);border-radius:10px;display:grid;gap:4px}
.totals div{display:flex;justify-content:space-between;gap:12px;font-variant-numeric:tabular-nums}
.totals .ttc{font-weight:700;font-size:17px;border-top:1px solid var(--line);padding-top:6px;margin-top:2px}
.inv-head{display:flex;justify-content:space-between;gap:16px;flex-wrap:wrap;margin-bottom:16px}
#toast{
  position:absolute;left:50%;bottom:84px;transform:translateX(-50%);z-index:60;
  background:var(--primary);color:var(--on-primary);padding:10px 16px;border-radius:10px;
  font-size:14px;font-weight:600;opacity:0;pointer-events:none;transition:opacity .2s;max-width:90%;text-align:center;
}
#toast.show{opacity:1}
@media (min-width:860px){#toast{bottom:20px}}

@media print{
  html,body{height:auto}
  #stage{overflow:visible}
  #stage>*{visibility:hidden}
  #modal,#modal *{visibility:visible}
  #modal{position:static;background:none;display:block}
  .sheet{max-height:none;box-shadow:none;border-radius:0;padding:0}
  .no-print{display:none!important}
  .credit{visibility:visible}
}
</style>
</head>
<body>
<div id="stage">
  <div id="splash" aria-label="Chargement de Ledgerly">
    <div class="ring-wrap">
      <svg class="ring" viewBox="0 0 100 100" aria-hidden="true">
        <circle cx="50" cy="50" r="44" stroke="#12B76A" stroke-dasharray="76 200.5" stroke-dashoffset="0"/>
        <circle cx="50" cy="50" r="44" stroke="#FCD116" stroke-dasharray="76 200.5" stroke-dashoffset="-92.2"/>
        <circle cx="50" cy="50" r="44" stroke="#4A8BE0" stroke-dasharray="76 200.5" stroke-dashoffset="-184.4"/>
      </svg>
      <div class="mark" id="splashMark"></div>
    </div>
    <div class="word">Ledgerly</div>
  </div>

  <div id="auth" hidden></div>

  <div id="app" hidden>
    <header class="topbar">
      <div class="brand"><span id="topMark"></span><span class="wordmark">Ledgerly</span></div>
      <div class="who"><span id="userName"></span><button class="link" data-act="tab" data-v="settings" aria-label="Paramètres"><svg viewBox="0 0 24 24" width="20" height="20" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><circle cx="12" cy="12" r="3"/><path d="M12 2v3M12 19v3M2 12h3M19 12h3M4.9 4.9l2.1 2.1M17 17l2.1 2.1M4.9 19.1L7 17M17 7l2.1-2.1"/></svg><span class="gear-l">Paramètres</span></button><button class="link" data-act="logout">Se déconnecter</button></div>
    </header>
    <nav class="nav" id="nav" aria-label="Navigation principale"></nav>
    <main id="view"></main>
  </div>

  <div id="modal"><div class="sheet" id="sheet"></div></div>
  <div id="toast" role="status" aria-live="polite"></div>
</div>
<footer class="credit">Conçu par Damien Starly Koumba</footer>

<script>
(function(){
'use strict';

/* ---------- Réglages ---------- */
var VAT_RATES=[18,10,0];      // Taux de TVA proposés (modifiables ici)
var CURRENCY='FCFA';

/* ---------- Utilitaires ---------- */
var $=function(s){return document.querySelector(s)};
var esc=function(s){return String(s==null?'':s).replace(/[&<>"']/g,function(c){return {'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]})};
var pad=function(n){return String(n).padStart(2,'0')};
var uid=function(){return Math.random().toString(36).slice(2,9)+Date.now().toString(36).slice(-4)};
var val=function(id){var e=document.getElementById(id);return e?e.value:''};

var mem={};
var LS={
  get:function(k){try{var v=localStorage.getItem(k);if(v!==null)return JSON.parse(v)}catch(e){}return mem[k]!==undefined?mem[k]:null},
  set:function(k,v){mem[k]=v;try{localStorage.setItem(k,JSON.stringify(v))}catch(e){}}
};

function todayStr(){var d=new Date();return d.getFullYear()+'-'+pad(d.getMonth()+1)+'-'+pad(d.getDate())}
function addDays(s,n){var d=new Date(s+'T00:00:00');d.setDate(d.getDate()+n);return d.getFullYear()+'-'+pad(d.getMonth()+1)+'-'+pad(d.getDate())}
function daysBetween(a,b){return Math.round((new Date(b+'T00:00:00')-new Date(a+'T00:00:00'))/864e5)}
function fdate(s){return s?new Date(s+'T00:00:00').toLocaleDateString('fr-FR',{day:'numeric',month:'short',year:'numeric'}):''}
var nf=new Intl.NumberFormat('fr-FR',{maximumFractionDigits:0});
function fmt(n){return nf.format(Math.round(n))+' '+CURRENCY}
function compact(n){
  if(n>=1e6)return (n/1e6).toFixed(1).replace('.',',')+' M';
  if(n>=1e3)return Math.round(n/1e3)+' k';
  return String(Math.round(n));
}
function niceMax(v){var p=Math.pow(10,Math.floor(Math.log10(v)));var n=v/p;return (n<=1?1:n<=2?2:n<=5?5:10)*p}

function mark(size,bg){
  return '<svg width="'+size+'" height="'+size+'" viewBox="0 0 48 48" aria-hidden="true">'+
    '<rect width="48" height="48" rx="12" style="fill:'+bg+'"/>'+
    '<path class="draw" d="M11 33 L20 24 L26 29 L37 16" fill="none" stroke="#FCD116" stroke-width="4" stroke-linecap="round" stroke-linejoin="round"/>'+
    '<circle cx="37" cy="16" r="3.6" fill="#12B76A"/></svg>';
}

/* ---------- Icônes ---------- */
var ICONS={
  home:'<path d="M3 11l9-8 9 8v9a1 1 0 0 1-1 1h-5v-6H9v6H4a1 1 0 0 1-1-1z"/>',
  file:'<path d="M6 3h8l5 5v13H6z"/><path d="M14 3v5h5M9 13h6M9 17h6"/>',
  users:'<circle cx="9" cy="8" r="3.5"/><path d="M2.5 20c.6-3.6 3.2-5.5 6.5-5.5s5.9 1.9 6.5 5.5"/><circle cx="17.5" cy="9" r="2.5"/><path d="M17 14.5c2.4.2 4 1.7 4.5 4.5"/>',
  bell:'<path d="M6 17V11a6 6 0 0 1 12 0v6l1.5 2h-15z"/><path d="M10 21h4"/>',
  wallet:'<path d="M3 7a2 2 0 0 1 2-2h13v4"/><path d="M3 7v11a2 2 0 0 0 2 2h15V9H5a2 2 0 0 1-2-2z"/><circle cx="16.5" cy="14.5" r="1.2"/>',
  bars:'<path d="M5 20V10M12 20V4M19 20v-7"/>'
};
var NAV=[
  {v:'dashboard',s:'Accueil',l:'Tableau de bord',i:'home'},
  {v:'invoices',s:'Factures',l:'Factures',i:'file'},
  {v:'clients',s:'Clients',l:'Clients',i:'users'},
  {v:'reminders',s:'Relances',l:'Relances',i:'bell'},
  {v:'cash',s:'Trésorerie',l:'Trésorerie',i:'wallet'},
  {v:'reports',s:'Rapports',l:'Rapports',i:'bars'}
];

/* ---------- État ---------- */
var user=null, db=null, view='dashboard', filter='all', authMode='register';
var draft=null, editingClient=null, pendingConfirm=null, msgs={};

function save(){if(user)LS.set('ledgerly:data:'+user.id,db)}

async function hashPw(pw,email){
  try{
    var buf=await crypto.subtle.digest('SHA-256',new TextEncoder().encode(email+'|'+pw));
    return Array.from(new Uint8Array(buf)).map(function(b){return b.toString(16).padStart(2,'0')}).join('');
  }catch(e){return 'p:'+btoa(unescape(encodeURIComponent(pw)))}
}

/* ---------- Calculs ---------- */
function totals(inv){
  var ht=inv.lines.reduce(function(s,l){return s+(+l.qty||0)*(+l.price||0)},0);
  var tva=ht*inv.vat/100;
  return {ht:ht,tva:tva,ttc:ht+tva};
}
function invState(inv){
  if(inv.status==='paid')return 'paid';
  return inv.due<todayStr()?'late':'pending';
}
function clientOf(id){return db.clients.find(function(c){return c.id===id})||{name:'Client supprimé',email:'',phone:''}}
function monthSeries(n){
  var now=new Date(),out=[],i;
  for(i=n-1;i>=0;i--){
    var d=new Date(now.getFullYear(),now.getMonth()-i,1);
    out.push({
      key:d.getFullYear()+'-'+pad(d.getMonth()+1),
      label:d.toLocaleDateString('fr-FR',{month:'short'}).replace('.',''),
      long:d.toLocaleDateString('fr-FR',{month:'long',year:'numeric'}),
      income:0,expense:0,billed:0,vat:0
    });
  }
  var idx={};out.forEach(function(m){idx[m.key]=m});
  db.invoices.forEach(function(inv){
    var t=totals(inv),b=idx[inv.date.slice(0,7)];
    if(b){b.billed+=t.ttc;b.vat+=t.tva}
    if(inv.status==='paid'){var p=idx[(inv.paidDate||inv.date).slice(0,7)];if(p)p.income+=t.ttc}
  });
  db.expenses.forEach(function(e){var m=idx[e.date.slice(0,7)];if(m)m.expense+=e.amount});
  return out;
}
function cashTotals(){
  var inc=db.invoices.filter(function(i){return i.status==='paid'}).reduce(function(s,i){return s+totals(i).ttc},0);
  var out=db.expenses.reduce(function(s,e){return s+e.amount},0);
  return {inc:inc,out:out,bal:inc-out};
}
function nextNumber(date){
  var y=date.slice(0,4),n=1,num;
  do{num='F-'+y+'-'+String(n).padStart(3,'0');n++}while(db.invoices.some(function(i){return i.number===num}));
  return num;
}

/* ---------- Graphique ---------- */
function chart(s){
  var max=Math.max.apply(null,[1].concat(s.map(function(m){return Math.max(m.income,m.expense)})));
  var top=niceMax(max),W=360,H=200,pl=40,pr=6,pt=10,pb=26;
  var cw=(W-pl-pr)/s.length,bh=H-pt-pb,g='';
  [0,.5,1].forEach(function(f){
    var y=pt+bh*(1-f);
    g+='<line x1="'+pl+'" x2="'+(W-pr)+'" y1="'+y+'" y2="'+y+'" stroke="var(--line)"/>'+
       '<text x="'+(pl-6)+'" y="'+(y+4)+'" text-anchor="end" font-size="10" fill="var(--muted)">'+compact(top*f)+'</text>';
  });
  s.forEach(function(m,i){
    var x=pl+cw*i+cw/2,h1=bh*m.income/top,h2=bh*m.expense/top;
    g+='<rect x="'+(x-17)+'" y="'+(pt+bh-h1)+'" width="16" height="'+h1+'" rx="3" fill="var(--green)"/>'+
       '<rect x="'+(x+1)+'" y="'+(pt+bh-h2)+'" width="16" height="'+h2+'" rx="3" fill="var(--blue)"/>'+
       '<text x="'+x+'" y="'+(H-8)+'" text-anchor="middle" font-size="11" fill="var(--muted)">'+esc(m.label)+'</text>';
  });
  return '<svg viewBox="0 0 '+W+' '+H+'" role="img" aria-label="Entrées et sorties des six derniers mois" style="width:100%;height:auto;max-width:640px;display:block">'+g+'</svg>';
}

/* ---------- Vues ---------- */
var views={};

views.dashboard=function(){
  var s=monthSeries(6),cur=s[s.length-1],c=cashTotals();
  var pending=db.invoices.filter(function(i){return i.status!=='paid'}).reduce(function(a,i){return a+totals(i).ttc},0);
  var late=db.invoices.filter(function(i){return invState(i)==='late'});
  var lateSum=late.reduce(function(a,i){return a+totals(i).ttc},0);
  var empty=!db.clients.length&&!db.invoices.length&&!db.expenses.length;
  return '<div class="wrap">'+
    '<div class="head"><div><h1>Bonjour, '+esc(user.name)+'</h1><p class="muted">Voici où en est votre activité.</p></div>'+
    '<button class="btn" data-act="newInvoice">Nouvelle facture</button></div>'+
    (empty?'<div class="empty"><h2>Votre espace est vide</h2><p>Ajoutez un premier client, ou chargez des données d’exemple pour explorer Ledgerly.</p>'+
      '<div class="actions"><button class="btn ghost" data-act="newClient">Ajouter un client</button><button class="btn" data-act="seed">Charger des données d’exemple</button></div></div>':'')+
    '<div class="figures">'+
      '<div class="fig cash"><div class="l">En caisse</div><div class="n">'+fmt(c.bal)+'</div></div>'+
      '<div class="fig"><div class="l"><span class="dot g"></span>Entrées ce mois</div><div class="n">'+fmt(cur.income)+'</div></div>'+
      '<div class="fig"><div class="l"><span class="dot b"></span>Sorties ce mois</div><div class="n">'+fmt(cur.expense)+'</div></div>'+
    '</div>'+
    '<p class="muted small">À encaisser : '+fmt(pending)+'</p>'+
    (late.length?'<div class="alert"><strong>'+late.length+(late.length>1?' factures en retard':' facture en retard')+'</strong>'+
      '<span>'+fmt(lateSum)+' attendus. Envoyez une relance pour accélérer le paiement.</span><br><button class="btn small" data-act="tab" data-v="reminders">Voir les relances</button></div>':'')+
    '<div class="section"><h2>Six derniers mois</h2><div class="panel">'+chart(s)+
    '<div class="legend"><span><i class="dot g"></i>Entrées</span><span><i class="dot b"></i>Sorties</span></div></div></div>'+
  '</div>';
};

views.invoices=function(){
  var counts={all:db.invoices.length,pending:0,late:0,paid:0};
  db.invoices.forEach(function(i){counts[invState(i)]++});
  var labels=[['all','Toutes'],['pending','En attente'],['late','En retard'],['paid','Payées']];
  var list=db.invoices.slice().sort(function(a,b){return b.date.localeCompare(a.date)||b.number.localeCompare(a.number)})
    .filter(function(i){return filter==='all'||invState(i)===filter});
  var rows=list.map(function(inv){
    var t=totals(inv),st=invState(inv),c=clientOf(inv.clientId);
    var chip=st==='paid'?'<span class="chip paid">Payée</span>':
      st==='late'?'<span class="chip late">En retard de '+daysBetween(inv.due,todayStr())+' j</span>':
      '<span class="chip pending">En attente</span>';
    return '<div class="item"><div class="top"><div><div class="t">'+esc(c.name)+'</div>'+
      '<div class="s">'+esc(inv.number)+', échéance le '+fdate(inv.due)+'</div>'+chip+'</div>'+
      '<div class="amt">'+fmt(t.ttc)+'</div></div>'+
      '<div class="acts"><button class="btn ghost small" data-act="viewInvoice" data-id="'+inv.id+'">Voir</button>'+
      (st!=='paid'?'<button class="btn small" data-act="payInvoice" data-id="'+inv.id+'">Marquer payée</button>':'')+
      '<button class="btn danger small" data-act="delInvoice" data-id="'+inv.id+'">Supprimer</button></div></div>';
  }).join('');
  return '<div class="wrap"><div class="head"><h1>Factures</h1><button class="btn" data-act="newInvoice">Nouvelle facture</button></div>'+
    '<div class="seg">'+labels.map(function(l){return '<button class="'+(filter===l[0]?'active':'')+'" data-act="setFilter" data-f="'+l[0]+'">'+l[1]+' ('+counts[l[0]]+')</button>'}).join('')+'</div>'+
    (rows?'<div class="list">'+rows+'</div>':'<div class="empty"><h2>Aucune facture ici</h2><p>'+(db.invoices.length?'Aucune facture ne correspond à ce filtre.':'Créez votre première facture en choisissant un client.')+'</p></div>')+
  '</div>';
};

views.clients=function(){
  var rows=db.clients.slice().sort(function(a,b){return a.name.localeCompare(b.name)}).map(function(c){
    var billed=db.invoices.filter(function(i){return i.clientId===c.id}).reduce(function(s,i){return s+totals(i).ttc},0);
    var contact=[c.email,c.phone].filter(Boolean).map(esc).join(', ');
    return '<div class="item"><div class="top"><div><div class="t">'+esc(c.name)+'</div><div class="s">'+(contact||'Pas de coordonnées')+'</div></div>'+
      '<div class="amt">'+fmt(billed)+'</div></div>'+
      '<div class="acts"><button class="btn ghost small" data-act="editClient" data-id="'+c.id+'">Modifier</button>'+
      '<button class="btn danger small" data-act="delClient" data-id="'+c.id+'">Supprimer</button></div></div>';
  }).join('');
  return '<div class="wrap"><div class="head"><div><h1>Clients</h1><p class="muted">Le montant affiché est le total facturé TTC.</p></div><button class="btn" data-act="newClient">Ajouter un client</button></div>'+
    (rows?'<div class="list">'+rows+'</div>':'<div class="empty"><h2>Aucun client</h2><p>Ajoutez un client pour pouvoir lui envoyer une facture.</p></div>')+'</div>';
};

function reminderText(inv,late){
  var c=clientOf(inv.clientId),amount=fmt(totals(inv).ttc),due=fdate(inv.due),sender=user.name;
  if(late>=30)return 'Bonjour '+c.name+',\n\nMalgré nos précédentes relances, la facture '+inv.number+' de '+amount+', échue le '+due+', reste impayée depuis '+late+' jours. Merci de la régler sous 48 heures, ou de nous contacter pour convenir d’un échéancier.\n\nCordialement,\n'+sender;
  if(late>=15)return 'Bonjour '+c.name+',\n\nSauf erreur de notre part, la facture '+inv.number+' de '+amount+', échue le '+due+', n’est toujours pas réglée ('+late+' jours de retard). Merci de procéder au paiement cette semaine.\n\nCordialement,\n'+sender;
  if(late>=1)return 'Bonjour '+c.name+',\n\nUn petit rappel : la facture '+inv.number+' de '+amount+' est arrivée à échéance le '+due+'. Si le paiement est déjà parti, merci d’ignorer ce message.\n\nCordialement,\n'+sender;
  return 'Bonjour '+c.name+',\n\nLa facture '+inv.number+' de '+amount+' arrive à échéance le '+due+'. Merci de prévoir son règlement.\n\nCordialement,\n'+sender;
}
function reminderCard(inv,late,soon){
  var c=clientOf(inv.clientId),m=reminderText(inv,late);msgs[inv.id]=m;
  var tone=soon?['soon','Rappel préventif']:late>=30?['late','Dernier avis']:late>=15?['late','Rappel ferme']:['pending','Rappel courtois'];
  var digits=(c.phone||'').replace(/\D/g,'');
  var subject=encodeURIComponent('Facture '+inv.number);
  return '<div class="item"><div class="top"><div><div class="t">'+esc(c.name)+'</div>'+
    '<div class="s">'+esc(inv.number)+', '+(soon?'échéance le '+fdate(inv.due):late+' jours de retard')+'</div>'+
    '<span class="chip '+tone[0]+'">'+tone[1]+'</span></div><div class="amt">'+fmt(totals(inv).ttc)+'</div></div>'+
    '<pre class="msg">'+esc(m)+'</pre>'+
    '<div class="acts"><button class="btn small" data-act="copyMsg" data-id="'+inv.id+'">Copier le message</button>'+
    (digits.length>=8?'<a class="btn ghost small" style="text-decoration:none;display:inline-flex;align-items:center" target="_blank" rel="noopener" href="https://wa.me/'+digits+'?text='+encodeURIComponent(m)+'">WhatsApp</a>':'')+
    (c.email?'<a class="btn ghost small" style="text-decoration:none;display:inline-flex;align-items:center" href="mailto:'+esc(c.email)+'?subject='+subject+'&body='+encodeURIComponent(m)+'">E-mail</a>':'')+
    '<button class="btn ghost small" data-act="payInvoice" data-id="'+inv.id+'">Marquer payée</button></div></div>';
}
views.reminders=function(){
  msgs={};
  var today=todayStr();
  var late=db.invoices.filter(function(i){return invState(i)==='late'}).map(function(i){return {i:i,n:daysBetween(i.due,today)}}).sort(function(a,b){return b.n-a.n});
  var soon=db.invoices.filter(function(i){return invState(i)==='pending'&&daysBetween(today,i.due)<=7}).sort(function(a,b){return a.due.localeCompare(b.due)});
  return '<div class="wrap"><div class="head"><div><h1>Relances</h1><p class="muted">Le ton du message s’adapte au retard. Copiez-le, ou envoyez-le par WhatsApp ou e-mail.</p></div></div>'+
    '<div class="section" style="margin-top:0"><h2>Factures en retard</h2>'+
    (late.length?'<div class="list" style="margin-top:12px">'+late.map(function(x){return reminderCard(x.i,x.n,false)}).join('')+'</div>':'<p class="muted" style="margin-top:8px">Aucune facture en retard.</p>')+'</div>'+
    '<div class="section"><h2>À échéance dans 7 jours</h2>'+
    (soon.length?'<div class="list" style="margin-top:12px">'+soon.map(function(i){return reminderCard(i,0,true)}).join('')+'</div>':'<p class="muted" style="margin-top:8px">Aucune échéance cette semaine.</p>')+'</div></div>';
};

views.cash=function(){
  var c=cashTotals();
  var mv=db.invoices.filter(function(i){return i.status==='paid'}).map(function(i){return {date:i.paidDate||i.date,label:'Paiement '+i.number,sub:clientOf(i.clientId).name,amt:totals(i).ttc,id:i.id,kind:'in'}})
    .concat(db.expenses.map(function(e){return {date:e.date,label:e.label,sub:'Dépense',amt:-e.amount,id:e.id,kind:'out'}}))
    .sort(function(a,b){return b.date.localeCompare(a.date)}).slice(0,40);
  var rows=mv.map(function(m){
    return '<div class="item"><div class="top"><div><div class="t">'+esc(m.label)+'</div><div class="s">'+esc(m.sub)+', '+fdate(m.date)+'</div></div>'+
      '<div class="amt '+(m.amt>=0?'pos':'neg')+'">'+(m.amt>=0?'+':'−')+fmt(Math.abs(m.amt))+'</div></div>'+
      (m.kind==='out'?'<div class="acts"><button class="btn danger small" data-act="delExpense" data-id="'+m.id+'">Supprimer</button></div>':'')+'</div>';
  }).join('');
  return '<div class="wrap"><div class="head"><div><h1>Trésorerie</h1><p class="muted">Montants TTC. Les entrées sont les factures marquées payées.</p></div></div>'+
    '<div class="figures"><div class="fig cash"><div class="l">Solde</div><div class="n">'+fmt(c.bal)+'</div></div>'+
    '<div class="fig"><div class="l"><span class="dot g"></span>Total encaissé</div><div class="n">'+fmt(c.inc)+'</div></div>'+
    '<div class="fig"><div class="l"><span class="dot b"></span>Total dépensé</div><div class="n">'+fmt(c.out)+'</div></div></div>'+
    '<div class="section"><h2>Ajouter une dépense</h2><div class="panel"><div class="expform">'+
    '<label class="full">Libellé<input id="x-label" placeholder="Loyer, internet, transport"></label>'+
    '<label>Montant ('+CURRENCY+')<input id="x-amount" type="number" inputmode="numeric" min="0"></label>'+
    '<label>Date<input id="x-date" type="date" value="'+todayStr()+'"></label>'+
    '<div class="full"><div id="x-err" class="err"></div><button class="btn block" data-act="saveExpense">Ajouter la dépense</button></div></div></div></div>'+
    '<div class="section"><h2>Mouvements récents</h2>'+(rows?'<div class="list" style="margin-top:12px">'+rows+'</div>':'<p class="muted" style="margin-top:8px">Aucun mouvement pour le moment.</p>')+'</div></div>';
};

views.reports=function(){
  var s=monthSeries(6).reverse();
  return '<div class="wrap"><div class="head"><div><h1>Rapports</h1><p class="muted">Synthèse mensuelle des six derniers mois.</p></div></div>'+
    '<div class="scroll"><table class="tbl"><thead><tr><th>Mois</th><th class="num">Facturé TTC</th><th class="num">TVA facturée</th><th class="num">Encaissé</th><th class="num">Dépensé</th></tr></thead><tbody>'+
    s.map(function(m){return '<tr><td>'+esc(m.long)+'</td><td class="num">'+fmt(m.billed)+'</td><td class="num">'+fmt(m.vat)+'</td><td class="num">'+fmt(m.income)+'</td><td class="num">'+fmt(m.expense)+'</td></tr>'}).join('')+
    '</tbody></table></div>'+
    '<p class="muted small" style="margin-top:12px">La TVA facturée est calculée sur les factures émises dans le mois. Vérifiez les taux et les délais de déclaration auprès de l’administration fiscale.</p></div>';
};

views.settings=function(){
  var pl=function(n,w){return n+' '+w+(n>1?'s':'')};
  var has=db.clients.length+db.invoices.length+db.expenses.length>0;
  return '<div class="wrap"><div class="head"><div><h1>Paramètres</h1><p class="muted">Gérez votre compte et vos données.</p></div></div>'+
    '<div class="section" style="margin-top:0"><h2>Compte</h2><div class="panel" style="margin-top:12px">'+
      '<label>Nom ou entreprise<input id="s-name" value="'+esc(user.name)+'"></label>'+
      '<p class="muted small" style="margin-bottom:12px">'+esc(user.email)+'</p>'+
      '<div id="s-err" class="err"></div>'+
      '<button class="btn" data-act="saveProfile">Enregistrer le nom</button></div></div>'+
    '<div class="section"><h2>Données</h2><div class="panel" style="margin-top:12px">'+
      '<p>'+(has?pl(db.clients.length,'client')+', '+pl(db.invoices.length,'facture')+', '+pl(db.expenses.length,'dépense')+' enregistrés.':'Aucune donnée enregistrée.')+'</p>'+
      '<p class="muted small" style="margin:6px 0 14px">Les données d’exemple servent à tester l’application. Réinitialisez pour repartir de zéro, ou chargez un nouveau jeu d’exemple.</p>'+
      '<div class="actions" style="justify-content:flex-start;margin-top:0">'+
        '<button class="btn" data-act="seedReplace">Charger les données d’exemple</button>'+
        '<button class="btn danger" data-act="resetData"'+(has?'':' disabled')+'>Réinitialiser les données</button></div></div></div>'+
    '<div class="section"><h2>Session</h2><div class="panel" style="margin-top:12px"><button class="btn ghost" data-act="logout">Se déconnecter</button></div></div></div>';
};

/* ---------- Navigation ---------- */
function buildNav(){
  $('#nav').innerHTML=NAV.map(function(n){
    return '<button data-act="tab" data-v="'+n.v+'"><svg viewBox="0 0 24 24" aria-hidden="true">'+ICONS[n.i]+'</svg><span class="lbl-s">'+n.s+'</span><span class="lbl-l">'+n.l+'</span></button>';
  }).join('')+'<div class="soon">Assistant fiscal IA : bientôt disponible.</div>';
}
function refresh(){
  if(!user)return;
  $('#userName').textContent=user.name;
  document.querySelectorAll('#nav button').forEach(function(b){b.classList.toggle('active',b.dataset.v===view)});
  $('#view').innerHTML=views[view]();
}
function go(v){view=v;refresh();$('#view').scrollTop=0}

/* ---------- Écrans de connexion ---------- */
function showScreen(name){
  $('#auth').hidden=name!=='auth';
  $('#app').hidden=name!=='app';
}
function renderAuth(){
  var reg=authMode==='register';
  $('#auth').innerHTML='<div class="authbox">'+
    '<div class="lockup">'+mark(44,'#0E2A47')+'<span class="wordmark">Ledgerly</span></div>'+
    '<h1>'+(reg?'Créez votre compte':'Content de vous revoir')+'</h1>'+
    '<p class="muted">Factures, TVA et trésorerie pour les petites entreprises.</p>'+
    '<div class="tabs"><button class="'+(reg?'active':'')+'" data-act="authTab" data-t="register">Créer un compte</button>'+
    '<button class="'+(reg?'':'active')+'" data-act="authTab" data-t="login">Se connecter</button></div>'+
    (reg?'<label>Nom ou entreprise<input id="a-name" autocomplete="name"></label>':'')+
    '<label>Adresse e-mail<input id="a-email" type="email" autocomplete="email" inputmode="email"></label>'+
    '<label>Mot de passe<input id="a-pw" type="password" autocomplete="'+(reg?'new-password':'current-password')+'"></label>'+
    '<div id="a-err" class="err" role="alert"></div>'+
    '<button class="btn block" data-act="'+(reg?'doRegister':'doLogin')+'">'+(reg?'Créer mon compte':'Se connecter')+'</button>'+
    '<p class="note">Version de démonstration : vos données restent dans ce navigateur.</p></div>';
}
function authErr(m){$('#a-err').textContent=m}
function startSession(u){
  user=u;LS.set('ledgerly:session',u.id);
  db=LS.get('ledgerly:data:'+u.id)||{clients:[],invoices:[],expenses:[]};
  db.clients=db.clients||[];db.invoices=db.invoices||[];db.expenses=db.expenses||[];
  view='dashboard';filter='all';
  showScreen('app');refresh();
}

/* ---------- Fenêtres, messages ---------- */
function openModal(html){$('#sheet').innerHTML=html;$('#modal').classList.add('open')}
function closeModal(){$('#modal').classList.remove('open');$('#sheet').innerHTML='';draft=null;editingClient=null;pendingConfirm=null}
var toastTimer=null;
function toast(m){var t=$('#toast');t.textContent=m;t.classList.add('show');clearTimeout(toastTimer);toastTimer=setTimeout(function(){t.classList.remove('show')},2600)}
function askConfirm(text,fn,label){
  pendingConfirm=fn;
  openModal('<h2>Confirmer</h2><p>'+esc(text)+'</p><div class="actions"><button class="btn ghost" data-act="closeModal">Annuler</button><button class="btn solid-danger" data-act="confirmYes">'+esc(label||'Supprimer')+'</button></div>');
}
async function copyText(t){
  try{await navigator.clipboard.writeText(t);toast('Message copié');return}catch(e){}
  try{
    var ta=document.createElement('textarea');ta.value=t;ta.style.position='fixed';ta.style.opacity='0';
    document.body.appendChild(ta);ta.select();var ok=document.execCommand('copy');document.body.removeChild(ta);
    toast(ok?'Message copié':'Copie impossible, sélectionnez le texte');
  }catch(e){toast('Copie impossible, sélectionnez le texte')}
}

/* ---------- Clients ---------- */
function openClientModal(id){
  var c=id?db.clients.find(function(x){return x.id===id}):{name:'',email:'',phone:''};
  if(!c)return;
  editingClient=id||null;
  openModal('<h2>'+(id?'Modifier le client':'Ajouter un client')+'</h2>'+
    '<label>Nom<input id="c-name" value="'+esc(c.name)+'"></label>'+
    '<label>Adresse e-mail<input id="c-email" type="email" inputmode="email" value="'+esc(c.email)+'"></label>'+
    '<label>Téléphone (avec l’indicatif, par exemple +241)<input id="c-phone" type="tel" inputmode="tel" value="'+esc(c.phone)+'"></label>'+
    '<div id="c-err" class="err"></div>'+
    '<div class="actions"><button class="btn ghost" data-act="closeModal">Annuler</button><button class="btn" data-act="saveClient">Enregistrer</button></div>');
}

/* ---------- Factures ---------- */
function linesHTML(){
  return draft.lines.map(function(l,i){
    return '<div class="line"><label class="l-desc-wrap">Description<input class="l-desc" value="'+esc(l.desc)+'"></label>'+
      '<label>Quantité<input class="l-qty" type="number" inputmode="decimal" min="0" step="any" value="'+esc(l.qty)+'"></label>'+
      '<label>Prix unitaire<input class="l-price" type="number" inputmode="decimal" min="0" step="any" value="'+esc(l.price)+'"></label>'+
      (draft.lines.length>1?'<button class="btn ghost rm" data-act="rmLine" data-i="'+i+'" aria-label="Retirer la ligne">Retirer</button>':'<span></span>')+'</div>';
  }).join('');
}
function draftTotals(){
  var t=totals({lines:draft.lines,vat:draft.vat});
  return '<div class="totals"><div><span>Total HT</span><span>'+fmt(t.ht)+'</span></div><div><span>TVA ('+draft.vat+' %)</span><span>'+fmt(t.tva)+'</span></div><div class="ttc"><span>Total TTC</span><span>'+fmt(t.ttc)+'</span></div></div>';
}
function openInvoiceModal(){
  if(!db.clients.length){toast('Ajoutez d’abord un client.');openClientModal();return}
  var t=todayStr();
  draft={clientId:db.clients[0].id,date:t,due:addDays(t,30),vat:VAT_RATES[0],lines:[{desc:'',qty:1,price:''}]};
  openModal('<h2>Nouvelle facture</h2>'+
    '<label>Client<select id="f-client">'+db.clients.map(function(c){return '<option value="'+c.id+'">'+esc(c.name)+'</option>'}).join('')+'</select></label>'+
    '<div class="row2"><label>Date<input type="date" id="f-date" value="'+draft.date+'"></label><label>Échéance<input type="date" id="f-due" value="'+draft.due+'"></label></div>'+
    '<div id="lines">'+linesHTML()+'</div>'+
    '<div style="margin:12px 0"><button class="btn ghost small" data-act="addLine">Ajouter une ligne</button></div>'+
    '<label>TVA<select id="f-vat">'+VAT_RATES.map(function(r){return '<option value="'+r+'">'+r+' %</option>'}).join('')+'</select></label>'+
    '<div id="f-totals">'+draftTotals()+'</div><div id="f-err" class="err"></div>'+
    '<div class="actions"><button class="btn ghost" data-act="closeModal">Annuler</button><button class="btn" data-act="saveInvoice">Enregistrer la facture</button></div>');
}
function syncDraft(){
  if(!draft||!document.getElementById('f-client'))return;
  draft.clientId=val('f-client');draft.date=val('f-date');draft.due=val('f-due');draft.vat=+val('f-vat');
  draft.lines=Array.prototype.map.call(document.querySelectorAll('#lines .line'),function(r){
    return {desc:r.querySelector('.l-desc').value,qty:r.querySelector('.l-qty').value,price:r.querySelector('.l-price').value};
  });
}
function openInvoiceView(id){
  var inv=db.invoices.find(function(i){return i.id===id});if(!inv)return;
  var c=clientOf(inv.clientId),t=totals(inv),st=invState(inv);
  var rows=inv.lines.map(function(l){var lt=(+l.qty||0)*(+l.price||0);return '<tr><td style="white-space:normal">'+esc(l.desc)+'</td><td class="num">'+esc(l.qty)+'</td><td class="num">'+fmt(+l.price||0)+'</td><td class="num">'+fmt(lt)+'</td></tr>'}).join('');
  openModal('<div class="inv-head"><div><h2>Facture '+esc(inv.number)+'</h2><p class="muted">Émise le '+fdate(inv.date)+', échéance le '+fdate(inv.due)+'</p></div>'+
    '<div><span class="chip '+st+'">'+(st==='paid'?'Payée':st==='late'?'En retard':'En attente')+'</span></div></div>'+
    '<div class="inv-head"><div><div class="muted small">De</div><strong>'+esc(user.name)+'</strong></div><div><div class="muted small">Pour</div><strong>'+esc(c.name)+'</strong><div class="muted small">'+esc(c.email)+'</div></div></div>'+
    '<div class="scroll"><table class="tbl"><thead><tr><th>Description</th><th class="num">Qté</th><th class="num">Prix</th><th class="num">Total</th></tr></thead><tbody>'+rows+'</tbody></table></div>'+
    '<div class="totals"><div><span>Total HT</span><span>'+fmt(t.ht)+'</span></div><div><span>TVA ('+inv.vat+' %)</span><span>'+fmt(t.tva)+'</span></div><div class="ttc"><span>Total TTC</span><span>'+fmt(t.ttc)+'</span></div></div>'+
    '<div class="actions no-print"><button class="btn ghost" data-act="closeModal">Fermer</button><button class="btn" data-act="print">Imprimer ou enregistrer en PDF</button></div>');
}

/* ---------- Données d'exemple ---------- */
function seedData(){
  var t=todayStr(),d=function(n){return addDays(t,n)};
  var cl=[['Boutique Mbolo','contact@boutique-mbolo.example','+241 06 00 00 01'],['Garage Ntoutoume','garage.ntoutoume@example.com','+241 06 00 00 02'],['Cabinet Obame & Associés','cabinet.obame@example.com','+241 06 00 00 03'],['Import-Export Moussavou','moussavou.ie@example.com','+241 06 00 00 04']]
    .map(function(a){return {id:uid(),name:a[0],email:a[1],phone:a[2]}});
  var L=function(desc,qty,price){return {desc:desc,qty:qty,price:price}};
  var defs=[
    [3,-130,-100,-95,[L('Licence initiale du logiciel',1,300000)]],
    [0,-100,-70,-65,[L('Logiciel de caisse, licence annuelle',1,240000)]],
    [1,-95,-65,null,[L('Installation et formation',2,85000)]],
    [1,-50,-20,null,[L('Module de facturation',1,120000)]],
    [2,-40,-10,null,[L('Abonnement trimestriel',3,30000)]],
    [0,-35,-5,-3,[L('Maintenance mensuelle',1,45000)]],
    [3,-20,10,null,[L('Logiciel de suivi des stocks',1,180000)]]
  ];
  defs.forEach(function(x){
    var date=d(x[1]);
    db.invoices.push({id:uid(),number:nextNumber(date),clientId:cl[x[0]].id,date:date,due:d(x[2]),vat:18,status:x[3]!==null?'paid':'pending',paidDate:x[3]!==null?d(x[3]):null,lines:x[4]});
  });
  [[-80,'Loyer du bureau',60000],[-50,'Loyer du bureau',60000],[-20,'Loyer du bureau',60000],[-60,'Abonnement internet',25000],[-30,'Abonnement internet',25000],[-10,'Transport et carburant',18000]]
    .forEach(function(e){db.expenses.push({id:uid(),date:d(e[0]),label:e[1],amount:e[2]})});
  db.clients=db.clients.concat(cl);
}

/* ---------- Actions ---------- */
var A={
  tab:function(d){go(d.v)},
  authTab:function(d){authMode=d.t;renderAuth()},
  doRegister:async function(){
    var name=val('a-name').trim(),email=val('a-email').trim().toLowerCase(),pw=val('a-pw');
    if(!name)return authErr('Entrez votre nom ou celui de votre entreprise.');
    if(!/^\S+@\S+\.\S+$/.test(email))return authErr('Entrez une adresse e-mail valide.');
    if(pw.length<6)return authErr('Le mot de passe doit contenir au moins 6 caractères.');
    var users=LS.get('ledgerly:users')||[];
    if(users.some(function(u){return u.email===email}))return authErr('Un compte existe déjà avec cet e-mail. Connectez-vous.');
    var u={id:uid(),name:name,email:email,hash:await hashPw(pw,email)};
    users.push(u);LS.set('ledgerly:users',users);startSession(u);
  },
  doLogin:async function(){
    var email=val('a-email').trim().toLowerCase(),pw=val('a-pw');
    var users=LS.get('ledgerly:users')||[];
    var h=await hashPw(pw,email);
    var u=users.find(function(x){return x.email===email&&x.hash===h});
    if(!u)return authErr('E-mail ou mot de passe incorrect.');
    startSession(u);
  },
  logout:function(){LS.set('ledgerly:session',null);user=null;db=null;authMode='login';renderAuth();showScreen('auth')},
  seed:function(){seedData();save();toast('Données d’exemple chargées');refresh()},

  saveProfile:function(){
    var name=val('s-name').trim(),err=$('#s-err');
    if(!name){err.textContent='Entrez un nom.';return}
    user.name=name;
    var users=LS.get('ledgerly:users')||[];
    users.forEach(function(u){if(u.id===user.id)u.name=name});
    LS.set('ledgerly:users',users);refresh();toast('Nom enregistré');
  },
  seedReplace:function(){
    var has=db.clients.length+db.invoices.length+db.expenses.length>0;
    var run=function(){db.clients=[];db.invoices=[];db.expenses=[];seedData();save();closeModal();refresh();toast('Données d’exemple chargées')};
    if(has)askConfirm('Les données actuelles seront remplacées par les données d’exemple. Continuer ?',run,'Remplacer');else run();
  },
  resetData:function(){
    askConfirm('Tous vos clients, factures et dépenses seront effacés. Cette action est définitive.',function(){db.clients=[];db.invoices=[];db.expenses=[];save();closeModal();refresh();toast('Données réinitialisées')},'Réinitialiser');
  },
  newClient:function(){openClientModal()},
  editClient:function(d){openClientModal(d.id)},
  saveClient:function(){
    var name=val('c-name').trim(),email=val('c-email').trim(),phone=val('c-phone').trim();
    var err=$('#c-err');
    if(!name){err.textContent='Entrez le nom du client.';return}
    if(email&&!/^\S+@\S+\.\S+$/.test(email)){err.textContent='Cette adresse e-mail n’est pas valide.';return}
    if(editingClient){var c=db.clients.find(function(x){return x.id===editingClient});c.name=name;c.email=email;c.phone=phone}
    else db.clients.push({id:uid(),name:name,email:email,phone:phone});
    save();closeModal();refresh();toast('Client enregistré');
  },
  delClient:function(d){
    var c=db.clients.find(function(x){return x.id===d.id});if(!c)return;
    if(db.invoices.some(function(i){return i.clientId===d.id}))return toast('Ce client a des factures. Supprimez-les d’abord.');
    askConfirm('Supprimer le client '+c.name+' ?',function(){db.clients=db.clients.filter(function(x){return x.id!==d.id});save();closeModal();refresh();toast('Client supprimé')});
  },

  newInvoice:function(){openInvoiceModal()},
  addLine:function(){syncDraft();draft.lines.push({desc:'',qty:1,price:''});$('#lines').innerHTML=linesHTML();$('#f-totals').innerHTML=draftTotals()},
  rmLine:function(d){syncDraft();draft.lines.splice(+d.i,1);$('#lines').innerHTML=linesHTML();$('#f-totals').innerHTML=draftTotals()},
  saveInvoice:function(){
    syncDraft();var err=$('#f-err');
    var lines=draft.lines.filter(function(l){return l.desc.trim()||l.price!==''});
    if(!draft.clientId){err.textContent='Choisissez un client.';return}
    if(!lines.length||lines.some(function(l){return !l.desc.trim()||!(+l.qty>0)||!(+l.price>=0)||l.price===''})){err.textContent='Chaque ligne doit avoir une description, une quantité et un prix.';return}
    if(!draft.date||!draft.due||draft.due<draft.date){err.textContent='L’échéance doit être égale ou postérieure à la date de la facture.';return}
    db.invoices.push({id:uid(),number:nextNumber(draft.date),clientId:draft.clientId,date:draft.date,due:draft.due,vat:draft.vat,status:'pending',paidDate:null,
      lines:lines.map(function(l){return {desc:l.desc.trim(),qty:+l.qty,price:+l.price}})});
    save();closeModal();view='invoices';filter='all';refresh();toast('Facture enregistrée');
  },
  viewInvoice:function(d){openInvoiceView(d.id)},
  payInvoice:function(d){var i=db.invoices.find(function(x){return x.id===d.id});if(!i)return;i.status='paid';i.paidDate=todayStr();save();refresh();toast('Facture marquée payée')},
  delInvoice:function(d){
    var i=db.invoices.find(function(x){return x.id===d.id});if(!i)return;
    askConfirm('Supprimer la facture '+i.number+' ?',function(){db.invoices=db.invoices.filter(function(x){return x.id!==d.id});save();closeModal();refresh();toast('Facture supprimée')});
  },
  setFilter:function(d){filter=d.f;refresh()},
  copyMsg:function(d){copyText(msgs[d.id]||'')},

  saveExpense:function(){
    var label=val('x-label').trim(),amount=+val('x-amount'),date=val('x-date'),err=$('#x-err');
    if(!label){err.textContent='Entrez un libellé.';return}
    if(!(amount>0)){err.textContent='Entrez un montant supérieur à zéro.';return}
    if(!date){err.textContent='Choisissez une date.';return}
    db.expenses.push({id:uid(),date:date,label:label,amount:amount});save();refresh();toast('Dépense ajoutée');
  },
  delExpense:function(d){db.expenses=db.expenses.filter(function(e){return e.id!==d.id});save();refresh();toast('Dépense supprimée')},

  closeModal:closeModal,
  confirmYes:function(){var f=pendingConfirm;if(f)f()},
  print:function(){try{window.print()}catch(e){toast('Impression indisponible ici. Ouvrez la page dans un navigateur.')}}
};

document.addEventListener('click',function(e){
  if(e.target.id==='modal'){closeModal();return}
  var t=e.target.closest('[data-act]');if(!t)return;
  var f=A[t.dataset.act];if(f)f(t.dataset,t);
});
document.addEventListener('input',function(e){
  if(draft&&e.target.closest('#modal')){syncDraft();var el=$('#f-totals');if(el)el.innerHTML=draftTotals()}
});
document.addEventListener('change',function(e){
  if(draft&&e.target.closest('#modal')){syncDraft();var el=$('#f-totals');if(el)el.innerHTML=draftTotals()}
});
document.addEventListener('keydown',function(e){
  if(e.key==='Escape'&&$('#modal').classList.contains('open'))closeModal();
  if(e.key==='Enter'&&e.target.closest&&e.target.closest('#auth')){e.preventDefault();(authMode==='register'?A.doRegister:A.doLogin)()}
});

/* ---------- Démarrage ---------- */
function boot(){
  $('#splashMark').innerHTML=mark(64,'#163B63');
  $('#topMark').innerHTML=mark(28,'var(--primary)');
  buildNav();
  var reduce=window.matchMedia&&window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  setTimeout(function(){
    var sid=LS.get('ledgerly:session'),users=LS.get('ledgerly:users')||[];
    var u=sid&&users.find(function(x){return x.id===sid});
    if(u)startSession(u);
    else{authMode=users.length?'login':'register';renderAuth();showScreen('auth')}
    $('#splash').classList.add('out');
    document.documentElement.classList.remove('splashing');
    setTimeout(function(){$('#splash').style.display='none'},reduce?0:500);
  },reduce?600:2600);
}
boot();
})();
</script>
</body>
</html>
