<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jutsu Forge — 呪術廻戦 術式開発</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Noto+Sans+JP:wght@400;500;700&family=Noto+Serif+JP:wght@700;900&display=swap');

*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

:root {
  --bg:        #09090b;
  --surface:   #111113;
  --panel:     #18181b;
  --panel2:    #1c1c20;
  --border:    #27272a;
  --border2:   #3f3f46;
  --accent:    #8b5cf6;
  --accent-h:  #7c3aed;
  --accent-l:  #a78bfa;
  --accent-xl: #ddd6fe;
  --gold:      #f59e0b;
  --gold-l:    #fcd34d;
  --red:       #ef4444;
  --green:     #22c55e;
  --blue:      #3b82f6;
  --zinc:      #71717a;
  --text:      #fafafa;
  --text2:     #d4d4d8;
  --text3:     #a1a1aa;
  --text4:     #71717a;
  --radius:    10px;
  --radius-lg: 16px;
}

html { scroll-behavior: smooth; }

body {
  background: var(--bg);
  color: var(--text);
  font-family: 'Inter', 'Noto Sans JP', sans-serif;
  font-size: 14px;
  line-height: 1.6;
  min-height: 100vh;
  -webkit-font-smoothing: antialiased;
}

/* ───── NAV ───── */
nav {
  position: sticky;
  top: 0;
  z-index: 50;
  height: 52px;
  background: rgba(9,9,11,0.85);
  backdrop-filter: blur(12px);
  border-bottom: 1px solid var(--border);
  display: flex;
  align-items: center;
  padding: 0 1.5rem;
  gap: 0.6rem;
}
.nav-logo {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-weight: 700;
  font-size: 0.95rem;
  color: var(--text);
  letter-spacing: -0.02em;
}
.nav-logo-icon {
  width: 26px; height: 26px;
  background: linear-gradient(135deg, var(--accent), var(--gold));
  border-radius: 7px;
  display: flex; align-items: center; justify-content: center;
  font-size: 0.8rem;
}
.nav-badge {
  font-size: 0.65rem;
  font-weight: 600;
  color: var(--accent-l);
  background: rgba(139,92,246,0.15);
  border: 1px solid rgba(139,92,246,0.3);
  padding: 1px 7px;
  border-radius: 999px;
  letter-spacing: 0.03em;
}
.nav-spacer { flex: 1; }
.nav-link {
  font-size: 0.8rem;
  color: var(--text3);
  text-decoration: none;
  padding: 0.3rem 0.6rem;
  border-radius: 6px;
  transition: color 0.15s, background 0.15s;
}
.nav-link:hover { color: var(--text); background: var(--panel); }

/* ───── HERO ───── */
.hero {
  max-width: 720px;
  margin: 0 auto;
  padding: 3.5rem 1.5rem 2rem;
  text-align: center;
}
.hero-eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 0.4rem;
  font-size: 0.72rem;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: var(--accent-l);
  background: rgba(139,92,246,0.1);
  border: 1px solid rgba(139,92,246,0.25);
  padding: 0.3rem 0.85rem;
  border-radius: 999px;
  margin-bottom: 1.2rem;
}
.hero-eyebrow::before { content: '✦'; font-size: 0.6rem; }
h1 {
  font-family: 'Inter', sans-serif;
  font-weight: 700;
  font-size: clamp(1.75rem, 4vw, 2.6rem);
  line-height: 1.15;
  letter-spacing: -0.03em;
  color: var(--text);
  margin-bottom: 0.75rem;
}
h1 em {
  font-style: normal;
  background: linear-gradient(135deg, var(--accent-l), var(--gold-l));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}
.hero-desc {
  font-size: 0.95rem;
  color: var(--text3);
  max-width: 480px;
  margin: 0 auto;
  line-height: 1.7;
}

/* ───── MAIN LAYOUT ───── */
.main {
  max-width: 720px;
  margin: 0 auto;
  padding: 0 1.5rem 6rem;
}

