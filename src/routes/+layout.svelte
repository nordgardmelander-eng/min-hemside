<script>
  import '../app.css';
</script>

<div class="site-shell">
  <header class="site-header">
    <nav class="container nav">
      <a class="logo" href="/">
        <span class="logo-mark">M</span>
        <span>Mikael Nordgard-Melander</span>
      </a>
      <div class="nav-links">
        <a href="/">Hjem</a>
        <a href="/about">Om meg</a>
        <a href="/kommende-events">Aktiviteter</a>
        <a href="mailto:mindful.tromso@gmail.com">Kontakt</a>
      </div>
    </nav>
  </header>

  <main class="container">
    <slot />
  </main>

  <footer class="site-footer">
    <div class="container footer-inner">
      <span>Mikael Nordgard-Melander</span>
      <span>Mindfulness instruktor</span>
    </div>
  </footer>
</div>
