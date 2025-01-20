<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1.0" name="viewport" />
  <title>شو رايك نتعلم احياء</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Cairo', sans-serif;
    }
    img {
      max-width: 100%;
      height: auto;
    }
    img.lazy {
      opacity: 0;
      transition: opacity 0.3s ease-in-out;
    }
    img.lazy.loaded {
      opacity: 1;
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-900">
  <!-- Header -->
  <header class="bg-blue-600 text-white p-4">
    <div class="container mx-auto flex flex-col md:flex-row justify-between items-center">
      <h1 class="text-2xl font-bold text-center md:text-left">تطبيق تعليمي</h1>
      <nav class="mt-4 md:mt-0">
        <ul class="flex flex-wrap justify-center space-x-4">
          <li><a class="hover:underline" href="#">الرئيسية</a></li>
          <li><a class="hover:underline" href="#lessons">الدروس</a></li>
          <li><a class="hover:underline" href="#exams">الامتحانات</a></li>
          <li><a class="hover:underline" href="#about">عن التطبيق</a></li>
          <li><a class="hover:underline" href="#contact">اتصل بنا</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <main class="container mx-auto p-4">
    <!-- Hero Section -->
    <section class="bg-white p-6 rounded-lg shadow-lg mb-6">
      <div class="flex flex-col md:flex-row items-center">
        <div class="md:w-1/2 text-center md:text-left">
          <h2 class="text-3xl font-bold mb-4">أهلاً وسهلاً في منصة تعليمية تحت إدارة المعلم ياسر أحمد علي - مدرسة عمر بن الخطاب الشاملة لبنين</h2>
          <p class="mb-4">تعلم مع أفضل الدروس والموارد التعليمية المتاحة على الإنترنت.</p>
          <a class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700" href="#lessons">ابدأ الآن</a>
        </div>
        <div class="md:w-1/2 mt-4 md:mt-0">
          <img
            alt="صورة توضيحية لتطبيق تعليمي"
            class="rounded-lg shadow-lg lazy"
            data-src="https://images.unsplash.com/photo-1532094349884-543bc11b234d?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=80"
            width="500"
            height="300"
          />
        </div>
      </div>
    </section>

    <!-- Lessons Section -->
    <section id="lessons" class="mb-6">
      <h2 class="text-2xl font-bold mb-4 text-center md:text-left">الدروس</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
        <!-- درس الأحياء -->
        <div class="bg-white p-4 rounded-lg shadow-lg">
          <img
            alt="درس الأحياء"
            class="rounded-lg mb-4 lazy"
            data-src="https://images.pexels.com/photos/356040/pexels-photo-356040.jpeg?auto=compress&cs=tinysrgb&w=500&h=300&dpr=1"
            width="300"
            height="200"
          />
          <h3 class="text-xl font-bold mb-2">دروس الأحياء</h3>
          <p class="mb-4">تعلم أساسيات الأحياء بطريقة سهلة وممتعة.</p>
          <ul class="list-disc list-inside">
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/watch?v=C10W1x0rYQs&list=PLgnwuP5pmLcZgzdnrCh9hCoF4bHIt3iwg" target="_blank">نانسي المصري - الأحياء</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/watch?v=7PP8FkficA4&list=PLnyQ95yc9e1MHlOIDuRN8N4mTA_lyTaM-" target="_blank">محمد البطاينة - الأحياء</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/watch?v=dH1v7PmmYos&list=PLa8IbBityehG9rG9OPqMCa55EK36C-RFr" target="_blank">محمد القاضي - الأحياء</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/watch?v=pZe-Pdk-9U4&list=PL3WEaKVkVNoIyD072nJdzJMwWECHMv_Y0" target="_blank">معلمة تسنيم - الأحياء</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/@haithamaalblaawe" target="_blank">هيثم البلعاوي - الأحياء</a></li>
          </ul>
        </div>

        <!-- درس الرياضيات -->
        <div class="bg-white p-4 rounded-lg shadow-lg">
          <img
            alt="درس الرياضيات"
            class="rounded-lg mb-4 lazy"
            data-src="https://images.pexels.com/photos/590022/pexels-photo-590022.jpeg?auto=compress&cs=tinysrgb&w=500&h=300&dpr=1"
            width="300"
            height="200"
          />
          <h3 class="text-xl font-bold mb-2">دروس الرياضيات</h3>
          <p class="mb-4">تعلم أساسيات الرياضيات بطريقة سهلة وممتعة.</p>
          <ul class="list-disc list-inside">
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/@thamer.q/playlists" target="_blank">ثامر قدورة - الرياضيات</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/watch?v=kzEKr8ehEoA&list=PLBfTigz4rlOtaKvwesvZpNYQ877khLAWC" target="_blank">محمد عدرة - الرياضيات</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/watch?v=Yl_RXbf55GI&list=PL3dN1bokM0IicqGL7VgAQ-Zej17NRPUf4" target="_blank">البروفسور في الرياضيات</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/watch?v=7ds5Vy3bAuc&list=PLa8IbBityehFaF-sTt1yRGEM7i0JmSGRF" target="_blank">الجينيس التوجيهي - الرياضيات</a></li>
          </ul>
        </div>

        <!-- درس الكيمياء -->
        <div class="bg-white p-4 rounded-lg shadow-lg">
          <img
            alt="درس الكيمياء"
            class="rounded-lg mb-4 lazy"
            data-src="https://images.pexels.com/photos/2280571/pexels-photo-2280571.jpeg?auto=compress&cs=tinysrgb&w=500&h=300&dpr=1"
            width="300"
            height="200"
          />
          <h3 class="text-xl font-bold mb-2">دروس الكيمياء</h3>
          <p class="mb-4">تعلم أساسيات الكيمياء بطريقة سهلة وممتعة.</p>
          <ul class="list-disc list-inside">
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/@ne_jo" target="_blank">نضال الهندي - الكيمياء</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/@MaherNajem/playlists" target="_blank">ماهر نجم - الكيمياء</a></li>
          </ul>
        </div>

        <!-- درس الفيزياء -->
        <div class="bg-white p-4 rounded-lg shadow-lg">
          <img
            alt="درس الفيزياء"
            class="rounded-lg mb-4 lazy"
            data-src="https://images.pexels.com/photos/414579/pexels-photo-414579.jpeg?auto=compress&cs=tinysrgb&w=500&h=300&dpr=1"
            width="300"
            height="200"
          />
          <h3 class="text-xl font-bold mb-2">دروس الفيزياء</h3>
          <p class="mb-4">تعلم أساسيات الفيزياء بطريقة سهلة وممتعة.</p>
          <ul class="list-disc list-inside">
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/watch?v=T66Xi1y02V0&list=PL00YNBO_l9urd8Gn6xzkXktYzQaIvIf6v" target="_blank">ناصر المعدي - الفيزياء</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/watch?v=qDS1EqDvYJc&list=PLVl097IR8SXNdGh6zJl-4XtCCPB2hlWk4" target="_blank">معاذ أمجد - الفيزياء</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/@t.amjaddodeen9025/playlists" target="_blank">امجد دودين - الفيزياء</a></li>
            <li><a class="text-blue-600 hover:underline" href="https://www.youtube.com/@%D9%81%D9%8A%D8%B2%D9%8A%D8%A7%D8%A1%D8%A7%D9%84%D8%AA%D9%88%D8%AC%D9%8A%D9%87%D9%8A-%D9%85%D8%B1%D9%88%D8%A7%D9%86%D9%85%D9%84%D9%88%D8%A7%D9%84%D8%B9-%D8%B28%D9%8A/videos" target="_blank">مروان ملو العين - الفيزياء</a></li>
          </ul>
        </div>

        <!-- المركز الوطني للمناهج المطورة - الصف الثاني عشر العلمي -->
        <div class="bg-white p-4 rounded-lg shadow-lg">
          <img
            alt="المركز الوطني للمناهج المطورة"
            class="rounded-lg mb-4 lazy"
            data-src="https://images.pexels.com/photos/590022/pexels-photo-590022.jpeg?auto=compress&cs=tinysrgb&w=500&h=300&dpr=1"
            width="300"
            height="200"
          />
          <h3 class="text-xl font-bold mb-2">المركز الوطني للمناهج المطورة - الصف الثاني عشر العلمي</h3>
          <p class="mb-4">الوصول إلى المناهج المطورة للصف الثاني عشر العلمي.</p>
          <ul class="list-disc list-inside">
            <li><a class="text-blue-600 hover:underline" href="https://nccd.gov.jo/Ar/Pages/Publications/?type=36" target="_blank">المناهج المطورة - الصف الثاني عشر العلمي</a></li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Exams Section -->
    <section id="exams" class="bg-white p-6 rounded-lg shadow-lg mb-6">
      <h2 class="text-2xl font-bold mb-4 text-center md:text-left">الامتحانات والتمارين</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
        <!-- تمرين الأحياء -->
        <div class="bg-white p-4 rounded-lg shadow-lg">
          <img
            alt="تمرين الأحياء"
            class="rounded-lg mb-4 lazy"
            data-src="https://images.pexels.com/photos/356040/pexels-photo-356040.jpeg?auto=compress&cs=tinysrgb&w=500&h=300&dpr=1"
            width="300"
            height="200"
          />
          <h3 class="text-xl font-bold mb-2">تمارين الأحياء</h3>
          <p class="mb-4">اختبر معرفتك في الأحياء مع هذه التمارين التفاعلية.</p>
          <a class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700" href="#">ابدأ التمرين</a>
        </div>

        <!-- تمرين الرياضيات -->
        <div class="bg-white p-4 rounded-lg shadow-lg">
          <img
            alt="تمرين الرياضيات"
            class="rounded-lg mb-4 lazy"
            data-src="https://images.pexels.com/photos/590022/pexels-photo-590022.jpeg?auto=compress&cs=tinysrgb&w=500&h=300&dpr=1"
            width="300"
            height="200"
          />
          <h3 class="text-xl font-bold mb-2">تمارين الرياضيات</h3>
          <p class="mb-4">اختبر مهاراتك في الرياضيات مع هذه التمارين.</p>
          <a class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700" href="#">ابدأ التمرين</a>
        </div>

        <!-- تمرين التاريخ -->
        <div class="bg-white p-4 rounded-lg shadow-lg">
          <img
            alt="تمرين التاريخ"
            class="rounded-lg mb-4 lazy"
            data-src="https://images.pexels.com/photos/267761/pexels-photo-267761.jpeg?auto=compress&cs=tinysrgb&w=500&h=300&dpr=1"
            width="300"
            height="200"
          />
          <h3 class="text-xl font-bold mb-2">تمارين التاريخ</h3>
          <p class="mb-4">اختبر معرفتك التاريخية مع هذه التمارين.</p>
          <a class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700" href="#">ابدأ التمرين</a>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="bg-white p-6 rounded-lg shadow-lg mb-6">
      <h2 class="text-2xl font-bold mb-4 text-center md:text-left">عن التطبيق</h2>
      <p class="mb-4">تطبيقنا التعليمي مصمم لمساعدتك على التعلم بطرق مبتكرة وسهلة. نحن نقدم مجموعة واسعة من الدروس والموارد التعليمية التي تغطي مختلف المواضيع والمستويات.</p>
      <p>هدفنا هو توفير بيئة تعليمية شاملة تساعدك على تحقيق أهدافك الأكاديمية والشخصية.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-white p-6 rounded-lg shadow-lg">
      <h2 class="text-2xl font-bold mb-4 text-center md:text-left">اتصل بنا</h2>
      <p class="mb-4">للتواصل معنا عبر الواتساب أو الفيسبوك:</p>
      <div class="flex flex-col md:flex-row space-y-4 md:space-y-0 md:space-x-4">
        <a class="bg-green-500 text-white px-4 py-2 rounded hover:bg-green-600 text-center" href="https://wa.me/962788123290" target="_blank">
          <i class="fab fa-whatsapp"></i> تواصل عبر الواتساب
        </a>
        <a class="bg-blue-500 text-white px-4 py-2 rounded hover:bg-blue-600 text-center" href="https://www.facebook.com/yourpage" target="_blank">
          <i class="fab fa-facebook"></i> تابعنا على الفيسبوك
        </a>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="bg-blue-600 text-white p-4 mt-6">
    <div class="container mx-auto text-center">
      <p>© 2023 تطبيق تعليمي. جميع الحقوق محفوظة.</p>
    </div>
  </footer>

  <!-- Lazy Loading Script -->
  <script>
    document.addEventListener("DOMContentLoaded", function() {
      const lazyImages = document.querySelectorAll("img.lazy");

      const lazyLoad = (target) => {
        const io = new IntersectionObserver((entries, observer) => {
          entries.forEach((entry) => {
            if (entry.isIntersecting) {
              const img = entry.target;
              img.src = img.dataset.src;
              img.classList.add("loaded");
              observer.unobserve(img);
            }
          });
        });

        io.observe(target);
      };

      lazyImages.forEach(lazyLoad);
    });
  </script>
</body>
</html>
