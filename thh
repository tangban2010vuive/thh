<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tặng bạn Minh Trang 20/10 💖</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600;700&family=Nunito:wght@400;600;700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Canvas Confetti library -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'rose-pastel': '#ffe4e6',
                        'pink-pastel': '#fbcfe8',
                        'cream': '#fffbf0',
                        'deep-rose': '#e11d48',
                        'soft-red': '#f43f5e'
                    },
                    fontFamily: {
                        'handwriting': ['Dancing Script', 'cursive'],
                        'sans': ['Nunito', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        body {
            font-family: 'Nunito', sans-serif;
            background: linear-gradient(135deg, #fff0f3 0%, #ffccd5 50%, #ffb3c1 100%);
            min-height: 100vh;
            overflow-x: hidden;
            -webkit-tap-highlight-color: transparent;
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #ffe4e6;
        }
        ::-webkit-scrollbar-thumb {
            background: #f43f5e;
            border-radius: 10px;
        }

        /* Background floating elements canvas */
        #bgCanvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 0;
        }

        /* Pulsing Glow Animation */
        @keyframes pulseGlow {
            0%, 100% {
                box-shadow: 0 0 25px rgba(244, 63, 94, 0.4);
                transform: scale(1);
            }
            50% {
                box-shadow: 0 0 45px rgba(244, 63, 94, 0.75);
                transform: scale(1.03);
            }
        }

        .pulse-box {
            animation: pulseGlow 2.5s infinite ease-in-out;
        }

        /* Float Animation */
        @keyframes floatAnim {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-12px); }
        }

        .floating {
            animation: floatAnim 3s ease-in-out infinite;
        }

        /* Envelope / Gift Card Flip & Fade Effects */
        .card-enter {
            opacity: 0;
            transform: scale(0.8) translateY(30px);
            transition: all 0.8s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        .card-show {
            opacity: 1;
            transform: scale(1) translateY(0);
        }

        /* Glassmorphism Effect */
        .glass {
            background: rgba(255, 255, 255, 0.88);
            backdrop-filter: blur(14px);
            -webkit-backdrop-filter: blur(14px);
            border: 1px solid rgba(255, 255, 255, 0.7);
        }
    </style>
</head>
<body class="relative flex flex-col justify-between items-center text-gray-800 antialiased min-h-screen p-4 md:p-8">

    <!-- Interactive Canvas for Floating Hearts and Petals -->
    <canvas id="bgCanvas"></canvas>

    <!-- Top Music Control Floating Button -->
    <div class="fixed top-4 right-4 z-50 flex items-center gap-2">
        <button id="musicToggle" class="glass px-4 py-2.5 rounded-full shadow-lg flex items-center gap-2 text-deep-rose font-bold hover:bg-white transition-all transform active:scale-95 text-sm md:text-base cursor-pointer">
            <i id="musicIcon" class="fa-solid fa-music animate-spin" style="animation-duration: 4s;"></i>
            <span id="musicText">Bật nhạc</span>
        </button>
    </div>

    <!-- Main Container -->
    <main class="relative z-10 w-full max-w-2xl mx-auto flex flex-col items-center justify-center my-auto py-6">

        <!-- Header Title -->
        <header class="text-center mb-8 floating">
            <span class="inline-block px-4 py-1.5 bg-rose-200/80 text-deep-rose font-semibold rounded-full text-sm mb-3 shadow-sm border border-rose-300">
                ✨ Ngày Phụ Nữ Việt Nam 20/10 ✨
            </span>
            <h1 class="text-4xl md:text-6xl font-bold font-handwriting text-deep-rose drop-shadow-md tracking-wide px-2">
                Tặng bạn Minh Trang 20/10 💖
            </h1>
        </header>

        <!-- GIFT BOX AREA (State 1: Unopened) -->
        <div id="giftContainer" class="flex flex-col items-center justify-center cursor-pointer my-4 transition-all duration-500">
            <div class="relative group">
                <!-- Glowing Aura -->
                <div class="absolute -inset-4 bg-gradient-to-r from-pink-400 to-rose-400 rounded-full blur-lg opacity-70 group-hover:opacity-100 transition duration-1000 group-hover:duration-200 animate-pulse"></div>
                
                <!-- Gift Box Envelope Card -->
                <div id="giftBox" class="relative pulse-box glass rounded-3xl p-8 md:p-12 flex flex-col items-center justify-center border-2 border-rose-300 transform group-hover:scale-105 transition-all duration-300">
                    <div class="w-28 h-28 md:w-36 md:h-36 flex items-center justify-center text-6xl md:text-8xl text-deep-rose mb-3 filter drop-shadow-lg">
                        <i class="fa-solid fa-gift animate-bounce"></i>
                    </div>
                    <span class="text-lg md:text-xl font-bold text-deep-rose bg-rose-100/90 px-6 py-2.5 rounded-full border border-rose-300 shadow-sm">
                        Chạm để mở quà! 🎁
                    </span>
                </div>
            </div>
            <p class="text-xs md:text-sm text-rose-700 font-semibold mt-5 italic bg-white/60 px-4 py-1.5 rounded-full border border-rose-200">
                Món quà bất ngờ đang chờ Minh Trang bên trong đấy! ✨
            </p>
        </div>

        <!-- GREETING CARD AREA (State 2: Opened - Initially Hidden) -->
        <div id="cardContainer" class="hidden w-full card-enter glass rounded-3xl p-6 md:p-10 shadow-2xl border-2 border-pink-300 relative overflow-hidden">
            <!-- Decorative ribbon badge -->
            <div class="absolute top-0 right-0 bg-gradient-to-l from-rose-500 to-pink-500 text-white text-xs font-extrabold px-8 py-1.5 transform rotate-45 translate-x-7 translate-y-3 shadow-md">
                SPECIAL 20/10
            </div>

            <div class="text-center mb-6">
                <span class="text-4xl md:text-5xl text-rose-500 inline-block mb-1">💐</span>
                <h2 class="text-3xl md:text-5xl font-bold font-handwriting text-deep-rose mt-1">
                    Gửi tặng Minh Trang 🌹
                </h2>
            </div>

            <!-- Letter Content -->
            <div class="bg-white/95 rounded-2xl p-6 md:p-8 shadow-inner border border-rose-100 text-gray-800 leading-relaxed space-y-4 text-base md:text-lg text-justify md:text-left">
                <p>
                    🌸 Chúc <span class="font-bold text-deep-rose">Minh Trang</span> có một ngày 20/10 thật nhiều niềm vui, luôn xinh đẹp, rạng rỡ và ngập tràn hạnh phúc!
                </p>
                <p>
                    💐 Mong rằng mọi điều ngọt ngào, may mắn và thành công nhất sẽ luôn đồng hành cùng cậu trên mọi chặng đường!
                </p>
                <p class="text-right font-handwriting text-2xl md:text-3xl text-deep-rose font-bold pt-4">
                    Thân tặng Minh Trang! ❤️
                </p>
            </div>
        </div>

    </main>

    <!-- Background Audio Element -->
    <audio id="bgAudio" loop preload="auto">
        <source src="https://cdn.pixabay.com/download/audio/2022/05/27/audio_1808fbf07a.mp3?filename=romantic-piano-112181.mp3" type="audio/mpeg">
    </audio>

    <!-- Footer -->
    <footer class="relative z-10 text-center text-xs text-rose-700/80 mt-auto pt-6">
        <p>Thực hiện với 💖 dành tặng Minh Trang ngày 20/10</p>
    </footer>

    <!-- JavaScript Logic -->
    <script>
        const giftContainer = document.getElementById('giftContainer');
        const cardContainer = document.getElementById('cardContainer');
        const musicToggle = document.getElementById('musicToggle');
        const musicIcon = document.getElementById('musicIcon');
        const musicText = document.getElementById('musicText');
        const bgAudio = document.getElementById('bgAudio');

        let isAudioPlaying = false;

        // Open Gift Box Handler
        giftContainer.addEventListener('click', () => {
            triggerHeartFireworks();

            giftContainer.classList.add('opacity-0', 'scale-50');
            setTimeout(() => {
                giftContainer.classList.add('hidden');
                cardContainer.classList.remove('hidden');
                setTimeout(() => {
                    cardContainer.classList.add('card-show');
                }, 50);
            }, 400);

            if (!isAudioPlaying) {
                playAudio();
            }
        });

        // Confetti Fireworks Effect (Heart shapes & romantic colors)
        function triggerHeartFireworks() {
            const count = 220;
            const defaults = {
                origin: { y: 0.65 }
            };

            function fire(particleRatio, opts) {
                confetti(Object.assign({}, defaults, opts, {
                    particleCount: Math.floor(count * particleRatio)
                }));
            }

            fire(0.25, {
                spread: 30,
                startVelocity: 55,
                colors: ['#f43f5e', '#e11d48', '#ffccd5']
            });
            fire(0.2, {
                spread: 60,
                colors: ['#ffffff', '#fb7185']
            });
            fire(0.35, {
                spread: 100,
                decay: 0.91,
                scalar: 0.85
            });
            fire(0.1, {
                spread: 120,
                startVelocity: 25,
                decay: 0.92,
                colors: ['#ffe4e6', '#f43f5e']
            });
            fire(0.1, {
                spread: 120,
                startVelocity: 45,
            });
        }

        // Audio Control Logic
        function playAudio() {
            bgAudio.play().then(() => {
                isAudioPlaying = true;
                musicText.innerText = "Tắt nhạc";
                musicIcon.classList.add('animate-spin');
            }).catch(err => {
                console.log("Audio autoplay prevented", err);
            });
        }

        function pauseAudio() {
            bgAudio.pause();
            isAudioPlaying = false;
            musicText.innerText = "Bật nhạc";
            musicIcon.classList.remove('animate-spin');
        }

        musicToggle.addEventListener('click', () => {
            if (isAudioPlaying) {
                pauseAudio();
            } else {
                playAudio();
            }
        });

        // Canvas Animation: Floating Hearts & Rose Petals Background
        const canvas = document.getElementById('bgCanvas');
        const ctx = canvas.getContext('2d');

        let particles = [];
        const particleCount = window.innerWidth < 768 ? 30 : 55;

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        }

        window.addEventListener('resize', resizeCanvas);
        resizeCanvas();

        class Particle {
            constructor() {
                this.reset();
            }

            reset() {
                this.x = Math.random() * canvas.width;
                this.y = canvas.height + Math.random() * 100;
                this.size = Math.random() * 12 + 8;
                this.speedY = Math.random() * 1.4 + 0.6;
                this.speedX = Math.sin(Math.random() * Math.PI) * 0.8;
                this.opacity = Math.random() * 0.6 + 0.3;
                this.type = Math.random() > 0.35 ? 'heart' : 'circle';
                this.color = ['#f43f5e', '#fb7185', '#fda4af', '#f472b6', '#e11d48'][Math.floor(Math.random() * 5)];
                this.rotation = Math.random() * Math.PI * 2;
                this.rotSpeed = (Math.random() - 0.5) * 0.025;
            }

            update() {
                this.y -= this.speedY;
                this.x += Math.sin(this.y * 0.01) + this.speedX;
                this.rotation += this.rotSpeed;

                if (this.y < -20) {
                    this.reset();
                }
            }

            draw() {
                ctx.save();
                ctx.translate(this.x, this.y);
                ctx.rotate(this.rotation);
                ctx.globalAlpha = this.opacity;
                ctx.fillStyle = this.color;

                if (this.type === 'heart') {
                    ctx.beginPath();
                    const topCurveHeight = this.size * 0.3;
                    ctx.moveTo(0, topCurveHeight);
                    ctx.bezierCurveTo(0, 0, -this.size / 2, 0, -this.size / 2, topCurveHeight);
                    ctx.bezierCurveTo(-this.size / 2, (this.size + topCurveHeight) / 2, 0, this.size, 0, this.size);
                    ctx.bezierCurveTo(0, this.size, this.size / 2, (this.size + topCurveHeight) / 2, this.size / 2, topCurveHeight);
                    ctx.bezierCurveTo(this.size / 2, 0, 0, 0, 0, topCurveHeight);
                    ctx.closePath();
                    ctx.fill();
                } else {
                    ctx.beginPath();
                    ctx.arc(0, 0, this.size / 2, 0, Math.PI * 2);
                    ctx.fill();
                }

                ctx.restore();
            }
        }

        for (let i = 0; i < particleCount; i++) {
            particles.push(new Particle());
        }

        function animateCanvas() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            particles.forEach(p => {
                p.update();
                p.draw();
            });
            requestAnimationFrame(animateCanvas);
        }

        window.onload = function() {
            animateCanvas();
        };
    </script>
</body>
</html>
