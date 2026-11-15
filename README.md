# abotalal-KSA-Discord
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="theme-color" content="#101923" />
  <title>abotalalKSA</title>

  <style>
    :root {
      --background: #101923;
      --panel: #182531;
      --text: #f5f7fa;
      --muted: #b7c2cc;
      --accent: #c9a96e;
      --border: rgba(255, 255, 255, 0.12);
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      font-family: Tahoma, Arial, sans-serif;
      color: var(--text);
      background:
        radial-gradient(ellipse at 50% 0%, rgba(201, 169, 110, 0.13), transparent 42%),
        var(--background);
      display: flex;
      flex-direction: column;
    }

    header {
      width: min(1100px, 100%);
      margin: 0 auto;
      padding: 26px 24px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 1px solid var(--border);
    }

    .brand {
      color: var(--text);
      font-size: 1.2rem;
      font-weight: 700;
      letter-spacing: 0.3px;
    }

    .brand span {
      color: var(--accent);
    }

    .tag {
      color: var(--muted);
      font-size: 0.9rem;
    }

    main {
      width: min(900px, 100%);
      margin: auto;
      padding: 64px 24px;
      text-align: center;
    }

    .eyebrow {
      display: inline-block;
      margin-bottom: 18px;
      padding: 8px 14px;
      color: var(--accent);
      border: 1px solid rgba(201, 169, 110, 0.35);
      border-radius: 999px;
      font-size: 0.9rem;
    }

    h1 {
      margin: 0;
      font-size: clamp(2rem, 6vw, 3.6rem);
      line-height: 1.35;
    }

    .intro {
      max-width: 580px;
      margin: 18px auto 38px;
      color: var(--muted);
      font-size: 1.05rem;
      line-height: 1.9;
    }

    .actions {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 18px;
      max-width: 650px;
      margin: 0 auto;
    }

    .action {
      min-height: 120px;
      padding: 24px;
      color: var(--text);
      background: linear-gradient(145deg, #1d2b37, var(--panel));
      border: 1px solid var(--border);
      border-radius: 18px;
      text-align: right;
      cursor: not-allowed;
      opacity: 0.82;
    }

    .action strong {
      display: block;
      margin-bottom: 10px;
      font-size: 1.2rem;
    }

    .action span {
      color: var(--muted);
      font-size: 0.9rem;
    }

    .notice {
      max-width: 650px;
      margin: 28px auto 0;
      padding: 14px 18px;
      color: #e4d7bd;
      background: rgba(201, 169, 110, 0.08);
      border: 1px solid rgba(201, 169, 110, 0.25);
      border-radius: 12px;
      font-size: 0.88rem;
      line-height: 1.8;
    }

    footer {
      padding: 20px 24px;
      color: var(--muted);
      border-top: 1px solid var(--border);
      text-align: center;
      font-size: 0.85rem;
    }

    @media (max-width: 600px) {
      header {
        padding: 20px;
      }

      .tag {
        font-size: 0.78rem;
      }

      main {
        padding: 48px 20px;
      }

      .actions {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="brand">abotalal<span>KSA</span></div>
    <div class="tag">صفحة تعريفية مستقلة</div>
  </header>

  <main>
    <div class="eyebrow">مرحبًا بكم</div>
    <h1>الخدمات والطلبات</h1>
    <p class="intro">
      اختر القسم المطلوب للاطلاع عليه. روابط الأقسام غير مفعّلة حاليًا.
    </p>

    <section class="actions" aria-label="الأقسام">
      <button class="action" type="button" disabled>
        <strong>تقديم القضية</strong>
        <span>القسم غير متاح حاليًا</span>
      </button>

      <button class="action" type="button" disabled>
        <strong>تقديم وزارة العدل</strong>
        <span>القسم غير متاح حاليًا</span>
      </button>
    </section>

    <p class="notice">
      تنبيه: هذه صفحة مستقلة وغير رسمية، وليست تابعة لوزارة العدل أو ممثلةً لها.
    </p>
  </main>

  <footer>
    © 2026 abotalalKSA — جميع الحقوق محفوظة
  </footer>
</body>
</html>