/* ───── SECTION HEADING ───── */
.section-heading {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  font-size: 0.72rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.1em;
  color: var(--text4);
  margin-bottom: 0.75rem;
  margin-top: 1.8rem;
}
.section-heading::after {
  content: '';
  flex: 1;
  height: 1px;
  background: var(--border);
}
.section-num {
  width: 20px; height: 20px;
  background: var(--panel);
  border: 1px solid var(--border2);
  border-radius: 5px;
  display: flex; align-items: center; justify-content: center;
  font-size: 0.65rem;
  color: var(--text3);
  font-weight: 700;
}

/* ───── FIELD GROUP ───── */
.field-group {
  background: var(--panel);
  border: 1px solid var(--border);
  border-radius: var(--radius-lg);
  overflow: hidden;
  margin-bottom: 0.75rem;
}
.field-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 0;
}
.field {
  padding: 1rem 1.25rem;
  border-bottom: 1px solid var(--border);
  position: relative;
}
.field:last-child { border-bottom: none; }
.field-row .field:first-child { border-right: 1px solid var(--border); }
.field-row:last-child .field { border-bottom: none; }
.field-row-3 { grid-template-columns: 1fr 1fr 1fr; }
.field-row-3 .field:nth-child(2) { border-right: 1px solid var(--border); border-left: 1px solid var(--border); }

label {
  display: flex;
  align-items: center;
  gap: 0.35rem;
  font-size: 0.75rem;
  font-weight: 600;
  color: var(--text3);
  margin-bottom: 0.4rem;
  letter-spacing: 0.02em;
}
.label-required {
  font-size: 0.6rem;
  color: var(--red);
  background: rgba(239,68,68,0.1);
  padding: 1px 5px;
  border-radius: 3px;
}

input[type="text"], textarea {
  width: 100%;
  background: transparent;
  border: none;
  outline: none;
  color: var(--text);
  font-family: 'Inter', 'Noto Sans JP', sans-serif;
  font-size: 0.92rem;
  line-height: 1.5;
  resize: none;
}
input::placeholder, textarea::placeholder { color: var(--text4); }
textarea { min-height: 72px; }

/* ───── TAGS ───── */
.tag-field { padding: 1rem 1.25rem; border-bottom: 1px solid var(--border); }
.tag-field:last-child { border-bottom: none; }
.tag-wrap { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-top: 0.5rem; }
.tag {
  display: inline-flex; align-items: center; gap: 0.25rem;
  padding: 0.28rem 0.75rem;
  font-size: 0.78rem;
  font-weight: 500;
  color: var(--text3);
  background: var(--panel2);
  border: 1px solid var(--border2);
  border-radius: 999px;
  cursor: pointer;
  transition: all 0.15s;
  user-select: none;
  white-space: nowrap;
}
.tag:hover { color: var(--text2); border-color: var(--accent); background: rgba(139,92,246,0.08); }
.tag.active {
  color: var(--accent-xl);
  background: rgba(139,92,246,0.18);
  border-color: var(--accent);
  font-weight: 600;
}

/* ───── RANK PICKER ───── */
.rank-field { padding: 1rem 1.25rem; border-bottom: 1px solid var(--border); }
.rank-field:last-child { border-bottom: none; }
.rank-grid { display: flex; gap: 0.5rem; margin-top: 0.5rem; }
.rank-btn {
  flex: 1;
  padding: 0.5rem 0.25rem;
  background: var(--panel2);
  border: 1px solid var(--border2);
  border-radius: 8px;
  font-family: 'Inter', 'Noto Sans JP', sans-serif;
  font-size: 0.82rem;
  font-weight: 600;
  color: var(--text4);
  cursor: pointer;
  transition: all 0.15s;
  text-align: center;
}
.rank-btn:hover { color: var(--text2); border-color: var(--border2); background: var(--panel); }
.rank-btn.r4 { color: var(--zinc);  border-color: var(--zinc);  background: rgba(113,113,122,0.1); }
.rank-btn.r3 { color: var(--green); border-color: var(--green); background: rgba(34,197,94,0.1); }
.rank-btn.r2 { color: var(--blue);  border-color: var(--blue);  background: rgba(59,130,246,0.1); }
.rank-btn.r1 { color: var(--gold);  border-color: var(--gold);  background: rgba(245,158,11,0.1); }
.rank-btn.r0 { color: var(--red);   border-color: var(--red);   background: rgba(239,68,68,0.12); box-shadow: 0 0 0 1px rgba(239,68,68,0.2); }

