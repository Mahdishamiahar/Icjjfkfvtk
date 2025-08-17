<!DOCTYPE html><html lang="fa" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>VIPZEXNET — پرسرعت، پایدار و همیشه آنلاین</title>
  <meta name="description" content="VIPZEXNET: سرویس‌های VPN پرسرعت و پایدار برای اندروید، iOS و ویندوز. خرید اشتراک، آموزش راه‌اندازی، پشتیبانی و شبکه‌های اجتماعی." />
  <link rel="preconnect" href="https://cdn.fontcdn.ir" />
  <link href="https://cdn.fontcdn.ir/Font/Persian/Vazirmatn/Vazirmatn.css" rel="stylesheet" />
  <style>
    :root{--bg-dark:#0b0f14;--glass:rgba(255,255,255,.06);--muted:#c9d4e3;--brand:#00c853;--brand-2:#11e070;--danger:#ff5252;--card:rgba(255,255,255,.08);--shadow:0 10px 30px rgba(0,0,0,.35);--radius:16px}
    *{box-sizing:border-box}
    html,body{height:100%}
    body{margin:0;background:var(--bg-dark) url('background.webp') center/cover fixed no-repeat;color:#fff;font-family:'Vazirmatn',system-ui,-apple-system,Segoe UI,Roboto,'Tahoma',sans-serif;line-height:1.85}
    body::before{content:"";position:fixed;inset:0;background:radial-gradient(80% 120% at 50% 0%,rgba(0,200,83,.14),transparent 70%),linear-gradient(180deg,rgba(0,0,0,.55),rgba(0,0,0,.65));z-index:-1}
    a{color:var(--brand)}img{max-width:100%;height:auto}

    /* ناوبری */
    .nav{position:sticky;top:0;z-index:50;backdrop-filter:blur(10px);background:rgba(10,14,18,.6);border-bottom:1px solid rgba(255,255,255,.08)}
    .nav .wrap{max-width:1100px;margin:auto;display:flex;align-items:center;justify-content:space-between;padding:12px 16px}
    .brand{display:flex;align-items:center;gap:10px;font-weight:900;letter-spacing:.2px}
    .brand-logo{width:36px;height:36px;border-radius:10px;background:linear-gradient(135deg,var(--brand),#0affb3);display:grid;place-items:center;box-shadow:var(--shadow)}
    .brand-logo span{font-weight:900;color:#072216}
    .menu{display:flex;gap:8px;align-items:center}
    .menu a{color:#fff;text-decoration:none;padding:8px 12px;border-radius:10px;transition:.25s}
    .menu a:hover{background:var(--glass)}
    .menu .cta{background:var(--brand);color:#062015;font-weight:800}
    .menu .cta:hover{transform:translateY(-1px);background:var(--brand-2)}
    .burger{display:none;cursor:pointer;border:1px solid rgba(255,255,255,.1);padding:8px 10px;border-radius:10px;color:#fff}
    @media (max-width:840px){
      .menu{display:none}.burger{display:block}
      .drawer{position:fixed;inset:56px 0 auto 0;background:rgba(10,14,18,.96);display:none;padding:18px;border-top:1px solid rgba(255,255,255,.08)}
      .drawer a{display:block;padding:12px 10px;border-radius:12px;text-decoration:none;color:#fff}
      .drawer a:hover{background:var(--glass)}
      .drawer.show{display:block}
    }

    /* هیرو */
    .hero{max-width:1100px;margin:24px auto 10px;display:grid;grid-template-columns:1.2fr .8fr;gap:18px;padding:0 16px}
    .hero-card{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:20px;padding:22px;box-shadow:var(--shadow)}
    .hero h1{margin:0 0 10px;font-size:clamp(22px,4.3vw,34px)}
    .hero p.lead{color:var(--muted);margin-top:6px}
    .badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .badge{background:rgba(255,255,255,.08);padding:6px 10px;border-radius:999px;font-size:.9rem}
    .slider{position:relative;overflow:hidden;height:160px;border-radius:16px;border:1px solid rgba(255,255,255,.08)}
    .slides{display:flex;width:300%;height:100%;transition:transform .6s ease}
    .slide{flex:1 0 100%;display:grid;place-items:center;background:linear-gradient(135deg,rgba(0,200,83,.18),rgba(0,200,83,.05));color:#eafff3;text-align:center;padding:16px}
    @media (max-width:940px){.hero{grid-template-columns:1fr}}

    /* عمومی */
    .wrap{max-width:1100px;margin:auto;padding:10px 16px}
    .section-title{font-size:clamp(18px,3.4vw,26px);margin:28px 0 14px}
    .pricing{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px}
    .card{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:20px;padding:18px;box-shadow:var(--shadow);transition:.25s}
    .card:hover{transform:translateY(-3px)}
    .card h3{margin:4px 0 8px}
    .price{font-size:1.25rem;font-weight:900}
    .features{margin:10px 0 14px;color:var(--muted)}
    .btn{display:inline-block;padding:10px 14px;border-radius:12px;background:var(--brand);color:#062015;text-decoration:none;font-weight:800;box-shadow:0 6px 18px rgba(0,200,83,.35)}
    .btn:hover{background:var(--brand-2)}
    .tag{display:inline-block;margin-bottom:8px;padding:6px 10px;border-radius:999px;background:rgba(255,255,255,.08);border:1px dashed rgba(255,255,255,.15)}
    .faq{display:grid;gap:10px}
    .faq-item{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:14px}
    .faq-q{cursor:pointer;padding:14px 16px;font-weight:700;display:flex;justify-content:space-between;align-items:center}
    .faq-a{padding:0 16px 14px;color:var(--muted);display:none}
    .faq-item.open .faq-a{display:block}
    .testimonials{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:14px}
    .review{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:16px;padding:14px}
    .socials{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:12px}
    .soc{background:var(--card);border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:14px;display:flex;gap:10px;align-items:center}
    .soc img{width:36px;height:36px;border-radius:10px}
    .float-chat{position:fixed;bottom:20px;left:20px;background:var(--brand);color:#062015;padding:10px 14px;border-radius:999px;font-weight:800;text-decoration:none;box-shadow:var(--shadow)}
    .float-ai{position:fixed;bottom:76px;left:20px;background:#121820;border:1px solid rgba(255,255,255,.12);color:#fff;padding:10px 14px;border-radius:999px;font-weight:800;text-decoration:none;box-shadow:var(--shadow)}
    .to-top{position:fixed;bottom:20px;right:20px;background:#121820;color:#fff;padding:10px 12px;border-radius:12px;text-decoration:none;border:1px solid rgba(255,255,255,.12)}
    footer{margin:34px 0 20px;text-align:center;color:#b7c5d8}
    footer a{color:#a9ffd0}

    /* چت شبیه ChatGPT */
    .ai-backdrop{position:fixed;inset:0;background:rgba(0,0,0,.75);z-index:100;display:none;justify-content:center;align-items:center;padding:10px}
    .chat-window{background:#0b0f14;color:#fff;width:95%;max-width:720px;height:85%;border-radius:18px;box-shadow:0 12px 40px rgba(0,0,0,.65);display:flex;flex-direction:column;overflow:hidden;border:1px solid rgba(255,255,255,.08)}
    .chat-header{padding:14px 18px;background:#121820;font-weight:800;display:flex;justify-content:space-between;align-items:center;border-bottom:1px solid rgba(255,255,255,.1)}
    .chat-header .title{display:flex;align-items:center;gap:10px}
    .chat-header .status{font-size:.85rem;color:#a8ffcf}
    .chat-messages{flex:1;overflow-y:auto;padding:18px;display:flex;flex-direction:column;gap:12px;scroll-behavior:smooth}
    .bubble{max-width:85%;padding:12px 14px;border-radius:16px;line-height:1.7;white-space:pre-wrap;word-wrap:break-word}
    .bubble.user{align-self:flex-end;background:#00c853;color:#062015;border-top-right-radius:6px}
    .bubble.bot{align-self:flex-start;background:#1c2530;color:#a9ffd0;border-top-left-radius:6px}
    .bubble.error{background:#ff5252;color:#fff}
    .chat-input{border-top:1px solid rgba(255,255,255,.12);padding:10px;background:#121820;display:flex;gap:8px;align-items:flex-end}
    .chat-input textarea{flex:1;background:#1c2530;color:#fff;border:none;outline:none;border-radius:12px;padding:12px 14px;resize:none;max-height:160px}
    .chat-input button{padding:10px 16px;background:#00c853;border:none;color:#062015;font-weight:900;border-radius:12px;cursor:pointer}
    .typing{opacity:.85;font-size:.95rem}
  </style>
</head>
<body>
  <!-- ناوبری -->
  <nav class="nav" aria-label="Main navigation">
    <div class="wrap">
      <a class="brand" href="#home" aria-label="VIPZEXNET Home">
        <div class="brand-logo" aria-hidden="true"><span>V</span></div>
        <span>VIPZEXNET</span>
      </a>
      <div class="menu" role="menubar">
        <a href="#plans" role="menuitem">پلن‌ها</a>
        <a href="#guide" role="menuitem">آموزش</a>
        <a href="#faq" role="menuitem">سوالات</a>
        <a href="#socials" role="menuitem">شبکه‌های اجتماعی</a>
        <a id="open-ai-menu" href="javascript:void(0)" role="menuitem" aria-label="ورود به هوش مصنوعی">🤖 ورود به هوش مصنوعی</a>
        <a class="cta" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید سریع</a>
      </div>
      <button class="burger" id="burger" aria-label="باز کردن منو">☰</button>
    </div>
    <div class="drawer" id="drawer">
      <a href="#plans">پلن‌ها</a>
      <a href="#guide">آموزش</a>
      <a href="#faq">سوالات</a>
      <a href="#socials">شبکه‌های اجتماعی</a>
      <a id="open-ai-drawer" href="javascript:void(0)">🤖 ورود به هوش مصنوعی</a>
      <a class="cta" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید سریع</a>
    </div>
  </nav>

  <!-- هیرو -->
  <section class="hero" id="home">
    <div class="hero-card">
      <h1>🔋 با VIPZEXNET بهترین سرعت VPN را تجربه کنید — بدون قطعی</h1>
      <p class="lead">اتصال پرسرعت، پایدار، بدون محدودیت و قابل استفاده در تمامی دستگاه‌ها</p>
      <div class="badges" aria-label="Supported locations and devices">
        <span class="badge">🌍 لوکیشن‌ها: 🇩🇪 🇦🇪 🇹🇷 🇸🇪 🇫🇷 🇬🇧 🇺🇸</span>
        <span class="badge">📱 دستگاه‌ها: اندروید، iOS، ویندوز</span>
        <span class="badge">🎯 مناسب: اینستاگرام، یوتیوب، گیم</span>
      </div>
      <div class="ticker" style="margin-top:10px">
        <div class="tick">⚡️ آپتایم بالا و پینگ پایین</div>
        <div class="tick">🛡️ پروتکل‌های امن و ضد فیلتر</div>
        <div class="tick">♾️ ترافیک نامحدود</div>
        <div class="tick">🎁 پشتیبانی سریع تلگرام</div>
      </div>
    </div>
    <div class="hero-card">
      <div class="slider" aria-roledescription="carousel">
        <div class="slides" id="slides">
          <div class="slide">🔥 پیشنهاد ویژه: اشتراک سه‌کاربره — فقط <b>۳۰٬۰۰۰</b> تومان</div>
          <div class="slide">🎮 مخصوص گیمرها: مسیرهای کم‌پینگ برای بازی‌های آنلاین</div>
          <div class="slide">🎓 آموزش قدم‌به‌قدم رایگان در آپارات — راه‌اندازی در ۱ دقیقه</div>
        </div>
      </div>
    </div>
  </section>

  <!-- پلن‌ها -->
  <section class="wrap" id="plans">
    <h2 class="section-title">💎 پلن‌های نامحدود</h2>
    <div class="pricing">
      <article class="card">
        <div class="tag">⭐️ تک‌کاربر</div>
        <h3>نامحدود تک‌کاربر</h3>
        <div class="price">۱۰۰,۰۰۰ تومان</div>
        <ul class="features">
          <li>ترافیک نامحدود</li>
          <li>پشتیبانی تلگرام</li>
          <li>مناسب استریم و سوشال</li>
        </ul>
        <a class="btn" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید</a>
      </article>
      <article class="card">
        <div class="tag">⭐️ دوکاربر</div>
        <h3>نامحدود دوکاربر</h3>
        <div class="price">۵۰,۰۰۰ تومان</div>
        <ul class="features">
          <li>فعال روی دو دستگاه</li>
          <li>پشتیبانی تلگرام</li>
          <li>سرعت پایدار</li>
        </ul>
        <a class="btn" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید</a>
      </article>
      <article class="card">
        <div class="tag">⭐️ سه‌کاربر</div>
        <h3>نامحدود سه‌کاربر</h3>
        <div class="price">۳۰,۰۰۰ تومان</div>
        <ul class="features">
          <li>فعال روی سه دستگاه</li>
          <li>پشتیبانی تلگرام</li>
          <li>برای خانواده/تیم کوچک</li>
        </ul>
        <a class="btn" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">خرید</a>
      </article>
    </div>
  </section>

  <!-- آموزش -->
  <section class="wrap" id="guide">
    <h2 class="section-title">🎓 آموزش وارد کردن کانفیگ</h2>
    <p>برای یادگیری نحوه وارد کردن کانفیگ VPN، روی دکمه زیر کلیک کنید. ویدیوها کوتاه و مرحله‌به‌مرحله هستند.</p>
    <p>
      <a class="btn" href="https://www.aparat.com/playlist/21562118" target="_blank" rel="noopener">مشاهده آموزش در آپارات</a>
      <a class="btn" id="copy-buy" href="#" style="background:#1bd67a;margin-right:8px">کپی لینک خرید</a>
    </p>
    <small style="color:#a7b6c9">نکته: برای بهترین سرعت، نزدیک‌ترین لوکیشن به خودتان را انتخاب کنید.</small>
  </section>

  <!-- نظرات -->
  <section class="wrap" id="reviews">
    <h2 class="section-title">💬 نظرات کاربران</h2>
    <div class="testimonials">
      <div class="review">«از وقتی VIPZEXNET گرفتم، پینگ پابجی خیلی بهتر شده. عالی بود!» — <b>سینا</b></div>
      <div class="review">«برای یوتیوب و اینستاگرام بدون قطعی کار می‌کنه. سپاس!» — <b>ریحانه</b></div>
      <div class="review">«نصب راحت، پشتیبانی سریع. پیشنهاد می‌کنم.» — <b>مهدی</b></div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="wrap" id="faq">
    <h2 class="section-title">❓ سوالات متداول</h2>
    <div class="faq">
      <div class="faq-item">
        <div class="faq-q">روی چه دستگاه‌هایی کار می‌کند؟ <span>＋</span></div>
        <div class="faq-a">اندروید، iOS و ویندوز پشتیبانی می‌شود. راهنمای نصب را در بخش آموزش ببینید.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">آیا سرعت محدود می‌شود؟ <span>＋</span></div>
        <div class="faq-a">خیر، پلن‌ها نامحدود هستند و برای استریم و بازی بهینه شده‌اند.</div>
      </div>
      <div class="faq-item">
        <div class="faq-q">پشتیبانی از کجا انجام می‌شود؟ <span>＋</span></div>
        <div class="faq-a">از طریق تلگرام در آیدی <a href="https://t.me/Mahdi_shami" target="_blank" rel="noopener">@Mahdi_shami</a>.</div>
      </div>
    </div>
  </section>

  <!-- شبکه‌های اجتماعی -->
  <section class="wrap" id="socials">
    <h2 class="section-title">🌐 شبکه‌های اجتماعی VIPZEXNET</h2>
    <div class="socials">
      <a class="soc" href="https://t.me/VIPZEXNET" target="_blank" rel="noopener">
        <img src="https://img.icons8.com/fluency/48/telegram-app.png" alt="Telegram"/>
        <div>
          <div><b>کانال تلگرام</b></div>
          <small>آخرین خبرها و تخفیف‌ها</small>
        </div>
      </a>
      <a class="soc" href="https://rubika.ir/VIPZEXNET" target="_blank" rel="noopener">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/66/Rubika_app_logo.png" alt="Rubika"/>
        <div>
          <div><b>کانال روبیکا</b></div>
          <small>اطلاعیه‌ها و پشتیبانی</small>
        </div>
      </a>
      <a class="soc" href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">
        <img src="https://img.icons8.com/fluency/48/online-store.png" alt="Buy"/>
        <div>
          <div><b>خرید سریع</b></div>
          <small>پرداخت امن و فعال‌سازی</small>
        </div>
      </a>
    </div>
  </section>

  <!-- دکمه‌های شناور -->
  <a class="float-ai" id="open-ai-fab" href="javascript:void(0)" aria-label="ورود به هوش مصنوعی">🤖 ورود به هوش مصنوعی</a>
  <a class="float-chat" href="https://t.me/Mahdi_shami" target="_blank" rel="noopener" aria-label="پشتیبانی تلگرام">💬 پشتیبانی</a>
  <a class="to-top" href="#home" aria-label="بازگشت به بالا">↑</a>

  <!-- فوتر -->
  <footer>
    <p>پشتیبانی در تلگرام: <a href="https://t.me/Mahdi_shami" target="_blank" rel="noopener">@Mahdi_shami</a></p>
    <p>خرید از طریق روبیکا: <a href="https://rubika.ir/Mahdi_shami89" target="_blank" rel="noopener">@Mahdi_shami89</a></p>
    <p>کانال روبیکا: <a href="https://rubika.ir/VIPZEXNET" target="_blank" rel="noopener">@VIPZEXNET</a> — کانال تلگرام: <a href="https://t.me/VIPZEXNET" target="_blank" rel="noopener">@VIPZEXNET</a></p>
    <p>© کلیه حقوق این سایت متعلق به VIPZEXNET است.</p>
  </footer>

  <!-- مودال چت شبیه ChatGPT -->
  <div class="ai-backdrop" id="ai-chat-modal" aria-hidden="true">
    <div class="chat-window" role="dialog" aria-modal="true" aria-label="چت با هوش مصنوعی">
      <div class="chat-header">
        <div class="title">🤖 <span>گفت‌وگو با هوش مصنوعی</span> <span class="status">· Chat gpt-3.5</span></div>
        <button id="close-ai-chat" style="border:none;background:none;font-size:20px;cursor:pointer;color:#bbb" aria-label="بستن">✖</button>
      </div>
      <div id="ai-messages" class="chat-messages">
        <div class="bubble bot">👋 سلام! من هوش مصنوعی VIPZEXNET هستم. هر سوالی داری بپرس.</div>
      </div>
      <form id="ai-form" class="chat-input">
        <textarea id="ai-input" rows="1" placeholder="پیام خود را بنویسید... (Enter = ارسال، Shift+Enter = خط جدید)"></textarea>
        <button type="submit">ارسال</button>
      </form>
    </div>
  </div>

  <script>
    /* ناوبری */
    const burger = document.getElementById('burger');
    const drawer = document.getElementById('drawer');
    burger?.addEventListener('click',()=>drawer.classList.toggle('show'));

    /* اسلایدر هیرو */
    const slides = document.getElementById('slides');
    let idx = 0;
    setInterval(()=>{ idx = (idx+1)%3; slides.style.transform = `translateX(-${idx*100}%)`; }, 3500);

    /* FAQ آکاردئون */
    document.querySelectorAll('.faq-q').forEach(q=>{ q.addEventListener('click',()=>{ q.parentElement.classList.toggle('open'); }); });

    /* کپی لینک خرید */
    const copyBtn = document.getElementById('copy-buy');
    copyBtn?.addEventListener('click',(e)=>{
      e.preventDefault();
      const url='https://rubika.ir/Mahdi_shami89';
      navigator.clipboard.writeText(url).then(()=>{
        copyBtn.textContent='کپی شد ✅'; setTimeout(()=>copyBtn.textContent='کپی لینک خرید',1800);
      });
    });

    /* --- چت هوش مصنوعی --- */
    const aiModal = document.getElementById('ai-chat-modal');
    const openAiMenu = document.getElementById('open-ai-menu');
    const openAiDrawer = document.getElementById('open-ai-drawer');
    const openAiFab = document.getElementById('open-ai-fab');
    const closeAiBtn = document.getElementById('close-ai-chat');
    const aiForm = document.getElementById('ai-form');
    const aiInput = document.getElementById('ai-input');
    const aiMessages = document.getElementById('ai-messages');

    function openAIModal(){ aiModal.style.display='flex'; aiModal.setAttribute('aria-hidden','false'); aiInput.focus(); }
    function closeAIModal(){ aiModal.style.display='none'; aiModal.setAttribute('aria-hidden','true'); }

    openAiMenu?.addEventListener('click', openAIModal);
    openAiDrawer?.addEventListener('click', ()=>{ openAIModal(); drawer.classList.remove('show'); });
    openAiFab?.addEventListener('click', openAIModal);
    closeAiBtn?.addEventListener('click', closeAIModal);
    aiModal.addEventListener('click', (e)=>{ if(e.target===aiModal) closeAIModal(); });

    // ارسال با Enter، خط جدید با Shift+Enter
    aiInput.addEventListener('keydown', (e)=>{
      if(e.key==='Enter' && !e.shiftKey){
        e.preventDefault();
        aiForm.requestSubmit();
      }
    });

    // اتوماتیک بزرگ شدن textarea مثل ChatGPT
    function autoGrow(){
      aiInput.style.height = 'auto';
      aiInput.style.height = Math.min(aiInput.scrollHeight, 160) + 'px';
    }
    aiInput.addEventListener('input', autoGrow);

    // افزودن حباب پیام
    function addBubble(text, who='bot', extraClass=''){
      const div = document.createElement('div');
      div.className = `bubble ${who} ${extraClass}`.trim();
      div.textContent = text;
      aiMessages.appendChild(div);
      aiMessages.scrollTop = aiMessages.scrollHeight;
      return div;
    }

    // تایپینگ نمایشی
    function addTyping(){ return addBubble('در حال نوشتن…', 'bot', 'typing'); }
    function stopTyping(node){ if(node){ node.remove(); } }

    aiForm.addEventListener('submit', async (e)=>{
      e.preventDefault();
      const text = aiInput.value.trim();
      if(!text) return;

      addBubble(text, 'user');
      aiInput.value=''; autoGrow();

      const typingNode = addTyping();

      try{
        // فراخوانی وب‌س
