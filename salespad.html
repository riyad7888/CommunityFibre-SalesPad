<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no"/>
<meta name="mobile-web-app-capable" content="yes"/>
<meta name="apple-mobile-web-app-capable" content="yes"/>
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent"/>
<meta name="apple-mobile-web-app-title" content="CF SalesPad"/>
<meta name="theme-color" content="#3a1f6e"/>
<title>CF SalesPad</title>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Mono:wght@400;500&family=DM+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet"/>
<style>
:root {
  --bg: #1a0d35;
  --card: #23134a;
  --card2: #2c1a5a;
  --border: #3d2570;
  --accent: #2ecc71;
  --accent2: #27ae60;
  --text: #f0eaff;
  --muted: #5a3d8a;
  --muted2: #9b7ecb;
  --red: #ff4e6a;
  --yellow: #ffd166;
  --purple: #c4a8ff;
  --orange: #fb923c;
  --green: #2ecc71;
  --radius: 14px;
}
* { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }
html, body { height: 100%; overflow: hidden; }
body {
  background: var(--bg);
  color: var(--text);
  font-family: 'DM Sans', sans-serif;
  display: flex; flex-direction: column;
  height: 100dvh;
  position: relative;
}
body::before {
  content: '';
  position: fixed; inset: 0; z-index: 0; pointer-events: none;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='80' height='50'%3E%3Cpath d='M0 25 Q10 10 20 25 Q30 40 40 25 Q50 10 60 25 Q70 40 80 25' fill='none' stroke='%234a2880' stroke-width='1.5' opacity='0.6'/%3E%3Cpath d='M0 45 Q10 30 20 45 Q30 60 40 45 Q50 30 60 45 Q70 60 80 45' fill='none' stroke='%234a2880' stroke-width='1.5' opacity='0.6'/%3E%3Cpath d='M0 5 Q10 -10 20 5 Q30 20 40 5 Q50 -10 60 5 Q70 20 80 5' fill='none' stroke='%234a2880' stroke-width='1.5' opacity='0.6'/%3E%3C/svg%3E");
  background-size: 80px 50px;
}

/* ── HEADER ── */
#header {
  background: rgba(26,13,53,0.97);
  border-bottom: 1px solid rgba(74,40,128,0.8);
  padding: 11px 16px 10px;
  flex-shrink: 0;
  display: flex; align-items: center; justify-content: space-between;
  gap: 10px;
  position: relative; z-index: 10;
  backdrop-filter: blur(10px);
  box-shadow: 0 2px 24px rgba(0,0,0,0.5);
}
#logo { flex-shrink: 0; display:flex; align-items:center; }
#logo svg { height: 38px; width: auto; }
#month-nav { display: flex; align-items: center; gap: 6px; }
#month-nav button {
  background: none; border: none; color: var(--muted2);
  font-size: 18px; cursor: pointer; padding: 2px 4px;
}
#month-label { font-size: 12px; font-weight: 700; color: var(--text); min-width: 80px; text-align: center; }
#add-btn {
  background: var(--accent); color: var(--bg);
  border: none; border-radius: 10px;
  width: 36px; height: 36px; font-size: 22px;
  cursor: pointer; display: flex; align-items: center; justify-content: center;
  font-weight: 700; flex-shrink: 0;
  box-shadow: 0 0 16px rgba(46,204,113,0.45);
  transition: transform 0.1s;
}
#add-btn:active { transform: scale(0.92); }

/* ── TAB BAR ── */
#tab-bar {
  background: rgba(26,13,53,0.97);
  border-bottom: 1px solid rgba(74,40,128,0.7);
  position: relative; z-index: 9;
  display: flex; flex-shrink: 0;
  padding: 0 12px;
  gap: 4px;
}
.tab-btn {
  flex: 1; background: none; border: none;
  padding: 10px 4px 9px;
  font-family: inherit; font-size: 11px; font-weight: 600;
  color: var(--muted2); cursor: pointer;
  border-bottom: 2px solid transparent;
  transition: all 0.2s; letter-spacing: 0.02em;
  white-space: nowrap;
}
.tab-btn.active { color: var(--accent); border-bottom-color: var(--accent); }