/* ───── SUBMIT BUTTON ───── */
.submit-wrap { margin-top: 1.25rem; }
.submit-btn {
  width: 100%;
  padding: 0.85rem 1.5rem;
  background: var(--accent);
  border: none;
  border-radius: var(--radius);
  color: #fff;
  font-family: 'Inter', 'Noto Sans JP', sans-serif;
  font-size: 0.92rem;
  font-weight: 600;
  letter-spacing: 0.01em;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  transition: background 0.15s, transform 0.1s, box-shadow 0.15s;
  box-shadow: 0 1px 3px rgba(0,0,0,0.4), 0 0 0 1px rgba(139,92,246,0.5);
}
.submit-btn:hover { background: var(--accent-h); box-shadow: 0 4px 16px rgba(139,92,246,0.4); transform: translateY(-1px); }
.submit-btn:active { transform: none; }
.submit-btn:disabled { opacity: 0.4; cursor: not-allowed; transform: none; box-shadow: none; }
.submit-btn svg { width: 16px; height: 16px; }

/* ───── ERROR ───── */
.error-box {
  display: none;
  margin-top: 0.75rem;
  padding: 0.75rem 1rem;
  background: rgba(239,68,68,0.08);
  border: 1px solid rgba(239,68,68,0.3);
  border-radius: var(--radius);
  color: #fca5a5;
  font-size: 0.82rem;
  line-height: 1.5;
}
.error-box.show { display: block; }

/* ───── LOADING OVERLAY ───── */
#loading {
  display: none;
  position: fixed; inset: 0; z-index: 999;
  background: rgba(9,9,11,0.8);
  backdrop-filter: blur(8px);
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 1.2rem;
}
#loading.on { display: flex; }
.loader-ring {
  width: 44px; height: 44px;
  border: 2px solid rgba(139,92,246,0.2);
  border-top-color: var(--accent-l);
  border-radius: 50%;
  animation: spin 0.8s linear infinite;
}
@keyframes spin { to { transform: rotate(360deg); } }
.loader-text {
  font-size: 0.82rem;
  font-weight: 500;
  color: var(--text3);
  letter-spacing: 0.06em;
  animation: pulse 1.6s ease-in-out infinite;
}
@keyframes pulse { 0%,100%{opacity:.4} 50%{opacity:1} }

/* ───── RESULT SECTION ───── */
#result-section { display: none; margin-top: 2rem; }
#result-section.show { display: block; animation: fadeUp 0.4s ease; }
@keyframes fadeUp { from{opacity:0;transform:translateY(16px)} to{opacity:1;transform:none} }

/* Result Card */
.result-card {
  background: var(--panel);
  border: 1px solid var(--border);
  border-radius: var(--radius-lg);
  overflow: hidden;
}

/* Result Header Band */
.result-header {
  padding: 1.5rem 1.5rem 1.25rem;
  border-bottom: 1px solid var(--border);
  background: linear-gradient(135deg, rgba(139,92,246,0.06) 0%, rgba(245,158,11,0.04) 100%);
}
.result-flavor {
  font-size: 0.78rem;
  color: var(--text4);
  font-style: italic;
  margin-bottom: 0.75rem;
  padding-left: 0.75rem;
  border-left: 2px solid var(--border2);
}
.result-title-row {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 1rem;
  flex-wrap: wrap;
}
.result-name {
  font-family: 'Noto Serif JP', serif;
  font-weight: 900;
  font-size: clamp(1.5rem, 3.5vw, 2rem);
  color: var(--text);
  letter-spacing: 0.02em;
  line-height: 1.2;
}
.result-reading {
  font-size: 0.8rem;
  color: var(--text4);
  margin-top: 0.2rem;
  letter-spacing: 0.05em;
}
.result-badges { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-top: 0.9rem; }
.badge {
  display: inline-flex; align-items: center;
  font-size: 0.7rem;
  font-weight: 600;
  padding: 0.22rem 0.7rem;
  border-radius: 5px;
  border: 1px solid;
  letter-spacing: 0.04em;
}
.b-type   { color: var(--accent-l);  border-color: rgba(167,139,250,0.4); background: rgba(139,92,246,0.1); }
.b-rank-特級 { color: var(--red);   border-color: rgba(239,68,68,0.4);  background: rgba(239,68,68,0.08); }
.b-rank-1級  { color: var(--gold);  border-color: rgba(245,158,11,0.4); background: rgba(245,158,11,0.08); }
.b-rank-2級  { color: var(--blue);  border-color: rgba(59,130,246,0.4); background: rgba(59,130,246,0.08); }
.b-rank-3級  { color: var(--green); border-color: rgba(34,197,94,0.4);  background: rgba(34,197,94,0.08); }
.b-rank-4級  { color: var(--zinc);  border-color: rgba(113,113,122,0.4);background: rgba(113,113,122,0.08); }

