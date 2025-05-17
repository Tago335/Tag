




<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>معلومات عني</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    body { font-family: 'Arial', sans-serif; direction: rtl; }
    .hero-bg { background: linear-gradient(to bottom, #1a202c, #2d3748); }
    .social-btn { transition: transform 0.3s ease, background-color 0.3s ease; }
    .social-btn:hover { transform: scale(1.1); }
    @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
    .animate-fade-in { animation: fadeIn 1s ease-in; }
  </style>
</head>
<body class="bg-gray-900 text-white">
  <!-- Hero Section -->
  <section class="hero-bg min-h-screen flex flex-col justify-center items-center text-center px-4">
    <h1 class="text-5xl md:text-7xl font-bold mb-4 animate-fade-in">مرحباً بكم!</h1>
    <p class="text-xl md:text-2xl mb-8 max-w-2xl">
      أنا [تاج الدين]، وهذا موقعي الشخصي لمشاركة قصتي وروابطي الاجتماعية.
    </p>
    <a
      href="#about"
      class="bg-blue-600 text-white px-6 py-3 rounded-full text-lg hover:bg-blue-700 transition"
    >
      اكتشف المزيد
    </a>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16 px-4 bg-gray-800">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-6">عني</h2>
      <p class="text-lg md:text-xl leading-relaxed">
        [صانع محتوى مرئي | شغف بالتفاصيل  
تصوير، مشاعر، وحياة  
الرقة | 2004  
تابع لترى الحياة من زاويتي.]
      </p>
    </div>
  </section>

  <!-- Social Media Links -->
  <section class="py-16 px-4 bg-gray-900">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-3xl md:text-4xl font-bold mb-8">تابعني</h2>
      <div class="flex flex-col md:flex-row justify-center gap-4">
        <a
          href="https://www.instagram.com/092f_?igsh=MW5jMnprMHB4NHpicw=="
          target="_blank"
          rel="noopener noreferrer"
          class="social-btn bg-pink-600 text-white px-6 py-3 rounded-full text-lg hover:bg-pink-700"
        >
          إنستغرام
        </a>
        <a
          href="https://m.kwaiapps.com/user/150000934859662?fid=150000934859662&cc=COPY_LINK&language=ar-ae&share_device_id=ANDROID_52bbb31c86f89f02&share_id=ANDROID_52bbb31c86f89f02_1747490905898&share_uid=150000934859662×tamp=1747490905898&share_item_type=profile&share_item_info=150000934859662"
          target="_blank"
          rel="noopener noreferrer"
          class="social-btn bg-yellow-600 text-white px-6 py-3 rounded-full text-lg hover:bg-yellow-700"
        >
          كواي
        </a>
        <a
          href="https://www.facebook.com/profile.php?id=100044140325783&mibextid=ZbWKwL"
          target="_blank"
          rel="noopener noreferrer"
          class="social-btn bg-blue-800 text-white px-6 py-3 rounded-full text-lg hover:bg-blue-900"
        >
          فيسبوك
        </a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 py-6 text-center">
    <p class="text-gray-400">© 2025 [تاج]. جميع الحقوق محفوظة.</p>
  </footer>
</body>
</html>
