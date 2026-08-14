<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>EVM Wallet Suite</title>
  <style>
    :root { color-scheme: dark; --bg:#0b1220; --panel:#111c31; --panel2:#172642; --text:#eef4ff; --muted:#a9b8d2; --accent:#61dafb; --accent2:#8b7cff; --border:#2b3b5c; }
    * { box-sizing: border-box; }
    body { margin:0; font-family:Arial,"Segoe UI",Tahoma,sans-serif; background:linear-gradient(135deg,#09111f,#111d35 55%,#17143a); color:var(--text); line-height:1.8; }
    .container { width:min(1080px,calc(100% - 32px)); margin:auto; }
    header { padding:72px 0 48px; text-align:center; }
    .badge { display:inline-block; padding:5px 14px; border:1px solid #36527e; border-radius:999px; color:var(--accent); background:#10213b; font-size:.9rem; }
    h1 { margin:16px 0 8px; font-size:clamp(2.1rem,5vw,4rem); letter-spacing:-1px; }
    .lead { max-width:720px; margin:auto; color:var(--muted); font-size:1.1rem; }
    .actions { display:flex; gap:12px; justify-content:center; flex-wrap:wrap; margin-top:28px; }
    a.button { display:inline-block; padding:11px 18px; border-radius:10px; text-decoration:none; color:#06111e; background:var(--accent); font-weight:700; transition:.2s; }
    a.button.secondary { color:var(--text); background:var(--panel2); border:1px solid var(--border); }
    a.button:hover { transform:translateY(-2px); filter:brightness(1.1); }
    main { padding-bottom:50px; }
    section { background:rgba(17,28,49,.88); border:1px solid var(--border); border-radius:18px; padding:28px; margin:20px 0; box-shadow:0 12px 40px #0002; }
    h2 { margin-top:0; color:var(--accent); }
    table { width:100%; border-collapse:collapse; margin-top:16px; overflow:hidden; }
    th,td { text-align:right; padding:14px; border-bottom:1px solid var(--border); vertical-align:top; }
    th { color:#d7e6ff; background:#192945; }
    td { color:var(--muted); }
    td:first-child { color:var(--text); font-weight:700; direction:ltr; text-align:left; }
    a { color:var(--accent); }
    .cards { display:grid; grid-template-columns:repeat(auto-fit,minmax(210px,1fr)); gap:14px; }
    .card { display:block; text-decoration:none; color:var(--text); background:var(--panel2); border:1px solid var(--border); border-radius:13px; padding:18px; transition:.2s; }
    .card:hover { border-color:var(--accent); transform:translateY(-3px); }
    .card strong { display:block; color:var(--accent); margin-bottom:5px; }
    blockquote { margin:20px 0 0; padding:14px 18px; border-right:4px solid #efb84b; background:#302917; color:#f5ddb0; border-radius:8px; }
    code { direction:ltr; display:inline-block; background:#0a1324; color:#b8d8ff; padding:2px 7px; border-radius:5px; }
    pre { direction:ltr; text-align:left; overflow:auto; background:#08101d; padding:18px; border:1px solid var(--border); border-radius:10px; color:#c9dcf7; }
    footer { text-align:center; color:var(--muted); padding:28px 0 45px; font-size:.9rem; }
    @media (max-width:650px) { section { padding:20px 16px; } th,td { padding:10px 7px; font-size:.9rem; } }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <span class="badge">EVM Wallet Suite</span>
      <h1>مجموعة محافظ EVM</h1>
      <p class="lead">واجهات محافظ رقمية تعمل مع شبكات Ethereum Virtual Machine، مع صفحات ويب جاهزة للتجربة ونسخ Android قابلة للتنزيل.</p>
      <div class="actions">
        <a class="button" href="evm.html">فتح محفظة EVM</a>
        <a class="button secondary" href="wallet.html">المحفظة متعددة الشبكات</a>
        <a class="button secondary" href="vault.html">فتح EVM Vault</a>
      </div>
    </div>
  </header>

  <main class="container">
    <section>
      <h2>نظرة عامة</h2>
      <p>يضم هذا المشروع مجموعة من الواجهات والتطبيقات المرتبطة بالمحافظ الرقمية وشبكات EVM. يمكنك فتح صفحات HTML من المتصفح أو تنزيل ملفات APK وتثبيتها على جهاز Android.</p>
    </section>

    <section>
      <h2>محتويات المشروع</h2>
      <table>
        <thead><tr><th>الملف</th><th>الوصف</th><th>الوصول</th></tr></thead>
        <tbody>
          <tr><td>evm.html</td><td>واجهة محفظة متعددة الشبكات للاستخدام من المتصفح.</td><td><a href="evm.html">فتح الصفحة</a></td></tr>
          <tr><td>wallet.html</td><td>واجهة محفظة متعددة الشبكات بديلة.</td><td><a href="wallet.html">فتح الصفحة</a></td></tr>
          <tr><td>vault.html</td><td>واجهة EVM Vault لمحفظة محلية.</td><td><a href="vault.html">فتح الصفحة</a></td></tr>
          <tr><td>evm.apk</td><td>تطبيق Android لمحفظة EVM.</td><td><a href="evm.apk" download>تنزيل التطبيق</a></td></tr>
          <tr><td>vault.apk</td><td>تطبيق Android الخاص بـ EVM Vault.</td><td><a href="vault.apk" download>تنزيل التطبيق</a></td></tr>
        </tbody>
      </table>
    </section>

    <section>
      <h2>الوصول السريع</h2>
      <div class="cards">
        <a class="card" href="evm.html"><strong>محفظة EVM</strong><span>فتح الواجهة الأساسية في المتصفح.</span></a>
        <a class="card" href="wallet.html"><strong>Wallet</strong><span>فتح واجهة المحفظة متعددة الشبكات.</span></a>
        <a class="card" href="vault.html"><strong>EVM Vault</strong><span>فتح واجهة الـ Vault المحلية.</span></a>
        <a class="card" href="evm.apk" download><strong>تحميل EVM APK</strong><span>تنزيل نسخة Android الأساسية.</span></a>
        <a class="card" href="vault.apk" download><strong>تحميل Vault APK</strong><span>تنزيل نسخة Android الخاصة بالـ Vault.</span></a>
      </div>
    </section>

    <section>
      <h2>التثبيت على Android</h2>
      <p>نزّل ملف APK المطلوب إلى جهازك، ثم افتحه واسمح بالتثبيت من مصدر خارجي عند طلب النظام. استخدم <code>evm.apk</code> للمحفظة الأساسية أو <code>vault.apk</code> لنسخة EVM Vault.</p>
      <blockquote><strong>تنبيه أمني:</strong> لا تستخدم محفظة فعلية أو تستورد مفاتيح خاصة قبل مراجعة الكود والتأكد من مصدر الملفات وسلامتها. لا تشارك عبارة الاسترداد أو المفتاح الخاص مع أي شخص.</blockquote>
    </section>

    <section>
      <h2>بنية المشروع</h2>
      <pre>.
├── evm.html       # واجهة محفظة EVM
├── wallet.html    # واجهة محفظة متعددة الشبكات
├── vault.html     # واجهة EVM Vault المحلية
├── evm.apk        # تطبيق Android للمحفظة
├── vault.apk      # تطبيق Android للـ Vault
└── README.html    # صفحة التوثيق هذه</pre>
    </section>
  </main>

  <footer>ملف HTML مستقل — يمكنك فتحه مباشرة بالنقر عليه في جهازك.</footer>
</body>
</html>