/* Result Body */
.result-body { padding: 0; }
.res-block {
  padding: 1.25rem 1.5rem;
  border-bottom: 1px solid var(--border);
}
.res-block:last-child { border-bottom: none; }
.res-block-label {
  font-size: 0.68rem;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.12em;
  color: var(--text4);
  margin-bottom: 0.6rem;
}
.res-block-text {
  font-size: 0.9rem;
  color: var(--text2);
  line-height: 1.75;
}

/* Techniques */
.tech-list { display: flex; flex-direction: column; gap: 0.6rem; }
.tech-item {
  padding: 0.8rem 1rem;
  background: var(--panel2);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  border-left: 2px solid var(--accent);
}
.tech-name {
  font-size: 0.9rem;
  font-weight: 700;
  color: var(--text);
  margin-bottom: 0.25rem;
}
.tech-name span { font-size: 0.75rem; font-weight: 400; color: var(--text4); margin-left: 0.3rem; }
.tech-desc { font-size: 0.83rem; color: var(--text3); line-height: 1.65; }

/* Domain */
.domain-block {
  background: linear-gradient(135deg, rgba(139,92,246,0.07), rgba(245,158,11,0.05));
  border: 1px solid rgba(139,92,246,0.25);
  border-radius: var(--radius);
  padding: 1rem 1.1rem;
}
.domain-name-text {
  font-family: 'Noto Serif JP', serif;
  font-weight: 900;
  font-size: 1.05rem;
  color: var(--gold-l);
  margin-bottom: 0.4rem;
}
.domain-name-text span { font-size: 0.78rem; font-weight: 400; color: var(--text4); margin-left: 0.3rem; }
.domain-desc-text { font-size: 0.85rem; color: var(--text2); line-height: 1.7; }

/* Stats */
.stats-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 0.6rem; }
.stat-card {
  background: var(--panel2);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 0.75rem;
  text-align: center;
}
.stat-label-t { font-size: 0.67rem; font-weight: 600; color: var(--text4); letter-spacing: 0.05em; margin-bottom: 0.35rem; }
.stat-num { font-size: 1.25rem; font-weight: 700; color: var(--text); letter-spacing: -0.02em; line-height: 1; margin-bottom: 0.45rem; }
.stat-bar-bg { height: 3px; background: var(--border); border-radius: 2px; overflow: hidden; }
.stat-bar-fill { height: 100%; border-radius: 2px; background: linear-gradient(90deg, var(--accent), var(--gold)); }

/* Weakness */
.weakness-block {
  display: flex;
  gap: 0.75rem;
  align-items: flex-start;
  padding: 0.9rem 1rem;
  background: rgba(239,68,68,0.05);
  border: 1px solid rgba(239,68,68,0.2);
  border-radius: var(--radius);
}
.weakness-icon { font-size: 1rem; line-height: 1.5; flex-shrink: 0; }
.weakness-text { font-size: 0.85rem; color: var(--text2); line-height: 1.7; }

/* Action row */
.result-actions {
  display: flex;
  gap: 0.5rem;
  margin-top: 1rem;
}
.btn-outline {
  display: inline-flex; align-items: center; gap: 0.4rem;
  padding: 0.55rem 1rem;
  background: transparent;
  border: 1px solid var(--border2);
  border-radius: var(--radius);
  color: var(--text3);
  font-family: 'Inter', 'Noto Sans JP', sans-serif;
  font-size: 0.8rem;
  font-weight: 500;
  cursor: pointer;
  transition: all 0.15s;
}
.btn-outline:hover { border-color: var(--accent); color: var(--accent-l); background: rgba(139,92,246,0.06); }