/* ── STATS BAR ── */
#stats-bar {
  background: rgba(35,19,74,0.97);
  border-bottom: 1px solid rgba(74,40,128,0.6);
  position: relative; z-index: 8;
  padding: 8px 14px;
  display: flex; gap: 6px; overflow-x: auto;
  flex-shrink: 0; scrollbar-width: none;
}
#stats-bar::-webkit-scrollbar { display: none; }
.stat-pill {
  background: var(--card2); border: 1px solid var(--border);
  border-radius: 20px; padding: 5px 12px;
  white-space: nowrap; display: flex; align-items: center; gap: 5px;
  font-size: 12px; flex-shrink: 0;
}
.stat-pill .sp-val { font-weight: 700; font-size: 14px; }
.stat-pill.green  { border-color: #34d39940; background: #052e1e; }
.stat-pill.green  .sp-val { color: var(--green); }
.stat-pill.blue   { border-color: #0ff4c640; background: #052e2a; }
.stat-pill.blue   .sp-val { color: var(--accent); }
.stat-pill.purple { border-color: #a78bfa40; background: #1a1235; }
.stat-pill.purple .sp-val { color: var(--purple); }
.stat-pill.yellow { border-color: #ffd16640; background: #2a2005; }
.stat-pill.yellow .sp-val { color: var(--yellow); }
.stat-pill.orange { border-color: #fb923c40; background: #2a1405; }
.stat-pill.orange .sp-val { color: var(--orange); }

/* ── PANELS ── */
.panel { display: none; flex: 1; overflow-y: auto; flex-direction: column; position: relative; z-index: 1; }
.panel.active { display: flex; }
.panel::-webkit-scrollbar { width: 3px; }
.panel::-webkit-scrollbar-thumb { background: var(--border); border-radius: 99px; }

/* ── SEARCH ── */
.search-wrap { padding: 10px 14px 8px; flex-shrink: 0; }
.search-inp {
  width: 100%; background: var(--card2);
  border: 1px solid var(--border); border-radius: 10px;
  padding: 9px 14px; color: var(--text);
  font-family: inherit; font-size: 13px; outline: none;
}
.search-inp::placeholder { color: var(--muted2); }
.search-inp:focus { border-color: var(--accent); }

/* ── LIST ── */
.list-body { flex: 1; padding: 0 14px 16px; }

/* ── SALE CARDS ── */
.sale-card {
  background: rgba(35,19,74,0.85); border: 1px solid rgba(74,40,128,0.6);
  border-radius: var(--radius); padding: 14px; margin-bottom: 10px;
  cursor: pointer; transition: border-color 0.15s, transform 0.1s;
  position: relative; overflow: hidden;
}
.sale-card::before {
  content: ''; position: absolute; top: 0; left: 0; width: 3px; height: 100%;
  background: var(--accent); border-radius: 3px 0 0 3px;
}
.sale-card.lead-card::before { background: var(--yellow); }
.sale-card.contract-card::before { background: var(--purple); }
.sale-card.contract-card.urgent::before { background: var(--red); }
.sale-card.contract-card.soon::before { background: var(--orange); }
.sale-card:active { transform: scale(0.99); border-color: var(--accent); }
.card-top { display: flex; justify-content: space-between; align-items: flex-start; gap: 8px; margin-bottom: 10px; }
.card-addr { font-weight: 600; font-size: 14px; color: var(--text); line-height: 1.3; flex: 1; }
.card-name { font-size: 11px; color: var(--muted2); margin-top: 1px; }
.card-num  { font-family: 'Bebas Neue', sans-serif; font-size: 18px; color: var(--accent); letter-spacing: 1px; flex-shrink: 0; }
.card-date { font-size: 10px; color: var(--muted2); margin-top: 1px; }
.card-tags { display: flex; flex-wrap: wrap; gap: 5px; }
.tag {
  font-size: 10px; font-weight: 600; padding: 3px 8px;
  border-radius: 6px; border: 1px solid;
}
.tag-internet { color: #60a5fa; border-color: #1d4ed840; background: #0c1e3d; }
.tag-tv       { color: #f472b6; border-color: #9d174d40; background: #2d0a1a; }
.tag-call     { color: #34d399; border-color: #06523640; background: #052e1a; }
.tag-norton   { color: #fb923c; border-color: #92400e40; background: #2d1405; }
.tag-publicip { color: #a78bfa; border-color: #4c1d9540; background: #1a0e35; }
.tag-none     { color: var(--muted2); border-color: var(--border); background: var(--card2); }
.tag-provider { color: #fbbf24; border-color: #fbbf2440; background: #2a1f05; }
.tag-reminder { color: var(--accent); border-color: #0ff4c640; background: #052e2a; }
.tag-urgent   { color: var(--red);    border-color: #ff4e6a40; background: #2d0a0a; }
.tag-soon     { color: var(--orange); border-color: #fb923c40; background: #2d1405; }
.tag-contract { color: var(--purple); border-color: #a78bfa40; background: #1a1235; }

/* countdown badge */
.countdown-badge {
  display: inline-flex; align-items: center; gap: 4px;
  font-size: 11px; font-weight: 700; padding: 4px 9px;
  border-radius: 8px; border: 1px solid;
}
.countdown-badge.urgent { color: var(--red);    border-color: #ff4e6a40; background: #2d0a0a; }
.countdown-badge.soon   { color: var(--orange); border-color: #fb923c40; background: #2d1405; }
.countdown-badge.ok     { color: var(--green);  border-color: #34d39940; background: #052e1a; }
.countdown-badge.past   { color: var(--muted2); border-color: var(--border); background: var(--card2); }

/* reminder badge */
.reminder-badge {
  font-size: 11px; font-weight: 600; padding: 3px 8px;
  border-radius: 6px; border: 1px solid;
  color: var(--yellow); border-color: #ffd16640; background: #2a2005;
}
.reminder-badge.overdue { color: var(--red); border-color: #ff4e6a40; background: #2d0a0a; }

.empty-state {
  text-align: center; padding: 60px 20px;
  color: var(--muted2); line-height: 2.2;
}
.empty-icon { font-size: 48px; display: block; margin-bottom: 8px; }
.empty-state strong { font-family: 'Bebas Neue', sans-serif; font-size: 20px; color: var(--muted2); letter-spacing: 1px; }

/* ── CONTRACT TRACKER YEAR/MONTH GRID ── */
.year-section { margin-bottom: 6px; }
.year-label {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 20px; letter-spacing: 2px;
  color: var(--muted2); padding: 14px 14px 6px;
  display: flex; align-items: center; gap: 10px;
}
.year-label span { font-size: 12px; font-family: 'DM Sans', sans-serif; font-weight: 600; color: var(--muted2); letter-spacing: 0; }
.month-row {
  padding: 0 14px 8px;
  display: flex; flex-direction: column; gap: 6px;
}
.month-block {
  background: rgba(35,19,74,0.85); border: 1px solid rgba(74,40,128,0.6);
  border-radius: 12px; overflow: hidden;
}
.month-header {
  display: flex; align-items: center; justify-content: space-between;
  padding: 10px 14px; cursor: pointer;
  background: rgba(44,26,90,0.9);
  transition: background 0.15s;
}
.month-header:active { background: var(--border); }
.month-name {
  font-family: 'Bebas Neue', sans-serif;
  font-size: 16px; letter-spacing: 1px;
  color: var(--text); display: flex; align-items: center; gap: 8px;
}
.month-count {
  font-size: 10px; font-weight: 700;
  background: rgba(15,244,198,0.1); border: 1px solid rgba(15,244,198,0.2);
  color: var(--accent); padding: 2px 7px; border-radius: 8px;
}
.month-count.zero { background: none; border-color: var(--border); color: var(--muted); }
.month-chevron { color: var(--muted2); font-size: 14px; transition: transform 0.2s; }
.month-block.open .month-chevron { transform: rotate(90deg); }
.month-contracts { display: none; padding: 8px 10px 10px; gap: 6px; flex-direction: column; }
.month-block.open .month-contracts { display: flex; }

.contract-row {
  background: rgba(26,13,53,0.7); border: 1px solid rgba(74,40,128,0.5);
  border-radius: 10px; padding: 11px 13px;
  display: flex; align-items: flex-start; gap: 10px;
  cursor: pointer; transition: border-color 0.15s;
  position: relative; overflow: hidden;
}
.contract-row::before {
  content: ''; position: absolute; left: 0; top: 0; bottom: 0;
  width: 3px; background: var(--purple); border-radius: 3px 0 0 3px;
}
.contract-row.urgent::before { background: var(--red); }
.contract-row.soon::before   { background: var(--orange); }
.contract-row:active { border-color: var(--accent); }
.cr-main { flex: 1; min-width: 0; }
.cr-name { font-size: 13px; font-weight: 600; color: var(--text); margin-bottom: 2px; }
.cr-addr { font-size: 11px; color: var(--muted2); margin-bottom: 5px; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
.cr-tags { display: flex; gap: 5px; flex-wrap: wrap; }
.cr-right { flex-shrink: 0; text-align: right; }

.add-contract-btn {
  display: flex; align-items: center; justify-content: center; gap: 6px;
  padding: 10px; border-radius: 10px;
  background: rgba(15,244,198,0.05); border: 1px dashed rgba(15,244,198,0.2);
  color: var(--muted2); font-size: 12px; font-weight: 600;
  cursor: pointer; transition: all 0.15s; font-family: inherit;
}
.add-contract-btn:active { background: rgba(15,244,198,0.1); }

/* ── BOTTOM EXPORT BAR ── */
#bottom-bar {
  background: rgba(26,13,53,0.97); border-top: 1px solid rgba(74,40,128,0.7);
  position: relative; z-index: 10;
  padding: 10px 14px max(10px, env(safe-area-inset-bottom));
  display: flex; gap: 8px; flex-shrink: 0;
}
.bottom-btn {
  flex: 1; background: var(--card2); border: 1px solid var(--border);
  border-radius: 10px; padding: 9px; color: var(--muted2);
  font-family: inherit; font-size: 12px; font-weight: 600;
  cursor: pointer; transition: all 0.15s;
}
.bottom-btn:active { background: var(--border); }
.bottom-btn.accent { background: #052e2a; border-color: var(--accent); color: var(--accent); }

/* ── MODALS ── */
.overlay {
  position: fixed; inset: 0; background: rgba(0,0,0,0.7);
  z-index: 1000; display: flex; align-items: flex-end; justify-content: center;
  backdrop-filter: blur(2px);
}
.modal {
  background: #23134a; border: 1px solid rgba(74,40,128,0.9);
  border-radius: 24px 24px 0 0; width: 100%; max-width: 480px;
  max-height: 92vh; overflow-y: auto;
  padding: 20px 18px 40px;
  animation: slideUp 0.25s ease;
}
@keyframes slideUp { from { transform: translateY(100%); opacity: 0; } to { transform: translateY(0); opacity: 1; } }
.modal::-webkit-scrollbar { width: 3px; }
.modal::-webkit-scrollbar-thumb { background: var(--border); }
.modal-handle { width: 40px; height: 4px; background: var(--border); border-radius: 99px; margin: 0 auto 18px; }
.modal-title {
  font-family: 'Bebas Neue', sans-serif; font-size: 24px; letter-spacing: 1px;
  color: var(--text); margin-bottom: 18px;
  display: flex; justify-content: space-between; align-items: center;
}
.modal-close { background: none; border: none; color: var(--muted2); font-size: 22px; cursor: pointer; }
.field-label { font-size: 10px; font-weight: 700; letter-spacing: 1.5px; color: var(--muted2); text-transform: uppercase; margin-bottom: 5px; margin-top: 12px; }
.field-input {
  width: 100%; background: var(--card2); border: 1px solid var(--border);
  border-radius: 10px; padding: 11px 13px; color: var(--text);
  font-family: inherit; font-size: 14px; outline: none; transition: border-color 0.2s;
}
.field-input:focus { border-color: var(--accent); }
.field-input::placeholder { color: var(--muted); }
.toggle-row { display: flex; gap: 8px; flex-wrap: wrap; margin-top: 2px; }
.toggle-chip {
  padding: 7px 14px; border-radius: 8px; border: 1.5px solid var(--border);
  background: var(--card2); color: var(--muted2); font-size: 13px;
  font-weight: 600; cursor: pointer; transition: all 0.15s; font-family: inherit;
}
.toggle-chip.on { border-color: var(--accent); background: #052e2a; color: var(--accent); }
.toggle-chip.on.tv       { border-color: #f472b6; background: #2d0a1a; color: #f472b6; }
.toggle-chip.on.call     { border-color: #34d399; background: #052e1a; color: #34d399; }
.toggle-chip.on.norton   { border-color: #fb923c; background: #2d1405; color: #fb923c; }
.toggle-chip.on.publicip { border-color: #a78bfa; background: #1a0e35; color: #a78bfa; }
.toggle-chip.on.slot-am  { border-color: #fbbf24; background: #2a1f05; color: #fbbf24; }
.toggle-chip.on.slot-pm  { border-color: #818cf8; background: #1a1840; color: #818cf8; }
.save-btn {
  width: 100%; margin-top: 20px;
  background: var(--accent); color: var(--bg);
  border: none; border-radius: 12px; padding: 15px;
  font-size: 16px; font-weight: 700; cursor: pointer;
  font-family: inherit; letter-spacing: 0.5px;
  box-shadow: 0 4px 20px rgba(15,244,198,0.3);
  transition: transform 0.1s;
}
.save-btn:active { transform: scale(0.98); }
.delete-btn {
  width: 100%; margin-top: 8px; background: none; color: var(--red);
  border: 1px solid #ff4e6a40; border-radius: 12px; padding: 12px;
  font-size: 14px; font-weight: 600; cursor: pointer; font-family: inherit;
}

/* view record */
.record-field {
  display: flex; justify-content: space-between;
  padding: 10px 0; border-bottom: 1px solid var(--border);
  font-size: 13px; gap: 12px;
}
.rf-label { color: var(--muted2); font-weight: 500; flex-shrink: 0; }
.rf-val   { color: var(--text);   font-weight: 600; text-align: right; word-break: break-all; }
.rf-val.accent { color: var(--accent); }
.rf-val.yes    { color: var(--green); }
.rf-val.no     { color: var(--muted); }
.rf-val.warn   { color: var(--orange); }
.rf-val.danger { color: var(--red); }

/* ── TOAST ── */
#toast {
  position: fixed; top: 80px; left: 50%; transform: translateX(-50%);
  background: #052e2a; border: 1px solid var(--accent);
  color: var(--accent); padding: 9px 18px; border-radius: 10px;
  font-size: 13px; font-weight: 600; z-index: 2000;
  display: none; box-shadow: 0 4px 20px rgba(15,244,198,0.2);
  white-space: nowrap;
}

/* ── CREDIT BAR ── */
#credit-bar {
  background: rgba(20,10,42,0.98);
  border-top: 1px solid rgba(74,40,128,0.5);
  padding: 7px 16px max(7px, env(safe-area-inset-bottom));
  display: flex; align-items: center; justify-content: center;
  flex-shrink: 0; position: relative; z-index: 10;
}
.credit-inner {
  display: flex; align-items: center; gap: 6px;
  font-size: 11px; color: rgba(196,168,255,0.65);
  letter-spacing: 0.02em;
}
.credit-inner svg { flex-shrink: 0; }
.credit-inner strong { color: #2ecc71; font-weight: 700; }
/* fix search wrap bg */
.search-wrap { padding: 10px 14px 8px; flex-shrink: 0; background: transparent; position: relative; z-index: 2; }
/* month-count green accent update */
.month-count { background: rgba(46,204,113,0.12); border: 1px solid rgba(46,204,113,0.25); color: var(--accent); }

/* ── DASHBOARD ── */
#panel-dash { padding-bottom: 0; }
.dash-scroll { flex:1; overflow-y:auto; padding: 0 14px 80px; }
.dash-scroll::-webkit-scrollbar { width: 3px; }
.dash-scroll::-webkit-scrollbar-thumb { background: var(--border); border-radius: 99px; }

.dash-month-row {
  display:flex; align-items:center; justify-content:center; gap:12px;
  padding: 14px 0 6px;
}
.dash-month-btn {
  background: rgba(74,40,128,0.4); border: 1px solid var(--border);
  border-radius: 8px; color: var(--muted2);
  font-size: 18px; cursor: pointer; padding: 2px 12px; line-height: 1;
}
#dash-month-label {
  font-family:'Bebas Neue',sans-serif; font-size:20px; letter-spacing:2px; color:var(--text);
  min-width:130px; text-align:center;
}

.dash-hero {
  background: linear-gradient(135deg,rgba(46,204,113,0.15),rgba(46,204,113,0.05));
  border: 1px solid rgba(46,204,113,0.3);
  border-radius: 18px; text-align:center; padding:22px 16px 18px;
  margin: 8px 0 14px;
}
.dash-hero-num {
  font-family:'Bebas Neue',sans-serif; font-size:72px; color:var(--accent);
  line-height:1; letter-spacing:2px;
  text-shadow: 0 0 30px rgba(46,204,113,0.4);
}
.dash-hero-label {
  font-size:13px; font-weight:700; color:var(--text);
  text-transform:uppercase; letter-spacing:0.1em; margin-top:2px;
}
.dash-hero-sub { font-size:11px; color:var(--muted2); margin-top:6px; }

.dash-section-title {
  font-size:10px; font-weight:700; letter-spacing:1.5px;
  color:var(--muted2); text-transform:uppercase;
  padding: 14px 0 8px;
}

.dash-grid {
  display:grid; grid-template-columns:1fr 1fr; gap:8px; margin-bottom:4px;
}
.dash-grid .dt-val { font-size:48px; }
.dash-tile {
  border-radius:14px; padding:14px 10px 12px; text-align:center;
  cursor:pointer; transition:transform 0.15s, opacity 0.15s;
  border:1px solid;
}
.dash-tile:active { transform:scale(0.96); opacity:0.85; }
.dash-tile.green  { background:rgba(46,204,113,0.1);  border-color:rgba(46,204,113,0.3); }
.dash-tile.yellow { background:rgba(255,209,102,0.1); border-color:rgba(255,209,102,0.3); }
.dash-tile.purple { background:rgba(196,168,255,0.1); border-color:rgba(196,168,255,0.3); }
.dash-tile.blue   { background:rgba(96,165,250,0.1);  border-color:rgba(96,165,250,0.3); }
.dash-tile.orange { background:rgba(96,165,250,0.1);  border-color:rgba(96,165,250,0.3); }
.dash-tile.red    { background:rgba(255,78,106,0.1);  border-color:rgba(255,78,106,0.3); }
.dt-icon { font-size:18px; margin-bottom:5px; line-height:1; }
.dt-val  {
  font-family:'Bebas Neue',sans-serif; font-size:32px; line-height:1; letter-spacing:1px;
}
.dash-tile.green  .dt-val { color:var(--accent); }
.dash-tile.yellow .dt-val { color:var(--yellow); }
.dash-tile.purple .dt-val { color:var(--purple); }
.dash-tile.blue   .dt-val { color:#60a5fa; }
.dash-tile.orange .dt-val { color:var(--orange); }
.dash-tile.blue   .dt-val { color:#60a5fa; }
.dash-tile.red    .dt-val { color:var(--red); }
.dt-label { font-size:10px; font-weight:600; color:var(--muted2); margin-top:3px; letter-spacing:0.03em; }

.dash-addons {
  background: rgba(35,19,74,0.7); border:1px solid var(--border);
  border-radius:14px; padding:12px 14px; display:flex; flex-direction:column; gap:10px;
}
.addon-row { display:flex; align-items:center; gap:10px; }
.addon-label { font-size:12px; font-weight:600; color:var(--text); width:85px; flex-shrink:0; }
.addon-bar-wrap { flex:1; height:6px; background:rgba(255,255,255,0.06); border-radius:3px; overflow:hidden; }
.addon-bar { height:100%; border-radius:3px; width:0%; transition:width 0.5s cubic-bezier(0.34,1.56,0.64,1); }
.addon-val { font-family:'DM Mono',monospace; font-size:13px; font-weight:700; color:var(--text); width:24px; text-align:right; flex-shrink:0; }

.dash-attach-card {
  background:rgba(35,19,74,0.7); border:1px solid var(--border);
  border-radius:14px; padding:14px 16px;
  display:flex; align-items:center; gap:14px;
}
.attach-icon { font-size:30px; flex-shrink:0; }
.attach-num  { font-family:'Bebas Neue',sans-serif; font-size:36px; color:var(--purple); line-height:1; letter-spacing:1px; }
.attach-label { font-size:11px; color:var(--muted2); margin-top:2px; }

.dash-trend {
  background:rgba(35,19,74,0.7); border:1px solid var(--border);
  border-radius:14px; padding:14px 14px 10px;
  display:flex; align-items:flex-end; gap:6px; height:90px;
  margin-bottom:8px;
}
.trend-bar-wrap { flex:1; display:flex; flex-direction:column; align-items:center; gap:4px; }
.trend-bar-bg   { width:100%; flex:1; background:rgba(255,255,255,0.05); border-radius:4px; display:flex; align-items:flex-end; overflow:hidden; }
.trend-bar-fill { width:100%; background:rgba(46,204,113,0.5); border-radius:4px; transition:height 0.5s ease; }
.trend-bar-fill.current { background:var(--accent); box-shadow:0 0 8px rgba(46,204,113,0.4); }
.trend-label    { font-size:9px; font-weight:600; color:var(--muted2); letter-spacing:0.04em; }
.trend-val      { font-size:10px; font-weight:700; color:var(--muted2); }
.trend-bar-wrap.current .trend-label { color:var(--accent); }
.trend-bar-wrap.current .trend-val   { color:var(--accent); }

/* ── SALE STATUS CHIP STYLES ── */
.status-chip {
  font-size:10px; font-weight:700; padding:3px 8px; border-radius:6px; border:1px solid;
}
.status-installed   { color:var(--green);   border-color:#2ecc7140; background:#052e1a; }
.status-pending     { color:var(--yellow);  border-color:#ffd16640; background:#2a2005; }
.status-cancelled   { color:var(--red);     border-color:#ff4e6a40; background:#2d0a0a; }
.status-reschedule  { color:#60a5fa;        border-color:#60a5fa40; background:#0c1e3d; }

/* Status toggle active states */
#status-installed.on   { border-color:var(--green);  background:#052e1a; color:var(--green); }
#status-pending.on     { border-color:var(--yellow); background:#2a2005; color:var(--yellow); }
#status-cancelled.on   { border-color:var(--red);    background:#2d0a0a; color:var(--red); }
#status-reschedule.on  { border-color:#60a5fa;       background:#0c1e3d; color:#60a5fa; }

/* ── ATTACHMENT UPLOAD ── */
.attach-upload-area {
  background:rgba(44,26,90,0.5); border:1px dashed rgba(196,168,255,0.3);
  border-radius:10px; padding:10px 12px;
}
.attach-upload-btn {
  background:rgba(196,168,255,0.1); border:1px solid rgba(196,168,255,0.3);
  border-radius:8px; padding:8px 14px; color:var(--purple);
  font-family:inherit; font-size:13px; font-weight:600; cursor:pointer;
  transition:all 0.15s;
}
.attach-upload-btn:active { background:rgba(196,168,255,0.2); }
#attach-list { display:flex; flex-wrap:wrap; gap:6px; margin-top:8px; }
.attach-item {
  display:flex; align-items:center; gap:5px;
  background:rgba(196,168,255,0.1); border:1px solid rgba(196,168,255,0.2);
  border-radius:8px; padding:4px 10px;
  font-size:11px; color:var(--purple); cursor:pointer;
  max-width:180px;
}
.attach-item span { overflow:hidden; text-overflow:ellipsis; white-space:nowrap; }
.attach-remove { flex-shrink:0; font-size:14px; color:var(--muted2); }


/* ── REMINDERS ── */
.reminder-section-title {
  font-size:10px; font-weight:700; letter-spacing:1.5px;
  color:var(--muted2); text-transform:uppercase;
  padding: 14px 0 8px; border-bottom:1px solid var(--border); margin-bottom:10px;
}
.reminder-item {
  display:flex; align-items:flex-start; gap:12px;
  padding:12px 0; border-bottom:1px solid rgba(255,255,255,0.05);
  cursor:pointer; transition:opacity 0.15s;
}
.reminder-item:active { opacity:0.75; }
.reminder-item:last-child { border-bottom:none; }
.ri-dot {
  width:10px; height:10px; border-radius:50%; flex-shrink:0; margin-top:4px;
}
.ri-dot.overdue  { background:var(--red);    box-shadow:0 0 6px rgba(255,78,106,0.5); }
.ri-dot.today    { background:var(--yellow); box-shadow:0 0 6px rgba(255,209,102,0.5); }
.ri-dot.soon     { background:var(--orange); box-shadow:0 0 6px rgba(251,146,60,0.5); }
.ri-dot.upcoming { background:var(--purple); box-shadow:0 0 6px rgba(196,168,255,0.4); }
.ri-body { flex:1; min-width:0; }
.ri-name { font-size:13px; font-weight:600; color:var(--text); margin-bottom:2px; }
.ri-detail { font-size:11px; color:var(--muted2); line-height:1.5; }
.ri-badge {
  font-size:10px; font-weight:700; padding:3px 8px; border-radius:6px; border:1px solid;
  flex-shrink:0; white-space:nowrap;
}
.ri-badge.overdue  { color:var(--red);    border-color:#ff4e6a40; background:#2d0a0a; }
.ri-badge.today    { color:var(--yellow); border-color:#ffd16640; background:#2a2005; }
.ri-badge.soon     { color:var(--orange); border-color:#fb923c40; background:#2d1405; }
.ri-badge.upcoming { color:var(--purple); border-color:#c4a8ff40; background:#1a1235; }
.reminder-empty {
  text-align:center; padding:30px 20px;
  color:var(--muted2); font-size:13px; line-height:2;
}
#bell-btn:has(+ *) { }
#bell-btn .bell-has-alerts { color:var(--yellow); }

</style>
</head>
<body>

<!-- HEADER -->
<div id="header">
  <div id="logo">
    <svg viewBox="0 0 200 60" xmlns="http://www.w3.org/2000/svg">
      <!-- CF spiral icon -->
      <g transform="translate(4,4)">
        <circle cx="26" cy="26" r="26" fill="white" opacity="0.95"/>
        <circle cx="26" cy="26" r="22" fill="white" opacity="0"/>
        <!-- Green C spiral -->
        <path d="M26 8 C15 8 7 16 7 26 C7 36 15 44 26 44 C32 44 37.5 41.5 41.5 37.5 L37 33 C34.2 35.8 30.3 37.5 26 37.5 C18.5 37.5 12.5 31.5 12.5 26 C12.5 18.5 18.5 12.5 26 12.5 C30.3 12.5 34.2 14.2 37 17 L41.5 12.5 C37.5 8.5 32 6 26 6 Z" fill="#2ecc71"/>
        <circle cx="26" cy="26" r="6" fill="#2ecc71" opacity="0.2"/>
        <path d="M26 20 C22.7 20 20 22.7 20 26 C20 29.3 22.7 32 26 32 C28.2 32 30.1 30.8 31.2 29 L27.8 27 C27.3 27.6 26.7 28 26 28 C24.9 28 24 27.1 24 26 C24 24.9 24.9 24 26 24 C26.7 24 27.3 24.4 27.8 25 L31.2 23 C30.1 21.2 28.2 20 26 20 Z" fill="#2ecc71"/>
      </g>
      <!-- Community Fibre text -->
      <text x="62" y="28" font-family="'DM Sans',sans-serif" font-weight="700" font-size="13.5" fill="#2ecc71" letter-spacing="0.2">Community</text>
      <text x="62" y="46" font-family="'DM Sans',sans-serif" font-weight="700" font-size="13.5" fill="#f0eaff" letter-spacing="0.2">Fibre</text>
      <!-- SalesPad label -->
      <text x="145" y="28" font-family="'DM Sans',sans-serif" font-weight="700" font-size="9" fill="rgba(196,168,255,0.7)" letter-spacing="0.5">SALES</text>
      <text x="145" y="42" font-family="'DM Sans',sans-serif" font-weight="700" font-size="9" fill="rgba(196,168,255,0.7)" letter-spacing="0.5">PAD</text>
    </svg>
  </div>
  <div id="month-nav">
    <button onclick="changeMonth(-1)">‹</button>
    <div id="month-label">March 2026</div>
    <button onclick="changeMonth(1)">›</button>
  </div>
  <div style="display:flex;align-items:center;gap:8px;">
    <button id="bell-btn" onclick="openReminders()" style="position:relative;background:rgba(74,40,128,0.4);border:1px solid var(--border);border-radius:10px;width:36px;height:36px;cursor:pointer;display:flex;align-items:center;justify-content:center;font-size:18px;flex-shrink:0;transition:all 0.15s;">
      🔔
      <span id="bell-badge" style="display:none;position:absolute;top:-4px;right:-4px;background:var(--red);color:#fff;font-size:9px;font-weight:700;min-width:16px;height:16px;border-radius:8px;display:none;align-items:center;justify-content:center;padding:0 3px;font-family:inherit;border:2px solid var(--bg);"></span>
    </button>
    <button id="add-btn" onclick="handleAdd()">+</button>
  </div>
</div>

<!-- TAB BAR -->
<div id="tab-bar">
  <button class="tab-btn" onclick="switchTab('dash',this)">📊 Dashboard</button>
  <button class="tab-btn active" onclick="switchTab('sales',this)">📋 Sales</button>
  <button class="tab-btn" onclick="switchTab('leads',this)">🌟 Leads</button>
  <button class="tab-btn" onclick="switchTab('contracts',this)">📅 Contracts</button>
</div>

<!-- STATS BAR (sales only) -->
<div id="stats-bar">
  <div class="stat-pill green"><span class="sp-val" id="s-total">0</span><span>Sales</span></div>
  <div class="stat-pill blue"><span class="sp-val" id="s-internet">0</span><span>Internet</span></div>
  <div class="stat-pill" style="border-color:#f472b640;background:#2d0a1a;"><span class="sp-val" style="color:#f472b6" id="s-tv">0</span><span>TV</span></div>
  <div class="stat-pill" style="border-color:#34d39940;background:#052e1a;"><span class="sp-val" style="color:#34d399" id="s-call">0</span><span>Call</span></div>
  <div class="stat-pill orange"><span class="sp-val" id="s-norton">0</span><span>Norton</span></div>
  <div class="stat-pill purple"><span class="sp-val" id="s-publicip">0</span><span>Public IP</span></div>
</div>

<!-- ══════════════ DASHBOARD PANEL ══════════════ -->
<div class="panel" id="panel-dash">
  <div class="dash-scroll">

    <!-- Month selector row -->
    <div class="dash-month-row">
      <button class="dash-month-btn" onclick="dashChangeMonth(-1)">‹</button>
      <span id="dash-month-label">March 2026</span>
      <button class="dash-month-btn" onclick="dashChangeMonth(1)">›</button>
    </div>

    <!-- Big total -->
    <div class="dash-hero">
      <div class="dash-hero-num" id="d-total">0</div>
      <div class="dash-hero-label">Total Sales</div>
      <div class="dash-hero-sub" id="d-attach-summary"></div>
    </div>

    <!-- Status grid -->
    <div class="dash-section-title">By Status</div>
    <div class="dash-grid dash-grid-4">
      <div class="dash-tile green"    onclick="filterByStatus('installed')">
        <div class="dt-icon">🟢</div>
        <div class="dt-val" id="d-installed">0</div>
        <div class="dt-label">Installed</div>
      </div>
      <div class="dash-tile yellow"   onclick="filterByStatus('pending')">
        <div class="dt-icon">⏳</div>
        <div class="dt-val" id="d-pending">0</div>
        <div class="dt-label">Pending</div>
      </div>
      <div class="dash-tile red"      onclick="filterByStatus('cancelled')">
        <div class="dt-icon">❌</div>
        <div class="dt-val" id="d-cancelled">0</div>
        <div class="dt-label">Cancelled</div>
      </div>
      <div class="dash-tile blue"     onclick="filterByStatus('reschedule')">
        <div class="dt-icon">🔄</div>
        <div class="dt-val" id="d-reschedule">0</div>
        <div class="dt-label">Reschedule</div>
      </div>
    </div>

    <!-- Add-ons breakdown -->
    <div class="dash-section-title">Add-ons Breakdown</div>
    <div class="dash-addons">
      <div class="addon-row"><span class="addon-label">📡 Internet</span><div class="addon-bar-wrap"><div class="addon-bar" id="bar-internet" style="background:#60a5fa"></div></div><span class="addon-val" id="d-internet">0</span></div>
      <div class="addon-row"><span class="addon-label">📺 TV</span><div class="addon-bar-wrap"><div class="addon-bar" id="bar-tv" style="background:#f472b6"></div></div><span class="addon-val" id="d-tv">0</span></div>
      <div class="addon-row"><span class="addon-label">📞 Call</span><div class="addon-bar-wrap"><div class="addon-bar" id="bar-call" style="background:#34d399"></div></div><span class="addon-val" id="d-call">0</span></div>
      <div class="addon-row"><span class="addon-label">🛡 Norton</span><div class="addon-bar-wrap"><div class="addon-bar" id="bar-norton" style="background:#fb923c"></div></div><span class="addon-val" id="d-norton">0</span></div>
      <div class="addon-row"><span class="addon-label">🌐 Public IP</span><div class="addon-bar-wrap"><div class="addon-bar" id="bar-publicip" style="background:#a78bfa"></div></div><span class="addon-val" id="d-publicip">0</span></div>
    </div>

    <!-- Attachment count -->
    <div class="dash-section-title">Attachments</div>
    <div class="dash-attach-card">
      <div class="attach-icon">📎</div>
      <div class="attach-main">
        <div class="attach-num" id="d-attachments">0</div>
        <div class="attach-label">Files attached across all sales</div>
      </div>
    </div>

    <!-- Monthly trend (last 6 months) -->
    <div class="dash-section-title">Monthly Trend</div>
    <div class="dash-trend" id="dash-trend"></div>

  </div>
</div>

<!-- ══════════════ SALES PANEL ══════════════ -->
<div class="panel active" id="panel-sales">
  <div class="search-wrap">
    <input class="search-inp" id="search" placeholder="🔍  Search address, customer number..." oninput="renderList()"/>
  </div>
  <div class="list-body" id="sale-list-wrap">
    <div id="sale-list"></div>
  </div>
</div>

<!-- ══════════════ FUTURE LEADS PANEL ══════════════ -->
<div class="panel" id="panel-leads">
  <div class="search-wrap">
    <input class="search-inp" id="lead-search" placeholder="🔍  Search name, address..." oninput="renderLeads()"/>
  </div>
  <div class="list-body">
    <div id="lead-list"></div>
  </div>
</div>

<!-- ══════════════ CONTRACTS PANEL ══════════════ -->
<div class="panel" id="panel-contracts">
  <div class="list-body" id="contract-list-wrap">
    <div id="contract-list"></div>
  </div>
</div>

<!-- BOTTOM BAR -->
<div id="bottom-bar">
  <button class="bottom-btn" id="btn-export" onclick="exportCSV()">📤 Export CSV</button>
  <button class="bottom-btn accent" id="btn-copy" onclick="copyMonthSummary()">📋 Copy Summary</button>
</div>

<!-- ══ SALE FORM MODAL ══ -->
<div id="form-modal" class="overlay" style="display:none" onclick="handleOverlayClick(event,'form-modal')">
  <div class="modal" onclick="event.stopPropagation()">
    <div class="modal-handle"></div>
    <div class="modal-title">
      <span id="modal-title-text">New Sale</span>
      <button class="modal-close" onclick="closeModal('form-modal')">✕</button>
    </div>
    <div class="field-label">Address *</div>
    <input class="field-input" id="f-address" placeholder="e.g. 14 Baker Street, London NW1"/>
    <div class="field-label">Internet Package</div>
    <input class="field-input" id="f-internet" placeholder="e.g. Fibre 500, Superfast 100"/>
    <div class="field-label">Add-ons</div>
    <div class="toggle-row">
      <button class="toggle-chip" id="chip-tv"       onclick="toggleChip('tv')">📺 TV</button>
      <button class="toggle-chip" id="chip-call"     onclick="toggleChip('call')">📞 Call</button>
      <button class="toggle-chip" id="chip-norton"   onclick="toggleChip('norton')">🛡 Norton</button>
      <button class="toggle-chip" id="chip-publicip" onclick="toggleChip('publicip')">🌐 Public IP</button>
    </div>
    <div class="field-label">Install Date</div>
    <input class="field-input" id="f-installdate" type="date"/>
    <div class="field-label">Time Slot</div>
    <div class="toggle-row">
      <button class="toggle-chip" id="chip-slot-am" onclick="selectSlot('8-1')">🌅 8am – 1pm</button>
      <button class="toggle-chip" id="chip-slot-pm" onclick="selectSlot('1-6')">🌆 1pm – 6pm</button>
    </div>
    <div class="field-label">Customer Number</div>
    <input class="field-input" id="f-custnumber" placeholder="e.g. C-84920"/>
    <div class="field-label">Status</div>
    <div class="toggle-row" id="status-row">
      <button class="toggle-chip" id="status-installed"   onclick="setStatus('installed')">🟢 Installed</button>
      <button class="toggle-chip" id="status-pending"     onclick="setStatus('pending')">⏳ Pending</button>
      <button class="toggle-chip" id="status-cancelled"   onclick="setStatus('cancelled')">❌ Cancelled</button>
      <button class="toggle-chip" id="status-reschedule"  onclick="setStatus('reschedule')">🔄 Reschedule</button>
    </div>
    <div class="field-label">Attachments</div>
    <div class="attach-upload-area" id="attach-area">
      <input type="file" id="f-attach" multiple accept="image/*,application/pdf,.doc,.docx,.xls,.xlsx" style="display:none" onchange="handleAttach(this)"/>
      <button class="attach-upload-btn" onclick="document.getElementById('f-attach').click()">📎 Add Files</button>
      <div id="attach-list"></div>
    </div>
    <div class="field-label">Notes</div>
    <input class="field-input" id="f-notes" placeholder="Any extra notes..."/>
    <button class="save-btn" onclick="saveSale()">✓ Save Sale</button>
    <button class="delete-btn" id="delete-btn" style="display:none" onclick="deleteSale()">🗑 Delete this record</button>
  </div>
</div>

<!-- ══ SALE VIEW MODAL ══ -->
<div id="view-modal" class="overlay view-modal" style="display:none" onclick="handleOverlayClick(event,'view-modal')">
  <div class="modal" onclick="event.stopPropagation()">
    <div class="modal-handle"></div>
    <div class="modal-title">
      <span id="view-title">Record</span>
      <div style="display:flex;gap:8px">
        <button class="modal-close" style="color:var(--accent);font-size:15px;font-weight:700" onclick="editFromView()">Edit</button>
        <button class="modal-close" onclick="closeModal('view-modal')">✕</button>
      </div>
    </div>
    <div id="view-body"></div>
  </div>
</div>

<!-- ══ LEAD FORM MODAL ══ -->
<div id="lead-form-modal" class="overlay" style="display:none" onclick="handleOverlayClick(event,'lead-form-modal')">
  <div class="modal" onclick="event.stopPropagation()">
    <div class="modal-handle"></div>
    <div class="modal-title">
      <span id="lead-modal-title">New Lead</span>
      <button class="modal-close" onclick="closeModal('lead-form-modal')">✕</button>
    </div>
    <div class="field-label">Full Name *</div>
    <input class="field-input" id="lf-name" placeholder="e.g. John Smith"/>
    <div class="field-label">Address *</div>
    <input class="field-input" id="lf-address" placeholder="e.g. 14 Baker Street, London NW1"/>
    <div class="field-label">Phone Number</div>
    <input class="field-input" id="lf-phone" placeholder="e.g. 07700 900123" type="tel"/>
    <div class="field-label">Current Provider</div>
    <input class="field-input" id="lf-provider" placeholder="e.g. BT, Sky, Virgin, TalkTalk"/>
    <div class="field-label">Come Back Date</div>
    <input class="field-input" id="lf-callback" type="date"/>
    <div class="field-label">Come Back Time</div>
    <input class="field-input" id="lf-calltime" type="time" placeholder="e.g. 14:00"/>
    <div class="field-label">Notes</div>
    <textarea class="field-input" id="lf-notes" placeholder="What did they say? Objections? Interested in what package?" rows="3" style="resize:none;line-height:1.5"></textarea>
    <button class="save-btn" onclick="saveLead()">✓ Save Lead</button>
    <button class="delete-btn" id="lead-delete-btn" style="display:none" onclick="deleteLead()">🗑 Delete this lead</button>
  </div>
</div>

<!-- ══ LEAD VIEW MODAL ══ -->
<div id="lead-view-modal" class="overlay" style="display:none" onclick="handleOverlayClick(event,'lead-view-modal')">
  <div class="modal" onclick="event.stopPropagation()">
    <div class="modal-handle"></div>
    <div class="modal-title">
      <span id="lead-view-title">Lead</span>
      <div style="display:flex;gap:8px">
        <button class="modal-close" style="color:var(--accent);font-size:15px;font-weight:700" onclick="editLead(null)">Edit</button>
        <button class="modal-close" onclick="closeModal('lead-view-modal')">✕</button>
      </div>
    </div>
    <div id="lead-view-body"></div>
  </div>
</div>

<!-- ══ CONTRACT FORM MODAL ══ -->
<div id="contract-form-modal" class="overlay" style="display:none" onclick="handleOverlayClick(event,'contract-form-modal')">
  <div class="modal" onclick="event.stopPropagation()">
    <div class="modal-handle"></div>
    <div class="modal-title">
      <span id="contract-modal-title">New Contract</span>
      <button class="modal-close" onclick="closeModal('contract-form-modal')">✕</button>
    </div>
    <div class="field-label">Full Name *</div>
    <input class="field-input" id="cf-name" placeholder="e.g. Sarah Jones"/>
    <div class="field-label">Address *</div>
    <input class="field-input" id="cf-address" placeholder="e.g. 22 Highbury Crescent, London N5"/>
    <div class="field-label">Phone Number</div>
    <input class="field-input" id="cf-phone" placeholder="e.g. 07700 900456" type="tel"/>
    <div class="field-label">Current Provider</div>
    <input class="field-input" id="cf-provider" placeholder="e.g. BT, Sky, Virgin, TalkTalk"/>
    <div class="field-label">Contract End Date *</div>
    <input class="field-input" id="cf-enddate" type="date"/>
    <div style="margin-top:10px;padding:10px 12px;background:rgba(167,139,250,0.08);border:1px solid rgba(167,139,250,0.2);border-radius:10px;font-size:12px;color:var(--muted2);line-height:1.5">
      📌 You'll be reminded to come back <strong style="color:var(--purple)">1 month before</strong> the contract ends.
    </div>
    <div class="field-label">Notes</div>
    <textarea class="field-input" id="cf-notes" placeholder="Any extra details, package they're on, interest level..." rows="3" style="resize:none;line-height:1.5"></textarea>
    <button class="save-btn" onclick="saveContract()">✓ Save Contract</button>
    <button class="delete-btn" id="contract-delete-btn" style="display:none" onclick="deleteContract()">🗑 Delete this record</button>
  </div>
</div>

<!-- ══ CONTRACT VIEW MODAL ══ -->
<div id="contract-view-modal" class="overlay" style="display:none" onclick="handleOverlayClick(event,'contract-view-modal')">
  <div class="modal" onclick="event.stopPropagation()">
    <div class="modal-handle"></div>
    <div class="modal-title">
      <span id="contract-view-title">Contract</span>
      <div style="display:flex;gap:8px">
        <button class="modal-close" style="color:var(--accent);font-size:15px;font-weight:700" onclick="editContract(null)">Edit</button>
        <button class="modal-close" onclick="closeModal('contract-view-modal')">✕</button>
      </div>
    </div>
    <div id="contract-view-body"></div>
  </div>
</div>

<!-- ══ REMINDER MODAL ══ -->
<div id="reminder-modal" class="overlay" style="display:none" onclick="handleOverlayClick(event,'reminder-modal')">
  <div class="modal" onclick="event.stopPropagation()" style="max-height:85vh;">
    <div class="modal-handle"></div>
    <div class="modal-title">
      <span>🔔 Reminders</span>
      <button class="modal-close" onclick="closeModal('reminder-modal')">✕</button>
    </div>
    <div id="reminder-body"></div>
  </div>
</div>

<!-- CREDIT FOOTER -->
<div id="credit-bar">
  <span class="credit-inner">
    <svg viewBox="0 0 52 16" width="52" height="16" xmlns="http://www.w3.org/2000/svg">
      <circle cx="8" cy="8" r="8" fill="white" opacity="0.9"/>
      <path d="M8 2 C5 2 2.5 4.3 2.5 8 C2.5 11.7 5 14 8 14 C9.8 14 11.4 13.2 12.4 11.9 L10.8 10.4 C10.1 11.2 9.1 11.7 8 11.7 C6.1 11.7 4.8 10.2 4.8 8 C4.8 5.8 6.1 4.3 8 4.3 C9.1 4.3 10.1 4.8 10.8 5.6 L12.4 4.1 C11.4 2.8 9.8 2 8 2 Z" fill="#2ecc71"/>
    </svg>
    Developed by <strong>Ala-Uddin Riyad</strong>
  </span>
</div>

<!-- TOAST -->
<div id="toast"></div>

<script>
// ══════════════════════════════════════════════════════
// STATE
// ══════════════════════════════════════════════════════
let sales = {};
let leads = [];
let contracts = [];
let currentYear  = new Date().getFullYear();
let currentMonth = new Date().getMonth();
let editingId    = null;
let editingLeadId    = null;
let editingContractId = null;
let chips = { tv: false, call: false, norton: false, publicip: false };
let currentSlot = null;
let currentTab  = 'sales';

const MONTHS = ['January','February','March','April','May','June','July','August','September','October','November','December'];
const MONTHS_SHORT = ['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec'];

// ══════════════════════════════════════════════════════
// STORAGE
// ══════════════════════════════════════════════════════
function save()          { try { localStorage.setItem('salespad_data',      JSON.stringify(sales));     } catch(e){} }
function saveLeads()     { try { localStorage.setItem('salespad_leads',     JSON.stringify(leads));     } catch(e){} }
function saveContracts() { try { localStorage.setItem('salespad_contracts', JSON.stringify(contracts)); } catch(e){} }
function load() {
  try { const d=localStorage.getItem('salespad_data');      if(d) sales     = JSON.parse(d); } catch(e){}
  try { const d=localStorage.getItem('salespad_leads');     if(d) leads     = JSON.parse(d); } catch(e){}
  try { const d=localStorage.getItem('salespad_contracts'); if(d) contracts = JSON.parse(d); } catch(e){}
}

// ══════════════════════════════════════════════════════
// TABS
// ══════════════════════════════════════════════════════
function switchTab(tab, btn) {
  currentTab = tab;
  document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
  document.querySelectorAll('.panel').forEach(p => p.classList.remove('active'));
  document.getElementById('panel-'+tab).classList.add('active');

  // stats bar only for sales
  document.getElementById('stats-bar').style.display = (tab==='sales') ? 'flex' : 'none';
  document.getElementById('month-nav').style.display = (tab==='sales') ? 'flex' : 'none';
  document.getElementById('bottom-bar').style.display = (tab==='sales') ? 'flex' : 'none';
  document.getElementById('add-btn').style.display = (tab==='dash') ? 'none' : 'flex';

  if (tab==='dash')      renderDashboard();
  if (tab==='sales')     renderList();
  if (tab==='leads')     renderLeads();
  if (tab==='contracts') renderContracts();
}

function handleAdd() {
  if (currentTab==='sales')     openAddModal();
  if (currentTab==='leads')     openLeadForm();
  if (currentTab==='contracts') openContractForm();
  if (currentTab==='dash')      { const b=document.querySelector('.tab-btn:nth-child(2)'); switchTab('sales',b); openAddModal(); }
}

// ══════════════════════════════════════════════════════
// MONTH NAV (Sales)
// ══════════════════════════════════════════════════════
function monthKey() { return `${currentYear}-${String(currentMonth+1).padStart(2,'0')}`; }
function changeMonth(dir) {
  currentMonth += dir;
  if (currentMonth > 11) { currentMonth = 0; currentYear++; }
  if (currentMonth < 0)  { currentMonth = 11; currentYear--; }
  document.getElementById('month-label').textContent = `${MONTHS[currentMonth]} ${currentYear}`;
  renderList(); renderStats();
}

// ══════════════════════════════════════════════════════
// SALES
// ══════════════════════════════════════════════════════
function renderList() {
  const q = document.getElementById('search').value.toLowerCase().trim();
  const list = (sales[monthKey()]||[]).filter(s => {
    if (!q) return true;
    return (s.address||'').toLowerCase().includes(q) ||
           (s.custnumber||'').toLowerCase().includes(q) ||
           (s.internet||'').toLowerCase().includes(q) ||
           (s.notes||'').toLowerCase().includes(q);
  }).slice().reverse();

  const el = document.getElementById('sale-list');
  if (!list.length) {
    el.innerHTML = `<div class="empty-state"><span class="empty-icon">📋</span><strong>No Sales Yet</strong><br><span style="font-size:13px;color:var(--muted)">Tap + to add your first sale<br>for ${MONTHS[currentMonth]} ${currentYear}</span></div>`;
    return;
  }
  el.innerHTML = list.map(s => {
    const tags = buildTags(s);
    return `<div class="sale-card" onclick="viewSale('${s.id}')">
      <div class="card-top">
        <div>
          <div class="card-addr">${s.address||'—'}</div>
          <div class="card-date">${s.installdate?'📅 '+fmtDate(s.installdate):''}${s.timeslot?' '+(s.timeslot==='8-1'?'🌅 8–1':'🌆 1–6'):''}${(s.installdate||s.timeslot)&&s.custnumber?' · ':''}${s.custnumber?'# '+s.custnumber:''}</div>
        </div>
        <div class="card-num">#${(sales[monthKey()]||[]).indexOf(s)+1}</div>
      </div>
      <div class="card-tags">${tags}<span class="status-chip status-${s.status||'pending'}">${statusLabel(s.status)}</span></div>
    </div>`;
  }).join('');
}

function buildTags(s) {
  let t = '';
  if (s.internet) t += `<span class="tag tag-internet">📡 ${s.internet}</span>`;
  if (s.tv)       t += `<span class="tag tag-tv">📺 TV</span>`;
  if (s.call)     t += `<span class="tag tag-call">📞 Call</span>`;
  if (s.norton)   t += `<span class="tag tag-norton">🛡 Norton</span>`;
  if (s.publicip) t += `<span class="tag tag-publicip">🌐 Public IP</span>`;
  if (s.timeslot) t += `<span class="tag" style="color:#fbbf24;border-color:#fbbf2440;background:#2a1f05">${s.timeslot==='8-1'?'🌅 8–1':'🌆 1–6'}</span>`;
  if (!t)         t += `<span class="tag tag-none">No add-ons</span>`;
  return t;
}

function renderStats() {
  const list = sales[monthKey()]||[];
  document.getElementById('s-total').textContent   = list.length;
  document.getElementById('s-internet').textContent= list.filter(s=>s.internet).length;
  document.getElementById('s-tv').textContent      = list.filter(s=>s.tv).length;
  document.getElementById('s-call').textContent    = list.filter(s=>s.call).length;
  document.getElementById('s-norton').textContent  = list.filter(s=>s.norton).length;
  document.getElementById('s-publicip').textContent= list.filter(s=>s.publicip).length;
}

function openAddModal() {
  editingId = null; chips = { tv:false,call:false,norton:false,publicip:false };
  document.getElementById('modal-title-text').textContent = 'New Sale';
  document.getElementById('f-address').value     = '';
  document.getElementById('f-internet').value    = '';
  document.getElementById('f-installdate').value = new Date().toISOString().split('T')[0];
  document.getElementById('f-custnumber').value  = '';
  document.getElementById('f-notes').value       = '';
  document.getElementById('delete-btn').style.display = 'none';
  currentSlot = null; updateSlotChips(); updateChips();
  currentStatus = 'pending'; updateStatusChips();
  currentAttachments = []; renderAttachList();
  document.getElementById('form-modal').style.display = 'flex';
  setTimeout(()=>document.getElementById('f-address').focus(),300);
}

function openEditModal(id) {
  const s = findSale(id); if (!s) return;
  editingId = id; chips = { tv:!!s.tv,call:!!s.call,norton:!!s.norton,publicip:!!s.publicip };
  document.getElementById('modal-title-text').textContent = 'Edit Sale';
  document.getElementById('f-address').value     = s.address||'';
  document.getElementById('f-internet').value    = s.internet||'';
  document.getElementById('f-installdate').value = s.installdate||'';
  currentSlot = s.timeslot||null; updateSlotChips();
  document.getElementById('f-custnumber').value  = s.custnumber||'';
  document.getElementById('f-notes').value       = s.notes||'';
  document.getElementById('delete-btn').style.display = 'block';
  updateChips(); closeModal('view-modal');
  currentStatus = s.status||'pending'; updateStatusChips();
  currentAttachments = (s.attachments||[]).slice(); renderAttachList();
  document.getElementById('form-modal').style.display = 'flex';
}

function selectSlot(slot) { currentSlot = currentSlot===slot?null:slot; updateSlotChips(); }
function updateSlotChips() {
  const am=document.getElementById('chip-slot-am'), pm=document.getElementById('chip-slot-pm');
  if(!am||!pm) return;
  am.classList.toggle('on',currentSlot==='8-1'); am.classList.toggle('slot-am',currentSlot==='8-1');
  pm.classList.toggle('on',currentSlot==='1-6'); pm.classList.toggle('slot-pm',currentSlot==='1-6');
}
function toggleChip(key) { chips[key]=!chips[key]; updateChips(); }
function updateChips() {
  Object.keys(chips).forEach(k=>{
    const el=document.getElementById('chip-'+k);
    el.classList.toggle('on',chips[k]);
    if(chips[k]) el.classList.add(k); else el.classList.remove(k);
  });
}

function saveSale() {
  const address = document.getElementById('f-address').value.trim();
  if (!address) { showToast('Address is required!','err'); return; }
  const key = monthKey(); if (!sales[key]) sales[key]=[];
  const data = {
    address, internet:document.getElementById('f-internet').value.trim(),
    tv:chips.tv, call:chips.call, norton:chips.norton, publicip:chips.publicip,
    installdate:document.getElementById('f-installdate').value,
    timeslot:currentSlot, custnumber:document.getElementById('f-custnumber').value.trim(),
    notes:document.getElementById('f-notes').value.trim(),
    status: currentStatus,
    attachments: currentAttachments.slice(),
  };
  if (editingId) {
    const idx=sales[key].findIndex(s=>s.id===editingId);
    if(idx!==-1) sales[key][idx]={...sales[key][idx],...data};
  } else { data.id=Date.now().toString(); data.createdAt=new Date().toISOString(); sales[key].push(data); }
  save(); closeModal('form-modal'); renderList(); renderStats(); renderDashboard();
  showToast(editingId?'✓ Updated!':'✓ Sale saved!');
}

function deleteSale() {
  if (!editingId) return; if (!confirm('Delete this record?')) return;
  const key=monthKey(); sales[key]=(sales[key]||[]).filter(s=>s.id!==editingId);
  save(); closeModal('form-modal'); renderList(); renderStats(); renderDashboard(); showToast('Deleted');
}

function viewSale(id) {
  const s=findSale(id); if (!s) return;
  const num=(sales[monthKey()]||[]).indexOf(s)+1;
  document.getElementById('view-title').textContent=`Sale #${num}`;
  const fields=[
    {label:'📍 Address',val:s.address||'—',cls:'accent'},
    {label:'📡 Internet',val:s.internet||'—',cls:''},
    {label:'📺 TV',val:s.tv?'Yes':'No',cls:s.tv?'yes':'no'},
    {label:'📞 Call',val:s.call?'Yes':'No',cls:s.call?'yes':'no'},
    {label:'🛡 Norton',val:s.norton?'Yes':'No',cls:s.norton?'yes':'no'},
    {label:'🌐 Public IP',val:s.publicip?'Yes':'No',cls:s.publicip?'yes':'no'},
    {label:'📅 Install Date',val:s.installdate?fmtDate(s.installdate):'—',cls:''},
    {label:'⏰ Time Slot',val:s.timeslot==='8-1'?'🌅 8am–1pm':s.timeslot==='1-6'?'🌆 1pm–6pm':'—',cls:s.timeslot?'yes':''},
    {label:'# Customer No.',val:s.custnumber||'—',cls:'accent'},
    {label:'📝 Notes',val:s.notes||'—',cls:''},
  ];
  document.getElementById('view-body').innerHTML=
    fields.map(f=>`<div class="record-field"><span class="rf-label">${f.label}</span><span class="rf-val ${f.cls}">${f.val}</span></div>`).join('')+
    `<button class="save-btn" style="margin-top:18px" onclick="editFromView('${id}')">✏ Edit Record</button>`;
  document.getElementById('view-modal').style.display='flex';
  document.getElementById('view-modal').dataset.saleId=id;
}

function editFromView(id) { openEditModal(id||document.getElementById('view-modal').dataset.saleId); }
function findSale(id) { return (sales[monthKey()]||[]).find(s=>s.id===id); }

function exportCSV() {
  const list=sales[monthKey()]||[]; if(!list.length){showToast('No data to export','err');return;}
  const headers=['#','Address','Internet Package','TV','Call','Norton','Public IP','Install Date','Time Slot','Customer Number','Notes'];
  const rows=list.map((s,i)=>[i+1,`"${(s.address||'').replace(/"/g,'""')}"`,`"${(s.internet||'').replace(/"/g,'""')}"`,s.tv?'Yes':'No',s.call?'Yes':'No',s.norton?'Yes':'No',s.publicip?'Yes':'No',s.installdate||'',s.timeslot==='8-1'?'8am-1pm':s.timeslot==='1-6'?'1pm-6pm':'',`"${(s.custnumber||'').replace(/"/g,'""')}"`,`"${(s.notes||'').replace(/"/g,'""')}"`]);
  const csv=[headers,...rows].map(r=>r.join(',')).join('\n');
  const blob=new Blob([csv],{type:'text/csv'}); const url=URL.createObjectURL(blob);
  const a=document.createElement('a'); a.href=url; a.download=`salespad-${monthKey()}.csv`; a.click();
  showToast('📤 CSV exported!');
}

function copyMonthSummary() {
  const list=sales[monthKey()]||[]; if(!list.length){showToast('No sales this month','err');return;}
  let text=`📊 ${MONTHS[currentMonth]} ${currentYear} — Sales Summary\n${'─'.repeat(35)}\nTotal Sales: ${list.length}\nInternet: ${list.filter(s=>s.internet).length} | TV: ${list.filter(s=>s.tv).length} | Call: ${list.filter(s=>s.call).length}\nNorton: ${list.filter(s=>s.norton).length} | Public IP: ${list.filter(s=>s.publicip).length}\n${'─'.repeat(35)}\n\n`;
  list.forEach((s,i)=>{
    text+=`${i+1}. ${s.address}\n`;
    if(s.internet) text+=`   📡 ${s.internet}\n`;
    const addons=[s.tv&&'TV',s.call&&'Call',s.norton&&'Norton',s.publicip&&'Public IP'].filter(Boolean);
    if(addons.length) text+=`   ✓ ${addons.join(', ')}\n`;
    if(s.installdate) text+=`   📅 ${fmtDate(s.installdate)}${s.timeslot==='8-1'?' · 🌅 8am–1pm':s.timeslot==='1-6'?' · 🌆 1pm–6pm':''}\n`;
    if(s.custnumber) text+=`   # ${s.custnumber}\n`;
    text+='\n';
  });
  navigator.clipboard?.writeText(text).then(()=>showToast('📋 Copied to clipboard!')).catch(()=>showToast('Copy failed','err'));
}

// ══════════════════════════════════════════════════════
// FUTURE LEADS
// ══════════════════════════════════════════════════════
function openLeadForm(id) {
  editingLeadId = id||null;
  const l = id ? leads.find(x=>x.id===id) : null;
  document.getElementById('lead-modal-title').textContent = l ? 'Edit Lead' : 'New Lead';
  document.getElementById('lf-name').value     = l?.name||'';
  document.getElementById('lf-address').value  = l?.address||'';
  document.getElementById('lf-phone').value    = l?.phone||'';
  document.getElementById('lf-provider').value = l?.provider||'';
  document.getElementById('lf-callback').value = l?.callback||'';
  document.getElementById('lf-calltime').value = l?.calltime||'';
  document.getElementById('lf-notes').value    = l?.notes||'';
  document.getElementById('lead-delete-btn').style.display = l ? 'block' : 'none';
  document.getElementById('lead-form-modal').style.display = 'flex';
  setTimeout(()=>document.getElementById('lf-name').focus(),300);
}

function saveLead() {
  const name    = document.getElementById('lf-name').value.trim();
  const address = document.getElementById('lf-address').value.trim();
  if (!name && !address) { showToast('Name or address required!','err'); return; }
  const data = {
    name, address,
    phone:    document.getElementById('lf-phone').value.trim(),
    provider: document.getElementById('lf-provider').value.trim(),
    callback: document.getElementById('lf-callback').value,
    calltime: document.getElementById('lf-calltime').value,
    notes:    document.getElementById('lf-notes').value.trim(),
  };
  if (editingLeadId) {
    const idx=leads.findIndex(x=>x.id===editingLeadId);
    if(idx!==-1) leads[idx]={...leads[idx],...data};
  } else { data.id=Date.now().toString(); data.createdAt=new Date().toISOString(); leads.push(data); }
  saveLeads(); closeModal('lead-form-modal'); closeModal('lead-view-modal'); renderLeads(); updateBell();
  showToast(editingLeadId?'✓ Lead updated!':'✓ Lead saved!');
}

function deleteLead() {
  if (!editingLeadId) return; if (!confirm('Delete this lead?')) return;
  leads = leads.filter(x=>x.id!==editingLeadId);
  saveLeads(); closeModal('lead-form-modal'); renderLeads(); updateBell(); showToast('Lead deleted');
}

function viewLead(id) {
  const l=leads.find(x=>x.id===id); if(!l) return;
  document.getElementById('lead-view-title').textContent = l.name||'Lead';
  const callbackDays = l.callback ? daysUntil(l.callback) : null;
  let callbackStr = '—', callbackCls = '';
  if (l.callback) {
    const d = callbackDays;
    if (d < 0)      { callbackStr = `${fmtDate(l.callback)} (${Math.abs(d)}d overdue)`; callbackCls = 'danger'; }
    else if (d===0) { callbackStr = `Today ${l.calltime||''}`.trim(); callbackCls = 'warn'; }
    else if (d===1) { callbackStr = `Tomorrow ${l.calltime||''}`.trim(); callbackCls = 'warn'; }
    else            { callbackStr = `${fmtDate(l.callback)}${l.calltime?' at '+l.calltime:''}`; callbackCls = 'yes'; }
  }
  const fields=[
    {label:'👤 Name',    val:l.name||'—',     cls:'accent'},
    {label:'📍 Address', val:l.address||'—',  cls:''},
    {label:'📞 Phone',   val:l.phone||'—',    cls:l.phone?'accent':''},
    {label:'📡 Provider',val:l.provider||'—', cls:l.provider?'yes':''},
    {label:'🔔 Come Back',val:callbackStr,    cls:callbackCls},
    {label:'📝 Notes',   val:l.notes||'—',    cls:''},
  ];
  document.getElementById('lead-view-body').innerHTML=
    fields.map(f=>`<div class="record-field"><span class="rf-label">${f.label}</span><span class="rf-val ${f.cls}">${f.val}</span></div>`).join('')+
    `<button class="save-btn" style="margin-top:18px" onclick="editLead('${id}')">✏ Edit Lead</button>`;
  document.getElementById('lead-view-modal').style.display='flex';
  document.getElementById('lead-view-modal').dataset.leadId=id;
}

function editLead(id) {
  const lid=id||document.getElementById('lead-view-modal').dataset.leadId;
  closeModal('lead-view-modal');
  openLeadForm(lid);
}

function renderLeads() {
  const q=(document.getElementById('lead-search').value||'').toLowerCase().trim();
  let list=leads.filter(l=>{
    if(!q) return true;
    return (l.name||'').toLowerCase().includes(q)||(l.address||'').toLowerCase().includes(q)||(l.phone||'').toLowerCase().includes(q)||(l.provider||'').toLowerCase().includes(q);
  });
  // sort: overdue first, then by callback date, then no date
  list.sort((a,b)=>{
    const da=a.callback?new Date(a.callback):new Date('9999-12-31');
    const db=b.callback?new Date(b.callback):new Date('9999-12-31');
    return da-db;
  });

  const el=document.getElementById('lead-list');
  if(!list.length){
    el.innerHTML=`<div class="empty-state"><span class="empty-icon">🌟</span><strong>No Leads Yet</strong><br><span style="font-size:13px;color:var(--muted)">Tap + to add a future lead<br>with appointment reminder</span></div>`;
    return;
  }
  el.innerHTML=list.map(l=>{
    const days = l.callback ? daysUntil(l.callback) : null;
    let reminderHtml='';
    if (days!==null) {
      if      (days<0)   reminderHtml=`<span class="reminder-badge overdue">⚠ ${Math.abs(days)}d overdue</span>`;
      else if (days===0) reminderHtml=`<span class="reminder-badge">🔔 Today${l.calltime?' at '+l.calltime:''}</span>`;
      else if (days===1) reminderHtml=`<span class="reminder-badge">🔔 Tomorrow${l.calltime?' at '+l.calltime:''}</span>`;
      else               reminderHtml=`<span class="reminder-badge">🔔 ${fmtDate(l.callback)}${l.calltime?' '+l.calltime:''}</span>`;
    }
    return `<div class="sale-card lead-card" onclick="viewLead('${l.id}')">
      <div class="card-top">
        <div>
          <div class="card-addr">${l.name||l.address||'—'}</div>
          <div class="card-name">${l.name&&l.address?'📍 '+l.address:l.name?'':''}${l.phone?' · 📞 '+l.phone:''}</div>
        </div>
        ${reminderHtml}
      </div>
      <div class="card-tags">
        ${l.provider?`<span class="tag tag-provider">📡 ${l.provider}</span>`:''}
        ${!l.provider?`<span class="tag tag-none">No provider noted</span>`:''}
      </div>
    </div>`;
  }).join('');
}

// ══════════════════════════════════════════════════════
// CONTRACTS TRACKER
// ══════════════════════════════════════════════════════
function openContractForm(id, prefillYear, prefillMonth) {
  editingContractId=id||null;
  const c=id?contracts.find(x=>x.id===id):null;
  document.getElementById('contract-modal-title').textContent=c?'Edit Contract':'New Contract';
  document.getElementById('cf-name').value    =c?.name||'';
  document.getElementById('cf-address').value =c?.address||'';
  document.getElementById('cf-phone').value   =c?.phone||'';
  document.getElementById('cf-provider').value=c?.provider||'';
  document.getElementById('cf-notes').value   =c?.notes||'';
  // prefill end date to last day of the given month if adding from month button
  if (c?.enddate) {
    document.getElementById('cf-enddate').value=c.enddate;
  } else if (prefillYear && prefillMonth!==undefined) {
    const lastDay=new Date(prefillYear,prefillMonth+1,0);
    document.getElementById('cf-enddate').value=lastDay.toISOString().split('T')[0];
  } else {
    document.getElementById('cf-enddate').value='';
  }
  document.getElementById('contract-delete-btn').style.display=c?'block':'none';
  document.getElementById('contract-form-modal').style.display='flex';
  setTimeout(()=>document.getElementById('cf-name').focus(),300);
}

function saveContract() {
  const name=document.getElementById('cf-name').value.trim();
  const address=document.getElementById('cf-address').value.trim();
  const enddate=document.getElementById('cf-enddate').value;
  if ((!name&&!address)||!enddate){showToast('Name/address and end date required!','err');return;}
  const data={
    name,address,enddate,
    phone:document.getElementById('cf-phone').value.trim(),
    provider:document.getElementById('cf-provider').value.trim(),
    notes:document.getElementById('cf-notes').value.trim(),
  };
  if(editingContractId){
    const idx=contracts.findIndex(x=>x.id===editingContractId);
    if(idx!==-1) contracts[idx]={...contracts[idx],...data};
  } else {data.id=Date.now().toString();data.createdAt=new Date().toISOString();contracts.push(data);}
  saveContracts();closeModal('contract-form-modal');closeModal('contract-view-modal');renderContracts();updateBell();
  showToast(editingContractId?'✓ Contract updated!':'✓ Contract saved!');
}

function deleteContract(){
  if(!editingContractId)return;if(!confirm('Delete this contract record?'))return;
  contracts=contracts.filter(x=>x.id!==editingContractId);
  saveContracts();closeModal('contract-form-modal');renderContracts();updateBell();showToast('Deleted');
}

function viewContract(id){
  const c=contracts.find(x=>x.id===id);if(!c)return;
  document.getElementById('contract-view-title').textContent=c.name||'Contract';
  const daysLeft=c.enddate?daysUntil(c.enddate):null;
  const visitDate=c.enddate?callbackDate(c.enddate):null;
  let endCls='', visitCls='yes';
  if(daysLeft!==null){
    if(daysLeft<0)      endCls='danger';
    else if(daysLeft<30) endCls='danger';
    else if(daysLeft<60) endCls='warn';
    else                 endCls='yes';
  }
  const fields=[
    {label:'👤 Name',          val:c.name||'—',    cls:'accent'},
    {label:'📍 Address',       val:c.address||'—', cls:''},
    {label:'📞 Phone',         val:c.phone||'—',   cls:c.phone?'accent':''},
    {label:'📡 Provider',      val:c.provider||'—',cls:c.provider?'yes':''},
    {label:'📅 Contract Ends', val:c.enddate?fmtDate(c.enddate)+(daysLeft>=0?` (${daysLeft}d left)`:` (${Math.abs(daysLeft)}d ago)`):'—', cls:endCls},
    {label:'🔔 Visit By',      val:visitDate?fmtDate(visitDate)+' (1 month before)':'—', cls:visitCls},
    {label:'📝 Notes',         val:c.notes||'—',   cls:''},
  ];
  document.getElementById('contract-view-body').innerHTML=
    fields.map(f=>`<div class="record-field"><span class="rf-label">${f.label}</span><span class="rf-val ${f.cls}">${f.val}</span></div>`).join('')+
    `<button class="save-btn" style="margin-top:18px" onclick="editContract('${id}')">✏ Edit Record</button>`;
  document.getElementById('contract-view-modal').style.display='flex';
  document.getElementById('contract-view-modal').dataset.cid=id;
}

function editContract(id){
  const cid=id||document.getElementById('contract-view-modal').dataset.cid;
  closeModal('contract-view-modal');
  openContractForm(cid);
}

function renderContracts(){
  const el=document.getElementById('contract-list');
  // Build year/month grid for 2026 and 2027
  const years=[2026,2027];
  let html='';
  years.forEach(yr=>{
    html+=`<div class="year-section"><div class="year-label">${yr} <span id="yr-count-${yr}"></span></div><div class="month-row">`;
    for(let m=0;m<12;m++){
      const monthContracts=contracts.filter(c=>{
        if(!c.enddate) return false;
        const d=new Date(c.enddate);
        return d.getFullYear()===yr && d.getMonth()===m;
      });
      const count=monthContracts.length;
      const isCurrentMonth=(yr===new Date().getFullYear()&&m===new Date().getMonth());
      html+=`<div class="month-block ${isCurrentMonth?'open':''}" id="mb-${yr}-${m}">
        <div class="month-header" onclick="toggleMonth('mb-${yr}-${m}')">
          <div class="month-name">${MONTHS[m]} <span class="month-count ${count===0?'zero':''}">${count}</span></div>
          <span class="month-chevron">›</span>
        </div>
        <div class="month-contracts">
          ${monthContracts.map(c=>contractRow(c)).join('')}
          <button class="add-contract-btn" onclick="openContractForm(null,${yr},${m})">＋ Add contract ending ${MONTHS_SHORT[m]} ${yr}</button>
        </div>
      </div>`;
    }
    html+='</div></div>';
  });
  el.innerHTML=html;
  // update year counts
  years.forEach(yr=>{
    const n=contracts.filter(c=>{if(!c.enddate)return false;const d=new Date(c.enddate);return d.getFullYear()===yr;}).length;
    const el2=document.getElementById('yr-count-'+yr);
    if(el2) el2.textContent=n?`${n} contract${n===1?'':'s'}`:'';
  });
}

function contractRow(c){
  const daysLeft=daysUntil(c.enddate);
  const visitDate=callbackDate(c.enddate);
  const visitDays=daysUntil(visitDate);
  let urgency='';
  if(visitDays<=0&&daysLeft>0)  urgency='urgent';// should visit now
  else if(visitDays<=7)          urgency='soon';
  return `<div class="contract-row ${urgency}" onclick="viewContract('${c.id}')">
    <div class="cr-main">
      <div class="cr-name">${c.name||'Unknown'}</div>
      <div class="cr-addr">${c.address||'—'}${c.provider?' · '+c.provider:''}</div>
      <div class="cr-tags">
        ${urgency==='urgent'?`<span class="countdown-badge urgent">⚠ Visit now</span>`:urgency==='soon'?`<span class="countdown-badge soon">🔔 Visit in ${visitDays}d</span>`:`<span class="countdown-badge ok">📅 Visit ${fmtDate(visitDate)}</span>`}
        ${daysLeft>=0?`<span class="tag tag-contract">${daysLeft}d left</span>`:`<span class="tag tag-urgent">Expired</span>`}
      </div>
    </div>
  </div>`;
}

function toggleMonth(id){
  document.getElementById(id).classList.toggle('open');
}

// ══════════════════════════════════════════════════════
// UTILS
// ══════════════════════════════════════════════════════
function daysUntil(dateStr){
  if(!dateStr) return null;
  const today=new Date(); today.setHours(0,0,0,0);
  const target=new Date(dateStr); target.setHours(0,0,0,0);
  return Math.round((target-today)/(1000*60*60*24));
}
function callbackDate(endDateStr){
  // 1 month before contract end
  const d=new Date(endDateStr);
  d.setMonth(d.getMonth()-1);
  return d.toISOString().split('T')[0];
}
function fmtDate(d){
  if(!d) return '';
  const [y,m,day]=d.split('-');
  return `${day}/${m}/${y}`;
}
function closeModal(id){ document.getElementById(id).style.display='none'; }
function handleOverlayClick(e,id){ if(e.target.classList.contains('overlay')) closeModal(id); }
function showToast(msg,type='ok'){
  const t=document.getElementById('toast');
  t.textContent=msg;
  t.style.background=type==='err'?'#2d0a0a':'#052e2a';
  t.style.borderColor=type==='err'?'var(--red)':'var(--accent)';
  t.style.color=type==='err'?'var(--red)':'var(--accent)';
  t.style.display='block';
  clearTimeout(t._t); t._t=setTimeout(()=>t.style.display='none',2500);
}

// ══════════════════════════════════════════════════════
// STATUS + ATTACHMENTS
// ══════════════════════════════════════════════════════
let currentStatus = 'pending';
let currentAttachments = []; // [{name, dataUrl}]

function setStatus(s) { currentStatus = s; updateStatusChips(); }
function updateStatusChips() {
  ['installed','pending','cancelled','reschedule'].forEach(s => {
    const el = document.getElementById('status-'+s);
    if (!el) return;
    el.classList.toggle('on', currentStatus === s);
  });
}
function statusLabel(s) {
  return {installed:'🟢 Installed',pending:'⏳ Pending',cancelled:'❌ Cancelled',reschedule:'🔄 Reschedule'}[s||'pending']||'⏳ Pending';
}
function statusCls(s) {
  return {installed:'yes',pending:'warn',cancelled:'danger',reschedule:'accent'}[s||'pending']||'';
}

function handleAttach(input) {
  const files = Array.from(input.files);
  files.forEach(file => {
    if (currentAttachments.length >= 10) { showToast('Max 10 files','err'); return; }
    const reader = new FileReader();
    reader.onload = e => {
      currentAttachments.push({ name: file.name, dataUrl: e.target.result, size: file.size });
      renderAttachList();
    };
    reader.readAsDataURL(file);
  });
  input.value = '';
}

function renderAttachList() {
  const el = document.getElementById('attach-list');
  if (!el) return;
  el.innerHTML = currentAttachments.map((a,i) => `
    <div class="attach-item" onclick="removeAttach(${i})">
      <span>${a.name}</span>
      <span class="attach-remove">✕</span>
    </div>`).join('');
}
function removeAttach(i) { currentAttachments.splice(i,1); renderAttachList(); }

// ── DASHBOARD ──────────────────────────────────────────────
let dashMonth = new Date().getMonth();
let dashYear  = new Date().getFullYear();

function dashChangeMonth(dir) {
  dashMonth += dir;
  if (dashMonth > 11) { dashMonth = 0; dashYear++; }
  if (dashMonth < 0)  { dashMonth = 11; dashYear--; }
  document.getElementById('dash-month-label').textContent = MONTHS[dashMonth].toUpperCase() + ' ' + dashYear;
  renderDashboard();
}

function renderDashboard() {
  const key = `${dashYear}-${String(dashMonth+1).padStart(2,'0')}`;
  const list = sales[key]||[];
  const total = list.length;

  // hero
  document.getElementById('d-total').textContent = total;

  // statuses
  const byStatus = s => list.filter(x=>(x.status||'pending')===s).length;
  document.getElementById('d-installed').textContent   = byStatus('installed');
  document.getElementById('d-pending').textContent     = byStatus('pending');
  document.getElementById('d-cancelled').textContent   = byStatus('cancelled');
  document.getElementById('d-reschedule').textContent  = byStatus('reschedule');

  // addons
  const internet = list.filter(s=>s.internet).length;
  const tv       = list.filter(s=>s.tv).length;
  const call     = list.filter(s=>s.call).length;
  const norton   = list.filter(s=>s.norton).length;
  const publicip = list.filter(s=>s.publicip).length;
  const maxAddon = Math.max(internet,tv,call,norton,publicip,1);
  document.getElementById('d-internet').textContent = internet;
  document.getElementById('d-tv').textContent       = tv;
  document.getElementById('d-call').textContent     = call;
  document.getElementById('d-norton').textContent   = norton;
  document.getElementById('d-publicip').textContent = publicip;
  [['internet',internet],['tv',tv],['call',call],['norton',norton],['publicip',publicip]].forEach(([k,v])=>{
    const bar = document.getElementById('bar-'+k);
    if (bar) setTimeout(()=>bar.style.width=(v/maxAddon*100)+'%',50);
  });

  // attachments
  const totalAttach = list.reduce((n,s)=>n+(s.attachments?s.attachments.length:0),0);
  document.getElementById('d-attachments').textContent = totalAttach;
  document.getElementById('d-attach-summary').textContent = totalAttach
    ? `${totalAttach} file${totalAttach!==1?'s':''} attached to ${list.filter(s=>s.attachments&&s.attachments.length).length} sale${list.filter(s=>s.attachments&&s.attachments.length).length!==1?'s':''}`
    : 'No files attached yet';

  // trend (last 6 months ending at dashMonth)
  const trendData = [];
  for (let i=5;i>=0;i--) {
    let m=dashMonth-i, y=dashYear;
    if(m<0){m+=12;y--;}
    const k=`${y}-${String(m+1).padStart(2,'0')}`;
    trendData.push({ label:MONTHS[m].slice(0,3), count:(sales[k]||[]).length, current:(i===0) });
  }
  const maxTrend = Math.max(...trendData.map(t=>t.count),1);
  const trendEl = document.getElementById('dash-trend');
  if (trendEl) {
    trendEl.innerHTML = trendData.map(t=>`
      <div class="trend-bar-wrap ${t.current?'current':''}">
        <div class="trend-val">${t.count}</div>
        <div class="trend-bar-bg">
          <div class="trend-bar-fill ${t.current?'current':''}" style="height:${Math.max(t.count/maxTrend*100,4)}%"></div>
        </div>
        <div class="trend-label">${t.label}</div>
      </div>`).join('');
  }
}

function filterByStatus(status) {
  // switch to sales tab and filter
  const salesBtn = document.querySelector('.tab-btn:nth-child(2)');
  switchTab('sales', salesBtn);
  // highlight — future enhancement placeholder
  showToast('Showing ' + statusLabel(status));
}


// ══════════════════════════════════════════════════════
// REMINDERS
// ══════════════════════════════════════════════════════
function getReminders() {
  const today = new Date(); today.setHours(0,0,0,0);
  const items = [];

  // ── LEADS: callback date reminders ──
  leads.forEach(l => {
    if (!l.callback) return;
    const d = new Date(l.callback); d.setHours(0,0,0,0);
    const diff = Math.round((d - today) / 86400000);
    if (diff > 7) return; // only show within 7 days or overdue
    let urgency = diff < 0 ? 'overdue' : diff === 0 ? 'today' : diff <= 2 ? 'soon' : 'upcoming';
    let when = diff < 0 ? `${Math.abs(diff)}d overdue` : diff === 0 ? 'Today' : diff === 1 ? 'Tomorrow' : `In ${diff} days`;
    items.push({
      type: 'lead',
      id: l.id,
      urgency,
      diff,
      name: l.name || l.address || 'Lead',
      detail: `📍 ${l.address||'—'}${l.phone?' · 📞 '+l.phone:''}${l.calltime?' · ⏰ '+l.calltime:''}`,
      when,
      dateStr: fmtDate(l.callback),
    });
  });

  // ── CONTRACTS: visit 1 month before end ──
  contracts.forEach(c => {
    if (!c.enddate) return;
    const visitStr = callbackDate(c.enddate);
    const vd = new Date(visitStr); vd.setHours(0,0,0,0);
    const diff = Math.round((vd - today) / 86400000);
    if (diff > 14) return; // only show within 14 days or overdue
    // also don't show if contract already expired
    const ed = new Date(c.enddate); ed.setHours(0,0,0,0);
    if (ed < today) return;
    let urgency = diff < 0 ? 'overdue' : diff === 0 ? 'today' : diff <= 3 ? 'soon' : 'upcoming';
    let when = diff < 0 ? `Visit was ${Math.abs(diff)}d ago` : diff === 0 ? 'Visit today' : diff === 1 ? 'Visit tomorrow' : `Visit in ${diff} days`;
    items.push({
      type: 'contract',
      id: c.id,
      urgency,
      diff,
      name: c.name || c.address || 'Contract',
      detail: `📍 ${c.address||'—'}${c.provider?' · 📡 '+c.provider:''} · Contract ends ${fmtDate(c.enddate)}`,
      when,
      dateStr: fmtDate(visitStr),
    });
  });

  // sort: overdue first, then by diff
  items.sort((a,b) => a.diff - b.diff);
  return items;
}

function updateBell() {
  const items = getReminders();
  const badge = document.getElementById('bell-badge');
  const btn   = document.getElementById('bell-btn');
  if (!badge) return;
  const urgent = items.filter(i => i.urgency === 'overdue' || i.urgency === 'today').length;
  if (items.length > 0) {
    badge.style.display = 'flex';
    badge.textContent = items.length;
    badge.style.background = urgent > 0 ? 'var(--red)' : 'var(--orange)';
    btn.style.borderColor = urgent > 0 ? 'rgba(255,78,106,0.5)' : 'rgba(251,146,60,0.4)';
    btn.innerHTML = `🔔<span id="bell-badge" style="display:flex;position:absolute;top:-4px;right:-4px;background:${urgent>0?'var(--red)':'var(--orange)'};color:#fff;font-size:9px;font-weight:700;min-width:16px;height:16px;border-radius:8px;align-items:center;justify-content:center;padding:0 3px;font-family:inherit;border:2px solid var(--bg);">${items.length}</span>`;
  } else {
    btn.innerHTML = '🔔';
    btn.style.borderColor = '';
  }
}

function openReminders() {
  const items = getReminders();
  const body = document.getElementById('reminder-body');

  if (!items.length) {
    body.innerHTML = `<div class="reminder-empty">✅<br><strong style="color:var(--text)">All clear!</strong><br>No upcoming reminders<br>for leads or contracts.</div>`;
    document.getElementById('reminder-modal').style.display = 'flex';
    return;
  }

  const leadItems     = items.filter(i => i.type === 'lead');
  const contractItems = items.filter(i => i.type === 'contract');

  let html = '';

  if (leadItems.length) {
    html += `<div class="reminder-section-title">🌟 Lead Callbacks (${leadItems.length})</div>`;
    html += leadItems.map(i => `
      <div class="reminder-item" onclick="goToLead('${i.id}')">
        <div class="ri-dot ${i.urgency}"></div>
        <div class="ri-body">
          <div class="ri-name">${i.name}</div>
          <div class="ri-detail">${i.detail}</div>
        </div>
        <span class="ri-badge ${i.urgency}">${i.when}</span>
      </div>`).join('');
  }

  if (contractItems.length) {
    html += `<div class="reminder-section-title" style="margin-top:${leadItems.length?'8px':'0'}">📅 Contract Visit Due (${contractItems.length})</div>`;
    html += contractItems.map(i => `
      <div class="reminder-item" onclick="goToContract('${i.id}')">
        <div class="ri-dot ${i.urgency}"></div>
        <div class="ri-body">
          <div class="ri-name">${i.name}</div>
          <div class="ri-detail">${i.detail}</div>
        </div>
        <span class="ri-badge ${i.urgency}">${i.when}</span>
      </div>`).join('');
  }

  body.innerHTML = html;
  document.getElementById('reminder-modal').style.display = 'flex';
}

function goToLead(id) {
  closeModal('reminder-modal');
  const btn = document.querySelector('.tab-btn:nth-child(3)');
  switchTab('leads', btn);
  setTimeout(() => viewLead(id), 200);
}

function goToContract(id) {
  closeModal('reminder-modal');
  const btn = document.querySelector('.tab-btn:nth-child(4)');
  switchTab('contracts', btn);
  // open the right month
  const c = contracts.find(x => x.id === id);
  if (c && c.enddate) {
    const d = new Date(c.enddate);
    // expand that month block
    setTimeout(() => {
      const mbId = `mb-${d.getFullYear()}-${d.getMonth()}`;
      const mb = document.getElementById(mbId);
      if (mb && !mb.classList.contains('open')) mb.classList.add('open');
      setTimeout(() => viewContract(id), 100);
    }, 300);
  }
}

// ══════════════════════════════════════════════════════
// BOOT
// ══════════════════════════════════════════════════════
load();
document.getElementById('month-label').textContent=`${MONTHS[currentMonth]} ${currentYear}`;
document.getElementById('dash-month-label').textContent=MONTHS[dashMonth].toUpperCase()+' '+dashYear;
renderList();
renderStats();
updateBell();
</script>
</body>
</html>
