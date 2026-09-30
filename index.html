<!doctype html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Lane Defense - Ultimate Edition</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Fira+Sans:ital,wght@0,500;0,700;0,800;0,900;1,700&family=Caveat:wght@700&display=swap" rel="stylesheet">
<style>
:root {
  --bg-dark: #070c14;
  --gold-accent: #facc15;
}

* { box-sizing: border-box; user-select: none; }
html, body {
  margin: 0; padding: 0;
  background: var(--bg-dark);
  font-family: "Fira Sans", system-ui, sans-serif;
  color: #fff;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow-x: hidden;
}

/* Main Frame 16:9 Aspect Ratio */
.game-frame {
  width: min(100vw, 1040px);
  aspect-ratio: 16 / 9;
  position: relative;
  border-radius: 20px;
  overflow: hidden;
  box-shadow: 0 0 50px rgba(0, 0, 0, 0.95), 0 0 25px rgba(250, 204, 21, 0.2);
  border: 4px solid #1e293b;
  background: #0f172a;
}

/* Animations */
.float-anim-1 { animation: floatBob 6s ease-in-out infinite alternate; }
.float-anim-2 { animation: floatBob 8s ease-in-out infinite alternate-reverse; }
@keyframes floatBob {
  0% { transform: translateY(0px); }
  100% { transform: translateY(-12px); }
}

/* Hexagon Nav Buttons in Lobby */
.nav-hex-btn {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 4px;
  cursor: pointer;
  background: none;
  border: none;
}

