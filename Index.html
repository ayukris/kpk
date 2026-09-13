<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Balap Katak Temukan KPK - SD Negeri Srondol Kulon 01</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700&family=Plus+Jakarta+Sans:wght@500;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        fredoka: ['Fredoka', 'sans-serif'],
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    },
                    colors: {
                        parkGreen: '#4ade80',
                        parkSky: '#38bdf8',
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Fredoka', 'Plus Jakarta Sans', sans-serif;
            background: linear-gradient(180deg, #7dd3fc 0%, #bae6fd 40%, #86efac 70%, #4ade80 100%);
            min-height: 100vh;
            overflow-x: hidden;
            user-select: none;
        }

        @keyframes floatCloud {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100vw); }
        }

        @keyframes frogHop {
            0%, 100% { transform: translateY(0) scale(1); }
            50% { transform: translateY(-12px) scale(1.1); }
        }

        @keyframes pulseGlow {
            0%, 100% { box-shadow: 0 0 15px rgba(255, 255, 255, 0.6); }
            50% { box-shadow: 0 0 25px rgba(255, 255, 255, 0.9); }
        }

        .animated-cloud-1 { animation: floatCloud 35s linear infinite; }
        .animated-cloud-2 { animation: floatCloud 50s linear infinite 15s; }
        .frog-hop { animation: frogHop 0.5s ease-in-out; }
        .glow-card { animation: pulseGlow 2s infinite; }

        /* Custom scrollbars */
        ::-webkit-scrollbar { width: 6px; }
        ::-webkit-scrollbar-track { background: rgba(0,0,0,0.05); }
        ::-webkit-scrollbar-thumb { background: rgba(0,0,0,0.2); border-radius: 4px; }

        .falling-container {
            position: relative;
            overflow: hidden;
            background: linear-gradient(180deg, rgba(224, 242, 254, 0.85) 0%, rgba(187, 247, 208, 0.85) 100%);
            border-radius: 1rem;
        }
    </style>
