<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Forex Scalping Calculator</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700;900&family=Rajdhani:wght@400;500;600;700&display=swap');

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: #0a0e1a;
    color: #e0e0e0;
    font-family: 'Rajdhani', sans-serif;
    min-height: 100vh;
    background-image:
      radial-gradient(ellipse at 20% 50%, rgba(0,255,150,0.04) 0%, transparent 50%),
      radial-gradient(ellipse at 80% 20%, rgba(0,180,255,0.04) 0%, transparent 50%);
  }

  header {
    background: linear-gradient(90deg, #0d1117, #0d2a1a, #0d1117);
    border-bottom: 1px solid #00ff9620;
    padding: 16px 24px;
    display: flex;
    align-items: center;
    gap: 14px;
  }

  header .logo {
    font-family: 'Orbitron', monospace;
    font-size: 1.3rem;
    font-weight: 900;
    color: #00ff96;
    text-shadow: 0 0 20px #00ff9660;
    letter-spacing: 2px;
  }

  header .sub {
    font-size: 0.85rem;
    color: #888;
    letter-spacing: 1px;
  }

  .badge {
    margin-left: auto;
    background: linear-gradient(135deg, #00ff96, #00c8ff);
    color: #0a0e1a;
    font-size: 0.7rem;
    font-weight: 700;
    padding: 4px 10px;
    border-radius: 20px;
    letter-spacing: 1px;
  }

  .container {
    max-width: 1100px;
    margin: 0 auto;
    padding: 24px 16px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }

  @media (max-width: 750px) {
    .container { grid-template-columns: 1fr; }
  }

  .card {
    background: #0d1117;
    border: 1px solid #1a2a20;
    border-radius: 16px;
    padding: 22px;
    position: relative;
    overflow: hidden;
  }

  .card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
    background: linear-gradient(90deg, transparent, #00ff96, transparent);
  }

  .card.blue::before { background: linear-gradient(90deg, transparent, #00c8ff, transparent); }
  .card.orange::before { background: linear-gradient(90deg, transparent, #ff9900, transparent); }
  .card.red::before { background: linear-gradient(90deg, transparent, #ff4466, transparent); }

  .card-title {
    font-family: 'Orbitron', monospace;
    font-size: 0.75rem;
    color: #00ff96;
    letter-spacing: 2px;
    margin-bottom: 18px;
    display: flex;
    align-items: center;
    gap: 8px;
  }

  .card.blue .card-title { color: #00c8ff; }
  .card.orange .card-title { color: #ff9900; }
  .card.red .card-title { color: #ff4466; }

  .card-title .icon { font-size: 1rem; }

  .form-group {
    margin-bottom: 14px;
  }

  label {
    display: block;
    font-size: 0.8rem;
    color: #888;
    margin-bottom: 6px;
    letter-spacing: 0.5px;
    text-transform: uppercase;
  }

  input, select {
    width: 100%;
    background: #161b22;
    border: 1px solid #2a3a30;
    border-radius: 8px;
    padding: 10px 14px;
    color: #e0e0e0;
    font-family: 'Rajdhani', sans-serif;
    font-size: 1rem;
    outline: none;
    transition: border-color 0.2s, box-shadow 0.2s;
  }

  input:focus, select:focus {
    border-color: #00ff9660;
    box-shadow: 0 0 0 3px #00ff9615;
  }

  select option { background: #161b22; }

  .btn {
    width: 100%;
    padding: 13px;
    border: none;
    border-radius: 10px;
    font-family: 'Orbitron', monospace;
    font-size: 0.85rem;
    font-weight: 700;
    letter-spacing: 1px;
    cursor: pointer;
    margin-top: 6px;
    transition: all 0.2s;
  }

  .btn-green {
    background: linear-gradient(135deg, #00ff96, #00c8a0);
    color: #0a0e1a;
    box-shadow: 0 4px 20px #00ff9630;
  }

  .btn-green:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 28px #00ff9650;
  }

  .btn-blue {
    background: linear-gradient(135deg, #00c8ff, #0080cc);
    color: #0a0e1a;
    box-shadow: 0 4px 20px #00c8ff30;
  }

  .btn-blue:hover { transform: translateY(-2px); box-shadow: 0 6px 28px #00c8ff50; }

  .btn-orange {
    background: linear-gradient(135deg, #ff9900, #ff6600);
    color: #0a0e1a;
    box-shadow: 0 4px 20px #ff990030;
  }

  .btn-orange:hover { transform: translateY(-2px); }

  .result-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
    margin-top: 16px;
  }

  .result-item {
    background: #161b22;
    border: 1px solid #1a2a20;
    border-radius: 10px;
    padding: 12px;
    text-align: center;
  }

  .result-item .r-label {
    font-size: 0.7rem;
    color: #666;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    margin-bottom: 4px;
  }

  .result-item .r-value {
    font-family: 'Orbitron', monospace;
    font-size: 1.1rem;
    font-weight: 700;
    color: #00ff96;
  }

  .result-item.blue .r-value { color: #00c8ff; }
  .result-item.orange .r-value { color: #ff9900; }
  .result-item.red .r-value { color: #ff4466; }
  .result-item.white .r-value { color: #fff; }

  .divider {
    height: 1px;
    background: linear-gradient(90deg, transparent, #1a2a20, transparent);
    margin: 16px 0;
  }

  .pip-table {
    width: 100%;
    border-collapse: collapse;
    font-size: 0.85rem;
  }

  .pip-table th {
    background: #161b22;
    color: #00ff96;
    padding: 8px 10px;
    text-align: left;
    font-size: 0.7rem;
    letter-spacing: 1px;
    text-transform: uppercase;
  }

  .pip-table td {
    padding: 8px 10px;
    border-bottom: 1px solid #1a2a2010;
    color: #ccc;
  }

  .pip-table tr:hover td { background: #161b2240; }

  .rr-bar {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-top: 10px;
  }

  .rr-loss { flex: 1; height: 12px; background: #ff446650; border-radius: 6px 0 0 6px; position: relative; }
  .rr-profit { flex: 1; height: 12px; background: #00ff9650; border-radius: 0 6px 6px 0; position: relative; }
  .rr-label { font-size: 0.75rem; color: #888; white-space: nowrap; }

  .signal-box {
    border-radius: 10px;
    padding: 14px;
    text-align: center;
    margin-top: 10px;
  }

  .signal-buy { background: #00ff9610; border: 1px solid #00ff9640; }
  .signal-sell { background: #ff446610; border: 1px solid #ff446640; }

  .signal-text {
    font-family: 'Orbitron', monospace;
    font-size: 1.2rem;
    font-weight: 900;
    letter-spacing: 3px;
  }

  .signal-buy .signal-text { color: #00ff96; }
  .signal-sell .signal-text { color: #ff4466; }

  .full-width { grid-column: 1 / -1; }

  .sessions {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin-top: 10px;
  }

  .session-chip {
    padding: 6px 14px;
    border-radius: 20px;
    font-size: 0.75rem;
    font-weight: 600;
    letter-spacing: 0.5px;
    cursor: pointer;
    border: 1px solid transparent;
    transition: all 0.2s;
  }

  .session-chip.active-session { border-color: #00ff96; color: #00ff96; background: #00ff9615; }
  .session-chip.london { border-color: #00c8ff60; color: #00c8ff; background: #00c8ff10; }
  .session-chip.newyork { border-color: #ff990060; color: #ff9900; background: #ff990010; }
  .session-chip.tokyo { border-color: #ff446660; color: #ff4466; background: #ff446610; }
  .session-chip.sydney { border-color: #aa88ff60; color: #aa88ff; background: #aa88ff10; }

  .trade-log {
    max-height: 220px;
    overflow-y: auto;
  }

  .trade-log::-webkit-scrollbar { width: 4px; }
  .trade-log::-webkit-scrollbar-thumb { background: #2a3a30; border-radius: 4px; }

  .trade-row {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 8px 10px;
    border-radius: 8px;
    margin-bottom: 6px;
    background: #161b22;
    font-size: 0.85rem;
    animation: fadeIn 0.3s ease;
  }

  @keyframes fadeIn { from { opacity: 0; transform: translateY(-6px); } to { opacity: 1; transform: translateY(0); } }

  .trade-type {
    font-family: 'Orbitron', monospace;
    font-size: 0.7rem;
    font-weight: 700;
    padding: 2px 8px;
    border-radius: 4px;
    min-width: 44px;
    text-align: center;
  }

  .buy-tag { background: #00ff9620; color: #00ff96; }
  .sell-tag { background: #ff446620; color: #ff4466; }

  .pnl-pos { color: #00ff96; font-weight: 700; }
  .pnl-neg { color: #ff4466; font-weight: 700; }

  .empty-state {
    text-align: center;
    color: #444;
    padding: 30px;
    font-size: 0.9rem;
  }

  .stats-row {
    display: flex;
    gap: 10px;
    margin-top: 12px;
  }

  .stat-box {
    flex: 1;
    background: #161b22;
    border-radius: 10px;
    padding: 10px;
    text-align: center;
    border: 1px solid #1a2a20;
  }

  .stat-box .s-label { font-size: 0.65rem; color: #666; text-transform: uppercase; letter-spacing: 0.5px; }
  .stat-box .s-value { font-family: 'Orbitron', monospace; font-size: 0.95rem; font-weight: 700; color: #fff; margin-top: 2px; }

  input[type=range] {
    -webkit-appearance: none;
    height: 6px;
    background: #1a2a20;
    border-radius: 3px;
    border: none;
    padding: 0;
    cursor: pointer;
  }

  input[type=range]::-webkit-slider-thumb {
    -webkit-appearance: none;
    width: 16px; height: 16px;
    border-radius: 50%;
    background: #00ff96;
    cursor: pointer;
    box-shadow: 0 0 8px #00ff9660;
  }
</style>
</head>
<body>

<header>
  <div>
    <div class="logo">⚡ SCALP PRO</div>
    <div class="sub">FOREX · INTRADAY · SCALPING CALCULATOR</div>
  </div>
  <div class="badge">LIVE TOOL</div>
</header>

<div class="container">

  <!-- POSITION SIZE CALCULATOR -->
  <div class="card">
    <div class="card-title"><span class="icon">📐</span> POSITION SIZE CALCULATOR</div>

    <div class="form-group">
      <label>Currency Pair</label>
      <select id="pair">
        <option value="EURUSD">EUR/USD</option>
        <option value="GBPUSD">GBP/USD</option>
        <option value="USDJPY">USD/JPY</option>
        <option value="USDCHF">USD/CHF</option>
        <option value="AUDUSD">AUD/USD</option>
        <option value="USDCAD">USD/CAD</option>
        <option value="GBPJPY">GBP/JPY</option>
        <option value="EURJPY">EUR/JPY</option>
      </select>
    </div>

    <div class="form-group">
      <label>Account Balance ($)</label>
      <input type="number" id="balance" value="10000" min="100" />
    </div>

    <div class="form-group">
      <label>Risk Per Trade: <span id="riskLabel" style="color:#00ff96">1%</span></label>
      <input type="range" id="riskPct" min="0.5" max="5" step="0.5" value="1"
        oninput="document.getElementById('riskLabel').textContent=this.value+'%'; calcPosition();" />
    </div>

    <div class="form-group">
      <label>Stop Loss (Pips)</label>
      <input type="number" id="slPips" value="5" min="1" />
    </div>

    <div class="form-group">
      <label>Take Profit (Pips)</label>
      <input type="number" id="tpPips" value="10" min="1" />
    </div>

    <button class="btn btn-green" onclick="calcPosition()">CALCULATE POSITION</button>

    <div class="result-grid" id="posResult" style="display:none">
      <div class="result-item">
        <div class="r-label">Lot Size</div>
        <div class="r-value" id="lotSize">—</div>
      </div>
      <div class="result-item blue">
        <div class="r-label">Risk Amount</div>
        <div class="r-value" id="riskAmt">—</div>
      </div>
      <div class="result-item orange">
        <div class="r-label">Pip Value</div>
        <div class="r-value" id="pipVal">—</div>
      </div>
      <div class="result-item white">
        <div class="r-label">R:R Ratio</div>
        <div class="r-value" id="rrRatio">—</div>
      </div>
    </div>

    <div id="rrBarDiv" style="display:none">
      <div class="divider"></div>
      <div style="font-size:0.75rem;color:#666;margin-bottom:6px;">RISK / REWARD VISUAL</div>
      <div class="rr-bar">
        <div class="rr-label" id="rrLoss">—</div>
        <div class="rr-loss" id="rrLossBar"></div>
        <div class="rr-profit" id="rrProfitBar"></div>
        <div class="rr-label" id="rrProfit">—</div>
      </div>
    </div>
  </div>

  <!-- SCALPING SIGNAL GENERATOR -->
  <div class="card blue">
    <div class="card-title"><span class="icon">🎯</span> SCALPING SIGNAL ANALYZER</div>

    <div class="form-group">
      <label>Entry Price</label>
      <input type="number" id="entryPrice" value="1.08500" step="0.00001" />
    </div>

    <div class="form-group">
      <label>Current RSI (1-100)</label>
      <input type="number" id="rsi" value="45" min="1" max="100" />
    </div>

    <div class="form-group">
      <label>EMA 9 Value</label>
      <input type="number" id="ema9" value="1.08490" step="0.00001" />
    </div>

    <div class="form-group">
      <label>EMA 21 Value</label>
      <input type="number" id="ema21" value="1.08460" step="0.00001" />
    </div>

    <div class="form-group">
      <label>Spread (Pips)</label>
      <input type="number" id="spread" value="1" step="0.1" min="0" />
    </div>

    <button class="btn btn-blue" onclick="analyzeSignal()">ANALYZE SIGNAL</button>

    <div id="signalResult" style="display:none">
      <div class="signal-box" id="signalBox">
        <div class="signal-text" id="signalText">—</div>
        <div id="signalDesc" style="font-size:0.8rem;color:#888;margin-top:6px;"></div>
      </div>

      <div class="result-grid" style="margin-top:10px;">
        <div class="result-item">
          <div class="r-label">Stop Loss</div>
          <div class="r-value" id="sigSL" style="font-size:0.9rem;">—</div>
        </div>
        <div class="result-item blue">
          <div class="r-label">Take Profit</div>
          <div class="r-value" id="sigTP" style="font-size:0.9rem;color:#00c8ff">—</div>
        </div>
      </div>
    </div>
  </div>

  <!-- PIP VALUE TABLE -->
  <div class="card orange">
    <div class="card-title"><span class="icon">📊</span> PIP VALUE REFERENCE TABLE</div>

    <div class="form-group">
      <label>Account Currency</label>
      <select id="accCurr">
        <option value="USD">USD</option>
        <option value="EUR">EUR</option>
        <option value="GBP">GBP</option>
        <option value="INR">INR</option>
      </select>
    </div>

    <div class="form-group">
      <label>Lot Size</label>
      <select id="lotType">
        <option value="100000">Standard (1.00)</option>
        <option value="10000">Mini (0.10)</option>
        <option value="1000" selected>Micro (0.01)</option>
      </select>
    </div>

    <button class="btn btn-orange" onclick="buildPipTable()">SHOW PIP VALUES</button>

    <div style="margin-top:14px;overflow-x:auto;">
      <table class="pip-table">
        <thead>
          <tr>
            <th>Pair</th>
            <th>Pip Size</th>
            <th>Pip Value</th>
            <th>10 Pips</th>
          </tr>
        </thead>
        <tbody id="pipTableBody">
          <tr><td colspan="4" style="color:#444;text-align:center;padding:16px;">Click button above ↑</td></tr>
        </tbody>
      </table>
    </div>
  </div>

  <!-- TRADE JOURNAL -->
  <div class="card red">
    <div class="card-title"><span class="icon">📓</span> TRADE JOURNAL & P&L TRACKER</div>

    <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;">
      <div class="form-group">
        <label>Trade Type</label>
        <select id="tradeType">
          <option value="BUY">BUY</option>
          <option value="SELL">SELL</option>
        </select>
      </div>
      <div class="form-group">
        <label>Pair</label>
        <select id="tradePair">
          <option>EUR/USD</option>
          <option>GBP/USD</option>
          <option>USD/JPY</option>
          <option>AUD/USD</option>
          <option>USD/CHF</option>
          <option>GBP/JPY</option>
        </select>
      </div>
    </div>

    <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;">
      <div class="form-group">
        <label>Entry Price</label>
        <input type="number" id="jEntry" step="0.00001" value="1.08500" />
      </div>
      <div class="form-group">
        <label>Exit Price</label>
        <input type="number" id="jExit" step="0.00001" value="1.08600" />
      </div>
    </div>

    <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;">
      <div class="form-group">
        <label>Lot Size</label>
        <input type="number" id="jLot" step="0.01" value="0.10" min="0.01" />
      </div>
      <div class="form-group">
        <label>Time</label>
        <input type="time" id="jTime" />
      </div>
    </div>

    <button class="btn btn-green" style="background:linear-gradient(135deg,#ff4466,#cc2244);box-shadow:0 4px 20px #ff446630;" onclick="logTrade()">LOG TRADE</button>

    <div class="divider"></div>

    <div class="stats-row" id="journalStats">
      <div class="stat-box">
        <div class="s-label">Total Trades</div>
        <div class="s-value" id="totalTrades">0</div>
      </div>
      <div class="stat-box">
        <div class="s-label">Win Rate</div>
        <div class="s-value" id="winRate" style="color:#00ff96">0%</div>
      </div>
      <div class="stat-box">
        <div class="s-label">Total P&L</div>
        <div class="s-value" id="totalPnl">$0</div>
      </div>
    </div>

    <div class="divider"></div>
    <div style="font-size:0.7rem;color:#666;margin-bottom:8px;text-transform:uppercase;letter-spacing:1px;">Recent Trades</div>
    <div class="trade-log" id="tradeLog">
      <div class="empty-state">No trades logged yet.<br/>Start scalping! 🚀</div>
    </div>
  </div>

  <!-- SESSION CLOCK -->
  <div class="card full-width">
    <div class="card-title"><span class="icon">🕐</span> FOREX SESSION TRACKER (IST)</div>
    <div style="display:flex;align-items:center;gap:16px;flex-wrap:wrap;">
      <div>
        <div style="font-size:0.75rem;color:#666;text-transform:uppercase;margin-bottom:4px;">Current IST Time</div>
        <div id="clockDisplay" style="font-family:'Orbitron',monospace;font-size:1.6rem;color:#fff;font-weight:700;">--:--:--</div>
      </div>
      <div class="sessions" id="sessionChips" style="flex:1;">
        <div class="session-chip tokyo" id="chip-tokyo">🇯🇵 Tokyo</div>
        <div class="session-chip london" id="chip-london">🇬🇧 London</div>
        <div class="session-chip newyork" id="chip-newyork">🗽 New York</div>
        <div class="session-chip sydney" id="chip-sydney">🇦🇺 Sydney</div>
      </div>
    </div>
    <div style="margin-top:14px;font-size:0.8rem;color:#555;line-height:1.8;">
      <span style="color:#ff4466;font-weight:600;">Tokyo:</span> 5:30 AM – 2:30 PM IST &nbsp;|&nbsp;
      <span style="color:#00c8ff;font-weight:600;">London:</span> 1:30 PM – 10:30 PM IST &nbsp;|&nbsp;
      <span style="color:#ff9900;font-weight:600;">New York:</span> 6:30 PM – 1:30 AM IST &nbsp;|&nbsp;
      <span style="color:#aa88ff;font-weight:600;">Sydney:</span> 4:00 AM – 1:00 PM IST
    </div>
    <div style="margin-top:8px;padding:10px 14px;background:#00ff9610;border:1px solid #00ff9630;border-radius:8px;font-size:0.82rem;color:#00ff96;" id="sessionTip">
      💡 Best scalping time: <strong>London-NY Overlap</strong> (6:30 PM – 10:30 PM IST) — highest liquidity & volatility!
    </div>
  </div>

</div>

<script>
// ─── TRADE LOG DATA ───────────────────────────────────────────
let trades = [];

// ─── POSITION SIZE CALCULATOR ─────────────────────────────────
function calcPosition() {
  const balance = parseFloat(document.getElementById('balance').value) || 10000;
  const risk = parseFloat(document.getElementById('riskPct').value) / 100;
  const sl = parseFloat(document.getElementById('slPips').value) || 5;
  const tp = parseFloat(document.getElementById('tpPips').value) || 10;
  const pair = document.getElementById('pair').value;

  const riskAmt = balance * risk;
  const isJPY = pair.includes('JPY');
  const pipValue = isJPY ? 0.001 : 0.0001;
  const standardPipValue = isJPY ? 1000 : 10; // per standard lot

  const lotSize = riskAmt / (sl * standardPipValue);
  const pipVal = lotSize * standardPipValue;
  const rr = (tp / sl).toFixed(2);

  document.getElementById('lotSize').textContent = lotSize.toFixed(2);
  document.getElementById('riskAmt').textContent = '$' + riskAmt.toFixed(2);
  document.getElementById('pipVal').textContent = '$' + pipVal.toFixed(2);
  document.getElementById('rrRatio').textContent = '1:' + rr;

  document.getElementById('posResult').style.display = 'grid';
  document.getElementById('rrBarDiv').style.display = 'block';

  // RR bar visual
  const total = sl + tp;
  const lossPct = Math.round((sl / total) * 100);
  const profitPct = 100 - lossPct;
  document.getElementById('rrLossBar').style.flex = sl;
  document.getElementById('rrProfitBar').style.flex = tp;
  document.getElementById('rrLoss').textContent = '-$' + riskAmt.toFixed(0);
  document.getElementById('rrProfit').textContent = '+$' + (riskAmt * rr).toFixed(0);
}

// ─── SIGNAL ANALYZER ─────────────────────────────────────────
function analyzeSignal() {
  const entry = parseFloat(document.getElementById('entryPrice').value);
  const rsi = parseFloat(document.getElementById('rsi').value);
  const ema9 = parseFloat(document.getElementById('ema9').value);
  const ema21 = parseFloat(document.getElementById('ema21').value);
  const spread = parseFloat(document.getElementById('spread').value) * 0.0001;
  const pair = document.getElementById('pair') ? document.getElementById('pair').value : 'EURUSD';
  const isJPY = pair.includes('JPY');
  const pip = isJPY ? 0.01 : 0.0001;

  let signal = 'NEUTRAL';
  let desc = '';
  let score = 0;

  if (ema9 > ema21) score++;
  if (ema9 < ema21) score--;
  if (rsi < 40) score++;
  if (rsi > 60) score--;
  if (entry > ema9) score++;
  if (entry < ema9) score--;

  if (score >= 2) { signal = 'BUY'; }
  else if (score <= -2) { signal = 'SELL'; }
  else { signal = 'WAIT'; }

  const box = document.getElementById('signalBox');
  box.className = 'signal-box';

  let sl, tp;
  if (signal === 'BUY') {
    box.classList.add('signal-buy');
    sl = (entry - 5 * pip).toFixed(isJPY ? 3 : 5);
    tp = (entry + 10 * pip).toFixed(isJPY ? 3 : 5);
    desc = `EMA9 > EMA21 ✅ | RSI: ${rsi} | Bullish momentum`;
  } else if (signal === 'SELL') {
    box.classList.add('signal-sell');
    sl = (entry + 5 * pip).toFixed(isJPY ? 3 : 5);
    tp = (entry - 10 * pip).toFixed(isJPY ? 3 : 5);
    desc = `EMA9 < EMA21 ✅ | RSI: ${rsi} | Bearish momentum`;
  } else {
    box.style.background = '#ffffff08';
    box.style.border = '1px solid #ffffff20';
    sl = '—'; tp = '—';
    desc = 'Mixed signals — wait for confirmation';
  }

  document.getElementById('signalText').textContent = signal;
  document.getElementById('signalDesc').textContent = desc;
  document.getElementById('sigSL').textContent = sl;
  document.getElementById('sigTP').textContent = tp;
  document.getElementById('signalResult').style.display = 'block';
}

// ─── PIP TABLE ────────────────────────────────────────────────
function buildPipTable() {
  const lotSize = parseInt(document.getElementById('lotType').value);
  const pairs = [
    { name: 'EUR/USD', pip: 0.0001, rate: 1.0 },
    { name: 'GBP/USD', pip: 0.0001, rate: 1.0 },
    { name: 'AUD/USD', pip: 0.0001, rate: 1.0 },
    { name: 'USD/JPY', pip: 0.01,   rate: 150.0 },
    { name: 'USD/CHF', pip: 0.0001, rate: 0.90 },
    { name: 'USD/CAD', pip: 0.0001, rate: 1.35 },
    { name: 'GBP/JPY', pip: 0.01,   rate: 150.0 },
    { name: 'EUR/JPY', pip: 0.01,   rate: 150.0 },
  ];

  let html = '';
  pairs.forEach(p => {
    const isJPY = p.name.includes('JPY');
    const pipVal = isJPY
      ? (lotSize / p.rate * p.pip * (1/p.pip)).toFixed(4)
      : (lotSize * p.pip).toFixed(4);
    const pipValNum = parseFloat(pipVal);
    html += `
      <tr>
        <td style="color:#fff;font-weight:600;">${p.name}</td>
        <td style="color:#888;">${p.pip}</td>
        <td style="color:#00ff96;">$${pipValNum.toFixed(4)}</td>
        <td style="color:#ff9900;">$${(pipValNum * 10).toFixed(3)}</td>
      </tr>`;
  });
  document.getElementById('pipTableBody').innerHTML = html;
}

// ─── TRADE JOURNAL ────────────────────────────────────────────
function logTrade() {
  const type = document.getElementById('tradeType').value;
  const pair = document.getElementById('tradePair').value;
  const entry = parseFloat(document.getElementById('jEntry').value);
  const exit = parseFloat(document.getElementById('jExit').value);
  const lot = parseFloat(document.getElementById('jLot').value);
  const time = document.getElementById('jTime').value || new Date().toTimeString().slice(0,5);

  const isJPY = pair.includes('JPY');
  const pipSize = isJPY ? 0.01 : 0.0001;
  const pipsMoved = (exit - entry) / pipSize;
  const pipVal = isJPY ? (lot * 1000 / 150) : (lot * 10);
  let pnl = pipsMoved * pipVal;
  if (type === 'SELL') pnl = -pnl;

  const trade = { type, pair, entry, exit, lot, pnl: pnl.toFixed(2), time, pips: (Math.abs(pipsMoved)).toFixed(1) };
  trades.unshift(trade);
  renderJournal();
}

function renderJournal() {
  const log = document.getElementById('tradeLog');
  if (trades.length === 0) {
    log.innerHTML = '<div class="empty-state">No trades logged yet.<br/>Start scalping! 🚀</div>';
    return;
  }

  let wins = 0, totalPnl = 0;
  trades.forEach(t => {
    if (parseFloat(t.pnl) > 0) wins++;
    totalPnl += parseFloat(t.pnl);
  });

  document.getElementById('totalTrades').textContent = trades.length;
  document.getElementById('winRate').textContent = Math.round((wins / trades.length) * 100) + '%';
  document.getElementById('winRate').style.color = wins / trades.length >= 0.5 ? '#00ff96' : '#ff4466';
  const pnlEl = document.getElementById('totalPnl');
  pnlEl.textContent = (totalPnl >= 0 ? '+' : '') + '$' + totalPnl.toFixed(2);
  pnlEl.style.color = totalPnl >= 0 ? '#00ff96' : '#ff4466';

  log.innerHTML = trades.slice(0, 10).map(t => {
    const pos = parseFloat(t.pnl) >= 0;
    return `
      <div class="trade-row">
        <span class="trade-type ${t.type === 'BUY' ? 'buy-tag' : 'sell-tag'}">${t.type}</span>
        <span style="color:#ccc;flex:1">${t.pair}</span>
        <span style="color:#888;font-size:0.78rem;">${t.time}</span>
        <span style="color:#666;font-size:0.78rem;">${t.pips} pips</span>
        <span class="${pos ? 'pnl-pos' : 'pnl-neg'}">${pos ? '+' : ''}$${t.pnl}</span>
      </div>`;
  }).join('');
}

// ─── SESSION CLOCK ────────────────────────────────────────────
function updateClock() {
  const now = new Date();
  const ist = new Date(now.toLocaleString('en-US', { timeZone: 'Asia/Kolkata' }));
  const h = ist.getHours(), m = ist.getMinutes(), s = ist.getSeconds();
  const hh = String(h).padStart(2,'0'), mm = String(m).padStart(2,'0'), ss = String(s).padStart(2,'0');
  document.getElementById('clockDisplay').textContent = `${hh}:${mm}:${ss}`;

  const toMins = (h, m) => h * 60 + m;
  const cur = toMins(h, m);

  const sessions = {
    tokyo:   { start: toMins(5,30),  end: toMins(14,30) },
    sydney:  { start: toMins(4,0),   end: toMins(13,0)  },
    london:  { start: toMins(13,30), end: toMins(22,30) },
    newyork: { start: toMins(18,30), end: toMins(25,30) },
  };

  Object.entries(sessions).forEach(([key, val]) => {
    const chip = document.getElementById('chip-' + key);
    const active = cur >= val.start && cur < val.end;
    if (active) {
      chip.classList.add('active-session');
    } else {
      chip.classList.remove('active-session');
    }
  });
}

// ─── INIT ─────────────────────────────────────────────────────
calcPosition();
buildPipTable();
updateClock();
setInterval(updateClock, 1000);

// Set current time in trade journal
const now = new Date();
document.getElementById('jTime').value = now.toTimeString().slice(0,5);
</script>
</body>
</html>