.hex-icon-box {
  width: 52px;
  height: 58px;
  clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
  background: linear-gradient(180deg, #ffe082 0%, #b87c28 100%);
  padding: 3px;
  display: flex;
  align-items: center;
  justify-content: center;
  transition: transform 0.15s, filter 0.15s;
  box-shadow: 0 4px 10px rgba(0,0,0,0.5);
}

.hex-icon-inner {
  width: 100%;
  height: 100%;
  clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
  background: linear-gradient(180deg, #2b78a3 0%, #103c58 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 22px;
}

.nav-hex-btn:hover .hex-icon-box {
  transform: translateY(-4px) scale(1.08);
  filter: brightness(1.2);
}

.nav-label {
  font-size: 11px;
  font-weight: 800;
  color: #ffffff;
  text-shadow: 0 2px 4px rgba(0,0,0,0.9), 0 0 2px #000;
}

/* Ribbon Button in Lobby */
.start-ribbon-btn {
  position: relative;
  height: 58px;
  padding-left: 50px;
  padding-right: 26px;
  background: linear-gradient(180deg, #fce092 0%, #d88a24 50%, #9e560f 100%);
  border: 3px solid #fff2ba;
  border-radius: 40px 16px 16px 40px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  box-shadow: 0 6px 16px rgba(0,0,0,0.6), inset 0 2px 0 rgba(255,255,255,0.6);
  transition: transform 0.15s, filter 0.15s;
}

.start-ribbon-btn:hover {
  transform: scale(1.05);
  filter: brightness(1.15);
}

.compass-icon {
  position: absolute;
  left: -8px;
  top: 50%;
  transform: translateY(-50%);
  width: 58px;
  height: 58px;
  border-radius: 50%;
  background: radial-gradient(circle at 35% 35%, #ffffff, #ffd700 60%, #b87c28);
  border: 4px solid #fff2ba;
  box-shadow: 0 4px 10px rgba(0,0,0,0.5);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 30px;
}

/* Team Setup Wooden Shelf */
.wooden-shelf {
  background: linear-gradient(180deg, #965d2a 0%, #633912 60%, #3d2008 100%);
  border: 3px solid #fcd34d;
  border-radius: 12px;
  box-shadow: 0 8px 20px rgba(0,0,0,0.6), inset 0 2px 4px rgba(255,255,255,0.3);
  position: relative;
}

.shelf-slot {
  position: relative;
  width: 68px;
  height: 80px;
  background: linear-gradient(180deg, #fef08a 0%, #d97706 100%);
  border: 2px solid #78350f;
  border-radius: 8px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  padding: 4px;
  cursor: pointer;
  box-shadow: inset 0 2px 0 rgba(255,255,255,0.5), 0 4px 8px rgba(0,0,0,0.4);
  transition: transform 0.12s, filter 0.12s;
  overflow: hidden;
}

.shelf-slot:hover { transform: translateY(-3px); filter: brightness(1.1); }

.empty-shelf-slot {
  background: linear-gradient(180deg, #5c3517 0%, #3a1e0a 100%);
  border: 2px dashed #ca8a04;
  opacity: 0.85;
}
.empty-shelf-slot:hover { opacity: 1; border-style: solid; border-color: #fde047; }

/* Parchment Hero Cards */
.parchment-card {
  width: 142px;
  min-width: 142px;
  height: 230px;
  background: linear-gradient(180deg, #fff7ed 0%, #ffedd5 40%, #fed7aa 100%);
  border: 3px solid #854d0e;
  border-radius: 14px;
  padding: 6px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  position: relative;
  box-shadow: 0 6px 14px rgba(0,0,0,0.5), inset 0 2px 0 rgba(255,255,255,0.8);
  cursor: pointer;
  transition: transform 0.15s, filter 0.15s;
}

.parchment-card:hover { transform: translateY(-5px); filter: brightness(1.05); }

.parchment-card.star-8 {
  border-color: #f43f5e;
  box-shadow: 0 0 20px rgba(244, 63, 94, 0.8), 0 0 10px rgba(250, 204, 21, 0.6);
  animation: auraGlow 3s ease-in-out infinite alternate;
}
@keyframes auraGlow {
  0% { filter: drop-shadow(0 0 2px #ef4444); }
  100% { filter: drop-shadow(0 0 8px #facc15); }
}

.act-badge {
  position: absolute;
  top: 4px;
  left: 4px;
  background: linear-gradient(180deg, #ef4444 0%, #b91c1c 100%);
  color: #fff;
  border: 1.5px solid #fde047;
  border-radius: 6px;
  font-size: 10px;
  font-weight: 900;
  padding: 1px 5px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.4);
}

.slot-badge {
  position: absolute;
  top: 4px;
  right: 4px;
  background: #78350f;
  color: #fde047;
  border: 1.5px solid #d97706;
  border-radius: 50%;
  width: 20px;
  height: 20px;
  font-size: 10px;
  font-weight: 900;
  display: grid;
  place-items: center;
}

.lock-badge {
  position: absolute;
  bottom: 26px;
  right: 4px;
  font-size: 14px;
  filter: drop-shadow(0 2px 2px rgba(0,0,0,0.8));
}

.oval-btn {
  padding: 7px 18px;
  border-radius: 9999px;
  font-weight: 900;
  font-size: 12px;
  border: 2px solid #fef08a;
  box-shadow: 0 4px 10px rgba(0,0,0,0.5), inset 0 2px 0 rgba(255,255,255,0.4);
  cursor: pointer;
  transition: transform 0.12s, filter 0.12s;
  display: flex;
  align-items: center;
  gap: 5px;
}
.oval-btn:hover { transform: scale(1.05); filter: brightness(1.15); }
.oval-btn-blue { background: linear-gradient(180deg, #0284c7 0%, #0369a1 100%); color: #fff; }
.oval-btn-purple { background: linear-gradient(180deg, #8b5cf6 0%, #6d28d9 100%); color: #fff; }
.oval-btn-gold { background: linear-gradient(180deg, #eab308 0%, #ca8a04 100%); color: #0f172a; }

/* Character Popover Context Menu */
.char-popover-menu {
  position: absolute;
  z-index: 60;
  width: 125px;
  background: linear-gradient(180deg, #fef08a 0%, #fef3c7 40%, #fde047 100%);
  border: 2.5px solid #92400e;
  border-radius: 12px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.8), inset 0 2px 0 rgba(255,255,255,0.8);
  padding: 4px;
  display: flex;
  flex-direction: column;
  gap: 3px;
  animation: popIn 0.15s ease-out;
}
@keyframes popIn {
  from { opacity: 0; transform: scale(0.85); }
  to { opacity: 1; transform: scale(1); }
}

.popover-btn {
  width: 100%;
  padding: 5px 8px;
  border-radius: 6px;
  font-size: 11px;
  font-weight: 800;
  color: #451a03;
  text-align: center;
  background: transparent;
  border: 1px solid transparent;
  cursor: pointer;
  transition: background 0.1s;
}
.popover-btn:hover {
  background: #fde047;
  border-color: #b45309;
}
.popover-btn-close {
  background: linear-gradient(180deg, #f59e0b 0%, #d97706 100%);
  color: #ffffff;
  border: 1px solid #78350f;
  margin-top: 2px;
}

/* Item Screen Layout */
.item-slot-box {
  width: 48px;
  height: 48px;
  border-radius: 10px;
  border: 2px solid #78350f;
  background: linear-gradient(180deg, #78350f 0%, #451a03 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  cursor: pointer;
  box-shadow: inset 0 2px 4px rgba(0,0,0,0.6);
}
.item-slot-box.has-item {
  border-color: #fde047;
  background: linear-gradient(180deg, #0284c7 0%, #0369a1 100%);
}

.item-card-mini {
  position: relative;
  width: 72px;
  height: 82px;
  border-radius: 10px;
  border: 2px solid #78350f;
  background: linear-gradient(180deg, #ca8a04 0%, #854d0e 100%);
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  padding: 3px;
  cursor: pointer;
  box-shadow: 0 4px 8px rgba(0,0,0,0.5);
  transition: transform 0.12s;
}
.item-card-mini:hover { transform: translateY(-3px); }

.item-grade-badge {
  position: absolute;
  top: 2px;
  left: 2px;
  font-size: 10px;
  font-weight: 900;
  padding: 0px 4px;
  border-radius: 4px;
  color: #fff;
}
.grade-F { background: #64748b; }
.grade-E { background: #b45309; }
.grade-D { background: #0284c7; }
.grade-C { background: #7e22ce; }
.grade-B { background: #eab308; color: #000; }

.equip-tag {
  position: absolute;
  top: 2px;
  left: 2px;
  background: #22c55e;
  color: #fff;
  font-size: 8px;
  font-weight: 900;
  padding: 1px 3px;
  border-radius: 3px;
}
.new-tag {
  position: absolute;
  top: 2px;
  right: 2px;
  background: #ef4444;
  color: #fff;
  font-size: 8px;
  font-weight: 900;
  border-radius: 50%;
  width: 14px;
  height: 14px;
  display: grid;
  place-items: center;
}

/* Gacha Track */
.gacha-track {
  display: flex;
  gap: 14px;
  overflow-x: auto;
  padding: 12px 6px;
  scroll-snap-type: x mandatory;
}

.gacha-card {
  scroll-snap-align: center;
  flex: 0 0 200px;
  height: 300px;
  position: relative;
  border-radius: 18px;
  border: 3.5px solid #fef08a;
  background: linear-gradient(180deg, #f87171 0%, #dc2626 40%, #b91c1c 100%);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  padding: 10px 8px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.7);
  transition: transform 0.2s, filter 0.2s;
  cursor: pointer;
  overflow: hidden;
}
.gacha-card:hover {
  transform: translateY(-6px) scale(1.02);
  filter: brightness(1.1);
  box-shadow: 0 12px 28px rgba(0,0,0,0.8), 0 0 15px #fde047;
}

.gacha-card.theme-gold {
  background: linear-gradient(180deg, #fde047 0%, #eab308 40%, #ca8a04 100%);
  border-color: #ffffff;
}
.gacha-card.theme-purple {
  background: linear-gradient(180deg, #c084fc 0%, #a855f7 40%, #7e22ce 100%);
  border-color: #fef08a;
}

.event-ribbon {
  position: absolute;
  top: 12px; right: -28px;
  transform: rotate(25deg);
  background: linear-gradient(180deg, #ef4444 0%, #991b1b 100%);
  color: #ffffff;
  border: 1.5px solid #fef08a;
  font-size: 8px;
  font-weight: 900;
  padding: 2px 26px;
  text-transform: uppercase;
}

/* Shop Card Styles */
.shop-card {
  border-radius: 18px;
  border: 3px solid #fde047;
  padding: 10px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0 10px 25px rgba(0,0,0,0.7);
  transition: transform 0.15s, filter 0.15s;
}
.shop-card:hover { transform: translateY(-4px); filter: brightness(1.1); }

/* Upgrade Card Styles */
.upgrade-card {
  background: linear-gradient(180deg, #ffffff 0%, #f1f5f9 60%, #e2e8f0 100%);
  border: 3px solid #0284c7;
  border-radius: 16px;
  padding: 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  box-shadow: 0 8px 18px rgba(0,0,0,0.5);
  color: #0f172a;
}

/* Four Guardian Gods Temple */
.god-card {
  width: 185px;
  height: 300px;
  border-radius: 14px;
  position: relative;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  border: 3.5px solid #334155;
  background: #0f172a;
  cursor: pointer;
  transition: transform 0.2s, filter 0.2s;
  box-shadow: 0 10px 25px rgba(0,0,0,0.8);
}
.god-card.active-god {
  border-color: #fde047;
  box-shadow: 0 0 25px rgba(250, 204, 21, 0.8);
}
.god-card.active-god:hover { transform: translateY(-6px) scale(1.03); }
.god-card.locked-god { filter: grayscale(0.85) brightness(0.65); cursor: not-allowed; }

.god-title-banner {
  width: 90%; margin: 10px auto 0; padding: 4px 8px;
  border-radius: 8px; font-weight: 900; font-size: 12px;
  text-align: center; color: #ffffff; border: 2px solid #ffffff;
}
.bg-azure-banner { background: linear-gradient(180deg, #38bdf8 0%, #0284c7 100%); }
.bg-tiger-banner { background: linear-gradient(180deg, #f59e0b 0%, #d97706 100%); }
.bg-tortoise-banner { background: linear-gradient(180deg, #22c55e 0%, #15803d 100%); }
.bg-vermilion-banner { background: linear-gradient(180deg, #ef4444 0%, #b91c1c 100%); }

/* Azure Dragon Temple Pity Pillar */
.pity-pillar-container {
  width: 70px; height: 270px; position: relative;
  display: flex; flex-direction: column; align-items: center;
}
.pity-pillar-body {
  width: 40px; height: 210px;
  background: linear-gradient(180deg, #475569 0%, #1e293b 100%);
  border: 3px solid #94a3b8; border-radius: 20px;
  position: relative; overflow: hidden;
  display: flex; flex-direction: column-reverse; padding: 3px;
}
.pity-pillar-fill {
  width: 100%;
  background: linear-gradient(180deg, #38bdf8 0%, #1d4ed8 100%);
  border-radius: 16px; transition: height 0.3s ease-out;
  box-shadow: 0 0 12px #38bdf8;
}

.bottom-dock {
  background: linear-gradient(180deg, #38c823 0%, #208e10 100%);
  border-top: 4px solid #1c6d0c;
  padding: 8px 12px; display: flex; align-items: center; gap: 10px;
}

.hex-btn {
  position: relative; width: 64px; height: 64px;
  clip-path: polygon(50% 0%, 93% 25%, 93% 75%, 50% 100%, 7% 75%, 7% 25%);
  display: flex; flex-direction: column; align-items: center; justify-content: center;
  cursor: pointer; transition: transform 0.1s;
}
.hex-btn:hover:not(:disabled) { transform: scale(1.06); }
.hex-btn:disabled { filter: grayscale(0.8) brightness(0.7); cursor: not-allowed; }
.hex-red { background: linear-gradient(180deg, #ff5e3a 0%, #d82300 100%); border: 3px solid #ffe17d; }
.hex-blue { background: linear-gradient(180deg, #3db2f6 0%, #1765c1 100%); border: 3px solid #b8f0ff; }

.card-slot {
  position: relative; flex: 1; max-width: 82px; aspect-ratio: 0.82;
  background: linear-gradient(180deg, #f2d49b 0%, #c99347 100%);
  border: 3px solid #734515; border-radius: 10px; padding: 3px;
  display: flex; flex-direction: column; align-items: center; justify-content: space-between;
  cursor: pointer; transition: transform 0.12s;
}
.card-slot:hover:not(:disabled) { transform: translateY(-4px); }
.card-slot:disabled { filter: grayscale(0.7) brightness(0.7); cursor: not-allowed; }

.cooldown-overlay {
  position: absolute; inset: 0; background: rgba(10, 15, 25, 0.78);
  border-radius: 7px; display: flex; align-items: center; justify-content: center;
  font-size: 18px; font-weight: 900; color: #fff;
}
</style>
</head>
<body>

<div class="game-frame" id="app">

  <!-- ==================== LOBBY SCREEN ==================== -->
  <section class="absolute inset-0 overflow-hidden" id="lobby">
    <svg class="absolute inset-0 w-full h-full" viewBox="0 0 1600 900" preserveAspectRatio="xMidYMid slice">
      <defs>
        <linearGradient id="sk" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#1e70d6"/>
          <stop offset="50%" stop-color="#4ea8ee"/>
          <stop offset="100%" stop-color="#c1e8f8"/>
        </linearGradient>
        <linearGradient id="gr" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stop-color="#91cf3e"/>
          <stop offset="50%" stop-color="#55a024"/>
          <stop offset="100%" stop-color="#184a1a"/>
        </linearGradient>
      </defs>
      <rect width="1600" height="900" fill="url(#sk)"/>
      <polygon points="-50,650 250,220 380,380 480,280 800,650" fill="#326abf"/>
      <polygon points="850,680 1200,420 1650,260 1650,680" fill="#2856a6"/>
      <path d="M0,640 Q400,540 900,620 T1600,570 V900 H0Z" fill="url(#gr)"/>
    </svg>

    <!-- Center Shrine Sign: "Temple of Four Gods" -->
    <div class="absolute top-[28%] left-1/2 transform -translate-x-1/2 -translate-y-1/2 cursor-pointer transition-transform hover:scale-110" 
         data-open="modalGuardianTemple">
      <div class="px-6 py-2 rounded-full border-2 border-yellow-300 bg-gradient-to-r from-cyan-500 via-teal-600 to-cyan-500 text-white font-extrabold text-sm md:text-base shadow-2xl tracking-wider flex items-center gap-2">
        <span>✨</span> Temple of Four Gods <span>✨</span>
      </div>
    </div>

    <!-- Top-Left Player Profile -->
    <div class="absolute top-3 left-3 flex items-center h-12">
      <div class="w-12 h-12 rounded-xl border-2 border-yellow-400 bg-emerald-500 flex items-center justify-center text-2xl shadow-md z-10">🐧</div>
      <div class="flex items-center -ml-2 pl-4 pr-4 h-9 bg-gradient-to-r from-blue-900 to-indigo-950 border-y-2 border-r-2 border-yellow-400 rounded-r-2xl gap-2 shadow-md">
        <span class="text-xs font-black text-white">trungsinheldorado@gmail.com</span>
      </div>
    </div>

    <!-- Top Currencies Bar -->
    <div class="absolute top-3 right-3 flex items-center gap-1.5">
      <div class="bg-slate-900/90 border border-emerald-400 rounded-full px-2.5 py-0.5 flex items-center gap-1 text-[11px] font-black text-emerald-300 shadow">
        <span>💵</span> <span class="coins-val">0</span>
      </div>
      <div class="bg-slate-900/90 border border-cyan-400 rounded-full px-2.5 py-0.5 flex items-center gap-1 text-[11px] font-black text-cyan-300 shadow">
        <span>☁️</span> <span class="cloud-val">0</span>
      </div>
      <div class="bg-slate-900/90 border border-slate-600 rounded-full px-2.5 py-0.5 flex items-center gap-1 text-[11px] font-black text-amber-300 shadow">
        <span>🪙</span> <span class="gold-val">1,000,000</span>
      </div>
      <div class="bg-slate-900/90 border border-slate-600 rounded-full px-2.5 py-0.5 flex items-center gap-1 text-[11px] font-black text-cyan-200 shadow">
        <span>💎</span> <span class="ruby-val">500</span>
      </div>
      <div class="bg-slate-900/90 border border-amber-500/80 rounded-full px-2.5 py-0.5 flex items-center gap-1 text-[11px] font-black text-amber-400 shadow">
        <span class="px-1 bg-amber-500 text-slate-950 rounded text-[9px]">B.P.</span> <span class="bp-val">0</span>
      </div>
    </div>

    <!-- Deployed 5-Hero Showcase Row -->
    <div class="absolute bottom-28 left-0 right-0 flex justify-center items-end gap-8 px-6" id="lobbyHeroShowcase"></div>

    <!-- Bottom Navigation Bar -->
    <div class="absolute bottom-4 left-6 flex items-center gap-3">
      <button class="nav-hex-btn" data-open="modalTeam">
        <div class="hex-icon-box"><div class="hex-icon-inner">⚔️</div></div>
        <span class="nav-label">Team</span>
      </button>

      <button class="nav-hex-btn" data-open="modalShop">
        <div class="hex-icon-box"><div class="hex-icon-inner">🛒</div></div>
        <span class="nav-label">Shop</span>
      </button>

      <button class="nav-hex-btn" data-open="modalUpgrade">
        <div class="hex-icon-box"><div class="hex-icon-inner">🔧</div></div>
        <span class="nav-label">Upgrade</span>
      </button>

      <button class="nav-hex-btn" data-open="modalGacha">
        <div class="hex-icon-box"><div class="hex-icon-inner">🎴</div></div>
        <span class="nav-label">Draw</span>
      </button>
    </div>

    <!-- Bottom Right Start Button -->
    <div class="absolute bottom-4 right-6">
      <button class="start-ribbon-btn" id="btnPlay">
        <div class="compass-icon">🧭</div>
        <span class="text-xl md:text-2xl font-black text-amber-950 tracking-wider italic">START</span>
      </button>
    </div>
  </section>

  <!-- ==================== MODAL: SHOP ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-2 bg-slate-950/90 backdrop-blur-md hidden" id="modalShop">
    <div class="w-full max-w-5xl h-[94vh] rounded-2xl overflow-hidden flex flex-col justify-between p-4 bg-cover bg-center relative border-2 border-yellow-400/80 shadow-2xl"
         style="background-image: radial-gradient(circle at center, rgba(15, 30, 45, 0.9), rgba(7, 12, 20, 0.98)), url('https://images.unsplash.com/photo-1518709268805-4e9042af9f23?auto=format&fit=crop&w=1200&q=80');">
      
      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <div class="flex items-center gap-3">
          <button class="w-8 h-8 rounded-full bg-slate-800 border border-yellow-400 text-amber-300 font-black flex items-center justify-center" data-close="modalShop">‹</button>
          <h2 class="text-2xl font-serif font-black text-amber-200">Shop</h2>
        </div>

        <div class="flex items-center gap-1.5 bg-slate-950/80 p-1 rounded-xl border border-slate-700">
          <button class="px-3 py-1 rounded-lg text-xs font-black bg-amber-500 text-slate-950" id="btnShopTabPackage">Package</button>
          <button class="px-3 py-1 rounded-lg text-xs font-bold text-slate-300 hover:text-white" id="btnShopTabRuby">Ruby</button>
          <button class="px-3 py-1 rounded-lg text-xs font-bold text-slate-300 hover:text-white" id="btnShopTabGold">Gold</button>
        </div>

        <div class="flex items-center gap-2 text-xs font-bold text-amber-300">
          <div>💵 <span class="coins-val">0</span></div>
          <div>🪙 <span class="gold-val">1,000,000</span></div>
          <div>💎 <span class="ruby-val">500</span></div>
          <div>🟧 <span class="bp-val">0</span></div>
        </div>
      </div>

      <div class="my-auto px-2 overflow-x-auto py-4">
        <div class="flex justify-center items-center gap-4 min-w-max" id="shopGrid"></div>
      </div>

      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <button class="oval-btn oval-btn-blue" data-close="modalShop">Back</button>
        <button class="oval-btn oval-btn-purple" id="btnShopToTeam">Team Setup</button>
      </div>
    </div>
  </div>

  <!-- ==================== MODAL: UPGRADE (TT) ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-2 bg-slate-950/90 backdrop-blur-md hidden" id="modalUpgrade">
    <div class="w-full max-w-5xl h-[94vh] rounded-2xl overflow-hidden flex flex-col justify-between p-4 bg-cover bg-center relative border-2 border-yellow-400/80 shadow-2xl"
         style="background-image: radial-gradient(circle at center, rgba(15, 30, 45, 0.9), rgba(7, 12, 20, 0.98)), url('https://images.unsplash.com/photo-1518709268805-4e9042af9f23?auto=format&fit=crop&w=1200&q=80');">
      
      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <div class="flex items-center gap-3">
          <button class="w-8 h-8 rounded-full bg-slate-800 border border-yellow-400 text-amber-300 font-black flex items-center justify-center" data-close="modalUpgrade">‹</button>
          <h2 class="text-2xl font-serif font-black text-amber-200">Upgrades</h2>
        </div>

        <div class="flex items-center gap-2 text-xs font-bold text-amber-300">
          <div>🪙 <span class="gold-val">1,000,000</span></div>
          <div>💎 <span class="ruby-val">500</span></div>
          <div>🟧 <span class="bp-val">0</span></div>
        </div>
      </div>

      <div class="grid grid-cols-2 md:grid-cols-3 gap-4 my-auto p-2 overflow-y-auto max-h-[72vh]" id="upgradeGrid"></div>

      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <button class="oval-btn oval-btn-blue" data-close="modalUpgrade">Back</button>
        <button class="oval-btn oval-btn-gold" id="btnUpgradeToPlay">Start Game</button>
      </div>
    </div>
  </div>

  <!-- ==================== MODAL: TEMPLE OF FOUR GODS ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-2 bg-slate-950/90 backdrop-blur-md hidden" id="modalGuardianTemple">
    <div class="w-full max-w-5xl h-[94vh] rounded-2xl overflow-hidden flex flex-col justify-between p-4 bg-cover bg-center relative border-2 border-yellow-400/80 shadow-2xl"
         style="background-image: radial-gradient(circle at center, rgba(15, 30, 45, 0.9), rgba(7, 12, 20, 0.98)), url('https://images.unsplash.com/photo-1518709268805-4e9042af9f23?auto=format&fit=crop&w=1200&q=80');">
      
      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <div class="flex items-center gap-3">
          <button class="w-8 h-8 rounded-full bg-slate-800 border border-yellow-400 text-amber-300 font-black text-base flex items-center justify-center" data-close="modalGuardianTemple">‹</button>
          <h2 class="text-2xl font-serif font-black text-amber-200 tracking-wide">Temple of Four Gods</h2>
        </div>

        <div class="flex items-center gap-2.5 text-xs font-bold text-amber-300">
          <div>💵 <span class="coins-val">0</span></div>
          <div>☁️ <span class="cloud-val">0</span></div>
          <div>🪙 <span class="gold-val">1,000,000</span></div>
          <div>💎 <span class="ruby-val">500</span></div>
        </div>
      </div>

      <div class="flex justify-center items-center gap-6 my-auto px-4">
        <!-- Azure Dragon Card -->
        <div class="god-card active-god" id="cardAzureDragon" onclick="openAzureDragonTemple()">
          <div class="god-title-banner bg-azure-banner">Azure Dragon</div>
          <div class="my-auto flex flex-col items-center">
            <div class="text-7xl filter drop-shadow-[0_0_15px_rgba(56,189,248,0.8)]">🐉</div>
            <div class="text-xs font-black text-cyan-200 mt-2">Azure Dragon</div>
            <div class="text-[10px] text-amber-300 font-extrabold mt-1">★★★★★★★</div>
          </div>
          <div class="bg-cyan-950/80 border-t border-cyan-400 text-center py-1 text-xs font-black text-cyan-300">
            UNLOCKED
          </div>
        </div>

        <div class="god-card locked-god">
          <div class="god-title-banner bg-tiger-banner">White Tiger</div>
          <div class="my-auto flex flex-col items-center opacity-60">
            <div class="text-6xl">🐯</div>
            <div class="text-xs font-black text-amber-200 mt-2">White Tiger</div>
            <div class="text-2xl mt-1">🔒</div>
          </div>
          <div class="bg-slate-900 border-t border-slate-700 text-center py-1 text-xs font-bold text-slate-400">LOCKED</div>
        </div>

        <div class="god-card locked-god">
          <div class="god-title-banner bg-tortoise-banner">Tortoise Warrior</div>
          <div class="my-auto flex flex-col items-center opacity-60">
            <div class="text-6xl">🐢</div>
            <div class="text-xs font-black text-emerald-200 mt-2">Tortoise Warrior</div>
            <div class="text-2xl mt-1">🔒</div>
          </div>
          <div class="bg-slate-900 border-t border-slate-700 text-center py-1 text-xs font-bold text-slate-400">LOCKED</div>
        </div>

        <div class="god-card locked-god">
          <div class="god-title-banner bg-vermilion-banner">Vermilion Bird</div>
          <div class="my-auto flex flex-col items-center opacity-60">
            <div class="text-6xl">🦩</div>
            <div class="text-xs font-black text-rose-200 mt-2">Vermilion Bird</div>
            <div class="text-2xl mt-1">🔒</div>
          </div>
          <div class="bg-slate-900 border-t border-slate-700 text-center py-1 text-xs font-bold text-slate-400">LOCKED</div>
        </div>
      </div>

      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <button class="oval-btn oval-btn-blue" data-close="modalGuardianTemple">Back</button>
        <div class="text-xs font-extrabold text-amber-300">Select Azure Dragon to enter Persuasion stage</div>
      </div>
    </div>
  </div>

  <!-- ==================== MODAL: PERSUADE AZURE DRAGON ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-2 bg-slate-950/90 backdrop-blur-md hidden" id="modalAzureDragonTemple">
    <div class="w-full max-w-5xl h-[94vh] rounded-2xl overflow-hidden flex flex-col justify-between p-4 bg-cover bg-center relative border-2 border-yellow-400/80 shadow-2xl"
         style="background-image: radial-gradient(circle at center, rgba(15, 30, 45, 0.85), rgba(7, 12, 20, 0.98)), url('https://images.unsplash.com/photo-1518709268805-4e9042af9f23?auto=format&fit=crop&w=1200&q=80');">
      
      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <div class="flex items-center gap-3">
          <button class="w-8 h-8 rounded-full bg-slate-800 border border-yellow-400 text-amber-300 font-black text-base flex items-center justify-center" id="btnBackToGuardianTemple">‹</button>
          <h2 class="text-2xl font-serif font-black text-cyan-200 tracking-wide">Dragon Shrine</h2>
        </div>

        <div class="flex items-center gap-2.5 text-xs font-bold text-amber-300">
          <div>☁️ <span class="cloud-val">0</span></div>
          <div>🪙 <span class="gold-val">1,000,000</span></div>
          <div>💎 <span class="ruby-val">500</span></div>
        </div>
      </div>

      <div class="flex justify-between items-center my-auto px-8 w-full">
        <div class="flex flex-col items-center relative">
          <div class="w-36 h-8 rounded-full bg-cyan-400/30 border border-cyan-300 shadow-[0_0_25px_#38bdf8] absolute -bottom-2"></div>
          <div class="text-8xl md:text-9xl filter drop-shadow-[0_0_20px_rgba(56,189,248,0.9)] animate-pulse z-10">🐉</div>
          <div class="text-xs font-extrabold text-fuchsia-400 tracking-widest mt-2 z-10">★★★★★★★</div>
          <div class="text-sm font-black text-cyan-200 bg-slate-900/90 border border-cyan-400/80 px-4 py-0.5 rounded-full mt-1 shadow z-10">Azure Dragon</div>
        </div>

        <div class="flex flex-col items-center max-w-md w-full gap-4">
          <div class="bg-slate-100 text-slate-900 font-extrabold text-sm rounded-2xl p-4 shadow-2xl border-2 border-cyan-300 relative text-center">
            <span id="azureDragonSpeech">"As one of the four guardians, I do not need your help!"</span>
            <div class="w-4 h-4 bg-slate-100 border-r-2 border-b-2 border-cyan-300 absolute -bottom-2 left-1/2 -translate-x-1/2 rotate-45"></div>
          </div>

          <button class="px-8 py-3 rounded-full bg-gradient-to-r from-amber-400 via-yellow-500 to-amber-600 border-2 border-white shadow-[0_0_20px_rgba(250,204,21,0.6)] hover:scale-105 active:scale-95 transition-transform flex items-center justify-center gap-2"
                  id="btnPersuadeAzureDragon">
            <span class="text-base font-serif font-black text-slate-950">Persuade</span>
            <div class="bg-slate-950/80 px-3 py-1 rounded-full border border-yellow-300 text-xs font-black text-cyan-300 flex items-center gap-1">
              <span>☁️</span> <span>30</span>
            </div>
          </button>
        </div>

        <div class="pity-pillar-container">
          <div class="text-[10px] font-black text-white bg-rose-700 border border-yellow-300 rounded-lg px-2 py-1 mb-2 text-center">
            4 Gauge Guaranteed Event
          </div>
          <div class="pity-pillar-body">
            <div class="pity-pillar-fill" id="pityGaugeBar" style="height: 0%;"></div>
          </div>
          <div class="text-xs font-black text-cyan-300 bg-slate-900/90 border border-cyan-400 px-2.5 py-0.5 rounded-full mt-2 shadow" id="txtPityCount">
            0/140
          </div>
        </div>
      </div>

      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <button class="oval-btn oval-btn-blue" id="btnBackToGuardianTemple2">Back</button>
        <div class="text-xs font-extrabold text-slate-300">Azure Dragon Rate: <b class="text-yellow-300">0.65%</b> (Guaranteed at 140/140)</div>
      </div>
    </div>
  </div>

  <!-- ==================== MAP SELECTION SCREEN ==================== -->
  <section class="absolute inset-0 bg-slate-900/95 flex flex-col justify-between p-6 hidden" id="mapSelect">
    <div class="flex justify-between items-center border-b border-slate-700 pb-3">
      <div class="flex items-center gap-3">
        <button class="bg-slate-800 text-amber-300 font-extrabold px-3 py-1.5 rounded-xl border border-yellow-400 text-sm" id="btnBackToLobby">‹ Back</button>
        <h2 class="text-2xl font-black text-amber-300">SELECT BATTLEFIELD MAP</h2>
      </div>

      <div class="flex items-center gap-2 bg-slate-800 p-1.5 rounded-xl border border-yellow-400">
        <span class="text-xs font-bold text-slate-300">Mode:</span>
        <button class="px-3 py-1 rounded-lg text-xs font-extrabold" id="btnToggleHard">
          <span id="diffModeText" class="text-emerald-400">Normal</span>
        </button>
      </div>
    </div>

    <div class="grid grid-cols-5 gap-4 my-auto px-4" id="mapNodesContainer"></div>
    <div class="text-center text-xs text-slate-400 font-semibold">Select a map to begin defense stages</div>
  </section>

  <!-- ==================== MODAL: TEAM SETUP ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-2 bg-slate-950/90 backdrop-blur-md hidden" id="modalTeam">
    <div class="w-full max-w-5xl h-[94vh] rounded-2xl overflow-hidden flex flex-col justify-between p-4 bg-cover bg-center relative border-2 border-yellow-400/80 shadow-2xl" 
         style="background-image: radial-gradient(circle at center, rgba(15, 30, 45, 0.85), rgba(7, 12, 20, 0.95)), url('https://images.unsplash.com/photo-1518709268805-4e9042af9f23?auto=format&fit=crop&w=1200&q=80');">
      
      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <div class="flex items-center gap-3">
          <button class="w-8 h-8 rounded-full bg-slate-800 border border-yellow-400 text-amber-300 font-black text-base flex items-center justify-center" data-close="modalTeam">‹</button>
          <h2 class="text-2xl font-serif font-black text-amber-200 tracking-wide">Team Setup</h2>
        </div>

        <div class="flex items-center gap-2.5 text-xs font-bold text-amber-300">
          <div>💵 <span class="coins-val">0</span></div>
          <div>🪙 <span class="gold-val">1,000,000</span></div>
          <div>💎 <span class="ruby-val">500</span></div>
          <div class="bg-slate-800/90 border border-slate-600 px-2.5 py-1 rounded-full text-slate-200 font-extrabold" id="txtMyCharCount">
            My Characters : 7/30
          </div>
        </div>
      </div>

      <div class="wooden-shelf p-2 my-2 flex flex-col items-center">
        <div class="text-[11px] font-extrabold text-amber-200 tracking-wider uppercase mb-1">
          5-HERO DEPLOYMENT SHELF (CLICK HERO TO UNEQUIP)
        </div>
        <div class="flex justify-center gap-3 w-full" id="shelfSlotsContainer"></div>
      </div>

      <div class="flex-1 flex items-center overflow-x-auto gap-3 p-2 border-y border-amber-400/30 bg-slate-950/40 rounded-xl relative" id="rosterCardsRow"></div>

      <!-- Character Context Menu Popover -->
      <div class="char-popover-menu hidden" id="charContextMenu">
        <button class="popover-btn" id="popBtnUnequip">Unequip</button>
        <button class="popover-btn" id="popBtnSell">Sell</button>
        <button class="popover-btn" id="popBtnLevelUp">Level Up</button>
        <button class="popover-btn" id="popBtnItem">Item</button>
        <button class="popover-btn" id="popBtnLock">Lock</button>
        <button class="popover-btn popover-btn-close" id="popBtnClose">Close</button>
      </div>

      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2 mt-2">
        <button class="oval-btn oval-btn-blue" data-close="modalTeam">Back</button>

        <div class="flex items-center gap-3">
          <button class="oval-btn oval-btn-purple" id="btnTeamToGacha"><span>🎴</span> Draw</button>
          <button class="oval-btn oval-btn-gold" id="btnTeamToStart"><span>🧭</span> Start Game</button>
        </div>
      </div>
    </div>
  </div>

  <!-- ==================== MODAL: HERO LEVEL UP FEED ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-950/90 backdrop-blur-md hidden" id="modalLevelUp">
    <div class="bg-slate-900 border-2 border-yellow-400 w-full max-w-lg rounded-2xl p-5 flex flex-col gap-4 shadow-2xl">
      <div class="flex justify-between items-center border-b border-slate-700 pb-2">
        <h2 class="text-lg font-black text-amber-300">LEVEL UP HERO</h2>
        <button class="text-rose-400 font-black text-sm" onclick="$('modalLevelUp').classList.add('hidden')">✕</button>
      </div>

      <div class="bg-slate-800 p-3 rounded-xl border border-amber-400/60 flex items-center gap-4" id="levelUpTargetBanner"></div>

      <div class="text-xs font-bold text-slate-300">
        Select unlocked & unequipped characters to feed as EXP materials:
      </div>

      <div class="grid grid-cols-4 gap-2.5 overflow-y-auto max-h-[220px] p-1 bg-slate-950/60 rounded-xl border border-slate-800" id="levelUpMaterialGrid"></div>

      <div class="flex justify-between items-center border-t border-slate-700 pt-3">
        <div class="text-xs font-black text-amber-300" id="txtLevelUpPreview">Preview: +0 EXP</div>
        <button class="oval-btn oval-btn-gold" id="btnConfirmLevelUp">Level Up</button>
      </div>
    </div>
  </div>

  <!-- ==================== MODAL: ITEM EQUIPMENT SCREEN ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-2 bg-slate-950/90 backdrop-blur-md hidden" id="modalHeroItem">
    <div class="w-full max-w-5xl h-[94vh] rounded-2xl overflow-hidden flex flex-col justify-between p-4 bg-cover bg-center relative border-2 border-yellow-400/80 shadow-2xl"
         style="background-image: radial-gradient(circle at center, rgba(15, 30, 45, 0.9), rgba(7, 12, 20, 0.98)), url('https://images.unsplash.com/photo-1518709268805-4e9042af9f23?auto=format&fit=crop&w=1200&q=80');">
      
      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <div class="flex items-center gap-3">
          <button class="w-8 h-8 rounded-full bg-slate-800 border border-yellow-400 text-amber-300 font-black text-base flex items-center justify-center" onclick="$('modalHeroItem').classList.add('hidden')">‹</button>
          <h2 class="text-2xl font-serif font-black text-amber-200 tracking-wide">Item Equipment</h2>
        </div>

        <div class="flex items-center gap-2.5 text-xs font-bold text-amber-300">
          <div>💵 <span class="coins-val">0</span></div>
          <div>🪙 <span class="gold-val">1,000,000</span></div>
          <div>💎 <span class="ruby-val">500</span></div>
        </div>
      </div>

      <div class="flex gap-4 my-auto h-[72vh] w-full">
        <!-- Left Panel: Hero Preview & Stats -->
        <div class="w-2/5 bg-amber-900/30 border-2 border-amber-600/80 rounded-2xl p-3 flex flex-col justify-between backdrop-blur-sm">
          <div class="bg-amber-900/60 border border-amber-500 rounded-xl text-center py-1 text-xs font-black text-amber-200" id="itemHeroName">
            Echo
          </div>

          <div class="relative my-auto flex justify-center items-center py-4">
            <div class="absolute top-0 left-4 item-slot-box" id="slotClock" onclick="clickItemSlot('clock')">
              <span class="text-2xl">⏱️</span>
              <span class="text-[8px] font-black text-amber-200 absolute bottom-0.5">Clock</span>
            </div>

            <div class="absolute top-0 right-4 item-slot-box" id="slotSword" onclick="clickItemSlot('sword')">
              <span class="text-2xl">🗡️</span>
              <span class="text-[8px] font-black text-amber-200 absolute bottom-0.5">Sword</span>
            </div>

            <div class="text-7xl filter drop-shadow-lg" id="itemHeroIcon">🦜</div>

            <div class="absolute bottom-0 left-4 item-slot-box" id="slotShield" onclick="clickItemSlot('shield')">
              <span class="text-2xl">🛡️</span>
              <span class="text-[8px] font-black text-amber-200 absolute bottom-0.5">Shield</span>
            </div>

            <div class="absolute bottom-0 right-4 item-slot-box" id="slotWings" onclick="clickItemSlot('wings')">
              <span class="text-2xl">👟</span>
              <span class="text-[8px] font-black text-amber-200 absolute bottom-0.5">Wings</span>
            </div>
          </div>

          <div class="bg-amber-950/80 border border-amber-700 rounded-xl p-2 space-y-1 text-xs font-black">
            <div class="flex justify-between text-cyan-300"><span>💧 Cost</span><span id="txtItemHeroCost">20</span></div>
            <div class="flex justify-between text-red-400"><span>⚔️ AP</span><span id="txtItemHeroAP">1</span></div>
            <div class="flex justify-between text-emerald-400"><span>❤ HP / HC</span><span id="txtItemHeroHP">10</span></div>
          </div>

          <div class="bg-amber-950/90 border border-amber-600 rounded-xl p-2 text-[10px] font-extrabold text-amber-100">
            <div class="text-[9px] text-amber-300 font-black mb-1 border-b border-amber-800 pb-0.5">Equipped Item Ability</div>
            <div class="grid grid-cols-2 gap-x-3 gap-y-0.5">
              <div class="flex justify-between"><span>MR:</span><span id="statMR" class="text-amber-300">-</span></div>
              <div class="flex justify-between"><span>PS:</span><span id="statPS" class="text-amber-300">-</span></div>
              <div class="flex justify-between"><span>AP:</span><span id="statAP" class="text-amber-300">-</span></div>
              <div class="flex justify-between"><span>SP:</span><span id="statSP" class="text-amber-300">-</span></div>
              <div class="flex justify-between"><span>HP:</span><span id="statHP" class="text-amber-300">-</span></div>
              <div class="flex justify-between"><span>AD:</span><span id="statAD" class="text-amber-300">-</span></div>
              <div class="col-span-2 flex justify-between"><span>AS:</span><span id="statAS" class="text-amber-300">-</span></div>
            </div>
          </div>
        </div>

        <!-- Right Panel: Inventory & Filters -->
        <div class="w-3/5 bg-slate-950/80 border-2 border-amber-500/80 rounded-2xl p-3 flex flex-col justify-between">
          <div class="flex items-center justify-between border-b border-slate-800 pb-2">
            <div class="flex gap-1" id="itemFilterGroup">
              <button class="px-3 py-1 rounded-lg text-xs font-black bg-amber-400 text-slate-950 shadow" data-type="all">All</button>
              <button class="px-3 py-1 rounded-lg text-xs font-bold bg-slate-800 text-slate-300" data-type="clock">Clock</button>
              <button class="px-3 py-1 rounded-lg text-xs font-bold bg-slate-800 text-slate-300" data-type="sword">Sword</button>
              <button class="px-3 py-1 rounded-lg text-xs font-bold bg-slate-800 text-slate-300" data-type="shield">Shield</button>
              <button class="px-3 py-1 rounded-lg text-xs font-bold bg-slate-800 text-slate-300" data-type="wings">Wings</button>
            </div>
          </div>

          <div class="bg-amber-950/90 border border-amber-600 rounded-xl p-2.5 my-2 text-xs font-extrabold text-amber-100 min-h-[64px]" id="selectedItemBanner">
            <div class="text-amber-300 font-black" id="lblItemTitle">No Item Selected</div>
            <div class="text-[11px] text-slate-300" id="lblItemPart">Part : -</div>
            <div class="text-[11px] text-cyan-300" id="lblItemBasic">basic ability : -</div>
            <div class="text-[11px] text-rose-300" id="lblItemAdd">additional ability : -</div>
          </div>

          <div class="grid grid-cols-6 gap-2 my-auto p-2 bg-slate-900/60 rounded-xl border border-slate-800 overflow-y-auto max-h-[220px]" id="itemInventoryGrid"></div>

          <div class="flex justify-between items-center pt-2 border-t border-slate-800">
            <button class="oval-btn oval-btn-blue" onclick="$('modalHeroItem').classList.add('hidden')">Back</button>
            <button class="oval-btn oval-btn-purple" id="btnItemToGacha"><span>🎴</span> Draw Item</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- ==================== MODAL: DRAW / GACHA ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-2 bg-slate-950/90 backdrop-blur-md hidden" id="modalGacha">
    <div class="w-full max-w-5xl h-[94vh] rounded-2xl overflow-hidden flex flex-col justify-between p-4 bg-cover bg-center relative border-2 border-yellow-400/80 shadow-2xl"
         style="background-image: radial-gradient(circle at center, rgba(15, 30, 45, 0.9), rgba(7, 12, 20, 0.98)), url('https://images.unsplash.com/photo-1518709268805-4e9042af9f23?auto=format&fit=crop&w=1200&q=80');">
      
      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <div class="flex items-center gap-3">
          <button class="w-8 h-8 rounded-full bg-slate-800 border border-yellow-400 text-amber-300 font-black text-base flex items-center justify-center" data-close="modalGacha">‹</button>
          <h2 class="text-2xl font-serif font-black text-amber-200 tracking-wide">Draw Cards</h2>
        </div>

        <div class="flex items-center bg-slate-950/80 p-1 rounded-xl border border-slate-700 gap-1">
          <button class="px-3 py-1 rounded-lg text-xs font-black text-white shadow bg-rose-600" id="tabGachaHeroes">
            <span>🐧</span> Heroes
          </button>
          <button class="px-3 py-1 rounded-lg text-xs font-bold text-slate-400 hover:text-white" id="tabGachaItems">
            <span>🗡️</span> Items
          </button>
        </div>

        <div class="flex items-center gap-2.5 text-xs font-bold text-amber-300">
          <div>💵 <span class="coins-val">0</span></div>
          <div>🪙 <span class="gold-val">1,000,000</span></div>
          <div>💎 <span class="ruby-val">500</span></div>
          <div>🟧 <span class="bp-val">0</span></div>
        </div>
      </div>

      <div class="gacha-track my-auto py-4" id="gachaPacksTrack"></div>

      <div class="flex justify-between items-center bg-slate-900/80 border border-yellow-400/50 rounded-xl px-4 py-2">
        <button class="oval-btn oval-btn-blue" data-close="modalGacha">Back</button>
        <button class="oval-btn oval-btn-purple" id="btnGachaToTeam"><span>⚔️</span> Team Setup</button>
        <button class="px-4 py-1.5 rounded-lg bg-slate-800 border border-slate-600 text-xs font-bold text-slate-300 hover:text-white" id="btnShowProb">Probability</button>
      </div>
    </div>
  </div>

  <!-- ==================== GACHA RESULT REVEAL ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-2 bg-slate-950/90 backdrop-blur-md hidden" id="modalGachaResult">
    <div class="w-full max-w-4xl h-[88vh] rounded-2xl overflow-hidden flex flex-col justify-between p-4 bg-slate-900 border-2 border-yellow-400 shadow-2xl relative"
         style="background-image: radial-gradient(circle at center, rgba(15, 30, 45, 0.92), rgba(7, 12, 20, 0.98)), url('https://images.unsplash.com/photo-1518709268805-4e9042af9f23?auto=format&fit=crop&w=1200&q=80');">
      
      <div class="flex justify-between items-center border-b border-amber-400/50 pb-2">
        <h2 class="text-xl font-serif font-black text-amber-200">Selection Completed</h2>
        <div class="flex items-center gap-2 text-xs font-bold text-amber-300">
          <div>💎 <span class="ruby-val">500</span></div>
          <div>🟧 <span class="bp-val">0</span></div>
        </div>
      </div>

      <div class="grid grid-cols-3 md:grid-cols-6 gap-3 my-auto p-2" id="gachaResultCards"></div>

      <div class="flex justify-center items-center gap-4 border-t border-amber-400/50 pt-3">
        <button class="oval-btn oval-btn-purple relative" id="btnDrawAgain">
          <span class="absolute -top-3 -right-2 bg-rose-600 text-white text-[9px] font-black px-1.5 py-0.5 rounded-full border border-yellow-300">10% OFF</span>
          <span>Draw Again</span>
        </button>

        <button class="oval-btn oval-btn-blue" id="btnCloseGachaResult">OK</button>
        <button class="oval-btn oval-btn-gold" id="btnResultToTeam"><span>⚔️</span> Team Setup</button>
      </div>
    </div>
  </div>

  <!-- ==================== PROBABILITY INFO POPUP ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-950/85 backdrop-blur-md hidden" id="modalProb">
    <div class="bg-slate-900 border-2 border-slate-700 rounded-2xl p-5 max-w-xl w-full text-xs space-y-3 max-h-[85vh] overflow-y-auto">
      <div class="flex justify-between items-center border-b border-slate-700 pb-2">
        <h3 class="font-black text-amber-300 text-sm">PROBABILITY & STATS TABLE</h3>
        <button class="text-rose-400 font-extrabold text-sm" onclick="$('modalProb').classList.add('hidden')">✕</button>
      </div>
      
      <div class="space-y-3 text-slate-300">
        <div class="bg-slate-950 p-3 rounded-xl border border-slate-800">
          <div class="font-black text-amber-300 mb-1">Item draw probability:</div>
          <p>• <b>F grade:</b> Clock (25%), Sword (25%), Shield (25%), Wings (25%)</p>
          <p>• <b>E ~ C grade:</b> E (70%), D (25%), C (5%)</p>
          <p>• <b>Item A Gacha (Coins):</b> C (60%), B (40%)</p>
        </div>

        <div class="bg-slate-950 p-3 rounded-xl border border-slate-800">
          <div class="font-black text-amber-300 mb-1">Item ability settings:</div>
          <p>• <b>F Grade:</b> AP (18-54), HP (100-300), SP (1-5%), AD (1-30)</p>
          <p>• <b>E Grade:</b> AP (36-108), HP (200-600), SP (6-10%), AD (31-60)</p>
          <p>• <b>D Grade:</b> AP (108-324), HP (600-1800), SP (11-15%), AD (61-100)</p>
          <p>• <b>C Grade:</b> AP (432-1296), HP (2400-7200), SP (16-20%), AD (101-140)</p>
          <p>• <b>B Grade:</b> AP (2160-6480), HP (12000-36000), SP (21-30%), AD (141-180)</p>
        </div>
      </div>
    </div>
  </div>

  <!-- ==================== MODAL: LEVEL SELECT ==================== -->
  <div class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-950/80 backdrop-blur-md hidden" id="modalLevels">
    <div class="bg-slate-900 border-2 border-amber-400 w-full max-w-xl rounded-2xl p-5 flex flex-col gap-3 shadow-2xl">
      <div class="flex justify-between items-center border-b border-slate-700 pb-2">
        <h2 class="text-xl font-black text-amber-300" id="levelMapTitle">Stage Select</h2>
        <button class="bg-rose-600 text-white px-3 py-1 rounded-lg text-xs font-bold" data-close="modalLevels">Close</button>
      </div>
      <div class="text-xs text-slate-300 font-semibold" id="levelMonstersText">Monsters: ...</div>
      <div class="grid grid-cols-5 gap-2.5 overflow-y-auto max-h-[300px] p-1" id="levelGrid"></div>
    </div>
  </div>

  <!-- ==================== GAME BATTLEFIELD STAGE ==================== -->
  <main class="hidden flex flex-col h-full" id="gameStage">
    <header class="bg-slate-900/95 border-b-2 border-slate-800 px-4 py-2 flex justify-between items-center relative z-10">
      <div class="flex items-center gap-2">
        <div class="bg-slate-800/90 border border-slate-600 px-3 py-1 rounded-2xl flex items-center gap-2 shadow">
          <span class="text-base">⚔️</span>
          <div class="flex flex-col text-left">
            <span class="text-[10px] text-emerald-400 font-extrabold uppercase leading-none" id="txtTopMode">Normal Mode</span>
            <span class="text-xs font-black text-white leading-tight" id="txtTopStage">Stage 1</span>
          </div>
        </div>
      </div>

      <button class="w-9 h-9 rounded-full bg-slate-800 hover:bg-slate-700 border-2 border-slate-600 text-white font-bold flex items-center justify-center shadow" id="btnBattlePause">
        ❚❚
      </button>
    </header>

    <div class="stage-container relative flex-1">
      <canvas id="cv" width="960" height="430"></canvas>

      <div class="absolute inset-0 z-20 flex items-center justify-center bg-slate-950/85 backdrop-blur-sm hidden" id="battleEndModal">
        <div class="bg-slate-900 p-6 rounded-2xl border-2 border-amber-400 text-center max-w-sm w-full mx-4 shadow-2xl">
          <div class="text-5xl mb-2" id="endModalIcon">🏆</div>
          <h2 class="text-2xl font-black text-amber-300 mb-1" id="endModalTitle">VICTORY!</h2>
          <p class="text-xs text-slate-300 mb-4" id="endModalMsg">You have successfully defended the lane.</p>
          <div class="text-sm font-bold text-amber-200 mb-4" id="endModalReward">Reward: +500 Gold</div>

          <div class="flex justify-center gap-2">
            <button class="bg-amber-400 text-slate-950 font-black px-4 py-2 rounded-xl text-sm shadow" id="btnRetry">Retry</button>
            <button class="bg-emerald-600 text-white font-bold px-4 py-2 rounded-xl text-sm shadow hidden" id="btnNextLevel">Next Level</button>
            <button class="bg-slate-700 text-white font-bold px-4 py-2 rounded-xl text-sm shadow" id="btnSelectMap">Select Map</button>
          </div>
        </div>
      </div>
    </div>

    <section class="bottom-dock">
      <button class="hex-btn hex-red" id="btnRocket" title="Fire Missile">
        <span class="text-2xl drop-shadow">🚀</span>
        <span class="text-[9px] font-black text-amber-200 leading-none tracking-tight">MISSILE</span>
        <div class="cooldown-overlay hidden" id="rocketCdText">15</div>
      </button>

      <button class="hex-btn hex-blue" id="btnManaUpgrade" title="Upgrade Mana">
        <span class="text-xl drop-shadow">💎</span>
        <span class="text-[9px] font-black text-cyan-100 leading-none" id="lblManaLvl">Lv. 1</span>
        <span class="text-[8px] font-bold text-cyan-200" id="lblManaCost">10</span>
      </button>

      <div class="flex-1 flex flex-col gap-1 items-center px-2">
        <div class="w-full bg-slate-950/80 border-2 border-cyan-400/80 rounded-full h-7 px-3 flex items-center justify-between text-xs font-black shadow-inner">
          <span class="text-cyan-300 text-base">💎</span>
          <span class="text-cyan-200 tracking-wider text-sm" id="battleManaText">100 / 100</span>
          <span class="text-[10px] text-cyan-400 font-extrabold uppercase">MANA</span>
        </div>
      </div>

      <div class="bg-slate-950/80 border-2 border-slate-700 rounded-full px-3 py-1 flex items-center gap-1.5 text-xs font-black text-amber-300 shadow">
        <span>🐧</span>
        <span id="txtWaveProgress">0 / 10</span>
      </div>

      <div id="heroSummonCards" class="flex gap-2"></div>
    </section>
    
    <p class="text-center text-xs font-bold text-amber-300 bg-slate-950 py-1 min-h-[20px]" id="toastText"></p>
  </main>

</div>

<script>
const W = 960, H = 430, LANE = 300;
const cv = document.getElementById('cv');
const ctx = cv.getContext('2d');
const $ = id => document.getElementById(id);

/* Hero Classes Master Data */
const HERO_CLASSES = {
  // 8★ God Heroes
  ogong:         { name: "Ogong", icon: "🐒", cost: 100, baseHp: 3600, baseAp: 1200, spd: 1.1, rng: 65, fx: "smash", cd: 8.0, role: "8★ God Hero", star: 8 },
  mukhyang:      { name: "Mukhyang", icon: "🎋", cost: 100, baseHp: 0, baseAp: 1000, hitCount: 30, useHitCount: true, spd: 1.0, rng: 70, fx: "slash", cd: 8.0, role: "8★ God Hero", star: 8 },
  spiritserpent: { name: "Spirit Serpent", icon: "🐍", cost: 100, baseHp: 0, baseAp: 870, hitCount: 25, useHitCount: true, spd: 1.0, rng: 160, fx: "magic", cd: 8.0, role: "8★ God Hero", star: 8 },
  flamecavalier: { name: "Flame Cavalier", icon: "🏇", cost: 100, baseHp: 1300, baseAp: 275, spd: 1.2, rng: 60, fx: "fire", cd: 8.0, role: "8★ God Hero", star: 8 },

  // Standard Roster
  azuredragon: { name: "Azure Dragon", icon: "🐉", cost: 120, baseHp: 1890, baseAp: 735, spd: 0.95, rng: 180, fx: "fire", cd: 15.0, role: "Guardian God", isUnique: true, star: 7 },
  penguin:    { name: "Ace", icon: "🐧", cost: 30, baseHp: 10, baseAp: 2, spd: 1.05, rng: 55, fx: "slash", cd: 2.5, role: "Attacker", star: 1 },
  parrot:     { name: "Echo", icon: "🦜", cost: 20, baseHp: 10, baseAp: 1, spd: 1.2, rng: 160, fx: "arrow", cd: 3.0, role: "Speed Type", star: 1 },
  owl:        { name: "Smartie", icon: "🦉", cost: 40, baseHp: 13, baseAp: 3, spd: 0.85, rng: 130, fx: "magic", cd: 4.5, role: "Range Type", star: 1 },
  duck:       { name: "Khan", icon: "🦆", cost: 30, baseHp: 30, baseAp: 2, spd: 0.95, rng: 55, fx: "slash", cd: 3.0, role: "Stamina Type", star: 1 },
  girl:       { name: "Lucy", icon: "👧", cost: 40, baseHp: 12, baseAp: 3, spd: 1.1, rng: 110, fx: "star", cd: 4.0, role: "Assassin", star: 1 },
  knight:     { name: "Brave", icon: "🛡️", cost: 50, baseHp: 35, baseAp: 4, spd: 0.8, rng: 55, fx: "slash", cd: 5.0, role: "Tanker", star: 2 },
  dragon:     { name: "Ignis", icon: "🐉", cost: 80, baseHp: 50, baseAp: 8, spd: 0.6, rng: 150, fx: "fire", cd: 10.0, role: "Dragon Type", star: 3 },
  demon:      { name: "Demon Lord", icon: "😈", cost: 90, baseHp: 75, baseAp: 12, spd: 0.85, rng: 140, fx: "magic", cd: 8.0, role: "Dark Type", star: 6 },
  robot:      { name: "Mecha-01", icon: "🤖", cost: 100, baseHp: 110, baseAp: 15, spd: 0.7, rng: 120, fx: "star", cd: 9.0, role: "Mecha Type", star: 6 },
  capowl:     { name: "Cap Owl", icon: "🎩", cost: 85, baseHp: 65, baseAp: 14, spd: 1.0, rng: 160, fx: "arrow", cd: 7.0, role: "Commander", star: 6 },
  golddragon: { name: "Gold Dragon", icon: "🐲", cost: 150, baseHp: 180, baseAp: 28, spd: 0.75, rng: 180, fx: "fire", cd: 12.0, role: "Mythic", star: 7 },
  phoenix:    { name: "Phoenix", icon: "🦅", cost: 140, baseHp: 150, baseAp: 32, spd: 1.15, rng: 200, fx: "fire", cd: 11.0, role: "Phoenix", star: 7 },
  angel:      { name: "Angel", icon: "👼", cost: 130, baseHp: 160, baseAp: 25, spd: 0.95, rng: 170, fx: "star", cd: 10.0, role: "Holy Type", star: 7 }
};

/* Item Definitions */
const ITEM_TYPES = {
  clock:  { name: "clock symbol", icon: "⏱️", targetSlot: "clock", desc: "Reduces spawn cooldown & Attack speed" },
  sword:  { name: "sword symbol", icon: "🗡️", targetSlot: "sword", desc: "Attack Power (AP) & Range (AD)" },
  shield: { name: "shield symbol", icon: "🛡️", targetSlot: "shield", desc: "Health (HP) & Magic Resist (MR)" },
  wings:  { name: "wings symbol", icon: "👟", targetSlot: "wings", desc: "Move Speed (SP) & Range (AD)" }
};

/* Gacha Packs Definition */
const CHARACTER_GACHA_PACKS = [
  { id: 'special', title: 'SPECIAL', subtitle: '1 Star to 5 Stars', type: 'free', theme: 'red', minStar: 1, maxStar: 5, count: 1 },
  { id: 'normal', title: 'NORMAL', subtitle: '1 Star to 5 Stars', costType: 'ruby', cost: 10, theme: 'gold', minStar: 1, maxStar: 5, count: 1 },
  { id: 'normal_plus', title: 'NORMAL PLUS', subtitle: '1 Star to 5 Stars', costType: 'ruby', cost: 20, theme: 'gold', minStar: 1, maxStar: 5, count: 1 },
  { id: 'premium', title: 'PREMIUM', subtitle: '3 Stars to 6 Stars', costType: 'ruby', cost: 30, theme: 'red', minStar: 3, maxStar: 6, count: 1 },
  { id: 'premium_plus', title: 'PREMIUM PLUS', subtitle: '(3 Stars to 6 Stars) x 6', costType: 'ruby', cost: 150, theme: 'red', minStar: 3, maxStar: 6, count: 6 },
  { id: 'bp_5star', title: 'BONUS POINT', subtitle: '5 Stars', costType: 'bp', cost: 75, theme: 'gold', minStar: 5, maxStar: 5, count: 1 },
  { id: 'bp_6star', title: 'BONUS POINT', subtitle: '6 Stars', costType: 'bp', cost: 450, theme: 'gold', minStar: 6, maxStar: 6, count: 1 },
  { id: 'bp_7star', title: 'BONUS POINT', subtitle: '7 Stars', costType: 'bp', cost: 2700, theme: 'gold', minStar: 7, maxStar: 7, count: 1 },
  { id: 'selection', title: 'SELECTION', subtitle: '4 Stars to 7 Stars', costType: 'ruby', cost: 100, theme: 'purple', minStar: 4, maxStar: 7, count: 1, event: 'Character 1+1 Event' },
  { id: 'selection_plus', title: 'SELECTION PLUS', subtitle: '(4 Stars to 7 Stars) x 6', costType: 'ruby', cost: 500, theme: 'purple', minStar: 4, maxStar: 7, count: 6, event: 'Character 1+1 Event' }
];

const ITEM_GACHA_PACKS = [
  { id: 'item_a_single', title: 'Item Select', subtitle: 'C ~ B grade', costType: 'coins', cost: 5, theme: 'red', minGrade: 'C', maxGrade: 'B', count: 1, label: 'US $5' },
  { id: 'item_a_multi', title: 'Item Select x10', subtitle: '(C ~ B grade) x 10', costType: 'coins', cost: 50, theme: 'red', minGrade: 'C', maxGrade: 'B', count: 10, label: 'US $50' },
  { id: 'item_f_all', title: 'F grade', subtitle: 'All gacha', costType: 'ruby', cost: 10, theme: 'purple', minGrade: 'F', maxGrade: 'F', count: 1 },
  { id: 'item_ec_sword_wings', title: 'E ~ C grade', subtitle: 'Sword, Wings gacha', costType: 'ruby', cost: 50, theme: 'gold', minGrade: 'E', maxGrade: 'C', count: 1, filterTypes: ['sword', 'wings'] },
  { id: 'item_ec_shield_clock', title: 'E ~ C grade', subtitle: 'Shield, Clock gacha', costType: 'ruby', cost: 50, theme: 'gold', minGrade: 'E', maxGrade: 'C', count: 1, filterTypes: ['shield', 'clock'] },
  { id: 'item_ec_sword_wings_x6', title: '(E ~ C grade) x 6', subtitle: 'Sword, Wings gacha', costType: 'ruby', cost: 300, theme: 'red', minGrade: 'E', maxGrade: 'C', count: 6, filterTypes: ['sword', 'wings'] },
  { id: 'item_ec_shield_clock_x6', title: '(E ~ C grade) x 6', subtitle: 'Shield, Clock gacha', costType: 'ruby', cost: 300, theme: 'red', minGrade: 'E', maxGrade: 'C', count: 6, filterTypes: ['shield', 'clock'] }
];

const ENEMY_TYPES = [
  [["🍄 Mushroom", 75, 12, 0.5, 50, 'slash'], ["🐗 Wild Boar", 120, 16, 0.6, 50, 'slash']],
  [["🐸 Poison Frog", 110, 18, 0.65, 50, 'slash'], ["🐊 Crocodile", 220, 26, 0.4, 60, 'smash']],
  [["💀 Skeleton", 150, 24, 0.5, 55, 'slash'], ["👹 Red Demon", 300, 38, 0.35, 60, 'smash']],
  [["👻 Shadow Ghost", 140, 28, 0.65, 100, 'magic'], ["🎃 Pumpkin Fiend", 240, 35, 0.5, 120, 'fire']],
  [["⛄ Ice Golem", 220, 32, 0.45, 110, 'magic'], ["🐻‍❄️ Polar Bear", 450, 48, 0.4, 60, 'smash']]
];

const MAPS = [
  { name: "Maze Garden", icon: "🌳" }, { name: "Poison Swamp", icon: "🌲" },
  { name: "Volcano Peak", icon: "🔥" }, { name: "Demon Graveyard", icon: "🎃" },
  { name: "Ice Citadel", icon: "❄️" }
];

/* Initial Resources set to: Gold 1,000,000 | Ruby 500 | Coins 0 | Cloud 0 | BP 0 */
const STORAGE_KEY = 'lanedef_v11_en';
let S = {
  coins: 0,
  cloud: 0,
  gold: 1000000,
  ruby: 500,
  bp: 0,
  azurePity: 0,
  freeDrawLastTime: 0,
  nid: 20,
  itemNid: 1,
  roster: [
    { id: 1, ch: "penguin", star: 1, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } },
    { id: 2, ch: "parrot", star: 1, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } },
    { id: 3, ch: "owl", star: 1, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } },
    { id: 4, ch: "duck", star: 1, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } },
    { id: 5, ch: "girl", star: 1, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } },
    { id: 6, ch: "knight", star: 2, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } },
    { id: 7, ch: "dragon", star: 3, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } }
  ],
  team: [1, 2, 3, 4, 5],
  itemsInventory: [],
  up: { mreg: 1, mmax: 1, rcd: 1, rdmg: 1, tower: 1, maxUnits: 10 },
  prog: { n: [0,0,0,0,0], h: [0,0,0,0,0] }
};

function loadState() {
  try {
    const data = JSON.parse(localStorage.getItem(STORAGE_KEY));
    if (data) S = { ...S, ...data };
  } catch (e) {}
}

function saveState() {
  try { localStorage.setItem(STORAGE_KEY, JSON.stringify(S)); } catch (e) {}
}

function getUnitStats(rosterItem) {
  const cls = HERO_CLASSES[rosterItem.ch] || HERO_CLASSES.penguin;
  if (rosterItem.ch === 'azuredragon') return { ap: 735, hp: 1890 };

  const starMult = 1 + 0.45 * (rosterItem.star - 1);
  const lvlMult = 1 + 0.15 * ((rosterItem.level || 1) - 1);

  let bonusAP = 0;
  let bonusHP = 0;

  if (rosterItem.items) {
    Object.values(rosterItem.items).forEach(itemId => {
      if (itemId) {
        const item = S.itemsInventory.find(i => i.id === itemId);
        if (item) {
          if (item.bonusAP) bonusAP += item.bonusAP;
          if (item.bonusHP) bonusHP += item.bonusHP;
        }
      }
    });
  }

  return {
    ap: Math.round(cls.baseAp * starMult * lvlMult) + bonusAP,
    hp: cls.useHitCount ? 0 : Math.round(cls.baseHp * starMult * lvlMult) + bonusHP,
    hc: cls.useHitCount ? cls.hitCount : 0
  };
}

let activePopoverHeroId = null;
let activeItemHeroId = null;
let activeItemFilter = 'all';
let currentGachaTab = 'heroes';
let lastDrawPacksContext = null;
let selectedLevelUpMaterials = [];
let activeShopTab = 'package';

function updateCurrencyDisplays() {
  document.querySelectorAll('.coins-val').forEach(e => e.textContent = S.coins.toLocaleString('en-US'));
  document.querySelectorAll('.cloud-val').forEach(e => e.textContent = S.cloud.toLocaleString('en-US'));
  document.querySelectorAll('.gold-val').forEach(e => e.textContent = S.gold.toLocaleString('en-US'));
  document.querySelectorAll('.ruby-val').forEach(e => e.textContent = S.ruby.toLocaleString('en-US'));
  document.querySelectorAll('.bp-val').forEach(e => e.textContent = S.bp.toLocaleString('en-US'));
  
  const charCountEl = $('txtMyCharCount');
  if (charCountEl) charCountEl.textContent = `My Characters : ${S.roster.length}/30`;

  if ($('txtPityCount')) $('txtPityCount').textContent = `${S.azurePity}/140`;
  if ($('pityGaugeBar')) $('pityGaugeBar').style.height = `${Math.min(100, (S.azurePity / 140) * 100)}%`;
}

function renderLobbyShowcase() {
  const container = $('lobbyHeroShowcase');
  container.innerHTML = S.team.map((id, idx) => {
    if (id === null || id === undefined) {
      return `
        <div class="flex flex-col items-center opacity-40 hover:opacity-80 cursor-pointer" onclick="openTeamSetupWithSlot(${idx})">
          <div class="w-12 h-12 rounded-2xl border-2 border-dashed border-yellow-300/60 flex items-center justify-center text-xl text-yellow-300 font-black">+</div>
          <div class="text-[10px] text-amber-200 font-bold mt-1">Slot ${idx + 1} Empty</div>
        </div>
      `;
    }
    const item = S.roster.find(r => r.id === id);
    if (!item) return '';
    const cls = HERO_CLASSES[item.ch] || HERO_CLASSES.penguin;
    return `
      <div class="flex flex-col items-center cursor-pointer" onclick="openTeamSetupWithSlot(${idx})">
        <div class="text-4xl md:text-5xl filter drop-shadow">${cls.icon}</div>
        <div class="text-[11px] text-amber-300 font-extrabold mt-1 tracking-widest">${'★'.repeat(item.star)}</div>
        <div class="text-xs font-black text-white leading-none mt-0.5">Lv.${item.level || 1}</div>
      </div>
    `;
  }).join('');
  updateCurrencyDisplays();
}

function openTeamSetupWithSlot(idx) {
  $('modalTeam').classList.remove('hidden');
  renderTeamSetup();
}

function openAzureDragonTemple() {
  $('modalGuardianTemple').classList.add('hidden');
  $('modalAzureDragonTemple').classList.remove('hidden');
  updateCurrencyDisplays();
}

function persuadeAzureDragon() {
  if (S.cloud < 30) return showToast("Not enough Cloud! Need 30 Cloud per attempt.");

  S.cloud -= 30;
  const rand = Math.random() * 100;
  let success = false;

  if (rand < 0.65) {
    success = true;
  } else {
    const pityRoll = Math.random() * 100;
    let points = 1;
    if (pityRoll < 70) points = 1;
    else if (pityRoll < 90) points = 2;
    else points = 4;

    S.azurePity += points;
    showToast(`Persuasion failed! Received +${points} Pity points.`);
    if (S.azurePity >= 140) success = true;
  }

  if (success) {
    S.azurePity = 0;
    const newDragon = { id: S.nid++, ch: 'azuredragon', star: 7, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } };
    S.roster.push(newDragon);
    saveState();
    updateCurrencyDisplays();
    showToast("🎉 SUCCESS! Azure Dragon has joined your squad!");
  } else {
    saveState();
    updateCurrencyDisplays();
  }
}

function renderTeamSetup() {
  updateCurrencyDisplays();

  // 1. Top Shelf Slots
  const shelfContainer = $('shelfSlotsContainer');
  shelfContainer.innerHTML = S.team.map((id, idx) => {
    if (id !== null && id !== undefined) {
      const item = S.roster.find(r => r.id === id);
      if (item) {
        const cls = HERO_CLASSES[item.ch] || HERO_CLASSES.penguin;
        return `
          <div class="shelf-slot" onclick="clickShelfSlot(${idx})" title="Click to unequip ${cls.name}">
            <div class="text-[9px] text-amber-300 font-black">${'★'.repeat(item.star)}</div>
            <div class="text-2xl">${cls.icon}</div>
            <div class="text-[10px] font-extrabold text-cyan-200 bg-black/50 w-full text-center rounded py-0.5">💧 ${cls.cost}</div>
          </div>
        `;
      }
    }
    return `
      <div class="shelf-slot empty-shelf-slot" onclick="clickShelfSlot(${idx})" title="Empty Slot">
        <div class="text-[10px] font-black text-amber-200/80">Slot ${idx + 1}</div>
        <div class="text-3xl text-amber-300/80 font-black">+</div>
        <div class="text-[9px] font-bold text-amber-200/60">EMPTY</div>
      </div>
    `;
  }).join('');

  // 2. Equipped Heroes first
  const equippedList = [];
  S.team.forEach((teamId, slotIdx) => {
    if (teamId !== null && teamId !== undefined) {
      const hero = S.roster.find(r => r.id === teamId);
      if (hero) equippedList.push({ ...hero, isEquipped: true, slotIdx: slotIdx + 1 });
    }
  });

  let unequippedList = S.roster.filter(r => !S.team.includes(r.id)).map(r => ({ ...r, isEquipped: false, slotIdx: null }));
  const fullSortedRoster = [...equippedList, ...unequippedList];

  const rosterContainer = $('rosterCardsRow');
  rosterContainer.innerHTML = fullSortedRoster.map(item => {
    const cls = HERO_CLASSES[item.ch] || HERO_CLASSES.penguin;
    const stats = getUnitStats(item);

    // Rule: Show ONLY HP if character uses HP, show ONLY HC if character uses Hit Count!
    let hpOrHcDisplay = cls.useHitCount
      ? `<div class="flex justify-between items-center text-amber-950"><span class="text-amber-800">HC</span><span class="text-blue-700 font-extrabold">${cls.hitCount}</span></div>`
      : `<div class="flex justify-between items-center text-amber-950"><span class="text-amber-800">HP</span><span class="text-emerald-700 font-extrabold">${stats.hp}</span></div>`;

    return `
      <div class="parchment-card star-${item.star}" onclick="openCharPopover(event, ${item.id})">
        ${item.isEquipped ? `<span class="act-badge">Act.</span><span class="slot-badge">${item.slotIdx}</span>` : ''}
        ${item.isLocked ? `<span class="lock-badge">🔒</span>` : ''}

        <div class="text-[11px] text-amber-600 font-black tracking-widest mt-0.5">${'★'.repeat(item.star)}</div>
        <div class="text-xs font-serif font-black text-amber-950 truncate max-w-full">${cls.name}</div>
        
        <div class="text-4xl my-1 flex justify-center items-center h-12">${cls.icon}</div>

        <div class="w-full flex items-center justify-between text-[10px] font-black text-amber-900 border-t border-amber-800/30 pt-1">
          <span>Lv.${item.level || 1}/20</span>
          <div class="w-12 h-2.5 bg-amber-900/30 rounded-full overflow-hidden border border-amber-800/50 relative">
            <div class="h-full bg-emerald-500" style="width: ${(item.exp || 0)}%;"></div>
            <span class="absolute inset-0 text-[8px] flex items-center justify-center text-amber-950 font-extrabold leading-none">${item.exp || 0}%</span>
          </div>
        </div>

        <div class="w-full flex items-center justify-between text-[9px] font-bold text-slate-800 bg-amber-200/60 rounded px-1.5 py-0.5 my-1">
          <span class="text-cyan-800 font-extrabold">💧 ${cls.cost}</span>
          <span class="truncate max-w-[70px] text-amber-900 font-extrabold">${cls.role}</span>
        </div>

        <div class="w-full space-y-0.5 text-[10px] font-black">
          <div class="flex justify-between items-center text-amber-950 border-b border-amber-800/20 pb-0.5">
            <span class="text-amber-800">AP</span>
            <span class="text-red-700 font-extrabold">${stats.ap}</span>
          </div>
          ${hpOrHcDisplay}
        </div>
      </div>
    `;
  }).join('');
}

function clickShelfSlot(slotIdx) {
  if (S.team[slotIdx] !== null && S.team[slotIdx] !== undefined) {
    S.team[slotIdx] = null;
    saveState();
    renderTeamSetup();
    renderLobbyShowcase();
  }
}

function openCharPopover(event, heroId) {
  event.stopPropagation();
  activePopoverHeroId = heroId;
  const item = S.roster.find(r => r.id === heroId);
  if (!item) return;

  const isEquipped = S.team.includes(heroId);
  $('popBtnUnequip').textContent = isEquipped ? "Unequip" : "Equip";
  $('popBtnLock').textContent = item.isLocked ? "Unlock" : "Lock";

  const popover = $('charContextMenu');
  popover.classList.remove('hidden');

  const rect = event.currentTarget.getBoundingClientRect();
  const parentRect = $('modalTeam').getBoundingClientRect();

  let left = rect.left - parentRect.left + 10;
  let top = rect.top - parentRect.top - 20;

  popover.style.left = `${Math.min(left, parentRect.width - 140)}px`;
  popover.style.top = `${Math.max(10, top)}px`;
}

function hideCharPopover() {
  $('charContextMenu').classList.add('hidden');
}

function handlePopoverAction(action) {
  if (!activePopoverHeroId) return;
  const heroId = activePopoverHeroId;
  const item = S.roster.find(r => r.id === heroId);
  if (!item) return;
  const cls = HERO_CLASSES[item.ch] || HERO_CLASSES.penguin;

  hideCharPopover();

  if (action === 'unequip') {
    const equippedSlot = S.team.indexOf(heroId);
    if (equippedSlot !== -1) {
      S.team[equippedSlot] = null;
      saveState();
      showToast(`Unequipped ${cls.name}!`);
    } else {
      const firstEmpty = S.team.findIndex(id => id === null || id === undefined);
      if (firstEmpty !== -1) {
        S.team[firstEmpty] = heroId;
        saveState();
        showToast(`Equipped ${cls.name} to Slot ${firstEmpty + 1}!`);
      } else {
        showToast("Team deployment slots are full!");
      }
    }
    renderTeamSetup();
    renderLobbyShowcase();
  } else if (action === 'sell') {
    if (item.isLocked) return showToast("Hero is LOCKED! Unlock first before selling.");
    if (S.team.includes(heroId)) return showToast("Cannot sell hero currently in active team!");

    const goldEarned = 500 * item.star;
    S.gold += goldEarned;
    S.roster = S.roster.filter(r => r.id !== heroId);
    saveState();
    showToast(`Sold ${cls.name} for +${goldEarned.toLocaleString('en-US')} Gold!`);
    renderTeamSetup();
  } else if (action === 'lock') {
    item.isLocked = !item.isLocked;
    saveState();
    showToast(item.isLocked ? `LOCKED ${cls.name}!` : `UNLOCKED ${cls.name}!`);
    renderTeamSetup();
  } else if (action === 'levelup') {
    openLevelUpFeedModal(heroId);
  } else if (action === 'item') {
    openHeroItemScreen(heroId);
  }
}

function openLevelUpFeedModal(targetHeroId) {
  const hero = S.roster.find(r => r.id === targetHeroId);
  if (!hero) return;
  const cls = HERO_CLASSES[hero.ch] || HERO_CLASSES.penguin;
  selectedLevelUpMaterials = [];

  $('levelUpTargetBanner').innerHTML = `
    <div class="text-5xl">${cls.icon}</div>
    <div class="flex-1">
      <div class="text-sm font-black text-amber-300">${cls.name} (${'★'.repeat(hero.star)})</div>
      <div class="text-xs text-slate-300">Current Level: <b class="text-emerald-400">Lv. ${hero.level || 1} / 20</b></div>
    </div>
  `;

  renderLevelUpMaterialGrid(targetHeroId);
  $('modalLevelUp').classList.remove('hidden');
}

function renderLevelUpMaterialGrid(targetHeroId) {
  const eligible = S.roster.filter(r => r.id !== targetHeroId && !S.team.includes(r.id) && !r.isLocked);
  
  $('levelUpMaterialGrid').innerHTML = eligible.length ? eligible.map(r => {
    const cls = HERO_CLASSES[r.ch] || HERO_CLASSES.penguin;
    const isSelected = selectedLevelUpMaterials.includes(r.id);

    return `
      <div class="p-2 rounded-xl border text-center cursor-pointer transition-transform ${isSelected ? 'bg-amber-500/30 border-amber-400 scale-105' : 'bg-slate-900 border-slate-700 hover:border-slate-500'}"
           onclick="toggleSelectMaterial(${r.id}, ${targetHeroId})">
        <div class="text-2xl">${cls.icon}</div>
        <div class="text-[10px] font-black truncate text-white">${cls.name}</div>
        <div class="text-[9px] text-amber-300 font-extrabold">${'★'.repeat(r.star)}</div>
      </div>
    `;
  }).join('') : `<div class="col-span-4 text-center text-xs text-slate-400 p-4">No available material heroes (Must be unequipped & unlocked)</div>`;

  const totalGainedExp = selectedLevelUpMaterials.length * 50;
  $('txtLevelUpPreview').textContent = `Preview: +${totalGainedExp} EXP (${selectedLevelUpMaterials.length} cards)`;
}

function toggleSelectMaterial(matId, targetHeroId) {
  if (selectedLevelUpMaterials.includes(matId)) {
    selectedLevelUpMaterials = selectedLevelUpMaterials.filter(id => id !== matId);
  } else {
    selectedLevelUpMaterials.push(matId);
  }
  renderLevelUpMaterialGrid(targetHeroId);
}

$('btnConfirmLevelUp').addEventListener('click', () => {
  if (!activePopoverHeroId || selectedLevelUpMaterials.length === 0) return showToast("Select at least 1 material hero!");
  const target = S.roster.find(r => r.id === activePopoverHeroId);
  if (!target) return;

  const gainedExp = selectedLevelUpMaterials.length * 50;
  target.exp = (target.exp || 0) + gainedExp;

  while (target.exp >= 100 && (target.level || 1) < 20) {
    target.exp -= 100;
    target.level = (target.level || 1) + 1;
  }
  if ((target.level || 1) >= 20) target.exp = 100;

  S.roster = S.roster.filter(r => !selectedLevelUpMaterials.includes(r.id));
  selectedLevelUpMaterials = [];

  saveState();
  $('modalLevelUp').classList.add('hidden');
  showToast(`Level Up Success! ${HERO_CLASSES[target.ch].name} reached Lv. ${target.level}!`);
  renderTeamSetup();
});

function openHeroItemScreen(heroId) {
  activeItemHeroId = heroId;
  const hero = S.roster.find(r => r.id === heroId);
  if (!hero) return;
  const cls = HERO_CLASSES[hero.ch] || HERO_CLASSES.penguin;

  if (!hero.items) hero.items = { clock: null, sword: null, shield: null, wings: null };

  $('itemHeroName').textContent = cls.name;
  $('itemHeroIcon').textContent = cls.icon;
  $('txtItemHeroCost').textContent = cls.cost;

  renderHeroItemScreen();
  $('modalHeroItem').classList.remove('hidden');
}

function renderHeroItemScreen() {
  const hero = S.roster.find(r => r.id === activeItemHeroId);
  if (!hero) return;
  const cls = HERO_CLASSES[hero.ch] || HERO_CLASSES.penguin;
  const stats = getUnitStats(hero);

  $('txtItemHeroAP').textContent = stats.ap;
  $('txtItemHeroHP').textContent = cls.useHitCount ? `${cls.hitCount} HC` : stats.hp;

  ['clock', 'sword', 'shield', 'wings'].forEach(type => {
    const slotEl = $(`slot${type.charAt(0).toUpperCase() + type.slice(1)}`);
    const equippedItemId = hero.items ? hero.items[type] : null;

    if (equippedItemId) {
      const item = S.itemsInventory.find(i => i.id === equippedItemId);
      if (item) {
        slotEl.className = 'item-slot-box has-item';
        slotEl.innerHTML = `
          <span class="text-2xl">${ITEM_TYPES[type].icon}</span>
          <span class="item-grade-badge grade-${item.grade}">${item.grade}</span>
        `;
      }
    } else {
      slotEl.className = 'item-slot-box';
      slotEl.innerHTML = `
        <span class="text-2xl">${ITEM_TYPES[type].icon}</span>
        <span class="text-[8px] font-black text-amber-200 absolute bottom-0.5">${type}</span>
      `;
    }
  });

  let sumMR = 0, sumPS = 0, sumAP = 0, sumSP = 0, sumHP = 0, sumAD = 0, sumAS = 0;
  if (hero.items) {
    Object.values(hero.items).forEach(itemId => {
      if (itemId) {
        const item = S.itemsInventory.find(i => i.id === itemId);
        if (item) {
          if (item.bonusAP) sumAP += item.bonusAP;
          if (item.bonusHP) sumHP += item.bonusHP;
          if (item.bonusSP) sumSP += item.bonusSP;
          if (item.bonusAD) sumAD += item.bonusAD;
        }
      }
    });
  }

  $('statMR').textContent = sumMR ? `+${sumMR}` : '-';
  $('statPS').textContent = sumPS ? `+${sumPS}` : '-';
  $('statAP').textContent = sumAP ? `+${sumAP}` : '-';
  $('statSP').textContent = sumSP ? `+${sumSP}%` : '-';
  $('statHP').textContent = sumHP ? `+${sumHP}` : '-';
  $('statAD').textContent = sumAD ? `+${sumAD}` : '-';
  $('statAS').textContent = sumAS ? `+${sumAS}` : '-';

  let items = S.itemsInventory;
  if (activeItemFilter !== 'all') items = items.filter(i => i.type === activeItemFilter);

  const grid = $('itemInventoryGrid');
  grid.innerHTML = items.length ? items.map(item => {
    const isEquipped = item.equippedToHeroId === activeItemHeroId;
    return `
      <div class="item-card-mini" onclick="clickInventoryItem(${item.id})">
        <span class="item-grade-badge grade-${item.grade}">${item.grade}</span>
        ${isEquipped ? `<span class="equip-tag">Equip</span>` : ''}
        <span class="new-tag">N</span>
        <div class="text-2xl my-auto">${ITEM_TYPES[item.type].icon}</div>
        <div class="text-[8px] font-black text-amber-200 bg-black/60 w-full text-center rounded truncate">${item.basicAbility}</div>
      </div>
    `;
  }).join('') : `<div class="col-span-6 text-center text-xs text-slate-400 p-6">No items in inventory! Draw item cards.</div>`;
}

function clickInventoryItem(itemId) {
  const item = S.itemsInventory.find(i => i.id === itemId);
  if (!item) return;

  $('lblItemTitle').textContent = ITEM_TYPES[item.type].name;
  $('lblItemPart').textContent = `Part : ${item.type}`;
  $('lblItemBasic').textContent = `basic ability : ${item.basicAbility}`;
  $('lblItemAdd').textContent = `additional ability : ${item.additionalAbility}`;

  const hero = S.roster.find(r => r.id === activeItemHeroId);
  if (!hero) return;
  if (!hero.items) hero.items = { clock: null, sword: null, shield: null, wings: null };

  if (hero.items[item.type] === item.id) {
    hero.items[item.type] = null;
    item.equippedToHeroId = null;
    showToast("Unequipped Item!");
  } else {
    hero.items[item.type] = item.id;
    item.equippedToHeroId = activeItemHeroId;
    showToast("Equipped Item!");
  }

  saveState();
  renderHeroItemScreen();
  renderTeamSetup();
}

function clickItemSlot(slotType) {
  activeItemFilter = slotType;
  renderHeroItemScreen();
}

$('itemFilterGroup').addEventListener('click', e => {
  if (e.target.dataset.type) {
    activeItemFilter = e.target.dataset.type;
    document.querySelectorAll('#itemFilterGroup button').forEach(b => {
      b.className = 'px-3 py-1 rounded-lg text-xs ' + (b.dataset.type === activeItemFilter ? 'font-black bg-amber-400 text-slate-950 shadow' : 'font-bold bg-slate-800 text-slate-300');
    });
    renderHeroItemScreen();
  }
});

/* ==================== SHOP TABS ==================== */
function renderShop() {
  updateCurrencyDisplays();
  const grid = $('shopGrid');
  grid.innerHTML = '';

  if (activeShopTab === 'package') {
    const packages = [
      { id: 'ogong', name: 'Sage Package', sub: 'Ogong', price: '109 Coins', icon: '🐒', desc: '8★ God Hero | AP 1200 / HP 3600\nKnockback + 1.5s Stun\nEvery 4th hit summons Big Monkey (5000 AOE Land Damage)' },
      { id: 'mukhyang', name: 'Bamboo Package', sub: 'Mukhyang', price: '109 Coins', icon: '🎋', desc: '8★ God Hero | AP 1000 / 30 HC\n1s Stun on hit\nEvery 4th hit applies Bamboo Seal on Tower (300 Dmg / 2s for 6s)' },
      { id: 'spiritserpent', name: 'Northern Package', sub: 'Spirit Serpent', price: '109 Coins', icon: '🐍', desc: '8★ God Hero | AP 870 / 25 HC\nEvery 5th hit summons Spirit Snake (400 Dmg to ALL land monsters)' },
      { id: 'flamecavalier', name: 'Flame Package', sub: 'Flame Cavalier', price: '109 Coins', icon: '🏇', desc: '8★ God Hero | AP 275 / HP 1300\nAOE Cleave Burn attacks\n1 attack buffed by x20 Damage (5500 AP)' }
    ];

    grid.innerHTML = packages.map(p => `
      <div class="shop-card w-52 h-80 bg-gradient-to-b from-amber-100 via-amber-200 to-amber-400 text-slate-900 border-2 border-amber-500">
        <div class="text-xs font-black text-amber-900 tracking-wider text-center uppercase">${p.name}</div>
        <div class="text-base font-black text-rose-700 text-center">◇ ${p.sub} ◇</div>
        <div class="text-6xl my-2 filter drop-shadow">${p.icon}</div>
        <div class="text-[10px] font-extrabold text-slate-800 text-center whitespace-pre-line bg-amber-50/80 p-1.5 rounded-lg border border-amber-300 w-full">${p.desc}</div>
        <button class="mt-2 w-full py-2 rounded-xl bg-gradient-to-r from-amber-400 to-yellow-500 text-slate-950 font-black text-sm border border-white shadow hover:scale-105 transition-transform" onclick="buyPackage('${p.id}')">
          US $109 (${p.price})
        </button>
      </div>
    `).join('');

  } else if (activeShopTab === 'ruby') {
    const rubyPacks = [
      { coins: 2, ruby: 20, bp: 5 },
      { coins: 5, ruby: 70, bp: 12 },
      { coins: 10, ruby: 150, bp: 25 },
      { coins: 20, ruby: 350, bp: 50 },
      { coins: 40, ruby: 800, bp: 100 }
    ];

    grid.innerHTML = rubyPacks.map(r => `
      <div class="shop-card w-48 h-72 bg-gradient-to-b from-rose-400 via-orange-500 to-amber-600 text-white relative">
        <div class="absolute top-2 right-2 bg-amber-400 text-slate-950 font-black text-[10px] px-2 py-0.5 rounded-full border border-white">
          +${r.bp} B.P.
        </div>
        <div class="text-xl font-black text-amber-200 mt-2">Ruby</div>
        <div class="text-5xl my-2">💎</div>
        <div class="text-2xl font-black text-yellow-300">${r.ruby}</div>
        <button class="w-full py-2 rounded-xl bg-amber-300 text-slate-950 font-black text-sm border border-white shadow hover:scale-105" onclick="buyRuby(${r.coins}, ${r.ruby}, ${r.bp})">
          💵 ${r.coins} Coins
        </button>
      </div>
    `).join('');

  } else if (activeShopTab === 'gold') {
    const goldPacks = [
      { ruby: 10, gold: 17000 },
      { ruby: 30, gold: 54000 },
      { ruby: 70, gold: 133000 },
      { ruby: 100, gold: 200000 },
      { ruby: 150, gold: 315000 }
    ];

    grid.innerHTML = goldPacks.map(g => `
      <div class="shop-card w-48 h-72 bg-gradient-to-b from-amber-300 via-yellow-400 to-amber-600 text-slate-950">
        <div class="text-xl font-black text-amber-900 mt-2">Gold</div>
        <div class="text-5xl my-2">🪙</div>
        <div class="text-lg font-black text-amber-950">${g.gold.toLocaleString('en-US')}</div>
        <button class="w-full py-2 rounded-xl bg-slate-900 text-yellow-300 font-black text-sm border border-yellow-400 shadow hover:scale-105" onclick="buyGold(${g.ruby}, ${g.gold})">
          💎 ${g.ruby} Ruby
        </button>
      </div>
    `).join('');
  }
}

function buyPackage(heroKey) {
  if (S.coins < 109) return showToast("Not enough Coins! Requires 109 Coins.");
  S.coins -= 109;

  const newHero = { id: S.nid++, ch: heroKey, star: 8, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } };
  S.roster.push(newHero);
  saveState();
  updateCurrencyDisplays();
  showToast(`🎉 Purchased 8★ ${HERO_CLASSES[heroKey].name} Package!`);
}

function buyRuby(coins, ruby, bp) {
  if (S.coins < coins) return showToast("Not enough Coins!");
  S.coins -= coins; S.ruby += ruby; S.bp += bp;
  saveState(); updateCurrencyDisplays();
  showToast(`Exchanged ${coins} Coins for +${ruby} Ruby & +${bp} B.P.!`);
}

function buyGold(ruby, gold) {
  if (S.ruby < ruby) return showToast("Not enough Ruby!");
  S.ruby -= ruby; S.gold += gold;
  saveState(); updateCurrencyDisplays();
  showToast(`Exchanged ${ruby} Ruby for +${gold.toLocaleString('en-US')} Gold!`);
}

/* ==================== GACHA PACKS DRAW & BP CALCULATION ==================== */
function renderGachaPacks() {
  updateCurrencyDisplays();
  const track = $('gachaPacksTrack');
  const packs = currentGachaTab === 'heroes' ? CHARACTER_GACHA_PACKS : ITEM_GACHA_PACKS;

  track.innerHTML = packs.map(pack => {
    const isSpecial = pack.id === 'special';
    let costDisplay = '';

    if (isSpecial) {
      const now = Date.now();
      const elapsed = Math.floor((now - (S.freeDrawLastTime || 0)) / 1000);
      const remaining = 3600 - elapsed;

      if (remaining <= 0) {
        costDisplay = `<span class="text-amber-200">⏰ Free Select!!</span>`;
      } else {
        const mins = Math.floor(remaining / 60);
        const secs = remaining % 60;
        costDisplay = `<span class="text-slate-300">⏳ ${mins}:${secs < 10 ? '0' : ''}${secs}</span>`;
      }
    } else if (pack.costType === 'ruby') {
      costDisplay = `<span>💎</span> <span>${pack.cost}</span>`;
    } else if (pack.costType === 'bp') {
      costDisplay = `<span class="px-1 bg-amber-400 text-slate-950 rounded text-[10px]">B.P.</span> <span>${pack.cost}</span>`;
    } else if (pack.costType === 'coins') {
      costDisplay = `<span class="text-amber-300 font-extrabold">${pack.label || pack.cost + ' Coins'}</span>`;
    }

    let icons = currentGachaTab === 'items' ? "⏱️🗡️🛡️👟" : "🐧🦜🦉👧";

    return `
      <div class="gacha-card theme-${pack.theme}" onclick="triggerDraw('${pack.id}')">
        ${pack.event ? `<div class="event-ribbon">${pack.event}</div>` : ''}

        <div class="bg-slate-950/80 border border-yellow-300 rounded-xl w-full text-center py-1">
          <div class="text-xs font-black text-amber-300 tracking-wider">${pack.title}</div>
        </div>

        <div class="text-xs font-serif font-black text-white text-center">${pack.subtitle}</div>

        <div class="my-auto text-4xl flex justify-center items-center gap-1 filter drop-shadow">
          ${icons}
        </div>

        <div class="w-full py-1.5 rounded-xl bg-slate-950/90 border border-yellow-400 flex items-center justify-center gap-1.5 text-xs font-black text-white shadow">
          ${costDisplay}
        </div>
      </div>
    `;
  }).join('');
}

function triggerDraw(packId) {
  const isItemTab = currentGachaTab === 'items';
  const pack = (isItemTab ? ITEM_GACHA_PACKS : CHARACTER_GACHA_PACKS).find(p => p.id === packId);
  if (!pack) return;

  lastDrawPacksContext = packId;

  // Rule: Free pack gives 0 BP. Ruby packs give Ruby / 10 BP!
  let bpEarned = 0;

  if (pack.type === 'free') {
    const now = Date.now();
    const elapsed = Math.floor((now - (S.freeDrawLastTime || 0)) / 1000);
    if (elapsed < 3600) {
      const mins = Math.ceil((3600 - elapsed) / 60);
      return showToast(`Free draw requires waiting ${mins} more minutes!`);
    }
    S.freeDrawLastTime = now;
    bpEarned = 0; // 0 BP for Free Pack
  } else if (pack.costType === 'ruby') {
    if (S.ruby < pack.cost) return showToast("Not enough Ruby!");
    S.ruby -= pack.cost;
    bpEarned = Math.floor(pack.cost / 10); // Ruby / 10 BP rule! (e.g., 10 Ruby -> 1 BP, 20 Ruby -> 2 BP)
  } else if (pack.costType === 'bp') {
    if (S.bp < pack.cost) return showToast("Not enough Bonus Point (B.P.)!");
    S.bp -= pack.cost;
    bpEarned = 0;
  } else if (pack.costType === 'coins') {
    if (S.coins < pack.cost) return showToast("Not enough Coins!");
    S.coins -= pack.cost;
    bpEarned = 0;
  }

  S.bp += bpEarned;

  let drawCount = pack.count;
  if (pack.event === 'Character 1+1 Event') drawCount *= 2;

  const pulled = [];

  if (isItemTab) {
    const itemTypesList = pack.filterTypes || ['clock', 'sword', 'shield', 'wings'];
    for (let i = 0; i < drawCount; i++) {
      const t = itemTypesList[Math.floor(Math.random() * itemTypesList.length)];
      let grade = 'F';
      const rand = Math.random() * 100;
      if (pack.minGrade === 'C') {
        grade = rand < 60 ? 'C' : 'B';
      } else {
        if (rand > 95) grade = 'C';
        else if (rand > 70) grade = 'D';
        else grade = 'E';
      }

      let basicStr = "SP +50%";
      let addStr = "AD +58";
      let bAP = 0, bHP = 0, bSP = 0, bAD = 0;

      if (t === 'sword') {
        bAP = grade === 'B' ? 2500 : grade === 'C' ? 500 : 50;
        bAD = grade === 'B' ? 150 : 58;
        basicStr = `AP +${bAP}`; addStr = `AD +${bAD}`;
      } else if (t === 'shield') {
        bHP = grade === 'B' ? 15000 : grade === 'C' ? 3000 : 300;
        basicStr = `HP +${bHP}`; addStr = "MR +50";
      } else if (t === 'wings') {
        bSP = grade === 'B' ? 25 : 10;
        bAD = grade === 'B' ? 160 : 60;
        basicStr = `SP +${bSP}%`; addStr = `AD +${bAD}`;
      } else if (t === 'clock') {
        basicStr = "AS +15%"; addStr = "PS +10";
      }

      const newItem = {
        id: S.itemNid++,
        type: t, grade,
        basicAbility: basicStr,
        additionalAbility: addStr,
        bonusAP: bAP, bonusHP: bHP, bonusSP: bSP, bonusAD: bAD,
        equippedToHeroId: null
      };
      S.itemsInventory.push(newItem);
      pulled.push({ isItem: true, ...newItem });
    }
  } else {
    const heroKeys = Object.keys(HERO_CLASSES).filter(k => k !== 'azuredragon');
    for (let i = 0; i < drawCount; i++) {
      let star = pack.minStar;
      if (pack.maxStar > pack.minStar) {
        const rand = Math.random() * 100;
        if (rand > 92 && pack.maxStar >= 7) star = 7;
        else if (rand > 80 && pack.maxStar >= 6) star = 6;
        else if (rand > 60 && pack.maxStar >= 5) star = 5;
        else if (rand > 35 && pack.maxStar >= 4) star = 4;
        else star = Math.max(pack.minStar, 3);
      }

      let chKey = heroKeys[Math.floor(Math.random() * heroKeys.length)];
      if (star === 7) chKey = ['golddragon', 'phoenix', 'angel'][Math.floor(Math.random() * 3)];
      else if (star === 6) chKey = ['demon', 'robot', 'capowl', 'knight'][Math.floor(Math.random() * 4)];

      const newHero = { id: S.nid++, ch: chKey, star, level: 1, exp: 0, isLocked: false, items: { clock: null, sword: null, shield: null, wings: null } };
      S.roster.push(newHero);
      pulled.push({ isItem: false, ...newHero });
    }
  }

  saveState();
  updateCurrencyDisplays();
  renderGachaPacks();

  // Selection Completed Modal
  const resultGrid = $('gachaResultCards');
  resultGrid.innerHTML = pulled.map(item => {
    if (item.isItem) {
      return `
        <div class="bg-amber-950/80 border-2 border-amber-500 rounded-xl p-2 text-center flex flex-col justify-between items-center shadow-lg relative">
          <span class="item-grade-badge grade-${item.grade}">${item.grade}</span>
          <div class="text-xs font-black text-amber-200 mt-1">${ITEM_TYPES[item.type].name}</div>
          <div class="text-3xl my-1">${ITEM_TYPES[item.type].icon}</div>
          <div class="bg-slate-950/90 border border-amber-400 rounded p-1 w-full text-[9px] font-black text-cyan-300">
            ${item.basicAbility}
          </div>
        </div>
      `;
    } else {
      const cls = HERO_CLASSES[item.ch] || HERO_CLASSES.penguin;
      const stats = getUnitStats(item);
      const hpOrHcText = cls.useHitCount ? `HC: ${cls.hitCount}` : `HP: ${stats.hp}`;

      return `
        <div class="bg-amber-950/80 border-2 border-amber-500 rounded-xl p-2 text-center flex flex-col justify-between items-center shadow-lg relative">
          <div class="text-xs font-black text-amber-200 mt-1">${cls.name}</div>
          <div class="text-3xl my-1">${cls.icon}</div>
          <div class="text-xs text-amber-300 font-black">${'★'.repeat(item.star)}</div>
          <div class="bg-slate-950/90 border border-red-400 rounded p-1 w-full text-[9px] font-black text-red-300 mt-1">
            AP: ${stats.ap} | ${hpOrHcText}
          </div>
        </div>
      `;
    }
  }).join('');

  $('modalGachaResult').classList.remove('hidden');
}

/* ==================== UPGRADE SCREEN (TT) ==================== */
function renderUpgrades() {
  updateCurrencyDisplays();
  const upgradeList = [
    { key: "mreg", name: "Mana Production Rate", maxLvl: 160, baseCost: 2000, icon: "💎⏱️" },
    { key: "mmax", name: "Max Mana Capacity", maxLvl: 160, baseCost: 2000, icon: "💎📦" },
    { key: "rcd",  name: "Missile Reload Cooldown", maxLvl: 120, baseCost: 2000, icon: "🚀⏱️" },
    { key: "rdmg", name: "Missile Firepower", maxLvl: 160, baseCost: 2000, icon: "🚀💥" },
    { key: "tower", name: "Tower Max HP", maxLvl: 160, baseCost: 2000, icon: "🐧🛡️" },
    { key: "maxUnits", name: "Max Deployed Heroes", maxLvl: 20, baseCost: 100000, icon: "🐧🐧", isUnitsCap: true }
  ];

  const grid = $('upgradeGrid');
  grid.innerHTML = upgradeList.map(u => {
    const curLvl = S.up[u.key] || (u.isUnitsCap ? 10 : 1);
    const isMax = curLvl >= u.maxLvl;
    const cost = u.isUnitsCap ? 100000 : Math.round(u.baseCost * Math.pow(1.05, curLvl - 1));

    return `
      <div class="upgrade-card h-60">
        <div class="text-xs font-extrabold text-slate-800 text-center h-8 flex items-center justify-center">${u.name}</div>
        <div class="bg-slate-900 text-amber-300 font-black text-[10px] px-3 py-0.5 rounded-full border border-yellow-400">
          LEVEL ${curLvl}/${u.maxLvl}
        </div>
        <div class="text-5xl my-2">${u.icon}</div>
        <button class="w-full py-2 rounded-xl font-black text-xs ${isMax ? 'bg-slate-400 text-slate-700' : 'bg-amber-400 text-slate-950 hover:bg-amber-300 border border-white'}"
                onclick="doUpgrade('${u.key}', ${cost}, ${u.maxLvl}, ${u.isUnitsCap || false})" ${isMax ? 'disabled' : ''}>
          ${isMax ? 'MAX' : `🪙 ${cost.toLocaleString('en-US')}`}
        </button>
      </div>
    `;
  }).join('');
}

function doUpgrade(key, cost, maxLvl, isUnitsCap) {
  if (S.gold < cost) return showToast("Not enough Gold!");
  const cur = S.up[key] || (isUnitsCap ? 10 : 1);
  if (cur >= maxLvl) return;

  S.gold -= cost;
  S.up[key] = cur + 1;
  saveState();
  renderUpgrades();
  showToast(`Upgraded to Level ${S.up[key]}!`);
}

/* ==================== MAP SELECTION & BATTLE ENGINE ==================== */
function renderMapNodes() {
  const isHard = Boolean(S.isHardMode);
  const modeKey = isHard ? 'h' : 'n';

  $('mapNodesContainer').innerHTML = MAPS.map((map, idx) => {
    const isUnlocked = idx === 0 || (S.prog[modeKey][idx - 1] >= 20);
    const prog = S.prog[modeKey][idx] || 0;

    return `
      <div class="flex flex-col items-center cursor-pointer transition-transform hover:scale-110" onclick="openMapLevels(${idx})">
        <div class="w-20 h-20 rounded-2xl flex items-center justify-center text-4xl shadow-2xl border-2 ${isUnlocked ? 'border-amber-400 bg-gradient-to-br from-amber-500 to-yellow-700' : 'border-slate-600 bg-slate-800 opacity-50'}">
          ${isUnlocked ? map.icon : '🔒'}
        </div>
        <div class="text-xs font-extrabold text-white mt-2">${map.name}</div>
        <div class="text-[10px] text-amber-300 font-bold">${isUnlocked ? `${prog}/20 Cleared` : 'Locked'}</div>
      </div>
    `;
  }).join('');
}

function openMapLevels(mapIdx) {
  const isHard = Boolean(S.isHardMode);
  const modeKey = isHard ? 'h' : 'n';
  if (mapIdx > 0 && S.prog[modeKey][mapIdx - 1] < 20) return showToast("Clear the previous map first!");

  const map = MAPS[mapIdx];
  $('levelMapTitle').textContent = `${map.name} (${isHard ? 'Hard' : 'Normal'})`;
  $('levelMonstersText').textContent = "Monsters: " + ENEMY_TYPES[mapIdx].map(m => m[0]).join(', ');

  const prog = S.prog[modeKey][mapIdx] || 0;
  $('levelGrid').innerHTML = Array.from({ length: 20 }, (_, i) => {
    const lvlNum = i + 1;
    const isPassed = i < prog;
    const isCurrent = i === prog;
    const isLocked = i > prog;

    return `
      <button class="p-3 rounded-xl border font-black text-sm flex flex-col items-center gap-1 ${isPassed ? 'bg-emerald-700 border-emerald-400 text-white' : isCurrent ? 'bg-amber-400 border-white text-slate-950' : 'bg-slate-800 border-slate-700 text-slate-500'}"
              onclick="startBattle(${mapIdx}, ${lvlNum})" ${isLocked ? 'disabled' : ''}>
        <span>${isLocked ? '🔒' : lvlNum}</span>
        <span class="text-[9px] font-bold">${isPassed ? '✓ Clear' : isCurrent ? 'Play' : 'Lock'}</span>
      </button>
    `;
  }).join('');

  $('modalLevels').classList.remove('hidden');
}

let gameState = null;
let animReqId = null;

function validateTeamAndStart() {
  const activeTeam = S.team.filter(id => id !== null && id !== undefined);
  if (activeTeam.length === 0) {
    showToast("Deploy at least 1 hero into your squad!");
    $('modalTeam').classList.remove('hidden');
    renderTeamSetup();
    return false;
  }
  return true;
}

function startBattle(mapIdx = 0, levelNum = 1) {
  if (!validateTeamAndStart()) return;

  $('modalLevels').classList.add('hidden');
  $('modalTeam').classList.add('hidden');
  $('modalGacha').classList.add('hidden');
  $('modalGuardianTemple').classList.add('hidden');
  $('modalAzureDragonTemple').classList.add('hidden');
  $('mapSelect').classList.add('hidden');
  $('lobby').classList.add('hidden');
  $('gameStage').classList.remove('hidden');

  const isHard = Boolean(S.isHardMode);
  const hpMult = (1 + 0.1 * (levelNum - 1) + 0.5 * mapIdx) * (isHard ? 1.5 : 1);
  const dmgMult = (1 + 0.08 * (levelNum - 1) + 0.3 * mapIdx) * (isHard ? 1.3 : 1);

  const maxManaCap = 100 + (S.up.mmax - 1) * 15;
  const towerHpVal = 75 + (S.up.tower - 1) * 20;

  gameState = {
    mapIdx, levelNum, isHard,
    enemyHpMult: hpMult, enemyDmgMult: dmgMult,
    playerHp: towerHpVal, playerMaxHp: towerHpVal,
    enemyHp: Math.round((100 + 50 * (levelNum - 1) + 200 * mapIdx) * (isHard ? 1.5 : 1)),
    enemyMaxHp: Math.round((100 + 50 * (levelNum - 1) + 200 * mapIdx) * (isHard ? 1.5 : 1)),
    mana: maxManaCap, maxMana: maxManaCap, manaLevel: 1, manaUpgradeCost: 10,
    units: [], projectiles: [], rockets: [],
    rocketReady: true, rocketCooldown: 0,
    spawnTimer: 1.5, unitCooldowns: [0, 0, 0, 0, 0],
    bambooSeals: [],
    enemiesDefeated: 0, maxWaveEnemies: 10,
    isRunning: true, lastTime: performance.now(), timeSec: 0
  };

  $('txtTopMode').textContent = isHard ? "Hard Mode" : "Normal Mode";
  $('txtTopStage').textContent = `Stage ${levelNum}`;

  renderBattleDeck();
  $('battleEndModal').classList.add('hidden');

  if (animReqId) cancelAnimationFrame(animReqId);
  animReqId = requestAnimationFrame(battleLoop);
}

function renderBattleDeck() {
  const container = $('heroSummonCards');
  container.innerHTML = S.team.map((id, idx) => {
    if (id === null || id === undefined) {
      return `<div class="card-slot opacity-40 cursor-not-allowed"><span class="card-num">${idx + 1}</span><div class="text-xl my-auto text-slate-400 font-black">-</div><div class="card-cost">Empty</div></div>`;
    }
    const item = S.roster.find(r => r.id === id);
    if (!item) return '';
    const cls = HERO_CLASSES[item.ch] || HERO_CLASSES.penguin;
    return `
      <button class="card-slot" id="btnSummon-${idx}" onclick="summonHero(${idx})">
        <span class="card-num">${idx + 1}</span>
        <span class="card-stars">${'★'.repeat(Math.min(item.star, 3))}</span>
        <div class="text-3xl my-auto">${cls.icon}</div>
        <div class="card-cost">💎 ${cls.cost}</div>
        <div class="cooldown-overlay hidden" id="cdSummon-${idx}">0</div>
      </button>
    `;
  }).join('');
}

function summonHero(teamIdx) {
  if (!gameState || !gameState.isRunning) return;
  const heroId = S.team[teamIdx];
  if (heroId === null || heroId === undefined) return;

  // Max units cap check on battlefield
  const currentActiveUnits = gameState.units.filter(u => u.side === 'player').length;
  const maxAllowed = S.up.maxUnits || 10;
  if (currentActiveUnits >= maxAllowed) {
    return showToast(`Max deployed hero limit reached (${maxAllowed})!`);
  }

  const item = S.roster.find(r => r.id === heroId);
  if (!item) return;
  const cls = HERO_CLASSES[item.ch] || HERO_CLASSES.penguin;

  if (cls.isUnique) {
    const existingUnique = gameState.units.some(u => u.side === 'player' && u.chKey === item.ch && u.hp > 0);
    if (existingUnique) return showToast("Azure Dragon is already on field!");
  }

  if (gameState.unitCooldowns[teamIdx] > 0) return showToast("Cooldown active!");
  if (gameState.mana < cls.cost) return showToast("Not enough Mana!");

  gameState.mana -= cls.cost;
  gameState.unitCooldowns[teamIdx] = cls.cd;

  const stats = getUnitStats(item);
  gameState.units.push({
    side: 'player', x: 130,
    hp: stats.hp, maxHp: stats.hp,
    useHitCount: cls.useHitCount || false,
    hc: cls.hitCount || 0, maxHc: cls.hitCount || 0,
    ap: stats.ap, spd: cls.spd, rng: cls.rng, fx: cls.fx, icon: cls.icon,
    chKey: item.ch, attackCd: 0, attackCount: 0, stunTimer: 0, lunge: 0
  });

  showToast(`Summoned ${cls.name}!`);
}

function upgradeManaLevel() {
  if (!gameState || !gameState.isRunning) return;
  if (gameState.mana < gameState.manaUpgradeCost) return showToast("Not enough Mana!");
  gameState.mana -= gameState.manaUpgradeCost;
  gameState.manaLevel++;
  gameState.maxMana += 20;
  gameState.manaUpgradeCost = Math.round(gameState.manaUpgradeCost * 1.5);
  showToast(`Mana upgraded to Lv. ${gameState.manaLevel}!`);
}

function spawnEnemyUnit() {
  const mapEnemies = ENEMY_TYPES[gameState.mapIdx];
  const template = mapEnemies[Math.floor(Math.random() * mapEnemies.length)];

  gameState.units.push({
    side: 'enemy', x: W - 130,
    hp: Math.round(template[1] * gameState.enemyHpMult),
    maxHp: Math.round(template[1] * gameState.enemyHpMult),
    ap: Math.round(template[2] * gameState.enemyDmgMult),
    spd: template[3], rng: template[4], fx: template[5],
    icon: template[0].split(' ')[0], attackCd: 0, stunTimer: 0, lunge: 0
  });
}

function fireRocket() {
  if (!gameState || !gameState.isRunning || !gameState.rocketReady) return;
  gameState.rocketReady = false;
  gameState.rocketCooldown = Math.max(5, 15 - (S.up.rcd - 1) * 0.1);

  const enemies = gameState.units.filter(u => u.side === 'enemy').sort((a, b) => a.x - b.x);
  const targetX = enemies.length > 0 ? enemies[0].x : W - 110;

  gameState.rockets.push({ sx: 110, sy: LANE - 50, x: 110, y: LANE - 50, tx: targetX, ty: LANE + 10, progress: 0, duration: 1.0 });
  showToast("Missile Launched!");
}

function battleLoop(now) {
  if (!gameState || !gameState.isRunning) return;

  const dt = Math.min((now - gameState.lastTime) / 1000, 0.1);
  gameState.lastTime = now;
  gameState.timeSec += dt;

  const regenRate = 12 * (1 + (S.up.mreg - 1) * 0.08);
  gameState.mana = Math.min(gameState.maxMana, gameState.mana + regenRate * dt);

  for (let i = 0; i < 5; i++) {
    if (gameState.unitCooldowns[i] > 0) gameState.unitCooldowns[i] = Math.max(0, gameState.unitCooldowns[i] - dt);
  }

  if (!gameState.rocketReady) {
    gameState.rocketCooldown -= dt;
    if (gameState.rocketCooldown <= 0) {
      gameState.rocketReady = true; gameState.rocketCooldown = 0;
    }
  }

  gameState.spawnTimer -= dt;
  if (gameState.spawnTimer <= 0) {
    spawnEnemyUnit();
    gameState.spawnTimer = Math.max(2.5, 5.0 - gameState.levelNum * 0.15);
  }

  // Bamboo Seals on Enemy Tower
  gameState.bambooSeals.forEach(seal => {
    seal.timer -= dt;
    seal.nextTick -= dt;
    if (seal.nextTick <= 0) {
      seal.nextTick = 2.0;
      gameState.enemyHp = Math.max(0, gameState.enemyHp - 300);
      showToast("🎋 Bamboo Seal ticks 300 damage to enemy tower!");
    }
  });
  gameState.bambooSeals = gameState.bambooSeals.filter(s => s.timer > 0);

  gameState.units.forEach(u => {
    if (u.stunTimer > 0) {
      u.stunTimer -= dt;
      return;
    }

    u.attackCd -= dt;
    u.lunge = Math.max(0, u.lunge - dt * 4);

    let target = null;
    let minDist = 9999;

    gameState.units.forEach(o => {
      if (o.side !== u.side) {
        const dist = Math.abs(o.x - u.x);
        if (dist <= u.rng && dist < minDist) {
          minDist = dist; target = o;
        }
      }
    });

    if (target) {
      if (u.attackCd <= 0) {
        u.lunge = 1; u.attackCd = 0.8;
        executeSpecialAttack(u, target);
      }
    } else if (u.side === 'player' && (W - 120 - u.x) <= u.rng) {
      if (u.attackCd <= 0) {
        u.lunge = 1; u.attackCd = 1.0;
        executeSpecialAttack(u, { isTower: true, side: 'enemy', x: W - 90 });
      }
    } else if (u.side === 'enemy' && (u.x - 120) <= u.rng) {
      if (u.attackCd <= 0) {
        u.lunge = 1; u.attackCd = 1.0;
        dealDamage({ isTower: true, side: 'player' }, u.ap);
      }
    } else {
      u.x += (u.side === 'player' ? 1 : -1) * u.spd * 32 * dt;
    }
  });

  gameState.units = gameState.units.filter(u => {
    if (u.useHitCount ? u.hc <= 0 : u.hp <= 0) {
      if (u.side === 'enemy') gameState.enemiesDefeated++;
      return false;
    }
    return true;
  });

  gameState.rockets.forEach(r => {
    r.progress += dt / r.duration;
    const k = Math.min(1, r.progress);
    r.x = r.sx + (r.tx - r.sx) * k;
    r.y = r.sy + (r.ty - r.sy) * k - Math.sin(k * Math.PI) * 100;

    if (r.progress >= 1) {
      r.done = true;
      const rDmg = 80 + (S.up.rdmg - 1) * 20;
      gameState.units.forEach(u => {
        if (u.side === 'enemy' && Math.abs(u.x - r.tx) < 80) dealDamage(u, rDmg);
      });
      if (Math.abs((W - 90) - r.tx) < 80) gameState.enemyHp = Math.max(0, gameState.enemyHp - rDmg);
    }
  });
  gameState.rockets = gameState.rockets.filter(r => !r.done);

  drawBattlefieldCanvas();
  updateBattleHUD();

  if (gameState.playerHp <= 0) return endBattle(false);
  if (gameState.enemyHp <= 0) return endBattle(true);

  animReqId = requestAnimationFrame(battleLoop);
}

function executeSpecialAttack(attacker, target) {
  attacker.attackCount = (attacker.attackCount || 0) + 1;

  if (attacker.chKey === 'ogong') {
    dealDamage(target, attacker.ap);
    if (!target.isTower) {
      target.x += 40;
      target.stunTimer = 1.5;
    }
    if (attacker.attackCount >= 4) {
      attacker.attackCount = 0;
      showToast("🐒 OGONG SUMMONS BIG MONKEY FOR 5000 AOE DAMAGE!");
      gameState.units.forEach(e => {
        if (e.side === 'enemy') dealDamage(e, 5000);
      });
    }

  } else if (attacker.chKey === 'mukhyang') {
    dealDamage(target, attacker.ap);
    if (!target.isTower) target.stunTimer = 1.0;
    if (attacker.attackCount >= 4) {
      attacker.attackCount = 0;
      showToast("🎋 MUKHYANG PLACES BAMBOO SEAL ON ENEMY TOWER!");
      gameState.bambooSeals.push({ timer: 6.0, nextTick: 2.0 });
    }

  } else if (attacker.chKey === 'spiritserpent') {
    dealDamage(target, attacker.ap);
    if (attacker.attackCount >= 5) {
      attacker.attackCount = 0;
      showToast("🐍 SPIRIT SERPENT SWEEPS ENEMY LAND WITH SPIRIT SNAKE (400 DMG)!");
      gameState.units.forEach(e => {
        if (e.side === 'enemy') dealDamage(e, 400);
      });
    }

  } else if (attacker.chKey === 'flamecavalier') {
    const dmg = attacker.ap * 20; // 5500 Damage
    showToast("FC FLAME CAVALIER EMPAWAERED ATTACK (5500 AP)!");
    gameState.units.forEach(e => {
      if (e.side === 'enemy' && Math.abs(e.x - attacker.x) <= 80) dealDamage(e, dmg);
    });

  } else {
    dealDamage(target, attacker.ap);
  }
}

function dealDamage(target, dmg) {
  if (target.isTower) {
    if (target.side === 'player') gameState.playerHp = Math.max(0, gameState.playerHp - dmg);
    else gameState.enemyHp = Math.max(0, gameState.enemyHp - dmg);
  } else if (target.useHitCount) {
    target.hc = Math.max(0, target.hc - 1);
  } else if (target.hp > 0) {
    target.hp -= dmg;
  }
}

function updateBattleHUD() {
  $('lblManaLvl').textContent = `Lv. ${gameState.manaLevel}`;
  $('lblManaCost').textContent = gameState.manaUpgradeCost;
  $('battleManaText').textContent = `${Math.floor(gameState.mana)} / ${gameState.maxMana}`;
  $('txtWaveProgress').textContent = `${gameState.enemiesDefeated} / ${gameState.maxWaveEnemies}`;

  $('btnRocket').disabled = !gameState.rocketReady;
  $('rocketCdText').classList.toggle('hidden', gameState.rocketReady);$('rocketCdText').textContent = Math.ceil(gameState.rocketCooldown);

  for (let i = 0; i < 5; i++) {
    const cd = gameState.unitCooldowns[i];
    const cdOverlay = $(`cdSummon-${i}`);
    const btn = $(`btnSummon-${i}`);
    if (cdOverlay && btn) {
      cdOverlay.classList.toggle('hidden', cd <= 0);
      cdOverlay.textContent = Math.ceil(cd);
      const heroId = S.team[i];
      const item = heroId !== null && heroId !== undefined ? S.roster.find(r => r.id === heroId) : null;
      const cls = item ? (HERO_CLASSES[item.ch] || HERO_CLASSES.penguin) : null;
      btn.disabled = !cls || cd > 0 || gameState.mana < cls.cost;
    }
  }
}

function drawBattlefieldCanvas() {
  ctx.clearRect(0, 0, W, H);

  const skyGrad = ctx.createLinearGradient(0, 0, 0, LANE);
  skyGrad.addColorStop(0, '#78cbe0'); skyGrad.addColorStop(1, '#aae2ef');
  ctx.fillStyle = skyGrad; ctx.fillRect(0, 0, W, LANE);

  ctx.fillStyle = '#2eb019'; ctx.fillRect(0, LANE - 20, W, H - LANE + 20);
  ctx.fillStyle = '#c5a37e'; ctx.fillRect(0, LANE, W, 70);

  // Tower Draw
  ctx.fillStyle = '#1e3a8a'; ctx.fillRect(50, LANE - 50, 40, 50);
  ctx.fillStyle = '#ffffff'; ctx.font = 'bold 12px sans-serif'; ctx.textAlign = 'center';
  ctx.fillText(`${Math.ceil(gameState.playerHp)}/${gameState.playerMaxHp}`, 70, LANE - 58);

  ctx.fillStyle = '#881337'; ctx.fillRect(W - 90, LANE - 50, 40, 50);
  ctx.fillText(`${Math.ceil(gameState.enemyHp)}/${gameState.enemyMaxHp}`, W - 70, LANE - 58);

  gameState.units.forEach(u => {
    const drawX = u.x; const drawY = LANE + 35;
    ctx.font = '24px sans-serif'; ctx.textAlign = 'center';
    ctx.fillText(u.icon, drawX, drawY);

    ctx.fillStyle = '#000'; ctx.fillRect(drawX - 16, drawY - 30, 32, 4);
    ctx.fillStyle = u.side === 'player' ? '#22c55e' : '#ef4444';
    const ratio = u.useHitCount ? (u.hc / u.maxHc) : Math.max(0, u.hp / u.maxHp);
    ctx.fillRect(drawX - 16, drawY - 30, 32 * ratio, 4);
  });

  gameState.rockets.forEach(r => {
    ctx.font = '28px sans-serif'; ctx.fillText('🚀', r.x, r.y);
  });
}

function endBattle(isVictory) {
  gameState.isRunning = false;
  $('battleEndModal').classList.remove('hidden');

  if (isVictory) {
    $('endModalIcon').textContent = '🏆';
    $('endModalTitle').textContent = 'VICTORY!';$('endModalMsg').textContent = 'You defended the lane successfully!';

    const goldEarned = 400 + gameState.levelNum * 50;
    const rubyEarned = gameState.isHard ? 10 : 5;
    const bpEarned = gameState.isHard ? 20 : 10;
    const cloudEarned = gameState.isHard ? 60 : 30;

    S.gold += goldEarned; S.ruby += rubyEarned; S.bp += bpEarned; S.cloud += cloudEarned;

    const modeKey = gameState.isHard ? 'h' : 'n';
    if (S.prog[modeKey][gameState.mapIdx] < gameState.levelNum) S.prog[modeKey][gameState.mapIdx] = gameState.levelNum;

    saveState();
    $('endModalReward').textContent = `Rewards: +${goldEarned} Gold, +${rubyEarned} Ruby, +${bpEarned} B.P., +${cloudEarned} Cloud`;
    $('btnNextLevel').classList.remove('hidden');
  } else {
    $('endModalIcon').textContent = '💥';
    $('endModalTitle').textContent = 'DEFEAT!';$('endModalMsg').textContent = 'Your Penguin Tower was destroyed.';
    $('endModalReward').textContent = 'Upgrade your squad and try again!';$('btnNextLevel').classList.add('hidden');
  }
}

function showToast(msg) {
  const toast = $('toastText');
  toast.textContent = msg;
  setTimeout(() => { if (toast.textContent === msg) toast.textContent = ''; }, 2200);
}

function setupEventListeners() {
  document.querySelectorAll('[data-open]').forEach(btn => {
    btn.addEventListener('click', () => {
      const id = btn.dataset.open;
      if (id === 'modalShop') renderShop();
      if (id === 'modalUpgrade') renderUpgrades();
      if (id === 'modalTeam') renderTeamSetup();
      if (id === 'modalGacha') renderGachaPacks();
      if (id === 'modalGuardianTemple') updateCurrencyDisplays();
      $(id).classList.remove('hidden');
    });
  });

  document.querySelectorAll('[data-close]').forEach(btn => {
    btn.addEventListener('click', () => $(btn.dataset.close).classList.add('hidden'));
  });

  // Shop Tabs
  $('btnShopTabPackage').addEventListener('click', () => { activeShopTab = 'package'; renderShop(); });
  $('btnShopTabRuby').addEventListener('click', () => { activeShopTab = 'ruby'; renderShop(); });$('btnShopTabGold').addEventListener('click', () => { activeShopTab = 'gold'; renderShop(); });

  // Popover Context Menu
  $('popBtnUnequip').addEventListener('click', () => handlePopoverAction('unequip'));$('popBtnSell').addEventListener('click', () => handlePopoverAction('sell'));
  $('popBtnLevelUp').addEventListener('click', () => handlePopoverAction('levelup'));$('popBtnItem').addEventListener('click', () => handlePopoverAction('item'));
  $('popBtnLock').addEventListener('click', () => handlePopoverAction('lock'));$('popBtnClose').addEventListener('click', hideCharPopover);

  document.addEventListener('click', e => {
    if (!e.target.closest('#charContextMenu') && !e.target.closest('.parchment-card')) {
      hideCharPopover();
    }
  });

  // Gacha Tabs
  $('tabGachaHeroes').addEventListener('click', () => {
    currentGachaTab = 'heroes';
    $('tabGachaHeroes').className = 'px-3 py-1 rounded-lg text-xs font-black text-white shadow bg-rose-600';$('tabGachaItems').className = 'px-3 py-1 rounded-lg text-xs font-bold text-slate-400 hover:text-white';
    renderGachaPacks();
  });

  $('tabGachaItems').addEventListener('click', () => {
    currentGachaTab = 'items';
    $('tabGachaItems').className = 'px-3 py-1 rounded-lg text-xs font-black text-white shadow bg-purple-600';$('tabGachaHeroes').className = 'px-3 py-1 rounded-lg text-xs font-bold text-slate-400 hover:text-white';
    renderGachaPacks();
  });

  $('btnDrawAgain').addEventListener('click', () => {$('modalGachaResult').classList.add('hidden');
    if (lastDrawPacksContext) triggerDraw(lastDrawPacksContext);
  });

  $('btnItemToGacha').addEventListener('click', () => {
    $('modalHeroItem').classList.add('hidden');$('modalGacha').classList.remove('hidden');
    currentGachaTab = 'items';
    renderGachaPacks();
  });

  $('btnResultToTeam').addEventListener('click', () => {$('modalGachaResult').classList.add('hidden');
    $('modalGacha').classList.add('hidden');$('modalTeam').classList.remove('hidden');
    renderTeamSetup();
  });

  $('btnPersuadeAzureDragon').addEventListener('click', persuadeAzureDragon);

  $('btnBackToGuardianTemple').addEventListener('click', () => {
    $('modalAzureDragonTemple').classList.add('hidden');$('modalGuardianTemple').classList.remove('hidden');
    updateCurrencyDisplays();
  });

  $('btnBackToGuardianTemple2').addEventListener('click', () => {
    $('modalAzureDragonTemple').classList.add('hidden');$('modalGuardianTemple').classList.remove('hidden');
    updateCurrencyDisplays();
  });

  $('btnPlay').addEventListener('click', () => {
    if (!validateTeamAndStart()) return;
    $('lobby').classList.add('hidden');$('mapSelect').classList.remove('hidden');
    renderMapNodes();
  });

  $('btnBackToLobby').addEventListener('click', () => {
    $('mapSelect').classList.add('hidden');$('lobby').classList.remove('hidden');
    renderLobbyShowcase();
  });

  $('btnToggleHard').addEventListener('click', () => {
    S.isHardMode = !S.isHardMode;
    $('diffModeText').textContent = S.isHardMode ? 'Hard' : 'Normal';
    $('diffModeText').className = S.isHardMode ? 'text-rose-400 font-extrabold' : 'text-emerald-400 font-extrabold';
    renderMapNodes();
  });

  $('btnTeamToGacha').addEventListener('click', () => {
    $('modalTeam').classList.add('hidden');$('modalGacha').classList.remove('hidden');
    renderGachaPacks();
  });

  $('btnGachaToTeam').addEventListener('click', () => {
    $('modalGacha').classList.add('hidden');$('modalTeam').classList.remove('hidden');
    renderTeamSetup();
  });

  $('btnShowProb').addEventListener('click', () => {$('modalProb').classList.remove('hidden');
  });

  $('btnCloseGachaResult').addEventListener('click', () => {$('modalGachaResult').classList.add('hidden');
  });

  $('btnTeamToStart').addEventListener('click', () => {
    if (!validateTeamAndStart()) return;
    $('modalTeam').classList.add('hidden');
    $('lobby').classList.add('hidden');$('mapSelect').classList.remove('hidden');
    renderMapNodes();
  });

  $('btnShopToTeam').addEventListener('click', () => {
    $('modalShop').classList.add('hidden');$('modalTeam').classList.remove('hidden');
    renderTeamSetup();
  });

  $('btnUpgradeToPlay').addEventListener('click', () => {$('modalUpgrade').classList.add('hidden');
    $('lobby').classList.add('hidden');$('mapSelect').classList.remove('hidden');
    renderMapNodes();
  });

  $('btnRocket').addEventListener('click', fireRocket);$('btnManaUpgrade').addEventListener('click', upgradeManaLevel);

  $('btnBattlePause').addEventListener('click', () => {
    if (gameState) gameState.isRunning = false;
    $('gameStage').classList.add('hidden');$('lobby').classList.remove('hidden');
    renderLobbyShowcase();
  });

  $('btnRetry').addEventListener('click', () => startBattle(gameState.mapIdx, gameState.levelNum));
  $('btnNextLevel').addEventListener('click', () => startBattle(gameState.mapIdx, gameState.levelNum + 1));$('btnSelectMap').addEventListener('click', () => {
    if (gameState) gameState.isRunning = false;
    $('gameStage').classList.add('hidden');$('mapSelect').classList.remove('hidden');
    renderMapNodes();
  });
}

window.addEventListener('DOMContentLoaded', () => {
  loadState();
  setupEventListeners();
  renderLobbyShowcase();
});
</script>
</body>
</html>
