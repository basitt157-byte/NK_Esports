<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NK Esports | Nova Knightz PUBG Mobile</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Rajdhani:wght@500;700&display=swap" rel="stylesheet">
    
    <style>
        body {
            background-color: #050505;
            color: white;
            font-family: 'Rajdhani', sans-serif;
            overflow-x: hidden;
        }
        .font-gaming { font-family: 'Orbitron', sans-serif; }
        
        .hero-gradient {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.9)), 
                        url('https://images.unsplash.com/photo-1542751371-adc38448a05e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
        }

        .gold-glow {
            text-shadow: 0 0 15px rgba(255, 215, 0, 0.7);
        }

        .card-hover:hover {
            transform: translateY(-10px) scale(1.02);
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            border-color: #fbbf24;
            box-shadow: 0 10px 30px -10px rgba(251, 191, 36, 0.5);
        }
    </style>
</head>
<body>

    <nav class="flex justify-between items-center px-10 py-6 absolute w-full z-50">
        <div class="text-3xl font-gaming font-bold tracking-tighter animate__animated animate__fadeInLeft">
            NK <span class="text-yellow-500">ESPORTS</span>
        </div>
        <ul class="hidden md:flex space-x-8 font-gaming text-sm tracking-widest">
            <li class="hover:text-yellow-500 cursor-pointer transition">HOME</li>
            <li class="hover:text-yellow-500 cursor-pointer transition">ROSTER</li>
            <li class="hover:text-yellow-500 cursor-pointer transition">TOURNAMENTS</li>
            <li class="hover:text-yellow-500 cursor-pointer transition">MERCH</li>
        </ul>
        <button class="bg-yellow-600 hover:bg-yellow-500 text-black px-6 py-2 font-bold rounded-sm skew-x-[-15deg] transition duration-300">
            JOIN CLAN
        </button>
    </nav>

    <section class="h-screen flex items-center justify-center hero-gradient relative">
        <div class="text-center z-10">
            <h2 class="text-xl tracking-[0.5em] text-yellow-500 animate__animated animate__fadeInDown">WE ARE THE NIGHT</h2>
            <h1 class="text-7xl md:text-9xl font-gaming font-bold gold-glow animate__animated animate__zoomIn">
                NOVA <span class="text-transparent bg-clip-text bg-gradient-to-r from-yellow-400 to-yellow-700">KNIGHTZ</span>
            </h1>
            <p class="mt-4 text-gray-300 max-w-lg mx-auto animate__animated animate__fadeInUp animate__delay-1s">
                Dominating the Battlegrounds with precision, strategy, and power. 
                The elite PUBG Mobile squad for the next generation.
            </p>
            <div class="mt-8 flex justify-center gap-4 animate__animated animate__fadeInUp animate__delay-1s">
                <button class="border-2 border-yellow-500 px-8 py-3 font-bold hover:bg-yellow-500 hover:text-black transition duration-500">
                    WATCH LIVE
                </button>
            </div>
        </div>
    </section>

    <section class="py-20 bg-black">
        <div class="container mx-auto grid grid-cols-1 md:grid-cols-3 gap-10 px-10">
            <div class="p-8 border border-gray-800 card-hover bg-[#0a0a0a] text-center">
                <h3 class="text-5xl font-gaming text-yellow-500 mb-2">150+</h3>
                <p class="text-gray-400 uppercase tracking-widest">Chicken Dinners</p>
            </div>
            <div class="p-8 border border-gray-800 card-hover bg-[#0a0a0a] text-center">
                <h3 class="text-5xl font-gaming text-yellow-500 mb-2">12</h3>
                <p class="text-gray-400 uppercase tracking-widest">Major Trophies</p>
            </div>
            <div class="p-8 border border-gray-800 card-hover bg-[#0a0a0a] text-center">
                <h3 class="text-5xl font-gaming text-yellow-500 mb-2">2M+</h3>
                <p class="text-gray-400 uppercase tracking-widest">Fans Worldwide</p>
            </div>
        </div>
    </section>

    <section class="py-20 px-10">
        <h2 class="text-4xl font-gaming font-bold mb-16 text-center underline decoration-yellow-500 underline-offset-8">THE ELITE SQUAD</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
            <div class="relative group overflow-hidden border-b-4 border-yellow-600">
                <img src="images/asim.jpg.jpg" alt="Player" class="grayscale group-hover:grayscale-0 transition duration-700">
                <div class="absolute bottom-0 left-0 w-full p-6 bg-gradient-to-t from-black to-transparent">
                    <p class="text-yellow-500 font-bold">IGL</p>
                    <h4 class="text-2xl font-gaming">NK Asim</h4>
                </div>
            </div>
            <div class="relative group overflow-hidden border-b-4 border-yellow-600">
                <img src="images/1.jpg.jpg" alt="Player" class="grayscale group-hover:grayscale-0 transition duration-700">
                <div class="absolute bottom-0 left-0 w-full p-6 bg-gradient-to-t from-black to-transparent">
                    <p class="text-yellow-500 font-bold">SNIPER</p>
                    <h4 class="text-2xl font-gaming">NK Mohsin</h4>
                </div>
            </div>
            <div class="relative group overflow-hidden border-b-4 border-yellow-600">
                <img src="images/html.jpg.jpg" alt="Player" class="grayscale group-hover:grayscale-0 transition duration-700">
                <div class="absolute bottom-0 left-0 w-full p-6 bg-gradient-to-t from-black to-transparent">
                    <p class="text-yellow-500 font-bold">ASSAULTER</p>
                    <h4 class="text-2xl font-gaming">NK Basit</h4>
                </div>
            </div>
            <div class="relative group overflow-hidden border-b-4 border-yellow-600">
                <img src="images/arham.jpg.jpg" alt="Player" class="grayscale group-hover:grayscale-0 transition duration-700">
                <div class="absolute bottom-0 left-0 w-full p-6 bg-gradient-to-t from-black to-transparent">
                    <p class="text-yellow-500 font-bold">SUPPORT</p>
                    <h4 class="text-2xl font-gaming">NK Arham</h4>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-10 border-t border-gray-900 text-center">
        <p class="text-gray-500 uppercase tracking-widest text-sm">&copy; 2024 NK ESPORTS (NOVA KNIGHTZ). ALL RIGHTS RESERVED.</p>
    </footer>

</body>
</html>