@media (max-width: 580px) {
  .field-row, .field-row-3 { grid-template-columns: 1fr; }
  .field-row .field:first-child { border-right: none; border-bottom: 1px solid var(--border); }
  .field-row-3 .field:nth-child(2) { border: none; border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); }
  .stats-grid { grid-template-columns: repeat(2, 1fr); }
  .rank-grid { flex-wrap: wrap; }
  .rank-btn { flex: 0 0 calc(33% - 0.4rem); }
  h1 { font-size: 1.6rem; }
}
</style>
</head>
<body>

<!-- Loading -->
<div id="loading">
  <div class="loader-ring"></div>
  <div class="loader-text">術式を構築中…</div>
</div>

<!-- Nav -->
<nav>
  <div class="nav-logo">
    <div class="nav-logo-icon">⚡</div>
    Jutsu Forge
  </div>
  <span class="nav-badge">Beta</span>
  <div class="nav-spacer"></div>
  <span style="font-size:0.75rem;color:var(--text4);">呪術廻戦 × AI 術式ジェネレーター</span>
</nav>

<!-- Hero -->
<div class="hero">
  <div class="hero-eyebrow">Powered by Claude AI</div>
  <h1>オリジナル<em>術式</em>を<br>今すぐ開発しよう</h1>
  <p class="hero-desc">コンセプトを入力するだけで、呪術廻戦の世界観に沿ったオリジナル術式・技・領域展開をAIが自動生成します。</p>
</div>

