<section class="hero card">
  <div class="hero-copy">
    <h1>
      Øvelser i virkelighet
      <span class="hero-subtitle">om stillhet, kropp og samkjærlighet</span>
    </h1>
    <p class="lead">
      Mikael Nordgard-Melander tilbyr mindfulness-veiledning med ro, nærvær og et tempo som er
      tilpasset deg.
    </p>
    <div class="actions">
      <a class="btn primary" href="/about">Les mer om meg</a>
      <a class="btn ghost" href="mailto:mindful.tromso@gmail.com">Send e-post</a>
    </div>
  </div>
</section>

<section class="hero-details">
  <aside class="hero-note card">
    <p class="note-title">Nærvær i praksis</p>
    <ul>
      <li>1:1-veiledning i trygt tempo</li>
      <li>Små grupper i Tromsø</li>
      <li>Digitale timer etter avtale</li>
    </ul>
  </aside>
</section>

<section class="offerings">
  <article class="card offer">
    <h2>Hva du kan forvente</h2>
    <ul class="offer-list">
      <li>Å observere tanker, følelser og kroppslige signaler uten å dømme dem.</li>
      <li>Å stoppe opp før automatiske reaksjoner tar over.</li>
      <li>Å møte det som oppstår med mer aksept, klarhet og bevissthet.</li>
    </ul>
  </article>

  <article class="card offer">
    <h2>Hvem det passer for</h2>
    <ul class="offer-list">
      <li>For deg som kjenner på uro, stress eller indre spenning i hverdagen.</li>
      <li>For deg som ønsker å forstå reaksjonene dine bedre før du handler.</li>
      <li>For deg som søker mer ro, balanse og tilstedeværelse i livet.</li>
    </ul>
  </article>

  <article class="card offer">
    <h2>Ta kontakt</h2>
    <p>
      Start med en uforpliktende melding på
      <a class="email-link" href="mailto:mindful.tromso@gmail.com">mindful.tromso@gmail.com</a>.
    </p>
  </article>
</section>

<style>
  .hero {
    position: relative;
    display: grid;
    grid-template-columns: minmax(0, 1.05fr) minmax(180px, 1fr);
    gap: 0.8rem;
    padding: clamp(1.1rem, 2.5vw, 1.6rem);
    overflow: hidden;
    background:
      linear-gradient(90deg, rgba(247, 248, 245, 0.78) 0%, rgba(247, 248, 245, 0.5) 40%, rgba(247, 248, 245, 0.14) 66%, rgba(247, 248, 245, 0.02) 100%),
      url('/Start.jpeg') 82% center / cover no-repeat;
  }

  .hero-copy {
    display: grid;
    gap: 0;
    max-width: 34rem;
    padding: 1.1rem;
    border-radius: 10px;
    background: rgba(252, 252, 251, 0.78);
    backdrop-filter: blur(2px);
  }

  .hero-details {
    margin-top: 0.9rem;
  }

  h1 {
    margin: 0;
    font-size: clamp(1.8rem, 4.2vw, 2.8rem);
    line-height: 1.12;
    max-width: 17ch;
  }

  .hero-subtitle {
    display: block;
    margin-top: 0.45rem;
    font-size: clamp(1rem, 2vw, 1.2rem);
    font-weight: 500;
    line-height: 1.3;
    color: var(--muted);
  }

  .lead {
    margin: 1.35rem 0 0;
    color: var(--muted);
    max-width: 56ch;
  }

  .actions {
    margin-top: 1.3rem;
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
  }

  .hero-note {
    border-radius: 12px;
    background: rgba(255, 255, 255, 0.9);
    padding: 1rem;
    backdrop-filter: blur(1px);
    box-shadow: 0 10px 24px rgba(20, 30, 24, 0.08);
  }

  .note-title {
    margin: 0;
    font-weight: 700;
    color: var(--accent);
  }

  .hero-note ul {
    margin: 0.7rem 0 0;
    padding-left: 1.1rem;
    color: var(--muted);
  }

  .hero-note li + li {
    margin-top: 0.3rem;
  }

  .offerings {
    margin-top: 1rem;
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.75rem;
  }

  .offer {
    padding: 0.95rem;
  }

  .offer h2 {
    margin: 0;
    font-size: 1.05rem;
  }

  .offer p {
    margin: 0.55rem 0 0;
    color: var(--muted);
  }

  .offer-list {
    margin: 0.65rem 0 0;
    padding-left: 1.1rem;
    color: var(--muted);
  }

  .offer-list li + li {
    margin-top: 0.4rem;
  }

  .email-link {
    color: var(--accent);
    font-weight: 700;
  }

  @media (max-width: 920px) {
    .hero {
      grid-template-columns: 1fr;
      background:
        linear-gradient(180deg, rgba(247, 248, 245, 0.8), rgba(247, 248, 245, 0.5)),
        url('/Start.jpeg') 72% center / cover no-repeat;
    }

    .hero-copy {
      max-width: none;
    }

    .offerings {
      grid-template-columns: 1fr;
    }
  }
</style>
