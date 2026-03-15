<section class="about-head card">
  <div class="about-copy">
    <p class="kicker">Om meg</p>
    <h1>Mikael Nordgard-Melander</h1>
    <p class="role">Mindfulness instruktør under utdanning</p>
    <p class="lead">Du er ikke her for å være perfekt, du er her for å være hel, da er du perfekt.</p>
  </div>
  <img class="portrait" src="/Portrett.jpg" alt="Portrett av Mikael Nordgard-Melander" />
</section>

<section class="about-grid">
  <article class="card block">
    <h2>Om meg</h2>
    <p>
      Eg kommer opprinnelig fra Sverige, men bor i dag på familiegården til min sambo i vakre
      arktiske omgivelser mellom fjord og fjell utenfor Tromsø. Sammen driver vi gården, hvor
      naturen, dyrene og årstidene setter rytmen for hverdagen.
    </p>
  </article>

  <article class="card block">
    <h2>Min tilnærming</h2>
    <p>
      Gjennom mindfulness ønsker jeg å skape et rom hvor mennesker kan senke tempoet, finne ro og
      bli mer til stede i egne liv. For meg handler mindfulness om å møte livet slik det er, med
      nysgjerrighet, vennlighet og aksept.
    </p>
    <p>
      Jeg er opptatt av å formidle en jordnær og tilgjengelig tilnærming til mindfulness,
      inspirert av naturen, stillheten og rytmen i livet på gården. Mitt ønske er å støtte
      mennesker i å finne mer balanse, ro og tilstedeværelse i hverdagen.
    </p>
    <a class="btn ghost method-link" href="/about/min-metod">Les mer om min metode</a>
  </article>

  <article class="card block">
    <h2>Hvordan jeg jobber</h2>
    <ul>
      <li>Trygt og rolig tempo, tilpasset deg</li>
      <li>Enkle ovelser du kan bruke i hverdagen</li>
      <li>Fokus på pust, kropp og nærvær</li>
    </ul>
  </article>

  <article class="card block practical">
    <h2>Praktisk informasjon</h2>
    <p>Format: 1:1-veiledning eller små grupper</p>
    <p>Sted: Tromsø / digitalt etter avtale</p>
    <p>Pris: 850.- / 60 min</p>
    <a class="btn primary" href="mailto:mindful.tromso@gmail.com">Send e-post</a>
  </article>
</section>

<style>
  .about-head {
    display: grid;
    grid-template-columns: 1.05fr 0.95fr;
    gap: 0.8rem;
    padding: clamp(1.1rem, 2.5vw, 1.6rem);
    align-items: center;
  }

  .kicker {
    margin: 0;
    text-transform: uppercase;
    letter-spacing: 0.12em;
    font-size: 0.78rem;
    font-weight: 700;
    color: var(--accent);
  }

  h1 {
    margin: 0.45rem 0 0;
    font-size: clamp(1.7rem, 4.2vw, 2.5rem);
    line-height: 1.12;
  }

  .role {
    margin: 0.4rem 0 0;
    color: var(--accent);
    font-weight: 650;
  }

  .lead {
    margin: 0.9rem 0 0;
    color: var(--muted);
  }

  .portrait {
    width: 100%;
    border-radius: 10px;
    border: 1px solid var(--line);
    box-shadow: var(--shadow);
  }

  .about-grid {
    margin-top: 1rem;
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.75rem;
  }

  .block {
    padding: 0.95rem;
  }

  .block h2 {
    margin: 0;
    font-size: 1.05rem;
  }

  .block p {
    margin: 0.6rem 0 0;
    color: var(--muted);
  }

  ul {
    margin: 0.65rem 0 0;
    padding-left: 1.1rem;
    color: var(--muted);
  }

  li + li {
    margin-top: 0.32rem;
  }

  .practical .btn {
    margin-top: 0.8rem;
  }

  .method-link {
    margin-top: 0.8rem;
  }

  @media (max-width: 920px) {
    .about-head {
      grid-template-columns: 1fr;
    }

    .about-grid {
      grid-template-columns: 1fr;
    }
  }
</style>
