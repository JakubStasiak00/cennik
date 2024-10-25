<template>
  <div class="wrap">
    <header>
      <h1>🍄Serwis urządzeń mobilnych i komputerowych Muchomor🍄</h1>
    </header>
    <main>
      <h2>
        Cennik
      </h2>
      <p>*Ceny mogą różnić się w zależności od modelu sprzętu. W celach adekwatnej wyceny usługi prosimy o kontakt*</p>
      <h3>
        Ogólne
      </h3>
      <ul class="general">
        <li>Diagnostyka <span>od 50zł</span></li>
        <li>Klonowanie dysku <span>od 100zł</span></li>
        <li>Instalacja systemu operacyjnego <span>100 zł</span></li>
        <li>Skanowanie i usuwanie wirusów <span>60zł</span></li>
        <li>Instalacja oprogramowania / sterowników <span>od 30zł</span></li>
        <li>Tworzenie kopii zapasowej <span>od 100zł</span></li>
      </ul>
      <h3>
        Komputery
      </h3>
      <ul class="pc">
        <li>Montaż z części klienta <span>od 100zł</span></li>
        <li>Wymiana podzespołów (RAM, Dyski, GPU) <span>od 30zł</span></li>
        <li>Wymiana podzespołów (CPU, płyta główna, zasilacz) <span>od 80zł</span></li>
        <li>Odkurzanie wnętrza i filtrów <span>od 30zł</span></li>
        <li>Czyszczenie i konserwacja chłodzenia <span>od 60zł</span></li>
      </ul>
      <h3>
        Laptopy
      </h3>
      <ul class="laptops">
        <li>Czyszczenie i konserwacja chłodzenia <span>od 150zł</span></li>
        <li>Wymiana komponentów (wentylatory, dyski, RAM etc.) <span>od 60zł</span></li>
        <li>Odkurzanie wnętrza i filtrów <span>od 60zł</span></li>
        <li>wymiana matrycy / taśmy matrycy <span>od 150zł</span></li>
      </ul>
      <h3>
        Urządzenia mobilne
      </h3>
      <ul class="mobile">
        <li>Wymiana baterii <span>od 100zł</span></li>
        <li>Wymiana wyświetlacza <span>od 150zł</span></li>
        <li>Wymiana płytki z gniazdem ładowania <span>od 120zł</span></li>
        <li>Wymiana kamery <span>od 100zł</span></li>
      </ul>
      <aside class="contact">
        <h3>Kontakt</h3>
        <div>tel: +48</div>
        <div>e-mail: </div>
        <div>social media:</div>
      </aside>
    </main>
    <footer>©Copyright protected</footer>
  </div>
</template>

<script setup>

</script>

<style scoped>
.wrap {
  font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  min-height: 100vh;
}

h1,
h2,
p {
  text-align: center;
}

header {
  margin-bottom: 2rem;
}

main {
  background-color: blanchedalmond;
  width: min(90%, 800px);
  margin-inline: auto;
  padding: 2rem 1rem;
}

footer {
  text-align: center;
  padding-top: 1rem;
}
</style>
