<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<meta name="theme-color" content="#0a0b0f">
<title>Gym Pro Tracker</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap');
:root{--bg:#0a0b0f;--card:rgba(20,22,32,0.78);--glass:rgba(255,255,255,0.03);--glass-border:rgba(255,255,255,0.07);--accent:#00f0a0;--accent-glow:rgba(0,240,160,0.25);--accent2:#00c07d;--danger:#ff3860;--danger-glow:rgba(255,56,96,0.25);--warn:#ffd166;--warn-glow:rgba(255,209,102,0.3);--text:#f0f2f5;--muted:#6b7280;--radius:20px;--shadow:0 8px 32px rgba(0,0,0,0.45);}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
html,body{margin:0;padding:0;background:var(--bg);color:var(--text);font-family:'Inter',-apple-system,BlinkMacSystemFont,sans-serif;height:100%;overflow:hidden;-webkit-font-smoothing:antialiased}
body::before{content:'';position:fixed;inset:0;z-index:-1;background:radial-gradient(ellipse 80% 50% at 20% 40%,rgba(0,240,160,0.08) 0%,transparent 50%),radial-gradient(ellipse 60% 60% at 80% 0%,rgba(0,192,125,0.06) 0%,transparent 50%),radial-gradient(ellipse 50% 40% at 50% 100%,rgba(255,209,102,0.04) 0%,transparent 50%);animation:bgPulse 10s ease-in-out infinite alternate}
@keyframes bgPulse{0%{opacity:0.6;transform:scale(1)}100%{opacity:1;transform:scale(1.05)}}
#app{height:100%;display:flex;flex-direction:column;position:relative;z-index:1}
.header{padding:16px 20px;display:flex;justify-content:space-between;align-items:center;background:rgba(10,11,15,0.88);backdrop-filter:blur(20px);border-bottom:1px solid var(--glass-border);flex-shrink:0}
.header h1{margin:0;font-size:20px;font-weight:800;letter-spacing:-0.5px;background:linear-gradient(135deg,#fff 0%,var(--accent) 100%);-webkit-background-clip:text;-webkit-text-fill-color:transparent}
.header .user-pill{display:flex;align-items:center;gap:10px;font-size:12px;color:var(--muted);font-weight:600}
.header .user-pill button{background:var(--glass);border:1px solid var(--glass-border);color:var(--text);padding:6px 12px;border-radius:10px;font-size:11px;font-weight:700;cursor:pointer}
.nav{display:flex;background:rgba(10,11,15,0.78);backdrop-filter:blur(16px);border-bottom:1px solid var(--glass-border);flex-shrink:0;overflow-x:auto;padding:4px 12px;gap:4px}
.nav::-webkit-scrollbar{display:none}
.nav button{flex:1;min-width:70px;padding:12px 6px;background:transparent;border:none;color:var(--muted);font-size:11px;font-weight:600;text-transform:uppercase;letter-spacing:0.8px;cursor:pointer;border-radius:12px;white-space:nowrap;transition:all .3s cubic-bezier(.4,0,.2,1);position:relative;overflow:hidden}
.nav button::after{content:'';position:absolute;bottom:0;left:50%;width:0;height:2px;background:var(--accent);border-radius:2px;transition:all .3s cubic-bezier(.4,0,.2,1);transform:translateX(-50%);box-shadow:0 0 10px var(--accent-glow)}
.nav button.active{color:var(--accent);background:rgba(0,240,160,0.08)}
.nav button.active::after{width:60%}
.screen-container{flex:1;position:relative;overflow:hidden}
.screen{display:none;height:100%;overflow-y:auto;padding:18px;animation:fadeIn .3s ease-out;-webkit-overflow-scrolling:touch}
.screen.active{display:block}
@keyframes fadeIn{from{opacity:0;transform:translateY(12px)}to{opacity:1;transform:translateY(0)}}
.card{background:var(--card);backdrop-filter:blur(12px);border:1px solid var(--glass-border);border-radius:var(--radius);padding:20px;margin-bottom:16px;box-shadow:var(--shadow),inset 0 1px 0 rgba(255,255,255,0.03)}
.card-title{font-size:16px;font-weight:700;margin:0 0 16px;display:flex;justify-content:space-between;align-items:center;letter-spacing:-0.2px}
.muted{color:var(--muted);font-size:13px;font-weight:500}
.btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;padding:12px 20px;border-radius:14px;border:none;font-size:14px;font-weight:700;cursor:pointer;transition:all .25s cubic-bezier(.4,0,.2,1);letter-spacing:-0.2px;color:#fff}
.btn:active{transform:scale(0.96)}
.btn-primary{background:linear-gradient(135deg,var(--accent) 0%,var(--accent2) 100%);color:#000;box-shadow:0 4px 20px var(--accent-glow)}
.btn-primary:hover{box-shadow:0 6px 30px var(--accent-glow)}
.btn-ghost{background:var(--glass);color:var(--text);border:1px solid var(--glass-border)}
.btn-danger{background:linear-gradient(135deg,var(--danger) 0%,#d6335c 100%);color:#fff;box-shadow:0 4px 20px var(--danger-glow)}
.btn-block{width:100%;padding:16px;font-size:16px}
.btn-sm{padding:8px 14px;font-size:12px;border-radius:10px}
.btn-xs{padding:6px 10px;font-size:11px;border-radius:8px}
label{display:block;font-size:11px;color:var(--muted);margin-bottom:8px;text-transform:uppercase;letter-spacing:1.2px;font-weight:600}
input,select{width:100%;padding:14px 16px;border-radius:14px;border:1px solid var(--glass-border);background:rgba(0,0,0,0.25);color:var(--text);font-size:15px;font-family:inherit;outline:none;margin-bottom:14px;transition:all .3s;box-shadow:inset 0 2px 4px rgba(0,0,0,0.2)}
input:focus,select:focus{border-color:rgba(0,240,160,0.5);background:rgba(0,240,160,0.03);box-shadow:0 0 0 3px rgba(0,240,160,0.1),inset 0 2px 4px rgba(0,0,0,0.2)}
.auth-wrap{position:fixed;inset:0;background:var(--bg);z-index:5000;display:flex;align-items:center;justify-content:center;padding:24px}
.auth-box{background:var(--card);border:1px solid var(--glass-border);border-radius:28px;padding:40px 28px;width:100%;max-width:420px;box-shadow:var(--shadow)}
.auth-box h2{margin:0 0 8px;font-size:26px;font-weight:800;background:linear-gradient(135deg,#fff 0%,var(--accent) 100%);-webkit-background-clip:text;-webkit-text-fill-color:transparent}
.auth-box .subtitle{color:var(--muted);font-size:14px;margin-bottom:28px;font-weight:500}
.auth-toggle{display:flex;background:rgba(0,0,0,0.3);border:1px solid var(--glass-border);border-radius:14px;padding:4px;margin-bottom:24px}
.auth-toggle button{flex:1;padding:12px;border:none;background:transparent;color:var(--muted);font-size:13px;font-weight:700;cursor:pointer;border-radius:10px;transition:all .3s}
.auth-toggle button.active{background:linear-gradient(135deg,var(--accent) 0%,var(--accent2) 100%);color:#000;box-shadow:0 4px 15px var(--accent-glow)}
.cal-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:18px}
.cal-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:8px;text-align:center}
.cal-day-name{font-size:10px;color:var(--muted);text-transform:uppercase;padding:8px 0;font-weight:700;letter-spacing:1px}
.cal-cell{aspect-ratio:1;display:flex;flex-direction:column;align-items:center;justify-content:center;border-radius:14px;background:var(--glass);border:1px solid var(--glass-border);font-size:14px;font-weight:600;cursor:pointer;position:relative;transition:all .25s cubic-bezier(.4,0,.2,1)}
.cal-cell:hover{background:rgba(255,255,255,0.06);transform:scale(1.08);z-index:2}
.cal-cell.other{opacity:0.25;pointer-events:none}
.cal-cell.today{border-color:rgba(0,240,160,0.5);color:var(--accent);box-shadow:0 0 15px var(--accent-glow)}
.cal-cell.has-data::after{content:'';position:absolute;bottom:6px;width:5px;height:5px;border-radius:50%;background:var(--accent);box-shadow:0 0 8px var(--accent)}
.cal-cell.selected{background:linear-gradient(135deg,var(--accent) 0%,var(--accent2) 100%);color:#000;border-color:transparent;font-weight:800;box-shadow:0 4px 20px var(--accent-glow);transform:scale(1.05)}
.day-meta{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:18px}
.stat-box{background:var(--glass);padding:16px;border-radius:16px;text-align:center;border:1px solid var(--glass-border);transition:all .3s}
.stat-box:hover{transform:translateY(-2px);border-color:rgba(0,240,160,0.2)}
.stat-box .val{font-size:20px;font-weight:800;color:var(--accent);text-shadow:0 0 20px var(--accent-glow)}
.stat-box .lbl{font-size:11px;color:var(--muted);margin-top:6px;font-weight:600;text-transform:uppercase;letter-spacing:.5px}
.workout-item{background:var(--glass);border:1px solid var(--glass-border);border-radius:16px;padding:16px;margin-bottom:12px;display:flex;justify-content:space-between;align-items:center;transition:all .3s}
.workout-item:hover{transform:translateX(4px);border-color:rgba(0,240,160,0.2)}
.aw-header{text-align:center;margin-bottom:20px}
.aw-timer{font-size:46px;font-weight:900;font-variant-numeric:tabular-nums;letter-spacing:2px;margin:10px 0;background:linear-gradient(135deg,#fff 0%,var(--accent) 100%);-webkit-background-clip:text;-webkit-text-fill-color:transparent;position:relative}
.aw-timer::after{content:'SESSION';position:absolute;bottom:-14px;left:50%;transform:translateX(-50%);font-size:10px;letter-spacing:3px;color:var(--muted);-webkit-text-fill-color:var(--muted);font-weight:700}
.rest-box{background:var(--glass);border:1px solid var(--glass-border);border-radius:var(--radius);padding:18px;text-align:center;margin-bottom:20px;transition:all .3s}
.rest-box.running{border-color:rgba(255,209,102,0.4);box-shadow:0 0 30px var(--warn-glow),inset 0 0 30px rgba(255,209,102,0.05)}
.rest-display{font-size:52px;font-weight:900;color:var(--warn);margin:10px 0;font-variant-numeric:tabular-nums;text-shadow:0 0 30px var(--warn-glow)}
.rest-box.running .rest-display{animation:pulseTimer 1s ease-in-out infinite}
@keyframes pulseTimer{0%,100%{transform:scale(1)}50%{transform:scale(1.03)}}
.exercise-card{background:var(--glass);border:1px solid var(--glass-border);border-radius:var(--radius);padding:18px;margin-bottom:14px}
.exercise-card h3{margin:0 0 12px;font-size:16px;font-weight:700;display:flex;justify-content:space-between;align-items:center}
.sets-row{display:flex;flex-wrap:wrap;gap:10px;margin-bottom:14px}
.set-chip{background:rgba(0,0,0,0.25);border:1px solid var(--glass-border);border-radius:12px;padding:10px 14px;font-size:13px;display:flex;align-items:center;gap:10px;transition:all .3s;font-weight:500}
.set-chip.done{border-color:rgba(0,240,160,0.4);color:var(--accent);background:rgba(0,240,160,0.08);box-shadow:0 0 15px rgba(0,240,160,0.1)}
.set-chip input{width:60px;text-align:center;padding:8px;font-size:14px;margin:0;background:rgba(0,0,0,0.3);border:1px solid var(--glass-border);border-radius:10px;color:inherit;font-weight:600}
.set-chip button{background:linear-gradient(135deg,var(--accent) 0%,var(--accent2) 100%);border:none;border-radius:10px;padding:8px 14px;font-size:12px;font-weight:800;cursor:pointer;color:#000;transition:all .2s;box-shadow:0 2px 10px var(--accent-glow)}
.volume-bar{height:10px;background:rgba(0,0,0,0.3);border-radius:5px;overflow:hidden;margin-top:10px}
.volume-fill{height:100%;background:linear-gradient(90deg,var(--accent) 0%,#00ff9d 100%);width:0%;transition:width .6s cubic-bezier(.4,0,.2,1);border-radius:5px;box-shadow:0 0 20px var(--accent-glow)}
.chart-wrap{position:relative;height:220px;background:var(--glass);border:1px solid var(--glass-border);border-radius:var(--radius);padding:16px;overflow:hidden}
.chart-svg{width:100%;height:100%}
.routine-card{background:var(--glass);border:1px solid var(--glass-border);border-radius:16px;padding:18px;margin-bottom:12px;transition:all .3s}
.routine-card:hover{transform:translateY(-2px);border-color:rgba(0,240,160,0.2);box-shadow:0 8px 32px rgba(0,0,0,0.3)}
.routine-card h3{margin:0 0 10px;font-size:16px;font-weight:700;display:flex;justify-content:space-between}
.ex-list{font-size:13px;color:var(--muted);margin:0 0 14px;line-height:1.6;font-weight:500}
.toggle{display:flex;background:rgba(0,0,0,0.3);border:1px solid var(--glass-border);border-radius:14px;overflow:hidden;margin-bottom:18px;padding:4px}
.toggle button{flex:1;padding:12px;border:none;background:transparent;color:var(--muted);font-size:13px;font-weight:700;cursor:pointer;border-radius:10px;transition:all .3s}
.toggle button.active{background:linear-gradient(135deg,var(--accent) 0%,var(--accent2) 100%);color:#000;box-shadow:0 4px 15px var(--accent-glow)}
.stats-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;margin-bottom:16px}
.big-stat{background:var(--glass);border:1px solid var(--glass-border);border-radius:18px;padding:20px;text-align:center;transition:all .3s}
.big-stat:hover{transform:translateY(-3px);border-color:rgba(0,240,160,0.2)}
.big-stat .num{font-size:26px;font-weight:900;color:var(--accent);text-shadow:0 0 25px var(--accent-glow)}
.big-stat .label{font-size:11px;color:var(--muted);margin-top:8px;font-weight:600;text-transform:uppercase;letter-spacing:.8px}
.hero-timer{position:relative;padding:36px 18px}
.hero-timer .aw-timer::after{content:'TOTAL SESSION TIME';bottom:-16px}
.pulse-ring{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);width:200px;height:200px;border-radius:50%;border:2px solid var(--accent);opacity:0;pointer-events:none}
.hero-timer.running .pulse-ring{animation:ringPulse 2s ease-out infinite}
@keyframes ringPulse{0%{transform:translate(-50%,-50%) scale(0.8);opacity:0.5}100%{transform:translate(-50%,-50%) scale(1.4);opacity:0}}
.empty-state{text-align:center;padding:40px 20px;color:var(--muted)}
.toast{position:fixed;bottom:24px;left:50%;transform:translateX(-50%) translateY(120px);background:#141620;border:1px solid var(--glass-border);color:var(--text);padding:14px 24px;border-radius:14px;font-size:14px;font-weight:600;z-index:2000;box-shadow:0 10px 40px rgba(0,0,0,0.5);transition:transform .4s cubic-bezier(.34,1.56,.64,1);display:flex;align-items:center;gap:10px}
.toast.show{transform:translateX(-50%) translateY(0)}
.toast.success{border-color:rgba(0,240,160,0.3)}
.toast.error{border-color:rgba(255,56,96,0.3)}
.list-row{display:flex;justify-content:space-between;align-items:center;padding:12px 0;border-bottom:1px solid var(--glass-border);font-size:14px}
.list-row:last-child{border-bottom:none}
.list-row .l{font-weight:600}
.list-row .r{color:var(--accent);font-weight:700}
.week-row{display:flex;gap:6px;margin-top:12px;overflow-x:auto;padding-bottom:4px}
.week-row::-webkit-scrollbar{display:none}
.day-pill{min-width:44px;height:60px;border-radius:12px;background:var(--glass);border:1px solid var(--glass-border);display:flex;flex-direction:column;align-items:center;justify-content:center;font-size:11px;font-weight:600;flex:1;transition:all .2s}
.day-pill.has(border-color:rgba(0,240,160,0.3);background:rgba(0,240,160,0.06);color:var(--accent)}
.day-pill .d{font-size:10px;color:var(--muted);margin-bottom:2px;text-transform:uppercase}
.routine-picker-overlay{position:fixed;inset:0;background:rgba(0,0,0,0.85);backdrop-filter:blur(20px);z-index:900;display:none;align-items:flex-end;justify-content:center;padding:0;opacity:0;transition:opacity .3s}
.routine-picker-overlay.active{display:flex;opacity:1}
.routine-picker-sheet{background:var(--card);border:1px solid var(--glass-border);border-radius:24px 24px 0 0;width:100%;max-width:500px;max-height:70vh;overflow-y:auto;padding:24px;transform:translateY(100%);transition:transform .35s cubic-bezier(.34,1.56,.64,1)}
.routine-picker-overlay.active .routine-picker-sheet{transform:translateY(0)}
.routine-picker-item{padding:16px;border-radius:14px;background:var(--glass);border:1px solid var(--glass-border);margin-bottom:10px;cursor:pointer;transition:all .2s;display:flex;justify-content:space-between;align-items:center}
.routine-picker-item:hover{border-color:rgba(0,240,160,0.3);background:rgba(0,240,160,0.06)}
.pr-table{width:100%;border-collapse:collapse;font-size:14px}
.pr-table th{text-align:left;padding:10px 8px;color:var(--muted);font-size:11px;text-transform:uppercase;letter-spacing:1px;border-bottom:1px solid var(--glass-border)}
.pr-table td{padding:12px 8px;border-bottom:1px solid var(--glass-border);font-weight:600}
.pr-table td:last-child{color:var(--accent);font-weight:800;text-align:right}
.pr-tag{display:inline-block;padding:3px 10px;border-radius:8px;font-size:11px;font-weight:700;background:rgba(0,240,160,0.12);color:var(--accent);border:1px solid rgba(0,240,160,0.25)}
.progress-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:16px}
@media(max-width:400px){.aw-timer{font-size:38px;letter-spacing:1px}.rest-display{font-size:44px}.header h1{font-size:18px}.card{padding:16px;border-radius:16px}.progress-grid{grid-template-columns:1fr}}
</style>
</head>
<body>

<div class="auth-wrap" id="authScreen">
  <div class="auth-box">
    <h2>Gym Pro</h2>
    <div class="subtitle">Track. Progress. Dominate.</div>
    <div class="auth-toggle" id="authToggle">
      <button class="active" onclick="setAuthMode('login')">Sign In</button>
      <button onclick="setAuthMode('register')">New Account</button>
    </div>
    <label>Username</label>
    <input type="text" id="authUser" placeholder="your_name" autocomplete="off" autocapitalize="none">
    <label>Password</label>
    <input type="password" id="authPass" placeholder="password" autocomplete="off">
    <button class="btn btn-primary btn-block" id="authBtn" onclick="handleAuth()">Sign In</button>
    <div id="authError" style="color:var(--danger);font-size:13px;text-align:center;margin-top:12px;display:none;"></div>
    <div id="storageStatus" style="color:var(--muted);font-size:11px;text-align:center;margin-top:8px;"></div>
  </div>
</div>

<div id="app" style="display:none;">
  <div class="header">
    <h1>Gym Pro</h1>
    <div class="user-pill">
      <span id="userDisplay"></span>
      <button onclick="logout()">Logout</button>
    </div>
  </div>
  <div class="nav" id="nav">
    <button data-screen="dashboard" class="active">Dashboard</button>
    <button data-screen="workout">Workout</button>
    <button data-screen="routines">Routines</button>
    <button data-screen="analytics">Analytics</button>
    <button data-screen="weight">Weight</button>
    <button data-screen="stats">Stats</button>
  </div>
  <div class="screen-container">
    <div class="screen active" id="dashboard">
      <div class="card"><div class="card-title">Today</div><div class="day-meta" id="dashTodayStats"></div></div>
      <div class="card"><div class="card-title">This Week</div><div class="week-row" id="dashWeek"></div></div>
      <div class="card">
        <div class="cal-header">
          <button class="btn btn-ghost btn-sm" onclick="changeMonth(-1)">&larr;</button>
          <b id="calMonth" style="font-size:16px;font-weight:700;"></b>
          <button class="btn btn-ghost btn-sm" onclick="changeMonth(1)">&rarr;</button>
        </div>
        <div class="cal-grid" id="calGrid"></div>
      </div>
      <div id="dayDetail"></div>
    </div>
    <div class="screen" id="workout">
      <div id="workoutStart">
        <div class="card hero-timer" id="heroTimerWrap" style="text-align:center;">
          <div class="pulse-ring"></div>
          <div class="aw-timer" id="mainTimer">00:00:00</div>
          <p class="muted" style="margin-top:20px;">Ready to crush it?</p>
          <button class="btn btn-primary btn-block" style="margin-top:24px;" onclick="openRoutinePicker()">Start Workout</button>
          <button class="btn btn-ghost btn-block" style="margin-top:12px;" onclick="goScreen('routines')">Manage Routines</button>
        </div>
        <div class="card" id="quickWeightCard">
          <div class="card-title">Daily Weight</div>
          <div style="display:flex;gap:12px;align-items:flex-start;">
            <div style="flex:1;"><input type="number" step="0.1" id="dailyWeightInput" placeholder="kg today"></div>
            <button class="btn btn-primary" style="margin-top:0;" onclick="saveDailyWeight()">Save</button>
          </div>
          <div id="todayWeightDisplay" class="muted" style="margin-top:8px;font-weight:500;"></div>
        </div>
        <div class="card"><div class="card-title">Recent Sessions</div><div id="recentWorkoutsList"></div></div>
      </div>
      <div id="workoutActive" style="display:none;">
        <div class="aw-header">
          <div class="aw-timer" id="sessionTimer">00:00:00</div>
          <div class="muted" id="activeRoutineTitle" style="font-weight:600;"></div>
        </div>
        <div class="rest-box" id="restBox">
          <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:8px;">
            <span style="font-size:12px;font-weight:700;text-transform:uppercase;letter-spacing:1px;color:var(--muted);">Rest Timer</span>
            <div style="display:flex;gap:8px;">
              <button class="btn btn-sm btn-ghost" onclick="addRest(30)">+30s</button>
              <button class="btn btn-sm btn-ghost" onclick="addRest(60)">+1m</button>
              <button class="btn btn-sm btn-danger" onclick="stopRest()">Stop</button>
            </div>
          </div>
          <div class="rest-display" id="restDisplay">00:00</div>
          <div style="display:flex;gap:8px;margin-top:14px;justify-content:center;flex-wrap:wrap;">
            <button class="btn btn-primary btn-sm" onclick="startRest(30)">30s</button>
            <button class="btn btn-primary btn-sm" onclick="startRest(60)">1m</button>
            <button class="btn btn-primary btn-sm" onclick="startRest(90)">1.5m</button>
            <button class="btn btn-primary btn-sm" onclick="startRest(120)">2m</button>
            <button class="btn btn-primary btn-sm" onclick="startRest(180)">3m</button>
            <button class="btn btn-primary btn-sm" onclick="startRest(300)">5m</button>
          </div>
        </div>
        <div id="exercisesList"></div>
        <button class="btn btn-primary btn-block" style="margin-bottom:12px;" onclick="finishWorkout()">Finish Workout</button>
        <button class="btn btn-danger btn-block" onclick="cancelWorkout()">Cancel Session</button>
      </div>
    </div>
    <div class="screen" id="routines">
      <div class="card">
        <div class="card-title">New Routine</div>
        <label>Routine Name</label>
        <input type="text" id="rName" placeholder="e.g., Push Day">
        <div id="routineExercisesInputs">
          <div class="exercise-input-row" style="display:flex;gap:10px;align-items:flex-start;margin-bottom:10px;">
            <div style="flex:1;"><input type="text" class="ex-name" placeholder="Exercise name (e.g. Bench Press)"></div>
            <div style="width:80px;"><input type="number" class="ex-sets" placeholder="Sets" value="4" min="1" max="20"></div>
            <div style="width:80px;"><input type="number" class="ex-reps" placeholder="Reps" value="10" min="1"></div>
          </div>
        </div>
        <button class="btn btn-ghost btn-sm" onclick="addExerciseInput()" style="margin-bottom:16px;">+ Add Another Exercise</button>
        <button class="btn btn-primary btn-block" onclick="addRoutine()">Add Routine</button>
      </div>
      <div id="routinesList"></div>
    </div>
    <div class="screen" id="analytics">
      <div class="toggle">
        <button class="active" onclick="setAnalyticsView('prs')">PRs</button>
        <button onclick="setAnalyticsView('exercise')">Exercises</button>
        <button onclick="setAnalyticsView('volume')">Volume</button>
      </div>
      <div id="analyticsContent"></div>
    </div>
    <div class="screen" id="weight">
      <div class="card">
        <div class="card-title">Log Weight</div>
        <div style="display:flex;gap:12px;align-items:flex-start;">
          <div style="flex:1;">
            <input type="date" id="weightDate">
            <input type="number" step="0.1" id="weightVal" placeholder="Weight in kg">
          </div>
          <button class="btn btn-primary" style="margin-top:0;" onclick="addWeightLog()">Add</button>
        </div>
      </div>
      <div class="card"><div class="card-title">30-Day Trend</div><div class="chart-wrap"><svg class="chart-svg" id="weightChart"></svg></div></div>
      <div class="card" id="weightHistory"></div>
    </div>
    <div class="screen" id="stats">
      <div class="toggle">
        <button class="active" onclick="setStatsView('week')">Week</button>
        <button onclick="setStatsView('month')">Month</button>
        <button onclick="setStatsView('all')">All Time</button>
      </div>
      <div id="statsContent"></div>
    </div>
  </div>
</div>

<div class="routine-picker-overlay" id="routinePicker" onclick="if(event.target===this)closeRoutinePicker()">
  <div class="routine-picker-sheet">
    <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:16px;">
      <div style="font-size:18px;font-weight:800;">Select Routine</div>
      <button class="btn btn-ghost btn-xs" onclick="closeRoutinePicker()">Close</button>
    </div>
    <div id="pickerList"></div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
(function(){
'use strict';

// ================= STORAGE ENGINE =================
var storageType = 'none';
var memStore = {};

function initStorage() {
  try {
    var testKey = '__gym_test_' + Date.now();
    localStorage.setItem(testKey, 'ok');
    var v = localStorage.getItem(testKey);
    localStorage.removeItem(testKey);
    if (v === 'ok') {
      storageType = 'localStorage';
      return;
    }
  } catch(e) {}
  try {
    var testKey2 = '__gym_test2_' + Date.now();
    sessionStorage.setItem(testKey2, 'ok');
    var v2 = sessionStorage.getItem(testKey2);
    sessionStorage.removeItem(testKey2);
    if (v2 === 'ok') {
      storageType = 'sessionStorage';
      return;
    }
  } catch(e) {}
  storageType = 'memory';
}

function storeSet(key, val) {
  try {
    if (storageType === 'localStorage') { localStorage.setItem(key, val); return true; }
    if (storageType === 'sessionStorage') { sessionStorage.setItem(key, val); return true; }
  } catch(e) {}
  memStore[key] = val;
  return true;
}

function storeGet(key) {
  try {
    if (storageType === 'localStorage') { var v = localStorage.getItem(key); if (v !== null) return v; }
    if (storageType === 'sessionStorage') { var v2 = sessionStorage.getItem(key); if (v2 !== null) return v2; }
  } catch(e) {}
  return memStore[key] || null;
}

function storeRemove(key) {
  try {
    if (storageType === 'localStorage') localStorage.removeItem(key);
    if (storageType === 'sessionStorage') sessionStorage.removeItem(key);
  } catch(e) {}
  delete memStore[key];
}

initStorage();

// ================= AUTH =================
var currentUser = null;
var authMode = 'login';

function setAuthMode(mode) {
  authMode = mode;
  var btns = document.querySelectorAll('#authToggle button');
  btns[0].classList.toggle('active', mode === 'login');
  btns[1].classList.toggle('active', mode === 'register');
  document.getElementById('authBtn').textContent = mode === 'login' ? 'Sign In' : 'Create Account';
  document.getElementById('authError').style.display = 'none';
}

function getAccounts() {
  var raw = storeGet('gymAccounts');
  if (!raw) return {};
  try { return JSON.parse(raw); } catch(e) { return {}; }
}

function saveAccounts(acc) {
  storeSet('gymAccounts', JSON.stringify(acc));
}

function getUserData() {
  if (!currentUser) return defaultData();
  var raw = storeGet('gymData_' + currentUser);
  if (!raw) return defaultData();
  try { return JSON.parse(raw); } catch(e) { return defaultData(); }
}

function saveUserData(d) {
  if (!currentUser) return;
  storeSet('gymData_' + currentUser, JSON.stringify(d));
}

function saveSession(user) {
  storeSet('gymSession', user);
}

function getSession() {
  return storeGet('gymSession');
}

function clearSession() {
  storeRemove('gymSession');
}

function defaultData() {
  return {
    routines: [
      { name: 'Push Day', exercises: [{name:'Bench Press',sets:4,reps:10},{name:'Incline Dumbbell Press',sets:3,reps:12},{name:'Shoulder Press',sets:4,reps:10},{name:'Tricep Pushdown',sets:3,reps:15},{name:'Lateral Raises',sets:3,reps:15}] },
      { name: 'Pull Day', exercises: [{name:'Deadlift',sets:3,reps:5},{name:'Lat Pulldown',sets:4,reps:12},{name:'Barbell Row',sets:4,reps:10},{name:'Bicep Curl',sets:3,reps:12},{name:'Face Pulls',sets:3,reps:15}] },
      { name: 'Leg Day', exercises: [{name:'Squat',sets:4,reps:8},{name:'Leg Press',sets:3,reps:12},{name:'Romanian Deadlift',sets:3,reps:10},{name:'Leg Extension',sets:3,reps:15},{name:'Calf Raises',sets:4,reps:20}] }
    ],
    workouts: {},
    weightLog: []
  };
}

var data = defaultData();

function showToast(msg, type) {
  type = type || 'success';
  var t = document.getElementById('toast');
  if (!t) return;
  t.textContent = msg;
  t.className = 'toast ' + type + ' show';
  setTimeout(function() { t.classList.remove('show'); }, 2500);
}

function handleAuth() {
  var user = document.getElementById('authUser').value.trim().toLowerCase();
  var pass = document.getElementById('authPass').value;
  var err = document.getElementById('authError');
  err.style.display = 'none';

  if (!user || !pass) { err.textContent = 'Fill all fields'; err.style.display = 'block'; return; }
  if (user.length < 3) { err.textContent = 'Username min 3 chars'; err.style.display = 'block'; return; }

  var accounts = getAccounts();

  if (authMode === 'register') {
    if (accounts[user]) { err.textContent = 'Username exists. Sign in instead.'; err.style.display = 'block'; return; }
    accounts[user] = { password: pass, created: new Date().toISOString() };
    saveAccounts(accounts);

    currentUser = user;
    data = defaultData();
    saveUserData(data);
    saveSession(user);
    showToast('Account created!');
    enterApp();
  } else {
    if (!accounts[user]) { err.textContent = 'Account not found. Create one?'; err.style.display = 'block'; return; }
    if (accounts[user].password !== pass) { err.textContent = 'Wrong password'; err.style.display = 'block'; return; }
    currentUser = user;
    data = getUserData();
    saveSession(user);
    showToast('Welcome back, ' + user + '!');
    enterApp();
  }
}

function enterApp() {
  document.getElementById('authScreen').style.display = 'none';
  document.getElementById('app').style.display = 'flex';
  document.getElementById('userDisplay').textContent = currentUser;
  initAll();
}

function logout() {
  currentUser = null;
  data = defaultData();
  clearSession();
  document.getElementById('app').style.display = 'none';
  document.getElementById('authScreen').style.display = 'flex';
  document.getElementById('authUser').value = '';
  document.getElementById('authPass').value = '';
  document.getElementById('authError').style.display = 'none';
  setAuthMode('login');
}

function updateStorageStatus() {
  var el = document.getElementById('storageStatus');
  if (!el) return;
  if (storageType === 'localStorage') el.textContent = 'Data will be saved to this device';
  else if (storageType === 'sessionStorage') el.textContent = 'Data clears when browser closes';
  else el.textContent = 'Data may be lost on page reload - use a real browser';
}

// ================= NAVIGATION =================
var currentScreen = 'dashboard';
function goScreen(id) {
  if (!id || id === currentScreen) return;
  var outgoing = document.querySelector('.screen.active');
  var incoming = document.getElementById(id);
  if (!incoming) return;
  if (outgoing) outgoing.classList.remove('active');
  incoming.classList.add('active');
  var btns = document.querySelectorAll('.nav button');
  for (var i = 0; i < btns.length; i++) {
    btns[i].classList.toggle('active', btns[i].dataset.screen === id);
  }
  currentScreen = id;
  if (id === 'dashboard') renderDashboard();
  if (id === 'workout') renderWorkoutPage();
  if (id === 'routines') renderRoutines();
  if (id === 'analytics') renderAnalytics();
  if (id === 'weight') renderWeightPage();
  if (id === 'stats') renderStats();
}

document.getElementById('nav').addEventListener('click', function(e) {
  var btn = e.target.closest('button');
  if (btn && btn.dataset.screen) goScreen(btn.dataset.screen);
});

// ================= DATE =================
function todayStr() {
  var d = new Date();
  return d.getFullYear() + '-' + String(d.getMonth()+1).padStart(2,'0') + '-' + String(d.getDate()).padStart(2,'0');
}
function fmtDate(d) {
  return d.getFullYear() + '-' + String(d.getMonth()+1).padStart(2,'0') + '-' + String(d.getDate()).padStart(2,'0');
}
function parseDate(s) { return new Date(s + 'T00:00:00'); }

// ================= DASHBOARD =================
var calCursor = new Date();
var selectedDay = todayStr();

function renderDashboard() {
  renderDashToday();
  renderDashWeek();
  renderCalendar();
  renderDayDetail();
}
function renderDashToday() {
  var w = data.workouts[todayStr()];
  var wl = null;
  for (var i = 0; i < data.weightLog.length; i++) { if (data.weightLog[i].date === todayStr()) { wl = data.weightLog[i]; break; } }
  var c = document.getElementById('dashTodayStats');
  if (!c) return;
  if (!w) {
    c.innerHTML = '<div class="stat-box"><div class="val">-</div><div class="lbl">No workout</div></div><div class="stat-box"><div class="val">-</div><div class="lbl">Tap Workout</div></div>';
  } else {
    var s = 0, v = 0;
    for (var i = 0; i < w.exercises.length; i++) {
      for (var j = 0; j < w.exercises[i].sets.length; j++) {
        if (w.exercises[i].sets[j].done) { s++; v += (parseFloat(w.exercises[i].sets[j].weight)||0) * (parseInt(w.exercises[i].sets[j].reps)||0); }
      }
    }
    var dur = w.durationSec || 0;
    var mm = String(Math.floor((dur%3600)/60)).padStart(2,'0');
    var ss = String(dur%60).padStart(2,'0');
    c.innerHTML = '<div class="stat-box"><div class="val">' + s + '</div><div class="lbl">Sets</div></div>' +
      '<div class="stat-box"><div class="val">' + Math.round(v).toLocaleString() + '</div><div class="lbl">Volume</div></div>' +
      '<div class="stat-box"><div class="val">' + mm + ':' + ss + '</div><div class="lbl">Duration</div></div>' +
      '<div class="stat-box"><div class="val">' + (wl ? wl.weight + ' kg' : '-') + '</div><div class="lbl">Weight</div></div>';
  }
}
function renderDashWeek() {
  var c = document.getElementById('dashWeek');
  if (!c) return;
  var today = new Date();
  var start = new Date(today);
  start.setDate(today.getDate() - today.getDay());
  var html = '';
  for (var i = 0; i < 7; i++) {
    var d = new Date(start);
    d.setDate(start.getDate() + i);
    var ds = fmtDate(d);
    var has = data.workouts[ds];
    var isToday = ds === todayStr();
    var dayName = d.toLocaleDateString('en-US', { weekday: 'narrow' });
    html += '<div class="day-pill ' + (has ? 'has' : '') + '" style="' + (isToday ? 'border-color:var(--accent);color:var(--accent);' : '') + '">' +
      '<div class="d">' + dayName + '</div><div>' + d.getDate() + '</div></div>';
  }
  c.innerHTML = html;
}
function renderCalendar() {
  var y = calCursor.getFullYear(), m = calCursor.getMonth();
  var monthEl = document.getElementById('calMonth');
  var grid = document.getElementById('calGrid');
  if (!monthEl || !grid) return;
  monthEl.textContent = new Date(y, m, 1).toLocaleString('default', { month: 'long', year: 'numeric' });
  grid.innerHTML = '';
  var days = ['Sun','Mon','Tue','Wed','Thu','Fri','Sat'];
  for (var i = 0; i < days.length; i++) {
    var el = document.createElement('div');
    el.className = 'cal-day-name';
    el.textContent = days[i];
    grid.appendChild(el);
  }
  var first = new Date(y, m, 1);
  var startDay = first.getDay();
  var daysInMonth = new Date(y, m+1, 0).getDate();
  var prevDays = new Date(y, m, 0).getDate();
  for (var i = startDay - 1; i >= 0; i--) {
    var el = document.createElement('div');
    el.className = 'cal-cell other';
    el.textContent = prevDays - i;
    grid.appendChild(el);
  }
  var tStr = todayStr();
  for (var i = 1; i <= daysInMonth; i++) {
    var ds = fmtDate(new Date(y, m, i));
    var el = document.createElement('div');
    var cls = 'cal-cell' + (ds === tStr ? ' today' : '') + (data.workouts[ds] ? ' has-data' : '');
    if (selectedDay === ds) cls += ' selected';
    el.className = cls;
    el.textContent = i;
    el.onclick = (function(d) { return function() { selectedDay = d; renderCalendar(); renderDayDetail(); }; })(ds);
    grid.appendChild(el);
  }
  var total = startDay + daysInMonth;
  var rem = Math.max(0, 42 - total);
  for (var i = 1; i <= rem; i++) {
    var el = document.createElement('div');
    el.className = 'cal-cell other';
    el.textContent = i;
    grid.appendChild(el);
  }
}
function changeMonth(n) {
  calCursor.setMonth(calCursor.getMonth() + n);
  renderCalendar();
  renderDayDetail();
}
function renderDayDetail() {
  var c = document.getElementById('dayDetail');
  if (!c) return;
  var w = data.workouts[selectedDay];
  if (!w) {
    c.innerHTML = '<div class="card empty-state"><div style="font-size:48px;margin-bottom:12px;">&#128197;</div><div>No workout on ' + selectedDay + '</div><div class="muted" style="margin-top:8px;">Select another day</div></div>';
    return;
  }
  var tv = 0, ts = 0;
  for (var i = 0; i < w.exercises.length; i++) {
    for (var j = 0; j < w.exercises[i].sets.length; j++) {
      if (w.exercises[i].sets[j].done) { ts++; tv += (parseFloat(w.exercises[i].sets[j].weight)||0) * (parseInt(w.exercises[i].sets[j].reps)||0); }
    }
  }
  var dur = w.durationSec || 0;
  var hh = String(Math.floor(dur/3600)).padStart(2,'0');
  var mm = String(Math.floor((dur%3600)/60)).padStart(2,'0');
  var ss = String(dur%60).padStart(2,'0');
  var html = '<div class="card"><div class="card-title">' + selectedDay + ' &bull; ' + (w.routineName || 'Workout') + '</div>' +
    '<div class="day-meta"><div class="stat-box"><div class="val">' + ts + '</div><div class="lbl">Sets</div></div>' +
    '<div class="stat-box"><div class="val">' + hh + ':' + mm + ':' + ss + '</div><div class="lbl">Duration</div></div>' +
    '<div class="stat-box"><div class="val">' + Math.round(tv).toLocaleString() + '</div><div class="lbl">Volume</div></div>' +
    '<div class="stat-box"><div class="val">' + w.exercises.length + '</div><div class="lbl">Exercises</div></div></div>';
  for (var i = 0; i < w.exercises.length; i++) {
    var ev = 0;
    for (var j = 0; j < w.exercises[i].sets.length; j++) {
      if (w.exercises[i].sets[j].done) ev += (parseFloat(w.exercises[i].sets[j].weight)||0) * (parseInt(w.exercises[i].sets[j].reps)||0);
    }
    html += '<div class="exercise-card"><h3>' + w.exercises[i].name + '<span style="font-size:13px;color:var(--muted);font-weight:600;">' + Math.round(ev).toLocaleString() + ' kg vol</span></h3><div class="sets-row">';
    for (var j = 0; j < w.exercises[i].sets.length; j++) {
      var s = w.exercises[i].sets[j];
      html += '<div class="set-chip ' + (s.done ? 'done' : '') + '"><span style="font-weight:700;opacity:0.7;">#' + (j+1) + '</span><span>' + (s.weight||'-') + 'kg &times; ' + (s.reps||'-') + '</span></div>';
    }
    html += '</div></div>';
  }
  var wl = null;
  for (var i = 0; i < data.weightLog.length; i++) { if (data.weightLog[i].date === selectedDay) { wl = data.weightLog[i]; break; } }
  if (wl) html += '<div class="stat-box" style="margin-top:12px;"><div class="val">' + wl.weight + ' kg</div><div class="lbl">Body Weight</div></div>';
  html += '</div>';
  c.innerHTML = html;
}

// ================= WORKOUT PAGE =================
function renderWorkoutPage() {
  updateDailyWeightDisplay();
  renderRecentWorkouts();
}
function renderRecentWorkouts() {
  var c = document.getElementById('recentWorkoutsList');
  if (!c) return;
  var keys = Object.keys(data.workouts).sort().reverse().slice(0, 6);
  if (!keys.length) { c.innerHTML = '<div class="muted">No workouts yet. Start your first one!</div>'; return; }
  var html = '';
  for (var i = 0; i < keys.length; i++) {
    var d = keys[i];
    var w = data.workouts[d];
    var s = 0, v = 0;
    for (var j = 0; j < w.exercises.length; j++) {
      for (var k = 0; k < w.exercises[j].sets.length; k++) {
        if (w.exercises[j].sets[k].done) { s++; v += (parseFloat(w.exercises[j].sets[k].weight)||0) * (parseInt(w.exercises[j].sets[k].reps)||0); }
      }
    }
    var dur = w.durationSec || 0;
    var mins = Math.floor(dur/60);
    html += '<div class="workout-item"><div class="info"><h3>' + d + '</h3><p>' + (w.routineName||'-') + ' &bull; ' + s + ' sets &bull; ' + mins + ' min</p></div>' +
      '<div style="text-align:right;"><div style="font-size:18px;font-weight:800;color:var(--accent);">' + Math.round(v).toLocaleString() + '</div><div class="muted" style="font-size:11px;">kg vol</div></div></div>';
  }
  c.innerHTML = html;
}

// ================= ROUTINE PICKER =================
function openRoutinePicker() {
  if (!data.routines.length) { showToast('Create a routine first!', 'error'); goScreen('routines'); return; }
  var list = document.getElementById('pickerList');
  if (!list) return;
  var html = '';
  for (var i = 0; i < data.routines.length; i++) {
    var r = data.routines[i];
    var totalSets = 0;
    for (var j = 0; j < r.exercises.length; j++) totalSets += (r.exercises[j].sets || 3);
    html += '<div class="routine-picker-item" onclick="closeRoutinePicker(); configureWorkout(' + i + ')">' +
      '<div><div style="font-weight:700;font-size:15px;">' + r.name + '</div><div style="font-size:12px;color:var(--muted);font-weight:500;">' + r.exercises.length + ' exercises &bull; ' + totalSets + ' sets</div></div><div style="font-size:20px;">&#9654;</div></div>';
  }
  list.innerHTML = html;
  document.getElementById('routinePicker').classList.add('active');
}
function closeRoutinePicker() {
  var rp = document.getElementById('routinePicker');
  if (rp) rp.classList.remove('active');
}

// ================= CONFIGURE WORKOUT =================
var pendingRoutine = null;
function configureWorkout(idx) {
  if (idx < 0 || idx >= data.routines.length) return;
  pendingRoutine = JSON.parse(JSON.stringify(data.routines[idx]));
  var html = '<div style="font-size:18px;font-weight:800;margin-bottom:16px;">Configure: ' + pendingRoutine.name + '</div>';
  for (var i = 0; i < pendingRoutine.exercises.length; i++) {
    var ex = pendingRoutine.exercises[i];
    html += '<div style="margin-bottom:14px;padding:14px;border-radius:14px;background:var(--glass);border:1px solid var(--glass-border);">' +
      '<div style="font-weight:700;margin-bottom:10px;">' + (i+1) + '. ' + ex.name + '</div>' +
      '<div style="display:flex;gap:10px;align-items:center;">' +
      '<div style="flex:1;"><label style="margin-bottom:4px;font-size:10px;">Sets</label><input type="number" id="cfg-sets-' + i + '" value="' + (ex.sets||4) + '" min="1" max="30" style="margin-bottom:0;"></div>' +
      '<div style="flex:1;"><label style="margin-bottom:4px;font-size:10px;">Target Reps</label><input type="number" id="cfg-reps-' + i + '" value="' + (ex.reps||10) + '" min="1" style="margin-bottom:0;"></div>' +
      '</div></div>';
  }
  html += '<button class="btn btn-primary btn-block" onclick="startConfiguredWorkout()">Start Workout</button>';
  html += '<button class="btn btn-ghost btn-block" style="margin-top:10px;" onclick="closeConfigureOverlay()">Cancel</button>';
  var sheet = document.querySelector('.routine-picker-sheet');
  if (sheet) { sheet.innerHTML = html; document.getElementById('routinePicker').classList.add('active'); }
}
function closeConfigureOverlay() { closeRoutinePicker(); pendingRoutine = null; }
function startConfiguredWorkout() {
  if (!pendingRoutine) return;
  for (var i = 0; i < pendingRoutine.exercises.length; i++) {
    pendingRoutine.exercises[i].sets = parseInt(document.getElementById('cfg-sets-' + i).value) || 4;
    pendingRoutine.exercises[i].reps = parseInt(document.getElementById('cfg-reps-' + i).value) || 10;
  }
  closeRoutinePicker();
  startWorkout(pendingRoutine);
  pendingRoutine = null;
}

// ================= ACTIVE WORKOUT =================
var activeWorkout = null, sessionStart = null, sessionTimerInterval = null, restInterval = null, restSeconds = 0;
function startWorkout(routine) {
  activeWorkout = {
    routineName: routine.name,
    date: todayStr(),
    startTime: Date.now(),
    exercises: [],
    durationSec: 0
  };
  for (var i = 0; i < routine.exercises.length; i++) {
    var ex = routine.exercises[i];
    var sets = [];
    var numSets = ex.sets || 4;
    for (var j = 0; j < numSets; j++) {
      sets.push({ weight: '', reps: ex.reps || 10, done: false });
    }
    activeWorkout.exercises.push({ name: ex.name, sets: sets });
  }
  sessionStart = Date.now();
  document.getElementById('workoutStart').style.display = 'none';
  document.getElementById('workoutActive').style.display = 'block';
  document.getElementById('activeRoutineTitle').textContent = routine.name;
  document.getElementById('heroTimerWrap').classList.add('running');
  renderActiveExercises();
  sessionTimerInterval = setInterval(function() {
    var sec = Math.floor((Date.now() - sessionStart) / 1000);
    activeWorkout.durationSec = sec;
    var hh = String(Math.floor(sec/3600)).padStart(2,'0');
    var mm = String(Math.floor((sec%3600)/60)).padStart(2,'0');
    var ss = String(sec%60).padStart(2,'0');
    var st = document.getElementById('sessionTimer');
    var mt = document.getElementById('mainTimer');
    if (st) st.textContent = hh + ':' + mm + ':' + ss;
    if (mt) mt.textContent = hh + ':' + mm + ':' + ss;
  }, 1000);
  showToast('Workout started!');
}
function renderActiveExercises() {
  var c = document.getElementById('exercisesList');
  if (!c) return;
  var html = '';
  for (var exIdx = 0; exIdx < activeWorkout.exercises.length; exIdx++) {
    var ex = activeWorkout.exercises[exIdx];
    var exVol = 0;
    for (var i = 0; i < ex.sets.length; i++) {
      if (ex.sets[i].done) exVol += (parseFloat(ex.sets[i].weight)||0) * (parseInt(ex.sets[i].reps)||0);
    }
    // find PR
    var prWeight = 0, prReps = 0;
    var workouts = data.workouts;
    var keys = Object.keys(workouts);
    for (var i = 0; i < keys.length; i++) {
      var day = workouts[keys[i]];
      for (var j = 0; j < day.exercises.length; j++) {
        if (day.exercises[j].name === ex.name) {
          for (var k = 0; k < day.exercises[j].sets.length; k++) {
            var s = day.exercises[j].sets[k];
            if (s.done && (parseFloat(s.weight)||0) > prWeight) {
              prWeight = parseFloat(s.weight)||0;
              prReps = parseInt(s.reps)||0;
            }
          }
        }
      }
    }
    var pct = prWeight > 0 ? Math.min(100, Math.round((exVol / Math.max(1, prWeight * prReps * ex.sets.length)) * 100)) : 0;

    html += '<div class="exercise-card">';
    html += '<h3>' + ex.name + '<span style="font-size:12px;color:var(--muted);font-weight:600;">PR: ' + prWeight + 'kg x ' + prReps + '</span></h3>';
    html += '<div class="sets-row">';
    for (var sIdx = 0; sIdx < ex.sets.length; sIdx++) {
      var set = ex.sets[sIdx];
      html += '<div class="set-chip ' + (set.done ? 'done' : '') + '">' +
        '<span style="font-weight:700;opacity:0.7;min-width:16px;">#' + (sIdx+1) + '</span>' +
        '<input type="number" placeholder="kg" value="' + (set.weight || '') + '" onchange="updateSet(' + exIdx + ',' + sIdx + ',this.value,' + (set.reps||'') + ')" ' + (set.done ? 'disabled' : '') + '>' +
        '<input type="number" placeholder="reps" value="' + (set.reps || '') + '" onchange="updateSet(' + exIdx + ',' + sIdx + ',' + (set.weight||'') + ',this.value)" ' + (set.done ? 'disabled' : '') + '>' +
        '<button onclick="toggleSet(' + exIdx + ',' + sIdx + ')">' + (set.done ? 'Done' : 'Do') + '</button>' +
        '</div>';
    }
    html += '</div>';
    html += '<div class="volume-bar"><div class="volume-fill" style="width:' + pct + '%;"></div></div>';
    html += '<div style="text-align:right;font-size:11px;color:var(--muted);margin-top:6px;font-weight:600;">' + (prWeight > 0 ? 'vs PR: ' + pct + '%' : 'No PR yet') + '</div>';
    html += '</div>';
  }
  c.innerHTML = html;
}
function updateSet(exIdx, sIdx, w, r) {
  if (!activeWorkout) return;
  var s = activeWorkout.exercises[exIdx].sets[sIdx];
  if (w !== null && w !== undefined && w !== '') s.weight = parseFloat(w);
  if (r !== null && r !== undefined && r !== '') s.reps = parseInt(r);
}
function toggleSet(exIdx, sIdx) {
  if (!activeWorkout) return;
  var s = activeWorkout.exercises[exIdx].sets[sIdx];
  if (!s.weight || !s.reps) { showToast('Enter weight and reps first', 'error'); return; }
  s.done = !s.done;
  if (s.done) { 
    startRest(90); 
    showToast('Set completed! Rest 90s'); 
  }
  renderActiveExercises();
}

// ================= REST TIMER =================
function startRest(sec) {
  stopRest();
  restSeconds = sec;
  updateRestDisplay();
  var rb = document.getElementById('restBox');
  if (rb) rb.classList.add('running');
  restInterval = setInterval(function() {
    restSeconds--;
    updateRestDisplay();
    if (restSeconds <= 0) {
      clearInterval(restInterval);
      restInterval = null;
      if (rb) rb.classList.remove('running');
      showToast('Rest is over! Next set!');
    }
  }, 1000);
}
function addRest(sec) {
  if (restInterval) {
    restSeconds += sec;
    updateRestDisplay();
    showToast('+' + sec + 's added');
  } else {
    startRest(sec);
  }
}
function stopRest() {
  clearInterval(restInterval);
  restInterval = null;
  var rb = document.getElementById('restBox');
  var rd = document.getElementById('restDisplay');
  if (rb) rb.classList.remove('running');
  if (rd) rd.textContent = '00:00';
}
function updateRestDisplay() {
  var mm = String(Math.max(0, Math.floor(restSeconds/60))).padStart(2,'0');
  var ss = String(Math.max(0, restSeconds%60)).padStart(2,'0');
  var txt = mm + ':' + ss;
  var rd = document.getElementById('restDisplay');
  if (rd) rd.textContent = txt;
}

// ================= FINISH / CANCEL =================
function finishWorkout() {
  if (!activeWorkout) return;
  clearInterval(sessionTimerInterval);
  data.workouts[activeWorkout.date] = JSON.parse(JSON.stringify(activeWorkout));
  saveUserData(data);
  activeWorkout = null;
  sessionStart = null;
  document.getElementById('workoutStart').style.display = 'block';
  document.getElementById('workoutActive').style.display = 'none';
  var mt = document.getElementById('mainTimer');
  if (mt) mt.textContent = '00:00:00';
  document.getElementById('heroTimerWrap').classList.remove('running');
  stopRest();
  showToast('Workout saved!');
  renderWorkoutPage();
  renderDashboard();
}
function cancelWorkout() {
  if (!confirm('Cancel this workout? All progress will be lost.')) return;
  clearInterval(sessionTimerInterval);
  activeWorkout = null;
  sessionStart = null;
  document.getElementById('workoutStart').style.display = 'block';
  document.getElementById('workoutActive').style.display = 'none';
  var mt = document.getElementById('mainTimer');
  if (mt) mt.textContent = '00:00:00';
  document.getElementById('heroTimerWrap').classList.remove('running');
  stopRest();
  showToast('Workout cancelled', 'error');
}

// ================= ROUTINES =================
function addExerciseInput() {
  var container = document.getElementById('routineExercisesInputs');
  var div = document.createElement('div');
  div.className = 'exercise-input-row';
  div.style.cssText = 'display:flex;gap:10px;align-items:flex-start;margin-bottom:10px;';
  div.innerHTML = '<div style="flex:1;"><input type="text" class="ex-name" placeholder="Exercise name"></div>' +
    '<div style="width:80px;"><input type="number" class="ex-sets" placeholder="Sets" value="4" min="1" max="20"></div>' +
    '<div style="width:80px;"><input type="number" class="ex-reps" placeholder="Reps" value="10" min="1"></div>';
  container.appendChild(div);
}
function renderRoutines() {
  var c = document.getElementById('routinesList');
  if (!c) return;
  if (!data.routines.length) {
    c.innerHTML = '<div class="card empty-state"><div style="font-size:48px;margin-bottom:12px;">&#128203;</div><div>No routines yet.</div><div class="muted" style="margin-top:8px;">Create your first routine above</div></div>';
    return;
  }
  var html = '';
  for (var i = 0; i < data.routines.length; i++) {
    var r = data.routines[i];
    html += '<div class="routine-card">' +
      '<h3>' + r.name + '<button class="btn btn-xs btn-ghost" onclick="deleteRoutine(' + i + ')">Delete</button></h3>' +
      '<div class="ex-list">';
    for (var j = 0; j < r.exercises.length; j++) {
      html += '<div style="display:flex;justify-content:space-between;"><span>' + (j+1) + '. ' + r.exercises[j].name + '</span><span style="color:var(--muted);">' + (r.exercises[j].sets||4) + ' sets x ' + (r.exercises[j].reps||10) + ' reps</span></div>';
    }
    html += '</div>' +
      '<button class="btn btn-primary btn-sm" onclick="configureWorkout(' + i + ')">Start Workout</button>' +
      '</div>';
  }
  c.innerHTML = html;
}
function addRoutine() {
  var name = document.getElementById('rName').value.trim();
  if (!name) { showToast('Enter routine name', 'error'); return; }
  var rows = document.querySelectorAll('#routineExercisesInputs .exercise-input-row');
  var exercises = [];
  for (var i = 0; i < rows.length; i++) {
    var n = rows[i].querySelector('.ex-name').value.trim();
    var s = parseInt(rows[i].querySelector('.ex-sets').value) || 4;
    var r = parseInt(rows[i].querySelector('.ex-reps').value) || 10;
    if (n) exercises.push({name: n, sets: s, reps: r});
  }
  if (!exercises.length) { showToast('Add at least one exercise', 'error'); return; }
  data.routines.push({name: name, exercises: exercises});
  saveUserData(data);
  document.getElementById('rName').value = '';
  document.getElementById('routineExercisesInputs').innerHTML =
    '<div class="exercise-input-row" style="display:flex;gap:10px;align-items:flex-start;margin-bottom:10px;">' +
    '<div style="flex:1;"><input type="text" class="ex-name" placeholder="Exercise name"></div>' +
    '<div style="width:80px;"><input type="number" class="ex-sets" placeholder="Sets" value="4" min="1" max="20"></div>' +
    '<div style="width:80px;"><input type="number" class="ex-reps" placeholder="Reps" value="10" min="1"></div></div>';
  renderRoutines();
  showToast('Routine added!');
}
function deleteRoutine(idx) {
  if (!confirm('Delete "' + data.routines[idx].name + '"?')) return;
  data.routines.splice(idx, 1);
  saveUserData(data);
  renderRoutines();
  showToast('Routine deleted', 'error');
}

// ================= WEIGHT =================
function renderWeightPage() {
  var wd = document.getElementById('weightDate');
  if (wd) wd.value = todayStr();
  renderWeightChart();
  renderWeightHistory();
}
function addWeightLog() {
  var d = document.getElementById('weightDate').value || todayStr();
  var w = parseFloat(document.getElementById('weightVal').value);
  if (!w || w <= 0) { showToast('Enter a valid weight', 'error'); return; }
  var existing = -1;
  for (var i = 0; i < data.weightLog.length; i++) {
    if (data.weightLog[i].date === d) { existing = i; break; }
  }
  if (existing >= 0) data.weightLog[existing].weight = w;
  else data.weightLog.push({date: d, weight: w});
  data.weightLog.sort(function(a,b) { return a.date.localeCompare(b.date); });
  saveUserData(data);
  document.getElementById('weightVal').value = '';
  renderWeightChart();
  renderWeightHistory();
  showToast('Weight logged!');
  renderDashboard();
}
function saveDailyWeight() {
  var w = parseFloat(document.getElementById('dailyWeightInput').value);
  if (!w || w <= 0) { showToast('Enter your weight', 'error'); return; }
  var d = todayStr();
  var existing = -1;
  for (var i = 0; i < data.weightLog.length; i++) {
    if (data.weightLog[i].date === d) { existing = i; break; }
  }
  if (existing >= 0) data.weightLog[existing].weight = w;
  else data.weightLog.push({date: d, weight: w});
  data.weightLog.sort(function(a,b) { return a.date.localeCompare(b.date); });
  saveUserData(data);
  document.getElementById('dailyWeightInput').value = '';
  updateDailyWeightDisplay();
  renderWeightChart();
  renderDashboard();
  showToast('Weight saved!');
}
function updateDailyWeightDisplay() {
  var t = null;
  for (var i = 0; i < data.weightLog.length; i++) {
    if (data.weightLog[i].date === todayStr()) { t = data.weightLog[i]; break; }
  }
  var el = document.getElementById('todayWeightDisplay');
  if (el) el.textContent = t ? 'Today: ' + t.weight + ' kg' : 'No weight logged today';
}
function renderWeightHistory() {
  var c = document.getElementById('weightHistory');
  if (!c) return;
  if (!data.weightLog.length) { c.innerHTML = '<div class="empty-state" style="padding:20px;"><div class="muted">No weight data yet.</div></div>'; return; }
  var html = '<div class="card-title">History</div>';
  var reversed = data.weightLog.slice().reverse();
  for (var i = 0; i < reversed.length; i++) {
    var change = '';
    if (i < reversed.length - 1) {
      var diff = (reversed[i].weight - reversed[i+1].weight).toFixed(1);
      change = diff > 0 ? ' + ' + diff : diff < 0 ? ' ' + diff : ' 0';
    }
    html += '<div class="list-row"><span class="l">' + reversed[i].date + '</span><span class="r">' + reversed[i].weight + ' kg' + change + '</span></div>';
  }
  c.innerHTML = html;
}
function renderWeightChart() {
  var svg = document.getElementById('weightChart');
  if (!svg) return;
  var logs = data.weightLog.slice(-30);
  if (logs.length < 2) { svg.innerHTML = '<text x="50%" y="50%" text-anchor="middle" fill="#6b7280" font-size="14" font-family="Inter,sans-serif">Need at least 2 entries</text>'; return; }
  var weights = logs.map(function(l) { return l.weight; });
  var minW = Math.min.apply(null, weights) - 1;
  var maxW = Math.max.apply(null, weights) + 1;
  var w = svg.clientWidth || 340, h = svg.clientHeight || 208;
  var pad = 40;
  function xs(i) { return pad + (i / (logs.length - 1)) * (w - pad * 2); }
  function ys(v) { return h - pad - ((v - minW) / (maxW - minW)) * (h - pad * 2); }

  var areaPath = 'M' + xs(0) + ',' + (h - pad) + ' ';
  for (var i = 0; i < logs.length; i++) { areaPath += 'L' + xs(i) + ',' + ys(logs[i].weight) + ' '; }
  areaPath += 'L' + xs(logs.length - 1) + ',' + (h - pad) + ' Z';
  var linePath = '';
  for (var i = 0; i < logs.length; i++) { linePath += (i ? 'L' : 'M') + xs(i) + ',' + ys(logs[i].weight) + ' '; }
  var circles = '';
  for (var i = 0; i < logs.length; i++) {
    circles += '<circle cx="' + xs(i) + '" cy="' + ys(logs[i].weight) + '" r="5" fill="#00f0a0" stroke="#0a0b0f" stroke-width="2.5" style="filter:drop-shadow(0 0 6px rgba(0,240,160,0.6));" />';
    circles += '<text x="' + xs(i) + '" y="' + (ys(logs[i].weight) - 14) + '" text-anchor="middle" fill="#a4b0be" font-size="11" font-family="Inter,sans-serif" font-weight="600">' + logs[i].weight + '</text>';
  }
  var grid = '';
  for (var i = 0; i <= 4; i++) {
    var y = pad + (i / 4) * (h - pad * 2);
    grid += '<line x1="' + pad + '" y1="' + y + '" x2="' + (w - pad) + '" y2="' + y + '" stroke="rgba(255,255,255,0.04)" stroke-width="1" />';
  }
  var html = '';
  html += '<defs><linearGradient id="areaGrad" x1="0" y1="0" x2="0" y2="1"><stop offset="0%" stop-color="rgba(0,240,160,0.2)"/><stop offset="100%" stop-color="rgba(0,240,160,0)"/></linearGradient></defs>';
  html += grid;
  html += '<path d="' + areaPath + '" fill="url(#areaGrad)" />';
  html += '<path d="' + linePath + '" fill="none" stroke="#00f0a0" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" style="filter:drop-shadow(0 0 8px rgba(0,240,160,0.4));" />';
  html += circles;
  svg.innerHTML = html;
}

// ================= ANALYTICS =================
var analyticsView = 'prs';
function setAnalyticsView(v) {
  analyticsView = v;
  var btns = document.querySelectorAll('#analytics .toggle button');
  var labels = {prs: 'PRs', exercise: 'Exercises', volume: 'Volume'};
  for (var i = 0; i < btns.length; i++) {
    btns[i].classList.toggle('active', btns[i].textContent.includes(labels[v]));
  }
  renderAnalytics();
}
function getExerciseHistory(exName) {
  var history = [];
  var keys = Object.keys(data.workouts).sort();
  for (var i = 0; i < keys.length; i++) {
    var w = data.workouts[keys[i]];
    for (var j = 0; j < w.exercises.length; j++) {
      if (w.exercises[j].name === exName) {
        var maxSet = null;
        for (var k = 0; k < w.exercises[j].sets.length; k++) {
          var s = w.exercises[j].sets[k];
          if (s.done) {
            var vol = (parseFloat(s.weight)||0) * (parseInt(s.reps)||0);
            if (!maxSet || vol > maxSet.vol) maxSet = {weight: parseFloat(s.weight)||0, reps: parseInt(s.reps)||0, vol: vol, date: keys[i]};
          }
        }
        if (maxSet) {
          var totalVol = 0, doneSets = 0;
          for (var k = 0; k < w.exercises[j].sets.length; k++) {
            var s = w.exercises[j].sets[k];
            if (s.done) { totalVol += (parseFloat(s.weight)||0) * (parseInt(s.reps)||0); doneSets++; }
          }
          history.push({weight: maxSet.weight, reps: maxSet.reps, vol: maxSet.vol, date: maxSet.date, totalVol: totalVol, sets: doneSets});
        }
      }
    }
  }
  return history;
}
function renderAnalytics() {
  var c = document.getElementById('analyticsContent');
  if (!c) return;
  var workouts = Object.values(data.workouts);
  if (!workouts.length) { c.innerHTML = '<div class="card empty-state"><div style="font-size:48px;margin-bottom:12px;">&#128202;</div><div>No workout data yet.</div><div class="muted" style="margin-top:8px;">Complete workouts to see analytics</div></div>'; return; }

  if (analyticsView === 'prs') {
    var prs = {};
    var wKeys = Object.keys(data.workouts);
    for (var i = 0; i < wKeys.length; i++) {
      var w = data.workouts[wKeys[i]];
      for (var j = 0; j < w.exercises.length; j++) {
        var e = w.exercises[j];
        for (var k = 0; k < e.sets.length; k++) {
          var s = e.sets[k];
          if (!s.done) continue;
          var wgt = parseFloat(s.weight) || 0;
          var reps = parseInt(s.reps) || 0;
          var vol = wgt * reps;
          if (!prs[e.name]) prs[e.name] = {maxWeight: 0, maxVol: 0, history: []};
          prs[e.name].history.push({date: wKeys[i], weight: wgt, reps: reps, vol: vol});
          if (wgt > prs[e.name].maxWeight) { prs[e.name].maxWeight = wgt; prs[e.name].bestWeight = {wgt: wgt, reps: reps, date: wKeys[i]}; }
          if (vol > prs[e.name].maxVol) { prs[e.name].maxVol = vol; prs[e.name].bestVol = {wgt: wgt, reps: reps, vol: vol, date: wKeys[i]}; }
        }
      }
    }
    var html = '<div class="card"><div class="card-title">Personal Records</div>';
    html += '<table class="pr-table"><thead><tr><th>Exercise</th><th>Max Weight</th><th>Max Volume</th><th>History</th></tr></thead><tbody>';
    var prEntries = Object.entries(prs).sort(function(a,b) { return b[1].maxWeight - a[1].maxWeight; });
    for (var i = 0; i < prEntries.length; i++) {
      var name = prEntries[i][0], p = prEntries[i][1];
      html += '<tr><td style="font-weight:700;">' + name + '</td>';
      html += '<td><span class="pr-tag">' + p.bestWeight.wgt + 'kg x ' + p.bestWeight.reps + '</span><div style="font-size:11px;color:var(--muted);margin-top:4px;">' + p.bestWeight.date + '</div></td>';
      html += '<td>' + Math.round(p.maxVol).toLocaleString() + ' kg<br><span style="font-size:11px;color:var(--muted);">@ ' + p.bestVol.wgt + 'x' + p.bestVol.reps + '</span></td>';
      html += '<td style="text-align:right;"><span class="pr-tag">' + p.history.length + ' sessions</span></td></tr>';
    }
    html += '</tbody></table></div>';
    if (prs['Deadlift']) {
      var dl = prs['Deadlift'];
      html += '<div class="card"><div class="card-title">Deadlift Progress</div>';
      html += '<div class="chart-wrap" style="height:180px;"><svg class="chart-svg" id="dlChart"></svg></div></div>';
      setTimeout(function() { renderExerciseChart('dlChart', dl.history.slice(-20), 'weight'); }, 50);
    }
    c.innerHTML = html;
  }

  if (analyticsView === 'exercise') {
    var exNames = [];
    var wKeys = Object.keys(data.workouts);
    for (var i = 0; i < wKeys.length; i++) {
      for (var j = 0; j < data.workouts[wKeys[i]].exercises.length; j++) {
        var name = data.workouts[wKeys[i]].exercises[j].name;
        if (exNames.indexOf(name) === -1) exNames.push(name);
      }
    }
    var html = '';
    for (var i = 0; i < exNames.length; i++) {
      var hist = getExerciseHistory(exNames[i]);
      if (!hist.length) continue;
      var chartId = 'ex-chart-' + exNames[i].replace(/\s+/g, '-');
      var maxW = Math.max.apply(null, hist.map(function(h) { return h.weight; }));
      var maxV = Math.max.apply(null, hist.map(function(h) { return h.totalVol; }));
      html += '<div class="card"><div class="card-title">' + exNames[i] + ' <span style="font-size:13px;color:var(--muted);">' + hist.length + ' sessions</span></div>';
      html += '<div style="display:flex;gap:12px;margin-bottom:12px;">';
      html += '<div class="stat-box" style="flex:1;"><div class="val">' + maxW + 'kg</div><div class="lbl">Best Weight</div></div>';
      html += '<div class="stat-box" style="flex:1;"><div class="val">' + Math.round(maxV).toLocaleString() + '</div><div class="lbl">Best Volume</div></div>';
      html += '<div class="stat-box" style="flex:1;"><div class="val">' + hist[hist.length-1].weight + 'kg</div><div class="lbl">Last</div></div>';
      html += '</div>';
      html += '<div class="chart-wrap" style="height:160px;"><svg class="chart-svg" id="' + chartId + '"></svg></div>';
      html += '</div>';
      (function(id, h) {
        setTimeout(function() { renderExerciseChart(id, h, 'weight'); }, 50);
      })(chartId, hist);
    }
    c.innerHTML = html || '<div class="card empty-state">No exercise data found.</div>';
  }

  if (analyticsView === 'volume') {
    var days = Object.entries(data.workouts).sort(function(a,b) { return a[0].localeCompare(b[0]); });
    var html = '<div class="card"><div class="card-title">Total Volume Per Workout</div>';
    html += '<div class="chart-wrap"><svg class="chart-svg" id="volumeChart"></svg></div></div>';
    var totalVol = 0, totalSets = 0, maxVol = 0, maxVolDay = '';
    for (var i = 0; i < days.length; i++) {
      var v = 0, s = 0;
      for (var j = 0; j < days[i][1].exercises.length; j++) {
        for (var k = 0; k < days[i][1].exercises[j].sets.length; k++) {
          var st = days[i][1].exercises[j].sets[k];
          if (st.done) { v += (parseFloat(st.weight)||0) * (parseInt(st.reps)||0); s++; }
        }
      }
      totalVol += v; totalSets += s;
      if (v > maxVol) { maxVol = v; maxVolDay = days[i][0]; }
    }
    html += '<div class="progress-grid">';
    html += '<div class="big-stat"><div class="num">' + Math.round(totalVol).toLocaleString() + '</div><div class="label">Total Volume</div></div>';
    html += '<div class="big-stat"><div class="num">' + totalSets + '</div><div class="label">Total Sets</div></div>';
    html += '<div class="big-stat"><div class="num">' + Math.round(maxVol).toLocaleString() + '</div><div class="label">Peak Volume</div></div>';
    html += '<div class="big-stat"><div class="num">' + maxVolDay + '</div><div class="label">Best Day</div></div>';
    html += '</div>';
    var exVolumes = {};
    for (var i = 0; i < days.length; i++) {
      for (var j = 0; j < days[i][1].exercises.length; j++) {
        var name = days[i][1].exercises[j].name;
        if (!exVolumes[name]) exVolumes[name] = 0;
        for (var k = 0; k < days[i][1].exercises[j].sets.length; k++) {
          var st = days[i][1].exercises[j].sets[k];
          if (st.done) exVolumes[name] += (parseFloat(st.weight)||0) * (parseInt(st.reps)||0);
        }
      }
    }
    html += '<div class="card"><div class="card-title">Volume by Exercise</div>';
    var evEntries = Object.entries(exVolumes).sort(function(a,b) { return b[1] - a[1]; });
    for (var i = 0; i < evEntries.length; i++) {
      html += '<div class="list-row"><span class="l">' + evEntries[i][0] + '</span><span class="r">' + Math.round(evEntries[i][1]).toLocaleString() + ' kg</span></div>';
    }
    html += '</div>';
    c.innerHTML = html;
    setTimeout(function() {
      var chartData = [];
      for (var i = 0; i < days.length; i++) {
        var v = 0;
        for (var j = 0; j < days[i][1].exercises.length; j++) {
          for (var k = 0; k < days[i][1].exercises[j].sets.length; k++) {
            var s = days[i][1].exercises[j].sets[k];
            if (s.done) v += (parseFloat(s.weight)||0) * (parseInt(s.reps)||0);
          }
        }
        chartData.push({date: days[i][0], value: v});
      }
      renderBarChart('volumeChart', chartData);
    }, 50);
  }
}
function renderExerciseChart(svgId, history, metric) {
  var svg = document.getElementById(svgId);
  if (!svg) return;
  if (history.length < 2) { svg.innerHTML = '<text x="50%" y="50%" text-anchor="middle" fill="#6b7280" font-size="12" font-family="Inter,sans-serif">Need more data</text>'; return; }
  var vals = history.map(function(h) { return h[metric]; });
  var minV = Math.min.apply(null, vals) * 0.95;
  var maxV = Math.max.apply(null, vals) * 1.05;
  var w = svg.clientWidth || 320, h = svg.clientHeight || 148, pad = 30;
  function xs(i) { return pad + (i / (history.length - 1)) * (w - pad * 2); }
  function ys(v) { return h - pad - ((v - minV) / (maxV - minV)) * (h - pad * 2); }
  var path = '';
  for (var i = 0; i < history.length; i++) { path += (i ? 'L' : 'M') + xs(i) + ',' + ys(history[i][metric]) + ' '; }
  var circles = '';
  for (var i = 0; i < history.length; i++) {
    circles += '<circle cx="' + xs(i) + '" cy="' + ys(history[i][metric]) + '" r="4" fill="#00f0a0" stroke="#0a0b0f" stroke-width="2" />';
  }
  var html = '<path d="' + path + '" fill="none" stroke="#00f0a0" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round" style="filter:drop-shadow(0 0 6px rgba(0,240,160,0.4));" />';
  html += circles;
  var last = history[history.length-1];
  html += '<text x="' + xs(history.length-1) + '" y="' + (ys(last[metric]) - 10) + '" text-anchor="end" fill="#a4b0be" font-size="11" font-family="Inter,sans-serif" font-weight="700">' + last[metric] + (metric==='weight'?'kg':'') + '</text>';
  svg.innerHTML = html;
}
function renderBarChart(svgId, chartData) {
  var svg = document.getElementById(svgId);
  if (!svg) return;
  if (chartData.length < 2) { svg.innerHTML = '<text x="50%" y="50%" text-anchor="middle" fill="#6b7280" font-size="12">Need more data</text>'; return; }
  var maxVal = Math.max.apply(null, chartData.map(function(d) { return d.value; }));
  if (maxVal < 1) maxVal = 1;
  var w = svg.clientWidth || 320, h = svg.clientHeight || 188, pad = 30;
  var barW = Math.max(4, (w - pad * 2) / chartData.length * 0.7);
  var gap = (w - pad * 2) / chartData.length;
  var html = '';
  for (var i = 0; i < chartData.length; i++) {
    var x = pad + i * gap + (gap - barW) / 2;
    var barH = ((chartData[i].value / maxVal) * (h - pad * 2));
    var y = h - pad - barH;
    html += '<rect x="' + x + '" y="' + y + '" width="' + barW + '" height="' + barH + '" rx="4" fill="url(#barGrad)" style="filter:drop-shadow(0 0 4px rgba(0,240,160,0.3));" />';
  }
  html += '<defs><linearGradient id="barGrad" x1="0" y1="0" x2="0" y2="1"><stop offset="0%" stop-color="#00f0a0"/><stop offset="100%" stop-color="#00c07d"/></linearGradient></defs>';
  svg.innerHTML = html;
}

// ================= STATS =================
var statsView = 'week';
function setStatsView(v) {
  statsView = v;
  var btns = document.querySelectorAll('#stats .toggle button');
  for (var i = 0; i < btns.length; i++) {
    btns[i].classList.toggle('active', btns[i].textContent.toLowerCase().indexOf(v === 'all' ? 'all' : v) !== -1);
  }
  renderStats();
}
function renderStats() {
  var c = document.getElementById('statsContent');
  if (!c) return;
  var workouts = Object.entries(data.workouts);
  if (!workouts.length) { c.innerHTML = '<div class="card empty-state"><div style="font-size:48px;margin-bottom:12px;">&#128202;</div><div>No workout data yet.</div><div class="muted" style="margin-top:8px;">Complete your first workout</div></div>'; return; }
  var now = new Date();
  var daysBack = statsView === 'week' ? 7 : statsView === 'month' ? 30 : 99999;
  var cutoff = new Date(now);
  if (daysBack < 99999) cutoff.setDate(cutoff.getDate() - daysBack);
  cutoff.setHours(0,0,0,0);
  var recent = [];
  for (var i = 0; i < workouts.length; i++) {
    if (parseDate(workouts[i][0]) >= cutoff) recent.push(workouts[i]);
  }
  var totalTime = 0, totalSets = 0, totalVol = 0, totalWorkouts = recent.length;
  var dayMap = {}, exFreq = {};
  for (var i = 0; i < recent.length; i++) {
    totalTime += recent[i][1].durationSec || 0;
    var ds = 0, dv = 0;
    for (var j = 0; j < recent[i][1].exercises.length; j++) {
      var e = recent[i][1].exercises[j];
      if (!exFreq[e.name]) exFreq[e.name] = {count: 0, vol: 0};
      exFreq[e.name].count++;
      for (var k = 0; k < e.sets.length; k++) {
        if (e.sets[k].done) {
          ds++;
          dv += (parseFloat(e.sets[k].weight)||0) * (parseInt(e.sets[k].reps)||0);
          exFreq[e.name].vol += (parseFloat(e.sets[k].weight)||0) * (parseInt(e.sets[k].reps)||0);
        }
      }
    }
    totalSets += ds;
    totalVol += dv;
    dayMap[recent[i][0]] = (dayMap[recent[i][0]] || 0) + ds;
  }
  var hh = String(Math.floor(totalTime/3600)).padStart(2,'0');
  var mm = String(Math.floor((totalTime%3600)/60)).padStart(2,'0');
  var html = '<div class="stats-grid">';
  html += '<div class="big-stat"><div class="num">' + totalWorkouts + '</div><div class="label">Workouts</div></div>';
  html += '<div class="big-stat"><div class="num">' + totalSets + '</div><div class="label">Total Sets</div></div>';
  html += '<div class="big-stat"><div class="num">' + hh + ':' + mm + '</div><div class="label">Time Spent</div></div>';
  html += '<div class="big-stat"><div class="num">' + Math.round(totalVol).toLocaleString() + '</div><div class="label">Volume (kg)</div></div>';
  html += '</div>';
  html += '<div class="card"><div class="card-title">Sets Per Day</div><div style="display:flex;align-items:flex-end;gap:6px;height:160px;padding-top:10px;">';
  var dayKeys = Object.keys(dayMap).sort();
  var maxDay = 1;
  for (var k in dayMap) { if (dayMap[k] > maxDay) maxDay = dayMap[k]; }
  for (var i = 0; i < dayKeys.length; i++) {
    var sets = dayMap[dayKeys[i]];
    var pct = (sets / maxDay) * 100;
    html += '<div style="flex:1;display:flex;flex-direction:column;align-items:center;gap:6px;min-width:30px;"><div style="width:100%;background:rgba(0,0,0,0.3);border-radius:8px;height:100px;position:relative;overflow:hidden;"><div style="position:absolute;bottom:0;width:100%;background:linear-gradient(180deg,var(--accent) 0%,var(--accent2) 100%);height:' + pct + '%;border-radius:8px 8px 0 0;transition:.5s;box-shadow:0 0 20px var(--accent-glow);"></div></div><span style="font-size:10px;color:var(--muted);font-weight:600;">' + dayKeys[i].slice(5) + '</span></div>';
  }
  html += '</div></div>';
  html += '<div class="card"><div class="card-title">Exercise Breakdown</div>';
  var efEntries = Object.entries(exFreq).sort(function(a,b) { return b[1].vol - a[1].vol; });
  for (var i = 0; i < efEntries.length; i++) {
    html += '<div class="list-row"><span class="l">' + efEntries[i][0] + '</span><span class="r">' + efEntries[i][1].count + 'x &bull; ' + Math.round(efEntries[i][1].vol).toLocaleString() + ' kg</span></div>';
  }
  html += '</div>';
  var recentWeights = [];
  for (var i = 0; i < data.weightLog.length; i++) {
    if (parseDate(data.weightLog[i].date) >= cutoff) recentWeights.push(data.weightLog[i]);
  }
  if (recentWeights.length >= 2) {
    var firstW = recentWeights[0].weight, lastW = recentWeights[recentWeights.length-1].weight;
    var change = (lastW - firstW).toFixed(1);
    var changeText = change > 0 ? '+' + change + ' kg' : change + ' kg';
    var changeColor = change > 0 ? 'var(--warn)' : (change < 0 ? 'var(--accent)' : 'var(--muted)');
    html += '<div class="card"><div class="card-title">Weight Change</div><div style="display:flex;gap:12px;align-items:center;"><div class="stat-box" style="flex:1;"><div class="val">' + firstW + ' kg</div><div class="lbl">Start</div></div><div style="font-size:20px;color:' + changeColor + ';font-weight:800;">' + changeText + '</div><div class="stat-box" style="flex:1;"><div class="val">' + lastW + ' kg</div><div class="lbl">Current</div></div></div></div>';
  }
  c.innerHTML = html;
}

// ================= INIT =================
function initAll() {
  renderDashboard();
  renderRoutines();
  renderWeightPage();
  renderStats();
  renderWorkoutPage();
  renderAnalytics();
}

// Auto-login check
updateStorageStatus();
var accounts = getAccounts();
var savedUser = getSession();
if (savedUser && accounts[savedUser]) {
  currentUser = savedUser;
  data = getUserData();
  enterApp();
}

})();
</script>
</body>
</html>