<!-- Form -->
<div class="main">

  <div class="section-heading"><div class="section-num">1</div> 術師プロフィール</div>
  <div class="field-group">
    <div class="field-row">
      <div class="field">
        <label>術師の名前</label>
        <input type="text" id="name" placeholder="黒羽 玄夜">
      </div>
      <div class="field">
        <label>術師のイメージ</label>
        <input type="text" id="vibe" placeholder="冷静・孤独・闇に生きる">
      </div>
    </div>
  </div>

  <div class="section-heading"><div class="section-num">2</div> 術式コンセプト</div>
  <div class="field-group">
    <div class="field">
      <label>着想・テーマ <span class="label-required">必須</span></label>
      <textarea id="concept" placeholder="例：「時間」をテーマにした術式。過去の出来事を呼び起こし攻撃に転換する。"></textarea>
    </div>
    <div class="tag-field">
      <label>タイプ（複数選択可）</label>
      <div class="tag-wrap" id="type-tags">
        <span class="tag" data-val="攻撃型">⚔ 攻撃型</span>
        <span class="tag" data-val="防御型">🛡 防御型</span>
        <span class="tag" data-val="補助型">🌀 補助型</span>
        <span class="tag" data-val="束縛型">⛓ 束縛型</span>
        <span class="tag" data-val="変容型">🧬 変容型</span>
        <span class="tag" data-val="結界型">🔮 結界型</span>
        <span class="tag" data-val="式神型">👁 式神型</span>
        <span class="tag" data-val="反転型">♾ 反転型</span>
        <span class="tag" data-val="操作型">🧠 操作型</span>
      </div>
    </div>
    <div class="tag-field">
      <label>属性（複数選択可）</label>
      <div class="tag-wrap" id="element-tags">
        <span class="tag" data-val="炎">🔥 炎</span>
        <span class="tag" data-val="水・氷">💧 水・氷</span>
        <span class="tag" data-val="雷">⚡ 雷</span>
        <span class="tag" data-val="闇・影">🌑 闇・影</span>
        <span class="tag" data-val="光・空間">✨ 光・空間</span>
        <span class="tag" data-val="血・肉体">🩸 血・肉体</span>
        <span class="tag" data-val="時間">⏳ 時間</span>
        <span class="tag" data-val="音・言葉">🎵 音・言葉</span>
        <span class="tag" data-val="金属">⚙ 金属</span>
        <span class="tag" data-val="自然・植物">🌿 自然・植物</span>
        <span class="tag" data-val="死・骨">💀 死・骨</span>
        <span class="tag" data-val="幻・夢">🌙 幻・夢</span>
      </div>
    </div>
  </div>

  <div class="section-heading"><div class="section-num">3</div> 強さ設定</div>
  <div class="field-group">
    <div class="rank-field">
      <label>呪術師等級</label>
      <div class="rank-grid">
        <div class="rank-btn" data-rank="4級" onclick="selectRank(this,'4級')">4級</div>
        <div class="rank-btn" data-rank="3級" onclick="selectRank(this,'3級')">3級</div>
        <div class="rank-btn" data-rank="2級" onclick="selectRank(this,'2級')">2級</div>
        <div class="rank-btn" data-rank="1級" onclick="selectRank(this,'1級')">1級</div>
        <div class="rank-btn" data-rank="特級" onclick="selectRank(this,'特級')">特級</div>
      </div>
    </div>
    <div class="field-row-3 field-row">
      <div class="field">
        <label>得意面</label>
        <input type="text" id="strength_point" placeholder="範囲攻撃">
      </div>
      <div class="field">
        <label>弱点</label>
        <input type="text" id="weakness_point" placeholder="近距離戦">
      </div>
      <div class="field">
        <label>参考キャラ</label>
        <input type="text" id="reference" placeholder="五条悟、伏黒恵">
      </div>
    </div>
  </div>

  <div class="section-heading"><div class="section-num">4</div> 追加要望 <span style="font-size:0.65rem;color:var(--text4);font-weight:400;letter-spacing:0;">(任意)</span></div>
  <div class="field-group">
    <div class="field">
      <label>自由記述</label>
      <textarea id="extra" style="min-height:60px;" placeholder="例：領域展開は必ず入れてほしい。術式名は漢字4文字で。既存術式と組み合わせた派生技を入れてほしい。"></textarea>
    </div>
  </div>

  <div class="submit-wrap">
    <button class="submit-btn" onclick="generateJutsu()">
      <svg viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.8">
        <path d="M8 1v14M1 8l7-7 7 7" stroke-linecap="round" stroke-linejoin="round"/>
      </svg>
      術式を生成する
    </button>
  </div>
  <div class="error-box" id="error-box"></div>

  <!-- Result -->
  <div id="result-section">
    <div class="section-heading" style="margin-top:2.5rem;"><div class="section-num">✦</div> 生成された術式</div>

    <div class="result-card">
      <div class="result-header">
        <div id="res-flavor" class="result-flavor" style="display:none;"></div>
        <div class="result-title-row">
          <div>
            <div class="result-name" id="res-name"></div>
            <div class="result-reading" id="res-reading"></div>
          </div>
        </div>
        <div class="result-badges" id="res-badges"></div>
      </div>

      <div class="result-body">
        <div class="res-block">
          <div class="res-block-label">Concept</div>
          <div class="res-block-text" id="res-concept"></div>
        </div>
        <div class="res-block">
          <div class="res-block-label">Ability</div>
          <div class="res-block-text" id="res-ability"></div>
        </div>
        <div class="res-block">
          <div class="res-block-label">Techniques</div>
          <div class="tech-list" id="res-techs"></div>
        </div>
        <div class="res-block" id="res-domain-block" style="display:none;">
          <div class="res-block-label">領域展開</div>
          <div class="domain-block">
            <div class="domain-name-text" id="res-domain-name"></div>
            <div class="domain-desc-text" id="res-domain-desc"></div>
          </div>
        </div>
        <div class="res-block">
          <div class="res-block-label">Stats</div>
          <div class="stats-grid" id="res-stats"></div>
        </div>
        <div class="res-block">
          <div class="res-block-label">Weakness & Cost</div>
          <div class="weakness-block">
            <div class="weakness-icon">⚠️</div>
            <div class="weakness-text" id="res-weakness"></div>
          </div>
        </div>
      </div>
    </div>

    <div class="result-actions">
      <button class="btn-outline" onclick="copyResult()">
        <svg width="13" height="13" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="5" y="5" width="9" height="9" rx="2"/><path d="M3 11H2a1 1 0 01-1-1V2a1 1 0 011-1h8a1 1 0 011 1v1" stroke-linecap="round"/></svg>
        結果をコピー
      </button>
      <button class="btn-outline" onclick="resetForm()">
        <svg width="13" height="13" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M1 4h10a4 4 0 010 8H1" stroke-linecap="round"/><path d="M4 1L1 4l3 3" stroke-linecap="round" stroke-linejoin="round"/></svg>
        もう一度作る
      </button>
    </div>
  </div>

