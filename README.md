# TesTanya‏<!DOCTYPE html>
‏<html lang="he" dir="rtl"><head><meta charset="utf-8">
‏<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
‏<meta name="theme-color" content="#ecebe7"><meta name="color-scheme" content="light dark">
‏<meta name="apple-mobile-web-app-capable" content="yes"><title>Testania · בוחן תניא</title>
‏<style>
‏:root{--bg:#ecebe7;--ink:#0a0a0a;--mut:rgba(10,10,10,.58);--glass:rgba(255,255,255,.66);--line:rgba(0,0,0,.08);--fill:rgba(0,0,0,.05);--g:#55b96a;--y:#f3c53f;--g2:#3a9a52;--sh:0 1px 0 rgba(255,255,255,.6) inset,0 14px 34px -14px rgba(0,0,0,.22)}
‏@media(prefers-color-scheme:dark){:root{--bg:#0c0c0b;--ink:#f5f5f2;--mut:rgba(245,245,242,.58);--glass:rgba(34,34,31,.6);--line:rgba(255,255,255,.1);--fill:rgba(255,255,255,.08);--sh:0 1px 0 rgba(255,255,255,.07) inset,0 14px 34px -14px rgba(0,0,0,.7)}}
‏*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
‏html{background:var(--bg)}
‏body{margin:0;color:var(--ink);font-family:-apple-system,BlinkMacSystemFont,"SF Pro Text","SF Hebrew","Segoe UI",system-ui,Arial,sans-serif;line-height:1.5;min-height:100vh;-webkit-font-smoothing:antialiased;padding:env(safe-area-inset-top,0) 0 env(safe-area-inset-bottom,0)}
‏main{position:relative;z-index:1;max-width:560px;margin:0 auto;padding:8px 16px 48px}
‏.hd{margin:16px 0 30px}
‏.bh{font-size:1.05rem;font-weight:800;text-align:right;padding-right:10%;margin-bottom:6px}
‏.logo{position:relative;direction:ltr;width:max-content;max-width:100%;margin:0 auto;display:flex;flex-direction:column;font-weight:900}
‏.logo::before{content:"";position:absolute;left:50%;top:52%;width:47%;aspect-ratio:1;border-radius:50%;background:var(--y);transform:translate(-50%,-50%)}
‏.wm{position:relative;font-family:Impact,Haettenschweiler,"Arial Narrow Bold","Arial Black",sans-serif;font-size:min(25vw,150px);line-height:.92;letter-spacing:-.06em;background:linear-gradient(90deg,var(--ink) 0 37%,var(--g) 37%);-webkit-background-clip:text;background-clip:text;color:transparent}
‏.tg{position:relative;direction:rtl;align-self:flex-start;margin:-.1em 0 0 6%;font-size:min(8.6vw,52px);letter-spacing:-.02em;line-height:1.1;color:var(--ink)}
‏.card{background:var(--glass);-webkit-backdrop-filter:blur(30px) saturate(1.7);backdrop-filter:blur(30px) saturate(1.7);border:1px solid var(--line);border-radius:28px;padding:20px;margin-bottom:14px;box-shadow:var(--sh)}
‏.eb{font-size:.74rem;font-weight:700;letter-spacing:.06em;color:var(--mut);margin:0 4px 8px;display:block}
‏.two{display:grid;grid-template-columns:2fr 1fr;gap:10px}
‏select,textarea,input{width:100%;font:inherit;font-size:1.05rem;font-weight:600;color:var(--ink);background:var(--fill);border:0;border-radius:16px;padding:14px 16px;outline:0}
‏select{-webkit-appearance:none;appearance:none;padding-left:38px;background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='14' height='9' fill='none' stroke='%238a8a85' stroke-width='2' stroke-linecap='round'%3E%3Cpath d='M1 1l6 6 6-6'/%3E%3C/svg%3E");background-repeat:no-repeat;background-position:left 14px center}
‏textarea{min-height:104px;resize:vertical;line-height:1.7}
‏select:focus-visible,textarea:focus-visible,input:focus-visible,button:focus-visible,summary:focus-visible{box-shadow:0 0 0 3px var(--g)}
‏button{font:inherit;font-weight:700;min-height:48px;padding:0 22px;border:0;border-radius:999px;background:var(--ink);color:var(--bg);transition:transform .15s,opacity .15s}
‏button:active{transform:scale(.96)}button:disabled{opacity:.4}
‏button.sec{background:var(--fill);color:var(--ink)}
‏.row{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
‏#rec{width:100%;height:76px;border-radius:38px;font-size:1.2rem;letter-spacing:-.01em;display:flex;align-items:center;justify-content:center;gap:12px}
‏#rec::before{content:"";width:14px;height:14px;border-radius:50%;background:var(--y)}
‏#rec.on{background:var(--y);color:#0a0a0a;animation:ring 1.4s infinite}#rec.on::before{background:#0a0a0a}
‏@keyframes ring{0%{box-shadow:0 0 0 0 rgba(243,197,63,.65)}100%{box-shadow:0 0 0 24px rgba(243,197,63,0)}}
‏#status,#micnote,#prog,#warn{font-size:.9rem;font-weight:600;color:var(--mut);margin:10px 4px 0}
‏#status:empty,#micnote:empty,#prog:empty,#warn:empty{display:none}
‏details{margin-top:14px}summary{font-size:.9rem;font-weight:700;color:var(--mut);cursor:pointer;padding:4px;border-radius:8px}
‏details textarea,details input{margin-top:10px}
‏#dl{margin-top:12px;width:100%;background:var(--g);color:#0a0a0a}
‏#res:not([hidden]){animation:up .5s cubic-bezier(.2,.8,.2,1)}
‏@keyframes up{from{opacity:0;transform:translateY(18px) scale(.98)}}
‏#score{--p:0;position:relative;width:176px;height:176px;margin:4px auto 18px;border-radius:50%;display:grid;place-items:center;text-align:center;background:conic-gradient(var(--g) calc(var(--p)*1%),var(--fill) 0)}
‏#score::before{content:"";position:absolute;inset:14px;border-radius:50%;background:var(--bg)}
‏#score b,#score small{position:relative}
‏#score b{font-size:3.4rem;font-weight:900;letter-spacing:-.05em;line-height:1;display:block}#score b i{font-style:normal;font-size:1.4rem;letter-spacing:0}
‏#score small{position:absolute;bottom:34px;font-size:.78rem;font-weight:700;color:var(--mut)}
‏.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:8px}
‏.stats div{background:var(--fill);border-radius:18px;padding:10px 4px;text-align:center}
‏.stats b{display:block;font-size:1.4rem;font-weight:800;letter-spacing:-.03em}.stats span{font-size:.72rem;font-weight:600;color:var(--mut)}
‏#out{font-size:1.35rem;font-weight:700;line-height:2.15;margin-top:18px}
‏.w{padding:2px 8px;margin:0 1px;display:inline-block;border-radius:9px;cursor:pointer;transition:transform .12s}.w:active{transform:scale(.94)}
‏.ok{background:rgba(85,185,106,.28)}.bad{background:var(--ink);color:var(--bg)}.mis{background:rgba(243,197,63,.5)}.ext{text-decoration:line-through;opacity:.5}
‏#tip{margin-top:12px;font-size:.92rem;font-weight:600;min-height:1.4em}
‏.legend{margin-top:10px;font-size:.78rem;display:flex;gap:6px;flex-wrap:wrap}.legend .w{cursor:default;font-size:.78rem;padding:1px 8px}
‏table{width:100%;border-collapse:collapse;font-size:.92rem;font-weight:600}th{font-size:.72rem;color:var(--mut);font-weight:700}td,th{padding:9px 4px;border-bottom:1px solid var(--line);text-align:right}
‏.tab{overflow-x:auto;margin:6px 0}
‏@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
‏</style></head><body>
‏<main>
‏<header class="hd"><div class="bh">ב״ה</div><h1 class="logo" aria-label="Testania, פשוט ושנננתם"><span class="wm">Testania</span><span class="tg">פשוט ושננתם</span></h1></header>

‏<section class="card">
‏<div class="two"><div><label class="eb" for="book">חלק</label><select id="book"></select></div>
‏<div><label class="eb" for="ch">פרק</label><select id="ch"></select></div></div>
‏<button id="dl" hidden>הורד את כל התניא (פעם אחת)</button><div id="prog" aria-live="polite"></div><div id="warn"></div>
‏<details><summary>טקסט חופשי וספרייה אישית</summary>
‏<textarea id="src" placeholder="הדבק כאן טקסט מקור. הוא יוסתר בזמן הבחינה"></textarea>
‏<input id="nm" placeholder="שם לשמירה, למשל פרק ב"><div class="row"><button class="sec" id="sv">שמור בספרייה</button></div></details>
‏</section>

‏<section class="card">
‏<button id="rec">התחל הקלטה</button>
‏<div id="status" aria-live="polite"></div><div id="micnote"></div>
‏<details open><summary>תמלול · אפשר גם להכתיב עם המיקרופון שבמקלדת</summary>
‏<textarea id="spk" placeholder="כאן יופיע מה ששמענו"></textarea>
‏<div class="row"><button id="chk">בדוק</button><button class="sec" id="clr">נקה</button></div></details>
‏</section>

‏<section class="card" id="res" hidden>
‏<div id="score"></div><div class="stats" id="stats"></div><div id="out"></div>
‏<div id="tip">גע במילה לפרטים</div><div class="row"><button id="nx">לפרק הבא</button></div>
‏<div class="legend"><span class="w ok">נכון</span><span class="w bad">שגוי</span><span class="w mis">חסר</span><span class="w ext">תוספת</span></div>
‏</section>

‏<section class="card"><span class="eb">היסטוריה והתקדמות</span><div class="tab" id="hist"></div>
‏<div class="row"><button class="sec" id="exp">ייצוא גיבוי</button><button class="sec" id="wipe">מחיקה</button></div></section>
‏</main>
‏<script>
‏const $=id=>document.getElementById(id);const ld=()=>{try{return JSON.parse(localStorage.getItem('tt')||'[]')}catch(e){return[]}};let T=ld();
// ---- בחירת קטע
‏const bk=$('book'),chs=$('ch');
‏function fillCh(){chs.textContent='';const b=T[bk.value];if(!b)return;Object.keys(b.c).forEach(k=>chs.add(new Option(k,k)))}
‏bk.onchange=fillCh;fillCh();
‏function refresh(){bk.textContent='';T.forEach((x,i)=>bk.add(new Option(x.b,i)));fillCh();$('dl').hidden=!!localStorage.getItem('dld');$('warn').textContent=T.length?'':'עדיין אין פרקים במכשיר. לחץ על ההורדה, או הדבק טקסט חופשי.'}
‏refresh();
‏const SF='https://www.sefaria.org/api/';
‏const flat=x=>typeof x==='string'?[x]:(x||[]).flatMap(flat);
‏const cln=t=>t.replace(/<sup[^>]*>[\s\S]*?<\/sup>/g,' ').replace(/<i class="footnote">[\s\S]*?<\/i>/g,' ').replace(/<[^>]+>/g,' ').replace(/&\w+;/g,' ').replace(/\u05BE/g,' ').replace(/[\u0591-\u05C7]/g,'').replace(/\s+/g,' ').trim();
‏const BOOKS=[['Tanya, Part I; Likkutei Amarim','ליקוטי אמרים'],['Tanya, Part II; Shaar HaYichud VehaEmunah','שער היחוד והאמונה'],['Tanya, Part III; Iggeret HaTeshuvah','אגרת התשובה'],['Tanya, Part IV; Iggeret HaKodesh','אגרת הקודש'],['Tanya, Part V; Kuntres Acharon','קונטרס אחרון']];
‏async function getCh(ref){for(let k=0;k<3;k++){try{const r=await fetch(SF+'texts/'+encodeURIComponent(ref)+'?context=0&commentary=0');const d=await r.json();if(d.error)return '';return flat(d.he).map(cln).join(' ').trim()}catch(e){await new Promise(r=>setTimeout(r,700))}}throw new Error('אין חיבור ל-Sefaria')}
‏$('dl').onclick=async()=>{const bt=$('dl'),pr=$('prog');bt.disabled=true;const out=[];
‏try{for(const [ref,name] of BOOKS){const c={};let ch=1,done=false;
‏while(!done&&ch<=80){const idx=[];for(let i=0;i<8;i++)idx.push(ch+i);
‏const res=await Promise.all(idx.map(n=>getCh(ref+' '+n)));
‏for(let i=0;i<res.length;i++){if(!res[i]){done=true;break}c[idx[i]]=res[i]}
‏ch+=8;pr.textContent='מוריד: '+name+' ('+Object.keys(c).length+' פרקים)'}
‏if(Object.keys(c).length)out.push({b:name,c})}
‏if(!out.length)throw new Error('לא התקבלו פרקים');
‏T=out.concat(T.filter(x=>x.b==='הספרייה שלי'));
‏localStorage.setItem('tt',JSON.stringify(T));localStorage.setItem('dld','1');refresh();
‏pr.textContent='הורדו '+out.reduce((a,b)=>a+Object.keys(b.c).length,0)+' פרקים ב-'+out.length+' חלקים. אפשר להתחיל!'}
‏catch(e){pr.textContent='ההורדה נכשלה ('+e.message+'). ייתכן שהדף נפתח בתצוגה מוגבלת בלי אינטרנט. פתח אותו ב-Chrome או Safari דרך כתובת https, או הדבק טקסט ושמור בספרייה.'}bt.disabled=false};
‏$('nx').onclick=()=>{if(chs.selectedIndex<chs.options.length-1)chs.selectedIndex++;else if(bk.selectedIndex<bk.options.length-1){bk.selectedIndex++;fillCh()}$('clr').click();window.scrollTo({top:0,behavior:'smooth'})};
‏const source=()=>$('src').value.trim()||(T[bk.value]&&T[bk.value].c[chs.value])||'';
// ---- נרמול והשוואה
‏const norm=w=>w.replace(/[\u0591-\u05C7]/g,'').replace(/[^\u05D0-\u05EA]/g,'').replace(/[ךםןףץ]/g,c=>({ך:'כ',ם:'מ',ן:'נ',ף:'פ',ץ:'צ'}[c]));
‏const soft=w=>{const n=norm(w);return (n[0]+n.slice(1).replace(/[וי]/g,'')).replace(/[תטס]/g,'ת').replace(/[חקכ]/g,'כ').replace(/ע/g,'א')};
‏const words=s=>s.replace(/\u05BE/g,' ').split(/\s+/).map(w=>({raw:w,n:norm(w)})).filter(x=>x.n);
‏function align(A,B){const n=A.length,m=B.length,D=Array.from({length:n+1},()=>new Uint32Array(m+1));
‏const a=A.map(x=>soft(x.raw)),b=B.map(x=>soft(x.raw));
‏for(let i=0;i<=n;i++)D[i][0]=i;for(let j=0;j<=m;j++)D[0][j]=j;
‏for(let i=1;i<=n;i++)for(let j=1;j<=m;j++)D[i][j]=Math.min(D[i-1][j-1]+(a[i-1]===b[j-1]?0:1),D[i-1][j]+1,D[i][j-1]+1);
‏const o=[];let i=n,j=m;while(i>0||j>0){
‏if(i&&j&&D[i][j]===D[i-1][j-1]+(a[i-1]===b[j-1]?0:1)){o.push({t:a[i-1]===b[j-1]?'ok':'bad',a:A[i-1],b:B[j-1]});i--;j--}
‏else if(i&&D[i][j]===D[i-1][j]+1){o.push({t:'mis',a:A[i-1]});i--}else{o.push({t:'ext',b:B[j-1]});j--}}
‏return o.reverse()}
// ---- היסטוריה
‏const H=()=>{try{return JSON.parse(localStorage.getItem('th')||'[]')}catch(e){return[]}};
‏const saveH=h=>{try{localStorage.setItem('th',JSON.stringify(h))}catch(e){}};
‏function renderH(){const h=H(),el=$('hist');el.textContent='';
‏if(!h.length){el.textContent='עוד אין בחינות.';return}
‏const t=document.createElement('table');t.innerHTML='<tr><th>קטע</th><th>אחרון</th><th>הכי טוב</th><th>פעמים</th></tr>';
‏const g={};h.forEach(x=>{(g[x.k]=g[x.k]||[]).push(x)});
‏Object.keys(g).forEach(k=>{const a=g[k],r=t.insertRow();
‏[k,a[a.length-1].s+'%',Math.max(...a.map(x=>x.s))+'%',a.length].forEach(v=>r.insertCell().textContent=v)});el.append(t)}
‏renderH();
‏$('exp').onclick=()=>{const u=URL.createObjectURL(new Blob([JSON.stringify(H())],{type:'application/json'}));const a=document.createElement('a');a.href=u;a.download='tanya-history.json';a.click()};
‏$('wipe').onclick=()=>{if(confirm('למחוק את כל ההיסטוריה?')){saveH([]);renderH()}};
// ---- בדיקה
‏function check(){const A=words(source()),B=words($('spk').value);
‏if(!A.length){$('status').textContent='אין טקסט מקור לפרק הזה';return}
‏if(!B.length){$('status').textContent='לא זוהה דיבור, נסה שוב';return}
‏$('status').textContent='';const ops=align(A,B),c={ok:0,bad:0,mis:0,ext:0},out=$('out');out.textContent='';
‏ops.forEach(o=>{c[o.t]++;const s=document.createElement('span');s.className='w '+o.t;s.textContent=o.t==='ext'?o.b.raw:o.a.raw;
‏s.onclick=()=>{$('tip').textContent=o.t==='ok'?'נכון':o.t==='bad'?`במקור: ${o.a.raw} · נאמר: ${o.b.raw}`:o.t==='mis'?`לא נאמרה: "${o.a.raw}"`:`מיותרת: "${o.b.raw}"`};out.append(s,' ')});
‏const sc=Math.round(c.ok/A.length*100);$('score').style.setProperty('--p',sc);$('score').innerHTML='<b>'+sc+'<i>%</i></b><small>דיוק</small>';
‏$('stats').innerHTML=[['נכון',c.ok],['שגוי',c.bad],['חסר',c.mis],['תוספת',c.ext]].map(([l,v])=>`<div><b>${v}</b><span>${l}</span></div>`).join('');$('res').hidden=false;$('res').scrollIntoView({behavior:'smooth'});
‏const k=$('src').value.trim()?'טקסט חופשי':(T[bk.value]?T[bk.value].b+' '+chs.value:'?');
‏const h=H();h.push({k,s:sc,d:Date.now()});saveH(h);renderH()}
‏$('chk').onclick=check;
‏$('sv').onclick=()=>{const t=$('src').value.trim(),n=$('nm').value.trim();if(!t||!n){$('warn').textContent='צריך טקסט ושם';return}
‏let b=T.find(x=>x.b==='הספרייה שלי');if(!b){b={b:'הספרייה שלי',c:{}};T.push(b)}b.c[n]=t;
‏try{localStorage.setItem('tt',JSON.stringify(T))}catch(e){}refresh();bk.value=T.indexOf(b);fillCh();chs.value=n;$('src').value='';$('nm').value='';$('warn').textContent='נשמר בספרייה ✓'};
‏$('clr').onclick=()=>{$('spk').value='';$('res').hidden=true;$('status').textContent=''};
// ---- הקלטה
‏const SR=window.SpeechRecognition||window.webkitSpeechRecognition;let rec,on=false,base='';if(!SR||location.protocol==='file:')$('micnote').textContent='אם המיקרופון חסום: פתח את הדף ב-Chrome או Safari דרך כתובת https (לא מתוך תצוגה מקדימה), ובאייפון הפעל הכתבה בהגדרות המקלדת.';
‏$('rec').onclick=()=>{
‏if(!SR){$('status').textContent='הדפדפן לא תומך בזיהוי דיבור. הכתב בתמלול עם המיקרופון שבמקלדת ולחץ בדוק.';return}
‏if(on){on=false;rec.stop();return}
‏rec=new SR();rec.lang='he-IL';rec.continuous=true;rec.interimResults=true;base='';
‏rec.onresult=e=>{let t='';for(let i=0;i<e.results.length;i++)t+=e.results[i][0].transcript+' ';$('spk').value=(base+t).trim()};
‏rec.onerror=e=>{on=false;$('status').textContent=(e.error==='not-allowed'||e.error==='service-not-allowed')?'אין גישה למיקרופון. אשר אותה בהגדרות הדפדפן, או הכתב בתמלול עם המיקרופון שבמקלדת ולחץ בדוק.':'שגיאה: '+e.error};
‏rec.onend=()=>{if(on){base=$('spk').value+' ';try{rec.start();return}catch(_){}}
‏$('rec').classList.remove('on');$('rec').textContent='התחל הקלטה';$('status').textContent='בודק...';setTimeout(check,300)};
‏$('spk').value='';try{rec.start();on=true;$('rec').classList.add('on');$('rec').textContent='עצור';$('status').textContent='מקשיב...'}catch(e){}};

‏</script></body></html>
