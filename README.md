<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ไทม์ไลน์โลก - เว็บไซต์ประวัติศาสตร์</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800 font-sans">

  <!-- Navbar -->
  <header class="bg-white shadow sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
      <h1 class="text-2xl font-bold text-indigo-700">ไทม์ไลน์โลก</h1>
      <nav class="space-x-6">
        <a href="#home" class="hover:text-indigo-600">หน้าแรก</a>
        <a href="#articles" class="hover:text-indigo-600">บทความ</a>
        <a href="#about" class="hover:text-indigo-600">เกี่ยวกับเรา</a>
        <a href="#contact" class="hover:text-indigo-600">ติดต่อ</a>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="bg-indigo-600 text-white py-20 text-center">
    <h2 class="text-4xl font-bold mb-4">โลกและประวัติศาสตร์ในมุมมองใหม่</h2>
    <p class="text-lg mb-6">สำรวจเหตุการณ์สำคัญจากอดีต ตั้งแต่เมโสโปเตเมียจนถึงยุคปัจจุบัน</p>
    <a href="#articles" class="bg-white text-indigo-700 px-6 py-3 rounded-full font-semibold shadow hover:bg-gray-100">เริ่มอ่านเลย</a>
  </section>

  <!-- Articles Section -->
  <section id="articles" class="max-w-6xl mx-auto py-16 px-6">
    <h3 class="text-3xl font-bold mb-8 text-center">บทความล่าสุด</h3>

    <!-- Search Bar -->
    <div class="mb-8 text-center">
      <input id="search" type="text" placeholder="ค้นหาบทความ..." class="w-full md:w-1/2 p-3 border rounded-xl">
    </div>

    <div id="articlesGrid" class="grid sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
      <!-- Card 1 -->
      <article class="article-card bg-white rounded-2xl shadow p-5 hover:shadow-lg transition" data-category="โบราณ">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Stele_of_Hammurabi_Louvre_Museum.jpg/330px-Stele_of_Hammurabi_Louvre_Museum.jpg" alt="ฮัมมูราบี" class="rounded-xl mb-4 w-full h-48 object-cover">
        <h4 class="text-xl font-semibold mb-2">กษัตริย์ฮัมมูราบี และกฎหมายโบราณ</h4>
        <p class="text-sm text-gray-600 mb-4">หนึ่งในกษัตริย์ผู้ทรงอิทธิพลที่สุดแห่งบาบิโลน ผู้สร้างกฎหมายลายลักษณ์อักษรฉบับแรกของโลก</p>
        <a href="#" class="text-indigo-600 font-semibold hover:underline">อ่านต่อ</a>
      </article>

      <!-- Advertisement Inline -->
      <div class="col-span-full bg-gradient-to-r from-purple-400 via-pink-500 to-red-500 p-6 rounded-2xl text-center shadow-lg transform hover:scale-105 transition duration-300">
        <h4 class="text-2xl font-bold mb-4 text-white">แนะนำสินค้า / สนับสนุนเว็บไซต์</h4>
        <p class="text-white mb-6">คลิกเพื่อดูโปรโมชั่นพิเศษและสินค้าน่าสนใจจาก Affiliate</p>
        <a href="https://example-affiliate-link.com" target="_blank" class="bg-white text-red-600 px-6 py-3 rounded-full font-semibold shadow hover:bg-gray-100 transition">คลิกดูสินค้าที่นี่</a>
      </div>

      <!-- Card 2 -->
      <article class="article-card bg-white rounded-2xl shadow p-5 hover:shadow-lg transition" data-category="โบราณ">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Pyramids_of_Egypt_giza.jpg/320px-Pyramids_of_Egypt_giza.jpg" alt="อียิปต์โบราณ" class="rounded-xl mb-4 w-full h-48 object-cover">
        <h4 class="text-xl font-semibold mb-2">อียิปต์โบราณและพีระมิดแห่งกิซา</h4>
        <p class="text-sm text-gray-600 mb-4">สิ่งมหัศจรรย์ของโลกยุคโบราณที่ยังคงตั้งตระหง่านและเต็มไปด้วยปริศนา</p>
        <a href="#" class="text-indigo-600 font-semibold hover:underline">อ่านต่อ</a>
      </article>

      <!-- Card 3 -->
      <article class="article-card bg-white rounded-2xl shadow p-5 hover:shadow-lg transition" data-category="ยุคกลาง">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Roman_Colosseum_in_Rome_Italy_-_April_2007.jpg/320px-Roman_Colosseum_in_Rome_Italy_-_April_2007.jpg" alt="โรมัน" class="rounded-xl mb-4 w-full h-48 object-cover">
        <h4 class="text-xl font-semibold mb-2">อาณาจักรโรมัน: ความรุ่งเรืองและการล่มสลาย</h4>
        <p class="text-sm text-gray-600 mb-4">เรื่องราวการขยายอำนาจและเหตุการณ์ที่นำไปสู่จุดจบของจักรวรรดิผู้ยิ่งใหญ่</p>
        <a href="#" class="text-indigo-600 font-semibold hover:underline">อ่านต่อ</a>
      </article>

      <!-- Advertisement 2 -->
      <div class="col-span-full bg-yellow-400 p-6 rounded-2xl text-center shadow-lg transform hover:scale-105 transition duration-300">
        <h4 class="text-2xl font-bold mb-4 text-white">โปรโมชั่นพิเศษ / Affiliate</h4>
        <p class="text-white mb-6">สนับสนุนเว็บไซต์และรับข้อเสนอพิเศษเพียงคลิกเดียว</p>
        <a href="https://example-affiliate-link2.com" target="_blank" class="bg-white text-yellow-500 px-6 py-3 rounded-full font-semibold shadow hover:bg-gray-100 transition">ดูข้อเสนอที่นี่</a>
      </div>
    </div>

    <!-- Category Filter -->
    <div class="mt-8 text-center space-x-4">
      <button onclick="filterCategory('ทั้งหมด')" class="px-4 py-2 bg-indigo-600 text-white rounded hover:bg-indigo-700">ทั้งหมด</button>
      <button onclick="filterCategory('โบราณ')" class="px-4 py-2 bg-indigo-600 text-white rounded hover:bg-indigo-700">โบราณ</button>
      <button onclick="filterCategory('ยุคกลาง')" class="px-4 py-2 bg-indigo-600 text-white rounded hover:bg-indigo-700">ยุคกลาง</button>
      <button onclick="filterCategory('ยุคใหม่')" class="px-4 py-2 bg-indigo-600 text-white rounded hover:bg-indigo-700">ยุคใหม่</button>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="bg-gray-200 py-16 px-6">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">เกี่ยวกับเรา</h3>
      <p class="text-gray-700 leading-relaxed">เว็บไซต์นี้สร้างขึ้นเพื่อแบ่งปันเรื่องราวประวัติศาสตร์โลกอย่างเข้าใจง่าย เหมาะสำหรับผู้ที่สนใจเรียนรู้เหตุการณ์สำคัญในอดีตและบทเรียนที่ยังคงมีคุณค่าในปัจจุบัน</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="max-w-4xl mx-auto py-16 px-6">
    <h3 class="text-3xl font-bold mb-6 text-center">ติดต่อเรา</h3>
    <form class="bg-white p-6 rounded-2xl shadow-md space-y-4">
      <input type="text" placeholder="ชื่อของคุณ" class="w-full p-3 border rounded-xl">
      <input type="email" placeholder="อีเมล" class="w-full p-3 border rounded-xl">
      <textarea placeholder="ข้อความ" rows="4" class="w-full p-3 border rounded-xl"></textarea>
      <button type="submit" class="bg-indigo-600 text-white px-6 py-3 rounded-xl hover:bg-indigo-700">ส่งข้อความ</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-indigo-700 text-white text-center py-6">
    <p>&copy; 2025 ไทม์ไลน์โลก | WorldTimeline</p>
  </footer>

  <!-- Scripts -->
  <script>
    const searchInput = document.getElementById('search');
    const articles = document.querySelectorAll('.article-card');
    let currentCategory = 'ทั้งหมด';

    function filterArticles() {
      const query = searchInput.value.toLowerCase();
      articles.forEach(article => {
        const title = article.querySelector('h4').textContent.toLowerCase();
        const matchCategory = currentCategory === 'ทั้งหมด' || article.dataset.category === currentCategory;
        const matchSearch = title.includes(query);
        article.style.display = matchCategory && matchSearch ? '' : 'none';
      });
    }

    searchInput.addEventListener('input', filterArticles);

    function filterCategory(category) {
      currentCategory = category;
      filterArticles();
    }
  </script>

</body>
</html>