</head>
<body class="flex flex-col min-h-screen text-slate-800">

    <!-- Clouds background layer -->
    <div class="fixed inset-0 pointer-events-none z-0 overflow-hidden">
        <div class="animated-cloud-1 absolute top-6 opacity-80">
            <svg width="140" height="60" viewBox="0 0 100 50" fill="white"><path d="M10 40 Q 20 20 35 25 Q 45 10 65 20 Q 80 15 90 35 Q 95 45 80 45 L 20 45 Q 5 45 10 40 Z"/></svg>
        </div>
        <div class="animated-cloud-2 absolute top-16 opacity-70">
            <svg width="180" height="80" viewBox="0 0 100 50" fill="white"><path d="M10 40 Q 20 20 35 25 Q 45 10 65 20 Q 80 15 90 35 Q 95 45 80 45 L 20 45 Q 5 45 10 40 Z"/></svg>
        </div>
    </div>

    <header class="relative z-10 bg-emerald-600/90 backdrop-blur-md text-white border-b-4 border-emerald-700 shadow-lg px-4 py-3">
        <div class="max-w-7xl mx-auto flex flex-wrap justify-between items-center gap-2">
            <div class="flex items-center space-x-3">
                <div class="bg-yellow-400 p-2 rounded-2xl shadow-md border-2 border-yellow-200">
                    <svg class="w-8 h-8 text-emerald-900" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/>
                    </svg>
                </div>
                <div>
                    <h1 class="text-xl md:text-2xl font-bold tracking-wide text-yellow-300 drop-shadow-sm">BALAP KATAK TEMUKAN KPK</h1>
                    <p class="text-xs md:text-sm font-medium text-emerald-100">Matematika Kelas 5 • SD Negeri Srondol Kulon 01</p>
                </div>
            </div>

            <!-- Top Controls -->
            <div class="flex items-center space-x-2">
                <button id="bgmToggleBtn" onclick="toggleMusic()" class="bg-emerald-500 hover:bg-emerald-400 text-white text-xs md:text-sm px-3 py-1.5 rounded-xl font-bold border-2 border-emerald-300 shadow transition flex items-center gap-1">
                    <span id="bgmIcon">🎵</span> Musik: ON
                </button>
                <button onclick="openInstructions()" class="bg-amber-500 hover:bg-amber-400 text-white text-xs md:text-sm px-3 py-1.5 rounded-xl font-bold border-2 border-amber-300 shadow transition">
                    ❓ Bantuan
                </button>
                <button onclick="resetGameModal()" class="bg-rose-500 hover:bg-rose-400 text-white text-xs md:text-sm px-3 py-1.5 rounded-xl font-bold border-2 border-rose-300 shadow transition">
                    🔄 Reset
                </button>
            </div>
        </div>
    </header>

    <main class="relative z-10 flex-1 max-w-7xl w-full mx-auto p-3 md:p-5 flex flex-col justify-center">

        <!-- Setup Screen -->
        <div id="setupScreen" class="bg-white/90 backdrop-blur-md rounded-3xl p-6 md:p-8 shadow-2xl border-4 border-emerald-400 max-w-2xl mx-auto w-full text-center">
            <div class="w-20 h-20 mx-auto mb-4 bg-emerald-100 rounded-full flex items-center justify-center border-4 border-emerald-400 shadow-inner">
                <span class="text-5xl">🐸</span>
            </div>
            <h2 class="text-2xl md:text-3xl font-extrabold text-emerald-800 mb-2">Selamat Datang di Arena Balap!</h2>
            <p class="text-slate-600 mb-6 text-sm md:text-base">Ayo berlomba melompati teratai dengan menjawab soal kelipatan & KPK secara cepat dan tepat!</p>

            <div class="mb-6 bg-emerald-50 p-4 rounded-2xl border-2 border-emerald-200">
                <label class="block font-bold text-emerald-900 mb-3 text-sm md:text-base">Pilih Mode Pemain:</label>
                <div class="grid grid-cols-2 md:grid-cols-4 gap-2">
                    <button onclick="setPlayerCount(1)" id="btnP1" class="mode-btn bg-emerald-600 text-white font-bold py-2.5 px-3 rounded-xl border-b-4 border-emerald-800 hover:brightness-110 transition text-sm">1 Pemain<br><span class="text-xs font-normal opacity-90">(3 Katak Bot)</span></button>
                    <button onclick="setPlayerCount(2)" id="btnP2" class="mode-btn bg-slate-200 text-slate-700 font-bold py-2.5 px-3 rounded-xl border-b-4 border-slate-400 hover:brightness-105 transition text-sm">2 Pemain<br><span class="text-xs font-normal opacity-75">(2 Katak Bot)</span></button>
                    <button onclick="setPlayerCount(3)" id="btnP3" class="mode-btn bg-slate-200 text-slate-700 font-bold py-2.5 px-3 rounded-xl border-b-4 border-slate-400 hover:brightness-105 transition text-sm">3 Pemain<br><span class="text-xs font-normal opacity-75">(1 Katak Bot)</span></button>
                    <button onclick="setPlayerCount(4)" id="btnP4" class="mode-btn bg-slate-200 text-slate-700 font-bold py-2.5 px-3 rounded-xl border-b-4 border-slate-400 hover:brightness-105 transition text-sm">4 Pemain<br><span class="text-xs font-normal opacity-75">(Semua Manusia)</span></button>
                </div>
            </div>

            <div class="mb-6 bg-emerald-50/90 p-4 rounded-2xl border-2 border-emerald-300 shadow-sm text-left">
                <label class="block font-bold text-emerald-900 mb-3 text-sm md:text-base text-center">✏️ Masukkan Nama Pemain:</label>
                <div id="playerNameInputs" class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                    <!-- Populated by JavaScript -->
                </div>
            </div>

            <button onclick="startGame()" class="w-full bg-yellow-400 hover:bg-yellow-300 text-emerald-950 font-black text-xl py-4 rounded-2xl border-b-4 border-yellow-600 shadow-xl transition transform hover:scale-[1.02] active:scale-95 flex items-center justify-center gap-2">
                🚀 MULAI PERMAINAN
            </button>
        </div>

        <!-- Main Game Screen (Hidden initially) -->
        <div id="gameScreen" class="hidden flex-1 flex flex-col space-y-4">

            <!-- 4 Players Grid Container -->
            <div id="lanesContainer" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-3 flex-1">
                <!-- Javascript will insert 4 Player Columns dynamically -->
            </div>
        </div>
    </main>

    <!-- Victory Modal -->
    <div id="victoryModal" class="fixed inset-0 bg-slate-900/80 backdrop-blur-md z-50 hidden flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-md w-full p-6 text-center shadow-2xl border-4 border-yellow-400 transform transition-all scale-100 relative overflow-hidden">
            <div class="absolute -top-10 -left-10 w-28 h-28 bg-yellow-300/30 rounded-full blur-xl"></div>
            <div class="text-6xl mb-3 animate-bounce">🏆</div>
            <h2 class="text-3xl font-black text-emerald-800 mb-1">JUARA BALAPAN!</h2>
            <p id="winnerText" class="text-lg font-bold text-amber-600 mb-4">Katak Hijau Memenangkan Balapan!</p>
            
            <div id="leaderboardList" class="bg-emerald-50 rounded-2xl p-4 mb-5 border-2 border-emerald-200 space-y-2 text-left">
                <!-- Leaderboard entries -->
            </div>

            <button onclick="restartGame()" class="w-full bg-emerald-500 hover:bg-emerald-400 text-white font-black text-lg py-3 rounded-xl border-b-4 border-emerald-700 shadow-lg transition">
                🎮 Main Lagi
            </button>
        </div>
    </div>

    <!-- Instruction Modal -->
    <div id="instructionModal" class="fixed inset-0 bg-slate-900/70 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-lg w-full p-6 text-slate-800 shadow-2xl border-4 border-emerald-400">
            <h3 class="text-2xl font-black text-emerald-800 mb-3 flex items-center gap-2">
                <span>📖</span> Cara Bermain
            </h3>
            <div class="space-y-3 text-sm text-slate-600 leading-relaxed mb-6">
                <p class="bg-sky-50 p-2.5 rounded-xl border border-sky-200"><strong class="text-sky-800">🚀 Babak 1 (Soal 1 - 5):</strong> Permainan Antariksa Cepat! Pilih angka yang merupakan kelipatan dari bilangan yang ditentukan. Gelembung angka bergerak turun. Klik secepat mungkin!</p>
                <p class="bg-emerald-50 p-2.5 rounded-xl border border-emerald-200"><strong class="text-emerald-800">🧠 Babak 2 (Soal 6 - 10):</strong> Pilihan Ganda KPK! Jawab soal tentang kelipatan ke-n, kelipatan persekutuan, dan KPK.</p>
                <p class="bg-amber-50 p-2.5 rounded-xl border border-amber-200"><strong class="text-amber-800">🏁 Pemenang:</strong> Setiap jawaban benar membuat katakmu melompat mendekati garis finish. Katak yang menyentuh garis finish terlebih dahulu dialah pemenangnya!</p>
            </div>
            <button onclick="closeInstructions()" class="w-full bg-slate-700 hover:bg-slate-600 text-white font-bold py-2.5 rounded-xl transition">
                Mengerti!
            </button>
        </div>
    </div>

    <script>
        class SoundEngine {
            constructor() {
                this.ctx = null;
                this.musicPlaying = false;
                this.musicInterval = null;
                this.isMuted = false;
            }

            init() {
                if (!this.ctx) {
                    const AudioContext = window.AudioContext || window.webkitAudioContext;
                    this.ctx = new AudioContext();
                }
                if (this.ctx.state === 'suspended') {
                    this.ctx.resume();
                }
            }

            playTone(freq, type, duration, gainVal = 0.1) {
                if (this.isMuted) return;
                this.init();
                try {
                    const osc = this.ctx.createOscillator();
                    const gain = this.ctx.createGain();
                    osc.type = type;
                    osc.frequency.setValueAtTime(freq, this.ctx.currentTime);
                    gain.gain.setValueAtTime(gainVal, this.ctx.currentTime);
                    gain.gain.exponentialRampToValueAtTime(0.0001, this.ctx.currentTime + duration);
                    osc.connect(gain);
                    gain.connect(this.ctx.destination);
                    osc.start();
                    osc.stop(this.ctx.currentTime + duration);
                } catch(e) {}
            }

            playJump() {
                if (this.isMuted) return;
                this.init();
                try {
                    const osc = this.ctx.createOscillator();
                    const gain = this.ctx.createGain();
                    osc.type = 'sine';
                    osc.frequency.setValueAtTime(150, this.ctx.currentTime);
                    osc.frequency.exponentialRampToValueAtTime(400, this.ctx.currentTime + 0.15);
                    gain.gain.setValueAtTime(0.15, this.ctx.currentTime);
                    gain.gain.linearRampToValueAtTime(0.01, this.ctx.currentTime + 0.15);
                    osc.connect(gain);
                    gain.connect(this.ctx.destination);
                    osc.start();
                    osc.stop(this.ctx.currentTime + 0.15);
                } catch(e){}
            }

            playCorrect() {
                this.playTone(523.25, 'triangle', 0.1, 0.15); // C5
                setTimeout(() => this.playTone(659.25, 'triangle', 0.1, 0.15), 80); // E5
                setTimeout(() => this.playTone(783.99, 'triangle', 0.2, 0.15), 160); // G5
            }

            playWrong() {
                this.playTone(180, 'sawtooth', 0.25, 0.15);
            }

            playWin() {
                const notes = [440, 554.37, 659.25, 880];
                notes.forEach((n, i) => {
                    setTimeout(() => this.playTone(n, 'triangle', 0.3, 0.2), i * 120);
                });
            }

            startBGM() {
                if (this.musicPlaying || this.isMuted) return;
                this.musicPlaying = true;
                const melody = [261.63, 329.63, 392.00, 329.63, 261.63, 392.00, 440.00, 392.00];
                let idx = 0;
                this.musicInterval = setInterval(() => {
                    if (!this.musicPlaying || this.isMuted) return;
                    this.playTone(melody[idx], 'sine', 0.2, 0.03);
                    idx = (idx + 1) % melody.length;
                }, 400);
            }

            stopBGM() {
                this.musicPlaying = false;
                if (this.musicInterval) clearInterval(this.musicInterval);
            }
        }

        const sounds = new SoundEngine();

        function toggleMusic() {
            sounds.isMuted = !sounds.isMuted;
            const btn = document.getElementById('bgmToggleBtn');
            if (sounds.isMuted) {
                sounds.stopBGM();
                btn.innerHTML = '🔇 Musik: OFF';
                btn.classList.replace('bg-emerald-500', 'bg-slate-500');
            } else {
                sounds.startBGM();
                btn.innerHTML = '🎵 Musik: ON';
                btn.classList.replace('bg-slate-500', 'bg-emerald-500');
            }
        }

        const FROGS = [
            { id: 1, name: 'Katak Hijau', color: '#22c55e', bgLight: '#dcfce7', border: '#16a34a', accent: 'bg-emerald-500' },
            { id: 2, name: 'Katak Biru', color: '#0ea5e9', bgLight: '#e0f2fe', border: '#0284c7', accent: 'bg-sky-500' },
            { id: 3, name: 'Katak Kuning', color: '#eab308', bgLight: '#fef9c3', border: '#ca8a04', accent: 'bg-yellow-500' },
            { id: 4, name: 'Katak Merah', color: '#f43f5e', bgLight: '#ffe4e6', border: '#e11d48', accent: 'bg-rose-500' }
        ];

        function getFrogSVG(colorHex) {
            return `
            <svg viewBox="0 0 100 90" class="w-12 h-12 md:w-14 md:h-14 drop-shadow-md">
                <!-- Legs -->
                <ellipse cx="20" cy="70" rx="16" ry="10" fill="${colorHex}" transform="rotate(-20 20 70)"/>
                <ellipse cx="80" cy="70" rx="16" ry="10" fill="${colorHex}" transform="rotate(20 80 70)"/>
                <!-- Body -->
                <ellipse cx="50" cy="55" rx="35" ry="28" fill="${colorHex}"/>
                <ellipse cx="50" cy="58" rx="22" ry="18" fill="#ffffff" opacity="0.4"/>
                <!-- Eyes Back -->
                <circle cx="32" cy="26" r="14" fill="${colorHex}"/>
                <circle cx="68" cy="26" r="14" fill="${colorHex}"/>
                <!-- Eyes White -->
                <circle cx="32" cy="24" r="9" fill="#ffffff"/>
                <circle cx="68" cy="24" r="9" fill="#ffffff"/>
                <!-- Pupils -->
                <circle cx="34" cy="24" r="5" fill="#000000"/>
                <circle cx="66" cy="24" r="5" fill="#000000"/>
                <!-- Pupil shine -->
                <circle cx="36" cy="22" r="2" fill="#ffffff"/>
                <circle cx="68" cy="22" r="2" fill="#ffffff"/>
                <!-- Mouth -->
                <path d="M 38 58 Q 50 68 62 58" stroke="#000" stroke-width="3" stroke-linecap="round" fill="none"/>
                <!-- Cheek blush -->
                <circle cx="28" cy="52" r="4" fill="#f43f5e" opacity="0.4"/>
                <circle cx="72" cy="52" r="4" fill="#f43f5e" opacity="0.4"/>
            </svg>`;
        }

        let humanPlayersCount = 1;
        let playersState = [];
        let animFrameReq = null;
        let isGameOver = false;

        function renderNameInputs() {
            const container = document.getElementById('playerNameInputs');
            if (!container) return;
            container.innerHTML = '';

            FROGS.forEach((frog, idx) => {
                const isHuman = idx < humanPlayersCount;
                const defaultName = isHuman ? `Pemain ${idx + 1}` : `Bot Katak ${idx + 1}`;
                
                const card = document.createElement('div');
                card.className = `flex items-center space-x-2.5 p-2.5 rounded-xl border-2 transition-all ${isHuman ? 'bg-white border-emerald-400 shadow-sm' : 'bg-slate-100 border-slate-300 opacity-75'}`;
                card.innerHTML = `
                    <div class="w-8 h-8 rounded-full flex items-center justify-center font-black text-white text-xs ${frog.accent} shrink-0 shadow">
                        ${frog.id}
                    </div>
                    <div class="flex-1 min-w-0">
                        <label class="block text-[10px] font-extrabold ${isHuman ? 'text-emerald-700' : 'text-slate-500'} uppercase tracking-wider">
                            ${isHuman ? '👤 Pemain ' + (idx + 1) : '🤖 Komputer'}
                        </label>
                        <input type="text" id="nameInput_${idx}" value="${defaultName}" placeholder="Ketik nama..." maxLength="15"
                            class="w-full text-xs md:text-sm font-bold bg-transparent border-b-2 ${isHuman ? 'border-emerald-300 focus:border-emerald-600' : 'border-slate-300'} focus:outline-none py-0.5 text-slate-800 placeholder-slate-400"
                            ${!isHuman ? 'readonly' : ''} />
                    </div>
                `;
                container.appendChild(card);
            });
        }

        function setPlayerCount(count) {
            humanPlayersCount = count;
            for (let i = 1; i <= 4; i++) {
                const btn = document.getElementById(`btnP${i}`);
                if (i === count) {
                    btn.className = "mode-btn bg-emerald-600 text-white font-bold py-2.5 px-3 rounded-xl border-b-4 border-emerald-800 shadow transition text-sm scale-105";
                } else {
                    btn.className = "mode-btn bg-slate-200 text-slate-700 font-bold py-2.5 px-3 rounded-xl border-b-4 border-slate-400 hover:brightness-105 transition text-sm";
                }
            }
            renderNameInputs();
        }

        window.addEventListener('DOMContentLoaded', () => {
            renderNameInputs();
        });

        function generatePlayerQuestions() {
            const questions = [];

            // Stage 1 (Q1 - Q5): Kelipatan Cepat (Falling Bubbles)
            const stage1Configs = [
                { num: 2, mults: [4, 6, 8, 10, 12, 14, 16], nonMults: [3, 5, 7, 9, 11, 13, 15] },
                { num: 3, mults: [6, 9, 12, 15, 18, 21, 24], nonMults: [4, 7, 10, 11, 13, 14, 16] },
                { num: 4, mults: [8, 12, 16, 20, 24, 28, 32], nonMults: [5, 9, 11, 13, 15, 17, 19] },
                { num: 5, mults: [10, 15, 20, 25, 30, 35, 40], nonMults: [7, 11, 14, 18, 22, 26, 29] },
                { num: 6, mults: [12, 18, 24, 30, 36, 42, 48], nonMults: [8, 10, 14, 16, 20, 22, 26] }
            ];

            stage1Configs.forEach((cfg, idx) => {
                const correctMult = cfg.mults[Math.floor(Math.random() * cfg.mults.length)];
                const wrongShuffled = [...cfg.nonMults].sort(() => Math.random() - 0.5).slice(0, 3);
                const options = [correctMult, ...wrongShuffled].sort(() => Math.random() - 0.5);

                questions.push({
                    stage: 1,
                    qNum: idx + 1,
                    prompt: `Pilih angka yang merupakan Kelipatan dari ${cfg.num}!`,
                    baseNum: cfg.num,
                    correct: correctMult,
                    options: options
                });
            });

            // Stage 2 (Q6 - Q10): Pilihan Ganda
            const q6Base = [3, 4, 5, 6, 7, 8, 9][Math.floor(Math.random() * 7)];
            const q6N = [4, 5, 6, 7, 8][Math.floor(Math.random() * 5)];
            const q6Ans = q6Base * q6N;
            const q6Wrong = [q6Ans - q6Base, q6Ans + q6Base, q6Ans + 2, q6Ans - 2].filter(x => x > 0 && x !== q6Ans);
            questions.push({
                stage: 2,
                qNum: 6,
                question: `Kelipatan ke-${q6N} dari bilangan ${q6Base} adalah ...`,
                options: [q6Ans, ...q6Wrong.slice(0, 3)].sort(() => Math.random() - 0.5),
                correct: q6Ans
            });

            // Q7: Kelipatan persekutuan sederhana
            const pair1 = [
                { a: 2, b: 3, ans: "6 dan 12" },
                { a: 3, b: 4, ans: "12 dan 24" },
                { a: 2, b: 5, ans: "10 dan 20" },
                { a: 4, b: 6, ans: "12 dan 24" }
            ][Math.floor(Math.random() * 4)];

            questions.push({
                stage: 2,
                qNum: 7,
                question: `Dua kelipatan persekutuan pertama dari ${pair1.a} dan ${pair1.b} adalah ...`,
                options: [pair1.ans, `${pair1.a*2} dan ${pair1.b*2}`, `${pair1.a*3} dan ${pair1.b*3}`, `${pair1.a+pair1.b} dan ${pair1.a*pair1.b+1}`].sort(() => Math.random() - 0.5),
                correct: pair1.ans
            });

            // Q8: Kelipatan persekutuan dalam rentang
            const pair2 = [
                { a: 3, b: 5, limit: 35, ans: "15 dan 30" },
                { a: 2, b: 4, limit: 15, ans: "4, 8, dan 12" },
                { a: 4, b: 8, limit: 25, ans: "8, 16, dan 24" },
                { a: 5, b: 10, limit: 35, ans: "10, 20, dan 30" }
            ][Math.floor(Math.random() * 4)];

            questions.push({
                stage: 2,
                qNum: 8,
                question: `Kelipatan persekutuan dari ${pair2.a} dan ${pair2.b} yang kurang dari ${pair2.limit} adalah ...`,
                options: [pair2.ans, `${pair2.a}, ${pair2.b}`, `${pair2.a*2}, ${pair2.b*2}`, `${pair2.limit-5}, ${pair2.limit-1}`].sort(() => Math.random() - 0.5),
                correct: pair2.ans
            });

            // Q9: KPK dari 2 Bilangan
            const kpkPairs = [
                { a: 4, b: 6, ans: 12 },
                { a: 6, b: 8, ans: 24 },
                { a: 5, b: 7, ans: 35 },
                { a: 8, b: 12, ans: 24 },
                { a: 9, b: 12, ans: 36 }
            ][Math.floor(Math.random() * 5)];

            questions.push({
                stage: 2,
                qNum: 9,
                question: `Kelipatan Persekutuan Terkecil (KPK) dari ${kpkPairs.a} dan ${kpkPairs.b} adalah ...`,
                options: [kpkPairs.ans, kpkPairs.a * kpkPairs.b, kpkPairs.ans * 2, kpkPairs.ans / 2 < 1 ? 2 : Math.floor(kpkPairs.ans / 2)].sort(() => Math.random() - 0.5),
                correct: kpkPairs.ans
            });

            // Q10: KPK dari 3 Bilangan atau Soal Cerita
            const kpkHard = [
                { q: "KPK dari 3, 4, dan 6 adalah ...", ans: 12, opt: [12, 24, 18, 36] },
                { q: "KPK dari 4, 6, dan 8 adalah ...", ans: 24, opt: [24, 48, 16, 32] },
                { q: "Lampu A menyala setiap 4 detik, Lampu B setiap 6 detik. Kedua lampu menyala bersama setiap ... detik.", ans: 12, opt: [12, 24, 10, 16] },
                { q: "Budi berenang setiap 6 hari sekali, Ani setiap 8 hari. Mereka akan berenang bersama lagi setelah ... hari.", ans: 24, opt: [24, 48, 14, 30] }
            ][Math.floor(Math.random() * 4)];

            questions.push({
                stage: 2,
                qNum: 10,
                question: kpkHard.q,
                options: kpkHard.opt.sort(() => Math.random() - 0.5),
                correct: kpkHard.ans
            });

            return questions;
        }

        function startGame() {
            sounds.init();
            sounds.startBGM();

            document.getElementById('setupScreen').classList.add('hidden');
            document.getElementById('gameScreen').classList.remove('hidden');

            isGameOver = false;

            playersState = FROGS.map((frog, idx) => {
                const isHuman = idx < humanPlayersCount;
                const inputEl = document.getElementById(`nameInput_${idx}`);
                let name = inputEl ? inputEl.value.trim() : '';
                if (!name) name = isHuman ? `Pemain ${idx + 1}` : `Bot Katak ${idx + 1}`;

                return {
                    ...frog,
                    isHuman: isHuman,
                    labelName: name,
                    currentQuestionIdx: 0,
                    score: 0,
                    progress: 0, // 0 to 10 steps
                    questions: generatePlayerQuestions(),
                    bubbles: [], // for falling stage
                    finishedTime: null,
                    botTimer: null
                };
            });

            renderLanes();

            // Start animation loop for falling bubbles and bot automation
            if (animFrameReq) cancelAnimationFrame(animFrameReq);
            lastTime = performance.now();
            animFrameReq = requestAnimationFrame(gameLoop);

            // Setup Bots
            playersState.forEach((p, idx) => {
                if (!p.isHuman) {
                    scheduleBotMove(idx);
                }
            });
        }

        function renderLanes() {
            const container = document.getElementById('lanesContainer');
            container.innerHTML = '';

            playersState.forEach((player, pIdx) => {
                const laneHtml = `
                <div id="lane-${pIdx}" class="bg-white/95 rounded-2xl p-3 shadow-xl border-2 flex flex-col justify-between relative overflow-hidden" style="border-color: ${player.border}">
                    <!-- Header Info Player -->
                    <div class="flex items-center justify-between p-2 rounded-xl mb-2" style="background-color: ${player.bgLight}">
                        <div class="flex items-center space-x-2">
                            <div class="w-8 h-8 rounded-full flex items-center justify-center font-black text-white ${player.accent}">
                                ${player.id}
                            </div>
                            <div>
                                <h3 class="font-extrabold text-xs md:text-sm text-slate-800 leading-tight">${player.labelName}</h3>
                                <span class="text-[10px] font-bold uppercase tracking-wider ${player.isHuman ? 'text-emerald-600' : 'text-slate-500'}">
                                    ${player.isHuman ? '👤 Pemain' : '🤖 Komputer'}
                                </span>
                            </div>
                        </div>
                        <div class="text-right">
                            <span id="p-${pIdx}-step" class="text-xs font-black text-slate-700 bg-white px-2 py-0.5 rounded-md shadow-sm">
                                Soal ${player.currentQuestionIdx + 1}/10
                            </span>
                        </div>
                    </div>

                    <!-- Mini Track Line -->
                    <div class="relative bg-emerald-100 h-14 rounded-xl mb-2 border border-emerald-300 p-1 flex items-center overflow-hidden">
                        <!-- Finish line indicator -->
                        <div class="absolute right-2 top-0 bottom-0 flex flex-col justify-center items-center z-0">
                            <span class="text-xs">🏁</span>
                            <div class="h-full w-1 border-r-2 border-dashed border-red-500"></div>
                        </div>
                        
                        <!-- Track finish water lily -->
                        <div class="w-full relative h-full flex items-center">
                            <!-- Frog Avatar moving along track -->
                            <div id="p-${pIdx}-frog" class="absolute transition-all duration-300 ease-out z-10 flex flex-col items-center" style="left: 0%;">
                                ${getFrogSVG(player.color)}
                            </div>
                        </div>
                    </div>

                    <!-- Question Container Area -->
                    <div id="p-${pIdx}-qarea" class="flex-1 flex flex-col">
                        <!-- Dynamic Question HTML will be rendered here -->
                    </div>
                </div>`;
                container.innerHTML += laneHtml;
            });

            // Initial render of questions
            playersState.forEach((_, idx) => updatePlayerQuestionUI(idx));
        }

        function updatePlayerQuestionUI(pIdx) {
            const player = playersState[pIdx];
            const qArea = document.getElementById(`p-${pIdx}-qarea`);
            const stepBadge = document.getElementById(`p-${pIdx}-step`);

            if (player.currentQuestionIdx >= 10) {
                stepBadge.innerText = "SELESAI!";
                qArea.innerHTML = `
                <div class="flex-1 flex flex-col items-center justify-center p-4 text-center bg-emerald-50 rounded-xl border border-emerald-200">
                    <span class="text-4xl mb-2">🎉</span>
                    <h4 class="font-black text-emerald-800 text-base">Garis Finish Terhubung!</h4>
                    <p class="text-xs text-slate-500 mt-1">Menunggu pemain lain selesai...</p>
                </div>`;
                return;
            }

            stepBadge.innerText = `Soal ${player.currentQuestionIdx + 1}/10`;
            const qData = player.questions[player.currentQuestionIdx];

            if (qData.stage === 1) {
                // Stage 1: Falling bubbles game
                // Initialize bubbles position
                player.bubbles = qData.options.map((val, i) => ({
                    value: val,
                    x: 15 + (i * 22), // percent horizontal spacing
                    y: -10 - (Math.random() * 20), // staggered start height
                    speed: 0.15 + (Math.random() * 0.08) // moderate falling speed
                }));

                qArea.innerHTML = `
                <div class="bg-sky-50 p-2 rounded-xl text-center mb-2 border border-sky-200">
                    <span class="text-[10px] font-bold text-sky-600 uppercase tracking-wider block">Babak 1: Antariksa Cepat</span>
                    <h4 class="font-black text-sky-950 text-xs md:text-sm">${qData.prompt}</h4>
                </div>
                <div id="p-${pIdx}-falling-box" class="falling-container flex-1 min-h-[190px] relative border-2 border-sky-200">
                    <!-- Bubbles will be positioned via game loop -->
                </div>`;
            } else {
                // Stage 2: Multiple Choice
                qArea.innerHTML = `
                <div class="bg-amber-50 p-2.5 rounded-xl text-center mb-2 border border-amber-200">
                    <span class="text-[10px] font-bold text-amber-600 uppercase tracking-wider block">Babak 2: Pilihan Ganda</span>
                    <h4 class="font-black text-amber-950 text-xs md:text-sm leading-snug">${qData.question}</h4>
                </div>
                <div class="grid grid-cols-2 gap-2 mt-auto">
                    ${qData.options.map(opt => `
                        <button onclick="handleAnswer(${pIdx}, '${opt}')" 
                                class="bg-white hover:bg-emerald-50 text-slate-800 font-extrabold py-2.5 px-2 text-xs md:text-sm rounded-xl border-2 border-slate-200 hover:border-emerald-400 shadow-sm transition active:scale-95 text-center">
                            ${opt}
                        </button>
                    `).join('')}
                </div>`;
            }
        }

        let lastTime = 0;
        function gameLoop(time) {
            const dt = time - lastTime;
            lastTime = time;

            if (!isGameOver) {
                playersState.forEach((player, pIdx) => {
                    if (player.currentQuestionIdx < 5) { // Stage 1 active
                        const qData = player.questions[player.currentQuestionIdx];
                        if (qData && qData.stage === 1) {
                            const container = document.getElementById(`p-${pIdx}-falling-box`);
                            if (container) {
                                let html = '';
                                player.bubbles.forEach((b, bIdx) => {
                                    b.y += b.speed * (dt / 16);
                                    if (b.y > 105) { // Loop back up if missed
                                        b.y = -15;
                                    }

                                    html += `
                                    <button onclick="handleAnswer(${pIdx}, ${b.value})" 
                                            style="left: ${b.x}%; top: ${b.y}%;"
                                            class="absolute transform -translate-x-1/2 w-11 h-11 md:w-12 md:h-12 bg-white/90 hover:bg-yellow-300 text-emerald-900 font-extrabold text-xs md:text-sm rounded-full border-2 border-emerald-400 shadow-md flex items-center justify-center active:scale-90 transition-transform">
                                        ${b.value}
                                    </button>`;
                                });
                                container.innerHTML = html;
                            }
                        }
                    }
                });
            }

            animFrameReq = requestAnimationFrame(gameLoop);
        }

        function handleAnswer(pIdx, selectedVal) {
            if (isGameOver) return;
            const player = playersState[pIdx];
            if (player.currentQuestionIdx >= 10) return;

            const qData = player.questions[player.currentQuestionIdx];
            let isCorrect = false;

            if (qData.stage === 1) {
                isCorrect = (Number(selectedVal) === qData.correct);
            } else {
                isCorrect = (String(selectedVal) === String(qData.correct));
            }

            const frogElem = document.getElementById(`p-${pIdx}-frog`);

            if (isCorrect) {
                sounds.playCorrect();
                sounds.playJump();
                player.score += 10;
                player.progress += 1; // 1 step out of 10

                // Frog animations
                if (frogElem) {
                    frogElem.classList.add('frog-hop');
                    setTimeout(() => frogElem.classList.remove('frog-hop'), 500);
                }
            } else {
                sounds.playWrong();
                // Bebek / Katak diam di tempat on wrong answer
            }

            // Update frog visual position on track (max 82% to fit inside container)
            const targetLeft = Math.min((player.progress / 10) * 82, 82);
            if (frogElem) {
                frogElem.style.left = `${targetLeft}%`;
            }

            // Advance immediately to next question
            player.currentQuestionIdx += 1;

            if (player.currentQuestionIdx >= 10) {
                player.finishedTime = Date.now();
                checkGameEnd();
            } else {
                updatePlayerQuestionUI(pIdx);
            }
        }

        function scheduleBotMove(pIdx) {
            if (isGameOver) return;
            const player = playersState[pIdx];
            if (player.currentQuestionIdx >= 10) return;

            // Random delay between 2 to 4 seconds for bot answer
            const delay = Math.floor(Math.random() * 2000) + 1800;
            player.botTimer = setTimeout(() => {
                if (isGameOver || player.currentQuestionIdx >= 10) return;
                
                const qData = player.questions[player.currentQuestionIdx];
                // Bot accuracy ~75%
                const isCorrect = Math.random() < 0.75;
                let choice = qData.correct;

                if (!isCorrect) {
                    const wrongOpts = qData.options.filter(o => o !== qData.correct);
                    choice = wrongOpts[Math.floor(Math.random() * wrongOpts.length)];
                }

                handleAnswer(pIdx, choice);

                if (player.currentQuestionIdx < 10) {
                    scheduleBotMove(pIdx);
                }
            }, delay);
        }

        function checkGameEnd() {
            const allFinished = playersState.every(p => p.currentQuestionIdx >= 10);
            const someoneFinished = playersState.some(p => p.progress >= 10);

            if (someoneFinished || allFinished) {
                // Determine Winner
                isGameOver = true;
                sounds.playWin();

                // Sort players by progress (desc), then score (desc), then finished time (asc)
                const sorted = [...playersState].sort((a, b) => {
                    if (b.progress !== a.progress) return b.progress - a.progress;
                    if (b.score !== a.score) return b.score - a.score;
                    return (a.finishedTime || Infinity) - (b.finishedTime || Infinity);
                });

                const winner = sorted[0];

                document.getElementById('winnerText').innerText = `${winner.labelName} (${winner.name}) Memenangkan Balapan! 🎉`;

                const listContainer = document.getElementById('leaderboardList');
                listContainer.innerHTML = sorted.map((p, idx) => `
                    <div class="flex items-center justify-between p-2 rounded-xl ${idx === 0 ? 'bg-yellow-200 border-2 border-yellow-400 font-extrabold' : 'bg-white border border-slate-200 text-xs'}">
                        <div class="flex items-center space-x-2">
                            <span class="text-sm font-black w-5">${idx === 0 ? '🥇' : idx === 1 ? '🥈' : idx === 2 ? '🥉' : '4.'}</span>
                            <span style="color: ${p.color}" class="font-bold">${p.labelName}</span>
                        </div>
                        <div class="text-right">
                            <span class="text-xs font-bold text-slate-700">${p.progress}/10 Soal Benar</span>
                        </div>
                    </div>
                `).join('');

                document.getElementById('victoryModal').classList.remove('hidden');
            }
        }

        function resetGameModal() {
            if (animFrameReq) cancelAnimationFrame(animFrameReq);
            playersState.forEach(p => { if (p.botTimer) clearTimeout(p.botTimer); });
            document.getElementById('gameScreen').classList.add('hidden');
            document.getElementById('victoryModal').classList.add('hidden');
            document.getElementById('setupScreen').classList.remove('hidden');
        }

        function restartGame() {
            document.getElementById('victoryModal').classList.add('hidden');
            startGame();
        }

        function openInstructions() {
            document.getElementById('instructionModal').classList.remove('hidden');
        }

        function closeInstructions() {
            document.getElementById('instructionModal').classList.add('hidden');
        }
    </script>
</body>
</html>
