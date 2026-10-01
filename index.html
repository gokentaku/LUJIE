<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>iPod - 鲁姐生日倒计时</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=VT323&family=Noto+Sans+SC:wght@500;700;900&display=swap" rel="stylesheet">
    
    <style>
        body {
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: radial-gradient(circle at center, #4b5563 0%, #1f2937 100%);
            font-family: 'Noto Sans SC', sans-serif;
            overflow: hidden;
            transition: background 0.1s;
        }

        .ipod-casing {
            width: 360px;
            height: 580px;
            background: linear-gradient(135deg, #ffffff 0%, #f0f0f0 40%, #e6e6e6 100%);
            border-radius: 36px;
            padding: 28px 24px;
            position: relative;
            box-sizing: border-box;
            box-shadow: 
                0 30px 60px rgba(0,0,0,0.5),
                inset 3px 3px 6px rgba(255,255,255,0.9),
                inset -4px -4px 12px rgba(150,150,150,0.3),
                0 0 0 1px #d1d5db, 
                0 0 0 3px #9ca3af;
            display: flex;
            flex-direction: column;
            align-items: center;
            z-index: 10; /* Ensure iPod is above some effects */
        }

        .ipod-casing::before {
            content: '';
            position: absolute;
            top: -2px;
            left: 50px;
            width: 35px;
            height: 6px;
            background: #6b7280;
            border-radius: 4px 4px 0 0;
            box-shadow: inset 0 2px 3px rgba(0,0,0,0.5);
        }

        .screen-glass {
            width: 100%;
            height: 250px;
            background: #0a0a0a;
            border-radius: 12px;
            padding: 10px;
            box-sizing: border-box;
            position: relative;
            overflow: hidden;
            box-shadow: 
                inset 0 3px 8px rgba(0,0,0,0.8),
                0 2px 4px rgba(255,255,255,0.8);
        }

        .screen-glass::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(
                to bottom right,
                rgba(255,255,255,0.15) 0%,
                rgba(255,255,255,0.05) 35%,
                rgba(255,255,255,0) 50%
            );
            pointer-events: none;
            z-index: 20;
        }

        .lcd-screen {
            width: 100%;
            height: 100%;
            background-color: #93a39b;
            background-image: repeating-linear-gradient(
                0deg,
                transparent,
                transparent 1px,
                rgba(0,0,0,0.04) 1px,
                rgba(0,0,0,0.04) 2px
            );
            border-radius: 4px;
            box-shadow: inset 0 0 15px rgba(0, 0, 0, 0.4);
            display: flex;
            flex-direction: column;
            position: relative;
            overflow: hidden;
        }

        .status-bar {
            height: 22px;
            border-bottom: 1px solid rgba(0,0,0,0.15);
            background: linear-gradient(to bottom, rgba(255,255,255,0.1), transparent);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 8px;
            font-family: 'VT323', monospace;
            color: #1a2421;
            font-size: 16px;
            z-index: 5;
        }

        .battery-icon {
            width: 22px;
            height: 11px;
            border: 1.5px solid #1a2421;
            position: relative;
            padding: 1px;
        }
        .battery-icon::after {
            content: '';
            position: absolute;
            right: -4px;
            top: 2px;
            width: 2px;
            height: 4px;
            background: #1a2421;
        }
        .battery-fill { width: 85%; height: 100%; background: #1a2421; }

        .content-area {
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: #000;
            text-align: center;
            z-index: 5;
        }

        .title {
            font-size: 1.15rem;
            font-weight: 700;
            margin-bottom: 12px;
            text-shadow: 1px 1px 0 rgba(255,255,255,0.4);
            letter-spacing: 1px;
        }

        .timer-display {
            font-family: 'VT323', monospace;
            display: flex;
            align-items: center;
            gap: 4px;
        }
        .time-group { display: flex; flex-direction: column; align-items: center; min-width: 65px; }
        .time-value { font-size: 3.5rem; line-height: 1; text-shadow: 0 1px 0 rgba(255,255,255,0.3); }
        .time-label {
            font-family: 'Noto Sans SC', sans-serif;
            font-size: 0.65rem;
            font-weight: 700;
            text-transform: uppercase;
            color: #1a2421;
            letter-spacing: 1px;
            margin-top: 4px;
        }
        .colon { font-size: 2.5rem; margin: 0 2px; padding-bottom: 15px; animation: blink 1s infinite; }
        @keyframes blink { 0%, 100% { opacity: 1; } 50% { opacity: 0.2; } }

        .click-wheel-wrapper { margin-top: 45px; position: relative; }
        .click-wheel {
            width: 230px; height: 230px; border-radius: 50%;
            background: radial-gradient(circle, #f3f4f6 0%, #e5e5e5 100%);
            box-shadow: 
                inset 1px 1px 4px rgba(255,255,255,0.9),
                inset -2px -2px 6px rgba(0,0,0,0.1),
                0 0 0 1px #d1d5db,
                0 5px 10px rgba(0,0,0,0.15);
            position: relative;
            display: flex; justify-content: center; align-items: center;
        }

        .wheel-label {
            position: absolute; font-family: sans-serif; font-size: 0.85rem; font-weight: bold;
            color: #9ca3af; text-shadow: 1px 1px 0 #fff; pointer-events: none;
        }
        .label-menu { top: 16px; letter-spacing: 1px; }
        .label-prev { left: 16px; font-size: 1rem; }
        .label-next { right: 16px; font-size: 1rem; }
        .label-play { bottom: 16px; font-size: 1.1rem; }

        .center-btn {
            width: 85px; height: 85px; border-radius: 50%;
            background: linear-gradient(135deg, #ffffff 0%, #f4f4f5 50%, #e4e4e7 100%);
            box-shadow: 
                inset -3px -3px 6px rgba(255,255,255,0.9),
                inset 3px 3px 6px rgba(0,0,0,0.15),
                0 0 0 1px #d1d5db, 0 3px 6px rgba(0,0,0,0.2);
            cursor: pointer; transition: all 0.1s;
        }
        .center-btn:active {
            box-shadow: 
                inset 3px 3px 6px rgba(0,0,0,0.2), inset -3px -3px 6px rgba(255,255,255,0.5),
                0 0 0 1px #d1d5db;
            background: #e4e4e7;
        }

        .y2k-neon-bg {
            animation: insane-bg 0.3s infinite;
        }
        @keyframes insane-bg {
            0% { background-color: #ff00ff; }
            25% { background-color: #00ffff; }
            50% { background-color: #00ff00; }
            75% { background-color: #ffff00; }
            100% { background-color: #ff0000; }
        }

        .y2k-screen-bg {
            background: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100"><rect width="100" height="100" fill="magenta"/><text x="10" y="50" font-size="20" fill="yellow">!!!</text></svg>') !important;
            background-size: cover !important;
            animation: insane-bg 0.1s infinite reverse !important;
        }

        .bouncing-3d-text {
            font-family: "Comic Sans MS", "SimSun", cursive;
            font-weight: 900;
            font-size: 2.5rem;
            color: #ffff00;
            text-shadow: 
                4px 4px 0px #ff00ff, 
                -2px -2px 0px #00ffff,
                0px 0px 20px #ffffff;
            animation: bounce-zoom 0.5s infinite alternate;
            position: absolute;
            z-index: 100;
            text-align: center;
            width: 100%;
            top: 30%;
        }

        @keyframes bounce-zoom {
            0% { transform: scale(0.8) translateY(20px) rotate(-10deg); color: #ffff00;}
            100% { transform: scale(1.3) translateY(-20px) rotate(10deg); color: #00ff00;}
        }

        .marquee-layer {
            position: fixed;
            top: 5%;
            width: 100vw;
            font-size: 3rem;
            font-weight: 900;
            color: #ff00ff;
            background: #00ff00;
            text-shadow: 2px 2px #fff;
            z-index: 999;
            pointer-events: none;
            white-space: nowrap;
            overflow: hidden;
            display: none;
        }
        .marquee-content {
            display: inline-block;
            animation: scroll-left 3s linear infinite;
        }
        @keyframes scroll-left {
            0% { transform: translateX(100vw); }
            100% { transform: translateX(-100%); }
        }

        .heart {
            position: fixed;
            bottom: -50px;
            font-size: 3rem;
            animation: floatUp 3s ease-in infinite;
            z-index: 998;
            pointer-events: none;
        }
        @keyframes floatUp {
            0% { transform: translateY(0) scale(0.5) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-120vh) scale(2) rotate(360deg); opacity: 0; }
        }
        
        #celebration { display: none; }
    </style>
</head>
<body>

    <div class="marquee-layer" id="tuwei-marquee">
        <div class="marquee-content">🎉🎂 祝鲁姐生日快乐 永远18岁 暴富暴瘦 🎂🎉 祝鲁姐生日快乐 永远18岁 暴富暴瘦 🎂🎉</div>
    </div>

    <div class="ipod-casing" id="ipod-body">
        <div class="screen-glass">
            <div class="lcd-screen" id="ipod-screen">
                <div class="status-bar">
                    <span id="sys-time">12:00</span>
                    <span id="play-status">▶ II</span>
                    <div class="battery-icon"><div class="battery-fill"></div></div>
                </div>

                <div class="content-area" id="countdown-view">
                    <div class="title">距离鲁姐生日还有</div>
                    <div class="timer-display">
                        <div class="time-group"><span class="time-value" id="val-hours">00</span><span class="time-label">小时</span></div>
                        <span class="colon">:</span>
                        <div class="time-group"><span class="time-value" id="val-minutes">00</span><span class="time-label">分钟</span></div>
                        <span class="colon">:</span>
                        <div class="time-group"><span class="time-value" id="val-seconds">00</span><span class="time-label">秒</span></div>
                    </div>
                </div>

                <div id="celebration">
                    <div class="bouncing-3d-text">鲁姐<br>生日快乐!</div>
                </div>
            </div>
        </div>

        <div class="click-wheel-wrapper">
            <div class="click-wheel">
                <span class="wheel-label label-menu">MENU</span>
                <span class="wheel-label label-prev">|&lt;&lt;</span>
                <span class="wheel-label label-next">&gt;&gt;|</span>
                <span class="wheel-label label-play">&gt;||</span>
                <div class="center-btn" id="center-btn"></div>
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const hEl = document.getElementById('val-hours');
            const mEl = document.getElementById('val-minutes');
            const sEl = document.getElementById('val-seconds');
            const centerBtn = document.getElementById('center-btn');
            
            let timerInterval;
            let isCelebrationActive = false;

            // Target Date: JST 10-05 00:00:00
            function getTargetTime() {
                // Ensure timezone is correct (+09:00 for Tokyo/JST)
                const targetStr = '2026-10-05T00:00:00+09:00';
                return new Date(targetStr).getTime();
            }
            const targetTime = getTargetTime();

            const formatNum = (n) => String(n).padStart(2, '0');

            const updateCountdown = () => {
                if (isCelebrationActive) return;
                const now = new Date().getTime();
                const diff = targetTime - now;

                if (diff <= 0) {
                    triggerTuweiCelebration();
                    return;
                }

                const hours = Math.floor(diff / (1000 * 60 * 60));
                const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((diff % (1000 * 60)) / 1000);

                hEl.textContent = formatNum(hours);
                mEl.textContent = formatNum(minutes);
                sEl.textContent = formatNum(seconds);
            };

            setInterval(() => {
                const now = new Date();
                document.getElementById('sys-time').textContent = `${formatNum(now.getHours())}:${formatNum(now.getMinutes())}`;
            }, 1000);
            
            updateCountdown();
            timerInterval = setInterval(updateCountdown, 1000);

            let audioCtx = null;
            function play8BitBirthdaySong() {
                if (!audioCtx) {
                    audioCtx = new (window.AudioContext || window.webkitAudioContext)();
                }
                if (audioCtx.state === 'suspended') {
                    audioCtx.resume();
                }

                // Melodic notes for Happy Birthday in key of C
                // Format: [Frequency in Hz, Duration in Beats]
                // 1 Beat = 0.4 seconds (Tempo = 150 BPM)
                const beatLen = 0.35;
                const melody = [
                    [261.63, 0.75], [261.63, 0.25], [293.66, 1], [261.63, 1], [349.23, 1], [329.63, 2], // Happy birthday to you
                    [261.63, 0.75], [261.63, 0.25], [293.66, 1], [261.63, 1], [392.00, 1], [349.23, 2], // Happy birthday to you
                    [261.63, 0.75], [261.63, 0.25], [523.25, 1], [440.00, 1], [349.23, 1], [329.63, 1], [293.66, 2], // Happy birthday dear Lu Jie
                    [466.16, 0.75], [466.16, 0.25], [440.00, 1], [349.23, 1], [392.00, 1], [349.23, 2]  // Happy birthday to you
                ];

                let startTime = audioCtx.currentTime;

                melody.forEach(note => {
                    const freq = note[0];
                    const duration = note[1] * beatLen;

                    const osc = audioCtx.createOscillator();
                    const gain = audioCtx.createGain();

                    osc.type = 'square'; // 8-bit style sound
                    osc.frequency.value = freq;
                    
                    // Envelope for discrete notes (prevents clicking)
                    gain.gain.setValueAtTime(0, startTime);
                    gain.gain.linearRampToValueAtTime(0.2, startTime + 0.05); // Volume
                    gain.gain.setValueAtTime(0.2, startTime + duration - 0.05);
                    gain.gain.linearRampToValueAtTime(0, startTime + duration);

                    osc.connect(gain);
                    gain.connect(audioCtx.destination);

                    osc.start(startTime);
                    osc.stop(startTime + duration);

                    startTime += duration; // Advance time for next note
                });
                
                // Loop song by recalling it after it finishes
                setTimeout(play8BitBirthdaySong, (startTime - audioCtx.currentTime) * 1000 + 500);
            }

            function spawnHearts() {
                const emojis = ['💖', '🌺', '🌟', '💃', '💋', '🎉', '🍎'];
                setInterval(() => {
                    const heart = document.createElement('div');
                    heart.className = 'heart';
                    heart.textContent = emojis[Math.floor(Math.random() * emojis.length)];
                    heart.style.left = Math.random() * 100 + 'vw';
                    heart.style.animationDuration = (Math.random() * 2 + 2) + 's';
                    document.body.appendChild(heart);
                    
                    // Cleanup
                    setTimeout(() => heart.remove(), 5000);
                }, 200);
            }

            // Core trigger function
            function triggerTuweiCelebration() {
                if (isCelebrationActive) return;
                isCelebrationActive = true;
                clearInterval(timerInterval);

                // UI Changes
                document.getElementById('countdown-view').style.display = 'none';
                document.getElementById('celebration').style.display = 'block';
                document.getElementById('tuwei-marquee').style.display = 'block';
                
                // Add crazy classes
                document.body.classList.add('y2k-neon-bg');
                document.getElementById('ipod-screen').classList.add('y2k-screen-bg');
                document.getElementById('play-status').textContent = '♫ PLAY';

                // Visual Effects
                spawnHearts();
                
                // Audio Execution (Wrapped in try/catch in case of strict auto-play policies, but click circumvents this)
                try {
                    play8BitBirthdaySong();
                } catch (e) {
                    console.log("Audio play failed, user gesture might be required.", e);
                }
            }

            centerBtn.addEventListener('click', () => {
                // Clicking the center button acts as the ultimate override and user gesture
                triggerTuweiCelebration();
            });
        });
    </script>
</body>
</html>
