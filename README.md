# -DaveThread<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>dave.thread</title>

  <!-- SEO -->
  <meta name="description" content="dave.thread - Powerful business insights and development strategies. Practical threads. Clear solutions. Real results for entrepreneurs and coders." />
  <meta name="keywords" content="business, strategy, development, coding, entrepreneurship, insights" />

  <!-- Open Graph for social sharing -->
  <meta property="og:title" content="dave.thread" />
  <meta property="og:description" content="Solutions. Strategy. Simplicity." />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://dave.thread/" />
  <meta property="og:image" content="https://dave.thread/og-image.png" />

  <!-- Favicon -->
  <link rel="icon" href="favicon.ico" type="image/x-icon" />

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet" />

  <style>
    :root {
      --bg: #ffffff;
      --text: #111111;
      --accent: #000000;
      --gray: #888888;
      --hover-accent: #222222;
    }
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }
    header {
      background: var(--accent);
      color: white;
      padding: 3rem 1rem;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
      letter-spacing: -1px;
    }
    header p {
      font-size: 1.25rem;
      color: #ccc;
    }
    main {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1.5rem;
      flex-grow: 1;
    }
    section {
      margin-bottom: 2.5rem;
    }
    section h2 {
      font-size: 1.75rem;
      margin-bottom: 0.75rem;
      border-bottom: 2px solid #eee;
      padding-bottom: 0.5rem;
    }
    ul {
      list-style-type: none;
      padding-left: 0;
    }
    ul li {
      margin-bottom: 1rem;
      font-weight: 600;
    }
    ul li a {
      color: var(--accent);
      text-decoration: none;
      transition: color 0.3s ease;
      cursor: pointer;
    }
    ul li a:hover,
    ul li a:focus {
      color: var(--hover-accent);
      text-decoration: underline;
      outline: none;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      background-color: #f9f9f9;
      color: var(--gray);
    }
    footer small a {
      color: var(--accent);
      text-decoration: none;
      margin: 0 0.25rem;
      transition: color 0.3s ease;
    }
    footer small a:hover,
    footer small a:focus {
      color: var(--hover-accent);
      text-decoration: underline;
      outline: none;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 2.25rem;
      }
      header p {
        font-size: 1rem;
      }
    }
    /* Back to top button styles */
    #backToTop {
      position: fixed;
      bottom: 2rem;
      right: 2rem;
      background: var(--accent);
      color: white;
      border: none;
      padding: 0.75rem 1rem;
      border-radius: 3px;
      cursor: pointer;
      font-size: 1rem;
      opacity: 0.7;
      transition: opacity 0.3s ease;
      display: none;
      z-index: 1000;
    }
    #backToTop:hover,
    #backToTop:focus {
      opacity: 1;
      outline: none;
    }
  </style>
</head>
<body>
  <header role="banner">
    <h1>dave.thread</h1>
    <p>Solutions. Strategy. Simplicity.</p>
  </header>

  <main role="main">
    <section aria-labelledby="about-title">
      <h2 id="about-title">About</h2>
      <p>dave.thread is your go-to source for powerful business insights and development strategies. Practical threads. Clear solutions. Real results — designed for entrepreneurs, coders, and curious minds.</p>
    </section>

    <section aria-labelledby="latest-title">
      <h2 id="latest-title">Latest Threads</h2>
      <ul>
        <li><a href="#simplify-dev-process" tabindex="0" aria-label="How to simplify your dev process in 3 steps">🧵 How to simplify your dev process in 3 steps</a></li>
        <li><a href="#strategy-clarity" tabindex="0" aria-label="Strategy isn’t complex. It’s clarity in motion.">🧵 Strategy isn’t complex. It’s clarity in motion.</a></li>
        <li><a href="#business-fixes" tabindex="0" aria-label="My 5 go-to fixes for early-stage business chaos">🧵 My 5 go-to fixes for early-stage business chaos</a></li>
      </ul>
    </section>

    <section aria-labelledby="follow-title">
      <h2 id="follow-title">Follow</h2>
      <p>Instagram / X / Threads: <strong>@dave.thread</strong></p>
    </section>

    <section aria-labelledby="contact-title">
      <h2 id="contact-title">Contact</h2>
      <p>Email me at: <a href="mailto:davetiwari084@gmail.com" aria-label="Send email to Dave Tiwari">davetiwari084@gmail.com</a></p>
    </section>
  </main>

  <footer role="contentinfo">
    &copy; 2025 dave.thread. Built for clarity.
    <br />
    <small>
      Follow me on
      <a href="https://instagram.com/dave.thread" target="_blank" rel="noopener noreferrer" aria-label="Instagram">Instagram</a>,
      <a href="https://twitter.com/dave_thread" target="_blank" rel="noopener noreferrer" aria-label="X Twitter">X</a>,
      <a href="https://threads.net/@dave.thread" target="_blank" rel="noopener noreferrer" aria-label="Threads">Threads</a>.
    </small>
  </footer>

  <button id="backToTop" aria-label="Back to top">↑ Top</button>

  <script>
    const backToTopButton = document.getElementById('backToTop');

    window.addEventListener('scroll', () => {
      if (window.scrollY > 300) {
        backToTopButton.style.display = 'block';
      } else {
        backToTopButton.style.display = 'none';
      }
    });

    backToTopButton.addEventListener('click', () => {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    });
  </script>
</body>
</html>
