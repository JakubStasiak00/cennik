<template>
  <div class="wrap">
    <header>
      <h1>🍄Serwis urządzeń mobilnych i komputerowych <span class="mushroom">Muchomor🍄</span></h1>
    </header>
    <main>
      <section class="top">
        <h2>
          Cennik napraw
        </h2>
        <p>Ceny mogą różnić się w zależności od modelu sprzętu. W celu adekwatnej wyceny usługi prosimy o kontakt.
        </p>
      </section>
      <section class="general-group">
        <h3>
          Ogólne
        </h3>
        <ul class="general">
          <li><span class="service">Diagnostyka</span> <span class="price">od 50zł</span></li>
          <li><span class="service">Klonowanie dysku</span> <span class="price">od 100zł</span></li>
          <li><span class="service">Instalacja systemu operacyjnego</span> <span class="price">100 zł</span></li>
          <li><span class="service">Skanowanie i usuwanie wirusów</span> <span class="price">60zł</span></li>
          <li><span class="service">Instalacja oprogramowania / sterowników</span> <span class="price">od 30zł</span>
          </li>
          <li><span class="service">Tworzenie kopii zapasowej</span> <span class="price">od 100zł</span></li>
        </ul>
      </section>
      <section class="pc-group">
        <h3>
          Komputery
        </h3>
        <ul class="pc">
          <li><span class="service">Montaż z części klienta</span> <span class="price">od 100zł</span></li>
          <li><span class="service">Wymiana podzespołów (RAM, Dyski, GPU)</span> <span class="price">od 30zł</span></li>
          <li><span class="service">Wymiana podzespołów (CPU, płyta główna, zasilacz)</span> <span class="price">od
              80zł</span></li>
          <li><span class="service">Odkurzanie wnętrza i filtrów</span> <span class="price">od 30zł</span></li>
          <li><span class="service">Czyszczenie i konserwacja chłodzenia</span> <span class="price">od 60zł</span></li>
        </ul>
      </section>
      <section class="laptop-group">
        <h3>
          Laptopy
        </h3>
        <ul class="laptops">
          <li><span class="service">Czyszczenie i konserwacja chłodzenia</span> <span class="price">od 150zł</span></li>
          <li><span class="service">Wymiana komponentów (wentylatory, dyski, RAM etc.)</span> <span class="price">od
              60zł</span></li>
          <li><span class="service">Odkurzanie wnętrza i filtrów</span> <span class="price">od 60zł</span></li>
          <li><span class="service">Wymiana matrycy / taśmy matrycy</span> <span class="price">od 150zł</span></li>
        </ul>
      </section>
      <section class="mobile-group">
        <h3>
          Urządzenia mobilne
        </h3>
        <ul class="mobile">
          <li><span class="service">Wymiana baterii</span> <span class="price">od 100zł</span></li>
          <li><span class="service">Wymiana wyświetlacza</span> <span class="price">od 150zł</span></li>
          <li><span class="service">Wymiana płytki z gniazdem ładowania</span> <span class="price">od 120zł</span></li>
          <li><span class="service">Wymiana kamery</span> <span class="price">od 100zł</span></li>
        </ul>
      </section>

      <aside class="contact">
        <h3>Kontakt</h3>
        <div>☏ tel: +48</div>
        <div>✉ e-mail: </div>
      </aside>
    </main>

    <footer>©Copyright protected</footer>
  </div>
</template>

<script setup>

</script>

<style scoped>
@media screen and (min-width: 1024px) {
  main {
    display: grid;
    gap: 2rem;
    grid-template-areas:
      'top top'
      'gen lap'
      'pc mob'
      'con con'
    ;
  }

  .pc-group {
    grid-area: pc;
  }

  .mobile-group {
    grid-area: mob;
  }

  .general-group {
    grid-area: gen;
  }

  .laptop-group {
    grid-area: lap;
  }

  .top {
    grid-area: top;
  }

  .contact {
    grid-area: con;
  }
}

.wrap {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  min-height: 100vh;
  background: url(../src/assets/mush.jpg);
  border-image: fill 1 linear-gradient(rgba(255, 255, 255, 0.65), rgba(255, 255, 255, 0.65));
}

h1,
h2,
p {
  text-align: center;
  text-wrap: balance;
}

p {
  font-weight: 500;
  margin-bottom: 1rem;
  font-size: 0.8rem;
}

h1,
h2,
h3 {
  text-transform: uppercase;
}

h3 {
  border-bottom: 3px solid rgb(255, 218, 163);
  padding-left: 0.3rem;
  padding-bottom: 0.7rem;
  margin: 2rem 0 0.3rem;
}

header {
  padding-top: 1rem;
  margin-bottom: 2rem;
  width: min(90%, 800px);
  margin-inline: auto;
}

main {
  background-color: rgb(255, 247, 235);
  width: min(90%, 1200px);
  margin-inline: auto;
  padding: 2rem 1rem;
  border-radius: 1rem;
}

footer {
  text-align: center;
  padding-top: 1rem;
  padding-bottom: 0.5rem;
}

li {
  width: 100%;
  display: flex;
  justify-content: space-between;
  border-bottom: 2px dashed rgb(255, 218, 163);
  padding-block: 0.7rem;
}

span:not(.mushroom) {
  flex: 1;
}

.mushroom {
  color: rgb(255, 100, 100);
}

.price {
  text-align: right;
}
</style>
