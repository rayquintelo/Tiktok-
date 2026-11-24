<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>TikTok Live — Control Panel</title>
<style>
  :root {
    --bg:      #0a0a14;
    --surface: #12121f;
    --border:  #1e1e35;
    --accent:  #ff0080;
    --accent2: #00d4ff;
    --text:    #e8e8f0;
    --muted:   #6b6b90;
    --success: #00e676;
    --warn:    #ffab00;
    --danger:  #ff3d3d;
    --radius:  10px;
    --font:    'Segoe UI', system-ui, sans-serif;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--font);
    min-height: 100vh;
    padding: 20px;
  }

  .header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 24px;
    padding-bottom: 16px;
    border-bottom: 1px solid var(--border);
    flex-wrap: wrap;
    gap: 12px;
  }
  .header h1 {
    font-size: 20px;
    font-weight: 700;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  .header-right { display: flex; align-items: center; gap: 12px; }
  .status-pill {
    display: flex;
    align-items: center;
    gap: 6px;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 20px;
    padding: 5px 12px;
    font-size: 12px;
  }
  .dot {
    width: 8px; height: 8px;
    border-radius: 50%;
    background: var(--danger);
    transition: background 0.3s;
    flex-shrink: 0;
  }
  .dot.on { background: var(--success); box-shadow: 0 0 6px var(--success); }

  .grid {
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    gap: 14px;
  }
  .col-4 { grid-column: span 4; }
  .col-6 { grid-column: span 6; }
  .col-8 { grid-column: span 8; }
  .col-12{ grid-column: span 12; }

  @media (max-width: 900px) {
    .col-4, .col-6, .col-8 { grid-column: span 12; }
  }

  .card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 16px;
  }
  .card-title {
    font-size: 11px;
    font-weight: 700;
    color: var(--muted);
    text-transform: uppercase;
    letter-spacing: 0.08em;
    margin-bottom: 14px;
  }

  .stats { display: flex; gap: 10px; flex-wrap: wrap; }
  .stat {
    background: var(--bg);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 10px 14px;
    flex: 1;
    min-width: 70px;
    text-align: center;
  }
  .stat .val {
    font-size: 28px;
    font-weight: 700;
    color: var(--accent);
    line-height: 1;
  }
  .stat .lbl { font-size: 10px; color: var(--muted); margin-top: 4px; }

  input[type=text] {
    width: 100%;
    background: var(--bg);
    border: 1px solid var(--border);
    border-radius: 8px;
    color: var(--text);
    padding: 9px 12px;
    font-size: 13px;
    font-family: var(--font);
    outline: none;
    transition: border 0.2s;
    margin-bottom: 8px;
  }
  input:focus { border-color: var(--accent); }

  .btn {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    padding: 8px 14px;
    border-radius: 8px;
    border: none;
    cursor: pointer;
    font-size: 12px;
    font-weight: 600;
    font-family: var(--font);
    transition: opacity 0.15s, transform 0.1s;
    white-space: nowrap;
  }
  .btn:active { transform: scale(0.97); }
  .btn-primary  { background: var(--accent);  color: #fff; }
  .btn-secondary{ background: var(--accent2); color: #000; }
  .btn-danger   { background: var(--danger);  color: #fff; }
  .btn-ghost    { background: var(--border);  color: var(--text); }
  .btn-success  { background: var(--success); color: #000; }
  .btn-warn     { background: var(--warn);    color: #000; }
  .btn-row { display: flex; gap: 8px; flex-wrap: wrap; margin-top: 8px; }

  .type-row {
    display: flex;
    gap: 6px;
    flex-wrap: wrap;
    margin-bottom: 10px;
  }
  .type-btn {
    padding: 4px 10px;
    border-radius: 20px;
    border: 1px solid var(--border);
    background: var(--bg);
    color: var(--muted);
    cursor: pointer;
    font-size: 11px;
    font-weight: 600;
    font-family: var(--font);
    transition: all 0.15s;
  }
  .type-btn.active {
    border-color: var(--accent);
    color: var(--accent);
    background: #1a0010;
  }

  .event-log {
    max-height: 280px;
    overflow-y: auto;
    scrollbar-width: thin;
    scrollbar-color: var(--border) transparent;
  }
  .event-row {
    display: flex;
    align-items: center;
    gap: 8px;
    padding: 7px 2px;
    border-bottom: 1px solid var(--border);
    font-size: 12px;
    animation: fadeIn 0.3s ease;
  }
  .event-row:last-child { border-bottom: none; }
  @keyframes fadeIn {
    from { opacity: 0; transform: translateY(-3px); }
    to   { opacity: 1; }
  }
  .badge {
    padding: 2px 7px;
    border-radius: 20px;
    font-size: 10px;
    font-weight: 700;
    white-space: nowrap;
    flex-shrink: 0;
  }
  .b-follow  { background:#1a3a1a; color:var(--success); }
  .b-like    { background:#3a1a2a; color:var(--accent);  }
  .b-comment { background:#1a2a3a; color:var(--accent2); }
  .b-gift    { background:#3a2a0a; color:var(--warn);    }
  .b-goal    { background:#2a1a3a; color:#c084fc;        }

  .ev-user { font-weight: 600; flex-shrink: 0; }
  .ev-pay  { color: var(--muted); flex: 1;
             overflow: hidden; text-overflow: ellipsis; white-space: nowrap; }
  .ev-time { color: var(--muted); font-size: 10px; white-space: nowrap; flex-shrink: 0; }

  .queue-list {
    max-height: 200px;
    overflow-y: auto;
    scrollbar-width: thin;
    scrollbar-color: var(--border) transparent;
  }
  .q-row {
    display: flex;
    align-items: center;
    gap: 8px;
    padding: 6px 0;
    border-bottom: 1px solid var(--border);
    font-size: 12px;
  }
  .q-row:last-child { border-bottom: none; }
  .q-pos  { color: var(--warn); font-weight: 700; width: 24px; text-align: center; flex-shrink: 0; }
  .q-user { flex: 1; }
  .q-type { color: var(--muted); font-size: 10px; }
  .q-kick {
    background: none;
    border: none;
    color: var(--danger);
    cursor: pointer;
    font-size: 13px;
    padding: 0 4px;
    flex-shrink: 0;
  }

  .goals-list { display: flex; flex-direction: column; gap: 10px; }
  .goal-item {}
  .goal-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 5px;
  }
  .goal-label { font-size: 12px; font-weight: 600; }
  .goal-count { font-size: 11px; color: var(--muted); }
  .goal-track {
    height: 8px;
    background: var(--bg);
    border-radius: 4px;
    overflow: hidden;
    border: 1px solid var(--border);
  }
  .goal-fill {
    height: 100%;
    border-radius: 4px;
    background: linear-gradient(90deg, var(--accent), var(--accent2));
    transition: width 0.6s cubic-bezier(.4,0,.2,1);
  }
  .goal-fill.done {
    background: linear-gradient(90deg, var(--success), #00bfa5);
  }

  .info-line {
    font-size: 11px;
    color: var(--muted);
    margin-top: 10px;
    padding-top: 10px;
    border-top: 1px solid var(--border);
  }

  #toast {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 8px;
    padding: 10px 16px;
    font-size: 13px;
    opacity: 0;
    transform: translateY(8px);
    transition: all 0.25s;
    pointer-events: none;
    z-index: 999;
  }
  #toast.show { opacity: 1; transform: translateY(0); }
  #toast.ok  { border-color: var(--success); color: var(--success); }
  #toast.err { border-color: var(--danger);  color: var(--danger);  }

  ::-webkit-scrollbar { width: 4px; }
  ::-webkit-scrollbar-track { background: transparent; }
  ::-webkit-scrollbar-thumb { background: var(--border); border-radius: 4px; }

  .empty { color: var(--muted); font-size: 12px; padding: 8px 0; }

  .bridge-url {
    font-size: 11px;
    color: var(--accent2);
    background: var(--bg);
    border: 1px solid var(--border);
    border-radius: 6px;
    padding: 6px 10px;
    margin-bottom: 8px;
    word-break: break-all;
    font-family: monospace;
  }
</style>
</head>
<body>

<div class="header">
  <h1>🎛 TikTok Live — Control Panel</h1>
  <div class="header-right">
    <div class="status-pill">
      <span class="dot" id="dot"></span>
      <span id="status-text">verificando...</span>
    </div>
    <div class="status-pill" id="uptime-pill">⏱ 0s</div>
  </div>
</div>

<div class="grid">

  <!-- Stats -->
  <div class="card col-12">
    <div class="card-title">Visão geral</div>
    <div class="stats">
      <div class="stat">
        <div class="val" id="s-queued">0</div>
        <div class="lbl">fila bridge</div>
      </div>
      <div class="stat">
        <div class="val" id="s-events">0</div>
        <div class="lbl">eventos</div>
      </div>
      <div class="stat">
        <div class="val" id="s-follow">0</div>
        <div class="lbl">follows</div>
      </div>
      <div class="stat">
        <div class="val" id="s-like">0</div>
        <div class="lbl">likes</div>
      </div>
      <div class="stat">
        <div class="val" id="s-comment">0</div>
        <div class="lbl">comentários</div>
      </div>
      <div class="stat">
        <div class="val" id="s-gift">0</div>
        <div class="lbl">presentes</div>
      </div>
    </div>
    <div class="btn-row" style="margin-top:14px;">
      <button class="btn btn-danger" onclick="doDisconnect()">⏹ Desconectar TikTok</button>
      <button class="btn btn-ghost"  onclick="clearQueue()">🗑 Limpar fila</button>
      <button class="btn btn-warn"   onclick="triggerGoal()">🏆 Disparar meta</button>
      <button class="btn btn-secondary" onclick="syncDance()">💃 Sync dance todos</button>
    </div>
    <div class="info-line" id="config-line">bridge: carregando...</div>
  </div>

  <!-- Conectar TikTok -->
  <div class="card col-4">
    <div class="card-title">Conexão TikTok LIVE</div>
    <input type="text" id="tt-user" placeholder="@seuusuario">
    <div class="btn-row">
      <button class="btn btn-primary" onclick="connectTT()">▶ Conectar</button>
    </div>
    <div class="info-line">
      Conecte ao username da conta que está ao vivo.
      A bridge inicia a captura automaticamente.
    </div>
  </div>

  <!-- Injetar evento -->
  <div class="card col-4">
    <div class="card-title">Injetar evento manual</div>
    <div class="type-row" id="type-row">
      <div class="type-btn active" data-type="follow">follow</div>
      <div class="type-btn" data-type="like">like</div>
      <div class="type-btn" data-type="comment">comment</div>
      <div class="type-btn" data-type="gift">gift</div>
      <div class="type-btn" data-type="goal_reached">meta</div>
    </div>
    <input type="text" id="inj-user" placeholder="username do TikTok">
    <input type="text" id="inj-pay"  placeholder="payload (ex: robot, palma)">
    <div class="btn-row">
      <button class="btn btn-success" onclick="injectEvent()">▷ Disparar</button>
    </div>
  </div>

  <!-- Metas -->
  <div class="card col-4">
    <div class="card-title">Metas da live</div>
    <div class="goals-list" id="goals-list">
      <div class="empty">sem dados de meta</div>
    </div>
    <div class="btn-row" style="margin-top:12px;">
      <button class="btn btn-ghost" onclick="resetGoals()">🔄 Resetar metas</button>
    </div>
  </div>

  <!-- Log de eventos -->
  <div class="card col-8">
    <div class="card-title">
      Log de eventos
      <span id="ev-count" style="color:var(--muted);font-weight:400;text-transform:none;letter-spacing:0;margin-left:6px;"></span>
    </div>
    <div class="event-log" id="event-log">
      <div class="empty">aguardando eventos...</div>
    </div>
  </div>

  <!-- Fila de espera -->
  <div class="card col-4">
    <div class="card-title">Fila da bridge</div>
    <div class="queue-list" id="queue-list">
      <div class="empty">fila vazia</div>
    </div>
  </div>

</div>

<div id="toast"></div>

<script>
// ── Demo data (substitui chamadas reais quando sem servidor) ──────────────────
const DEMO_MODE = true;   // ← mude para false quando rodar o server.js real

const BASE = window.location.origin;

// Estado de demo
let demoState = {
  connected: false,
  user: null,
  uptime: 0,
  queued: 0,
  events: [],
  queue: [],
  counters: { follow:0, like:0, comment:0, gift:0, goal_reached:0 },
  goals: [
    { label:"🔥 50 curtidas",     type:"likes",     target:50,  current:12, reached:false },
    { label:"👥 20 seguidores",   type:"followers", target:20,  current:5,  reached:false },
    { label:"🎁 10 presentes",    type:"gifts",     target:10,  current:3,  reached:false },
    { label:"💬 100 comentários", type:"comments",  target:100, current:28, reached:false },
  ],
};

const NAMES = ["danca_br","tikfan99","live_lover","roblox_kid","neon_girl",
               "bass_drop","dancarino","user_star","pink_wave","hyper_fan"];
const TYPES = ["follow","like","comment","gift","comment","like","follow","comment"];
const PAYS  = ["","","robot","","palma","","","dança"];

function randomEvent() {
  const i  = Math.floor(Math.random() * TYPES.length);
  const t  = TYPES[i];
  const u  = NAMES[Math.floor(Math.random() * NAMES.length)];
  const p  = PAYS[i];
  return { type:t, username:u, payload:p,
           receivedAt: new Date().toISOString(),
           sig: Math.random().toString(36).slice(2) };
}

// ── Utilitários ───────────────────────────────────────────────────────────────
function toast(msg, type="ok") {
  const t = document.getElementById("toast");
  t.textContent = msg;
  t.className = `show ${type}`;
  setTimeout(() => { t.className = ""; }, 2500);
}

async function api(method, path, body) {
  if (DEMO_MODE) return demoApi(method, path, body);
  try {
    const r = await fetch(BASE + path, {
      method,
      headers: { "Content-Type":"application/json" },
      body: body ? JSON.stringify(body) : undefined,
    });
    return await r.json();
  } catch(e) {
    toast("Sem servidor: " + e.message, "err");
    return null;
  }
}

function demoApi(method, path, body) {
  if (path === "/api/status") {
    demoState.uptime += 2;
    demoState.queued = Math.floor(Math.random() * 4);
    return { ...demoState,
      queue: demoState.queue,
      uptime: demoState.uptime };
  }
  if (path === "/api/events") {
    return { events: demoState.events.slice(0,50) };
  }
  if (path === "/api/queue") {
    return { queue: demoState.queue };
  }
  if (path === "/api/config") {
    return {
      poll_url: "http://localhost:3000/poll",
      secret_set: true,
      tiktok_user: demoState.user || "não conectado",
    };
  }
  if (path === "/api/connect" && body?.username) {
    demoState.connected = true;
    demoState.user = body.username;
    return { ok: true };
  }
  if (path === "/api/disconnect") {
    demoState.connected = false;
    demoState.user = null;
    return { ok: true };
  }
  if (method === "DELETE" && path === "/api/queue") {
    demoState.queue = [];
    return { ok: true };
  }
  if (path === "/api/inject" && body) {
    const e = { ...body, receivedAt: new Date().toISOString(),
                sig: Math.random().toString(36).slice(2) };
    demoState.events.unshift(e);
    demoState.counters[body.type] = (demoState.counters[body.type]||0)+1;
    return { ok: true };
  }
  return { ok: true };
}

// ── Status ────────────────────────────────────────────────────────────────────
let totalEvents = 0;

async function refreshStatus() {
  const d = await api("GET", "/api/status");
  if (!d) return;
  const dot  = document.getElementById("dot");
  const text = document.getElementById("status-text");
  dot.className  = "dot" + (d.connected ? " on" : "");
  text.textContent = d.connected ? `@${d.user}` : "desconectado";
  document.getElementById("uptime-pill").textContent = `⏱ ${d.uptime}s`;
  document.getElementById("s-queued").textContent = d.queued ?? 0;
}

async function refreshConfig() {
  const d = await api("GET", "/api/config");
  if (!d) return;
  document.getElementById("config-line").textContent =
    `bridge: ${window.location.host}  |  poll → Roblox: ${d.poll_url}`;
}

// ── Contadores ────────────────────────────────────────────────────────────────
function updateCounters(events) {
  const c = { follow:0, like:0, comment:0, gift:0 };
  for (const e of events) {
    if (c[e.type] !== undefined) c[e.type]++;
  }
  document.getElementById("s-follow").textContent  = c.follow;
  document.getElementById("s-like").textContent    = c.like;
  document.getElementById("s-comment").textContent = c.comment;
  document.getElementById("s-gift").textContent    = c.gift;
  document.getElementById("s-events").textContent  = events.length;
}

// ── Log de eventos ────────────────────────────────────────────────────────────
const BADGE_CLASS = {
  follow:"b-follow", like:"b-like", comment:"b-comment",
  gift:"b-gift", goal_reached:"b-goal"
};
const BADGE_LABEL = {
  follow:"follow", like:"like", comment:"comment",
  gift:"gift", goal_reached:"meta"
};

let lastSig = null;

async function refreshEvents() {
  const d = await api("GET", "/api/events");
  if (!d?.events) return;
  if (d.events.length && d.events[0].sig === lastSig) return;
  if (d.events.length) lastSig = d.events[0].sig;

  updateCounters(d.events);
  document.getElementById("ev-count").textContent =
    d.events.length ? `(${d.events.length})` : "";

  const log = document.getElementById("event-log");
  if (!d.events.length) {
    log.innerHTML = `<div class="empty">aguardando eventos...</div>`;
    return;
  }
  log.innerHTML = "";
  for (const e of d.events.slice(0, 40)) {
    const bc  = BADGE_CLASS[e.type] || "b-comment";
    const lbl = BADGE_LABEL[e.type] || e.type;
    const t   = e.receivedAt
      ? new Date(e.receivedAt).toLocaleTimeString("pt-BR")
      : "—";
    const row = document.createElement("div");
    row.className = "event-row";
    row.innerHTML = `
      <span class="badge ${bc}">${lbl}</span>
      <span class="ev-user">@${e.username}</span>
      <span class="ev-pay">${e.payload || ""}</span>
      <span class="ev-time">${t}</span>
    `;
    log.appendChild(row);
  }
}

// ── Fila ──────────────────────────────────────────────────────────────────────
async function refreshQueue() {
  const d = await api("GET", "/api/queue");
  const list = document.getElementById("queue-list");
  if (!d?.queue?.length) {
    list.innerHTML = `<div class="empty">fila vazia</div>`;
    return;
  }
  list.innerHTML = "";
  d.queue.slice(0,15).forEach((e,i) => {
    const row = document.createElement("div");
    row.className = "q-row";
    row.innerHTML = `
      <span class="q-pos">#${i+1}</span>
      <span class="q-user">@${e.username||e.type||"?"}</span>
      <span class="q-type">${e.type||""}</span>
      <button class="q-kick" title="remover" onclick="kickQueue('${e.username}')">✕</button>
    `;
    list.appendChild(row);
  });
}

// ── Metas ─────────────────────────────────────────────────────────────────────
function renderGoals(goals) {
  const el = document.getElementById("goals-list");
  if (!goals?.length) { el.innerHTML = `<div class="empty">sem dados</div>`; return; }
  el.innerHTML = "";
  for (const g of goals) {
    const pct  = Math.min(g.current / g.target, 1);
    const done = g.reached || pct >= 1;
    const item = document.createElement("div");
    item.className = "goal-item";
    item.innerHTML = `
      <div class="goal-header">
        <span class="goal-label">${g.label}</span>
        <span class="goal-count">${g.current}/${g.target}</span>
      </div>
      <div class="goal-track">
        <div class="goal-fill ${done?"done":""}" style="width:${Math.round(pct*100)}%"></div>
      </div>
    `;
    el.appendChild(item);
  }
}

// ── Ações ─────────────────────────────────────────────────────────────────────
async function connectTT() {
  const u = document.getElementById("tt-user").value.trim().replace("@","");
  if (!u) { toast("Digite um username","err"); return; }
  const d = await api("POST","/api/connect",{ username:u });
  if (d?.ok) toast(`Conectando @${u}…`);
}

async function doDisconnect() {
  const d = await api("POST","/api/disconnect");
  if (d?.ok) toast("Desconectado");
}

async function clearQueue() {
  await api("DELETE","/api/queue");
  toast("Fila limpa");
  demoState.queue = [];
  refreshQueue();
}

async function triggerGoal() {
  await injectRaw("goal_reached","admin_panel","");
  toast("Meta disparada 🏆");
}

async function syncDance() {
  await injectRaw("goal_reached","sync_all","celebration");
  toast("Sync dance disparado 💃");
}

async function resetGoals() {
  for (const g of demoState.goals) { g.current = 0; g.reached = false; }
  renderGoals(demoState.goals);
  toast("Metas resetadas");
}

async function kickQueue(username) {
  demoState.queue = demoState.queue.filter(e => e.username !== username);
  refreshQueue();
  toast(`@${username} removido da fila`);
}

async function injectRaw(type, username, payload) {
  return api("POST","/api/inject",{ type, username, payload });
}

// Injetar evento manual
let selectedType = "follow";

document.getElementById("type-row").addEventListener("click", e => {
  const btn = e.target.closest(".type-btn");
  if (!btn) return;
  document.querySelectorAll(".type-btn").forEach(b => b.classList.remove("active"));
  btn.classList.add("active");
  selectedType = btn.dataset.type;
});

async function injectEvent() {
  const u = document.getElementById("inj-user").value.trim();
  const p = document.getElementById("inj-pay").value.trim();
  if (!u) { toast("Digite um username","err"); return; }
  const d = await api("POST","/api/inject",{ type:selectedType, username:u, payload:p });
  if (d?.ok) {
    toast(`${selectedType} → @${u}`);
    document.getElementById("inj-user").value = "";
    document.getElementById("inj-pay").value  = "";
    if (DEMO_MODE) {
      demoState.events.unshift({
        type:selectedType, username:u, payload:p,
        receivedAt: new Date().toISOString(),
        sig: Math.random().toString(36).slice(2),
      });
      // Atualiza meta demo
      const map = { follow:"followers", like:"likes",
                    comment:"comments", gift:"gifts" };
      const gt  = map[selectedType];
      if (gt) {
        for (const g of demoState.goals) {
          if (g.type === gt && !g.reached) {
            g.current = Math.min(g.current+1, g.target);
            if (g.current >= g.target) g.reached = true;
          }
        }
      }
      renderGoals(demoState.goals);
    }
  }
}

document.getElementById("inj-user").addEventListener("keydown", e => {
  if (e.key === "Enter") injectEvent();
});

// ── Demo: gera eventos automáticos ───────────────────────────────────────────
if (DEMO_MODE) {
  setInterval(() => {
    if (!demoState.connected) return;
    const e = randomEvent();
    demoState.events.unshift(e);
    if (demoState.events.length > 100) demoState.events.pop();
    const map = { follow:"followers", like:"likes",
                  comment:"comments", gift:"gifts" };
    const gt  = map[e.type];
    if (gt) {
      for (const g of demoState.goals) {
        if (g.type === gt && !g.reached) {
          g.current = Math.min(g.current+1, g.target);
          if (g.current >= g.target) g.reached = true;
        }
      }
    }
  }, 1800);
}

// ── Tick principal ────────────────────────────────────────────────────────────
async function tick() {
  await Promise.all([
    refreshStatus(),
    refreshEvents(),
    refreshQueue(),
  ]);
  renderGoals(demoState.goals);
}

refreshConfig();
tick();
setInterval(tick, 2500);
</script>
</body>
</html>
