<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Plum · Escalation Intelligence</title>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=Figtree:wght@300;400;500;600&family=IBM+Plex+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
:root{
  --fire:#FF3B30;--fire-bg:#FFF0EF;--fire-border:#FFCFC9;
  --watch:#FF9500;--watch-bg:#FFF8EE;--watch-border:#FFE0A3;
  --safe:#34C759;--blue:#3B82F6;--blue-bg:#EFF6FF;
  --navy:#0F172A;--navy-2:#1E293B;
  --text:#0F172A;--text-2:#475569;--text-3:#94A3B8;
  --bg:#F1F5F9;--card:#FFFFFF;--border:#E2E8F0;
  --r:12px;--rs:8px;
}
body{font-family:'Figtree',sans-serif;background:var(--bg);color:var(--text);min-height:100vh;-webkit-font-smoothing:antialiased;}
header{background:var(--navy);padding:0 32px;height:64px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:100;border-bottom:1px solid rgba(255,255,255,0.06);}
.logo{display:flex;align-items:center;gap:12px;}
.logo-mark{width:34px;height:34px;background:var(--fire);border-radius:9px;display:flex;align-items:center;justify-content:center;font-family:'Syne',sans-serif;font-weight:800;font-size:17px;color:white;}
.logo-text{font-family:'Syne',sans-serif;font-weight:700;font-size:17px;color:white;}
.logo-sub{font-size:11px;color:rgba(255,255,255,0.3);font-weight:400;margin-left:6px;}
.header-right{display:flex;align-items:center;gap:12px;}
.refresh-btn{background:rgba(255,255,255,0.08);border:1px solid rgba(255,255,255,0.12);color:rgba(255,255,255,0.8);padding:6px 14px;border-radius:6px;font-family:'Figtree',sans-serif;font-size:13px;font-weight:500;cursor:pointer;transition:background 0.15s;}
.refresh-btn:hover{background:rgba(255,255,255,0.15);}
.last-updated{font-size:11px;color:rgba(255,255,255,0.3);font-family:'IBM Plex Mono',monospace;}
.demo-badge{font-size:10px;font-weight:700;letter-spacing:0.06em;background:rgba(255,149,0,0.2);color:#FF9500;border:1px solid rgba(255,149,0,0.3);padding:3px 8px;border-radius:4px;}
main{max-width:1360px;margin:0 auto;padding:28px 32px 80px;}
.stats-strip{display:grid;grid-template-columns:repeat(6,1fr);gap:12px;margin-bottom:32px;}
.stat-card{background:var(--card);border:1px solid var(--border);border-radius:var(--r);padding:16px 18px;}
.stat-label{font-size:10px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:var(--text-3);margin-bottom:7px;}
.stat-value{font-family:'Syne',sans-serif;font-size:28px;font-weight:800;line-height:1;}
.stat-value.fire{color:var(--fire);}
.stat-value.watch{color:var(--watch);}
.stat-value.good{color:var(--safe);}
.stat-sub{font-size:11px;color:var(--text-3);margin-top:4px;}
.zone{margin-bottom:36px;}
.zone-header{display:flex;align-items:center;gap:10px;margin-bottom:14px;}
.zone-dot{width:10px;height:10px;border-radius:50%;}
.zone-dot.fire{background:var(--fire);animation:pulse 2s infinite;}
.zone-dot.watch{background:var(--watch);}
.zone-dot.queue{background:var(--text-3);}
@keyframes pulse{0%,100%{opacity:1;box-shadow:0 0 0 0 rgba(255,59,48,0.4);}50%{opacity:0.7;box-shadow:0 0 0 6px rgba(255,59,48,0);}}
.zone-title{font-family:'Syne',sans-serif;font-size:13px;font-weight:700;letter-spacing:0.07em;text-transform:uppercase;}
.zone-title.fire{color:var(--fire);}
.zone-title.watch{color:var(--watch);}
.zone-title.queue{color:var(--text-2);}
.zone-count{font-size:12px;color:var(--text-3);background:var(--bg);border:1px solid var(--border);border-radius:20px;padding:2px 9px;font-weight:500;}
.zone-hint{font-size:12px;color:var(--text-3);}
.zone-empty{padding:28px;background:var(--card);border:1px dashed var(--border);border-radius:var(--r);color:var(--text-3);font-size:13px;text-align:center;}
.cards-grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(380px,1fr));gap:14px;}
.esc-card{background:var(--card);border-radius:var(--r);border:1px solid var(--border);border-left:4px solid var(--border);padding:20px;transition:transform 0.15s,box-shadow 0.15s;}
.esc-card:hover{transform:translateY(-2px);box-shadow:0 6px 24px rgba(0,0,0,0.08);}
.esc-card.fire{border-left-color:var(--fire);border-color:var(--fire-border);background:#FFFAF9;}
.esc-card.watch{border-left-color:var(--watch);border-color:var(--watch-border);background:#FFFDF7;}
.card-top{display:flex;align-items:flex-start;justify-content:space-between;margin-bottom:10px;gap:10px;}
.card-account{font-family:'Syne',sans-serif;font-size:15px;font-weight:700;line-height:1.2;}
.card-contact{font-size:11px;color:var(--text-3);margin-top:2px;}
.score-badge{display:flex;flex-direction:column;align-items:center;justify-content:center;width:48px;height:48px;border-radius:10px;flex-shrink:0;}
.score-badge.fire{background:var(--fire-bg);}
.score-badge.watch{background:var(--watch-bg);}
.score-badge.normal{background:var(--bg);}
.score-num{font-family:'Syne',sans-serif;font-size:20px;font-weight:800;line-height:1;}
.score-badge.fire .score-num{color:var(--fire);}
.score-badge.watch .score-num{color:var(--watch);}
.score-badge.normal .score-num{color:var(--text-2);}
.score-max{font-size:9px;color:var(--text-3);}
.tat-badge{display:inline-flex;align-items:center;gap:4px;font-size:10px;font-weight:700;padding:3px 8px;border-radius:20px;font-family:'IBM Plex Mono',monospace;}
.tat-badge.ok{background:#DCFCE7;color:#14532D;}
.tat-badge.warn{background:#FEF3C7;color:#92400E;}
.tat-badge.crit{background:#FEE2E2;color:#991B1B;animation:blink 1.5s infinite;}
@keyframes blink{0%,100%{opacity:1;}50%{opacity:0.55;}}
.tat-dot{width:5px;height:5px;border-radius:50%;background:currentColor;flex-shrink:0;}
.card-flags{display:flex;gap:5px;flex-wrap:wrap;margin-bottom:10px;}
.flag{font-size:10px;font-weight:700;letter-spacing:0.04em;text-transform:uppercase;padding:3px 7px;border-radius:4px;white-space:nowrap;}
.flag.churn{background:#FEF3C7;color:#92400E;}
.flag.emergency{background:#FEE2E2;color:#991B1B;}
.flag.legal{background:#EDE9FE;color:#4C1D95;}
.flag.irdai{background:#DBEAFE;color:#1E3A8A;}
.flag.sla{background:#FFF7ED;color:#7C2D12;}
.flag.issue{background:var(--bg);color:var(--text-2);}
.card-summary{font-size:13px;line-height:1.65;color:var(--text-2);margin-bottom:12px;}
.card-action{background:var(--blue-bg);border-radius:var(--rs);padding:10px 12px;margin-bottom:12px;border-left:3px solid var(--blue);}
.card-action-label{font-size:9px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:var(--blue);margin-bottom:3px;}
.card-action-text{font-size:12px;color:var(--navy-2);font-weight:500;line-height:1.5;}
.card-owner-row{display:flex;align-items:center;gap:8px;margin-bottom:12px;padding:9px 11px;background:var(--bg);border-radius:var(--rs);border:1px solid var(--border);}
.owner-label{font-size:10px;font-weight:700;letter-spacing:0.06em;text-transform:uppercase;color:var(--text-3);white-space:nowrap;}
.owner-input{flex:1;border:none;background:transparent;font-family:'Figtree',sans-serif;font-size:12px;color:var(--text);outline:none;min-width:0;}
.owner-input::placeholder{color:var(--text-3);}
.owner-save{background:var(--navy);color:white;border:none;padding:4px 10px;border-radius:5px;font-size:11px;font-weight:600;cursor:pointer;white-space:nowrap;font-family:'Figtree',sans-serif;}
.owner-saved{font-size:11px;color:var(--safe);font-weight:600;display:none;white-space:nowrap;}
.card-footer{display:flex;align-items:center;justify-content:space-between;gap:6px;flex-wrap:wrap;}
.card-source{font-size:10px;color:var(--text-3);background:var(--bg);padding:2px 7px;border-radius:3px;border:1px solid var(--border);}
.notes-text{font-size:11px;color:var(--text-3);font-style:italic;border-top:1px solid var(--border);padding-top:8px;margin-top:8px;line-height:1.5;}
.status-sel{font-size:10px;font-weight:700;letter-spacing:0.04em;border:none;border-radius:4px;padding:4px 6px;cursor:pointer;font-family:'Figtree',sans-serif;outline:none;}
.status-sel.open{background:#FEE2E2;color:#991B1B;}
.status-sel.in-progress{background:#FEF3C7;color:#92400E;}
.status-sel.blocked{background:#EDE9FE;color:#4C1D95;}
.status-sel.closed{background:#DCFCE7;color:#14532D;}
.queue-controls{display:flex;gap:10px;margin-bottom:12px;align-items:center;flex-wrap:wrap;}
.search-box{flex:1;min-width:180px;max-width:280px;padding:8px 12px;border:1px solid var(--border);border-radius:var(--rs);font-family:'Figtree',sans-serif;font-size:13px;background:white;color:var(--text);outline:none;}
.search-box:focus{border-color:var(--blue);}
.filter-select{padding:8px 12px;border:1px solid var(--border);border-radius:var(--rs);font-family:'Figtree',sans-serif;font-size:13px;background:white;color:var(--text);cursor:pointer;outline:none;}
.table-wrap{background:var(--card);border:1px solid var(--border);border-radius:var(--r);overflow:hidden;overflow-x:auto;}
table{width:100%;border-collapse:collapse;min-width:960px;}
thead{background:var(--navy);}
thead th{padding:11px 14px;font-size:10px;font-weight:700;letter-spacing:0.07em;text-transform:uppercase;color:rgba(255,255,255,0.45);text-align:left;cursor:pointer;white-space:nowrap;user-select:none;}
thead th:hover{color:rgba(255,255,255,0.85);}
tbody tr{border-bottom:1px solid var(--border);transition:background 0.1s;}
tbody tr:last-child{border-bottom:none;}
tbody tr:hover{background:#F8FAFC;}
tbody td{padding:11px 14px;font-size:13px;color:var(--text-2);vertical-align:middle;}
.score-pill{display:inline-flex;align-items:center;justify-content:center;width:32px;height:32px;border-radius:8px;font-family:'Syne',sans-serif;font-size:14px;font-weight:700;}
.score-pill.fire{background:var(--fire-bg);color:var(--fire);}
.score-pill.watch{background:var(--watch-bg);color:var(--watch);}
.score-pill.normal{background:var(--bg);color:var(--text-2);}
.mini-flags{display:flex;gap:3px;flex-wrap:wrap;}
.mini-flag{width:20px;height:20px;border-radius:3px;display:flex;align-items:center;justify-content:center;font-size:9px;font-weight:800;cursor:help;}
.tbl-owner-input{border:1px solid var(--border);border-radius:4px;padding:4px 7px;font-size:11px;font-family:'Figtree',sans-serif;width:120px;outline:none;background:white;}
.tbl-owner-input:focus{border-color:var(--blue);}
.tbl-status-sel{font-size:10px;font-weight:700;letter-spacing:0.03em;border:none;border-radius:4px;padding:4px 6px;cursor:pointer;font-family:'Figtree',sans-serif;outline:none;}
.tbl-status-sel.open{background:#FEE2E2;color:#991B1B;}
.tbl-status-sel.in-progress{background:#FEF3C7;color:#92400E;}
.tbl-status-sel.blocked{background:#EDE9FE;color:#4C1D95;}
.tbl-status-sel.closed{background:#DCFCE7;color:#14532D;}
.section-divider{display:flex;align-items:center;gap:12px;margin:32px 0 16px;}
.sdl{flex:1;height:1px;background:var(--border);}
.sdlabel{font-size:11px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:var(--text-3);}
.input-section{background:var(--card);border:1px solid var(--border);border-radius:var(--r);padding:26px;}
.input-title{font-family:'Syne',sans-serif;font-size:16px;font-weight:700;margin-bottom:4px;}
.input-subtitle{font-size:13px;color:var(--text-3);line-height:1.5;margin-bottom:18px;}
.input-grid{display:grid;grid-template-columns:1fr 230px;gap:16px;align-items:flex-start;}
textarea{width:100%;padding:12px 14px;border:1px solid var(--border);border-radius:var(--rs);font-family:'Figtree',sans-serif;font-size:13px;line-height:1.65;resize:vertical;min-height:130px;color:var(--text);background:var(--bg);outline:none;transition:border-color 0.15s;}
textarea:focus{border-color:var(--blue);background:white;}
textarea::placeholder{color:var(--text-3);}
.submit-col{display:flex;flex-direction:column;gap:10px;}
.submit-btn{background:var(--navy);color:white;border:none;padding:13px 20px;border-radius:var(--rs);font-family:'Syne',sans-serif;font-size:14px;font-weight:700;cursor:pointer;transition:background 0.15s;text-align:center;}
.submit-btn:hover{background:var(--navy-2);}
.submit-btn:disabled{opacity:0.5;cursor:not-allowed;}
.input-hint{font-size:11px;color:var(--text-3);line-height:1.7;}
.submit-status{font-size:12px;padding:9px 12px;border-radius:var(--rs);display:none;line-height:1.5;}
.submit-status.success{background:#DCFCE7;color:#14532D;display:block;}
.submit-status.error{background:#FEE2E2;color:#991B1B;display:block;}
.submit-status.processing{background:var(--blue-bg);color:#1E3A8A;display:block;}
.email-box{background:var(--navy);border-radius:var(--rs);padding:12px 14px;margin-top:2px;}
.email-box-label{font-size:9px;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:rgba(255,255,255,0.35);margin-bottom:4px;}
.email-addr{font-family:'IBM Plex Mono',monospace;font-size:10px;color:rgba(255,255,255,0.6);word-break:break-all;line-height:1.5;}
@media(max-width:1100px){.stats-strip{grid-template-columns:repeat(3,1fr);}}
@media(max-width:800px){main{padding:16px;}.stats-strip{grid-template-columns:repeat(2,1fr);}.cards-grid{grid-template-columns:1fr;}.input-grid{grid-template-columns:1fr;}}
</style>
</head>
<body>
<header>
  <div class="logo">
    <div class="logo-mark">P</div>
    <div><span class="logo-text">Plum<span class="logo-sub">Escalation Intelligence</span></span></div>
  </div>
  <div class="header-right">
    <span class="demo-badge" id="demo-badge" style="display:none">DEMO DATA</span>
    <span class="last-updated" id="last-updated">—</span>
    <button class="refresh-btn" onclick="loadData()">↻ Refresh</button>
  </div>
</header>
<main>
  <div class="stats-strip">
    <div class="stat-card"><div class="stat-label">Total Open</div><div class="stat-value" id="stat-total">—</div><div class="stat-sub">active escalations</div></div>
    <div class="stat-card"><div class="stat-label">On Fire</div><div class="stat-value fire" id="stat-fire">—</div><div class="stat-sub">score ≥ 8 · act now</div></div>
    <div class="stat-card"><div class="stat-label">Watching</div><div class="stat-value watch" id="stat-watch">—</div><div class="stat-sub">score 5–7 · monitor</div></div>
    <div class="stat-card"><div class="stat-label">SLA Breached</div><div class="stat-value fire" id="stat-sla">—</div><div class="stat-sub">open &gt; 48 hrs</div></div>
    <div class="stat-card"><div class="stat-label">No Owner</div><div class="stat-value watch" id="stat-unowned">—</div><div class="stat-sub">unassigned now</div></div>
    <div class="stat-card"><div class="stat-label">Resolved</div><div class="stat-value good" id="stat-closed">—</div><div class="stat-sub">closed this week</div></div>
  </div>
  <div class="zone">
    <div class="zone-header"><div class="zone-dot fire"></div><div class="zone-title fire">Fire Now</div><div class="zone-count" id="fire-count">0</div><span class="zone-hint">Risk score ≥ 8 · legal / IRDAI / medical emergency signals detected · act today</span></div>
    <div class="cards-grid" id="fire-cards"><div class="zone-empty">No fire-level escalations. All clear.</div></div>
  </div>
  <div class="zone">
    <div class="zone-header"><div class="zone-dot watch"></div><div class="zone-title watch">Watching</div><div class="zone-count" id="watch-count">0</div><span class="zone-hint">Score 5–7 · churn risk or SLA breach · monitor closely</span></div>
    <div class="cards-grid" id="watch-cards"><div class="zone-empty">No watch-level escalations right now.</div></div>
  </div>
  <div class="zone">
    <div class="zone-header"><div class="zone-dot queue"></div><div class="zone-title queue">Full Queue</div><div class="zone-count" id="queue-count">0</div><span class="zone-hint">All escalations · assign owners and update status directly here</span></div>
    <div class="queue-controls">
      <input type="text" class="search-box" placeholder="Search account or summary..." id="search-box" oninput="renderTable()">
      <select class="filter-select" id="filter-issue" onchange="renderTable()"><option value="">All issue types</option><option value="claim_stuck">Claim stuck</option><option value="emergency">Emergency</option><option value="onboarding">Onboarding</option><option value="billing">Billing</option><option value="training">Training</option><option value="other">Other</option></select>
      <select class="filter-select" id="filter-status" onchange="renderTable()"><option value="">All statuses</option><option value="Open">Open</option><option value="In Progress">In Progress</option><option value="Blocked">Blocked</option><option value="Closed">Closed</option></select>
      <select class="filter-select" id="filter-risk" onchange="renderTable()"><option value="">All risk levels</option><option value="fire">Fire (≥8)</option><option value="watch">Watch (5–7)</option><option value="normal">Normal (&lt;5)</option></select>
    </div>
    <div class="table-wrap">
      <table>
        <thead><tr>
          <th onclick="sortBy('composite_score')">Score ↕</th>
          <th onclick="sortBy('account')">Account ↕</th>
          <th>Issue</th><th>Summary</th><th>Signals</th>
          <th onclick="sortBy('timestamp')">TAT ↕</th>
          <th>Owner</th><th>Status</th>
        </tr></thead>
        <tbody id="queue-tbody"><tr><td colspan="8" style="text-align:center;padding:40px;color:var(--text-3)">Loading...</td></tr></tbody>
      </table>
    </div>
  </div>
  <div class="section-divider"><div class="sdl"></div><div class="sdlabel">Add Escalation Manually</div><div class="sdl"></div></div>
  <div class="input-section">
    <div class="input-title">Add Escalation Manually</div>
    <div class="input-subtitle">Paste any message — email, WhatsApp text, Slack thread. Gemini reads it, extracts risk signals, scores it, and adds it to the dashboard in ~15 seconds.</div>
    <div class="input-grid">
      <textarea id="msg-input" placeholder="Paste escalation message here...&#10;&#10;Example: Dear Avik, I am writing to formally escalate the experience during Rahul Gaur's medical emergency. The Health ID was never issued despite 20+ follow-up emails..."></textarea>
      <div class="submit-col">
        <button class="submit-btn" id="submit-btn" onclick="submitEscalation()">Process Escalation →</button>
        <div class="input-hint">Gemini extracts: account name · issue type · urgency 1–5 · churn / emergency / legal / IRDAI / SLA signals · composite risk score · suggested action for VP.</div>
        <div class="submit-status" id="submit-status"></div>
        <div class="email-box"><div class="email-box-label">Or forward emails directly to</div><div class="email-addr"><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="18702a7b7b6f752d702f2c607277732f206a292a7521767b727c7673687120742d5870777773366d6b2a367579737d367b7775">[email&#160;protected]</a></div></div>
      </div>
    </div>
  </div>
</main>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
const SHEET_ID='1cLwLZ5COwH_M-7Ai0HshNRdTSLcyMRlLLyjbFLgWPxo';
const WEBHOOK='https://hook.us2.make.com/gteix35k28vaopr78cf8n41de963lol3';
const CSV_URL=`https://docs.google.com/spreadsheets/d/${SHEET_ID}/export?format=csv&gid=0`;
const n=Date.now(),h=hrs=>new Date(n-hrs*3600000).toISOString().slice(0,16).replace('T',' ');
const DEMO=[
  {id:'ESC-001',timestamp:h(52),source:'email',account:'Agnihotra Manufacturing Pvt Ltd',contact_name:'Snigdha Saha — HR Head',issue_type:'emergency',summary:'Employee Rahul Gaur (EmpID PM0227, Claim 82086141) underwent emergency surgery. Cashless processing was blocked because the Health ID was never issued despite 20+ follow-up emails over the past month. The HR team had to personally coordinate with hospital, TPA, and multiple Plum contacts. POC Nishita was reportedly hostile when HR sought help and instructed them to manage it themselves. Toll-free number was also unreachable during the crisis.',base_urgency:'5',churn_risk:'true',emergency_flag:'true',legal_threat:'true',irdai_mention:'true',sla_breach:'true',composite_score:'13',key_names:'Rahul Gaur · EmpID PM0227 · Claim 82086141',suggested_action:'Call Snigdha Saha within the hour, personally commit to a senior RM replacement, and ensure Health ID and claim resolution today.',owner:'Avik Bhandari',status:'In Progress',notes:'IL notified. Claim to be processed as business exception. UW approval awaited. TAT committed to next Friday.'},
  {id:'ESC-002',timestamp:h(38),source:'email',account:'SME Factory Client — Mumbai',contact_name:'Factory Owner (name unknown)',issue_type:'claim_stuck',summary:'Client has a reimbursement claim in progress. The portal requires documents uploaded one by one with strict scan format and placement rules — extremely time consuming. Website crashed after the full upload was complete. Client emailed all documents to Plum requesting they upload on their behalf, but received no response. Also requested an offline Mumbai contact for physical document handover — this too was ignored. Client is reconsidering Plum vs traditional offline agent.',base_urgency:'4',churn_risk:'true',emergency_flag:'false',legal_threat:'false',irdai_mention:'false',sla_breach:'false',composite_score:'6',key_names:'None',suggested_action:'Assign an RM to manually upload the documents this week and create an offline submission pathway for SME accounts in Mumbai.',owner:'',status:'Open',notes:''},
  {id:'ESC-003',timestamp:h(29),source:'email',account:'BF5278 Enterprises',contact_name:'Karan',issue_type:'onboarding',summary:'Payment was made on 20 Feb 2026 to add a new employee. Promised TAT was 3–5 working days. Today is 28 Feb — 8 days elapsed with no update. Karan is following up with a payment screenshot attached.',base_urgency:'3',churn_risk:'false',emergency_flag:'false',legal_threat:'false',irdai_mention:'false',sla_breach:'true',composite_score:'5',key_names:'Employee addition pending · Payment proof attached',suggested_action:'Check employee addition status in system immediately and reply to Karan today with a confirmed completion date.',owner:'Abhishek Ranjan',status:'In Progress',notes:'Fasttracked per Arun Chacko. DUR pendency on consultation paper and self-attestation — closed per Rajorshi.'},
  {id:'ESC-004',timestamp:h(72),source:'email',account:'Unnamed — HR Community',contact_name:'HR Director (name withheld)',issue_type:'other',summary:'Client stated explicitly they will not put a good word for Plum to anyone in the HR community. Refused to fill feedback survey citing no improvement on previously raised escalations. This is a direct reputation risk — HR directors are highly networked and influence group insurance purchasing decisions across the market.',base_urgency:'4',churn_risk:'true',emergency_flag:'false',legal_threat:'false',irdai_mention:'false',sla_breach:'false',composite_score:'6',key_names:'None',suggested_action:'Schedule a service recovery call with this HR director this week before they speak to peers or post publicly.',owner:'',status:'Open',notes:''},
  {id:'ESC-005',timestamp:h(18),source:'email',account:'Rishabh Arora & Associates',contact_name:'HR Manager',issue_type:'training',summary:'Employees have not started using the Plum app. The Thursday group training session felt generic — staff could not ask questions or fully understand the application. Tax invoices are also still pending. There is a risk that the insurance benefits go entirely unused, creating a renewal risk at policy end.',base_urgency:'3',churn_risk:'false',emergency_flag:'false',legal_threat:'false',irdai_mention:'false',sla_breach:'false',composite_score:'3',key_names:'None',suggested_action:'Assign onboarding specialist to schedule a company-specific 45-min session within this week and resolve the pending tax invoices.',owner:'Vaishnavi Bhat',status:'In Progress',notes:'Dedicated training to be scheduled. Tax invoice follow-up still pending.'},
  {id:'ESC-006',timestamp:h(96),source:'slack',account:'Chirag Gupta Industries',contact_name:'Director (Mikhel Dhiman — internal)',issue_type:'claim_stuck',summary:'Internal Slack thread: client call with director did not go as expected. Claim needs processing as business exception. IL awaiting UW approval with TAT committed to next Friday. Separately, hotline calls from client are getting disconnected — technical issue unresolved.',base_urgency:'4',churn_risk:'false',emergency_flag:'false',legal_threat:'false',irdai_mention:'false',sla_breach:'true',composite_score:'6',key_names:'Chirag Gupta · Claim L7533',suggested_action:'Follow up on UW approval with Arun today and escalate the hotline disconnection issue to tech support.',owner:'Arun Chacko',status:'Blocked',notes:'IL processing claim as business exception per Avik. UW approval pending. Hotline issue not yet resolved.'},
  {id:'ESC-007',timestamp:h(6),source:'email',account:'Unknown',contact_name:'Unknown',issue_type:'other',summary:'Single-line email: "Request to call." No context, no account name, no issue details. Could be time-sensitive — clients who keep it brief are often either very busy or very frustrated.',base_urgency:'2',churn_risk:'false',emergency_flag:'false',legal_threat:'false',irdai_mention:'false',sla_breach:'false',composite_score:'2',key_names:'None',suggested_action:'Call back today to understand the issue before it goes unaddressed and escalates further.',owner:'',status:'Open',notes:''}
];
let allData=[],sortField='composite_score',sortDir=-1,ownerEdits={},statusEdits={};
function parseCSV(t){
  const lines=t.trim().split('\n');if(lines.length<2)return[];
  const hdrs=lines[0].split(',').map(h=>h.trim().replace(/^"|"$/g,''));
  return lines.slice(1).map(line=>{
    const cols=[];let q=false,c='';
    for(const ch of line){if(ch==='"'){q=!q;}else if(ch===','&&!q){cols.push(c);c='';}else{c+=ch;}}
    cols.push(c);
    const o={};hdrs.forEach((h,i)=>{o[h]=(cols[i]||'').trim().replace(/^"|"$/g,'');});return o;
  }).filter(r=>r.id&&r.id!=='id'&&r.id.trim()!=='');
}
async function loadData(){
  document.getElementById('last-updated').textContent='Refreshing...';
  let liveRows=[];
  try{
    const res=await fetch(CSV_URL+'&nocache='+Date.now());
    const txt=await res.text();
    const p=parseCSV(txt);
    if(p.length>0){
      liveRows=p.map(r=>({
        ...r,
        composite_score:String(parseInt(r.composite_score)||0),
        base_urgency:String(parseInt(r.base_urgency)||3),
        churn_risk:r.churn_risk==='true'||r.churn_risk===true?'true':'false',
        emergency_flag:r.emergency_flag==='true'||r.emergency_flag===true?'true':'false',
        legal_threat:r.legal_threat==='true'||r.legal_threat===true?'true':'false',
        irdai_mention:r.irdai_mention==='true'||r.irdai_mention===true?'true':'false',
        sla_breach:r.sla_breach==='true'||r.sla_breach===true?'true':'false',
        owner:ownerEdits[r.id]!==undefined?ownerEdits[r.id]:r.owner,
        status:statusEdits[r.id]!==undefined?statusEdits[r.id]:r.status
      }));
    }
  }catch(e){}
  const liveIds=new Set(liveRows.map(r=>r.id));
  const demoRows=DEMO.filter(r=>!liveIds.has(r.id)).map(r=>({
    ...r,
    owner:ownerEdits[r.id]!==undefined?ownerEdits[r.id]:r.owner,
    status:statusEdits[r.id]!==undefined?statusEdits[r.id]:r.status
  }));
  allData=[...liveRows,...demoRows];
  if(liveRows.length>0){
    document.getElementById('demo-badge').style.display='none';
  } else {
    document.getElementById('demo-badge').style.display='inline-block';
  }
  renderAll();
  const t=new Date();
  document.getElementById('last-updated').textContent='Updated '+t.toLocaleTimeString('en-IN',{hour:'2-digit',minute:'2-digit'})+(liveRows.length>0?' · '+liveRows.length+' live':' · demo only');
}
function sc(s){const n=parseInt(s)||0;return n>=8?'fire':n>=5?'watch':'normal';}
function il(t){return{claim_stuck:'Claim Stuck',onboarding:'Onboarding',billing:'Billing',training:'Training',emergency:'Emergency',other:'Other'}[t]||t||'—';}
function tat(ts){
  if(!ts)return{h:0,label:'—',cls:'ok'};
  const d=new Date(ts);if(isNaN(d))return{h:0,label:'—',cls:'ok'};
  const hrs=Math.floor((Date.now()-d.getTime())/3600000);
  if(hrs<24)return{h:hrs,label:hrs+'h open',cls:'ok'};
  if(hrs<48)return{h:hrs,label:Math.floor(hrs/24)+'d '+Math.floor(hrs%24)+'h',cls:'warn'};
  return{h:hrs,label:Math.floor(hrs/24)+'d — SLA breach',cls:'crit'};
}
function flags(row,mini){
  const f=[];
  if(row.emergency_flag==='true')f.push(mini?{c:'emergency',t:'E',title:'Medical Emergency'}:{c:'emergency',t:'EMERGENCY'});
  if(row.legal_threat==='true')f.push(mini?{c:'legal',t:'L',title:'Legal Threat'}:{c:'legal',t:'LEGAL THREAT'});
  if(row.irdai_mention==='true')f.push(mini?{c:'irdai',t:'I',title:'IRDAI Mentioned'}:{c:'irdai',t:'IRDAI'});
  if(row.churn_risk==='true')f.push(mini?{c:'churn',t:'C',title:'Churn Risk'}:{c:'churn',t:'CHURN RISK'});
  if(row.sla_breach==='true')f.push(mini?{c:'sla',t:'S',title:'SLA Breach'}:{c:'sla',t:'SLA BREACH'});
  return f;
}
function stcls(s){return(s||'open').toLowerCase().replace(/\s+/g,'-');}
function buildCard(row){
  const score=parseInt(row.composite_score)||0,cls=sc(row.composite_score),ff=flags(row,false),t=tat(row.timestamp),st=stcls(row.status||'Open');
  return`<div class="esc-card ${cls}">
    <div class="card-top">
      <div style="flex:1;min-width:0">
        <div class="card-account">${row.account||'Unknown'}</div>
        <div class="card-contact">${row.contact_name&&row.contact_name!=='Unknown'?row.contact_name+' · ':''}${il(row.issue_type)}</div>
      </div>
      <div class="score-badge ${cls}"><div class="score-num">${score}</div><div class="score-max">/17</div></div>
    </div>
    <div class="card-flags">
      ${ff.map(f=>`<span class="flag ${f.c}">${f.t}</span>`).join('')}
      <span class="flag issue">${il(row.issue_type)}</span>
      <span class="tat-badge ${t.cls}"><span class="tat-dot"></span>${t.label}</span>
    </div>
    <div class="card-summary">${row.summary||'—'}</div>
    ${row.suggested_action?`<div class="card-action"><div class="card-action-label">Suggested action for VP</div><div class="card-action-text">${row.suggested_action}</div></div>`:''}
    <div class="card-owner-row">
      <span class="owner-label">Owner</span>
      <input class="owner-input" id="own-${row.id}" placeholder="Assign to..." value="${row.owner||''}">
      <button class="owner-save" onclick="saveOwner('${row.id}')">Save</button>
      <span class="owner-saved" id="ownsaved-${row.id}">✓ Saved</span>
    </div>
    <div class="card-footer">
      <span class="card-source">${row.source||'email'}</span>
      ${row.notes&&row.notes.trim()?`<span style="font-size:10px;color:var(--text-3);font-style:italic;max-width:200px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap" title="${row.notes}">${row.notes}</span>`:''}
      <select class="status-sel ${st}" onchange="saveStatus('${row.id}',this.value,this)">
        <option ${(row.status||'Open')==='Open'?'selected':''}>Open</option>
        <option ${row.status==='In Progress'?'selected':''}>In Progress</option>
        <option ${row.status==='Blocked'?'selected':''}>Blocked</option>
        <option ${row.status==='Closed'?'selected':''}>Closed</option>
      </select>
    </div>
  </div>`;
}
function saveOwner(id){
  const val=document.getElementById('own-'+id).value.trim();
  ownerEdits[id]=val;const idx=allData.findIndex(r=>r.id===id);if(idx>=0)allData[idx].owner=val;
  const s=document.getElementById('ownsaved-'+id);s.style.display='inline';setTimeout(()=>{s.style.display='none';},2000);
  renderStats();renderTable();
}
function saveStatus(id,val,sel){
  statusEdits[id]=val;const idx=allData.findIndex(r=>r.id===id);if(idx>=0)allData[idx].status=val;
  sel.className='status-sel '+stcls(val);renderStats();renderCards();renderTable();
}
function saveTblOwner(id){
  const inp=document.getElementById('tblo-'+id);if(!inp)return;
  const val=inp.value.trim();ownerEdits[id]=val;const idx=allData.findIndex(r=>r.id===id);if(idx>=0)allData[idx].owner=val;
  renderStats();renderCards();
}
function saveTblStatus(id,val,sel){
  statusEdits[id]=val;const idx=allData.findIndex(r=>r.id===id);if(idx>=0)allData[idx].status=val;
  sel.className='tbl-status-sel '+stcls(val);renderStats();renderCards();
}
function renderCards(){
  const open=allData.filter(r=>r.status!=='Closed');
  const fire=open.filter(r=>parseInt(r.composite_score)>=8).sort((a,b)=>(parseInt(b.composite_score)||0)-(parseInt(a.composite_score)||0));
  const watch=open.filter(r=>{const s=parseInt(r.composite_score)||0;return s>=5&&s<8;}).sort((a,b)=>(parseInt(b.composite_score)||0)-(parseInt(a.composite_score)||0));
  document.getElementById('fire-count').textContent=fire.length;
  document.getElementById('watch-count').textContent=watch.length;
  document.getElementById('fire-cards').innerHTML=fire.length?fire.map(buildCard).join(''):'<div class="zone-empty">No fire-level escalations right now. All clear.</div>';
  document.getElementById('watch-cards').innerHTML=watch.length?watch.map(buildCard).join(''):'<div class="zone-empty">No watch-level escalations right now.</div>';
}
function renderStats(){
  const open=allData.filter(r=>r.status!=='Closed'),closed=allData.filter(r=>r.status==='Closed');
  document.getElementById('stat-total').textContent=open.length;
  document.getElementById('stat-fire').textContent=open.filter(r=>parseInt(r.composite_score)>=8).length;
  document.getElementById('stat-watch').textContent=open.filter(r=>{const s=parseInt(r.composite_score)||0;return s>=5&&s<8;}).length;
  document.getElementById('stat-sla').textContent=open.filter(r=>tat(r.timestamp).h>=48).length;
  document.getElementById('stat-unowned').textContent=open.filter(r=>!r.owner||!r.owner.trim()).length;
  document.getElementById('stat-closed').textContent=closed.length;
}
function renderTable(){
  const search=(document.getElementById('search-box').value||'').toLowerCase();
  const issF=document.getElementById('filter-issue').value,stF=document.getElementById('filter-status').value,rkF=document.getElementById('filter-risk').value;
  let rows=[...allData].filter(r=>{
    if(search&&!(r.account||'').toLowerCase().includes(search)&&!(r.summary||'').toLowerCase().includes(search))return false;
    if(issF&&r.issue_type!==issF)return false;if(stF&&r.status!==stF)return false;
    if(rkF&&sc(r.composite_score)!==rkF)return false;return true;
  });
  rows.sort((a,b)=>{let av=a[sortField]||'',bv=b[sortField]||'';if(sortField==='composite_score'){av=parseInt(av)||0;bv=parseInt(bv)||0;}if(av<bv)return sortDir;if(av>bv)return-sortDir;return 0;});
  document.getElementById('queue-count').textContent=rows.length;
  const tbody=document.getElementById('queue-tbody');
  if(!rows.length){tbody.innerHTML='<tr><td colspan="8" style="text-align:center;padding:32px;color:var(--text-3)">No escalations match your filters.</td></tr>';return;}
  tbody.innerHTML=rows.map(r=>{
    const score=parseInt(r.composite_score)||0,cls=sc(r.composite_score),ff=flags(r,true),t=tat(r.timestamp),st=stcls(r.status||'Open');
    const sum=(r.summary||'').substring(0,110)+(r.summary&&r.summary.length>110?'…':'');
    return`<tr>
      <td><span class="score-pill ${cls}">${score}</span></td>
      <td><div style="font-weight:600;color:var(--text);font-size:13px">${r.account||'Unknown'}</div><div style="font-size:11px;color:var(--text-3)">${r.contact_name&&r.contact_name!=='Unknown'?r.contact_name:''}</div></td>
      <td><span class="flag issue" style="white-space:nowrap">${il(r.issue_type)}</span></td>
      <td style="max-width:220px;font-size:12px;line-height:1.5;color:var(--text-2)">${sum}</td>
      <td><div class="mini-flags">${ff.map(f=>`<span class="mini-flag flag ${f.c}" title="${f.title||f.c}">${f.t}</span>`).join('')||'<span style="color:var(--text-3);font-size:11px">—</span>'}</div></td>
      <td><span class="tat-badge ${t.cls}" style="white-space:nowrap"><span class="tat-dot"></span>${t.label}</span></td>
      <td style="min-width:140px"><input class="tbl-owner-input" id="tblo-${r.id}" value="${r.owner||''}" placeholder="Assign..." onblur="saveTblOwner('${r.id}')"></td>
      <td><select class="tbl-status-sel ${st}" onchange="saveTblStatus('${r.id}',this.value,this)"><option ${(r.status||'Open')==='Open'?'selected':''}>Open</option><option ${r.status==='In Progress'?'selected':''}>In Progress</option><option ${r.status==='Blocked'?'selected':''}>Blocked</option><option ${r.status==='Closed'?'selected':''}>Closed</option></select></td>
    </tr>`;
  }).join('');
}
function renderAll(){renderStats();renderCards();renderTable();}
function sortBy(f){if(sortField===f)sortDir*=-1;else{sortField=f;sortDir=-1;}renderTable();}
async function submitEscalation(){
  const msg=document.getElementById('msg-input').value.trim();if(!msg){document.getElementById('msg-input').focus();return;}
  const btn=document.getElementById('submit-btn'),st=document.getElementById('submit-status');
  btn.disabled=true;btn.textContent='Sending to Gemini...';
  st.className='submit-status processing';st.textContent='Analyzing with Gemini — extracting risk signals and scoring...';
  try{
    await fetch(WEBHOOK,{method:'POST',headers:{'Content-Type':'application/json'},body:JSON.stringify({message:msg}),mode:'no-cors'});
    st.className='submit-status success';st.textContent='✓ Sent. Result will appear on dashboard in ~15 seconds.';
    document.getElementById('msg-input').value='';
    setTimeout(()=>loadData(),16000);setTimeout(()=>loadData(),32000);
  }ca
