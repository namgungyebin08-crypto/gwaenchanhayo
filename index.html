<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>괜찮아요 - 강화도 독거노인 안부확인 시스템</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@2.44.0/tabler-icons.min.css">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
  --green:#2d9e6b;--green-light:#e8f7f0;
  --red:#e24b4a;--red-light:#fdf0f0;
  --blue:#3a7bd5;
  --dark:#1a2332;--mid:#4a5568;
  --light:#f7f8fa;--border:#e2e8f0;--white:#fff;
  --radius:10px;--radius-lg:14px;
}
body{font-family:'Noto Sans KR',sans-serif;background:var(--light);color:var(--dark);min-height:100vh}
input,select,textarea{width:100%;padding:10px 14px;border:1px solid var(--border);border-radius:var(--radius);font-family:'Noto Sans KR',sans-serif;font-size:14px;color:var(--dark);background:#fff;outline:none;transition:border-color .2s}
input:focus,select:focus,textarea:focus{border-color:var(--green)}
.nav{display:flex;align-items:center;justify-content:space-between;padding:0 20px;height:52px;background:#fff;border-bottom:1px solid var(--border);position:sticky;top:0;z-index:10}
.nav-logo{font-size:15px;font-weight:700;color:var(--dark)}
.nav-logo em{color:var(--green);font-style:normal}
.tabs{display:flex;gap:4px}
.tab{background:none;border:1px solid transparent;border-radius:var(--radius);padding:6px 14px;font-size:13px;color:var(--mid);cursor:pointer;font-family:'Noto Sans KR',sans-serif}
.tab:hover{background:var(--light)}
.tab.on{background:var(--light);color:var(--dark);border-color:var(--border)}
.page{display:none;padding:24px 20px;max-width:640px;margin:0 auto}
.page.on{display:block}
.big-wrap{display:flex;flex-direction:column;align-items:center;padding:12px 0 24px}
.big-date{font-size:14px;color:var(--mid);margin-bottom:32px}
.circle-btn{width:200px;height:200px;border-radius:50%;background:var(--green);border:none;cursor:pointer;display:flex;flex-direction:column;align-items:center;justify-content:center;gap:10px;margin-bottom:36px;transition:transform .15s,opacity .15s;box-shadow:0 8px 28px rgba(45,158,107,.3)}
.circle-btn:hover{transform:scale(1.04)}
.circle-btn:active{transform:scale(.97)}
.circle-btn.done{background:var(--blue);cursor:default;box-shadow:0 8px 28px rgba(58,123,213,.3)}
.circle-btn.done:hover{transform:none}
.circle-btn i{font-size:48px;color:#fff}
.circle-btn span{font-size:18px;font-weight:700;color:#fff}
.mini-list{width:100%;max-width:360px;background:#fff;border:1px solid var(--border);border-radius:var(--radius-lg);padding:16px 20px}
.mini-row{display:flex;align-items:center;gap:10px;padding:8px 0;border-bottom:1px solid var(--border)}
.mini-row:last-child{border:none}
.dot{width:8px;height:8px;border-radius:50%;flex-shrink:0}
.dot-g{background:var(--green)}.dot-r{background:var(--red)}.dot-b{background:#cbd5e0}
.mini-name{font-size:14px;font-weight:500;flex:1}
.mini-time{font-size:12px;color:var(--mid)}
.stat-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:20px}
.stat{background:#fff;border:1px solid var(--border);border-radius:var(--radius);padding:14px 16px}
.stat-n{font-size:28px;font-weight:700;line-height:1;margin-bottom:4px}
.stat-l{font-size:12px;color:var(--mid)}
.n-g{color:var(--green)}.n-r{color:var(--red)}.n-d{color:var(--dark)}
.p-cards{display:flex;flex-direction:column;gap:8px}
.p-card{background:#fff;border:1px solid var(--border);border-radius:var(--radius-lg);padding:14px 18px;display:flex;align-items:center;gap:12px}
.p-card.p-ok{border-color:#86efac}
.p-card.p-no{border-color:#fca5a5}
.av{width:40px;height:40px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:18px;flex-shrink:0;background:var(--light)}
.p-info{flex:1}
.p-name{font-size:14px;font-weight:700}
.p-det{font-size:12px;color:var(--mid);margin-top:2px}
.badge{padding:3px 10px;border-radius:20px;font-size:11px;font-weight:700}
.b-ok{background:var(--green-light);color:var(--green)}
.b-no{background:var(--red-light);color:var(--red)}
.act-btn{background:none;border:1px solid var(--border);border-radius:8px;padding:5px 12px;font-size:12px;color:var(--mid);cursor:pointer;font-family:'Noto Sans KR',sans-serif;margin-top:4px}
.act-btn:hover{border-color:var(--red);color:var(--red)}
.reg-box{background:#fff;border:1px solid var(--border);border-radius:var(--radius-lg);padding:24px}
.form-lbl{font-size:13px;font-weight:700;color:var(--mid);display:block;margin-bottom:6px}
.form-g{margin-bottom:16px}
.sub-btn{width:100%;padding:13px;background:var(--green);border:none;border-radius:var(--radius);color:#fff;font-size:15px;font-weight:700;cursor:pointer;font-family:'Noto Sans KR',sans-serif;margin-top:4px;transition:opacity .15s}
.sub-btn:hover{opacity:.88}
.ok-msg{display:none;background:var(--green-light);border:1px solid #86efac;border-radius:var(--radius);padding:12px 16px;font-size:13px;color:var(--green);text-align:center;margin-top:12px}
.reg-list-title{font-size:14px;font-weight:700;margin:24px 0 12px}
.reg-item{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid var(--border);font-size:13px}
.reg-item:last-child{border:none}
.ri-name{font-weight:700;flex:1}
.ri-area{font-size:12px;color:var(--mid)}
.del-btn{background:none;border:none;color:#cbd5e0;cursor:pointer;padding:4px;font-size:14px}
.del-btn:hover{color:var(--red)}
.gb-box{background:#fff;border:1px solid var(--border);border-radius:var(--radius-lg);padding:24px;margin-bottom:20px}
.gb-title{font-size:16px;font-weight:700;margin-bottom:4px}
.gb-sub{font-size:13px;color:var(--mid);margin-bottom:20px}
.gb-entries{display:flex;flex-direction:column;gap:10px;margin-top:20px;max-height:400px;overflow-y:auto}
.gb-entry{background:var(--light);border-radius:var(--radius);padding:12px 16px}
.gb-entry-top{display:flex;align-items:center;justify-content:space-between;margin-bottom:6px}
.gb-entry-name{font-size:13px;font-weight:700}
.gb-entry-time{font-size:11px;color:var(--mid)}
.gb-entry-msg{font-size:13px;color:var(--mid);line-height:1.6}
.gb-empty{font-size:13px;color:var(--mid);text-align:center;padding:32px 0}
</style>
</head>
<body>

<div class="nav">
  <div class="nav-logo"><em>괜찮아요</em> 안부확인 시스템</div>
  <div class="tabs">
    <button class="tab on" onclick="go('senior',this)">어르신</button>
    <button class="tab" onclick="go('manager',this)">담당자</button>
    <button class="tab" onclick="go('register',this)">등록</button>
    <button class="tab" onclick="go('guestbook',this)">방문록</button>
  </div>
</div>

<div class="page on" id="pg-senior">
  <div class="big-wrap">
    <div class="big-date" id="s-date"></div>
    <button class="circle-btn" id="main-btn" onclick="sendOk()">
      <i class="ti ti-mood-smile"></i>
      <span>괜찮아요</span>
    </button>
    <div class="mini-list">
      <div style="font-size:12px;color:var(--mid);margin-bottom:8px">오늘 응답 현황 (교동면)</div>
      <div id="s-list"></div>
    </div>
  </div>
</div>

<div class="page" id="pg-manager">
  <div style="display:flex;justify-content:space-between;align-items:flex-end;margin-bottom:20px">
    <div>
      <div style="font-size:18px;font-weight:700">담당자 현황판</div>
      <div style="font-size:13px;color:var(--mid);margin-top:2px">교동면 독거노인 안부 확인</div>
    </div>
    <div style="font-size:12px;color:var(--mid)" id="m-date"></div>
  </div>
  <div class="stat-grid">
    <div class="stat"><div class="stat-n n-d" id="st-total">0</div><div class="stat-l">전체 등록</div></div>
    <div class="stat"><div class="stat-n n-g" id="st-ok">0</div><div class="stat-l">응답 완료</div></div>
    <div class="stat"><div class="stat-n n-r" id="st-no">0</div><div class="stat-l">미응답</div></div>
  </div>
  <div class="p-cards" id="p-list"></div>
</div>

<div class="page" id="pg-register">
  <div class="reg-box">
    <div style="font-size:16px;font-weight:700;margin-bottom:4px">어르신 등록</div>
    <div style="font-size:13px;color:var(--mid);margin-bottom:20px">새로운 독거노인을 시스템에 등록합니다</div>
    <div class="form-g"><label class="form-lbl">성함</label><input id="r-name" type="text" placeholder="예) 김순자"></div>
    <div class="form-g">
      <label class="form-lbl">거주 읍면</label>
      <select id="r-area">
        <option value="교동면">교동면 (WAI 최취약)</option>
        <option value="삼산면">삼산면 (WAI 취약)</option>
        <option value="서도면">서도면 (WAI 취약)</option>
        <option value="내가면">내가면</option>
        <option value="강화읍">강화읍</option>
      </select>
    </div>
    <div class="form-g"><label class="form-lbl">담당자 연락처</label><input id="r-contact" type="text" placeholder="예) 010-1234-5678"></div>
    <button class="sub-btn" onclick="regPerson()">등록하기</button>
    <div class="ok-msg" id="reg-ok">✓ 등록이 완료되었습니다!</div>
  </div>
  <div class="reg-list-title">등록된 어르신 목록</div>
  <div id="r-list"></div>
</div>

<div class="page" id="pg-guestbook">
  <div class="gb-box">
    <div class="gb-title">발표 방문록</div>
    <div class="gb-sub">이 시스템을 보고 느낀 점을 남겨주세요 💚</div>
    <div class="form-g"><label class="form-lbl">이름 (선택)</label><input id="gb-name" type="text" placeholder="익명으로 남겨도 됩니다"></div>
    <div class="form-g"><label class="form-lbl">한 마디</label><textarea id="gb-msg" rows="3" placeholder="강화도 어르신들을 위한 시스템을 보고..."></textarea></div>
    <button class="sub-btn" onclick="submitGb()">방문록 남기기</button>
    <div class="ok-msg" id="gb-ok">✓ 감사합니다! 방문록이 저장되었습니다.</div>
    <div class="gb-entries" id="gb-list">
      <div class="gb-empty">불러오는 중...</div>
    </div>
  </div>
</div>

<script>
const STORAGE_KEY='gwaenchanhayo_gb_v1';
let persons=[
  {id:1,name:"김순자",area:"교동면",contact:"032-930-0001",ok:true,time:"오전 8:42"},
  {id:2,name:"이봉남",area:"교동면",contact:"032-930-0002",ok:false,time:null},
  {id:3,name:"박정순",area:"교동면",contact:"032-930-0003",ok:true,time:"오전 9:15"},
  {id:4,name:"최길동",area:"삼산면",contact:"032-930-0004",ok:false,time:null},
  {id:5,name:"윤복희",area:"교동면",contact:"032-930-0005",ok:true,time:"오전 10:02"},
];
let nid=6,myOk=false,gbEntries=[];

function dateStr(){
  const d=new Date(),days=['일','월','화','수','목','금','토'];
  return `${d.getFullYear()}년 ${d.getMonth()+1}월 ${d.getDate()}일 (${days[d.getDay()]})`;
}
function timeStr(){
  const d=new Date(),h=d.getHours(),m=String(d.getMinutes()).padStart(2,'0');
  return `${h<12?'오전':'오후'} ${h<=12?h:h-12}:${m}`;
}
function go(name,el){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('on'));
  document.querySelectorAll('.tab').forEach(t=>t.classList.remove('on'));
  document.getElementById('pg-'+name).classList.add('on');
  el.classList.add('on');
  if(name==='manager')renderManager();
  if(name==='register')renderRegList();
  if(name==='guestbook')loadGb();
}
function renderSenior(){
  document.getElementById('s-date').textContent=dateStr();
  document.getElementById('s-list').innerHTML=persons.slice(0,4).map(p=>`
    <div class="mini-row">
      <div class="dot ${p.ok?'dot-g':'dot-r'}"></div>
      <span class="mini-name">${p.name} 어르신</span>
      <span class="mini-time">${p.ok?p.time:'미응답'}</span>
    </div>`).join('');
}
function sendOk(){
  if(myOk)return;myOk=true;
  const b=document.getElementById('main-btn');
  b.classList.add('done');
  b.innerHTML=`<i class="ti ti-circle-check"></i><span>전송 완료!</span>`;
  const u=persons.find(p=>!p.ok);
  if(u){u.ok=true;u.time=timeStr();}
  renderSenior();
}
function renderManager(){
  document.getElementById('m-date').textContent=dateStr();
  const ok=persons.filter(p=>p.ok).length;
  document.getElementById('st-total').textContent=persons.length;
  document.getElementById('st-ok').textContent=ok;
  document.getElementById('st-no').textContent=persons.length-ok;
  document.getElementById('p-list').innerHTML=persons.map(p=>`
    <div class="p-card ${p.ok?'p-ok':'p-no'}">
      <div class="av">${p.ok?'😊':'❓'}</div>
      <div class="p-info">
        <div class="p-name">${p.name} 어르신</div>
        <div class="p-det">${p.area} · ${p.contact}</div>
      </div>
      <div style="display:flex;flex-direction:column;align-items:flex-end;gap:4px">
        <span class="badge ${p.ok?'b-ok':'b-no'}">${p.ok?'응답 완료':'미응답 !'}</span>
        <span style="font-size:11px;color:var(--mid)">${p.ok?p.time:'확인 필요'}</span>
        ${!p.ok?`<button class="act-btn" onclick="markOk(${p.id})">응답 처리</button>`:''}
      </div>
    </div>`).join('');
}
function markOk(id){
  const p=persons.find(x=>x.id===id);
  if(p){p.ok=true;p.time=timeStr();}
  renderManager();renderSenior();
}
function regPerson(){
  const name=document.getElementById('r-name').value.trim();
  const area=document.getElementById('r-area').value;
  const contact=document.getElementById('r-contact').value.trim();
  if(!name||!contact){alert('성함과 연락처를 입력해주세요.');return;}
  persons.push({id:nid++,name,area,contact,ok:false,time:null});
  document.getElementById('r-name').value='';
  document.getElementById('r-contact').value='';
  const m=document.getElementById('reg-ok');
  m.style.display='block';setTimeout(()=>m.style.display='none',2500);
  renderRegList();
}
function renderRegList(){
  document.getElementById('r-list').innerHTML=persons.map(p=>`
    <div class="reg-item">
      <span class="ri-name">${p.name} 어르신</span>
      <span class="ri-area">${p.area}</span>
      <button class="del-btn" onclick="delPerson(${p.id})">✕</button>
    </div>`).join('');
}
function delPerson(id){
  if(!confirm('삭제하시겠어요?'))return;
  persons=persons.filter(p=>p.id!==id);
  renderRegList();renderSenior();
}

// 방문록: Firebase Realtime Database 사용
const DB_URL='https://gwaenchanhayo-5a660-default-rtdb.firebaseio.com/guestbook.json';

async function loadGb(){
  const el=document.getElementById('gb-list');
  el.innerHTML='<div class="gb-empty">불러오는 중...</div>';
  try{
    const r=await fetch(DB_URL);
    const data=await r.json();
    if(data){
      gbEntries=Object.values(data).sort((a,b)=>b.ts-a.ts);
    }else{gbEntries=[];}
  }catch(e){
    gbEntries=[];
  }
  renderGb();
}

function renderGb(){
  const el=document.getElementById('gb-list');
  if(!gbEntries.length){
    el.innerHTML='<div class="gb-empty">아직 방문록이 없어요. 첫 번째로 남겨보세요! 💚</div>';
    return;
  }
  el.innerHTML=gbEntries.map(e=>`
    <div class="gb-entry">
      <div class="gb-entry-top">
        <span class="gb-entry-name">${e.name||'익명'}</span>
        <span class="gb-entry-time">${e.time}</span>
      </div>
      <div class="gb-entry-msg">${e.msg}</div>
    </div>`).join('');
}

async function submitGb(){
  const name=document.getElementById('gb-name').value.trim();
  const msg=document.getElementById('gb-msg').value.trim();
  if(!msg){alert('한 마디를 입력해주세요.');return;}
  const entry={
    name:name||'익명',
    msg,
    time:new Date().toLocaleString('ko-KR',{month:'numeric',day:'numeric',hour:'2-digit',minute:'2-digit'}),
    ts:Date.now()
  };
  try{
    await fetch(DB_URL,{method:'POST',headers:{'Content-Type':'application/json'},body:JSON.stringify(entry)});
    gbEntries.unshift(entry);
  }catch(e){}
  document.getElementById('gb-name').value='';
  document.getElementById('gb-msg').value='';
  const m=document.getElementById('gb-ok');
  m.style.display='block';setTimeout(()=>m.style.display='none',2500);
  renderGb();
}

renderSenior();
</script>
</body>
</html>