</div>

<script>
let selectedRank = '1級';
let selectedTypes = new Set();
let selectedElements = new Set();

document.querySelectorAll('.tag').forEach(t => {
  t.addEventListener('click', () => {
    const inType = !!t.closest('#type-tags');
    const val = t.dataset.val;
    const set = inType ? selectedTypes : selectedElements;
    if (t.classList.toggle('active')) set.add(val); else set.delete(val);
  });
});

function selectRank(el, rank) {
  selectedRank = rank;
  const cls = {'4級':'r4','3級':'r3','2級':'r2','1級':'r1','特級':'r0'};
  document.querySelectorAll('.rank-btn').forEach(b => {
    b.className = 'rank-btn';
    if (b.dataset.rank === rank) b.classList.add(cls[rank]);
  });
}
selectRank(document.querySelector('[data-rank="1級"]'), '1級');

async function generateJutsu() {
  const name    = document.getElementById('name').value.trim();
  const vibe    = document.getElementById('vibe').value.trim();
  const concept = document.getElementById('concept').value.trim();
  const types   = [...selectedTypes].join('、');
  const elems   = [...selectedElements].join('、');
  const sp      = document.getElementById('strength_point').value.trim();
  const wp      = document.getElementById('weakness_point').value.trim();
  const ref     = document.getElementById('reference').value.trim();
  const extra   = document.getElementById('extra').value.trim();
  const errEl   = document.getElementById('error-box');
  errEl.classList.remove('show');

  if (!concept) {
    errEl.textContent = '術式のコンセプト（着想・テーマ）を入力してください。';
    errEl.classList.add('show');
    return;
  }

  document.getElementById('loading').classList.add('on');
  document.querySelector('.submit-btn').disabled = true;
  document.getElementById('result-section').classList.remove('show');

  const sys = `あなたは呪術廻戦の術式デザイナーです。呪術廻戦の世界観（呪力=負の感情エネルギー、生得術式、領域展開、反転術式）を熟知しています。
主要術式：五条悟=無下限呪術(蒼・赫・茈)、宿儺=解・捌・御廚子、伏黒=十種影法術、釘崎=芻零呪法、七海=十劃呪法、夏油=呪霊操術、真人=無為転変。
JSON形式のみで返答。前置き・後置き不要。各文字列は簡潔に：
{"jutsu_name":"術式名","jutsu_reading":"読み","jutsu_concept":"概念(60字以内)","jutsu_description":"詳細(80字以内)","techniques":[{"name":"技名","reading":"読み","description":"説明(50字以内)"},{"name":"技名","reading":"読み","description":"説明(50字以内)"},{"name":"技名","reading":"読み","description":"説明(50字以内)"}],"domain_name":"領域展開名","domain_reading":"読み","domain_description":"説明(80字以内)","stats":{"attack":0,"defense":0,"speed":0,"range":0,"versatility":0,"curse_output":0},"weakness":"弱点(50字以内)","flavor_text":"格言(25字以内)"}`;

  const usr = `術師名：${name||'未設定'} イメージ：${vibe||'未設定'}
コンセプト：${concept}
タイプ：${types||'指定なし'} 属性：${elems||'指定なし'}
等級：${selectedRank} 得意：${sp||'指定なし'} 弱点：${wp||'指定なし'}
参考：${ref||'指定なし'} 要望：${extra||'特になし'}`;

  try {
    const res  = await fetch('/.netlify/functions/generate', {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({
        system: sys,
        messages: [{ role: 'user', content: usr }]
      })
    });
    const data  = await res.json();
    const text  = data.content?.find(b => b.type === 'text')?.text || '';
    const clean = text.replace(/```json|```/g, '').trim();
    const d     = JSON.parse(clean);
    renderResult(d, name, selectedRank);
    document.getElementById('result-section').classList.add('show');
    setTimeout(() => document.getElementById('result-section').scrollIntoView({ behavior: 'smooth', block: 'start' }), 100);
  } catch(e) {
    errEl.textContent = '生成に失敗しました。再度お試しください。(' + e.message + ')';
    errEl.classList.add('show');
  } finally {
    document.getElementById('loading').classList.remove('on');
    document.querySelector('.submit-btn').disabled = false;
  }
}

