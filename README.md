<!DOCTYPE html>
<html lang="tr">
  <head>
    <!-- Essential SEO Meta Tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Türkiye'nin En Güncel Bilgi Kaynağı | Ziyaretçi Dostu Site</title>
    <meta name="description" content="Trend konular, uzman içerikler ve interaktif topluluk ile her gün binlerce ziyaretçinin buluşma noktası." />
    <link rel="canonical" href="https://www.orneksite.com/" />

    <!-- Open Graph / Facebook -->
    <meta property="og:type" content="website" />
    <meta property="og:url" content="https://www.orneksite.com/" />
    <meta property="og:title" content="Türkiye'nin En Güncel Bilgi Kaynağı" />
    <meta property="og:description" content="Trend konular, uzman içerikler ve interaktif topluluk ile her gün binlerce ziyaretçinin buluşma noktası." />
    <meta property="og:image" content="https://www.orneksite.com/og-image.jpg" />

    <!-- Twitter -->
    <meta property="twitter:card" content="summary_large_image" />
    <meta property="twitter:url" content="https://www.orneksite.com/" />
    <meta property="twitter:title" content="Türkiye'nin En Güncel Bilgi Kaynağı" />
    <meta property="twitter:description" content="Trend konular, uzman içerikler ve interaktif topluluk ile her gün binlerce ziyaretçinin buluşma noktası." />
    <meta property="twitter:image" content="https://www.orneksite.com/og-image.jpg" />

    <!-- Structured Data -->
    <script type="application/ld+json">
      {
        "@context": "https://schema.org",
        "@type": "Organization",
        "name": "OrnekSite",
        "url": "https://www.orneksite.com/",
        "logo": "https://www.orneksite.com/logo.svg",
        "sameAs": [
          "https://www.facebook.com/orneksite",
          "https://www.instagram.com/orneksite",
          "https://twitter.com/orneksite"
        ]
      }
    </script>

    <!-- Tailwind CSS (CDN) -->
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body class="antialiased text-gray-800">
    <!-- Header & Navigation -->
    <header class="bg-white shadow sticky top-0 z-50">
      <div class="max-w-7xl mx-auto px-4 py-4 flex items-center justify-between">
        <a href="/" class="text-2xl font-bold text-indigo-600">OrnekSite</a>
        <nav class="hidden md:flex space-x-6">
          <a href="#konular" class="hover:text-indigo-600">Konular</a>
          <a href="#blog" class="hover:text-indigo-600">Blog</a>
          <a href="#bulten" class="hover:text-indigo-600">Bülten</a>
        </nav>
        <a href="#bulten" class="md:inline-block hidden bg-indigo-600 text-white px-4 py-2 rounded-lg hover:bg-indigo-700 transition">Üye Ol</a>
      </div>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="bg-gradient-to-r from-indigo-500 to-purple-600 text-white py-24">
      <div class="max-w-4xl mx-auto text-center px-4">
        <h1 class="text-4xl md:text-6xl font-extrabold mb-6 leading-tight">Trend Bilgiler, Uzman İçerikler</h1>
        <p class="text-lg md:text-2xl mb-8">Tek tıkla merak ettiğin her şey burada. Gündemin nabzını tut, topluluğa katıl, sen de sesini duyur.</p>
        <a href="#bulten" class="inline-block bg-white text-indigo-600 font-semibold px-8 py-3 rounded-full shadow-lg hover:shadow-xl transition">Hemen Başla</a>
      </div>
    </section>

    <!-- Featured Topics -->
    <section id="konular" class="py-16 bg-gray-50">
      <div class="max-w-6xl mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-10">Popüler Konular</h2>
        <div class="grid gap-8 md:grid-cols-2 lg:grid-cols-4">
          <div class="bg-white p-6 rounded-2xl shadow">
            <h3 class="text-xl font-semibold mb-2">Yemek & Tarifler</h3>
            <p class="text-gray-600">2025'in protein odaklı ve sürdürülebilir yemek trendleriyle sofranızı renklendirin.</p>
          </div>
          <div class="bg-white p-6 rounded-2xl shadow">
            <h3 class="text-xl font-semibold mb-2">Seyahat</h3>
            <p class="text-gray-600">Sürdürülebilir rotalar ve uzaktan çalışma dostu destinasyonları keşfedin.</p>
          </div>
          <div class="bg-white p-6 rounded-2xl shadow">
            <h3 class="text-xl font-semibold mb-2">Kişisel Finans</h3>
            <p class="text-gray-600">Gen Z ve Y kuşağı için bütçe, yatırım ve tasarruf tüyoları.</p>
          </div>
          <div class="bg-white p-6 rounded-2xl shadow">
            <h3 class="text-xl font-semibold mb-2">Yapay Zeka</h3>
            <p class="text-gray-600">Güncel AI araçlarını kullanarak iş ve günlük yaşamınızı optimize edin.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Blog Section -->
    <section id="blog" class="py-16">
      <div class="max-w-6xl mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-10">En Son Yazılar</h2>
        <div class="space-y-12">
          <article class="flex flex-col md:flex-row gap-6">
            <img src="https://via.placeholder.com/400x250" alt="Blog Post" class="w-full md:w-1/3 rounded-2xl object-cover" />
            <div class="flex-1">
              <h3 class="text-2xl font-semibold mb-2">Yapay Zeka Destekli Reklamcılıkla Büyüme Stratejileri</h3>
              <p class="text-gray-700 mb-4">Reddit'in 2025'te kazandığı ivme, AI tabanlı hedefli reklamcılığın gücünü kanıtlıyor. İşte sizin de uygulayabileceğiniz adımlar...</p>
              <a href="#" class="text-indigo-600 font-medium hover:underline">Devamını Oku →</a>
            </div>
          </article>
        </div>
      </div>
    </section>

    <!-- Newsletter CTA -->
    <section id="bulten" class="bg-indigo-600 text-white py-16">
      <div class="max-w-3xl mx-auto px-4 text-center">
        <h2 class="text-3xl md:text-4xl font-bold mb-6">Haftalık Bültenimize Katılın</h2>
        <p class="text-lg mb-8">En yeni içerikleri ve özel indirimleri doğrudan e‑postanıza alın.</p>
        <form class="flex flex-col md:flex-row gap-4 justify-center">
          <input type="email" placeholder="E‑posta adresiniz" class="flex-1 px-4 py-3 rounded-lg text-gray-800" required />
          <button type="submit" class="bg-white text-indigo-600 font-semibold px-6 py-3 rounded-lg hover:bg-gray-100 transition">Abone Ol</button>
        </form>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-8">
      <div class="max-w-6xl mx-auto px-4 flex flex-col md:flex-row justify-between items-center gap-4">
        <p>© 2025 OrnekSite. Tüm hakları saklıdır.</p>
        <nav class="flex space-x-4">
          <a href="#" class="hover:text-white">Gizlilik Politikası</a>
          <a href="#" class
