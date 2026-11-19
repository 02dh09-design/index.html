# index.html
Doniyor.1502 
<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Fizika formulalari</title>
<style>:root{--bg:#f5f6fa;--card:#fff;--fg:#1a1d2e;--muted:#6b7089;--acc:#5b5bf0;--line:#e3e5ef;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0e0f17;--card:#181a27;--fg:#eef0fa;--muted:#8d92ad;--acc:#8b8bff;--line:#262a3d}}:root[data-theme="dark"]{--bg:#0e0f17;--card:#181a27;--fg:#eef0fa;--muted:#8d92ad;--acc:#8b8bff;--line:#262a3d}*{box-sizing:border-box}body{margin:0;background:var(--bg);color:var(--fg);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;background-color:var(--bg)}header{position:sticky;top:env(safe-area-inset-top,0px);background:var(--bg);padding:12px 14px 8px;z-index:5}h1{margin:0 0 8px;font-size:20px}#q{width:100%;padding:11px 14px;border-radius:12px;border:1px solid var(--line);background:var(--card);color:var(--fg);font-size:16px}#chips{display:flex;gap:8px;overflow-x:auto;padding:10px 0 2px}.chip{flex:none;border:1px solid var(--line);background:var(--card);color:var(--fg);border-radius:999px;padding:8px 14px;font-size:14px}.chip.on{background:var(--acc);color:#fff;border-color:var(--acc)}main{padding:6px 14px 40px;max-width:720px;margin:0 auto}details{background:var(--card);border:1px solid var(--line);border-radius:14px;margin:10px 0;overflow:hidden}summary{padding:14px;font-weight:600;cursor:pointer}.f{padding:10px 14px;border-top:1px solid var(--line)}.f code{display:block;font-family:ui-monospace,Menlo,Consolas,monospace;font-size:17px;color:var(--acc);overflow-x:auto;white-space:nowrap}.f span{font-size:13px;color:var(--muted)}.sec{margin:14px 2px 0;font-size:13px;color:var(--muted);text-transform:uppercase;letter-spacing:.05em}#none{text-align:center;color:var(--muted);padding:30px}header,main{zoom:var(--z,1.3)}.zb{border:1px solid var(--line);background:var(--card);color:var(--fg);border-radius:10px;padding:6px 12px;font-size:16px}</style>
</head>
<body>
<header>
<div style="display:flex;align-items:center;justify-content:space-between;margin-bottom:8px"><h1 style="margin:0">⚛️ Fizika formulalari</h1><span><button class="zb" id="zm">A−</button> <button class="zb" id="zp">A+</button></span></div>
<input id="q" type="search" placeholder="Formula yoki mavzu qidirish…">
<div id="chips"></div>
</header>
<main id="m"></main>
<script>
var D=[
["Mexanika","⚙️",[
["Tekis va tezlanuvchan harakat",[
["v = s / t","tezlik"],
["a = (v − v₀) / t","tezlanish"],
["s = v₀t + at²/2","bosib o‘tilgan yo‘l"],
["v² = v₀² + 2as","vaqtsiz bog‘lanish"]]],
["Erkin tushish",[
["v = gt","tushish tezligi (g ≈ 9,8 m/s²)"],
["h = gt²/2","tushish balandligi"],
["v = √(2gh)","yerga urilish tezligi"]]],
["Aylana bo‘ylab harakat",[
["T = 1/ν","davr va chastota"],
["ω = 2π/T = 2πν","burchak tezlik"],
["v = ωR","chiziqli tezlik"],
["a = v²/R = ω²R","markazga intilma tezlanish"]]],
["Dinamika (Nyuton qonunlari)",[
["F = ma","Nyutonning 2-qonuni"],
["p = mv","impuls"],
["FΔt = Δp","kuch impulsi"],
["F = μN","ishqalanish kuchi"],
["F = kx","Guk qonuni (elastiklik kuchi)"]]],
["Butun olam tortishish",[
["F = G·m₁m₂/r²","tortishish kuchi (G = 6,67·10⁻¹¹)"],
["g = GM/R²","erkin tushish tezlanishi"],
["v₁ = √(gR) ≈ 7,9 km/s","birinchi kosmik tezlik"]]],
["Ish, energiya, quvvat",[
["A = F·s·cosα","mexanik ish"],
["N = A/t = F·v","quvvat"],
["Eₖ = mv²/2","kinetik energiya"],
["Eₚ = mgh","potensial energiya"],
["Eₚ = kx²/2","deformatsiyalangan prujina energiyasi"],
["η = Aₓ/Aₜ · 100%","foydali ish koeffitsiyenti"]]],
["Statika va gidrostatika",[
["M = F·d","kuch momenti"],
["p = F/S","bosim"],
["p = ρgh","suyuqlik ustuni bosimi"],
["Fₐ = ρgV","Arximed kuchi"]]]
]],
["Molekulyar fizika va termodinamika","🌡️",[
["Molekulyar-kinetik nazariya",[
["ν = m/M","modda miqdori"],
["N = νNₐ","molekulalar soni (Nₐ = 6,02·10²³)"],
["p = (1/3)n·m₀·v²","gaz bosimining asosiy tenglamasi"],
["Ē = (3/2)kT","molekula o‘rtacha kinetik energiyasi"],
["p = nkT","bosim va konsentratsiya"]]],
["Gaz qonunlari",[
["pV = (m/M)RT","Mendeleyev–Klapeyron tenglamasi"],
["p₁V₁/T₁ = p₂V₂/T₂","birlashgan gaz qonuni"],
["pV = const","izotermik jarayon (Boyl–Mariott)"],
["V/T = const","izobarik jarayon (Gey-Lyussak)"],
["p/T = const","izoxorik jarayon (Sharl)"]]],
["Termodinamika",[
["U = (3/2)νRT","ideal gaz ichki energiyasi"],
["ΔU = Q + A","termodinamikaning 1-qonuni"],
["Q = cmΔT","qizdirish uchun issiqlik miqdori"],
["Q = λm","erish issiqligi"],
["Q = rm","bug‘lanish issiqligi"],
["η = (T₁ − T₂)/T₁","Karno sikli FIK"]]]
]],["Elektr va magnetizm","⚡",[
["Elektrostatika",[
["F = k·q₁q₂/r²","Kulon qonuni (k = 9·10⁹)"],
["E = F/q","elektr maydon kuchlanganligi"],
["φ = W/q","potensial"],
["C = q/U","sig‘im"],
["C = ε₀εS/d","yassi kondensator sig‘imi"],
["W = CU²/2","kondensator energiyasi"]]],
["O‘zgarmas tok",[
["I = q/t","tok kuchi"],
["I = U/R","Om qonuni (zanjir qismi)"],
["R = ρl/S","o‘tkazgich qarshiligi"],
["I = ε/(R + r)","to‘liq zanjir uchun Om qonuni"],
["Q = I²Rt","Joul–Lens qonuni"],
["P = UI","tok quvvati"]]],
["Ketma-ket va parallel ulash",[
["R = R₁ + R₂","ketma-ket (I bir xil)"],
["1/R = 1/R₁ + 1/R₂","parallel (U bir xil)"]]],
["Magnetizm",[
["F = BIl·sinα","Amper kuchi"],
["F = qvB·sinα","Lorens kuchi"],
["Φ = BS·cosα","magnit oqimi"],
["ε = −ΔΦ/Δt","elektromagnit induksiya (Faradey)"],
["ε = Blv·sinα","harakatlanuvchi o‘tkazgichda EYuK"],
["W = LI²/2","g‘altak magnit maydon energiyasi"]]]
]],
["Tebranish va to‘lqinlar","🌊",[
["Mexanik tebranishlar",[
["x = A·cos(ωt)","garmonik tebranish tenglamasi"],
["T = 2π√(m/k)","prujinali mayatnik davri"],
["T = 2π√(l/g)","matematik mayatnik davri"],
["ω = 2π/T","siklik chastota"]]],
["Mexanik to‘lqinlar",[
["λ = vT","to‘lqin uzunligi"],
["v = λν","to‘lqin tezligi"]]],
["Elektromagnit tebranishlar",[
["T = 2π√(LC)","Tomson formulasi"],
["X_L = ωL","induktiv qarshilik"],
["X_C = 1/(ωC)","sig‘im qarshiligi"],
["Z = √(R² + (X_L − X_C)²)","to‘liq qarshilik"],
["U = U₀/√2","o‘zgaruvchan tokning effektiv qiymati"]]]
]],
["Optika","🔭",[
["Geometrik optika",[
["n = c/v","absolyut sindirish ko‘rsatkichi"],
["sinα / sinβ = n","sinish qonuni (Snellius)"],
["α = α′","qaytish qonuni"],
["1/F = 1/d + 1/f","yupqa linza formulasi"],
["D = 1/F","linzaning optik kuchi (dioptriya)"],
["Γ = f/d","chiziqli kattalashtirish"]]],
["To‘lqin optikasi",[
["d·sinφ = kλ","difraksion panjara maksimumi"],
["Δ = kλ","interferensiya maksimumi sharti"],
["Δ = (2k+1)λ/2","interferensiya minimumi sharti"]]]
]],
["Atom va yadro fizikasi","☢️",[
["Kvant fizikasi",[
["E = hν","foton energiyasi (h = 6,63·10⁻³⁴)"],
["hν = A + Eₖ","fotoeffekt uchun Eynshteyn tenglamasi"],
["p = h/λ","foton impulsi"],
["λ = h/(mv)","de Broyl to‘lqin uzunligi"]]],
["Yadro fizikasi",[
["E = mc²","massa va energiya bog‘lanishi"],
["ΔE = Δm·c²","yadroning bog‘lanish energiyasi"],
["N = N₀·2^(−t/T)","radioaktiv yemirilish qonuni"]]]
]]
];
var m=document.getElementById('m'),chips=document.getElementById('chips'),q=document.getElementById('q'),cur=0;
function esc(s){return s.replace(/&/g,'&amp;').replace(/</g,'&lt;')}
function render(){
var t=q.value.trim().toLowerCase(),h='',any=false;
D.forEach(function(s,i){
if(!t&&i!==cur)return;
var sh='';
s[2].forEach(function(tp){
var fs=tp[1].filter(function(f){return !t||(tp[0]+f[0]+f[1]).toLowerCase().indexOf(t)>-1});
if(!fs.length)return;
any=true;
sh+='<details'+(t?' open':'')+'><summary>'+esc(tp[0])+'</summary>'+fs.map(function(f){return '<div class="f"><code>'+esc(f[0])+'</code><span>'+esc(f[1])+'</span></div>'}).join('')+'</details>';
});
if(sh)h+=(t?'<div class="sec">'+s[1]+' '+esc(s[0])+'</div>':'')+sh;
});
m.innerHTML=any?h:'<div id="none">Hech narsa topilmadi</div>';
}
function chipsDraw(){
chips.innerHTML=D.map(function(s,i){return '<button class="chip'+(i===cur?' on':'')+'" data-i="'+i+'">'+s[1]+' '+esc(s[0])+'</button>'}).join('');
}
chips.onclick=function(e){var b=e.target.closest('.chip');if(!b)return;cur=+b.dataset.i;q.value='';chipsDraw();render();window.scrollTo(0,0)};
q.oninput=render;
chipsDraw();render();
var Z=1.3;function sz(d){Z=Math.max(0.8,Math.min(2.2,Z+d));document.documentElement.style.setProperty("--z",Z)}document.getElementById("zm").onclick=function(){sz(-0.15)};document.getElementById("zp").onclick=function(){sz(0.15)};sz(0);
</script>
</body>
</html>