function renderResult(d, name, rank) {
  // Flavor
  const flavorEl = document.getElementById('res-flavor');
  if (d.flavor_text) { flavorEl.textContent = '"' + d.flavor_text + '"'; flavorEl.style.display = ''; }
  else flavorEl.style.display = 'none';

  // Title
  document.getElementById('res-name').textContent = d.jutsu_name;
  document.getElementById('res-reading').textContent =
    '（' + d.jutsu_reading + '）' + (name ? '　使用者：' + name : '');

  // Badges
  const rc = {'特級':'b-rank-特級','1級':'b-rank-1級','2級':'b-rank-2級','3級':'b-rank-3級','4級':'b-rank-4級'}[rank]||'b-rank-1級';
  document.getElementById('res-badges').innerHTML =
    `<span class="badge b-type">生得術式</span><span class="badge ${rc}">${rank}</span>`;

  // Text blocks
  document.getElementById('res-concept').textContent = d.jutsu_concept;
  document.getElementById('res-ability').textContent  = d.jutsu_description;

  // Techniques
  document.getElementById('res-techs').innerHTML = (d.techniques||[]).map(t =>
    `<div class="tech-item">
       <div class="tech-name">「${t.name}」<span>（${t.reading}）</span></div>
       <div class="tech-desc">${t.description}</div>
     </div>`).join('');

  // Domain
  const db = document.getElementById('res-domain-block');
  if (d.domain_name) {
    document.getElementById('res-domain-name').innerHTML =
      `「${d.domain_name}」<span>（${d.domain_reading||''}）</span>`;
    document.getElementById('res-domain-desc').textContent = d.domain_description;
    db.style.display = '';
  } else db.style.display = 'none';

  // Stats
  const labels = { attack:'攻撃力', defense:'防御力', speed:'速度', range:'射程', versatility:'汎用性', curse_output:'呪力出力' };
  document.getElementById('res-stats').innerHTML = Object.entries(d.stats||{}).map(([k,v]) =>
    `<div class="stat-card">
       <div class="stat-label-t">${labels[k]||k}</div>
       <div class="stat-num">${v}</div>
       <div class="stat-bar-bg"><div class="stat-bar-fill" style="width:${v}%"></div></div>
     </div>`).join('');

  // Weakness
  document.getElementById('res-weakness').textContent = d.weakness;

  // Save for copy
  window._copyText = [
    `【術式名】${d.jutsu_name}（${d.jutsu_reading}）`,
    `【等級】${rank}`,
    `【概念】${d.jutsu_concept}`,
    `【能力】${d.jutsu_description}`,
    ...(d.techniques||[]).map(t=>`【技】${t.name}（${t.reading}）：${t.description}`),
    d.domain_name?`【領域展開】${d.domain_name}（${d.domain_reading}）：${d.domain_description}`:'',
    `【弱点】${d.weakness}`,
    d.flavor_text?`【格言】"${d.flavor_text}"`:'',
  ].filter(Boolean).join('\n');
}

function copyResult() {
  if (!window._copyText) return;
  navigator.clipboard.writeText(window._copyText).then(() => {
    const b = document.querySelector('.result-actions .btn-outline');
    b.textContent = '✓ コピーしました';
    setTimeout(() => b.innerHTML = `<svg width="13" height="13" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="5" y="5" width="9" height="9" rx="2"/><path d="M3 11H2a1 1 0 01-1-1V2a1 1 0 011-1h8a1 1 0 011 1v1" stroke-linecap="round"/></svg> 結果をコピー`, 2000);
  });
}

function resetForm() {
  document.getElementById('result-section').classList.remove('show');
  window.scrollTo({ top: 0, behavior: 'smooth' });
}
</script>
</body>
</html>
