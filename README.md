<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>YeongStar Token [YST]</title>

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    body { font-family: 'Inter', sans-serif; scroll-behavior: smooth; }
    .glass-morphism {
      background: rgba(255, 255, 255, 0.9);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border-bottom: 1px solid rgba(0, 0, 0, 0.05);
    }
    .gradient-text {
      background: linear-gradient(135deg, #f59e0b 0%, #d97706 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
  </style>
</head>

<body class="bg-slate-50 text-slate-900 font-sans">

  <!-- Navigation -->
  <nav class="fixed w-full z-50 glass-morphism">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <div class="flex items-center space-x-3">
        <div class="w-10 h-10 bg-amber-500 rounded-full flex items-center justify-center text-white shadow-lg">
          <i data-lucide="star" class="w-6 h-6 fill-current"></i>
        </div>
        <div class="flex flex-col leading-tight">
          <span class="text-xl font-black tracking-tighter text-slate-900 uppercase">
            YeongStar Token <span class="text-amber-500">[YST]</span>
          </span>
          <span class="text-[10px] font-bold text-slate-400 tracking-widest uppercase">Decentralized Finance</span>
        </div>
      </div>

      <div class="hidden lg:flex space-x-10 font-bold text-slate-600">
        <a href="#home" class="hover:text-amber-600 transition-colors">Home</a>
        <a href="#about" class="hover:text-amber-600 transition-colors">About</a>
        <a href="#tokenomics" class="hover:text-amber-600 transition-colors">Tokenomics</a>
        <a href="#roadmap" class="hover:text-amber-600 transition-colors">Roadmap</a>
      </div>

      <div>
        <button class="bg-slate-900 text-white px-6 py-2.5 rounded-full font-bold hover:bg-amber-600 transition-all shadow-lg active:scale-95">
          Connect Wallet
        </button>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section id="home" class="relative min-h-screen flex items-center pt-20 overflow-hidden bg-white">
    <div class="absolute top-0 right-0 -mt-20 -mr-20 w-96 h-96 bg-amber-100 rounded-full filter blur-[100px] opacity-50"></div>
    <div class="absolute bottom-0 left-0 -mb-20 -ml-20 w-96 h-96 bg-blue-100 rounded-full filter blur-[100px] opacity-50"></div>

    <div class="max-w-7xl mx-auto px-6 relative z-10 grid md:grid-cols-2 gap-16 items-center">
      <div>
        <div class="inline-flex items-center space-x-2 px-4 py-1.5 bg-amber-50 text-amber-700 rounded-full text-xs font-bold mb-8 border border-amber-100 uppercase tracking-wider">
          <i data-lucide="sparkles" class="w-3.5 h-3.5"></i>
          <span>Official Launching 2026</span>
        </div>

        <h1 class="text-5xl md:text-8xl font-black leading-[0.95] mb-8 tracking-tighter text-slate-900">
          The Next <br />
          <span class="gradient-text">Star in Crypto.</span>
        </h1>

        <p class="text-lg text-slate-500 mb-10 max-w-lg leading-relaxed font-medium">
          YeongStar Token [YST] is a community-driven next-generation digital asset built for transparent governance and fast transactions.
        </p>

        <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
          <button class="bg-amber-500 text-white px-10 py-5 rounded-2xl font-black text-lg hover:bg-amber-600 transition-all shadow-2xl shadow-amber-200 flex items-center justify-center group">
            <span>Get Started</span>
            <i data-lucide="arrow-right" class="ml-2 w-5 h-5 group-hover:translate-x-1 transition-transform"></i>
          </button>
        </div>
      </div>

      <div class="relative">
        <div class="relative z-10 p-2 bg-gradient-to-br from-amber-200 to-amber-500 rounded-[3rem] shadow-2xl transform rotate-3 hover:rotate-0 transition-transform duration-500">
          <img
            src="https://images.unsplash.com/photo-1639762681485-074b7f938ba0?q=80&w=2832&auto=format&fit=crop"
            alt="Crypto Concept"
            class="rounded-[2.8rem] w-full aspect-square object-cover shadow-inner"
            onerror="this.src='https://via.placeholder.com/600x600?text=YST+Token'"
          />
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-slate-50 border-t border-slate-200 py-20">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <div class="flex items-center justify-center space-x-3 mb-8">
        <div class="w-10 h-10 bg-amber-500 rounded-full flex items-center justify-center text-white">
          <i data-lucide="star" class="w-6 h-6 fill-current"></i>
        </div>
        <span class="text-2xl font-black tracking-tighter text-slate-900">YeongStar Token [YST]</span>
      </div>

      <p class="text-slate-400 text-sm mb-4">© 2026 YeongStar Project Ecosystem. All rights reserved.</p>

      <p class="text-slate-400 text-sm mb-10">
        Contact:
        <a href="mailto:yeong4326@naver.com" class="hover:text-amber-500 transition-colors">
          yeong4326@naver.com
        </a>
      </p>

      <div class="flex justify-center space-x-6">
        <a href="#" class="text-slate-400 hover:text-amber-500 transition-colors"><i data-lucide="twitter"></i></a>
        <a href="#" class="text-slate-400 hover:text-amber-500 transition-colors"><i data-lucide="github"></i></a>
        <a href="#" class="text-slate-400 hover:text-amber-500 transition-colors"><i data-lucide="send"></i></a>
      </div>
    </div>
  </footer>

  <script>
    lucide.createIcons();
  </script>
</body>
</html>
