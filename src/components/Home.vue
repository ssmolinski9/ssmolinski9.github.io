<template>
  <div class="container mb-5">
    <div class="jumbotron text-center">
      <h1 class="display-4 orange-text">Sebastian Smoliński</h1>
      <p class="lead mt-3">— Strona osobista, doświadczenia, projekty —</p>
      <router-link to="/projects" tag="button" class="btn btn-orange btn-lg mt-4">Zobacz projekty</router-link>
    </div>

    <div class="row mt-5">
      <div class="col-sm-12">
        <h4>O mnie</h4>
        <img src="@/assets/prof.png" class="img-fluid img-thumbnail float-left mr-3 mb-3" alt="Zdjęcie profilowe">

        <p class="text-justify">
          Cześć! Mam na imię Sebastian i pracuję jako młodszy programista głównie w technologiach związanych
          z językiem Java.  Informatyką interesuję się od dzieciństwa, a samym programowaniem od czasów gimnazjalnych.
          Jest to moja główna pasja i całą moją ścieżkę edukacji zaplanowałem w oparciu właśnie o tę dziedzinę.
        </p>
        <p class="text-justify">
          Wiedzę rozwijam przede wszystkim w takich aspektach jak inżynieria oprogramowania, czystość kodu,
          systemy i aplikacje internetowe oraz tematy związane z bazami danych.
          Moimi głównymi językami programowania są Java oraz TypeScript (też JavaScript), jednak jestem otwarty
          na inne rozwiązania i nie boję się dobierać nowych technologii jeśli pasują do projektu.
          Technologicznie bazuję głównie na sprawdzonych frameworkach takich jak Spring, Angular czy VueJS.
        </p>
        <p class="text-justify">
          Poza pracą zawodową staram się rozwijać w projektach hobbistycznych. Próbuję w nich rozwijać zdolności w
          znanych mi już technologiach jak i próbować czegoś zupełnie nowego. W takich mniejszych projektach próbuję
          wdrażać metodyki dobrego zarządzania projektem jak i staram się rozwijać w zarządzaniu małym zespołem.
          Wszystkie ukończone prace zamieszczam na moim <a href="https://github.com/ssmolinski9">GitHubie</a>.
        </p>
        <p class="text-justify">
          Poza informatyką interesuję się przede wszystkim piłką nożną
          (szczególnie biznesowe aspekty zarządzania klubem sportowym). Od dziecka interesuję się także szeroko
          literaturą polską, szczególnie twórczością Stanisława Lema oraz współczesną poezją.
        </p>
      </div>
    </div>

    <div class="row mt-5">
      <div class="col-sm-6 text-center">
        <h2>
          <span class="material-icons">school</span>
        </h2>
        <h4>Szkoła średnia</h4>
        <h5>Technikum w Czarnej Białostockiej</h5>
        <br/>
        <p class="text-justify">
          O profilu technik informatyk. W trakcie edukacji w tej szkole zdobyłem podstawową wiedzę
          oraz praktykę techniczną, która została potwierdzona trzema kwalifikacjami w tym zawodzie
          (E.12, E.13, E.14). W szkole nauczyłem się m.in. o eksploatacji i konserwacji komputerów osobistych
          i urządzeń peryferyjnych, sieciach komputerowych, zarządzaniu serwerami
          (systemy Windows Server oraz dystrybucje linuxowe), zarządzaniu bazami danych,
          oraz o programowaniu prostych skryptów (najczęściej w języku JavaScript).
        </p>
      </div>

      <div class="col-sm-6 text-center">
        <h2>
          <span class="material-icons">school</span>
        </h2>
        <h4>Studia inżynierskie</h4>
        <h5>Politechnika Białostocka</h5>
        <br/>
        <p class="text-justify">
          Ukończyłem kierunek informatyka na Wydziale Informatyki, uzyskałem dyplom inżyniera. Tematem mojej pracy
          dyplomowej było wykonanie aplikacji internetowej dla agencji nieruchomości (Spring i Angular jako baza
          technologiczna). W toku tych studiów posiadłem wiedzę nie tylko o zagadnieniach czysto programistycznych
          (pisanie kodu), ale także o aspektach techniki cyfrowej (jak fizycznie wykonane są układy, jak też jak się
          je programuje), o bezpieczeństwie sieci komputerowych, zarządzaniu w inżynierii programowania, biometrii
          czy sztucznej inteligencji.
        </p>
      </div>
    </div>

    <div class="row mt-5">
      <div class="col-sm-12">
        <div class="card p-3 bg-first">
          <h4 class="text-right">Technologie</h4>
          <div class="card-body">
            <div class="row">
              <div class="col-sm-12 col-md-4">
                <h5 class="text-center">Java</h5>
                <p class="text-justify">
                  Główny język programowania, którego płynnie używam do większości projektów. Używam go także
                  jako główny język w mojej pracy zawodowej. Staram się cały czas pogłębiać wiedzę odnośnie
                  standardowego API Javy, np. analizując kod źródłowy dostępny w JDK. Nie mam także problemów z
                  korzystaniem ze powszechnych wzorców projektowych w tym języku.
                </p>
              </div>
              <div class="col-sm-12 col-md-4">
                <h5 class="text-center">Spring</h5>
                <p class="text-justify">
                  Jeden z najlepiej znanych przeze mnie rozwiązań do budowy aplikacji rozproszonych. Korzystam z
                  niego w pracy zawodowej, prywatnych projektach jak i projektach wykonanych w trakcie studiów
                  (łącznie z aplikacją do pracy inżynierskiej). Szczególnie miałem styczność z tworzeniem rozwiązań
                  opartych o mikroserwisy w tej technologii.
                </p>
              </div>
              <div class="col-sm-12 col-md-4">
                <h5 class="text-center">Angular</h5>
                <p class="text-justify">
                  Do pisania aplikacji front-endowych wybieram zazwyczaj tę technologię, znam ją najbardziej.
                  Szczególnie potrafię pisać aplikacje klienckie do działania z REST API czy tworzyć aplikacje z
                  zaimplementowanymi socketami. W Angularze wykonałem także część frontową aplikacji inżynierskiej.
                </p>
              </div>
              <div class="col-sm-12 col-md-4">
                <h5 class="text-center">Systemy baz danych</h5>
                <p class="text-justify">
                  Potrafię pisać skrypty SQL o średnim stopniu zaawansowania, zwłaszcza na podstawie rozszerzenie
                  PL/SQL. Jeśli chodzi o systemy zarządzania bazą danych, to w najczęściej korzystałem z takich
                  rozwiązań jak bazy Oracle oraz PostgreSQL. Dodatkowo w języku Java swobodnie korzystam z takich
                  rozwiązań jak Hibernate.
                </p>
              </div>
              <div class="col-sm-12 col-md-4">
                <h5 class="text-center">Dev-Ops</h5>
                <p class="text-justify">
                  Głównie w celach automatyzacji zarządzania prywatnymi projektami zapoznałem się z niektórymi
                  narzędziami z rodziny Dev-Ops. Skupiałem się na takich aspektach jak konfigurowanie pipeline
                  Gitlab CI/CD do automatycznego budowania, testowania, kontroli wersji i tworzenia obrazu aplikacji.
                  Dodatkowo znam podstawy Dockera, którego używam w niektórych projektach.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="row mt-5">
      <div class="col-sm-12">
        <h4 class="pb-3">Doświadczenie</h4>
      </div>

      <div class="col-sm-6 text-center">
        <h2>
          <span class="material-icons">store</span>
        </h2>
        <h4>05/2016 – 06/2016</h4>
        <h5>Informatyk w KOLEKTYW / Skrzynka Pomysłów</h5>
        <br/>
        <p class="text-justify">
          W tym białostockim sklepie odbywałem praktyki w ramach zajęć w technikum.
          Byłem odpowiedzialny za wsparcie techniczne, konserwację sprzętu (komputerów osobistych).
          Zajmowałem się też działaniem sklepu w internecie (głównie za pośrednictwem allegro).
          Okazjonalnie także wykonywałem i edytowałem zdjęcia produktów (wykonanie zdjęcia aparatem,
          wycięcie tła i poprawienie kolorów w programie graficznym).
        </p>
      </div>

      <div class="col-sm-6 text-center">
        <h2>
          <span class="material-icons">web</span>
        </h2>
        <h4>07/2018 – 08/2018</h4>
        <h5>Praktykant tester w Transition Technologies</h5>
        <br/>
        <p class="text-justify">
          Podczas moich dwumiesięcznych praktyk zajmowałem się nauką na stanowisku pracy testera aplikacji w
          białostockim oddziale firmy Transition Technologies. Uczestniczyłem w procesie wytwarzania oprogramowania
          (w komercyjnym projekcie), byłem odpowiedzialny głównie za przeprowadzanie testów manualnych.
        </p>
      </div>

      <div class="col-sm-6 text-center">
        <h2>
          <span class="material-icons">important_devices</span>
        </h2>
        <h4>07/2019 – 09/2019</h4>
        <h5>Stażysta programista w Comarch</h5>
        <br/>
        <p class="text-justify">
          Podczas wakacji w 2019 roku odbyłem trzymiesięczny staż w białostockim oddziale Comarch.
          Byłem odpowiedzialny głównie za pisanie kodu źródłowego w języku Java (komercyjne projekty systemów z rodziny
          CRM) oraz pracę z bazami danych w technologii PostgreSQL.
        </p>
      </div>

      <div class="col-sm-6 text-center">
        <h2>
          <span class="material-icons">developer_board</span>
        </h2>
        <h4>10/2019 - 11/2020</h4>
        <h5>Młodszy programista w Comarch</h5>
        <br/>
        <p class="text-justify">
          Byłem odpowiedzialny za pisanie kodu źródłowego do systemów z rodziny CRM w różnych technologiach, uczestniczyłem
          także w pracach rozwojowych R&D. Poza tworzeniem kodu byłem także odpowiedzialny za operacje na bazach danych
          czy analizę części systemu.
        </p>
      </div>

      <div class="col-sm-6 text-center">
        <h2>
          <span class="material-icons">favorite</span>
        </h2>
        <h4>11/2020 - obecnie</h4>
        <h5>Młodszy programista w Execon</h5>
        <br/>
        <p class="text-justify">
          Moje aktualne miejsce pracy. Jestem odpowiedzialny głównie za prace rozwojowe i utrzymaniowe w projektach
          opartych o różne technologie.
        </p>
      </div>
    </div>

  </div>
</template>

<script>
export default {
name: "Home"
}
</script>

<style scoped>
.orange-text {
  color: #ff9800;
}

.btn-orange {
  background-color: #ff9800;
  color: white;
  border-radius: 0 !important;
}

.img-thumbnail {
  border: 0 !important;
}

.material-icons {
  font-size: 48pt;
  color: #ff9800;
}

p {
  font-size: 1.15rem;
}

.bg-first {
  background-color: #29b6f6;
  color: white;
}
</style>
