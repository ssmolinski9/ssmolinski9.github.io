<template>
  <div class="container mb-5">
    <div class="card text-white bg-warning mb-3">
      <div class="card-header">Python / Rozwiązania biometryczne</div>
      <div class="card-body">
        <h5 class="card-title text-center">Misern Voice</h5>

        <div class="col-sm-12 text-center">
          <img src="@/assets/projects/misern-voice-2.png" class="img-fluid mr-3 mb-3"
               alt="Podgląd konsoli misern-voice">
        </div>

        <p class="card-text text-justify">
          Aplikacja konsolowa wykorzystująca biblioteki rozpoznawania mowy. Dzięki niej można rozpoznać nagrać
          krótką próbkę głosu, a program rozpozna język (spośród angielskiego, niemieckiego i hiszpańskiego)
          oraz treść wypowiedzianego tekstu. Istnieje możliwość rozszerzenia aplikacji o następne języki.
          Dodatkowo wygenerowana zostanie transformata Fouriera dla nagranej próbki.
          Program zrealizowany w grupie razem z <a href="https://github.com/Filonczuk" class="text-white">Michałem Fiłończukiem</a>
          oraz <a href="https://github.com/ernestst" class="text-white">Ernestem Stachelskim</a> w ramach zajęć biometrii.
        </p>

        <p class="card-text text-justify">
          Program działa w konsoli, jako parametr uruchomieniowy może przyjąć "-h" aby wyświetlić pomoc, parametr
          "-s" żeby określić czas nagrywania lub "-f" aby wygenerować transformatę z już istniejącego pliku.
          W momencie ujrzenia napisu "Recording..." można rozpocząć wypowiadanie tekstu do mikrofonu, który w systemie
          ustawiony jest jako źródło wejściowe (program nie umożliwia wyboru konkretnego mikrofonu, zawsze używa głównego).
        </p>

        <p class="card-text text-justify font-weight-bold">
          Źródło: <a href="https://github.com/ssmolinski9/misern-voice" class="text-white">GitHub</a>.
        </p>
      </div>
    </div>

    <div class="card text-white bg-warning mb-3">
      <div class="card-header">Java / Analiza grafiki</div>
      <div class="card-body">
        <h5 class="card-title text-center">JS Paint</h5>

        <div class="col-sm-12 text-center">
          <img src="@/assets/projects/js-paint.png" class="img-fluid mr-3 mb-3"
               alt="Podgląd programu graficznego" style="width: 50%">
        </div>

        <p class="card-text text-justify">
          Aplikacja pozwalająca na manipulowanie zdjęciami. Pozwala na dodawanie i manipulację prostymi kształtami,
          stosowanie filtrów zmiany jasności, wyrównania, rozmycia, operacje na histogramie, możliwość binaryzacji,
          możliwość stosowania operacji morfilogicznych. Dodatkowo posiada moduł analizy koloru na wybranym obrazie
          (wskazuje ilość zaznaczonego koloru w zależności od podanej tolerancji).
        </p>

        <p class="card-text text-justify">
          Program zrealizowany w ramach zajęć grafiki komputerowej na studiach inżynierskich.
        </p>

        <p class="card-text text-justify font-weight-bold">
          Źródło: <a href="https://github.com/ssmolinski9/js-paint" class="text-white">GitHub</a>.
        </p>
      </div>
    </div>

    <div class="card text-white bg-warning mb-3 mt-5">
      <div class="card-header">Java / Rozwiązania biometryczne</div>
      <div class="card-body">
        <h5 class="card-title text-center">Misern Fingerprints</h5>

        <div class="col-sm-12 text-center">
          <img src="@/assets/projects/misern-fingerprint.png" class="img-fluid mr-3 mb-3"
               alt="Aplikacja przygotowująca odcisk palca" style="width: 60%">
        </div>

        <p class="card-text text-justify">
          Aplikacja pozwala na operacje na wycztanym obrazie przedstawiającym odcisk palca. Program pozwala na przeprowadzenie
          automatycznego procesu lub przeprowadzenie go krok po kroku. Wczytany obraz należy poddać binaryzacji (algorytm Otsu),
          następnie przefiltrować go w celu pozbycia się zakłóceń (filtr medianowy). W kolejnym kroku przeprowadzana zostaje
          szkieletyzacja obrazu za pomocą algorytmu KMM. Ostatnim krokiem jest usunięcie fałszywych minuncji.
          Program zrealizowany w grupie razem z <a href="https://github.com/Filonczuk" class="text-white">Michałem Fiłończukiem</a>
          oraz <a href="https://github.com/ernestst" class="text-white">Ernestem Stachelskim</a> w ramach zajęć biometrii.
        </p>

        <p class="card-text text-justify font-weight-bold">
          Źródło: <a href="https://github.com/ssmolinski9/misern-fingerprint" class="text-white">GitHub</a>.
        </p>
      </div>
    </div>

    <div class="card text-white bg-warning mb-3 mt-5">
      <div class="card-header">Django / Aplikacja internetowa</div>
      <div class="card-body">
        <h5 class="card-title text-center">Misern Budget</h5>

        <div class="col-sm-12 text-center">
          <img src="@/assets/projects/misern-budget.png" class="img-fluid mr-3 mb-3"
               alt="Podgląd budżetu">
        </div>

        <p class="card-text text-justify">
          Aplikacja internetowa dostarczająca narzędzia do zarządzania budżetem domowym, stworzona w ramach projektu na
          studiach razem z <a href="https://github.com/Filonczuk" class="text-white">Michałem Fiłończukiem</a>
          oraz <a href="https://github.com/ernestst" class="text-white">Ernestem Stachelskim</a>. Aplikacja służy do
          monitorowania przychodów oraz wydatków w ramach budżetu domowego — użytkownik może dodawać wpisy z konkretnych
          dni w zdefiniowanych przez siebie kategoriach oraz przypisywać wydatki do źródeł pieniędzy
          (karty kredytowe, gotówka itd.). Istnieją wbudowane filtry, generowanie raportów PDF, wyświetlanie wykresów.
        </p>

        <p class="card-text text-justify font-weight-bold">
          Źródło: <a href="https://gitlab.com/ssmolinski6/misern-budget" class="text-white">GitLab</a>.
        </p>
      </div>
    </div>

    <div class="card text-white bg-warning mb-3 mt-5">
      <div class="card-header">Java / Aplikacja desktopowa</div>
      <div class="card-body">
        <h5 class="card-title text-center">Text Editor</h5>

        <div class="col-sm-12 text-center">
          <img src="@/assets/projects/texteditor.png" class="img-fluid mr-3 mb-3"
               alt="Edytor tekstu">
        </div>

        <p class="card-text text-justify">
          Prosty edytor tekstu, który umożliwia sporządzanie notatek w formacie .txt. Program umożliwia zmianę fontu
          tekstu, zapisywanie, odczytywanie plików. Istnieje możliwość ustawienia programu jako program domyślny dla
          plików z odpowiednim rozszerzeniem. Program dostępny na licencji GNU LGPL. W programie używana jest otwarto
          źródłowa klasa <a href="https://github.com/NigoroJr/typebest/blob/master/src/say/swing/JFontChooser.java"
          class="text-white">JFontChooser</a>.
        </p>

        <p class="card-text text-justify font-weight-bold">
          Źródło: <a href="https://github.com/ssmolinski9/text-editor" class="text-white">GitHub</a>.
        </p>
      </div>
    </div>

    <div class="card text-white bg-warning mb-3 mt-5">
      <div class="card-header">C / POSIX</div>
      <div class="card-body">
        <h5 class="card-title text-center">Problem czytelników i pisarzy</h5>

        <div class="col-sm-12 text-center">
          <img src="@/assets/projects/no-preview.png" class="img-fluid mr-3 mb-3"
               alt="Brak podglądu" style="width: 50%">
        </div>

        <p class="card-text text-justify">
          Zbiór rozwiązań popularnego problemu czytelników i pisarzy. Problem polega na sposobie synchronizacji dostępu
          do danych, które niektóre procesy mogą edytować, a niektóre odczytywać. W zbiorze istnieje rozwiązanie
          optymalne, rozwiązanie preferujące czytelników oraz takie preferujące pisarzy. Program zrealizowany
          razem z <a href="https://github.com/Filonczuk" class="text-white">Michałem Fiłończukiem</a>
          oraz <a href="https://github.com/ernestst" class="text-white">Ernestem Stachelskim</a>.
        </p>

        <p class="card-text text-justify font-weight-bold">
          Źródło: <a href="https://github.com/ssmolinski9/readers-writers" class="text-white">GitHub</a>.
        </p>
      </div>
    </div>

    <div class="card text-white bg-warning mb-3 mt-5">
      <div class="card-header">C / Demon unixowy</div>
      <div class="card-body">
        <h5 class="card-title text-center">MisernD</h5>

        <div class="col-sm-12 text-center">
          <img src="@/assets/projects/no-preview.png" class="img-fluid mr-3 mb-3"
               alt="Brak podglądu" style="width: 50%">
        </div>

        <p class="card-text text-justify">
          Usługa napisana pod systemy unixowe w ramach zajęć z systemów operacyjnych. Demon pozwala na synchronizację
          dostarczonych katalogów (z wyróżnieniem źródłowego oraz docelowego). Dodatkowe opcje pozwalają na synchronizację
          podkatalogów w ramach katalogu, ustawianie niestandardowego czasu częstotliwości budzenia się usługi itd.
          Program napisany w grupie trzyosobowej razem z <a href="https://github.com/Filonczuk" class="text-white">
          Michałem Fiłończukiem</a> oraz <a href="https://github.com/ernestst" class="text-white">Ernestem Stachelskim</a>.
        </p>

        <p class="card-text text-justify font-weight-bold">
          Źródło: <a href="https://github.com/ssmolinski9/misernd" class="text-white">GitHub</a>.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "ProjectsList"
}
</script>

<style scoped>
p {
  font-size: 1.15rem;
}
</style>
