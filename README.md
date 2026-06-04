<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>صيدلية مستشفى الثدي — NCI</title>
<link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800;900&display=swap" rel="stylesheet">
<style>
:root{--navy:#0b1f35;--navy2:#132d46;--teal:#0da88f;--gold:#f5b731;--rose:#e8405a;--bg:#edf2f7;--card:#fff;--border:#cdd9e8;--text:#1a2e3e;--muted:#6b8294;--green:#16a34a;}
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:'Tajawal',sans-serif;background:var(--bg);color:var(--text);min-height:100vh;}
header{background:linear-gradient(135deg,var(--navy),#1b4a6e);color:#fff;padding:14px 22px;display:flex;align-items:center;justify-content:space-between;box-shadow:0 4px 20px rgba(0,0,0,.35);}
.logo h1{font-size:1.05rem;font-weight:800;}
.logo p{font-size:.72rem;opacity:.6;margin-top:2px;}
.hbadge{background:var(--teal);color:#fff;border-radius:20px;padding:4px 14px;font-size:.78rem;font-weight:700;}
nav{background:var(--navy2);display:flex;padding:0 22px;overflow-x:auto;}
.nb{background:none;border:none;color:rgba(255,255,255,.5);font-family:'Tajawal',sans-serif;font-size:.88rem;font-weight:600;padding:12px 16px;cursor:pointer;border-bottom:3px solid transparent;transition:all .2s;white-space:nowrap;}
.nb.active{color:#fff;border-bottom-color:var(--teal);}
.nb:hover:not(.active){color:rgba(255,255,255,.8);}
.main{padding:18px 22px;max-width:960px;margin:0 auto;}
.card{background:var(--card);border-radius:14px;border:1px solid var(--border);box-shadow:0 2px 10px rgba(0,0,0,.06);margin-bottom:14px;overflow:hidden;}
.ch{padding:13px 18px;display:flex;align-items:center;gap:9px;border-bottom:1px solid var(--bg);}
.ch h2{font-size:.92rem;font-weight:700;}
.dot{width:9px;height:9px;border-radius:50%;}
.dn{background:var(--navy)}.dt{background:var(--teal)}.dg{background:var(--gold)}.dr{background:var(--rose)}
.cb{padding:16px 18px;}
.fg{display:grid;grid-template-columns:repeat(auto-fill,minmax(175px,1fr));gap:11px;}
.f{display:flex;flex-direction:column;gap:4px;}
.f label{font-size:.73rem;font-weight:700;color:var(--muted);}
.req{color:var(--rose);}
.f input,.f select,.f textarea{border:1.5px solid var(--border);border-radius:8px;padding:8px 11px;font-family:'Tajawal',sans-serif;font-size:.9rem;color:var(--text);background:var(--bg);outline:none;transition:border-color .2s;}
.f input:focus,.f select:focus,.f textarea:focus{border-color:var(--teal);box-shadow:0 0 0 3px rgba(13,168,143,.12);background:#fff;}
.f input.err{border-color:var(--rose)!important;background:#fff5f6!important;}
.s2{grid-column:span 2}
.dsec{padding:14px 18px 0;}
.dtitle{font-size:.82rem;font-weight:700;color:var(--teal);margin-bottom:10px;}
.drow{display:grid;grid-template-columns:2fr 0.8fr 1fr auto;gap:8px;margin-bottom:8px;align-items:end;}
.addbtn{background:none;border:1.5px dashed var(--teal);color:var(--teal);border-radius:8px;padding:7px 14px;font-family:'Tajawal',sans-serif;font-size:.82rem;font-weight:700;cursor:pointer;margin:4px 0 14px;display:inline-flex;align-items:center;gap:5px;}
.addbtn:hover{background:#e0fdf4;}
.delbtn{background:#fff0f3;border:1.5px solid #fcc;color:var(--rose);border-radius:7px;padding:7px 9px;cursor:pointer;height:36px;display:flex;align-items:center;font-size:.9rem;}
.ztog{display:flex;align-items:center;gap:11px;padding:11px 18px;background:#fff8f9;border-top:1px solid #fde8ec;}
.sw{position:relative;width:40px;height:21px;flex-shrink:0;}
.sw input{opacity:0;width:0;height:0;}
.sl{position:absolute;cursor:pointer;inset:0;background:#cdd9e8;border-radius:21px;transition:.3s;}
.sl:before{content:"";position:absolute;width:15px;height:15px;right:3px;bottom:3px;background:#fff;border-radius:50%;transition:.3s;}
.sw input:checked+.sl{background:var(--rose);}
.sw input:checked+.sl:before{transform:translateX(-19px);}
#zf{display:none;padding:10px 18px 14px;background:#fff8f9;border-top:1px solid #fde8ec;}
.btn{padding:9px 20px;border:none;border-radius:9px;font-family:'Tajawal',sans-serif;font-size:.9rem;font-weight:700;cursor:pointer;transition:all .2s;display:inline-flex;align-items:center;gap:6px;}
.bt{background:var(--teal);color:#fff;}
.bt:hover{background:#0b9680;transform:translateY(-1px);}
.bt:disabled{opacity:.6;cursor:not-allowed;transform:none;}
.bg{background:var(--bg);color:var(--text);border:1.5px solid var(--border);}
.bg:hover{background:#dde8f2;}
.be{background:linear-gradient(135deg,var(--navy),var(--teal));color:#fff;}
.msg{padding:11px 15px;border-radius:8px;font-weight:600;font-size:.86rem;margin:0 18px 14px;}
.mok{background:#e0fdf4;color:#065f46;border:1px solid #a7f3d0;}
.mer{background:#fff0f3;color:var(--rose);border:1px solid #fcc;}
.tw{overflow-x:auto;}
table{width:100%;border-collapse:collapse;font-size:.8rem;min-width:700px;}
thead tr{background:var(--navy);color:#ddf0ff;}
thead th{padding:9px 11px;font-weight:600;text-align:right;white-space:nowrap;}
tbody tr{border-bottom:1px solid #eef3f8;transition:background .15s;}
tbody tr:hover{background:#f0faff;}
tbody td{padding:8px 11px;vertical-align:middle;}
.tag{display:inline-block;border-radius:20px;padding:2px 8px;font-size:.7rem;font-weight:700;}
.tf{background:#e0fdf4;color:#065f46}.tn{background:#fef3c7;color:#92400e}.ti{background:#ede9fe;color:#5b21b6}.ts{background:#fee2e2;color:#991b1b}
.stag{border-radius:20px;padding:2px 8px;font-size:.7rem;font-weight:700;}
.spend{background:#fef3c7;color:#92400e}.sdone{background:#e0fdf4;color:#065f46}
.dbtn{background:none;border:none;color:var(--rose);cursor:pointer;padding:3px 7px;border-radius:5px;}
.dbtn:hover{background:#fff0f3;}
.fb{display:flex;flex-wrap:wrap;gap:9px;align-items:center;padding:11px 18px;border-bottom:1px solid var(--bg);}
.fb label{font-size:.75rem;font-weight:700;color:var(--muted);}
.fb input,.fb select{border:1.5px solid var(--border);border-radius:7px;padding:5px 9px;font-family:'Tajawal',sans-serif;font-size:.82rem;background:var(--bg);outline:none;}
.cnt{background:var(--teal);color:#fff;border-radius:20px;padding:2px 10px;font-size:.73rem;font-weight:700;margin-right:auto;}
.pag{display:flex;align-items:center;justify-content:center;gap:5px;padding:10px;}
.pag button{padding:4px 10px;border:1.5px solid var(--border);border-radius:6px;background:var(--bg);font-family:'Tajawal',sans-serif;font-size:.8rem;cursor:pointer;}
.pag button:hover,.pag button.on{background:var(--teal);color:#fff;border-color:var(--teal);}
.pag span{color:var(--muted);font-size:.78rem;}
.pg{display:none;}.pg.active{display:block;}
.spin{display:inline-block;width:14px;height:14px;border:2px solid rgba(255,255,255,.4);border-top-color:#fff;border-radius:50%;animation:sp .7s linear infinite;vertical-align:middle;}
@keyframes sp{to{transform:rotate(360deg)}}
#toast{position:fixed;bottom:20px;left:50%;transform:translateX(-50%) translateY(80px);background:var(--navy);color:#fff;padding:10px 22px;border-radius:40px;font-size:.85rem;font-weight:600;box-shadow:0 6px 20px rgba(0,0,0,.25);transition:transform .3s;z-index:999;}
#toast.show{transform:translateX(-50%) translateY(0);}
/* setup */
#setup{position:fixed;inset:0;background:rgba(11,31,53,.8);z-index:900;display:flex;align-items:center;justify-content:center;}
#setupBox{background:#fff;border-radius:16px;padding:28px;width:90%;max-width:480px;box-shadow:0 20px 60px rgba(0,0,0,.3);}
#setupBox h2{font-size:1rem;font-weight:800;margin-bottom:8px;}
#setupBox p{font-size:.83rem;color:var(--muted);margin-bottom:16px;line-height:1.7;}
@media(max-width:600px){
  .main,.fb{padding-right:12px;padding-left:12px;}
  .fg{grid-template-columns:1fr;}
  .drow{grid-template-columns:1fr 1fr;}
  .drow .f:first-child{grid-column:span 2;}
}
</style>
</head>
<body>

<!-- SETUP -->
<div id="setup">
  <div id="setupBox">
    <h2>⚙️ ربط Google Sheets</h2>
    <p>الصق رابط الـ Apps Script (Web App URL) عشان البيانات تروح للشيت فور الإدخال</p>
    <div class="f" style="margin-bottom:14px">
      <label>Web App URL</label>
      <input type="url" id="su_url" placeholder="https://script.google.com/macros/s/..." style="font-size:.8rem;direction:ltr">
    </div>
    <div style="display:flex;gap:10px;flex-wrap:wrap">
      <button class="btn bt" onclick="doSetup()">💾 حفظ والبدء</button>
      <button class="btn bg" onclick="skipSetup()">بدون شيت (محلي)</button>
    </div>
  </div>
</div>

<header>
  <div class="logo">
    <h1>🏥 صيدلية مستشفى الثدي</h1>
    <p>National Cancer Institute · Cairo University</p>
  </div>
  <span class="hbadge">نظام الصرف</span>
</header>

<nav>
  <button class="nb active" onclick="go('entry',this)">➕ إدخال</button>
  <button class="nb" onclick="go('dispense',this)">💊 الصرف</button>
  <button class="nb" onclick="go('records',this)">📋 السجلات</button>
  <button class="nb" onclick="go('export',this)">⬇️ تصدير</button>
  <button class="nb" onclick="go('settings',this)">⚙️ إعدادات</button>
</nav>

<div class="main">

<!-- ENTRY -->
<div class="pg active" id="pg_entry">
  <div class="card">
    <div class="ch"><div class="dot dn"></div><h2>بيانات المريضة</h2></div>
    <div class="cb">
      <div class="fg">
        <div class="f"><label><span class="req">* </span>التاريخ</label><input type="date" id="e_date"></div>
        <div class="f s2"><label><span class="req">* </span>اسم المريضة</label><input type="text" id="e_name" placeholder="الاسم رباعى" autocomplete="off"></div>
        <div class="f"><label><span class="req">* </span>رقم الملف</label><input type="text" id="e_fileno" placeholder="مثال: 22/15104"></div>
        <div class="f"><label><span class="req">* </span>المعاملة المالية</label>
          <select id="e_fin">
            <option value="">اختر...</option>
            <option>مجانى</option><option>تأمين صحى</option><option>نفقة دولة</option><option>شامل</option>
          </select>
        </div>
        <div class="f"><label><span class="req">* </span>الصيدلي (إدخال)</label>
          <input type="text" id="e_pharm_in" placeholder="اسم الصيدلي" list="plist" autocomplete="off">
        </div>
        <div class="f"><label>وقت الإدخال</label><input type="time" id="e_tin" style="background:#f5f5f5;color:var(--muted)" readonly></div>
      </div>
    </div>
  </div>

  <div class="card">
    <div class="ch"><div class="dot dt"></div><h2>الأدوية</h2></div>
    <div class="dsec">
      <div class="dtitle">يمكن إضافة أكثر من دواء لنفس المريضة — الكميات تُكمل من صيدلي الصرف</div>
      <div id="drugRows"></div>
      <button class="addbtn" onclick="addDrug()">＋ دواء آخر</button>
    </div>
    <div class="ztog">
      <label class="sw"><input type="checkbox" id="zt" onchange="document.getElementById('zf').style.display=this.checked?'block':'none'"><span class="sl"></span></label>
      <span style="font-size:.88rem;font-weight:700;color:var(--rose)">💉 Zoladex</span>
    </div>
    <div id="zf">
      <div class="fg" style="padding-top:10px">
        <div class="f"><label>رقم مريض Zoladex</label><input type="text" id="z_pid" placeholder="رقم المريض"></div>
        <div class="f"><label>ملاحظة</label><input type="text" id="z_note" placeholder="ملاحظة..."></div>
      </div>
    </div>
    <div style="padding:0 18px 14px;margin-top:10px;border-top:1px solid var(--bg);padding-top:12px">
      <div class="f"><label>بروتوكولات / ملاحظات إضافية</label>
        <textarea id="e_notes" rows="2" placeholder="أي ملاحظات..." style="resize:vertical;border:1.5px solid var(--border);border-radius:8px;padding:8px;font-family:'Tajawal',sans-serif;background:var(--bg);outline:none;font-size:.88rem;"></textarea>
      </div>
    </div>
  </div>

  <div class="card">
    <div class="ch"><div class="dot dg"></div><h2>بيانات الصرف (اختياري — يكملها صيدلي الصرف)</h2></div>
    <div class="cb">
      <div class="fg">
        <div class="f"><label>وقت الصرف</label><input type="time" id="e_tdisp"></div>
        <div class="f"><label>الصيدلي (صرف)</label><input type="text" id="e_pdisp" placeholder="اسم صيدلي الصرف" list="plist"></div>
      </div>
    </div>
  </div>

  <div id="eMsg" style="display:none"></div>
  <div style="display:flex;gap:10px;flex-wrap:wrap;margin-bottom:24px">
    <button class="btn bt" style="font-size:.95rem;padding:11px 24px" id="sendBtn" onclick="submitEntry()">📤 إرسال للشيت</button>
    <button class="btn bg" onclick="clearEntry()">🔄 مسح</button>
  </div>
</div>

<!-- DISPENSE -->
<div class="pg" id="pg_dispense">
  <div class="card">
    <div class="ch"><div class="dot dg"></div><h2>💊 شاشة الصرف</h2></div>
    <div class="fb">
      <label>بحث:</label><input type="text" id="ds_q" placeholder="اسم أو رقم..." oninput="renderD()">
      <label>التاريخ:</label><input type="date" id="ds_d" onchange="renderD()">
      <label>الحالة:</label>
      <select id="ds_s" onchange="renderD()">
        <option value="">الكل</option>
        <option value="pending">⏳ معلق</option>
        <option value="done">✅ مكتمل</option>
      </select>
      <span class="cnt" id="dCnt">0</span>
    </div>
    <div class="tw">
      <table>
        <thead><tr><th>#</th><th>التاريخ</th><th>الاسم</th><th>رقم الملف</th><th>الأدوية</th><th>الكميات</th><th>وقت الصرف</th><th>صيدلي الصرف</th><th>حالة</th></tr></thead>
        <tbody id="dBody"></tbody>
      </table>
    </div>
  </div>
</div>

<!-- RECORDS -->
<div class="pg" id="pg_records">
  <div class="card">
    <div class="ch"><div class="dot dn"></div><h2>📋 جميع السجلات</h2></div>
    <div class="fb">
      <label>بحث:</label><input type="text" id="rs_q" placeholder="اسم أو رقم أو دواء..." oninput="renderR()">
      <label>التاريخ:</label><input type="date" id="rs_d" onchange="renderR()">
      <label>المعاملة:</label>
      <select id="rs_f" onchange="renderR()">
        <option value="">الكل</option>
        <option>مجانى</option><option>تأمين صحى</option><option>نفقة دولة</option><option>شامل</option>
      </select>
      <button class="btn bg" style="padding:5px 11px;font-size:.8rem" onclick="clearRF()">مسح</button>
      <span class="cnt" id="rCnt">0</span>
    </div>
    <div class="tw">
      <table>
        <thead><tr><th>#</th><th>التاريخ</th><th>الاسم</th><th>رقم الملف</th><th>المعاملة</th><th>الأدوية</th><th>Zoladex</th><th>وقت إدخال</th><th>وقت صرف</th><th>صيدلي صرف</th><th>حالة</th><th></th></tr></thead>
        <tbody id="rBody"></tbody>
      </table>
    </div>
    <div class="pag" id="rPag"></div>
  </div>
</div>

<!-- EXPORT -->
<div class="pg" id="pg_export">
  <div class="card">
    <div class="ch"><div class="dot dt"></div><h2>⬇️ تصدير Excel</h2></div>
    <div class="cb">
      <p style="color:var(--muted);font-size:.84rem;margin-bottom:14px">كل دواء في صف منفصل — مناسب للتحليل في Excel</p>
      <div class="fg" style="max-width:380px;margin-bottom:14px">
        <div class="f"><label>من تاريخ</label><input type="date" id="xf"></div>
        <div class="f"><label>إلى تاريخ</label><input type="date" id="xt"></div>
      </div>
      <div style="display:flex;gap:10px;flex-wrap:wrap">
        <button class="btn be" onclick="doExport()">⬇️ تحميل CSV</button>
        <button class="btn bg" onclick="doExportAll()">⬇️ تحميل الكل</button>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="ch"><div class="dot dr"></div><h2>إدارة البيانات</h2></div>
    <div class="cb">
      <p style="color:var(--muted);font-size:.83rem;margin-bottom:6px" id="stInfo"></p>
      <p style="color:var(--muted);font-size:.76rem;margin-bottom:12px">البيانات الأساسية في Google Sheets — المحلية احتياطية</p>
      <button class="btn" style="background:#fff0f3;color:var(--rose);border:1.5px solid #fcc;font-size:.84rem" onclick="clearLocal()">🗑️ مسح المحلية</button>
    </div>
  </div>
</div>

<!-- SETTINGS -->
<div class="pg" id="pg_settings">
  <div class="card">
    <div class="ch"><div class="dot dt"></div><h2>⚙️ إعدادات الاتصال</h2></div>
    <div class="cb">
      <div class="f" style="max-width:500px;margin-bottom:14px">
        <label>Web App URL</label>
        <input type="url" id="set_url" style="font-size:.8rem;direction:ltr">
      </div>
      <div style="display:flex;gap:10px;flex-wrap:wrap">
        <button class="btn bt" onclick="saveSettings()">💾 حفظ</button>
        <button class="btn bg" onclick="testConn()">🔗 اختبار</button>
      </div>
      <div id="connMsg" style="margin-top:10px;display:none"></div>
    </div>
  </div>
</div>

</div>

<datalist id="plist">
  <option>Nada Amr</option><option>Radwa</option><option>Hajer</option>
  <option>NADA ABDULLAH</option><option>Maram hamdy</option><option>Passant Yousry</option>
  <option>Sara Emad</option><option>Esraa Islam</option><option>Farida Meklad</option>
  <option>Hend Mahmoud</option><option>Mariam Amr</option><option>Nihal</option>
  <option>Mona Atef</option><option>Nourhan Essam</option><option>Yasmina Yasser</option>
  <option>Doaa Elsaghier</option><option>Ahmed Medhat</option><option>Marwa Fathy</option>
  <option>Noha Nabil</option><option>Hala Ahmad</option><option>Asmaa yehia</option>
</datalist>

<div id="toast">تم</div>

<script>
// ══════ DRUGS ══════
const DRUGS = {
  "هرمونى وتدعيمى":["Tamoxifen","Aramidex","Anastrazole","Aromasin","Letrozole","NOLVADEX","FASLODEX","Supportive","ZOLADEX","TAMOXIFEN-ZOLADEX","Femapent","Exemestane"],
  "Xeloda & أقراص كيماوى":["Xeloda","Tykerb","Navelbine oral","Affinitor","Everlicar","Ibrance 125","Ibrance 100","Ibrance 75","LAPATINIB","Lynparza"],
  "أخرى":["أخرى / يدوى"]
};
const UNITS_MAP = {
  Xeloda:["قرص","شريط","علبة"],Tamoxifen:["قرص","شريط","علبة"],
  Aramidex:["قرص","شريط","علبة"],Anastrazole:["قرص","شريط","علبة"],
  Aromasin:["قرص","شريط","علبة"],Lynparza:["قرص","علبة"],
  Ibrance:["كبسولة","علبة"],Supportive:["قرص","علبة","شريط","وحدة"],
  def:["قرص","شريط","علبة","كبسولة","مليجرام","وحدة"]
};
function getU(d){for(const k in UNITS_MAP)if(d&&k!=='def'&&d.toLowerCase().includes(k.toLowerCase()))return UNITS_MAP[k];return UNITS_MAP.def;}
function drugOpts(s=''){let o='<option value="">اختر الدواء...</option>';for(const g in DRUGS){o+=`<optgroup label="${g}">`;DRUGS[g].forEach(d=>o+=`<option${d===s?' selected':''}>${d}</option>`);o+='</optgroup>';}return o;}

// ══════ STATE ══════
let DB = JSON.parse(localStorage.getItem('nci_db')||'[]');
let NID = DB.length?Math.max(...DB.map(r=>r.id))+1:1;
const FIXED_URL='https://script.google.com/macros/s/AKfycbwD936Q-d_Ma_-rQS50BdBZVNUIW150U8aI0_A33_JuwEZ9tjhvVyprP0fsvDYFt1LvUw/exec';
let URL_ = FIXED_URL;
localStorage.setItem('nci_url', FIXED_URL);
let dc = 0;

function saveL(){localStorage.setItem('nci_db',JSON.stringify(DB));}

// ══════ SETUP ══════
window.onload=function(){
  // دايما مخفي — الـ URL محفوظ في الكود
  document.getElementById('setup').style.display='none';
  localStorage.setItem('nci_rdy','1');
  localStorage.setItem('nci_url', URL_);
  document.getElementById('set_url').value=URL_;
  initEntry(); updateSt();
};
function doSetup(){
  const u=document.getElementById('su_url').value.trim();
  if(!u){alert('الصق الرابط أولاً');return;}
  URL_=u; localStorage.setItem('nci_url',u); localStorage.setItem('nci_rdy','1');
  document.getElementById('setup').style.display='none';
  document.getElementById('set_url').value=u;
  toast('✅ تم الإعداد');
}
function skipSetup(){localStorage.setItem('nci_rdy','1');document.getElementById('setup').style.display='none';}

// ══════ NAV ══════
function go(id,btn){
  document.querySelectorAll('.pg').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('.nb').forEach(b=>b.classList.remove('active'));
  document.getElementById('pg_'+id).classList.add('active');
  btn.classList.add('active');
  if(id==='records')renderR();
  if(id==='dispense')renderD();
  if(id==='export')updateSt();
}

// ══════ DRUG ROWS ══════
function initEntry(){
  dc=0; document.getElementById('drugRows').innerHTML=''; addDrug();
  document.getElementById('e_date').valueAsDate=new Date();
  const n=new Date();
  document.getElementById('e_tin').value=pad(n.getHours())+':'+pad(n.getMinutes());
}
function pad(x){return String(x).padStart(2,'0');}
function addDrug(drug='',qty='',unit=''){
  dc++;const id=dc;
  const div=document.createElement('div');div.className='drow';div.id='dr_'+id;
  const units=getU(drug);
  div.innerHTML=`
    <div class="f"><label>الدواء</label><select onchange="onDC(this,${id})">${drugOpts(drug)}</select></div>
    <div class="f"><label>الكمية</label><input type="number" id="qty_${id}" value="${qty}" min="0.5" step="0.5" placeholder="—"></div>
    <div class="f"><label>الوحدة</label><select id="un_${id}">${units.map(u=>`<option${u===unit?' selected':''}>${u}</option>`).join('')}</select></div>
    ${id>1?`<button class="delbtn" onclick="document.getElementById('dr_${id}').remove()">🗑</button>`:'<div></div>'}`;
  document.getElementById('drugRows').appendChild(div);
}
function onDC(sel,id){document.getElementById('un_'+id).innerHTML=getU(sel.value).map(u=>`<option>${u}</option>`).join('');}
function getDrugs(){
  return [...document.querySelectorAll('#drugRows .drow')].map(r=>{
    const s=r.querySelectorAll('select');const q=r.querySelector('input[type=number]');
    return s[0]&&s[0].value?{drug:s[0].value,qty:q?q.value:'',unit:s[1]?s[1].value:''}:null;
  }).filter(Boolean);
}

// ══════ SUBMIT ══════
async function submitEntry(){
  const req=['e_date','e_name','e_fileno','e_fin','e_pharm_in'];
  let ok=true;
  req.forEach(id=>{const e=document.getElementById(id);e.classList.remove('err');if(!e.value.trim()){e.classList.add('err');ok=false;}});
  if(!ok){showMsg('eMsg','⚠️ يرجى تعبئة الحقول الإلزامية','er');return;}
  const drugs=getDrugs();
  if(!drugs.length){showMsg('eMsg','⚠️ أضيفي دواء واحد على الأقل','er');return;}

  const now=new Date();
  const tin=document.getElementById('e_tin').value||pad(now.getHours())+':'+pad(now.getMinutes());
  const rec={
    id:NID++,
    date:document.getElementById('e_date').value,
    name:document.getElementById('e_name').value.trim(),
    fileno:document.getElementById('e_fileno').value.trim(),
    fin:document.getElementById('e_fin').value,
    pharm_in:document.getElementById('e_pharm_in').value.trim(),
    time_in:tin, drugs,
    time_disp:document.getElementById('e_tdisp').value||'',
    pharm_disp:document.getElementById('e_pdisp').value.trim()||'',
    zoladex:document.getElementById('zt').checked?{pid:document.getElementById('z_pid').value.trim(),note:document.getElementById('z_note').value.trim()}:null,
    notes:document.getElementById('e_notes').value.trim(),
    sent:false
  };
  DB.push(rec); saveL();

  const btn=document.getElementById('sendBtn');
  btn.disabled=true; btn.innerHTML='<span class="spin"></span> جاري الإرسال...';

  if(URL_){
    try{
      let allOk=true;
      for(let i=0;i<rec.drugs.length;i++){
        const d=rec.drugs[i];
        const p=new URLSearchParams({
          action:'addRow',
          date:rec.date,name:rec.name,fileno:rec.fileno,fin:rec.fin,
          pharm_in:rec.pharm_in,time_in:rec.time_in,
          drug:d.drug,qty:d.qty||'',unit:d.unit||'',
          time_disp:rec.time_disp||'',pharm_disp:rec.pharm_disp||'',
          zoladex:rec.zoladex?'نعم':'لا',
          zoladex_pid:rec.zoladex?rec.zoladex.pid:'',
          notes:rec.notes||'',
          record_id:rec.id
        });
        try{
          const res=await fetch(URL_+'?'+p.toString());
          const js=await res.json();
          if(js.status!=='ok') allOk=false;
        }catch(fe){ allOk=false; }
      }
      rec.sent=allOk; saveL();
      if(allOk){
        showMsg('eMsg',`✅ وصل للشيت — ${rec.name} (${drugs.length} ${drugs.length===1?'دواء':'أدوية'})`,'ok');
        toast('✅ تم الحفظ في Google Sheets');
      } else {
        showMsg('eMsg','⚠️ تم الحفظ محليًا — تحققي من الاتصال','er');
      }
    }catch(e){
      showMsg('eMsg','⚠️ خطأ في الإرسال — محفوظ محليًا','er');
    }
  } else {
    showMsg('eMsg',`✅ محفوظ محليًا — ${rec.name}`,'ok');
    toast('💾 تم الحفظ محليًا');
  }
  btn.disabled=false; btn.innerHTML='📤 إرسال للشيت';
  clearEntry();
}

function clearEntry(){
  ['e_date','e_name','e_fileno','e_pharm_in','e_notes','e_tdisp','e_pdisp','z_pid','z_note'].forEach(id=>{const e=document.getElementById(id);if(e)e.value='';});
  document.getElementById('e_fin').selectedIndex=0;
  document.getElementById('drugRows').innerHTML=''; dc=0; addDrug();
  document.getElementById('zt').checked=false;
  document.getElementById('zf').style.display='none';
  document.getElementById('e_date').valueAsDate=new Date();
  const n=new Date(); document.getElementById('e_tin').value=pad(n.getHours())+':'+pad(n.getMinutes());
}
function showMsg(id,msg,type){const e=document.getElementById(id);e.className='msg '+(type==='ok'?'mok':'mer');e.textContent=msg;e.style.display='block';if(type==='ok')setTimeout(()=>e.style.display='none',4000);}

// ══════ DISPENSE ══════
function renderD(){
  const q=(document.getElementById('ds_q').value||'').toLowerCase();
  const date=document.getElementById('ds_d').value;
  const st=document.getElementById('ds_s').value;
  const recs=DB.filter(r=>{
    if(date&&r.date!==date)return false;
    if(q&&!r.name.toLowerCase().includes(q)&&!r.fileno.toLowerCase().includes(q))return false;
    const pend=r.drugs.some(d=>!d.qty);
    if(st==='pending'&&!pend)return false;
    if(st==='done'&&pend)return false;
    return true;
  });
  document.getElementById('dCnt').textContent=recs.length+' سجل';
  document.getElementById('dBody').innerHTML=recs.map(r=>{
    const pend=r.drugs.some(d=>!d.qty);
    const drugsHtml=r.drugs.map((d,i)=>`
      <div style="display:flex;align-items:center;gap:5px;margin-bottom:3px">
        <b style="font-size:.77rem;min-width:80px">${d.drug}</b>
        <input type="number" value="${d.qty||''}" min="0.5" step="0.5" placeholder="كمية"
          style="width:58px;border:1.5px solid var(--border);border-radius:6px;padding:3px 5px;font-size:.8rem"
          onchange="updQ(${r.id},${i},this.value,'qty')">
        <select style="border:1.5px solid var(--border);border-radius:6px;padding:3px 5px;font-size:.77rem;background:var(--bg)"
          onchange="updQ(${r.id},${i},this.value,'unit')">
          ${getU(d.drug).map(u=>`<option${u===d.unit?' selected':''}>${u}</option>`).join('')}
        </select>
      </div>`).join('');
    return `<tr style="${pend?'background:#fffbeb':''}">
      <td><small style="color:var(--muted)">${r.id}</small></td>
      <td><b>${r.date}</b></td><td>${r.name}</td><td><small>${r.fileno}</small></td>
      <td>${r.drugs.map(d=>`<small>${d.drug}</small>`).join('<br>')}</td>
      <td>${drugsHtml}</td>
      <td><input type="time" value="${r.time_disp||''}" onchange="updF(${r.id},'time_disp',this.value)"
        style="border:1.5px solid var(--border);border-radius:6px;padding:4px 6px;font-size:.8rem"></td>
      <td><input type="text" value="${r.pharm_disp||''}" list="plist" placeholder="اسم الصيدلي"
        onchange="updF(${r.id},'pharm_disp',this.value)"
        style="border:1.5px solid var(--border);border-radius:6px;padding:4px 6px;font-size:.8rem;width:120px"></td>
      <td>${pend?'<span class="stag spend">⏳ معلق</span>':'<span class="stag sdone">✅ تم</span>'}</td>
    </tr>`;
  }).join('');
}
function updQ(rid,idx,val,field){
  const r=DB.find(x=>x.id===rid);if(!r)return;
  r.drugs[idx][field]=val; saveL();
  if(URL_&&r.sent){
    const d=r.drugs[idx];
    const p=new URLSearchParams({action:'updateDispense',record_id:rid,drug_idx:idx,qty:d.qty,unit:d.unit,time_disp:r.time_disp,pharm_disp:r.pharm_disp});
    fetch(URL_+'?'+p.toString()).catch(()=>{});
  }
  toast('💾 تم');
}
function updF(rid,field,val){
  const r=DB.find(x=>x.id===rid);if(!r)return;
  r[field]=val; saveL();
  if(URL_&&r.sent){
    const p=new URLSearchParams({action:'updateDispense',record_id:rid,drug_idx:0,qty:r.drugs[0]?.qty||'',unit:r.drugs[0]?.unit||'',time_disp:r.time_disp,pharm_disp:r.pharm_disp});
    fetch(URL_+'?'+p.toString()).catch(()=>{});
  }
  toast('💾 تم');
}

// ══════ RECORDS ══════
const PG=50;let rp=1,rf=[];
function renderR(p){
  if(p)rp=p;
  const q=(document.getElementById('rs_q').value||'').toLowerCase();
  const date=document.getElementById('rs_d').value;
  const fin=document.getElementById('rs_f').value;
  rf=DB.filter(r=>{
    if(date&&r.date!==date)return false;
    if(fin&&r.fin!==fin)return false;
    if(q){const ds=r.drugs.map(d=>d.drug).join(' ').toLowerCase();if(!r.name.toLowerCase().includes(q)&&!r.fileno.toLowerCase().includes(q)&&!ds.includes(q))return false;}
    return true;
  });
  document.getElementById('rCnt').textContent=rf.length+' سجل';
  const sl=rf.slice((rp-1)*PG,rp*PG);
  const ft=v=>{if(!v)return'';const m={مجانى:'tf',تأمين:'ti',نفقة:'tn',شامل:'ts'};const c=Object.keys(m).find(k=>v.includes(k));return`<span class="tag ${c?m[c]:'tf'}">${v}</span>`;};
  document.getElementById('rBody').innerHTML=sl.map((r,i)=>{
    const ds=r.drugs.map(d=>`<small><b>${d.drug}</b>${d.qty?' — '+d.qty+' '+d.unit:' <span style="color:var(--gold)">⏳</span>'}</small>`).join('<br>');
    const pend=r.drugs.some(d=>!d.qty);
    return`<tr><td>${(rp-1)*PG+i+1}</td><td>${r.date}</td><td><b>${r.name}</b></td><td><small>${r.fileno}</small></td>
      <td>${ft(r.fin)}</td><td style="line-height:1.8">${ds}</td>
      <td style="text-align:center">${r.zoladex?'💉✅':'—'}</td>
      <td><small>${r.time_in||'—'}</small></td><td><small>${r.time_disp||'—'}</small></td><td><small>${r.pharm_disp||'—'}</small></td>
      <td>${pend?'<span class="stag spend">⏳</span>':'<span class="stag sdone">✅</span>'}</td>
      <td><button class="dbtn" onclick="delR(${r.id})">🗑</button></td></tr>`;
  }).join('');
  const pages=Math.ceil(rf.length/PG);
  const pg=document.getElementById('rPag');
  if(pages<=1){pg.innerHTML='';return;}
  let h='';
  if(rp>1)h+=`<button onclick="renderR(${rp-1})">◀</button>`;
  for(let i=Math.max(1,rp-2);i<=Math.min(pages,rp+2);i++)h+=`<button class="${i===rp?'on':''}" onclick="renderR(${i})">${i}</button>`;
  if(rp<pages)h+=`<button onclick="renderR(${rp+1})">▶</button>`;
  h+=`<span>${rp}/${pages} — ${rf.length}</span>`;
  pg.innerHTML=h;
}
function delR(id){if(!confirm('حذف؟'))return;DB=DB.filter(r=>r.id!==id);saveL();renderR();}
function clearRF(){['rs_q','rs_d'].forEach(id=>document.getElementById(id).value='');document.getElementById('rs_f').value='';rp=1;renderR();}

// ══════ EXPORT ══════
function buildCSV(recs){
  const h=['التاريخ','اسم المريضة','رقم الملف','المعاملة المالية','الصيدلي (إدخال)','وقت الإدخال','الدواء','الكمية','الوحدة','وقت الصرف','الصيدلي (صرف)','Zoladex','رقم Zoladex','ملاحظات'].join('\t');
  const rows=[];
  recs.forEach(r=>{r.drugs.forEach(d=>{rows.push([r.date,r.name,r.fileno,r.fin,r.pharm_in,r.time_in,d.drug,d.qty||'',d.unit||'',r.time_disp||'',r.pharm_disp||'',r.zoladex?'نعم':'لا',r.zoladex?.pid||'',r.notes||''].join('\t'));});});
  return[h,...rows].join('\n');
}
function doExport(){const f=document.getElementById('xf').value,t=document.getElementById('xt').value;const recs=DB.filter(r=>{if(f&&r.date<f)return false;if(t&&r.date>t)return false;return true;});if(!recs.length){toast('⚠️ لا يوجد بيانات');return;}dl(buildCSV(recs),`NCI_${f||'all'}_${t||'all'}.tsv`);}
function doExportAll(){if(!DB.length){toast('⚠️ لا يوجد بيانات');return;}dl(buildCSV(DB),'NCI_All.tsv');}
function dl(c,n){const b=new Blob(['\uFEFF'+c],{type:'text/tab-separated-values;charset=utf-8'});const a=document.createElement('a');a.href=URL.createObjectURL(b);a.download=n;a.click();toast('⬇️ تم');}

// ══════ SETTINGS ══════
function saveSettings(){const u=document.getElementById('set_url').value.trim();URL_=u;localStorage.setItem('nci_url',u);toast('✅ تم الحفظ');}
async function testConn(){
  const u=document.getElementById('set_url').value.trim();
  if(!u){showCM('⚠️ أدخلي الرابط أولاً','er');return;}
  showCM('🔄 جاري الاختبار...','ok');
  try{
    const r=await fetch(u+'?action=test');
    const d=await r.json();
    showCM(d.status==='ok'?'✅ الاتصال يعمل بنجاح!':'⚠️ رد غير متوقع',d.status==='ok'?'ok':'er');
  }catch(e){showCM('❌ تعذر الاتصال — تأكدي من الرابط وإعدادات Deploy','er');}
}
function showCM(msg,type){const e=document.getElementById('connMsg');e.className='msg '+(type==='ok'?'mok':'mer');e.textContent=msg;e.style.display='block';}
function updateSt(){const s=new Blob([localStorage.getItem('nci_db')||'']).size;const el=document.getElementById('stInfo');if(el)el.textContent=`✅ ${DB.length} سجل (${(s/1024).toFixed(1)} KB)`;}
function clearLocal(){if(!confirm('مسح البيانات المحلية؟'))return;DB=[];localStorage.removeItem('nci_db');NID=1;saveL();updateSt();renderR();toast('🗑️ تم');}

// ══════ TOAST ══════
let _tt;
function toast(m){const t=document.getElementById('toast');t.textContent=m;t.classList.add('show');clearTimeout(_tt);_tt=setTimeout(()=>t.classList.remove('show'),2600);}
</script>
</body>
</html>
