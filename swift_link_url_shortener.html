<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SwiftLink | URL Shortener</title>

  <!-- Google Font -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg-main: #0a0f2c;
      --glass-bg: rgba(255, 255, 255, 0.12);
      --glass-border: rgba(255, 255, 255, 0.25);
      --accent-gradient: linear-gradient(135deg, #7f5cff, #35c6ff);
      --text-main: #ffffff;
      --text-muted: #c9c9d6;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: radial-gradient(circle at top, #141b4d, var(--bg-main));
      color: var(--text-main);
      line-height: 1.6;
    }

    /* Header */
    header {
      position: sticky;
      top: 0;
      z-index: 1000;
      backdrop-filter: blur(14px);
      background: rgba(10, 15, 44, 0.6);
      border-bottom: 1px solid var(--glass-border);
    }

    .nav {
      max-width: 1200px;
      margin: auto;
      padding: 16px 24px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 22px;
      font-weight: 700;
      background: var(--accent-gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .nav ul {
      display: flex;
      gap: 24px;
      list-style: none;
    }

    .nav a {
      color: var(--text-muted);
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    .nav a:hover {
      color: #ffffff;
    }

    /* Hero Section */
    .hero {
      min-height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 40px 20px;
    }

    .hero-card {
      max-width: 700px;
      width: 100%;
      padding: 48px 32px;
      background: var(--glass-bg);
      backdrop-filter: blur(20px);
      border-radius: 20px;
      border: 1px solid var(--glass-border);
      text-align: center;
    }

    .hero h1 {
      font-size: 42px;
      font-weight: 700;
      margin-bottom: 12px;
    }

    .hero p {
      color: var(--text-muted);
      margin-bottom: 32px;
      font-size: 18px;
    }

    /* Shortener */
    .shortener {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }

    .shortener input {
      flex: 1;
      min-width: 220px;
      padding: 16px 18px;
      border-radius: 12px;
      border: none;
      outline: none;
      font-size: 16px;
    }

    .shortener button {
      padding: 16px 26px;
      border-radius: 12px;
      border: none;
      background: var(--accent-gradient);
      color: #ffffff;
      font-size: 16px;
      font-weight: 600;
      cursor: pointer;
      transition: transform 0.2s ease, opacity 0.2s ease;
    }

    .shortener button:hover {
      transform: translateY(-2px);
      opacity: 0.9;
    }

    /* Result Box */
    .result {
      margin-top: 24px;
      display: none;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      padding: 16px;
      background: rgba(0, 0, 0, 0.25);
      border-radius: 12px;
      border: 1px solid var(--glass-border);
    }

    .result span {
      word-break: break-all;
      font-size: 15px;
    }

    .copy-btn {
      padding: 10px 16px;
      border-radius: 10px;
      border: none;
      background: var(--accent-gradient);
      color: #fff;
      cursor: pointer;
      font-size: 14px;
    }

    /* Spinner */
    .spinner {
      width: 24px;
      height: 24px;
      border: 3px solid rgba(255, 255, 255, 0.3);
      border-top: 3px solid #ffffff;
      border-radius: 50%;
      animation: spin 1s linear infinite;
      margin: 20px auto 0;
      display: none;
    }

    @keyframes spin {
      to { transform: rotate(360deg); }
    }

    /* Features */
    .features {
      max-width: 1200px;
      margin: 80px auto;
      padding: 0 24px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 24px;
    }

    .feature-card {
      background: var(--glass-bg);
      backdrop-filter: blur(16px);
      border-radius: 16px;
      padding: 32px 24px;
      border: 1px solid var(--glass-border);
      text-align: center;
    }

    .feature-card h3 {
      margin-bottom: 12px;
      font-size: 20px;
    }

    .feature-card p {
      color: var(--text-muted);
      font-size: 15px;
    }

    /* Footer */
    footer {
      background: #06091f;
      padding: 32px 20px;
      text-align: center;
      color: var(--text-muted);
      font-size: 14px;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 32px;
      }

      .hero p {
        font-size: 16px;
      }
    }
  </style>
</head>
<body>

  <header>
    <nav class="nav">
      <div class="logo">SwiftLink</div>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#">Pricing</a></li>
        <li><a href="#">Login</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-card">
      <h1>Shorten Your Links in Seconds</h1>
      <p>Clean, fast, and secure URL shortening for modern creators.</p>

      <div class="shortener">
        <input type="url" id="longUrl" placeholder="Paste your long URL here" />
        <button id="shortenBtn">Shorten</button>
      </div>

      <div class="spinner" id="spinner"></div>

      <div class="result" id="resultBox">
        <span id="shortUrl"></span>
        <button class="copy-btn" id="copyBtn">Copy</button>
      </div>
    </div>
  </section>

  <section class="features" id="features">
    <div class="feature-card">
      <h3>⚡ Speed</h3>
      <p>Instant link shortening with global edge performance.</p>
    </div>
    <div class="feature-card">
      <h3>🔒 Security</h3>
      <p>Safe and reliable links with HTTPS protection.</p>
    </div>
    <div class="feature-card">
      <h3>📊 Analytics</h3>
      <p>Track clicks and performance with clear insights.</p>
    </div>
  </section>

  <footer>
    <p>© 2026 SwiftLink. All rights reserved.</p>
  </footer>

  <script>
    const shortenBtn = document.getElementById('shortenBtn');
    const longUrlInput = document.getElementById('longUrl');
    const resultBox = document.getElementById('resultBox');
    const shortUrlSpan = document.getElementById('shortUrl');
    const copyBtn = document.getElementById('copyBtn');
    const spinner = document.getElementById('spinner');

    function isValidUrl(url) {
      try {
        new URL(url);
        return true;
      } catch {
        return false;
      }
    }

    shortenBtn.addEventListener('click', async () => {
      const longUrl = longUrlInput.value.trim();

      if (!isValidUrl(longUrl)) {
        alert('Please enter a valid URL');
        return;
      }

      spinner.style.display = 'block';
      resultBox.style.display = 'none';

      try {
        const response = await fetch('https://cleanuri.com/api/v1/shorten', {
          method: 'POST',
          headers: { 'Content-Type': 'application/x-www-form-urlencoded' },
          body: `url=${encodeURIComponent(longUrl)}`
        });

        const data = await response.json();
        spinner.style.display = 'none';

        if (data.result_url) {
          shortUrlSpan.textContent = data.result_url;
          resultBox.style.display = 'flex';
        } else {
          alert('Failed to shorten URL');
        }
      } catch (error) {
        spinner.style.display = 'none';
        alert('Error connecting to the API');
      }
    });

    copyBtn.addEventListener('click', () => {
      navigator.clipboard.writeText(shortUrlSpan.textContent);
      copyBtn.textContent = 'Copied';
      setTimeout(() => copyBtn.textContent = 'Copy', 1500);
    });
  </script>

</body>
</html>
