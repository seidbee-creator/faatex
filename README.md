[index.html](https://github.com/user-attachments/files/25597852/index.html)
<!doctype html>
<html lang="uz">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>FAATEX MChJ — Buxgalteriya autsorsing xizmatlari</title>
    <meta
      name="description"
      content="FAATEX MChJ tomonidan ko‘rsatiladigan buxgalteriya autsorsing xizmatlari uchun professional va ishonchli landing sahifa. Soliq hisobotlari, kadrlar hisobi, buxgalteriyani tiklash va boshqa xizmatlar."
    />
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
      tailwind.config = {
        theme: {
          extend: {
            colors: {
              navy: "#065f46", // chuqur yashil
              steel: "#00b050", // logo rangiga yaqin och yashil
            },
          },
        },
      };
    </script>
    <link
      rel="icon"
      type="image/png"
      href="assets/faatex-logo.png"
    />
    <!-- AOS (Animate on Scroll) -->
    <link
      rel="stylesheet"
      href="https://unpkg.com/aos@2.3.4/dist/aos.css"
    />
    <script src="https://unpkg.com/aos@2.3.4/dist/aos.js"></script>
    <style>
      body {
        font-family: "Times New Roman", Times, serif;
        font-size: 14px;
      }
    </style>
  </head>
  <body class="bg-slate-50 text-slate-900">
    <!-- Navbar -->
    <header
      class="sticky top-0 z-40 bg-white/80 backdrop-blur border-b border-slate-200"
    >
      <nav
        class="mx-auto flex max-w-6xl items-center justify-between px-4 py-3 sm:px-6 lg:px-8"
      >
        <div class="flex items-center gap-3">
          <a href="#hero" class="flex items-center">
            <img
              src="assets/2 (2).png"
              alt="FAATEX MChJ logotipi"
              class="h-10 w-auto object-contain"
            />
          </a>
          <div class="leading-tight">
            <div class="text-sm font-semibold tracking-tight text-navy">
              FAATEX MChJ
            </div>
            <div class="text-xs text-slate-500">
              Buxgalteriya autsorsing markazi
            </div>
          </div>
        </div>

        <button
          id="mobile-menu-btn"
          class="inline-flex items-center rounded-md border border-slate-200 px-3 py-1.5 text-sm font-medium text-slate-700 shadow-sm hover:bg-slate-50 sm:hidden"
          aria-label="Menyuni ochish"
        >
          <span class="mr-2">Menyu</span>
          <span class="h-4 w-[1.1rem] border-y border-slate-600">
            <span class="block h-[1px] w-full bg-slate-600 translate-y-[5px]"></span>
          </span>
        </button>

        <div
          id="desktop-nav"
          class="hidden items-center gap-8 text-sm font-medium text-slate-700 sm:flex"
        >
          <a href="#services" class="hover:text-navy">Xizmatlar</a>
          <a href="#pricing" class="hover:text-navy">Tariflar</a>
          <a href="#about" class="hover:text-navy">Biz haqimizda</a>
          <a href="#faq" class="hover:text-navy">FAQ</a>
          <a
            href="#contact"
            class="rounded-full bg-steel px-4 py-2 text-sm font-semibold text-white shadow-sm hover:bg-navy"
          >
            Bepul maslahat
          </a>
        </div>
      </nav>

      <!-- Mobile menu -->
      <div
        id="mobile-menu"
        class="hidden border-t border-slate-200 bg-white sm:hidden"
      >
        <div class="mx-auto flex max-w-6xl flex-col space-y-1 px-4 py-3">
          <a href="#services" class="rounded-md px-3 py-2 text-sm font-medium"
            >Xizmatlar</a
          >
          <a href="#pricing" class="rounded-md px-3 py-2 text-sm font-medium"
            >Tariflar</a
          >
          <a href="#about" class="rounded-md px-3 py-2 text-sm font-medium"
            >Biz haqimizda</a
          >
          <a href="#faq" class="rounded-md px-3 py-2 text-sm font-medium"
            >FAQ</a
          >
          <a
            href="#contact"
            class="mt-1 rounded-full bg-steel px-3 py-2 text-sm font-semibold text-center text-white shadow-sm"
          >
            Bepul maslahat
          </a>
        </div>
      </div>
    </header>

    <main class="mx-auto max-w-6xl px-4 sm:px-6 lg:px-8">
      <!-- Hero -->
      <section
        class="grid gap-10 py-14 sm:grid-cols-2 sm:items-center md:py-20"
        id="hero"
      >
        <div data-aos="fade-right">
          <p
            class="inline-flex items-center rounded-full bg-slate-100 px-3 py-1 text-xs font-medium text-navy"
          >
            10+ yillik tajribaga ega mutaxassislar
          </p>
          <h1
            class="mt-4 text-3xl font-extrabold tracking-tight text-slate-900 sm:text-4xl lg:text-5xl"
          >
            Biznesingiz moliya xavfsizligini
            <span class="text-steel">professionallarga</span> topshiring
          </h1>
          <p class="mt-4 text-sm text-slate-600 sm:text-base">
            Soliq, kadrlar va buxgalteriya hisobini to‘liq autsorsingga
            topshiring. Biz hujjatlaringizni tartibga keltiramiz, soliq
            xavflarini minimallashtiramiz va sizni rivojlanishga erkin
            qo‘yib beramiz.
          </p>
          <div class="mt-6 flex flex-wrap items-center gap-3">
            <a
              href="#services"
              class="rounded-full bg-navy px-6 py-2.5 text-sm font-semibold text-white shadow-md hover:bg-steel"
            >
              Xizmatlarni ko‘rish
            </a>
            <a
              href="#calculator"
              class="text-sm font-medium text-navy underline-offset-4 hover:underline"
            >
              Xizmat narxini hisoblash
            </a>
          </div>
          <dl
            class="mt-8 grid grid-cols-3 gap-4 rounded-2xl bg-white p-4 text-xs shadow-sm ring-1 ring-slate-100 sm:text-sm"
          >
            <div>
              <dt class="font-semibold text-slate-700">10+ yil</dt>
              <dd class="text-slate-500">amaliy tajriba</dd>
            </div>
            <div>
              <dt class="font-semibold text-slate-700">500+</dt>
              <dd class="text-slate-500">mamnun mijozlar</dd>
            </div>
            <div>
              <dt class="font-semibold text-slate-700">100%</dt>
              <dd class="text-slate-500">soliq xavfsizligi</dd>
            </div>
          </dl>
        </div>

        <div
          class="relative h-full"
          data-aos="fade-left"
          data-aos-delay="150"
        >
          <div
            class="absolute -inset-4 -z-10 rounded-3xl bg-gradient-to-br from-navy/5 via-steel/5 to-transparent"
          ></div>
          <div
            class="relative rounded-3xl bg-white p-5 shadow-xl ring-1 ring-slate-100"
          >
            <h2 class="text-sm font-semibold text-slate-800">
              Moliyaviy ko‘rsatkichlar
            </h2>
            <p class="mt-2 text-xs text-slate-600">
              Biz xizmatlarimiz orqali soliq yuklamasini, ish haqi fondini va
              hujjatlar aylanishini doimiy nazorat ostida ushlab turamiz.
            </p>
            <div class="mt-4 space-y-3 text-xs">
              <div class="rounded-2xl bg-slate-50 px-3 py-3">
                <p class="font-semibold text-slate-800">Tajribali jamoa</p>
                <p class="mt-1 text-[11px] text-slate-500">
                  10+ yillik tajriba va yuzlab muvaffaqiyatli loyihalar.
                </p>
              </div>
              <div class="rounded-2xl bg-slate-50 px-3 py-3">
                <p class="font-semibold text-slate-800">Xavfsiz hamkorlik</p>
                <p class="mt-1 text-[11px] text-slate-500">
                  Maxfiylik, mas'uliyat va shaffof narx siyosati kafolatlanadi.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Services -->
      <section id="services" class="py-14 md:py-16">
        <div class="flex items-end justify-between gap-4">
          <div data-aos="fade-up">
            <h2 class="text-2xl font-bold tracking-tight text-slate-900">
              Asosiy xizmatlarimiz
            </h2>
            <p class="mt-2 text-sm text-slate-600">
              Biznesingiz uchun to‘liq buxgalteriya, soliq va kadrlar hisobini
              bir joyda jamlaymiz.
            </p>
          </div>
        </div>
        <div
          class="mt-8 grid gap-6 md:grid-cols-2 lg:grid-cols-4"
          data-aos="fade-up"
          data-aos-delay="100"
        >
          <!-- Service cards -->
          <article
            class="flex flex-col rounded-2xl bg-white p-4 shadow-sm ring-1 ring-slate-100"
          >
            <div
              class="mb-3 inline-flex h-9 w-9 items-center justify-center rounded-xl bg-navy/10 text-navy"
            >
              ₮
            </div>
            <h3 class="text-sm font-semibold text-slate-900">
              Soliq hisoboti va optimallashtirish
            </h3>
            <p class="mt-2 text-xs text-slate-600">
              Hisobotlarni o‘z vaqtida topshirish, soliq yuklamasini
              kamaytirish va qonunchilik talablariga to‘liq moslik.
            </p>
          </article>
          <article
            class="flex flex-col rounded-2xl bg-white p-4 shadow-sm ring-1 ring-slate-100"
          >
            <div
              class="mb-3 inline-flex h-9 w-9 items-center justify-center rounded-xl bg-navy/10 text-navy"
            >
              👥
            </div>
            <h3 class="text-sm font-semibold text-slate-900">
              Kadrlar hisobi va ish haqi
            </h3>
            <p class="mt-2 text-xs text-slate-600">
              Mehnat shartnomalari, buyruqlar, ta'tillar va ish haqi
              hisob-kitoblarini to‘liq yuritish.
            </p>
          </article>
          <article
            class="flex flex-col rounded-2xl bg-white p-4 shadow-sm ring-1 ring-slate-100"
          >
            <div
              class="mb-3 inline-flex h-9 w-9 items-center justify-center rounded-xl bg-navy/10 text-navy"
            >
              📚
            </div>
            <h3 class="text-sm font-semibold text-slate-900">
              Buxgalteriyani qayta tiklash
            </h3>
            <p class="mt-2 text-xs text-slate-600">
              Chalkash va to‘liq yuritilmagan hisoblarni tahlil qilish, xatolarni
              tuzatish va tartibga keltirish.
            </p>
          </article>
          <article
            class="flex flex-col rounded-2xl bg-white p-4 shadow-sm ring-1 ring-slate-100"
          >
            <div
              class="mb-3 inline-flex h-9 w-9 items-center justify-center rounded-xl bg-navy/10 text-navy"
            >
              🌍
            </div>
            <h3 class="text-sm font-semibold text-slate-900">
              Tashqi iqtisodiy faoliyat hisobi
            </h3>
            <p class="mt-2 text-xs text-slate-600">
              Eksport-import operatsiyalari, valyuta tushumlari va bojxona
              hujjatlarini to‘g‘ri yuritish.
            </p>
          </article>
        </div>
      </section>

      <!-- Pricing -->
      <section id="pricing" class="py-14 md:py-16">
        <div class="text-center" data-aos="fade-up">
          <h2 class="text-2xl font-bold tracking-tight text-slate-900">
            Ishbilarmonlar uchun mos tariflar
          </h2>
          <p class="mt-2 text-sm text-slate-600">
            Biznes hajmingizga qarab moslashuvchan tariflarni tanlang yoki
            individual taklif so‘rang.
          </p>
        </div>

        <div
          class="mt-8 grid gap-6 md:grid-cols-3"
          data-aos="fade-up"
          data-aos-delay="100"
        >
          <!-- Start -->
          <div
            class="flex flex-col rounded-3xl bg-white p-5 shadow-md ring-1 ring-slate-100"
          >
            <h3 class="text-sm font-semibold text-slate-900">Start</h3>
            <p class="mt-1 text-xs text-slate-500">
              Yakka tartibdagi tadbirkorlar uchun
            </p>
            <p class="mt-4 text-2xl font-bold text-navy">1.2 mln so‘m</p>
            <p class="text-[11px] text-slate-500">oyiga, boshlang‘ich paket</p>
            <ul class="mt-4 space-y-2 text-xs text-slate-700">
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-500">✓</span>
                <span>Yagona soliq va boshqa asosiy hisobotlar</span>
              </li>
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-500">✓</span>
                <span>Oyiga 1 marotaba soliq konsultatsiyasi</span>
              </li>
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-500">✓</span>
                <span>Elektron hujjat almashinuvi</span>
              </li>
            </ul>
            <button
              class="mt-5 rounded-full border border-slate-200 px-4 py-2 text-xs font-semibold text-slate-800 hover:bg-slate-50"
              data-scroll-to="#contact"
            >
              Tarif bo‘yicha so‘rov qoldirish
            </button>
          </div>

          <!-- Biznes (popular) -->
          <div
            class="relative flex flex-col rounded-3xl bg-gradient-to-b from-navy to-steel p-5 text-white shadow-xl ring-2 ring-steel"
          >
            <div
              class="absolute -top-3 right-4 rounded-full bg-amber-400 px-3 py-0.5 text-[10px] font-semibold text-slate-900 shadow-sm"
            >
              Ommabop
            </div>
            <h3 class="text-sm font-semibold">Biznes</h3>
            <p class="mt-1 text-xs text-slate-100">
              MChJ va kichik korxonalar uchun
            </p>
            <p class="mt-4 text-2xl font-bold">2.8 mln so‘m</p>
            <p class="text-[11px] text-slate-100">oyiga, kengaytirilgan paket</p>
            <ul class="mt-4 space-y-2 text-xs text-slate-50">
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-200">✓</span>
                <span>Barcha soliq va moliyaviy hisobotlar to‘liq yuritiladi</span>
              </li>
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-200">✓</span>
                <span>Kadrlar hisobi va ish haqi bo‘yicha xizmatlar</span>
              </li>
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-200">✓</span>
                <span>Auditor va soliq tekshiruvlariga tayyorlov</span>
              </li>
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-200">✓</span>
                <span>Cheklanmagan onlayn konsultatsiyalar</span>
              </li>
            </ul>
            <button
              class="mt-5 rounded-full bg-white px-4 py-2 text-xs font-semibold text-navy shadow-sm hover:bg-amber-50"
              data-scroll-to="#contact"
            >
              Ommabop tarifni tanlash
            </button>
          </div>

          <!-- Premium -->
          <div
            class="flex flex-col rounded-3xl bg-white p-5 shadow-md ring-1 ring-slate-100"
          >
            <h3 class="text-sm font-semibold text-slate-900">Premium</h3>
            <p class="mt-1 text-xs text-slate-500">
              Yirik ishlab chiqarish va eksportyorlar uchun
            </p>
            <p class="mt-4 text-2xl font-bold text-navy">Individual</p>
            <p class="text-[11px] text-slate-500">
              loyihangiz hajmi va murakkabligiga qarab
            </p>
            <ul class="mt-4 space-y-2 text-xs text-slate-700">
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-500">✓</span>
                <span>IFRS elementlari va konsolidatsiya hisobotlari</span>
              </li>
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-500">✓</span>
                <span>Tashqi iqtisodiy faoliyat bo‘yicha to‘liq hamrohlik</span>
              </li>
              <li class="flex items-start gap-2">
                <span class="mt-0.5 text-emerald-500">✓</span>
                <span>Maxsus soliq rejalashtirish va risk-menejment</span>
              </li>
            </ul>
            <button
              class="mt-5 rounded-full border border-slate-200 px-4 py-2 text-xs font-semibold text-slate-800 hover:bg-slate-50"
              data-scroll-to="#contact"
            >
              Individual taklif so‘rash
            </button>
          </div>
        </div>
      </section>

      <!-- Biz haqimizda -->
      <section id="about" class="py-14 md:py-16">
        <div class="grid gap-10 md:grid-cols-2 md:items-center">
          <div data-aos="fade-right">
            <h2 class="text-2xl font-bold tracking-tight text-slate-900">
              Biz haqimizda
            </h2>
            <p class="mt-2 text-sm text-slate-600">
              FAATEX MChJ — buxgalteriya autsorsing markazi bo‘lib, ichki
              buxgalteriya bo‘limiga nisbatan sizga ancha tejamkor, xavfsiz va
              tizimli yechimlarni taklif etadi. Xarajatlarni kamaytirish, risklarni
              bo‘lishish va tajribali mutaxassislar jamoasiga ega bo‘lishingizga
              yordam beramiz.
            </p>
            <dl class="mt-5 space-y-3 text-xs text-slate-700">
              <div class="flex gap-3">
                <dt class="mt-0.5 text-emerald-500">✓</dt>
                <dd>
                  <span class="font-semibold">Ma'lumotlar maxfiyligi</span> –
                  barcha ma'lumotlar shifrlangan va cheklangan kirish bilan
                  saqlanadi.
                </dd>
              </div>
              <div class="flex gap-3">
                <dt class="mt-0.5 text-emerald-500">✓</dt>
                <dd>
                  <span class="font-semibold">Mas'uliyat</span> – soliq
                  tekshiruvlari vaqtida hujjatlar tayyorligi va tushuntirishlarda
                  to‘liq hamrohlik qilamiz.
                </dd>
              </div>
              <div class="flex gap-3">
                <dt class="mt-0.5 text-emerald-500">✓</dt>
                <dd>
                  <span class="font-semibold">Shaffof narxlar</span> – yashirin
                  to‘lovlar va qo‘shimcha kutilmagan xarajatlarsiz.
                </dd>
              </div>
            </dl>
          </div>
          <div data-aos="fade-left" class="space-y-4 text-xs text-slate-600">
            <div
              class="rounded-2xl bg-white p-4 shadow-sm ring-1 ring-slate-100"
            >
              <p class="text-xs font-semibold text-slate-700 uppercase tracking-wide">
                Nega aynan biz?
              </p>
              <p class="mt-2 text-xs text-slate-600">
                Biz soliq va buxgalteriya jarayonlaringizni tizimli boshqarib,
                xatolar va jarimalar xavfini kamaytirishga yordam beramiz.
              </p>
              <div class="mt-4 grid gap-3 text-xs sm:grid-cols-2">
                <div class="rounded-2xl bg-slate-50 px-3 py-3">
                  <p class="font-semibold text-slate-800">Tajribali jamoa</p>
                  <p class="mt-1 text-[11px] text-slate-500">
                    10+ yillik tajriba va yuzlab muvaffaqiyatli loyihalar.
                  </p>
                </div>
                <div class="rounded-2xl bg-slate-50 px-3 py-3">
                  <p class="font-semibold text-slate-800">Xavfsiz hamkorlik</p>
                  <p class="mt-1 text-[11px] text-slate-500">
                    Maxfiylik, mas'uliyat va shaffof narx siyosati kafolatlanadi.
                  </p>
                </div>
              </div>
            </div>
            <div class="flex flex-col gap-4">
              <div
                class="flex-1 rounded-2xl bg-white p-4 text-slate-900 shadow-sm ring-1 ring-slate-100"
              >
                <p class="text-xs font-semibold text-slate-700">
                  Xizmatlarimizni baholang — so‘rovnoma
                </p>
                <p class="mt-2 text-xs text-slate-600">
                  Faoliyatimizni qanday baholaysiz?
                </p>
                <div
                  class="mt-3 flex flex-wrap gap-2 text-[11px]"
                  id="satisfaction-survey"
                >
                  <button
                    type="button"
                    data-survey-option="alo"
                    class="rounded-full border border-slate-200 px-3 py-1 font-medium text-slate-700 hover:border-steel hover:text-steel"
                  >
                    A'lo
                  </button>
                  <button
                    type="button"
                    data-survey-option="yaxshi"
                    class="rounded-full border border-slate-200 px-3 py-1 font-medium text-slate-700 hover:border-steel hover:text-steel"
                  >
                    Yaxshi
                  </button>
                  <button
                    type="button"
                    data-survey-option="qoniqarli"
                    class="rounded-full border border-slate-200 px-3 py-1 font-medium text-slate-700 hover:border-steel hover:text-steel"
                  >
                    Qoniqarli
                  </button>
                  <button
                    type="button"
                    data-survey-option="yomon"
                    class="rounded-full border border-slate-200 px-3 py-1 font-medium text-slate-700 hover:border-steel hover:text-steel"
                  >
                    Yomon
                  </button>
                </div>
                <p
                  id="survey-result"
                  class="mt-2 hidden text-[11px] text-steel"
                ></p>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- FAQ -->
      <section id="faq" class="py-14 md:py-16">
        <div class="max-w-3xl" data-aos="fade-up">
          <h2 class="text-2xl font-bold tracking-tight text-slate-900">
            Ko‘p so‘raladigan savollar
          </h2>
          <p class="mt-2 text-sm text-slate-600">
            Agar savolingizga javob topa olmasangiz, pastdagi forma orqali
            bog‘laning.
          </p>
          <div class="mt-6 space-y-3">
            <!-- FAQ item -->
            <div class="rounded-2xl bg-white p-4 shadow-sm ring-1 ring-slate-100">
              <button
                class="flex w-full items-center justify-between text-left text-sm font-semibold text-slate-900"
                data-faq-toggle
              >
                <span>Nega autsorsing arzonroq?</span>
                <span class="ml-4 text-slate-400" aria-hidden="true">+</span>
              </button>
              <div class="mt-2 hidden text-xs text-slate-600" data-faq-content>
                Ichki buxgalteriya bo‘limi uchun ish haqi, soliqlar, ofis va
                infratuzilma xarajatlari talab etiladi. Autsorsingda esa siz
                faqat xizmat uchun to‘laysiz va qolgan xarajatlarni biz
                qoplaymiz.
              </div>
            </div>
            <div class="rounded-2xl bg-white p-4 shadow-sm ring-1 ring-slate-100">
              <button
                class="flex w-full items-center justify-between text-left text-sm font-semibold text-slate-900"
                data-faq-toggle
              >
                <span>Ma'lumotlar maxfiyligi qanday himoyalanadi?</span>
                <span class="ml-4 text-slate-400" aria-hidden="true">+</span>
              </button>
              <div class="mt-2 hidden text-xs text-slate-600" data-faq-content>
                Biz barcha mijozlar bilan maxfiylik to‘g‘risida kelishuv
                (NDA) tuzamiz, ma'lumotlarni shifrlangan serverlarda saqlaymiz va
                faqat mas'ul mutaxassislar uchun cheklangan kirish huquqini
                taqdim etamiz.
              </div>
            </div>
            <div class="rounded-2xl bg-white p-4 shadow-sm ring-1 ring-slate-100">
              <button
                class="flex w-full items-center justify-between text-left text-sm font-semibold text-slate-900"
                data-faq-toggle
              >
                <span>Soliq tekshiruvi bo‘lsa javobgarlik kimda?</span>
                <span class="ml-4 text-slate-400" aria-hidden="true">+</span>
              </button>
              <div class="mt-2 hidden text-xs text-slate-600" data-faq-content>
                Hisobotlarimizga asoslangan xatoliklar uchun javobgarlikni biz
                o‘z zimmamizga olamiz. Tekshiruv jarayonida hujjatlarni
                tayyorlash, tushuntirishlar berish va hamrohlik qilishni to‘liq
                amalga oshiramiz.
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Contact -->
      <section id="contact" class="pb-16 md:pb-20">
        <div
          class="mx-auto max-w-6xl rounded-3xl bg-slate-900 px-5 py-8 text-slate-50 shadow-xl md:px-8"
          data-aos="fade-up"
        >
          <div class="space-y-4 text-xs text-slate-200">
            <div>
              <p class="text-[11px] uppercase tracking-wide text-slate-400">
                Manzil
              </p>
              <p class="mt-1">
                Toshkent shahri, Yangihayot tumani, Navro'z ko‘chasi, 20-uy
              </p>
              <a
                href="https://maps.google.com"
                target="_blank"
                rel="noreferrer"
                class="mt-1 inline-flex items-center text-[11px] text-steel underline-offset-4 hover:underline"
              >
                Google Maps orqali ko‘rish
              </a>
            </div>
            <div>
              <p class="text-[11px] uppercase tracking-wide text-slate-400">
                Aloqa
              </p>
              <p class="mt-1">Telefon: +998 97 890 50 80</p>
              <p>Telefon: +998 97 420 80 50</p>
              <p class="mt-1">Email: Saidahmad199@gmail.com</p>
            </div>
            <div>
              <p class="text-[11px] uppercase tracking-wide text-slate-400">
                Ijtimoiy tarmoqlar
              </p>
              <div class="mt-1 flex flex-wrap gap-3">
                <a
                  href="https://t.me/"
                  target="_blank"
                  rel="noreferrer"
                  class="inline-flex items-center gap-1 text-[11px] text-slate-200 underline-offset-4 hover:text-steel hover:underline"
                >
                  <span>Telegram</span>
                </a>
                <a
                  href="https://instagram.com/"
                  target="_blank"
                  rel="noreferrer"
                  class="inline-flex items-center gap-1 text-[11px] text-slate-200 underline-offset-4 hover:text-steel hover:underline"
                >
                  <span>Instagram</span>
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer class="border-t border-slate-200 bg-white py-4">
      <div
        class="mx-auto flex max-w-6xl flex-col items-center justify-between gap-2 px-4 text-[11px] text-slate-500 sm:flex-row sm:px-6 lg:px-8"
      >
        <p>© <span id="year"></span> FAATEX MChJ. Barcha huquqlar himoyalangan.</p>
        <p>Made with professional accounting care.</p>
      </div>
    </footer>

    <!-- Simple JS for interactions -->
    <script>
      // Mobile menu
      const mobileBtn = document.getElementById("mobile-menu-btn");
      const mobileMenu = document.getElementById("mobile-menu");
      mobileBtn?.addEventListener("click", () => {
        mobileMenu.classList.toggle("hidden");
      });

      // Smooth scroll buttons
      document.querySelectorAll("[data-scroll-to]").forEach((btn) => {
        btn.addEventListener("click", (e) => {
          e.preventDefault();
          const target = btn.getAttribute("data-scroll-to");
          if (target) {
            document.querySelector(target)?.scrollIntoView({ behavior: "smooth" });
          }
        });
      });

      // Calculator logic (removed form, static display only for now)

      // Lead form
      const leadForm = document.getElementById("lead-form");
      const leadMessage = document.getElementById("lead-message");
      leadForm?.addEventListener("submit", (e) => {
        e.preventDefault();
        leadMessage.classList.remove("hidden");
      });

      // Contact form
      const contactForm = document.getElementById("contact-form");
      const contactMessage = document.getElementById("contact-message");
      contactForm?.addEventListener("submit", (e) => {
        e.preventDefault();
        contactMessage.classList.remove("hidden");
      });

      // FAQ accordion
      document.querySelectorAll("[data-faq-toggle]").forEach((btn) => {
        btn.addEventListener("click", () => {
          const content = btn.parentElement.querySelector("[data-faq-content]");
          const icon = btn.querySelector("span:last-child");
          if (!content) return;
          const isHidden = content.classList.contains("hidden");
          // Close all others
          document.querySelectorAll("[data-faq-content]").forEach((el) => {
            el.classList.add("hidden");
          });
          document
            .querySelectorAll("[data-faq-toggle] span:last-child")
            .forEach((i) => {
              i.textContent = "+";
            });
          // Toggle current
          if (isHidden) {
            content.classList.remove("hidden");
            if (icon) icon.textContent = "−";
          } else {
            content.classList.add("hidden");
            if (icon) icon.textContent = "+";
          }
        });
      });

      // Satisfaction survey
      const surveyContainer = document.getElementById("satisfaction-survey");
      const surveyResult = document.getElementById("survey-result");
      if (surveyContainer) {
        surveyContainer
          .querySelectorAll("button[data-survey-option]")
          .forEach((btn) => {
            btn.addEventListener("click", () => {
              surveyContainer
                .querySelectorAll("button[data-survey-option]")
                .forEach((b) => {
                  b.classList.remove("bg-steel", "text-white", "border-steel");
                });
              btn.classList.add("bg-steel", "text-white", "border-steel");
              if (surveyResult) {
                surveyResult.textContent = `Tanlovingiz uchun rahmat: ${btn.textContent.trim()}.`;
                surveyResult.classList.remove("hidden");
              }
            });
          });
      }

      // Year in footer
      document.getElementById("year").textContent = new Date().getFullYear();

      // Init AOS
      AOS.init({
        duration: 700,
        once: true,
        offset: 80,
      });
    </script>
  </body>
</html>

