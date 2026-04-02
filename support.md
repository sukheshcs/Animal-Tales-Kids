<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Animal Tales Kids Support</title>
  <style>
    :root {
      --peach: #fff5ec;
      --sun: #ffb347;
      --orange: #ff8c42;
      --pink: #ff5a7a;
      --ink: #1f2430;
      --muted: #60697a;
      --card: rgba(255, 255, 255, 0.88);
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      color: var(--ink);
      background:
        radial-gradient(circle at top left, rgba(255, 179, 71, 0.35), transparent 35%),
        radial-gradient(circle at top right, rgba(255, 90, 122, 0.22), transparent 30%),
        linear-gradient(180deg, #fff7f0 0%, #fff3f7 100%);
    }

    .wrap {
      max-width: 860px;
      margin: 0 auto;
      padding: 48px 20px 72px;
    }

    .hero,
    .card {
      background: var(--card);
      border: 1px solid rgba(255, 255, 255, 0.7);
      border-radius: 28px;
      box-shadow: 0 18px 60px rgba(255, 140, 66, 0.12);
      backdrop-filter: blur(8px);
    }

    .hero {
      padding: 36px 32px;
      margin-bottom: 24px;
    }

    .badge {
      display: inline-block;
      padding: 8px 14px;
      border-radius: 999px;
      background: linear-gradient(135deg, var(--sun), var(--orange));
      color: white;
      font-weight: 700;
      font-size: 13px;
      letter-spacing: 0.02em;
    }

    h1 {
      margin: 16px 0 12px;
      font-size: clamp(34px, 6vw, 54px);
      line-height: 1.04;
    }

    h2 {
      margin: 0 0 12px;
      font-size: 24px;
    }

    p {
      margin: 0;
      line-height: 1.7;
      color: var(--muted);
      font-size: 17px;
    }

    .grid {
      display: grid;
      gap: 20px;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      margin-top: 20px;
    }

    .card {
      padding: 24px;
    }

    ul {
      margin: 12px 0 0;
      padding-left: 18px;
      color: var(--muted);
      line-height: 1.8;
    }

    a {
      color: #db3d67;
      font-weight: 600;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    .footer {
      margin-top: 28px;
      text-align: center;
      color: var(--muted);
      font-size: 14px;
    }
  </style>
</head>
<body>
  <main class="wrap">
    <section class="hero">
      <span class="badge">Animal Tales Kids Support</span>
      <h1>Help for parents, families, and little learners</h1>
      <p>
        Animal Tales Kids is a playful learning app with animal sounds, A-Z vocabulary,
        short moral stories, and simple games for children ages 2 to 8. If you need help,
        want to report an issue, or have a suggestion, contact us using the details below.
      </p>
    </section>

    <section class="grid">
      <article class="card">
        <h2>Contact Support</h2>
        <p>Email: <a href="mailto:support@animaltaleskids.com">support@animaltaleskids.com</a></p>
        <p style="margin-top: 12px;">
          We aim to respond to support questions within 3 business days.
        </p>
      </article>

      <article class="card">
        <h2>What to include</h2>
        <ul>
          <li>Your device model</li>
          <li>iPhone or iPad iOS version</li>
          <li>A short description of the issue</li>
          <li>Screenshots if available</li>
        </ul>
      </article>

      <article class="card">
        <h2>Common help topics</h2>
        <ul>
          <li>Animal sounds not playing</li>
          <li>Story voice playback issues</li>
          <li>App not opening correctly</li>
          <li>Questions about learning content</li>
        </ul>
      </article>

      <article class="card">
        <h2>Privacy</h2>
        <p>
          If you also need a privacy page for App Store Connect, publish a separate
          privacy policy URL alongside this support page.
        </p>
      </article>
    </section>

    <p class="footer">© 2026 Animal Tales Kids. All rights reserved.</p>
  </main>
</body>
</html>
